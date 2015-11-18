#### Test 5105326159f447b_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2420): stay LED for fully charged
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/STATUSBAR-IconMerger( 2582): checkOverflow(384), More:false, Req:false Child:2
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AndroidRuntime( 6846): 
D/AndroidRuntime( 6846): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6846): CheckJNI is OFF
D/AndroidRuntime( 6846): setted country_code = Poland
D/AndroidRuntime( 6846): setted countryiso_code = PL
D/AndroidRuntime( 6846): setted sales_code = PLS
D/AndroidRuntime( 6846): readGMSProperty: start
D/AndroidRuntime( 6846): readGMSProperty: already setted!!
D/AndroidRuntime( 6846): readGMSProperty: end
D/AndroidRuntime( 6846): addProductProperty: start
D/dalvikvm( 6846): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6846): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6846): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6846): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6846): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6846): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6846): failed to load memtrack module: -2
D/dalvikvm( 6846): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6846): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2420): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@4
I/SurfaceFlinger( 1920): id=20 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1920): id=21 createSurf (16x16),-1 flag=20004, EimLayer
W/ActivityManager( 2420): mDVFSHelper.acquire()
I/SELinux ( 6875): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6875):  
D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6846): Shutting down VM
D/dalvikvm( 6846): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+0ms, total 3ms
I/SELinux ( 6875): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6875):  
I/SELinux ( 6875):  
I/SELinux ( 6875): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6875): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6875): >>>>> Normal User
E/dalvikvm( 6875): >>>>> com.test.thalitest [ userId:0 | appId:10448 ]
E/SELinux ( 6875): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 6875): in addTimaSignatureService
D/TimaKeyStoreProvider( 6875): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6875): Added TimaKesytore provider
V/WindowManager( 2420): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SQLiteSecureOpenHelper( 4113): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4113): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (8/10)
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (-2/10)
D/Launcher( 2773): onTrimMemory. Level: 20
D/dalvikvm( 6875): GC_CONCURRENT freed 3006K, 29% free 9559K/13456K, paused 2ms+1ms, total 17ms
D/dalvikvm( 6875): WAIT_FOR_CONCURRENT_GC blocked 15ms
V/WebViewChromium( 6875): Binding Chromium to the background looper Looper (main, tid 1) {422312f8}
I/chromium( 6875): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 6875): Initializing chromium process, renderers=0
W/chromium( 6875): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 6875): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 6875): loaded /system/lib/egl/libGLESv1_CM_mali.so
D/libEGL  ( 6875): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 6875): Mali API Version : 401
I/Mali    ( 6875): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 6875): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 6875): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 6875): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 6875): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 6875): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 6875): VFY: replacing opcode 0x6e at 0x0008
,D/StatusBarManagerService( 2420): tr p:6875,o:f
D/PhoneStatusBar( 2582): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
W/dalvikvm( 6875): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 6875): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 6875): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 6875): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 6875): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 6875): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 6875): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 6875): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 6875): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6875): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 6875): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 6875): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 6875): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2582): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2420): semi p:6875,o:f
,I/SurfaceFlinger( 1920): id=22 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 6875): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 6875): Enabling debug mode 0
,W/AwContents( 6875): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/AwContents( 6875): nativeOnDraw failed; clearing to background color.
D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2420): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@8
W/IInputConnectionWrapper( 6875): showStatusIcon on inactive InputConnection
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,D/JsMessageQueue( 6875): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 6875): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4222daa0
,D/dalvikvm( 6875): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4222daa0
,D/jxcore_app_log( 6875): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027067552
,D/JX-Cordova( 6875): jxcore cordova android initializing
,I/dalvikvm( 6875): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 6875): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 6875): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 6875): GC_CONCURRENT freed 1294K, 17% free 11336K/13516K, paused 1ms+2ms, total 22ms
,D/dalvikvm( 6875): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 6875): GC_CONCURRENT freed 2086K, 17% free 14769K/17756K, paused 2ms+2ms, total 38ms
,D/dalvikvm( 6875): WAIT_FOR_CONCURRENT_GC blocked 33ms
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 6875): GC_FOR_ALLOC freed 5131K, 29% free 15968K/22240K, paused 49ms, total 49ms
,D/dalvikvm( 6875): GC_CONCURRENT freed 6681K, 31% free 17457K/25048K, paused 1ms+9ms, total 61ms
,D/dalvikvm( 6875): WAIT_FOR_CONCURRENT_GC blocked 43ms
,D/dalvikvm( 6875): GC_FOR_ALLOC freed 1527K, 32% free 17158K/25048K, paused 50ms, total 50ms
,I/dalvikvm-heap( 6875): Grow heap (frag case) to 21.211MB for 3767174-byte allocation
,D/dalvikvm( 6875): GC_FOR_ALLOC freed 2483K, 37% free 18353K/28728K, paused 46ms, total 46ms
,W/jxcore-log( 6875): Initializing JXcore engine
,W/jxcore-log( 6875): JXcore engine is ready
,W/jxcore-log( 6875): Starting JXcore engine
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
I/TLC_TIMA_PKM_initialize( 2420): initializing...
I/TLC_TIMA_PKM_initialize( 2420): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 2420): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2420): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2420): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2420): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2420): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2420): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2420): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2420): device_id = 0x0
I/TZ: mc_tlc_communication( 2420): tlc_open() was called
I/TZ: mc_tlc_communication( 2420): Opening MobiCore device
I/TZ: mc_tlc_communication( 2420): Allocating WSM for TCI
I/TZ: mc_tlc_communication( 2420): Opening the session
,I/TZ: mc_tlc_communication( 2420): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2420): Trustlet response is completed
,W/jxcore-log( 6875): Platform android
W/jxcore-log( 6875): 
,W/jxcore-log( 6875): Process ARCH arm
W/jxcore-log( 6875): 
,I/PowerManagerService( 2420): [PWL] Off : 105s ago
,I/PowerManagerService( 2420): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2420): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2420): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2420, ws=null) (elapsedTime=427)
,I/jxcore-log( 6875): JXcore Cordova bridge is ready!
I/jxcore-log( 6875): 
,W/jxcore-log( 6875): JXcore engine is started
,I/chromium( 6875): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6875): Turning radios to true
I/jxcore-log( 6875): 
,W/ActivityManager( 2420): Permission Denial: getCurrentUser() from pid=6875, uid=10448 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 2420): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 2420): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6875, uid=10448 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 2420): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/BluetoothManagerService( 2420): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:620)
W/BluetoothManagerService( 2420): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
W/BluetoothManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DevicePolicyManagerService( 2420): getAllowBluetoothMode - value retunrs : 2
,D/BluetoothManagerService( 2420): foregroundUser: 0,
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
,E/BluetoothManagerService( 2420): Package is exist.
,I/WifiManager( 6875): packageName : com.test.thalitest
,I/WifiManager( 6875): setWifiEnabled : true
,I/WifiService( 2420): setWifiEnabled: true pid=6875, uid=10448
,W/ActivityManager( 2420): Permission Denial: getCurrentUser() from pid=6875, uid=10448 requires android.permission.INTERACT_ACROSS_USERS
D/BluetoothAdapterState( 5021): CURRENT_STATE=OFF, MSG = USER_TURN_ON
I/BluetoothAdapterState( 5021): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 5021): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5021): updateAdapterState state is 11
D/BluetoothAdapterService( 5021): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 5021): Autoconnection is available 
W/WifiService( 2420): Failed getting userId using ActivityManagerNative
W/WifiService( 2420): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6875, uid=10448 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2420): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2420): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2420): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2420): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapterService( 5021): updateAdapterState prevState = 10newState = 11
D/BtConfig.SecureMode( 5021): isSecureModeOn:false
,D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/InputMethodManagerService( 2420): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2420): [BT Setting State] State =11
D/PhoneApp( 2753): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 11
I/SamsungIME( 3050): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,E/WifiHW  ( 2420): ##################### set firmware type 0 #####################
I/WifiHW  ( 1915): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
E/WifiHW  ( 1915): Cannot open "/data/.cid.info": No such file or directory
I/WifiHW  ( 1915): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
E/WifiHW  ( 1915): TEMP_FAILURE_RETRY complete
,D/SoftapController( 1915): Softap fwReload - Ok
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
,I/QuickConnect[1.1][2] ( 4995): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_ON
W/BluetoothAdapterService( 5021): isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 5021): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/CommandListener( 1915): Setting iface cfg
,D/CommandListener( 1915): Trying to bring down wlan0
W/BluetoothAdapterService( 5021): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5021): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,D/WifiHW  ( 2420): Skip the update_ctrl_interface
,D/WifiHW  ( 2420): Skip the update_ctrl_interface
,E/WifiHW  ( 2420): supplicant_name : p2p_supplicant
,D/WifiMonitor( 2420): startMonitoring(wlan0) with mConnected = false
,W/BluetoothAdapterService( 5021): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5021): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/wpa_supplicant( 6922): wpa_supplicant v2.1-devel-4.4.22014-07-16/12:43:14
,I/wpa_supplicant( 6922): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 6922): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 6922): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 6922): getIMSI cannot open file
,E/wpa_supplicant( 6922): Interworking config: - SIM READ ERROR
,D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,D/BluetoothNotiBroadcastReceiver( 5476): onReceive,
,W/BluetoothAdapterService( 5021): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService,
,D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5021): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5021): Unable to stop service com.android.bluetooth.gatt.GattService. Invalid state: 12
W/BluetoothAdapterService( 5021): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 5021): Not skipping com.android.bluetooth.hfp.HeadsetService
,I/SELinux ( 6924): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6924):  
,W/BluetoothAdapterService( 5021): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5021): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5021): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5021): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5021): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5021): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5021): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 5021): Not skipping com.android.bluetooth.pan.PanService
I/SELinux ( 6924): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6924):  
I/SELinux ( 6924):  
,I/SELinux ( 6924): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6924): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6924): >>>>> Normal User
,E/dalvikvm( 6924): >>>>> pl.k2.droidoaudioteka [ userId:0 | appId:10066 ]
,E/SELinux ( 6924): [DEBUG] seapp_context_lookup: seinfoCategory = default
,W/BluetoothAdapterService( 5021): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5021): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5021): check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5021): Not skipping com.broadcom.bt.service.sap.SapService
,I/wpa_supplicant( 6922): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 6922): getIMSI cannot open file
,E/wpa_supplicant( 6922): Interworking config: - SIM READ ERROR
,I/wpa_supplicant( 6922): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 6922): rfkill: Cannot open RFKILL control device
,I/dalvikvm( 6924): Enabling JNI app bug workarounds for target SDK version 7...
,I/BluetoothAdapterState( 5021): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/QuickConnect[1.1][2] ( 4995): HeadsetProfile.onServiceConnected - Bluetooth service connected
,D/HeadsetService( 5021): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 5021): classInitNative: succeeds
D/HeadsetStateMachine( 5021): Version 1.5
,D/HeadsetStateMachine( 5021): make,
D/TimaKeyStoreProvider( 6924): in addTimaSignatureService
,E/HeadsetStateMachine( 5021): # of Max HF connection is 2,
,I/bluedroid( 5021): get_profile_interface handsfree,
,D/TimaKeyStoreProvider( 6924): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 6924): Added TimaKesytore provider,
,D/BluetoothAtMessage( 5021): createCMTIContentObservers,
,D/HeadsetStateMachine( 5021): Enter Disconnected: -2,
,E/HeadsetStateMachine( 5021): set to mRemoteBrsf = 0,
D/HeadsetStateMachine( 5021): map size, before remove : 0
D/HeadsetStateMachine( 5021): map size, after remove: 0
,D/HeadsetStateMachine( 5021): mNextConnectingDevice : null,
D/BluetoothA2dp( 4995): Proxy object connected
,D/BluetoothA2dp( 4113): Proxy object connected,
,D/QuickConnect[1.1][2] ( 4995): A2dpProfile.onServiceConnected - Bluetooth service connected
,D/BluetoothA2dp( 2420): Proxy object connected
D/A2dpService( 5021): Received start request. Starting profile...
,I/BluetoothA2dpServiceJni( 5021): classInitNative: succeeds
,D/A2dpStateMachine( 5021): make
,I/bluedroid( 5021): get_profile_interface a2dp
,I/GKI_LINUX( 5021): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 5021): Enter Disconnected: -2
,I/BluetoothAvrcpServiceJni( 5021): classInitNative: succeeds
,I/bluedroid( 5021): get_profile_interface avrcp
,D/MediaFocusControl( 2420): >>> registerRemoteControlDisplay
,I/BluetoothHidServiceJni( 5021): classInitNative: succeeds
D/BluetoothInputDevice( 4995): Proxy object connected
D/HidService( 5021): Received start request. Starting profile...
,I/bluedroid( 5021): get_profile_interface hidhost
,D/HidService( 5021): setHidService(): set to: null
,I/BluetoothHealthServiceJni( 5021): classInitNative: succeeds
,D/HealthService( 5021): Received start request. Starting profile...
,D/QuickConnect[1.1][2] ( 4995): HidProfile.onServiceConnected - Bluetooth service connected
,I/bluedroid( 5021): get_profile_interface health
,I/BluetoothPanServiceJni( 5021): classInitNative(L105): succeeds
,D/BluetoothPan( 2420): BluetoothPAN Proxy object connected
D/PanService( 5021): Received start request. Starting profile...
D/BluetoothPanServiceJni( 5021): initializeNative(L110): pan
,I/bluedroid( 5021): get_profile_interface pan
,D/dalvikvm( 6924): GC_CONCURRENT freed 2993K, 29% free 9566K/13452K, paused 3ms+1ms, total 39ms
,D/dalvikvm( 6924): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/BluetoothTethering( 2420): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothMapService( 5021): Received start request. Starting profile...
,W/BluetoothMapMasInstance( 5021): mAccount : null
,I/BluetoothSAPServiceJni( 5021): classInitNative(L204): succeeds
,D/SapService( 5021): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 5021): initializeNative(L209): sap
,I/bluedroid( 5021): get_profile_interface sap
,D/HeadsetStateMachine( 5021): Try to query the phonestate on bind
,D/BluetoothPhoneService( 2753): handleMessage: 4
,V/BluetoothPhoneService( 2753): Call state Converted2: IDLE/IDLE -> 6
,W/BluetoothHeadset( 2753): Proxy not attached to service
,D/HeadsetStateMachine( 5021): Proxy object connected
,D/HeadsetPhoneState( 5021): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetStateMachine( 5021): Disconnected process message: 11
,D/HeadsetPhoneState( 5021): sendDeviceDataStateChanged
D/HeadsetStateMachine( 5021): Disconnected process message: 20
,D/HeadsetPhoneState( 5021): Signal level : previous=0 curr=0
D/BluetoothAdapterService( 5021): Profile still not running:com.broadcom.bt.service.sap.SapService
V/HeadsetService( 5021): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5021): Disconnected process message: 10
D/HeadsetPhoneState( 5021): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 5021): Disconnected process message: 11
D/BluetoothAdapterService( 5021): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5021): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5021): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5021): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5021): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterState( 5021): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 5021): enable
,D/GKI_LINUX( 5021): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,E/bt-btif ( 5021): Calling BTA_HhEnable
,E/bt-btif ( 5021): btif_storage_get_adapter_property service_mask:0x160040
,E/BluetoothServiceJni( 5021): populateRssiValuesNative
I/bluedroid( 5021): getModelRssiValues
,E/BluetoothServiceJni( 5021): model_rssi_values_callback: low = -75, mid = -65, high = 127
,E/BluetoothRemoteDevices( 5021): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BtConfig.SecureMode( 5021): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5021): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 241
,E/BluetoothRemoteDevices( 5021): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 10
,D/BtConfig.SecureMode( 5021): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5021): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 241
,E/BluetoothRemoteDevices( 5021): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,D/BtConfig.SecureMode( 5021): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5021): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 241
,E/BluetoothRemoteDevices( 5021): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,D/BtConfig.SecureMode( 5021): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5021): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 241
,W/System.err( 6924): java.io.FileNotFoundException: /system/etc/vold.fstab: open failed: ENOENT (No such file or directory)
,E/BluetoothRemoteDevices( 5021): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
D/BtConfig.SecureMode( 5021): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5021): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 241
,E/BluetoothRemoteDevices( 5021): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/BtConfig.SecureMode( 5021): isSecureModeOn:false
E/BluetoothRemoteDevices( 5021): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 241
E/bt-btif ( 5021): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 5021): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
E/bt-btif ( 5021): btif_sock_init: !radio_req && !rfc_init
,D/IOP_DB_BT( 5021): db_open: file /etc/bluetooth/iop_bt.db
,W/System.err( 6924): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 6924): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 6924): 	at java.util.Scanner.<init>(Scanner.java:158)
W/System.err( 6924): 	at java.util.Scanner.<init>(Scanner.java:138)
W/System.err( 6924): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.readVoldFile(StorageOptions.java:107)
,W/System.err( 6924): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.determineStorageOptions(StorageOptions.java:31)
D/IOP_DB_BT( 5021): db_open: db_open : handle 2010211372l, read 9734 bytes onto local cache
D/IOP_DB_BT( 5021): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 5021): db_query: result 1
I/        ( 5021): iop_db_open: iop_db_open status 0
,I/bte_conf( 5021): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,W/System.err( 6924): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:81)
W/System.err( 6924): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:129)
I/bte_conf( 5021): [1] primary_record=1 vendor_id=0x0075 vendor_id_source=0x0001 product_id=0x0100 version=0x0200
I/bte_conf( 5021): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 5021): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,D/BluetoothAdapterState( 5021): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5021): ScanMode =  20
,D/BluetoothAdapterProperties( 5021): State =  11
D/BtConfig.SecureMode( 5021): isSecureModeOn:false
,D/BtConfig.SecureMode( 5021): isSecureModeOn:false
W/System.err( 6924): 	at pl.k2.droidoaudioteka.ui.AudiotekaApplication.onCreate(AudiotekaApplication.java:171)
D/BtConfig.SecureMode( 5021): isSecureModeOn:false
,D/BtConfig.SecureMode( 5021): isSecureModeOn:false
D/BtConfig.SecureMode( 5021): isSecureModeOn:false
D/BtConfig.SecureMode( 5021): isSecureModeOn:false
,I/BluetoothAdapterState( 5021): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterService( 5021): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5021): updateAdapterState state is 12
,W/System.err( 6924): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 6924): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 6924): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
,W/System.err( 6924): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 6924): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6924): 	at android.os.Looper.loop(Looper.java:146)
,W/System.err( 6924): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 6924): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 6924): 	at java.lang.reflect.Method.invoke(Method.java:515)
,W/System.err( 6924): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 6924): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 6924): 	at dalvik.system.NativeStart.main(Native Method)
,W/System.err( 6924): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
,W/System.err( 6924): 	at libcore.io.Posix.open(Native Method)
W/System.err( 6924): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 6924): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 6924): 	... 20 more
,D/BluetoothAdapterService( 5021): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterService(1109582480)( 5021): Register RemoteMessageListener
D/HeadsetService( 5021): registerMessageListener
D/BluetoothAdapterService( 5021): Autoconnection is available 
D/BluetoothAdapterService( 5021): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 5021): starting service from this receiver
,D/BluetoothInputDevice( 4995): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 4113): onBluetoothStateChange: up=true
W/System.err( 6924): file res dir: /data/data/pl.k2.droidoaudioteka/files
,W/System.err( 6924): Excternal dir: /mnt/sdcard
,D/BluetoothPanServiceJni( 5021): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
D/BluetoothA2dp( 2420): onBluetoothStateChange: up=true
W/ContextImpl( 5021): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.startService:506 com.android.bluetooth.btservice.AdapterService.updateAdapterState:653 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
,D/BluetoothA2dp( 4995): onBluetoothStateChange: up=true
,D/BluetoothAdapterService( 5021): initWakeLock, pfd lock: {ParcelFileDescriptor: FileDescriptor[85]}, pfd unlock: {ParcelFileDescriptor: FileDescriptor[86]}
,D/bluedroid( 5021): init_wake_lock lock_fd:85, unlock_fd:86
I/BluetoothAdapterState( 5021): Entering On State from state = 11
,D/HeadsetStateMachine( 5021): Disconnected process message: 70
D/HeadsetStateMachine( 5021): processRegisterMessageListener : 2, com.android.bluetooth.btservice.RemoteDevices$1@42293958
,I/BluetoothPbapService( 5021): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
W/InputMethodManagerService( 2420): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2420): [BT Setting State] State =12
,I/InputMethodManagerService( 2420): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/BluetoothAdapterService(1109582480)( 5021): Get Bonded Devices being called
I/SamsungIME( 3050): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
D/PhoneApp( 2753): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 12
I/QuickConnect[1.1][2] ( 4995): BluetoothHelper.ACTION_STATE_CHANGED - STATE_ON
D/BluetoothHeadset( 2753): registerListener : 11, listenercom.android.phone.PhoneGlobals$MessageListener@4245b478, true
D/BluetoothHeadset( 2753): registerMessageListener
D/HeadsetService( 5021): registerMessageListener
D/HeadsetService( 5021): registerMessageListener
D/HeadsetStateMachine( 5021): Disconnected process message: 70
D/HeadsetStateMachine( 5021): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@422fc308
D/PhoneApp( 2753): registerMessageListener
I/BluetoothPbapService( 5021): Handler(): got msg=1
,V/BluetoothPbapService( 5021): PBAP Service initSocket try: 0
,D/BluetoothMapMasInstance( 5021): set MAP SDP message type : 1
D/BluetoothAdapterService(1109582480)( 5021): Get Bonded Devices being called
W/BluetoothAdapter( 5021): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 5021): SOCK FLAG = 1 ***********************
D/BluetoothPbapService( 5021): PBAP Socket is BluetoothServerSocket
W/BluetoothAdapter( 5021): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 5021): SOCK FLAG = 3 ***********************
V/MaBo    ( 6924): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:2
,I/System.out( 6924): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6924): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6924): moge zapisać w resDir?true
,D/GKI_LINUX( 5021): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,V/MaBo    ( 6924): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
,D/BluetoothAdapterService(1109582480)( 5021): Get Bonded Devices being called
,I/System.out( 6924): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6924): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,W/GAV2    ( 6924): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GAV2    ( 6924): Thread[main,5,main]: ExceptionReporter created, original handler is pl.k2.droidoaudioteka.common.helpers.AudiotekaExceptionHandler
,I/AUDIOTEKA_GA( 6924): init tracking...
,I/AUDIOTEKA_GA( 6924): app started!
,I/BugSenseHandler( 6924): Registering default exceptions handler
,D/AuthorizationBluetoothService( 2837): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/DownloadService( 6924): Tworzenie serwisu - onCreate()
,I/DownloadService( 6924): Start serwisu - onStart()
,I/BugSenseHandler( 6924): Registering default exceptions handler
,I/BugSenseHandler( 6924): Flushing...
,I/PlayerService( 6924): Tworzenie serwisu - onCreate()
,I/MediaFocusControl( 2420):   Remote Control   registerMediaButtonIntent() for PendingIntent{44b39550: PendingIntentRecord{44b39518 pl.k2.droidoaudioteka broadcastIntent}}
,I/BugSenseHandler( 6924): Registering default exceptions handler
,V/AUDIOTEKA_MB( 6924): new AudioManagerFocusWrapper in playerservice oncreate
,I/PlayerService( 6924): Start serwisu - onStart()
,V/KeyguardUpdateMonitor( 2582): handleSetGenerationId(g=2, clear=true)
,I/BugSenseHandler( 6924): Flushing...
,I/BugSenseHandler( 6924): Registering default exceptions handler
,D/dalvikvm( 5476): GC_EXPLICIT freed 606K, 28% free 9799K/13452K, paused 3ms+6ms, total 114ms
,I/knox    ( 4935): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 4935): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/knox    ( 4935): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 4935): KNOXAgentService : onCreate()
D/knox    ( 4935): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 4935): KNOXAgentService. startJobThread() start
D/knox    ( 4935): KNOXAgentService. JobThread()
D/knox    ( 4935): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 4935): KNOXAgentService. startJobThread() wait
,I/SELinux ( 6968): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6968):  
,D/knox    ( 4935): KNOXAgentService : onDestroy().
,D/knox    ( 4935): ModuleBase.cancelAllAlarmManageModule()
,I/SELinux ( 6968): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6968):  
I/SELinux ( 6968):  
,I/SELinux ( 6968): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6968): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6968): >>>>> Normal User
,E/dalvikvm( 6968): >>>>> tv.peel.smartremote [ userId:0 | appId:10165 ]
,E/SELinux ( 6968): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 6968): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6968): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 6968): Added TimaKesytore provider
,D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,E/Tethering( 2420): No numeric data
,I/ConnectivityService( 2420): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering( 2420): sendTetherStateChangedBroadcast 1, 0, 0
D/NtpTrustedTime( 2420): forceRefresh() from cache miss
,D/dalvikvm( 6968): GC_CONCURRENT freed 2997K, 29% free 9565K/13452K, paused 3ms+1ms, total 65ms
,D/dalvikvm( 6968): WAIT_FOR_CONCURRENT_GC blocked 59ms
,I/wpa_supplicant( 6922): wlan0: Setting scan request: 0 sec 100000 usec
,D/NtpTrustedTime( 2420): forceRefresh Fail.
,V/NetworkStats( 2420): performPollLocked(flags=0x1)
,V/NetworkStats( 2420): performPollLocked() took 25ms
D/NtpTrustedTime( 2420): forceRefresh() from cache miss
D/NtpTrustedTime( 2420): forceRefresh Fail.
I/wpa_supplicant( 6922): >>>>> Not GET KEY, IV <<<<<
I/wpa_supplicant( 6922): >>>>> Not GET KEY, IV <<<<<
I/wpa_supplicant( 6922): rfkill: Cannot open RFKILL control device
D/Tethering( 2420): interfaceLinkStateChanged p2p0, true
D/Tethering( 2420): interfaceStatusChanged p2p0, true
,D/Tethering( 2420): interfaceLinkStateChanged p2p0, true
,D/Tethering( 2420): interfaceStatusChanged p2p0, true
,I/wpa_supplicant( 6922): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,W/ContextImpl( 5476): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
I/wpa_supplicant( 6922): P2P: initialized channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
I/wpa_supplicant( 6922): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant( 6922): Skip scan - bUseNetwork false
,D/WifiStateMachine( 2420): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
D/WifiNative( 2420): callSECApiString - ID [21]
,I/wpa_supplicant( 6922): HOTSPOT20_ENABLE called
,I/wpa_supplicant( 6922): wlan0: HS20_DISABLED_COMPLETE normal
,I/System.out( 6924): Thread-612(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/WifiNative( 2420): callSECApiInt - ID [65]
,I/System.out( 6924): Thread-612(ApacheHTTPLog):isShipBuild true
,I/System.out( 6924): Thread-612(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/WifiConfigStore( 2420): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative( 2420): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 6922): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 6922): reset timer : RESET_TIMER 0
I/wpa_supplicant( 6922): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 6922): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 6922): First Scan Start
,I/wpa_supplicant( 6922): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine( 2420): Set the Nv default ccode
,W/Settings( 5273): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/System.out( 6924): pool-1-thread-2 calls detatch()
,W/BugSenseHandler( 6924): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
I/System.out( 6924): pool-1-thread-1 calls detatch()
,W/BugSenseHandler( 6924): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
,D/WifiStateMachine( 2420): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,E/WifiStateMachine( 2420): HS20_DISABLED_COMPLETEnormal
D/WifiP2pService( 2420): P2pDisabledState{ what=131203 }
,D/CommandListener( 1915): Setting iface cfg
,D/LocalBluetoothProfileManager( 5476): Adding local A2DP profile
,D/CommandListener( 1915): Trying to bring up p2p0
,I/wpa_supplicant( 6922): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,D/WifiMonitor( 2420): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 2420): P2pEnablingState
D/WifiP2pService( 2420): P2pEnablingState{ what=147457 }
D/WifiP2pService( 2420): P2p socket connection successful
,E/WifiStateMachine( 2420): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiP2pService( 2420): P2pEnabledState
D/WifiDisplayController( 2420): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController( 2420): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 2420): disconnect
,D/QuickConnect[1.1][2] ( 4995): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
D/WifiDisplayController( 2420): updateConnection
D/WifiDisplayController( 2420): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiP2pService( 2420): sending p2p connection changed broadcast: IDLE
D/WifiDisplayAdapter( 2420): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/QuickConnect[1.1][2] ( 4995): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
D/WifiDisplayAdapter( 2420): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/WifiP2pStateTracker( 2420): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiDisplayController( 2420): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/QuickConnect[1.1][2] ( 4995): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/WifiDisplayController( 2420): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: S5mini-1
D/WifiDisplayController( 2420):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiDisplayController( 2420):  primary type: 10-0050F204-5
D/WifiDisplayController( 2420):  secondary type: null
D/WifiDisplayController( 2420):  wps: 0
D/WifiDisplayController( 2420):  grpcapab: 0
D/WifiDisplayController( 2420):  devcapab: 0
D/WifiDisplayController( 2420):  status: 3
D/WifiDisplayController( 2420):  wfdInfo: null
D/WifiDisplayController( 2420):  groupownerAddress: null
D/WifiDisplayController( 2420):  GOdeviceName: null
D/WifiDisplayController( 2420):  interfaceAddress: 
D/WifiDisplayController( 2420):  SConnectInfo : null
,D/QuickConnect[1.1][2] ( 4995): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
D/WifiP2pService( 2420): DeviceAddress: 02:e0:6d
,D/WifiP2pService( 2420): sending p2p persistent groups changed broadcast
,D/WifiP2pService( 2420): InactiveState
,D/WifiP2pService( 2420): InactiveState{ what=139287 }
D/WifiP2pService( 2420): P2pEnabledState{ what=139287 }
,D/QuickConnect[1.1][2] ( 4995): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/WifiP2pService( 2420): DefaultState{ what=139287 }
,D/LocalBluetoothProfileManager( 5476): Adding local HEADSET profile
W/ContextImpl( 5476): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
,E/BluetoothHeadset( 5476): BTStateChangeCB is registed
,W/ContextImpl( 5476): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
E/BluetoothHeadset( 5476): BluetoothHeadset service is binded
,D/Bluetoothsap( 5476): bindService called to Bluetooth SAP Service
W/ContextImpl( 5476): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,W/ContextImpl( 5476): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,W/ContextImpl( 5476): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
D/LocalBluetoothProfileManager( 5476): PANU : true
D/LocalBluetoothProfileManager( 5476): Adding local MAP profile
,D/BluetoothMap( 5476): Create BluetoothMap proxy object
W/ContextImpl( 5476): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,W/ContextImpl( 5476): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/Bluetoothsap( 5476): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 5476): LocalBluetoothProfileManager construction complete
,W/ContextImpl( 5476): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
I/System.out( 6924): pool-1-thread-2 calls detatch()
W/BugSenseHandler( 6924): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
,D/DockEventReceiver( 5476): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 5476): onReceive
,D/BluetoothA2dp( 5476): Proxy object connected
,D/A2dpProfile( 5476): Bluetooth service connected
,D/BtConfig.SecureMode( 5021): isSecureModeOn:false
,D/HeadsetProfile( 5476): Bluetooth service connected
,D/AuthorizationBluetoothService( 2837): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 2837): Proximity feature is not enabled.
,D/Bluetoothsap( 5476): BluetoothSAP Proxy object connected,
D/SapProfile( 5476): Bluetooth service connected
,D/Bluetoothsap( 5476): getConnectedDevices()
,D/BluetoothInputDevice( 5476): Proxy object connected
,D/HidProfile( 5476): Bluetooth service connected
,D/BluetoothPan( 5476): BluetoothPAN Proxy object connected
,D/PanProfile( 5476): Bluetooth service connected
I/System.out( 6924): pool-1-thread-1 calls detatch()
,W/BugSenseHandler( 6924): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
,W/BluetoothAdapter( 5021): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMap( 5476): Proxy object connected
,E/BluetoothServiceJni( 5021): SOCK FLAG = 0 ***********************
,D/GKI_LINUX( 5021): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,I/BtOppRfcommListener( 5021): Accept thread started.
,D/MapProfile( 5476): Bluetooth service connected
,D/BluetoothPbap( 5476): Proxy object connected
,D/PbapServerProfile( 5476): Bluetooth service connected
D/Bluetoothsap( 5476): BluetoothSAP Proxy object connected
D/SapProfile( 5476): Bluetooth service connected
,D/Bluetoothsap( 5476): getConnectedDevices()
,I/ActivityManager( 2420): Killing 5555:com.google.android.music:main/u0a125 (adj 15): empty #43
,I/knox    ( 4935): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 4935): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,D/knox    ( 4935): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
,I/knox    ( 4935): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 4935): KNOXAgentService : onCreate()
,D/knox    ( 4935): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 4935): KNOXAgentService. startJobThread() start
D/knox    ( 4935): KNOXAgentService. JobThread()
D/knox    ( 4935): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 4935): KNOXAgentService. startJobThread() wait
,D/knox    ( 4935): KNOXAgentService : onDestroy().
,D/knox    ( 4935): ModuleBase.cancelAllAlarmManageModule()
,D/NearbySettings( 5476): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 5476): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 5476): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 5476): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 5476): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5476): DMSUtil.isNetworkConnected - WIFI: IDLE
,I/NearbySettings( 5476): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5476): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 5476): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5476): MountReceiver.mPrefHandler - 7002
,D/FileShare-Server( 5878): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Server( 5878): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,D/GKI_LINUX( 5021): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,I/wpa_supplicant( 6922): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,I/wpa_supplicant( 6922): nl80211: Received scan results (3 BSSes)
,I/wpa_supplicant( 6922): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 6922): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2462 MHz)
,I/wpa_supplicant( 6922): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 6922): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-8ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 6922): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 6922): Associated with C0.AA.48
,I/wpa_supplicant( 6922): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 6922): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 6922): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 6922): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 6922): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,D/WifiNative( 2420): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7002): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7002):  
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7002): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7002):  
I/SELinux ( 7002):  
,I/SELinux ( 7002): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7002): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7002): >>>>> Normal User
,E/dalvikvm( 7002): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7002): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7002): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7002): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7002): Added TimaKesytore provider
,D/WifiP2pService( 2420): InactiveState{ what=143375 }
,D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,D/dalvikvm( 7002): GC_CONCURRENT freed 3001K, 29% free 9566K/13456K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 7002): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/System.out( 7002): Inside WakeupProvider
,I/System.out( 7002): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 7002): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7002): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7002): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,I/dhcpcd  ( 7014): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7014): bssid match
,D/NearbySettings( 5476): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5476): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5476): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
,I/NearbySettings( 5476): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5476): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5476): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5476): MountReceiver.mPrefHandler - 7002
,I/ActivityManager( 2420): Killing 5694:com.android.calendar/u0a144 (adj 15): empty #43
,D/DialogFlow( 7002): initQueue()
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 340, Delta = 20
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
V/HeadsetService( 5021): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5021): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:2
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;,
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 10,
,D/PackageManager( 2420): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiP2pService( 2420): InactiveState{ what=143375 }
,D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2420): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2420): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2420): CaptivePortalCheckState enter
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2420): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService( 2420): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2420): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
D/ConnectivityService( 2420): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2420): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2420): net.tcp.delack.wifi not found in system properties. Using defaults
,D/NearbySettings( 5476): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 5476): MountReceiver.onReceive - Keep current state
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/ConnectivityService( 2420): handleConnectivityChange: setting default proxy info 
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
D/NearbySettings( 5476): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.112 lookup 2 prio 150 2>&1
,V/NearbySettings( 5476): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5476): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 5476): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5476): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5476): MountReceiver.onReceive - Keep current state
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/NetworkStats( 2420): updateIfacesLocked()
,V/NetworkStats( 2420): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2420): forceRefresh() from cache miss
,V/NetworkStats( 2420): performPollLocked() took 27ms
,D/NearbySettings( 5476): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 5476): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger( 1920): id=23 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 2420): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2420
,I/GAV2    ( 6924): Thread[GAThread,5,main]: connecting to Analytics service
,W/ContextImpl( 6924): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:529 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 6924): Thread[GAThread,5,main]: connect: bindService returned true for Intent { act=com.google.android.gms.analytics.service.START (has extras) }
,D/NtpTrustedTime( 2420): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1447838145380 mCachedNtpElapsedRealtime : 319378 mCachedNtpCertainty : 9
,D/GAV2    ( 6924): Thread[main,5,main]: service connected, binder: android.os.BinderProxy@4249bdd0
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/GAV2    ( 6924): Thread[main,5,main]: bound to service
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,I/GAV2    ( 6924): Thread[main,5,main]: Connected to service
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,V/NetworkStats( 2420): advisePersistThreshold() given 9223372036854775, clamped to 2097152
I/GAV2    ( 6924): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 6924): Thread[GAThread,5,main]: putHit called
,I/GAV2    ( 6924): Thread[GAThread,5,main]: Sending hit to service
D/AmoledAdjustTimer( 2420): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/Tethering( 2420): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2420): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2420): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/        ( 2420): Setting time of day to sec=1447838145
,D/        ( 2420): Trying to open a file
,D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/        ( 2420): File Open Success
D/        ( 2420): File Close Success
,I/        ( 2420): DRM_TIME_PATH CHMOD 660 for resetState done 
V/AlarmManager( 2420): waitForAlarm result :65536
,D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
,I/DBG_DM  ( 4611): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
I/DBG_DM  ( 4611): [3.19.140541][Line:609][onReceive] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_DM  ( 4611): [3.19.140541][Line:214][xdmAgentTaskHandler] XEVENT_DM_INIT
,I/DBG_DM  ( 4611): [3.19.140541][Line:432][xdmInitAdpWaitSystemRootingCheck] Check completed.
,I/DBG_DM  ( 4611): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
I/PCWCLIENTTRACE_PushUtil( 6101): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6101): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6101): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6101): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 4611): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 4611): [3.19.140541][Line:78][xdmFeatureGetBearerSettingFromCSCFotaDataBase] 
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
D/StatusBar-DoNotDistrub( 2582): Received intent with android.intent.action.TIME_SET action
,D/StatusBar-DoNotDistrub( 2582): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/NotificationMgr( 2753): updateNotificationsAtStartup()...
D/NotificationMgr( 2753): - start call log query...
W/Settings( 2420): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/AudioService( 2420): getStreamVolume 5 index 110
D/StatusBar-DoNotDistrub( 2582): sendBroadcast android.intent.action.DORMANT_MODE_OFF
D/StatusBar-DoNotDistrub( 2582): The STREAM NOTIFICATION volume is 0
,E/Parcel  ( 2420): nm 23
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=com.android.systemui
,I/PrGenericPlugin( 1923): [A] ENTER onAcquireDrmInfo : 0xff5
,I/PrGenericPlugin( 1923): [A] LEAVE onAcquireDrmInfo : 0xff5
,I/DrmEventService( 2420):  no response from SecureClock 
,D/STATUSBAR-NotificationService( 2420): received android.intent.action.DORMANT_MODE_OFF
D/LightsService( 2420): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2420) 
,I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 5
D/Sensors ( 2420): LightSensor setDelay = 200000000
,D/Sensors ( 2420): LightSensor setSensorDelay = 200000000
D/Sensors ( 2420): Light sensor flush: not enabled 0
D/Sensors ( 2420): LightSensor enable = 1
,D/Sensors ( 2420): LightSensor enableSensor = 1
,D/LightsService( 2420): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/SensorManager( 2420): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,I/SQLiteSecureOpenHelper( 4113): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4113): getDatabaseLocked(b,b,pwd)...
,I/SELinux ( 7072): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7072):  
,D/dalvikvm( 1921): WAIT_FOR_CONCURRENT_GC blocked 1ms
,I/DBG_DM  ( 4611): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 9% free 9502K/10436K, paused 2ms+4ms, total 32ms
I/SELinux ( 7072): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7072):  
I/SELinux ( 7072):  
,I/SELinux ( 7072): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7072): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7072): >>>>> Normal User
,E/dalvikvm( 7072): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
,E/SELinux ( 7072): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 9% free 9502K/10436K, paused 2ms+3ms, total 26ms
,D/TimaKeyStoreProvider( 7072): in addTimaSignatureService
,I/DBG_DM  ( 4611): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,D/TimaKeyStoreProvider( 7072): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7072): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 9% free 9502K/10436K, paused 3ms+3ms, total 26ms
,D/btif_config_util( 5021): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/Sensors ( 2420): LightSensor enable = 0
,D/Sensors ( 2420): LightSensor enableSensor = 0
,D/SensorManager( 2420): unregisterListener ::   
D/LightsService( 2420): [SvcLED]  onSensorChanged::light value = 8
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/dalvikvm( 4611): Total arena pages for JIT: 11
,I/dalvikvm( 4611): Total arena pages for JIT: 12
,I/dalvikvm( 4611): Total arena pages for JIT: 13
I/dalvikvm( 4611): Total arena pages for JIT: 14
I/dalvikvm( 4611): Total arena pages for JIT: 15
,I/dalvikvm( 4611): Total arena pages for JIT: 16
,I/dalvikvm( 4611): Total arena pages for JIT: 17
,I/DBG_DM  ( 4611): [3.19.140541][Line:5949][xdbGetFUMOInitiatedType] Initiated Type: 2
,I/DBG_DM  ( 4611): [3.19.140541][Line:119][xdmInitAdpEXTInit] nStatus [220]
,I/DBG_DM  ( 4611): [3.19.140541][Line:463][xdmGetEnableLiveDemoFromCSCFeature] enable LiveDemo : false
,E/DBG_DM  ( 4611): Warning!!! [3.19.140541][Line:65][xdmInitAdpGetSIMLockState] SIM Status is not ready
,D/dalvikvm( 2420): GC_EXPLICIT freed 2986K, 55% free 24436K/53836K, paused 15ms+25ms, total 312ms
,D/NotificationMgr( 2753): call log query complete.
D/NotificationMgr( 2753): call log cursor count : 0
,D/NotificationMgr( 2753): call log cursor count2 : null
,D/dalvikvm( 7072): GC_CONCURRENT freed 2998K, 29% free 9570K/13460K, paused 3ms+13ms, total 70ms
,D/dalvikvm( 7072): WAIT_FOR_CONCURRENT_GC blocked 64ms
,I/SQLiteSecureOpenHelper( 4113): getWritableDatabase(pwd)
,I/jxcore-log( 6875): Attempting to connect to the test coordinator server
I/jxcore-log( 6875): 
,I/SQLiteSecureOpenHelper( 4113): getDatabaseLocked(b,b,pwd)...
,I/DBG_DM  ( 4611): [3.19.140541][Line:261][xdmInitAdpEXTInit] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 4611): [3.19.140541][Line:271][xdmAgentTaskHandler] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 4611): [3.19.140541][Line:1854][xdmAgentCheckResumeNoti] 
,I/DBG_DM  ( 4611): [3.19.140541][Line:318][xdmBroadcastGetIsSavedNfcMode] m_IsSavedNfcMode : false
,I/DBG_DM  ( 4611): [3.19.140541][Line:769][xdmUIEvent] XUI_DL_UPDATE_START
,I/DBG_DM  ( 4611): [3.19.140541][Line:546][xuiAdpGetUpdateReport] Get bUpdateReport = false
,I/DBG_DM  ( 4611): [3.19.140541][Line:369][handleMessage] event ->214
,I/DBG_DM  ( 4611): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 4611): [3.19.140541][Line:2008][xdmCallUiFotaInstall] 
,I/DBG_DM  ( 4611): [3.19.140541][Line:729][xdmUIEvent] XUI_DL_UPDATE_CONFIRM
W/ContextImpl( 4611): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 com.wssyncmldm.XDMService.xdmCallUiFotaInstall:2023 com.wssyncmldm.XDMService$1.handleMessage:372 android.os.Handler.dispatchMessage:102 
,I/SELinux ( 7087): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7087):  
,I/DBG_DM  ( 4611): [3.19.140541][Line:1320][xdmCheckIdleScreen] Idle Screen : false
I/DBG_DM  ( 4611): [3.19.140541][Line:890][xdmUnRegisterBatteryReceiver] 
E/DBG_DM  ( 4611): Warning!!! [3.19.140541][Line:898][xdmUnRegisterBatteryReceiver] didn't register
,E/DBG_DM  ( 4611): Warning!!! [3.19.140541][Line:899][xdmUnRegisterBatteryReceiver] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.XDMService$3@423449a0
,I/dalvikvm( 4611): Total arena pages for JIT: 18
I/SELinux ( 7087): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7087):  
I/SELinux ( 7087):  
,I/SELinux ( 7087): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7087): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7087): >>>>> Normal User
,E/dalvikvm( 7087): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7087): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/DBG_DM  ( 4611): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,D/TimaKeyStoreProvider( 7087): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7087): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7087): Added TimaKesytore provider
,I/DBG_DM  ( 4611): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,D/dalvikvm( 7087): GC_CONCURRENT freed 2990K, 29% free 9576K/13456K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 7087): WAIT_FOR_CONCURRENT_GC blocked 14ms
,E/dalvikvm( 7072): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a
W/dalvikvm( 7072): VFY: unable to resolve new-instance 406 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm( 7072): VFY: replacing opcode 0x22 at 0x0000
W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
D/STATUSBAR-StatusBarManagerService( 2420): sendNotification(1) - 4
,W/ResourceType( 2582): Attempt to retrieve bag 0x01030068 which is invalid or in a cycle.
,W/ResourceType( 2582): Attempt to retrieve bag 0x01030067 which is invalid or in a cycle.
,D/ProgressBar( 2582): setProgressDrawable drawableHeight = 12
,D/ProgressBar( 2582): setProgressDrawable drawableHeight = 12
,D/PhoneStatusBar( 2582): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@42250440
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
W/dalvikvm( 7072): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 7072): Link of class 'Lal;' failed
E/dalvikvm( 7072): Could not find class 'al', referenced from method b.a
W/dalvikvm( 7072): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
D/dalvikvm( 7072): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 7072): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 7072): Link of class 'Lan;' failed
E/dalvikvm( 7072): Could not find class 'an', referenced from method b.a
W/dalvikvm( 7072): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
D/dalvikvm( 7072): VFY: replacing opcode 0x22 at 0x002a
I/dalvikvm( 7072): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm( 7072): VFY: unable to resolve virtual method 5407: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 7072): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 7072): Could not find method android.view.View.getTransitionName, referenced from method b.a
W/dalvikvm( 7072): VFY: unable to resolve virtual method 5231: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 7072): VFY: replacing opcode 0x6e at 0x0006
,W/dalvikvm( 7072): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 7072): Could not find class 'android.app.RemoteInput[]', referenced from method b.a
W/dalvikvm( 7072): VFY: unable to resolve new-array 12200 ([Landroid/app/RemoteInput;) in Lb;
,D/dalvikvm( 7072): VFY: replacing opcode 0x23 at 0x0005
,D/dalvikvm( 7072): DexOpt: unable to opt direct call 0x090f at 0x0e in Lb;.a
W/dalvikvm( 7072): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 7072): Link of class 'Lal;' failed
,D/dalvikvm( 7072): DexOpt: unable to opt direct call 0x068d at 0x08 in Lb;.a
W/dalvikvm( 7072): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 7072): Link of class 'Lan;' failed
D/dalvikvm( 7072): DexOpt: unable to opt direct call 0x0802 at 0x2c in Lb;.a
,D/dalvikvm( 7072): DexOpt: unable to opt direct call 0x0957 at 0x13 in Lb;.a
,I/dalvikvm( 7072): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method dyp.a
W/dalvikvm( 7072): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7072): VFY: replacing opcode 0x6e at 0x000d
,I/SELinux ( 7105): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7105):  
,I/SELinux ( 7105): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7105):  
I/SELinux ( 7105):  
I/SELinux ( 7105): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7105): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7105): >>>>> Normal User
E/dalvikvm( 7105): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7105): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7105): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7105): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7105): Added TimaKesytore provider
D/dalvikvm( 7072): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7072): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7072): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7072): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7072): VFY: unable to resolve instance field 46
,D/dalvikvm( 7072): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 7072): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7072): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7072): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 7072): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 7072): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 7072): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42303788
,D/dalvikvm( 7072): Added shared lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42303788
,D/dalvikvm( 7072): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42303788, skipping init
,D/dalvikvm( 7072): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x42303788
D/dalvikvm( 7072): Added shared lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x42303788
,V/JNIHelp ( 7072): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/dalvikvm( 7105): GC_CONCURRENT freed 2987K, 29% free 9572K/13452K, paused 3ms+1ms, total 30ms
,D/dalvikvm( 7105): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/KLMS-2.3.201 : ( 7105): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7105): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1447838146964
,I/dalvikvm( 7072): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 7072): VFY: unable to resolve static method 1165: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 7072): VFY: replacing opcode 0x71 at 0x0046
,I/KLMS-2.3.201 : ( 7105): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/dalvikvm( 7072): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42303788
,D/dalvikvm( 7072): Shared lib '/data/app-lib/com.google.android.gms-4/libgmscore.so' already loaded in same CL 0x42303788
D/dalvikvm( 7072): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x42303788
,D/dalvikvm( 7072): Shared lib '/data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42303788
,I/SELinux ( 7128): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7128):  
,I/SELinux ( 7128): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7128):  
I/SELinux ( 7128):  
I/SELinux ( 7128): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7128): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7128): >>>>> Normal User
E/dalvikvm( 7128): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7128): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/LocationTagReadyService( 3418): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3418): [Slink platform] The state of Slink geocode service is true
,D/TimaKeyStoreProvider( 7128): in addTimaSignatureService
,W/WifiP2pStateTracker( 2420): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
D/TimaKeyStoreProvider( 7128): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7128): Added TimaKesytore provider
D/ConnectivityService( 2420): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2420):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
D/ConnectivityService( 2420): handleConnectivityChange: setting default proxy info 
D/ConnectivityService( 2420): updateSourceRoutes : no source routing conditions
,I/dalvikvm( 3139): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 3139): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 3139): VFY: replacing opcode 0x6e at 0x0033
,D/GalaxyFinderApplication( 3418): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3418): [Slink platform] The state of Slink geocode service is true
,I/ProviderInstaller( 7072): Installed default security provider GmsCore_OpenSSL
I/dalvikvm( 7072): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
W/dalvikvm( 7072): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7072): VFY: replacing opcode 0x6e at 0x000d
,I/GallerySearchProvider( 3561): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/dalvikvm( 7072): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 7072): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 7072): VFY: replacing opcode 0x6e at 0x0220
,I/SELinux ( 7142): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7142):  
,I/SELinux ( 7142): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7142):  
I/SELinux ( 7142):  
,I/SELinux ( 7142): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7142): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7142): >>>>> Normal User
,E/dalvikvm( 7142): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7142): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7142): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7142): Cannot add TimaSignature Service, License check Failed
,E/YouTube MDX( 7072): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/dalvikvm( 2721): GC_EXPLICIT freed 317K, 31% free 9947K/14348K, paused 4ms+13ms, total 125ms
,D/ActivityThread( 7142): Added TimaKesytore provider
,D/dalvikvm( 7128): GC_CONCURRENT freed 2997K, 29% free 9565K/13452K, paused 3ms+1ms, total 94ms
,D/dalvikvm( 7128): WAIT_FOR_CONCURRENT_GC blocked 86ms
,D/dalvikvm( 7072): DexOpt: --- BEGIN 'ads-1564287492.jar' (bootstrap=0) ---
,D/SO_AGENT( 7128): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7128): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/dalvikvm( 7142): GC_CONCURRENT freed 3000K, 29% free 9566K/13456K, paused 3ms+8ms, total 30ms
,D/dalvikvm( 7142): WAIT_FOR_CONCURRENT_GC blocked 23ms
,V/KVNProvider( 7142): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7142): getFindoCursor query string : 
,E/Auth.Api.Credentials( 3139): [CredentialSyncAdapter] Unknown sync event.
,I/SA      ( 6263): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,V/KVNProvider( 7142): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 6263): [BDLM] already registered in spp
I/SA      ( 6263): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,I/SA      ( 6263): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7072): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/SA      ( 6263): [SLFUCHKMGR] constructor called
,D/dalvikvm( 6205): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42229b78, skipping init
I/SA      ( 6263): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6263): [OR] == isSIMCardReady false ==
,I/SA      ( 6263): [SCU] == networkStateCheck == true
I/SA      ( 6263): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6263): isChinaCountryCode : false
,I/SA      ( 6263): [OR] == networkStateCheck true ==
,I/SA      ( 6263): [OR] GetMyCountryZoneTask
,I/SA      ( 6263): [OR] onReceive END
I/ActivityManager( 2420): Killing 5760:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/DelayedSyncController( 5975): Delaying sync.
,I/SA      ( 6263): [SRS] prepareGetMyCountryZone
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
,I/SecureStorage( 6205): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 1964): [INFO]: SPID(0x00000004)Credentials: uid 1000, gid 1000, pid 6205
,I/SecureStorage( 1964): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
,I/SCloudBackupReceiver( 6036): Other Intent
,I/SA      ( 6263): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6263): [SSP] query invoked,
,I/SELinux ( 7187): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7187):  
,I/SELinux ( 7187): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7187):  
I/SELinux ( 7187):  
,I/SELinux ( 7187): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7187): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7187): >>>>> Normal User
,E/dalvikvm( 7187): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ],
,E/SELinux ( 7187): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,D/dalvikvm( 7072): GC_CONCURRENT freed 1896K, 21% free 10722K/13460K, paused 20ms+9ms, total 145ms,
,D/TimaKeyStoreProvider( 7187): in addTimaSignatureService,
,D/dalvikvm( 7161): DexOpt: load 6ms, verify+opt 14ms, 194052 bytes,
,D/TimaKeyStoreProvider( 7187): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7187): Added TimaKesytore provider
,I/GoogleURLConnFactory( 3139): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 7072): DexOpt: --- END 'ads-1564287492.jar' (success) ---
,D/dalvikvm( 7072): DEX prep '/data/data/com.google.android.youtube/cache/ads-1564287492.jar': unzip in 0ms, rewrite 406ms
,I/SA      ( 6263): [TPMU] GetMccFromDB : null
,I/SA      ( 6263): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6263): [TPM] isNoProxy(default) : true
,I/SA      ( 6263): [RC New] Execute method=[GET] start
,I/System.out( 7087): Thread-609(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7087): Thread-609(ApacheHTTPLog):isShipBuild true
,I/System.out( 7087): Thread-609(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection...,
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
,I/dalvikvm( 7072): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner,
D/dalvikvm( 7187): GC_CONCURRENT freed 2999K, 29% free 9570K/13456K, paused 3ms+1ms, total 88ms
W/dalvikvm( 7072): VFY: unable to resolve virtual method 2614: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 7072): VFY: replacing opcode 0x6e at 0x0002,
D/dalvikvm( 7187): WAIT_FOR_CONCURRENT_GC blocked 83ms
I/dalvikvm( 7072): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 7072): VFY: unable to resolve virtual method 2615: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;,
D/dalvikvm( 7072): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7072): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 7072): VFY: unable to resolve virtual method 2622: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 7072): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7072): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 7072): VFY: unable to resolve virtual method 2623: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;,
D/dalvikvm( 7072): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7072): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method agv.getLeanbackLaunchIntentForPackage
W/dalvikvm( 7072): VFY: unable to resolve virtual method 2639: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 7072): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7072): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method agv.getPackageInstaller,
W/dalvikvm( 7072): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 7072): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7072): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method agv.getUserBadgedDrawableForDensity
W/dalvikvm( 7072): VFY: unable to resolve virtual method 2659: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 7072): VFY: replacing opcode 0x6e at 0x0002,
I/dalvikvm( 7072): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method agv.getUserBadgedIcon
W/dalvikvm( 7072): VFY: unable to resolve virtual method 2660: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 7072): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7072): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method agv.getUserBadgedLabel
,W/dalvikvm( 7072): VFY: unable to resolve virtual method 2661: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm( 7072): VFY: replacing opcode 0x6e at 0x0002,
,V/GLSActivity( 2837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
V/GLSActivity( 2837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system,
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30,
W/ContextImpl( 7072): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system,
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30,
W/ContextImpl( 7072): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system,
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30,
W/ContextImpl( 7072): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 7072): Found 10012,
,D/com.samsung.app( 7187): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7187): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7187): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7187): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,D/com.samsung.app( 7187): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,W/ContextImpl( 7072): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
D/com.samsung.app( 7187): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,I/System.out( 7087): AsyncTask #1 calls detatch()
,D/daemonapp( 5219): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7187): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5219): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,W/System.err( 7087): com.sec.android.fota.osp.http.RestClientException
,W/System.err( 7087): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
,W/System.err( 7087): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
,W/System.err( 7087): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
,W/System.err( 7087): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,D/com.samsung.app( 7187): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,W/System.err( 7087): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7087): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 7087): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 7087): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7087): 	at java.lang.Thread.run(Thread.java:841)
D/daemonapp( 5219): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/System.err( 7087): Caused by: java.lang.NullPointerException
,W/System.err( 7087): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7087): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7087): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7087): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7087): 	... 8 more
,D/com.samsung.app( 7187): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7187): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2420): Killing 5756:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,I/SELinux ( 7221): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7221):  
,I/ActivityManager( 2420): Killing 5273:com.google.android.talk/u0a109 (adj 15): empty #43
,I/SELinux ( 7221): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7221):  
I/SELinux ( 7221):  
,I/SELinux ( 7221): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7221): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7221): >>>>> Normal User
,E/dalvikvm( 7221): >>>>> com.samsung.android.internal.headlines [ userId:0 | appId:10110 ]
,E/SELinux ( 7221): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7221): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7221): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7221): Added TimaKesytore provider
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 7221): GC_CONCURRENT freed 3003K, 29% free 9566K/13460K, paused 14ms+1ms, total 41ms
,D/dalvikvm( 7221): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/HeadlinesChannelApplication( 7221): [onCreate]
,D/Headlines( 7221): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,E/WifiStateMachine( 2420): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/HeadlinesChannelUtil( 7221): getCountryCode(): countryCode = PL
,I/System.out( 3139): Thread-189(HTTPLog):isShipBuild true
,I/System.out( 3139): Thread-189(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 7072): Thread-668(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/SELinux ( 7251): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7251):  
D/Headlines( 7221): Breath.onCreate
D/HeadlinesCardManager( 7221): HeadlinesCardManager : constructor
E/HeadlinesCardManager( 7221): HeadlinesCardManager : ctor = image_cache size is 42MB
D/SA Version( 7221): CardProvider Library : 13
I/SELinux ( 7251): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7251):  
I/SELinux ( 7251):  
I/SELinux ( 7251): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7251): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7251): >>>>> Normal User
E/dalvikvm( 7251): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7251): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/MagazineService::CardProviderContentProvider( 6308): insertProvider: provider already exists.: com.samsung.android.app.headlines
,D/MagazineService::CardProviderContentProvider( 6308): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/TimaKeyStoreProvider( 7251): in addTimaSignatureService
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 7221): registerCardProvider: provider already exists.
,D/TimaKeyStoreProvider( 7251): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7251): Added TimaKesytore provider
,I/Headlines( 7221): HeadlinesDataCenter ctor
,I/Headlines( 7221): HeadlinesDataCenter. mLocale = en_US
,D/HeadlinesChannelUtil( 7221): getCountryCode(): countryCode = PL
,D/HeadlinesCardManager( 7221): HeadlinesCardManager : constructor welcome :YES
,D/Headlines( 7221): Breath timer started. interval : 30000
,I/System.out( 6263): Thread-569(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
D/Headlines( 7221): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 7221): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 7221): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 7221): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 7221): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 7221): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 7221): requestUpdateNewsWelcomeCard !!! no welcome card
,D/dalvikvm( 7251): GC_CONCURRENT freed 2996K, 29% free 9575K/13460K, paused 4ms+1ms, total 27ms
,D/dalvikvm( 7251): WAIT_FOR_CONCURRENT_GC blocked 13ms
I/System.out( 6263): Thread-569(ApacheHTTPLog):isShipBuild true
,I/System.out( 6263): Thread-569(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 7072): Thread-668(ApacheHTTPLog):isShipBuild true
,I/System.out( 7072): Thread-668(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/SurfaceFlinger( 1920): id=23 Removed Uoast (10/11)
,I/SurfaceFlinger( 1920): id=23 Removed Uoast (-2/11)
I/ActivityManager( 2420): Killing 5781:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,D/PowerManagerService( 2420): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2420) eventTime = 322779
D/PowerManagerService( 2420): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2420 (0x0)
,D/PowerManagerService( 2420): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2420, ws=WorkSource{1000}) (elapsedTime=3459)
,I/SurfaceFlinger( 1920): id=24 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 2420): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2420
,I/SecureStorage( 1964): [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 1964): [INFO]: SPID(0x00000004)PID: 6205, TID: 6231
,V/WebViewChromium( 7251): Binding Chromium to the background looper Looper (main, tid 1) {42231050}
,I/chromium( 7251): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7251): Initializing chromium process, renderers=0
,W/chromium( 7251): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection...
,D/libEGL  ( 7251): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7251): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7251): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7251): Mali API Version : 401
,I/Mali    ( 7251): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/SecureStorage( 6205): [INFO]: SPID(0x00000000)Processing data has been completed
,W/GAV2    ( 7251): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7251): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/dalvikvm( 7072): GC_CONCURRENT freed 1344K, 17% free 11352K/13584K, paused 15ms+9ms, total 91ms
,I/System.out( 7072): Thread-668 calls detatch()
,W/ActivityThread( 6205): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/System.out( 7072): Thread-668 calls detatch()
,D/dalvikvm( 2420): GC_EXPLICIT freed 1743K, 55% free 24389K/53836K, paused 10ms+16ms, total 185ms
,I/NSApplication( 7251): Starting up...
,I/ImageResourceManager( 5643): ImageResourceManager: uninitalized
,D/dalvikvm( 5643): GC_FOR_ALLOC freed 148K, 27% free 9824K/13456K, paused 26ms, total 29ms
,I/dalvikvm-heap( 5643): Grow heap (frag case) to 12.493MB for 2129936-byte allocation
,D/dalvikvm( 5643): GC_FOR_ALLOC freed 7K, 24% free 11896K/15540K, paused 16ms, total 16ms
,I/iu.Environment( 5643): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/ActivityManager( 2420): Killing 6021:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/QuickConnect[1.1][2] ( 4995): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 4995): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 4995): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4223b9f0
,I/System.out( 7072): Thread-668 calls detatch()
,I/SELinux ( 7300): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7300):  
,I/iu.UploadsManager( 5643): num queued entries: 0
,D/dalvikvm( 5643): GC_CONCURRENT freed 9K, 24% free 11901K/15540K, paused 2ms+2ms, total 53ms
,D/dalvikvm( 5643): WAIT_FOR_CONCURRENT_GC blocked 42ms
,I/dalvikvm-heap( 5643): Grow heap (frag case) to 14.521MB for 2129936-byte allocation
,D/dalvikvm( 5643): GC_FOR_ALLOC freed 4K, 21% free 13976K/17624K, paused 31ms, total 31ms
,I/iu.UploadsManager( 5643): num updated entries: 0
I/SELinux ( 7300): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7300):  
I/SELinux ( 7300):  
,I/SELinux ( 7300): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7300): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7300): >>>>> Normal User
E/dalvikvm( 7300): >>>>> com.android.email [ userId:0 | appId:10157 ]
,I/dalvikvm( 6205): Total arena pages for JIT: 11
I/dalvikvm( 6205): Total arena pages for JIT: 12
I/dalvikvm( 6205): Total arena pages for JIT: 13
I/dalvikvm( 6205): Total arena pages for JIT: 14
I/dalvikvm( 6205): Total arena pages for JIT: 15
I/dalvikvm( 6205): Total arena pages for JIT: 16
,I/dalvikvm( 6205): Total arena pages for JIT: 17
,E/SELinux ( 7300): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/iu.SyncManager( 5643): NEXT; no task
,D/TimaKeyStoreProvider( 7300): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7300): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7300): Added TimaKesytore provider
,I/System.out( 6205): Thread-563(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables,
,I/System.out( 6205): Thread-563(ApacheHTTPLog):isShipBuild true,
,I/System.out( 6205): Thread-563(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false,
,I/System.out( 7072): Thread-668 calls detatch(),
,D/dalvikvm( 7300): GC_CONCURRENT freed 2986K, 29% free 9588K/13460K, paused 3ms+1ms, total 29ms
,D/dalvikvm( 7300): WAIT_FOR_CONCURRENT_GC blocked 25ms,
,I/System.out( 7072): Thread-650 calls detatch(),
,I/dalvikvm( 6205): Total arena pages for JIT: 18,
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId,
,I/System.out( 7072): Thread-668 calls detatch(),
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability,
,I/System.out( 6205): Thread-563 calls detatch(),
,I/SELinux ( 7322): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7322):  
D/RCPManagerService( 2420): exchangeData() failure , invalid userId
D/RCPManagerService( 2420): exchangeData() failure , invalid userId
D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,I/SELinux ( 7322): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7322):  
I/SELinux ( 7322):  
,I/SELinux ( 7322): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7322): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7322): >>>>> Normal User
,E/dalvikvm( 7322): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7322): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SA      ( 6263): [RC New] [v2liruge] api execute + 2319
,I/SA      ( 6263): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6263): AsyncTask #1 calls detatch()
,I/SA      ( 6263): [TPMU] getNetworkMcc : 
,D/TimaKeyStoreProvider( 7322): in addTimaSignatureService
,I/System.out( 7072): Thread-668 calls detatch()
,D/TimaKeyStoreProvider( 7322): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7322): Added TimaKesytore provider
,I/ActivityManager( 2420): Killing 5892:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,W/ActivityManager( 2420): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SA      ( 6263): [SCU] saveMccToPreferece Start
,I/SA      ( 6263): [SCU] RegionMCC : 260
,I/SA      ( 6263): [SSP] query invoked
,I/SA      ( 6263): [TPMU] GetMccFromDB : null
I/SA      ( 6263): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6263): [SCU] saveMccToPreferece End
,I/SA      ( 6263): [RC New] executeRequest [v2liruge] end. 2390
,I/SA      ( 6263): [RC New] Execute end
I/SA      ( 6263): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6263): [OR] GetMyCountryZoneTask Success
,I/SELinux ( 7338): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7338):  
,I/ActivityManager( 2420): Killing 6073:com.samsung.groupcast/u0a15 (adj 15): empty #43
D/dalvikvm( 7322): GC_CONCURRENT freed 2996K, 29% free 9565K/13452K, paused 2ms+2ms, total 32ms
D/dalvikvm( 7322): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/BadgeProvider( 7322): onCreate
,D/BadgeProvider( 7322): DatabaseHelper
I/SELinux ( 7338): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7338):  
I/SELinux ( 7338):  
,I/SELinux ( 7338): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7338): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7338): >>>>> Normal User
,E/dalvikvm( 7338): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7338): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/BadgeProvider( 7322): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 7338): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7338): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7338): Added TimaKesytore provider
,D/BadgeProvider( 7322): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7322): sendNotify, [notify] : null
D/BadgeProvider( 7322): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7322): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7322): update, [UpdateCount] : 1
,D/Launcher.Model( 2773): reloadBadges entered.
,I/System.out( 7072): Thread-668 calls detatch()
,I/ActivityManager( 2420): Killing 6087:com.android.musicfx/u0a24 (adj 15): empty #43
,D/dalvikvm( 7338): GC_CONCURRENT freed 3000K, 29% free 9565K/13452K, paused 12ms+1ms, total 35ms
,D/dalvikvm( 7338): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/SELinux ( 7352): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7352):  
,I/ActivityManager( 2420): Killing 6115:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 9% free 9502K/10436K, paused 2ms+3ms, total 30ms
I/SELinux ( 7352): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7352):  
I/SELinux ( 7352):  
I/SELinux ( 7352): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7352): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7352): >>>>> Normal User
E/dalvikvm( 7352): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
,E/SELinux ( 7352): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/System.out( 7072): Thread-668 calls detatch(),
,D/TimaKeyStoreProvider( 7352): in addTimaSignatureService,
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 9% free 9502K/10436K, paused 2ms+3ms, total 28ms,
D/NtpTrustedTime( 2420): getCachedNtpTime() cache hit
,D/TimaKeyStoreProvider( 7352): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7352): Added TimaKesytore provider,
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 9% free 9502K/10436K, paused 3ms+3ms, total 27ms
,D/dalvikvm( 3139): GC_FOR_ALLOC freed 1459K, 19% free 11924K/14604K, paused 41ms, total 41ms
,D/dalvikvm( 7352): GC_CONCURRENT freed 2980K, 29% free 9587K/13456K, paused 4ms+3ms, total 25ms
,D/dalvikvm( 7352): WAIT_FOR_CONCURRENT_GC blocked 12ms
,I/System.out( 7072): Thread-668 calls detatch()
,I/dalvikvm( 7352): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 7352): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 7352): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 7352): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
,W/dalvikvm( 7352): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7352): VFY: replacing opcode 0x22 at 0x0000
,E/dalvikvm( 7352): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
,W/dalvikvm( 7352): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 7352): VFY: replacing opcode 0x22 at 0x0037
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6101): mConnectivityHandler : connected
,I/System.out( 7072): Thread-668 calls detatch()
,W/PCWCLIENTTRACE_AccountUtil( 6101): [hasSamungAccount] - No Samsung Account
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,W/dalvikvm( 7352): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7352): Link of class 'Ldqp;' failed
,W/dalvikvm( 7352): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7352): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7352): Link of class 'Ldqp;' failed
I/dalvikvm( 7352): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 7352): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 7352): VFY: replacing opcode 0x6e at 0x0000
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,E/dalvikvm( 7352): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7352): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7352): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 7352): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7352): Link of class 'Ldqp;' failed
W/dalvikvm( 7352): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7352): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7352): Link of class 'Ldqp;' failed
I/dalvikvm( 7352): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 7352): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
,D/dalvikvm( 7352): VFY: replacing opcode 0x6e at 0x0008
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,E/dalvikvm( 7352): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 7352): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
,D/dalvikvm( 7352): VFY: replacing opcode 0x1c at 0x0026
,W/dalvikvm( 7352): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7352): Link of class 'Ldqp;' failed
,W/dalvikvm( 7352): VFY: unable to find class referenced in signature (Ldqp;)
,W/dalvikvm( 7352): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 7352): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7352): Link of class 'Ldqp;' failed
I/dalvikvm( 7352): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 7352): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
,D/dalvikvm( 7352): VFY: replacing opcode 0x6e at 0x0003
E/PCWCLIENTTRACE_SecurePreferencesJNI( 6101): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6101): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6101): GetString : secure API is not supported!!
,I/PCWCLIENTTRACE_PushUtil( 6101): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6101): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6101): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6101): [ensureRegistration] - No Samsung account
W/dalvikvm( 7352): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7352): Link of class 'Lax;' failed
E/dalvikvm( 7352): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 7352): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
,D/dalvikvm( 7352): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 7352): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7352): Link of class 'Laz;' failed
E/dalvikvm( 7352): Could not find class 'az', referenced from method g.a
W/dalvikvm( 7352): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
,D/dalvikvm( 7352): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 7352): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 7352): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7352): VFY: replacing opcode 0x6e at 0x0008
,I/dalvikvm( 7352): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
W/dalvikvm( 7352): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 7352): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 7352): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 7352): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7352): VFY: replacing opcode 0x6e at 0x0006
,I/System.out( 7072): Thread-668 calls detatch()
,I/System.out( 7072): Thread-656 calls detatch()
I/dalvikvm( 7352): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 7352): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
,D/dalvikvm( 7352): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 7352): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 7352): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 7352): VFY: replacing opcode 0x72 at 0x0000
,I/dalvikvm( 7352): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
W/dalvikvm( 7352): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 7352): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7352): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 7352): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 7352): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 7352): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 7352): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 7352): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 7352): VFY: replacing opcode 0x23 at 0x0005
,I/dalvikvm( 7352): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
W/dalvikvm( 7352): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7352): VFY: replacing opcode 0x6e at 0x0009
,W/dalvikvm( 7352): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
W/dalvikvm( 7352): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
,E/dalvikvm( 7352): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 7352): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;,
,D/dalvikvm( 7352): VFY: replacing opcode 0x1c at 0x0002,
,E/dalvikvm( 7352): Could not find class 'android.telecom.TelecomManager', referenced from method g.n,
W/dalvikvm( 7352): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 7352): VFY: replacing opcode 0x1f at 0x000c,
,D/dalvikvm( 7072): GC_CONCURRENT freed 1808K, 19% free 11544K/14240K, paused 3ms+23ms, total 109ms,
,D/dalvikvm( 7352): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS,
W/dalvikvm( 7352): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7352): VFY: replacing opcode 0x62 at 0x0006,
,D/dalvikvm( 7352): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a,
,D/dalvikvm( 7352): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a,
,I/System.out( 7072): Thread-668 calls detatch(),
D/dalvikvm( 7352): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
D/dalvikvm( 7352): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
,D/dalvikvm( 7352): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
,W/dalvikvm( 7352): Unable to resolve superclass of Lax; (841)
,W/dalvikvm( 7352): Link of class 'Lax;' failed
D/dalvikvm( 7352): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
,W/dalvikvm( 7352): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7352): Link of class 'Laz;' failed
,D/dalvikvm( 7352): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 7352): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
,D/dalvikvm( 7352): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,I/ActivityManager( 2420): Killing 6129:com.sec.android.app.shealth/u0a36 (adj 15): empty #43
,D/dalvikvm( 7352): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x4222e9d8
,D/dalvikvm( 7352): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x4222e9d8
,I/System.out( 7072): Thread-668 calls detatch()
,D/dalvikvm( 2837): GC_EXPLICIT freed 1216K, 20% free 11051K/13784K, paused 4ms+7ms, total 58ms
,D/DelayedSyncController( 5975): Delaying sync.
,I/dalvikvm( 7352): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
W/dalvikvm( 7352): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 7352): VFY: replacing opcode 0x6e at 0x0076
,D/PicasaService( 3561): start picasa sync
,D/PicasaService( 3561): end picasa sync
,I/Babel_SMS( 7352): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7352): MmsConfig.loadMmsSettings
I/Babel_SMS( 7352): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/Babel_SMS( 7352): MmsConfig.loadFromDatabase
,I/System.out( 7072): Thread-668 calls detatch()
,E/Babel_SMS( 7352): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7352): MmsConfig.loadFromResources
,E/Babel_SMS( 7352): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7352): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,W/dalvikvm( 7352): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7352): Link of class 'Lfzc;' failed
,E/dalvikvm( 7352): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 7352): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
,D/dalvikvm( 7352): VFY: replacing opcode 0x22 at 0x0033
,W/dalvikvm( 7352): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7352): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7352): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
,W/dalvikvm( 7352): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,I/dalvikvm( 7352): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 7352): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
,D/dalvikvm( 7352): VFY: replacing opcode 0x74 at 0x006d
I/dalvikvm( 7352): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 7352): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
,D/dalvikvm( 7352): VFY: replacing opcode 0x6e at 0x0033
,I/SELinux ( 7396): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7396):  
,D/dalvikvm( 7352): GC_CONCURRENT freed 1776K, 20% free 10882K/13544K, paused 10ms+2ms, total 68ms
,D/dalvikvm( 7352): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 7352): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/dalvikvm( 7352): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
,W/dalvikvm( 7352): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
,D/dalvikvm( 7352): VFY: replacing opcode 0x6e at 0x0030
,W/dalvikvm( 7352): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7352): Link of class 'Lfzc;' failed
,D/dalvikvm( 7352): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
,E/SensorService( 2420): Permission Denial : SEC Private Sensor 
,E/SensorService( 2420): Permission Denial : SEC Private Sensor 
,D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1924): DEBUG:duration time(    1 msec):(HAL_getCameraInfo)
I/SELinux ( 7396): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7396):  
I/SELinux ( 7396):  
,I/SELinux ( 7396): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7396): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7396): >>>>> Normal User
,E/dalvikvm( 7396): >>>>> com.google.android.syncadapters.calendar [ userId:0 | appId:10107 ]
,E/SELinux ( 7396): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/System.out( 7072): Thread-657 calls detatch()
,I/System.out( 7072): Thread-668 calls detatch()
,D/TimaKeyStoreProvider( 7396): in addTimaSignatureService
,W/Settings( 7352): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TimaKeyStoreProvider( 7396): Cannot add TimaSignature Service, License check Failed
,I/Babel_Crash( 7352): startup - clean
,D/ActivityThread( 7396): Added TimaKesytore provider
,I/Babel   ( 7352): deleted: false for 0
,I/dalvikvm( 7352): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
,D/dalvikvm( 7396): GC_CONCURRENT freed 2997K, 29% free 9570K/13456K, paused 3ms+1ms, total 22ms
,D/dalvikvm( 7396): WAIT_FOR_CONCURRENT_GC blocked 18ms
W/dalvikvm( 7352): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7352): VFY: replacing opcode 0x6e at 0x000d
,W/AbstractGoogleClient( 7396): Application name is not set. Call Builder#setApplicationName.
,I/System.out( 7072): Thread-668 calls detatch()
,W/dalvikvm( 7352): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,I/dalvikvm( 7352): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 7352): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
D/dalvikvm( 7352): VFY: replacing opcode 0x6e at 0x004e
,W/dalvikvm( 7352): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7352): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7352): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 7352): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
,D/dalvikvm( 7352): VFY: replacing opcode 0x22 at 0x0071
,W/dalvikvm( 7352): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7352): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,I/SELinux ( 7416): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7416):  
,W/dalvikvm( 7352): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7352): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7352): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 7352): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
D/dalvikvm( 7352): VFY: replacing opcode 0x1f at 0x0021
,W/dalvikvm( 7352): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 7352): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
,I/SELinux ( 7416): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7416):  
I/SELinux ( 7416):  
,I/SELinux ( 7416): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7416): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7416): >>>>> Normal User
,E/dalvikvm( 7416): >>>>> com.android.providers.calendar [ userId:0 | appId:10045 ]
,E/SELinux ( 7416): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/dalvikvm( 7352): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/dalvikvm( 7352): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
,D/dalvikvm( 7352): VFY: replacing opcode 0x6e at 0x0074
,D/TimaKeyStoreProvider( 7416): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7416): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7416): Added TimaKesytore provider
,I/vclib   ( 7352): onServiceConnected
,W/Babel   ( 7352): Attempted to change video mute state without an active call.
,I/System.out( 7072): Thread-668 calls detatch()
,I/Gmail   ( 4894): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 10657, normalSync: true
,D/dalvikvm( 7416): GC_CONCURRENT freed 2994K, 29% free 9565K/13452K, paused 3ms+22ms, total 52ms
,D/dalvikvm( 7416): WAIT_FOR_CONCURRENT_GC blocked 38ms
,I/iu.Environment( 3139): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/System.out( 7072): Thread-668 calls detatch()
,I/SurfaceFlinger( 1920): id=24 Removed Uoast (10/11)
,I/SurfaceFlinger( 1920): id=24 Removed Uoast (-2/11)
,D/PowerManagerService( 2420): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2420) eventTime = 326284
,D/PowerManagerService( 2420): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2420 (0x0)
,D/PowerManagerService( 2420): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2420, ws=WorkSource{1000}) (elapsedTime=3461)
,D/UdcCache:FPQuery( 3139): Bootstrapping UDC settings cache for all accounts
,I/iu.UploadsManager( 3139): num queued entries: 0
,I/CheckinService( 3139): Checkin interval check for package: unspecified last checkin: 1447260279528 min interval config: 0 actual interval: 577872795
,I/iu.UploadsManager( 3139): num updated entries: 0
,I/iu.SyncManager( 3139): NEXT; no task
,D/dalvikvm( 7352): GC_CONCURRENT freed 869K, 13% free 12062K/13816K, paused 7ms+2ms, total 135ms
,D/dalvikvm( 7352): WAIT_FOR_CONCURRENT_GC blocked 58ms
,D/dalvikvm( 7352): WAIT_FOR_CONCURRENT_GC blocked 59ms
,I/System.out( 7072): Thread-668 calls detatch()
,V/GLSActivity( 2837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinService( 3139): Checking schedule, now: 1447838152445 next: 1447818622446
,I/CheckinService( 3139): active receiver: enabled
,I/CheckinService( 3139): Preparing to send checkin request
,I/EventLogService( 3139): Accumulating logs since 1447836476271
,I/System.out( 7072): Thread-668 calls detatch()
,D/WaitQueueForNetworkActivate( 6407): notifyNetworkActivated
,I/System.out( 7352): Thread-650(HTTPLog):isShipBuild true
,I/System.out( 7352): Thread-650(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/ContextImpl( 6407): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager( 2420): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/dalvikvm( 7352): GC_FOR_ALLOC freed 868K, 15% free 12648K/14776K, paused 44ms, total 51ms
,I/System.out( 7072): Thread-668 calls detatch()
,D/dalvikvm( 7352): GC_FOR_ALLOC freed 787K, 17% free 12676K/15160K, paused 128ms, total 129ms
,I/System.out( 7072): Thread-668 calls detatch()
,I/Babel   ( 7352): connection state changed from UNKNOWN to CONNECTED
,D/dalvikvm( 2420): GC_EXPLICIT freed 2289K, 55% free 24466K/53836K, paused 8ms+21ms, total 205ms
,I/System.out( 7072): Thread-668 calls detatch()
,I/GCM     ( 2837): GCM config loaded
,I/System.out( 7072): Thread-668 calls detatch(),
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 360, Delta = 20,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 5021): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5021): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/dalvikvm( 7352): GC_CONCURRENT freed 2146K, 19% free 13710K/16744K, paused 2ms+14ms, total 174ms
D/dalvikvm( 7352): WAIT_FOR_CONCURRENT_GC blocked 137ms
,I/System.out( 4894): Thread-382(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables,
,I/CheckinRequestBuilder( 3139): Checkin reason type: 12 attempt count: 1,
,I/System.out( 7072): Thread-668 calls detatch(),
,I/System.out( 4894): Thread-382(ApacheHTTPLog):isShipBuild true
,I/System.out( 4894): Thread-382(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/SPPClientService( 5408): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
D/hcjo    ( 6407): AutoUpdateManager:IDLE:execute
,E/SPPClientService( 5408): [SystemStateMoniter] Current Time : 327354
,E/SPPClientService( 5408): [SystemStateMoniter] No Connect : false
,I/dalvikvm( 6407): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
,W/dalvikvm( 6407): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 6407): VFY: replacing opcode 0x6e at 0x0024
,D/InitializeManagerStateMachine( 6407): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6407): exit::IDLE
,D/InitializeManagerStateMachine( 6407): entry::NETWORK_CHECK
,I/SELinux ( 7464): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7464):  
D/InitializeManagerStateMachine( 6407): execute::NETWORK_CHECK:NETWORK_STATE_OK
E/ActivityThread( 3139): Failed to find provider info for com.google.android.wearable.settings
,I/SELinux ( 7464): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7464):  
I/SELinux ( 7464):  
,I/SELinux ( 7464): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7464): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7464): >>>>> Normal User
,E/dalvikvm( 7464): >>>>> com.android.calendar [ userId:0 | appId:10144 ]
,E/SELinux ( 7464): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/InitializeManagerStateMachine( 6407): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6407): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 6407): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6407): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6407): entry::SUCCESS
,D/hcjo    ( 6407): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6407): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 6407): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6407): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6407): exit::SUCCESS
,D/InitializeManagerStateMachine( 6407): entry::IDLE
,D/TimaKeyStoreProvider( 7464): in addTimaSignatureService
,I/ActivityManager( 2420): Killing 6147:com.sec.android.service.health/u0a16 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7464): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7464): Added TimaKesytore provider
,D/dalvikvm( 7464): GC_CONCURRENT freed 2998K, 29% free 9572K/13456K, paused 2ms+1ms, total 28ms
,D/dalvikvm( 7464): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/System.out( 7072): Thread-668 calls detatch()
,D/dalvikvm( 7072): GC_CONCURRENT freed 1956K, 20% free 11589K/14428K, paused 8ms+7ms, total 61ms
,D/ConnectivityService( 2420): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
,D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0,
,I/ActivityManager( 2420): Killing 6243:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty #43,
,D/BootCompletedReceiver( 2420): onReceive,
,I/KLMS-2.3.201 : ( 7105): KLMSSystemProperties(): getBoolean(): ro.product_ship = true,
,I/System.out( 7072): Thread-668 calls detatch(),
,I/KLMS-2.3.201 : ( 7105): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1447838153822,
,I/KLMS-2.3.201 : ( 7105): StateImplV2() : dateTimeChanged() : Wed Nov 18 10:15:53 CET 2015,
,I/SELinux ( 7481): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7481):  
,I/SELinux ( 7481): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7481):  
I/SELinux ( 7481):  
I/SELinux ( 7481): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7481): [DEBUG] seapp_context_lookup: seinfoCategory = release,
E/dalvikvm( 7481): >>>>> Normal User
,E/dalvikvm( 7481): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
,E/SELinux ( 7481): [DEBUG] seapp_context_lookup: seinfoCategory = release,
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
,D/TimaKeyStoreProvider( 7481): in addTimaSignatureService,
,I/System.out( 7072): Thread-668 calls detatch(),
,D/TimaKeyStoreProvider( 7481): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7481): Added TimaKesytore provider,
,D/dalvikvm( 7481): GC_CONCURRENT freed 3012K, 29% free 9557K/13460K, paused 2ms+2ms, total 27ms,
,D/dalvikvm( 7481): WAIT_FOR_CONCURRENT_GC blocked 19ms,
,I/dalvikvm( 2837): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 2837): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2837): VFY: replacing opcode 0x6e at 0x0033,
,I/System.out( 7072): Thread-668 calls detatch(),
,I/GAV2    ( 7251): Thread[GAThread,5,main]: No campaign data found.,
,I/System.out( 2837): Thread-59(HTTPLog):isShipBuild true,
,I/System.out( 2837): Thread-59(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false,
,W/ContextImpl( 7481): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 ,
,I/SELinux ( 7504): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7504):  
,E/Device Type Shared Preferences( 7481): Device Type Shared Preferences - getDeviceTypeChecked -true,
E/Device Type Shared Preferences( 7481): Device Type Shared Preferences - not connecting to service
,E/com.sec.android.app.shealth.SHealthApplication( 7481): ContentProvider is not null
,W/ResourceType( 7481): No package identifier when getting value for resource number 0x00000000,
,I/System.out( 7481): resource Id::2131361807
I/SELinux ( 7504): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7504):  
I/SELinux ( 7504):  
I/SELinux ( 7504): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7504): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7504): >>>>> Normal User
,E/dalvikvm( 7504): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ],
,E/SELinux ( 7504): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7504): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7504): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7504): Added TimaKesytore provider
,I/System.out( 7072): Thread-668 calls detatch()
,D/dalvikvm( 7504): GC_CONCURRENT freed 3006K, 29% free 9561K/13456K, paused 2ms+6ms, total 30ms
,D/dalvikvm( 7504): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/com.sec.android.app.shealth.SHealthApplication( 7481): Success during batch insertion in App registry:0
,I/System.out( 7072): Thread-668 calls detatch()
,D/dalvikvm( 2837): GC_CONCURRENT freed 1846K, 21% free 11167K/13972K, paused 2ms+6ms, total 37ms
,D/dalvikvm( 4894): GC_CONCURRENT freed 2184K, 23% free 10371K/13456K, paused 3ms+5ms, total 48ms
,I/System.out( 7072): Thread-668 calls detatch()
,V/MediaPlayer( 7481): decode(56, 30565892, 48105)
,V/MediaPlayerService( 1924): decode(26, 30565892, 48105)
,V/MediaPlayerService( 1924): player type = 3
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
V/StagefrightPlayer( 1924): setDataSource(26, 30565892, 48105)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 8, 0, 0)
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
V/AudioCache( 1924): notify(0x442b3068, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 1, 0, 0)
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
V/AudioCache( 1924): notify(0x442b3068, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,I/System.out( 7072): Thread-668 calls detatch()
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 8, 0, 0)
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
,V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 7481): decode(58, 30501792, 10421)
,V/MediaPlayerService( 1924): decode(26, 30501792, 10421)
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
V/StagefrightPlayer( 1924): setDataSource(26, 30501792, 10421)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f3bc0, 8, 0, 0)
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
V/AudioCache( 1924): notify(0x444f3bc0, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f3bc0, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f3bc0, 1, 0, 0)
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
V/AudioCache( 1924): notify(0x444f3bc0, 6, 0, 0)
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
V/AudioCache( 1924): notify(0x444f3bc0, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f3bc0, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f3bc0, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x45, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
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
V/MediaPlayer( 7481): decode(59, 34044116, 34198)
,V/MediaPlayerService( 1924): decode(26, 34044116, 34198)
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
V/StagefrightPlayer( 1924): setDataSource(26, 34044116, 34198)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f3818, 8, 0, 0)
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
V/AudioCache( 1924): notify(0x444f3818, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f3818, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f3818, 1, 0, 0)
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
V/AudioCache( 1924): notify(0x444f3818, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,I/AudioPlayer( 1924): First fillBuffer call!!
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f3818, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f3818, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f3818, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x46, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/System.out( 7072): Thread-668 calls detatch()
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
,V/MediaPlayer( 7481): decode(60, 30449260, 7405)
,V/MediaPlayerService( 1924): decode(26, 30449260, 7405)
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
V/StagefrightPlayer( 1924): setDataSource(26, 30449260, 7405)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f84e8, 8, 0, 0)
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
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x444f84e8, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f84e8, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f84e8, 1, 0, 0)
,V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f84e8, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
,V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f84e8, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f84e8, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
,V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f84e8, 8, 0, 0)
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
V/MediaPlayer( 7481): decode(61, 34134748, 5555)
,V/MediaPlayerService( 1924): decode(26, 34134748, 5555)
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
V/StagefrightPlayer( 1924): setDataSource(26, 34134748, 5555)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444ef0b8, 8, 0, 0)
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
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x444ef0b8, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444ef0b8, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444ef0b8, 1, 0, 0)
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
V/AudioCache( 1924): notify(0x444ef0b8, 6, 0, 0)
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
V/AudioCache( 1924): notify(0x444ef0b8, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444ef0b8, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
,V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444ef0b8, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x48, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
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
,V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 7481): decode(62, 26954540, 5085)
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
V/AudioCache( 1924): notify(0x444f3dd8, 8, 0, 0)
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
V/AudioCache( 1924): notify(0x444f3dd8, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f3dd8, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f3dd8, 1, 0, 0)
,V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f3dd8, 6, 0, 0)
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
V/AudioCache( 1924): notify(0x444f3dd8, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f3dd8, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f3dd8, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x49, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
,V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
,V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 7481): decode(63, 26959684, 21552)
,V/MediaPlayerService( 1924): decode(26, 26959684, 21552)
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
V/StagefrightPlayer( 1924): setDataSource(26, 26959684, 21552)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b2aa0, 8, 0, 0)
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
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b2aa0, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b2aa0, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b2aa0, 1, 0, 0)
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
V/AudioCache( 1924): notify(0x442b2aa0, 6, 0, 0)
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
V/AudioCache( 1924): notify(0x442b2aa0, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b2aa0, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b2aa0, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
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
,V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
,V/MediaPlayer( 7481): decode(64, 34130460, 4230)
,V/MediaPlayerService( 1924): decode(26, 34130460, 4230)
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
V/StagefrightPlayer( 1924): setDataSource(26, 34130460, 4230)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 8, 0, 0)
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
V/AudioCache( 1924): notify(0x442b3068, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/System.out( 7072): Thread-668 calls detatch()
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 1924): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 6, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): addBatteryData
V/MediaPlayerService( 1924): wait for playback complete
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
,V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 7, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 8, 0, 0)
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
,V/MediaPlayer( 7481): decode(65, 26923896, 9400)
,V/MediaPlayerService( 1924): decode(26, 26923896, 9400)
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
V/StagefrightPlayer( 1924): setDataSource(26, 26923896, 9400)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 8, 0, 0)
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
,I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 1, 0, 0)
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
V/AudioCache( 1924): notify(0x442b3068, 6, 0, 0)
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
V/AudioCache( 1924): notify(0x442b3068, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
,V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 8, 0, 0)
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
V/MediaPlayer( 7481): decode(66, 30512272, 44276)
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
V/AudioCache( 1924): notify(0x444f84a8, 8, 0, 0)
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
,I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache( 1924): notify(0x444f84a8, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f84a8, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f84a8, 1, 0, 0)
,V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f84a8, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
,V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f84a8, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
,V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f84a8, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
,V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f84a8, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x4d, OMX_CommandStateSet, OMX_StateIdle)
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
,V/MediaPlayer( 7481): decode(67, 30472480, 29256)
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
V/AudioCache( 1924): notify(0x444f3dd8, 8, 0, 0)
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
,I/ActivityManager( 2420): Waited long enough for: ServiceRecord{44c6a2d0 u0 pl.k2.droidoaudioteka/.services.DownloadService}
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x444f3dd8, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f3dd8, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f3dd8, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f3dd8, 6, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
D/dalvikvm( 7504): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42227848, skipping init
,I/ActivityManager( 2420): Waited long enough for: ServiceRecord{44c6a168 u0 pl.k2.droidoaudioteka/.services.PlayerService}
I/SecureStorage( 7504): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 7504): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage( 1964): [INFO]: SPID(0x00000005)Credentials: uid 10016, gid 10016, pid 7504
I/SecureStorage( 1964): [INFO]: SPID(0x00000005)Received function mask & code: 0000010C
I/SecureStorage( 7504): [INFO]: SPID(0x00000000)SS Daemon is running
,I/SecureStorage( 7504): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 1964): [INFO]: SPID(0x00000005)Credentials: uid 10016, gid 10016, pid 7504
,I/SecureStorage( 1964): [INFO]: SPID(0x00000005)Received function mask & code: 00000106
,I/SELinux ( 7584): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7584):  
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
,V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f3dd8, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f3dd8, 7, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f3dd8, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x4e, OMX_CommandStateSet, OMX_StateIdle)
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
,V/MediaPlayer( 7481): decode(68, 34078380, 52024)
,V/MediaPlayerService( 1924): decode(26, 34078380, 52024)
,D/AmoledAdjustTimer( 2420): prevTemp = 293, currTemp = 295, prevStep = 4, currStep = 4
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
V/StagefrightPlayer( 1924): setDataSource(26, 34078380, 52024)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
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
I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1924): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
V/MediaPlayerService( 1924): wait for playback complete
,I/SELinux ( 7584): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7584):  
I/SELinux ( 7584):  
I/SELinux ( 7584): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7584): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7584): >>>>> Normal User
I/System.out( 7072): Thread-668 calls detatch()
E/dalvikvm( 7584): >>>>> com.google.android.gms.unstable [ userId:0 | appId:10012 ]
E/SELinux ( 7584): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/dalvikvm( 4894): GC_CONCURRENT freed 2115K, 25% free 10223K/13456K, paused 4ms+2ms, total 71ms
,D/TimaKeyStoreProvider( 7584): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7584): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7584): Added TimaKesytore provider
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 7, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x4f, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 7481): decode(69, 30556608, 9226)
,V/MediaPlayerService( 1924): decode(26, 30556608, 9226)
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
V/StagefrightPlayer( 1924): setDataSource(26, 30556608, 9226)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 8, 0, 0)
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
V/AudioCache( 1924): notify(0x442b3068, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 1, 0, 0)
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
V/AudioCache( 1924): notify(0x442b3068, 6, 0, 0)
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
V/AudioCache( 1924): notify(0x442b3068, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 7, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
,V/StagefrightPlayer( 1924): reset
,V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3068, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x50, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 7481): decode(70, 26989388, 4509)
,V/MediaPlayerService( 1924): decode(26, 26989388, 4509)
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
V/StagefrightPlayer( 1924): setDataSource(26, 26989388, 4509)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b0a18, 8, 0, 0)
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
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b0a18, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b0a18, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b0a18, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b0a18, 6, 0, 0)
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
V/AudioCache( 1924): notify(0x442b0a18, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b0a18, 7, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b0a18, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x51, OMX_CommandStateSet, OMX_StateIdle)
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
,D/dalvikvm( 7584): GC_CONCURRENT freed 3009K, 29% free 9560K/13460K, paused 3ms+1ms, total 39ms
,D/dalvikvm( 7584): WAIT_FOR_CONCURRENT_GC blocked 36ms
,W/dalvikvm( 7584): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7584): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 7584): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 7584): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 7584): VFY: replacing opcode 0x6e at 0x00ca
,I/MultiDex( 7584): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7584): install
,I/MultiDex( 7584): MultiDexExtractor.load(/data/app/com.google.android.gms-4.apk, false)
,I/MultiDex( 7584): loading existing secondary dex files
,I/MultiDex( 7584): load found 3 secondary dex files
,I/MultiDex( 7584): install done
,D/dalvikvm( 7584): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 7584): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7584): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 7584): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7584): VFY: unable to resolve instance field 46
,D/dalvikvm( 7584): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 7584): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7584): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7584): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 7584): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 7584): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 7584): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x422288d0
,D/dalvikvm( 7584): Added shared lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x422288d0
,D/dalvikvm( 7584): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-4/libgmscore.so 0x422288d0, skipping init
,D/dalvikvm( 7584): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x422288d0
,D/dalvikvm( 7584): Added shared lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x422288d0
,V/JNIHelp ( 7584): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/CaptivePortalTracker( 2420): DelayedCaptiveCheckState{ when=-28ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 2420): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2420): Checking http://216.58.209.46/generate_204
W/ActivityThread( 2420): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/dalvikvm( 7584): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x422288d0
,D/dalvikvm( 7584): Shared lib '/data/app-lib/com.google.android.gms-4/libgmscore.so' already loaded in same CL 0x422288d0
D/dalvikvm( 7584): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x422288d0
,D/dalvikvm( 7584): Shared lib '/data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so' already loaded in same CL 0x422288d0
,I/System.out( 2420): Thread-161(HTTPLog):isShipBuild true
,I/System.out( 7072): Thread-668 calls detatch()
,I/System.out( 2420): Thread-161(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/CaptivePortalTracker( 2420): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 2420): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2420): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2420): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2420): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/ProviderInstaller( 7584): Installed default security provider GmsCore_OpenSSL
,I/dalvikvm( 7584): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
,W/dalvikvm( 7584): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7584): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 7584): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 7584): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 7584): VFY: replacing opcode 0x6e at 0x0220
,I/dalvikvm( 7584): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 7584): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,E/dalvikvm( 7584): Could not find class 'com.google.android.gms.common.h.c', referenced from method com.google.android.gms.common.h.b.a
,W/dalvikvm( 7584): VFY: unable to resolve new-instance 2668 (Lcom/google/android/gms/common/h/c;) in Lcom/google/android/gms/common/h/b;
,D/dalvikvm( 7584): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 7584): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.h.b.b
W/dalvikvm( 7584): VFY: unable to resolve virtual method 328: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 7584): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 7584): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 7584): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,D/dalvikvm( 7584): DexOpt: unable to opt direct call 0x2d44 at 0x02 in Lcom/google/android/gms/common/h/b;.a
,I/System.out( 7072): Thread-668 calls detatch()
I/System.out( 7396): Thread-642(HTTPLog):isShipBuild true
,I/System.out( 7396): Thread-642(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/GetConfigurationSnapshotOperation( 2837): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,E/Parcel  ( 1924): nm 16
,D/WVCdm   ( 1924): Instantiating CDM.
,I/WVCdm   ( 1924): Level3 Library Nov 20 2013 18:09:31
,I/dalvikvm( 7584): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
,W/dalvikvm( 7584): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 7584): VFY: replacing opcode 0x6e at 0x0033
,W/dalvikvm( 7584): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 7584): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 7584): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 7584): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 7584): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 7584): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 7584): Using platform SSLCertificateSocketFactory
,I/System.out( 7584): Thread-656(HTTPLog):isShipBuild true
,I/System.out( 7584): Thread-656(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 7072): Thread-668 calls detatch()
,I/PhenotypeFlagCommitter( 2837): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,E/wv_dash ( 1924): chunk TEE virt: 0x200c18
,I/SecureStorage( 1964): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 1964): [INFO]: SPID(0x00000005)PID: 7504, TID: 7520
,D/WVCdm   ( 1924): OEMCrypto_Initialize Level 1 success. I will use level 1.
,I/WVCdm   ( 1924): CdmEngine::OpenSession
,I/WVCdm   ( 1924): CdmEngine::QueryKeyControlInfo
,E/Parcel  ( 7584): nm 16
,D/dalvikvm( 7584): GC_CONCURRENT freed 1754K, 20% free 10876K/13516K, paused 11ms+16ms, total 125ms
,D/dalvikvm( 7584): WAIT_FOR_CONCURRENT_GC blocked 55ms
,D/dalvikvm( 7584): WAIT_FOR_CONCURRENT_GC blocked 25ms
,E/Parcel  ( 1924): nm 16
,E/Parcel  ( 1924): nm 1
,I/WVCdm   ( 1924): CdmEngine::GenerateKeyRequest
,D/WVCdm   ( 1924): PrepareKeyRequest: nonce=3397328083
,I/GoogleURLConnFactory( 2837): Using platform SSLCertificateSocketFactory
,I/SecureStorage( 7504): [INFO]: SPID(0x00000000)Processing data has been completed
I/SecureStorage( 7504): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 7504): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 7504): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 7504): Open platform.db in secure mode
,D/NativeLibraryUtils( 7584): Install completed successfully. count=13 extracted=0
,E/Parcel  ( 7584): nm 1834
,E/Parcel  ( 1924): nm 16
,I/WVCdm   ( 1924): CdmEngine::CloseSession
,I/SQLiteSecureOpenHelper( 7504): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 7504): ...getDatabaseLocked(b,b,pwd)
,E/SPPClientService( 5408): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,V/AlarmManager( 2420):  next == MAX_VALUE
,E/SPPClientService( 5408): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,D/SO_AGENT( 7128): [ServerTimeReceiver.java(Line:44/Method:onReceive)] Receive broadcast meassage:android.intent.action.TIME_SET
,I/SO_AGENT( 7128): [ServerTimeReceiver.java(Line:47/Method:onReceive)] No action is available before server time settings
,I/SA      ( 6263): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,E/SPPClientService( 5408): [a] [ConnectionManager] Connection is already disconnected.
V/AlarmManager( 2420): waitForAlarm result :4
V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Mms/MessagingNotification( 5506): [start]    nonBlockingUpdateMessageIndicator()
,D/Mms/MessagingNotification( 5506): sDisableVibrateForCamera = false
,D/Mms/MessagingNotification( 5506): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 5506): isDefault true
,D/TP/MmsSmsProvider( 2753): match 8:Elapsed time : 9.214 ms
,D/dalvikvm( 7584): GC_CONCURRENT freed 1422K, 17% free 11500K/13812K, paused 12ms+22ms, total 92ms
,D/dalvikvm( 7584): WAIT_FOR_CONCURRENT_GC blocked 51ms
,I/SELinux ( 7638): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7638):  
I/ActivityManager( 2420): Killing 4745:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
,D/TP/MmsSmsProvider( 2753): match 200:Elapsed time : 2.718 ms
,I/SELinux ( 7638): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7638):  
I/SELinux ( 7638):  
,I/SELinux ( 7638): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7638): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7638): >>>>> Normal User
,E/dalvikvm( 7638): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10064 ]
,E/SELinux ( 7638): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7638): in addTimaSignatureService
,D/dalvikvm( 7584): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42335628
,D/TimaKeyStoreProvider( 7638): Cannot add TimaSignature Service, License check Failed
D/dalvikvm( 7584): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42335628
D/dalvikvm( 7584): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42335628, skipping init
,D/ActivityThread( 7638): Added TimaKesytore provider
,D/GetCommittedConfigurationOperation( 2837): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/BadgeProvider( 7322): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/BadgeProvider( 7322): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 7322): sendNotify, [notify] : null
D/BadgeProvider( 7322): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 7322): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7322): update, [UpdateCount] : 1
,D/Launcher.Model( 2773): reloadBadges entered.
,D/dalvikvm( 7638): GC_CONCURRENT freed 2996K, 29% free 9573K/13460K, paused 16ms+2ms, total 57ms
D/dalvikvm( 7638): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/System.out( 4894): SyncAdapterThread-1 calls detatch()
,D/Mms/MessagingNotification( 5506): setBadgeCount(), count=0
,D/MessagingNotification( 5506): remove alarm
,D/Mms/MessagingNotification( 5506): updateAllHistoryAsRead()
,D/Mms/MessagingNotification( 5506): [end]    nonBlockingUpdateMessageIndicator()
,D/com.samsung.app( 7187): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidintentactionTIME_SET
,D/com.samsung.app( 7187): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/ Time Manager ( 7638): Time Difference not stored. TIME_DIFFERENCE
,I/SELinux ( 7655): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7655):  
,I/ActivityManager( 2420): Killing 6283:com.sec.android.service.cm/u0a82 (adj 15): empty #43
I/SELinux ( 7655): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7655):  
I/SELinux ( 7655):  
I/SELinux ( 7655): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7655): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7655): >>>>> Normal User
E/dalvikvm( 7655): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10088 ]
E/SELinux ( 7655): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7655): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7655): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7655): Added TimaKesytore provider
,D/WVMDrmPlugIn( 1923): WVMDrmPlugin::onInitialize : 873
D/WVMDrmPlugIn( 1923): WVMDrmPlugin::onSetOnInfoListener : add 873
I/PrGenericPlugin( 1923): [A] ENTER onInitialize : 0x369
,I/PrGenericPlugin( 1923): [A] LEAVE onInitialize : 0x369
,D/WVMDrmPlugIn( 1923): WVMDrmPlugin::onGetSupportInfo : 0
,I/PrGenericPlugin( 1923): [A] ENTER onGetSupportInfo : 0
,I/PrGenericPlugin( 1923): [A] LEAVE onGetSupportInfo : 0
,E/Parcel  ( 1924): nm 16
,I/WVCdm   ( 1924): CdmEngine::OpenSession
,D/dalvikvm( 4894): GC_EXPLICIT freed 1437K, 25% free 10179K/13456K, paused 18ms+6ms, total 167ms
,I/WVCdm   ( 1924): CdmEngine::QueryKeyControlInfo
,E/Parcel  ( 7584): nm 16
E/Parcel  ( 1924): nm 16
,E/Parcel  ( 1924): nm 16
E/Parcel  ( 1924): nm 16
E/Parcel  ( 1924): nm 1
,I/WVCdm   ( 1924): CdmEngine::GenerateKeyRequest
,D/WVCdm   ( 1924): PrepareKeyRequest: nonce=3636565014
,I/Gmail   ( 4894): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 10723, normalSync: true
,D/dalvikvm( 7655): GC_CONCURRENT freed 2993K, 29% free 9575K/13460K, paused 4ms+1ms, total 28ms
,D/dalvikvm( 7655): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/Gmail   ( 4894): lowestBackward conversation id 0
,E/Parcel  ( 7584): nm 1869
E/Parcel  ( 1924): nm 16
,I/WVCdm   ( 1924): CdmEngine::CloseSession
,W/Settings( 7584): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 2420): GC_EXPLICIT freed 1492K, 55% free 24638K/53836K, paused 7ms+20ms, total 194ms
,D/dalvikvm( 3139): GC_CONCURRENT freed 1752K, 18% free 12099K/14740K, paused 6ms+11ms, total 65ms
,D/CalendarSyncAdapter( 7396): Found 0 events marked dirty & lastSynced,
,I/SELinux ( 7672): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7672):  
,I/ActivityManager( 2420): Killing 6295:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty #43,
,I/SELinux ( 7672): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7672):  
I/SELinux ( 7672):  
I/SELinux ( 7672): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7672): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7672): >>>>> Normal User
E/dalvikvm( 7672): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 7672): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7672): in addTimaSignatureService
I/ActivityManager( 2420): Killing 6321:com.samsung.helphub/1000 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7672): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7672): Added TimaKesytore provider
,I/ActivityManager( 2420): Killing 6334:com.sec.kidsplat.installer/u0a160 (adj 15): empty #43
,D/dalvikvm( 7672): GC_CONCURRENT freed 3004K, 29% free 9568K/13460K, paused 3ms+2ms, total 66ms
,D/dalvikvm( 7672): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 7584): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/elm:14132( 7672): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14132( 7672): ELMEngine.ELMEngine( context ).
,D/elm:14132( 7672): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 7672): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.,
,I/knox    ( 4935): MainReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver },
,D/elm:14132( 7672): ElmAgentService : onCreate()
,W/ContextImpl( 4935): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/elm:14132( 7672): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
D/knox    ( 4935): MainReceiver.listeningToTimeDateChanges( context, intent ).
I/knox    ( 4935): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,D/knox    ( 4935): KNOXAgentService : onCreate()
,D/knox    ( 4935): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 4935): KNOXAgentService. startJobThread() start
,D/knox    ( 4935): KNOXAgentService. JobThread()
,D/knox    ( 4935): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 4935): KNOXAgentService. startJobThread() wait
,D/elm:14132( 7672): ELMAgentService.listeningToTimeDateChanges( context, intent ).
D/elm:14132( 7672): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14132( 7672): ModuleBase.resetCalllogAPIAlarm()
,I/SELinux ( 7691): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7691):  
,D/knox    ( 4935): KNOXAgentService : onDestroy().
,D/knox    ( 4935): ModuleBase.cancelAllAlarmManageModule()
D/elm:14132( 7672): ModuleBase.ModifySetAlarm()
D/elm:14132( 7672): MDMBridge.getInstance()
,D/elm:14132( 7672): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 7672): ElmAgentService : onDestroy().
I/ActivityManager( 2420): Killing 6346:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty #43
,D/dalvikvm( 7685): DexOpt: load 6ms, verify+opt 15ms, 123556 bytes
,I/SELinux ( 7691): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7691):  
I/SELinux ( 7691):  
,I/SELinux ( 7691): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7691): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7691): >>>>> Normal User
,E/dalvikvm( 7691): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10145 ]
,E/SELinux ( 7691): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/dalvikvm( 7584): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 7584): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 129ms
,D/libEGL  ( 7584): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7584): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7584): loaded /system/lib/egl/libGLESv2_mali.so
,I/PeopleSync( 3139): onPerformSync() [5005f081]
,D/TimaKeyStoreProvider( 7691): in addTimaSignatureService
,I/Mali    ( 7584): Mali API Version : 401
,I/Mali    ( 7584): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/TimaKeyStoreProvider( 7691): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7691): Added TimaKesytore provider
,I/Mali    ( 7584): Mali API Version : 401
,I/Mali    ( 7584): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/dalvikvm( 7691): GC_CONCURRENT freed 3001K, 29% free 9566K/13460K, paused 4ms+5ms, total 28ms
,D/dalvikvm( 7691): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/SELinux ( 7711): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7711):  
I/ActivityManager( 2420): Killing 6358:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty #43
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 9% free 9502K/10436K, paused 2ms+4ms, total 33ms
I/SELinux ( 7711): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7711):  
I/SELinux ( 7711):  
,I/SELinux ( 7711): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7711): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7711): >>>>> Normal User
,E/dalvikvm( 7711): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10168 ]
,E/SELinux ( 7711): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 9% free 9502K/10436K, paused 2ms+3ms, total 27ms
,D/TimaKeyStoreProvider( 7711): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7711): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7711): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 9% free 9502K/10436K, paused 2ms+3ms, total 29ms
,D/dalvikvm( 2837): GC_CONCURRENT freed 1703K, 19% free 11428K/14084K, paused 7ms+15ms, total 81ms
,I/Mali    ( 7584): Mali API Version : 401
,I/Mali    ( 7584): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/dalvikvm( 7711): GC_CONCURRENT freed 3004K, 29% free 9566K/13460K, paused 1ms+2ms, total 20ms
,D/dalvikvm( 7711): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/System.out( 2837): Thread-141(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 2837): Thread-141(ApacheHTTPLog):isShipBuild true
,I/System.out( 2837): Thread-141(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/PeopleDatabaseHelper( 3139): cleanUpNonGplusAccounts done.
I/ActivityManager( 2420): Killing 6372:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty #43
,D/daemonapp( 5219): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5219): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5219): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5219): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5219): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 5219): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5219): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5219): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5219): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5219): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5219): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5219): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5219): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5219): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5219): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5219): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/GetCommittedConfigurationOperation( 2837): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/comdaemonstockapp( 5219): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 5219): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,I/CheckinService( 3139): Checkin interval check for package: unspecified last checkin: 1447260279528 min interval config: 0 actual interval: 577879784
,I/CheckinRequestBuilder( 3139): Classify the device as Phone.
,I/PeopleSync( 3139): Setting subscription: result=true [5005f081]
,D/Headlines( 7221): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7221): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7221): Breath 10794 latestRequest time : 1447838148712 current time : 1447838159506
,I/PeopleSync( 3139): Starting sync, feed=null [5005f081]
,I/System.out( 2837): GDataFeedFetcher calls detatch()
,D/Mms/Contact( 5506): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/Contact( 5506): performUpdate:widgetCount=0
D/QuickConnect[1.1][2] ( 4995): PreDiscoveryHelper.mContentObserver - Contact Data changed
,V/QuickConnect[1.1][2] ( 4995): CONTACT_Info.getMyMobileNumber - 
,D/ContactProvider( 3561): getAllContactInfoList Start
,D/QuickConnect[1.1][2] ( 4995): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 4995): CONTACT_Info.getMyMobileNumber - null 
,D/ContactProvider( 3561): getAllContactInfoList End
,I/syncContacts( 3561): thread: 164, onChange
,W/BaseAppContext( 3139): Using Auth Proxy for data requests.
,D/GetCommittedConfigurationOperation( 2837): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/BaseAppContext( 3139): Using Auth Proxy for data requests.
,I/System.out( 2837): GDataFeedFetcher calls detatch()
,W/BaseAppContext( 3139): Using Auth Proxy for data requests.
,D/QuickConnect[1.1][2] ( 4995): PreDiscoveryHelper.mContentObserver - Contact Data changed
D/Mms/Contact( 5506): sContactsObserver.onChange(),selfUpdate=false
,V/QuickConnect[1.1][2] ( 4995): CONTACT_Info.getMyMobileNumber - 
,I/PeopleSync( 3139): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,D/QuickConnect[1.1][2] ( 4995): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 4995): CONTACT_Info.getMyMobileNumber - null 
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/ContactProvider( 3561): getAllContactInfoList Start
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2420): waitForAlarm result :8
,D/WearableService( 2734): callingUid 10012, callindPid: 2734
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
D/dalvikvm( 2582): GC_CONCURRENT freed 15635K, 33% free 33938K/50456K, paused 8ms+8ms, total 76ms
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,W/Uploader( 2837):  no longer exists, so no auth token.
,E/MDM     ( 2734): [83] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/GetCommittedConfigurationOperation( 2837): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/LocationInitializer( 3139): Restart initialization of location
,D/ContactProvider( 3561): getAllContactInfoList End
,I/syncContacts( 3561): thread: 165, onChange
,D/GCM     ( 2837): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/dalvikvm( 2420): GC_EXPLICIT freed 1810K, 55% free 24656K/53836K, paused 10ms+16ms, total 189ms
D/AuthorizationBluetoothService( 2837): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 2837): Proximity feature is not enabled.
V/GLSActivity( 2837): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 2734): No location to return for getLastLocation()
W/FusedLocationProvider( 2837): location=null
V/GmsCoreStatsServiceLauncher( 3139): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/dalvikvm( 2837): GC_CONCURRENT freed 1769K, 19% free 11685K/14416K, paused 8ms+5ms, total 90ms
D/dalvikvm( 2837): WAIT_FOR_CONCURRENT_GC blocked 29ms
D/GetCommittedConfigurationOperation( 2837): no corresponding serverToken: com.google.android.gms.playlog.uploader
D/GetCommittedConfigurationOperation( 2837): no corresponding serverToken: com.google.android.gms.playlog.uploader
W/BaseAppContext( 3139): Using Auth Proxy for data requests.
W/BaseAppContext( 3139): Using Auth Proxy for data requests.
W/BaseAppContext( 3139): Using Auth Proxy for data requests.
W/BaseAppContext( 3139): Using Auth Proxy for data requests.
W/BaseAppContext( 3139): Using Auth Proxy for data requests.
W/BaseAppContext( 3139): Using Auth Proxy for data requests.
W/BaseAppContext( 3139): Using Auth Proxy for data requests.
E/SPPClientService( 5408): [g] getNetMCC return empty string
E/SPPClientService( 5408): [g] getNetMNC return empty string
D/Mms/MessagesLockscreen( 5506): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
W/Binder  ( 2582): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 2582): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
W/Binder  ( 2582): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
W/Binder  ( 2582): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
W/Binder  ( 2582): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
W/Binder  ( 2582): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
W/Binder  ( 2582): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
W/Binder  ( 2582): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
W/Binder  ( 2582): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
W/Binder  ( 2582): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
W/Binder  ( 2582): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
W/Binder  ( 2582): 	at android.view.View.inflate(View.java:18495)
W/Binder  ( 2582): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
W/Binder  ( 2582): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
W/Binder  ( 2582): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
W/Binder  ( 2582): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
W/Binder  ( 2582): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
W/Binder  ( 2582): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 2582): 	at dalvik.system.NativeStart.run(Native Method)
W/Binder  ( 2582): Caused by: java.lang.reflect.InvocationTargetException
W/Binder  ( 2582): 	at java.lang.reflect.Constructor.constructNative(Native Method)
W/Binder  ( 2582): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
W/Binder  ( 2582): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
W/Binder  ( 2582): 	... 16 more
W/Binder  ( 2582): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
W/Binder  ( 2582): 	at android.os.Handler.<init>(Handler.java:200)
W/Binder  ( 2582): 	at android.os.Handler.<init>(Handler.java:114)
W/Binder  ( 2582): 	at android.widget.TextClock.<init>(TextClock.java:130)
W/Binder  ( 2582): 	at android.widget.TextClock.<init>(TextClock.java:191)
W/Binder  ( 2582): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
W/Binder  ( 2582): 	... 19 more
E/JavaBinder( 2582): *** Uncaught remote exception!  (Exceptions are not yet supported across processes.)
E/JavaBinder( 2582): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
E/JavaBinder( 2582): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
E/JavaBinder( 2582): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
E/JavaBinder( 2582): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
E/JavaBinder( 2582): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
E/JavaBinder( 2582): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
E/JavaBinder( 2582): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
E/JavaBinder( 2582): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
E/JavaBinder( 2582): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
E/JavaBinder( 2582): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
E/JavaBinder( 2582): 	at android.view.View.inflate(View.java:18495)
E/JavaBinder( 2582): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
E/JavaBinder( 2582): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
E/JavaBinder( 2582): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
E/JavaBinder( 2582): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
E/JavaBinder( 2582): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
E/JavaBinder( 2582): 	at android.os.Binder.execTransact(Binder.java:404)
E/JavaBinder( 2582): 	at dalvik.system.NativeStart.run(Native Method)
E/JavaBinder( 2582): Caused by: java.lang.reflect.InvocationTargetException
E/JavaBinder( 2582): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/JavaBinder( 2582): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/JavaBinder( 2582): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
E/JavaBinder( 2582): 	... 16 more
E/JavaBinder( 2582): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
E/JavaBinder( 2582): 	at android.os.Handler.<init>(Handler.java:200)
E/JavaBinder( 2582): 	at android.os.Handler.<init>(Handler.java:114)
E/JavaBinder( 2582): 	at android.widget.TextClock.<init>(TextClock.java:130)
E/JavaBinder( 2582): 	at android.widget.TextClock.<init>(TextClock.java:191)
E/JavaBinder( 2582): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
E/JavaBinder( 2582): 	... 19 more
D/GetCommittedConfigurationOperation( 2837): no corresponding serverToken: com.google.android.gms.playlog.uploader
D/dalvikvm( 3139): GC_FOR_ALLOC freed 1743K, 19% free 12234K/15024K, paused 43ms, total 45ms
I/CheckinTask( 3139): Sending checkin request (11776 bytes)
I/SELinux ( 7760): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7760):  
I/SELinux ( 7760): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7760):  
I/SELinux ( 7760):  
I/SELinux ( 7760): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7760): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7760): >>>>> Normal User
E/dalvikvm( 7760): >>>>> com.google.android.music:main [ userId:0 | appId:10125 ]
E/SELinux ( 7760): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/GetCommittedConfigurationOperation( 2837): no corresponding serverToken: com.google.android.gms.playlog.uploader
D/TimaKeyStoreProvider( 7760): in addTimaSignatureService
D/TimaKeyStoreProvider( 7760): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7760): Added TimaKesytore provider
D/dalvikvm( 7760): GC_CONCURRENT freed 2990K, 29% free 9573K/13452K, paused 3ms+1ms, total 28ms
D/dalvikvm( 7760): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/MusicStore( 7760): Database version: 85
,W/ContextImpl( 7760): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 7760): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7760): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
I/CheckinResponseProcessor( 3139): From server: 10 gservices updates and 0 deletes
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7760): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7760): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,D/WifiDisplayAdapter( 2420): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 2420): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/AudioService( 2420): getStreamVolume 3 index 70
I/MediaRouter( 7760): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/Mms/Contact( 5506): performUpdate:widgetCount=0
,D/WifiDisplayAdapter( 2420): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/CastUtils( 7760): Removing provider: MediaRouter.RouteProviderInfo{ packageName=com.google.android.gms }
,I/CertBlacklister( 2420): Certificate blacklist changed, updating...
,I/System.out( 3843): Thread-212(HTTPLog):isShipBuild true
,I/System.out( 3843): Thread-212(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/CertBlacklister( 2420): Certificate blacklist updated
,I/GservicesProvider( 2837): main difference update completed
,I/SELinux ( 7795): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7795):  
,I/CheckinRequestBuilder( 3139): Checkin reason type: 12 attempt count: 1
,I/SELinux ( 7795): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7795):  
I/SELinux ( 7795):  
,I/SELinux ( 7795): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7795): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7795): >>>>> Normal User
,E/dalvikvm( 7795): >>>>> com.google.android.configupdater [ userId:0 | appId:10003 ]
,E/SELinux ( 7795): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/ActivityThread( 3139): Failed to find provider info for com.google.android.wearable.settings
,I/ConfigStore( 7760): Config Database version: 1
,D/TimaKeyStoreProvider( 7795): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7795): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7795): Added TimaKesytore provider
,D/dalvikvm( 7795): GC_CONCURRENT freed 2994K, 29% free 9566K/13452K, paused 7ms+4ms, total 30ms
,D/dalvikvm( 7795): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/ContextImpl( 7795): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 7795): Update started
,E/UpdateRequestReceiver( 7795): Received malformed URL while handling Gservices.CHANGED_ACTION
,W/ContextImpl( 7795): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 7795): Update started
,D/dalvikvm( 2837): GC_EXPLICIT freed 1586K, 20% free 11594K/14416K, paused 31ms+17ms, total 210ms
,E/UpdateRequestReceiver( 7795): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 7795): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 7795): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/SELinux ( 7829): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7829):  
,I/SELinux ( 7829): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7829):  
I/SELinux ( 7829):  
,I/SELinux ( 7829): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7829): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7829): >>>>> Normal User
,E/dalvikvm( 7829): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 7829): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7829): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7829): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7829): Added TimaKesytore provider
,D/dalvikvm( 2420): GC_EXPLICIT freed 1354K, 55% free 24674K/53836K, paused 10ms+14ms, total 209ms
,I/DownloadManager( 2721): Download 57 starting
I/ActivityManager( 2420): Killing 5826:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty #43
,W/ActivityThread( 2721): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/dalvikvm( 7829): GC_CONCURRENT freed 2997K, 29% free 9570K/13456K, paused 2ms+1ms, total 27ms
,D/dalvikvm( 7829): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/DownloadManager( 2721): Download 58 starting
,D/dalvikvm( 2837): null clazz in OP_INSTANCE_OF, single-stepping
,E/Volley  ( 3139): [118] BasicNetwork.performRequest: Unexpected response code 410 for https://www.googleapis.com/plus/v2whitelisted/people/me/people/all?prettyPrint=false&fields=items(etag,id,names,nicknames,images,urls,sortKeys,taglines,emails,phoneNumbers,addresses,metadata,memberships,legacyFields/mobileOwnerId),nextPageToken,nextSyncToken&customResponseMaskingType=menagerie&includeAffinity=gplusAutocomplete&includeAffinity=chatAutocomplete&includeAffinity=emailAutocomplete&includeOthers=true&maxResults=100&orderBy=modified&syncToken=CI7Nj_uQKhIBMRjYEioECAEQAQ
,I/PeopleSync( 3139): Sync Token out of date, syncing all people/gaia-map
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 370, Delta = 10
,I/System.out( 7760): Thread-686(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4355, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5021): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5021): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/System.out( 7760): Thread-686(ApacheHTTPLog):isShipBuild true
,I/System.out( 7760): Thread-686(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/Velvet.VelvetFactory( 5863): refreshing search history.
,I/Search.GservicesUpdateTask( 5863): Updating Gservices keys
,E/SPPClientService( 5408): [b] __ProvisionReply__
,D/PreloadUpdateManagerStateMachine( 6407): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6407): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6407): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6407): AutoUpdateTriggerManager:REQUEST2:requestInterval
,E/SPPClientService( 5408): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5408): [d] null
,V/AlarmManager( 2420):  next == MAX_VALUE
,I/Volley  ( 6407): RestApi Request Add : 2307
,E/SPPClientService( 5408): [g] getPLMN return empty string
,I/ActivityManager( 2420): Waited long enough for: ServiceRecord{42f65e68 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,E/SPPClientService( 5408): [b] SharedConstants.WHAT_PROV_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5408): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,I/dalvikvm( 3139): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 3139): VFY: unable to resolve static method 1165: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 3139): VFY: replacing opcode 0x71 at 0x0046
,E/SPPClientService( 5408): [a] [ConnectionManager] Connection is already disconnected.
,I/CheckinRequestBuilder( 3139): Classify the device as Phone.
,I/System.out( 2721): Thread-53(HTTPLog):isShipBuild true
,I/System.out( 2721): Thread-53(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 2721): Thread-52(HTTPLog):isShipBuild true
,I/System.out( 2721): Thread-52(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/SPPClientService( 5408): [g] getNetMCC return empty string
,I/Icing   ( 3139): Indexing 6245F4AA15572483160DEB38E2CBB6FB536E377A from com.google.android.music
,D/dalvikvm( 2837): GC_EXPLICIT freed 538K, 21% free 11478K/14416K, paused 5ms+7ms, total 54ms
,I/DownloadManager( 2721): Ignoring Content-Length since Transfer-Encoding is also defined
,D/dalvikvm( 3139): GC_EXPLICIT freed 1709K, 19% free 12254K/14952K, paused 4ms+7ms, total 65ms
,W/SQLiteConnectionPool( 3139): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/dalvikvm( 5408): GC_CONCURRENT freed 2117K, 23% free 10417K/13460K, paused 2ms+11ms, total 126ms
,V/DownloadManager( 2721): MIME Type = text/plain
,I/DownloadManager( 2721): Download 58 finished with status SUCCESS
,D/dalvikvm( 6407): GC_CONCURRENT freed 2541K, 26% free 10073K/13500K, paused 5ms+15ms, total 95ms
,I/DownloadManager( 2721): Ignoring Content-Length since Transfer-Encoding is also defined
,I/ActivityManager( 2420): Killing 5909:com.sec.knox.bridge/1000 (adj 15): empty #43
I/Icing   ( 3139): Indexing done 6245F4AA15572483160DEB38E2CBB6FB536E377A
,I/CheckinTask( 3139): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/Auth    ( 2837): [BroadcastManager] Broadcasting account services changed.
I/CheckinService( 3139): Checking schedule, now: 1447838164544 next: 1448396507488
,I/CheckinService( 3139): active receiver: disabled
,V/DownloadManager( 2721): MIME Type = text/plain
,D/EnterpriseDeviceManagerService( 2420): Creating context as user 0
,I/DownloadManager( 2721): Download 57 finished with status SUCCESS
,D/CheckinService( 3139): Recording last checkin time for package unspecified as 1447838164620
,D/SystemEventReceiver( 3139): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 3139): Updating ocr activity enabled=false
,D/dalvikvm( 2837): GC_EXPLICIT freed 708K, 21% free 11513K/14416K, paused 9ms+13ms, total 75ms
,I/System.out( 7760): SyncAdapterThread-1 calls detatch()
,I/Auth    ( 2837): [BroadcastManager] Broadcasting account services changed.
,W/ActivityManager( 2420): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,I/CheckinService( 3139): Checkin interval check for package: unspecified last checkin: 1447838164620 min interval config: 0 actual interval: 256
,I/SystemUpdateService( 3139): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
I/CheckinService( 3139): Checking schedule, now: 1447838164952 next: 1448396507488
,I/CheckinService( 3139): active receiver: disabled
,D/SystemUpdateService( 3139): onCreate
,D/SystemUpdateService( 3139): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/OcrModelManager( 3139): Updating downloaded model state (gservices changed)
,I/PeopleSync( 3139): Sync finished, successful=true, took 5169ms
,I/SystemUpdateService( 3139): cancelUpdate (empty URL)
,I/SystemUpdateService( 3139): active receiver: disabled
,D/SystemUpdateService( 3139): onDestroy
,D/GCM     ( 2837): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/GCoreUlr( 2734): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 2734): DispatchingService.onCreate()
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7760): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,D/dalvikvm( 6407): GC_CONCURRENT freed 2064K, 26% free 10015K/13500K, paused 3ms+2ms, total 26ms
,D/AmoledAdjustTimer( 2420): prevTemp = 295, currTemp = 297, prevStep = 4, currStep = 4
,D/dalvikvm( 2420): GC_EXPLICIT freed 1714K, 55% free 24721K/53836K, paused 7ms+17ms, total 214ms
,W/ContextImpl( 7795): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,I/Auth    ( 2837): [BroadcastManager] Broadcasting account services changed.
,W/ContextImpl( 7795): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,I/GCoreUlr( 2734): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/DownloadManager( 2721): Download 59 starting
,I/PeopleSync( 3139): ***Sync canceled***, duration: 7075 [5005f081]
,W/MusicApiClient( 7760): No content in 'data' field in GET sync response for Track
,I/System.out( 7760): SyncAdapterThread-1 calls detatch()
,E/SPPClientService( 5408): [b] __InitReply__
,I/DownloadManager( 2721): Ignoring Content-Length since Transfer-Encoding is also defined
,D/dalvikvm( 6407): GC_CONCURRENT freed 1774K, 25% free 10253K/13500K, paused 2ms+21ms, total 89ms
,I/DownloadManager( 2721): Download 60 starting
,D/dalvikvm( 3139): GC_EXPLICIT freed 1049K, 19% free 12238K/14952K, paused 16ms+9ms, total 178ms
,D/SyncManager( 2420): handleSyncHandlerMessage: dropping since the sync is no longer active: 
,I/System.out( 6407): Thread-595(HTTPLog):isShipBuild true
,I/System.out( 6407): Thread-595(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 5863): GC_CONCURRENT freed 1968K, 24% free 10364K/13544K, paused 6ms+11ms, total 110ms
,I/DownloadManager( 2721): Ignoring Content-Length since Transfer-Encoding is also defined
,I/PeopleSync( 3139): onPerformSync() [5005f081]
,V/DownloadManager( 2721): MIME Type = text/plain
,I/DownloadManager( 2721): Download 59 finished with status SUCCESS
,D/GCM     ( 2837): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 2837): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/DownloadManager( 2721): MIME Type = text/plain
,W/MusicApiClient( 7760): No content in 'data' field in GET sync response for SyncablePlaylist
,I/System.out( 7760): SyncAdapterThread-1 calls detatch()
,D/dalvikvm( 2837): GC_EXPLICIT freed 1074K, 20% free 11553K/14392K, paused 4ms+7ms, total 50ms
,I/DownloadManager( 2721): Download 60 finished with status SUCCESS
,D/dalvikvm( 2721): GC_CONCURRENT freed 1434K, 28% free 10438K/14348K, paused 5ms+10ms, total 66ms
,W/ContextImpl( 7795): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/PeopleSync( 3139): Setting subscription: result=true [5005f081]
,I/UpdateFetcherService( 7795): Update downloaded, starting installation
,I/UpdateFetcherService( 7795): Started installation
,I/GCoreUlr( 2734): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/dalvikvm( 7760): GC_CONCURRENT freed 2059K, 22% free 10496K/13452K, paused 4ms+3ms, total 69ms
,I/GCoreUlr( 2734): Unbound from all location providers
,D/hcjo    ( 6407): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    ( 6407): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine( 6407): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
D/PreloadUpdateManagerStateMachine( 6407): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6407): entry::REQ_UPDATE_CHECK
,W/ContextImpl( 7795): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/Volley  ( 6407): RestApi Request Add : 2315
,I/UpdateFetcherService( 7795): Update downloaded, starting installation
,I/UpdateFetcherService( 7795): Started installation
,I/GCoreUlr( 2734): DispatchingService.onDestroy()
,I/GCoreUlr( 2734): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2734): Unbound from all location providers
,W/MusicApiClient( 7760): No content in 'data' field in GET sync response for SyncablePlaylistEntry
,I/System.out( 7760): SyncAdapterThread-1 calls detatch()
,I/SELinux ( 7925): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7925):  
,I/SELinux ( 7925): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7925):  
I/SELinux ( 7925):  
,I/SELinux ( 7925): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7925): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7925): >>>>> Normal User
,E/dalvikvm( 7925): >>>>> com.google.android.apps.docs [ userId:0 | appId:10094 ]
,E/SELinux ( 7925): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7925): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7925): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7925): Added TimaKesytore provider
,D/dalvikvm( 7925): GC_CONCURRENT freed 2977K, 29% free 9591K/13456K, paused 4ms+1ms, total 20ms
,D/dalvikvm( 7925): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2420): GC_EXPLICIT freed 1473K, 55% free 24738K/53836K, paused 12ms+21ms, total 250ms
,W/MusicApiClient( 7760): No content in 'data' field in GET sync response for SyncableRadioStation,
,I/System.out( 7760): SyncAdapterThread-1 calls detatch(),
,I/MusicSyncAdapter( 7760): Periodic sync is disabled
,W/ContextImpl( 7760): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/ConfigUpdateInstallReceiver( 2420): Not installing, new version is <= current version
,W/ContextImpl( 7760): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/CacheService( 7760): onCreate,
,D/CacheService( 7760): onBind,
,E/dalvikvm( 7925): Could not find class 'com.google.trix.ritz.shared.messages.b', referenced from method bnz.<init>,
W/dalvikvm( 7925): VFY: unable to resolve new-instance 7208 (Lcom/google/trix/ritz/shared/messages/b;) in Lbnz;
,D/dalvikvm( 7925): VFY: replacing opcode 0x22 at 0x03bc
E/dalvikvm( 7925): Could not find class 'com.google.trix.ritz.shared.render.g', referenced from method bnz.<init>
,W/dalvikvm( 7925): VFY: unable to resolve new-instance 7339 (Lcom/google/trix/ritz/shared/render/g;) in Lbnz;
,D/dalvikvm( 7925): VFY: replacing opcode 0x22 at 0x03cb,
,E/dalvikvm( 7925): Could not find class 'com.google.trix.ritz.shared.behavior.validation.a', referenced from method bnz.<init>,
W/dalvikvm( 7925): VFY: unable to resolve new-instance 7168 (Lcom/google/trix/ritz/shared/behavior/validation/a;) in Lbnz;
,D/dalvikvm( 7925): VFY: replacing opcode 0x22 at 0x05d8
,W/ContextImpl( 7760): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/dalvikvm( 7925): Could not find class 'com.google.trix.ritz.shared.mutation.O', referenced from method bnz.<init>
W/dalvikvm( 7925): VFY: unable to resolve new-instance 7301 (Lcom/google/trix/ritz/shared/mutation/O;) in Lbnz;
,D/dalvikvm( 7925): VFY: replacing opcode 0x22 at 0x07a9
,D/dalvikvm( 7925): DexOpt: unable to opt direct call 0xb146 at 0x3be in Lbnz;.<init>
,D/dalvikvm( 7925): DexOpt: unable to opt direct call 0xb292 at 0x3cd in Lbnz;.<init>
,D/dalvikvm( 7925): DexOpt: unable to opt direct call 0xb108 at 0x5da in Lbnz;.<init>
,D/dalvikvm( 7925): DexOpt: unable to opt direct call 0xb23b at 0x7ab in Lbnz;.<init>
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 7760): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
I/qtaguid ( 6407): Failed write_ctrl(u -1) res=-1 errno=9
I/qtaguid ( 6407): Untagging socket -1 failed errno=-9
,W/NetworkManagementSocketTagger( 6407): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine( 6407): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
D/PreloadUpdateManagerStateMachine( 6407): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine( 6407): entry::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 6407): exit::NOTIFY_NOTIFICATION
,D/PreloadUpdateManagerStateMachine( 6407): entry::FINISH
D/PreloadUpdateManagerStateMachine( 6407): exit::FINISH
,D/PreloadUpdateManagerStateMachine( 6407): entry::IDLE
,I/ActivityManager( 2420): Killing 5962:com.sec.android.Kies/1000 (adj 15): empty #43
W/dalvikvm( 7925): method Lcom/google/android/apps/docs/editors/toolbar/PreHoneyCombActionBar;.a incorrectly overrides package-private method with same name in Lakm;
W/dalvikvm( 7925): method Lcom/google/android/apps/docs/editors/toolbar/PreHoneyCombActionBar;.b incorrectly overrides package-private method with same name in Lakm;
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 7760): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7760): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,I/MusicLeanback( 7760): Conditions not met for autocaching.
,I/MusicLeanback( 7760): Stop autocaching.
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7760): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 7925): VFY: unable to resolve instance field 20115
D/dalvikvm( 7925): VFY: replacing opcode 0x54 at 0x001e
I/dalvikvm( 7925): DexOpt: unable to optimize instance field ref 0x4e93 at 0x28 in LbvF;.getInstance
I/dalvikvm( 2734): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 2734): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
D/dalvikvm( 2734): VFY: replacing opcode 0x6e at 0x0033
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7760): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7760): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7760): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/MusicLeanback( 7760): Conditions not met for autocaching.
,I/MusicLeanback( 7760): Stop autocaching.
,W/ArtDownloadService( 7760): Setting cache size 0
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7760): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ContextImpl( 7760): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7760): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
D/CacheService( 7760): onDestroy
,W/ContextImpl( 7760): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
I/ActivityManager( 2420): Killing 5990:com.google.android.apps.uploader/u0a117 (adj 15): empty #43
,W/ArtDownloadService( 7760): Setting cache size 0
,W/BaseAppContext( 2734): Using Auth Proxy for data requests.
,W/dalvikvm( 2734): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2734): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/ActiveOrDefaultContextProvider( 7925): Missing scope.enter somewhere. Returning default context
,W/dalvikvm( 2734): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 2734): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2734): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2734): VFY: replacing opcode 0x6e at 0x00bb
,W/ActiveOrDefaultContextProvider( 7925): Missing scope.enter somewhere. Returning default context
,D/dalvikvm( 7925): GC_CONCURRENT freed 2135K, 23% free 10458K/13476K, paused 3ms+2ms, total 33ms
,W/GAV2    ( 7925): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/dalvikvm( 7925): GC_FOR_ALLOC freed 244K, 22% free 10603K/13476K, paused 21ms, total 21ms
,I/dalvikvm-heap( 7925): Grow heap (frag case) to 11.293MB for 79892-byte allocation
,D/dalvikvm( 7925): GC_FOR_ALLOC freed 1K, 22% free 10679K/13556K, paused 21ms, total 21ms
,I/System.out( 7925): Thread-698(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7925): Thread-698(ApacheHTTPLog):isShipBuild true
,I/System.out( 7925): Thread-698(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 7925): DocsSyncAdapter calls detatch()
,I/GAV2    ( 5643): Thread[GAThread,5,main]: No campaign data found.
I/System.out( 2734): Thread-90(HTTPLog):isShipBuild true
,I/System.out( 2734): Thread-90(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/GCoreUlr( 2734): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr( 2734): DispatchingService.onCreate()
,I/GCoreUlr( 2734): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/dalvikvm( 2734): GC_CONCURRENT freed 1808K, 24% free 11033K/14392K, paused 7ms+5ms, total 66ms
,I/GCoreUlr( 2734): Unbound from all location providers
,I/GCoreUlr( 2734): DispatchingService.onDestroy()
,I/GCoreUlr( 2734): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2734): Unbound from all location providers
,D/dalvikvm( 2837): GC_EXPLICIT freed 664K, 21% free 11499K/14392K, paused 4ms+6ms, total 50ms
,I/jxcore-log( 6875): Attempting to connect to the test coordinator server
I/jxcore-log( 6875): 
,I/System.out( 7925): DocsSyncAdapter calls detatch()
,I/jxcore-log( 6875): Attempting to connect to the test coordinator server
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Attempting to connect to the test coordinator server
I/jxcore-log( 6875): 
,D/dalvikvm( 7925): GC_FOR_ALLOC freed 2346K, 24% free 11171K/14564K, paused 36ms, total 36ms
,V/CalendarSyncAdapter( 7396): Saving inProgress state: {calendarId=thalitester@gmail.com, maxAttendees=50, maxResults=200, timeMax=2016-11-25T00:00:00.000Z, updatedMin=2015-11-05T21:58:54.693Z}
,D/dalvikvm( 7396): GC_CONCURRENT freed 2431K, 25% free 10090K/13452K, paused 2ms+3ms, total 34ms
,D/CalendarSyncAdapter( 7396): Found 0 events marked dirty & lastSynced
,I/jxcore-log( 6875): Attempting to connect to the test coordinator server
I/jxcore-log( 6875): 
,D/dalvikvm( 2420): GC_EXPLICIT freed 1640K, 55% free 24654K/53836K, paused 7ms+16ms, total 193ms
,I/jxcore-log( 6875): Attempting to connect to the test coordinator server
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Attempting to connect to the test coordinator server
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Test app app.js loaded
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/System.out( 7925): DocsSyncAdapter calls detatch()
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_error","data":"timeout"} : connect_error : timeout
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): DBG, CoordinatorConnector connect_timeout called
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): DBG, CoordinatorConnector connect_timeout called
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): DBG, CoordinatorConnector connect_timeout called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): DBG, CoordinatorConnector connect_timeout called
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): DBG, CoordinatorConnector connect_timeout called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): DBG, CoordinatorConnector connect_timeout called
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): DBG, CoordinatorConnector connect_timeout called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Error:{"type":"connect_timeout","data":20000} : connect_timeout : 20000
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): {"type":"test","name":"setup","id":0}
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): LogCallback not set !!!!
I/jxcore-log( 6875): 
,I/chromium( 6875): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/GAV2    ( 7925): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager( 2420): Killing 5451:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/ActivityManager( 2420): Waited long enough for: ServiceRecord{44203ba8 u0 com.sec.spp.push/.PushClientService}
,I/jxcore-log( 6875): DBG, CoordinatorConnector connect called
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): DBG, CoordinatorConnector connect called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): DBG, CoordinatorConnector connect called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): DBG, CoordinatorConnector connect called
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): DBG, CoordinatorConnector connect called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): DBG, CoordinatorConnector connect called
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): DBG, CoordinatorConnector connect called
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): DBG, CoordinatorConnector too_late called
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): {"id":0,"ok":false,"name":"Coordinator server got disconnected","operator":"fail","error":{},"test":0,"type":"assert"}
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
,I/WifiManager( 6875): packageName : com.test.thalitest
,I/WifiManager( 6875): setWifiEnabled : false
,I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
,D/BluetoothAdapterService(1109582480)( 5021): unRegister RemoteMessageListener
,D/HeadsetService( 5021): registerMessageListener
D/HeadsetStateMachine( 5021): Disconnected process message: 80
D/BluetoothAdapterState( 5021): CURRENT_STATE=ON, MSG = USER_TURN_OFF
I/BluetoothAdapterState( 5021): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 5021): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5021): updateAdapterState state is 13
I/BluetoothPbapService( 5021): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
D/BluetoothAdapterService( 5021): Broadcasting updateAdapterState() to 1 receivers.
,D/HeadsetStateMachine( 5021): processUnRegisterMessageListener : 2
,D/BluetoothAdapterService( 5021): Autoconnection is available 
D/BluetoothAdapterService( 5021): updateAdapterState prevState = 12newState = 13
,D/BluetoothAdapterService( 5021): terminating service from this receiver
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
,E/bt-btif ( 5021): bta_jv_rfcomm_stop_server
W/InputMethodManagerService( 2420): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 2420): [BT Setting State] State =13
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
,W/ContextImpl( 5021): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.stopService:511 com.android.bluetooth.btservice.AdapterService.updateAdapterState:657 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
I/wpa_supplicant( 6922): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 6922): wlan0: Setting scan request: 0 sec 0 usec
D/PhoneApp( 2753): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 13
,I/SamsungIME( 3050): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
W/Settings( 2420): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 6922): Scan requested (ret=0) - scan timeout 30 seconds
,I/WifiStateMachine( 2420): ignore requestNetworkTransitionWakelock airplane:true
,I/QuickConnect[1.1][2] ( 4995): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_OFF
D/WifiP2pService( 2420): InactiveState{ what=143375 }
D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,V/BluetoothEventManager( 5476): Received android.bluetooth.adapter.action.STATE_CHANGED
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3
E/bt-btif ( 5021): bta_jv_rfcomm_stop_server
I/WifiManager( 6875): packageName : com.test.thalitest
I/BtOppRfcommListener( 5021): stopping Accept Thread
E/BtOppRfcommListener( 5021): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/WifiManager( 6875): setWifiEnabled : false
D/GKI_LINUX( 5021): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
E/bt-btif ( 5021): bta_jv_rfcomm_stop_server
,I/BluetoothAdapterState( 5021): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/BluetoothAdapterState( 5021): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/BtOppRfcommListener( 5021): BluetoothSocket listen thread finished
E/bt-btif ( 5021): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
D/CommandListener( 1915): Clearing all IP addresses on wlan0
E/bt-btif ( 5021): cmd socket is not created
E/WifiController( 2420): illegal state found both WifiController and WifiStateMachine
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
,W/ContextImpl( 5476): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/btif_config_util( 5021): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
,I/WifiManager( 6875): packageName : com.test.thalitest
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
I/WifiManager( 6875): setWifiEnabled : false
,D/BluetoothPbap( 5476): Proxy object disconnected
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
,D/PbapServerProfile( 5476): Bluetooth service disconnected
D/ConnectivityService( 2420): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2420): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2420): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2420): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2420): net.tcp.delack.default not found in system default properties
,E/ConnectivityService( 2420): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
E/WifiController( 2420): illegal state found both WifiController and WifiStateMachine
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/IOP_DB_BT( 5021): db_close: nbr users 0
,D/IOP_DB_BT( 5021): db_close: free database
,D/ConnectivityService( 2420): Attempting to switch to mobile
,D/ConnectivityService( 2420): Attempting to switch to BLUETOOTH_TETHER
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-18ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 2420): InactiveState{ what=131204 }
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
E/WifiStateMachine( 2420): Error! unhandled message{ when=-23ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/DockEventReceiver( 5476): finishStartingService: stopping service
D/STATUSBAR-IconMerger( 2582): checkOverflow(384), More:false, Req:false Child:3
,D/WifiP2pService( 2420): P2pEnabledState{ what=131204 }
I/WifiManager( 6875): packageName : com.test.thalitest
D/BluetoothNotiBroadcastReceiver( 5476): onReceive
I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
E/WifiController( 2420): illegal state found both WifiController and WifiStateMachine
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
D/WifiP2pService( 2420): sending p2p connection changed broadcast: FAILED
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
,I/WifiManager( 6875): packageName : com.test.thalitest
,I/WifiManager( 6875): setWifiEnabled : false
,I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
,E/WifiController( 2420): illegal state found both WifiController and WifiStateMachine
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
W/WifiP2pStateTracker( 2420): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController( 2420): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter( 2420): onP2pDisconnected
,D/QuickConnect[1.1][2] ( 4995): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
D/IpRemoteDisplayController( 2420): disconnectWfdBridgeServer
,D/IpRemoteDisplayController( 2420): WfdBridgeServer is already null
D/QuickConnect[1.1][2] ( 4995): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
V/RouteController( 1915): RTNETLINK answers: No such process
V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
,I/WifiManager( 6875): packageName : com.test.thalitest
,I/WifiManager( 6875): setWifiEnabled : false
,D/WifiP2pService( 2420): sending p2p connection changed broadcast: DISCONNECTED
V/RouteController( 1915): RTNETLINK answers: No such file or directory
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
,E/WifiStateMachine( 2420): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController( 2420): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 2420): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 2420): disconnect
D/WifiDisplayController( 2420): updateConnection
D/WifiDisplayController( 2420): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayAdapter( 2420): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/WifiController( 2420): illegal state found both WifiController and WifiStateMachine
D/QuickConnect[1.1][2] ( 4995): SconnectManager.INetworkStateListener, onDisabled - mNetworkState : 0
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
,D/QuickConnect[1.1][2] ( 4995): P2pHelper.cancelConnectPeer -  mTargetList clear all 
D/WifiP2pService( 2420): P2pDisablingState
W/WifiP2pStateTracker( 2420): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiP2pService( 2420): P2pDisablingState{ what=139287 }
D/WifiP2pService( 2420): DefaultState{ what=139287 }
,I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
D/WifiP2pService( 2420): P2pDisablingState{ what=147458 }
D/WifiP2pService( 2420): p2p socket connection lost
,D/WifiP2pService( 2420): P2pDisabledState
D/QuickConnect[1.1][2] ( 4995): P2pHelper.removeP2pConfirm - skip: false
D/QuickConnect[1.1][2] ( 4995): CentralActionManager.removeHoldingIntentAll - all request done.
D/QuickConnect[1.1][2] ( 4995): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/QuickConnect[1.1][2] ( 4995): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
W/NetworkManagementService( 2420): route cmd failed: 
W/NetworkManagementService( 2420): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '35 route del src v6 2' failed with '400 35 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2420): '
W/NetworkManagementService( 2420): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2420): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2420): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2420): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2420): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2420): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2420): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2420): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2420): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2420): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2420): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/QuickConnect[1.1][2] ( 4995): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
,D/AuthorizationBluetoothService( 2837): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/WifiP2pService( 2420): P2pDisabledState{ what=139376 }
D/WifiP2pService( 2420): DefaultState{ what=139376 }
E/WifiP2pService( 2420): Unhandled message { what=139376 }
D/WifiP2pService( 2420): P2pDisabledState{ what=139287 }
,D/WifiP2pService( 2420): DefaultState{ what=139287 }
,D/QuickConnect[1.1][2] ( 4995): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/WifiDisplayController( 2420): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter( 2420): onP2pDisconnected
D/IpRemoteDisplayController( 2420): disconnectWfdBridgeServer
,D/IpRemoteDisplayController( 2420): WfdBridgeServer is already null
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
I/WifiManager( 6875): packageName : com.test.thalitest
,D/QuickConnect[1.1][2] ( 4995): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,I/WifiManager( 6875): setWifiEnabled : false
,D/WifiDisplayAdapter( 2420): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
D/WifiNative( 2420): callSECApiBoolean - ID [13]
E/WifiController( 2420): illegal state found both WifiController and WifiStateMachine
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
I/wpa_supplicant( 6922): USE_NETWORK : USE_NETWORK OFF
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/BluetoothAdapterState( 5021): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 5021): isSecureModeOn:false
W/BluetoothAdapterService( 5021): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5021): Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5021): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5021): Not skipping com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5021): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 5021): Not skipping com.android.bluetooth.a2dp.A2dpService
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
D/HeadsetService( 5021): Received stop request...Stopping profile...
I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
,D/NetUtils( 2420): android_net_utils_resetConnections in env=0x7992bca0 clazz=0x60d00001 iface=wlan0 mask=0x3
,D/ConnectivityService( 2420): resetConnections(wlan0, 3)
E/SPPClientService( 5408): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
E/SPPClientService( 5408): [e] exceptionCaught(). NET_TIMEOUT
,I/GAV2    ( 7925): Thread[GAThread,5,main]: No campaign data found.
W/BluetoothAdapterService( 5021): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5021): Not skipping com.android.bluetooth.hid.HidService
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
,I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
,E/SPPClientService( 5408): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5408): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5408): [b] ResponseMap empty
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/QuickConnect[1.1][2] ( 4995): HeadsetProfile.onServiceDisconnected - Bluetooth service disconnected
W/BluetoothAdapterService( 5021): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
,D/GKI_LINUX( 5021): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
W/BluetoothAdapterService( 5021): Not skipping com.android.bluetooth.hdp.HealthService
,D/NearbySettings( 5476): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5476): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5476): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 5476): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 5476): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5476): MountReceiver.onReceive - Set preference state off
,W/BluetoothAdapterService( 5021): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.android.bluetooth.pan.PanService
I/WifiManager( 6875): packageName : com.test.thalitest
,W/BluetoothAdapterService( 5021): Not skipping com.android.bluetooth.pan.PanService
,D/A2dpService( 5021): Received stop request...Stopping profile...
D/Avrcp   ( 5021): Unregistering previous receiver
,D/A2dpStateMachine( 5021): Exit Disconnected: -1
,D/MediaFocusControl( 2420): <<< unregisterRemoteControlDisplay
W/BluetoothAdapterService( 5021): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,I/WifiManager( 6875): setWifiEnabled : false
D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
D/BluetoothA2dp( 4995): Proxy object disconnected
,D/QuickConnect[1.1][2] ( 4995): A2dpProfile.onServiceConnected - Bluetooth service disconnected
,D/BluetoothA2dp( 2420): Proxy object disconnected
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
,W/BluetoothAdapterService( 5021): Not skipping com.android.bluetooth.map.BluetoothMapService
,I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
,V/NearbySettings( 5476): MountReceiver.mPrefHandler - 7002
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
W/BluetoothAdapterService( 5021): check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5021): Not skipping com.broadcom.bt.service.sap.SapService
,D/HeadsetProfile( 5476): Bluetooth service disconnected
,D/BluetoothA2dp( 4113): Proxy object disconnected
D/BluetoothAdapterState( 5021): Stopping profile services that were post enabled
,D/BluetoothA2dp( 5476): Proxy object disconnected
,D/A2dpProfile( 5476): Bluetooth service disconnected
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
,I/WifiManager( 6875): packageName : com.test.thalitest
D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5021): Profile still running: com.broadcom.bt.service.sap.SapService
D/HidService( 5021): Received stop request...Stopping profile...
D/HidService( 5021): Stopping Bluetooth HidService
I/WifiManager( 6875): setWifiEnabled : false
,I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
,V/NativeCrypto( 2837): Read error: ssl=0x7ba03520: I/O error during system call, Connection timed out
D/NearbySettings( 5476): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
,V/NearbySettings( 5476): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5476): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/Tethering( 2420): interfaceLinkStateChanged p2p0, true
,I/wpa_supplicant( 6922): p2p0: CTRL-EVENT-TERMINATING 
D/Tethering( 2420): interfaceStatusChanged p2p0, true
,I/WifiManager( 6875): packageName : com.test.thalitest
,I/WifiManager( 6875): setWifiEnabled : false
D/BluetoothInputDevice( 4995): Proxy object disconnected
D/QuickConnect[1.1][2] ( 4995): HidProfile.onServiceDisconnected - Bluetooth service disconnected
,I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
V/NativeCrypto( 2837): SSL shutdown failed: ssl=0x7ba03520: I/O error during system call, Broken pipe
E/WifiStateMachine( 2420): Error! unhandled message{ when=-162ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-165ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-88ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering( 2420): interfaceLinkStateChanged p2p0, false
D/Tethering( 2420): interfaceStatusChanged p2p0, false
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-92ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 6922): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 6922): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
W/BluetoothHeadsetServiceJni( 5021): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 5021): Cleaning up Bluetooth Handsfree callback object
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
,D/HealthService( 5021): Received stop request...Stopping profile...
,I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
D/PanService( 5021): Received stop request...Stopping profile...
I/NearbySettings( 5476): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 5476): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5476): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5476): MountReceiver.mPrefHandler - 7002
,D/BluetoothInputDevice( 5476): Proxy object disconnected
,D/HidProfile( 5476): Bluetooth service disconnected
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
,I/WifiManager( 6875): packageName : com.test.thalitest
D/BluetoothPan( 2420): BluetoothPAN Proxy object disconnected
,I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5021): Profile still running: com.broadcom.bt.service.sap.SapService
I/GKI_LINUX( 5021): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
D/BluetoothPan( 5476): BluetoothPAN Proxy object disconnected
D/PanProfile( 5476): Bluetooth service disconnected
I/GKI_LINUX( 5021): GKI_exit_task: GKI_exit_task 2 done
,I/GKI_LINUX( 5021): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/BluetoothMapService( 5021): Received stop request...Stopping profile...
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
D/SapService( 5021): Received stop request...Stopping profile...
,D/SapService( 5021): Stopping Bluetooth SapService
,I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5021): Profile still running: com.broadcom.bt.service.sap.SapService
D/BluetoothMap( 5476): Proxy object disconnected
W/BluetoothHidServiceJni( 5021): Cleaning up Bluetooth HID Interface...
,W/BluetoothHidServiceJni( 5021): Cleaning up Bluetooth GID callback object
D/MapProfile( 5476): Bluetooth service disconnected
D/Bluetoothsap( 5476): BluetoothSAP Proxy object disconnected
D/SapProfile( 5476): Bluetooth service disconnected
D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5021): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothHealthServiceJni( 5021): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 5021): Cleaning up Bluetooth Health object
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
I/WifiManager( 6875): packageName : com.test.thalitest
,I/WifiManager( 6875): setWifiEnabled : false
D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/Bluetoothsap( 5476): BluetoothSAP Proxy object disconnected
D/SapProfile( 5476): Bluetooth service disconnected
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
,D/BluetoothAdapterService( 5021): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothPanServiceJni( 5021): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 5021): Cleaning up Bluetooth PAN callback object
,D/BtSettings.ProfileConfig( 5021): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5021): Profile still running: com.broadcom.bt.service.sap.SapService
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6875): 
D/BluetoothAdapterService( 5021): Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
D/BluetoothAdapterState( 5021): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 5021): Bluetooth adapter state changed: 13-> 10
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
D/BluetoothAdapterService( 5021): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5021): updateAdapterState state is 10
,D/BluetoothAdapterService( 5021): Broadcasting updateAdapterState() to 1 receivers.
W/BluetoothSAPServiceJni( 5021): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 5021): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService( 5021): Autoconnection is available 
D/BluetoothAdapterService( 5021): updateAdapterState prevState = 13newState = 10
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
,I/BluetoothAdapterState( 5021): Entering OffState
,D/FileShare-Server( 5878): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/FileShare-Server( 5878): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() DISCONNECTED
,D/BluetoothInputDevice( 5476): onBluetoothStateChange: up=false
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
,I/WifiManager( 6875): packageName : com.test.thalitest
,I/WifiManager( 6875): setWifiEnabled : false
,I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
,D/BluetoothInputDevice( 4995): onBluetoothStateChange: up=false
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
,D/BluetoothA2dp( 4113): onBluetoothStateChange: up=false
,E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
,I/WifiManager( 6875): packageName : com.test.thalitest
,I/WifiManager( 6875): setWifiEnabled : false
D/BluetoothMap( 5476): onBluetoothStateChange: up=false
,I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
,D/NearbySettings( 5476): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 5476): DMSUtil.isNetworkConnected - flag-null, state-null
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
D/Tethering( 2420): interfaceStatusChanged wlan0, true
,I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
,I/NearbySettings( 5476): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
D/BluetoothPbap( 5476): onBluetoothStateChange: up=false
I/NearbySettings( 5476): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 5476): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 5476): MountReceiver.onReceive - Set preference state off
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
,V/NearbySettings( 5476): MountReceiver.mPrefHandler - 7002
I/WifiManager( 6875): packageName : com.test.thalitest
,I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
D/BluetoothTethering( 2420): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering( 2420): attempted to stop reverse tether with nothing tethered
,D/ConnectivityService( 2420): handleInetConditionChange: no active default network - ignore
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): updateIfacesLocked()
V/NetworkStats( 2420): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
V/NetworkStats( 2420): advisePersistThreshold() given 9223372036854775, clamped to 2097152
I/PowerManagerService( 2420): [PWL] Off : 140s ago
I/PowerManagerService( 2420): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2420): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2420): [PWL]       PARTIAL_WAKE_LOCK              'NetworkStats' (uid=1000, pid=2420, ws=null) (elapsedTime=6)
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
I/WifiManager( 6875): packageName : com.test.thalitest
D/BluetoothA2dp( 2420): onBluetoothStateChange: up=false
I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
D/Bluetoothsap( 5476): onBluetoothStateChange: up=false
D/Bluetoothsap( 5476): Unbinding service...
I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
I/knox    ( 4935): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
,W/ContextImpl( 4935): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
D/BluetoothA2dp( 4995): onBluetoothStateChange: up=false
I/knox    ( 4935): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
D/Bluetoothsap( 5476): onBluetoothStateChange: up=false
D/Bluetoothsap( 5476): Unbinding service...
D/knox    ( 4935): KNOXAgentService : onCreate()
D/knox    ( 4935): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 4935): KNOXAgentService. startJobThread() start
D/knox    ( 4935): KNOXAgentService. JobThread()
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
D/knox    ( 4935): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 4935): KNOXAgentService. startJobThread() wait
I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
,D/BluetoothA2dp( 5476): onBluetoothStateChange: up=false
,V/NetworkStats( 2420): performPollLocked() took 46ms
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/knox    ( 4935): KNOXAgentService : onDestroy().
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
D/knox    ( 4935): ModuleBase.cancelAllAlarmManageModule()
,I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
W/InputMethodManagerService( 2420): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2420): [BT Setting State] State =10
,I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
,I/SamsungIME( 3050): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/InputMethodManagerService( 2420): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/PhoneApp( 2753): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 10
I/QuickConnect[1.1][2] ( 4995): BluetoothHelper.ACTION_STATE_CHANGED - STATE_OFF
V/BluetoothEventManager( 5476): Received android.bluetooth.adapter.action.STATE_CHANGED
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
,I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
,W/ContextImpl( 5476): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
D/Tethering( 2420): interfaceLinkStateChanged wlan0, false
D/Tethering( 2420): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 6922): wlan0: CTRL-EVENT-TERMINATING 
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
D/DockEventReceiver( 5476): finishStartingService: stopping service
D/Tethering( 2420): InitialState.processMessage what=4
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
D/BluetoothNotiBroadcastReceiver( 5476): onReceive
,E/Tethering( 2420): No numeric data
I/ConnectivityService( 2420): defaultVal : 1, tetherEnabledInSettings : true,
,D/Tethering( 2420): sendTetherStateChangedBroadcast 0, 0, 0,
D/PackageManager( 2420): [MSG] WRITE_SETTINGS
D/SSRMv2:SIOP( 2420): SIOP:: AP = 360, Delta = -10
,V/NetworkStats( 2420): performPollLocked(flags=0x1),
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit,
V/NetworkStats( 2420): performPollLocked() took 32ms
,W/PackageSettings( 2420): Skipping PackageSetting{42700030 com.example.hello/10447} due to missing metadata,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4350, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
D/PackageManager( 2420): checkUidPermission - Execution time: 160 ms
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
D/WifiStateMachine( 2420): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
W/Settings( 7352): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,W/Settings( 2734): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
,I/WifiManager( 6875): packageName : com.test.thalitest
,I/WifiManager( 6875): setWifiEnabled : false
,I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
D/STATUSBAR-IconMerger( 2582): checkOverflow(384), More:false, Req:false Child:3
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
,E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
,D/AuthorizationBluetoothService( 2837): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
,I/WifiManager( 6875): packageName : com.test.thalitest
,I/WifiManager( 6875): setWifiEnabled : false
,I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
,I/knox    ( 4935): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
,W/ContextImpl( 4935): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/WifiManager( 6875): packageName : com.test.thalitest
,I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
I/knox    ( 4935): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
D/knox    ( 4935): KNOXAgentService : onCreate()
D/knox    ( 4935): KNOXAgentService : set alarms for deniallog and usage data upload
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
,D/knox    ( 4935): KNOXAgentService. startJobThread() start
D/knox    ( 4935): KNOXAgentService. JobThread()
D/knox    ( 4935): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 4935): KNOXAgentService. startJobThread() wait
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
D/knox    ( 4935): KNOXAgentService : onDestroy().
,D/knox    ( 4935): ModuleBase.cancelAllAlarmManageModule()
I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
I/WifiManager( 6875): packageName : com.test.thalitest
,I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6875): toggleBluetooth - 
,I/jxcore-log( 6875): 
I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
I/WifiManager( 6875): packageName : com.test.thalitest
,I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
,I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
,E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
D/WifiStateMachine( 2420): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
,I/WifiManager( 6875): packageName : com.test.thalitest
I/WifiManager( 6875): setWifiEnabled : false
D/Tethering( 2420): Tethering got CONNECTIVITY_ACTION
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
D/Tethering( 2420): MasterInitialState.processMessage what=3
,I/ApplicationPolicy( 2420): updateDataUsageMap
,D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
,D/CaptivePortalTracker( 2420): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
D/ConnectivityService( 2420): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/DBG_DM  ( 4611): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
,I/WifiManager( 6875): packageName : com.test.thalitest
,I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
I/PCWCLIENTTRACE_PushUtil( 6101): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6101): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6101): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6101): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6101): noConnectivity : true
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
,E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
,I/WifiManager( 6875): packageName : com.test.thalitest
,I/WifiManager( 6875): setWifiEnabled : false
,I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
,E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
,I/WifiManager( 6875): packageName : com.test.thalitest
,I/WifiManager( 6875): setWifiEnabled : false
I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection...
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): The client has disconnected!
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): Turning radios to false
I/jxcore-log( 6875): 
,E/BluetoothManagerService( 2420): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6875): toggleBluetooth - 
I/jxcore-log( 6875): 
,I/WifiManager( 6875): packageName : com.test.thalitest
,I/WifiManager( 6875): setWifiEnabled : false
,I/WifiService( 2420): setWifiEnabled: false pid=6875, uid=10448
,I/jxcore-log( 6875): toggleWiFi
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): DBG, CoordinatorConnector too_late called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): DBG, CoordinatorConnector too_late called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): DBG, CoordinatorConnector too_late called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): DBG, CoordinatorConnector too_late called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): DBG, CoordinatorConnector too_late called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
,I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): DBG, CoordinatorConnector too_late called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): got too_late event, closing connection now.
I/jxcore-log( 6875): 
I/jxcore-log( 6875): CoordinatorConnector close called
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST TOOK:  ms ****
I/jxcore-log( 6875): 
I/jxcore-log( 6875): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 6875): 
,I/chromium( 6875): [INFO:CONSOLE(63)] "logCallback 0 isOK: false : Coordinator server got disconnected", source: file:///android_asset/www/js/thali_main.js (63)
,E/Watchdog( 2420): !@Sync 11
,I/KLMS-2.3.201 : ( 7105): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7105): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1447838174140
,I/KLMS-2.3.201 : ( 7105): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/SO_AGENT( 7128): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7128): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 6263): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 6263): [BDLM] already registered in spp,
I/SA      ( 6263): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 6263): [OR] == ACTION_CONNECTIVITY_CHANGE ==,
I/SA      ( 6263): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6263): [OR] == isSIMCardReady false ==
I/SA      ( 6263): [SCU] == networkStateCheck == false
,I/SA      ( 6263): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 6036): Other Intent
,D/com.samsung.app( 7187): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7187): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 7221): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 7221): getCountryCode(): countryCode = PL
,D/Headlines( 7221): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 7221): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 7221): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 7221): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 7221): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 7221): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 7221): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 5643): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 5643): num queued entries: 0
,I/iu.UploadsManager( 5643): num updated entries: 0
,D/QuickConnect[1.1][2] ( 4995): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 4995): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 4995): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4223b9f0
,I/iu.SyncManager( 5643): NEXT; no task
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/PackageManager( 2420): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.google.android.gms.checkin.CheckinService$ActiveReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10012, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@43f1a6c8, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}]
,D/AndroidRuntime( 8034): ,
D/AndroidRuntime( 8034): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8034): CheckJNI is OFF
,D/AndroidRuntime( 8034): setted country_code = Poland,
,D/AndroidRuntime( 8034): setted countryiso_code = PL,
D/AndroidRuntime( 8034): setted sales_code = PLS
,D/AndroidRuntime( 8034): readGMSProperty: start,
D/AndroidRuntime( 8034): readGMSProperty: already setted!!
D/AndroidRuntime( 8032): 
D/AndroidRuntime( 8032): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8034): readGMSProperty: end
D/AndroidRuntime( 8034): addProductProperty: start
,D/AndroidRuntime( 8032): CheckJNI is OFF,
D/AndroidRuntime( 8032): setted country_code = Poland
,D/AndroidRuntime( 8032): setted countryiso_code = PL,
D/AndroidRuntime( 8032): setted sales_code = PLS
D/AndroidRuntime( 8032): readGMSProperty: start
,D/AndroidRuntime( 8032): readGMSProperty: already setted!!
D/AndroidRuntime( 8032): readGMSProperty: end
,D/AndroidRuntime( 8032): addProductProperty: start
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection - timeout
,D/dalvikvm( 8034): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 8034): Added shared lib libjavacore.so 0x0
D/dalvikvm( 8034): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 8034): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 8034): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 8032): Trying to load lib libjavacore.so 0x0
,I/InputReader( 2420): Reconfiguring input devices.  changes=0x00000010
,D/dalvikvm( 8032): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 8032): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 8032): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 8032): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/AndroidRuntime( 8036): 
D/AndroidRuntime( 8036): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
,D/AndroidRuntime( 8030): 
D/AndroidRuntime( 8030): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/AndroidRuntime( 8038): 
D/AndroidRuntime( 8038): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8036): CheckJNI is OFF
D/AndroidRuntime( 8030): CheckJNI is OFF
D/AndroidRuntime( 8036): setted country_code = Poland
D/AndroidRuntime( 8036): setted countryiso_code = PL
D/AndroidRuntime( 8036): setted sales_code = PLS
D/AndroidRuntime( 8036): readGMSProperty: start
D/AndroidRuntime( 8036): readGMSProperty: already setted!!
D/AndroidRuntime( 8036): readGMSProperty: end
D/AndroidRuntime( 8036): addProductProperty: start
D/AndroidRuntime( 8028): 
D/AndroidRuntime( 8028): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8030): setted country_code = Poland
D/AndroidRuntime( 8030): setted countryiso_code = PL
D/AndroidRuntime( 8030): setted sales_code = PLS
D/AndroidRuntime( 8030): readGMSProperty: start
D/AndroidRuntime( 8030): readGMSProperty: already setted!!
D/AndroidRuntime( 8038): CheckJNI is OFF
D/AndroidRuntime( 8030): readGMSProperty: end
D/AndroidRuntime( 8030): addProductProperty: start
D/AndroidRuntime( 8038): setted country_code = Poland
D/AndroidRuntime( 8038): setted countryiso_code = PL
D/AndroidRuntime( 8038): setted sales_code = PLS
D/AndroidRuntime( 8038): readGMSProperty: start
D/AndroidRuntime( 8038): readGMSProperty: already setted!!
D/AndroidRuntime( 8038): readGMSProperty: end
D/AndroidRuntime( 8038): addProductProperty: start
,D/AndroidRuntime( 8028): CheckJNI is OFF
,D/AndroidRuntime( 8028): setted country_code = Poland
,D/AndroidRuntime( 8028): setted countryiso_code = PL
D/AndroidRuntime( 8028): setted sales_code = PLS
D/AndroidRuntime( 8028): readGMSProperty: start
,D/AndroidRuntime( 8028): readGMSProperty: already setted!!
D/AndroidRuntime( 8028): readGMSProperty: end
,D/AndroidRuntime( 8028): addProductProperty: start
,D/dalvikvm( 8038): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 8030): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 8038): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 8036): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 8028): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 8030): Added shared lib libjavacore.so 0x0
D/dalvikvm( 8038): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 8038): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 8038): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 8036): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 8028): Added shared lib libjavacore.so 0x0
D/dalvikvm( 8028): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 8028): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 8028): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 8030): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 8030): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 8030): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 8036): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 8036): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 8036): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "smsto"
,E/memtrack( 8034): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 8034): failed to load memtrack module: -2
,E/memtrack( 8038): Couldn't load memtrack module (No such file or directory)
E/memtrack( 8032): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 8032): failed to load memtrack module: -2
,E/android.os.Debug( 8038): failed to load memtrack module: -2
,D/RegisteredServicesCache( 2757): empty dynamic service,
,D/dalvikvm( 8034): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods,
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms",
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/memtrack( 8028): Couldn't load memtrack module (No such file or directory),
,E/android.os.Debug( 8028): failed to load memtrack module: -2,
,E/memtrack( 8036): Couldn't load memtrack module (No such file or directory),
,E/android.os.Debug( 8036): failed to load memtrack module: -2,
,E/memtrack( 8030): Couldn't load memtrack module (No such file or directory),
,E/android.os.Debug( 8030): failed to load memtrack module: -2
,D/dalvikvm( 8038): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods,
,D/dalvikvm( 8032): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,D/dalvikvm( 8028): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods,
,D/dalvikvm( 8036): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods,
,D/dalvikvm( 8030): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods,
,D/AndroidRuntime( 8034): Calling main entry com.android.commands.pm.Pm,
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :,
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mmsto"
,D/AndroidRuntime( 8028): Calling main entry com.android.commands.pm.Pm
,D/AmoledAdjustTimer( 2420): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
,D/PackageManager( 2420): START PACKAGE DELETE: observer{1147824120}
D/PackageManager( 2420): pkg{<packageName>}
D/PackageManager( 2420): user{0}
,D/PackageManager( 2420): deletePackageAsUser : uid = 2000 userId = 0,
,E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD,
E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection...,
,D/ApplicationPolicy( 2420): getApplicationUninstallationEnabled,
,D/PackageManager( 2420): [MSG] DELETE_PACKAGE_AS_USER,
D/ApplicationPolicy( 2420): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2420): deletePackageX- pkg:com.test.thalitest, userId:0
,D/AndroidRuntime( 8032): Calling main entry com.android.commands.pm.Pm
D/AndroidRuntime( 8030): Calling main entry com.android.commands.pm.Pm
D/AndroidRuntime( 8036): Calling main entry com.android.commands.pm.Pm
,D/AndroidRuntime( 8038): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2420): START PACKAGE DELETE: observer{1122012800}
D/PackageManager( 2420): pkg{<packageName>}
D/PackageManager( 2420): user{0}
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
D/PackageManager( 2420): deletePackageAsUser : uid = 2000 userId = 0
,D/PackageManager( 2420): START PACKAGE DELETE: observer{1123097088}
D/PackageManager( 2420): pkg{<packageName>}
D/PackageManager( 2420): user{0}
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
D/PackageManager( 2420): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager( 2420): START PACKAGE DELETE: observer{1143011152}
D/PackageManager( 2420): pkg{<packageName>}
D/PackageManager( 2420): user{0}
,D/PackageManager( 2420): START PACKAGE DELETE: observer{1121625096}
D/PackageManager( 2420): pkg{<packageName>}
D/PackageManager( 2420): user{0}
,D/PackageManager( 2420): START PACKAGE DELETE: observer{1122436296}
D/PackageManager( 2420): pkg{<packageName>}
D/PackageManager( 2420): user{0}
,D/PackageManager( 2420): deletePackageAsUser : uid = 2000 userId = 0
,D/PackageManager( 2420): deletePackageAsUser : uid = 2000 userId = 0
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "smsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/PackageManager( 2420): deletePackageAsUser : uid = 2000 userId = 0
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mmsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/Babel   ( 7352): connection state changed from CONNECTED to DISCONNECTED
,D/PackageManager( 2420): !@killApplicatoin: 10448, uninstall pkg
,I/ActivityManager( 2420): Killing 6875:com.test.thalitest/u0a448 (adj 0): stop com.test.thalitest
,W/InputDispatcher( 2420): channel ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher( 2420): channel ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher( 2420): Attempted to unregister already unregistered input channel
,I/WindowState( 2420): WIN DEATH: Window{435cb6d0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1920): id=22 Removed NainActivit (8/10)
I/SurfaceFlinger( 1920): id=22 Removed NainActivit (-2/10)
,D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 2420): Skipping PackageSetting{42700030 com.example.hello/10447} due to missing metadata
,W/ApplicationsProvider( 2956): Could not fetch usage stats
W/ApplicationsProvider( 2956): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2956): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2956): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2956): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2956): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2956): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2956): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2956): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2956): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 2956): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2956): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2956): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10448, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/iu.Environment( 3139): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 3139): num queued entries: 0
,I/iu.UploadsManager( 3139): num updated entries: 0
,I/iu.SyncManager( 3139): NEXT; no task
,D/dalvikvm( 5863): GC_EXPLICIT freed 244K, 25% free 10227K/13472K, paused 5ms+5ms, total 65ms
,D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10448, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/SurfaceFlinger( 1920): id=21 Removed EimLayer (6/9)
I/SurfaceFlinger( 1920): id=21 Removed EimLayer (-2/9)
I/SurfaceFlinger( 1920): id=20 Removed EimLayer (5/8)
I/SurfaceFlinger( 1920): id=20 Removed EimLayer (-2/8)
,I/FPMS_FingerprintManagerService( 2602): onReceive: android.intent.action.PACKAGE_REMOVED
,I/InputReader( 2420): Reconfiguring input devices.  changes=0x00000010
,D/dalvikvm( 2956): GC_EXPLICIT freed 1606K, 26% free 10081K/13456K, paused 11ms+8ms, total 114ms
,E/SamsungIME( 3050): mOCRHelper is null
,W/GeofencerStateMachine( 2734): Ignoring removeGeofence because network location is disabled.
,D/QuickConnect[1.1][2] ( 4995): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,V/WindowManager( 2420): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/Launcher( 2773): onRestart, Launcher: 1113567568
,D/Launcher( 2773): onStart, Launcher: 1113567568
,D/Launcher.HomeView( 2773): onStart
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "smsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SurfaceFlinger( 1920): id=25 createSurf (720x1280),1 flag=4, Mauncher
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
,D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/dalvikvm( 2420): GC_EXPLICIT freed 3354K, 54% free 24952K/53836K, paused 17ms+29ms, total 359ms
,D/dalvikvm( 2420): WAIT_FOR_CONCURRENT_GC blocked 164ms
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mmsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/RegisteredServicesCache( 2757): empty dynamic service
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/RCPManagerService( 2420): PackageReceiver onReceive()
,I/HarmonyEASService( 2420): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/dalvikvm( 2773): GC_CONCURRENT freed 6929K, 38% free 19108K/30376K, paused 15ms+9ms, total 143ms
,D/dalvikvm( 2773): WAIT_FOR_CONCURRENT_GC blocked 118ms
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "smsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/SPPClientService( 5408): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5408): [SystemStateMoniter] Current Time : 350518
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mms"
E/SPPClientService( 5408): [SystemStateMoniter] No Connect : true
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mmsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 2757): GC_CONCURRENT freed 1223K, 27% free 10597K/14348K, paused 30ms+10ms, total 146ms
,D/dalvikvm( 2757): WAIT_FOR_CONCURRENT_GC blocked 56ms
,E/SPPClientService( 5408): [[SystemStateMonitorService]] No Active Internet
,I/Icing.InternalIcingCorporaProvider( 5863): Updating corpora: A: com.google.android.gms, C: MAYBE
,D/FileShare-Server( 5878): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,I/SELinux ( 8106): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8106):  
,E/SPPClientService( 5408): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5408): [a] [ConnectionManager] Connection is already disconnected.
I/SELinux ( 8106): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8106):  
I/SELinux ( 8106):  
,I/SELinux ( 8106): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8106): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8106): >>>>> Normal User
,E/dalvikvm( 8106): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
D/dalvikvm( 7352): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7352): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7352): VFY: replacing opcode 0x62 at 0x000a
E/SELinux ( 8106): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 7352): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7352): VFY: unable to resolve instance field 46
,D/dalvikvm( 7352): VFY: replacing opcode 0x54 at 0x005f
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/dalvikvm( 7352): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7352): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7352): VFY: replacing opcode 0x62 at 0x0047
D/TimaKeyStoreProvider( 8106): in addTimaSignatureService
D/dalvikvm( 7352): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 7352): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 7352): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42b0e798
,E/SPPClientService( 5408): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/TimaKeyStoreProvider( 8106): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8106): Added TimaKesytore provider
D/dalvikvm( 7352): Added shared lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42b0e798
,D/dalvikvm( 7352): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42b0e798, skipping init
,D/dalvikvm( 7352): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x42b0e798
,D/dalvikvm( 7352): Added shared lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x42b0e798
,V/JNIHelp ( 7352): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/dalvikvm( 2420): GC_EXPLICIT freed 1224K, 54% free 24868K/53836K, paused 9ms+31ms, total 690ms
,D/dalvikvm( 8106): GC_CONCURRENT freed 3011K, 29% free 9559K/13460K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 8106): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/dalvikvm( 7352): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42b0e798
D/dalvikvm( 7352): Shared lib '/data/app-lib/com.google.android.gms-4/libgmscore.so' already loaded in same CL 0x42b0e798
,D/dalvikvm( 7352): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x42b0e798
,D/dalvikvm( 7352): Shared lib '/data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42b0e798
,D/BackupManagerService( 2420): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 2420): removePackageParticipantsLocked: uid=10448 #1
D/BezelQuickConnect( 5007): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED
D/BezelQuickConnect( 5007): BezelBroadcastReceiver - packageName : com.google.android.gms
,W/ApplicationsProvider( 2956): Could not fetch usage stats
W/ApplicationsProvider( 2956): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2956): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2956): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2956): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2956): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2956): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2956): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2956): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2956): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2956): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2956): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2956): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/PackageBroadcastService( 3139): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 3139): Null package name or gms related package.  Ignoreing.
I/ActivityManager( 2420): Killing 5715:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,D/PhoneStatusBar( 2582): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2420): tr p:2773,o:f
,D/StatusBarManagerService( 2420): semi p:2773,o:f
D/PhoneStatusBar( 2582): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
D/elm:14132( 7672): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,I/ProviderInstaller( 7352): Installed default security provider GmsCore_OpenSSL
,W/InputMethodManagerService( 2420): Got RemoteException sending setActive(false) notification to pid 6875 uid 10448
,I/Choreographer( 2773): Skipped 53 frames!  The application may be doing too much work on its main thread.
D/PackageManager( 2420): delete sourFile : 
,D/elm:14132( 7672): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14132( 7672): ElmAgentService : onCreate()
D/elm:14132( 7672): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14132( 7672): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 7672): MDMBridge.getInstance()
,D/elm:14132( 7672): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 7672): MDMBridge.getAllLicenseInfoFromSDK()
,I/SELinux ( 8125): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8125):  
,D/elm:14132( 7672): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
,D/elm:14132( 7672): ElmAgentService : onDestroy().
,D/PackageManager( 2420): delete native library directory: 
D/PackageManager( 2420): return delete result to caller: 1147824120
,D/PackageManager( 2420): returnCode: 1
D/AndroidRuntime( 8034): Shutting down VM
,D/dalvikvm( 8034): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 2ms+0ms, total 6ms
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Scheme: "sms"
,I/SELinux ( 8125): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8125):  
I/SELinux ( 8125):  
,I/SELinux ( 8125): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8125): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8125): >>>>> Normal User
,E/dalvikvm( 8125): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
,E/SELinux ( 8125): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 8125): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8125): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8125): Added TimaKesytore provider
,D/PackageManager( 2420): getApplicationInfo - Execution time: 126 ms
,D/PackageManager( 2420): getPackageUid - Execution time: 110 ms
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/Icing   ( 3139): updateResources: need to parse f{com.google.android.gms}
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "smsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mmsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 8125): GC_CONCURRENT freed 3009K, 29% free 9560K/13456K, paused 5ms+4ms, total 52ms
,D/dalvikvm( 8125): WAIT_FOR_CONCURRENT_GC blocked 42ms
,D/ApplicationPolicy( 2420): getApplicationUninstallationEnabled
,D/ApplicationPolicy( 2420): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService( 2420): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2420): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManager( 2420): !@killApplicatoin: 10448, uninstall pkg
F/PackageManager( 2420): Unable to backup package manager settings,  current changes will be lost at reboot
,E/SQLiteDatabase( 8125): Failed to open database '/data/data/com.sec.android.app.mss/databases/user.db'.
E/SQLiteDatabase( 8125): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8125): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8125): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8125): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8125): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8125): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8125): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8125): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8125): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8125): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8125): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8125): 	at com.sec.android.app.mss.b.h.b(Unknown Source)
E/SQLiteDatabase( 8125): 	at com.sec.android.app.mss.receiver.VerificationReceiver.onReceive(Unknown Source)
E/SQLiteDatabase( 8125): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 8125): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 8125): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 8125): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8125): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8125): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8125): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8125): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8125): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8125): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8125): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 8125): Shutting down VM
,W/dalvikvm( 8125): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 8125): FATAL EXCEPTION: main
E/AndroidRuntime( 8125): Process: com.sec.android.app.mss, PID: 8125
E/AndroidRuntime( 8125): java.lang.RuntimeException: Unable to start receiver com.sec.android.app.mss.receiver.VerificationReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8125): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 8125): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 8125): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 8125): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8125): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 8125): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 8125): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 8125): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 8125): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 8125): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 8125): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 8125): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8125): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 8125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 8125): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8125): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 8125): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 8125): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8125): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 8125): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 8125): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 8125): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 8125): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 8125): 	at com.sec.android.app.mss.b.h.b(Unknown Source)
E/AndroidRuntime( 8125): 	at com.sec.android.app.mss.receiver.VerificationReceiver.onReceive(Unknown Source)
E/AndroidRuntime( 8125): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 8125): 	... 10 more
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writeLPr(Settings.java:1876)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.removePackageDataLI(PackageManagerService.java:13205)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.deleteInstalledPackageLI(PackageManagerService.java:13330)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.deletePackageLI(PackageManagerService.java:13588)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.deletePackageX(PackageManagerService.java:13062)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.access$4900(PackageManagerService.java:252)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12966)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 22 more
,D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10448, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 8139): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8139):  
I/ActivityManager( 2420): Killing 7142:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SharedPreferencesImpl( 3139): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,I/SELinux ( 8139): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8139):  
I/SELinux ( 8139):  
,I/SELinux ( 8139): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8139): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 8139): >>>>> Normal User
,E/dalvikvm( 8139): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
,D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10448, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
E/SELinux ( 8139): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/FPMS_FingerprintManagerService( 2602): onReceive: android.intent.action.PACKAGE_REMOVED
,D/TimaKeyStoreProvider( 8139): in addTimaSignatureService
,I/InputReader( 2420): Reconfiguring input devices.  changes=0x00000010
,D/TimaKeyStoreProvider( 8139): Cannot add TimaSignature Service, License check Failed
,E/SamsungIME( 3050): mOCRHelper is null
,D/ActivityThread( 8139): Added TimaKesytore provider
,W/GeofencerStateMachine( 2734): Ignoring removeGeofence because network location is disabled.
,D/QuickConnect[1.1][2] ( 4995): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
,D/RCPManagerService( 2420): PackageReceiver onReceive()
E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop226.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 5 more
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop165.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "smsto"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop134.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/Process ( 8125): Sending signal. PID: 8125 SIG: 9
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop165.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,D/RegisteredServicesCache( 2757): empty dynamic service
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mmsto"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/ActivityManager( 2420): Process com.sec.android.app.mss (pid 8125) (adj 9) has died.
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/SharedPreferencesImpl( 3139): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop169.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,E/SQLiteLog( 7072): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog( 7072): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop170.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "smsto"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/Icing   ( 3139): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop166.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop168.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mmsto"
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
D/dalvikvm( 8139): GC_CONCURRENT freed 2988K, 29% free 9576K/13456K, paused 26ms+3ms, total 70ms
D/dalvikvm( 8139): WAIT_FOR_CONCURRENT_GC blocked 44ms
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop134.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,I/PCWCLIENTTRACE_PushUtil( 6101): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6101): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6101): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6101): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/SharedPreferencesImpl( 3139): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,I/SELinux ( 8154): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8154):  
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SharedPreferencesImpl( 3139): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,I/SELinux ( 8154): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8154):  
I/SELinux ( 8154):  
,I/SELinux ( 8154): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8154): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8154): >>>>> Normal User
,E/dalvikvm( 8154): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
,E/SELinux ( 8154): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/Icing   ( 3139): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,E/SharedPreferencesImpl( 3139): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml.bak
,D/TimaKeyStoreProvider( 8154): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8154): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8154): Added TimaKesytore provider
,E/SQLiteLog( 5863): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/Icing.InternalIcingCorporaProvider( 5863): Exception thrown from registerCorpora
E/Icing.InternalIcingCorporaProvider( 5863): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/Icing.InternalIcingCorporaProvider( 5863): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.executeWithConnection(AppDataSearchProviderBase.java:297)
E/Icing.InternalIcingCorporaProvider( 5863): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider.registerCorpora(AppDataSearchProvider.java:171)
E/Icing.InternalIcingCorporaProvider( 5863): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.safeRegisterCorpora(InternalIcingCorporaProvider.java:376)
E/Icing.InternalIcingCorporaProvider( 5863): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.registerCorpora(InternalIcingCorporaProvider.java:330)
E/Icing.InternalIcingCorporaProvider( 5863): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:273)
E/Icing.InternalIcingCorporaProvider( 5863): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/Icing.InternalIcingCorporaProvider( 5863): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/Icing.InternalIcingCorporaProvider( 5863): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/Icing.InternalIcingCorporaProvider( 5863): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/Icing.InternalIcingCorporaProvider( 5863): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/Icing.InternalIcingCorporaProvider( 5863): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/Icing.InternalIcingCorporaProvider( 5863): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/Icing.InternalIcingCorporaProvider( 5863): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Icing.InternalIcingCorporaProvider( 5863): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Icing.InternalIcingCorporaProvider( 5863): 	at android.os.Looper.loop(Looper.java:146)
E/Icing.InternalIcingCorporaProvider( 5863): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/Icing.InternalIcingCorporaProvider( 5863): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/Icing.InternalIcingCorporaProvider( 5863): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/Icing.InternalIcingCorporaProvider( 5863): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/Icing.InternalIcingCorporaProvider( 5863): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/Icing.InternalIcingCorporaProvider( 5863): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/Icing.InternalIcingCorporaProvider( 5863): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/Icing.InternalIcingCorporaProvider( 5863): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/Icing.InternalIcingCorporaProvider( 5863): 	at com.google.android.gms.appdatasearch.util.AppDataSearchDbOpenHelperBase.cleanSequenceTable(AppDataSearchDbOpenHelperBase.java:352)
E/Icing.InternalIcingCorporaProvider( 5863): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.requestIndexingIfRequired(AppDataSearchProviderBase.java:321)
E/Icing.InternalIcingCorporaProvider( 5863): 	at com.google.android.gms.ap,pdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:165)
E/Icing.InternalIcingCorporaProvider( 5863): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:156)
E/Icing.InternalIcingCorporaProvider( 5863): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.executeWithConnection(AppDataSearchProviderBase.java:295)
E/Icing.InternalIcingCorporaProvider( 5863): 	... 15 more
W/Icing.InternalIcingCorporaProvider( 5863): Corpora registration failed
E/SQLiteLog( 5863): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 5863): threadid=16: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 5863): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 5863): Process: com.google.android.googlequicksearchbox:search, PID: 5863
E/AndroidRuntime( 5863): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 5863): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 5863): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 5863): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 5863): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 5863): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 5863): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 5863): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:171)
E/AndroidRuntime( 5863): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 5863): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
E/AndroidRuntime( 5863): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 5863): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 5863): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 5863): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 5863): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 5863): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 5863): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 5863): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5863): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5863): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 5863): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/Icing   ( 3139): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,I/Process ( 5863): Sending signal. PID: 5863 SIG: 9
E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop235.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 5 more
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 2420): Process com.google.android.googlequicksearchbox:search (pid 5863) (adj 5) has died.
,D/dalvikvm( 8154): GC_CONCURRENT freed 3000K, 29% free 9573K/13460K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 8154): WAIT_FOR_CONCURRENT_GC blocked 21ms
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 2420): GC_EXPLICIT freed 2241K, 54% free 25029K/53836K, paused 12ms+29ms, total 445ms
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/PackageManager( 2420): Package source /data/app/com.test.thalitest-1.apk does not exist.
D/PackageManager( 2420): Couldn't delete sourFile : 
W/PackageManager( 2420): Couldn't delete native library directory /data/app-lib/com.test.thalitest-1
,D/AndroidRuntime( 8028): Shutting down VM
D/PackageManager( 2420): return delete result to caller: 1122012800
,D/PackageManager( 2420): returnCode: 1
D/dalvikvm( 8028): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 0ms+0ms, total 4ms
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "sms"
F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:558)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 24 more
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "smsto"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:559)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 24 more
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/PackageManager( 2420):   Scheme: "mms"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:560)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 24 more
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mmsto"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:561)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 24 more
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ApplicationPolicy( 2420): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2420): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService( 2420): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2420): [MSG] DELETE_PACKAGE_AS_USER
,F/PackageManager( 2420): Unable to backup package manager settings,  current changes will be lost at reboot
D/PackageManager( 2420): !@killApplicatoin: 10448, uninstall pkg
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writeLPr(Settings.java:1876)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.removePackageDataLI(PackageManagerService.java:13205)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.deleteInstalledPackageLI(PackageManagerService.java:13330)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.deletePackageLI(PackageManagerService.java:13588)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.deletePackageX(PackageManagerService.java:13062)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.access$4900(PackageManagerService.java:252)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12966)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 22 more
,D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10448, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
V/GmsNetworkLocationProvi( 2734): DISABLE
,I/GCoreNlp( 2734): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10448, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/FPMS_FingerprintManagerService( 2602): onReceive: android.intent.action.PACKAGE_REMOVED
,I/InputReader( 2420): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 3050): mOCRHelper is null
,D/QuickConnect[1.1][2] ( 4995): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop168.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "smsto"
F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop171.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms"
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop207.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mmsto"
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop168.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
D/RegisteredServicesCache( 2757): empty dynamic service
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "sms"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop168.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "smsto"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop169.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop17.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mmsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop169.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,W/AtomicFile( 2420): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl( 2420): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,D/EnterpriseDeviceManagerService( 2420): Package has changed for user 0
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/AlarmManager( 2420): waitForAlarm result :8
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 2420): GC_EXPLICIT freed 2200K, 54% free 24851K/53836K, paused 10ms+23ms, total 290ms
,D/AndroidRuntime( 8030): Shutting down VM
W/PackageManager( 2420): Package source /data/app/com.test.thalitest-1.apk does not exist.
D/PackageManager( 2420): Couldn't delete sourFile : 
W/PackageManager( 2420): Couldn't delete native library directory /data/app-lib/com.test.thalitest-1
D/PackageManager( 2420): return delete result to caller: 1123097088
,D/PackageManager( 2420): returnCode: 1
D/dalvikvm( 8030): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+0ms, total 4ms
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:558)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 24 more
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "smsto"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:559)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 24 more
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:560)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 24 more
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mmsto"
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
D/ApplicationPolicy( 2420): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2420): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService( 2420): deletePackageX- pkg:com.test.thalitest, userId:0
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:561)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 24 more
D/PackageManager( 2420): [MSG] DELETE_PACKAGE_AS_USER
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 2420): !@killApplicatoin: 10448, uninstall pkg
,F/PackageManager( 2420): Unable to backup package manager settings,  current changes will be lost at reboot
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writeLPr(Settings.java:1876)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.removePackageDataLI(PackageManagerService.java:13205)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.deleteInstalledPackageLI(PackageManagerService.java:13330)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.deletePackageLI(PackageManagerService.java:13588)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.deletePackageX(PackageManagerService.java:13062)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.access$4900(PackageManagerService.java:252)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12966)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 22 more
,D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10448, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/FPMS_FingerprintManagerService( 2602): onReceive: android.intent.action.PACKAGE_REMOVED
,D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10448, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SamsungIME( 3050): mOCRHelper is null
D/QuickConnect[1.1][2] ( 4995): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
,I/InputReader( 2420): Reconfiguring input devices.  changes=0x00000010
,D/RegisteredServicesCache( 2757): empty dynamic service
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop170.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "smsto"
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop207.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms"
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop171.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mmsto"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop166.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop168.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "smsto"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop169.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop164.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mmsto"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop168.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector( 2420): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2420): clearDefaults: com.test.thalitest
,D/dalvikvm( 2420): GC_EXPLICIT freed 1786K, 54% free 24927K/53836K, paused 9ms+21ms, total 276ms
,D/AndroidRuntime( 8038): Shutting down VM
W/PackageManager( 2420): Package source /data/app/com.test.thalitest-1.apk does not exist.
D/PackageManager( 2420): Couldn't delete sourFile : 
W/PackageManager( 2420): Couldn't delete native library directory /data/app-lib/com.test.thalitest-1
D/PackageManager( 2420): return delete result to caller: 1143011152
D/PackageManager( 2420): returnCode: 1
,D/dalvikvm( 8038): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+0ms, total 5ms
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:558)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 24 more
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "smsto"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:559)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 24 more
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms"
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:560)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 24 more
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mmsto"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:561)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 24 more
D/ApplicationPolicy( 2420): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2420): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService( 2420): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2420): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManager( 2420): !@killApplicatoin: 10448, uninstall pkg
,F/PackageManager( 2420): Unable to backup package manager settings,  current changes will be lost at reboot
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writeLPr(Settings.java:1876)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.removePackageDataLI(PackageManagerService.java:13205)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.deleteInstalledPackageLI(PackageManagerService.java:13330)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.deletePackageLI(PackageManagerService.java:13588)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.deletePackageX(PackageManagerService.java:13062)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.access$4900(PackageManagerService.java:252)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12966)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 22 more
D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10448, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10448, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/FPMS_FingerprintManagerService( 2602): onReceive: android.intent.action.PACKAGE_REMOVED
,W/System.err( 8154): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err( 8154): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 8154): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 8154): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err( 8154): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err( 8154): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
,W/System.err( 8154): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err( 8154): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err( 8154): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
,W/System.err( 8154): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err( 8154): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err( 8154): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
,W/System.err( 8154): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 8154): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 8154): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
,W/System.err( 8154): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 8154): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 8154): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 8154): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 8154): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 8154): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 8154): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 8154): 	at dalvik.system.NativeStart.main(Native Method)
,W/System.err( 8154): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
,W/System.err( 8154): 	at libcore.io.Posix.open(Native Method)
W/System.err( 8154): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 8154): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 8154): 	... 21 more
,E/SamsungIME( 3050): mOCRHelper is null
,I/InputReader( 2420): Reconfiguring input devices.  changes=0x00000010
,D/QuickConnect[1.1][2] ( 4995): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop164.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
D/RegisteredServicesCache( 2757): empty dynamic service
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "smsto"
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,W/AtomicFile( 2420): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
W/AppWidgetServiceImpl( 2420): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop134.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mmsto"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop168.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,D/GalaxyFinderApplication( 8154): [Slink platform] Version = 29011
,D/GalaxyFinderApplication( 8154): [Slink platform] use state of slink location service is [false] to [true]
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop171.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "smsto",
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 8174): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8174):  
F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
D/dalvikvm( 2757): GC_CONCURRENT freed 1999K, 26% free 10646K/14348K, paused 3ms+5ms, total 38ms
,D/dalvikvm( 2757): WAIT_FOR_CONCURRENT_GC blocked 20ms,
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
,E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): ,	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): ,	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
,E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	,at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	,at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,D/dalvikvm( 2753): GC_CONCURRENT freed 1887K, 28% free 10365K/14368K, paused 12ms+8ms, total 158ms,
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms",
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot,
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf,
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop207.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218),
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	,at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	,at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065),
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method),
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :,
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mmsto"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/SELinux ( 8174): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8174):  
I/SELinux ( 8174):  
I/SELinux ( 8174): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SQLiteLog( 7481): (3850) statement aborts at 35: [DELETE FROM app_registry WHERE package_name=? AND plugin_id=? AND sync_status != 170004 AND sync_status = 170002] disk I/O error,
W/dalvikvm( 7481): threadid=12: thread exiting with uncaught exception (group=0x4180ac08)
E/SELinux ( 8174): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 8174): >>>>> Normal User
E/dalvikvm( 8174): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10043 ]
,E/SELinux ( 8174): [DEBUG] seapp_context_lookup: seinfoCategory = samsung,
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop207.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409),
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	,at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395),
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): ,	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	,at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110),
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
E/AndroidRuntime( 7481): FATAL EXCEPTION: IntentService[HandleAppDataService]
,E/AndroidRuntime( 7481): Process: com.sec.android.app.shealth, PID: 7481
E/AndroidRuntime( 7481): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 7481): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 7481): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 7481): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 7481): ,	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 7481): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 7481): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericDelete(BaseContentProvider.java:486)
E/AndroidRuntime( 7481): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.delete(BaseContentProvider.java:441)
E/AndroidRuntime( 7481): 	,at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 7481): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 7481): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.deleteAppRegistryData(AppRegistryDbManagerWithProvider.java:459)
E/AndroidRuntime( 7481): 	at com.sec.android.app.shealth.service.HandleAppDataService.onHandleIntent(HandleAppDataService.java:56)
E/AndroidRuntime( 7481): ,	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7481): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7481): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7481): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/TimaKeyStoreProvider( 8174): in addTimaSignatureService,
E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop275.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	,at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546),
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	,... 5 more
I/Process ( 7481): Sending signal. PID: 7481 SIG: 9
,D/TimaKeyStoreProvider( 8174): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8174): Added TimaKesytore provider
,D/dalvikvm( 3919): GC_CONCURRENT freed 2496K, 26% free 10101K/13484K, paused 25ms+6ms, total 227ms
,I/ActivityManager( 2420): Process com.sec.android.app.shealth (pid 7481) (adj 5) has died.
,D/EnterpriseDeviceManagerService( 2420): Package has changed for user 0
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 8174): GC_CONCURRENT freed 2997K, 29% free 9569K/13452K, paused 4ms+3ms, total 38ms
,D/dalvikvm( 8174): WAIT_FOR_CONCURRENT_GC blocked 33ms
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 2420): GC_EXPLICIT freed 1977K, 54% free 24917K/53836K, paused 9ms+25ms, total 451ms
W/PackageManager( 2420): Package source /data/app/com.test.thalitest-1.apk does not exist.
D/PackageManager( 2420): Couldn't delete sourFile : 
W/PackageManager( 2420): Couldn't delete native library directory /data/app-lib/com.test.thalitest-1
D/PackageManager( 2420): return delete result to caller: 1121625096
D/PackageManager( 2420): returnCode: 1
,D/AndroidRuntime( 8032): Shutting down VM
,D/dalvikvm( 8032): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 0ms+0ms, total 4ms
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:558)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 24 more
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :,
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "smsto"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms"
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:559)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 24 more
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
E/SQLiteDatabase( 8174): Failed to open database '/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db'.
E/SQLiteDatabase( 8174): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8174): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8174): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8174): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:429)
E/SQLiteDatabase( 8174): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 8174): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 8174): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 8174): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 8174): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 8174): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 8174): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 8174): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8174): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8174): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8174): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8174): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8174): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8174): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8174): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 8174): Shutting down VM
,W/dalvikvm( 8174): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 8174): FATAL EXCEPTION: main
E/AndroidRuntime( 8174): Process: com.samsung.android.sdk.samsunglink, PID: 8174
E/AndroidRuntime( 8174): java.lang.RuntimeException: Unable to get provider com.mfluent.asp.datamodel.ASPMediaStoreProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8174): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 8174): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 8174): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 8174): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8174): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 8174): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8174): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 8174): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 8174): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 8174): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 8174): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 8174): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 8174): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 8174): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8174): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8174): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 8174): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 8174): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8174): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8174): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8174): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 8174): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 8174): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8174): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 8174): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 8174): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 8174): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 8174): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:429)
E/AndroidRuntime( 8174): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 8174): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 8174): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 8174): 	... 12 more
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStr,eam.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:560)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 24 more
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mmsto"
F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop279.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 5 more
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:561)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 24 more
D/ApplicationPolicy( 2420): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2420): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2420): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2420): [MSG] DELETE_PACKAGE_AS_USER
I/Process ( 8174): Sending signal. PID: 8174 SIG: 9
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SA      ( 6263): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
I/SA      ( 6263): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
I/ActivityManager( 2420): Killing 6308:com.samsung.android.magazine.service/u0a110 (adj 15): empty #43
F/PackageManager( 2420): Unable to backup package manager settings,  current changes will be lost at reboot
D/PackageManager( 2420): !@killApplicatoin: 10448, uninstall pkg
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writeLPr(Settings.java:1876)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.removePackageDataLI(PackageManagerService.java:13205)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.deleteInstalledPackageLI(PackageManagerService.java:13330)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.deletePackageLI(PackageManagerService.java:13588)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.deletePackageX(PackageManagerService.java:13062)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.access$4900(PackageManagerService.java:252)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12966)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 22 more
D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10448, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/ActivityManager( 2420): Process com.samsung.android.sdk.samsunglink (pid 8174) (adj 9) has died.
,D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10448, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,E/SharedPreferencesImpl( 3561): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,I/FPMS_FingerprintManagerService( 2602): onReceive: android.intent.action.PACKAGE_REMOVED
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SamsungIME( 3050): mOCRHelper is null
,D/QuickConnect[1.1][2] ( 4995): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
,I/InputReader( 2420): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop164.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "smsto"
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop166.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,I/SELinux ( 8192): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8192):  
,D/RegisteredServicesCache( 2757): empty dynamic service
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms"
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop171.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mmsto"
F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/SELinux ( 8192): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8192):  
I/SELinux ( 8192):  
I/SELinux ( 8192): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 8192): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 8192): >>>>> Normal User
E/dalvikvm( 8192): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 8192): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop164.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 8192): in addTimaSignatureService
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop207.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
D/TimaKeyStoreProvider( 8192): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 8192): Added TimaKesytore provider
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "smsto"
F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop169.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms"
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop166.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mmsto"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop164.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 2420): GC_EXPLICIT freed 1733K, 54% free 25035K/53836K, paused 9ms+26ms, total 321ms
W/PackageManager( 2420): Package source /data/app/com.test.thalitest-1.apk does not exist.
D/PackageManager( 2420): Couldn't delete sourFile : 
W/PackageManager( 2420): Couldn't delete native library directory /data/app-lib/com.test.thalitest-1
D/PackageManager( 2420): return delete result to caller: 1122436296
,D/PackageManager( 2420): returnCode: 1
D/AndroidRuntime( 8036): Shutting down VM
,D/dalvikvm( 8036): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+1ms, total 4ms
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector( 2420): onPackageRemoved : com.test.thalitest
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
D/UsbSettingsManager( 2420): clearDefaults: com.test.thalitest
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
D/dalvikvm( 8192): GC_CONCURRENT freed 2983K, 29% free 9583K/13456K, paused 2ms+2ms, total 31ms
D/dalvikvm( 8192): WAIT_FOR_CONCURRENT_GC blocked 27ms
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:558)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 24 more
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "smsto"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:559)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 24 more
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mms"
D/AndroidRuntime( 2420): Shutting down VM
,W/dalvikvm( 2420): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/AndroidRuntime( 2420): !@*** FATAL EXCEPTION IN SYSTEM PROCESS: main
E/AndroidRuntime( 2420): java.lang.RuntimeException: Error receiving broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) } in com.android.server.enterprise.keystore.TimaKeystoreService$KeystoreReceiver@42d90718
E/AndroidRuntime( 2420): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:782)
E/AndroidRuntime( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2420): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:2178)
E/AndroidRuntime( 2420): 	at com.android.server.SystemServer.main(SystemServer.java:2317)
E/AndroidRuntime( 2420): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2420): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2420): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 2420): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 2420): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2420): Caused by: android.database.sqlite.SQLiteDatabaseLockedException: database is locked (code 5)
E/AndroidRuntime( 2420): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2420): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 2420): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2420): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2420): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 2420): 	at com.android.server.enterprise.storage.EdmStorageProviderBase.delete(EdmStorageProviderBase.java:471)
E/AndroidRuntime( 2420): 	at com.android.server.enterprise.storage.EdmStorageProviderBase.deleteDataByFields(EdmStorageProviderBase.java:1447)
E/AndroidRuntime( 2420): 	at com.android.server.enterprise.storage.EdmStorageProvider.deleteDataByFields(EdmStorageProvider.java:445)
E/AndroidRuntime( 2420): 	at com.android.server.enterprise.keystore.TimaKeystoreService.deletePackageRecord(TimaKeystoreService.java:348)
E/AndroidRuntime( 2420): 	at com.android.server.enterprise.keystore.TimaKeystoreService.access$300(TimaKeystoreService.java:72)
E/AndroidRuntime( 2420): 	at com.android.server.enterprise.keystore.TimaKeystoreService$KeystoreReceiver.onReceive(TimaKeystoreService.java:294)
E/AndroidRuntime( 2420): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:772)
E/AndroidRuntime( 2420): 	... 10 more
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:560)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 24 more
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mmsto"
,F/PackageManager( 2420): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2420): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:561)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2420): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2420): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2420): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2420): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 24 more
,I/Icing.InternalIcingCorporaProvider( 8192): Updating corpora: A: com.google.android.gms, C: MAYBE
,I/SELinux ( 8208): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8208):  
,D/EnterpriseDeviceManagerService( 2420): Package has changed for user 0
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 9% free 9502K/10436K, paused 3ms+4ms, total 35ms,
,D/LocationManagerService( 2420): getProviders()=[passive],
I/SELinux ( 8208): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8208):  
I/SELinux ( 8208):  
,I/SELinux ( 8208): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 8208): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
E/dalvikvm( 8208): >>>>> Normal User
,E/dalvikvm( 8208): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ],
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SELinux ( 8208): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 9% free 9502K/10436K, paused 3ms+4ms, total 30ms,
,D/TimaKeyStoreProvider( 8208): in addTimaSignatureService,
D/TimaKeyStoreProvider( 8208): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 8208): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 9% free 9502K/10436K, paused 2ms+4ms, total 34ms
,D/dalvikvm( 8208): GC_CONCURRENT freed 3004K, 29% free 9569K/13460K, paused 2ms+2ms, total 29ms,
,D/dalvikvm( 8208): WAIT_FOR_CONCURRENT_GC blocked 26ms
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,E/Icing   ( 3139): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system),
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,D/UserAnalysis.PlaceProvider( 8208): Create SecureDbHelper,
,E/SharedPreferencesImpl( 3139): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak,
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Icing   ( 3139): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 8208): Create SecureDbHelper
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/SQLiteDatabase( 8208): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 8208): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8208): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 8208): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 8208): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteDatabase( 8208): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 8208): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 8208): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 8208): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 8208): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8208): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8208): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8208): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8208): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8208): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8208): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8208): 	at dalvik.system.NativeStart.main(Native Method)
E/SharedPreferencesImpl( 3139): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,E/SQLiteOpenHelper( 8208): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 8208): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 8208): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 8208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 8208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 8208): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 8208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 8208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 8208): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 8208): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 8208): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 8208): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 8208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 8208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 8208): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 8208): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 8208): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 8208): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteOpenHelper( 8208): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 8208): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 8208): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 8208): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 8208): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 8208): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 8208): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 8208): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 8208): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 8208): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 8208): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 8208): 	at dalvik.system.NativeStart.main(Native Method)
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/SQLiteOpenHelper( 8208): Opened privacy in read-only mode
,I/CrashAnrDetector( 2420): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2420): clearDefaults: com.test.thalitest
,E/SQLiteDatabase( 8208): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 8208): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8208): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 8208): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 8208): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteDatabase( 8208): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 8208): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 8208): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 8208): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 8208): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8208): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8208): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8208): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8208): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8208): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8208): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8208): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 8208): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 8208): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 8208): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 8208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 8208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 8208): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 8208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 8208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteO,penHelper( 8208): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 8208): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 8208): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 8208): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 8208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 8208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 8208): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 8208): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 8208): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 8208): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteOpenHelper( 8208): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 8208): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 8208): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 8208): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 8208): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 8208): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 8208): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 8208): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 8208): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 8208): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 8208): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 8208): 	at dalvik.system.NativeStart.main(Native Method)
,E/SharedPreferencesImpl( 3139): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,W/SQLiteOpenHelper( 8208): Opened privacy in read-only mode
,E/Icing   ( 3139): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,E/SQLiteDatabase( 8208): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 8208): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8208): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8208): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8208): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
E/SQLiteDatabase( 8208): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 8208): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 8208): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 8208): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 8208): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8208): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8208): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8208): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8208): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8208): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8208): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8208): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 8208): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 8208): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 8208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 8208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 8208): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 8208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
,W/System.err( 8208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 8208): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 8208): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 8208): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 8208): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
,W/System.err( 8208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 8208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 8208): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
,W/System.err( 8208): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 8208): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
W/System.err( 8208): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
W/System.err( 8208): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
,W/System.err( 8208): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 8208): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 8208): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 8208): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 8208): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 8208): 	at java.lang.reflect.Method.invokeNative(Native Method)
,W/System.err( 8208): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 8208): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 8208): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 8208): 	at dalvik.system.NativeStart.main(Native Method)
,D/EnterpriseDeviceManagerService( 2420): Package has changed for user 0
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 8227): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 8227):  
,E/SharedPreferencesImpl( 3139): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak,
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Icing   ( 3139): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)

```
