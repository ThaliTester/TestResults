#### Test 51074821f72e61a_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2418): stay LED for fully charged
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:2
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
D/AndroidRuntime( 6763): 
D/AndroidRuntime( 6763): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6763): CheckJNI is OFF
D/AndroidRuntime( 6763): setted country_code = Poland
D/AndroidRuntime( 6763): setted countryiso_code = PL
D/AndroidRuntime( 6763): setted sales_code = PLS
D/AndroidRuntime( 6763): readGMSProperty: start
D/AndroidRuntime( 6763): readGMSProperty: already setted!!
D/AndroidRuntime( 6763): readGMSProperty: end
D/AndroidRuntime( 6763): addProductProperty: start
D/dalvikvm( 6763): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6763): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6763): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6763): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6763): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6763): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6763): failed to load memtrack module: -2
D/dalvikvm( 6763): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6763): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2418): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2418): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  pkgName : ACTIVITY_RESUME_BOOSTER@4
I/SurfaceFlinger( 1920): id=19 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1920): id=20 createSurf (16x16),-1 flag=20004, EimLayer
W/ActivityManager( 2418): mDVFSHelper.acquire()
I/SELinux ( 6787): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6787):  
D/PointerIcon( 2418): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2418): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2418): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2418): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6763): Shutting down VM
D/dalvikvm( 6763): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 6787): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6787):  
I/SELinux ( 6787):  
I/SELinux ( 6787): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6787): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6787): >>>>> Normal User
E/dalvikvm( 6787): >>>>> com.test.thalitest [ userId:0 | appId:10452 ]
E/SELinux ( 6787): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 6787): in addTimaSignatureService
D/TimaKeyStoreProvider( 6787): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6787): Added TimaKesytore provider
V/WindowManager( 2418): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SQLiteSecureOpenHelper( 4127): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4127): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (8/10)
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (-2/10)
D/Launcher( 2776): onTrimMemory. Level: 20
D/dalvikvm( 6787): GC_CONCURRENT freed 3009K, 32% free 9562K/13904K, paused 2ms+1ms, total 17ms
D/dalvikvm( 6787): WAIT_FOR_CONCURRENT_GC blocked 15ms
V/WebViewChromium( 6787): Binding Chromium to the background looper Looper (main, tid 1) {42a881f0}
I/chromium( 6787): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 6787): Initializing chromium process, renderers=0
W/chromium( 6787): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 6787): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 6787): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6787): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 6787): Mali API Version : 401
,I/Mali    ( 6787): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 6787): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 6787): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 6787): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 6787): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 6787): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 6787): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/StatusBarManagerService( 2418): tr p:6787,o:f
W/dalvikvm( 6787): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 6787): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 6787): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 6787): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 6787): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 6787): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 6787): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 6787): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 6787): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6787): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 6787): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 6787): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 6787): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2418): semi p:6787,o:f
,I/SurfaceFlinger( 1920): id=21 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2418): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2418): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2418): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2418): setMouseCustomIcon IconType is same.101
,D/PointerIcon( 2418): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2418): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 6787): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 6787): Enabling debug mode 0
,W/AwContents( 6787): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/AwContents( 6787): nativeOnDraw failed; clearing to background color.
D/CustomFrequencyManagerService( 2418): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  pkgName : ACTIVITY_RESUME_BOOSTER@8
D/CustomFrequencyManagerService( 2418): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2418): mDVFSHelper.release()
W/IInputConnectionWrapper( 6787): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 6787): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 6787): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42a7eec8
,D/dalvikvm( 6787): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42a7eec8
D/jxcore_app_log( 6787): JniHelper::setJavaVM(0x41fe0220), pthread_self() = 2027439832
,D/JX-Cordova( 6787): jxcore cordova android initializing
I/dalvikvm( 6787): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 6787): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 6787): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 6787): GC_CONCURRENT freed 1289K, 19% free 11345K/13960K, paused 2ms+2ms, total 23ms
,D/dalvikvm( 6787): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,D/dalvikvm( 6787): GC_CONCURRENT freed 1922K, 18% free 14897K/18164K, paused 3ms+2ms, total 44ms
,D/dalvikvm( 6787): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/CustomFrequencyManagerService( 2418): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 6787): GC_FOR_ALLOC freed 5412K, 31% free 16204K/23152K, paused 50ms, total 53ms
,D/dalvikvm( 6787): GC_CONCURRENT freed 6616K, 32% free 17674K/25724K, paused 2ms+9ms, total 55ms
,D/dalvikvm( 6787): WAIT_FOR_CONCURRENT_GC blocked 42ms
,D/dalvikvm( 6787): GC_FOR_ALLOC freed 1600K, 33% free 17386K/25724K, paused 51ms, total 51ms
,I/dalvikvm-heap( 6787): Grow heap (frag case) to 21.864MB for 3767174-byte allocation
,D/dalvikvm( 6787): GC_FOR_ALLOC freed 2489K, 37% free 18575K/29404K, paused 48ms, total 48ms
,W/jxcore-log( 6787): Initializing JXcore engine
,W/jxcore-log( 6787): JXcore engine is ready
,W/jxcore-log( 6787): Starting JXcore engine
,W/jxcore-log( 6787): Platform android
W/jxcore-log( 6787): 
,W/jxcore-log( 6787): Process ARCH arm
W/jxcore-log( 6787): 
,D/TimaService( 2418): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2418): TimaServiceHandler.handleMessage what =1
,D/TimaService( 2418): TIMA: checkEvent, operation: 50000 subject: 10000
I/TLC_TIMA_PKM_initialize( 2418): initializing...
I/TLC_TIMA_PKM_initialize( 2418): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 2418): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2418): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2418): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2418): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2418): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2418): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2418): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2418): device_id = 0x0
I/TZ: mc_tlc_communication( 2418): tlc_open() was called
I/TZ: mc_tlc_communication( 2418): Opening MobiCore device
I/TZ: mc_tlc_communication( 2418): Allocating WSM for TCI
I/TZ: mc_tlc_communication( 2418): Opening the session
,I/TZ: mc_tlc_communication( 2418): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2418): Trustlet response is completed
,I/PowerManagerService( 2418): [PWL] Off : 75s ago
I/PowerManagerService( 2418): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2418): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2418): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2418, ws=null) (elapsedTime=200)
,I/jxcore-log( 6787): JXcore Cordova bridge is ready!
I/jxcore-log( 6787): 
,W/jxcore-log( 6787): JXcore engine is started
,I/chromium( 6787): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6787): Turning radios to true
I/jxcore-log( 6787): 
,D/dalvikvm( 2418): GC_EXPLICIT freed 3675K, 57% free 24287K/55604K, paused 8ms+13ms, total 162ms
,W/ActivityManager( 2418): Permission Denial: getCurrentUser() from pid=6787, uid=10452 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 2418): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 2418): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6787, uid=10452 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 2418): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/BluetoothManagerService( 2418): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:620)
W/BluetoothManagerService( 2418): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService( 2418): 	at android.os.Binder.execTransact(Binder.java:404)
W/BluetoothManagerService( 2418): 	at dalvik.system.NativeStart.run(Native Method)
E/DevicePolicyManagerService( 2418): getAllowBluetoothMode - value retunrs : 2
,D/BluetoothManagerService( 2418): foregroundUser: 0
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,E/BluetoothManagerService( 2418): Package is exist.
,I/WifiManager( 6787): packageName : com.test.thalitest
,I/WifiManager( 6787): setWifiEnabled : true
,I/WifiService( 2418): setWifiEnabled: true pid=6787, uid=10452
,W/ActivityManager( 2418): Permission Denial: getCurrentUser() from pid=6787, uid=10452 requires android.permission.INTERACT_ACROSS_USERS
D/BluetoothAdapterState( 5024): CURRENT_STATE=OFF, MSG = USER_TURN_ON
I/BluetoothAdapterState( 5024): Bluetooth adapter state changed: 10-> 11
W/WifiService( 2418): Failed getting userId using ActivityManagerNative
W/WifiService( 2418): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6787, uid=10452 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2418): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2418): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2418): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2418): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2418): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2418): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapterService( 5024): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5024): updateAdapterState state is 11
D/BluetoothAdapterService( 5024): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 5024): Autoconnection is available 
D/BluetoothAdapterService( 5024): updateAdapterState prevState = 10newState = 11
D/BtConfig.SecureMode( 5024): isSecureModeOn:false
D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5024): isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/InputMethodManagerService( 2418): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 2418): [BT Setting State] State =11
W/BluetoothAdapterService( 5024): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/PhoneApp( 2753): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 11
W/BluetoothAdapterService( 5024): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.android.bluetooth.hid.HidService
I/SamsungIME( 2999): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
W/BluetoothAdapterService( 5024): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
I/QuickConnect[1.1][2] ( 4997): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_ON
W/BluetoothAdapterService( 5024): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.android.bluetooth.pan.PanService
E/WifiHW  ( 2418): ##################### set firmware type 0 #####################
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/WifiHW  ( 1915): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
E/WifiHW  ( 1915): Cannot open "/data/.cid.info": No such file or directory
I/WifiHW  ( 1915): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
E/WifiHW  ( 1915): TEMP_FAILURE_RETRY complete
,D/SoftapController( 1915): Softap fwReload - Ok
,W/BluetoothAdapterService( 5024): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5024): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5024): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5024): Unable to stop service com.android.bluetooth.gatt.GattService. Invalid state: 12
W/BluetoothAdapterService( 5024): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 5024): Not skipping com.android.bluetooth.hfp.HeadsetService
D/CommandListener( 1915): Setting iface cfg
,D/CommandListener( 1915): Trying to bring down wlan0
,D/WifiHW  ( 2418): Skip the update_ctrl_interface
,D/WifiHW  ( 2418): Skip the update_ctrl_interface
,E/WifiHW  ( 2418): supplicant_name : p2p_supplicant
,D/BluetoothNotiBroadcastReceiver( 5491): onReceive
,D/WifiMonitor( 2418): startMonitoring(wlan0) with mConnected = false
W/BluetoothAdapterService( 5024): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5024): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 6840): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6840):  
,I/wpa_supplicant( 6839): wpa_supplicant v2.1-devel-4.4.22014-07-16/12:43:14
,I/wpa_supplicant( 6839): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 6839): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 6839): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 6839): getIMSI cannot open file
,E/wpa_supplicant( 6839): Interworking config: - SIM READ ERROR
,D/HeadsetService( 5024): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 5024): classInitNative: succeeds
D/HeadsetStateMachine( 5024): Version 1.5
,D/HeadsetStateMachine( 5024): make
,W/BluetoothAdapterService( 5024): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5024): Not skipping com.android.bluetooth.hid.HidService
,E/HeadsetStateMachine( 5024): # of Max HF connection is 2
,W/BluetoothAdapterService( 5024): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5024): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5024): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
I/SELinux ( 6840): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6840):  
I/SELinux ( 6840):  
,I/SELinux ( 6840): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,E/SELinux ( 6840): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6840): >>>>> Normal User
E/dalvikvm( 6840): >>>>> pl.k2.droidoaudioteka [ userId:0 | appId:10066 ]
,W/BluetoothAdapterService( 5024): Not skipping com.android.bluetooth.pan.PanService
,E/SELinux ( 6840): [DEBUG] seapp_context_lookup: seinfoCategory = default
,I/dalvikvm( 6840): Enabling JNI app bug workarounds for target SDK version 7...
,D/QuickConnect[1.1][2] ( 4997): HeadsetProfile.onServiceConnected - Bluetooth service connected
W/BluetoothAdapterService( 5024): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,D/TimaKeyStoreProvider( 6840): in addTimaSignatureService
D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 5024): Not skipping com.android.bluetooth.map.BluetoothMapService
D/TimaKeyStoreProvider( 6840): Cannot add TimaSignature Service, License check Failed
W/BluetoothAdapterService( 5024): check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5024): Not skipping com.broadcom.bt.service.sap.SapService
D/ActivityThread( 6840): Added TimaKesytore provider
,I/bluedroid( 5024): get_profile_interface handsfree
,I/BluetoothAdapterState( 5024): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAtMessage( 5024): createCMTIContentObservers
,D/HeadsetStateMachine( 5024): Enter Disconnected: -2
,E/HeadsetStateMachine( 5024): set to mRemoteBrsf = 0
,D/BluetoothA2dp( 2418): Proxy object connected
D/HeadsetStateMachine( 5024): map size, before remove : 0
D/HeadsetStateMachine( 5024): map size, after remove: 0
,D/HeadsetStateMachine( 5024): mNextConnectingDevice : null
D/A2dpService( 5024): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 5024): classInitNative: succeeds
,D/BluetoothA2dp( 4997): Proxy object connected
,D/A2dpStateMachine( 5024): make
,D/QuickConnect[1.1][2] ( 4997): A2dpProfile.onServiceConnected - Bluetooth service connected
,I/bluedroid( 5024): get_profile_interface a2dp
D/BluetoothA2dp( 4127): Proxy object connected
,I/GKI_LINUX( 5024): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 5024): Enter Disconnected: -2
,I/BluetoothAvrcpServiceJni( 5024): classInitNative: succeeds
,I/wpa_supplicant( 6839): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 6839): getIMSI cannot open file
,E/wpa_supplicant( 6839): Interworking config: - SIM READ ERROR
I/wpa_supplicant( 6839): >>>>> Not GET KEY, IV <<<<<
,I/bluedroid( 5024): get_profile_interface avrcp
,I/wpa_supplicant( 6839): rfkill: Cannot open RFKILL control device
,D/MediaFocusControl( 2418): >>> registerRemoteControlDisplay
,I/BluetoothHidServiceJni( 5024): classInitNative: succeeds
,D/BluetoothInputDevice( 4997): Proxy object connected
D/HidService( 5024): Received start request. Starting profile...
I/bluedroid( 5024): get_profile_interface hidhost
,D/HidService( 5024): setHidService(): set to: null
,D/QuickConnect[1.1][2] ( 4997): HidProfile.onServiceConnected - Bluetooth service connected
,I/BluetoothHealthServiceJni( 5024): classInitNative: succeeds
,D/HealthService( 5024): Received start request. Starting profile...
,I/bluedroid( 5024): get_profile_interface health
,I/BluetoothPanServiceJni( 5024): classInitNative(L105): succeeds
,D/BluetoothPan( 2418): BluetoothPAN Proxy object connected
D/PanService( 5024): Received start request. Starting profile...
D/BluetoothPanServiceJni( 5024): initializeNative(L110): pan
,I/bluedroid( 5024): get_profile_interface pan
,D/BluetoothTethering( 2418): got CMD_CHANNEL_HALF_CONNECTED
,D/HeadsetStateMachine( 5024): Try to query the phonestate on bind
,D/BluetoothPhoneService( 2753): handleMessage: 4
,V/BluetoothPhoneService( 2753): Call state Converted2: IDLE/IDLE -> 6
,W/BluetoothHeadset( 2753): Proxy not attached to service
,D/BluetoothMapService( 5024): Received start request. Starting profile...
,W/BluetoothMapMasInstance( 5024): mAccount : null
,I/BluetoothSAPServiceJni( 5024): classInitNative(L204): succeeds
D/SapService( 5024): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 5024): initializeNative(L209): sap
,I/bluedroid( 5024): get_profile_interface sap
,D/HeadsetPhoneState( 5024): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetStateMachine( 5024): Proxy object connected
,D/HeadsetStateMachine( 5024): Disconnected process message: 11
,D/HeadsetPhoneState( 5024): sendDeviceDataStateChanged
D/HeadsetStateMachine( 5024): Disconnected process message: 20
D/HeadsetPhoneState( 5024): Signal level : previous=0 curr=0
D/BluetoothAdapterService( 5024): Profile still not running:com.broadcom.bt.service.sap.SapService
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5024): Disconnected process message: 10
D/HeadsetPhoneState( 5024): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 5024): Disconnected process message: 11
D/BluetoothAdapterService( 5024): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5024): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5024): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5024): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5024): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterState( 5024): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 5024): enable
,D/GKI_LINUX( 5024): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,E/bt-btif ( 5024): Calling BTA_HhEnable
,E/bt-btif ( 5024): btif_storage_get_adapter_property service_mask:0x160040
E/BluetoothServiceJni( 5024): populateRssiValuesNative
I/bluedroid( 5024): getModelRssiValues
,E/BluetoothServiceJni( 5024): model_rssi_values_callback: low = -75, mid = -65, high = 127
,E/BluetoothRemoteDevices( 5024): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BtConfig.SecureMode( 5024): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5024): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 241
,E/BluetoothRemoteDevices( 5024): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 10
,D/BtConfig.SecureMode( 5024): isSecureModeOn:false
D/dalvikvm( 6840): GC_CONCURRENT freed 2989K, 32% free 9580K/13900K, paused 6ms+9ms, total 56ms
,D/dalvikvm( 6840): WAIT_FOR_CONCURRENT_GC blocked 17ms
,E/BluetoothRemoteDevices( 5024): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 241
E/BluetoothRemoteDevices( 5024): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
D/BtConfig.SecureMode( 5024): isSecureModeOn:false
E/BluetoothRemoteDevices( 5024): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 241
E/BluetoothRemoteDevices( 5024): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,D/BtConfig.SecureMode( 5024): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5024): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 241
,E/BluetoothRemoteDevices( 5024): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,D/BtConfig.SecureMode( 5024): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5024): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 241
,E/BluetoothRemoteDevices( 5024): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/BtConfig.SecureMode( 5024): isSecureModeOn:false
E/BluetoothRemoteDevices( 5024): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 241
E/bt-btif ( 5024): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 5024): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
E/bt-btif ( 5024): btif_sock_init: !radio_req && !rfc_init
,D/IOP_DB_BT( 5024): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT( 5024): db_open: db_open : handle 2010289196l, read 9734 bytes onto local cache
,D/IOP_DB_BT( 5024): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 5024): db_query: result 1
,I/        ( 5024): iop_db_open: iop_db_open status 0
,I/bte_conf( 5024): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 5024): [1] primary_record=1 vendor_id=0x0075 vendor_id_source=0x0001 product_id=0x0100 version=0x0200
,I/bte_conf( 5024): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 5024): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothAdapterState( 5024): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5024): ScanMode =  20
,D/BluetoothAdapterProperties( 5024): State =  11
D/BtConfig.SecureMode( 5024): isSecureModeOn:false
D/BtConfig.SecureMode( 5024): isSecureModeOn:false
D/BtConfig.SecureMode( 5024): isSecureModeOn:false
D/BtConfig.SecureMode( 5024): isSecureModeOn:false
D/BtConfig.SecureMode( 5024): isSecureModeOn:false
D/BtConfig.SecureMode( 5024): isSecureModeOn:false
,I/BluetoothAdapterState( 5024): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 5024): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5024): updateAdapterState state is 12
,D/BluetoothAdapterService( 5024): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothA2dp( 4127): onBluetoothStateChange: up=true
,D/BluetoothAdapterService(1118414160)( 5024): Register RemoteMessageListener
,D/HeadsetService( 5024): registerMessageListener
D/BluetoothAdapterService( 5024): Autoconnection is available 
D/BluetoothAdapterService( 5024): updateAdapterState prevState = 11newState = 12
,D/BluetoothAdapterService( 5024): starting service from this receiver
,D/BluetoothA2dp( 2418): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 4997): onBluetoothStateChange: up=true
,D/BluetoothInputDevice( 4997): onBluetoothStateChange: up=true
D/HeadsetStateMachine( 5024): Disconnected process message: 70
,D/HeadsetStateMachine( 5024): processRegisterMessageListener : 2, com.android.bluetooth.btservice.RemoteDevices$1@42aee8b8
,D/BluetoothAdapterService( 5024): initWakeLock, pfd lock: {ParcelFileDescriptor: FileDescriptor[85]}, pfd unlock: {ParcelFileDescriptor: FileDescriptor[86]}
,D/bluedroid( 5024): init_wake_lock lock_fd:85, unlock_fd:86
W/InputMethodManagerService( 2418): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2418): [BT Setting State] State =12
,I/InputMethodManagerService( 2418): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/BluetoothAdapterService(1118414160)( 5024): Get Bonded Devices being called
W/ContextImpl( 5024): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.startService:506 com.android.bluetooth.btservice.AdapterService.updateAdapterState:653 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
D/PhoneApp( 2753): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 12
I/SamsungIME( 2999): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothHeadset( 2753): registerListener : 11, listenercom.android.phone.PhoneGlobals$MessageListener@42bdca98, true
D/BluetoothHeadset( 2753): registerMessageListener
I/QuickConnect[1.1][2] ( 4997): BluetoothHelper.ACTION_STATE_CHANGED - STATE_ON
W/System.err( 6840): java.io.FileNotFoundException: /system/etc/vold.fstab: open failed: ENOENT (No such file or directory)
I/BluetoothPbapService( 5024): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
I/BluetoothPbapService( 5024): Handler(): got msg=1
,D/HeadsetService( 5024): registerMessageListener
D/HeadsetService( 5024): registerMessageListener
D/HeadsetStateMachine( 5024): Disconnected process message: 70
,D/BluetoothPanServiceJni( 5024): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
,D/HeadsetStateMachine( 5024): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@42b4a8b0
,I/BluetoothAdapterState( 5024): Entering On State from state = 11
,D/PhoneApp( 2753): registerMessageListener
,V/BluetoothPbapService( 5024): PBAP Service initSocket try: 0
,W/System.err( 6840): 	at libcore.io.IoBridge.open(IoBridge.java:409)
,W/System.err( 6840): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 6840): 	at java.util.Scanner.<init>(Scanner.java:158)
W/System.err( 6840): 	at java.util.Scanner.<init>(Scanner.java:138)
,W/System.err( 6840): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.readVoldFile(StorageOptions.java:107)
,W/System.err( 6840): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.determineStorageOptions(StorageOptions.java:31)
W/System.err( 6840): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:81)
W/System.err( 6840): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:129)
W/System.err( 6840): 	at pl.k2.droidoaudioteka.ui.AudiotekaApplication.onCreate(AudiotekaApplication.java:171)
W/System.err( 6840): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 6840): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 6840): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 6840): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 6840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6840): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6840): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 6840): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 6840): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 6840): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
,W/System.err( 6840): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 6840): 	at dalvik.system.NativeStart.main(Native Method)
,W/System.err( 6840): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
,D/BluetoothAdapterService(1118414160)( 5024): Get Bonded Devices being called
,W/BluetoothAdapter( 5024): getBluetoothService() called with no BluetoothManagerCallback
,D/GKI_LINUX( 5024): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/BluetoothMapMasInstance( 5024): set MAP SDP message type : 1
,W/System.err( 6840): 	at libcore.io.Posix.open(Native Method)
,W/System.err( 6840): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 6840): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 6840): 	... 20 more
,D/STATUSBAR-IconMerger( 2578): checkOverflow(336), More:false, Req:false Child:2
E/BluetoothServiceJni( 5024): SOCK FLAG = 1 ***********************
D/GKI_LINUX( 5024): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
W/BluetoothAdapter( 5024): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothPbapService( 5024): PBAP Socket is BluetoothServerSocket
E/BluetoothServiceJni( 5024): SOCK FLAG = 3 ***********************
W/System.err( 6840): file res dir: /data/data/pl.k2.droidoaudioteka/files
W/System.err( 6840): Excternal dir: /mnt/sdcard
,V/MaBo    ( 6840): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6840): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6840): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6840): moge zapisać w resDir?true
,D/GKI_LINUX( 5024): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1118414160)( 5024): Get Bonded Devices being called
,V/MaBo    ( 6840): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6840): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6840): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,D/dalvikvm( 2735): GC_CONCURRENT freed 1823K, 23% free 10906K/14128K, paused 6ms+11ms, total 85ms
,W/GAV2    ( 6840): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GAV2    ( 6840): Thread[main,5,main]: ExceptionReporter created, original handler is pl.k2.droidoaudioteka.common.helpers.AudiotekaExceptionHandler
,I/AUDIOTEKA_GA( 6840): init tracking...
,I/AUDIOTEKA_GA( 6840): app started!
,I/BugSenseHandler( 6840): Registering default exceptions handler
,E/DataBuffer( 2735): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42ab2d10)
,D/AuthorizationBluetoothService( 2849): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/BugSenseHandler( 6840): Flushing...
,I/BugSenseHandler( 6840): Registering default exceptions handler
,I/knox    ( 4940): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,I/DownloadService( 6840): Tworzenie serwisu - onCreate()
,I/DownloadService( 6840): Start serwisu - onStart()
W/ContextImpl( 4940): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 4940): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 4940): KNOXAgentService : onCreate()
,D/knox    ( 4940): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 4940): KNOXAgentService. startJobThread() start
D/knox    ( 4940): KNOXAgentService. JobThread()
D/knox    ( 4940): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 4940): KNOXAgentService. startJobThread() wait
,I/SELinux ( 6882): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6882):  
,I/BugSenseHandler( 6840): Registering default exceptions handler
,D/knox    ( 4940): KNOXAgentService : onDestroy().
,D/knox    ( 4940): ModuleBase.cancelAllAlarmManageModule()
I/SELinux ( 6882): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6882):  
I/SELinux ( 6882):  
,I/SELinux ( 6882): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6882): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6882): >>>>> Normal User
,E/dalvikvm( 6882): >>>>> tv.peel.smartremote [ userId:0 | appId:10165 ]
,E/SELinux ( 6882): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 6882): in addTimaSignatureService
,I/PlayerService( 6840): Tworzenie serwisu - onCreate()
,I/MediaFocusControl( 2418):   Remote Control   registerMediaButtonIntent() for PendingIntent{4315f780: PendingIntentRecord{42bc85f0 pl.k2.droidoaudioteka broadcastIntent}}
,I/BugSenseHandler( 6840): Flushing...
,I/BugSenseHandler( 6840): Registering default exceptions handler
,V/KeyguardUpdateMonitor( 2578): handleSetGenerationId(g=2, clear=true)
,D/TimaKeyStoreProvider( 6882): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6882): Added TimaKesytore provider
,V/AUDIOTEKA_MB( 6840): new AudioManagerFocusWrapper in playerservice oncreate
,I/PlayerService( 6840): Start serwisu - onStart()
,D/dalvikvm( 6882): GC_CONCURRENT freed 2993K, 32% free 9580K/13900K, paused 4ms+2ms, total 33ms
,D/dalvikvm( 6882): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
,E/Tethering( 2418): No numeric data
,D/Tethering( 2418): sendTetherStateChangedBroadcast 1, 0, 0
I/ConnectivityService( 2418): defaultVal : 1, tetherEnabledInSettings : true
,I/wpa_supplicant( 6839): wlan0: Setting scan request: 0 sec 100000 usec
,D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/NtpTrustedTime( 2418): forceRefresh() from cache miss
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
,D/NtpTrustedTime( 2418): forceRefresh Fail.
V/NetworkStats( 2418): performPollLocked(flags=0x1)
,V/NetworkStats( 2418): performPollLocked() took 24ms
D/NtpTrustedTime( 2418): forceRefresh() from cache miss
D/NtpTrustedTime( 2418): forceRefresh Fail.
,I/wpa_supplicant( 6839): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 6839): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 6839): rfkill: Cannot open RFKILL control device
,D/Tethering( 2418): interfaceLinkStateChanged p2p0, true
,D/Tethering( 2418): interfaceStatusChanged p2p0, true
,D/Tethering( 2418): interfaceLinkStateChanged p2p0, true
,D/Tethering( 2418): interfaceStatusChanged p2p0, true
,I/wpa_supplicant( 6839): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,W/ContextImpl( 5491): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/wpa_supplicant( 6839): P2P: initialized channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
I/wpa_supplicant( 6839): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 6839): Skip scan - bUseNetwork false
,D/WifiStateMachine( 2418): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
D/WifiNative( 2418): callSECApiString - ID [21]
,I/wpa_supplicant( 6839): HOTSPOT20_ENABLE called
,I/wpa_supplicant( 6839): wlan0: HS20_DISABLED_COMPLETE normal
,D/WifiNative( 2418): callSECApiInt - ID [65]
,D/LocalBluetoothProfileManager( 5491): Adding local A2DP profile
,E/WifiConfigStore( 2418): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/LocalBluetoothProfileManager( 5491): Adding local HEADSET profile
W/ContextImpl( 5491): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
,E/BluetoothHeadset( 5491): BTStateChangeCB is registed
,D/WifiNative( 2418): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 6839): USE_NETWORK : USE_NETWORK ON
,E/BluetoothHeadset( 5491): BluetoothHeadset service is binded
,W/ContextImpl( 5491): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
I/wpa_supplicant( 6839): reset timer : RESET_TIMER 0
I/wpa_supplicant( 6839): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 6839): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 6839): First Scan Start
,I/wpa_supplicant( 6839): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings( 5276): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ContextImpl( 5491): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/Bluetoothsap( 5491): bindService called to Bluetooth SAP Service
E/WifiStateMachine( 2418): Set the Nv default ccode
,W/ContextImpl( 5491): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,D/WifiStateMachine( 2418): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,E/WifiStateMachine( 2418): HS20_DISABLED_COMPLETEnormal
W/ContextImpl( 5491): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
,D/LocalBluetoothProfileManager( 5491): PANU : true
,D/LocalBluetoothProfileManager( 5491): Adding local MAP profile
D/WifiP2pService( 2418): P2pDisabledState{ what=131203 }
,D/BluetoothMap( 5491): Create BluetoothMap proxy object
W/ContextImpl( 5491): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,I/System.out( 6840): Thread-604(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6840): Thread-607(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/wpa_supplicant( 6839): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
D/CommandListener( 1915): Setting iface cfg
,D/CommandListener( 1915): Trying to bring up p2p0
,D/WifiMonitor( 2418): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 2418): P2pEnablingState
D/WifiP2pService( 2418): P2pEnablingState{ what=147457 }
D/WifiP2pService( 2418): P2p socket connection successful
D/WifiP2pService( 2418): P2pEnabledState
W/ContextImpl( 5491): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,E/WifiStateMachine( 2418): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiP2pService( 2418): sending p2p connection changed broadcast: IDLE
D/WifiDisplayController( 2418): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController( 2418): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 2418): disconnect
D/WifiDisplayController( 2418): updateConnection
D/WifiDisplayController( 2418): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,I/System.out( 6840): Thread-607(ApacheHTTPLog):isShipBuild true
,D/QuickConnect[1.1][2] ( 4997): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
,I/System.out( 6840): Thread-607(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/WifiDisplayAdapter( 2418): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/ContextImpl( 5491): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/QuickConnect[1.1][2] ( 4997): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
W/WifiP2pStateTracker( 2418): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayAdapter( 2418): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiDisplayController( 2418): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/QuickConnect[1.1][2] ( 4997): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
D/WifiP2pService( 2418): DeviceAddress: 02:e0:6d
,D/WifiDisplayController( 2418): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: S5mini-1
D/WifiDisplayController( 2418):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiDisplayController( 2418):  primary type: 10-0050F204-5
D/WifiDisplayController( 2418):  secondary type: null
D/WifiDisplayController( 2418):  wps: 0
D/WifiDisplayController( 2418):  grpcapab: 0
D/WifiDisplayController( 2418):  devcapab: 0
D/WifiDisplayController( 2418):  status: 3
D/WifiDisplayController( 2418):  wfdInfo: null
D/WifiDisplayController( 2418):  groupownerAddress: null
D/WifiDisplayController( 2418):  GOdeviceName: null
D/WifiDisplayController( 2418):  interfaceAddress: 
D/WifiDisplayController( 2418):  SConnectInfo : null
D/QuickConnect[1.1][2] ( 4997): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
D/Bluetoothsap( 5491): bindService called to Bluetooth SAP Service
D/LocalBluetoothProfileManager( 5491): LocalBluetoothProfileManager construction complete
,D/WifiP2pService( 2418): sending p2p persistent groups changed broadcast
,D/WifiP2pService( 2418): InactiveState
,D/WifiP2pService( 2418): InactiveState{ what=139287 }
,D/WifiP2pService( 2418): P2pEnabledState{ what=139287 }
,D/QuickConnect[1.1][2] ( 4997): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
,D/WifiP2pService( 2418): DefaultState{ what=139287 }
I/System.out( 6840): Thread-604(ApacheHTTPLog):isShipBuild true
I/System.out( 6840): Thread-604(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/DockEventReceiver( 5491): finishStartingService: stopping service
,I/System.out( 6840): pool-1-thread-2 calls detatch()
I/System.out( 6840): pool-1-thread-1 calls detatch()
,W/BugSenseHandler( 6840): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
,W/BugSenseHandler( 6840): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
,D/BluetoothNotiBroadcastReceiver( 5491): onReceive
,D/BtConfig.SecureMode( 5024): isSecureModeOn:false
,D/AuthorizationBluetoothService( 2849): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 2849): Proximity feature is not enabled.
,D/BluetoothA2dp( 5491): Proxy object connected
,D/A2dpProfile( 5491): Bluetooth service connected
,D/HeadsetProfile( 5491): Bluetooth service connected
,D/Bluetoothsap( 5491): BluetoothSAP Proxy object connected
,W/BluetoothAdapter( 5024): getBluetoothService() called with no BluetoothManagerCallback
,D/SapProfile( 5491): Bluetooth service connected
E/BluetoothServiceJni( 5024): SOCK FLAG = 0 ***********************
D/Bluetoothsap( 5491): getConnectedDevices()
,D/GKI_LINUX( 5024): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,I/BtOppRfcommListener( 5024): Accept thread started.
,D/BluetoothInputDevice( 5491): Proxy object connected
,D/HidProfile( 5491): Bluetooth service connected
,D/BluetoothPan( 5491): BluetoothPAN Proxy object connected
,D/PanProfile( 5491): Bluetooth service connected
,D/BluetoothMap( 5491): Proxy object connected
,D/MapProfile( 5491): Bluetooth service connected
,I/System.out( 6840): pool-1-thread-2 calls detatch()
,W/BugSenseHandler( 6840): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
,D/BluetoothPbap( 5491): Proxy object connected
D/PbapServerProfile( 5491): Bluetooth service connected
D/Bluetoothsap( 5491): BluetoothSAP Proxy object connected
D/SapProfile( 5491): Bluetooth service connected
,D/Bluetoothsap( 5491): getConnectedDevices()
,I/ActivityManager( 2418): Killing 5754:com.android.providers.calendar/u0a45 (adj 15): empty #43
,I/knox    ( 4940): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 4940): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 4940): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 4940): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
,D/GKI_LINUX( 5024): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/knox    ( 4940): KNOXAgentService : onCreate()
,D/knox    ( 4940): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 4940): KNOXAgentService. startJobThread() start
,D/knox    ( 4940): KNOXAgentService. JobThread()
D/knox    ( 4940): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 4940): KNOXAgentService. startJobThread() wait
,D/knox    ( 4940): KNOXAgentService : onDestroy().
,D/knox    ( 4940): ModuleBase.cancelAllAlarmManageModule()
,D/NearbySettings( 5491): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 5491): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 5491): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 5491): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 5491): DMSUtil.isNetworkConnected - flag-null, state-null
I/System.out( 6840): pool-1-thread-1 calls detatch()
I/NearbySettings( 5491): DMSUtil.isNetworkConnected - WIFI: IDLE
W/BugSenseHandler( 6840): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
I/NearbySettings( 5491): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5491): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 5491): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5491): MountReceiver.mPrefHandler - 7002
,D/FileShare-Server( 5876): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Server( 5876): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,I/wpa_supplicant( 6839): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,I/wpa_supplicant( 6839): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 6839): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 6839): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2462 MHz)
,I/wpa_supplicant( 6839): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 6839): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,E/WifiStateMachine( 2418): Error! unhandled message{ when=-4ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 6839): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 6839): Associated with C0.AA.48
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
,D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
,D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 6839): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 6839): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 6839): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 6839): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 6839): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
,D/WifiNative( 2418): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 6919): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6919):  
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 6919): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6919):  
I/SELinux ( 6919):  
,I/SELinux ( 6919): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6919): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6919): >>>>> Normal User
,E/dalvikvm( 6919): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 6919): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 6919): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6919): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6919): Added TimaKesytore provider
,D/WifiP2pService( 2418): InactiveState{ what=143375 }
,D/WifiP2pService( 2418): P2pEnabledState{ what=143375 }
,D/dalvikvm( 6919): GC_CONCURRENT freed 2989K, 32% free 9583K/13900K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 6919): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/System.out( 6919): Inside WakeupProvider
,I/System.out( 6919): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 6919): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 6919): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 6919): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,I/dhcpcd  ( 6933): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6933): bssid match
,D/NearbySettings( 5491): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5491): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5491): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 5491): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5491): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5491): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5491): MountReceiver.mPrefHandler - 7002
,I/ActivityManager( 2418): Killing 5705:com.android.calendar/u0a144 (adj 15): empty #43
,D/DialogFlow( 6919): initQueue()
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(336), More:false, Req:false Child:2
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiP2pService( 2418): InactiveState{ what=143375 }
,D/WifiP2pService( 2418): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2418): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2418): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2418): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2418): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2418): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2418): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
D/ConnectivityService( 2418): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2418): net.tcp.usercfg.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2418): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,D/ConnectivityService( 2418): handleConnectivityChange: setting default proxy info 
,D/NearbySettings( 5491): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 5491): MountReceiver.onReceive - Keep current state
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.112 lookup 2 prio 150 2>&1
D/TimaService( 2418): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
D/TimaService( 2418): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/NearbySettings( 5491): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5491): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5491): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 5491): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5491): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5491): MountReceiver.onReceive - Keep current state
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/NtpTrustedTime( 2418): forceRefresh() from cache miss
V/NetworkStats( 2418): updateIfacesLocked()
V/NetworkStats( 2418): performPollLocked(flags=0x1)
,V/NetworkStats( 2418): performPollLocked() took 24ms
,D/NearbySettings( 5491): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 5491): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger( 1920): id=22 createSurf (1x1),1 flag=4, Uoast
,D/NtpTrustedTime( 2418): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1447852646840 mCachedNtpElapsedRealtime : 318035 mCachedNtpCertainty : 15
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
V/NetworkStats( 2418): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/PowerManagerService( 2418): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2418
,E/Watchdog( 2418): !@Sync 10
,D/PackageManager( 2418): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/Tethering( 2418): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2418): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 2418): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
D/STATUSBAR-NetworkController( 2578): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2578): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2578): updateDataNetType()
,D/STATUSBAR-NetworkController( 2578): NoService, mRoamingIconId = 0
D/        ( 2418): Setting time of day to sec=1447852647
D/        ( 2418): Trying to open a file
D/        ( 2418): File Open Success
D/        ( 2418): File Close Success
I/        ( 2418): DRM_TIME_PATH CHMOD 660 for resetState done 
,V/AlarmManager( 2418): waitForAlarm result :65536
,I/PCWCLIENTTRACE_PushUtil( 6102): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6102): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6102): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6102): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 4608): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/DBG_DM  ( 4608): [3.19.140541][Line:609][onReceive] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_DM  ( 4608): [3.19.140541][Line:214][xdmAgentTaskHandler] XEVENT_DM_INIT
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,I/DBG_DM  ( 4608): [3.19.140541][Line:432][xdmInitAdpWaitSystemRootingCheck] Check completed.
,I/DBG_DM  ( 4608): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/NotificationMgr( 2753): updateNotificationsAtStartup()...
,D/NotificationMgr( 2753): - start call log query...
D/StatusBar-DoNotDistrub( 2578): Received intent with android.intent.action.TIME_SET action
D/StatusBar-DoNotDistrub( 2578): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Settings( 2418): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Parcel  ( 2418): nm 23
,D/StatusBar-DoNotDistrub( 2578): sendBroadcast android.intent.action.DORMANT_MODE_OFF
I/AudioService( 2418): getStreamVolume 5 index 110
I/PrGenericPlugin( 1923): [A] ENTER onAcquireDrmInfo : 0x482
I/PrGenericPlugin( 1923): [A] LEAVE onAcquireDrmInfo : 0x482
,I/DrmEventService( 2418):  no response from SecureClock 
D/StatusBar-DoNotDistrub( 2578): The STREAM NOTIFICATION volume is 0
D/STATUSBAR-StatusBarManagerService( 2418): manageDisableList what=0x0 pkg=com.android.systemui
,D/STATUSBAR-NotificationService( 2418): received android.intent.action.DORMANT_MODE_OFF
D/LightsService( 2418): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2418) 
,I/SensorManagerA( 2418): getReportingMode :: sensor.mType = 5
,D/LightsService( 2418): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/Sensors ( 2418): LightSensor setDelay = 200000000
D/Sensors ( 2418): LightSensor setSensorDelay = 200000000
D/Sensors ( 2418): Light sensor flush: not enabled 0
D/Sensors ( 2418): LightSensor enable = 1
D/Sensors ( 2418): LightSensor enableSensor = 1
,D/SensorManager( 2418): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
D/NotificationMgr( 2753): call log query complete.
D/NotificationMgr( 2753): call log cursor count : 0
D/NotificationMgr( 2753): call log cursor count2 : null
I/DBG_DM  ( 4608): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
I/DBG_DM  ( 4608): [3.19.140541][Line:78][xdmFeatureGetBearerSettingFromCSCFotaDataBase] 
,I/SQLiteSecureOpenHelper( 4127): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4127): getDatabaseLocked(b,b,pwd)...
,I/dalvikvm( 4608): Total arena pages for JIT: 11
,I/dalvikvm( 4608): Total arena pages for JIT: 12
,I/dalvikvm( 4608): Total arena pages for JIT: 13
I/dalvikvm( 4608): Total arena pages for JIT: 14
,I/dalvikvm( 4608): Total arena pages for JIT: 15
I/dalvikvm( 4608): Total arena pages for JIT: 16
,I/dalvikvm( 4608): Total arena pages for JIT: 17
,I/DBG_DM  ( 4608): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,I/DBG_DM  ( 4608): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/DBG_DM  ( 4608): [3.19.140541][Line:5949][xdbGetFUMOInitiatedType] Initiated Type: 2
,I/SELinux ( 6987): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6987):  
,I/dalvikvm( 4608): Total arena pages for JIT: 18
,I/DBG_DM  ( 4608): [3.19.140541][Line:119][xdmInitAdpEXTInit] nStatus [220]
,I/DBG_DM  ( 4608): [3.19.140541][Line:463][xdmGetEnableLiveDemoFromCSCFeature] enable LiveDemo : false
,E/DBG_DM  ( 4608): Warning!!! [3.19.140541][Line:65][xdmInitAdpGetSIMLockState] SIM Status is not ready
,I/SELinux ( 6987): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6987):  
I/SELinux ( 6987):  
,I/SELinux ( 6987): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6987): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6987): >>>>> Normal User
,E/dalvikvm( 6987): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
,I/SQLiteSecureOpenHelper( 4127): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4127): getDatabaseLocked(b,b,pwd)...
,E/SELinux ( 6987): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/Sensors ( 2418): LightSensor enable = 0
,D/Sensors ( 2418): LightSensor enableSensor = 0
,D/SensorManager( 2418): unregisterListener ::   
D/LightsService( 2418): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2418): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/TimaKeyStoreProvider( 6987): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6987): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6987): Added TimaKesytore provider
,I/DBG_DM  ( 4608): [3.19.140541][Line:261][xdmInitAdpEXTInit] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 4608): [3.19.140541][Line:271][xdmAgentTaskHandler] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 4608): [3.19.140541][Line:1854][xdmAgentCheckResumeNoti] 
,I/DBG_DM  ( 4608): [3.19.140541][Line:769][xdmUIEvent] XUI_DL_UPDATE_START
I/DBG_DM  ( 4608): [3.19.140541][Line:369][handleMessage] event ->214
,I/DBG_DM  ( 4608): [3.19.140541][Line:318][xdmBroadcastGetIsSavedNfcMode] m_IsSavedNfcMode : false
,I/DBG_DM  ( 4608): [3.19.140541][Line:546][xuiAdpGetUpdateReport] Get bUpdateReport = false
,I/DBG_DM  ( 4608): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 4608): [3.19.140541][Line:2008][xdmCallUiFotaInstall] 
,I/SELinux ( 7001): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7001):  
,W/ContextImpl( 4608): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 com.wssyncmldm.XDMService.xdmCallUiFotaInstall:2023 com.wssyncmldm.XDMService$1.handleMessage:372 android.os.Handler.dispatchMessage:102 
,I/DBG_DM  ( 4608): [3.19.140541][Line:729][xdmUIEvent] XUI_DL_UPDATE_CONFIRM
,I/SELinux ( 7001): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7001):  
I/SELinux ( 7001):  
,I/SELinux ( 7001): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7001): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7001): >>>>> Normal User
,E/dalvikvm( 7001): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7001): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 13% free 9506K/10880K, paused 2ms+4ms, total 37ms
,I/DBG_DM  ( 4608): [3.19.140541][Line:1320][xdmCheckIdleScreen] Idle Screen : false
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 13% free 9506K/10880K, paused 3ms+3ms, total 25ms
,D/TimaKeyStoreProvider( 7001): in addTimaSignatureService
,I/DBG_DM  ( 4608): [3.19.140541][Line:890][xdmUnRegisterBatteryReceiver] 
,E/DBG_DM  ( 4608): Warning!!! [3.19.140541][Line:898][xdmUnRegisterBatteryReceiver] didn't register
,E/DBG_DM  ( 4608): Warning!!! [3.19.140541][Line:899][xdmUnRegisterBatteryReceiver] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.XDMService$3@42b956f0
,D/TimaKeyStoreProvider( 7001): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7001): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 13% free 9506K/10880K, paused 2ms+2ms, total 28ms
,I/DBG_DM  ( 4608): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,D/dalvikvm( 6987): GC_CONCURRENT freed 2994K, 32% free 9581K/13904K, paused 112ms+2ms, total 148ms
,D/dalvikvm( 6987): WAIT_FOR_CONCURRENT_GC blocked 31ms
,I/GAV2    ( 6840): Thread[GAThread,5,main]: connecting to Analytics service
,W/ContextImpl( 6840): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:529 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/DBG_DM  ( 4608): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/GAV2    ( 6840): Thread[GAThread,5,main]: connect: bindService returned true for Intent { act=com.google.android.gms.analytics.service.START (has extras) }
,D/GAV2    ( 6840): Thread[main,5,main]: service connected, binder: android.os.BinderProxy@42cfc9e8
,D/GAV2    ( 6840): Thread[main,5,main]: bound to service
,I/GAV2    ( 6840): Thread[main,5,main]: Connected to service
,I/GAV2    ( 6840): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 6840): Thread[GAThread,5,main]: putHit called
,I/GAV2    ( 6840): Thread[GAThread,5,main]: Sending hit to service
,D/dalvikvm( 7001): GC_FOR_ALLOC freed 3021K, 32% free 9552K/13900K, paused 50ms, total 118ms
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2418): sendNotification(1) - 4
,W/ResourceType( 2578): Attempt to retrieve bag 0x01030068 which is invalid or in a cycle.
,W/ResourceType( 2578): Attempt to retrieve bag 0x01030067 which is invalid or in a cycle.
,D/ProgressBar( 2578): setProgressDrawable drawableHeight = 12
,D/dalvikvm( 3436): GC_EXPLICIT freed 1905K, 22% free 11741K/14972K, paused 13ms+9ms, total 106ms
,D/ProgressBar( 2578): setProgressDrawable drawableHeight = 12
,D/PhoneStatusBar( 2578): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@42adec10
,D/dalvikvm( 7001): GC_CONCURRENT freed 236K, 32% free 9566K/13900K, paused 7ms+5ms, total 104ms
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,E/dalvikvm( 6987): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a
,W/dalvikvm( 6987): VFY: unable to resolve new-instance 406 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm( 6987): VFY: replacing opcode 0x22 at 0x0000
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/dalvikvm( 6987): Unable to resolve superclass of Lal; (749)
,W/dalvikvm( 6987): Link of class 'Lal;' failed
E/dalvikvm( 6987): Could not find class 'al', referenced from method b.a
W/dalvikvm( 6987): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
,D/dalvikvm( 6987): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 6987): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 6987): Link of class 'Lan;' failed
E/dalvikvm( 6987): Could not find class 'an', referenced from method b.a
,W/dalvikvm( 6987): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
,D/dalvikvm( 6987): VFY: replacing opcode 0x22 at 0x002a
,I/dalvikvm( 6987): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm( 6987): VFY: unable to resolve virtual method 5407: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 6987): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 6987): Could not find method android.view.View.getTransitionName, referenced from method b.a
W/dalvikvm( 6987): VFY: unable to resolve virtual method 5231: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 6987): VFY: replacing opcode 0x6e at 0x0006
,W/dalvikvm( 6987): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
,E/dalvikvm( 6987): Could not find class 'android.app.RemoteInput[]', referenced from method b.a
W/dalvikvm( 6987): VFY: unable to resolve new-array 12200 ([Landroid/app/RemoteInput;) in Lb;
,D/dalvikvm( 6987): VFY: replacing opcode 0x23 at 0x0005
,D/dalvikvm( 2418): GC_EXPLICIT freed 2461K, 56% free 24549K/55604K, paused 12ms+20ms, total 208ms
W/WifiP2pStateTracker( 2418): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2418): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2418):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2418): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2418): updateSourceRoutes : no source routing conditions
,D/dalvikvm( 6987): DexOpt: unable to opt direct call 0x090f at 0x0e in Lb;.a
,W/dalvikvm( 6987): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 6987): Link of class 'Lal;' failed
D/dalvikvm( 6987): DexOpt: unable to opt direct call 0x068d at 0x08 in Lb;.a
,W/dalvikvm( 6987): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 6987): Link of class 'Lan;' failed
D/dalvikvm( 6987): DexOpt: unable to opt direct call 0x0802 at 0x2c in Lb;.a
,D/dalvikvm( 6987): DexOpt: unable to opt direct call 0x0957 at 0x13 in Lb;.a
,I/dalvikvm( 6987): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method dyp.a
,W/dalvikvm( 6987): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6987): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 2849): GC_EXPLICIT freed 732K, 21% free 11020K/13900K, paused 4ms+6ms, total 52ms
,I/SELinux ( 7028): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7028):  
,D/dalvikvm( 6987): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6987): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 6987): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 6987): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 6987): VFY: unable to resolve instance field 46
,D/dalvikvm( 6987): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 6987): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6987): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6987): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 6987): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 6987): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 6987): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42b43d60
,D/dalvikvm( 6987): Added shared lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42b43d60
,D/dalvikvm( 6987): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42b43d60, skipping init
,D/dalvikvm( 6987): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x42b43d60
D/dalvikvm( 6987): Added shared lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x42b43d60
,V/JNIHelp ( 6987): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/SELinux ( 7028): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7028):  
I/SELinux ( 7028):  
,I/SELinux ( 7028): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7028): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7028): >>>>> Normal User
,E/dalvikvm( 7028): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7028): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/btif_config_util( 5024): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/TimaKeyStoreProvider( 7028): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7028): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7028): Added TimaKesytore provider
,D/dalvikvm( 6987): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42b43d60
,D/dalvikvm( 6987): Shared lib '/data/app-lib/com.google.android.gms-4/libgmscore.so' already loaded in same CL 0x42b43d60
,D/dalvikvm( 6987): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x42b43d60
,D/dalvikvm( 6987): Shared lib '/data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42b43d60
,D/libgps  ( 2418): agps_ril_update_network_state: Waiting for IPC connection...
D/dalvikvm( 7028): GC_CONCURRENT freed 3014K, 32% free 9562K/13904K, paused 3ms+3ms, total 24ms
,D/dalvikvm( 7028): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/KLMS-2.3.201 : ( 7028): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7028): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1447852648802
,I/KLMS-2.3.201 : ( 7028): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/dalvikvm( 6987): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 6987): VFY: unable to resolve static method 1165: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 6987): VFY: replacing opcode 0x71 at 0x0046
,I/ProviderInstaller( 6987): Installed default security provider GmsCore_OpenSSL
,I/dalvikvm( 6987): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
W/dalvikvm( 6987): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6987): VFY: replacing opcode 0x6e at 0x000d
,I/SELinux ( 7049): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7049):  
,I/LocationTagReadyService( 3247): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3247): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3247): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3247): [Slink platform] The state of Slink geocode service is true
,I/dalvikvm( 6987): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
,W/dalvikvm( 6987): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 6987): VFY: replacing opcode 0x6e at 0x0220
,I/SELinux ( 7049): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7049):  
I/SELinux ( 7049):  
,I/SELinux ( 7049): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7049): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7049): >>>>> Normal User
,E/dalvikvm( 7049): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7049): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/GallerySearchProvider( 3374): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,E/YouTube MDX( 6987): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/TimaKeyStoreProvider( 7049): in addTimaSignatureService
,D/dalvikvm( 6987): DexOpt: --- BEGIN 'ads549175451.jar' (bootstrap=0) ---
,D/TimaKeyStoreProvider( 7049): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7049): Added TimaKesytore provider
,D/dalvikvm( 2719): GC_EXPLICIT freed 316K, 29% free 9956K/13888K, paused 6ms+5ms, total 68ms
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 6987): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/SELinux ( 7074): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7074):  
,I/System.out( 7001): Thread-606(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7001): Thread-606(ApacheHTTPLog):isShipBuild true
,I/System.out( 7001): Thread-606(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/SELinux ( 7074): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7074):  
I/SELinux ( 7074):  
,I/SELinux ( 7074): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7074): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7074): >>>>> Normal User
,E/dalvikvm( 7074): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7074): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7074): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7074): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7074): Added TimaKesytore provider
,D/dalvikvm( 7049): GC_CONCURRENT freed 2986K, 32% free 9576K/13896K, paused 6ms+2ms, total 25ms
,D/dalvikvm( 7049): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/SO_AGENT( 7049): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7049): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/dalvikvm( 7074): GC_CONCURRENT freed 2996K, 32% free 9577K/13904K, paused 4ms+1ms, total 21ms
,D/dalvikvm( 7074): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/SA      ( 6263): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,D/dalvikvm( 6987): GC_CONCURRENT freed 1898K, 24% free 10750K/13976K, paused 5ms+28ms, total 98ms
,I/SA      ( 6263): [BDLM] already registered in spp
I/SA      ( 6263): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 6263): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,V/KVNProvider( 7074): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7074): getFindoCursor query string : 
,I/SA      ( 6263): [SLFUCHKMGR] constructor called
,V/KVNProvider( 7074): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 6263): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6263): [OR] == isSIMCardReady false ==
,I/SA      ( 6263): [SCU] == networkStateCheck == true
I/SA      ( 6263): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6263): isChinaCountryCode : false
,I/SA      ( 6263): [OR] == networkStateCheck true ==
,I/SA      ( 6263): [OR] GetMyCountryZoneTask
,I/SA      ( 6263): [OR] onReceive END
,D/dalvikvm( 6202): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42ad8f80, skipping init
,I/SA      ( 6263): [SRS] prepareGetMyCountryZone
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 6047): Other Intent
,I/SecureStorage( 6202): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 1964): [INFO]: SPID(0x00000004)Credentials: uid 1000, gid 1000, pid 6202
,I/SecureStorage( 1964): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
,I/SA      ( 6263): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SELinux ( 7102): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7102):  
,I/SELinux ( 7102): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7102):  
I/SELinux ( 7102):  
,I/SELinux ( 7102): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7102): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7102): >>>>> Normal User
,E/dalvikvm( 7102): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7102): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 7066): DexOpt: load 7ms, verify+opt 156ms, 194052 bytes
,I/dalvikvm( 6987): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 6987): VFY: unable to resolve virtual method 2614: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 6987): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 6987): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 6987): VFY: unable to resolve virtual method 2615: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 6987): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 6987): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 6987): VFY: unable to resolve virtual method 2622: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 6987): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 6987): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 6987): VFY: unable to resolve virtual method 2623: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6987): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 6987): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method agv.getLeanbackLaunchIntentForPackage
W/dalvikvm( 6987): VFY: unable to resolve virtual method 2639: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 6987): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 6987): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method agv.getPackageInstaller
W/dalvikvm( 6987): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6987): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 6987): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method agv.getUserBadgedDrawableForDensity
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/dalvikvm( 6987): VFY: unable to resolve virtual method 2659: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6987): VFY: replacing opcode 0x6e at 0x0002
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
I/dalvikvm( 6987): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method agv.getUserBadgedIcon
W/dalvikvm( 6987): VFY: unable to resolve virtual method 2660: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 6987): VFY: replacing opcode 0x6e at 0x0002
W/ContextImpl( 6987): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
I/dalvikvm( 6987): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method agv.getUserBadgedLabel
W/dalvikvm( 6987): VFY: unable to resolve virtual method 2661: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
D/dalvikvm( 6987): VFY: replacing opcode 0x6e at 0x0002
D/TimaKeyStoreProvider( 7102): in addTimaSignatureService
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 6987): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 6987): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
I/SA      ( 6263): [SSP] query invoked
D/TimaKeyStoreProvider( 7102): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7102): Added TimaKesytore provider
,I/System.out( 7001): AsyncTask #1 calls detatch()
,I/jxcore-log( 6787): Attempting to connect to the test coordinator server
I/jxcore-log( 6787): 
,W/InstanceID/Rpc( 6987): Found 10012
,D/dalvikvm( 6987): DexOpt: --- END 'ads549175451.jar' (success) ---
,D/dalvikvm( 6987): DEX prep '/data/data/com.google.android.youtube/cache/ads549175451.jar': unzip in 10ms, rewrite 609ms
,I/SA      ( 6263): [TPMU] GetMccFromDB : null
,I/SA      ( 6263): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6263): [TPM] isNoProxy(default) : true
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 6987): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/SA      ( 6263): [RC New] Execute method=[GET] start
,D/dalvikvm( 7102): GC_CONCURRENT freed 2995K, 32% free 9581K/13904K, paused 5ms+2ms, total 28ms
,D/dalvikvm( 7102): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/System.err( 7001): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7001): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7001): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7001): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7001): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7001): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7001): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 7001): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 7001): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7001): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 7001): Caused by: java.lang.NullPointerException
W/System.err( 7001): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7001): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7001): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7001): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7001): 	... 8 more
,I/ActivityManager( 2418): Killing 5758:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/com.samsung.app( 7102): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/libgps  ( 2418): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2418): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2418): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2418): agps_ril_update_network_availability: Waiting for IPC connection...
,D/com.samsung.app( 7102): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7102): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7102): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7102): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7102): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5222): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7102): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5222): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7102): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5222): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7102): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7102): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2418): Killing 5687:com.sec.phone/1001 (adj 15): empty #43
,I/SELinux ( 7140): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7140):  
,I/ActivityManager( 2418): Killing 5276:com.google.android.talk/u0a109 (adj 15): empty #43
I/SELinux ( 7140): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7140):  
I/SELinux ( 7140):  
I/SELinux ( 7140): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7140): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7140): >>>>> Normal User
E/dalvikvm( 7140): >>>>> com.samsung.android.internal.headlines [ userId:0 | appId:10110 ]
E/SELinux ( 7140): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7140): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7140): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7140): Added TimaKesytore provider
,I/System.out( 6987): Thread-660(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6987): Thread-660(ApacheHTTPLog):isShipBuild true
,I/System.out( 6987): Thread-660(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 7140): GC_CONCURRENT freed 2999K, 32% free 9577K/13904K, paused 4ms+1ms, total 25ms
,D/dalvikvm( 7140): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/HeadlinesChannelApplication( 7140): [onCreate]
,D/Headlines( 7140): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 7140): getCountryCode(): countryCode = PL
,D/Headlines( 7140): Breath.onCreate
,I/SELinux ( 7161): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7161):  
D/HeadlinesCardManager( 7140): HeadlinesCardManager : constructor
E/HeadlinesCardManager( 7140): HeadlinesCardManager : ctor = image_cache size is 42MB
D/SA Version( 7140): CardProvider Library : 13
D/MagazineService::CardProviderContentProvider( 6308): insertProvider: provider already exists.: com.samsung.android.app.headlines
D/MagazineService::CardProviderContentProvider( 6308): insertProvider: provider is updated.: com.samsung.android.app.headlines
I/SELinux ( 7161): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7161):  
I/SELinux ( 7161):  
I/SELinux ( 7161): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7161): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7161): >>>>> Normal User
E/dalvikvm( 7161): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 7140): registerCardProvider: provider already exists.
,E/SELinux ( 7161): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/Headlines( 7140): HeadlinesDataCenter ctor
I/Headlines( 7140): HeadlinesDataCenter. mLocale = en_US
,D/HeadlinesChannelUtil( 7140): getCountryCode(): countryCode = PL
,D/HeadlinesCardManager( 7140): HeadlinesCardManager : constructor welcome :YES
,D/TimaKeyStoreProvider( 7161): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7161): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7161): Added TimaKesytore provider
,D/Headlines( 7140): Breath timer started. interval : 30000
,D/Headlines( 7140): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,V/AlarmManager( 2418): waitForAlarm result :8
D/HeadlinesCardManager( 7140): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 7140): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 7140): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 7140): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 7140): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 7140): requestUpdateNewsWelcomeCard !!! no welcome card
,I/ActivityManager( 2418): Killing 5778:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/SurfaceFlinger( 1920): id=22 Removed Uoast (10/11)
,I/SurfaceFlinger( 1920): id=22 Removed Uoast (-2/11)
D/PowerManagerService( 2418): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2418) eventTime = 321498
D/PowerManagerService( 2418): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2418 (0x0)
D/PowerManagerService( 2418): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2418, ws=WorkSource{1000}) (elapsedTime=3448)
,D/dalvikvm( 7161): GC_CONCURRENT freed 3003K, 32% free 9575K/13904K, paused 3ms+2ms, total 46ms
,D/dalvikvm( 7161): WAIT_FOR_CONCURRENT_GC blocked 41ms
,I/SurfaceFlinger( 1920): id=23 createSurf (1x1),1 flag=4, Uoast
,E/WifiStateMachine( 2418): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/PowerManagerService( 2418): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2418
,I/System.out( 6263): Thread-566(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,V/WebViewChromium( 7161): Binding Chromium to the background looper Looper (main, tid 1) {42a88150}
,I/chromium( 7161): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7161): Initializing chromium process, renderers=0
,I/System.out( 6263): Thread-566(ApacheHTTPLog):isShipBuild true
,I/System.out( 6263): Thread-566(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/chromium( 7161): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,I/System.out( 6987): Thread-660 calls detatch()
,D/libEGL  ( 7161): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7161): loaded /system/lib/egl/libGLESv1_CM_mali.so
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/libEGL  ( 7161): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7161): Mali API Version : 401
,I/Mali    ( 7161): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/SecureStorage( 1964): [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 1964): [INFO]: SPID(0x00000004)PID: 6202, TID: 6227
,W/GAV2    ( 7161): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 7161): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/SecureStorage( 6202): [INFO]: SPID(0x00000000)Processing data has been completed
,I/NSApplication( 7161): Starting up...
,I/ActivityManager( 2418): Killing 5954:com.android.defcontainer/u0a6 (adj 15): empty #43
,I/ImageResourceManager( 5643): ImageResourceManager: uninitalized
,I/iu.Environment( 5643): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/QuickConnect[1.1][2] ( 4997): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 4997): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 4997): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42a91e78
,I/SELinux ( 7203): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7203):  
,I/SELinux ( 7203): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7203):  
I/SELinux ( 7203):  
,I/SELinux ( 7203): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7203): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7203): >>>>> Normal User
,E/dalvikvm( 7203): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7203): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7203): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7203): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7203): Added TimaKesytore provider
,D/libgps  ( 2418): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2418): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2418): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/dalvikvm( 6202): Total arena pages for JIT: 11
,I/dalvikvm( 6202): Total arena pages for JIT: 12
,I/dalvikvm( 6202): Total arena pages for JIT: 13
,I/dalvikvm( 6202): Total arena pages for JIT: 14
I/dalvikvm( 6202): Total arena pages for JIT: 15
,I/dalvikvm( 6202): Total arena pages for JIT: 16
,I/dalvikvm( 6202): Total arena pages for JIT: 17
,I/dalvikvm( 3436): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 3436): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 3436): VFY: replacing opcode 0x6e at 0x0033
,D/dalvikvm( 5643): GC_FOR_ALLOC freed 1203K, 29% free 9968K/13896K, paused 202ms, total 204ms
,D/dalvikvm( 7203): GC_CONCURRENT freed 2982K, 31% free 9592K/13900K, paused 6ms+2ms, total 36ms
,D/dalvikvm( 7203): WAIT_FOR_CONCURRENT_GC blocked 31ms
,I/dalvikvm-heap( 5643): Grow heap (frag case) to 13.058MB for 2129936-byte allocation
,D/dalvikvm( 5643): GC_FOR_ALLOC freed <1K, 25% free 12048K/15980K, paused 29ms, total 29ms
,I/iu.UploadsManager( 5643): num queued entries: 0
,I/iu.UploadsManager( 5643): num updated entries: 0
,I/iu.SyncManager( 5643): NEXT; no task
,D/dalvikvm( 5643): GC_CONCURRENT freed 25K, 25% free 12033K/15980K, paused 5ms+47ms, total 96ms
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/DelayedSyncController( 6008): Delaying sync.
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/NtpTrustedTime( 2418): getCachedNtpTime() cache hit
,E/Auth.Api.Credentials( 3436): [CredentialSyncAdapter] Unknown sync event.
,I/SELinux ( 7229): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7229):  
,D/dalvikvm( 2849): null clazz in OP_INSTANCE_OF, single-stepping
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,I/SELinux ( 7229): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7229):  
I/SELinux ( 7229):  
,I/SELinux ( 7229): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7229): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7229): >>>>> Normal User
,E/dalvikvm( 7229): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7229): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm( 5643): GC_FOR_ALLOC freed 121K, 26% free 11936K/15980K, paused 49ms, total 50ms
,D/TimaKeyStoreProvider( 7229): in addTimaSignatureService
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 7229): Cannot add TimaSignature Service, License check Failed
,I/ActivityManager( 2418): Killing 5882:com.google.android.partnersetup/u0a14 (adj 15): empty #43
D/ActivityThread( 7229): Added TimaKesytore provider
D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,I/ActivityManager( 2418): Killing 6077:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/SELinux ( 7243): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7243):  
I/ActivityManager( 2418): Killing 6089:com.android.musicfx/u0a24 (adj 15): empty #43
,W/ActivityManager( 2418): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 7243): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7243):  
I/SELinux ( 7243):  
,I/SELinux ( 7243): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7243): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7243): >>>>> Normal User
,E/dalvikvm( 7243): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7243): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/dalvikvm( 7229): GC_CONCURRENT freed 2993K, 32% free 9579K/13904K, paused 14ms+1ms, total 37ms
,D/dalvikvm( 7229): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/TimaKeyStoreProvider( 7243): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7243): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7243): Added TimaKesytore provider
,D/BadgeProvider( 7229): onCreate
,D/BadgeProvider( 7229): DatabaseHelper
,D/BadgeProvider( 7229): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/dalvikvm( 5643): GC_FOR_ALLOC freed 8K, 21% free 16095K/20148K, paused 38ms, total 39ms
,D/BadgeProvider( 7229): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7229): sendNotify, [notify] : null
D/BadgeProvider( 7229): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7229): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7229): update, [UpdateCount] : 1
,I/SA      ( 6263): [RC New] [v2liruge] api execute + 2101
,I/SA      ( 6263): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6263): AsyncTask #1 calls detatch()
,I/SA      ( 6263): [TPMU] getNetworkMcc : 
,D/dalvikvm( 7243): GC_CONCURRENT freed 3004K, 32% free 9573K/13904K, paused 4ms+12ms, total 42ms
,D/dalvikvm( 7243): WAIT_FOR_CONCURRENT_GC blocked 34ms
,D/Launcher.Model( 2776): reloadBadges entered.
,I/SA      ( 6263): [SCU] saveMccToPreferece Start
,I/SA      ( 6263): [SCU] RegionMCC : 260
,I/SA      ( 6263): [SSP] query invoked
W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/SA      ( 6263): [TPMU] GetMccFromDB : null
,I/SA      ( 6263): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6263): [SCU] saveMccToPreferece End
I/SA      ( 6263): [RC New] executeRequest [v2liruge] end. 2169
,I/SA      ( 6263): [RC New] Execute end
I/SA      ( 6263): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6263): [OR] GetMyCountryZoneTask Success
,I/SELinux ( 7255): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7255):  
I/ActivityManager( 2418): Killing 6115:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,I/SELinux ( 7255): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7255):  
I/SELinux ( 7255):  
,I/SELinux ( 7255): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7255): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7255): >>>>> Normal User
,E/dalvikvm( 7255): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
,E/SELinux ( 7255): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7255): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7255): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7255): Added TimaKesytore provider
,D/dalvikvm( 2418): GC_EXPLICIT freed 1967K, 57% free 24401K/55604K, paused 14ms+16ms, total 246ms
,I/ActivityManager( 2418): Killing 6129:com.sec.android.app.shealth/u0a36 (adj 15): empty #43
,D/dalvikvm( 7255): GC_CONCURRENT freed 3000K, 32% free 9573K/13900K, paused 4ms+2ms, total 31ms
,D/dalvikvm( 7255): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/PicasaService( 3374): start picasa sync
,D/PicasaService( 3374): end picasa sync
,I/dalvikvm( 7255): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
,W/dalvikvm( 7255): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 7255): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 7255): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7255): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7255): VFY: replacing opcode 0x22 at 0x0000
,D/DelayedSyncController( 6008): Delaying sync.
,E/dalvikvm( 7255): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
W/dalvikvm( 7255): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 7255): VFY: replacing opcode 0x22 at 0x0037
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6102): mConnectivityHandler : connected
,W/dalvikvm( 7255): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 7255): Link of class 'Ldqp;' failed
W/dalvikvm( 7255): VFY: unable to find class referenced in signature (Ldqp;)
,W/PCWCLIENTTRACE_AccountUtil( 6102): [hasSamungAccount] - No Samsung Account
,W/dalvikvm( 7255): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7255): Link of class 'Ldqp;' failed
I/dalvikvm( 7255): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 7255): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 7255): VFY: replacing opcode 0x6e at 0x0000
,I/dalvikvm( 2735): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
,W/dalvikvm( 2735): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,E/dalvikvm( 7255): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7255): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7255): VFY: replacing opcode 0x22 at 0x0000
,D/dalvikvm( 2735): VFY: replacing opcode 0x6e at 0x0033
,W/dalvikvm( 7255): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 7255): Link of class 'Ldqp;' failed
,W/dalvikvm( 7255): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7255): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7255): Link of class 'Ldqp;' failed
I/dalvikvm( 7255): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 7255): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
,D/dalvikvm( 7255): VFY: replacing opcode 0x6e at 0x0008
E/dalvikvm( 7255): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 7255): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
,D/dalvikvm( 7255): VFY: replacing opcode 0x1c at 0x0026
,W/dalvikvm( 7255): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7255): Link of class 'Ldqp;' failed
,W/dalvikvm( 7255): VFY: unable to find class referenced in signature (Ldqp;)
,W/dalvikvm( 7255): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 7255): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7255): Link of class 'Ldqp;' failed
,I/dalvikvm( 7255): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 7255): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
,D/dalvikvm( 7255): VFY: replacing opcode 0x6e at 0x0003
W/dalvikvm( 7255): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7255): Link of class 'Lax;' failed
E/dalvikvm( 7255): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 7255): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
,D/dalvikvm( 7255): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 7255): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7255): Link of class 'Laz;' failed
E/dalvikvm( 7255): Could not find class 'az', referenced from method g.a
W/dalvikvm( 7255): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
,D/dalvikvm( 7255): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 7255): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 7255): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7255): VFY: replacing opcode 0x6e at 0x0008
,I/dalvikvm( 7255): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
W/dalvikvm( 7255): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 7255): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 7255): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 7255): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7255): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 7255): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 7255): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
,D/dalvikvm( 7255): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 7255): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 7255): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 7255): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7255): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
W/dalvikvm( 7255): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 7255): VFY: replacing opcode 0x72 at 0x0000
,I/dalvikvm( 7255): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 7255): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 7255): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 7255): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 7255): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
,W/dalvikvm( 7255): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 7255): VFY: replacing opcode 0x23 at 0x0005
,I/dalvikvm( 7255): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
,W/dalvikvm( 7255): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7255): VFY: replacing opcode 0x6e at 0x0009
E/PCWCLIENTTRACE_SecurePreferencesJNI( 6102): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6102): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6102): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6102): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6102): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6102): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6102): [ensureRegistration] - No Samsung account
,W/dalvikvm( 7255): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
,W/dalvikvm( 7255): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
,E/dalvikvm( 7255): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 7255): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
,D/dalvikvm( 7255): VFY: replacing opcode 0x1c at 0x0002
,E/dalvikvm( 7255): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 7255): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 7255): VFY: replacing opcode 0x1f at 0x000c
,D/dalvikvm( 7255): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 7255): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7255): VFY: replacing opcode 0x62 at 0x0006
,D/dalvikvm( 7255): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7255): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
,D/dalvikvm( 7255): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7255): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
,D/dalvikvm( 7255): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
,W/dalvikvm( 7255): Unable to resolve superclass of Lax; (841)
,W/dalvikvm( 7255): Link of class 'Lax;' failed
,D/dalvikvm( 7255): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 7255): Unable to resolve superclass of Laz; (841)
,W/dalvikvm( 7255): Link of class 'Laz;' failed
,D/dalvikvm( 7255): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 7255): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
,D/dalvikvm( 7255): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,D/dalvikvm( 7255): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x42a88638
,D/dalvikvm( 7255): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x42a88638
,I/dalvikvm( 7255): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
W/dalvikvm( 7255): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 7255): VFY: replacing opcode 0x6e at 0x0076
,I/Babel_SMS( 7255): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7255): MmsConfig.loadMmsSettings
I/Babel_SMS( 7255): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/Babel_SMS( 7255): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7255): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7255): MmsConfig.loadFromResources
,E/Babel_SMS( 7255): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7255): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,W/dalvikvm( 7255): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7255): Link of class 'Lfzc;' failed
E/dalvikvm( 7255): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 7255): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
,D/dalvikvm( 7255): VFY: replacing opcode 0x22 at 0x0033
W/dalvikvm( 7255): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7255): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7255): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
,W/dalvikvm( 7255): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,I/dalvikvm( 7255): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 7255): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
,D/dalvikvm( 7255): VFY: replacing opcode 0x74 at 0x006d
,I/dalvikvm( 7255): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 7255): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
,D/dalvikvm( 7255): VFY: replacing opcode 0x6e at 0x0033
I/dalvikvm( 7255): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
,W/dalvikvm( 7255): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
D/dalvikvm( 7255): VFY: replacing opcode 0x6e at 0x0030
,W/dalvikvm( 7255): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7255): Link of class 'Lfzc;' failed
,D/dalvikvm( 7255): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
E/SensorService( 2418): Permission Denial : SEC Private Sensor 
,E/SensorService( 2418): Permission Denial : SEC Private Sensor 
D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,W/Settings( 7255): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7255): startup - clean
,D/dalvikvm( 7255): GC_CONCURRENT freed 1782K, 23% free 10879K/13964K, paused 3ms+5ms, total 34ms
,I/Babel   ( 7255): deleted: false for 0
,I/dalvikvm( 7255): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
,W/dalvikvm( 7255): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7255): VFY: replacing opcode 0x6e at 0x000d
,W/dalvikvm( 7255): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,I/dalvikvm( 7255): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 7255): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
,D/dalvikvm( 7255): VFY: replacing opcode 0x6e at 0x004e
W/dalvikvm( 7255): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7255): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7255): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 7255): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
,D/dalvikvm( 7255): VFY: replacing opcode 0x22 at 0x0071
,W/dalvikvm( 7255): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7255): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7255): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7255): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7255): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 7255): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
,D/dalvikvm( 7255): VFY: replacing opcode 0x1f at 0x0021
,W/dalvikvm( 7255): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 7255): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
,I/dalvikvm( 7255): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/dalvikvm( 7255): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
,D/dalvikvm( 7255): VFY: replacing opcode 0x6e at 0x0074
,I/vclib   ( 7255): onServiceConnected
,W/Babel   ( 7255): Attempted to change video mute state without an active call.
,I/iu.Environment( 3436): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 3436): num queued entries: 0
,I/iu.UploadsManager( 3436): num updated entries: 0
,I/iu.SyncManager( 3436): NEXT; no task
,D/WaitQueueForNetworkActivate( 6407): notifyNetworkActivated
,W/ContextImpl( 6407): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager( 2418): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/dalvikvm( 7255): GC_CONCURRENT freed 845K, 16% free 12078K/14252K, paused 26ms+2ms, total 81ms
,D/dalvikvm( 7255): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 7255): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 7255): GC_FOR_ALLOC freed 824K, 18% free 12616K/15212K, paused 27ms, total 27ms
,I/System.out( 7255): Thread-647(HTTPLog):isShipBuild true
,I/System.out( 7255): Thread-647(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/GCM     ( 2849): GCM config loaded
,D/dalvikvm( 7255): GC_FOR_ALLOC freed 1821K, 24% free 12991K/16900K, paused 42ms, total 42ms
,I/Babel   ( 7255): connection state changed from UNKNOWN to CONNECTED
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/VacuumService( 2849): Vacuum at: now=1447852653550 tag=VacuumService
,D/hcjo    ( 6407): AutoUpdateManager:IDLE:execute
,E/SPPClientService( 5410): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5410): [SystemStateMoniter] Current Time : 324804
,E/SPPClientService( 5410): [SystemStateMoniter] No Connect : false
I/dalvikvm( 6407): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
W/dalvikvm( 6407): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 6407): VFY: replacing opcode 0x6e at 0x0024
,D/InitializeManagerStateMachine( 6407): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6407): exit::IDLE
,D/InitializeManagerStateMachine( 6407): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 6407): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6407): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6407): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6407): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6407): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6407): entry::SUCCESS
,D/hcjo    ( 6407): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/SELinux ( 7307): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7307):  
,D/hcjo    ( 6407): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 13% free 9506K/10880K, paused 2ms+2ms, total 31ms
I/SELinux ( 7307): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7307):  
I/SELinux ( 7307):  
,I/SELinux ( 7307): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7307): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7307): >>>>> Normal User
,E/dalvikvm( 7307): >>>>> com.android.calendar [ userId:0 | appId:10144 ]
,E/SELinux ( 7307): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/hcjo    ( 6407): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6407): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6407): exit::SUCCESS
,D/InitializeManagerStateMachine( 6407): entry::IDLE
,D/TimaKeyStoreProvider( 7307): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7307): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7307): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 13% free 9506K/10880K, paused 2ms+13ms, total 44ms
,I/ActivityManager( 2418): Killing 6147:com.sec.android.service.health/u0a16 (adj 15): empty #43
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 13% free 9506K/10880K, paused 2ms+3ms, total 24ms
,I/SurfaceFlinger( 1920): id=23 Removed Uoast (10/11)
,I/SurfaceFlinger( 1920): id=23 Removed Uoast (-2/11)
,D/PowerManagerService( 2418): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2418) eventTime = 325010
,D/PowerManagerService( 2418): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2418 (0x0)
,D/dalvikvm( 7307): GC_CONCURRENT freed 3004K, 32% free 9569K/13900K, paused 2ms+1ms, total 28ms
,D/dalvikvm( 7307): WAIT_FOR_CONCURRENT_GC blocked 20ms
D/PowerManagerService( 2418): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2418, ws=WorkSource{1000}) (elapsedTime=3474)
,D/BootCompletedReceiver( 2418): onReceive
D/ConnectivityService( 2418): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/ActivityManager( 2418): Killing 6235:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty #43
,D/STATUSBAR-NetworkController( 2578): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2578): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2578): updateDataNetType()
,D/STATUSBAR-NetworkController( 2578): NoService, mRoamingIconId = 0
,D/UdcCache:FPQuery( 3436): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/KLMS-2.3.201 : ( 7028): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/System.out( 3436): Thread-185(HTTPLog):isShipBuild true
,I/System.out( 3436): Thread-185(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/KLMS-2.3.201 : ( 7028): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1447852654128
,I/KLMS-2.3.201 : ( 7028): StateImplV2() : dateTimeChanged() : Wed Nov 18 14:17:34 CET 2015
,I/SELinux ( 7325): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7325):  
,I/SELinux ( 7325): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7325):  
I/SELinux ( 7325):  
,I/SELinux ( 7325): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7325): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7325): >>>>> Normal User
,E/dalvikvm( 7325): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
,E/SELinux ( 7325): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7325): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7325): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7325): Added TimaKesytore provider
,D/dalvikvm( 7325): GC_CONCURRENT freed 2990K, 32% free 9582K/13904K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7325): WAIT_FOR_CONCURRENT_GC blocked 17ms
,W/ContextImpl( 7325): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
,I/SELinux ( 7344): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7344):  
,E/Device Type Shared Preferences( 7325): Device Type Shared Preferences - getDeviceTypeChecked -true
,E/Device Type Shared Preferences( 7325): Device Type Shared Preferences - not connecting to service
,E/com.sec.android.app.shealth.SHealthApplication( 7325): ContentProvider is not null
,I/SELinux ( 7344): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7344):  
I/SELinux ( 7344):  
,I/SELinux ( 7344): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7344): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7344): >>>>> Normal User
,E/dalvikvm( 7344): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,E/SELinux ( 7344): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/ResourceType( 7325): No package identifier when getting value for resource number 0x00000000
,I/System.out( 7325): resource Id::2131361807
,D/TimaKeyStoreProvider( 7344): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7344): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7344): Added TimaKesytore provider
,D/dalvikvm( 7344): GC_CONCURRENT freed 3001K, 32% free 9575K/13904K, paused 4ms+7ms, total 45ms
,D/dalvikvm( 7344): WAIT_FOR_CONCURRENT_GC blocked 33ms
,D/com.sec.android.app.shealth.SHealthApplication( 7325): Success during batch insertion in App registry:0
,D/GetConfigurationSnapshotOperation( 2849): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2849): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 2849): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 2849): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/dalvikvm( 2849): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 2849): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2849): VFY: replacing opcode 0x6e at 0x0033
,I/System.out( 2849): Thread-133(HTTPLog):isShipBuild true
,I/System.out( 2849): Thread-133(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,V/MediaPlayer( 7325): decode(56, 30565892, 48105)
,V/MediaPlayerService( 1924): decode(26, 30565892, 48105)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
,V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(26, 30565892, 48105)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x4414fca0, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
,V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
,I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 1924): mDispatchers.add
,I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x4414fca0, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x4414fca0, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x4414fca0, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
,V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x4414fca0, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,D/dalvikvm( 2849): GC_CONCURRENT freed 1612K, 21% free 11369K/14380K, paused 4ms+10ms, total 54ms
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x4414fca0, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x4414fca0, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x4414fca0, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x44, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
,V/MediaPlayer( 7325): decode(58, 30501792, 10421)
,V/MediaPlayerService( 1924): decode(26, 30501792, 10421)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
,V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(26, 30501792, 10421)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f07c8, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
,I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x444f07c8, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f07c8, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f07c8, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f07c8, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f07c8, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f07c8, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f07c8, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x45, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
,V/MediaPlayer( 7325): decode(59, 34044116, 34198)
,V/MediaPlayerService( 1924): decode(26, 34044116, 34198)
,V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
,V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(26, 34044116, 34198)
V/AwesomePlayer( 1924): reset_l()
,V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f41720, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
,V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
V/MediaPlayerService( 1924): wait for prepare
,V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
,I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder',
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x43f41720, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f41720, 5, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f41720, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
,V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f41720, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f41720, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f41720, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f41720, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x46, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 7325): decode(60, 30449260, 7405)
,V/MediaPlayerService( 1924): decode(26, 30449260, 7405)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
,V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
,V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(26, 30449260, 7405)
V/AwesomePlayer( 1924): reset_l()
,V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f9c50, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
,V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
V/MediaPlayerService( 1924): wait for prepare
,V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
,I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x444f9c50, 200, 973, 0)
,V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f9c50, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f9c50, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
,V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0),
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f9c50, 6, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): addBatteryData
V/MediaPlayerService( 1924): wait for playback complete
,I/AudioPlayer( 1924): First fillBuffer call!!
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f9c50, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f9c50, 7, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f9c50, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x47, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 7325): decode(61, 34134748, 5555)
,V/MediaPlayerService( 1924): decode(26, 34134748, 5555)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(26, 34134748, 5555)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441af928, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
,V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
,I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x441af928, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441af928, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441af928, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441af928, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441af928, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441af928, 7, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
,V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441af928, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x48, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 7325): decode(62, 26954540, 5085)
,V/MediaPlayerService( 1924): decode(26, 26954540, 5085)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(26, 26954540, 5085)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b21b8, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
,I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
,I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b21b8, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b21b8, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b21b8, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
,V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
,I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
,V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b21b8, 6, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b21b8, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b21b8, 7, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
,V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b21b8, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x49, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
,V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
,V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
,V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
,V/MediaPlayer( 7325): decode(63, 26959684, 21552)
,V/MediaPlayerService( 1924): decode(26, 26959684, 21552)
,V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
,V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
,V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
,V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
,V/StagefrightPlayer( 1924): setDataSource(26, 26959684, 21552)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f414c8, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
,V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
,V/AwesomePlayer( 1924): prepareAsync
,V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
,I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x43f414c8, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f414c8, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f414c8, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
,V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f414c8, 6, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
,V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f414c8, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f414c8, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
,V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f414c8, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x4a, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
,V/MediaPlayer( 7325): decode(64, 34130460, 4230)
,V/MediaPlayerService( 1924): decode(26, 34130460, 4230)
,V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
,V/AwesomePlayer( 1924): constructor
,V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
,V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
,V/StagefrightPlayer( 1924): setDataSource(26, 34130460, 4230)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache( 1924): notify(0x441ad140, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
,V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
,V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
,I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
,I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x441ad140, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441ad140, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441ad140, 1, 0, 0)
,V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache( 1924): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441ad140, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441ad140, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441ad140, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441ad140, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x4b, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 7325): decode(65, 26923896, 9400)
,V/MediaPlayerService( 1924): decode(26, 26923896, 9400)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
,V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
,V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
,V/StagefrightPlayer( 1924): setDataSource(26, 26923896, 9400)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f03f0, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
,V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
,V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
,V/AwesomePlayer( 1924): prepareAsync
V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
,I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
,I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x444f03f0, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f03f0, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f03f0, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache( 1924): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f03f0, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f03f0, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f03f0, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f03f0, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x4c, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 7325): decode(66, 30512272, 44276)
,V/MediaPlayerService( 1924): decode(26, 30512272, 44276)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
,V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(26, 30512272, 44276)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f414c8, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
,I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
,I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x43f414c8, 200, 973, 0)
,V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f414c8, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f414c8, 1, 0, 0)
,V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/dalvikvm( 7344): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42a758e8, skipping init
I/SecureStorage( 7344): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/SecureStorage( 7344): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage( 1964): [INFO]: SPID(0x00000005)Credentials: uid 10016, gid 10016, pid 7344
I/SecureStorage( 1964): [INFO]: SPID(0x00000005)Received function mask & code: 0000010C
,I/SecureStorage( 7344): [INFO]: SPID(0x00000000)SS Daemon is running
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f414c8, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,I/SecureStorage( 7344): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 1964): [INFO]: SPID(0x00000005)Credentials: uid 10016, gid 10016, pid 7344
,I/SecureStorage( 1964): [INFO]: SPID(0x00000005)Received function mask & code: 00000106
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f414c8, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f414c8, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f414c8, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x4d, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 7325): decode(67, 30472480, 29256)
,V/MediaPlayerService( 1924): decode(26, 30472480, 29256)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(26, 30472480, 29256)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b5a38, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
,I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b5a38, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b5a38, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b5a38, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b5a38, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,D/GetCommittedConfigurationOperation( 2849): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b5a38, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b5a38, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b5a38, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x4e, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 7325): decode(68, 34078380, 52024)
,V/MediaPlayerService( 1924): decode(26, 34078380, 52024)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
,V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(26, 34078380, 52024)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444ef0d8, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
,V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
,V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
,I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x444ef0d8, 200, 973, 0)
,V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444ef0d8, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444ef0d8, 1, 0, 0)
,V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
,I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1924): open(48000, 2, 0x0, 1, 4)
,V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444ef0d8, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,I/GAV2    ( 7161): Thread[GAThread,5,main]: No campaign data found.
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
,V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444ef0d8, 2, 0, 0)
,V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444ef0d8, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
,V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
,V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444ef0d8, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x4f, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
,V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
,V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
,V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
,V/MediaPlayer( 7325): decode(69, 30556608, 9226)
,V/MediaPlayerService( 1924): decode(27, 30556608, 9226)
,V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
,V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
,V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(27, 30556608, 9226)
,V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f41720, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
,V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
,V/MediaPlayerService( 1924): prepare
,V/AwesomePlayer( 1924): prepareAsync
,V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
,I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
,V/AwesomePlayer( 1924): checkOffloadExceptions is true
,I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,V/MediaPlayerService( 1924): wait for prepare
I/OMX     ( 1924): mDispatchers.add
,I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
,V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x43f41720, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f41720, 5, 0, 0)
,V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f41720, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
,V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
,V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f41720, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,W/Uploader( 2849):  no longer exists, so no auth token.
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f41720, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f41720, 7, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
,V/AudioCache( 1924): wait - success
,V/StagefrightPlayer( 1924): reset
,V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f41720, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x50, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
,V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
,V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
,V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
,V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 7325): decode(70, 26989388, 4509)
,V/MediaPlayerService( 1924): decode(26, 26989388, 4509)
,V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
,V/AwesomePlayer( 1924): constructor
,V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
,V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
,V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(26, 26989388, 4509)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache( 1924): notify(0x441afd38, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
,V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
,V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
,V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
,I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x441afd38, 200, 973, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441afd38, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441afd38, 1, 0, 0)
V/AudioCache( 1924): prepared
,V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
,V/StagefrightPlayer( 1924): start
,V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441afd38, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
I/AudioPlayer( 1924): First fillBuffer call!!
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441afd38, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441afd38, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441afd38, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x51, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,D/GetCommittedConfigurationOperation( 2849): no corresponding serverToken: com.google.android.gms.playlog.uploader
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): stay LED for fully charged
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 350, Delta = 20
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/GetCommittedConfigurationOperation( 2849): no corresponding serverToken: com.google.android.gms.playlog.uploader
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/GetCommittedConfigurationOperation( 2849): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 2849): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/SecureStorage( 1964): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 1964): [INFO]: SPID(0x00000005)PID: 7344, TID: 7357
,E/SPPClientService( 5410): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/SecureStorage( 7344): [INFO]: SPID(0x00000000)Processing data has been completed
I/SecureStorage( 7344): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 7344): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 7344): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 7344): Open platform.db in secure mode
V/AlarmManager( 2418):  next == MAX_VALUE
,E/SPPClientService( 5410): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5410): [a] [ConnectionManager] Connection is already disconnected.
V/AlarmManager( 2418): waitForAlarm result :4
V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SQLiteSecureOpenHelper( 7344): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 7344): ...getDatabaseLocked(b,b,pwd)
,D/SO_AGENT( 7049): [ServerTimeReceiver.java(Line:44/Method:onReceive)] Receive broadcast meassage:android.intent.action.TIME_SET
,I/SO_AGENT( 7049): [ServerTimeReceiver.java(Line:47/Method:onReceive)] No action is available before server time settings
,I/SA      ( 6263): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/Mms/MessagingNotification( 5506): [start]    nonBlockingUpdateMessageIndicator()
,D/Mms/MessagingNotification( 5506): sDisableVibrateForCamera = false
,D/Mms/MessagingNotification( 5506): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 5506): isDefault true
,D/TP/MmsSmsProvider( 2753): match 8:Elapsed time : 9.282 ms
,I/SELinux ( 7448): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7448):  
I/ActivityManager( 2418): Killing 4746:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
,D/TP/MmsSmsProvider( 2753): match 200:Elapsed time : 3.503 ms
,I/SELinux ( 7448): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7448):  
I/SELinux ( 7448):  
,I/SELinux ( 7448): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7448): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7448): >>>>> Normal User
,E/dalvikvm( 7448): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10064 ]
,E/SELinux ( 7448): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7448): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7448): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7448): Added TimaKesytore provider
,D/dalvikvm( 7448): GC_CONCURRENT freed 2998K, 32% free 9573K/13900K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 7448): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/com.samsung.app( 7102): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidintentactionTIME_SET
,D/com.samsung.app( 7102): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/ Time Manager ( 7448): Time Difference not stored. TIME_DIFFERENCE
,I/SELinux ( 7462): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7462):  
I/ActivityManager( 2418): Killing 6283:com.sec.android.service.cm/u0a82 (adj 15): empty #43
,I/SELinux ( 7462): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7462):  
I/SELinux ( 7462):  
,I/SELinux ( 7462): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7462): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7462): >>>>> Normal User
,E/dalvikvm( 7462): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10088 ]
,E/SELinux ( 7462): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 2418): GC_EXPLICIT freed 2074K, 57% free 24413K/55604K, paused 6ms+16ms, total 205ms
,D/TimaKeyStoreProvider( 7462): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7462): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7462): Added TimaKesytore provider
,D/BadgeProvider( 7229): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/Launcher.Model( 2776): reloadBadges entered.
D/BadgeProvider( 7229): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 7229): sendNotify, [notify] : null
D/BadgeProvider( 7229): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 7229): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7229): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 5506): setBadgeCount(), count=0
,D/MessagingNotification( 5506): remove alarm
,D/Mms/MessagingNotification( 5506): updateAllHistoryAsRead()
,D/Mms/MessagingNotification( 5506): [end]    nonBlockingUpdateMessageIndicator()
D/dalvikvm( 7462): GC_CONCURRENT freed 2995K, 32% free 9579K/13900K, paused 3ms+1ms, total 31ms
,D/dalvikvm( 7462): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/CaptivePortalTracker( 2418): DelayedCaptiveCheckState{ when=-7ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker( 2418): Checking http://216.58.209.46/generate_204
D/ConnectivityService( 2418): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/ActivityThread( 2418): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/System.out( 2418): Thread-161(HTTPLog):isShipBuild true
,I/System.out( 2418): Thread-161(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/CaptivePortalTracker( 2418): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker( 2418): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 2418): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2418): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2418): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/SELinux ( 7478): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7478):  
I/ActivityManager( 2418): Killing 6295:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty #43
,I/SELinux ( 7478): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7478):  
I/SELinux ( 7478):  
,I/SELinux ( 7478): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7478): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7478): >>>>> Normal User
,E/dalvikvm( 7478): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 7478): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7478): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7478): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7478): Added TimaKesytore provider
,D/dalvikvm( 7478): GC_CONCURRENT freed 2998K, 32% free 9576K/13904K, paused 4ms+2ms, total 31ms
,D/dalvikvm( 7478): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/elm:14132( 7478): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14132( 7478): ELMEngine.ELMEngine( context ).
,D/elm:14132( 7478): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 7478): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,I/knox    ( 4940): MainReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,D/elm:14132( 7478): ElmAgentService : onCreate()
,W/ContextImpl( 4940): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/elm:14132( 7478): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
D/knox    ( 4940): MainReceiver.listeningToTimeDateChanges( context, intent ).
I/knox    ( 4940): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
D/knox    ( 4940): KNOXAgentService : onCreate()
D/knox    ( 4940): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 4940): KNOXAgentService. startJobThread() start
D/knox    ( 4940): KNOXAgentService. JobThread()
D/elm:14132( 7478): ELMAgentService.listeningToTimeDateChanges( context, intent ).
D/knox    ( 4940): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 4940): KNOXAgentService. startJobThread() wait
D/elm:14132( 7478): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:14132( 7478): ModuleBase.resetCalllogAPIAlarm()
,I/SELinux ( 7493): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7493):  
,D/elm:14132( 7478): ModuleBase.ModifySetAlarm()
D/elm:14132( 7478): MDMBridge.getInstance()
,D/elm:14132( 7478): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 7478): ElmAgentService : onDestroy().
D/knox    ( 4940): KNOXAgentService : onDestroy().
,D/knox    ( 4940): ModuleBase.cancelAllAlarmManageModule()
I/ActivityManager( 2418): Killing 6321:com.samsung.helphub/1000 (adj 15): empty #43
,I/SELinux ( 7493): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7493):  
I/SELinux ( 7493):  
,I/SELinux ( 7493): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7493): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7493): >>>>> Normal User
,E/dalvikvm( 7493): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10145 ]
,E/SELinux ( 7493): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,I/ActivityManager( 2418): Waited long enough for: ServiceRecord{45550af0 u0 pl.k2.droidoaudioteka/.services.DownloadService}
,D/TimaKeyStoreProvider( 7493): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7493): Cannot add TimaSignature Service, License check Failed
,I/ActivityManager( 2418): Waited long enough for: ServiceRecord{45449790 u0 pl.k2.droidoaudioteka/.services.PlayerService}
D/ActivityThread( 7493): Added TimaKesytore provider
,D/dalvikvm( 7493): GC_CONCURRENT freed 3010K, 32% free 9563K/13900K, paused 2ms+2ms, total 22ms
,D/dalvikvm( 7493): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/SELinux ( 7505): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7505):  
I/ActivityManager( 2418): Killing 6334:com.sec.kidsplat.installer/u0a160 (adj 15): empty #43
,I/SELinux ( 7505): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7505):  
I/SELinux ( 7505):  
,I/SELinux ( 7505): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7505): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7505): >>>>> Normal User
,E/dalvikvm( 7505): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10168 ]
,E/SELinux ( 7505): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7505): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7505): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7505): Added TimaKesytore provider
,D/dalvikvm( 7505): GC_CONCURRENT freed 3006K, 32% free 9570K/13904K, paused 4ms+1ms, total 24ms
,D/dalvikvm( 7505): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/ActivityManager( 2418): Killing 6346:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty #43
,D/daemonapp( 5222): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5222): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5222): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5222): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5222): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionTIME_SET, run:true
D/comsamsunglog( 5222): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5222): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5222): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5222): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5222): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5222): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5222): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5222): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5222): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5222): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5222): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/comdaemonstockapp( 5222): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 5222): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,I/CheckinService( 3436): Checkin interval check for package: unspecified last checkin: 1447838164620 min interval config: 0 actual interval: 14493646
,D/Headlines( 7140): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7140): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7140): Breath 8113 latestRequest time : 1447852650231 current time : 1447852658344
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 295, prevStep = 4, currStep = 4
,E/SPPClientService( 5410): [g] getNetMCC return empty string
,E/SPPClientService( 5410): [g] getNetMNC return empty string
,D/Mms/MessagesLockscreen( 5506): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
,W/Binder  ( 2578): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 2578): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
W/Binder  ( 2578): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
W/Binder  ( 2578): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
W/Binder  ( 2578): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
W/Binder  ( 2578): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
W/Binder  ( 2578): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
W/Binder  ( 2578): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
W/Binder  ( 2578): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
W/Binder  ( 2578): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
W/Binder  ( 2578): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
W/Binder  ( 2578): 	at android.view.View.inflate(View.java:18495)
W/Binder  ( 2578): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
W/Binder  ( 2578): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
W/Binder  ( 2578): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
W/Binder  ( 2578): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
W/Binder  ( 2578): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
W/Binder  ( 2578): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 2578): 	at dalvik.system.NativeStart.run(Native Method)
W/Binder  ( 2578): Caused by: java.lang.reflect.InvocationTargetException
W/Binder  ( 2578): 	at java.lang.reflect.Constructor.constructNative(Native Method)
W/Binder  ( 2578): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
W/Binder  ( 2578): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
W/Binder  ( 2578): 	... 16 more
W/Binder  ( 2578): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
W/Binder  ( 2578): 	at android.os.Handler.<init>(Handler.java:200)
W/Binder  ( 2578): 	at android.os.Handler.<init>(Handler.java:114)
W/Binder  ( 2578): 	at android.widget.TextClock.<init>(TextClock.java:130)
W/Binder  ( 2578): 	at android.widget.TextClock.<init>(TextClock.java:191)
W/Binder  ( 2578): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
W/Binder  ( 2578): 	... 19 more
,E/JavaBinder( 2578): *** Uncaught remote exception!  (Exceptions are not yet supported across processes.)
E/JavaBinder( 2578): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
E/JavaBinder( 2578): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
E/JavaBinder( 2578): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
E/JavaBinder( 2578): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
E/JavaBinder( 2578): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
E/JavaBinder( 2578): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
E/JavaBinder( 2578): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
E/JavaBinder( 2578): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
E/JavaBinder( 2578): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
E/JavaBinder( 2578): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
E/JavaBinder( 2578): 	at android.view.View.inflate(View.java:18495)
E/JavaBinder( 2578): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
E/JavaBinder( 2578): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
E/JavaBinder( 2578): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
E/JavaBinder( 2578): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
E/JavaBinder( 2578): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
E/JavaBinder( 2578): 	at android.os.Binder.execTransact(Binder.java:404)
E/JavaBinder( 2578): 	at dalvik.system.NativeStart.run(Native Method)
E/JavaBinder( 2578): Caused by: java.lang.reflect.InvocationTargetException
E/JavaBinder( 2578): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/JavaBinder( 2578): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/JavaBinder( 2578): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
E/JavaBinder( 2578): 	... 16 more
E/JavaBinder( 2578): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
E/JavaBinder( 2578): 	at android.os.Handler.<init>(Handler.java:200)
E/JavaBinder( 2578): 	at android.os.Handler.<init>(Handler.java:114)
E/JavaBinder( 2578): 	at android.widget.TextClock.<init>(TextClock.java:130)
E/JavaBinder( 2578): 	at android.widget.TextClock.<init>(TextClock.java:191)
E/JavaBinder( 2578): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
E/JavaBinder( 2578): 	... 19 more
,D/dalvikvm( 2578): GC_CONCURRENT freed 15651K, 34% free 33965K/50944K, paused 6ms+7ms, total 63ms
,E/SPPClientService( 5410): [b] __ProvisionReply__
,V/AlarmManager( 2418):  next == MAX_VALUE
,E/SPPClientService( 5410): [g] getPLMN return empty string
,E/SPPClientService( 5410): [b] SharedConstants.WHAT_PROV_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5410): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5410): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5410): [g] getNetMCC return empty string
,D/dalvikvm( 5410): GC_CONCURRENT freed 2119K, 26% free 10421K/13900K, paused 3ms+4ms, total 53ms
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3687): Thread-188(HTTPLog):isShipBuild true
,I/System.out( 3687): Thread-188(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,E/SPPClientService( 5410): [b] __InitReply__
,D/PreloadUpdateManagerStateMachine( 6407): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6407): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6407): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6407): AutoUpdateTriggerManager:IDLE:setInterval:86400000
D/hcjo    ( 6407): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6407): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 6407): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6407): entry::IDLE
,I/ActivityManager( 2418): Waited long enough for: ServiceRecord{44be0748 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): stay LED for fully charged
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 350, Delta = 0
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 6787): Attempting to connect to the test coordinator server
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Attempting to connect to the test coordinator server
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Attempting to connect to the test coordinator server
I/jxcore-log( 6787): 
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 297, prevStep = 4, currStep = 4
,I/jxcore-log( 6787): Attempting to connect to the test coordinator server
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Attempting to connect to the test coordinator server
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Attempting to connect to the test coordinator server
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Attempting to connect to the test coordinator server
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Attempting to connect to the test coordinator server
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Test app app.js loaded
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"setup","id":0}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): LogCallback not set !!!!
I/jxcore-log( 6787): 
,I/Choreographer( 6787): Skipped 1673 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6787): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 6787): DBG, CoordinatorConnector connect called
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): DBG, CoordinatorConnector connect called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector connect called
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): DBG, CoordinatorConnector connect called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector connect called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector connect called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector connect called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector connect called
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): DBG, CoordinatorConnector connect called
I/jxcore-log( 6787): 
,I/PowerManagerService( 2418): [PWL] Off : 105s ago
,I/ActivityManager( 2418): Waited long enough for: ServiceRecord{43889bc0 u0 com.sec.spp.push/.PushClientService}
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = -20
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 11
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :4
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2418): waitForAlarm result :8
V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
V/AlarmManager( 2418): waitForAlarm result :4
V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
I/SELinux ( 7589): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7589):  
,I/SELinux ( 7589): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7589):  
I/SELinux ( 7589):  
,I/SELinux ( 7589): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7589): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7589): >>>>> Normal User
,E/dalvikvm( 7589): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
E/SELinux ( 7589): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 7589): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7589): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7589): Added TimaKesytore provider
,D/dalvikvm( 7589): GC_CONCURRENT freed 2999K, 32% free 9572K/13900K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 7589): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/Headlines( 7140): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7140): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7140): Breath 30540 latestRequest time : 1447852650231 current time : 1447852680772
,I/ActivityManager( 2418): Killing 6358:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty #43
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = -10
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 140s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 12
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,D/Headlines( 7140): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7140): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7140): Breath 60031 latestRequest time : 1447852650231 current time : 1447852710263
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 13
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2418): waitForAlarm result :8
,D/Headlines( 7140): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7140): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7140): Breath 90019 latestRequest time : 1447852650231 current time : 1447852740251
,I/PowerManagerService( 2418): [PWL] Off : 180s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 14
,D/AmoledAdjustTimer( 2418): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 291, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :4
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 7140): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7140): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
D/Headlines( 7140): Breath 130891 latestRequest time : 1447852650231 current time : 1447852781122
,D/Headlines( 7140): stop 
D/SnetService( 3436): snet destroyed
,I/SELinux ( 8038): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8038):  
,D/Headlines( 7140): Breath.onDestroy : 
,I/ActivityManager( 2418): Killing 6372:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty #43
,I/SELinux ( 8038): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8038):  
I/SELinux ( 8038):  
,I/SELinux ( 8038): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8038): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 8038): >>>>> Normal User
,E/dalvikvm( 8038): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10039 ]
,E/SELinux ( 8038): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 8038): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8038): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8038): Added TimaKesytore provider
,D/dalvikvm( 8038): GC_CONCURRENT freed 2996K, 32% free 9580K/13904K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 8038): WAIT_FOR_CONCURRENT_GC blocked 24ms
,E/SPPClientService( 8038): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 8038): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 8038): PushLog.txt file is not deleted.
,D/SPPClientService( 8038): PushLog.txt file is not deleted.
,D/SPPClientService( 8038): ============PushLog. stop!
,I/ActivityManager( 2418): Killing 5823:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty #43
,E/SPPClientService( 5410): [b] __PingReply__
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 225s ago
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 15
,D/AmoledAdjustTimer( 2418): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): stay LED for fully charged
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2418): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = -10
,E/Watchdog( 2418): !@Sync 16
,D/AmoledAdjustTimer( 2418): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 275s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2418): !@Sync 17
,D/AmoledAdjustTimer( 2418): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2418): !@Sync 18
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2418): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 2418): GC_CONCURRENT freed 3417K, 56% free 24622K/55604K, paused 24ms+18ms, total 284ms
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2418): !@Sync 19
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/TimaService( 2418): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2418): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2418): TimaServiceHandler.handleMessage what =1
,I/jxcore-log( 6787): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"end","test":0}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"test connectionTable table building and cleanup","id":1}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): DB value for ThaliReplicationManager is: "bogus"
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":50,"expected":50,"test":1,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":40,"expected":40,"test":1,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":60,"expected":60,"test":1,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":1,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":1,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":{"muxPort":60,"time":1447852944185},"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":9,"ok":true,"name":"Cleanup was called, this table is no longer live.","operator":"throws","actual":{"message":"Cleanup was called, this table is no longer live."},"test":1,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"end","test":1}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"teardown","id":2}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 1 isOK: undefined : test connectionTable table building and cleanup", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : Cleanup was called, this table is no longer live.", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 2 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"end","test":2}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"setup","id":3}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 3 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/jxcore-log( 6787): {"type":"end","test":3}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"test connectionTable emitting events for peerIds","id":4}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): DB value for ThaliReplicationManager is: "bogus"
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":30,"expected":30,"test":4,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":40,"expected":40,"test":4,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":50,"expected":50,"test":4,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":60,"expected":60,"test":4,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":7,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"end","test":4}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"teardown","id":5}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 4 isOK: undefined : test connectionTable emitting events for peerIds", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 5 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,I/jxcore-log( 6787): {"type":"end","test":5}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"setup","id":6}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 6 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,E/Watchdog( 2418): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/jxcore-log( 6787): {"type":"end","test":6}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"test","name":"start with bad friendly names","id":7}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":0,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":1,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":2,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":3,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"end","test":7}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"teardown","id":8}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 7 isOK: undefined : start with bad friendly names", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 8 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/jxcore-log( 6787): {"type":"end","test":8}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"setup","id":9}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 9 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/System.out( 6987): Thread-660 calls detatch()
,D/dalvikvm( 6987): GC_CONCURRENT freed 1457K, 20% free 11280K/14068K, paused 7ms+6ms, total 73ms
,I/System.out( 6987): Thread-660 calls detatch()
,I/jxcore-log( 6787): {"type":"end","test":9}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"test","name":"make sure startIdentityExchange sets things up properly","id":10}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 10 isOK: undefined : make sure startIdentityExchange sets things up properly", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 6787): 
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: DAEzz4LLaZPXrF8nyQ/lqw==;Matt
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":51052,"expected":51052,"test":10,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":10,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"DAEzz4LLaZPXrF8nyQ/lqw==;Matt","expected":"DAEzz4LLaZPXrF8nyQ/lqw==;Matt","test":10,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":4,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"123","expected":"123","test":10,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":8,"ok":true,"name":"should be equal","operator":"equal","actual":"bar1","expected":"bar1","test":10,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":9,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"456","expected":"456","test":10,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":11,"ok":true,"name":"should be equal","operator":"equal","actual":"bar2","expected":"bar2","test":10,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":"started","expected":"started","test":10,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"end","test":10}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"teardown","id":11}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"end","test":11}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"setup","id":12}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 11 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 12 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"end","test":12}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"test","name":"make sure we get an error if we call start and then immediately call stop","id":13}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state startIdentityExchangeCalledCB","test":13,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"end","test":13}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"teardown","id":14}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: H9z8/nZUHzqGjycSerj0pQ==;Toby
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":52874,"expected":52874,"test":13,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":13,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"H9z8/nZUHzqGjycSerj0pQ==;Toby","expected":"H9z8/nZUHzqGjycSerj0pQ==;Toby","test":13,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":13,"type":"assert"}
I/jxcore-log( 6787): 
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 13 isOK: undefined : make sure we get an error if we call start and then immediately call stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 14 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/PowerManagerService( 2418): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 10
,I/jxcore-log( 6787): {"type":"end","test":14}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"setup","id":15}
I/jxcore-log( 6787): 
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 15 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 289, prevStep = 4, currStep = 4
,I/jxcore-log( 6787): {"type":"end","test":15}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"test","name":"Make sure stop is clean from start","id":16}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: tLgZyfKEEy39nAT5qWc0OA==;Luke
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":37349,"expected":37349,"test":16,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":16,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"tLgZyfKEEy39nAT5qWc0OA==;Luke","expected":"tLgZyfKEEy39nAT5qWc0OA==;Luke","test":16,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":3,"ok":true,"name":"Should not have gotten error on startIdentityExchange","operator":"notOk","actual":null,"expected":false,"test":16,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":4,"ok":true,"name":"Should not have gotten error on stopIdentityExchange","operator":"notOk","expected":false,"test":16,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":5,"ok":true,"name":"State should be Stopped","operator":"equal","actual":"stopped","expected":"stopped","test":16,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"end","test":16}
I/jxcore-log( 6787): 
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 16 isOK: undefined : Make sure stop is clean from start", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"test","name":"teardown","id":17}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : Should not have gotten error on startIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : Should not have gotten error on stopIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : State should be Stopped", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 17 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"end","test":17}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"setup","id":18}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 18 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = -10
,I/jxcore-log( 6787): {"type":"end","test":18}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"test","name":"Make sure stop is clean from stop execute identity exchange","id":19}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: NByaq7XhIp1Y3xzILgNW9Q==;Jukka
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":59716,"expected":59716,"test":19,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":19,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"NByaq7XhIp1Y3xzILgNW9Q==;Jukka","expected":"NByaq7XhIp1Y3xzILgNW9Q==;Jukka","test":19,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":19,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":4,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":19,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"stopped","expected":"stopped","test":19,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"end","test":19}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 19 isOK: undefined : Make sure stop is clean from stop execute identity exchange", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"test","name":"teardown","id":20}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 20 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/jxcore-log( 6787): {"type":"end","test":20}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"setup","id":21}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 21 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"end","test":21}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"test","name":"make sure we do not have a race condition between startIdentityExchange and executeIdentityExchange","id":22}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: d9c+8p5fJIvAOOF3tsvkRA==;Doug
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":36439,"expected":36439,"test":22,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":22,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"d9c+8p5fJIvAOOF3tsvkRA==;Doug","expected":"d9c+8p5fJIvAOOF3tsvkRA==;Doug","test":22,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":4,"ok":true,"name":"should not throw","operator":"throws","test":22,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"end","test":22}
I/jxcore-log( 6787): 
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 22 isOK: undefined : make sure we do not have a race condition between startIdentityExchange and executeIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should not throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"test","name":"teardown","id":23}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 23 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/jxcore-log( 6787): {"type":"end","test":23}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"setup","id":24}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 24 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/jxcore-log( 6787): {"type":"end","test":24}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"illegal method combinations","id":25}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":1,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":2,"ok":true,"name":"should throw","operator":"throws","actual":"event stopIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: DFp7WcX5h7ew8PXL/mum7g==;David
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":45726,"expected":45726,"test":25,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":25,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"DFp7WcX5h7ew8PXL/mum7g==;David","expected":"DFp7WcX5h7ew8PXL/mum7g==;David","test":25,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":25,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":7,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":8,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":9,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":25,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":10,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":11,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: DFp7WcX5h7ew8PXL/mum7g==;David
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":45726,"expected":45726,"test":25,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":13,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":25,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":14,"ok":true,"name":"should be equal","operator":"equal","actual":"DFp7WcX5h7ew8PXL/mum7g==;David","expected":"DFp7WcX5h7ew8PXL/mum7g==;David","test":25,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":15,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":25,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":16,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":17,"ok":true,"name":"should throw","operator":"throws","actual":"event stopIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":18,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":19,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":20,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"end","test":25}
I/jxcore-log( 6787): 
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 25 isOK: undefined : illegal method combinations", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"test","name":"teardown","id":26}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 13 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 14 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 15 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 16 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 17 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 18 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 19 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 20 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 26 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2418): !@Sync 21
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/jxcore-log( 6787): {"type":"end","test":26}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"setup","id":27}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 27 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4064): GC_CONCURRENT freed 2878K, 31% free 9729K/13936K, paused 8ms+6ms, total 50ms
,I/jxcore-log( 6787): {"type":"end","test":27}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"test","name":"do an identity exchange and get code multiple times to make sure we do not hork state","id":28}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: M3llWO9R4Xx7VTFaGFmDBw==;John
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":42663,"expected":42663,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"M3llWO9R4Xx7VTFaGFmDBw==;John","expected":"M3llWO9R4Xx7VTFaGFmDBw==;John","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: 1CvGisFkLbBTJVFjM7btjw==;Srikanth
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":54536,"expected":54536,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"1CvGisFkLbBTJVFjM7btjw==;Srikanth","expected":"1CvGisFkLbBTJVFjM7btjw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":7,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO smallerHash Making /identity/cb request to pkOther value 1CvGisFkLbBTJVFjM7btjw==
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 28 isOK: undefined : do an identity exchange and get code multiple times to make sure we do not hork state", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO smallerHash Making /identity/rnmine request to pkOther value 1CvGisFkLbBTJVFjM7btjw==
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":9,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":10,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":11,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":115520,"expected":115520,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":13,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":14,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: M3llWO9R4Xx7VTFaGFmDBw==;John
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":15,"ok":true,"name":"should be equal","operator":"equal","actual":42663,"expected":42663,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":16,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":17,"ok":true,"name":"should be equal","operator":"equal","actual":"M3llWO9R4Xx7VTFaGFmDBw==;John","expected":"M3llWO9R4Xx7VTFaGFmDBw==;John","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":18,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: 1CvGisFkLbBTJVFjM7btjw==;Srikanth
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":19,"ok":true,"name":"should be equal","operator":"equal","actual":54536,"expected":54536,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":20,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":21,"ok":true,"name":"should be equal","operator":"equal","actual":"1CvGisFkLbBTJVFjM7btjw==;Srikanth","expected":"1CvGisFkLbBTJVFjM7btjw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":22,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO smallerHash Making /identity/cb request to pkOther value 1CvGisFkLbBTJVFjM7btjw==
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 13 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 14 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 15 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 16 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 17 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 18 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 19 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO smallerHash Making /identity/rnmine request to pkOther value 1CvGisFkLbBTJVFjM7btjw==
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 20 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 21 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 22 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":23,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":24,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 23 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":25,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":26,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":27,"ok":true,"name":"should be equal","operator":"equal","actual":121664,"expected":121664,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":28,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":29,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: M3llWO9R4Xx7VTFaGFmDBw==;John
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":30,"ok":true,"name":"should be equal","operator":"equal","actual":42663,"expected":42663,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":31,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":32,"ok":true,"name":"should be equal","operator":"equal","actual":"M3llWO9R4Xx7VTFaGFmDBw==;John","expected":"M3llWO9R4Xx7VTFaGFmDBw==;John","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":33,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: 1CvGisFkLbBTJVFjM7btjw==;Srikanth
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":34,"ok":true,"name":"should be equal","operator":"equal","actual":54536,"expected":54536,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":35,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":36,"ok":true,"name":"should be equal","operator":"equal","actual":"1CvGisFkLbBTJVFjM7btjw==;Srikanth","expected":"1CvGisFkLbBTJVFjM7btjw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":37,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO smallerHash Making /identity/cb request to pkOther value 1CvGisFkLbBTJVFjM7btjw==
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 24 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 25 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 26 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO smallerHash Making /identity/rnmine request to pkOther value 1CvGisFkLbBTJVFjM7btjw==
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 27 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":38,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":39,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 28 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 29 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":40,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":41,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":42,"ok":true,"name":"should be equal","operator":"equal","actual":565376,"expected":565376,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":43,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":44,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: M3llWO9R4Xx7VTFaGFmDBw==;John
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":45,"ok":true,"name":"should be equal","operator":"equal","actual":42663,"expected":42663,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":46,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":47,"ok":true,"name":"should be equal","operator":"equal","actual":"M3llWO9R4Xx7VTFaGFmDBw==;John","expected":"M3llWO9R4Xx7VTFaGFmDBw==;John","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":48,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: 1CvGisFkLbBTJVFjM7btjw==;Srikanth
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":49,"ok":true,"name":"should be equal","operator":"equal","actual":54536,"expected":54536,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":50,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":51,"ok":true,"name":"should be equal","operator":"equal","actual":"1CvGisFkLbBTJVFjM7btjw==;Srikanth","expected":"1CvGisFkLbBTJVFjM7btjw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":52,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO smallerHash Making /identity/cb request to pkOther value 1CvGisFkLbBTJVFjM7btjw==
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 30 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 31 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 32 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 33 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO smallerHash Making /identity/rnmine request to pkOther value 1CvGisFkLbBTJVFjM7btjw==
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 34 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 35 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 36 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 37 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 38 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 39 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":53,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":54,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 40 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 41 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 42 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":55,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":56,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":57,"ok":true,"name":"should be equal","operator":"equal","actual":904064,"expected":904064,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":58,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":59,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: M3llWO9R4Xx7VTFaGFmDBw==;John
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":60,"ok":true,"name":"should be equal","operator":"equal","actual":42663,"expected":42663,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":61,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":62,"ok":true,"name":"should be equal","operator":"equal","actual":"M3llWO9R4Xx7VTFaGFmDBw==;John","expected":"M3llWO9R4Xx7VTFaGFmDBw==;John","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":63,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: 1CvGisFkLbBTJVFjM7btjw==;Srikanth
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":64,"ok":true,"name":"should be equal","operator":"equal","actual":54536,"expected":54536,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":65,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":66,"ok":true,"name":"should be equal","operator":"equal","actual":"1CvGisFkLbBTJVFjM7btjw==;Srikanth","expected":"1CvGisFkLbBTJVFjM7btjw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":67,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO smallerHash Making /identity/cb request to pkOther value 1CvGisFkLbBTJVFjM7btjw==
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 43 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 44 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 45 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 46 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 47 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 48 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 49 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 50 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 51 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 52 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 53 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 54 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO smallerHash Making /identity/rnmine request to pkOther value 1CvGisFkLbBTJVFjM7btjw==
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 55 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 56 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 57 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 58 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 59 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 60 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":68,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":69,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 61 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 62 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 63 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 64 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 65 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 66 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 67 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 68 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":70,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":71,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":72,"ok":true,"name":"should be equal","operator":"equal","actual":251968,"expected":251968,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":73,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":74,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: M3llWO9R4Xx7VTFaGFmDBw==;John
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":75,"ok":true,"name":"should be equal","operator":"equal","actual":42663,"expected":42663,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":76,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":77,"ok":true,"name":"should be equal","operator":"equal","actual":"M3llWO9R4Xx7VTFaGFmDBw==;John","expected":"M3llWO9R4Xx7VTFaGFmDBw==;John","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":78,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: 1CvGisFkLbBTJVFjM7btjw==;Srikanth
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":79,"ok":true,"name":"should be equal","operator":"equal","actual":54536,"expected":54536,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":80,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":81,"ok":true,"name":"should be equal","operator":"equal","actual":"1CvGisFkLbBTJVFjM7btjw==;Srikanth","expected":"1CvGisFkLbBTJVFjM7btjw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":82,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO smallerHash Making /identity/cb request to pkOther value 1CvGisFkLbBTJVFjM7btjw==
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 69 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 70 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 71 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO smallerHash Making /identity/rnmine request to pkOther value 1CvGisFkLbBTJVFjM7btjw==
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 72 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":83,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":84,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":85,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":86,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":87,"ok":true,"name":"should be equal","operator":"equal","actual":215872,"expected":215872,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":88,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":89,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: M3llWO9R4Xx7VTFaGFmDBw==;John
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":90,"ok":true,"name":"should be equal","operator":"equal","actual":42663,"expected":42663,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":91,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":92,"ok":true,"name":"should be equal","operator":"equal","actual":"M3llWO9R4Xx7VTFaGFmDBw==;John","expected":"M3llWO9R4Xx7VTFaGFmDBw==;John","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":93,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: 1CvGisFkLbBTJVFjM7btjw==;Srikanth
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":94,"ok":true,"name":"should be equal","operator":"equal","actual":54536,"expected":54536,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":95,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":96,"ok":true,"name":"should be equal","operator":"equal","actual":"1CvGisFkLbBTJVFjM7btjw==;Srikanth","expected":"1CvGisFkLbBTJVFjM7btjw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":97,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO smallerHash Making /identity/cb request to pkOther value 1CvGisFkLbBTJVFjM7btjw==
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 73 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 74 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 75 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 76 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 77 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 78 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 79 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 80 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 81 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 82 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 83 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 84 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 85 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 86 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 87 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO smallerHash Making /identity/rnmine request to pkOther value 1CvGisFkLbBTJVFjM7btjw==
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":98,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":99,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":100,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":101,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":102,"ok":true,"name":"should be equal","operator":"equal","actual":447680,"expected":447680,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":103,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":104,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: M3llWO9R4Xx7VTFaGFmDBw==;John
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":105,"ok":true,"name":"should be equal","operator":"equal","actual":42663,"expected":42663,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":106,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":107,"ok":true,"name":"should be equal","operator":"equal","actual":"M3llWO9R4Xx7VTFaGFmDBw==;John","expected":"M3llWO9R4Xx7VTFaGFmDBw==;John","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":108,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: 1CvGisFkLbBTJVFjM7btjw==;Srikanth
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":109,"ok":true,"name":"should be equal","operator":"equal","actual":54536,"expected":54536,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":110,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":111,"ok":true,"name":"should be equal","operator":"equal","actual":"1CvGisFkLbBTJVFjM7btjw==;Srikanth","expected":"1CvGisFkLbBTJVFjM7btjw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":112,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO smallerHash Making /identity/cb request to pkOther value 1CvGisFkLbBTJVFjM7btjw==
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 88 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 89 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 90 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 91 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 92 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 93 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 94 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 95 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 96 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 97 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 98 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 99 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 100 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 101 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 102 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 103 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 104 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 105 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 106 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 107 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 108 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 109 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 110 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 111 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 112 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO smallerHash Making /identity/rnmine request to pkOther value 1CvGisFkLbBTJVFjM7btjw==
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":113,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":114,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 113 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 114 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":115,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":116,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":117,"ok":true,"name":"should be equal","operator":"equal","actual":714752,"expected":714752,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":118,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":119,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: M3llWO9R4Xx7VTFaGFmDBw==;John
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":120,"ok":true,"name":"should be equal","operator":"equal","actual":42663,"expected":42663,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":121,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): {"id":122,"ok":true,"name":"should be equal","operator":"equal","actual":"M3llWO9R4Xx7VTFaGFmDBw==;John","expected":"M3llWO9R4Xx7VTFaGFmDBw==;John","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":123,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: 1CvGisFkLbBTJVFjM7btjw==;Srikanth
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":124,"ok":true,"name":"should be equal","operator":"equal","actual":54536,"expected":54536,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":125,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":126,"ok":true,"name":"should be equal","operator":"equal","actual":"1CvGisFkLbBTJVFjM7btjw==;Srikanth","expected":"1CvGisFkLbBTJVFjM7btjw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":127,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO smallerHash Making /identity/cb request to pkOther value 1CvGisFkLbBTJVFjM7btjw==
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 115 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 116 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 117 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 118 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 119 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 120 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO smallerHash Making /identity/rnmine request to pkOther value 1CvGisFkLbBTJVFjM7btjw==
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 121 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 122 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 123 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":128,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":129,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 124 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 125 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 126 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":130,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":131,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":132,"ok":true,"name":"should be equal","operator":"equal","actual":229056,"expected":229056,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":133,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":134,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"},
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: M3llWO9R4Xx7VTFaGFmDBw==;John
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":135,"ok":true,"name":"should be equal","operator":"equal","actual":42663,"expected":42663,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":136,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":137,"ok":true,"name":"should be equal","operator":"equal","actual":"M3llWO9R4Xx7VTFaGFmDBw==;John","expected":"M3llWO9R4Xx7VTFaGFmDBw==;John","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":138,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: 1CvGisFkLbBTJVFjM7btjw==;Srikanth
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":139,"ok":true,"name":"should be equal","operator":"equal","actual":54536,"expected":54536,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":140,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":141,"ok":true,"name":"should be equal","operator":"equal","actual":"1CvGisFkLbBTJVFjM7btjw==;Srikanth","expected":"1CvGisFkLbBTJVFjM7btjw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":142,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO smallerHash Making /identity/cb request to pkOther value 1CvGisFkLbBTJVFjM7btjw==
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 127 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 128 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 129 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 130 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 131 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO smallerHash Making /identity/rnmine request to pkOther value 1CvGisFkLbBTJVFjM7btjw==
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 132 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 133 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":143,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":144,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":145,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":146,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":147,"ok":true,"name":"should be equal","operator":"equal","actual":36480,"expected":36480,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":148,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":149,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: M3llWO9R4Xx7VTFaGFmDBw==;John
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":150,"ok":true,"name":"should be equal","operator":"equal","actual":42663,"expected":42663,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":151,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":152,"ok":true,"name":"should be equal","operator":"equal","actual":"M3llWO9R4Xx7VTFaGFmDBw==;John","expected":"M3llWO9R4Xx7VTFaGFmDBw==;John","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":153,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO identityExchange We will advertise the following device name as we start: 1CvGisFkLbBTJVFjM7btjw==;Srikanth
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":154,"ok":true,"name":"should be equal","operator":"equal","actual":54536,"expected":54536,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":155,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":156,"ok":true,"name":"should be equal","operator":"equal","actual":"1CvGisFkLbBTJVFjM7btjw==;Srikanth","expected":"1CvGisFkLbBTJVFjM7btjw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":157,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO smallerHash Making /identity/cb request to pkOther value 1CvGisFkLbBTJVFjM7btjw==
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 134 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 135 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 136 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 137 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 138 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 139 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 140 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 141 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 142 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 143 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 144 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 145 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 146 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 147 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 148 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 149 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 150 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO smallerHash Making /identity/rnmine request to pkOther value 1CvGisFkLbBTJVFjM7btjw==
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":158,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":159,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":160,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":161,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":162,"ok":true,"name":"should be equal","operator":"equal","actual":230976,"expected":230976,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":163,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":164,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"end","test":28}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"teardown","id":29}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 151 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 152 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 153 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 154 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 155 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 156 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 157 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 158 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 159 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 160 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 161 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 162 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 163 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 164 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 29 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 10
,I/jxcore-log( 6787): {"type":"end","test":29}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"setup","id":30}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 30 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/jxcore-log( 6787): {"type":"end","test":30}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"test compareEqualSizeBuffers","id":31}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":1,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":2,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":3,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":4,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"Buffers must be of the same size."},"test":31,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":8,"ok":true,"name":"should be equal","operator":"equal","actual":0,"expected":0,"test":31,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":0,"expected":0,"test":31,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":1,"expected":1,"test":31,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":11,"ok":true,"name":"should be equal","operator":"equal","actual":1,"expected":1,"test":31,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"end","test":31}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"teardown","id":32}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 31 isOK: undefined : test compareEqualSizeBuffers", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 32 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"end","test":32}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"setup","id":33}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 33 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/jxcore-log( 6787): {"type":"end","test":33}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"test","name":"Make sure we return 404 before hitting start","id":34}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 34 isOK: undefined : Make sure we return 404 before hitting start", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":34,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"end","test":34}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"teardown","id":35}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 35 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,I/jxcore-log( 6787): {"type":"end","test":35}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"setup","id":36}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 36 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/jxcore-log( 6787): {"type":"end","test":36}
I/jxcore-log( 6787): 
,E/jxcore-log( 6787): (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
E/jxcore-log( 6787): 
,E/jxcore-log( 6787): Trace: 
E/jxcore-log( 6787):     at Console.prototype.trace@console.js:165:13
E/jxcore-log( 6787):     at addListener@events.js:140:7
E/jxcore-log( 6787):     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/pouchdb-all-dbs/index.js:61:3
E/jxcore-log( 6787):     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:138:9
E/jxcore-log( 6787):     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/util.js:26:16
E/jxcore-log( 6787):     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:507:13
E/jxcore-log( 6787):     at module.exports/Promise.prototype._settlePromiseAt@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:581:13
E/jxcore-log( 6787):     at module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/
,E/jxcore-log( 6787): (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
E/jxcore-log( 6787): 
,E/jxcore-log( 6787): Trace: 
E/jxcore-log( 6787):     at Console.prototype.trace@console.js:165:13
E/jxcore-log( 6787):     at addListener@events.js:140:7
E/jxcore-log( 6787):     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/pouchdb-all-dbs/index.js:85:3
E/jxcore-log( 6787):     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:138:9
E/jxcore-log( 6787):     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/util.js:26:16
E/jxcore-log( 6787):     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:507:13
E/jxcore-log( 6787):     at module.exports/Promise.prototype._settlePromiseAt@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:581:13
E/jxcore-log( 6787):     at module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"test","name":"Random path after start, need 404","id":37}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 37 isOK: undefined : Random path after start, need 404", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":37,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"end","test":37}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"teardown","id":38}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"end","test":38}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"setup","id":39}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 38 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 39 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/jxcore-log( 6787): {"type":"end","test":39}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"test","name":"Confirm we go to wrongPeer if our hash is smaller","id":40}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"WrongPeer","expected":"WrongPeer","test":40,"type":"assert"}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 40 isOK: undefined : Confirm we go to wrongPeer if our hash is smaller", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":40,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"yXzH++PngsAG2rxgCjZnCA==","expected":"yXzH++PngsAG2rxgCjZnCA==","test":40,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":40,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"end","test":40}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"teardown","id":41}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 41 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"end","test":41}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"setup","id":42}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 42 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"end","test":42}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"test","name":"Confirm we go to wrongPeer if our hash is smaller","id":43}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"WrongPeer","expected":"WrongPeer","test":43,"type":"assert"}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 43 isOK: undefined : Confirm we go to wrongPeer if our hash is smaller", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":43,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"NpTuaYtFol9rmSF+Xofw/Q==","expected":"NpTuaYtFol9rmSF+Xofw/Q==","test":43,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":43,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"end","test":43},
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"teardown","id":44},
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 44 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 22
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/jxcore-log( 6787): {"type":"end","test":44}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"setup","id":45}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 45 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"end","test":45}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"test","name":"Confirm we get wrongPeer on cb if we give hash other than expected","id":46}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 46 isOK: undefined : Confirm we get wrongPeer on cb if we give hash other than expected", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":46,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"rCUbBIE7KnXAhQNZZEHyjQ==","expected":"rCUbBIE7KnXAhQNZZEHyjQ==","test":46,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":46,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"end","test":46}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"teardown","id":47}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 47 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"end","test":47}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"setup","id":48}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 48 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/jxcore-log( 6787): {"type":"end","test":48}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"test","name":"Confirm we get Skip Ahead even with a wrong peer on a rnMine request (and we can argue if this is a good choice)","id":49}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 49 isOK: undefined : Confirm we get Skip Ahead even with a wrong peer on a rnMine request (and we can argue if this is a good choice)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"skippedAhead","expected":"skippedAhead","test":49,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"HuHtUoC5frIS969L2prH5Q==","expected":"HuHtUoC5frIS969L2prH5Q==","test":49,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":49,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"end","test":49}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"teardown","id":50}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 50 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"end","test":50}
I/jxcore-log( 6787): 
I/PowerManagerService( 2418): [PWL] Off : 455s ago
,I/jxcore-log( 6787): {"type":"test","name":"setup","id":51}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 51 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"end","test":51}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"test","name":"NoIdentityExchange after start & stop","id":52}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 52 isOK: undefined : NoIdentityExchange after start & stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"k2PzBQdhVHPTqc0+NkqhUg==","expected":"k2PzBQdhVHPTqc0+NkqhUg==","test":52,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":2,"ok":true,"name":{"req":{"method":"post","url":"http://127.0.0.1:46264/identity/cb","data":{"cbValue":"pVZnYZrW7Aul257lcMOCBx0Y82ZsSz1UGQk2Hv+kDzI=","pkMine":"Hdeu+BUl+Ocy3L/R1AqDww=="}},"header":{"x-powered-by":"Express","content-type":"application/json; charset=utf-8","content-length":"77","etag":"W/\"4d-71PfgxwFA+foSk/xKYdHiA\"","date":"Wed, 18 Nov 2015 13:23:42 GMT","connection":"close"},"status":400,"text":"{\"errorCode\":\"notDoingIdentityExchange\",\"pkOther\":\"k2PzBQdhVHPTqc0+NkqhUg==\"}"},"operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"k2PzBQdhVHPTqc0+NkqhUg==","expected":"k2PzBQdhVHPTqc0+NkqhUg==","test":52,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":5,"ok":true,"name":{"req":{"method":"post","url":"http://127.0.0.1:54050/identity/rnmine","data":{"rnMine":"/LJPWQbieW8xfYuBJzBoIg==","pkOther":"s5EmjbjnrWA5mAIy7aID8Q=="}},"header":{"x-powered-by":"Express","content-type":"application/json; charset=utf-8","content-length":"77","etag":"W/\"4d-71PfgxwFA+foSk/xKYdHiA\"","date":"Wed, 18 Nov 2015 13:23:42 GMT","connection":"close"},"status":400,"text":"{\"errorCode\":\"notDoingIdentityExchange\",\"pkOther\":\"k2PzBQdhVHPTqc0+NkqhUg==\"}"},"operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"k2PzBQdhVHPTqc0+NkqhUg==","expected":"k2PzBQdhVHPTqc0+NkqhUg==","test":52,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":8,"ok":true,"name":{"req":{"method":"post","url":"http://127.0.0.1:53410/identity/cb","data":{"cbValue":"Lt/mKcvo0wiqMLjoOYtX11nbthU3vXOq7Xs03SaxafM=","pkMine":"pMr7U1Wio5BJqoeZzPX1rQ=="}},"header":{"x-powered-by":"Express","content-type":"application/json; charset=utf-8","content-length":"77","etag":"W/\"4d-71PfgxwFA+foSk/xKYdHiA\"","date":"Wed, 18 Nov 2015 13:23:42 GMT","connection":"close"},"status":400,"text":"{\"errorCode\":\"notDoingIdentityExchange\",\"pkOther\":\"k2PzBQdhVHPTqc0+NkqhUg==\"}"},"operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"k2PzBQdhVHPTqc0+NkqhUg==","expected":"k2PzBQdhVHPTqc0+NkqhUg==","test":52,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":11,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"end","test":52}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"teardown","id":53}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : [object Object]", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : [object Object]", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : [object Object]", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 53 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"end","test":53}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"setup","id":54}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 54 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,I/jxcore-log( 6787): {"type":"end","test":54}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 6787): {"type":"test","name":"cbRequest - bad request bodies","id":55}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 55 isOK: undefined : cbRequest - bad request bodies", source: file:///android_asset/www/js/thali_main.js (63)
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): stay LED for fully charged
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,I/jxcore-log( 6787): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":" ","pkMine":"zynk0fSNz2qgvrai6iVFTw=="}
I/jxcore-log( 6787): 
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/jxcore-log( 6787): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":"{@#{$@#{$","pkMine":"/ujMe3986P3IwXfn5VxpBA=="}
I/jxcore-log( 6787): 
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 6787): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":"ng0RK3gccsQmOb3Y4AVRoyNw94gMpBEpne9O3ZgueJFr","pkMine":"5X+LP6tfPsYVL3AMQz9RDg=="}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":"ObElvjYBgcqd4m4ZQbEx4SGOgfPaohVVOMzSYQuWow==","pkMine":"hnlkgxSCKghQ2Ow4/JjJmw=="}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"8loE3aNAtIZTQD9zdgi6mO4eOLG5jgiHZ/IaNUUcnxQ=","pkMine":" "}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"dGSuPWVSzVYiFj2PJYLZ1h3TH8zqnfpJUi+7Ai17BQU=","pkMine":"{@#{$@#{$"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"DeHh+fAIYmpgVmMor08JpQBlJRxsmCu7WIP8O3aGQCs=","pkMine":"qs2PjPg/gUkY/RomLHSGLkA="}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"Gq0PhHwtc+EeN+Wq2IiuXNUC2z5RNYD2THr6mOQ0Es0=","pkMine":"nbr0JTO+Qy8TS2teQWBp"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":" "}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":"{@#{$@#{$"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":"qs2PjPg/gUkY/RomLHSGLkA="}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":"nbr0JTO+Qy8TS2teQWBp"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":" "}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":"{@#{$@#{$"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":"qs2PjPg/gUkY/RomLHSGLkA="}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":"nbr0JTO+Qy8TS2teQWBp"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"ng0RK3gccsQmOb3Y4AVRoyNw94gMpBEpne9O3ZgueJFr","pkMine":" "}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"ng0RK3gccsQmOb3Y4AVRoyNw94gMpBEpne9O3ZgueJFr","pkMine":"{@#{$@#{$"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"ng0RK3gccsQmOb3Y4AVRoyNw94gMpBEpne9O3ZgueJFr","pkMine":"qs2PjPg/gUkY/RomLHSGLkA="}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"ng0RK3gccsQmOb3Y4AVRoyNw94gMpBEpne9O3ZgueJFr","pkMine":"nbr0JTO+Qy8TS2teQWBp"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"ObElvjYBgcqd4m4ZQbEx4SGOgfPaohVVOMzSYQuWow==","pkMine":" "}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"ObElvjYBgcqd4m4ZQbEx4SGOgfPaohVVOMzSYQuWow==","pkMine":"{@#{$@#{$"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"ObElvjYBgcqd4m4ZQbEx4SGOgfPaohVVOMzSYQuWow==","pkMine":"qs2PjPg/gUkY/RomLHSGLkA="}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"ObElvjYBgcqd4m4ZQbEx4SGOgfPaohVVOMzSYQuWow==","pkMine":"nbr0JTO+Qy8TS2teQWBp"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): INFO largerHash Got a /identity/cb request with a bum pkMine - {}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":11,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":13,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":14,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":15,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":16,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":17,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":18,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":19,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":20,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":21,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":22,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":23,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":24,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":25,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":26,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":27,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":28,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":29,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":30,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":31,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":32,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":33,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":34,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":35,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":36,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":37,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":38,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":39,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":40,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":41,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":42,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":43,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":44,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":45,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
I/jxcore-log( 6787): {"id":46,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
I/jxcore-log( 6787): {"id":47,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":48,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":49,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":50,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":51,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":52,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":53,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":54,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":55,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":56,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":57,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":58,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":59,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":60,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":61,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":62,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":63,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":64,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":65,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":66,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":67,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":68,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":69,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":70,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":71,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":72,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":73,"ok":true,"name":"should be equal","operator":"equal","actual":"6mxb41FQobD0vD4YvbSN2Q==","expected":"6mxb41FQobD0vD4YvbSN2Q==","test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":74,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"end","test":55}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"teardown","id":56}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 13 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 14 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 15 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 16 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 17 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 18 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 19 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 20 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 21 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 22 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 23 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 24 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 25 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 26 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 27 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 28 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 29 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 30 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 31 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 32 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 33 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 34 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 35 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 36 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 37 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 38 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 39 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 40 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 41 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 42 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 43 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 44 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 45 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 46 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 47 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 48 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 49 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 50 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 51 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 52 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 53 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 54 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 55 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 56 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 57 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 58 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 59 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 60 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 61 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 62 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 63 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 64 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 65 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 66 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 67 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 68 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 69 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 70 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 71 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 72 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 73 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 74 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 56 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"end","test":56}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"setup","id":57}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 57 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"end","test":57}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"type":"test","name":"re-do cb (to check we can reset) and make sure rnOther changes","id":58}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 58 isOK: undefined : re-do cb (to check we can reset) and make sure rnOther changes", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":"U+1ROR2nds+ENprPfB4y9w==","expected":true,"test":58,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"mlf1CWkfF22rroSGVmX9sA==","expected":"mlf1CWkfF22rroSGVmX9sA==","test":58,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":2,"ok":true,"name":"should not be equal","operator":"notEqual","actual":"U+1ROR2nds+ENprPfB4y9w==","test":58,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"mlf1CWkfF22rroSGVmX9sA==","expected":"mlf1CWkfF22rroSGVmX9sA==","test":58,"type":"assert"}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6787): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"mlf1CWkfF22rroSGVmX9sA==","expected":"mlf1CWkfF22rroSGVmX9sA==","test":58,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"end","test":58}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): {"type":"test","name":"teardown","id":59}
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 59 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 10
,E/Watchdog( 2418): !@Sync 23
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2418): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2418): <AppSync3 Whitelist>
,V/AlarmManager( 2418): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2418): !@Sync 24
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 525s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2418): !@Sync 25
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2418): !@Sync 26
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2418): !@Sync 27
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2418): [PWL] Off : 600s ago
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2418): !@Sync 28
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 29
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/dalvikvm( 2418): GC_CONCURRENT freed 3714K, 56% free 24585K/55604K, paused 22ms+13ms, total 238ms
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 2418): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2418): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2418): TimaServiceHandler.handleMessage what =1
,I/PowerManagerService( 2418): [PWL] Off : 680s ago
I/PowerManagerService( 2418): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2418): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2418): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2418, ws=null) (elapsedTime=5297)
,E/Watchdog( 2418): !@Sync 30
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/GAV2    ( 6840): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 6840): Thread[disconnect check,5,main]: Disconnected from service
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 31
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2418): !@Sync 32
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2418): [PWL] Off : 765s ago
,E/Watchdog( 2418): !@Sync 33
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 34
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2418): waitForAlarm result :8
,I/SensorManagerA( 2418): getReportingMode :: sensor.mType = 5
,D/LightsService( 2418): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2418): LightSensor setDelay = 200000000
D/Sensors ( 2418): LightSensor setSensorDelay = 200000000
D/Sensors ( 2418): Light sensor flush: not enabled 0
D/Sensors ( 2418): LightSensor enable = 1
D/Sensors ( 2418): LightSensor enableSensor = 1
,D/SensorManager( 2418): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,E/SPPClientService( 5410): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/LightsService( 2418): [SvcLED]  onSensorChanged::light value = 0
D/Sensors ( 2418): LightSensor enable = 0
D/Sensors ( 2418): LightSensor enableSensor = 0
,D/SensorManager( 2418): unregisterListener ::   
D/LightsService( 2418): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 35
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): stay LED for fully charged
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2418): [PWL] Off : 855s ago
,E/Watchdog( 2418): !@Sync 36
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 37
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): stay LED for fully charged
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2418): !@Sync 38
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2418): [PWL] Off : 950s ago
,E/Watchdog( 2418): !@Sync 39
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/TimaService( 2418): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2418): TimaServiceHandler.handleMessage what =1
,D/TimaService( 2418): TIMA: checkEvent, operation: 50000 subject: 10000
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 41
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/dalvikvm( 2418): GC_CONCURRENT freed 3686K, 56% free 24591K/55604K, paused 20ms+18ms, total 262ms
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 11476
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 11478
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 11479
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 11481
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 11483
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 11484
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 11486
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 11488
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 11489
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 11490
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): stay LED for fully charged
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/dalvikvm( 2849): GC_CONCURRENT freed 1796K, 22% free 11511K/14704K, paused 7ms+10ms, total 85ms
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService( 2418): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2578): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2578): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2578): updateDataNetType()
,D/STATUSBAR-NetworkController( 2578): NoService, mRoamingIconId = 0
,E/Watchdog( 2418): !@Sync 42
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2418): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/BatteryService( 2418): stay LED for fully charged
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2418): !@Sync 43
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2418): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2418): <AppSync3 Whitelist>
,V/AlarmManager( 2418): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 44
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :4
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5410): [b] __PingReply__
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 45
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4064): GC_CONCURRENT freed 2050K, 31% free 9727K/13936K, paused 3ms+3ms, total 42ms
,D/dalvikvm( 4064): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2418): waitForAlarm result :4
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 1155s ago
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 11864
,E/Watchdog( 2418): !@Sync 46
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): stay LED for fully charged
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 47
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 48
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 49
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 1265s ago
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2418): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,D/TimaService( 2418): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2418): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2418): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): stay LED for fully charged
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 12252
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 283, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 51
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2776): GC_CONCURRENT freed 7378K, 36% free 18970K/29400K, paused 12ms+9ms, total 107ms
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/dalvikvm( 2418): GC_CONCURRENT freed 3645K, 56% free 24617K/55604K, paused 24ms+20ms, total 262ms
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 52
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 53
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2418): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 54
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 55
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 56
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/BatteryService( 2418): stay LED for fully charged
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5024): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2418): !@Sync 57
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2418): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): stay LED for fully charged
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 58
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 59
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/TimaService( 2418): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2418): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2418): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2418): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/BatteryService( 2418): stay LED for fully charged
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 61
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2418): Prepared write state in 65ms
,I/ProcessStatsService( 2418): Prepared write state in 28ms
,I/ProcessStatsService( 2418): Pruning old procstats: /data/system/procstats/state-2015-11-17-22-50-51.bin
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 1625s ago
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :4
,I/SensorManagerA( 2418): getReportingMode :: sensor.mType = 5
,D/LightsService( 2418): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2418): LightSensor setDelay = 200000000
D/Sensors ( 2418): LightSensor setSensorDelay = 200000000
D/Sensors ( 2418): Light sensor flush: not enabled 0
D/Sensors ( 2418): LightSensor enable = 1
D/Sensors ( 2418): LightSensor enableSensor = 1
D/SensorManager( 2418): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
V/NetworkStats( 2418): performPollLocked(flags=0x3)
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
V/NetworkStats( 2418): performPollLocked() took 59ms
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,I/SELinux (13402): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13402):  
,I/SELinux (13402): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13402):  
I/SELinux (13402):  
,I/SELinux (13402): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (13402): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(13402): >>>>> Normal User
,E/dalvikvm(13402): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
E/SELinux (13402): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(13402): in addTimaSignatureService
,D/Sensors ( 2418): LightSensor enable = 0
,D/Sensors ( 2418): LightSensor enableSensor = 0
,D/LightsService( 2418): [SvcLED]  onSensorChanged::light value = 2
D/TimaKeyStoreProvider(13402): Cannot add TimaSignature Service, License check Failed
,D/SensorManager( 2418): unregisterListener ::   
,D/ActivityThread(13402): Added TimaKesytore provider
D/LightsService( 2418): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/dalvikvm(13402): GC_CONCURRENT freed 3011K, 32% free 9559K/13896K, paused 3ms+2ms, total 27ms
,D/dalvikvm(13402): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/@ WidgetProvider(13402): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(13402): onUpdate called for widgetId : 0
,D/@ WidgetProvider(13402): Widget random data : 1
,D/@ WidgetProvider(13402): onUpdate called for widgetId : 5
,D/@ WidgetProvider(13402): Widget random data : 10
,E/dalvikvm(13402): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(13402): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(13402): VFY: replacing opcode 0x22 at 0x0038
,I/ActivityManager( 2418): Killing 5908:com.sec.knox.bridge/1000 (adj 15): empty #43
E/dalvikvm(13402): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(13402): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(13402): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(13402): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(13402): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(13402): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(13402): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(13402): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(13402): VFY: replacing opcode 0x22 at 0x0038
,D/dalvikvm(13402): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
D/dalvikvm(13402): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(13402): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(13402): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,I/EventLogService( 3436): Aggregate from 1447852392189 (log), 1447852392189 (data)
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 3436): GC_CONCURRENT freed 1866K, 22% free 11855K/15120K, paused 8ms+19ms, total 147ms
W/SQLiteConnectionPool( 3436): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/System.out(13402): Thread-669(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(13402): Thread-669(ApacheHTTPLog):isShipBuild true
,I/System.out(13402): Thread-669(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 2418): GC_CONCURRENT freed 3658K, 56% free 24687K/55604K, paused 11ms+16ms, total 234ms
,I/System.out(13402): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(13402): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(13402): Max ALLOWED memory (MB): 128
V/ImageManager(13402): Max SHOULD USE memory (MB): 128
,V/ImageManager(13402): Max Image Cache memory (MB): 32
,D/skia    (13402): getTotalSize : Do not get file length
,D/@ WidgetProvider(13402): Building widget : 5
,D/dalvikvm( 5410): GC_CONCURRENT freed 1920K, 25% free 10421K/13888K, paused 6ms+4ms, total 56ms
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 62
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 283, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 63
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2418): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2418): <AppSync3 Whitelist>
,V/AlarmManager( 2418): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 64
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,E/SPPClientService( 5410): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,V/HeadsetService( 5024): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5024): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 65
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/jxcore-log( 6787): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,D/BluetoothAdapterService(1118414160)( 5024): unRegister RemoteMessageListener
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,D/HeadsetService( 5024): registerMessageListener
,D/HeadsetStateMachine( 5024): Disconnected process message: 80
,D/BluetoothAdapterState( 5024): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,I/BluetoothAdapterState( 5024): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 5024): Bluetooth PBAP supproted is true
,D/HeadsetStateMachine( 5024): processUnRegisterMessageListener : 2
,D/BluetoothAdapterService( 5024): updateAdapterState state is 13
,I/BluetoothPbapService( 5024): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,E/bt-btif ( 5024): bta_jv_rfcomm_stop_server
,D/BluetoothAdapterService( 5024): Broadcasting updateAdapterState() to 1 receivers.
,I/WifiManager( 6787): packageName : com.test.thalitest
,D/BluetoothAdapterService( 5024): Autoconnection is available 
D/BluetoothAdapterService( 5024): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 5024): terminating service from this receiver
W/ContextImpl( 5024): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.stopService:511 com.android.bluetooth.btservice.AdapterService.updateAdapterState:657 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
I/WifiManager( 6787): setWifiEnabled : false
D/BluetoothPbap( 5491): Proxy object disconnected
,D/PbapServerProfile( 5491): Bluetooth service disconnected
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,D/GKI_LINUX( 5024): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,I/BluetoothAdapterState( 5024): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
W/InputMethodManagerService( 2418): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2418): [BT Setting State] State =13
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
D/PhoneApp( 2753): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 13
,I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,I/SamsungIME( 2999): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
I/QuickConnect[1.1][2] ( 4997): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_OFF
I/wpa_supplicant( 6839): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 6839): wlan0: Setting scan request: 0 sec 0 usec
W/Settings( 2418): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2418): ignore requestNetworkTransitionWakelock airplane:true
,V/BluetoothEventManager( 5491): Received android.bluetooth.adapter.action.STATE_CHANGED
,I/wpa_supplicant( 6839): Scan requested (ret=0) - scan timeout 30 seconds
,D/BluetoothAdapterState( 5024): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/WifiP2pService( 2418): InactiveState{ what=143375 }
,D/WifiP2pService( 2418): P2pEnabledState{ what=143375 }
E/bt-btif ( 5024): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,I/WifiManager( 6787): packageName : com.test.thalitest
,D/STATUSBAR-IconMerger( 2578): checkOverflow(336), More:false, Req:false Child:3
E/bt-btif ( 5024): bta_jv_rfcomm_stop_server
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
E/BtOppRfcommListener( 5024): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btif ( 5024): bta_jv_rfcomm_stop_server
,E/bt-btif ( 5024): cmd socket is not created
,W/ContextImpl( 5491): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/btif_config_util( 5024): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
I/BtOppRfcommListener( 5024): stopping Accept Thread
I/BtOppRfcommListener( 5024): BluetoothSocket listen thread finished
D/CommandListener( 1915): Clearing all IP addresses on wlan0
,E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
D/IOP_DB_BT( 5024): db_close: nbr users 0
,D/IOP_DB_BT( 5024): db_close: free database
D/ConnectivityService( 2418): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2418): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2418): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2418): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2418): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2418): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
D/ConnectivityService( 2418): Attempting to switch to mobile
,D/ConnectivityService( 2418): Attempting to switch to BLUETOOTH_TETHER
D/DockEventReceiver( 5491): finishStartingService: stopping service
E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
E/WifiStateMachine( 2418): Error! unhandled message{ when=-9ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2418): Error! unhandled message{ when=-8ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
D/WifiP2pService( 2418): InactiveState{ what=131204 }
,D/BluetoothNotiBroadcastReceiver( 5491): onReceive
D/WifiP2pService( 2418): P2pEnabledState{ what=131204 }
D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,I/jxcore-log( 6787): {"id":0,"ok":false,"name":"Coordinator server got disconnected","operator":"fail","error":{},"test":59,"type":"assert"}
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,D/WifiP2pService( 2418): sending p2p connection changed broadcast: FAILED
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,W/WifiP2pStateTracker( 2418): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,I/WifiManager( 6787): packageName : com.test.thalitest
,I/WifiManager( 6787): setWifiEnabled : false
D/WifiDisplayController( 2418): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter( 2418): onP2pDisconnected
D/IpRemoteDisplayController( 2418): disconnectWfdBridgeServer
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
,D/IpRemoteDisplayController( 2418): WfdBridgeServer is already null
D/QuickConnect[1.1][2] ( 4997): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
V/RouteController( 1915): RTNETLINK answers: No such process
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
D/QuickConnect[1.1][2] ( 4997): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,E/WifiStateMachine( 2418): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController( 2418): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 2418): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,D/QuickConnect[1.1][2] ( 4997): SconnectManager.INetworkStateListener, onDisabled - mNetworkState : 0
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
D/WifiDisplayController( 2418): disconnect
D/WifiDisplayController( 2418): updateConnection
D/WifiDisplayController( 2418): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
D/WifiP2pService( 2418): sending p2p connection changed broadcast: DISCONNECTED
,D/WifiDisplayAdapter( 2418): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AuthorizationBluetoothService( 2849): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/QuickConnect[1.1][2] ( 4997): P2pHelper.cancelConnectPeer -  mTargetList clear all 
,D/QuickConnect[1.1][2] ( 4997): P2pHelper.removeP2pConfirm - skip: false
W/WifiP2pStateTracker( 2418): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController( 2418): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter( 2418): onP2pDisconnected
D/IpRemoteDisplayController( 2418): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 2418): WfdBridgeServer is already null
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,D/QuickConnect[1.1][2] ( 4997): CentralActionManager.removeHoldingIntentAll - all request done.
I/WifiManager( 6787): packageName : com.test.thalitest
,D/QuickConnect[1.1][2] ( 4997): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/WifiP2pService( 2418): P2pDisablingState
D/QuickConnect[1.1][2] ( 4997): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
D/QuickConnect[1.1][2] ( 4997): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
,I/WifiManager( 6787): setWifiEnabled : false
,D/WifiDisplayAdapter( 2418): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/NetworkManagementService( 2418): route cmd failed: 
W/NetworkManagementService( 2418): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2418): '
W/NetworkManagementService( 2418): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2418): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2418): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2418): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2418): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2418): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2418): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2418): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2418): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2418): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2418): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2418): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2418): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,D/WifiP2pService( 2418): P2pDisablingState{ what=139287 }
,E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
,D/QuickConnect[1.1][2] ( 4997): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
,D/WifiP2pService( 2418): DefaultState{ what=139287 }
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,D/WifiP2pService( 2418): P2pDisablingState{ what=147458 }
V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
D/WifiP2pService( 2418): p2p socket connection lost
D/WifiP2pService( 2418): P2pDisabledState
D/WifiP2pService( 2418): P2pDisabledState{ what=139376 }
D/WifiP2pService( 2418): DefaultState{ what=139376 }
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,I/WifiManager( 6787): packageName : com.test.thalitest
E/WifiP2pService( 2418): Unhandled message { what=139376 }
,D/WifiP2pService( 2418): P2pDisabledState{ what=139287 }
I/WifiManager( 6787): setWifiEnabled : false
V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,D/WifiP2pService( 2418): DefaultState{ what=139287 }
D/QuickConnect[1.1][2] ( 4997): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
D/BluetoothAdapterState( 5024): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 5024): isSecureModeOn:false
W/BluetoothAdapterService( 5024): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5024): Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5024): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5024): Not skipping com.android.bluetooth.hfp.HeadsetService
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
D/HeadsetService( 5024): Received stop request...Stopping profile...
D/CommandListener( 1915): Clearing all IP addresses on wlan0
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,D/NetUtils( 2418): android_net_utils_resetConnections in env=0x77c69a58 clazz=0x62b00001 iface=wlan0 mask=0x3
,D/ConnectivityService( 2418): resetConnections(wlan0, 3)
W/BluetoothAdapterService( 5024): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 5024): Not skipping com.android.bluetooth.a2dp.A2dpService
E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
D/NearbySettings( 5491): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 5491): DMSUtil.isNetworkConnected - flag-null, state-null
D/QuickConnect[1.1][2] ( 4997): HeadsetProfile.onServiceDisconnected - Bluetooth service disconnected
I/NearbySettings( 5491): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
W/BluetoothAdapterService( 5024): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 5024): Not skipping com.android.bluetooth.hid.HidService
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
W/BluetoothAdapterService( 5024): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 5024): Not skipping com.android.bluetooth.hdp.HealthService
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/NearbySettings( 5491): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 5491): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 5491): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 5491): MountReceiver.mPrefHandler - 7002
D/HeadsetProfile( 5491): Bluetooth service disconnected
W/BluetoothAdapterService( 5024): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.android.bluetooth.pan.PanService
E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6787): 
W/BluetoothAdapterService( 5024): Not skipping com.android.bluetooth.pan.PanService
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
W/BluetoothAdapterService( 5024): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 5024): Not skipping com.android.bluetooth.map.BluetoothMapService
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
W/BluetoothAdapterService( 5024): check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
W/BluetoothAdapterService( 5024): Not skipping com.broadcom.bt.service.sap.SapService
E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
D/NearbySettings( 5,491): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BluetoothAdapterState( 5024): Stopping profile services that were post enabled
V/NearbySettings( 5491): DMSUtil.isNetworkConnected - flag-null, state-null
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/NearbySettings( 5491): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
I/NearbySettings( 5491): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 5491): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 5491): MountReceiver.onReceive - Set preference state off
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
V/NearbySettings( 5491): MountReceiver.mPrefHandler - 7002
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5024): Profile still running: com.broadcom.bt.service.sap.SapService
D/FileShare-Server( 5876): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/FileShare-Server( 5876): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() DISCONNECTED
D/GKI_LINUX( 5024): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
W/BluetoothHeadsetServiceJni( 5024): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 5024): Cleaning up Bluetooth Handsfree callback object
D/A2dpService( 5024): Received stop request...Stopping profile...
D/A2dpStateMachine( 5024): Exit Disconnected: -1
D/Avrcp   ( 5024): Unregistering previous receiver
D/MediaFocusControl( 2418): <<< unregisterRemoteControlDisplay
E/SPPClientService( 5410): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
E/SPPClientService( 5410): [e] exceptionCaught(). NET_TIMEOUT
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
D/BluetoothA2dp( 4997): Proxy object disconnected
D/BluetoothA2dp( 2418): Proxy object disconnected
,D/QuickConnect[1.1][2] ( 4997): A2dpProfile.onServiceConnected - Bluetooth service disconnected
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
D/HidService( 5024): Received stop request...Stopping profile...
,D/HidService( 5024): Stopping Bluetooth HidService
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
D/BluetoothInputDevice( 4997): Proxy object disconnected
,D/QuickConnect[1.1][2] ( 4997): HidProfile.onServiceDisconnected - Bluetooth service disconnected
,D/HealthService( 5024): Received stop request...Stopping profile...
,D/PanService( 5024): Received stop request...Stopping profile...
,D/BluetoothPan( 2418): BluetoothPAN Proxy object disconnected
,D/BluetoothMapService( 5024): Received stop request...Stopping profile...
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,I/WifiManager( 6787): packageName : com.test.thalitest
D/SapService( 5024): Received stop request...Stopping profile...
,D/SapService( 5024): Stopping Bluetooth SapService
I/WifiManager( 6787): setWifiEnabled : false
,E/SPPClientService( 5410): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
D/BluetoothA2dp( 4127): Proxy object disconnected
D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5024): Profile still running: com.broadcom.bt.service.sap.SapService
,I/GKI_LINUX( 5024): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 5024): GKI_exit_task: GKI_exit_task 2 done
I/GKI_LINUX( 5024): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
,E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5024): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothHidServiceJni( 5024): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 5024): Cleaning up Bluetooth GID callback object
,D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5024): Profile still running: com.broadcom.bt.service.sap.SapService
,W/BluetoothHealthServiceJni( 5024): Cleaning up Bluetooth Health Interface...
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
,W/BluetoothHealthServiceJni( 5024): Cleaning up Bluetooth Health object
D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5024): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothPanServiceJni( 5024): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 5024): Cleaning up Bluetooth PAN callback object
,I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
,E/SPPClientService( 5410): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
E/SPPClientService( 5410): [b] ResponseMap empty
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
D/BtSettings.ProfileConfig( 5024): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5024): Profile still running: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5024): Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,D/BluetoothAdapterState( 5024): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 5024): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 5024): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5024): updateAdapterState state is 10
,D/BluetoothAdapterService( 5024): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterService( 5024): Autoconnection is available 
D/BluetoothAdapterService( 5024): updateAdapterState prevState = 13newState = 10
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/BluetoothAdapterState( 5024): Entering OffState
,W/BluetoothSAPServiceJni( 5024): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,W/BluetoothSAPServiceJni( 5024): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/BluetoothA2dp( 4127): onBluetoothStateChange: up=false
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
D/BluetoothA2dp( 5491): Proxy object disconnected
D/A2dpProfile( 5491): Bluetooth service disconnected
D/BluetoothInputDevice( 5491): Proxy object disconnected
,D/HidProfile( 5491): Bluetooth service disconnected
D/BluetoothPan( 5491): BluetoothPAN Proxy object disconnected
D/PanProfile( 5491): Bluetooth service disconnected
D/BluetoothMap( 5491): Proxy object disconnected
D/MapProfile( 5491): Bluetooth service disconnected
D/Bluetoothsap( 5491): BluetoothSAP Proxy object disconnected
D/SapProfile( 5491): Bluetooth service disconnected
,I/WifiManager( 6787): packageName : com.test.thalitest
,I/WifiManager( 6787): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
D/Bluetoothsap( 5491): onBluetoothStateChange: up=false
,D/Bluetoothsap( 5491): Unbinding service...
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,V/NativeCrypto( 2849): Read error: ssl=0x7b655f00: I/O error during system call, Connection timed out
,I/WifiManager( 6787): packageName : com.test.thalitest
D/Bluetoothsap( 5491): BluetoothSAP Proxy object disconnected
,D/SapProfile( 5491): Bluetooth service disconnected
,I/WifiManager( 6787): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
V/NativeCrypto( 2849): SSL shutdown failed: ssl=0x7b655f00: I/O error during system call, Broken pipe
,E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
,D/BluetoothInputDevice( 5491): onBluetoothStateChange: up=false
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,D/BluetoothPbap( 5491): onBluetoothStateChange: up=false
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,D/BluetoothA2dp( 2418): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 4997): onBluetoothStateChange: up=false
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,I/WifiManager( 6787): packageName : com.test.thalitest
,I/WifiManager( 6787): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,D/BluetoothMap( 5491): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 5491): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 4997): onBluetoothStateChange: up=false
,E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
,D/WifiNative( 2418): callSECApiBoolean - ID [13]
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
D/Bluetoothsap( 5491): onBluetoothStateChange: up=false
,D/Bluetoothsap( 5491): Unbinding service...
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
,I/wpa_supplicant( 6839): USE_NETWORK : USE_NETWORK OFF
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6787): 
E/WifiStateMachine( 2418): Error! unhandled message{ when=-20ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2418): Error! unhandled message{ when=-20ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,E/WifiStateMachine( 2418): Error! unhandled message{ when=-4ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2418): Error! unhandled message{ when=-4ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
,W/InputMethodManagerService( 2418): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2418): [BT Setting State] State =10
,I/InputMethodManagerService( 2418): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
I/SamsungIME( 2999): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
I/QuickConnect[1.1][2] ( 4997): BluetoothHelper.ACTION_STATE_CHANGED - STATE_OFF
D/PhoneApp( 2753): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 10
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
V/BluetoothEventManager( 5491): Received android.bluetooth.adapter.action.STATE_CHANGED
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
D/NearbySettings( 5491): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/WifiManager( 6787): packageName : com.test.thalitest
V/NearbySettings( 5491): DMSUtil.isNetworkConnected - flag-null, state-null
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
I/NearbySettings( 5491): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/NearbySettings( 5491): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 5491): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 5491): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 5491): MountReceiver.mPrefHandler - 7002
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/knox    ( 4940): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/WifiManager( 6787): packageName : com.test.thalitest
D/Tethering( 2418): interfaceLinkStateChanged p2p0, true
D/Tethering( 2418): interfaceStatusChanged p2p0, true
I/wpa_supplicant( 6839): p2p0: CTRL-EVENT-TERMINATING 
I/WifiManager( 6787): setWifiEnabled : false
D/Tethering( 2418): interfaceLinkStateChanged p2p0, false
D/Tethering( 2418): interfaceStatusChanged p2p0, false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT dis,able again.
I/wpa_supplicant( 6839): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
W/ContextImpl( 4940): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/wpa_supplicant( 6839): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
D/Tethering( 2418): interfaceStatusChanged wlan0, true
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
D/Tethering( 2418): interfaceStatusChanged wlan0, true
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
D/BluetoothTethering( 2418): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering( 2418): attempted to stop reverse tether with nothing tethered
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/knox    ( 4940): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
D/knox    ( 4940): KNOXAgentService : onCreate()
D/knox    ( 4940): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 4940): KNOXAgentService. startJobThread() start
D/knox    ( 4940): KNOXAgentService. JobThread()
D/knox    ( 4940): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 4940): KNOXAgentService. startJobThread() wait
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
D/ConnectivityService( 2418): handleInetConditionChange: no active default network - ignore
V/NetworkStats( 2418): updateIfacesLocked()
V/NetworkStats( 2418): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
V/NetworkStats( 2418): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
D/knox    ( 4940): KNOXAgentService : onDestroy().
D/knox    ( 4940): ModuleBase.cancelAllAlarmManageModule()
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,V/NetworkStats( 2418): performPollLocked() took 20ms
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,W/ContextImpl( 5491): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
D/DockEventReceiver( 5491): finishStartingService: stopping service
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
D/BluetoothNotiBroadcastReceiver( 5491): onReceive
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
D/Tethering( 2418): interfaceStatusChanged wlan0, true
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,D/AuthorizationBluetoothService( 2849): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,I/WifiManager( 6787): packageName : com.test.thalitest
,I/WifiManager( 6787): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,I/WifiManager( 6787): packageName : com.test.thalitest
,I/WifiManager( 6787): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,I/WifiManager( 6787): packageName : com.test.thalitest
,I/WifiManager( 6787): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,I/WifiManager( 6787): packageName : com.test.thalitest
,I/WifiManager( 6787): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,I/WifiManager( 6787): packageName : com.test.thalitest
,I/WifiManager( 6787): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,I/WifiManager( 6787): packageName : com.test.thalitest
,I/WifiManager( 6787): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,I/WifiManager( 6787): packageName : com.test.thalitest
,I/WifiManager( 6787): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,I/WifiManager( 6787): packageName : com.test.thalitest
,I/WifiManager( 6787): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,I/WifiManager( 6787): packageName : com.test.thalitest
,I/WifiManager( 6787): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Turning radios to false,
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.,
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): ,
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452,
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Turning radios to false,
I/jxcore-log( 6787): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
,I/WifiManager( 6787): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,I/WifiManager( 6787): packageName : com.test.thalitest
,I/WifiManager( 6787): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,I/wpa_supplicant( 6839): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering( 2418): interfaceLinkStateChanged wlan0, false
,D/Tethering( 2418): interfaceStatusChanged wlan0, false
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
D/Tethering( 2418): InitialState.processMessage what=4
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,E/Tethering( 2418): No numeric data
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,I/WifiManager( 6787): packageName : com.test.thalitest
,I/WifiManager( 6787): setWifiEnabled : false
,I/ConnectivityService( 2418): defaultVal : 1, tetherEnabledInSettings : true
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/Tethering( 2418): sendTetherStateChangedBroadcast 0, 0, 0
,V/NetworkStats( 2418): performPollLocked(flags=0x1)
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,V/NetworkStats( 2418): performPollLocked() took 22ms
I/WifiManager( 6787): packageName : com.test.thalitest
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6,787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
D/WifiStateMachine( 2418): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
W/Settings( 7255): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
W/Settings( 2735): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/knox    ( 4940): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,W/ContextImpl( 4940): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/knox    ( 4940): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
D/knox    ( 4940): KNOXAgentService : onCreate()
D/knox    ( 4940): KNOXAgentService : set alarms for deniallog and usage data upload
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
D/knox    ( 4940): KNOXAgentService. JobThread()
D/knox    ( 4940): KNOXAgentService. startJobThread() start
D/knox    ( 4940): KNOXAgentService. JobThread. notifyAll().
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
D/knox    ( 4940): KNOXAgentService. startJobThread() wait
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
D/knox    ( 4940): KNOXAgentService : onDestroy().
D/knox    ( 4940): ModuleBase.cancelAllAlarmManageModule()
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore,-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
D/WifiStateMachine( 2418): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/ApplicationPolicy( 2418): updateDataUsageMap
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
D/Tethering( 2418): Tethering got CONNECTIVITY_ACTION
D/Tethering( 2418): MasterInitialState.processMessage what=3
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
D/CaptivePortalTracker( 2418): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2418): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
D/STATUSBAR-NetworkController( 2578): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2578): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2578): updateDataNetType()
D/STATUSBAR-NetworkController( 2578): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4608): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/PCWCLIENTTRACE_PushUtil( 6102): SPPPushClient is installed : true
I/WifiManager( 6787): packageName : com.test.thalitest
I/PCWCLIENTTRACE_PushUtil( 6102): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6102): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6102): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver( 6102): noConnectivity : true
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
I/WifiManager( 6787): packageName : com.test.thalitest
I/WifiManager( 6787): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,D/libgps  ( 2418): agps_ril_update_network_state: Waiting for IPC connection...
,I/WifiManager( 6787): packageName : com.test.thalitest
,I/WifiManager( 6787): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,I/WifiManager( 6787): packageName : com.test.thalitest
,I/WifiManager( 6787): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,I/WifiManager( 6787): packageName : com.test.thalitest
,I/WifiManager( 6787): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,I/WifiManager( 6787): packageName : com.test.thalitest
,I/WifiManager( 6787): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
I/jxcore-log( 6787): The client has disconnected!
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Turning radios to false
I/jxcore-log( 6787): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6787): toggleBluetooth - 
I/jxcore-log( 6787): 
,I/WifiManager( 6787): packageName : com.test.thalitest
,I/WifiManager( 6787): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=6787, uid=10452
,I/jxcore-log( 6787): toggleWiFi
I/jxcore-log( 6787): 
,I/chromium( 6787): [INFO:CONSOLE(63)] "logCallback 0 isOK: false : Coordinator server got disconnected", source: file:///android_asset/www/js/thali_main.js (63)
,I/KLMS-2.3.201 : ( 7028): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7028): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1447854303174
,I/KLMS-2.3.201 : ( 7028): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/SO_AGENT( 7049): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7049): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 6263): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 6263): [BDLM] already registered in spp
I/SA      ( 6263): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 6263): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 6263): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6263): [OR] == isSIMCardReady false ==
I/SA      ( 6263): [SCU] == networkStateCheck == false
,I/SA      ( 6263): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 6047): Other Intent
,D/com.samsung.app( 7102): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7102): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 7140): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 7140): getCountryCode(): countryCode = PL
,D/Headlines( 7140): Breath.onCreate
,D/Headlines( 7140): Breath timer started. interval : 30000
,D/Headlines( 7140): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 7140): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 7140): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 7140): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 7140): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 7140): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 7140): requestUpdateNewsWelcomeCard !!! no welcome card
V/AlarmManager( 2418): waitForAlarm result :8
,I/iu.Environment( 5643): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 5643): num queued entries: 0
,D/QuickConnect[1.1][2] ( 4997): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 4997): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 4997): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42a91e78
,I/iu.UploadsManager( 5643): num updated entries: 0
,I/iu.SyncManager( 5643): NEXT; no task
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,I/Babel   ( 7255): connection state changed from CONNECTED to DISCONNECTED
,I/iu.Environment( 3436): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 3436): num queued entries: 0
,I/iu.UploadsManager( 3436): num updated entries: 0
,I/iu.SyncManager( 3436): NEXT; no task
,E/SPPClientService( 5410): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5410): [SystemStateMoniter] Current Time : 1974666
,E/SPPClientService( 5410): [SystemStateMoniter] No Connect : true
,D/Headlines( 7140): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 7140): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7140): Breath 170 latestRequest time : 1447854303302 current time : 1447854303472
,E/SPPClientService( 5410): [[SystemStateMonitorService]] No Active Internet
,E/SPPClientService( 5410): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5410): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5410): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/libgps  ( 2418): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2418): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2418): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2418): agps_ril_update_network_availability: Waiting for IPC connection...
,I/jxcore-log( 6787): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,D/libgps  ( 2418): agps_ril_update_network_availability: Waiting for IPC connection - timeout,
E/libgps  ( 2418): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2418): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/jxcore-log( 6787): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,I/jxcore-log( 6787): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6787): 
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
I/jxcore-log( 6787): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 6787): 
D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2

```
