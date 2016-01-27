#### Test 568182540458528_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,--------- beginning of main
D/AndroidRuntime(10597): 
D/AndroidRuntime(10597): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10597): CheckJNI is OFF
D/AndroidRuntime(10597): readGMSProperty: start
D/AndroidRuntime(10597): readGMSProperty: already setted!!
D/AndroidRuntime(10597): readGMSProperty: end
D/AndroidRuntime(10597): addProductProperty: start
E/AffinityControl(10597): AffinityControl: registerfunction enter
D/AndroidRuntime(10597): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3522): inState():  stateMachine is null !!
I/PersonaManagerService( 3522): PersonaId don't exist
I/ActivityManager( 3522): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3522): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3522): mDVFSHelper.acquire()
D/FocusedStackFrame( 3522): Set to : 0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/Zygote  (10615): MountEmulatedStorage()
I/libpersona(10615): KNOX_SDCARD checking this for 10601
E/Zygote  (10615): v2
I/libpersona(10615): KNOX_SDCARD not a persona
I/SELinux (10615): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=10615 uid=10601 gids={50601, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (10615): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10615): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(10597): Shutting down VM
D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(10615): TimaSignature is unavailable
D/ActivityThread(10615): Added TimaKeyStore provider
V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3522): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/ResourcesManager(10615): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger( 2850): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger( 2850): id=8 Removed Mauncher (-2/8)
V/ActivityThread( 4001): updateVisibility : ActivityRecord{1571b09b token=android.os.BinderProxy@3b9f1d0a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 4001): onTrimMemory. Level: 20
I/WebViewFactory(10615): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(10615): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(10615): Loading: webviewchromium
I/LibraryLoader(10615): Time to load native libraries: 3 ms (timestamps 7842-7845)
I/LibraryLoader(10615): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(10615): Binding Chromium to main looper Looper (main, tid 1) {f5b8993}
I/LibraryLoader(10615): Expected native library version number "",actual native library version number ""
I/chromium(10615): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(10615): Initializing chromium process, renderers=0
,W/art     (10615): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(10615): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium(10615): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(10615): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(10615): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/BluetoothAdapter(10615): 680955344: getState() :  mService = null. Returning STATE_OFF
,W/chromium(10615): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(10615): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     (10615): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents(10615): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine(10615): CordovaWebView is running on device made by: samsung
W/art     (10615): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (10615): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity(10615): performCreate Call secproduct feature valuefalse
D/Activity(10615): performCreate Call debug elastic valuetrue
D/OpenGLRenderer(10615): Render dirty regions requested: true
D/ActivityManager( 3522): post active user change for 0
D/KnoxTimeoutHandler( 3522): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3522): handleActiveUserChange for user 0
I/SurfaceFlinger( 2850): id=12 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(10615): Initialized EGL, version 1.4
I/OpenGLRenderer(10615): HWUI protection enabled for context ,  &this =0xaf5541a0 ,&mEglDisplay = 1 , &mEglConfig = -1279688432 
D/OpenGLRenderer(10615): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(10615): Enabling debug mode 0
D/mali_winsys(10615): new_window_surface returns 0x3000,  [1440x2560]-format:1
V/ActivityThread(10615): updateVisibility : ActivityRecord{19910b00 token=android.os.BinderProxy@11dc28f6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/InputMethodManagerService( 3522): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 3522): mDVFSHelper.release()
I/Timeline( 3522): Timeline: Activity_windows_visible id: ActivityRecord{a3e62be u0 com.test.thalitest/.MainActivity t25} time:128259
W/IInputConnectionWrapper(10615): showStatusIcon on inactive InputConnection
I/Timeline(10615): Timeline: Activity_idle id: android.os.BinderProxy@11dc28f6 time:128265
D/JsMessageQueue(10615): Set native->JS mode to OnlineEventsBridgeMode
I/chromium(10615): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(10615): 
D/jxcore_app_log(10615): JniHelper::setJavaVM(0xb4d5c280), pthread_self() = -1358473472
I/chromium(10615): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(10615): Initializing JXcore engine
W/jxcore-log(10615): JXcore engine is ready
,E/auditd  ( 4542): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3522): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3522): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(10615): Starting JXcore engine
,W/jxcore-log(10615): Platform android
W/jxcore-log(10615): 
W/jxcore-log(10615): Process ARCH arm
W/jxcore-log(10615): 
,I/jxcore-log(10615): JXcore Cordova bridge is ready!
I/jxcore-log(10615): 
W/jxcore-log(10615): JXcore engine is started
,I/jxcore-log(10615): Toggling radios to true
I/jxcore-log(10615): 
,D/BluetoothAdapter(10615): enable()
,W/ActivityManager( 3522): Permission Denial: getCurrentUser() from pid=10615, uid=10601 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 3522): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 3522): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10615, uid=10601 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 3522): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/BluetoothManagerService( 3522): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2160)
W/BluetoothManagerService( 3522): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:671)
W/BluetoothManagerService( 3522): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService( 3522): 	at android.os.Binder.execTransact(Binder.java:446)
E/DevicePolicyManagerService( 3522): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3522): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider( 3522): name = bluetooth_on
,E/DevicePolicyManagerService( 3522): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3522): getAllowBluetoothMode - value retunrs : 2
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
I/WifiManager(10615): packageName : com.test.thalitest
D/WifiService( 3522): New client listening to asynchronous messages
D/SecContentProvider( 3522): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3522): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3522): mCursor = null
D/WifiService( 3522): setWifiEnabled: true pid=10615, uid=10601
E/WifiService( 3522): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3522): Permission Denial: getCurrentUser() from pid=10615, uid=10601 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3522): Failed getting userId using ActivityManagerNative
W/WifiService( 3522): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10615, uid=10601 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3522): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3522): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3522): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3522): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3522): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3522): name = wifi_on
,E/WifiStateMachine( 3522): setting operational mode to 1
,I/WifiService( 3522): disconnect: pid=10615, uid=10601
,E/WifiHW  ( 3522): ##################### set firmware type 0 #####################
,E/Zygote  (10686): MountEmulatedStorage()
I/libpersona(10686): KNOX_SDCARD checking this for 1002
E/Zygote  (10686): v2
I/libpersona(10686): KNOX_SDCARD not a persona
I/jxcore-log(10615): Radios toggled
I/jxcore-log(10615): 
,I/SELinux (10686): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/jxcore-log(10615): My device name is: samsung-SM-N910C
I/jxcore-log(10615): 
I/WifiHW  ( 2845): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
I/SELinux (10686): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=10686 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
E/SELinux (10686): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/WifiHW  ( 2845): module is murata
E/WifiHW  ( 2845): ==========[WIFI] MURATA MODULE ===========
I/WifiHW  ( 2845): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt_murata
E/WifiHW  ( 2845): TEMP_FAILURE_RETRY complete
D/SoftapController( 2845): Softap fwReload - Ok
,D/CommandListener( 2845): Setting iface cfg
D/CommandListener( 2845): Trying to bring down wlan0
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/TimaKeyStoreProvider(10686): TimaSignature is unavailable
,D/ActivityThread(10686): Added TimaKeyStore provider
,D/ResourcesManager(10686): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,W/ResourcesManager(10686): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager(10686): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/BluetoothA2dpSinkServiceJni(10686): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig(10686): Adding GattService
,D/BtSettings.ProfileConfig(10686): Adding HeadsetService
D/BtSettings.ProfileConfig(10686): Adding A2dpService
D/BtSettings.ProfileConfig(10686): Adding HidService
D/BtSettings.ProfileConfig(10686): Adding HealthService
,D/BtSettings.ProfileConfig(10686): Adding PanService
D/BtSettings.ProfileConfig(10686): Adding BluetoothMapService
D/BtSettings.ProfileConfig(10686): Adding SapService
D/BtSettings.ProfileConfig(10686): Adding HeadsetClientService
D/BtSettings.ProfileConfig(10686): Adding A2dpSinkService
D/BtSettings.ProfileConfig(10686): Adding SapClientService
D/BtSettings.ProfileConfig(10686): Adding HidDevService
I/BtSettings.ProfileConfig(10686): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 3522): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
,W/BackupManagerService( 3522): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3522): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
,W/BackupManagerService( 3522): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3522): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
,D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
,W/BackupManagerService( 3522): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3522): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
,W/BackupManagerService( 3522): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3522): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
,W/BackupManagerService( 3522): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3522): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
W/BackupManagerService( 3522): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/SettingsProvider( 3522): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
E/WifiHW  ( 3522): supplicant_name : p2p_supplicant
E/WifiStateMachine( 3522): setWifiState: enabling
E/WifiStateMachine( 3522): Supplicant start successful
D/WifiMonitor( 3522): startMonitoring(wlan0) with mConnected = false
,D/SmartBondingService( 3522): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SLocation( 3522): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=false enabledDesc:null
D/STATUSBAR-WifiQuickSettingButton( 3693): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3693): Wifi onReceive(2)
,D/STATUSBAR-QSTileView( 3693): onStateChanged: Wi-Fi
D/HotspotTile( 3693): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 3693): onReceive : 2, 0
D/SmartBondingService( 3522): getNetworkEnabled : wifi : false mobile : false
,I/Hs20UtilService( 6348): Starting #2
,I/Hs20UtilService( 6348): Message received 5011
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,W/BackupManagerService( 3522): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3522): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
,W/BackupManagerService( 3522): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,E/Zygote  (10702): MountEmulatedStorage()
E/Zygote  (10702): v2
I/libpersona(10702): KNOX_SDCARD checking this for 10127
I/libpersona(10702): KNOX_SDCARD not a persona
,D/SettingsProvider( 3522): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
I/ActivityManager( 3522): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=10702 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
,I/SELinux (10702): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10702): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10702): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/BackupManagerService( 3522): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3522): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
,W/BackupManagerService( 3522): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3522): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
,D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
,D/TimaKeyStoreProvider(10702): TimaSignature is unavailable
,I/wpa_supplicant(10701): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant(10701): Successfully initialized wpa_supplicant
D/ActivityThread(10702): Added TimaKeyStore provider
I/SecureStorage(10701): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,W/BackupManagerService( 3522): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 3522): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
,D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
,W/BackupManagerService( 3522): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecureStorage(10701): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage( 2902): [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10701
I/SecureStorage( 2902): [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
I/SecureStorage(10701): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant(10701): ssSupport state is = 1
,I/wpa_supplicant(10701): >>>>> GET KEY, IV <<<<<
,I/SecureStorage(10701): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage( 2902): [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10701
I/SecureStorage( 2902): [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,D/ResourcesManager(10702): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/BluetoothAdapterState(10686): make
,I/bluedroid(10686): init
I/BluetoothAdapterState(10686): Entering OffState
,I/bte_conf(10686): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf(10686): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config(10686): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf(10686): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif (10686): btif_fetch_local_ble_random_bdaddr
I/bluedroid(10686): get_profile_interface socket
I/bluedroid(10686): get_profile_interface map_client
,D/BluetoothAdapterService(10686): checkAddrForIOP: Loading from conf
,D/KeyguardWallpaperUpdator(10702): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(10702): cancelUpdateCategory
D/KeyguardWallpaperUpdator(10702): stopCheckCategoryVersion
,I/GKI_LINUX(10686): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties(10686): Address is:E0:DB:10:14:E2:C0
E/BluetoothServiceJni(10686): populateRssiValuesNative
I/bluedroid(10686): getModelRssiValues
E/BluetoothServiceJni(10686): model_rssi_values_callback: low = -75, mid = -65, high = 127
D/BluetoothAdapterProperties(10686): modelRssiValuesCallback, low, mid, high = -75,-65,127
,D/BluetoothAdapterProperties(10686): Name is: Note4-1
,D/SettingsProvider( 3522): name = bluetooth_name
,I/SignOutReceiver( 8274): WIFI_STATE_CHANGED_ACTION
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10723): MountEmulatedStorage()
I/libpersona(10723): KNOX_SDCARD checking this for 1000
E/Zygote  (10723): v2
I/libpersona(10723): KNOX_SDCARD not a persona
,I/SELinux (10723): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10723): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10723): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=10723 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/BluetoothAdapterService(10686): Inband Ring is supported
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8749(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 365us total 10.950ms
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 245us total 7.758ms
,I/bluedroid(10686): config_hci_snoop_log
,D/BluetoothManagerService( 3522): Broadcasting onBluetoothServiceUp() to 11 receivers.
D/TimaKeyStoreProvider(10723): TimaSignature is unavailable
,D/ActivityThread(10723): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 246us total 7.863ms
,E/DevicePolicyManagerService( 3522): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 3522): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider( 3522): uri = 3 selection = isBluetoothEnabled
,D/BluetoothAdapterState(10686): CURRENT_STATE=OFF, MSG = USER_TURN_ON
D/BluetoothAdapterProperties(10686): Setting state to 11
I/BluetoothAdapterState(10686): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService(10686): Bluetooth PBAP supproted is true
D/BluetoothAdapterService(10686): updateAdapterState state is 11
,D/BluetoothAdapterService(10686): Autoconnection is available 
D/BluetoothAdapterService(10686): updateAdapterState prevState = 10newState = 11
D/ResourcesManager(10723): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BluetoothSecureManager(10686): getInstant: null
D/BluetoothSecureManager(10686): calling getMethod for getService
D/BluetoothSecureManager(10686): calling getService
,D/BluetoothSecureManager(10686): getService return binder: android.os.BinderProxy@25a8980b
,W/InputMethodManagerService( 3522): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3522): [BT Setting State] State =11
,D/BluetoothSecureManagerService( 3522): isSecureModeEnabled
,D/BluetoothSecureManagerService( 3522): getSecureModeSetting, name: secure_mode_enable
D/BluetoothTile( 3693):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 3693): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BtConfig.SecureMode(10686): isSecureModeOn:false
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,I/SamsungIME( 4427): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
D/StatusBarManagerService( 3522): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
D/STATUSBAR-QSTileView( 3693): onStateChanged: Bluetooth
D/StatusBarManagerService( 3522): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 3693): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
,W/BluetoothAdapterService(10686): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService(10686): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService(10686): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService(10686): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService(10686): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService(10686): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService(10686): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService(10686): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(10686): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService(10686): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10686): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,V/[CarModeFW](10046): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
,W/BluetoothAdapterService(10686): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,D/BluetoothBondStateMachine(10686): make
,W/BluetoothAdapterService(10686): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
I/BluetoothBondStateMachine(10686): StableState(): Entering Off State
W/BluetoothAdapterService(10686): Not skipping com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService(10686): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService(10686): Not skipping com.android.bluetooth.hfp.HeadsetService
,I/BtGatt.JNI(10686): classInitNative(L900): classInitNative: Success!
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/BtGatt.DebugUtils(10686): handleDebugAction() action=null
D/BtGatt.GattService(10686): Received start request. Starting profile...
D/BtGatt.GattService(10686): start()
I/bluedroid(10686): get_profile_interface gatt
D/BluetoothAdapterService(10686): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5b8993
D/BtGatt.AdvertiseManager(10686): advertise manager created
,E/Zygote  (10742): MountEmulatedStorage()
E/Zygote  (10742): v2
I/libpersona(10742): KNOX_SDCARD checking this for 10186
I/libpersona(10742): KNOX_SDCARD not a persona
,I/SELinux (10742): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10742): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc tv.peel.smartremote for broadcast tv.peel.smartremote/com.peel.receiver.ConnectivityActionReceiver: pid=10742 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
E/SELinux (10742): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Killing 9896:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,W/BluetoothAdapterService(10686): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService(10686): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/BluetoothAdapterService(10686): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5b8993
W/BluetoothAdapterService(10686): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService(10686): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService(10686): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService(10686): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService(10686): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService(10686): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService(10686): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService(10686): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/TimaKeyStoreProvider(10742): TimaSignature is unavailable
D/ActivityThread(10742): Added TimaKeyStore provider
D/HeadsetService(10686): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni(10686): classInitNative: succeeds
,D/HeadsetStateMachine(10686): make
,E/HeadsetStateMachine(10686): # of Max HF connection is 2
,W/BluetoothAdapterService(10686): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,I/bluedroid(10686): get_profile_interface handsfree
,W/BluetoothAdapterService(10686): Not skipping com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService(10686): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(10686): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService(10686): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(10686): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService(10686): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService(10686): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService(10686): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig(10686): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService(10686): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState(10686): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/DualScoManager(10686): Instantiating Dual Sco Manager
I/DualScoManager(10686): Set HeadsetServiceHelper
D/BluetoothAtMessage(10686): createCMTIContentObservers
,D/SettingsProvider( 3522): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
D/ResourcesManager(10742): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,W/BackupManagerService( 3522): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,W/ResourcesManager(10742): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/HeadsetStateMachine(10686): Enter Disconnected: -2
E/HeadsetStateMachine(10686): set to mRemoteBrsf = 0
,D/BluetoothAdapterService(10686): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5b8993
,E/BluetoothAdapterService(257657235)(10686): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,D/HeadsetStateMachine(10686): map size, before remove : 0
D/HeadsetStateMachine(10686): map size, after remove: 0
D/BluetoothA2dp( 4806): Proxy object connected
,D/BluetoothA2dp( 3522): Proxy object connected
D/A2dpService(10686): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni(10686): classInitNative: succeeds
V/Avrcp   (10686): make
V/Avrcp   (10686): Avrcp
I/bluedroid(10686): get_profile_interface avrcp
,V/Avrcp   (10686): start
,E/RemoteController(10686): Cannot set synchronization mode on an unregistered RemoteController
,V/Avrcp   (10686): ++registerMediaPlayers++
,I/Avrcp   (10686): No of Audio players :: 2
I/Avrcp   (10686): App Package name is com.google.android.music
,D/ResourcesManager(10686): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/Avrcp   (10686): App pkg name is Google Play Music
,I/Avrcp   (10686): Name::Google Play Music
V/Avrcp   (10686): MediaPlayerInfo: mPlayerId=1
I/Avrcp   (10686): App Package name is com.sec.android.app.music
,D/ResourcesManager(10686): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/Avrcp   (10686): App pkg name is Music
,I/Avrcp   (10686): Name::Music
V/Avrcp   (10686): MediaPlayerInfo: mPlayerId=2
,I/Avrcp   (10686): No of Video players :: 1
I/Avrcp   (10686): Video App Package name is com.sec.android.app.videoplayer
,D/ResourcesManager(10686): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/Avrcp   (10686): Video App pkg name is Video Player
,I/Avrcp   (10686): Name::Video Player
V/Avrcp   (10686): MediaPlayerInfo: mPlayerId=3
I/Avrcp   (10686): Add tempPlayer
V/Avrcp   (10686): MediaPlayerInfo: mPlayerId=4
I/Avrcp   (10686): Total no of players: 4
V/Avrcp   (10686): swapping the samsung player with 1st player
I/Avrcp   (10686):  Updating now playing list upon AVRCP Start
V/Avrcp   (10686): handleMessage, msg=207
,D/BluetoothMediaBrowser(10686):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,V/Avrcp   (10686): CurrentAudioFocusPackageName is null
I/Avrcp   (10686): There is no currently selected player ,setting Samsung Music Player ID
I/Avrcp   (10686):  set player publishabilty with player id::1 toBePublished ::true
I/BluetoothA2dpServiceJni(10686): classInitNative: succeeds
D/A2dpStateMachine(10686): make
,I/bluedroid(10686): get_profile_interface a2dp
I/GKI_LINUX(10686): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif (10686): warning : media task started media_task_refcnt 1 
,D/BluetoothAdapterService(10686): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5b8993
D/A2dpStateMachine(10686): Enter Disconnected: -2
,I/BluetoothHidServiceJni(10686): classInitNative: succeeds
,D/HidService(10686): Received start request. Starting profile...
I/bluedroid(10686): get_profile_interface hidhost
D/HidService(10686): setHidService(): set to: null
D/BluetoothAdapterService(10686): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5b8993
I/BluetoothHealthServiceJni(10686): classInitNative: succeeds
D/HealthService(10686): Received start request. Starting profile...
,I/bluedroid(10686): get_profile_interface health
D/BluetoothAdapterService(10686): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5b8993
,I/BluetoothPanServiceJni(10686): classInitNative(L105): succeeds
,D/BluetoothMediaBrowser(10686): no now playing list
D/BluetoothMediaBrowser(10686):  getNowPlayingId now playing id : -1
D/Avrcp   (10686):  checkNowPlayingList start
,D/BluetoothPan( 3522): BluetoothPAN Proxy object connected
,D/PanService(10686): Received start request. Starting profile...
D/BluetoothPanServiceJni(10686): initializeNative(L110): pan
I/bluedroid(10686): get_profile_interface pan
D/BluetoothAdapterService(10686): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5b8993
,D/BluetoothMapService(10686): Received start request. Starting profile...
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10768): MountEmulatedStorage()
E/Zygote  (10768): v2
I/libpersona(10768): KNOX_SDCARD checking this for 10178
I/libpersona(10768): KNOX_SDCARD not a persona
,I/SELinux (10768): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10768): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10768): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=10768 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(10768): TimaSignature is unavailable
,D/ActivityThread(10768): Added TimaKeyStore provider
,I/WebViewFactory(10742): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(10742): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/SecureStorage( 2902): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,D/ResourcesManager(10768): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/LibraryLoader(10742): Loading: webviewchromium
,W/ResourcesManager(10768): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(10768): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10768): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10768): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10768): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(10768): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/LibraryLoader(10742): Time to load native libraries: 6 ms (timestamps 79-85)
I/LibraryLoader(10742): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(10742): Binding Chromium to main looper Looper (main, tid 1) {35dfc5cd}
,I/LibraryLoader(10742): Expected native library version number "",actual native library version number ""
I/chromium(10742): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(10742): Initializing chromium process, renderers=0
,W/art     (10742): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(10742): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium(10742): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(10742): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46768 len=2953
I/chromium(10742): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:37 off:229524 len:643667
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
D/RCPManagerService( 3522): exchangeData() failure , invalid userId
D/RCPManagerService( 3522): exchangeData() failure , invalid userId
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/BluetoothAdapterService(10686): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5b8993
D/HeadsetStateMachine(10686): Try to query the phonestate on bind
,I/Telecom ( 3953): BluetoothPhoneService: queryPhoneState
,E/Zygote  (10819): MountEmulatedStorage()
E/Zygote  (10819): v2
I/libpersona(10819): KNOX_SDCARD checking this for 10082
I/libpersona(10819): KNOX_SDCARD not a persona
I/SELinux (10819): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=10819 uid=10082 gids={50082, 9997} abi=armeabi-v7a
I/Telecom ( 3953): BluetoothPhoneService: updateHeadsetWithCallState
,I/SELinux (10819): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10819): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/Telecom ( 3953): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 3953): Proxy not attached to service
,D/HeadsetStateMachine(10686): Proxy object connected
,I/BluetoothSAPServiceJni(10686): classInitNative(L204): succeeds
,D/SapService(10686): Received start request. Starting profile...
D/BluetoothSAPServiceJni(10686): initializeNative(L209): sap
I/bluedroid(10686): get_profile_interface sap
D/BluetoothAdapterService(10686): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5b8993
D/HeadsetPhoneState(10686): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState(10686): sendDeviceDataStateChanged
D/HeadsetStateMachine(10686): Disconnected process message: 11
D/HeadsetStateMachine(10686): Disconnected process message: 18
D/HeadsetPhoneState(10686): Signal level : previous=0 curr=0
E/BluetoothAdapterService(257657235)(10686): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
V/HeadsetService(10686): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10686): Disconnected process message: 10
D/BluetoothA2dp(10686): Proxy object connected
D/BluetoothAdapterService(10686): Bluetooth A2dp source service connected
D/HeadsetPhoneState(10686): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine(10686): Disconnected process message: 11
E/BluetoothAdapterService(257657235)(10686): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
E/BluetoothAdapterService(257657235)(10686): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/BluetoothAdapterService(257657235)(10686): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,E/BluetoothAdapterService(257657235)(10686): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,W/chromium(10742): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,D/TimaKeyStoreProvider(10819): TimaSignature is unavailable
I/ActivityManager( 3522): Killing 9921:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
D/ActivityThread(10819): Added TimaKeyStore provider
W/chromium(10742): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,E/BluetoothAdapterService(257657235)(10686): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(257657235)(10686): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState(10686): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid(10686): enable
,I/GKI_LINUX(10686): gki_task_entry task_id=0 [BTU] starting
,I/bt_hci_bdroid(10686): init
,I/bt_vendor(10686): init
I/bt_vnd_conf(10686): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf(10686): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial(10686): userial_init
,I/ActivityManager( 3522): Killing 9188:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,D/ResourcesManager(10819): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,W/art     (10742): Attempt to remove local handle scope entry from IRT, ignoring
,D/BadgeProvider(10819): onCreate
D/BadgeProvider(10819): DatabaseHelper
,W/AwContents(10742): onDetachedFromWindow called when already detached. Ignoring
,D/BadgeProvider(10819): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/ActivityManager( 3522): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/BadgeProvider(10819): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider(10819): sendNotify, [notify] : null
D/BadgeProvider(10819): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(10819): update, [BadgeCount] : badgecount=0
D/BadgeProvider(10819): update, [UpdateCount] : 1
D/Launcher.Model( 4001): reloadBadges entered.
,I/bt_userial_vendor(10686): userial vendor open: opening /dev/ttySAC3
,I/bt_userial_vendor(10686): userial_vendor_open():UART is setup
I/bt_userial_vendor(10686): device fd = 65 open
E/bt_hwcfg(10686): Start CFG HW, HCI reset
D/bt_userial(10686): Entering userial_read_thread()
,I/ActivityManager( 3522): Killing 8377:com.android.mms/u0a52 (adj 13): bgCount ##31
,I/SecureStorage(10701): [INFO]: SPID(0x00000005)Processing data has been completed
,E/bt_hwcfg(10686): Read Local Name after HCI reset
,D/BluetoothNotiBroadcastReceiver( 7824): onReceive
,I/SecureStorage(10701): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,D/AuthorizationBluetoothService( 4245): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/bt_hwcfg(10686): Chipset BCM43569A1
D/bt_hwcfg(10686): Target name = [BCM4358A1]
,I/bt_hwcfg(10686): module_type[murata].
I/bt_hwcfg(10686): module_type[murata] is invalid.
E/bt_hwcfg(10686): patchram path ORG . BCM4358A1
E/bt_hwcfg(10686): patchram path ORG .. BCM4358A1
E/bt_hwcfg(10686): patchram path ORG bcm4358A0_V0033.0000.hcd BCM4358A1
E/bt_hwcfg(10686): patchram path ORG bcm4358A1_V0044.0078.hcd BCM4358A1
I/bt_hwcfg(10686): patch(org) : bcm4358A1_V0044.0078.hcd
I/bt_hwcfg(10686): Found patchfile: /vendor/firmware/bcm4358A1_V0044.0078.hcd
E/bt_hwcfg(10686): ORG patchram base 0044
E/bt_hwcfg(10686): ORG patchram minor 0078
E/bt_hwcfg(10686): fw ver (org)44.78
E/bt_hwcfg(10686): Final Patchram is /vendor/firmware/bcm4358A1_V0044.0078.hcd
,I/SecureStorage(10701): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2902): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10701
I/SecureStorage( 2902): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10701): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10701): ssSupport state is = 1
,I/wpa_supplicant(10701): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant(10701): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10701): SIM READ ERROR
I/wpa_supplicant(10701): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10701): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10701): SIM READ ERROR
I/wpa_supplicant(10701): Blacklist: Clear (all) 
I/wpa_supplicant(10701): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10701): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant(10701): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10701): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,I/wpa_supplicant(10701): rfkill: Cannot open RFKILL control device
,I/bt_hwcfg(10686): Axi patch failure or not include AXI patching
,I/bt_hwcfg(10686): bt vendor lib: set UART baud 3000000
,D/CountryDetector( 3522): No listener is left
,I/bt_hwcfg(10686): bt vendor lib: set UART baud 115200
I/bt_hwcfg(10686): FW Download delta = 481825
D/bt_hwcfg(10686): Settlement delay -- 100 ms
I/bt_hwcfg(10686): Setting fw settlement delay to 100 
,I/bt_hwcfg(10686): bt vendor lib: set UART baud 3000000
,I/bt_hwcfg(10686): vendor lib fwcfg completed
,I/        (10686): BTE_InitTraceLevels -- TRC_HCI
I/        (10686): BTE_InitTraceLevels -- TRC_L2CAP
I/        (10686): BTE_InitTraceLevels -- TRC_RFCOMM
I/        (10686): BTE_InitTraceLevels -- TRC_AVDT
I/        (10686): BTE_InitTraceLevels -- TRC_AVRC
I/        (10686): BTE_InitTraceLevels -- TRC_A2D
I/        (10686): BTE_InitTraceLevels -- TRC_BNEP
I/        (10686): BTE_InitTraceLevels -- TRC_BTM
I/        (10686): BTE_InitTraceLevels -- TRC_GAP
I/        (10686): BTE_InitTraceLevels -- TRC_PAN
I/        (10686): BTE_InitTraceLevels -- TRC_SAP
I/        (10686): BTE_InitTraceLevels -- TRC_SDP
I/        (10686): BTE_InitTraceLevels -- TRC_GATT
I/        (10686): BTE_InitTraceLevels -- TRC_SMP
I/        (10686): BTE_InitTraceLevels -- TRC_BTAPP
I/        (10686): BTE_InitTraceLevels -- TRC_BTIF
I/        (10686): BTE_InitTraceLevels -- TRC_PROTOCOL
,E/Tethering( 3522): No numeric data
,D/Tethering( 3522): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime( 3522): forceRefresh() from cache miss
,D/HotspotTile( 3693): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 3693): updateTetherState():false, false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 3522): forceRefresh Fail.
,V/NetworkStats( 3522): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3522): UpdateStatsForKnox
,V/NetworkStats( 3522): performPollLocked() took 2ms
,D/NtpTrustedTime( 3522): forceRefresh() from cache miss
,D/NtpTrustedTime( 3522): forceRefresh Fail.
,I/wpa_supplicant(10701): wlan0: Setting scan request: 0 sec 100000 usec
,I/wpa_supplicant(10701): wlan0: State: DISCONNECTED -> DISCONNECTED
I/SecureStorage(10701): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10701): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2902): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10701
I/SecureStorage( 2902): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10701): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10701): ssSupport state is = 1
,I/SecureStorage(10701): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10701): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2902): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10701
I/SecureStorage( 2902): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10701): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10701): ssSupport state is = 1
I/wpa_supplicant(10701): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10701): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10701): SIM READ ERROR
I/wpa_supplicant(10701): rfkill: Cannot open RFKILL control device
E/wpa_supplicant(10701): nl80211: Could not configure driver mode
E/wpa_supplicant(10701): p2p0: Failed to initialize driver interface
I/wpa_supplicant(10701): Blacklist: Clear (all) 
,I/SecureStorage(10701): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,W/bt-l2cap(10686): l2c_link_processs_ble_num_bufs 15
,E/bt-btm  (10686): BTM_SecRegister:p_cb_info->p_le_callback == 0xb390f9e1 
E/bt-btm  (10686): BTM_SecRegister: btm_cb.api.p_le_callback = 0xb390f9e1 
,I/SecureStorage(10701): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2902): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10701
I/SecureStorage( 2902): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10701): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10701): ssSupport state is = 1
I/SecureStorage(10701): [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,I/SecureStorage(10701): [INFO]: SPID(0x00000005)This device supports Secure Storage
,I/SecureStorage( 2902): [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10701
I/SecureStorage( 2902): [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
I/SecureStorage(10701): [INFO]: SPID(0x00000005)SS Daemon is running
I/wpa_supplicant(10701): ssSupport state is = 1
I/wpa_supplicant(10701): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10701): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10701): SIM READ ERROR
I/wpa_supplicant(10701): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant(10701): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant(10701): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant(10701): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant(10701): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant(10701): Skip scan - bUseNetwork false
,E/WifiStateMachine( 3522): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,E/WifiStateMachine( 3522): setSuspendOptimizations: 2 true
E/WifiStateMachine( 3522): mSuspendOptNeedsDisabled 0
,E/WifiStateMachine( 3522): Supplicant connection established
D/WifiNative-HAL( 3522): callSECApiBoolean - ID [21]
,I/wpa_supplicant(10701): HOTSPOT20_ENABLE called
I/wpa_supplicant(10701): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant(10701): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant(10701): SIM READ ERROR
I/wpa_supplicant(10701): Blacklist: Clear (all) 
,I/wpa_supplicant(10701): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant(10701): Skip scan - bUseNetwork false
,E/WifiStateMachine( 3522): setWifiState: enabled
D/WifiNative-HAL( 3522): callSECApiInt - ID [210]
,D/BluetoothAdapterProperties(10686): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,D/SmartBondingService( 3522): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/WifiConfigStore( 3522): Loading config and enabling all networks 
D/SLocation( 3522): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,E/bt-btif (10686): Write Extended Inqui
,D/SmartBondingService( 3522): getNetworkEnabled : wifi : true mobile : false
,E/bt-btif (10686): btif_storage_get_adapter_property service_mask:0x2120048
D/BluetoothAdapterProperties(10686): Address is:E0:DB:10:14:E2:C0
E/BluetoothServiceJni(10686): populateRssiValuesNative
I/bluedroid(10686): getModelRssiValues
E/BluetoothServiceJni(10686): model_rssi_values_callback: low = -75, mid = -65, high = 127
D/BluetoothAdapterProperties(10686): modelRssiValuesCallback, low, mid, high = -75,-65,127
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
,D/STATUSBAR-QSTileView( 3693): onStateChanged: Wi-Fi
D/HotspotTile( 3693): onReceive : 3, 0
,D/BluetoothAdapterProperties(10686): Name is: Note4-1
,D/SettingsProvider( 3522): name = bluetooth_name
,D/BluetoothAdapterProperties(10686): Scan Mode:20
D/BluetoothAdapterProperties(10686): Discoverable Timeout:120
D/BluetoothAdapterProperties(10686): LE Address is:E0:B7:20:28:C5:81
E/bt-btif (10686): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif (10686): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif (10686): btif_sock_init: !radio_req && !rfc_init
E/bt-btif (10686): btif_sock_init: !vhci_init
D/IOP_DB_BT(10686): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT(10686): db_open: db_open : handle 3024928784l, read 14063 bytes onto local cache
D/IOP_DB_BT(10686): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,D/IOP_DB_BT(10686): db_query: result 1
I/        (10686): iop_db_open: iop_db_open status 0
D/bte_conf(10686): Device ID record 1 : primary
D/bte_conf(10686):   vendorId            = 0075
D/bte_conf(10686):   vendorIdSource      = 0001
D/bte_conf(10686):   product             = 0100
D/bte_conf(10686):   version             = 0200
D/bte_conf(10686):   clientExecutableURL = 
D/bte_conf(10686):   serviceDescription  = 
D/bte_conf(10686):   documentationURL    = 
D/bte_conf(10686): bte_load_did_conf no section named DID2.
I/Hs20UtilService( 6348): Starting #3
E/WifiConfigStore( 3522): Not a HS20
D/BluetoothAdapterState(10686): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothPanServiceJni(10686): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
I/Hs20UtilService( 6348): Message received 5011
D/BluetoothAdapterProperties(10686): ScanMode =  20
D/BluetoothAdapterProperties(10686): State =  11
,I/WifiStateMachine( 3522): callSECApi what=207
D/SecContentProvider( 3522): uri = 3 selection = isDiscoverableEnabled
,D/BluetoothAdapterProperties(10686): Setting state to 12
I/BluetoothAdapterState(10686): Bluetooth adapter state changed: 11-> 12
,E/WifiConfigStore( 3522): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/BluetoothAdapterProperties(10686): Scan Mode:21
D/BluetoothAdapterProperties(10686): Discoverable Timeout:120
,D/SettingsProvider( 3522): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
,D/KeyguardWallpaperUpdator(10702): cancelUpdateWallpaper
,I/WifiStateMachine( 3522): update LTECoexState:0
D/WifiNative-HAL( 3522): callSECApiInt - ID [65]
,D/KeyguardWallpaperUpdator(10702): cancelUpdateCategory
D/KeyguardWallpaperUpdator(10702): stopCheckCategoryVersion
,W/BackupManagerService( 3522): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService(10686): Bluetooth PBAP supproted is true
D/BluetoothAdapterService(10686): updateAdapterState state is 12
,I/SignOutReceiver( 8274): WIFI_STATE_CHANGED_ACTION
,D/WifiNative-HAL( 3522): callSECApiBoolean - ID [13]
I/wpa_supplicant(10701): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant(10701): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant(10701): reset timer : RESET_TIMER 0
I/wpa_supplicant(10701): P2P: Current p2p state = IDLE
I/wpa_supplicant(10701): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant(10701): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant(10701): First Scan Start
,D/BluetoothAdapterService(10686): Autoconnection is available 
D/BluetoothAdapterService(10686): updateAdapterState prevState = 11newState = 12
D/BluetoothA2dp(10686): onBluetoothStateChange: up=true
D/BluetoothAdapterService(10686): starting service from this receiver
,D/BluetoothA2dp( 4806): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 3522): onBluetoothStateChange: up=true
,I/wpa_supplicant(10701): Scan requested (ret=0) - scan timeout 30 seconds
D/WifiNative-HAL( 3522): Setting external_sim to 1
,D/WifiStateMachine( 3522): Setting OUI to DA-A1-19
I/WifiNative-HAL( 3522): startHal
E/wifi    ( 3522): getStaticLongField sWifiHalHandle 0x8fa6185c
D/wifi    ( 3522): halHandle = 0x0, mVM = 0xb4d5c280, mCls = 0x601db6
I/WifiNative-HAL( 3522): Could not start hal
,I/BluetoothAdapterState(10686): Entering On State from state = 11
E/WifiStateMachine( 3522): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
,E/WifiStateMachine( 3522): Attempting to reconnect to wifi network ..
,E/native  ( 3522): do suspend true
,I/BluetoothPbapService(10686): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,W/InputMethodManagerService( 3522): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3522): [BT Setting State] State =12
I/InputMethodManagerService( 3522): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/WifiP2pService( 3522): P2pDisabledState{ what=131203 }
,E/bt_h4   (10686): vendor lib postload completed
D/CommandListener( 2845): Setting iface cfg
D/CommandListener( 2845): Trying to bring up p2p0
,D/WifiMonitor( 3522): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 3522): P2pEnablingState
D/WifiP2pService( 3522): P2pEnablingState{ what=147457 }
D/WifiP2pService( 3522): P2p socket connection successful
D/BluetoothTile( 3693):  onBluetoothStateChange:
D/WifiP2pService( 3522): P2pEnabledState
,D/BluetoothTile( 3693):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 3693): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothHeadset( 3953): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@325d8665, true
I/SamsungIME( 4427): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothHeadset( 3953): registerMessageListener
,D/StatusBarManagerService( 3522): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,D/StatusBarManagerService( 3522): setIconVisibility slot=bluetooth visible=true
D/PhoneStatusBar( 3693): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,E/WifiStateMachine( 3522): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,D/WifiStateMachine( 3522): updateConfiguredNetworkExpiration - currTime: 1453857044203
D/WifiStateMachine( 3522): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/WifiP2pService( 3522): sending p2p connection changed broadcast: IDLE
,E/WifiStateMachine( 3522): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-HAL( 3522): callSECStringApiVoid - ID [215]
E/WifiNative-HAL( 3522): invaild command id : 215
,E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3522): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine( 3522): set country code pl
,D/HeadsetService(10686): registerMessageListener
D/HeadsetService(10686): registerMessageListener
D/WifiScanningService( 3522): SCAN_AVAILABLE : 3
,I/Telecom ( 3953): BluetoothPhoneService: updateHeadsetWithCallState
D/RttService( 3522): SCAN_AVAILABLE : 3
D/HeadsetStateMachine(10686): Disconnected process message: 70
D/WifiScanningService( 3522): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 3522): startHal
D/HeadsetStateMachine(10686): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@4e56e19
D/RttService( 3522): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,I/Telecom ( 3953): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
E/WifiStateMachine( 3522): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/BluetoothTile( 3693):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 3693): onStateChanged: Bluetooth
D/WifiDisplayController( 3522): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,V/[CarModeFW](10046): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
D/WifiP2pService( 3522): create mNetworkAgent
,D/WifiDisplayController( 3522): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 3522): disconnect
D/WifiDisplayController( 3522): updateConnection
D/WifiDisplayController( 3522): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/[CarModeFW](10046): ConnectivityManager-handleMessage INITIAL_STATE_ON
,D/WifiDisplayController( 3522): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/HeadsetStateMachine(10686): Disconnected process message: 9
,D/HeadsetStateMachine(10686): mNumActive: 0 mNumHeld: 0 mCallState: 6
,D/AllShareCastTile( 3693): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 3693): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/ConnectivityService( 3522): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 3522): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 3522): updateNetworkInfo()
D/ConnectivityService( 3522): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/BluetoothPbapService(10686): Handler(): got msg=1
E/CSLegacyTypeTracker( 3522): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
D/SecContentProvider( 3522): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ContextImpl( 7824): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/wpa_supplicant(10701): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/wifi    ( 3522): getStaticLongField sWifiHalHandle 0x8e81998c
D/wifi    ( 3522): halHandle = 0x0, mVM = 0xb4d5c280, mCls = 0x800aa2
I/WifiNative-HAL( 3522): Could not start hal
E/WifiScanningService( 3522): could not start HAL
,E/WifiStateMachine( 3522): set frequency band 0
,I/AudioHardwareTinyALSA( 2858): setParameters(A2dpSuspended=false)
,E/HeadsetStateMachine(10686): terminateScoUsingVirtualVoiceCall:No present call to terminate
,V/BluetoothPbapService(10686): PBAP Service initSocket try: 0
,W/BluetoothAdapter(10686): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10686): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
,D/BluetoothSocket(10686): bindListen(), new LocalSocket 
D/BluetoothSocket(10686): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10686): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@dd5d2d5
D/BluetoothSocket(10686): channel: 19
D/BluetoothPbapService(10686): PBAP Socket is BluetoothServerSocket
,I/wpa_supplicant(10701): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3522): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
E/WifiStateMachine( 3522): setDetailed state send new extra info
,D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,D/WifiNative-HAL( 3522): p2pGetDeviceAddress
D/WifiNative-HAL( 3522): p2pGetDeviceAddress returning 92:b6:86:43:73:1c
,D/WifiP2pService( 3522): DeviceAddress: 92:73:1c
,D/WifiDisplayController( 3522): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note4-1
D/WifiDisplayController( 3522):  deviceAddress: 92:b6:86:43:73:1c
D/WifiDisplayController( 3522):  primary type: 10-0050F204-5
D/WifiDisplayController( 3522):  secondary type: null
D/WifiDisplayController( 3522):  wps: 0
D/WifiDisplayController( 3522):  grpcapab: 0
D/WifiDisplayController( 3522):  devcapab: 0
D/WifiDisplayController( 3522):  status: 3
D/WifiDisplayController( 3522):  wfdInfo: null
D/WifiDisplayController( 3522):  groupownerAddress: null
D/WifiDisplayController( 3522):  GOdeviceName: null
D/WifiDisplayController( 3522):  interfaceAddress: 
D/WifiDisplayController( 3522):  SConnectInfo : null
,D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,D/WifiP2pService( 3522): sending p2p persistent groups changed broadcast
,D/WifiP2pService( 3522): InactiveState
D/WifiP2pService( 3522): InactiveState{ what=143376 }
E/ConnectivityService( 3522): updateNetworkInfo()
D/WifiP2pService( 3522): P2pEnabledState{ what=143376 }
,I/wpa_supplicant(10701): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,D/WifiP2pService( 3522): InactiveState{ what=143376 }
D/WifiP2pService( 3522): P2pEnabledState{ what=143376 }
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 42809(2MB) AllocSpace objects, 10(160KB) LOS objects, 24% free, 48MB/64MB, paused 1.257ms total 88.183ms
,D/BluetoothManagerService( 3522): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/LocalBluetoothProfileManager( 7824): Adding local A2DP profile
,D/BluetoothMapMasInstance(10686): set MAP SDP message type : 1
,D/LocalBluetoothProfileManager( 7824): Adding local HEADSET profile
,W/BluetoothAdapter(10686): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothHeadset( 7824): BTStateChangeCB is registed
,D/BluetoothSocket(10686): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket(10686): bindListen(), new LocalSocket 
D/BluetoothSocket(10686): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10686): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3005daea
D/BluetoothSocket(10686): channel: 5
,E/BluetoothHeadset( 7824): BluetoothHeadset service is binded
,W/ContextImpl( 7824): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2137 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/Bluetoothsap( 7824): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 7824): PANU : true
D/LocalBluetoothProfileManager( 7824): Adding local MAP profile
,D/BluetoothMap( 7824): Create BluetoothMap proxy object
,W/LocalBluetoothProfileManager( 7824): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 7824): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 7824): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 7824): onReceive
D/BluetoothA2dp( 7824): Proxy object connected
,D/A2dpProfile( 7824): Bluetooth service connected
,D/BluetoothAdapterService(10686): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5b8993
D/BtConfig.SecureMode(10686): isSecureModeOn:false
,D/HeadsetProfile( 7824): Bluetooth service connected
,D/AuthorizationBluetoothService( 4245): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/Bluetoothsap( 7824): BluetoothSAP Proxy object connected
,D/SapProfile( 7824): Bluetooth service connected
D/Bluetoothsap( 7824): getConnectedDevices()
,D/BluetoothInputDevice( 7824): Proxy object connected
D/HidProfile( 7824): Bluetooth service connected
,D/BluetoothPan( 7824): BluetoothPAN Proxy object connected
D/PanProfile( 7824): Bluetooth service connected
,D/BluetoothMap( 7824): Proxy object connected
D/MapProfile( 7824): Bluetooth service connected
D/BluetoothPbap( 7824): Proxy object connected
D/PbapServerProfile( 7824): Bluetooth service connected
,D/NearbySettings( 7824): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 7824): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 7824): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 7824): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 7824): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 7824): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/SecContentProvider( 3522): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/WifiService( 3522): New client listening to asynchronous messages
,I/NearbySettings( 7824): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 7824): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7824): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 7824): MountReceiver.mPrefHandler - 7002
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10882): MountEmulatedStorage()
E/Zygote  (10882): v2
I/libpersona(10882): KNOX_SDCARD checking this for 10079
I/libpersona(10882): KNOX_SDCARD not a persona
,I/SELinux (10882): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=10882 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (10882): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10882): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/BluetoothAdapter(10686): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(10686): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
D/BluetoothSocket(10686): bindListen(), new LocalSocket 
D/BluetoothSocket(10686): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(10686): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@344e9024
,D/BluetoothSocket(10686): channel: 12
I/BtOppRfcommListener(10686): Accept thread started.
,D/TimaKeyStoreProvider(10882): TimaSignature is unavailable
,D/ActivityThread(10882): Added TimaKeyStore provider
,D/ResourcesManager(10882): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/FileShare-Server(10882): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 3522): Killing 9968:com.sec.android.app.myfiles/u0a53 (adj 13): bgCount ##31
,I/wpa_supplicant(10701): nl80211: Received scan results (5 BSSes)
,I/wpa_supplicant(10701): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant(10701): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant(10701): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant(10701): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3522): [1,453,857,044,748 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3522): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@e7b6ccb sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3522): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,I/wpa_supplicant(10701): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant(10701): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3522): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3522): setDetailed state send new extra info"NG700"
I/wpa_supplicant(10701): Associated with C0.AA.48
,D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,I/wpa_supplicant(10701): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant(10701): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3522): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,I/wpa_supplicant(10701): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant(10701): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant(10701): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3522): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant(10701): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(10701): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant(10701): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant(10701): Blacklist: Clear (temp) 
I/wpa_supplicant(10701): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3522): Network connection established
,D/WifiNative-HAL( 3522): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3522): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine( 3522): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,E/WifiStateMachine( 3522): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid null
D/ConnectivityService( 3522): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3522): L2ConnectedState "NG700" nid=0
D/ConnectivityService( 3522): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiConfigStore( 3522): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3522): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3522): updateNetworkInfo()
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 6348): Starting #4
,I/Hs20UtilService( 6348): Message received 5007
,D/NearbySettings( 7824): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 7824): DMSUtil.isNetworkConnected - flag-null, state-null
E/WifiStateMachine( 3522): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
E/WifiStateMachine( 3522): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3522): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3522): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/NearbySettings( 7824): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 7824): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 7824): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7824): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 7824): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver( 8274): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2845): Setting iface cfg
,E/WifiStateMachine( 3522): Start Dhcp Watchdog 1
,D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,E/WifiStateMachine( 3522): Force RSSI Broadcast 1/3
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3522): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3522): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3522): do suspend false
,D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService( 3522): InactiveState{ what=143375 }
D/SecContentProvider2( 3522): mCursor = null
D/WifiP2pService( 3522): P2pEnabledState{ what=143375 }
,I/jxcore-log(10615): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(10615): 
,E/dhcpcd  (10900): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (10900): version 5.5.6 starting
,E/dhcpcd  (10900): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (10900): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (10900): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (10900): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  (10900): bssid match
,I/dhcpcd  (10900): wlan0: rebinding lease of 192.168.1.124
,I/jxcore-log(10615): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(10615): 
,I/dhcpcd  (10900): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/jxcore-log(10615): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(10615): 
,I/jxcore-log(10615): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(10615): 
,I/dhcpcd  (10900): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3522): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3522): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/jxcore-log(10615): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(10615): 
,I/jxcore-log(10615): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(10615): 
,I/jxcore-log(10615): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(10615): 
,I/jxcore-log(10615): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(10615): 
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3522): do suspend true
,D/WifiP2pService( 3522): InactiveState{ what=143375 }
D/WifiP2pService( 3522): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3522): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3522): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3522): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3522): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3522): Not connected state, yet.
E/WifiStateMachine( 3522): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiStateMachine( 3522): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3522): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3522): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3522): callSECApiInt - ID [210]
,E/WifiStateMachine( 3522): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3522): updateNetworkInfo()
,D/ConnectivityService( 3522): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3522): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine( 3522): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3522): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3522): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3522): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3522): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 6348): Starting #5
,E/WifiStateMachine( 3522): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3522): Now, connected state.
E/WifiStateMachine( 3522): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine( 3522): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
I/Hs20UtilService( 6348): Message received 5007
,I/WifiTrafficPoller( 3522): evaluateTrafficStatsPolling
,D/NearbySettings( 7824): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 7824): MountReceiver.onReceive - Keep current state
,D/ConnectivityService( 3522): Adding Route [fe80::/64 -> :: wlan0] to network 502
,D/ConnectivityService( 3522): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,D/ConnectivityService( 3522): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 502
,E/ConnectivityService( 3522): Unexpected mtu value: 0, wlan0
,V/        ( 2845): QcRouteController
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3522): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller( 3522): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3522): callSECApiVoid - ID [212]
,E/WifiStateMachine( 3522): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine( 3522): REQUEST_POWER_SAVE_ON
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
V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,E/Watchdog( 3522): !@Sync 4
,I/SignOutReceiver( 8274): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2845): QcRouteController
,I/Hs20UtilService( 6348): Starting #6
,I/Hs20UtilService( 6348): Message received 5007
,D/NearbySettings( 7824): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 7824): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 7824): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
V/        ( 2845): QcRouteController
I/NearbySettings( 7824): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 7824): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 7824): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 7824): MountReceiver.mPrefHandler - 7002
V/        ( 2845): QcRouteController
,I/SignOutReceiver( 8274): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2845): QcRouteController
,I/Hs20UtilService( 6348): Starting #7
,I/Hs20UtilService( 6348): Message received 5007
,D/NearbySettings( 7824): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 7824): MountReceiver.onReceive - Keep current state
,D/ConnectivityService( 3522): Setting Dns servers for network 502 to [/192.168.1.1]
,D/ConnectivityService( 3522): LTETest block dns file not exists
,D/ConnectivityService( 3522): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
E/ConnectivityService( 3522): updateNetworkInfo()
E/ConnectivityService( 3522): updateNetworkInfo()
D/ConnectivityService( 3522): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3522): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 3522): rematching NetworkAgentInfo [WIFI () - 502]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): Checking http://clients3.google.com/generate_204 on "NG700"
,I/WifiStateMachine( 3522): callSECApi what=220
D/WifiStateMachine( 3522): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/System.out( 3522): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 3522): (HTTPLog)-Static: isShipBuild true
I/System.out( 3522): (HTTPLog)-Thread-189-841700711: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 3522): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService( 3522):    accepting network in place of null
D/ConnectivityService( 3522): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
D/TelephonyNetworkFactory( 3983): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 3522): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3522): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,D/ConnectivityService( 3522): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 1000
,D/Tethering( 3522): MasterInitialState.processMessage what=3
D/ConnectivityService( 3522): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/SmartBondingService( 3522): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3522): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
,V/NetworkStats( 3522): updateIfacesLocked()
D/NetworkStatsFactory( 3522): UpdateStatsForKnox
V/NetworkStats( 3522): performPollLocked(flags=0x1)
,D/ConnectivityService( 3522): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/NtpTrustedTime( 3522): forceRefresh() from cache miss
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 1000
D/SmartBondingService( 3522): getNetworkEnabled : wifi : true mobile : false
,V/NetworkStats( 3522): performPollLocked() took 5ms
,D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 4469): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
,I/SignOutReceiver( 8274): NETWORK_STATE_CHANGED_ACTION
,D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,I/SurfaceFlinger( 2850): id=13 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3522): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3522
,D/NtpTrustedTime( 3522): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1453857047503 mCachedNtpElapsedRealtime : 133020 mCachedNtpCertainty : 10
,D/mali_winsys( 3693): new_window_surface returns 0x3000,  [1120x201]-format:1
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
V/NetworkStats( 3522): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/System.out( 3522): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jan 2016 01:10:47 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453857046047], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453857046032]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): Validated
D/ConnectivityService( 3522): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 3522): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 3522): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService( 3522): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524290
D/ConnectivityService( 3522): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 4469): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,I/jxcore-log(10615): Test app app.js loaded
I/jxcore-log(10615): 
,I/chromium(10615): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService( 3522): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 5899): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 5899): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 5899): [com.wssyncmldm.llllIIIllIlIIIIllllI(263/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,D/SmartBondingService( 3522): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3522): SmartBondingReceiver: wifi is connected
,D/SmartBondingService( 3522): SmartBondingReceiver: wifi ap is changed, init speed ratio
,D/SmartBondingService( 3522): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
,D/SmartBondingService( 3522): getSBEnabled() enabled =false
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,D/AlarmManagerService( 3522): Setting time of day to sec=1453857048
,D/AlarmManagerService( 3522): Trying to open a file
,D/SmartBondingService( 3522): getNetworkEnabled : wifi : true mobile : false
,D/AlarmManagerService( 3522): File Open Success
D/AlarmManagerService( 3522): File Close Success
I/AlarmManagerService( 3522): DRM_TIME_PATH CHMOD 666 for resetState done 
,V/AlarmManager( 3522): waitForAlarm result :65536
,I/DBG_DM  ( 5899): [IlIIlIIlIllllIlllIII(224/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/DBG_DM  ( 5899): [IlIlllIlllllIlIllllI(403/llllllIllIlIlllIIlIl)] Check completed.
,I/DBG_DM  ( 5899): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 5899): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10968): MountEmulatedStorage()
E/Zygote  (10968): v2
I/libpersona(10968): KNOX_SDCARD checking this for 1000
I/libpersona(10968): KNOX_SDCARD not a persona
,I/SELinux (10968): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10968): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=10968 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (10968): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 5899): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 5899): [IIlIIIlllllIIlIIIlII(72/llllIIIllIlIIIIllllI)] 
,D/WifiStateMachine( 3522): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
,D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_SET
D/SettingsProvider( 3522): name = lockscreen_zoom_panning_effect
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 10060
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
,I/System.out( 3522): Thread-145(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3522): Thread-145(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3522): Thread-145(ApacheHTTPLog):isShipBuild true
W/BackupManagerService( 3522): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
I/System.out( 3522): Thread-145(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 1000
,D/KeyguardEffectViewUtil( 3693): isPowerSavingMode() :false
,D/KeyguardEffectViewUtil( 3693): isStrongPowerSavingMode() :false
D/KeyguardEffectViewController( 3693): isZoomPanningEffectEnabled() isZoomPanningEffect = false, isPowerSavingMode = false
,D/VisualEffectParticleEffect( 3693): KeyguardEffectViewParticleSpace : setLayers
D/VisualEffectParticleEffect( 3693): KeyguardEffectViewParticleSpace : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{a0af3f6 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3693): KeyguardEffectViewParticleSpace : wallpaperWidget = com.android.keyguard.sec.KeyguardEffectViewWallpaper{34303f7 V.E..... ......I. 0,0-0,0}
D/VisualEffectParticleEffect( 3693): setInitValues : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{a0af3f6 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3693): clearEffect
D/WallpaperWidget( 3693): setLockScreenWallpaper()
,D/KeyguardEffectViewUtil( 3693): getCurrentWallpaper() mWallpaperPath :null
,D/TimaKeyStoreProvider(10968): TimaSignature is unavailable
,W/Settings( 3522): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ActivityThread(10968): Added TimaKeyStore provider
,W/SEC_DRM_PLUGIN_Playready( 2855): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1453857046 after conversion: 1453857046
W/SEC_DRM_PLUGIN_Playready( 2855): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1453857048 after conversion: 1453857048
,I/DBG_DM  ( 5899): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 5899): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 8
,D/ResourcesManager(10968): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/DBG_DM  ( 5899): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,I/DBG_DM  ( 5899): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,I/DBG_DM  ( 5899): [IlIlllIlllllIlIllllI(177/lllIlIlIIIllIIlIllIl)] nDownloadPostpone is [8]
,D/ResourcesManager( 6462): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/PCWCLIENTTRACE_LOG(10968): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(10968): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(10968): new DMDBOpenHelper instance
,W/ResourcesManager( 6462): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6462): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/appmanager(:<default>):QuickExperimentControllerImpl(10304): Exposure of experiment com.facebook.http.g.an@2b54033d occurred when no user was logged in
,I/GoogleURLConnFactory( 4245): Using platform SSLCertificateSocketFactory
,I/DBG_DM  ( 5899): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 0
,I/PCWCLIENTTRACE_PushUtil(10968): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(10968): sales region : global
I/PCWCLIENTTRACE_PushUtil(10968): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(10968): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 5899): [IlIIlIIlIllllIlllIII(280/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 5899): [llllIIIllIllIlllIIlI(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/DBG_DM  ( 5899): [IlIIlIIlIllllIlllIII(1907/lllIlIlIIIllIIlIllIl)] 
,W/appmanager(:<default>):QuickExperimentControllerImpl(10304): Exposure of experiment com.facebook.http.g.aw@29de1c83 occurred when no user was logged in
W/appmanager(:<default>):QuickExperimentControllerImpl(10304): Exposure of experiment com.facebook.http.g.aj@10943e00 occurred when no user was logged in
W/appmanager(:<default>):QuickExperimentControllerImpl(10304): Exposure of experiment com.facebook.http.g.a@2e029639 occurred when no user was logged in
I/DBG_DM  ( 5899): [com.wssyncmldm.XDMBroadcastReceiver(332/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
I/DBG_DM  ( 5899): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
,I/DBG_DM  ( 5899): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(502/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,W/appmanager(:<default>):QuickExperimentControllerImpl(10304): Exposure of experiment com.facebook.http.g.k@2eff3a2c occurred when no user was logged in
,E/Zygote  (10998): MountEmulatedStorage()
E/Zygote  (10998): v2
I/libpersona(10998): KNOX_SDCARD checking this for 10135
I/libpersona(10998): KNOX_SDCARD not a persona
I/SELinux (10998): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=10998 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (10998): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10998): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 5899): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 5899): [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
,I/DBG_DM  ( 5899): [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
,I/DBG_DM  ( 5899): [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 5899): [llllIIIllIllIlllIIlI(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
E/DBG_DM  ( 5899): [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
,E/DBG_DM  ( 5899): [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@c2dc751
,D/TimaKeyStoreProvider(10998): TimaSignature is unavailable
,I/DBG_DM  ( 5899): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : false
D/ActivityThread(10998): Added TimaKeyStore provider
,I/System.out(10304): Thread-1424(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(10304): Thread-1424(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(10304): Thread-1424(ApacheHTTPLog):isShipBuild true
I/System.out(10304): Thread-1424(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/appmanager(:<default>):QuickExperimentControllerImpl(10304): Exposure of experiment com.facebook.http.g.c@283d371 occurred when no user was logged in
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10110
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10998): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/Zygote  (11019): MountEmulatedStorage()
E/Zygote  (11019): v2
I/libpersona(11019): KNOX_SDCARD checking this for 10090
I/libpersona(11019): KNOX_SDCARD not a persona
,I/SELinux (11019): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/DBG_DM  ( 5899): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/SELinux (11019): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11019): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=11019 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11035): MountEmulatedStorage()
I/libpersona(11035): KNOX_SDCARD checking this for 10050
E/Zygote  (11035): v2
I/libpersona(11035): KNOX_SDCARD not a persona
,I/SELinux (11035): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11035): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11035): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.sec.android.gallery3d for service com.sec.android.gallery3d/.remote.picasa.PicasaService: pid=11035 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11019): TimaSignature is unavailable
,D/ActivityThread(11019): Added TimaKeyStore provider
,D/TimaKeyStoreProvider(11035): TimaSignature is unavailable
,D/ActivityThread(11035): Added TimaKeyStore provider
,I/System.out( 3522): AsyncTask #1 calls detatch()
,I/dex2oat (11015): ----------------------------------------------------
I/dex2oat (11015): <SS>: S T A R T I N G . . .
I/dex2oat (11015): <SS>: Zip is absent. Canceled.
W/System.err( 3522): java.io.IOException: Not Found
I/dex2oat (11015): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads324089066.jar --oat-fd=54 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads324089066.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
W/System.err( 3522): 	at a.d.b(Unknown Source)
W/System.err( 3522): 	at a.d.doInBackground(Unknown Source)
W/System.err( 3522): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 3522): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 3522): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 3522): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
D/ResourcesManager(11019): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
W/System.err( 3522): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 3522): 	at java.lang.Thread.run(Thread.java:818)
,D/GpsLocationProvider( 3522): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 5899): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/KeyguardEffectViewUtil( 3693): set current wallpaper info
,D/SettingsProvider( 3522): name = keyguard_current_wallpaper_type
D/ResourcesManager(11035): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 10060
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
,W/ResourcesManager(11035): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(11035): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11035): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11035): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11035): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(11035): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(11035): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(11035): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 3522): Killing 9985:com.sec.android.app.soundalive/u0a59 (adj 13): bgCount ##31
,I/System.out( 6462): Thread-615(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6462): Thread-615(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6462): Thread-615(ApacheHTTPLog):isShipBuild true
I/System.out( 6462): Thread-615(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10202
,D/SecContentProvider2( 3522): uri = 14 selection = getSealedState
D/SecContentProvider2( 3522): mCursor = null
,I/MusicStore(10998): Database version: 104
D/ApplicationPolicy( 3522): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 3522): showStatusBarByNotification() mOpenByNotification=false
,I/DBG_DM  ( 5899): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
,D/ResourcesManager( 3693): creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
,I/DBG_DM  ( 5899): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/qtaguid ( 6462): Tagging socket 27 with tag ff44265f00000000{4282656351,0} uid -1, pid: 6462, getuid(): 10202
,D/ResourcesManager(10998): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(10998): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(10998): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/ActivityThread( 4469): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager( 3522): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 15843, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager( 3522): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 165281, reason: UserStart
,V/JNIHelp (10998): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourceType( 4967): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4967): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/dex2oat (11015): dex2oat took 146.051ms (threads: 8)
,W/BackupManagerService( 3522): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/PackageManager( 3522): findPreferredActivity: No PreferredActivities set
,D/SettingsProvider( 3522): name = keyguard_current_wallpaper_file_path
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 10060
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
,W/BackupManagerService( 3522): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/SettingsProvider( 3522): name = keyguard_current_wallpaper_res_id
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
W/ActivityThread(10998): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 10060
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
W/System  (10998): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1fcb90b7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(10998): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(10998): GMSCore installation verified
,W/BackupManagerService( 3522): dataChanged but no participant pkg='com.android.providers.settings' uid=10060
,D/SSRM:n  ( 3522): SIOP:: AP = 280, PST = 276, CUR = 32
,I/DBG_DM  ( 5899): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 8
D/StatusBar-DoNotDistrub( 3693): Received intent with android.intent.action.TIME_SET action
,D/StatusBar-DoNotDistrub( 3693): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar-DoNotDistrub( 3693): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,V/AudioPolicyManager( 2858): getOutputsForDevice device 0002 -> 0002
I/DBG_DM  ( 5899): [com.wssyncmldm.ui.XUIFotaPostponeActivity(378/lllIlIlIIIllIIlIllIl)] No idle Postpone
,I/AudioService( 3522): getStreamVolume 5 index 110
D/StatusBar-DoNotDistrub( 3693): The STREAM NOTIFICATION volume is 0
,D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=com.android.systemui
I/ConfigStore(10998): Config Database version: 1
,I/DBG_DM  ( 5899): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,W/ActivityThread(10304): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/qtaguid ( 6462): Untagging socket 27
I/System.out( 6462): Thread-615 calls detatch()
,D/SecContentProvider2( 3522): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3522): mCursor = null
,D/NearbySource(11035): Nearby Source Create!
,D/DelayedSyncController(11019): Delaying sync.
,D/NearbyContext(11035): Nearby Context Create!
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11035): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource(11035): Samsung link source created
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ContextImpl(10998): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ContactProvider(11035): getAllContactInfoList Start
D/KnoxNotification( 3693): ----- inflateViews : modified publicViewLocal -----
,I/System.out( 4245): (HTTPLog)-Static: isSBSettingEnabled false
,D/KnoxNotification( 3693): ----- inflateViews : modified KnoxViewLocal -----
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10202
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4187, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:-193, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1740
D/BatteryService( 3522): stay LED for fully charged
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/PersonaManager( 3693): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 3693): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@18effa07
,D/PersonaManager( 3693): isKioskContainerExistOnDevice
D/PersonaManager( 3693): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3693): Icon Only
,I/System.out(10304): P[5]_NetworkDispatch1 calls detatch()
,I/System.out( 4245): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4245): Tagging socket 67 with tag 1000120300000000{268440067,0} uid -1, pid: 4245, getuid(): 10014
,V/HeadsetService(10686): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10686): Disconnected process message: 10
,I/qtaguid ( 6462): Tagging socket 54 with tag 0{0,0} uid -1, pid: 6462, getuid(): 10202
,I/StatusBar( 3693): Icon Only
,D/PanelView( 3693): There is/are notification(s) 
,D/PanelView( 3693): There is/are notification(s) 
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10998): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/PersonaManager( 3693): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3693): Icon Only
I/StatusBar( 3693): Icon Only
D/PanelView( 3693): There is/are notification(s) 
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10998): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/KeyguardEffectViewUtil( 3693): isPowerSavingMode() :false
,D/KeyguardEffectViewUtil( 3693): isStrongPowerSavingMode() :false
,D/KeyguardEffectViewController( 3693): isZoomPanningEffectEnabled() isZoomPanningEffect = false, isPowerSavingMode = false
,D/VisualEffectParticleEffect( 3693): KeyguardEffectViewParticleSpace : setLayers
D/VisualEffectParticleEffect( 3693): KeyguardEffectViewParticleSpace : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{a0af3f6 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3693): KeyguardEffectViewParticleSpace : wallpaperWidget = com.android.keyguard.sec.KeyguardEffectViewWallpaper{34303f7 V.E..... ......I. 0,0-0,0}
D/VisualEffectParticleEffect( 3693): setInitValues : widgetLayout = com.android.systemui.statusbar.phone.NotificationPanelView{a0af3f6 G.E..... ......I. 0,0-0,0 #7f0e0193 app:id/notification_panel}
D/VisualEffectParticleEffect( 3693): clearEffect
D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,E/Auth.Api.Credentials( 4469): [CredentialSyncAdapter] Unknown sync event.
,D/ContactProvider(11035): getAllContactInfoList End
I/syncContacts(11035): thread: 1478, sync time = 174
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/PanelView( 3693): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,I/ActivityManager( 3522): Killing 10004:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##31
,I/AudioService( 3522): getStreamVolume 3 index 0
,I/MediaRouter(10998): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/NetworkMonitor(10998): type=WIFI subType= reason=null isConnected=true
,I/qtaguid ( 4245): Tagging socket 71 with tag 1000120300000000{268440067,0} uid -1, pid: 4245, getuid(): 10014
,W/DefaultRequestDirector( 6462): Authentication error: Unable to respond to any of these challenges: {bearer=WWW-Authenticate: Bearer realm="https://accounts.google.com/"}
,I/qtaguid ( 6462): Untagging socket 54
,I/System.out( 6462): Thread-620 calls detatch()
,E/Volley  ( 6462): [620] xe.a: Unexpected response code 401 for https://www.googleapis.com/youtubei/v1/account/get_setting_categories?key=AIzaSyA8eiZmM1FaDVjRy-df2KTyQ_vz_yYM39w
,I/qtaguid ( 6462): Tagging socket 54 with tag 0{0,0} uid -1, pid: 6462, getuid(): 10202
,I/qtaguid ( 6462): Tagging socket 61 with tag 0{0,0} uid -1, pid: 6462, getuid(): 10202
,E/Zygote  (11096): MountEmulatedStorage()
E/Zygote  (11096): v2
I/libpersona(11096): KNOX_SDCARD checking this for 10002
I/libpersona(11096): KNOX_SDCARD not a persona
,I/SELinux (11096): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11096 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11096): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11096): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/DefaultRequestDirector( 6462): Authentication error: Unable to respond to any of these challenges: {bearer=WWW-Authenticate: Bearer realm="https://accounts.google.com/"}
,I/NetworkMonitor(10998): type=WIFI subType= reason=null isConnected=true
,I/qtaguid ( 6462): Untagging socket 54
,I/System.out( 6462): Thread-620 calls detatch()
,E/Volley  ( 6462): [620] xe.a: Unexpected response code 401 for https://www.googleapis.com/youtubei/v1/account/get_setting_categories?key=AIzaSyA8eiZmM1FaDVjRy-df2KTyQ_vz_yYM39w
,E/YouTube ( 6462): apps.youtube.app.task.YouTubeNetworkTaskService.a:119 Failed to fetch settings
E/YouTube ( 6462): fdv: java.util.concurrent.ExecutionException: wb
E/YouTube ( 6462): 	at fco.a(SourceFile:103)
E/YouTube ( 6462): 	at fcp.c(SourceFile:160)
E/YouTube ( 6462): 	at com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService.a(SourceFile:111)
E/YouTube ( 6462): 	at com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService.a(SourceFile:49)
E/YouTube ( 6462): 	at emi.run(Unknown Source)
E/YouTube ( 6462): Caused by: java.util.concurrent.ExecutionException: wb
E/YouTube ( 6462): 	at xz.a(SourceFile:117)
E/YouTube ( 6462): 	at xz.get(SourceFile:88)
E/YouTube ( 6462): 	at gky.get(SourceFile:69)
E/YouTube ( 6462): 	at fco.a(SourceFile:99)
E/YouTube ( 6462): 	... 4 more
E/YouTube ( 6462): Caused by: wb
E/YouTube ( 6462): 	at xe.a(SourceFile:141)
E/YouTube ( 6462): 	at gkq.a(SourceFile:49)
E/YouTube ( 6462): 	at wk.run(SourceFile:105)
,D/TimaKeyStoreProvider(11096): TimaSignature is unavailable
,D/ActivityThread(11096): Added TimaKeyStore provider
,I/ActivityManager( 3522): Killing 10021:com.google.android.apps.docs/u0a101 (adj 13): bgCount ##31
,D/PicasaService(11035): start picasa sync
,D/ResourcesManager(11096): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,D/PicasaService(11035): end picasa sync
,I/ActivityManager( 3522): Killing 10064:com.vlingo.midas/u0a34 (adj 13): bgCount ##31
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(10615): setDiscoveryMode: Mode set to BLE
,I/jxcore-log(10615): BLE advertisement is supported
I/jxcore-log(10615): 
,D/ChimeraCfgMgr( 4469): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4469): Module APK com.google.android.play.games already loaded
,I/ActivityManager( 3522): Killing 10111:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11116): MountEmulatedStorage()
E/Zygote  (11116): v2
I/libpersona(11116): KNOX_SDCARD checking this for 1000
I/libpersona(11116): KNOX_SDCARD not a persona
,I/SELinux (11116): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11116): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11116): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11116 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/GamesSyncServiceMain( 4469): Found unexpected GCM tag when scheduling; aborting
W/GamesSyncServiceMain( 4469): Failed to execute periodic sync, missing client context - aborting
,D/TimaKeyStoreProvider(11116): TimaSignature is unavailable
,D/ActivityThread(11116): Added TimaKeyStore provider
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 81533(3MB) AllocSpace objects, 9(167KB) LOS objects, 24% free, 49MB/65MB, paused 2.414ms total 156.696ms
,D/ResourcesManager(11116): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/DelayedSyncController(11019): Delaying sync.
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/DIAGMON_AGENT(11116): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,E/Zygote  (11137): MountEmulatedStorage()
E/Zygote  (11137): v2
I/libpersona(11137): KNOX_SDCARD checking this for 10123
I/libpersona(11137): KNOX_SDCARD not a persona
,I/SELinux (11137): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11137): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=11137 uid=10123 gids={50123, 9997, 3003} abi=armeabi-v7a
,E/SELinux (11137): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8745(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 876us total 20.672ms
,I/GoogleURLConnFactory( 4469): Using platform SSLCertificateSocketFactory
,D/TimaKeyStoreProvider(11137): TimaSignature is unavailable
,D/ActivityThread(11137): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 801us total 18.725ms
,D/ResourcesManager(11137): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 935us total 16.007ms
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DIAGMON_AGENT(11116): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11116): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11116): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11116): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/System.out( 4469): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 4469): (HTTPLog)-Static: isShipBuild true
I/System.out( 4469): (HTTPLog)-Thread-310-177884234: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 4469): (HTTPLog)-Static: isSBSettingEnabled false
,W/AbstractGoogleClient(11137): Application name is not set. Call Builder#setApplicationName.
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,W/PhenotypeConfigurator( 4245): Server returned 404
,I/System.out( 4469): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4469): Tagging socket 99 with tag 1000210100000000{268443905,0} uid -1, pid: 4469, getuid(): 10014
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11162): MountEmulatedStorage()
E/Zygote  (11162): v2
I/libpersona(11162): KNOX_SDCARD checking this for 10012
I/libpersona(11162): KNOX_SDCARD not a persona
,I/SELinux (11162): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11162 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11162): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11162): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/qtaguid ( 4469): Tagging socket 105 with tag 1000210100000000{268443905,0} uid -1, pid: 4469, getuid(): 10014
,D/TimaKeyStoreProvider(11162): TimaSignature is unavailable
,D/ActivityThread(11162): Added TimaKeyStore provider
,D/ResourcesManager(11162): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/FOTA_Client(11162): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11162): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/System.out( 4245): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4245): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 4245): Tagging socket 56 with tag 1000040100000000{268436481,0} uid 10014, pid: 4245, getuid(): 10014
,I/FOTA_Client(11162): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/qtaguid ( 4245): Tagging socket 74 with tag 1000040100000000{268436481,0} uid 10014, pid: 4245, getuid(): 10014
,E/Zygote  (11180): MountEmulatedStorage()
E/Zygote  (11180): v2
I/libpersona(11180): KNOX_SDCARD checking this for 10021
I/libpersona(11180): KNOX_SDCARD not a persona
,I/SELinux (11180): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11180): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11180 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,E/SELinux (11180): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11180): TimaSignature is unavailable
,D/ActivityThread(11180): Added TimaKeyStore provider
,D/ResourcesManager(11180): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (11180): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Jan 27 02:10:49 GMT+01:00 2016
,I/KLMS-2.4.521: (11180): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11180): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11180): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11180): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11180): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11180): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11180): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,E/Zygote  (11196): MountEmulatedStorage()
E/Zygote  (11196): v2
I/libpersona(11196): KNOX_SDCARD checking this for 10038
I/libpersona(11196): KNOX_SDCARD not a persona
,I/KLMS-2.4.521: (11180): StateImplV2(): networkChangeListener().START
,I/SELinux (11196): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11196 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/SELinux (11196): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11196): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (11180): NetworkChangeOperations(): uploadRequestLog().START 
,D/TimaKeyStoreProvider(11196): TimaSignature is unavailable
,D/ActivityThread(11196): Added TimaKeyStore provider
,I/KLMS-2.4.521: (11180): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (11180): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (11180): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3522): Killing 10128:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/ResourcesManager(11196): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(11196): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11217): MountEmulatedStorage()
E/Zygote  (11217): v2
I/libpersona(11217): KNOX_SDCARD checking this for 1000
I/libpersona(11217): KNOX_SDCARD not a persona
,I/SELinux (11217): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11217): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=11217 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (11217): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Killing 10145:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11217): TimaSignature is unavailable
,D/ActivityThread(11217): Added TimaKeyStore provider
,D/ResourcesManager(11217): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11237): MountEmulatedStorage()
E/Zygote  (11237): v2
I/libpersona(11237): KNOX_SDCARD checking this for 10039
I/libpersona(11237): KNOX_SDCARD not a persona
,I/SELinux (11237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11237): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11237): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=11237 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/System.out(11137): (HTTPLog)-Static: isSBSettingEnabled false
I/ActivityManager( 3522): Killing 10162:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
I/System.out(11137): (HTTPLog)-Static: isShipBuild true
I/System.out(11137): (HTTPLog)-Thread-1491-900898853: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(11137): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10123
,I/System.out(11137): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid (11137): Tagging socket 28 with tag 1100000000000000{285212672,0} uid -1, pid: 11137, getuid(): 10123
,I/VacuumService( 4245): Vacuum at: now=1453857049963 tag=VacuumService
,D/TimaKeyStoreProvider(11237): TimaSignature is unavailable
,D/ActivityThread(11237): Added TimaKeyStore provider
,D/ResourcesManager(11237): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(11237): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(11237): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService(11237): PushLog.txt file is not deleted.
D/SPPClientService(11237): PushLog.txt file is not deleted.
D/SPPClientService(11237): ============PushLog. stop!
,E/SPPClientService(11237): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11260): MountEmulatedStorage()
,E/Zygote  (11260): v2
I/libpersona(11260): KNOX_SDCARD checking this for 10045
I/libpersona(11260): KNOX_SDCARD not a persona
,I/SELinux (11260): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11260): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11260): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=11260 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 10246:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11260): TimaSignature is unavailable
,D/ActivityThread(11260): Added TimaKeyStore provider
,D/ResourcesManager(11260): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/qtaguid (11137): Untagging socket 28
,I/SA      (11260): [SSP] onCreated
,D/WifiStateMachine( 3522): updateConfiguredNetworkExpiration - currTime: 1453857050140
D/WifiStateMachine( 3522): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,I/SA      (11260): [TPM] There is no property file
,I/SA      (11260): [SCU] isHaveSA() - false
,I/SA      (11260): [TPM] getModelProperty : null
I/SA      (11260): [TPM] getCSCProperty : null
,I/SA      (11260): [DM] init START
,I/SA      (11260): [DM] This device is not a Vodafone
,I/SA      (11260): checkReactivationActive for LOLLIPOP
I/SA      (11260): checkReactivationActive for reactiveActive
I/SA      (11260): setSupportRL : true
,I/SA      (11260): [SCU] isHaveSA() - false
I/SA      (11260): support phone number id : false
I/SA      (11260): [DM] init END
,I/SA      (11260): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11260): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11260): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11260): [SLFUCHKMGR] constructor called
,I/SA      (11260): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11260): [OR] == isSIMCardReady false ==
,I/SA      (11260): [SCU] == networkStateCheck == true
I/SA      (11260): [DM] getCountryCodeFromCSC : PL
I/SA      (11260): isChinaCountryCode : false
I/SA      (11260): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11260): [OR] == networkStateCheck true ==
,I/SA      (11260): [OR] GetMyCountryZoneTask
,I/SA      (11260): [OR] onReceive END
,I/ActivityManager( 3522): Killing 10194:com.google.android.apps.plus/u0a147 (adj 13): bgCount ##31
,I/SA      (11260): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 3717): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/CalendarSyncAdapter(11137): Found 0 events marked dirty & lastSynced
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/SA      (11260): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11260): [SSP] query invoked
,E/Zygote  (11282): MountEmulatedStorage()
I/libpersona(11282): KNOX_SDCARD checking this for 10067
E/Zygote  (11282): v2
I/libpersona(11282): KNOX_SDCARD not a persona
I/SELinux (11282): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SA      (11260): [TPMU] GetMccFromDB : null
,I/SA      (11260): [SCU] getMccFromPreferece mcc = 260
I/SA      (11260): [TPM] isNoProxy(default) : true
,I/SELinux (11282): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11282): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=11282 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,W/libprocessgroup( 3522): failed to kill pid 10194: No such process
,W/IdleConnectionHandler(10304): Removing a connection that never existed!
,D/TimaKeyStoreProvider(11282): TimaSignature is unavailable
,D/ActivityThread(11282): Added TimaKeyStore provider
,I/ActivityManager( 3522): Killing 10264:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/ActivityManager( 3522): Killing 10281:com.facebook.system/u0a10 (adj 13): bgCount ##31
,D/ResourcesManager(11282): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/ActivityManager( 3522): Killing 10334:com.sec.android.app.samsungapps/u0a13 (adj 13): bgCount ##31
,I/sCloudBackupApp(11282): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(11282): Other Intent
,I/ActivityManager( 3522): Killing 10365:com.sec.android.widgetapp.activeapplicationwidget/u0a173 (adj 13): bgCount ##31
,D/accuweather( 5157): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,W/BaseAppContext( 4245): Using Auth Proxy for data requests.
,E/BaseAppContext( 4245): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5157): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5157): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
,D/accuweather( 5157): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5157): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5157): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5157): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11305): MountEmulatedStorage()
E/Zygote  (11305): v2
I/libpersona(11305): KNOX_SDCARD checking this for 1000
I/libpersona(11305): KNOX_SDCARD not a persona
,I/SELinux (11305): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11305): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=11305 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (11305): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/System.out( 4245): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4245): Tagging socket 56 with tag 1000040100000000{268436481,0} uid 10014, pid: 4245, getuid(): 10014
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/TimaKeyStoreProvider(11305): TimaSignature is unavailable
,D/ActivityThread(11305): Added TimaKeyStore provider
,D/ResourcesManager(11305): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(11305): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/WifiStateMachine( 3522): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine( 3522): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService( 3522): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/SmartBondingService( 3522): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/SmartBondingService( 3522): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
,D/SmartBondingService( 3522): getSBEnabled() enabled =false
,V/        ( 2845): QcRouteController
,I/KnoxUsageLogPro(11305): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(11305): premStatus:2
,I/qtaguid ( 4469): Untagging socket 99
,V/        ( 2845): QcRouteController
,W/NetworkManagementService( 3522): route cmd failed: 
W/NetworkManagementService( 3522): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '56 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 56 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3522): '
W/NetworkManagementService( 3522): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3522): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3522): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3522): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3522): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3522): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3522): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3522): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3522): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3522): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 3522): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 4469): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 4469): CM callback handler got msg 524295
I/KnoxUsageLogPro(11305): isEulaShown : false
I/KnoxUsageLogPro(11305): KnoxUsageReceiver onReceive : not Processible, just return
I/ActivityManager( 3522): Killing 10399:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
D/KeyguardWallpaperUpdator(10702): cancelUpdateWallpaper
D/KeyguardWallpaperUpdator(10702): cancelUpdateCategory
D/KeyguardWallpaperUpdator(10702): stopCheckCategoryVersion
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11322): MountEmulatedStorage()
E/Zygote  (11322): v2
I/libpersona(11322): KNOX_SDCARD checking this for 10136
I/libpersona(11322): KNOX_SDCARD not a persona
,I/SELinux (11322): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11322): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11322): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=11322 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3522): Killing 10418:com.android.calendar/u0a164 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11322): TimaSignature is unavailable
,D/ActivityThread(11322): Added TimaKeyStore provider
,D/ResourcesManager(11322): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/WifiStateMachine( 3522): REQUEST_POWER_SAVE_ON
,I/PhenotypeConfigurator( 4245): Scheduling Phenotype for one-off execution 6387 seconds from now (1453857050675)
,E/WifiStateMachine( 3522): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/GetConfigurationSnapshotOperation( 4245): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/System.out( 4245): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4245): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4245): Tagging socket 84 with tag 1000060200000000{268436994,0} uid 10014, pid: 4245, getuid(): 10014
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11322): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11322): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11322): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11322): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/qtaguid ( 4245): Tagging socket 92 with tag 1000060200000000{268436994,0} uid 10014, pid: 4245, getuid(): 10014
,I/PhenotypeFlagCommitter( 4245): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 4245): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 3522): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/SA      (11260): [RC New] Execute method=[GET] start
,I/WebViewFactory(11322): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11322): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11322): Loading: webviewchromium
,I/LibraryLoader(11322): Time to load native libraries: 3 ms (timestamps 6353-6356)
I/LibraryLoader(11322): Expected native library version number "",actual native library version number ""
,I/SA      (11260): [RC New] Security=[true]
,I/System.out(11260): Thread-1525(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
V/WebViewChromiumFactoryProvider(11322): Binding Chromium to main looper Looper (main, tid 1) {f910f89}
I/System.out(11260): Thread-1525(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11260): Thread-1525(ApacheHTTPLog):isShipBuild true
I/System.out(11260): Thread-1525(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10045
I/LibraryLoader(11322): Expected native library version number "",actual native library version number ""
,I/chromium(11322): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/BrowserStartupController(11322): Initializing chromium process, renderers=0
,W/art     (11322): Attempt to remove local handle scope entry from IRT, ignoring
,E/Zygote  (11369): MountEmulatedStorage()
E/Zygote  (11369): v2
I/libpersona(11369): KNOX_SDCARD checking this for 10122
I/libpersona(11369): KNOX_SDCARD not a persona
,I/SELinux (11369): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=11369 uid=10122 gids={50122, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11369): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11369): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/AudioManagerAndroid(11322): Requires BLUETOOTH permission
,W/chromium(11322): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/System.out( 4245): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 4245): Tagging socket 56 with tag 1000040100000000{268436481,0} uid 10014, pid: 4245, getuid(): 10014
I/chromium(11322): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(11322): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,D/TimaKeyStoreProvider(11369): TimaSignature is unavailable
,D/ActivityThread(11369): Added TimaKeyStore provider
,D/ResourcesManager(11369): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/NSApplication(11322): Starting up...
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  (10900): wlan0: sending IPv6 Router Solicitation
,E/Zygote  (11414): MountEmulatedStorage()
,E/Zygote  (11414): v2
I/libpersona(11414): KNOX_SDCARD checking this for 10147
I/libpersona(11414): KNOX_SDCARD not a persona
,I/SELinux (11414): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=11414 uid=10147 gids={50147, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11414): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11414): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Killing 9760:com.android.defcontainer/u0a5 (adj 15): bgCount ##31
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8743(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 864us total 21.191ms
,D/TimaKeyStoreProvider(11414): TimaSignature is unavailable
,D/ActivityThread(11414): Added TimaKeyStore provider
,I/qtaguid ( 4245): Untagging socket 84
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 796us total 18.054ms
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 615us total 17.183ms
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 49036(2MB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 48MB/64MB, paused 1.847ms total 145.174ms
,I/SurfaceFlinger( 2850): id=13 Removed Uoast (8/9)
,I/SurfaceFlinger( 2850): id=13 Removed Uoast (-2/9)
W/ActivityManager( 3522): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/PowerManagerService( 3522): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3522) eventTime = 136632
,D/PowerManagerService( 3522): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3522 (0x0)
,D/PowerManagerService( 3522): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3522, ws=WorkSource{10060}) (elapsedTime=3616)
,D/ActivityThread(11369): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,W/ActivityManager( 3522): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/OpenGLRenderer( 5899): Render dirty regions requested: true
,D/ResourcesManager(11414): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager(11414): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/SurfaceFlinger( 2850): id=14 createSurf (1x1),1 flag=4, Uoast
,I/System.out( 4245): (HTTPLog)-Static: isSBSettingEnabled false
,D/PowerManagerService( 3522): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3522
,I/Gmail   (11369): getAccountsCursor
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,I/GCoreUlr( 4245): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/OpenGLRenderer( 5899): Initialized EGL, version 1.4
,I/GCoreUlr( 4245): DispatchingService.onCreate()
,W/GAV2    (11369): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/OpenGLRenderer( 5899): HWUI protection enabled for context ,  &this =0xaf722088 ,&mEglDisplay = 1 , &mEglConfig = -1351229168 
,D/OpenGLRenderer( 5899): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer( 5899): Enabling debug mode 0
,D/mali_winsys( 5899): new_window_surface returns 0x3000,  [616x201]-format:1
I/System.out( 4245): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 4245): Tagging socket 81 with tag 1000120100000000{268440065,0} uid -1, pid: 4245, getuid(): 10014
,W/ActivityManager( 3522): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager( 3522): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 3522): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   (11369): Observing account changes for notifications
,W/ActivityManager( 3522): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/qtaguid ( 4245): Tagging socket 97 with tag 1000120100000000{268440065,0} uid -1, pid: 4245, getuid(): 10014
,I/GCoreUlr( 4245): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/ActivityManager( 3522): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/GCoreUlr( 4245): Unbound from all location providers
I/GCoreUlr( 4245): Place inference reporting - stopped
,E/Gmail   (11369): Error finding the version of the Email provider.....
E/Gmail   (11369): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   (11369): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
E/Gmail   (11369): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   (11369): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   (11369): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   (11369): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   (11369): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   (11369): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration(11369): We do not support migrating this version of the Email provider.
,W/Gmail   (11369): Sync started for account: account:61035162
,I/Gmail   (11369): getAccountsCursor
,I/GCoreUlr( 4245): DispatchingService.onDestroy()
I/GCoreUlr( 4245): Stopping handler for UlrDispSvcFast
,E/SQLiteLog(11369): (283) recovered 32 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/GCoreUlr( 4245): Unbound from all location providers
I/GCoreUlr( 4245): Place inference reporting - stopped
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   (11369): notifyAccountChanged
,I/Gmail   (11369): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   (11369): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   (11369): notifyAccountChanged
,I/Gmail   (11369): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   (11369): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/art     ( 4245): Explicit concurrent mark sweep GC freed 102032(5MB) AllocSpace objects, 37(1479KB) LOS objects, 34% free, 29MB/45MB, paused 902us total 49.232ms
,D/ResourcesManager( 4469): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   (11369): getAccountsCursor
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   (11369): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 15715, normalSync: true
,D/LocationManagerService( 3522): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/Gmail   (11369): getAccountsCursor
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 4245): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4245): Tagging socket 81 with tag 1000120100000000{268440065,0} uid -1, pid: 4245, getuid(): 10014
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11488): MountEmulatedStorage()
E/Zygote  (11488): v2
I/libpersona(11488): KNOX_SDCARD checking this for 10150
I/libpersona(11488): KNOX_SDCARD not a persona
,I/SELinux (11488): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11488): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=11488 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux (11488): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SA      (11260): [RC New] [v2liruge] api execute + 638
I/SA      (11260): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11260): AsyncTask #1 calls detatch()
,I/SA      (11260): [TPMU] getNetworkMcc : 
,D/TimaKeyStoreProvider(11488): TimaSignature is unavailable
,I/SA      (11260): [SCU] saveMccToPreferece Start
I/SA      (11260): [SCU] RegionMCC : 260
D/ActivityThread(11488): Added TimaKeyStore provider
I/SA      (11260): [SSP] query invoked
,I/SA      (11260): [TPMU] GetMccFromDB : null
I/SA      (11260): [SCU] getMccFromPreferece mcc = 260
I/SA      (11260): [SCU] saveMccToPreferece End
,I/SA      (11260): [RC New] executeRequest [v2liruge] end. 682
I/SA      (11260): [RC New] Execute end
,I/SA      (11260): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11260): [OR] GetMyCountryZoneTask Success
,D/ResourcesManager(11488): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(11488): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11488): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(11488): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(11369): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11369): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11369): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/QuickConnect(11488): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(11488): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(11488): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,V/JNIHelp (11369): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/LocationManagerService( 3522): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ActivityManager( 3522): Killing 9327:com.android.vending/u0a31 (adj 13): bgCount ##31
,I/System.out( 4245): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 4245): Tagging socket 81 with tag 1000120100000000{268440065,0} uid -1, pid: 4245, getuid(): 10014
,W/ActivityThread(11369): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11369): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2ff0fa52: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11369): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/iu.SyncManager( 4469): SYNC; picasa accounts
,D/LocationManagerService( 3522): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/btif_config_util(10686): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/NetworkLogImpl( 4469): Loaded NetworkSpeedPredictor
,I/iu.Environment( 4469): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 4469): num queued entries: 0
,I/iu.UploadsManager( 4469): num updated entries: 0
,I/iu.SyncManager( 4469): NEXT; no task
,W/art     (11414): Attempt to remove local handle scope entry from IRT, ignoring
,I/System.out( 4245): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4245): Tagging socket 81 with tag 1000120100000000{268440065,0} uid -1, pid: 4245, getuid(): 10014
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,E/Zygote  (11513): MountEmulatedStorage()
E/Zygote  (11513): v2
I/libpersona(11513): KNOX_SDCARD checking this for 10013
I/libpersona(11513): KNOX_SDCARD not a persona
,I/SELinux (11513): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11513): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=11513 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux (11513): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11513): TimaSignature is unavailable
,D/ActivityThread(11513): Added TimaKeyStore provider
,D/LocationManagerService( 3522): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10147
,I/System.out(11369): Thread-1561(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11369): Thread-1561(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out(11369): Thread-1561(ApacheHTTPLog):isShipBuild true
I/System.out(11369): Thread-1561(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/ResourcesManager(11513): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10122
,I/qtaguid (11369): Tagging socket 59 with tag 1010000000000000{269484032,0} uid -1, pid: 11369, getuid(): 10122
,I/System.out( 4245): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4245): Tagging socket 81 with tag 1000120100000000{268440065,0} uid -1, pid: 4245, getuid(): 10014
,I/qtaguid (11369): Tagging socket 63 with tag 1010000000000000{269484032,0} uid -1, pid: 11369, getuid(): 10122
,D/WaitQueueForNetworkActivate(11513): notifyNetworkActivated
,D/ResourcesManager( 4245): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,W/ContextImpl(11513): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3522): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/GCM     ( 4245): GCM config loaded
,I/GCM     ( 4245): Ack for not saved message 44
,D/LocationManagerService( 3522): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/hcjo    (11513): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(11513): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(11513): exit::IDLE
D/InitializeManagerStateMachine(11513): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(11513): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(11513): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(11513): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11513): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(11513): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11513): entry::SUCCESS
D/hcjo    (11513): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (11513): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,I/FOTA_Client(11162): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/splitIntent( 3522): Split this intent : android.intent.action.TIME_SET !!   mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=17 divideNum= 5 r.nextReceiver= 1 receivers.size=23
I/splitIntent( 3522): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,D/hcjo    (11513): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (11513): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/InitializeManagerStateMachine(11513): exit::SUCCESS
D/InitializeManagerStateMachine(11513): entry::IDLE
,E/Zygote  (11546): MountEmulatedStorage()
I/libpersona(11546): KNOX_SDCARD checking this for 10052
E/Zygote  (11546): v2
I/libpersona(11546): KNOX_SDCARD not a persona
,I/SELinux (11546): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11546): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=11546 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/SELinux (11546): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11556): MountEmulatedStorage()
,E/Zygote  (11556): v2
I/libpersona(11556): KNOX_SDCARD checking this for 10164
I/libpersona(11556): KNOX_SDCARD not a persona
,I/SELinux (11556): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11556): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=11556 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/SELinux (11556): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11546): TimaSignature is unavailable
,D/ActivityThread(11546): Added TimaKeyStore provider
,I/System.out( 4245): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4245): Tagging socket 81 with tag 1000120100000000{268440065,0} uid -1, pid: 4245, getuid(): 10014
,I/FOTA_Client(11162): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,D/daemonapp( 3778): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 3778): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/TimaKeyStoreProvider(11556): TimaSignature is unavailable
,D/ActivityThread(11556): Added TimaKeyStore provider
,I/KLMS-2.4.521: (11180): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Wed Jan 27 02:10:52 GMT+01:00 2016
D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ResourcesManager(11546): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,W/ResourcesManager(11546): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(11546): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11546): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(11546): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11546): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(11546): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/daemonapp( 3778): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,I/KLMS-2.4.521: (11180): KLMSAbstractReciever(): onReceive().END.
D/comsamsunglog( 3778): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3778): [MSC_Daemon]>>> daemonapp [Version : 15022501 ] [ 3 ] 
D/comsamsunglog( 3778): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3778): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 3778): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(11556): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,I/KLMS-2.4.521: (11180): KLMSIntentService(): onCreate()
D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
W/ResourcesManager(11556): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11556): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11556): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11556): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
I/KLMS-2.4.521: (11180): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/daemonapp( 3778): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,I/KLMS-2.4.521: (11180): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11180): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,I/KLMS-2.4.521: (11180): KLMSIntentService(): TIME_CHANGED
,D/PackageManager( 3522): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/daemonapp( 3778): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 3778): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,E/Zygote  (11578): MountEmulatedStorage()
E/Zygote  (11578): v2
I/libpersona(11578): KNOX_SDCARD checking this for 10036
D/daemonapp( 3778): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
I/libpersona(11578): KNOX_SDCARD not a persona
,I/SELinux (11578): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11578): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11578): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/com.cigna.mobile.coach.CoachBroadcastReceiver: pid=11578 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/KLMS-2.4.521: (11180): StateImplV2(): dateTimeChanged().START : Wed Jan 27 02:10:52 GMT+01:00 2016
,D/TimaKeyStoreProvider(11578): TimaSignature is unavailable
E/daemonapp( 3778): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/ActivityThread(11578): Added TimaKeyStore provider
,D/comdaemonstockapp( 3778): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
D/comdaemonstockapp( 3778): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,I/KLMS-2.4.521: (11180): StateImplV2(): dateTimeChanged().END
,D/Mms/MmsApp(11546): [start]    onCreate() consume time = 0.0
,D/Mms/ArtClassLoader(11546): init before art
,I/KLMS-2.4.521: (11180): KLMSIntentService(): onDestroy()
D/Mms/ArtClassLoader(11546): init [DONE] art
,D/LocationManagerService( 3522): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/Mms/TelephonyPermission(11546): start operation mode monitor
,I/ActivityManager( 3522): Killing 10819:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,D/ResourcesManager(11578): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(11546): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ResourcesManager(11546): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/TelephonyPermission(11546): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(11546): isDefault true
,D/Mms/MmsApp(11546): onCreate() com.android.mms
,I/System.out( 4245): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4245): Tagging socket 81 with tag 1000120100000000{268440065,0} uid -1, pid: 4245, getuid(): 10014
,D/Mms/MmsApp(11546): [start]    initCountryIso consume time = 43.603333
,D/CountryDetector( 3522): The first listener is added
,D/Mms/MmsApp(11546): [end]    initCountryIso consume time = 13.440667
D/Mms/MmsConfig(11546): [start]    MmsConfig.init() consume time = 0.081833
,D/SecurityLogAgent(10723): KnoxConfiguration : Current State = 0
,D/SecurityLogAgent(10723): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent(10723): StateMachine : Initialized
,D/SecurityLogAgent(10723): StateMachine : Changed Current State = 0
I/CheckinService( 4469): Checkin interval check for package: unspecified last checkin: 1453758514713 min interval config: 0 actual interval: 98537515
,D/SecurityLogAgent(10723): StateMachine : Current State = 0
D/Mms/MmsConfig(11546): before partial update
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/Mms/MmsConfig(11546): Load Resize quality : 80
,D/Mms/MmsConfig(11546):  enable multiwindow = true
,E/Mms/MessageUtils(11546): setCountryDetector : update country detector info 
E/Mms/MessageUtils(11546): updateCountryIso : update country iso info 
,D/Mms/PackageInfo(11546): com.sec.imsservice is not installed
D/Mms/MmsConfig(11546): [end]    init() consume time = 39.068042
,D/Mms/Contact(11546): [start]    init() consume time = 0.803833
,E/Zygote  (11606): MountEmulatedStorage()
,E/Zygote  (11606): v2
I/libpersona(11606): KNOX_SDCARD checking this for 10191
I/libpersona(11606): KNOX_SDCARD not a persona
,I/SELinux (11606): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=11606 uid=10191 gids={50191, 9997} abi=armeabi-v7a
,I/SELinux (11606): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11606): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Mms/Contact(11546): [end]    init consume time = 15.334625
,D/Mms/DraftCache(11546): [start]    rebuildCache consume time = 3.540709
,D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/TP/MmsSmsProvider( 3983): query,matched:13, calling pid = 11546
,D/TP/MmsSmsProvider( 3983): match 13:Elapsed time : 8.681 ms
,D/SHealthUpgrade(SHealthUpgradeUtil)(11578): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)(11578): checkState() : APP TYPE = Full
,D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/TimaKeyStoreProvider(11606): TimaSignature is unavailable
D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthServiceInstalled() : HealthService is Installed.
,D/ActivityThread(11606): Added TimaKeyStore provider
,D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
D/TP/MmsSmsProvider( 3983): query,matched:12, calling pid = 11546
,D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/TP/MmsSmsProvider( 3983): match 12:Elapsed time : 2.211 ms
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/Mms/TelephonyUtils(11546): getSubId from simSlot 0, return Value = -1
,D/Mms/DownloadManager(11546): roaming -> false (slotId = 0)
I/libpersona(11629): KNOX_SDCARD checking this for 10019
D/Mms/DownloadManager(11546): [NotificationTransaction] getAutoDownloadState simSlot : 0
I/libpersona(11629): KNOX_SDCARD not a persona
D/Mms/DownloadManager(11546): auto download without roaming -> true
I/ActivityManager( 3522): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=11629 uid=10019 gids={50019, 9997} abi=armeabi-v7a
D/Mms/DownloadManager(11546): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
E/Zygote  (11629): MountEmulatedStorage()
E/Zygote  (11629): v2
I/SELinux (11629): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11629): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11629): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Mms/TelephonyUtils(11546): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils(11546): getSubId from simSlot 1, return Value = 9223372036854775807
D/Mms/DownloadManager(11546): roaming -> false (slotId = 1)
D/Mms/DownloadManager(11546): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager(11546): auto download without roaming -> true
D/Mms/DownloadManager(11546): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager(11546): auto download during roaming secondary -> false
D/Mms/DownloadManager(11546): mAutoDownload ------> true
,D/Mms/Conversation(11546): [start]    init() consume time = 77.327833
,D/Mms/MmsApp(11546): [end]    onCreate() consume time = 0.27375
,D/TP/MmsSmsProvider( 3983): deleteConversation threadId: 9223372036854775807
,D/Mms/DownloadManager(11546): Service state changed: Bundle[mParcelledData.dataSize=692]
,D/Mms/DownloadManager(11546): roaming ------> false, mSimSlot = 0
,D/TP/MmsSmsProvider( 3983): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
,D/Mms/TelephonyUtils(11546): getSubId from simSlot 0, return Value = -1
,D/Mms/DownloadManager(11546): roaming -> false (slotId = 0)
D/Mms/DownloadManager(11546): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(11546): auto download without roaming -> true
D/Mms/DownloadManager(11546): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager(11546): mAutoDownload ------> true
,D/TimaKeyStoreProvider(11629): TimaSignature is unavailable
,D/ActivityThread(11629): Added TimaKeyStore provider
,E/SQLiteLog( 3983): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 3983): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3983): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3983): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3983): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3983): (284) automatic index on im_threads(normal_thread_id)
,D/TP/MmsSmsProvider( 3983): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 3983): need read changed broadcast:false
,D/Mms/Conversation(11546): [end]    init consume time = 23.033958
D/Mms/MessagingNotification(11546): [start]    init() consume time = 0.09525
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 26023(1470KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 48MB/64MB, paused 1.565ms total 141.490ms
,D/ResourcesManager(11606): creating new AssetManager and set to /system/app/TaskManager/TaskManager.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager(11606): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager(11629): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,E/Zygote  (11646): MountEmulatedStorage()
,E/Zygote  (11646): v2
I/libpersona(11646): KNOX_SDCARD checking this for 10069
I/libpersona(11646): KNOX_SDCARD not a persona
,I/SELinux (11646): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=11646 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11646): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027,
E/SELinux (11646): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Mms/DraftCache(11546): [end]    rebuildCache consume time = 142.37325
,D/Mms/MessagingNotification(11546): [end]    init consume time = 6.812084
,I/ActivityManager( 3522): Killing 10046:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11646): TimaSignature is unavailable
,D/ActivityThread(11646): Added TimaKeyStore provider
,D/SHealthUpgrade(SHealthUpgradeUtil)(11578): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/TP/MmsSmsProvider( 3983): query,matched:0, calling pid = 11546
D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthServiceInstalled() : HealthService is Installed.
,V/TP/MmsSmsProvider( 3983): getSimpleConversations entered.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
D/TP/MmsSmsProvider( 3983): match 0:Elapsed time : 1.835 ms
,D/Mms/Synchronizer(11546): [start]    doSync consume time = 25.369833
,D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/Mms/SpamFilter(11546): [start]    SpamFilter fill() begin consume time = 2.943375
,D/TP/MmsSmsProvider( 3983): update uri: content://mms-sms/db_synchronization
V/TP/MmsSmsProvider( 3983): syncDBData start
,D/com.sec.android.service.health.keyManager.KeyManager(11578): Current encrypted state : -1
,I/SecSQLiteOpenHelper(11578): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(11578): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11578): Open platform.db in secure mode
V/TP/MmsSmsProvider( 3983): syncDBData sms end
D/SecSQLiteDatabase(11578): Android Version: 5.0.1
D/SecSQLiteDatabase(11578): Load library secsqlite.so for Android 5.0.1
,V/TP/MmsSmsProvider( 3983): syncDBData mms end
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/TP/MmsSmsProvider( 3983): query,matched:400, calling pid = 11546
V/TP/MmsSmsProvider( 3983): syncDBData end
,I/SecSQLiteDatabase(11578): openSecureDatabase...
,D/ResourcesManager(11646): creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
,I/SecSQLiteDatabase(11578): private openSecureDatabase...
I/SecSQLiteConnectionPool(11578): OpenSecure
I/SecSQLiteConnectionPool(11578): OpenSecure with password
I/SecSQLiteConnectionPool(11578): openSecureConnectionLocked
,I/SecSQLiteDatabase(11578): ...private openSecureDatabase
I/SecSQLiteDatabase(11578): ...openSecureDatabase
,E/Zygote  (11663): MountEmulatedStorage()
E/Zygote  (11663): v2
I/libpersona(11663): KNOX_SDCARD checking this for 10082
I/libpersona(11663): KNOX_SDCARD not a persona
,I/SELinux (11663): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11663): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11663): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=11663 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/Mms/Synchronizer(11546): [end]    doSync consume time = 33.723375
,I/ActivityManager( 3522): Killing 10381:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,I/ActivityManager( 3522): Killing 10882:com.samsung.android.app.FileShareServer/u0a79 (adj 13): bgCount ##31
,D/Mms/SpamFilter(11546): [end]    SpamFilter fill() finished consume time = 13.877958
,D/TimaKeyStoreProvider(11663): TimaSignature is unavailable
,D/ActivityThread(11663): Added TimaKeyStore provider
,E/SQLiteLog(11578): (26) statement aborts at 0: [PRAGMA user_version;] file is encrypted or is not a database
,E/SecDefaultDatabaseErrorHandler(11578): Corruption reported by sqlite on database: /data/data/com.sec.android.app.shealth/databases/platform.db
E/SecDefaultDatabaseErrorHandler(11578): backup the database file: /data/data/com.sec.android.app.shealth/databases/platform.db
D/SecSQLiteOpenHelper(11578): ...getDatabaseLocked(b,b,pwd)
,I/ActivityManager( 3522): Killing 7824:com.android.settings/1000 (adj 13): bgCount ##31
,D/ResourcesManager(11663): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/BadgeProvider(11663): onCreate
D/BadgeProvider(11663): DatabaseHelper
,D/WifiService( 3522): Client connection lost with reason: 4
,I/ActivityManager( 3522): Killing 8274:com.samsung.android.snote/u0a160 (adj 13): bgCount ##31
,D/accuweather( 5157): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,I/SecureStorage(11629): [INFO]: SPID(0x00000000)Processing data
,D/accuweather( 5157): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/ Time Manager (11646): Time Difference not stored. TIME_DIFFERENCE
,I/SecureStorage( 2902): [INFO]: SPID(0x00000005)Credentials: uid 10019, gid 10019, pid 11629
I/SecureStorage( 2902): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11681): MountEmulatedStorage()
E/Zygote  (11681): v2
I/libpersona(11681): KNOX_SDCARD checking this for 10094
I/libpersona(11681): KNOX_SDCARD not a persona
,I/SELinux (11681): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11681): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=11681 uid=10094 gids={50094, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11681): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Mms/MessagingNotification(11546): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 3983): query,matched:26, calling pid = 11546
,D/TP/SmsProvider( 3983): match 26:Elapsed time : 1.486 ms
,D/TimaKeyStoreProvider(11681): TimaSignature is unavailable
,D/ActivityThread(11681): Added TimaKeyStore provider
,D/TP/MmsSmsProvider( 3983): query,matched:6, calling pid = 11546
,D/TP/MmsSmsProvider( 3983): match 6:Elapsed time : 1.457 ms
,I/Mms/ReservationManager(11546): ReservationManager()
,I/Mms/ReservationManager(11546): resetAfterConnected()
,D/TP/MmsSmsProvider( 3983): query,matched:7, calling pid = 11546
,D/ResourcesManager(11681): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/TP/MmsSmsProvider( 3983): match 7:Elapsed time : 2.648 ms
,W/ResourcesManager(11681): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(11681): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11681): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11681): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11681): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11681): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/Mms/ReservationManager(11546): getReservedSendMessageCount(): retMessageCount=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11697): MountEmulatedStorage()
I/libpersona(11697): KNOX_SDCARD checking this for 10028
E/Zygote  (11697): v2
I/libpersona(11697): KNOX_SDCARD not a persona
,I/SELinux (11697): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11697): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=11697 uid=10028 gids={50028, 9997} abi=armeabi-v7a
,E/SELinux (11697): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8723(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 727us total 13.477ms
,D/TimaKeyStoreProvider(11697): TimaSignature is unavailable
,D/ActivityThread(11697): Added TimaKeyStore provider
,I/ActivityManager( 3522): Killing 10304:com.facebook.appmanager/u0a110 (adj 13): bgCount ##31
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 646us total 11.827ms
,D/ResourcesManager(11697): creating new AssetManager and set to /system/priv-app/OmaCP/OmaCP.apk
,W/ResourcesManager(11697): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 434us total 11.540ms
,D/SettingsProvider( 3522): name = next_alarm_formatted
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 10094
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
,I/OMACP   (11697): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/Mms/Omacp(11546): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,I/qtaguid (11369): Untagging socket 59
I/System.out(11369): SyncAdapterThread-1 calls detatch()
,D/Mms/PerformanceUtils(11546): link cahcing start
,D/Mms/ArtClassLoader(11546): init before art
D/Mms/ArtClassLoader(11546): init [DONE] art
,E/AclDataUtils(11414): Circle ID not found for type: 9
,I/OMACP   (11697): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   (11697): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   (11697): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   (11697): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   (11697): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   (11697): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   (11697): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   (11697): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/OMACP   (11697): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   (11697): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   (11697): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   (11697): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   (11697): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,D/Mms/PerformanceUtils(11546): link cahcing done
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11714): MountEmulatedStorage()
,E/Zygote  (11714): v2
I/libpersona(11714): KNOX_SDCARD checking this for 10106
I/libpersona(11714): KNOX_SDCARD not a persona
,I/SELinux (11714): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=11714 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
I/SELinux (11714): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11714): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Killing 10968:com.sec.pcw.device/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11714): TimaSignature is unavailable
,D/ActivityThread(11714): Added TimaKeyStore provider
,D/ResourcesManager(11714): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/elm:14491(11714): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14491(11714): ELMEngine.ELMEngine( context ).
D/elm:14491(11714): MDMBridge.setEnterpriseBridge()
,D/elm:14491(11714): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/elm:14491(11714): ElmAgentService : onCreate()
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/elm:14491(11714): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/elm:14491(11714): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:14491(11714): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14491(11714): ModuleBase.ModifySetAlarm()
D/elm:14491(11714): MDMBridge.getInstance()
D/elm:14491(11714): MDMBridge.getAllLicenseInfoFromSDK()
,I/art     (10220): Explicit concurrent mark sweep GC freed 2698(111KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 27MB/35MB, paused 877us total 27.994ms
,E/Zygote  (11732): MountEmulatedStorage()
,E/Zygote  (11732): v2
I/libpersona(11732): KNOX_SDCARD checking this for 10163
I/ActivityManager( 3522): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=11732 uid=10163 gids={50163, 9997} abi=armeabi-v7a
I/libpersona(11732): KNOX_SDCARD not a persona
I/SELinux (11732): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11732): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/GoogleHttpClient(10220): GMS http client unavailable, use old client
,E/SELinux (11732): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/elm:14491(11714): ElmAgentService : onDestroy().
,D/TimaKeyStoreProvider(11732): TimaSignature is unavailable
,D/ActivityThread(11732): Added TimaKeyStore provider
,D/ResourcesManager(11732): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG_Transparent/SPlannerWidget_OS_UPG_Transparent.apk
,W/ResourcesManager(11732): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(11732): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/ActivityManager( 3522): Killing 10998:com.google.android.music:main/u0a135 (adj 13): bgCount ##31
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(10220): Thread-1380(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(10220): Thread-1380(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(10220): Thread-1380(ApacheHTTPLog):isShipBuild true
I/System.out(10220): Thread-1380(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,I/qtaguid (10220): Tagging socket 34 with tag 1244000400000000{306446340,0} uid -1, pid: 10220, getuid(): 10014
,V/AlarmManager( 3522): waitForAlarm result :4
,I/art     (11369): Explicit concurrent mark sweep GC freed 162050(6MB) AllocSpace objects, 12(215KB) LOS objects, 21% free, 29MB/37MB, paused 3.741ms total 58.722ms
,I/Gmail   (11369): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 15770, normalSync: true
,I/Gmail   (11369): lowestBackward conversation id 0
,I/Gmail   (11369): notifyAccountChanged
,I/Gmail   (11369): getAccountsCursor
,I/Gmail   (11369): notifyAccountChanged
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Gmail   (11369): Sync complete for account: account:61035162
,I/Gmail   (11369): getAccountsCursor
,I/ActivityManager( 3522): Killing 11096:com.sec.android.cloudagent/u0a2 (adj 13): bgCount ##31
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SecureStorage( 2902): [INFO]: SPID(0x00000006)Secure Storage Daemon finished processing with result: 0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11759): MountEmulatedStorage()
E/Zygote  (11759): v2
I/libpersona(11759): KNOX_SDCARD checking this for 10101
I/libpersona(11759): KNOX_SDCARD not a persona
,I/SELinux (11759): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11759): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=11759 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (11759): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11759): TimaSignature is unavailable
,D/ActivityThread(11759): Added TimaKeyStore provider
,D/ResourcesManager(11759): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/qtaguid (10220): Tagging socket 38 with tag 1244000400000000{306446340,0} uid -1, pid: 10220, getuid(): 10014
,D/DocsApplication(11759): Installing DEX configuration.
,D/DexInstaller(11759): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper(11759): Provided clientMode=RELEASE, packageInfo=PackageInfo{36f7fb8 com.google.android.apps.docs}
,D/TAG     (11759): onCreate()
,D/CrossAppStateProvider(11759): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,I/SecureStorage(11629): [INFO]: SPID(0x00000006)Processing data has been completed
,I/SecureStorage(11629): [INFO]: SPID(0x00000006)Skip using SecureStorageExceptionJNI
,I/SecSQLiteOpenHelper(11578): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(11578): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11578): Open platform.db in secure mode
I/SecSQLiteDatabase(11578): openSecureDatabase...
I/SecSQLiteDatabase(11578): private openSecureDatabase...
I/SecSQLiteConnectionPool(11578): OpenSecure
I/SecSQLiteConnectionPool(11578): OpenSecure with password
I/SecSQLiteConnectionPool(11578): openSecureConnectionLocked
I/SecSQLiteDatabase(11578): ...private openSecureDatabase
I/SecSQLiteDatabase(11578): ...openSecureDatabase
,I/SecSQLiteOpenHelper(11578): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper(11578): ...getDatabaseLocked(b,b,pwd)
,D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/-----SIC-----(11578): ------------------skip TGH
,I/qtaguid (10220): Untagging socket 34
,I/System.out(10220): GDataFeedFetcher calls detatch()
,I/SecSQLiteOpenHelper(11578): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(11578): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(11578): Open platform.db in secure mode
I/SecSQLiteDatabase(11578): openSecureDatabase...
I/SecSQLiteDatabase(11578): private openSecureDatabase...
I/SecSQLiteConnectionPool(11578): OpenSecure
I/SecSQLiteConnectionPool(11578): OpenSecure with password
I/SecSQLiteConnectionPool(11578): openSecureConnectionLocked
I/SecSQLiteDatabase(11578): ...private openSecureDatabase
I/SecSQLiteDatabase(11578): ...openSecureDatabase
,I/SecSQLiteOpenHelper(11578): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper(11578): ...getDatabaseLocked(b,b,pwd)
,D/Mms/Contact(11546): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/Contact(11546): performUpdate:widgetCount=0
,D/Mms/ContactsCache(11546): [start]    invalidate() consume time = 1101.851792
D/Mms/ContactsCache(11546): [end]    invalidate() consume time = 0.149584
,I/qtaguid (10220): Tagging socket 34 with tag 1144000400000000{289669124,0} uid -1, pid: 10220, getuid(): 10014
,D/ContactProvider(11035): getAllContactInfoList Start
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11578): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11578): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,V/MediaPlayer(11578): decode(37, 20909908, 4230)
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
V/AudioCache( 2858): notify(0xaea1b790, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
,I/SO_AGENT(11196): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,V/AwesomePlayer( 2858): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2858): mBitrate = -1 bits/sec
I/OggExtractor( 2858): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2858): current audio track index (0) is added to vector
V/AwesomePlayer( 2858): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2858): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2858): prepare
V/AwesomePlayer( 2858): prepareAsync
,V/MediaPlayerService( 2858): wait for prepare
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
,I/SA      (11260): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/ContactProvider(11035): getAllContactInfoList End
,I/syncContacts(11035): thread: 1483, onChange
,I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 1, 0, 0)
V/AudioCache( 2858): prepared
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
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2858): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/MediaPlayerService( 2858): wait for playback complete
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
,V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 8, 0, 0)
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
,V/MediaPlayer(11578): decode(36, 20763080, 15440)
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
V/StagefrightPlayer( 2858): setDataSource(26, 20763080, 15440)
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 8, 0, 0)
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
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache( 2858): notify(0xae9204c0, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 1, 0, 0)
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
,V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
,I/qtaguid (10220): Untagging socket 34
,I/System.out(10220): GDataFeedFetcher calls detatch()
,V/MediaPlayerService( 2858): wait for playback complete
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/ActivityManager( 3522): Killing 11035:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthServiceInstalled() : HealthService is Installed.
,D/AdaptiveEventManager( 3693): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 3693): M updateContainers()
D/AdaptiveEventContainerSmall( 3693): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 3693): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 3693): pedoEvent == null
D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
D/AdaptiveEventManager( 3693): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 3693): M updateContainers()
D/AdaptiveEventContainerSmall( 3693): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 3693): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 3693): pedoEvent == null
,V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2858): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2858): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2858): ~OggSource --
I/OggExtractor( 2858): ~OggExtractor ++
I/OggExtractor( 2858): ~MyVorbisExtractor ++ 
I/OggExtractor( 2858): ~MyVorbisExtractor --
I/OggExtractor( 2858): ~OggExtractor --
,D/Mms/Contact(11546): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/ContactsCache(11546): [start]    invalidate() consume time = 116.976666
D/Mms/ContactsCache(11546): [end]    invalidate() consume time = 0.437
,I/AudioPlayer( 2858): reset out
,V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2858): SecVideoCapture destructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): mSecCapture clear
I/SecMediaClock( 2858): SecMediaClock destructor
,V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): ~StagefrightPlayer
W/System.err(11578): java.lang.NumberFormatException: Invalid int: "null"
W/System.err(11578): 	at java.lang.Integer.invalidInt(Integer.java:138)
W/System.err(11578): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err(11578): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err(11578): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:498)
W/System.err(11578): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1242)
W/System.err(11578): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(11578): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(11578): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
I/ActivityManager( 3522): Killing 11116:com.sec.android.diagmonagent/1000 (adj 13): bgCount ##31
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/AwesomePlayer( 2858): destructor
,V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/MediaPlayer(11578): decode(38, 20807608, 9226)
,V/MediaPlayerService( 2858): decode(26, 20807608, 9226)
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
,V/AwesomePlayer( 2858): mSecMediaClock clear
V/StagefrightPlayer( 2858): StagefrightPlayer
V/AwesomePlayer( 2858): setListener
V/StagefrightPlayer( 2858): initCheck
V/AwesomePlayer( 2858): setAudioSink
V/StagefrightPlayer( 2858): setDataSource(26, 20807608, 9226)
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache( 2858): notify(0xb020d150, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
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
I/SecMediaClock( 2858): reset
,I/SecVideoCapture( 2858): SecVideoCapture constructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): initAudioDecoder
V/AwesomePlayer( 2858): checkOffloadExceptions is true
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,E/DatabaseUtils( 3522): Writing exception to parcel
E/DatabaseUtils( 3522): java.lang.NullPointerException: key == null
E/DatabaseUtils( 3522): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils( 3522): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils( 3522): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils( 3522): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:376)
E/DatabaseUtils( 3522): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils( 3522): 	at android.os.Binder.execTransact(Binder.java:446)
V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache( 2858): notify(0xb020d150, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 1, 0, 0)
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
V/AudioCache( 2858): notify(0xb020d150, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
V/MediaPlayerService( 2858): wait for playback complete
,W/System.err( 9946): android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
,W/System.err( 9946): 	at android.provider.Settings$System.getLongForUser(Settings.java:1679)
W/System.err( 9946): 	at android.provider.Settings$System.getLong(Settings.java:1669)
W/System.err( 9946): 	at com.sec.android.sCloudSync.g.d.b(SourceFile:83)
W/System.err( 9946): 	at com.sec.android.sCloudSync.Receivers.TimeChangedReceiver.onReceive(SourceFile:64)
W/System.err( 9946): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
W/System.err( 9946): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
W/System.err( 9946): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
W/System.err( 9946): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 9946): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 9946): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err( 9946): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 9946): 	at java.lang.reflect.Method.invoke(Method.java:372)
I/splitIntent( 3522): Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
W/System.err( 9946): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 9946): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
,V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer(11578): decode(39, 20914220, 4890)
V/MediaPlayerService( 2858): decode(26, 20914220, 4890)
,V/MediaPlayerService( 2858): player type = 3
V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): constructor
V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2858): mAudioTrackVector clear
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
,V/AudioCache( 2858): notify(0xb236c420, 8, 0, 0)
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
,I/AwesomePlayer( 2858): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2858): prepare
V/AwesomePlayer( 2858): prepareAsync
V/MediaPlayerService( 2858): wait for prepare
V/AwesomePlayer( 2858): onPrepareAsyncEvent
I/SecMediaClock( 2858): SecMediaClock constructor
I/SecMediaClock( 2858): reset
,I/SecVideoCapture( 2858): SecVideoCapture constructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): initAudioDecoder
V/AwesomePlayer( 2858): checkOffloadExceptions is true
E/SQLiteLog( 4228): (284) automatic index on sqlite_sq_B3918790(STAT_DATA_ID)
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
,V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache( 2858): notify(0xb236c420, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 1, 0, 0)
V/AudioCache( 2858): prepared
V/AudioCache( 2858): wait - success
V/MediaPlayerService( 2858): start
,V/StagefrightPlayer( 2858): start
V/AwesomePlayer( 2858): play
V/AwesomePlayer( 2858): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2858): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7,
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
E/SQLiteLog( 4228): (284) automatic index on sqlite_sq_B3918970(STAT_DATA_ID)
,I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:1, 1, 0
,I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2858): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache( 2858): notify(0xb236c420, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1287635273, value : -859651136
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1287635273, value : -859651136
V/MediaPlayerService( 2858): wait for playback complete
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 8, 0, 0)
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
,V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
,V/MediaPlayer(11578): decode(34, 20840384, 17329)
V/MediaPlayerService( 2858): decode(26, 20840384, 17329)
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
,V/AwesomePlayer( 2858): setListener
V/StagefrightPlayer( 2858): initCheck
V/AwesomePlayer( 2858): setAudioSink
V/StagefrightPlayer( 2858): setDataSource(26, 20840384, 17329)
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 8, 0, 0)
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
V/AudioCache( 2858): notify(0xaea1b790, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 1, 0, 0)
V/AudioCache( 2858): prepared
V/AudioCache( 2858): wait - success
V/MediaPlayerService( 2858): start
V/StagefrightPlayer( 2858): start
,V/AwesomePlayer( 2858): play
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
V/AudioCache( 2858): notify(0xaea1b790, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/MediaPlayerService( 2858): wait for playback complete
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
,V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
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
,V/MediaPlayer(11578): decode(33, 20740576, 6644)
V/MediaPlayerService( 2858): decode(26, 20740576, 6644)
,V/MediaPlayerService( 2858): player type = 3
V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): constructor
V/AwesomePlayer( 2858): setDefault
,V/AwesomePlayer( 2858): reset_l()
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
V/StagefrightPlayer( 2858): setDataSource(26, 20740576, 6644)
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 8, 0, 0)
,V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
,V/AwesomePlayer( 2858): track of type 'audio/vorbis' does not publish bitrate,
V/AwesomePlayer( 2858): mBitrate = -1 bits/sec
I/OggExtractor( 2858): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2858): current audio track index (0) is added to vector
V/AwesomePlayer( 2858): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2858): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2858): prepare
,V/AwesomePlayer( 2858): prepareAsync
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
,I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 1, 0, 0)
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
,I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:1, 1, 0
,I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2858): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
V/MediaPlayerService( 2858): wait for playback complete
,I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2858): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2858): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2858): ~OggSource --
I/OggExtractor( 2858): ~OggExtractor ++
I/OggExtractor( 2858): ~MyVorbisExtractor ++ 
,I/OggExtractor( 2858): ~MyVorbisExtractor --
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
E/SQLiteLog(10096): (284) automatic index on view_events(_id)
,V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/MediaPlayer(11578): decode(41, 20816916, 23389)
,V/MediaPlayerService( 2858): decode(26, 20816916, 23389)
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
V/StagefrightPlayer( 2858): setDataSource(26, 20816916, 23389)
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 8, 0, 0)
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
,I/SecMediaClock( 2858): reset
I/SecVideoCapture( 2858): SecVideoCapture constructor
I/SecVideoCapture( 2858): reset
,V/AwesomePlayer( 2858): initAudioDecoder
V/AwesomePlayer( 2858): checkOffloadExceptions is true
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
,V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
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
V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 1, 0, 0)
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
V/AudioCache( 2858): notify(0xb020d150, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
V/MediaPlayerService( 2858): wait for playback complete
,I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(11578): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,W/GAV2    (11759): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/com.sec.android.service.health.cp.common.HttpConnectionConstants(11578): RegionGroup for  is null
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
,V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
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
,V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
,V/MediaPlayer(11578): decode(42, 20706272, 8154)
,V/MediaPlayerService( 2858): decode(26, 20706272, 8154)
,V/MediaPlayerService( 2858): player type = 3
V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): constructor
,V/AwesomePlayer( 2858): setDefault
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
,V/StagefrightPlayer( 2858): StagefrightPlayer
V/AwesomePlayer( 2858): setListener
V/StagefrightPlayer( 2858): initCheck
V/AwesomePlayer( 2858): setAudioSink
V/StagefrightPlayer( 2858): setDataSource(26, 20706272, 8154)
,V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
E/SQLiteLog( 4228): (284) automatic index on sqlite_sq_AF29A650(STAT_DATA_ID)
V/AudioCache( 2858): notify(0xb236c420, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
,E/SQLiteLog( 4228): (284) automatic index on sqlite_sq_AF2289C0(STAT_DATA_ID)
,D/BluetoothManager(11578): getConnectedDevices
,D/BluetoothManager(11578): getConnectedDevices
,V/AwesomePlayer( 2858): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 2858): mBitrate = -1 bits/sec
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
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/BluetoothManager(11578): getConnectedDevices
,I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 1, 0, 0)
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
,I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2858): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
,V/AudioCache( 2858): notify(0xb236c420, 6, 0, 0)
,V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
,V/MediaPlayerService( 2858): wait for playback complete
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
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
,V/MediaPlayer(11578): decode(44, 20679752, 4804)
V/MediaPlayerService( 2858): decode(26, 20679752, 4804)
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
V/StagefrightPlayer( 2858): setDataSource(26, 20679752, 4804)
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 8, 0, 0)
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
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/BluetoothManager(11578): getConnectedDevices
,I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/WifiService( 3522): acquireWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@32f44b34}
D/BluetoothManager(11578): getConnectedDevices
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2858): finishAsyncPrepare_l
,V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 200, 973, 0)
V/AudioCache( 2858): ignored
,V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 1, 0, 0)
V/AudioCache( 2858): prepared
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
,I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2858): open(44100, 1, 0x0, 1, 0)
D/BluetoothManager(11578): getConnectedDevices
V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache( 2858): notify(0xaea1b790, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
,V/MediaPlayerService( 2858): wait for playback complete
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
,V/AwesomePlayer( 2858): reset_l()
,V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x84, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer(11578): decode(43, 20649204, 9400)
V/MediaPlayerService( 2858): decode(26, 20649204, 9400)
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
V/StagefrightPlayer( 2858): setDataSource(26, 20649204, 9400)
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 8, 0, 0)
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
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache( 2858): notify(0xae9204c0, 1, 0, 0)
V/AudioCache( 2858): prepared
V/AudioCache( 2858): wait - success
V/MediaPlayerService( 2858): start
V/StagefrightPlayer( 2858): start
V/AwesomePlayer( 2858): play
V/AwesomePlayer( 2858): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2858): startAudioPlayer_l, sendErrorNotification (0)
,V/MediaPlayer(11578): decode(50, 20722624, 4112),
V/MediaPlayerService( 2858): decode(38, 20722624, 4112)
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
V/StagefrightPlayer( 2858): setDataSource(38, 20722624, 4112)
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 8, 0, 0)
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
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 31198(1623KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 48MB/64MB, paused 9.004ms total 169.451ms
,I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
,V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 1, 0, 0)
V/AudioCache( 2858): prepared
V/AudioCache( 2858): wait - success
V/MediaPlayerService( 2858): start
V/StagefrightPlayer( 2858): start
V/AwesomePlayer( 2858): play
V/AwesomePlayer( 2858): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2858): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:1, 1, 0
,I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2858): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2858): open(44100, 1, 0x0, 1, 0)
,E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
,I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1733175209, value : 485677307
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1733175209, value : 485677307
V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
V/AwesomePlayer( 2858): onCheckAudioStatus
,D/CalendarAlarmManager(10096): sys current time:1453857053968
,V/MediaPlayerService( 2858): wait for playback complete
V/MediaPlayerService( 2858): wait for playback complete
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
,D/CalendarAlarmManager(10096): reminder amount:0
,V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
,V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x86, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/ActivityManager( 3522): Killing 11217:com.policydm/1000 (adj 13): bgCount ##31
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
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x85, OMX_CommandStateSet, OMX_StateIdle)
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
,V/MediaPlayer(11578): decode(45, 20857804, 52024)
,V/MediaPlayerService( 2858): decode(26, 20857804, 52024)
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
V/StagefrightPlayer( 2858): setDataSource(26, 20857804, 52024)
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 8, 0, 0)
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
,I/SecMediaClock( 2858): SecMediaClock constructor
,I/SecMediaClock( 2858): reset
I/SecVideoCapture( 2858): SecVideoCapture constructor
,I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): initAudioDecoder
,V/AwesomePlayer( 2858): checkOffloadExceptions is true
V/AudioPolicyManager( 2858): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
,I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/System.out(11759): Thread-1631(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11759): Thread-1631(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11759): Thread-1631(ApacheHTTPLog):isShipBuild true
I/System.out(11759): Thread-1631(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 1, 0, 0)
V/AudioCache( 2858): prepared
V/AudioCache( 2858): wait - success
V/MediaPlayerService( 2858): start
V/StagefrightPlayer( 2858): start
,V/AwesomePlayer( 2858): play
V/AwesomePlayer( 2858): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2858): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2858): open(48000, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
,V/MediaPlayerService( 2858): wait for playback complete
,I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10101
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
,V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x87, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2858): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2858): OggSource::~OggSource() mExtractor !mStarted ref count = 1
,I/OggExtractor( 2858): ~OggSource --
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
,V/MediaPlayer(11578): decode(46, 20722624, 4112)
,V/MediaPlayerService( 2858): decode(26, 20722624, 4112)
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
V/StagefrightPlayer( 2858): setDataSource(26, 20722624, 4112)
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 8, 0, 0)
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
,V/MediaPlayerService( 2858): wait for prepare
V/AwesomePlayer( 2858): onPrepareAsyncEvent
I/SecMediaClock( 2858): SecMediaClock constructor
I/SecMediaClock( 2858): reset
,I/SecVideoCapture( 2858): SecVideoCapture constructor
I/SecVideoCapture( 2858): reset
V/AwesomePlayer( 2858): initAudioDecoder
V/AwesomePlayer( 2858): checkOffloadExceptions is true
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2858): finishAsyncPrepare_l
,V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 1, 0, 0)
V/AudioCache( 2858): prepared
V/AudioCache( 2858): wait - success
V/MediaPlayerService( 2858): start
V/StagefrightPlayer( 2858): start
,V/AwesomePlayer( 2858): play
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
,V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
V/AwesomePlayer( 2858): onCheckAudioStatus
V/MediaPlayerService( 2858): wait for playback complete
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xaea1b790, 8, 0, 0)
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
I/Mms/MmsApp(11546):  start initViewCache mms
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/MediaPlayer(11578): decode(47, 20785700, 21825)
V/MediaPlayerService( 2858): decode(25, 20785700, 21825)
V/MediaPlayerService( 2858): player type = 3
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
V/StagefrightPlayer( 2858): setDataSource(25, 20785700, 21825)
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
V/AwesomePlayer( 2858): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2858): mBitrate = -1 bits/sec
I/OggExtractor( 2858): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2858): current audio track index (0) is added to vector
V/AwesomePlayer( 2858): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2858): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2858): prepare
V/AwesomePlayer( 2858): prepareAsync
V/MediaPlayerService( 2858): wait for prepare
D/Mms/ComposeMessageFragment(11546): [start]    fillCache consume time = 541.38725
D/Mms/ComposeMessageFragment(11546): fillCache, easy = false
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
I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 1, 0, 0)
V/AudioCache( 2858): prepared
V/AudioCache( 2858): wait - success
V/MediaPlayerService( 2858): start
V/StagefrightPlayer( 2858): start
V/AwesomePlayer( 2858): play
V/AwesomePlayer( 2858): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2858): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2858): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
V/MediaPlayerService( 2858): wait for playback complete
I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1287635273, value : -859651136
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1287635273, value : -859651136
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb020d150, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x89, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2858): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2858): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2858): ~OggSource --
I/OggExtractor( 2858): ~OggExtractor ++
I/OggExtractor( 2858): ~MyVorbisExtractor ++ 
I/OggExtractor( 2858): ~MyVorbisExtractor --
I/OggExtractor( 2858): ~OggExtractor --
I/AudioPlayer( 2858): reset out
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
V/MediaPlayer(11578): decode(48, 20684636, 21552)
V/MediaPlayerService( 2858): decode(26, 20684636, 21552)
V/MediaPlayerService( 2858): player type = 3
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
,V/StagefrightPlayer( 2858): StagefrightPlayer
V/AwesomePlayer( 2858): setListener
V/StagefrightPlayer( 2858): initCheck
V/AwesomePlayer( 2858): setAudioSink
V/StagefrightPlayer( 2858): setDataSource(26, 20684636, 21552)
,V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
,V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
,V/AwesomePlayer( 2858): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 2858): mBitrate = -1 bits/sec
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
,V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
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
V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 1, 0, 0)
V/AudioCache( 2858): prepared
V/AudioCache( 2858): wait - success
V/MediaPlayerService( 2858): start
V/StagefrightPlayer( 2858): start
,V/AwesomePlayer( 2858): play
V/AwesomePlayer( 2858): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2858): startAudioPlayer_l, sendErrorNotification (0)
,I/SurfaceFlinger( 2850): id=14 Removed Uoast (8/9)
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/SurfaceFlinger( 2850): id=14 Removed Uoast (-2/9)
,I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2858): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2858): open(44100, 2, 0x0, 1, 0)
,I/SyncAdapterService(11322): Ignoring sync request for non-current account
,V/AwesomePlayer( 2858): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 6, 0, 0)
,V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
V/MediaPlayerService( 2858): wait for playback complete
,E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
,D/PowerManagerService( 3522): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3522) eventTime = 139998
,D/PowerManagerService( 3522): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3522 (0x0)
,D/PowerManagerService( 3522): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3522, ws=WorkSource{1000}) (elapsedTime=3299)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2858): addBatteryData
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xae9204c0, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x8a, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2858): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2858): OggSource::~OggSource() mExtractor !mStarted ref count = 1
,I/OggExtractor( 2858): ~OggSource --
I/OggExtractor( 2858): ~OggExtractor ++
I/OggExtractor( 2858): ~MyVorbisExtractor ++ 
I/OggExtractor( 2858): ~MyVorbisExtractor --
I/OggExtractor( 2858): ~OggExtractor --
,I/AudioPlayer( 2858): reset out
D/AbsListView(11546): Get MotionRecognitionManager
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
,V/MediaPlayer(11578): decode(51, 20778600, 7017)
,V/MediaPlayerService( 2858): decode(31, 20778600, 7017)
,D/MotionRecognitionService( 3522):  ssp status : true
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
V/StagefrightPlayer( 2858): setDataSource(31, 20778600, 7017)
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
V/AwesomePlayer( 2858): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2858): mSecCapture clear
V/AwesomePlayer( 2858): mSecMediaClock clear
D/Mms/ComposeMessageFragment(11546): [end]    fillCache consume time = 137.608875
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
,I/System.out(11759): SyncManager calls detatch()
I/OMXCodec( 2858): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2858): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2858): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2858): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager( 2858): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2858): finishAsyncPrepare_l
V/AwesomePlayer( 2858): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 200, 973, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 5, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 1, 0, 0)
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
V/AudioCache( 2858): notify(0xb236c420, 6, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): addBatteryData
I/AudioPlayer( 2858): First fillBuffer call!!
I/AudioPlayer( 2858): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2858): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/MediaPlayerService( 2858): wait for playback complete
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2858): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2858): onCheckAudioStatus
V/AwesomePlayer( 2858): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2858): onStreamDone
V/AwesomePlayer( 2858): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2858): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 2, 0, 0)
V/AudioCache( 2858): playback complete - thread will wake up later
V/AwesomePlayer( 2858): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 7, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=1)
V/AudioCache( 2858): wait - success
V/StagefrightPlayer( 2858): reset
V/AwesomePlayer( 2858): addBatteryData
V/AwesomePlayer( 2858): reset_l()
V/AwesomePlayer( 2858): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2858): notify(0xb236c420, 8, 0, 0)
V/AudioCache( 2858): ignored
V/AwesomePlayer( 2858): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2858): mAudioTrackVector clear
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stop() sendCommand(0x8b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2858): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2858): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2858): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2858): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2858): ~OggSource --
I/OggExtractor( 2858): ~OggExtractor ++
I/OggExtractor( 2858): ~MyVorbisExtractor ++ 
I/OggExtractor( 2858): ~MyVorbisExtractor --
I/OggExtractor( 2858): ~OggExtractor --
,W/BaseAppContext( 4469): Using Auth Proxy for data requests.
I/AudioPlayer( 2858): reset out
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
,W/BaseAppContext( 4469): Using Auth Proxy for data requests.
,W/BaseAppContext( 4469): Using Auth Proxy for data requests.
,W/BaseAppContext( 4469): Using Auth Proxy for data requests.
,W/BaseAppContext( 4469): Using Auth Proxy for data requests.
,W/BaseAppContext( 4469): Using Auth Proxy for data requests.
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 4469): Using Auth Proxy for data requests.
,I/System.out( 4245): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4245): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4245): Tagging socket 67 with tag 1000040100000000{268436481,0} uid 10014, pid: 4245, getuid(): 10014
,I/qtaguid ( 4245): Tagging socket 77 with tag 1000040100000000{268436481,0} uid 10014, pid: 4245, getuid(): 10014
,I/art     ( 4469): Explicit concurrent mark sweep GC freed 26364(1688KB) AllocSpace objects, 43(855KB) LOS objects, 20% free, 31MB/39MB, paused 2.688ms total 64.281ms
,D/Mms/BubbleViewCache(11546): fillCache bubble = 8
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11907): MountEmulatedStorage()
E/Zygote  (11907): v2
I/libpersona(11907): KNOX_SDCARD checking this for 10135
I/libpersona(11907): KNOX_SDCARD not a persona
,I/SELinux (11907): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.google.android.music:main for service com.google.android.music/.sync.SyncAdapterService: pid=11907 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11907): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11907): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11907): TimaSignature is unavailable
,D/ActivityThread(11907): Added TimaKeyStore provider
,D/ResourcesManager(11907): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore(11907): Database version: 104
,I/dhcpcd  (10900): wlan0: sending IPv6 Router Solicitation
,W/bdH     (11759): Application name is not set. Call Builder#setApplicationName.
D/ResourcesManager(11907): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11907): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(11907): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11907): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/System.out(11759): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(11759): (HTTPLog)-Static: isShipBuild true
I/System.out(11759): (HTTPLog)-Thread-1631-250232474: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(11759): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10101
,I/System.out(11759): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/ActivityThread(11907): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11907): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1fcb90b7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11907): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11907): GMSCore installation verified
,I/ConfigStore(11907): Config Database version: 1
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11907): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11907): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11907): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3522): getStreamVolume 3 index 0
,I/MediaRouter(11907): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/GHttpClientFactory(11907): Using the GMSCore's GoogleHttpClient
,I/NetworkMonitor(11907): type=WIFI subType= reason=null isConnected=true
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor(11907): type=WIFI subType= reason=null isConnected=true
,W/PsynchoHelperImpl(11759): Error fetching or saving configuration
W/PsynchoHelperImpl(11759): bdz: 404 Not Found
W/PsynchoHelperImpl(11759): {
W/PsynchoHelperImpl(11759):   "errors": [
W/PsynchoHelperImpl(11759):     {
W/PsynchoHelperImpl(11759):       "domain": "global",
W/PsynchoHelperImpl(11759):       "reason": "notFound",
W/PsynchoHelperImpl(11759):       "message": "Setting psyncho_auto_backup_promo in namespace FEATURE_SWITCH was not found",
W/PsynchoHelperImpl(11759):       "locationType": "other",
W/PsynchoHelperImpl(11759):       "location": "setting"
W/PsynchoHelperImpl(11759):     }
W/PsynchoHelperImpl(11759):   ],
W/PsynchoHelperImpl(11759):   "code": 404,
W/PsynchoHelperImpl(11759):   "message": "Setting psyncho_auto_backup_promo in namespace FEATURE_SWITCH was not found"
W/PsynchoHelperImpl(11759): }
W/PsynchoHelperImpl(11759): 	at bdP.newExceptionOnError(AbstractGoogleJsonClientRequest.java:113)
W/PsynchoHelperImpl(11759): 	at bdP.newExceptionOnError(AbstractGoogleJsonClientRequest.java:40)
W/PsynchoHelperImpl(11759): 	at bdK.a(AbstractGoogleClientRequest.java:321)
W/PsynchoHelperImpl(11759): 	at bei.a(HttpRequest.java:1049)
W/PsynchoHelperImpl(11759): 	at bdJ.executeUnparsed(AbstractGoogleClientRequest.java:419)
W/PsynchoHelperImpl(11759): 	at bdJ.executeUnparsed(AbstractGoogleClientRequest.java:352)
W/PsynchoHelperImpl(11759): 	at bdJ.execute(AbstractGoogleClientRequest.java:469)
W/PsynchoHelperImpl(11759): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:142)
W/PsynchoHelperImpl(11759): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:215)
W/PsynchoHelperImpl(11759): 	at OQ.a(PsynchoHelperImpl.java:60)
W/PsynchoHelperImpl(11759): 	at agr.a(DriveSpecificSyncManager.java:27)
W/PsynchoHelperImpl(11759): 	at agO.a(LegacySyncManager.java:678)
W/PsynchoHelperImpl(11759): 	at agO.b(LegacySyncManager.java:582)
W/PsynchoHelperImpl(11759): 	at agO.a(LegacySyncManager.java:467)
W/PsynchoHelperImpl(11759): 	at agO.a(LegacySyncManager.java:97)
W/PsynchoHelperImpl(11759): 	at agQ.run(LegacySyncManager.java:419)
W/PsynchoHelperImpl(11759): 	at ami.a(NetworkUtilitiesImpl.java:31)
W/PsynchoHelperImpl(11759): 	at agP.run(LegacySyncManager.java:416)
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10101
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(11907): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(11907): (HTTPLog)-Static: isShipBuild true
I/System.out(11907): (HTTPLog)-Thread-1631-691047857: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(11907): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10135
,I/System.out(11907): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/Mms/Contact(11546): performUpdate:widgetCount=0
,I/GAV4    (11322): Thread[GAThread,5,main]: No campaign data found.
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11907): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,V/GLSActivity( 4245): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(11907): (HTTPLog)-Static: isSBSettingEnabled false
,W/MusicApiClient(11907): No content in 'data' field in GET sync response for Track
,I/GAV2    (11369): Thread[GAThread,5,main]: No campaign data found.
,I/MusicSyncAdapter(11907): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
I/MusicSyncAdapter(11907): Periodic update
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11975): MountEmulatedStorage()
E/Zygote  (11975): v2
I/libpersona(11975): KNOX_SDCARD checking this for 10031
I/libpersona(11975): KNOX_SDCARD not a persona
,I/SELinux (11975): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11975): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.ConsumptionAppDataChangedReceiver: pid=11975 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (11975): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Killing 11282:com.samsung.android.scloud.backup/u0a67 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11975): TimaSignature is unavailable
,D/ActivityThread(11975): Added TimaKeyStore provider
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/GAV2    (11414): Thread[GAThread,5,main]: No campaign data found.
,D/ResourcesManager(11975): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,E/Zygote  (11994): MountEmulatedStorage()
,E/Zygote  (11994): v2
I/libpersona(11994): KNOX_SDCARD checking this for 10195
I/libpersona(11994): KNOX_SDCARD not a persona
,I/SELinux (11994): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=11994 uid=10195 gids={50195, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux (11994): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11994): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11994): TimaSignature is unavailable
,D/ActivityThread(11994): Added TimaKeyStore provider
,D/ResourcesManager(11994): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/ResourcesManager(11994): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,D/Finsky  (11975): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  (11975): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings(11975): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings(11975): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SQLiteLog(10220): (283) recovered 276 frames from WAL file /data/user/0/com.google.android.gsf/databases/googlesettings.db-wal
,D/Ads     (11975): Skipping gmscore version check
,D/Finsky  (11975): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  (11975): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  (11975): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  (11975): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/System.out(11759): SyncManager calls detatch()
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11907): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11907): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ArtDownloadService(11907): Setting cache size 0
,W/System  (11907): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/GHttpClientFactory(11907): Using the GMSCore's GoogleHttpClient
,D/WearableService( 4245): callingUid 10014, callindPid: 4245
,I/MusicLeanback(11907): Conditions not met for autocaching.
,I/PlayMovies(11994): SyncService$SyncAdapter.onPerformSync:252 Skipping sync for 515013DC511638B0584069811EF28701C0771BF5
I/MusicLeanback(11907): Stop autocaching.
,D/WearableClient(11907): WearableClientImpl.onPostInitHandler: done
,W/GAV2    (11759): SyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/WearableClient(11907): WearableClientImpl.onPostInitHandler: done
,D/WifiService( 3522): releaseWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@32f44b34}
,D/PlayMovies(11994): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,D/WearableClient(11907): WearableClientImpl.onPostInitHandler: done
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11907): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,D/WearableClient(11907): WearableClientImpl.onPostInitHandler: done
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11907): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,I/ActivityManager( 3522): Killing 11137:com.google.android.syncadapters.calendar/u0a123 (adj 13): bgCount ##31
E/GmsUtils(11907): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/AudioCapabilities(11994): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities(11994): Unsupported mime audio/mpeg-L2
,D/PlayMovies(11994): TransferService.onCreate:52 creating transfer service
,W/AudioCapabilities(11994): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities(11994): Unsupported mime audio/x-ima
,E/GmsUtils(11907): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager( 3522): Killing 11305:com.sec.knox.bridge/1000 (adj 13): bgCount ##31
,W/VideoCapabilities(11994): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities(11994): Unsupported mime video/wvc1
,W/VideoCapabilities(11994): Unsupported mime video/x-ms-wmv
,E/ActivityThread(11907): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@34303f7 that was originally bound here
E/ActivityThread(11907): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@34303f7 that was originally bound here
E/ActivityThread(11907): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11907): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11907): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11907): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11907): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11907): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11907): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11907): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11907): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11907): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11907): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11907): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11907): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11907): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11907): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11907): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11907): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11907): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11907): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11907): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11907): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11907): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/VideoCapabilities(11994): Unrecognized profile/level 32768/2 for video/mp4v-es
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.videos/files/Movies/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11994): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.videos/files/Movies
,W/VideoCapabilities(11994): Unsupported mime video/wvc1
,W/VideoCapabilities(11994): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities(11994): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities(11994): Unsupported mime video/x-ms-wmv8
,D/ResourcesManager( 4469): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/VideoCapabilities(11994): Unsupported mime video/sorenson
,W/VideoCapabilities(11994): Unsupported mime video/mp43
,W/AudioCapabilities(11994): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities(11994): Unsupported mime audio/mpeg-L2
,D/WVCdm   ( 2858): Instantiating CDM.
W/VideoCapabilities(11994): Unrecognized profile/level 32768/2 for video/mp4v-es
,I/WVCdm   ( 2858): CdmEngine::QueryStatus
I/WVCdm   ( 2858): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   ( 2858): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/VideoCapabilities(11994): Unsupported profile 4 for video/mp4v-es
,W/ResourcesManager( 4469): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,E/wv_dash ( 2858): No saved usage table. Creating new table.
,D/WVCdm   ( 2858): OEMCrypto_Initialize Level 1 success. I will use level 1.
,I/WVCdm   ( 2858): L3 Terminate.
,E/Auth.Api.Credentials( 4469): [CredentialSyncAdapter] Unknown sync event.
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12074): MountEmulatedStorage()
E/Zygote  (12074): v2
I/libpersona(12074): KNOX_SDCARD checking this for 10123
I/libpersona(12074): KNOX_SDCARD not a persona
,I/SELinux (12074): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12074): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12074): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=12074 uid=10123 gids={50123, 9997, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12074): TimaSignature is unavailable
,D/ActivityThread(12074): Added TimaKeyStore provider
,D/ResourcesManager(12074): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,W/AbstractGoogleClient(12074): Application name is not set. Call Builder#setApplicationName.
,I/System.out(12074): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(12074): (HTTPLog)-Static: isShipBuild true
I/System.out(12074): (HTTPLog)-Thread-1638-730995105: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(12074): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10123
,I/System.out(12074): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid (12074): Tagging socket 28 with tag 1000000400000000{268435460,0} uid -1, pid: 12074, getuid(): 10123
,V/CalendarSyncAdapter(12074): Saving inProgress state: {calendarId=thalitester@gmail.com, maxAttendees=50, maxResults=200, timeMax=2017-02-23T00:00:00.000Z, updatedMin=2015-11-18T16:31:02.459Z}
,I/qtaguid (12074): Untagging socket 28
,D/CalendarSyncAdapter(12074): Found 0 events marked dirty & lastSynced
,I/ActivityManager( 3522): Killing 11019:com.android.chrome/u0a90 (adj 13): bgCount ##31
,I/ActivityManager( 3522): Killing 10702:com.samsung.android.keyguardwallpaperupdator/u0a127 (adj 13): bgCount ##31
,D/SSRM:n  ( 3522): SIOP:: AP = 290, PST = 269, CUR = -193
,I/PowerManagerService( 3522): [PWL] Off : 50s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:-104, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:62
D/BatteryService( 3522): stay LED for fully charged
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService(10686): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10686): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/dhcpcd  (10900): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (10900): wlan0: no IPv6 Routers available
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 40739(2MB) AllocSpace objects, 20(3MB) LOS objects, 24% free, 48MB/64MB, paused 1.885ms total 174.003ms
,I/GAV3    (11578): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    (11759): Thread[GAThread,5,main]: No campaign data found.
,W/ProcessCpuTracker( 3522): Skipping unknown process pid 12138
,V/AlarmManager( 3522): waitForAlarm result :8
,D/WearableClient(11907): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11907): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11907): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11907): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/WearableClient(11907): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11907): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/MusicLeanback(11907): Conditions not met for autocaching.
I/MusicLeanback(11907): Stop autocaching.
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PreloadUpdateManagerStateMachine(11513): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(11513): exit::IDLE
D/PreloadUpdateManagerStateMachine(11513): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (11513): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (11513): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(11513): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(11513): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(11513): entry::IDLE
,D/PackageManager( 3522): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/PageBuddyNotiSvc( 4652): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,I/InputReader( 3522): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 4001): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/Zygote  (12195): MountEmulatedStorage()
E/Zygote  (12195): v2
I/libpersona(12195): KNOX_SDCARD checking this for 10022
I/libpersona(12195): KNOX_SDCARD not a persona
,W/ResourceType( 4967): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
I/SELinux (12195): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/ResourceType( 4967): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
I/ActivityManager( 3522): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=12195 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12195): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12195): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/RegisteredServicesCache( 3968): empty dynamic service
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/TimaKeyStoreProvider(12195): TimaSignature is unavailable
,D/ActivityThread(12195): Added TimaKeyStore provider
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/SecContentProvider2( 3522): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3522): mCursor = null
,D/ResourcesManager(12195): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(12195): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12195): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12195): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/Launcher.Workspace( 4001): isBadgeUpdate : false
,I/LocationWidgetApplication(12195): onCreate() : start
,D/LocationWidgetApplication(12195): countryCode = POLAND
,D/LocationManagerService( 3522): getProviders()=[]
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/LocationManagerService( 3522): getProviders()=[passive]
D/LocationManagerService( 3522): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/LWLocationManager(12195): getDeviceLocationId :  id = -100
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Books/Books.apk
D/LocationWidgetApplication(12195): getLastUiLocationId() : mLastUiLocationId = -100
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/LocationWidgetFuctionData(12195): readDB
,I/LocationWidgetFuctionData(12195): selectedAppSize: 3
I/LocationWidgetFuctionData(12195): configPlaceList aroundMeItems
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,E/Zygote  (12217): MountEmulatedStorage()
E/Zygote  (12217): v2
I/libpersona(12217): KNOX_SDCARD checking this for 10003
I/libpersona(12217): KNOX_SDCARD not a persona
,I/SELinux (12217): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12217): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=12217 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
,E/SELinux (12217): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/TimaKeyStoreProvider(12217): TimaSignature is unavailable
,D/ActivityThread(12217): Added TimaKeyStore provider
,D/ResourcesManager(12217): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/UserAnalysis.PlaceProvider(12217): PlaceProvider onCreate()
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
W/ResourceType( 3522): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/UserAnalysis.SecureDbManager(12217): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper(12217): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(12217): Create SecureDbHelper
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/IntelligenceServiceApplication(12217): onCreate()
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,W/ResourcesManager( 3522): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3522): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3522): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/BackupManagerService( 3522): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/LocationWidgetFuctionData(12195): selectedAppSize: 3
,I/LocationWidgetFuctionData(12195): selectedAppSize: 3
,I/LocationWidgetFuctionData(12195): selectedAppSize: 3
,I/LocationWidgetFuctionData(12195): selectedAppSize: 3
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12232): MountEmulatedStorage()
E/Zygote  (12232): v2
I/libpersona(12232): KNOX_SDCARD checking this for 10035
I/libpersona(12232): KNOX_SDCARD not a persona
,I/SELinux (12232): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12232): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12232 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,E/SELinux (12232): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Killing 10768:com.android.email/u0a178 (adj 13): bgCount ##31
,I/ActivityManager( 3522): Killing 11488:com.samsung.android.sconnect/u0a150 (adj 13): bgCount ##32
,D/TimaKeyStoreProvider(12232): TimaSignature is unavailable
,D/ActivityThread(12232): Added TimaKeyStore provider
,D/ResourcesManager(12232): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/FeatureConfig(12232): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager(12232): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(12232): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(12232): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(12232): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12232): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(12232): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(12232): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager(12232): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(12232): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(12232): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourcesManager(12232): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/ActivityManager( 3522): Killing 10742:tv.peel.smartremote/u0a186 (adj 13): bgCount ##31
,D/ResourcesManager(12232): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(12232): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12232): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12232): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager(12232): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
E/Zygote  (12249): MountEmulatedStorage()
W/ResourcesManager(12232): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
E/Zygote  (12249): v2
W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/libpersona(12249): KNOX_SDCARD checking this for 10050
I/libpersona(12249): KNOX_SDCARD not a persona
,I/SELinux (12249): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/ResourcesManager(12232): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/SELinux (12249): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12249 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux (12249): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(12232): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager(12232): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12232): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8736(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 967us total 21.626ms
,W/ResourcesManager(12232): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider(12249): TimaSignature is unavailable
,D/ActivityThread(12249): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 848us total 18.679ms
,D/ResourcesManager(12232): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(12249): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(12232): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager(12249): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12249): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12249): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12249): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12249): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12249): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12249): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12249): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12232): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 698us total 18.335ms
,D/ResourcesManager(12232): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager(12232): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(12232): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager(12232): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager(12232): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/ResourcesManager(12232): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication(12232): system/finder_cp/cpdata.xml file not found
,D/PackageManager( 3522): findPreferredActivity: No PreferredActivities set
,D/NearbySource(12249): Nearby Source Create!
D/NearbyContext(12249): Nearby Context Create!
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12249): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(12249): Samsung link source created
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ContactProvider(12249): getAllContactInfoList Start
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/UpdateIcingCorporaServi( 4038): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,I/ActivityManager( 3522): Killing 11162:com.sec.android.fotaclient/u0a12 (adj 13): bgCount ##31
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12270): MountEmulatedStorage()
E/Zygote  (12270): v2
I/libpersona(12270): KNOX_SDCARD checking this for 10079
I/libpersona(12270): KNOX_SDCARD not a persona
,I/SELinux (12270): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12270): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=12270 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12270): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ContactProvider(12249): getAllContactInfoList End
,I/syncContacts(12249): thread: 1658, sync time = 165
,D/TimaKeyStoreProvider(12270): TimaSignature is unavailable
,D/ActivityThread(12270): Added TimaKeyStore provider
,D/ResourcesManager( 4038): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(12270): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/FileShare-Server(12270): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.videos
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12285): MountEmulatedStorage()
E/Zygote  (12285): v2
I/libpersona(12285): KNOX_SDCARD checking this for 1000
I/libpersona(12285): KNOX_SDCARD not a persona
,I/UpdateIcingCorporaServi( 4038): UpdateCorporaTask done [took 114 ms] updated apps [took 114 ms] 
I/SELinux (12285): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=12285 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux (12285): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12285): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Killing 11546:com.android.mms/u0a52 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12285): TimaSignature is unavailable
,D/ActivityThread(12285): Added TimaKeyStore provider
,D/ResourcesManager(12285): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12285): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/CountryDetector( 3522): No listener is left
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12300): MountEmulatedStorage()
E/Zygote  (12300): v2
I/libpersona(12300): KNOX_SDCARD checking this for 1000
I/libpersona(12300): KNOX_SDCARD not a persona
,I/SELinux (12300): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12300): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=12300 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (12300): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Killing 11180:com.samsung.klmsagent/u0a21 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12300): TimaSignature is unavailable
,D/ActivityThread(12300): Added TimaKeyStore provider
,D/ResourcesManager(12300): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,D/ShortcutReceiver(12300):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/PackageBroadcastService( 4469): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,E/Zygote  (12317): MountEmulatedStorage()
E/Zygote  (12317): v2
I/libpersona(12317): KNOX_SDCARD checking this for 10110
I/libpersona(12317): KNOX_SDCARD not a persona
,I/SELinux (12317): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12317): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.oxygen.appmanager.packages.PackageReceiver: pid=12317 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux (12317): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Killing 11556:com.android.calendar/u0a164 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12317): TimaSignature is unavailable
,D/ActivityThread(12317): Added TimaKeyStore provider
,D/ResourcesManager(12317): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (12317): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(12317): not using cross-dex optimization: ART in use
,I/art     (12317): Thread[1,tid=12317,WaitingForJniOnLoad,Thread*=0xb4d08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(12317): about to lock: /data/data/com.facebook.appmanager/mdex_lock
V/DexLibLoader(12317): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
,V/DexLibLoader(12317): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
D/DexLibLoader(12317): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(12317): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (12317): Attempt to remove local handle scope entry from IRT, ignoring
,D/DexLibLoader(12317): loading pre-built fallback odex files
V/MultiDexClassLoader(12317): installing MultiDexClassLoader before application classloader
,D/DexLibLoader(12317): released odex store lock
D/DexLibLoader(12317): DexLibLoader.loadAll took 29 ms
,W/ca      (12317): Verify
,D/SSRM:n  ( 3522): SIOP:: AP = 270, PST = 269, CUR = -104
,W/LightSharedPreferencesImpl(12317): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(12317): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(12317): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(12317): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(12317): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(12317): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(12317): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(12317): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(12317): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(12317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(12317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(12317): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(12317): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(12317): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(12317): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(12317): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(12317): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(12317): 	... 10 more
,E/ActivityThread(12317): Failed to find provider info for com.facebook.appmanager.installrecord
,W/appmanager(:<default>):b(12317): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(12317): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):QuickExperimentControllerImpl(12317): Exposure of experiment com.facebook.common.network.l@10157387 occurred when no user was logged in
,I/ActivityManager( 3522): Killing 10723:com.samsung.android.securitylogagent/1000 (adj 13): bgCount ##31
,W/BroadcastQueue( 3522): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{9f848c7 u0 ReceiverList{300a0a06 12317 com.facebook.appmanager/10110/u0 remote:39f71ce1}}
,W/BroadcastQueue( 3522): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{9f848c7 u0 ReceiverList{300a0a06 12317 com.facebook.appmanager/10110/u0 remote:39f71ce1}}
,W/BroadcastQueue( 3522): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{177d02db u0 ReceiverList{2cabcfea 12317 com.facebook.appmanager/10110/u0 remote:20367bd5}}
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:3, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:64
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10686): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10686): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12317): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12317): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,W/appmanager(:<default>):QuickExperimentControllerImpl(12317): Exposure of experiment com.facebook.imagepipeline.a.g@34fa125d occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(12317): Exposure of experiment com.facebook.imagepipeline.a.d@2de81f1e occurred when no user was logged in
,I/art     (12317): Explicit concurrent mark sweep GC freed 44737(2MB) AllocSpace objects, 3(48KB) LOS objects, 22% free, 27MB/35MB, paused 1.519ms total 52.943ms
,W/appmanager(:<default>):m(12317): No feature status reporters found; is this dead code?
,I/Icing   ( 4469): Indexing 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26 from com.google.android.gms
,W/appmanager(:<default>):b(12317): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(12317): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(12317): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ResourcesManager( 4469): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/appmanager(:<default>):QuickExperimentControllerImpl(12317): Exposure of experiment com.facebook.http.g.bb@2d8596da occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(12317): Exposure of experiment com.facebook.http.g.an@1c73d70b occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(12317): Exposure of experiment com.facebook.http.g.aw@19b1e801 occurred when no user was logged in
W/appmanager(:<default>):QuickExperimentControllerImpl(12317): Exposure of experiment com.facebook.http.g.aj@173646a6 occurred when no user was logged in
W/appmanager(:<default>):QuickExperimentControllerImpl(12317): Exposure of experiment com.facebook.http.g.a@3606d8e7 occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(12317): Exposure of experiment com.facebook.http.g.k@9f02732 occurred when no user was logged in
,I/System.out(12317): Thread-1709(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(12317): Thread-1709(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(12317): Thread-1709(ApacheHTTPLog):isShipBuild true
I/System.out(12317): Thread-1709(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/Icing   ( 4469): Indexing done 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26
,W/appmanager(:<default>):QuickExperimentControllerImpl(12317): Exposure of experiment com.facebook.http.g.c@35bfddf occurred when no user was logged in
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10110
,W/ActivityThread(12317): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/System.out(12317): P[5]_NetworkDispatch1 calls detatch()
,W/appmanager(:<default>):b(12317): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(12317): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/IdleConnectionHandler(12317): Removing a connection that never existed!
,I/ActivityManager( 3522): Waited long enough for: ServiceRecord{2612c98d u0 com.google.android.music/.download.artwork.ArtDownloadService}
,W/ProcessCpuTracker( 3522): Skipping unknown process pid 12416
,E/Watchdog( 3522): !@Sync 5
,V/AlarmManager( 3522): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
,D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3693): *** don't update sliding image ***
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 269, CUR = 3
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService(10686): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10686): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3522): [PWL] Off : 75s ago
,W/IcingInternalCorpora( 4469): getNumBytesRead when not calculated.
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 268, CUR = 38
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:54
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10686): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10686): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4245): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 268, CUR = 49
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10686): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10686): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3522): !@Sync 6
,V/AlarmManager( 3522): waitForAlarm result :4
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 266, CUR = 49
,E/ActivityThread( 4469): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager( 3522): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 165281, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager( 3522): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 256927, reason: UserStart
,W/ResourceType( 4967): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4967): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/SecContentProvider2( 3522): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 3522): mCursor = null
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10686): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10686): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3522): [PWL] Off : 105s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 261, CUR = 46
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10686): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10686): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3522): waitForAlarm result :8
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 260, CUR = 43,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10686): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10686): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3522): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
,D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3693): *** don't update sliding image ***
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 3522): !@Sync 7
,V/AlarmManager( 3522): waitForAlarm result :4
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 259, CUR = 40
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10686): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10686): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 256, CUR = 38
,I/PowerManagerService( 3522): [PWL] Off : 140s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10686): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine(10686): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 252, CUR = 35
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3522): !@Sync 8
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 250, CUR = 35
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService(10686): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine(10686): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 ,
,I/jxcore-log(10615): --= Surplus to requirements =--
I/jxcore-log(10615): 
I/jxcore-log(10615): ****TEST TOOK:  ms ****
I/jxcore-log(10615): 
I/jxcore-log(10615): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10615): 
,D/AndroidRuntime(12578): 
D/AndroidRuntime(12578): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12578): CheckJNI is OFF
,D/AndroidRuntime(12578): readGMSProperty: start
D/AndroidRuntime(12578): readGMSProperty: already setted!!
,D/AndroidRuntime(12578): readGMSProperty: end
D/AndroidRuntime(12578): addProductProperty: start
,E/AffinityControl(12578): AffinityControl: registerfunction enter
,D/AndroidRuntime(12578): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3522): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3522): START PACKAGE DELETE: observer{308170578}
D/PackageManager( 3522): pkg{<packageName>}
D/PackageManager( 3522): user{0}
D/PackageManager( 3522): caller{2000}
D/PackageManager( 3522): flags{3}
D/PersonaManagerService( 3522): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3522): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3522): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3522): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3522): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3522): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3522): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3522): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3522): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3522): !@killApplicatoin: 10601, uninstall pkg
,I/ActivityManager( 3522): Force stopping com.test.thalitest appid=10601 user=-1: uninstall pkg
,I/ActivityManager( 3522): Killing 10615:com.test.thalitest/u0a601 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3522):   Force finishing activity ActivityRecord{a3e62be u0 com.test.thalitest/.MainActivity t25}
,I/SurfaceFlinger( 2850): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger( 2850): id=12 Removed NainActivit (-2/8)
,D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 3522): Skipping PackageSetting{14347df com.example.hello/10563} due to missing metadata
,I/ActivityManager( 3522): Force stopping com.test.thalitest appid=10601 user=0: pkg removed
,D/WifiService( 3522): Client connection lost with reason: 4
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/art     ( 7933): Explicit concurrent mark sweep GC freed 24559(1442KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.134ms total 46.477ms
,I/art     ( 4038): Explicit concurrent mark sweep GC freed 13562(778KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 1.250ms total 43.354ms
,I/art     ( 4469): Explicit concurrent mark sweep GC freed 23474(1283KB) AllocSpace objects, 2(32KB) LOS objects, 20% free, 31MB/39MB, paused 1.403ms total 82.337ms
,I/InputReader( 3522): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 4245): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 4427): mOCRHelper is null
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/LocationWidgetApplication(12195): getLastUiLocationId() : mLastUiLocationId = -100
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/EnterpriseDeviceManagerService( 3522): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3522): Admin package name: com.google.android.gms
,E/Zygote  (12601): MountEmulatedStorage()
E/Zygote  (12601): v2
I/libpersona(12601): KNOX_SDCARD checking this for 10063
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/libpersona(12601): KNOX_SDCARD not a persona
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux (12601): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12601 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux (12601): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12601): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourceType( 3522): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourceType( 4967): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4967): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider(12601): TimaSignature is unavailable
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityThread(12601): Added TimaKeyStore provider
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 3522): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3522): onPackageRemoved : com.test.thalitest
,D/ResourcesManager(12195): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager(12601): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager(12195): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
I/art     ( 3522): Explicit concurrent mark sweep GC freed 56224(3MB) AllocSpace objects, 39(624KB) LOS objects, 24% free, 49MB/65MB, paused 1.891ms total 156.382ms
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     ( 3522): WaitForGcToComplete blocked for 152.639ms for cause Explicit
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/VRSetupWizardStub/PackageIntentReceiver(12601): onReceive()
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/VRSetupWizardStub/PackageIntentReceiver(12601): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12601): packagename:com.test.thalitest
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12195): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(12195): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
E/Zygote  (12618): MountEmulatedStorage()
I/libpersona(12618): KNOX_SDCARD checking this for 10021
E/Zygote  (12618): v2
I/libpersona(12618): KNOX_SDCARD not a persona
,I/SELinux (12618): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12618 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 11606:com.sec.android.app.taskmanager/u0a191 (adj 13): bgCount ##31
I/SELinux (12618): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12618): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/SecContentProvider2( 3522): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3522): mCursor = null
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(12195): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/TimaKeyStoreProvider(12618): TimaSignature is unavailable
,D/ActivityThread(12618): Added TimaKeyStore provider
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 248, CUR = 34
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/RegisteredServicesCache( 3968): empty dynamic service
,D/ResourcesManager(12195): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(12618): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(12195): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/KLMS-2.4.521: (12618): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Jan 27 02:12:58 GMT+01:00 2016
,I/KLMS-2.4.521: (12618): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3522): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3522): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,I/KLMS-2.4.521: (12618): KLMSIntentService(): onCreate()
,D/ResourcesManager(12195): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,I/KLMS-2.4.521: (12618): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12618): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12618): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/elm:14491(11714): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/ResourcesManager(12195): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/KLMS-2.4.521: (12618): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.4.521: (12618): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (12618): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/RCPManagerService( 3522): PackageReceiver onReceive()
,D/ResourcesManager(12195): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(12195): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/HarmonyEASService( 3522): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3522): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/art     ( 3522): Explicit concurrent mark sweep GC freed 11278(584KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 49MB/65MB, paused 2.486ms total 130.389ms
,D/BackupManagerService( 3522): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3522): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3522): uID is 10601
V/EnterpriseBillingPolicy( 3522): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3522): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3522): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3522): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 3522): getBillingProfileForVpnEngine - end - null
,D/ResourcesManager(12195): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(12195): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(12195): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/RCPManager(12285):  in createShortcut() for packageName: com.test.thalitest userId0
D/ResourcesManager(12195): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(12195): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/RCPManagerService( 3522):  in createShortcut() for packageName: com.test.thalitest userId0
W/ResourcesManager(12195): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/RCPManagerService( 3522): queryAllProviders():  providerCallBack is not register for 0
W/ResourcesManager(12195): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12195): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/KLMS-2.4.521: (12618): KLMSIntentService(): listeningToPackageRemoved().END
,E/Zygote  (12636): MountEmulatedStorage()
E/Zygote  (12636): v2
,I/libpersona(12636): KNOX_SDCARD checking this for 10160
I/libpersona(12636): KNOX_SDCARD not a persona
,I/SELinux (12636): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager(12195): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,I/SELinux (12636): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=12636 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
,E/SELinux (12636): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (12618): KLMSIntentService(): onDestroy()
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12195): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/TimaKeyStoreProvider(12636): TimaSignature is unavailable
D/ActivityThread(12636): Added TimaKeyStore provider
,E/Zygote  (12651): MountEmulatedStorage()
E/Zygote  (12651): v2
I/libpersona(12651): KNOX_SDCARD checking this for 10052
I/libpersona(12651): KNOX_SDCARD not a persona
,I/SELinux (12651): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12651): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12651 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
E/SELinux (12651): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/PackageManager( 3522): delete codoeFile: 
,D/ResourcesManager(12195): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/AASAUninstall( 3522):  com.test.thalitest not target!
,D/PackageManager( 3522): result of delete: 1{308170578}
,D/AndroidRuntime(12578): Shutting down VM
,D/elm:14491(11714): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14491(11714): ElmAgentService : onCreate()
,D/TaskPersister( 3522): removeObsoleteFile: deleting file=25_task.xml
D/elm:14491(11714): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491(11714): MainReceiver.listeningToPackageRemoved()
,D/elm:14491(11714): MDMBridge.getInstance()
D/elm:14491(11714): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(11714): MDMBridge.getAllLicenseInfoFromSDK()
,D/TimaKeyStoreProvider(12651): TimaSignature is unavailable
,D/ActivityThread(12651): Added TimaKeyStore provider
,D/ResourcesManager(12636): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager(12636): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12636): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12636): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/elm:14491(11714): ElmAgentService : onDestroy().
,D/com.sec.android.service.health.upgrade.UninstallReceiver(11629): onReceive()
,I/com.sec.android.service.health.upgrade.UninstallReceiver(11629): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(11629): onReceive() : package name is not s health. Return !!!
,D/ResourcesManager(12651): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12195): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,W/ResourcesManager(12651): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(12651): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12651): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12651): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12651): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12651): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(12195): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,E/Zygote  (12667): MountEmulatedStorage()
I/libpersona(12667): KNOX_SDCARD checking this for 1000
E/Zygote  (12667): v2
I/libpersona(12667): KNOX_SDCARD not a persona
,I/SELinux (12667): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12667): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=12667 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (12667): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(12195): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/LocationWidgetApplication(12195): getLastUiLocationId() : mLastUiLocationId = -100
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(12195): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/ResourcesManager(12195): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/TimaKeyStoreProvider(12667): TimaSignature is unavailable
,D/ActivityThread(12667): Added TimaKeyStore provider
,E/Zygote  (12683): MountEmulatedStorage()
E/Zygote  (12683): v2
I/libpersona(12683): KNOX_SDCARD checking this for 1000
I/libpersona(12683): KNOX_SDCARD not a persona
I/SELinux (12683): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12683): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=12683 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/ResourcesManager(12195): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
E/SELinux (12683): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Killing 11646:com.samsung.android.scloud.sync/u0a69 (adj 13): bgCount ##31
,D/Mms/MmsApp(12651): [start]    onCreate() consume time = 0.0
,D/Mms/ArtClassLoader(12651): init before art
,D/Mms/ArtClassLoader(12651): init [DONE] art
,D/ResourcesManager(12195): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/Mms/TelephonyPermission(12651): start operation mode monitor
,V/Common  (12636): getScreenSize 1440 2560
,D/ResourcesManager(12651): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(12651): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager(12195): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12683): TimaSignature is unavailable
,D/ActivityThread(12683): Added TimaKeyStore provider
D/ResourcesManager(12667): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,I/JAM     (12636): Load The ApaService JNI
,D/ResourcesManager(12195): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
I/JAM     (12636): version: ProfessionalAudio_v1.0.b5
I/JAM     (12636): Try v1.0.b3 ...
,D/Spen    (12636): SpenSdk version level = 55
D/Spen    (12636): SpenSdk jar version = 3.0.243
,D/Spen    (12636): SpenSdk apk version = 3.0.235
D/Spen    (12636): Server UPDATE Check
,W/linker  (12636): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,E/Zygote  (12701): MountEmulatedStorage()
E/Zygote  (12701): v2
I/libpersona(12701): KNOX_SDCARD checking this for 10160
I/libpersona(12701): KNOX_SDCARD not a persona
D/SPenError(12636): JNI_OnLoad
,D/JNI_Bitmap(12636): Init .. Done
I/SELinux (12701): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/SPenSpiDecoder(12636): JNI_OnLoad .. Done
D/SPenError(12636): JNI_OnLoad Success
,D/PluginManager(12636): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
I/ActivityManager( 3522): Start proc com.samsung.android.snote:provider for content provider com.samsung.android.snote/.model.provider.SNoteProvider: pid=12701 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
D/PluginManager(12636): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
,D/Init_SPenSdk_Jni(12636): JNI_OnLoad
,D/Init_SPenSdk_Jni(12636): AndroidSDK: 21
D/Init_SPenSdk_Jni(12636): JNI_OnLoad .. Done
,I/SELinux (12701): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/Model_ObjectBase_Jni(12636): JNI_OnLoad .. Done
D/Model_ObjectStroke_Jni(12636): JNI_OnLoad .. Done
E/SELinux (12701): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Model_ObjectImage_Jni(12636): JNI_OnLoad .. Done
,D/Model_ObjectText_Jni(12636): JNI_OnLoad .. Done
D/Model_ObjectContainer_Jni(12636): JNI_OnLoad .. Done
,D/Mms/TelephonyPermission(12651): DefaultSmsApp is com.android.mms
,D/Model_PageDoc_Jni(12636): JNI_OnLoad .. Done
D/Mms/TelephonyPermission(12651): isDefault true
D/Model_NoteDoc_Jni(12636): check build type eng[0]
,D/Model_NoteDoc_Jni(12636): JNI_OnLoad .. Done
D/Model_NoteFile_Jni(12636): JNI_OnLoad .. Done
D/Model_ObjectUtil_Jni(12636): JNI_OnLoad .. Done
D/Model   (12636): OnLoad class Done
W/ContextImpl(12667): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
,D/spe_log (12636): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
,D/SPen_Library(12636): Draw Engine JNI_OnLoad enter!!
D/SPen_Library(12636): Canvas JNI_OnLoad enter!!
,D/ResourcesManager(12195): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
D/SPen_Library(12636): Canvas JNI_OnLoad Success
D/SPen_Library(12636): TextView JNI_OnLoad enter!!
,D/SPen_Library(12636): TextView JNI_OnLoad Success
D/SPen_Library(12636): Text JNI_OnLoad enter!!
D/SPen_Library(12636): Text JNI_OnLoad Success
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/SPen_Library(12636): FontManager JNI_OnLoad enter!!
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/SPen_Library(12636): FontManager JNI_OnLoad Success
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/SPen_Library(12636): CapturePage JNI_OnLoad enter!!
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/SPen_Library(12636): CapturePage JNI_OnLoad Success
D/SPen_Library(12636): Multi JNI_OnLoad enter!!
,D/SPen_Library(12636): Multi JNI_OnLoad Success
D/SPen_Library(12636): Draw Engine JNI_OnLoad Success
,D/SPen_Library(12636): Brush JNI_OnLoad enter!!
,D/SPen_Library(12636): Brush JNI_OnLoad Success
,D/SPen_Library(12636): ChineseBrush JNI_OnLoad enter!!
,D/SPen_Library(12636): ChineseBrush JNI_OnLoad Success
,D/SPen_Library(12636): InkPen JNI_OnLoad enter!!
,D/SPen_Library(12636): InkPen JNI_OnLoad Success
,D/ResourcesManager(12195): creating new AssetManager and set to /system/app/Books/Books.apk
,D/SPen_Library(12636): Marker JNI_OnLoad enter!!
D/SPen_Library(12636): Marker JNI_OnLoad Success
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8779(373KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 880us total 29.456ms
D/SPen_Library(12636): Pencil JNI_OnLoad enter!!
,D/SPen_Library(12636): Pencil JNI_OnLoad Success
,D/SPen_Library(12636): NativePen JNI_OnLoad enter!!
D/SPen_Library(12636): NativePen JNI_OnLoad Success
,D/Mms/MmsApp(12651): onCreate() com.android.mms
,D/SPen_Library(12636): MontblancFountainPen JNI_OnLoad enter!!
D/SPen_Library(12636): MontblancFountainPen JNI_OnLoad Success
,D/SPen_Library(12636): MontblancCalligraphyPen JNI_OnLoad enter!!
,D/SPen_Library(12636): MontblancCalligraphyPen JNI_OnLoad Success
,D/SPen_Library(12636): MagicPen JNI_OnLoad enter!!
,D/SPen_Library(12636): MagicPen JNI_OnLoad Success
,D/ResourcesManager(12683): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
D/SPen_Library(12636): ObliquePen JNI_OnLoad enter!!
,D/SPen_Library(12636): ObliquePen JNI_OnLoad Success
,D/SPen_Library(12636): FountainPen JNI_OnLoad enter!!
,D/SPen_Library(12636): FountainPen JNI_OnLoad Success
D/Spen    (12636): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni(12636): SPenSdk_init2
D/Init_SPenSdk(12636): Init - screen_width = 1440, screen_height = 2560, maxCacheSize = 100 M
D/Init_SPenSdk(12636): Total S Pen SDK Directory Size = 0
D/Spen    (12636): initialize complete
,W/linker  (12636): libSPenImageFilterLibs.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
D/ResourcesManager(12195): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/TimaKeyStoreProvider(12701): TimaSignature is unavailable
,D/ActivityThread(12701): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 930us total 17.138ms
,D/ResourcesManager(12195): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/Mms/MmsApp(12651): [start]    initCountryIso consume time = 97.152375
,D/CountryDetector( 3522): The first listener is added
,I/PCWCLIENTTRACE_LOG(12683): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(12683): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(12683): new DMDBOpenHelper instance
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 469us total 13.984ms
,D/Mms/MmsApp(12651): [end]    initCountryIso consume time = 11.014917
D/Mms/MmsConfig(12651): [start]    MmsConfig.init() consume time = 0.091
,D/ResourcesManager(12195): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/Mms/MmsConfig(12651): before partial update
,E/Zygote  (12722): MountEmulatedStorage()
I/libpersona(12722): KNOX_SDCARD checking this for 10121
E/Zygote  (12722): v2
I/libpersona(12722): KNOX_SDCARD not a persona
I/SELinux (12722): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12722): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12722): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=12722 uid=10121 gids={50121, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/Mms/MmsConfig(12651): Load Resize quality : 80
,D/Mms/MmsConfig(12651):  enable multiwindow = true
,D/ResourcesManager(12195): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/TimaKeyStoreProvider(12722): TimaSignature is unavailable
,D/ActivityThread(12722): Added TimaKeyStore provider
,E/Mms/MessageUtils(12651): setCountryDetector : update country detector info 
E/Mms/MessageUtils(12651): updateCountryIso : update country iso info 
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_PushUtil(12683): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12683): sales region : global
I/PCWCLIENTTRACE_PushUtil(12683): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12683): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager(12195): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/Mms/PackageInfo(12651): com.sec.imsservice is not installed
D/Mms/MmsConfig(12651): [end]    init() consume time = 41.407875
,D/Mms/Contact(12651): [start]    init() consume time = 0.520208
D/ResourcesManager(12701): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,E/Zygote  (12739): MountEmulatedStorage()
E/Zygote  (12739): v2
I/libpersona(12739): KNOX_SDCARD checking this for 10116
I/libpersona(12739): KNOX_SDCARD not a persona
,I/SELinux (12739): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
W/ResourcesManager(12701): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,I/SELinux (12739): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12739): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=12739 uid=10116 gids={50116, 9997, 1023} abi=armeabi-v7a
W/ResourcesManager(12701): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12701): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/Mms/Contact(12651): [end]    init consume time = 12.942042
,D/Mms/DraftCache(12651): [start]    rebuildCache consume time = 1.519291
D/ResourcesManager(12195): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/TP/MmsSmsProvider( 3983): query,matched:13, calling pid = 12651
,D/TP/MmsSmsProvider( 3983): match 13:Elapsed time : 1.263 ms
,D/TimaKeyStoreProvider(12739): TimaSignature is unavailable
,D/ActivityThread(12739): Added TimaKeyStore provider
,E/Zygote  (12756): MountEmulatedStorage()
E/Zygote  (12756): v2
I/libpersona(12756): KNOX_SDCARD checking this for 10183
I/libpersona(12756): KNOX_SDCARD not a persona
,I/SELinux (12756): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12756): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12756): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12756 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,D/ResourcesManager(12722): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,I/ActivityManager( 3522): Killing 11681:com.sec.android.app.clockpackage/u0a94 (adj 13): bgCount ##31
I/ActivityManager( 3522): Killing 11663:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##32
,D/Mms/TelephonyUtils(12651): getSubId from simSlot 0, return Value = -1
D/Mms/DownloadManager(12651): roaming -> false (slotId = 0)
D/Mms/DownloadManager(12651): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(12651): auto download without roaming -> true
D/Mms/DownloadManager(12651): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
E/Mms/TelephonyUtils(12651): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils(12651): getSubId from simSlot 1, return Value = 9223372036854775807
D/Mms/DownloadManager(12651): roaming -> false (slotId = 1)
D/Mms/DownloadManager(12651): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager(12651): auto download without roaming -> true
D/Mms/DownloadManager(12651): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager(12651): auto download during roaming secondary -> false
D/Mms/DownloadManager(12651): mAutoDownload ------> true
,D/TimaKeyStoreProvider(12756): TimaSignature is unavailable
,D/ActivityThread(12756): Added TimaKeyStore provider
,D/ResourcesManager(12195): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/ResourcesManager(12195): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(12739): creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
,D/ResourcesManager(12232): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(12232): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(12232): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12232): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(12195): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,D/ResourcesManager(12232): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 3522): Killing 11697:com.wsomacp/u0a28 (adj 13): bgCount ##31
,D/SNoteProvider(12701): onCreate enableSnoteSync = true
D/ResourcesManager(12756): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12232): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(12232): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager(12232): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(12195): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(12232): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,E/SQLiteLog(11578): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog(11578): (3850) statement aborts at 19: [delete  from app_registry where package_name= "com.test.thalitest" AND plugin_id= "1"] disk I/O error
,E/SQLiteQuery(11578): exception: disk I/O error (code 3850); query: delete  from app_registry where package_name= "com.test.thalitest" AND plugin_id= "1"
,D/ResourcesManager(12195): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,D/ResourcesManager(12195): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager(12232): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,E/Zygote  (12776): MountEmulatedStorage()
I/libpersona(12776): KNOX_SDCARD checking this for 1000
E/Zygote  (12776): v2
I/libpersona(12776): KNOX_SDCARD not a persona
,E/SQLiteLog(12756): (28) failed to open "/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db" with flag (131138) and mode_t (0) due to error (30)
,E/AndroidRuntime(11578): FATAL EXCEPTION: IntentService[HandleAppDataService]
E/AndroidRuntime(11578): Process: com.sec.android.app.shealth, PID: 11578
E/AndroidRuntime(11578): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime(11578): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForCursorWindow(Native Method)
E/AndroidRuntime(11578): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:1015)
E/AndroidRuntime(11578): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
E/AndroidRuntime(11578): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
E/AndroidRuntime(11578): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:147)
E/AndroidRuntime(11578): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:136)
E/AndroidRuntime(11578): 	at android.content.ContentResolver.query(ContentResolver.java:503)
E/AndroidRuntime(11578): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/AndroidRuntime(11578): 	at com.sec.android.app.shealth.framework.ui.data.AppRegistryDbManagerWithProvider.deleteAppRegistryData(Unknown Source)
E/AndroidRuntime(11578): 	at com.sec.android.app.shealth.service.HandleAppDataService.onHandleIntent(HandleAppDataService.java:66)
E/AndroidRuntime(11578): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime(11578): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(11578): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(11578): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 3522): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=12776 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SQLiteDatabase(12756): Failed to open database '/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db'.
E/SQLiteDatabase(12756): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12756): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12756): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12756): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12756): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12756): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12756): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12756): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12756): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12756): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12756): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12756): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12756): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12756): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12756): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:269)
E/SQLiteDatabase(12756): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:232)
E/SQLiteDatabase(12756): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(12756): 	at android.content.ContentP,rovider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(12756): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(12756): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(12756): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(12756): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12756): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12756): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12756): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12756): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12756): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12756): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12756): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12756): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(12756): Shutting down VM
I/SELinux (12776): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
E/AndroidRuntime(12756): FATAL EXCEPTION: main
E/AndroidRuntime(12756): Process: com.samsung.android.provider.shootingmodeprovider, PID: 12756
E/AndroidRuntime(12756): java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12756): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(12756): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(12756): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(12756): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(12756): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(12756): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12756): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12756): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(12756): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(12756): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(12756): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(12756): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(12756): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12756): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12756): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12756): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12756): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12756): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12756): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12756): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12756): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12756): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12756): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12756): 	at android.content.ContextWrapper.openOrCrea,teDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12756): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12756): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12756): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:269)
E/AndroidRuntime(12756): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:232)
E/AndroidRuntime(12756): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(12756): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(12756): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(12756): 	... 11 more
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3522): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3522): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3522): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3522): displayNotification : [0ah,00h,01h]
W/ResourcesManager(12232): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/SNoteProvider(12701): ===query=== 
D/UsbHostManager( 3522): displayNotification : [09h,00h,00h]
D/UsbHostManager( 3522): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3522): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
I/SELinux (12776): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/UsbSettingsManager( 3522): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
E/SQLiteLog(12701): (28) failed to open "/data/user/0/com.samsung.android.snote/databases/Snote.db" with flag (131138) and mode_t (0) due to error (30)
E/SELinux (12776): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/SQLiteDatabase(12701): Failed to open database '/data/user/0/com.samsung.android.snote/databases/Snote.db'.
E/SQLiteDatabase(12701): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12701): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12701): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12701): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12701): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12701): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12701): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12701): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12701): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12701): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12701): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12701): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12701): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12701): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12701): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:156)
E/SQLiteDatabase(12701): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:2285)
E/SQLiteDatabase(12701): 	at com.samsung.android.snote.model.provider.SNoteProvider.query(SourceFile:751)
E/SQLiteDatabase(12701): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteDatabase(12701): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteDatabase(12701): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase(12701): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err(12701): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err(12701): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err(12701): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err(12701): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err(12701): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err(12701): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err(12701): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err(12701): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err(12701): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err(12701): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err(12701): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
W/System.err(12701): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err(12701): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err(12701): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err(12701): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:156)
W/System.err(12701): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:2285)
W/System.err(12701): 	at com.samsung.android.snote.model.provider.SNoteProvider.query(SourceFile:751)
W/System.err(12701): 	at android.content.ContentProvider.query(ContentProvider.java:987)
W/System.err(12701): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
W/System.err(12701): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
W/System.err(12701): 	at android.os.Binder.execTransact(Binder.java:446)
D/SNoteProvider(12701): message = not an error (code 0): Could not open the database in read/write mode.
D/ResourcesManager(12195): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
E/SQLiteLog(12739): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131138) and mode_t (0) due to error (30)
D/SNoteProvider(12701): ===query=== 
V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.shealth
V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.samsung.android.provider.shootingmodeprovider
D/TP/MmsSmsProvider( 3983): query,matched:12, calling pid = 12651
E/SQLiteLog(12701): (28) failed to open "/data/user/0/com.samsung.android.snote/databases/Snote.db" with flag (131138) and mode_t (0) due to error (30)
,D/ResourcesManager(12195): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
D/TP/MmsSmsProvider( 3983): match 12:Elapsed time : 5.746 ms
D/ResourcesManager(12232): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
E/SQLiteDatabase(12739): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase(12739): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12739): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12739): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12739): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12739): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12739): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12739): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12739): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12739): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12739): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12739): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteDatabase(12739): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteDatabase(12739): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteDatabase(12739): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase(12739): 	at android.os.Binder.execTransact(Binder.java:446)
W/ResourcesManager(12232): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/SQLiteOpenHelper(12739): Couldn't open filter.db for writing (will try read-only):
E/SQLiteOpenHelper(12739): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12739): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12739): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12739): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12739): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12739): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12739): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12739): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12739): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12739): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12739): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteOpenHelper(12739): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteOpenHelper(12739): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteOpenHelper(12739): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteOpenHelper(12739): 	at android.os.Binder.execTransact(Binder.java:446)
D/ResourcesManager(12232): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
W/ResourcesManager(12232): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/SQLiteOpenHelper(12739): Opened filter.db in read-only mode
W/ResourcesManager(12232): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/Mms/MmsApp(12651): [end]    onCreate() consume time = 11.2655
E/SQLiteLog(12739): (284) automatic index on titles(filter_id)
D/UsbHostManager( 3522): usbDeviceRemoved : /dev/bus/usb/001/001
D/TimaKeyStoreProvider(12776): TimaSignature is unavailable
E/UsbHostManager( 3522): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
D/ResourcesManager(12195): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
D/ActivityThread(12776): Added TimaKeyStore provider
D/ResourcesManager(12232): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/SQLiteLog(11237): (28) failed to open "/data/data/com.sec.spp.push/databases/registration_db" with flag (131138) and mode_t (0) due to error (30)
,D/Mms/FreeMessageStatusReceiver(12651): onReceive, action : android.intent.action.PACKAGE_REMOVED
,E/DropBoxManagerService( 3522): Can't write: system_app_crash
E/DropBoxManagerService( 3522): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3522): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3522): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3522): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3522): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3522): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3522): 	... 5 more
E/DropBoxManagerService( 3522): Can't write: system_app_crash
E/DropBoxManagerService( 3522): java.io.FileNotFoundException: /data/system/dropbox/drop195.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3522): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3522): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3522): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3522): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3522): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3522): 	... 5 more
E/SQLiteDatabase(11237): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase(11237): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(11237): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(11237): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(11237): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(11237): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(11237): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(11237): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(11237): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(11237): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(11237): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(11237): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(11237): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(11237): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(11237): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(1,1237): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase(11237): 	at com.sec.spp.push.i.c.d(Unknown Source)
E/SQLiteDatabase(11237): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase(11237): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase(11237): 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
E/SQLiteDatabase(11237): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(11237): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(11237): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(11237): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(11237): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(11237): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(11237): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SPPClientService(11237): [c] [getAppId()] SQLiteException with message =not an error (code 0): Could not open the database in read/write mode.
,D/Mms/Conversation(12651): [start]    init() consume time = 178.752542
D/MtpClient(12249): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(12249): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
I/EventHub( 3522): Removing device '/dev/input/event10' due to inotify event
E/SQLiteDatabase(12701): Failed to open database '/data/user/0/com.samsung.android.snote/databases/Snote.db'.
E/SQLiteDatabase(12701): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12701): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12701): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12701): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12701): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12701): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12701): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12701): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12701): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12701): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12701): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12701): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12701): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12701): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12701): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:156)
E/SQLiteDatabase(12701): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:2285)
E/SQLiteDatabase(12701): 	at com.samsung.android.snote.model.provider.SNoteProvider.query(SourceFile:751)
E/SQLiteDatabase(12701): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteDatabase(12701): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteDatabase(12701): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase(12701): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err(12701): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err(12701): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err(12701): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err(12701): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err(12701): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err(12701): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err(12701): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err(12701): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err(12701): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err(12701): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err(12701): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
W/System.err(12701): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err(12701): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err(12701): 	at android,.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err(12701): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:156)
W/System.err(12701): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:2285)
W/System.err(12701): 	at com.samsung.android.snote.model.provider.SNoteProvider.query(SourceFile:751)
W/System.err(12701): 	at android.content.ContentProvider.query(ContentProvider.java:987)
W/System.err(12701): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
W/System.err(12701): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
W/System.err(12701): 	at android.os.Binder.execTransact(Binder.java:446)
D/SNoteProvider(12701): message = not an error (code 0): Could not open the database in read/write mode.
,V/Common  (12701): getScreenSize 1440 2560
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12232): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager(12232): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/Zygote  (12804): MountEmulatedStorage()
,E/Zygote  (12804): v2
I/libpersona(12804): KNOX_SDCARD checking this for 10039
I/libpersona(12804): KNOX_SDCARD not a persona
,I/SELinux (12804): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/EventHub( 3522): Removing device '/dev/input/event7' due to inotify event
I/SELinux (12804): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=12804 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12804): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(12232): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager(12232): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/Mms/DraftCache(12651): [end]    rebuildCache consume time = 139.284959
,D/ResourcesManager(12232): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/ResourcesManager(12232): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/EventHub( 3522): Removing device '/dev/input/event8' due to inotify event
,D/Mms/DownloadManager(12651): Service state changed: Bundle[mParcelledData.dataSize=692]
,D/Mms/DownloadManager(12651): roaming ------> false, mSimSlot = 0
D/ResourcesManager(12195): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/Mms/TelephonyUtils(12651): getSubId from simSlot 0, return Value = -1
,D/Mms/DownloadManager(12651): roaming -> false (slotId = 0)
D/Mms/DownloadManager(12651): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(12651): auto download without roaming -> true
D/Mms/DownloadManager(12651): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager(12651): mAutoDownload ------> true
,D/ResourcesManager(12232): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/Mms/FreeMessageReceiverService(12651): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService(12651): onHandleIntent: ACTION_PACKAGE_REMOVED
,W/ResourcesManager(12232): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/EventHub( 3522): Removing device '/dev/input/event9' due to inotify event
,D/TimaKeyStoreProvider(12804): TimaSignature is unavailable
,D/ActivityThread(12804): Added TimaKeyStore provider
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/TP/MmsSmsProvider( 3983): deleteConversation threadId: 9223372036854775807
,E/SharedPreferencesImpl( 4469): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/GoogleAnalyticsPlayLogs.xml to backup file /data/data/com.google.android.gms/shared_prefs/GoogleAnalyticsPlayLogs.xml.bak
,D/ResourcesManager(12232): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/EventHub( 3522): Removing device '/dev/input/event11' due to inotify event
,D/ResourcesManager(12776): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,E/Zygote  (12820): MountEmulatedStorage()
E/Zygote  (12820): v2
I/libpersona(12820): KNOX_SDCARD checking this for 10190
I/libpersona(12820): KNOX_SDCARD not a persona
,I/SELinux (12820): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12820): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12820): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12820 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
I/EventHub( 3522): Removing device '/dev/input/event12' due to inotify event
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12232): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager(12232): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(12232): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,E/SQLiteLog(12776): (28) failed to open "/data/data/com.samsung.helphub/databases/search.db" with flag (131138) and mode_t (0) due to error (30)
W/ResourcesManager(12232): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/EventHub( 3522): Removing device '/dev/input/event13' due to inotify event
,E/SQLiteDatabase(12776): Failed to open database '/data/data/com.samsung.helphub/databases/search.db'.
E/SQLiteDatabase(12776): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12776): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12776): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12776): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12776): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12776): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12776): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12776): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12776): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12776): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12776): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12776): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12776): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12776): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12776): 	at com.samsung.helphub.search.SearchProvider.onCreate(SearchProvider.java:63)
E/SQLiteDatabase(12776): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(12776): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(12776): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(12776): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(12776): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(12776): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12776): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12776): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12776): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12776): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12776): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12776): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12776): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12776): Couldn't open search.db for writing (will try read-only):
E/SQLiteOpenHelper(12776): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12776): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12776): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12776): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12776): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12776): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12776): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12776): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12776): 	at android.database.,sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12776): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12776): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12776): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12776): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12776): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12776): 	at com.samsung.helphub.search.SearchProvider.onCreate(SearchProvider.java:63)
E/SQLiteOpenHelper(12776): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteOpenHelper(12776): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteOpenHelper(12776): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteOpenHelper(12776): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteOpenHelper(12776): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteOpenHelper(12776): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12776): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12776): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12776): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12776): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12776): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12776): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12776): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/SQLiteOpenHelper(12776): Opened search.db in read-only mode
,E/Zygote  (12835): MountEmulatedStorage()
E/Zygote  (12835): v2
I/libpersona(12835): KNOX_SDCARD checking this for 1000
I/libpersona(12835): KNOX_SDCARD not a persona
,I/SELinux (12835): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.android.settings for broadcast com.android.settings/.TactileAssistBroadcastReceiver: pid=12835 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (12835): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/TimaKeyStoreProvider(12820): TimaSignature is unavailable
,E/SELinux (12835): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(12232): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ActivityThread(12820): Added TimaKeyStore provider
,W/ResourcesManager(12232): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager( 3522): Killing 11732:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,I/EventHub( 3522): Removing device '/dev/input/event14' due to inotify event
,D/TimaKeyStoreProvider(12835): TimaSignature is unavailable
,D/ActivityThread(12835): Added TimaKeyStore provider
,I/Process (12756): Sending signal. PID: 12756 SIG: 9
,I/Process (11578): Sending signal. PID: 11578 SIG: 9
,D/ResourcesManager(12820): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,I/TapandpayWidget:TanpandpayAppWidgetProvider(12820): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(12820): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,I/TapandpayWidget:Utils(12820): Clear T&P info.
,D/TapandpayWidget:TanpandpayAppWidgetProvider(12820): Widget is not attached.
,D/ResourcesManager(12804): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
I/ActivityManager( 3522): Killing 11196:com.sec.android.soagent/u0a38 (adj 13): bgCount ##31
,D/ResourcesManager(12835): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(12835): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(12835): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.

```
