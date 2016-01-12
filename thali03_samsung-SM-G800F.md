#### Test 55613145ac448d4_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/AmoledAdjustTimer( 3236): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
D/SSRMv2:SIOP( 3236): SIOP:: AP = 310, Delta = 0
--------- beginning of /dev/log/main
D/AndroidRuntime( 7218): 
D/AndroidRuntime( 7218): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7218): CheckJNI is OFF
D/AndroidRuntime( 7218): setted country_code = Poland
D/AndroidRuntime( 7218): setted countryiso_code = PL
D/AndroidRuntime( 7218): setted sales_code = PLS
D/AndroidRuntime( 7218): readGMSProperty: start
D/AndroidRuntime( 7218): readGMSProperty: already setted!!
D/AndroidRuntime( 7218): readGMSProperty: end
D/AndroidRuntime( 7218): addProductProperty: start
D/dalvikvm( 7218): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7218): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7218): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7218): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7218): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7218): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7218): failed to load memtrack module: -2
D/dalvikvm( 7218): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7218): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 3236): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 3236): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 3236  pkgName : ACTIVITY_RESUME_BOOSTER@4
I/SurfaceFlinger( 1919): id=26 createSurf (16x16),-1 flag=20004, EimLayer
W/ActivityManager( 3236): mDVFSHelper.acquire()
I/SurfaceFlinger( 1919): id=27 createSurf (16x16),-1 flag=20004, EimLayer
I/SELinux ( 7247): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7247):  
D/PointerIcon( 3236): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3236): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3236): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3236): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7218): Shutting down VM
D/dalvikvm( 7218): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 7247): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7247):  
I/SELinux ( 7247):  
I/SELinux ( 7247): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7247): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7247): >>>>> Normal User
E/dalvikvm( 7247): >>>>> com.test.thalitest [ userId:0 | appId:10188 ]
E/SELinux ( 7247): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7247): in addTimaSignatureService
D/TimaKeyStoreProvider( 7247): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7247): Added TimaKesytore provider
V/WindowManager( 3236): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SQLiteSecureOpenHelper( 4435): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4435): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1919): id=18 Removed Mauncher (8/10)
I/SurfaceFlinger( 1919): id=18 Removed Mauncher (-2/10)
D/Launcher( 3692): onTrimMemory. Level: 20
D/dalvikvm( 7247): GC_CONCURRENT freed 3003K, 33% free 9562K/14120K, paused 3ms+1ms, total 19ms
D/dalvikvm( 7247): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7247): Binding Chromium to the background looper Looper (main, tid 1) {422d71f8}
I/chromium( 7247): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7247): Initializing chromium process, renderers=0
W/chromium( 7247): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7247): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7247): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7247): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7247): Mali API Version : 401
,I/Mali    ( 7247): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7247): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7247): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7247): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7247): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7247): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7247): VFY: replacing opcode 0x6e at 0x0008
,D/StatusBarManagerService( 3236): tr p:7247,o:f
D/PhoneStatusBar( 3500): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
W/dalvikvm( 7247): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7247): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7247): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7247): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 7247): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7247): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7247): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7247): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7247): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7247): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7247): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7247): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7247): CordovaWebView is running on device made by: samsung
,D/StatusBarManagerService( 3236): semi p:7247,o:f
D/PhoneStatusBar( 3500): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/SurfaceFlinger( 1919): id=28 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 3236): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 3236): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3236): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3236): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3236): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 3236): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7247): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7247): Enabling debug mode 0
,W/AwContents( 7247): nativeOnDraw failed; clearing to background color.,
W/ContextImpl( 3236): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7247): showStatusIcon on inactive InputConnection,
,D/CustomFrequencyManagerService( 3236): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 3236  tag : ACTIVITY_RESUME_BOOSTER@4,
,W/ActivityManager( 3236): mDVFSHelper.release(),
,D/CustomFrequencyManagerService( 3236): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 3236  pkgName : ACTIVITY_RESUME_BOOSTER@8,
,D/JsMessageQueue( 7247): Set native->JS mode to OnlineEventsBridgeMode,
,D/dalvikvm( 7247): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422cf3e0,
D/dalvikvm( 7247): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422cf3e0
D/jxcore_app_log( 7247): JniHelper::setJavaVM(0x41735220), pthread_self() = 2030983088
D/JX-Cordova( 7247): jxcore cordova android initializing
,D/dalvikvm( 7247): GC_CONCURRENT freed 1294K, 21% free 11341K/14184K, paused 3ms+2ms, total 25ms,
D/dalvikvm( 7247): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 7247): WAIT_FOR_CONCURRENT_GC blocked 14ms,
,D/dalvikvm( 7247): GC_CONCURRENT freed 1924K, 19% free 14960K/18448K, paused 3ms+2ms, total 43ms,
D/dalvikvm( 7247): WAIT_FOR_CONCURRENT_GC blocked 21ms
W/PluginManager( 7247): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 21ms. Plugin should use CordovaInterface.getThreadPool().
,D/dalvikvm( 7247): WAIT_FOR_CONCURRENT_GC blocked 29ms,
,D/CustomFrequencyManagerService( 3236): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 3236  tag : ACTIVITY_RESUME_BOOSTER@8,
,D/dalvikvm( 7247): GC_FOR_ALLOC freed 5356K, 31% free 16246K/23364K, paused 50ms, total 52ms,
,D/dalvikvm( 7247): GC_CONCURRENT freed 6717K, 32% free 17699K/25988K, paused 3ms+10ms, total 70ms,
D/dalvikvm( 7247): WAIT_FOR_CONCURRENT_GC blocked 29ms,
,D/dalvikvm( 7247): WAIT_FOR_CONCURRENT_GC blocked 41ms
,D/dalvikvm( 7247): GC_FOR_ALLOC freed 1296K, 33% free 17492K/25988K, paused 52ms, total 53ms,
,I/dalvikvm-heap( 7247): Grow heap (frag case) to 22.111MB for 3688532-byte allocation,
,D/dalvikvm( 7247): GC_FOR_ALLOC freed 2413K, 37% free 18681K/29592K, paused 53ms, total 53ms,
,W/jxcore-log( 7247): Initializing JXcore engine,
,W/jxcore-log( 7247): JXcore engine is ready,
,W/jxcore-log( 7247): Starting JXcore engine
,W/jxcore-log( 7247): Platform android
W/jxcore-log( 7247): 
,W/jxcore-log( 7247): Process ARCH arm
W/jxcore-log( 7247): 
,I/jxcore-log( 7247): JXcore Cordova bridge is ready!
I/jxcore-log( 7247): 
,W/jxcore-log( 7247): JXcore engine is started
,I/chromium( 7247): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7247): Toggling radios to true,
I/jxcore-log( 7247): 
,W/ActivityManager( 3236): Permission Denial: getCurrentUser() from pid=7247, uid=10188 requires android.permission.INTERACT_ACROSS_USERS,
,W/BluetoothManagerService( 3236): Failed getting userId using ActivityManagerNative,
W/BluetoothManagerService( 3236): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7247, uid=10188 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 3236): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/BluetoothManagerService( 3236): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:620)
W/BluetoothManagerService( 3236): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService( 3236): 	at android.os.Binder.execTransact(Binder.java:404)
W/BluetoothManagerService( 3236): 	at dalvik.system.NativeStart.run(Native Method)
,E/DevicePolicyManagerService( 3236): getAllowBluetoothMode - value retunrs : 2
,D/BluetoothManagerService( 3236): foregroundUser: 0,
,E/BluetoothManagerService( 3236): Package is exist.,
,I/WifiManager( 7247): packageName : com.test.thalitest
,I/WifiManager( 7247): setWifiEnabled : true
I/WifiService( 3236): setWifiEnabled: true pid=7247, uid=10188
,D/BluetoothAdapterState( 5437): CURRENT_STATE=OFF, MSG = USER_TURN_ON
I/BluetoothAdapterState( 5437): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 5437): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5437): updateAdapterState state is 11
,D/BluetoothAdapterService( 5437): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 5437): Autoconnection is available 
D/BluetoothAdapterService( 5437): updateAdapterState prevState = 10newState = 11
D/BtConfig.SecureMode( 5437): isSecureModeOn:false
,D/BtSettings.ProfileConfig( 5437): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/ActivityManager( 3236): Permission Denial: getCurrentUser() from pid=7247, uid=10188 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3236): Failed getting userId using ActivityManagerNative
W/WifiService( 3236): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7247, uid=10188 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3236): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 3236): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 3236): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 3236): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 3236): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 3236): 	at dalvik.system.NativeStart.run(Native Method)
W/BluetoothAdapterService( 5437): isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,D/BtSettings.ProfileConfig( 5437): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/InputMethodManagerService( 3236): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 3236): [BT Setting State] State =11
W/BluetoothAdapterService( 5437): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5437): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
I/WifiService( 3236): disconnect: pid=7247, uid=10188
D/PhoneApp( 3672): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 11
W/BluetoothAdapterService( 5437): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5437): getProfileSaveSetting: com.android.bluetooth.hid.HidService
E/WifiHW  ( 3236): ##################### set firmware type 0 #####################
I/SamsungIME( 3879): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
I/WifiHW  ( 3036): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
E/WifiHW  ( 3036): Cannot open "/data/.cid.info": No such file or directory
I/WifiHW  ( 3036): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
E/WifiHW  ( 3036): TEMP_FAILURE_RETRY complete
D/SoftapController( 3036): Softap fwReload - Ok
I/jxcore-log( 7247): Radios toggled
I/jxcore-log( 7247): 
W/BluetoothAdapterService( 5437): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5437): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
I/jxcore-log( 7247): My device name is: samsung-SM-G800F
I/jxcore-log( 7247): 
I/QuickConnect[1.1][2] ( 5410): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_ON
W/BluetoothAdapterService( 5437): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5437): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/CommandListener( 3036): Setting iface cfg
D/CommandListener( 3036): Trying to bring down wlan0
W/BluetoothAdapterService( 5437): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5437): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 5437): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5437): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5437): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5437): Unable to stop service com.android.bluetooth.gatt.GattService. Invalid state: 12
W/BluetoothAdapterService( 5437): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5437): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5437): Not skipping com.android.bluetooth.hfp.HeadsetService
D/WifiHW  ( 3236): Skip the update_ctrl_interface
D/WifiHW  ( 3236): Skip the update_ctrl_interface
,E/WifiHW  ( 3236): supplicant_name : p2p_supplicant
,D/BluetoothNotiBroadcastReceiver( 5946): onReceive
W/BluetoothAdapterService( 5437): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5437): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5437): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/WifiMonitor( 3236): startMonitoring(wlan0) with mConnected = false
D/STATUSBAR-NetworkController( 3500): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7296): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7296):  
,I/wpa_supplicant( 7295): wpa_supplicant v2.1-devel-4.4.22014-07-16/12:43:14
,I/wpa_supplicant( 7295): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 7295): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 7295): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 7295): getIMSI cannot open file
,E/wpa_supplicant( 7295): Interworking config: - SIM READ ERROR
,D/HeadsetService( 5437): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 5437): classInitNative: succeeds
D/HeadsetStateMachine( 5437): Version 1.5
,D/HeadsetStateMachine( 5437): make
,E/HeadsetStateMachine( 5437): # of Max HF connection is 2
,W/BluetoothAdapterService( 5437): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5437): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5437): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5437): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 5437): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5437): Not skipping com.android.bluetooth.hdp.HealthService
,D/QuickConnect[1.1][2] ( 5410): HeadsetProfile.onServiceConnected - Bluetooth service connected
W/BluetoothAdapterService( 5437): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5437): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5437): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5437): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5437): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5437): Not skipping com.android.bluetooth.map.BluetoothMapService
I/SELinux ( 7296): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7296):  
I/SELinux ( 7296):  
,I/SELinux ( 7296): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7296): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7296): >>>>> Normal User
,E/dalvikvm( 7296): >>>>> pl.k2.droidoaudioteka [ userId:0 | appId:10066 ]
,E/SELinux ( 7296): [DEBUG] seapp_context_lookup: seinfoCategory = default
,W/BluetoothAdapterService( 5437): check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 5437): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5437): Not skipping com.broadcom.bt.service.sap.SapService
,I/dalvikvm( 7296): Enabling JNI app bug workarounds for target SDK version 7...
,D/TimaKeyStoreProvider( 7296): in addTimaSignatureService
,I/BluetoothAdapterState( 5437): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid( 5437): get_profile_interface handsfree
,D/TimaKeyStoreProvider( 7296): Cannot add TimaSignature Service, License check Failed
,D/BluetoothAtMessage( 5437): createCMTIContentObservers
,D/ActivityThread( 7296): Added TimaKesytore provider
,D/HeadsetStateMachine( 5437): Enter Disconnected: -2
,E/HeadsetStateMachine( 5437): set to mRemoteBrsf = 0
,D/HeadsetStateMachine( 5437): map size, before remove : 0
D/HeadsetStateMachine( 5437): map size, after remove: 0
,D/HeadsetStateMachine( 5437): mNextConnectingDevice : null
D/BluetoothA2dp( 4435): Proxy object connected
,D/BluetoothA2dp( 5410): Proxy object connected
,D/BluetoothA2dp( 3236): Proxy object connected
,D/QuickConnect[1.1][2] ( 5410): A2dpProfile.onServiceConnected - Bluetooth service connected
,D/A2dpService( 5437): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 5437): classInitNative: succeeds
,D/A2dpStateMachine( 5437): make
,I/bluedroid( 5437): get_profile_interface a2dp
,I/GKI_LINUX( 5437): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 5437): Enter Disconnected: -2
,I/BluetoothAvrcpServiceJni( 5437): classInitNative: succeeds
,I/wpa_supplicant( 7295): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 7295): getIMSI cannot open file
E/wpa_supplicant( 7295): Interworking config: - SIM READ ERROR
I/bluedroid( 5437): get_profile_interface avrcp
,I/wpa_supplicant( 7295): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 7295): rfkill: Cannot open RFKILL control device
,D/MediaFocusControl( 3236): >>> registerRemoteControlDisplay
,I/BluetoothHidServiceJni( 5437): classInitNative: succeeds
,D/BluetoothInputDevice( 5410): Proxy object connected
D/HidService( 5437): Received start request. Starting profile...
,I/bluedroid( 5437): get_profile_interface hidhost
,D/HidService( 5437): setHidService(): set to: null
,D/QuickConnect[1.1][2] ( 5410): HidProfile.onServiceConnected - Bluetooth service connected
,I/BluetoothHealthServiceJni( 5437): classInitNative: succeeds
,D/HealthService( 5437): Received start request. Starting profile...
,I/bluedroid( 5437): get_profile_interface health
,I/BluetoothPanServiceJni( 5437): classInitNative(L105): succeeds
,D/BluetoothPan( 3236): BluetoothPAN Proxy object connected
,D/PanService( 5437): Received start request. Starting profile...
D/BluetoothPanServiceJni( 5437): initializeNative(L110): pan
,I/bluedroid( 5437): get_profile_interface pan
,D/BluetoothTethering( 3236): got CMD_CHANNEL_HALF_CONNECTED,
,D/BluetoothMapService( 5437): Received start request. Starting profile...,
D/dalvikvm( 7296): GC_CONCURRENT freed 3006K, 33% free 9563K/14120K, paused 3ms+2ms, total 25ms,
,D/dalvikvm( 7296): WAIT_FOR_CONCURRENT_GC blocked 12ms
,W/BluetoothMapMasInstance( 5437): mAccount : null,
,I/BluetoothSAPServiceJni( 5437): classInitNative(L204): succeeds,
D/SapService( 5437): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 5437): initializeNative(L209): sap
,I/bluedroid( 5437): get_profile_interface sap,
,D/HeadsetStateMachine( 5437): Try to query the phonestate on bind,
D/BluetoothPhoneService( 3672): handleMessage: 4
,D/HeadsetStateMachine( 5437): Proxy object connected
,V/BluetoothPhoneService( 3672): Call state Converted2: IDLE/IDLE -> 6
,D/HeadsetPhoneState( 5437): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetStateMachine( 5437): Disconnected process message: 11
D/HeadsetPhoneState( 5437): sendDeviceDataStateChanged
D/HeadsetStateMachine( 5437): Disconnected process message: 20
D/HeadsetPhoneState( 5437): Signal level : previous=0 curr=0
,V/HeadsetService( 5437): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5437): Disconnected process message: 10
D/HeadsetPhoneState( 5437): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
W/BluetoothHeadset( 3672): Proxy not attached to service
,D/HeadsetStateMachine( 5437): Disconnected process message: 11
D/BluetoothAdapterService( 5437): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5437): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5437): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5437): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5437): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5437): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterState( 5437): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 5437): enable
,D/GKI_LINUX( 5437): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,E/bt-btif ( 5437): Calling BTA_HhEnable
,E/bt-btif ( 5437): btif_storage_get_adapter_property service_mask:0x160040
E/BluetoothServiceJni( 5437): populateRssiValuesNative
I/bluedroid( 5437): getModelRssiValues
,E/BluetoothServiceJni( 5437): model_rssi_values_callback: low = -75, mid = -65, high = 127
,E/BluetoothRemoteDevices( 5437): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BtConfig.SecureMode( 5437): isSecureModeOn:false
,W/System.err( 7296): java.io.FileNotFoundException: /system/etc/vold.fstab: open failed: ENOENT (No such file or directory)
,E/BluetoothRemoteDevices( 5437): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 241
W/System.err( 7296): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 7296): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 7296): 	at java.util.Scanner.<init>(Scanner.java:158)
W/System.err( 7296): 	at java.util.Scanner.<init>(Scanner.java:138)
W/System.err( 7296): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.readVoldFile(StorageOptions.java:107)
W/System.err( 7296): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.determineStorageOptions(StorageOptions.java:31)
W/System.err( 7296): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:81)
W/System.err( 7296): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:129)
W/System.err( 7296): 	at pl.k2.droidoaudioteka.ui.AudiotekaApplication.onCreate(AudiotekaApplication.java:171)
W/System.err( 7296): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 7296): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 7296): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7296): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 7296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7296): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 7296): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 7296): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 7296): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 7296): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 7296): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 7296): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 7296): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
E/BluetoothRemoteDevices( 5437): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 10
,W/System.err( 7296): 	at libcore.io.Posix.open(Native Method)
W/System.err( 7296): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 7296): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 7296): 	... 20 more
,D/BtConfig.SecureMode( 5437): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5437): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 241
,W/System.err( 7296): file res dir: /data/data/pl.k2.droidoaudioteka/files
,W/System.err( 7296): Excternal dir: /mnt/sdcard
,E/BluetoothRemoteDevices( 5437): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,D/BtConfig.SecureMode( 5437): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5437): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 241
,E/BluetoothRemoteDevices( 5437): devicePropertyChangedCallback: bdDevice: F8:CF:C5:D9:E5:61, value is empty for type: 10
,D/BtConfig.SecureMode( 5437): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5437): devicePropertyChangedCallback: bdDevice: F8:CF:C5:D9:E5:61, value is empty for type: 241
,E/BluetoothRemoteDevices( 5437): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
,D/BtConfig.SecureMode( 5437): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5437): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 241
,E/BluetoothRemoteDevices( 5437): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,D/BtConfig.SecureMode( 5437): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5437): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 241
,E/BluetoothRemoteDevices( 5437): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,D/BtConfig.SecureMode( 5437): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5437): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 241
,E/BluetoothRemoteDevices( 5437): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/BtConfig.SecureMode( 5437): isSecureModeOn:false
E/BluetoothRemoteDevices( 5437): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 241
E/bt-btif ( 5437): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 5437): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
E/bt-btif ( 5437): btif_sock_init: !radio_req && !rfc_init
,D/IOP_DB_BT( 5437): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 5437): db_open: db_open : handle 2009994284l, read 9734 bytes onto local cache
D/IOP_DB_BT( 5437): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 5437): db_query: result 1
,I/        ( 5437): iop_db_open: iop_db_open status 0
,I/bte_conf( 5437): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 5437): [1] primary_record=1 vendor_id=0x0075 vendor_id_source=0x0001 product_id=0x0100 version=0x0200
I/bte_conf( 5437): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 5437): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothAdapterState( 5437): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5437): ScanMode =  20
,D/BluetoothAdapterProperties( 5437): State =  11
D/BtConfig.SecureMode( 5437): isSecureModeOn:false
D/BtConfig.SecureMode( 5437): isSecureModeOn:false
D/BtConfig.SecureMode( 5437): isSecureModeOn:false
D/BtConfig.SecureMode( 5437): isSecureModeOn:false
D/BtConfig.SecureMode( 5437): isSecureModeOn:false
D/BtConfig.SecureMode( 5437): isSecureModeOn:false
D/BtConfig.SecureMode( 5437): isSecureModeOn:false
D/BtConfig.SecureMode( 5437): isSecureModeOn:false
,I/BluetoothAdapterState( 5437): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterService( 5437): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5437): updateAdapterState state is 12
,D/BluetoothAdapterService( 5437): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothA2dp( 4435): onBluetoothStateChange: up=true
,D/BluetoothAdapterService(1110257528)( 5437): Register RemoteMessageListener
,D/HeadsetService( 5437): registerMessageListener
D/BluetoothAdapterService( 5437): Autoconnection is available 
,D/HeadsetStateMachine( 5437): Disconnected process message: 70
D/HeadsetStateMachine( 5437): processRegisterMessageListener : 2, com.android.bluetooth.btservice.RemoteDevices$1@4234d8b0
D/BluetoothAdapterService( 5437): updateAdapterState prevState = 11newState = 12
,D/BluetoothAdapterService( 5437): starting service from this receiver
D/BluetoothA2dp( 5410): onBluetoothStateChange: up=true
D/BluetoothInputDevice( 5410): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 3236): onBluetoothStateChange: up=true
,W/ContextImpl( 5437): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.startService:506 com.android.bluetooth.btservice.AdapterService.updateAdapterState:653 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
,V/MaBo    ( 7296): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/BluetoothAdapterState( 5437): Entering On State from state = 11
,D/BluetoothPanServiceJni( 5437): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
,D/BluetoothAdapterService( 5437): initWakeLock, pfd lock: {ParcelFileDescriptor: FileDescriptor[85]}, pfd unlock: {ParcelFileDescriptor: FileDescriptor[86]}
D/bluedroid( 5437): init_wake_lock lock_fd:85, unlock_fd:86
,I/BluetoothPbapService( 5437): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
W/InputMethodManagerService( 3236): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3236): [BT Setting State] State =12
,I/InputMethodManagerService( 3236): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/BluetoothAdapterService(1110257528)( 5437): Get Bonded Devices being called
D/PhoneApp( 3672): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 12
I/SamsungIME( 3879): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothHeadset( 3672): registerListener : 11, listenercom.android.phone.PhoneGlobals$MessageListener@424f6ed0, true
I/QuickConnect[1.1][2] ( 5410): BluetoothHelper.ACTION_STATE_CHANGED - STATE_ON
D/BluetoothHeadset( 3672): registerMessageListener
D/HeadsetService( 5437): registerMessageListener
D/HeadsetService( 5437): registerMessageListener
D/HeadsetStateMachine( 5437): Disconnected process message: 70
D/PhoneApp( 3672): registerMessageListener
D/HeadsetStateMachine( 5437): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@423c0af8
I/BluetoothPbapService( 5437): Handler(): got msg=1
V/BluetoothPbapService( 5437): PBAP Service initSocket try: 0
D/BluetoothMapMasInstance( 5437): set MAP SDP message type : 1
W/BluetoothAdapter( 5437): getBluetoothService() called with no BluetoothManagerCallback
,I/System.out( 7296): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,W/BluetoothAdapter( 5437): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 5437): SOCK FLAG = 3 ***********************
,E/BluetoothServiceJni( 5437): SOCK FLAG = 1 ***********************
,D/BluetoothPbapService( 5437): PBAP Socket is BluetoothServerSocket
,I/System.out( 7296): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 7296): moge zapisać w resDir?true
D/STATUSBAR-IconMerger( 3500): checkOverflow(336), More:false, Req:false Child:2
,V/MaBo    ( 7296): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 7296): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 7296): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,W/GAV2    ( 7296): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/GAV2    ( 7296): Thread[main,5,main]: ExceptionReporter created, original handler is pl.k2.droidoaudioteka.common.helpers.AudiotekaExceptionHandler
,I/AUDIOTEKA_GA( 7296): init tracking...
,I/AUDIOTEKA_GA( 7296): app started!
,I/BugSenseHandler( 7296): Registering default exceptions handler
,D/AuthorizationBluetoothService( 3760): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/GKI_LINUX( 5437): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,I/DownloadService( 7296): Tworzenie serwisu - onCreate()
,I/DownloadService( 7296): Start serwisu - onStart()
,I/BugSenseHandler( 7296): Registering default exceptions handler
,I/BugSenseHandler( 7296): Flushing...
,I/knox    ( 5352): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,I/BugSenseHandler( 7296): Registering default exceptions handler
W/ContextImpl( 5352): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 5352): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 5352): KNOXAgentService : onCreate()
,D/knox    ( 5352): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 5352): KNOXAgentService. startJobThread() start
,D/knox    ( 5352): KNOXAgentService. JobThread()
,I/SELinux ( 7339): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7339):  
,I/PlayerService( 7296): Tworzenie serwisu - onCreate()
,D/knox    ( 5352): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 5352): KNOXAgentService. startJobThread() wait
,D/knox    ( 5352): KNOXAgentService : onDestroy().
,D/knox    ( 5352): ModuleBase.cancelAllAlarmManageModule()
,I/MediaFocusControl( 3236):   Remote Control   registerMediaButtonIntent() for PendingIntent{433a83e0: PendingIntentRecord{4303dcc0 pl.k2.droidoaudioteka broadcastIntent}}
,I/SELinux ( 7339): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7339):  
I/SELinux ( 7339):  
,I/SELinux ( 7339): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7339): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7339): >>>>> Normal User
,E/dalvikvm( 7339): >>>>> tv.peel.smartremote [ userId:0 | appId:10165 ]
,E/SELinux ( 7339): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/BugSenseHandler( 7296): Flushing...
,I/BugSenseHandler( 7296): Registering default exceptions handler
,V/KeyguardUpdateMonitor( 3500): handleSetGenerationId(g=2, clear=true)
,D/TimaKeyStoreProvider( 7339): in addTimaSignatureService
,V/AUDIOTEKA_MB( 7296): new AudioManagerFocusWrapper in playerservice oncreate
,D/TimaKeyStoreProvider( 7339): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7339): Added TimaKesytore provider
,I/PlayerService( 7296): Start serwisu - onStart()
,D/dalvikvm( 7339): GC_CONCURRENT freed 2993K, 33% free 9572K/14116K, paused 4ms+2ms, total 22ms
,D/dalvikvm( 7339): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/System.out( 7296): Thread-505(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7296): Thread-505(ApacheHTTPLog):isShipBuild true
,I/System.out( 7296): Thread-505(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 7296): pool-1-thread-1 calls detatch()
,W/BugSenseHandler( 7296): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
,W/ContextImpl( 5946): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/LocalBluetoothProfileManager( 5946): Adding local A2DP profile
,D/Tethering( 3236): interfaceLinkStateChanged wlan0, true
,D/Tethering( 3236): interfaceStatusChanged wlan0, true
V/AlarmManager( 3236): waitForAlarm result :8
,I/ConnectivityService( 3236): defaultVal : 1, tetherEnabledInSettings : true
,E/Tethering( 3236): No numeric data
,V/AlarmManager( 3236): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 3500): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 3500): handleTimeUpdate
,D/NtpTrustedTime( 3236): forceRefresh() from cache miss
,D/Tethering( 3236): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime( 3236): forceRefresh Fail.
,V/NetworkStats( 3236): performPollLocked(flags=0x1)
I/wpa_supplicant( 7295): wlan0: Setting scan request: 0 sec 100000 usec
D/Tethering( 3236): interfaceLinkStateChanged wlan0, true
D/Tethering( 3236): interfaceStatusChanged wlan0, true
,D/STATUSBAR-IconMerger( 3500): checkOverflow(336), More:false, Req:false Child:2
,V/NetworkStats( 3236): performPollLocked() took 24ms
D/NtpTrustedTime( 3236): forceRefresh() from cache miss
,D/NtpTrustedTime( 3236): forceRefresh Fail.
,W/ContextImpl( 5946): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
D/LocalBluetoothProfileManager( 5946): Adding local HEADSET profile
I/wpa_supplicant( 7295): >>>>> Not GET KEY, IV <<<<<
I/wpa_supplicant( 7295): >>>>> Not GET KEY, IV <<<<<
I/wpa_supplicant( 7295): rfkill: Cannot open RFKILL control device
E/BluetoothHeadset( 5946): BTStateChangeCB is registed
D/Tethering( 3236): interfaceLinkStateChanged p2p0, true
D/Tethering( 3236): interfaceStatusChanged p2p0, true
D/Tethering( 3236): interfaceLinkStateChanged p2p0, true
,D/Tethering( 3236): interfaceStatusChanged p2p0, true
,W/ContextImpl( 5946): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
E/BluetoothHeadset( 5946): BluetoothHeadset service is binded
,W/ContextImpl( 5946): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/Bluetoothsap( 5946): bindService called to Bluetooth SAP Service
,I/wpa_supplicant( 7295): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,W/ContextImpl( 5946): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,D/LocalBluetoothProfileManager( 5946): PANU : true
,D/LocalBluetoothProfileManager( 5946): Adding local MAP profile
,W/ContextImpl( 5946): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
,D/BluetoothMap( 5946): Create BluetoothMap proxy object
W/ContextImpl( 5946): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,I/System.out( 7296): pool-1-thread-2 calls detatch()
,W/BugSenseHandler( 7296): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
W/ContextImpl( 5946): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,W/ContextImpl( 5946): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
I/wpa_supplicant( 7295): P2P: initialized channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
I/wpa_supplicant( 7295): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant( 7295): Skip scan - bUseNetwork false
D/Bluetoothsap( 5946): bindService called to Bluetooth SAP Service
D/LocalBluetoothProfileManager( 5946): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 5946): finishStartingService: stopping service
,D/WifiStateMachine( 3236): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/BluetoothNotiBroadcastReceiver( 5946): onReceive
,D/BluetoothA2dp( 5946): Proxy object connected
,D/WifiNative( 3236): callSECApiString - ID [21]
I/wpa_supplicant( 7295): HOTSPOT20_ENABLE called
,I/wpa_supplicant( 7295): wlan0: HS20_DISABLED_COMPLETE normal
D/STATUSBAR-NetworkController( 3500): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 3500): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 3500): refreshSignalCluster: data=-1 bt=false
,D/WifiNative( 3236): callSECApiInt - ID [65]
,D/BtConfig.SecureMode( 5437): isSecureModeOn:false
,E/WifiConfigStore( 3236): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/AuthorizationBluetoothService( 3760): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 3760): Proximity feature is not enabled.
,D/A2dpProfile( 5946): Bluetooth service connected
,D/WifiNative( 3236): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 7295): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 7295): reset timer : RESET_TIMER 0
I/wpa_supplicant( 7295): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 7295): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 7295): First Scan Start
,I/wpa_supplicant( 7295): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine( 3236): Set the Nv default ccode
,W/Settings( 5693): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine( 3236): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,E/WifiStateMachine( 3236): HS20_DISABLED_COMPLETEnormal
,D/WifiP2pService( 3236): P2pDisabledState{ what=131203 }
W/BluetoothAdapter( 5437): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 5437): SOCK FLAG = 0 ***********************
D/GKI_LINUX( 5437): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
I/BtOppRfcommListener( 5437): Accept thread started.
D/HeadsetProfile( 5946): Bluetooth service connected
D/Bluetoothsap( 5946): BluetoothSAP Proxy object connected
D/SapProfile( 5946): Bluetooth service connected
D/Bluetoothsap( 5946): getConnectedDevices()
,D/BluetoothInputDevice( 5946): Proxy object connected
,D/HidProfile( 5946): Bluetooth service connected
,D/BluetoothPan( 5946): BluetoothPAN Proxy object connected
,D/PanProfile( 5946): Bluetooth service connected
D/BluetoothMap( 5946): Proxy object connected
I/wpa_supplicant( 7295): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
D/CommandListener( 3036): Setting iface cfg
D/MapProfile( 5946): Bluetooth service connected
D/CommandListener( 3036): Trying to bring up p2p0
D/BluetoothPbap( 5946): Proxy object connected
D/WifiMonitor( 3236): startMonitoring(p2p0) with mConnected = true
D/PbapServerProfile( 5946): Bluetooth service connected
D/Bluetoothsap( 5946): BluetoothSAP Proxy object connected
D/SapProfile( 5946): Bluetooth service connected
D/Bluetoothsap( 5946): getConnectedDevices()
D/WifiP2pService( 3236): P2pEnablingState
D/WifiP2pService( 3236): P2pEnablingState{ what=147457 }
D/WifiP2pService( 3236): P2p socket connection successful
D/WifiP2pService( 3236): P2pEnabledState
D/WifiP2pService( 3236): sending p2p connection changed broadcast: IDLE
E/WifiStateMachine( 3236): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController( 3236): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/QuickConnect[1.1][2] ( 5410): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
D/WifiDisplayController( 3236): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 3236): disconnect
D/WifiDisplayController( 3236): updateConnection
D/WifiDisplayController( 3236): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 3236): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/WifiP2pStateTracker( 3236): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/QuickConnect[1.1][2] ( 5410): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
D/WifiDisplayController( 3236): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter( 3236): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/QuickConnect[1.1][2] ( 5410): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
D/QuickConnect[1.1][2] ( 5410): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
I/ActivityManager( 3236): Killing 6117:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
I/knox    ( 5352): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/WifiP2pService( 3236): DeviceAddress: 02:e0:6d
D/WifiDisplayController( 3236): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: S5mini-1
D/WifiDisplayController( 3236):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiDisplayController( 3236):  primary type: 10-0050F204-5
D/WifiDisplayController( 3236):  secondary type: null
D/WifiDisplayController( 3236):  wps: 0
D/WifiDisplayController( 3236):  grpcapab: 0
D/WifiDisplayController( 3236):  devcapab: 0
D/WifiDisplayController( 3236):  status: 3
D/WifiDisplayController( 3236):  wfdInfo: null
D/WifiDisplayController( 3236):  groupownerAddress: null
D/WifiDisplayController( 3236):  GOdeviceName: null
D/WifiDisplayController( 3236):  interfaceAddress: 
D/WifiDisplayController( 3236):  SConnectInfo : null
W/ContextImpl( 5352): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/GKI_LINUX( 5437): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
I/knox    ( 5352): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 5352): KNOXAgentService : onCreate()
D/knox    ( 5352): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 5352): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
D/WifiP2pService( 3236): sending p2p persistent groups changed broadcast
D/knox    ( 5352): KNOXAgentService. startJobThread() start
D/knox    ( 5352): KNOXAgentService. JobThread()
D/knox    ( 5352): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 5352): KNOXAgentService. startJobThread() wait
D/knox    ( 5352): KNOXAgentService : onDestroy().
D/knox    ( 5352): ModuleBase.cancelAllAlarmManageModule()
D/QuickConnect[1.1][2] ( 5410): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/WifiP2pService( 3236): InactiveState
D/WifiP2pService( 3236): InactiveState{ what=139287 }
D/WifiP2pService( 3236): P2pEnabledState{ what=139287 }
D/WifiP2pService( 3236): DefaultState{ what=139287 }
D/NearbySettings( 5946): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 5946): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 5946): MountReceiver.onReceive - Create mPrefHandler
D/NearbySettings( 5946): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/NearbySettings( 5946): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 5946): DMSUtil.isNetworkConnected - WIFI: IDLE
I/NearbySettings( 5946): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5946): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 5946): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 5946): MountReceiver.mPrefHandler - 7002
D/FileShare-Server( 6350): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/FileShare-Server( 6350): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
I/wpa_supplicant( 7295): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
I/wpa_supplicant( 7295): nl80211: Received scan results (8 BSSes)
I/wpa_supplicant( 7295): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 7295): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 7295): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
D/Tethering( 3236): interfaceLinkStateChanged wlan0, true
D/Tethering( 3236): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 7295): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
D/Tethering( 3236): interfaceLinkStateChanged wlan0, true
D/Tethering( 3236): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 7295): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 3236): interfaceLinkStateChanged wlan0, true
D/Tethering( 3236): interfaceStatusChanged wlan0, true
D/Tethering( 3236): interfaceLinkStateChanged wlan0, true
D/Tethering( 3236): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 7295): Associated with C0.AA.48
E/WifiStateMachine( 3236): Error! unhandled message{ when=-25ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 7295): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 7295): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 7295): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 7295): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 7295): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 3236): interfaceLinkStateChanged wlan0, true
D/Tethering( 3236): interfaceStatusChanged wlan0, true
D/WifiNative( 3236): callSECApiVoid - ID [50]
D/STATUSBAR-NetworkController( 3500): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/SELinux ( 7373): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7373):  
D/STATUSBAR-NetworkController( 3500): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 3500): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/SELinux ( 7373): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7373):  
I/SELinux ( 7373):  
I/SELinux ( 7373): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7373): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7373): >>>>> Normal User
E/dalvikvm( 7373): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
E/SELinux ( 7373): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 7373): in addTimaSignatureService
D/TimaKeyStoreProvider( 7373): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7373): Added TimaKesytore provider
D/WifiP2pService( 3236): InactiveState{ what=143375 }
D/WifiP2pService( 3236): P2pEnabledState{ what=143375 }
D/dalvikvm( 7373): GC_CONCURRENT freed 2989K, 33% free 9576K/14116K, paused 7ms+3ms, total 36ms
D/dalvikvm( 7373): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/System.out( 7373): Inside WakeupProvider
,I/System.out( 7373): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 7373): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7373): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7373): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,I/dhcpcd  ( 7386): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7386): bssid match
,D/NearbySettings( 5946): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5946): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5946): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 5946): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5946): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 5946): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5946): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 3236): Killing 6204:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,D/DialogFlow( 7373): initQueue()
,I/PowerManagerService( 3236): [PWL] Off : 180s ago
I/PowerManagerService( 3236): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 3236): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 3236): [PWL]       PARTIAL_WAKE_LOCK              'DHCP' (uid=1000, pid=3236, ws=null) (elapsedTime=1029)
,D/AmoledAdjustTimer( 3236): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 3236): SIOP:: AP = 330, Delta = 20
,D/BatteryService( 3236): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 3236): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3236): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3500): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3500): handleBatteryUpdate
D/UiModeManager( 3236): mCoverManager.getCoverState() : true
V/HeadsetService( 5437): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 3500):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 5437): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 3500): checkOverflow(336), More:false, Req:false Child:2
,D/BatteryMeterView( 3500): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiP2pService( 3236): InactiveState{ what=143375 }
,D/WifiP2pService( 3236): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 3236): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 3500): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 3500): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 3236): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 3236): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 3236): evaluateTrafficStatsPolling
,D/WifiStateMachine( 3236): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 3236): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 3236): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/STATUSBAR-NetworkController( 3500): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 3236): evaluateTrafficStatsPolling
D/ConnectivityService( 3236): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 3236): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 3236): net.tcp.delack.wifi not found in system properties. Using defaults
,D/NearbySettings( 5946): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 5946): MountReceiver.onReceive - Keep current state
D/STATUSBAR-NetworkController( 3500): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 3500): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 3500): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 3236): handleConnectivityChange: setting default proxy info 
,V/RouteController( 3036): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
D/STATUSBAR-IconMerger( 3500): checkOverflow(288), More:false, Req:false Child:2
,V/RouteController( 3036): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 3036): RTNETLINK answers: No such file or directory
,V/RouteController( 3036): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1,
,D/NearbySettings( 5946): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,V/RouteController( 3036): /system/bin/ip route flush cached 2>&1,
,V/NearbySettings( 5946): DMSUtil.isNetworkConnected - flag-null, state-null,
,I/NearbySettings( 5946): DMSUtil.isNetworkConnected - WIFI: CONNECTED,
,V/RouteController( 3036): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1,
I/NearbySettings( 5946): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5946): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5946): MountReceiver.onReceive - Keep current state,
,V/RouteController( 3036): RTNETLINK answers: No such process
,V/RouteController( 3036): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 3036): /system/bin/ip route flush cached 2>&1
,D/NtpTrustedTime( 3236): forceRefresh() from cache miss
V/NetworkStats( 3236): updateIfacesLocked()
,V/NetworkStats( 3236): performPollLocked(flags=0x1)
,V/NetworkStats( 3236): performPollLocked() took 14ms,
,D/NearbySettings( 5946): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 5946): MountReceiver.onReceive - Keep current state,
,I/SurfaceFlinger( 1919): id=29 createSurf (1x1),1 flag=4, Uoast
,D/NtpTrustedTime( 3236): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1452596703047 mCachedNtpElapsedRealtime : 273234 mCachedNtpCertainty : 10
,D/NtpTrustedTime( 3236): currentTimeMillis() cache hit
D/NtpTrustedTime( 3236): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3236): currentTimeMillis() cache hit
D/NtpTrustedTime( 3236): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3236): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3236): currentTimeMillis() cache hit
V/NetworkStats( 3236): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/PowerManagerService( 3236): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3236
,D/PackageManager( 3236): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/STATUSBAR-NetworkController( 3500): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 3500): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 3500): updateDataNetType()
,D/Tethering( 3236): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 3236): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 3236): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,V/AlarmManager( 3236): waitForAlarm result :65536,
,D/STATUSBAR-NetworkController( 3500): NoService, mRoamingIconId = 0,
D/NtpTrustedTime( 3236): currentTimeMillis() cache hit
D/        ( 3236): Setting time of day to sec=1452596703
D/        ( 3236): Trying to open a file
D/        ( 3236): File Open Success
D/        ( 3236): File Close Success
I/        ( 3236): DRM_TIME_PATH CHMOD 660 for resetState done 
,I/PCWCLIENTTRACE_PushUtil( 6520): SPPPushClient is installed : true,
I/PCWCLIENTTRACE_PushUtil( 6520): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6520): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6520): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE,
,I/DBG_DM  ( 4982): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected,
,I/DBG_DM  ( 4982): [3.19.140541][Line:609][onReceive] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_DM  ( 4982): [3.19.140541][Line:214][xdmAgentTaskHandler] XEVENT_DM_INIT
,I/DBG_DM  ( 4982): [3.19.140541][Line:432][xdmInitAdpWaitSystemRootingCheck] Check completed.
,I/DBG_DM  ( 4982): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/SELinux ( 7437): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7437):  
,I/DBG_DM  ( 4982): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 4982): [3.19.140541][Line:78][xdmFeatureGetBearerSettingFromCSCFotaDataBase] 
,I/SELinux ( 7437): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7437):  
I/SELinux ( 7437):  
,I/SELinux ( 7437): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7437): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7437): >>>>> Normal User
,E/dalvikvm( 7437): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7437): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7437): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7437): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7437): Added TimaKesytore provider
,D/KeyguardUpdateMonitor( 3500): received broadcast android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 3500): handleTimeUpdate
D/StatusBar-DoNotDistrub( 3500): Received intent with android.intent.action.TIME_SET action
,D/StatusBar-DoNotDistrub( 3500): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/NotificationMgr( 3672): updateNotificationsAtStartup()...
W/Settings( 3236): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/NotificationMgr( 3672): - start call log query...
,I/SQLiteSecureOpenHelper( 4435): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4435): getDatabaseLocked(b,b,pwd)...
,D/dalvikvm( 7437): GC_CONCURRENT freed 3000K, 33% free 9563K/14120K, paused 12ms+1ms, total 52ms
,D/dalvikvm( 7437): WAIT_FOR_CONCURRENT_GC blocked 35ms,
,I/DBG_DM  ( 4982): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,I/dalvikvm( 4982): Total arena pages for JIT: 11
,I/dalvikvm( 4982): Total arena pages for JIT: 12
I/dalvikvm( 4982): Total arena pages for JIT: 13
I/dalvikvm( 4982): Total arena pages for JIT: 14
I/dalvikvm( 4982): Total arena pages for JIT: 15
I/dalvikvm( 4982): Total arena pages for JIT: 16
,I/dalvikvm( 4982): Total arena pages for JIT: 17
,D/dalvikvm( 3236): GC_CONCURRENT freed 3713K, 56% free 24611K/54704K, paused 18ms+16ms, total 232ms
,D/dalvikvm( 3236): WAIT_FOR_CONCURRENT_GC blocked 124ms
,D/dalvikvm( 3236): WAIT_FOR_CONCURRENT_GC blocked 139ms
D/dalvikvm( 3236): WAIT_FOR_CONCURRENT_GC blocked 130ms
D/dalvikvm( 3236): WAIT_FOR_CONCURRENT_GC blocked 110ms
D/dalvikvm( 3236): WAIT_FOR_CONCURRENT_GC blocked 93ms,
I/DBG_DM  ( 4982): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
D/dalvikvm( 3236): WAIT_FOR_CONCURRENT_GC blocked 86ms
,D/dalvikvm( 3236): WAIT_FOR_CONCURRENT_GC blocked 54ms,
D/StatusBar-DoNotDistrub( 3500): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,I/AudioService( 3236): getStreamVolume 5 index 110,
D/StatusBar-DoNotDistrub( 3500): The STREAM NOTIFICATION volume is 0
,D/STATUSBAR-StatusBarManagerService( 3236): manageDisableList what=0x0 pkg=com.android.systemui,
E/Parcel  ( 3236): nm 23
,I/PrGenericPlugin( 1922): [A] ENTER onAcquireDrmInfo : 0xa33,
I/PrGenericPlugin( 1922): [A] LEAVE onAcquireDrmInfo : 0xa33
,I/DrmEventService( 3236):  no response from SecureClock 
I/SensorManagerA( 3236): getReportingMode :: sensor.mType = 5
D/STATUSBAR-NotificationService( 3236): received android.intent.action.DORMANT_MODE_OFF
D/LightsService( 3236): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3236) 
,D/LightsService( 3236): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off,
D/Sensors ( 3236): LightSensor setDelay = 200000000
D/Sensors ( 3236): LightSensor setSensorDelay = 200000000
D/Sensors ( 3236): Light sensor flush: not enabled 0
D/Sensors ( 3236): LightSensor enable = 1
D/Sensors ( 3236): LightSensor enableSensor = 1
,D/SensorManager( 3236): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  ,
D/STATUSBAR-NetworkController( 3500): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-IconMerger( 3500): checkOverflow(288), More:false, Req:false Child:2
,D/NotificationMgr( 3672): call log query complete.
D/NotificationMgr( 3672): call log cursor count : 0
,D/NotificationMgr( 3672): call log cursor count2 : null
,I/SQLiteSecureOpenHelper( 4435): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4435): getDatabaseLocked(b,b,pwd)...
,I/DBG_DM  ( 4982): [3.19.140541][Line:5949][xdbGetFUMOInitiatedType] Initiated Type: 2
,I/DBG_DM  ( 4982): [3.19.140541][Line:119][xdmInitAdpEXTInit] nStatus [220]
,I/DBG_DM  ( 4982): [3.19.140541][Line:463][xdmGetEnableLiveDemoFromCSCFeature] enable LiveDemo : false
,E/DBG_DM  ( 4982): Warning!!! [3.19.140541][Line:65][xdmInitAdpGetSIMLockState] SIM Status is not ready
,I/DBG_DM  ( 4982): [3.19.140541][Line:261][xdmInitAdpEXTInit] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 4982): [3.19.140541][Line:271][xdmAgentTaskHandler] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 4982): [3.19.140541][Line:1854][xdmAgentCheckResumeNoti] 
,I/DBG_DM  ( 4982): [3.19.140541][Line:318][xdmBroadcastGetIsSavedNfcMode] m_IsSavedNfcMode : false
,I/DBG_DM  ( 4982): [3.19.140541][Line:769][xdmUIEvent] XUI_DL_UPDATE_START
,I/DBG_DM  ( 4982): [3.19.140541][Line:369][handleMessage] event ->214
,I/DBG_DM  ( 4982): [3.19.140541][Line:546][xuiAdpGetUpdateReport] Get bUpdateReport = false
,I/DBG_DM  ( 4982): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 4982): [3.19.140541][Line:2008][xdmCallUiFotaInstall] 
,W/dalvikvm( 3653): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 3653): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 3653): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 3653): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 3653): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 3653): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 3653): Using platform SSLCertificateSocketFactory
,I/DBG_DM  ( 4982): [3.19.140541][Line:729][xdmUIEvent] XUI_DL_UPDATE_CONFIRM
W/ContextImpl( 4982): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 com.wssyncmldm.XDMService.xdmCallUiFotaInstall:2023 com.wssyncmldm.XDMService$1.handleMessage:372 android.os.Handler.dispatchMessage:102 
,D/Sensors ( 3236): LightSensor enable = 0
,D/Sensors ( 3236): LightSensor enableSensor = 0
,D/SensorManager( 3236): unregisterListener ::   
D/LightsService( 3236): [SvcLED]  onSensorChanged::light value = 8
D/ChimeraCfgMgr( 4176): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/LightsService( 3236): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/ChimeraModuleLdr( 4176): Module APK com.google.android.play.games already loaded
,I/DBG_DM  ( 4982): [3.19.140541][Line:890][xdmUnRegisterBatteryReceiver] 
,E/DBG_DM  ( 4982): Warning!!! [3.19.140541][Line:898][xdmUnRegisterBatteryReceiver] didn't register
,I/DBG_DM  ( 4982): [3.19.140541][Line:1320][xdmCheckIdleScreen] Idle Screen : false
,E/DBG_DM  ( 4982): Warning!!! [3.19.140541][Line:899][xdmUnRegisterBatteryReceiver] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.XDMService$3@423dfec0
,I/GamesSyncServiceMain( 4176): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 4176): Failed to execute periodic sync, missing client context - aborting
,I/dalvikvm( 4982): Total arena pages for JIT: 18
,I/DBG_DM  ( 4982): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/GAV2    ( 7296): Thread[GAThread,5,main]: connecting to Analytics service
,W/ContextImpl( 7296): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:529 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 7296): Thread[GAThread,5,main]: connect: bindService returned true for Intent { act=com.google.android.gms.analytics.service.START (has extras) }
,I/GAV2    ( 7296): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 7296): Thread[GAThread,5,main]: putHit called
,I/SELinux ( 7465): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7465):  
,I/DBG_DM  ( 4982): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,D/dalvikvm( 3035): GC_EXPLICIT freed 42K, 15% free 9499K/11096K, paused 2ms+3ms, total 29ms
,I/SELinux ( 7465): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7465):  
I/SELinux ( 7465):  
D/dalvikvm( 3035): GC_EXPLICIT freed <1K, 15% free 9499K/11096K, paused 2ms+3ms, total 24ms
,I/SELinux ( 7465): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7465): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 7465): >>>>> Normal User
,E/dalvikvm( 7465): >>>>> com.android.chrome [ userId:0 | appId:10085 ]
,E/SELinux ( 7465): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/dalvikvm( 3035): GC_EXPLICIT freed <1K, 15% free 9499K/11096K, paused 3ms+4ms, total 25ms
,I/SELinux ( 7477): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7477):  
,D/TimaKeyStoreProvider( 7465): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7465): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7465): Added TimaKesytore provider
,I/SELinux ( 7477): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7477):  
I/SELinux ( 7477):  
,I/SELinux ( 7477): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7477): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7477): >>>>> Normal User
,E/dalvikvm( 7477): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
,E/SELinux ( 7477): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/SELinux ( 7483): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7483):  
,W/ContextImpl( 3236): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 3236): sendNotification(1) - 4
D/TimaKeyStoreProvider( 7477): in addTimaSignatureService
D/GAV2    ( 7296): Thread[main,5,main]: service connected, binder: android.os.BinderProxy@4249d180
D/GAV2    ( 7296): Thread[main,5,main]: bound to service
,I/GAV2    ( 7296): Thread[main,5,main]: Connected to service
W/WifiP2pStateTracker( 3236): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/TimaKeyStoreProvider( 7477): Cannot add TimaSignature Service, License check Failed
,W/ResourceType( 3500): Attempt to retrieve bag 0x01030068 which is invalid or in a cycle.
D/ConnectivityService( 3236): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 3236):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
D/ConnectivityService( 3236): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 3236): updateSourceRoutes : no source routing conditions
W/ResourceType( 3500): Attempt to retrieve bag 0x01030067 which is invalid or in a cycle.
D/ActivityThread( 7477): Added TimaKesytore provider
D/ProgressBar( 3500): setProgressDrawable drawableHeight = 12
,I/SELinux ( 7483): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7483):  
I/SELinux ( 7483):  
I/SELinux ( 7483): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7483): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/ProgressBar( 3500): setProgressDrawable drawableHeight = 12
E/dalvikvm( 7483): >>>>> Normal User
E/dalvikvm( 7483): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7483): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/GAV2    ( 7296): Thread[GAThread,5,main]: Sending hit to service
,D/PhoneStatusBar( 3500): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@422f9230
,D/TimaKeyStoreProvider( 7483): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7483): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7483): Added TimaKesytore provider
,D/dalvikvm( 7465): GC_CONCURRENT freed 3004K, 33% free 9562K/14116K, paused 2ms+2ms, total 37ms
,D/dalvikvm( 7465): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/dalvikvm( 7477): GC_CONCURRENT freed 2997K, 33% free 9570K/14120K, paused 5ms+1ms, total 26ms
,D/dalvikvm( 7477): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/STATUSBAR-IconMerger( 3500): checkOverflow(288), More:false, Req:false Child:3
,I/PhenotypeConfigurator( 3653): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/dalvikvm( 7483): GC_CONCURRENT freed 2994K, 33% free 9572K/14120K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 7483): WAIT_FOR_CONCURRENT_GC blocked 12ms
,E/dalvikvm( 7477): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a
W/dalvikvm( 7477): VFY: unable to resolve new-instance 406 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm( 7477): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 7477): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 7477): Link of class 'Lal;' failed
E/dalvikvm( 7477): Could not find class 'al', referenced from method b.a
W/dalvikvm( 7477): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
,D/dalvikvm( 7477): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 7477): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 7477): Link of class 'Lan;' failed
E/dalvikvm( 7477): Could not find class 'an', referenced from method b.a
W/dalvikvm( 7477): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
,D/dalvikvm( 7477): VFY: replacing opcode 0x22 at 0x002a
I/dalvikvm( 7477): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm( 7477): VFY: unable to resolve virtual method 5407: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 7477): Could not find method android.view.View.getTransitionName, referenced from method b.a
W/dalvikvm( 7477): VFY: unable to resolve virtual method 5231: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0006
,W/dalvikvm( 7477): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 7477): Could not find class 'android.app.RemoteInput[]', referenced from method b.a
W/dalvikvm( 7477): VFY: unable to resolve new-array 12200 ([Landroid/app/RemoteInput;) in Lb;
,D/dalvikvm( 7477): VFY: replacing opcode 0x23 at 0x0005
,D/dalvikvm( 7477): DexOpt: unable to opt direct call 0x090f at 0x0e in Lb;.a
W/dalvikvm( 7477): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 7477): Link of class 'Lal;' failed
,D/dalvikvm( 7477): DexOpt: unable to opt direct call 0x068d at 0x08 in Lb;.a
W/dalvikvm( 7477): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 7477): Link of class 'Lan;' failed
D/dalvikvm( 7477): DexOpt: unable to opt direct call 0x0802 at 0x2c in Lb;.a
,D/dalvikvm( 7477): DexOpt: unable to opt direct call 0x0957 at 0x13 in Lb;.a
,I/dalvikvm( 7477): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method dyp.a
W/dalvikvm( 7477): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 7477): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7477): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7477): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 7477): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 7477): VFY: unable to resolve instance field 36
,D/dalvikvm( 7477): VFY: replacing opcode 0x54 at 0x005f,
,D/dalvikvm( 7477): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 7477): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7477): VFY: replacing opcode 0x62 at 0x0047,
D/dalvikvm( 7477): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/SELinux ( 7512): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7512):  
,I/dalvikvm( 7477): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b,
,D/dalvikvm( 7477): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42392040,
,D/dalvikvm( 7477): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42392040
,D/dalvikvm( 7477): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42392040, skipping init
,D/dalvikvm( 7477): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42392040
,D/dalvikvm( 7477): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42392040
,V/JNIHelp ( 7477): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/SELinux ( 7512): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7512):  
I/SELinux ( 7512):  
,I/SELinux ( 7512): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7512): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7512): >>>>> Normal User
,E/dalvikvm( 7512): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7512): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7512): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7512): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7512): Added TimaKesytore provider
,D/btif_config_util( 5437): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/dalvikvm( 7477): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42392040
,D/dalvikvm( 7477): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x42392040
,D/dalvikvm( 7477): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42392040
D/libgps  ( 3236): agps_ril_update_network_state: Waiting for IPC connection...
,D/dalvikvm( 7477): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42392040
,D/dalvikvm( 7512): GC_CONCURRENT freed 2997K, 33% free 9562K/14112K, paused 3ms+1ms, total 28ms
,D/dalvikvm( 7512): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/KLMS-2.3.201 : ( 7512): KLMSValidator() : checkQATesting()
,I/ProviderInstaller( 7477): Installed default security provider GmsCore_OpenSSL
,I/KLMS-2.3.201 : ( 7512): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452596705192
,I/KLMS-2.3.201 : ( 7512): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/dalvikvm( 7477): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 7477): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x000d
,W/ContextImpl( 3236): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/dalvikvm( 7477): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 7477): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 7477): VFY: replacing opcode 0x71 at 0x004e
,I/ActivityManager( 3236): Killing 6244:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7534): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7534):  
,E/YouTube MDX( 7477): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/LocationTagReadyService( 4727): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 4727): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 4727): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 4727): [Slink platform] The state of Slink geocode service is true
,I/SELinux ( 7534): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7534):  
I/SELinux ( 7534):  
,I/SELinux ( 7534): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7534): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7534): >>>>> Normal User
,E/dalvikvm( 7534): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7534): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm( 7477): DexOpt: --- BEGIN 'ads-333194849.jar' (bootstrap=0) ---
,D/TimaKeyStoreProvider( 7534): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7534): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7534): Added TimaKesytore provider
,I/GallerySearchProvider( 6078): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,E/cutils  ( 1910): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1910): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7477): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/SELinux ( 7557): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7557):  
,I/SELinux ( 7557): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7557):  
I/SELinux ( 7557):  
,I/SELinux ( 7557): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7557): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7557): >>>>> Normal User
,E/dalvikvm( 7557): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7557): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7557): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7557): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7557): Added TimaKesytore provider
,D/dalvikvm( 7477): GC_CONCURRENT freed 1867K, 25% free 10776K/14192K, paused 6ms+6ms, total 55ms
,D/dalvikvm( 7477): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 7555): DexOpt: load 4ms, verify+opt 101ms, 194052 bytes
,D/dalvikvm( 7557): GC_CONCURRENT freed 2981K, 33% free 9580K/14116K, paused 8ms+1ms, total 29ms
,D/dalvikvm( 7557): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/SELinux ( 7576): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7576):  
,I/SELinux ( 7576): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7576):  
I/SELinux ( 7576):  
,I/SELinux ( 7576): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7576): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7576): >>>>> Normal User
,E/dalvikvm( 7576): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7576): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/ActivityManager( 3236): Killing 6275:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7576): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7576): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7576): Added TimaKesytore provider
,D/dalvikvm( 7534): GC_CONCURRENT freed 3001K, 33% free 9562K/14112K, paused 53ms+1ms, total 118ms
,D/dalvikvm( 7534): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 7477): DexOpt: --- END 'ads-333194849.jar' (success) ---
,D/dalvikvm( 7477): DEX prep '/data/data/com.google.android.youtube/cache/ads-333194849.jar': unzip in 0ms, rewrite 334ms
,I/dalvikvm( 7477): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 7477): VFY: unable to resolve virtual method 2614: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7477): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 7477): VFY: unable to resolve virtual method 2615: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7477): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 7477): VFY: unable to resolve virtual method 2622: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7477): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
,W/dalvikvm( 7477): VFY: unable to resolve virtual method 2623: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7477): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method agv.getLeanbackLaunchIntentForPackage
W/dalvikvm( 7477): VFY: unable to resolve virtual method 2639: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 7477): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method agv.getPackageInstaller
W/dalvikvm( 7477): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 7477): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method agv.getUserBadgedDrawableForDensity
W/dalvikvm( 7477): VFY: unable to resolve virtual method 2659: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0002
,D/SO_AGENT( 7534): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/dalvikvm( 7477): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method agv.getUserBadgedIcon
W/dalvikvm( 7477): VFY: unable to resolve virtual method 2660: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
I/SO_AGENT( 7534): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7477): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method agv.getUserBadgedLabel
,W/dalvikvm( 7477): VFY: unable to resolve virtual method 2661: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0002
,E/cutils  ( 1910): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1910): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 7477): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/cutils  ( 1910): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7477): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
I/dalvikvm( 3653): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 3653): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 3653): VFY: replacing opcode 0x6e at 0x003d
W/Vold    ( 1910): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1910): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7477): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/Vold    ( 1910): Returning OperationFailed - no handler for errno 30
D/dalvikvm( 7576): GC_FOR_ALLOC freed 3032K, 33% free 9539K/14120K, paused 24ms, total 24ms
,W/InstanceID/Rpc( 7477): Found 10012
,D/dalvikvm( 7576): GC_CONCURRENT freed 208K, 33% free 9557K/14120K, paused 1ms+13ms, total 29ms
,D/dalvikvm( 7576): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/SA      ( 6664): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,V/KVNProvider( 7576): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,I/SA      ( 6664): [BDLM] already registered in spp
,I/System.out( 7483): Thread-514(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,V/KVNProvider( 7576): getFindoCursor query string : 
,I/SA      ( 6664): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 6664): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/System.out( 7483): Thread-514(ApacheHTTPLog):isShipBuild true
,I/System.out( 7483): Thread-514(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/cutils  ( 1910): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,V/KVNProvider( 7576): getTagSearchCursor() tagSearchCursor count : 0
,W/Vold    ( 1910): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7477): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/ActivityManager( 3236): Killing 5693:com.google.android.talk/u0a109 (adj 15): empty #43
,D/dalvikvm( 6631): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x422d06d0, skipping init
,I/SA      ( 6664): [SLFUCHKMGR] constructor called
I/SA      ( 6664): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6664): [OR] == isSIMCardReady false ==
I/SA      ( 6664): [SCU] == networkStateCheck == true
,I/SA      ( 6664): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 6664): isChinaCountryCode : false
,I/SA      ( 6664): [OR] == networkStateCheck true ==
,I/SA      ( 6664): [OR] GetMyCountryZoneTask
,I/SA      ( 6664): [OR] onReceive END
,I/SecureStorage( 6631): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 1958): [INFO]: SPID(0x00000004)Credentials: uid 1000, gid 1000, pid 6631
,I/SecureStorage( 1958): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
,I/SA      ( 6664): [SRS] prepareGetMyCountryZone
I/ActivityManager( 3236): Killing 6225:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/System.out( 3653): Thread-119(HTTPLog):isShipBuild true
,I/System.out( 3653): Thread-119(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/SA      ( 6664): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6664): [SSP] query invoked
,D/PhoneNumberLocatorBootCompletedReceiver( 3672): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 3672): Phone number locator feature is dsiabled
,I/SELinux ( 7626): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7626):  
,I/SELinux ( 7626): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7626):  
I/SELinux ( 7626):  
,I/SELinux ( 7626): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7626): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7626): >>>>> Normal User
,E/dalvikvm( 7626): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7626): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7626): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7626): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7626): Added TimaKesytore provider
,I/ActivityManager( 3236): Killing 6198:com.sec.phone/1001 (adj 15): empty #43
,D/dalvikvm( 7626): GC_CONCURRENT freed 2996K, 33% free 9570K/14120K, paused 4ms+1ms, total 29ms
,D/dalvikvm( 7626): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/SA      ( 6664): [TPMU] GetMccFromDB : null
I/SA      ( 6664): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6664): [TPM] isNoProxy(default) : true
,D/libgps  ( 3236): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 3236): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 3236): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 3236): agps_ril_update_network_availability: Waiting for IPC connection...
,I/SA      ( 6664): [RC New] Execute method=[GET] start
,I/System.out( 7483): AsyncTask #1 calls detatch()
,E/WifiStateMachine( 3236): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/System.out( 7477): Thread-568(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/dalvikvm( 3653): GC_FOR_ALLOC freed 1375K, 23% free 11678K/15040K, paused 63ms, total 67ms
,I/System.out( 7477): Thread-568(ApacheHTTPLog):isShipBuild true
,I/System.out( 7477): Thread-568(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/System.err( 7483): com.sec.android.fota.osp.http.RestClientException
,W/System.err( 7483): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
,W/System.err( 7483): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
,W/System.err( 7483): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
,W/System.err( 7483): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7483): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 7483): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 7483): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 7483): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7483): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7483): Caused by: java.lang.NullPointerException
,W/System.err( 7483): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7483): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7483): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7483): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7483): 	... 8 more
,D/dalvikvm( 7483): GC_CONCURRENT freed 2599K, 30% free 9944K/14120K, paused 3ms+18ms, total 51ms
,I/SurfaceFlinger( 1919): id=29 Removed Uoast (10/11)
,I/SurfaceFlinger( 1919): id=29 Removed Uoast (-2/11)
,D/dalvikvm( 3236): GC_EXPLICIT freed 1786K, 56% free 24607K/54704K, paused 8ms+15ms, total 188ms
,D/PowerManagerService( 3236): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3236) eventTime = 276742
,D/PowerManagerService( 3236): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3236 (0x0)
,D/PowerManagerService( 3236): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3236, ws=WorkSource{1000}) (elapsedTime=3489)
,I/sCloudBackupApp( 7626): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7626): Other Intent
I/ActivityManager( 3236): Killing 6011:com.google.android.music:main/u0a125 (adj 15): empty #43
,I/SurfaceFlinger( 1919): id=30 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3236): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3236
,I/SELinux ( 7651): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7651):  
,I/SELinux ( 7651): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7651):  
I/SELinux ( 7651):  
,I/SELinux ( 7651): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7651): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7651): >>>>> Normal User
,E/dalvikvm( 7651): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7651): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7651): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7651): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7651): Added TimaKesytore provider
,I/System.out( 6664): Thread-467(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7483): AsyncTask #2 calls detatch()
D/dalvikvm( 7651): GC_CONCURRENT freed 2993K, 33% free 9567K/14112K, paused 3ms+3ms, total 24ms
,D/dalvikvm( 7651): WAIT_FOR_CONCURRENT_GC blocked 13ms
,I/System.out( 6664): Thread-467(ApacheHTTPLog):isShipBuild true
,I/System.out( 6664): Thread-467(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/com.samsung.app( 7651): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7651): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7651): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7651): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7651): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7651): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5637): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/STATUSBAR-NetworkController( 3500): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/com.samsung.app( 7651): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
W/BackupManagerService( 3236): dataChanged but no participant pkg='com.android.providers.settings' uid=10011
,D/daemonapp( 5637): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7651): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5637): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7651): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7651): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 3236): Killing 6131:com.android.calendar/u0a144 (adj 15): empty #43
,I/ActivityManager( 3236): Killing 6150:com.android.providers.calendar/u0a45 (adj 15): empty #43
,I/SELinux ( 7665): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7665):  
,I/SELinux ( 7665): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7665):  
I/SELinux ( 7665):  
,I/SELinux ( 7665): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7665): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7665): >>>>> Normal User
,E/dalvikvm( 7665): >>>>> com.samsung.android.internal.headlines [ userId:0 | appId:10110 ]
,E/SELinux ( 7665): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7665): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7665): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7665): Added TimaKesytore provider
,I/SecureStorage( 1958): [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 1958): [INFO]: SPID(0x00000004)PID: 6631, TID: 6655
,D/dalvikvm( 7665): GC_CONCURRENT freed 2996K, 33% free 9563K/14112K, paused 3ms+2ms, total 37ms
,D/dalvikvm( 7665): WAIT_FOR_CONCURRENT_GC blocked 34ms
,D/HeadlinesChannelApplication( 7665): [onCreate]
,D/Headlines( 7665): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 7665): getCountryCode(): countryCode = PL
,D/Headlines( 7665): Breath.onCreate
,D/HeadlinesCardManager( 7665): HeadlinesCardManager : constructor
E/HeadlinesCardManager( 7665): HeadlinesCardManager : ctor = image_cache size is 42MB
,D/SA Version( 7665): CardProvider Library : 13
,I/System.out( 7477): Thread-568 calls detatch()
,I/SELinux ( 7677): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7677):  
,D/MagazineService::CardProviderContentProvider( 6711): insertProvider: provider already exists.: com.samsung.android.app.headlines
,D/MagazineService::CardProviderContentProvider( 6711): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 7665): registerCardProvider: provider already exists.
,I/Headlines( 7665): HeadlinesDataCenter ctor
I/Headlines( 7665): HeadlinesDataCenter. mLocale = en_US
,D/HeadlinesChannelUtil( 7665): getCountryCode(): countryCode = PL
D/HeadlinesCardManager( 7665): HeadlinesCardManager : constructor welcome :YES
I/SELinux ( 7677): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7677):  
I/SELinux ( 7677):  
,I/SELinux ( 7677): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7677): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7677): >>>>> Normal User
,E/dalvikvm( 7677): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7677): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7677): in addTimaSignatureService
,D/libgps  ( 3236): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 3236): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 3236): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/TimaKeyStoreProvider( 7677): Cannot add TimaSignature Service, License check Failed
D/Headlines( 7665): Breath timer started. interval : 30000
,D/ActivityThread( 7677): Added TimaKesytore provider
,D/dalvikvm( 7477): GC_CONCURRENT freed 1390K, 21% free 11372K/14308K, paused 5ms+40ms, total 150ms,
D/Headlines( 7665): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 7665): updateCategory : HeadlinesCardManager:updateCategory() category size == 0,
D/HeadlinesCardManager( 7665): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 7665): queryCategory.  mRequest is not initialized.,
D/HeadlinesCardManager( 7665): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 7665): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 7665): requestUpdateNewsWelcomeCard !!! no welcome card,
,I/SecureStorage( 6631): [INFO]: SPID(0x00000000)Processing data has been completed,
,I/dalvikvm( 4176): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a,
W/dalvikvm( 4176): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 4176): VFY: replacing opcode 0x6e at 0x003d
D/dalvikvm( 7677): GC_CONCURRENT freed 2994K, 33% free 9575K/14120K, paused 6ms+1ms, total 34ms
,D/dalvikvm( 7677): WAIT_FOR_CONCURRENT_GC blocked 28ms,
,E/ActivityThread( 4176): Failed to find provider info for com.android.contacts.metadata,
,D/dalvikvm( 3760): GC_EXPLICIT freed 1623K, 27% free 10795K/14640K, paused 4ms+9ms, total 71ms,
,I/System.out( 7477): Thread-550 calls detatch(),
,V/WebViewChromium( 7677): Binding Chromium to the background looper Looper (main, tid 1) {422daf78},
,I/chromium( 7677): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserProcessMain( 7677): Initializing chromium process, renderers=0,
,W/PhenotypeConfigurator( 3653): Server returned 404,
,W/chromium( 7677): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation,
,D/libEGL  ( 7677): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7677): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7677): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7677): Mali API Version : 401
,I/Mali    ( 7677): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/DelayedSyncController( 7465): Delaying sync.
,D/NtpTrustedTime( 3236): getCachedNtpTime() cache hit
,I/SA      ( 6664): [RC New] [v2liruge] api execute + 1576
,I/SA      ( 6664): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6664): AsyncTask #1 calls detatch()
,I/SA      ( 6664): [TPMU] getNetworkMcc : 
,I/SA      ( 6664): [SCU] saveMccToPreferece Start
I/SA      ( 6664): [SCU] RegionMCC : 260
,I/SA      ( 6664): [SSP] query invoked
,W/GAV2    ( 7677): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SA      ( 6664): [TPMU] GetMccFromDB : null
I/SA      ( 6664): [SCU] getMccFromPreferece mcc = 260,
,I/SA      ( 6664): [SCU] saveMccToPreferece End,
,D/SyncManager( 3236): failed sync operation ,
,I/SA      ( 6664): [RC New] executeRequest [v2liruge] end. 1624,
,D/SyncManager( 3236): not retrying sync operation because the error is a hard error: ,
,I/SA      ( 6664): [RC New] Execute end,
I/SA      ( 6664): [OR] GetMyCountryZoneTask mcc = 260,
,I/SA      ( 6664): [OR] GetMyCountryZoneTask Success,
,E/cutils  ( 1910): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system,
W/Vold    ( 1910): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 7677): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache,
,I/ActivityManager( 3236): Killing 6154:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43,
,I/NSApplication( 7677): Starting up...,
,I/ImageResourceManager( 6398): ImageResourceManager: uninitalized,
,I/iu.Environment( 6398): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*,
,D/QuickConnect[1.1][2] ( 5410): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE,
,I/QuickConnect[1.1][2] ( 5410): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service,
,V/QuickConnect[1.1][2] ( 5410): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422e3660,
,I/SELinux ( 7729): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7729):  ,
,D/dalvikvm( 6398): GC_FOR_ALLOC freed 1041K, 31% free 9850K/14116K, paused 44ms, total 47ms
,D/dalvikvm( 3035): GC_EXPLICIT freed 42K, 15% free 9499K/11096K, paused 2ms+3ms, total 32ms,
I/SELinux ( 7729): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7729):  
I/SELinux ( 7729):  
,I/SELinux ( 7729): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7729): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
E/dalvikvm( 7729): >>>>> Normal User
,E/dalvikvm( 7729): >>>>> com.android.email [ userId:0 | appId:10157 ],
E/SELinux ( 7729): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,I/dalvikvm-heap( 6398): Grow heap (frag case) to 13.161MB for 2129936-byte allocation,
,D/dalvikvm( 3035): GC_EXPLICIT freed <1K, 15% free 9499K/11096K, paused 2ms+3ms, total 27ms,
,D/dalvikvm( 6398): GC_FOR_ALLOC freed <1K, 27% free 11930K/16200K, paused 18ms, total 18ms,
,I/iu.SyncManager( 6398): SYNC; picasa accounts,
,D/TimaKeyStoreProvider( 7729): in addTimaSignatureService,
,D/dalvikvm( 3035): GC_EXPLICIT freed <1K, 15% free 9499K/11096K, paused 2ms+3ms, total 27ms,
,D/TimaKeyStoreProvider( 7729): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7729): Added TimaKesytore provider,
,D/dalvikvm( 6398): GC_CONCURRENT freed 40K, 27% free 11904K/16200K, paused 3ms+7ms, total 54ms,
,I/iu.UploadsManager( 6398): num queued entries: 0,
,I/iu.UploadsManager( 6398): num updated entries: 0,
,I/iu.SyncManager( 6398): NEXT; no task,
,D/dalvikvm( 7729): GC_CONCURRENT freed 2980K, 33% free 9578K/14112K, paused 5ms+1ms, total 39ms,
,D/dalvikvm( 7729): WAIT_FOR_CONCURRENT_GC blocked 34ms,
,D/dalvikvm( 6398): GC_FOR_ALLOC freed 13K, 27% free 11926K/16200K, paused 17ms, total 17ms,
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6520): mConnectivityHandler : connected,
,D/RCPManagerService( 3236): exchangeData() failure , invalid userId,
,W/PCWCLIENTTRACE_AccountUtil( 6520): [hasSamungAccount] - No Samsung Account,
,D/RCPManagerService( 3236): exchangeData() failure , invalid userId,
,D/RCPManagerService( 3236): exchangeData() failure , invalid userId,
,D/dalvikvm( 6398): GC_FOR_ALLOC freed 11K, 22% free 16082K/20368K, paused 23ms, total 23ms,
,I/ActivityManager( 3236): Killing 5907:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43,
,E/ConnectivityChangeReceiver( 4176): Ignoring connectivity change,
E/PCWCLIENTTRACE_SecurePreferencesJNI( 6520): failed to loading secure library,
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6520): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6520): GetString : secure API is not supported!!,
I/PCWCLIENTTRACE_PushUtil( 6520): SPPPushClient is installed : true,
I/PCWCLIENTTRACE_PushUtil( 6520): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 6520): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6520): [ensureRegistration] - No Samsung account,
,I/SELinux ( 7756): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7756):  
,E/Watchdog( 3236): !@Sync 8
I/SELinux ( 7756): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7756):  
I/SELinux ( 7756):  
I/SELinux ( 7756): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7756): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7756): >>>>> Normal User
E/dalvikvm( 7756): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
E/SELinux ( 7756): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/RCPManagerService( 3236): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 7756): in addTimaSignatureService
,V/AlarmManager( 3236): waitForAlarm result :4
D/RCPManagerService( 3236): exchangeData() failure , invalid userId
D/TimaKeyStoreProvider( 7756): Cannot add TimaSignature Service, License check Failed
D/RCPManagerService( 3236): exchangeData() failure , invalid userId
D/ActivityThread( 7756): Added TimaKesytore provider
,V/AlarmManager( 3236): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/ActivityManager( 3236): Killing 6459:com.android.defcontainer/u0a6 (adj 15): empty #43
,W/ActivityManager( 3236): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 7772): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7772):  
,I/ActivityManager( 3236): Killing 6356:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,I/SELinux ( 7772): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7772):  
I/SELinux ( 7772):  
,I/SELinux ( 7772): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7772): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7772): >>>>> Normal User
,E/dalvikvm( 7772): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
D/dalvikvm( 7756): GC_CONCURRENT freed 3007K, 33% free 9562K/14120K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 7756): WAIT_FOR_CONCURRENT_GC blocked 25ms
,E/SELinux ( 7772): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7772): in addTimaSignatureService
,D/BadgeProvider( 7756): onCreate
,D/BadgeProvider( 7756): DatabaseHelper
,D/TimaKeyStoreProvider( 7772): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7772): Added TimaKesytore provider
,D/BadgeProvider( 7756): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7756): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7756): sendNotify, [notify] : null
D/BadgeProvider( 7756): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7756): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7756): update, [UpdateCount] : 1
,D/Launcher.Model( 3692): reloadBadges entered.
,D/dalvikvm( 7772): GC_CONCURRENT freed 3001K, 33% free 9566K/14120K, paused 2ms+1ms, total 28ms
,D/dalvikvm( 7772): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/System.out( 7477): Thread-556 calls detatch()
,I/SELinux ( 7788): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7788):  
I/ActivityManager( 3236): Killing 6494:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/SELinux ( 7788): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7788):  
I/SELinux ( 7788):  
,I/SELinux ( 7788): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7788): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7788): >>>>> Normal User
,E/dalvikvm( 7788): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
,E/SELinux ( 7788): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7788): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7788): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7788): Added TimaKesytore provider
I/ActivityManager( 3236): Killing 6506:com.android.musicfx/u0a24 (adj 15): empty #43
,D/dalvikvm( 7788): GC_CONCURRENT freed 2991K, 33% free 9573K/14116K, paused 3ms+1ms, total 30ms
,D/dalvikvm( 7788): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/DriveInitializer( 4176): Awaiting to be initialized,
,W/DriveInitializer( 4176): Background init thread started,
,I/dalvikvm( 7788): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N,
W/dalvikvm( 7788): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 7788): VFY: replacing opcode 0x6e at 0x0008,
,E/cutils  ( 1910): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system,
,W/ContextImpl( 4176): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files,
W/Vold    ( 1910): Returning OperationFailed - no handler for errno 30
,E/dalvikvm( 7788): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a,
W/dalvikvm( 7788): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7788): VFY: replacing opcode 0x22 at 0x0000,
,E/dalvikvm( 7788): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a,
,W/dalvikvm( 7788): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 7788): VFY: replacing opcode 0x22 at 0x0037,
,D/dalvikvm( 3236): GC_EXPLICIT freed 1923K, 56% free 24611K/54704K, paused 8ms+20ms, total 206ms,
,W/DriveInitializer( 4176): Background init thread ended,
,W/dalvikvm( 7788): Unable to resolve superclass of Ldqp; (762),
W/dalvikvm( 7788): Link of class 'Ldqp;' failed
W/dalvikvm( 7788): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7788): Unable to resolve superclass of Ldqp; (762),
W/dalvikvm( 7788): Link of class 'Ldqp;' failed
I/dalvikvm( 7788): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 7788): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 7788): VFY: replacing opcode 0x6e at 0x0000,
,D/dalvikvm( 4176): GC_CONCURRENT freed 1972K, 23% free 12267K/15788K, paused 19ms+6ms, total 134ms
D/dalvikvm( 4176): WAIT_FOR_CONCURRENT_GC blocked 42ms
,D/dalvikvm( 4176): WAIT_FOR_CONCURRENT_GC blocked 46ms
,D/dalvikvm( 4176): WAIT_FOR_CONCURRENT_GC blocked 42ms
,D/dalvikvm( 4176): WAIT_FOR_CONCURRENT_GC blocked 52ms
,E/dalvikvm( 7788): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7788): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7788): VFY: replacing opcode 0x22 at 0x0000
,D/STATUSBAR-NetworkController( 3500): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
W/dalvikvm( 7788): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7788): Link of class 'Ldqp;' failed
W/dalvikvm( 7788): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7788): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7788): Link of class 'Ldqp;' failed
I/dalvikvm( 7788): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 7788): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
D/dalvikvm( 7788): VFY: replacing opcode 0x6e at 0x0008
E/dalvikvm( 7788): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 7788): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
D/dalvikvm( 7788): VFY: replacing opcode 0x1c at 0x0026
,W/dalvikvm( 7788): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7788): Link of class 'Ldqp;' failed
,W/dalvikvm( 7788): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7788): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 7788): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7788): Link of class 'Ldqp;' failed
I/dalvikvm( 7788): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 7788): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
,D/dalvikvm( 7788): VFY: replacing opcode 0x6e at 0x0003
W/dalvikvm( 7788): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7788): Link of class 'Lax;' failed
E/dalvikvm( 7788): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 7788): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
,D/dalvikvm( 7788): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 7788): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7788): Link of class 'Laz;' failed
E/dalvikvm( 7788): Could not find class 'az', referenced from method g.a
W/dalvikvm( 7788): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
,D/dalvikvm( 7788): VFY: replacing opcode 0x22 at 0x002c
,I/dalvikvm( 7788): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
,W/dalvikvm( 7788): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7788): VFY: replacing opcode 0x6e at 0x0008
,I/dalvikvm( 7788): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
W/dalvikvm( 7788): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 7788): VFY: replacing opcode 0x6e at 0x000c
,I/dalvikvm( 7788): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 7788): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7788): VFY: replacing opcode 0x6e at 0x0006
,I/dalvikvm( 7788): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 7788): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
D/dalvikvm( 7788): VFY: replacing opcode 0x6e at 0x000a
,I/dalvikvm( 7788): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 7788): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 7788): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7788): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
,W/dalvikvm( 7788): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 7788): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7788): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
,W/dalvikvm( 7788): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 7788): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 7788): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 7788): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 7788): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 7788): VFY: replacing opcode 0x23 at 0x0005
,I/dalvikvm( 7788): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
,W/dalvikvm( 7788): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7788): VFY: replacing opcode 0x6e at 0x0009
,W/dalvikvm( 7788): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
,W/dalvikvm( 7788): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 7788): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 7788): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
,D/dalvikvm( 7788): VFY: replacing opcode 0x1c at 0x0002
,E/dalvikvm( 7788): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 7788): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 7788): VFY: replacing opcode 0x1f at 0x000c
,D/dalvikvm( 7788): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7788): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7788): VFY: replacing opcode 0x62 at 0x0006
,D/dalvikvm( 7788): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7788): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
,D/dalvikvm( 7788): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7788): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
,D/dalvikvm( 7788): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
W/dalvikvm( 7788): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7788): Link of class 'Lax;' failed
,D/dalvikvm( 7788): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 7788): Unable to resolve superclass of Laz; (841)
,W/dalvikvm( 7788): Link of class 'Laz;' failed
,D/dalvikvm( 7788): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 7788): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
,D/dalvikvm( 7788): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,D/GCM     ( 3760): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,I/SurfaceFlinger( 1919): id=30 Removed Uoast (10/11)
,I/SurfaceFlinger( 1919): id=30 Removed Uoast (-2/11)
D/PowerManagerService( 3236): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3236) eventTime = 280242
D/PowerManagerService( 3236): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3236 (0x0)
D/PowerManagerService( 3236): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3236, ws=WorkSource{1000}) (elapsedTime=3466)
,I/GCM     ( 3760): GCM config loaded
,D/dalvikvm( 7788): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x422da268
,D/dalvikvm( 7788): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x422da268
,W/InstanceID/Rpc( 3760): Found 10012
,I/PhenotypeConfigurator( 3653): Scheduling Phenotype for one-off execution 12592 seconds from now (1452596710221)
,D/GetConfigurationSnapshotOperation( 3653): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
I/dalvikvm( 7788): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
W/dalvikvm( 7788): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 7788): VFY: replacing opcode 0x6e at 0x0076
,I/Babel_SMS( 7788): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7788): MmsConfig.loadMmsSettings
I/Babel_SMS( 7788): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/Babel_SMS( 7788): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7788): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7788): MmsConfig.loadFromResources
,E/Babel_SMS( 7788): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7788): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/PhenotypeFlagCommitter( 3653): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 7788): Unable to resolve superclass of Lfzc; (613)
,W/dalvikvm( 7788): Link of class 'Lfzc;' failed
E/dalvikvm( 7788): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 7788): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
,D/dalvikvm( 7788): VFY: replacing opcode 0x22 at 0x0033
,W/dalvikvm( 7788): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7788): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7788): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
,W/dalvikvm( 7788): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,I/dalvikvm( 7788): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 7788): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
,D/dalvikvm( 7788): VFY: replacing opcode 0x74 at 0x006d
,I/dalvikvm( 7788): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
,W/dalvikvm( 7788): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
,D/dalvikvm( 7788): VFY: replacing opcode 0x6e at 0x0033
,I/dalvikvm( 7788): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 7788): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
,D/dalvikvm( 7788): VFY: replacing opcode 0x6e at 0x0030
W/dalvikvm( 7788): Unable to resolve superclass of Lfzc; (613)
,W/dalvikvm( 7788): Link of class 'Lfzc;' failed
,D/dalvikvm( 7788): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
,I/GoogleURLConnFactory( 3653): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 7788): GC_CONCURRENT freed 1762K, 24% free 10885K/14196K, paused 3ms+2ms, total 36ms
D/dalvikvm( 7788): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 7788): WAIT_FOR_CONCURRENT_GC blocked 22ms
,E/SensorService( 3236): Permission Denial : SEC Private Sensor 
,E/SensorService( 3236): Permission Denial : SEC Private Sensor 
,D/ExynosCameraInterface( 3039): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 3039): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
D/ExynosCameraInterface( 3039): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 3039): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,W/Settings( 7788): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7788): startup - clean
,D/dalvikvm( 3760): GC_EXPLICIT freed 1111K, 26% free 10862K/14640K, paused 12ms+15ms, total 133ms
,I/dalvikvm( 7788): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
,W/dalvikvm( 7788): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7788): VFY: replacing opcode 0x6e at 0x000d
,I/Babel   ( 7788): deleted: false for 0
,W/dalvikvm( 7788): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
I/dalvikvm( 7788): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 7788): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
,D/dalvikvm( 7788): VFY: replacing opcode 0x6e at 0x004e
W/dalvikvm( 7788): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7788): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7788): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 7788): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
,D/dalvikvm( 7788): VFY: replacing opcode 0x22 at 0x0071
,W/dalvikvm( 7788): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7788): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7788): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7788): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7788): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 7788): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
,D/dalvikvm( 7788): VFY: replacing opcode 0x1f at 0x0021
,W/dalvikvm( 7788): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 7788): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
,I/dalvikvm( 7788): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/dalvikvm( 7788): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
,D/dalvikvm( 7788): VFY: replacing opcode 0x6e at 0x0074
,D/WaitQueueForNetworkActivate( 6808): notifyNetworkActivated
,W/ContextImpl( 6808): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager( 3236): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/System.out( 4176): Thread-147(HTTPLog):isShipBuild true
,I/System.out( 4176): Thread-147(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/vclib   ( 7788): onServiceConnected
,W/Babel   ( 7788): Attempted to change video mute state without an active call.
,D/LocationManagerService( 3236): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 6631): Total arena pages for JIT: 11
,I/dalvikvm( 6631): Total arena pages for JIT: 12
,I/dalvikvm( 6631): Total arena pages for JIT: 13
I/dalvikvm( 6631): Total arena pages for JIT: 14
,I/dalvikvm( 6631): Total arena pages for JIT: 15
,I/dalvikvm( 6631): Total arena pages for JIT: 16
,I/dalvikvm( 6631): Total arena pages for JIT: 17
,D/dalvikvm( 7788): GC_CONCURRENT freed 969K, 18% free 11963K/14484K, paused 17ms+2ms, total 94ms
,D/dalvikvm( 7788): WAIT_FOR_CONCURRENT_GC blocked 44ms
,D/dalvikvm( 7788): WAIT_FOR_CONCURRENT_GC blocked 45ms
,D/dalvikvm( 7788): GC_FOR_ALLOC freed 674K, 19% free 12582K/15476K, paused 26ms, total 27ms
,D/hcjo    ( 6808): AutoUpdateManager:IDLE:execute
,D/dalvikvm( 7788): GC_FOR_ALLOC freed 1790K, 24% free 12973K/17068K, paused 51ms, total 51ms
,I/dalvikvm( 6808): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
W/dalvikvm( 6808): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 6808): VFY: replacing opcode 0x6e at 0x0024
,D/InitializeManagerStateMachine( 6808): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6808): exit::IDLE
,D/InitializeManagerStateMachine( 6808): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 6808): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6808): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6808): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6808): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6808): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6808): entry::SUCCESS
,D/hcjo    ( 6808): AutoUpdateManager:INITCHECK:onInitializeSuccess
I/System.out( 7788): Thread-560(HTTPLog):isShipBuild true
,I/System.out( 7788): Thread-560(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/hcjo    ( 6808): AutoUpdateTriggerManager:IDLE:setInterval:345600000
D/hcjo    ( 6808): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6808): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6808): exit::SUCCESS
,D/InitializeManagerStateMachine( 6808): entry::IDLE
,I/iu.SyncManager( 4176): SYNC; picasa accounts
,I/Babel   ( 7788): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager( 3236): Killing 6533:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,D/NetworkLogImpl( 4176): Loaded NetworkSpeedPredictor
,I/iu.Environment( 4176): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 4176): num queued entries: 0
,I/iu.UploadsManager( 4176): num updated entries: 0
,I/iu.SyncManager( 4176): NEXT; no task
,E/SPPClientService( 5844): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5844): [SystemStateMoniter] Current Time : 281550
,E/SPPClientService( 5844): [SystemStateMoniter] No Connect : false
,D/LocationManagerService( 3236): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/SELinux ( 7859): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7859):  
,V/GLSActivity( 3760): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 3760): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SELinux ( 7859): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7859):  
I/SELinux ( 7859):  
,I/SELinux ( 7859): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7859): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7859): >>>>> Normal User
,E/dalvikvm( 7859): >>>>> com.android.calendar [ userId:0 | appId:10144 ]
,E/SELinux ( 7859): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7859): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7859): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7859): Added TimaKesytore provider
,D/dalvikvm( 7859): GC_CONCURRENT freed 2994K, 33% free 9568K/14116K, paused 4ms+1ms, total 48ms
,D/dalvikvm( 7859): WAIT_FOR_CONCURRENT_GC blocked 40ms
,I/ActivityManager( 3236): Killing 6554:com.sec.android.app.shealth/u0a36 (adj 15): empty #43
,D/BootCompletedReceiver( 3236): onReceive
,I/KLMS-2.3.201 : ( 7512): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7512): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1452596711769
,I/KLMS-2.3.201 : ( 7512): StateImplV2() : dateTimeChanged() : Tue Jan 12 12:05:11 CET 2016
,I/SELinux ( 7876): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7876):  
,I/SELinux ( 7876): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7876):  
I/SELinux ( 7876):  
,I/SELinux ( 7876): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7876): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7876): >>>>> Normal User
E/dalvikvm( 7876): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
,E/SELinux ( 7876): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7876): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7876): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7876): Added TimaKesytore provider
,I/dalvikvm( 4176): Could not find method android.content.Context.getNoBackupFilesDir, referenced from method com.google.android.gms.iid.n.<init>
,W/dalvikvm( 4176): VFY: unable to resolve virtual method 378: Landroid/content/Context;.getNoBackupFilesDir ()Ljava/io/File;
,D/dalvikvm( 4176): VFY: replacing opcode 0x6e at 0x002c
,I/dalvikvm( 4176): Could not find method android.content.Context.getDrawable, referenced from method android.support.v4.content.g.a
W/dalvikvm( 4176): VFY: unable to resolve virtual method 287: Landroid/content/Context;.getDrawable (I)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4176): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 4176): Could not find method android.content.Context.getColor, referenced from method android.support.v4.content.g.b
,W/dalvikvm( 4176): VFY: unable to resolve virtual method 283: Landroid/content/Context;.getColor (I)I
,D/dalvikvm( 4176): VFY: replacing opcode 0x6e at 0x0006
,D/dalvikvm( 7876): GC_CONCURRENT freed 3005K, 33% free 9564K/14120K, paused 2ms+2ms, total 31ms
,D/dalvikvm( 7876): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 3653): GC_CONCURRENT freed 1737K, 23% free 11893K/15252K, paused 7ms+14ms, total 84ms
,W/ContextImpl( 7876): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
,E/Device Type Shared Preferences( 7876): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 7876): Device Type Shared Preferences - not connecting to service
,E/com.sec.android.app.shealth.SHealthApplication( 7876): ContentProvider is not null
,W/ResourceType( 7876): No package identifier when getting value for resource number 0x00000000
,I/System.out( 7876): resource Id::2131361807
,D/AmoledAdjustTimer( 3236): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 3236): SIOP:: AP = 350, Delta = 20,
,D/com.sec.android.app.shealth.SHealthApplication( 7876): Success during batch insertion in App registry:0,
,D/ConnectivityService( 3236): handleInetConditionHoldEnd: net=1, condition=100, published condition=0,
,D/STATUSBAR-NetworkController( 3500): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION,
D/STATUSBAR-NetworkController( 3500): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 3500): updateDataNetType()
,D/STATUSBAR-NetworkController( 3500): NoService, mRoamingIconId = 0,
,D/BatteryService( 3236): level:100, scale:100, status:5, health:2, present:true, voltage: 4350, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 3236): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3236): stay LED for fully charged,
,D/UiModeManager( 3236): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 3500): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3500): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3500):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 5437): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5437): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 3500): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 3500): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/LocationManagerService( 3236): getLastLocation: Request[POWER_NONE passive fastest=0 num=1],
,D/LocationManagerService( 3236): getLastLocation: Request[POWER_NONE passive fastest=0 num=1],
,V/MediaPlayer( 7876): decode(56, 30565892, 48105),
,V/MediaPlayerService( 3039): decode(30, 30565892, 48105),
V/MediaPlayerService( 3039): player type = 3
V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): constructor
V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): reset_l(),
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
,V/StagefrightPlayer( 3039): StagefrightPlayer
V/AwesomePlayer( 3039): setListener
V/StagefrightPlayer( 3039): initCheck
V/AwesomePlayer( 3039): setAudioSink
V/StagefrightPlayer( 3039): setDataSource(30, 30565892, 48105)
V/AwesomePlayer( 3039): reset_l(),
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x440b0ea0, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted,
,V/AwesomePlayer( 3039): mSecMediaClock clear
V/AwesomePlayer( 3039): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 3039): mBitrate = -1 bits/sec
V/AwesomePlayer( 3039): current audio track index (0) is added to vector
,V/AwesomePlayer( 3039): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 3039): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 3039): prepare
V/AwesomePlayer( 3039): prepareAsync
V/MediaPlayerService( 3039): wait for prepare
V/AwesomePlayer( 3039): onPrepareAsyncEvent
I/SecMediaClock( 3039): SecMediaClock constructor
,I/SecMediaClock( 3039): reset
V/AwesomePlayer( 3039): initAudioDecoder
V/AwesomePlayer( 3039): checkOffloadExceptions is true
,I/OMXCodec( 3039): Attempting to allocate OMX node 'OMX.google.vorbis.decoder',
I/OMX     ( 3039): mDispatchers.add
I/OMXCodec( 3039): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 3039): finishAsyncPrepare_l
,V/AwesomePlayer( 3039): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 3039): notify(0x440b0ea0, 200, 973, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x440b0ea0, 5, 0, 0)
,V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x440b0ea0, 1, 0, 0)
V/AudioCache( 3039): prepared
V/AudioCache( 3039): wait - success
V/MediaPlayerService( 3039): start
,V/StagefrightPlayer( 3039): start
V/AwesomePlayer( 3039): play
V/AwesomePlayer( 3039): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 3039): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port,
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 3039): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 3039): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x440b0ea0, 6, 0, 0)
V/AudioCache( 3039): ignored
,V/AwesomePlayer( 3039): addBatteryData
V/MediaPlayerService( 3039): wait for playback complete
,I/AudioPlayer( 3039): First fillBuffer call!!,
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] End Of Stream,
V/AwesomePlayer( 3039): postAudioEOS delayUs (0)
V/AwesomePlayer( 3039): onCheckAudioStatus
V/AwesomePlayer( 3039): onCheckAudioStatus() set AUDIO_AT_EOS flag,
V/AwesomePlayer( 3039): onStreamDone
V/AwesomePlayer( 3039): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 3039): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x440b0ea0, 2, 0, 0)
,V/AudioCache( 3039): playback complete - thread will wake up later
V/AwesomePlayer( 3039): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x440b0ea0, 7, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=1),
V/AwesomePlayer( 3039): addBatteryData
V/AudioCache( 3039): wait - success
V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache( 3039): notify(0x440b0ea0, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop() sendCommand(0x43, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 3039): reset out
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 3039): SecMediaClock destructor
V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): ~StagefrightPlayer
,V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
,V/AwesomePlayer( 3039): destructor
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
,V/MediaPlayer( 7876): decode(58, 30501792, 10421)
V/MediaPlayerService( 3039): decode(30, 30501792, 10421)
V/MediaPlayerService( 3039): player type = 3
V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): constructor
V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): reset_l()
,V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): StagefrightPlayer
V/AwesomePlayer( 3039): setListener
,V/StagefrightPlayer( 3039): initCheck
V/AwesomePlayer( 3039): setAudioSink
V/StagefrightPlayer( 3039): setDataSource(30, 30501792, 10421)
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43f40e00, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear,
,V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/AwesomePlayer( 3039): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 3039): mBitrate = -1 bits/sec
V/AwesomePlayer( 3039): current audio track index (0) is added to vector
V/AwesomePlayer( 3039): setDataSource_l: Audio(1), Video(0)
,I/AwesomePlayer( 3039): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 3039): prepare
V/AwesomePlayer( 3039): prepareAsync
V/MediaPlayerService( 3039): wait for prepare
,V/AwesomePlayer( 3039): onPrepareAsyncEvent
I/SecMediaClock( 3039): SecMediaClock constructor
I/SecMediaClock( 3039): reset
V/AwesomePlayer( 3039): initAudioDecoder
,V/AwesomePlayer( 3039): checkOffloadExceptions is true
,I/OMXCodec( 3039): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 3039): mDispatchers.add
I/OMXCodec( 3039): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 3039): finishAsyncPrepare_l
V/AwesomePlayer( 3039): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 3039): notify(0x43f40e00, 200, 973, 0)
V/AudioCache( 3039): ignored
,V/AwesomePlayer( 3039): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43f40e00, 5, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43f40e00, 1, 0, 0)
,V/AudioCache( 3039): prepared
V/AudioCache( 3039): wait - success
V/MediaPlayerService( 3039): start
V/StagefrightPlayer( 3039): start
V/AwesomePlayer( 3039): play
V/AwesomePlayer( 3039): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 3039): startAudioPlayer_l, sendErrorNotification (0),
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] PORT_DISABLED(1),
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port,
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 3039): open(44100, 2, 0x0, 1, 4),
V/AwesomePlayer( 3039): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43f40e00, 6, 0, 0)
V/AudioCache( 3039): ignored
,V/AwesomePlayer( 3039): addBatteryData
V/MediaPlayerService( 3039): wait for playback complete
,I/AudioPlayer( 3039): First fillBuffer call!!,
,D/LocationManagerService( 3236): getLastLocation: Request[POWER_NONE passive fastest=0 num=1],
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 3039): postAudioEOS delayUs (0)
V/AwesomePlayer( 3039): onCheckAudioStatus
V/AwesomePlayer( 3039): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 3039): onStreamDone
V/AwesomePlayer( 3039): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 3039): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43f40e00, 2, 0, 0)
V/AudioCache( 3039): playback complete - thread will wake up later
V/AwesomePlayer( 3039): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43f40e00, 7, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 3039): addBatteryData
V/AudioCache( 3039): wait - success
V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43f40e00, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop() sendCommand(0x44, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 3039): reset out
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 3039): SecMediaClock destructor
V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): ~StagefrightPlayer
V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/AwesomePlayer( 3039): destructor
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/MediaPlayer( 7876): decode(59, 34044116, 34198)
,V/MediaPlayerService( 3039): decode(29, 34044116, 34198)
V/MediaPlayerService( 3039): player type = 3
V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): constructor
V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): StagefrightPlayer
V/AwesomePlayer( 3039): setListener
V/StagefrightPlayer( 3039): initCheck
V/AwesomePlayer( 3039): setAudioSink
V/StagefrightPlayer( 3039): setDataSource(29, 34044116, 34198)
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442b6978, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 3039): mSecMediaClock clear
V/AwesomePlayer( 3039): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 3039): mBitrate = -1 bits/sec
V/AwesomePlayer( 3039): current audio track index (0) is added to vector
V/AwesomePlayer( 3039): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 3039): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 3039): prepare
V/AwesomePlayer( 3039): prepareAsync
V/MediaPlayerService( 3039): wait for prepare
V/AwesomePlayer( 3039): onPrepareAsyncEvent
I/SecMediaClock( 3039): SecMediaClock constructor
I/SecMediaClock( 3039): reset
V/AwesomePlayer( 3039): initAudioDecoder
V/AwesomePlayer( 3039): checkOffloadExceptions is true
,I/OMXCodec( 3039): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 3039): mDispatchers.add
I/OMXCodec( 3039): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 3039): finishAsyncPrepare_l
V/AwesomePlayer( 3039): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache( 3039): notify(0x442b6978, 200, 973, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442b6978, 5, 0, 0)
V/AudioCache( 3039): ignored
,V/AwesomePlayer( 3039): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442b6978, 1, 0, 0)
V/AudioCache( 3039): prepared
V/AudioCache( 3039): wait - success
V/MediaPlayerService( 3039): start
V/StagefrightPlayer( 3039): start
V/AwesomePlayer( 3039): play
V/AwesomePlayer( 3039): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 3039): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 3039): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 3039): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442b6978, 6, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): addBatteryData
,V/MediaPlayerService( 3039): wait for playback complete
,I/AudioPlayer( 3039): First fillBuffer call!!
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 3039): postAudioEOS delayUs (0)
V/AwesomePlayer( 3039): onCheckAudioStatus
V/AwesomePlayer( 3039): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 3039): onStreamDone
V/AwesomePlayer( 3039): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 3039): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442b6978, 2, 0, 0)
V/AudioCache( 3039): playback complete - thread will wake up later
V/AwesomePlayer( 3039): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442b6978, 7, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 3039): addBatteryData
V/AudioCache( 3039): wait - success
V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442b6978, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop() sendCommand(0x45, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/AudioPlayer( 3039): reset out
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 3039): SecMediaClock destructor
V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): ~StagefrightPlayer
V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
,V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/AwesomePlayer( 3039): destructor
,V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
,V/MediaPlayer( 7876): decode(60, 30449260, 7405)
,V/MediaPlayerService( 3039): decode(30, 30449260, 7405)
V/MediaPlayerService( 3039): player type = 3
,V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): constructor
V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
,V/StagefrightPlayer( 3039): StagefrightPlayer
V/AwesomePlayer( 3039): setListener
V/StagefrightPlayer( 3039): initCheck
V/AwesomePlayer( 3039): setAudioSink
V/StagefrightPlayer( 3039): setDataSource(30, 30449260, 7405)
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache( 3039): notify(0x43b65fa0, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 3039): mSecMediaClock clear
V/AwesomePlayer( 3039): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 3039): mBitrate = -1 bits/sec
V/AwesomePlayer( 3039): current audio track index (0) is added to vector
V/AwesomePlayer( 3039): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 3039): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 3039): prepare
V/AwesomePlayer( 3039): prepareAsync
V/MediaPlayerService( 3039): wait for prepare
V/AwesomePlayer( 3039): onPrepareAsyncEvent
I/SecMediaClock( 3039): SecMediaClock constructor
I/SecMediaClock( 3039): reset
V/AwesomePlayer( 3039): initAudioDecoder
V/AwesomePlayer( 3039): checkOffloadExceptions is true
,I/OMXCodec( 3039): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 3039): mDispatchers.add
,I/OMXCodec( 3039): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 3039): finishAsyncPrepare_l
V/AwesomePlayer( 3039): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 3039): notify(0x43b65fa0, 200, 973, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43b65fa0, 5, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43b65fa0, 1, 0, 0)
V/AudioCache( 3039): prepared
V/AudioCache( 3039): wait - success
V/MediaPlayerService( 3039): start
V/StagefrightPlayer( 3039): start
V/AwesomePlayer( 3039): play
V/AwesomePlayer( 3039): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 3039): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 3039): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 3039): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43b65fa0, 6, 0, 0)
V/AudioCache( 3039): ignored
,V/AwesomePlayer( 3039): addBatteryData
V/MediaPlayerService( 3039): wait for playback complete
,I/AudioPlayer( 3039): First fillBuffer call!!
,I/GAV2    ( 7677): Thread[GAThread,5,main]: No campaign data found.
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 3039): postAudioEOS delayUs (0)
V/AwesomePlayer( 3039): onCheckAudioStatus
V/AwesomePlayer( 3039): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 3039): onStreamDone
V/AwesomePlayer( 3039): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 3039): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43b65fa0, 2, 0, 0)
V/AudioCache( 3039): playback complete - thread will wake up later
V/AwesomePlayer( 3039): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43b65fa0, 7, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 3039): addBatteryData
V/AudioCache( 3039): wait - success
V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43b65fa0, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 3039): mAudioTrackVector clear
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop() sendCommand(0x46, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 3039): reset out
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 3039): SecMediaClock destructor
V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): ~StagefrightPlayer
V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/AwesomePlayer( 3039): destructor
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
,V/MediaPlayer( 7876): decode(61, 34134748, 5555)
,V/MediaPlayerService( 3039): decode(30, 34134748, 5555)
V/MediaPlayerService( 3039): player type = 3
V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): constructor
V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): StagefrightPlayer
V/AwesomePlayer( 3039): setListener
V/StagefrightPlayer( 3039): initCheck
V/AwesomePlayer( 3039): setAudioSink
V/StagefrightPlayer( 3039): setDataSource(30, 34134748, 5555)
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442c0c20, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 3039): mSecMediaClock clear
,V/AwesomePlayer( 3039): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 3039): mBitrate = -1 bits/sec
V/AwesomePlayer( 3039): current audio track index (0) is added to vector
V/AwesomePlayer( 3039): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 3039): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 3039): prepare
V/AwesomePlayer( 3039): prepareAsync
,V/MediaPlayerService( 3039): wait for prepare
V/AwesomePlayer( 3039): onPrepareAsyncEvent
I/SecMediaClock( 3039): SecMediaClock constructor
I/SecMediaClock( 3039): reset
V/AwesomePlayer( 3039): initAudioDecoder
V/AwesomePlayer( 3039): checkOffloadExceptions is true
,I/OMXCodec( 3039): Attempting to allocate OMX node 'OMX.google.vorbis.decoder',
I/OMX     ( 3039): mDispatchers.add
I/OMXCodec( 3039): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] OMXCodec::start mState=1,
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 3039): finishAsyncPrepare_l
V/AwesomePlayer( 3039): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache( 3039): notify(0x442c0c20, 200, 973, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442c0c20, 5, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442c0c20, 1, 0, 0)
,V/AudioCache( 3039): prepared
V/AudioCache( 3039): wait - success
V/MediaPlayerService( 3039): start
V/StagefrightPlayer( 3039): start
V/AwesomePlayer( 3039): play
V/AwesomePlayer( 3039): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 3039): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 3039): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 3039): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442c0c20, 6, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): addBatteryData
,V/MediaPlayerService( 3039): wait for playback complete
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 3039): postAudioEOS delayUs (0)
V/AwesomePlayer( 3039): onCheckAudioStatus
V/AwesomePlayer( 3039): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 3039): onStreamDone
V/AwesomePlayer( 3039): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 3039): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442c0c20, 2, 0, 0)
V/AudioCache( 3039): playback complete - thread will wake up later
V/AwesomePlayer( 3039): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442c0c20, 7, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 3039): addBatteryData
V/AudioCache( 3039): wait - success
V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442c0c20, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop() sendCommand(0x47, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 3039): reset out
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 3039): SecMediaClock destructor
V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): ~StagefrightPlayer
V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/AwesomePlayer( 3039): destructor
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 3039): mSecMediaClock clear
V/MediaPlayer( 7876): decode(62, 26954540, 5085)
V/MediaPlayerService( 3039): decode(30, 26954540, 5085)
V/MediaPlayerService( 3039): player type = 3
V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): constructor
V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): StagefrightPlayer
V/AwesomePlayer( 3039): setListener
V/StagefrightPlayer( 3039): initCheck
V/AwesomePlayer( 3039): setAudioSink
V/StagefrightPlayer( 3039): setDataSource(30, 26954540, 5085)
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x44046090, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 3039): mSecMediaClock clear
V/AwesomePlayer( 3039): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 3039): mBitrate = -1 bits/sec
V/AwesomePlayer( 3039): current audio track index (0) is added to vector
V/AwesomePlayer( 3039): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 3039): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 3039): prepare
V/AwesomePlayer( 3039): prepareAsync
V/MediaPlayerService( 3039): wait for prepare
V/AwesomePlayer( 3039): onPrepareAsyncEvent
I/SecMediaClock( 3039): SecMediaClock constructor
I/SecMediaClock( 3039): reset
V/AwesomePlayer( 3039): initAudioDecoder
V/AwesomePlayer( 3039): checkOffloadExceptions is true
,I/OMXCodec( 3039): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 3039): mDispatchers.add
I/OMXCodec( 3039): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 3039): finishAsyncPrepare_l
V/AwesomePlayer( 3039): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 3039): notify(0x44046090, 200, 973, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x44046090, 5, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x44046090, 1, 0, 0)
V/AudioCache( 3039): prepared
V/AudioCache( 3039): wait - success
V/MediaPlayerService( 3039): start
,V/StagefrightPlayer( 3039): start
V/AwesomePlayer( 3039): play
V/AwesomePlayer( 3039): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 3039): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 3039): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 3039): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x44046090, 6, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): addBatteryData
,V/MediaPlayerService( 3039): wait for playback complete
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 3039): postAudioEOS delayUs (0)
,V/AwesomePlayer( 3039): onCheckAudioStatus
V/AwesomePlayer( 3039): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 3039): onStreamDone
V/AwesomePlayer( 3039): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 3039): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x44046090, 2, 0, 0)
V/AudioCache( 3039): playback complete - thread will wake up later
V/AwesomePlayer( 3039): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x44046090, 7, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 3039): addBatteryData
V/AudioCache( 3039): wait - success
V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x44046090, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop() sendCommand(0x48, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/AudioPlayer( 3039): reset out
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 3039): SecMediaClock destructor
,V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): ~StagefrightPlayer
V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
,V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
,V/AwesomePlayer( 3039): destructor
V/AwesomePlayer( 3039): reset_l()
,V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 3039): mSecMediaClock clear
,V/MediaPlayer( 7876): decode(63, 26959684, 21552)
,V/MediaPlayerService( 3039): decode(30, 26959684, 21552)
,V/MediaPlayerService( 3039): player type = 3
V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): constructor
,V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
,V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): StagefrightPlayer
V/AwesomePlayer( 3039): setListener
V/StagefrightPlayer( 3039): initCheck
,V/AwesomePlayer( 3039): setAudioSink
V/StagefrightPlayer( 3039): setDataSource(30, 26959684, 21552)
V/AwesomePlayer( 3039): reset_l()
,V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442b6d08, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
,V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 3039): mSecMediaClock clear
,V/AwesomePlayer( 3039): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 3039): mBitrate = -1 bits/sec
V/AwesomePlayer( 3039): current audio track index (0) is added to vector
V/AwesomePlayer( 3039): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 3039): AwesomePlayer::setDataSource_l():: This is not a DRM content
,V/MediaPlayerService( 3039): prepare
V/AwesomePlayer( 3039): prepareAsync
V/MediaPlayerService( 3039): wait for prepare
V/AwesomePlayer( 3039): onPrepareAsyncEvent
I/SecMediaClock( 3039): SecMediaClock constructor
I/SecMediaClock( 3039): reset
V/AwesomePlayer( 3039): initAudioDecoder
V/AwesomePlayer( 3039): checkOffloadExceptions is true
,I/OMXCodec( 3039): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 3039): mDispatchers.add
I/OMXCodec( 3039): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 3039): finishAsyncPrepare_l
V/AwesomePlayer( 3039): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 3039): notify(0x442b6d08, 200, 973, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442b6d08, 5, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442b6d08, 1, 0, 0)
V/AudioCache( 3039): prepared
V/AudioCache( 3039): wait - success
V/MediaPlayerService( 3039): start
,V/StagefrightPlayer( 3039): start
V/AwesomePlayer( 3039): play
V/AwesomePlayer( 3039): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 3039): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 3039): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 3039): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442b6d08, 6, 0, 0)
,V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): addBatteryData
,V/MediaPlayerService( 3039): wait for playback complete
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 3039): postAudioEOS delayUs (0)
V/AwesomePlayer( 3039): onCheckAudioStatus
V/AwesomePlayer( 3039): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 3039): onStreamDone
V/AwesomePlayer( 3039): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 3039): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442b6d08, 2, 0, 0)
V/AudioCache( 3039): playback complete - thread will wake up later
,V/AwesomePlayer( 3039): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442b6d08, 7, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 3039): addBatteryData
V/AudioCache( 3039): wait - success
V/StagefrightPlayer( 3039): reset
,V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442b6d08, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop() sendCommand(0x49, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 3039): reset out
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 3039): SecMediaClock destructor
,V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): ~StagefrightPlayer
V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/AwesomePlayer( 3039): destructor
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/MediaPlayer( 7876): decode(64, 34130460, 4230)
,V/MediaPlayerService( 3039): decode(30, 34130460, 4230)
,V/MediaPlayerService( 3039): player type = 3
V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): constructor
V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): StagefrightPlayer
V/AwesomePlayer( 3039): setListener
V/StagefrightPlayer( 3039): initCheck
V/AwesomePlayer( 3039): setAudioSink
V/StagefrightPlayer( 3039): setDataSource(30, 34130460, 4230)
,V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442c06d0, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
,V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 3039): mSecMediaClock clear
V/AwesomePlayer( 3039): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 3039): mBitrate = -1 bits/sec
V/AwesomePlayer( 3039): current audio track index (0) is added to vector
V/AwesomePlayer( 3039): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 3039): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 3039): prepare
V/AwesomePlayer( 3039): prepareAsync
V/MediaPlayerService( 3039): wait for prepare
V/AwesomePlayer( 3039): onPrepareAsyncEvent
I/SecMediaClock( 3039): SecMediaClock constructor
,I/SecMediaClock( 3039): reset
V/AwesomePlayer( 3039): initAudioDecoder
V/AwesomePlayer( 3039): checkOffloadExceptions is true
,I/OMXCodec( 3039): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 3039): mDispatchers.add
I/OMXCodec( 3039): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 3039): finishAsyncPrepare_l
V/AwesomePlayer( 3039): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 3039): notify(0x442c06d0, 200, 973, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442c06d0, 5, 0, 0)
V/AudioCache( 3039): ignored
,V/AwesomePlayer( 3039): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442c06d0, 1, 0, 0)
V/AudioCache( 3039): prepared
V/AudioCache( 3039): wait - success
V/MediaPlayerService( 3039): start
V/StagefrightPlayer( 3039): start
V/AwesomePlayer( 3039): play
V/AwesomePlayer( 3039): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 3039): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache( 3039): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer( 3039): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442c06d0, 6, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): addBatteryData
,V/MediaPlayerService( 3039): wait for playback complete
V/AwesomePlayer( 3039): postAudioEOS delayUs (0)
V/AwesomePlayer( 3039): onCheckAudioStatus
V/AwesomePlayer( 3039): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 3039): onStreamDone
V/AwesomePlayer( 3039): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer( 3039): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442c06d0, 2, 0, 0)
V/AudioCache( 3039): playback complete - thread will wake up later
V/AwesomePlayer( 3039): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442c06d0, 7, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=1)
V/AudioCache( 3039): wait - success
V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): addBatteryData
,V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442c06d0, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop() sendCommand(0x4a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/AudioPlayer( 3039): reset out
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 3039): SecMediaClock destructor
V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): ~StagefrightPlayer
V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/AwesomePlayer( 3039): destructor
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/MediaPlayer( 7876): decode(65, 26923896, 9400)
,V/MediaPlayerService( 3039): decode(31, 26923896, 9400)
V/MediaPlayerService( 3039): player type = 3
,V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): constructor
V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): StagefrightPlayer
V/AwesomePlayer( 3039): setListener
V/StagefrightPlayer( 3039): initCheck
V/AwesomePlayer( 3039): setAudioSink
V/StagefrightPlayer( 3039): setDataSource(31, 26923896, 9400)
V/AwesomePlayer( 3039): reset_l()
,V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x4408aa38, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 3039): mSecMediaClock clear
V/AwesomePlayer( 3039): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 3039): mBitrate = -1 bits/sec
V/AwesomePlayer( 3039): current audio track index (0) is added to vector
V/AwesomePlayer( 3039): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 3039): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 3039): prepare
V/AwesomePlayer( 3039): prepareAsync
V/MediaPlayerService( 3039): wait for prepare
V/AwesomePlayer( 3039): onPrepareAsyncEvent
I/SecMediaClock( 3039): SecMediaClock constructor
I/SecMediaClock( 3039): reset
V/AwesomePlayer( 3039): initAudioDecoder
V/AwesomePlayer( 3039): checkOffloadExceptions is true
,I/OMXCodec( 3039): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 3039): mDispatchers.add
,I/OMXCodec( 3039): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 3039): finishAsyncPrepare_l
V/AwesomePlayer( 3039): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 3039): notify(0x4408aa38, 200, 973, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x4408aa38, 5, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x4408aa38, 1, 0, 0)
V/AudioCache( 3039): prepared
V/AudioCache( 3039): wait - success
V/MediaPlayerService( 3039): start
V/StagefrightPlayer( 3039): start
V/AwesomePlayer( 3039): play
V/AwesomePlayer( 3039): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 3039): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache( 3039): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer( 3039): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x4408aa38, 6, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): addBatteryData
,V/MediaPlayerService( 3039): wait for playback complete
,I/AudioPlayer( 3039): First fillBuffer call!!
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 3039): postAudioEOS delayUs (0)
V/AwesomePlayer( 3039): onCheckAudioStatus
V/AwesomePlayer( 3039): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 3039): onStreamDone
V/AwesomePlayer( 3039): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 3039): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x4408aa38, 2, 0, 0)
V/AudioCache( 3039): playback complete - thread will wake up later
V/AwesomePlayer( 3039): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x4408aa38, 7, 0, 0)
V/AudioCache( 3039): ignored
,V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 3039): addBatteryData
V/AudioCache( 3039): wait - success
V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
,V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x4408aa38, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop() sendCommand(0x4b, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 3039): reset out
,V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 3039): SecMediaClock destructor
V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): ~StagefrightPlayer
V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
,V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
,V/AwesomePlayer( 3039): destructor
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 3039): mSecMediaClock clear
V/MediaPlayer( 7876): decode(66, 30512272, 44276)
,V/MediaPlayerService( 3039): decode(30, 30512272, 44276)
,V/MediaPlayerService( 3039): player type = 3
V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): constructor
V/AwesomePlayer( 3039): setDefault
,V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
,V/StagefrightPlayer( 3039): StagefrightPlayer
V/AwesomePlayer( 3039): setListener
V/StagefrightPlayer( 3039): initCheck
V/AwesomePlayer( 3039): setAudioSink
V/StagefrightPlayer( 3039): setDataSource(30, 30512272, 44276)
,V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442beaf0, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
,V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 3039): mSecMediaClock clear
,V/AwesomePlayer( 3039): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 3039): mBitrate = -1 bits/sec
,V/AwesomePlayer( 3039): current audio track index (0) is added to vector
V/AwesomePlayer( 3039): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 3039): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 3039): prepare
,V/AwesomePlayer( 3039): prepareAsync
,V/MediaPlayerService( 3039): wait for prepare
V/AwesomePlayer( 3039): onPrepareAsyncEvent
I/SecMediaClock( 3039): SecMediaClock constructor
I/SecMediaClock( 3039): reset
V/AwesomePlayer( 3039): initAudioDecoder
V/AwesomePlayer( 3039): checkOffloadExceptions is true
,I/OMXCodec( 3039): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 3039): mDispatchers.add
I/OMXCodec( 3039): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 3039): finishAsyncPrepare_l
V/AwesomePlayer( 3039): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 3039): notify(0x442beaf0, 200, 973, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442beaf0, 5, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442beaf0, 1, 0, 0)
V/AudioCache( 3039): prepared
V/AudioCache( 3039): wait - success
V/MediaPlayerService( 3039): start
V/StagefrightPlayer( 3039): start
V/AwesomePlayer( 3039): play
V/AwesomePlayer( 3039): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 3039): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 3039): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 3039): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442beaf0, 6, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): addBatteryData
V/MediaPlayerService( 3039): wait for playback complete
,I/AudioPlayer( 3039): First fillBuffer call!!
,D/SO_AGENT( 7534): [ServerTimeReceiver.java(Line:44/Method:onReceive)] Receive broadcast meassage:android.intent.action.TIME_SET
,I/SO_AGENT( 7534): [ServerTimeReceiver.java(Line:47/Method:onReceive)] No action is available before server time settings
,I/SA      ( 6664): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 3039): postAudioEOS delayUs (0)
,V/AwesomePlayer( 3039): onCheckAudioStatus
V/AwesomePlayer( 3039): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 3039): onStreamDone
V/AwesomePlayer( 3039): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer( 3039): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442beaf0, 2, 0, 0)
V/AudioCache( 3039): playback complete - thread will wake up later
V/AwesomePlayer( 3039): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442beaf0, 7, 0, 0)
V/AudioCache( 3039): ignored
,V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 3039): addBatteryData
V/AudioCache( 3039): wait - success
,V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442beaf0, 8, 0, 0)
V/AudioCache( 3039): ignored
,V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop() sendCommand(0x4c, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/AudioPlayer( 3039): reset out
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 3039): SecMediaClock destructor
V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): ~StagefrightPlayer
,V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 3039): mSecMediaClock clear
V/AwesomePlayer( 3039): destructor
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 3039): mSecMediaClock clear
V/MediaPlayer( 7876): decode(67, 30472480, 29256)
,V/MediaPlayerService( 3039): decode(29, 30472480, 29256)
V/MediaPlayerService( 3039): player type = 3
V/AwesomePlayer( 3039): setDefault
,V/AwesomePlayer( 3039): constructor
V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): StagefrightPlayer
V/AwesomePlayer( 3039): setListener
V/StagefrightPlayer( 3039): initCheck
V/AwesomePlayer( 3039): setAudioSink
V/StagefrightPlayer( 3039): setDataSource(29, 30472480, 29256)
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442bc7e0, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 3039): mSecMediaClock clear
V/AwesomePlayer( 3039): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 3039): mBitrate = -1 bits/sec
V/AwesomePlayer( 3039): current audio track index (0) is added to vector
V/AwesomePlayer( 3039): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 3039): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 3039): prepare
V/AwesomePlayer( 3039): prepareAsync
V/MediaPlayerService( 3039): wait for prepare
V/AwesomePlayer( 3039): onPrepareAsyncEvent
I/SecMediaClock( 3039): SecMediaClock constructor
I/SecMediaClock( 3039): reset
V/AwesomePlayer( 3039): initAudioDecoder
V/AwesomePlayer( 3039): checkOffloadExceptions is true
,I/OMXCodec( 3039): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 3039): mDispatchers.add
I/OMXCodec( 3039): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 3039): finishAsyncPrepare_l
V/AwesomePlayer( 3039): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 3039): notify(0x442bc7e0, 200, 973, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442bc7e0, 5, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442bc7e0, 1, 0, 0)
V/AudioCache( 3039): prepared
V/AudioCache( 3039): wait - success
V/MediaPlayerService( 3039): start
V/StagefrightPlayer( 3039): start
V/AwesomePlayer( 3039): play
V/AwesomePlayer( 3039): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 3039): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 3039): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 3039): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442bc7e0, 6, 0, 0)
V/AudioCache( 3039): ignored
,V/AwesomePlayer( 3039): addBatteryData
,V/MediaPlayerService( 3039): wait for playback complete
,D/Mms/MessagingNotification( 5961): [start]    nonBlockingUpdateMessageIndicator()
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 3039): postAudioEOS delayUs (0)
V/AwesomePlayer( 3039): onCheckAudioStatus
V/AwesomePlayer( 3039): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 3039): onStreamDone
V/AwesomePlayer( 3039): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 3039): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442bc7e0, 2, 0, 0)
V/AudioCache( 3039): playback complete - thread will wake up later
V/AwesomePlayer( 3039): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442bc7e0, 7, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 3039): addBatteryData
V/AudioCache( 3039): wait - success
,V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442bc7e0, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop() sendCommand(0x4d, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 3039): reset out
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 3039): SecMediaClock destructor
V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): ~StagefrightPlayer
V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/AwesomePlayer( 3039): destructor
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/MediaPlayer( 7876): decode(68, 34078380, 52024)
,V/MediaPlayerService( 3039): decode(30, 34078380, 52024)
V/MediaPlayerService( 3039): player type = 3
V/AwesomePlayer( 3039): setDefault
,V/AwesomePlayer( 3039): constructor
D/LocationManagerService( 3236): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): StagefrightPlayer
V/AwesomePlayer( 3039): setListener
V/StagefrightPlayer( 3039): initCheck
V/AwesomePlayer( 3039): setAudioSink
V/StagefrightPlayer( 3039): setDataSource(30, 34078380, 52024)
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442bfa40, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 3039): mSecMediaClock clear
V/AwesomePlayer( 3039): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 3039): mBitrate = -1 bits/sec
V/AwesomePlayer( 3039): current audio track index (0) is added to vector
V/AwesomePlayer( 3039): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 3039): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 3039): prepare
V/AwesomePlayer( 3039): prepareAsync
V/MediaPlayerService( 3039): wait for prepare
V/AwesomePlayer( 3039): onPrepareAsyncEvent
I/SecMediaClock( 3039): SecMediaClock constructor
I/SecMediaClock( 3039): reset
V/AwesomePlayer( 3039): initAudioDecoder
V/AwesomePlayer( 3039): checkOffloadExceptions is true
,I/OMXCodec( 3039): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 3039): mDispatchers.add
I/OMXCodec( 3039): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 3039): finishAsyncPrepare_l
V/AwesomePlayer( 3039): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 3039): notify(0x442bfa40, 200, 973, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442bfa40, 5, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442bfa40, 1, 0, 0)
V/AudioCache( 3039): prepared
V/AudioCache( 3039): wait - success
V/MediaPlayerService( 3039): start
V/StagefrightPlayer( 3039): start
V/AwesomePlayer( 3039): play
V/AwesomePlayer( 3039): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 3039): startAudioPlayer_l, sendErrorNotification (0)
D/Mms/MessagingNotification( 5961): sDisableVibrateForCamera = false
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 3039): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer( 3039): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442bfa40, 6, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): addBatteryData
,I/AudioPlayer( 3039): First fillBuffer call!!
,V/MediaPlayerService( 3039): wait for playback complete
,D/Mms/MessagingNotification( 5961): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 5961): isDefault true
,I/SELinux ( 7960): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7960):  
I/ActivityManager( 3236): Killing 6092:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty #43
,D/TP/MmsSmsProvider( 3672): match 200:Elapsed time : 1.515 ms
,I/SELinux ( 7960): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7960):  
I/SELinux ( 7960):  
,I/SELinux ( 7960): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7960): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7960): >>>>> Normal User
,E/dalvikvm( 7960): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10064 ]
,D/TP/MmsSmsProvider( 3672): match 8:Elapsed time : 16.875 ms
,E/SELinux ( 7960): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7960): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7960): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7960): Added TimaKesytore provider
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 3039): postAudioEOS delayUs (0)
V/AwesomePlayer( 3039): onCheckAudioStatus
V/AwesomePlayer( 3039): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 3039): onStreamDone
V/AwesomePlayer( 3039): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 3039): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442bfa40, 2, 0, 0)
V/AudioCache( 3039): playback complete - thread will wake up later
V/AwesomePlayer( 3039): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442bfa40, 7, 0, 0)
V/AudioCache( 3039): ignored
,V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 3039): addBatteryData
V/AudioCache( 3039): wait - success
,V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x442bfa40, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop() sendCommand(0x4e, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 3039): reset out
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 3039): SecMediaClock destructor
V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): ~StagefrightPlayer
V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/AwesomePlayer( 3039): destructor
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 3039): mSecMediaClock clear
V/MediaPlayer( 7876): decode(69, 30556608, 9226)
,V/MediaPlayerService( 3039): decode(30, 30556608, 9226)
D/BadgeProvider( 7756): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
V/MediaPlayerService( 3039): player type = 3
V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): constructor
V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): StagefrightPlayer
V/AwesomePlayer( 3039): setListener
V/StagefrightPlayer( 3039): initCheck
V/AwesomePlayer( 3039): setAudioSink
V/StagefrightPlayer( 3039): setDataSource(30, 30556608, 9226)
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43b64948, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 3039): mSecMediaClock clear
V/AwesomePlayer( 3039): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 3039): mBitrate = -1 bits/sec
V/AwesomePlayer( 3039): current audio track index (0) is added to vector
V/AwesomePlayer( 3039): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 3039): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 3039): prepare
V/AwesomePlayer( 3039): prepareAsync
V/MediaPlayerService( 3039): wait for prepare
V/AwesomePlayer( 3039): onPrepareAsyncEvent
I/SecMediaClock( 3039): SecMediaClock constructor
I/SecMediaClock( 3039): reset
V/AwesomePlayer( 3039): initAudioDecoder
V/AwesomePlayer( 3039): checkOffloadExceptions is true
,I/OMXCodec( 3039): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 3039): mDispatchers.add
I/OMXCodec( 3039): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 3039): finishAsyncPrepare_l
V/AwesomePlayer( 3039): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 3039): notify(0x43b64948, 200, 973, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43b64948, 5, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43b64948, 1, 0, 0)
V/AudioCache( 3039): prepared
V/AudioCache( 3039): wait - success
V/MediaPlayerService( 3039): start
V/StagefrightPlayer( 3039): start
V/AwesomePlayer( 3039): play
V/AwesomePlayer( 3039): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 3039): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 3039): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 3039): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43b64948, 6, 0, 0)
V/AudioCache( 3039): ignored
,V/AwesomePlayer( 3039): addBatteryData
,V/MediaPlayerService( 3039): wait for playback complete
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 3039): postAudioEOS delayUs (0)
V/AwesomePlayer( 3039): onCheckAudioStatus
V/AwesomePlayer( 3039): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 3039): onStreamDone
V/AwesomePlayer( 3039): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 3039): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43b64948, 2, 0, 0)
V/AudioCache( 3039): playback complete - thread will wake up later
V/AwesomePlayer( 3039): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43b64948, 7, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 3039): addBatteryData
V/AudioCache( 3039): wait - success
V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43b64948, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop() sendCommand(0x4f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 3039): reset out
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 3039): SecMediaClock destructor
V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): ~StagefrightPlayer
V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/AwesomePlayer( 3039): destructor
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
,V/MediaPlayer( 7876): decode(70, 26989388, 4509)
V/MediaPlayerService( 3039): decode(30, 26989388, 4509)
,D/BadgeProvider( 7756): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 7756): sendNotify, [notify] : null
V/MediaPlayerService( 3039): player type = 3
V/AwesomePlayer( 3039): setDefault
V/AwesomePlayer( 3039): constructor
V/AwesomePlayer( 3039): setDefault
D/BadgeProvider( 7756): update, [uri] : content://com.sec.badge/apps/2
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): StagefrightPlayer
V/AwesomePlayer( 3039): setListener
V/StagefrightPlayer( 3039): initCheck
V/AwesomePlayer( 3039): setAudioSink
V/StagefrightPlayer( 3039): setDataSource(30, 26989388, 4509)
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43b64948, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 3039): mSecMediaClock clear
D/BadgeProvider( 7756): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7756): update, [UpdateCount] : 1
,D/Launcher.Model( 3692): reloadBadges entered.
V/AwesomePlayer( 3039): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 3039): mBitrate = -1 bits/sec
V/AwesomePlayer( 3039): current audio track index (0) is added to vector
V/AwesomePlayer( 3039): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 3039): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 3039): prepare
V/AwesomePlayer( 3039): prepareAsync
V/MediaPlayerService( 3039): wait for prepare
V/AwesomePlayer( 3039): onPrepareAsyncEvent
I/SecMediaClock( 3039): SecMediaClock constructor
I/SecMediaClock( 3039): reset
V/AwesomePlayer( 3039): initAudioDecoder
V/AwesomePlayer( 3039): checkOffloadExceptions is true
,I/OMXCodec( 3039): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 3039): mDispatchers.add
I/OMXCodec( 3039): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 3039): finishAsyncPrepare_l
V/AwesomePlayer( 3039): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 3039): notify(0x43b64948, 200, 973, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43b64948, 5, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43b64948, 1, 0, 0)
V/AudioCache( 3039): prepared
V/AudioCache( 3039): wait - success
V/MediaPlayerService( 3039): start
V/StagefrightPlayer( 3039): start
V/AwesomePlayer( 3039): play
V/AwesomePlayer( 3039): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 3039): startAudioPlayer_l, sendErrorNotification (0)
D/Mms/MessagingNotification( 5961): setBadgeCount(), count=0
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 3039):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 3039): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 3039): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43b64948, 6, 0, 0)
V/AudioCache( 3039): ignored
,V/AwesomePlayer( 3039): addBatteryData
,V/MediaPlayerService( 3039): wait for playback complete
,D/MessagingNotification( 5961): remove alarm
V/AwesomePlayer( 3039): postAudioEOS delayUs (0)
V/AwesomePlayer( 3039): onCheckAudioStatus
V/AwesomePlayer( 3039): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 3039): onStreamDone
V/AwesomePlayer( 3039): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 3039): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43b64948, 2, 0, 0)
V/AudioCache( 3039): playback complete - thread will wake up later
V/AwesomePlayer( 3039): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43b64948, 7, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 3039): addBatteryData
V/AudioCache( 3039): wait - success
V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 3039): notify(0x43b64948, 8, 0, 0)
V/AudioCache( 3039): ignored
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stop() sendCommand(0x50, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 3039): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 3039): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 3039): reset out
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 3039): SecMediaClock destructor
V/AwesomePlayer( 3039): mSecMediaClock clear
V/StagefrightPlayer( 3039): ~StagefrightPlayer
V/StagefrightPlayer( 3039): reset
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 3039): mSecMediaClock clear
V/AwesomePlayer( 3039): destructor
V/AwesomePlayer( 3039): reset_l()
V/AwesomePlayer( 3039): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 3039): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 3039): mAudioTrackVector clear
V/AwesomePlayer( 3039): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 3039): mSecMediaClock clear
,D/Mms/MessagingNotification( 5961): [end]    nonBlockingUpdateMessageIndicator()
,D/Mms/MessagingNotification( 5961): updateAllHistoryAsRead()
,D/dalvikvm( 7960): GC_CONCURRENT freed 3002K, 33% free 9566K/14120K, paused 4ms+5ms, total 33ms
,D/dalvikvm( 7960): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/LocationManagerService( 3236): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/CaptivePortalTracker( 3236): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker( 3236): Checking http://216.58.209.46/generate_204
D/ConnectivityService( 3236): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/ActivityThread( 3236): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/com.samsung.app( 7651): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidintentactionTIME_SET
,I/ Time Manager ( 7960): Time Difference not stored. TIME_DIFFERENCE
,D/com.samsung.app( 7651): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/SELinux ( 7984): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7984):  
,I/ActivityManager( 3236): Killing 5152:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
,I/System.out( 3236): Thread-162(HTTPLog):isShipBuild true
,I/System.out( 3236): Thread-162(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/SELinux ( 7984): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7984):  
I/SELinux ( 7984):  
,I/SELinux ( 7984): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7984): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7984): >>>>> Normal User
,E/dalvikvm( 7984): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10088 ]
,E/SELinux ( 7984): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/CaptivePortalTracker( 3236): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 3236): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 3236): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 3236): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TimaKeyStoreProvider( 7984): in addTimaSignatureService
D/ConnectivityService( 3236): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/TimaKeyStoreProvider( 7984): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7984): Added TimaKesytore provider
,D/dalvikvm( 7984): GC_CONCURRENT freed 2989K, 33% free 9571K/14116K, paused 4ms+1ms, total 25ms
,D/dalvikvm( 7984): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/SELinux ( 7998): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7998):  
I/ActivityManager( 3236): Killing 6686:com.sec.android.service.cm/u0a82 (adj 15): empty #43
,I/SELinux ( 7998): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7998):  
I/SELinux ( 7998):  
,I/SELinux ( 7998): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7998): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7998): >>>>> Normal User
,E/dalvikvm( 7998): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 7998): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7998): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7998): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7998): Added TimaKesytore provider
,D/dalvikvm( 7998): GC_CONCURRENT freed 3027K, 33% free 9544K/14120K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7998): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/elm:14132( 7998): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14132( 7998): ELMEngine.ELMEngine( context ).
,D/elm:14132( 7998): MDMBridge.setEnterpriseBridge()
,D/dalvikvm( 3236): GC_EXPLICIT freed 1781K, 55% free 24784K/54704K, paused 6ms+19ms, total 167ms
,D/elm:14132( 7998): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
I/ActivityManager( 3236): Waited long enough for: ServiceRecord{434bfb38 u0 pl.k2.droidoaudioteka/.services.DownloadService}
I/ActivityManager( 3236): Waited long enough for: ServiceRecord{43784f08 u0 pl.k2.droidoaudioteka/.services.PlayerService}
,I/knox    ( 5352): MainReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,D/elm:14132( 7998): ElmAgentService : onCreate()
W/ContextImpl( 5352): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,D/knox    ( 5352): MainReceiver.listeningToTimeDateChanges( context, intent ).
,I/knox    ( 5352): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver },
,D/elm:14132( 7998): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService },
D/knox    ( 5352): KNOXAgentService : onCreate()
D/knox    ( 5352): KNOXAgentService : set alarms for deniallog and usage data upload
,D/elm:14132( 7998): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/knox    ( 5352): KNOXAgentService. startJobThread() start
I/SELinux ( 8016): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8016):  
D/knox    ( 5352): KNOXAgentService. JobThread()
,D/knox    ( 5352): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 5352): KNOXAgentService. startJobThread() wait
,D/elm:14132( 7998): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14132( 7998): ModuleBase.resetCalllogAPIAlarm()
,D/knox    ( 5352): KNOXAgentService : onDestroy().
,D/knox    ( 5352): ModuleBase.cancelAllAlarmManageModule()
,D/elm:14132( 7998): ModuleBase.ModifySetAlarm()
,D/elm:14132( 7998): MDMBridge.getInstance()
,D/elm:14132( 7998): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 7998): ElmAgentService : onDestroy().
I/ActivityManager( 3236): Killing 6698:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty #43
,I/SELinux ( 8016): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8016):  
I/SELinux ( 8016):  
,I/SELinux ( 8016): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8016): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 8016): >>>>> Normal User
,E/dalvikvm( 8016): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10145 ]
,E/SELinux ( 8016): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 8016): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8016): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8016): Added TimaKesytore provider
,E/SPPClientService( 5844): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,D/dalvikvm( 8016): GC_CONCURRENT freed 2997K, 33% free 9563K/14116K, paused 3ms+1ms, total 28ms
,D/dalvikvm( 8016): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/SELinux ( 8029): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8029):  
,I/SELinux ( 8029): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8029):  
I/SELinux ( 8029):  
,I/SELinux ( 8029): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8029): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8029): >>>>> Normal User
,E/dalvikvm( 8029): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10168 ]
,E/SELinux ( 8029): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/SPPClientService( 5844): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,D/TimaKeyStoreProvider( 8029): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8029): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8029): Added TimaKesytore provider
,E/SPPClientService( 5844): [a] [ConnectionManager] Connection is already disconnected.
V/AlarmManager( 3236): waitForAlarm result :4
V/AlarmManager( 3236): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm( 8029): GC_CONCURRENT freed 3000K, 33% free 9562K/14116K, paused 2ms+2ms, total 35ms,
,D/dalvikvm( 8029): WAIT_FOR_CONCURRENT_GC blocked 33ms
,I/ActivityManager( 3236): Killing 6724:com.samsung.helphub/1000 (adj 15): empty #43,
,D/daemonapp( 5637): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR,
D/daemonapp( 5637): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng,
,D/daemonapp( 5637): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings,
,D/daemonapp( 5637): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo,
,D/daemonapp( 5637): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionTIME_SET, run:true
D/comsamsunglog( 5637): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5637): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5637): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5637): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5637): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5637): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5637): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5637): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5637): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5637): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5637): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/comdaemonstockapp( 5637): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 5637): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,I/CheckinService( 4176): Checkin interval check for package: unspecified last checkin: 1452482426840 min interval config: 0 actual interval: 114287875
,I/DBG_DM  ( 4982): [3.19.140541][Line:2663][xdmDbsqlGetFUMOStatus] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 4982): [3.19.140541][Line:1835][xtpAdpGetUserCancel] flag is : false
,I/DBG_DM  ( 4982): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,I/DBG_DM  ( 4982): [3.19.140541][Line:174][onReceive] sec.fota.polling.intent.RECEIVE
,I/DBG_DM  ( 4982): [3.19.140541][Line:536][xdmBroadCastCheckReceivedNfcMode] nMode : 0
,I/DBG_DM  ( 4982): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,I/DBG_DM  ( 4982): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4982): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,I/DBG_DM  ( 4982): [3.19.140541][Line:258][xuiAdpUserInitiate] 
,I/DBG_DM  ( 4982): [3.19.140541][Line:3767][xdbGetWifiOnlyFlag] Wifi_Only_flag : true
,I/DBG_DM  ( 4982): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/DBG_DM  ( 4982): [3.19.140541][Line:283][xuiAdpUserInitiate] bWifiOnly flag : true
,I/DBG_DM  ( 4982): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,I/DBG_DM  ( 4982): [3.19.140541][Line:1835][xtpAdpGetUserCancel] flag is : false
,I/DBG_DM  ( 4982): [3.19.140541][Line:1733][xfotaDlAgentHdlrGetUpdateProcessingState] bUpdateProcessing : false
,I/DBG_DM  ( 4982): [3.19.140541][Line:769][xdmUIEvent] XUI_DL_UPDATE_START
,I/DBG_DM  ( 4982): [3.19.140541][Line:369][handleMessage] event ->214
,I/SELinux ( 8045): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8045):  
,I/DBG_DM  ( 4982): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 4982): [3.19.140541][Line:2008][xdmCallUiFotaInstall] 
,D/dalvikvm( 3035): GC_EXPLICIT freed 42K, 15% free 9499K/11096K, paused 2ms+4ms, total 31ms
,I/SELinux ( 8045): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8045):  
I/SELinux ( 8045):  
,I/SELinux ( 8045): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8045): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 8045): >>>>> Normal User
,E/dalvikvm( 8045): >>>>> com.android.providers.calendar [ userId:0 | appId:10045 ]
,E/SELinux ( 8045): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/DBG_DM  ( 4982): [3.19.140541][Line:729][xdmUIEvent] XUI_DL_UPDATE_CONFIRM
W/ContextImpl( 4982): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 com.wssyncmldm.XDMService.xdmCallUiFotaInstall:2023 com.wssyncmldm.XDMService$1.handleMessage:372 android.os.Handler.dispatchMessage:102 
,I/DBG_DM  ( 4982): [3.19.140541][Line:890][xdmUnRegisterBatteryReceiver] 
,D/dalvikvm( 3035): GC_EXPLICIT freed <1K, 15% free 9499K/11096K, paused 3ms+3ms, total 26ms
,I/DBG_DM  ( 4982): [3.19.140541][Line:1320][xdmCheckIdleScreen] Idle Screen : false
,E/DBG_DM  ( 4982): Warning!!! [3.19.140541][Line:898][xdmUnRegisterBatteryReceiver] didn't register
,E/DBG_DM  ( 4982): Warning!!! [3.19.140541][Line:899][xdmUnRegisterBatteryReceiver] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.XDMService$3@423dfec0
,D/TimaKeyStoreProvider( 8045): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8045): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8045): Added TimaKesytore provider
,I/DBG_DM  ( 4982): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,D/dalvikvm( 3035): GC_EXPLICIT freed <1K, 15% free 9499K/11096K, paused 2ms+3ms, total 25ms
,I/DBG_DM  ( 4982): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 3236): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 3236): sendNotification(2) - 4
,I/SurfaceFlinger( 1919): id=31 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3236): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3236
D/dalvikvm( 8045): GC_CONCURRENT freed 3003K, 33% free 9558K/14116K, paused 2ms+2ms, total 28ms
D/dalvikvm( 8045): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/Headlines( 7665): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7665): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7665): Breath 8167 latestRequest time : 1452596707268 current time : 1452596715435
,D/dalvikvm( 3760): GC_CONCURRENT freed 1882K, 26% free 10918K/14640K, paused 3ms+5ms, total 45ms
,D/GCM     ( 3760): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,D/Mms/MessagesLockscreen( 5961): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
,W/Binder  ( 3500): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 3500): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
W/Binder  ( 3500): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
W/Binder  ( 3500): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
W/Binder  ( 3500): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
W/Binder  ( 3500): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
W/Binder  ( 3500): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
W/Binder  ( 3500): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
W/Binder  ( 3500): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
W/Binder  ( 3500): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
W/Binder  ( 3500): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
W/Binder  ( 3500): 	at android.view.View.inflate(View.java:18495)
W/Binder  ( 3500): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
W/Binder  ( 3500): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
W/Binder  ( 3500): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
W/Binder  ( 3500): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
W/Binder  ( 3500): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
W/Binder  ( 3500): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 3500): 	at dalvik.system.NativeStart.run(Native Method)
W/Binder  ( 3500): Caused by: java.lang.reflect.InvocationTargetException
W/Binder  ( 3500): 	at java.lang.reflect.Constructor.constructNative(Native Method)
W/Binder  ( 3500): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
W/Binder  ( 3500): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
W/Binder  ( 3500): 	... 16 more
W/Binder  ( 3500): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
W/Binder  ( 3500): 	at android.os.Handler.<init>(Handler.java:200)
W/Binder  ( 3500): 	at android.os.Handler.<init>(Handler.java:114)
W/Binder  ( 3500): 	at android.widget.TextClock.<init>(TextClock.java:130)
W/Binder  ( 3500): 	at android.widget.TextClock.<init>(TextClock.java:191)
W/Binder  ( 3500): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
W/Binder  ( 3500): 	... 19 more
,E/JavaBinder( 3500): *** Uncaught remote exception!  (Exceptions are not yet supported across processes.)
E/JavaBinder( 3500): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
E/JavaBinder( 3500): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
E/JavaBinder( 3500): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
E/JavaBinder( 3500): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
E/JavaBinder( 3500): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
E/JavaBinder( 3500): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
E/JavaBinder( 3500): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
E/JavaBinder( 3500): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
E/JavaBinder( 3500): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
E/JavaBinder( 3500): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
E/JavaBinder( 3500): 	at android.view.View.inflate(View.java:18495)
E/JavaBinder( 3500): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
E/JavaBinder( 3500): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
E/JavaBinder( 3500): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
E/JavaBinder( 3500): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
E/JavaBinder( 3500): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
E/JavaBinder( 3500): 	at android.os.Binder.execTransact(Binder.java:404)
E/JavaBinder( 3500): 	at dalvik.system.NativeStart.run(Native Method)
E/JavaBinder( 3500): Caused by: java.lang.reflect.InvocationTargetException
E/JavaBinder( 3500): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/JavaBinder( 3500): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/JavaBinder( 3500): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
E/JavaBinder( 3500): 	... 16 more
E/JavaBinder( 3500): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
E/JavaBinder( 3500): 	at android.os.Handler.<init>(Handler.java:200)
E/JavaBinder( 3500): 	at android.os.Handler.<init>(Handler.java:114)
E/JavaBinder( 3500): 	at android.widget.TextClock.<init>(TextClock.java:130)
E/JavaBinder( 3500): 	at android.widget.TextClock.<init>(TextClock.java:191)
E/JavaBinder( 3500): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
E/JavaBinder( 3500): 	... 19 more
,E/SPPClientService( 5844): [g] getNetMCC return empty string
,E/SPPClientService( 5844): [g] getNetMNC return empty string
,I/jxcore-log( 7247): Test app app.js loaded
I/jxcore-log( 7247): 
,I/chromium( 7247): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager( 3236): Killing 6738:com.sec.kidsplat.installer/u0a160 (adj 15): empty #43
,I/jxcore-log( 7247): --= Surplus to requirements =--
I/jxcore-log( 7247): 
I/jxcore-log( 7247): ****TEST TOOK:  ms ****
I/jxcore-log( 7247): 
,I/jxcore-log( 7247): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7247): 
,D/AndroidRuntime( 8074): 
D/AndroidRuntime( 8074): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8074): CheckJNI is OFF
,D/AndroidRuntime( 8074): setted country_code = Poland
,D/AndroidRuntime( 8074): setted countryiso_code = PL
,D/AndroidRuntime( 8074): setted sales_code = PLS
D/AndroidRuntime( 8074): readGMSProperty: start
,D/AndroidRuntime( 8074): readGMSProperty: already setted!!
D/AndroidRuntime( 8074): readGMSProperty: end
,D/AndroidRuntime( 8074): addProductProperty: start
,D/dalvikvm( 8074): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 8074): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 8074): Trying to load lib libnativehelper.so 0x0
,D/dalvikvm( 8074): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 8074): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,E/memtrack( 8074): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 8074): failed to load memtrack module: -2
,D/dalvikvm( 8074): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,D/AndroidRuntime( 8074): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 3236): START PACKAGE DELETE: observer{1126007016}
D/PackageManager( 3236): pkg{<packageName>}
D/PackageManager( 3236): user{0}
,D/PackageManager( 3236): deletePackageAsUser : uid = 2000 userId = 0
,D/ApplicationPolicy( 3236): getApplicationUninstallationEnabled
,D/ApplicationPolicy( 3236): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService( 3236): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 3236): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManager( 3236): !@killApplicatoin: 10188, uninstall pkg
,I/ActivityManager( 3236): Killing 7247:com.test.thalitest/u0a188 (adj 0): stop com.test.thalitest
,D/PointerIcon( 3236): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3236): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3236): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 3236): setHoveringSpenCustomIcon IconType is same.1
,I/SurfaceFlinger( 1919): id=27 Removed EimLayer (5/11)
I/SurfaceFlinger( 1919): id=27 Removed EimLayer (-2/11)
I/SurfaceFlinger( 1919): id=26 Removed EimLayer (4/10)
,I/SurfaceFlinger( 1919): id=26 Removed EimLayer (-2/10)
,V/WindowManager( 3236): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/Launcher( 3692): onRestart, Launcher: 1114251384
,D/Launcher( 3692): onStart, Launcher: 1114251384
,D/Launcher.HomeView( 3692): onStart
,I/SurfaceFlinger( 1919): id=28 Removed NainActivit (6/9)
,I/SurfaceFlinger( 1919): id=28 Removed NainActivit (-2/9)
I/WindowState( 3236): WIN DEATH: Window{43180518 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger( 1919): id=28 Removed NainActivit (-2/9)
,I/SurfaceFlinger( 1919): id=32 createSurf (720x1280),1 flag=4, Mauncher
D/STATUSBAR-StatusBarManagerService( 3236): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 3236): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3236): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3236): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3236): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 3236): setHoveringSpenCustomIcon IconType is same.1
,D/StatusBarManagerService( 3236): tr p:3692,o:f
,D/PhoneStatusBar( 3500): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 3500): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 3236): semi p:3692,o:f
,W/ContextImpl( 3236): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 3236): Got RemoteException sending setActive(false) notification to pid 7247 uid 10188
,W/PackageSettings( 3236): Skipping PackageSetting{428c1a00 com.example.hello/10614} due to missing metadata
,D/PackageManager( 3236): checkUidPermission - Execution time: 184 ms
,D/PackageManager( 3236): checkUidPermission - Execution time: 121 ms
D/PackageManager( 3236): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10188, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/dalvikvm( 4176): WAIT_FOR_CONCURRENT_GC blocked 1ms,
,D/PackageManager( 3236): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10188, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,E/SamsungIME( 3879): mOCRHelper is null
,D/QuickConnect[1.1][2] ( 5410): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
,D/elm:14132( 7998): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,I/FPMS_FingerprintManagerService( 3521): onReceive: android.intent.action.PACKAGE_REMOVED
,D/dalvikvm( 6777): GC_EXPLICIT freed 158K, 31% free 9955K/14336K, paused 9ms+16ms, total 99ms
,D/RCPManagerService( 3236): PackageReceiver onReceive()
,W/GeofencerStateMachine( 3653): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 3236):   Action: "android.intent.action.SENDTO"
I/PackageManager( 3236):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 3236):   Scheme: "sms"
I/PackageManager( 3236): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/HarmonyEASService( 3236): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/dalvikvm( 3862): GC_EXPLICIT freed 1428K, 30% free 10015K/14116K, paused 18ms+6ms, total 158ms
,I/PackageManager( 3236):   Action: "android.intent.action.SENDTO"
I/PackageManager( 3236):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 3236):   Scheme: "smsto"
,I/PackageManager( 3236): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 6336): GC_EXPLICIT freed 2498K, 30% free 9882K/14116K, paused 37ms+5ms, total 200ms
,I/PackageManager( 3236):   Action: "android.intent.action.SENDTO"
I/PackageManager( 3236):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 3236):   Scheme: "mms"
,I/PackageManager( 3236): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 7998): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/dalvikvm( 4176): GC_EXPLICIT freed 1020K, 23% free 12267K/15788K, paused 9ms+10ms, total 274ms
,D/elm:14132( 7998): ElmAgentService : onCreate()
D/elm:14132( 7998): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) },
D/elm:14132( 7998): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 7998): MDMBridge.getInstance()
,D/elm:14132( 7998): MDMBridge.getAllLicenseInfoFromSDK(),
,D/elm:14132( 7998): MDMBridge.getAllLicenseInfoFromSDK(),
I/PackageManager( 3236):   Action: "android.intent.action.SENDTO"
I/PackageManager( 3236):   Category: "android.intent.category.DEFAULT",
,I/PackageManager( 3236):   Scheme: "mmsto",
I/PackageManager( 3236): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 8089): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 8089):  
I/PackageManager( 3236):   Action: "android.intent.action.SENDTO"
I/PackageManager( 3236):   Category: "android.intent.category.DEFAULT",
,I/PackageManager( 3236):   Scheme: "sms"
I/PackageManager( 3236): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/InputReader( 3236): Reconfiguring input devices.  changes=0x00000010,
,D/elm:14132( 7998): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
,I/PackageManager( 3236):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 3236):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 3236):   Scheme: "smsto"
I/PackageManager( 3236): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 8089): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8089):  
I/SELinux ( 8089):  
,I/SELinux ( 8089): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/elm:14132( 7998): ElmAgentService : onDestroy().
,E/SELinux ( 8089): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8089): >>>>> Normal User
,E/dalvikvm( 8089): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
,E/SELinux ( 8089): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/RegisteredServicesCache( 3682): empty dynamic service
,I/PackageManager( 3236):   Action: "android.intent.action.SENDTO"
I/PackageManager( 3236):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 3236):   Scheme: "mms"
I/PackageManager( 3236): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 8089): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8089): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8089): Added TimaKesytore provider
,I/PackageManager( 3236):   Action: "android.intent.action.SENDTO"
I/PackageManager( 3236):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 3236):   Scheme: "mmsto"
I/PackageManager( 3236): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/EnterpriseDeviceManagerService( 3236): Package has changed for user 0
,D/dalvikvm( 8089): GC_CONCURRENT freed 2997K, 33% free 9567K/14116K, paused 2ms+1ms, total 32ms
,D/dalvikvm( 8089): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/Resources( 3236): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService( 3236): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 3236): removePackageParticipantsLocked: uid=10188 #1
,W/Resources( 3236): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 8101): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8101):  
,I/SurfaceFlinger( 1919): id=31 Removed Uoast (8/9)
,I/ActivityManager( 3236): Killing 6750:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty #43
I/SurfaceFlinger( 1919): id=31 Removed Uoast (-2/9)
,D/PowerManagerService( 3236): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3236) eventTime = 289031
,D/PowerManagerService( 3236): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3236 (0x0)
,D/PowerManagerService( 3236): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3236, ws=WorkSource{1000}) (elapsedTime=3684)
,I/SELinux ( 8101): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8101):  
I/SELinux ( 8101):  
,I/SELinux ( 8101): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8101): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 8101): >>>>> Normal User
,E/dalvikvm( 8101): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
,E/SELinux ( 8101): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm( 3236): GC_EXPLICIT freed 2761K, 55% free 25094K/54704K, paused 23ms+23ms, total 563ms
D/PackageManager( 3236): delete sourFile : 
,D/TimaKeyStoreProvider( 8101): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8101): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8101): Added TimaKesytore provider
,E/SPPClientService( 5844): [b] __ProvisionReply__
,E/SPPClientService( 5844): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5844): [d] null
D/PackageManager( 3236): delete native library directory: 
,D/PackageManager( 3236): return delete result to caller: 1126007016
,D/PackageManager( 3236): returnCode: 1
D/AndroidRuntime( 8074): Shutting down VM
,D/dalvikvm( 8074): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+0ms, total 5ms
,I/PackageManager( 3236):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 3236):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 3236):   Scheme: "sms"
I/PackageManager( 3236): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 8101): GC_CONCURRENT freed 2993K, 33% free 9572K/14120K, paused 7ms+2ms, total 39ms
,D/dalvikvm( 8101): WAIT_FOR_CONCURRENT_GC blocked 32ms
I/PackageManager( 3236):   Action: "android.intent.action.SENDTO"
I/PackageManager( 3236):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 3236):   Scheme: "smsto"
I/PackageManager( 3236): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/SPPClientService( 5844): [g] getPLMN return empty string
,W/Resources( 3236): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SPPClientService( 5844): [b] SharedConstants.WHAT_PROV_NETWORK_NOT_AVAILABLE
I/PackageManager( 3236):   Action: "android.intent.action.SENDTO"
I/PackageManager( 3236):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 3236):   Scheme: "mms"
I/PackageManager( 3236): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/SPPClientService( 5844): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,W/Resources( 3236): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PackageManager( 3236): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 3236):   Action: "android.intent.action.SENDTO"
I/PackageManager( 3236):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 3236):   Scheme: "mmsto"
,I/PCWCLIENTTRACE_PushUtil( 6520): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6520): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6520): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6520): [onReceive] - android.intent.action.PACKAGE_REMOVED
,W/Resources( 3236): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SPPClientService( 5844): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5844): [g] getNetMCC return empty string,
,I/SELinux ( 8115): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 8115):  
,I/SELinux ( 8115): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 8115):  
I/SELinux ( 8115):  
,I/SELinux ( 8115): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 8115): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8115): >>>>> Normal User
,E/dalvikvm( 8115): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ],
,E/SELinux ( 8115): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 8115): in addTimaSignatureService
I/ActivityManager( 3236): Killing 6762:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty #43
,D/TimaKeyStoreProvider( 8115): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8115): Added TimaKesytore provider
,W/ApplicationsProvider( 3862): Could not fetch usage stats
W/ApplicationsProvider( 3862): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 3862): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 3862): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 3862): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 3862): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 3862): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 3862): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 3862): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 3862): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 3862): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 3862): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 3862): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Resources( 3236): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3236): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 8115): GC_CONCURRENT freed 3008K, 33% free 9555K/14120K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 8115): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/Resources( 3236): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3236): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3236): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3236): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3236): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3236): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3236): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3236): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3236): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3236): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector( 3236): onPackageRemoved : com.test.thalitest,
D/UsbSettingsManager( 3236): clearDefaults: com.test.thalitest
,W/AtomicFile( 3236): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
,W/AppWidgetServiceImpl( 3236): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,W/System.err( 8115): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory),
W/System.err( 8115): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 8115): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 8115): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err( 8115): 	,at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err( 8115): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err( 8115): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err( 8115): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err( 8115): ,	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err( 8115): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err( 8115): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err( 8115): ,	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 8115): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 8115): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 8115): ,	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 8115): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8115): 	at android.os.Looper.loop(Looper.java:146)
,W/System.err( 8115): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 8115): 	at java.lang.reflect.Method.invokeNative(Native Method)
,W/System.err( 8115): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 8115): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
,W/System.err( 8115): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 8115): 	at dalvik.system.NativeStart.main(Native Method)
,W/System.err( 8115): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 8115): 	at libcore.io.Posix.open(Native Method)
W/System.err( 8115): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110),
W/System.err( 8115): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 8115): ,	... 21 more
,D/GalaxyFinderApplication( 8115): [Slink platform] Version = 29011,
,D/GalaxyFinderApplication( 8115): [Slink platform] use state of slink location service is [false] to [true],
,I/SELinux ( 8133): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8133):  
,E/SQLiteLog( 7876): (3850) statement aborts at 35: [DELETE FROM app_registry WHERE package_name=? AND plugin_id=? AND sync_status != 170004 AND sync_status = 170002] disk I/O error,
,W/dalvikvm( 7876): threadid=13: thread exiting with uncaught exception (group=0x4180cc08),
E/AndroidRuntime( 7876): FATAL EXCEPTION: IntentService[HandleAppDataService]
E/AndroidRuntime( 7876): Process: com.sec.android.app.shealth, PID: 7876
,E/AndroidRuntime( 7876): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 7876): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 7876): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 7876): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 7876): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 7876): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618),
E/AndroidRuntime( 7876): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericDelete(BaseContentProvider.java:486)
E/AndroidRuntime( 7876): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.delete(BaseContentProvider.java:441)
E/AndroidRuntime( 7876): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273),
E/AndroidRuntime( 7876): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 7876): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.deleteAppRegistryData(AppRegistryDbManagerWithProvider.java:459)
E/AndroidRuntime( 7876): 	,at com.sec.android.app.shealth.service.HandleAppDataService.onHandleIntent(HandleAppDataService.java:56)
E/AndroidRuntime( 7876): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7876): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7876): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7876): 	,at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService( 3236): Can't write: system_app_crash
E/DropBoxManagerService( 3236): java.io.FileNotFoundException: /data/system/dropbox/drop219.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3236): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 3236): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 3236): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 3236): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 3236): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 3236): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 3236): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3236): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3236): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 3236): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 3236): 	... 5 more
I/Process ( 7876): Sending signal. PID: 7876 SIG: 9
,I/SELinux ( 8133): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8133):  
I/SELinux ( 8133):  
,I/SELinux ( 8133): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/ActivityManager( 3236): Process com.sec.android.app.shealth (pid 7876) (adj 5) has died.
E/SELinux ( 8133): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 8133): >>>>> Normal User
E/dalvikvm( 8133): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10043 ]
E/SELinux ( 8133): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 8133): in addTimaSignatureService
D/TimaKeyStoreProvider( 8133): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 8133): Added TimaKesytore provider
,D/dalvikvm( 8133): GC_CONCURRENT freed 3002K, 33% free 9559K/14116K, paused 2ms+2ms, total 22ms
,D/dalvikvm( 8133): WAIT_FOR_CONCURRENT_GC blocked 20ms
,E/SQLiteDatabase( 8133): Failed to open database '/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db'.
E/SQLiteDatabase( 8133): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8133): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8133): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8133): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8133): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8133): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8133): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8133): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8133): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8133): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8133): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8133): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8133): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8133): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8133): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:429)
E/SQLiteDatabase( 8133): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 8133): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 8133): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 8133): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 8133): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 8133): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 8133): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 8133): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8133): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8133): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8133): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8133): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8133): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8133): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8133): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 8133): Shutting down VM
,W/dalvikvm( 8133): threadid=1: thread exiting with uncaught exception (group=0x4180cc08)
E/AndroidRuntime( 8133): FATAL EXCEPTION: main
E/AndroidRuntime( 8133): Process: com.samsung.android.sdk.samsunglink, PID: 8133
E/AndroidRuntime( 8133): java.lang.RuntimeException: Unable to get provider com.mfluent.asp.datamodel.ASPMediaStoreProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8133): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 8133): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 8133): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 8133): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8133): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 8133): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8133): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 8133): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 8133): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 8133): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 8133): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 8133): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 8133): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 8133): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8133): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8133): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 8133): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 8133): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8133): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8133): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8133): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 8133): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 8133): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8133): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 8133): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 8133): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 8133): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 8133): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:429)
E/AndroidRuntime( 8133): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 8133): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 8133): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 8133): 	... 12 more
E/DropBoxManagerService( 3236): Can't write: system_app_crash
E/DropBoxManagerService( 3236): java.io.FileNotFoundException: /data/system/dropbox/drop220.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3236): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 3236): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 3236): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 3236): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 3236): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 3236): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 3236): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3236): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3236): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 3236): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 3236): 	... 5 more
I/Process ( 8133): Sending signal. PID: 8133 SIG: 9
I/SA      ( 6664): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
I/SA      ( 6664): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
I/ActivityManager( 3236): Killing 6777:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty #43
I/ActivityManager( 3236): Process com.samsung.android.sdk.samsunglink (pid 8133) (adj 9) has died.
,E/SharedPreferencesImpl( 6078): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
I/Icing.InternalIcingCorporaProvider( 6336): Updating corpora: A: com.test.thalitest, C: MAYBE
E/SQLiteLog( 6336): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/dalvikvm( 6336): threadid=15: thread exiting with uncaught exception (group=0x4180cc08)
,I/SELinux ( 8152): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8152):  
,E/AndroidRuntime( 6336): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 6336): Process: com.google.android.googlequicksearchbox:search, PID: 6336
E/AndroidRuntime( 6336): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6336): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6336): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 6336): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6336): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6336): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 6336): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 6336): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:171)
E/AndroidRuntime( 6336): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 6336): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
E/AndroidRuntime( 6336): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 6336): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 6336): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 6336): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 6336): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 6336): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 6336): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 6336): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6336): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6336): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6336): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6336): Sending signal. PID: 6336 SIG: 9
E/DropBoxManagerService( 3236): Can't write: system_app_crash
E/DropBoxManagerService( 3236): java.io.FileNotFoundException: /data/system/dropbox/drop221.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3236): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 3236): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 3236): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 3236): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 3236): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 3236): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 3236): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3236): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3236): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 3236): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 3236): 	... 5 more
,I/ActivityManager( 3236): Process com.google.android.googlequicksearchbox:search (pid 6336) (adj 5) has died.
,I/SELinux ( 8152): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8152):  
I/SELinux ( 8152):  
,I/SELinux ( 8152): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8152): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8152): >>>>> Normal User
,E/dalvikvm( 8152): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 8152): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 8152): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8152): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8152): Added TimaKesytore provider
,D/dalvikvm( 5844): GC_CONCURRENT freed 2137K, 27% free 10415K/14116K, paused 5ms+9ms, total 59ms
,D/dalvikvm( 8152): GC_CONCURRENT freed 3005K, 33% free 9559K/14116K, paused 3ms+1ms, total 24ms
,D/dalvikvm( 8152): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/UserAnalysis.PlaceProvider( 8152): Create SecureDbHelper
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 8152): Create SecureDbHelper
,E/SQLiteDatabase( 8152): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 8152): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8152): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8152): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8152): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 8152): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 8152): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteDatabase( 8152): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 8152): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 8152): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 8152): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 8152): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8152): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8152): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8152): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8152): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8152): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8152): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8152): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 8152): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 8152): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 8152): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 8152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 8152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 8152): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 8152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 8152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 8152): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 8152): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 8152): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 8152): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 8152): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 8152): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 8152): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 8152): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 8152): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 8152): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteOpenHelper( 8152): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 8152): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 8152): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 8152): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 8152): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 8152): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 8152): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 8152): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 8152): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 8152): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 8152): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 8152): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 8152): Opened privacy in read-only mode,
,E/SQLiteDatabase( 8152): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 8152): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
,E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8152): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8152): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8152): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 8152): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 8152): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteDatabase( 8152): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 8152): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 8152): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 8152): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 8152): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8152): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8152): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8152): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8152): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8152): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8152): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8152): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 8152): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 8152): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 8152): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 8152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 8152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 8152): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 8152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 8152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 8152): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 8152): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 8152): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 8152): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 8152): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 8152): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 8152): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 8152): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 8152): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 8152): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteOpenHelper( 8152): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 8152): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 8152): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 8152): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 8152): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 8152): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 8152): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 8152): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 8152): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 8152): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 8152): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 8152): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 8152): Opened privacy in read-only mode
,E/SQLiteDatabase( 8152): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 8152): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8152): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8152): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8152): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8152): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8152): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
E/SQLiteDatabase( 8152): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 8152): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 8152): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 8152): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 8152): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8152): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8152): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8152): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8152): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8152): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8152): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8152): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 8152): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 8152): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 8152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 8152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 8152): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 8152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 8152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 8152): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 8152): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 8152): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteData,base.java:696)
W/System.err( 8152): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 8152): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 8152): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 8152): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 8152): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 8152): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
W/System.err( 8152): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
W/System.err( 8152): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 8152): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 8152): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 8152): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8152): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 8152): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 8152): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 8152): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 8152): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 8152): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 8152): 	at dalvik.system.NativeStart.main(Native Method)
,I/SELinux ( 8165): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8165):  
,I/SELinux ( 8165): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8165):  
I/SELinux ( 8165):  
,I/SELinux ( 8165): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8165): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8165): >>>>> Normal User
,E/dalvikvm( 8165): >>>>> com.samsung.android.app.assistantmenu [ userId:0 | appId:1000 ]
,E/SELinux ( 8165): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 8165): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8165): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8165): Added TimaKesytore provider
,D/dalvikvm( 8165): GC_CONCURRENT freed 2998K, 33% free 9566K/14116K, paused 2ms+1ms, total 23ms
,D/dalvikvm( 8165): WAIT_FOR_CONCURRENT_GC blocked 20ms
,W/ContextImpl( 8165): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:165 android.app.ActivityThread.handleReceiver:2698 
,E/SQLiteDatabase( 8165): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 8165): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8165): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8165): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8165): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8165): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8165): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8165): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8165): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8165): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8165): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8165): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8165): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8165): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8165): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8165): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 8165): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 8165): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 8165): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8165): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8165): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 8165): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 8165): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 8165): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 8165): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 8165): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 8165): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 8165): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 8165): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 8165): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 8165): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 8165): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 8165): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 8165): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 8165): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
,W/System.err( 8165): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 8165): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 8165): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 8165): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8165): 	at android.os.Looper.loop(Looper.java:146)
,W/System.err( 8165): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/RCPManager( 6379):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3236):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3236): queryAllProviders():  providerCallBack is not register for 0
,I/SELinux ( 8178): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8178):  
,I/SELinux ( 8178): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8178):  
I/SELinux ( 8178):  
,I/SELinux ( 8178): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8178): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 8178): >>>>> Normal User
,E/dalvikvm( 8178): >>>>> com.sec.android.service.cm [ userId:0 | appId:10082 ]
,E/SELinux ( 8178): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 8178): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8178): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8178): Added TimaKesytore provider
,D/dalvikvm( 8178): GC_CONCURRENT freed 2996K, 33% free 9566K/14116K, paused 2ms+1ms, total 23ms
,D/dalvikvm( 8178): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/CapabilityManagerService New( 8178): Receiver Broadcast:android.intent.action.PACKAGE_REMOVED
,D/CapabilityManagerService New( 8178): The package(com.test.thalitest) removed
,W/System.err( 3236): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 3236): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 3236): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 3236): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 3236): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 3236): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 3236): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 3236): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 3236): 	at android.os.Binder.execTransact(Binder.java:404)
,W/System.err( 3236): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 3236): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 3236): 	at libcore.io.Posix.open(Native Method)
W/System.err( 3236): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 3236): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 3236): 	... 8 more
,W/System.err( 3236): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 3236): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 3236): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 3236): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 3236): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
,W/System.err( 3236): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 3236): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
,W/System.err( 3236): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 3236): 	at android.os.Binder.execTransact(Binder.java:404)
,W/System.err( 3236): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 3236): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
,W/System.err( 3236): 	at libcore.io.Posix.open(Native Method)
W/System.err( 3236): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 3236): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 3236): 	... 8 more
,I/SELinux ( 8190): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8190):  
I/ActivityManager( 3236): Killing 6292:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty #43
,I/SELinux ( 8190): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8190):  
I/SELinux ( 8190):  
,I/SELinux ( 8190): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8190): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8190): >>>>> Normal User
,E/dalvikvm( 8190): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10104 ]
,E/SELinux ( 8190): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 8190): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8190): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8190): Added TimaKesytore provider
,D/dalvikvm( 8190): GC_CONCURRENT freed 3001K, 33% free 9566K/14120K, paused 2ms+2ms, total 22ms
,D/dalvikvm( 8190): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/MagazineService::MagazineBroadcastReceiver( 6711): [onReceive] android.intent.action.PACKAGE_REMOVED com.test.thalitest
,I/MagazineService::MagazineService( 6711): [onHandleIntent] ACTION_PACKAGE_REMOVED
,E/SQLiteLog( 6711): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/dalvikvm( 6711): threadid=10: thread exiting with uncaught exception (group=0x4180cc08)
E/AndroidRuntime( 6711): FATAL EXCEPTION: IntentService[MagazineService::MagazineService]
E/AndroidRuntime( 6711): Process: com.samsung.android.magazine.service, PID: 6711
E/AndroidRuntime( 6711): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6711): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6711): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 6711): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6711): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6711): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 6711): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 6711): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:408)
E/AndroidRuntime( 6711): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6711): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6711): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/AndroidRuntime( 6711): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6711): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6711): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6711): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SELinux ( 8203): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8203):  
,I/Process ( 6711): Sending signal. PID: 6711 SIG: 9
E/DropBoxManagerService( 3236): Can't write: system_app_crash
E/DropBoxManagerService( 3236): java.io.FileNotFoundException: /data/system/dropbox/drop222.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3236): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 3236): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 3236): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 3236): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 3236): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 3236): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 3236): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3236): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3236): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 3236): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 3236): 	... 5 more
,I/ActivityManager( 3236): Process com.samsung.android.magazine.service (pid 6711) (adj 5) has died.
,I/SELinux ( 8203): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8203):  
I/SELinux ( 8203):  
I/SELinux ( 8203): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/PreloadUpdateManagerStateMachine( 6808): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 6808): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6808): entry::CHECK_TIMEOUT_FOR_UPDATE
E/SELinux ( 8203): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8203): >>>>> Normal User
E/dalvikvm( 8203): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 8203): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/hcjo    ( 6808): AutoUpdateTriggerManager:REQUEST2:requestInterval,
,D/TimaKeyStoreProvider( 8203): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 8203): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 8203): Added TimaKesytore provider,
,I/Volley  ( 6808): RestApi Request Add : 2307,
,D/dalvikvm( 8203): GC_CONCURRENT freed 3003K, 33% free 9559K/14116K, paused 2ms+2ms, total 23ms
,D/dalvikvm( 8203): WAIT_FOR_CONCURRENT_GC blocked 20ms
,E/SQLiteDatabase( 8203): Failed to open database '/data/data/com.samsung.helphub/databases/search.db'.
E/SQLiteDatabase( 8203): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8203): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8203): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8203): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8203): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8203): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8203): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8203): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8203): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8203): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8203): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8203): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 8203): 	at com.samsung.helphub.search.SearchProvider.onCreate(SearchProvider.java:63)
E/SQLiteDatabase( 8203): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 8203): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 8203): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 8203): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 8203): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 8203): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 8203): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 8203): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8203): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8203): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8203): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8203): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8203): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8203): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8203): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 8203): Couldn't open search.db for writing (will try read-only):
E/SQLiteOpenHelper( 8203): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 8203): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 8203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 8203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 8203): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 8203): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 8203): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 8203): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 8203): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 8203): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 8203): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 8203): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 8203): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 8203): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 8203): 	at com.samsung.helphub.search.SearchProvider.onCreate(SearchProvider.java:63)
E/SQLiteOpenHelper( 8203): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteOpenHelper( 8203): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteOpenHelper( 8203): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteOpenHelper( 8203): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteOpenHelper( 8203): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteOpenHelper( 8203): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteOpenHelper( 8203): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteOpenHelper( 8203): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 8203): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 8203): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 8203): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 8203): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 8203): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 8203): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,E/SQLiteOpenHelper( 8203): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 8203): Opened search.db in read-only mode,
,I/SELinux ( 8216): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 8216):  
,I/SELinux ( 8220): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 8220):  
,I/SELinux ( 8216): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 8216):  
I/SELinux ( 8216):  
,I/SELinux ( 8216): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 8216): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
E/dalvikvm( 8216): >>>>> Normal User
E/dalvikvm( 8216): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,D/dalvikvm( 3035): GC_EXPLICIT freed 44K, 15% free 9499K/11096K, paused 3ms+4ms, total 35ms,
,E/SELinux ( 8216): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
I/SELinux ( 8220): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8220):  
I/SELinux ( 8220):  
,I/SELinux ( 8220): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8220): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8220): >>>>> Normal User
,E/dalvikvm( 8220): >>>>> com.android.keychain [ userId:0 | appId:1000 ]
,E/SELinux ( 8220): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 8216): in addTimaSignatureService
,D/dalvikvm( 3035): GC_EXPLICIT freed <1K, 15% free 9499K/11096K, paused 2ms+3ms, total 29ms
,D/TimaKeyStoreProvider( 8216): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8216): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 8220): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8220): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8220): Added TimaKesytore provider
,D/dalvikvm( 3035): GC_EXPLICIT freed <1K, 15% free 9499K/11096K, paused 3ms+3ms, total 29ms
,D/dalvikvm( 8220): GC_CONCURRENT freed 3005K, 33% free 9562K/14116K, paused 4ms+1ms, total 28ms
,D/dalvikvm( 8220): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/ContextImpl( 8220): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 8242): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8242):  
,E/SQLiteDatabase( 8220): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 8220): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8220): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8220): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8220): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8220): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8220): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8220): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8220): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8220): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8220): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8220): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8220): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8220): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8220): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8220): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/SQLiteDatabase( 8220): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/SQLiteDatabase( 8220): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 8220): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8220): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8220): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 8220): threadid=10: thread exiting with uncaught exception (group=0x4180cc08)
,E/AndroidRuntime( 8220): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 8220): Process: com.android.keychain, PID: 8220
E/AndroidRuntime( 8220): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8220): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8220): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 8220): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 8220): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8220): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8220): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8220): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 8220): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 8220): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8220): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 8220): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 8220): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 8220): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 8220): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/AndroidRuntime( 8220): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/AndroidRuntime( 8220): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 8220): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8220): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 8220): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/dalvikvm( 8216): GC_CONCURRENT freed 2978K, 33% free 9583K/14116K, paused 4ms+2ms, total 44ms
D/dalvikvm( 8216): WAIT_FOR_CONCURRENT_GC blocked 31ms
,I/Process ( 8220): Sending signal. PID: 8220 SIG: 9
E/DropBoxManagerService( 3236): Can't write: system_app_crash
E/DropBoxManagerService( 3236): java.io.FileNotFoundException: /data/system/dropbox/drop223.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3236): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 3236): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 3236): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 3236): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 3236): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 3236): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 3236): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3236): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3236): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 3236): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 3236): 	... 5 more
,I/ActivityManager( 3236): Process com.android.keychain (pid 8220) (adj 5) has died.
,I/SELinux ( 8242): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8242):  
I/SELinux ( 8242):  
,I/SELinux ( 8242): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8242): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8242): >>>>> Normal User
,E/dalvikvm( 8242): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10160 ]
,E/SELinux ( 8242): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 8242): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8242): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8242): Added TimaKesytore provider
,I/Icing.InternalIcingCorporaProvider( 8216): Updating corpora: A: com.test.thalitest, C: MAYBE
,D/dalvikvm( 8242): GC_CONCURRENT freed 3014K, 33% free 9555K/14120K, paused 3ms+1ms, total 27ms,
,D/dalvikvm( 8242): WAIT_FOR_CONCURRENT_GC blocked 23ms,
,I/SELinux ( 8259): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 8259):  
,D/KidsModeInstallReceiver( 8242): onReceive intent data =  package:com.test.thalitest
,D/LocationManagerService( 3236): getProviders()=[passive]
,D/KidsPlatformStub( 8242): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 8266): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8266):  
I/ActivityManager( 3236): Killing 6350:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty #43
,I/SELinux ( 8259): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8259):  
I/SELinux ( 8259):  
,I/SELinux ( 8259): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8259): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 8259): >>>>> Normal User
,E/dalvikvm( 8259): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 8259): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 8259): in addTimaSignatureService
I/SELinux ( 8266): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8266):  
I/SELinux ( 8266):  
,I/SELinux ( 8266): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8266): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8266): >>>>> Normal User
,E/dalvikvm( 8266): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10164 ]
,E/SELinux ( 8266): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 8259): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8259): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 8266): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8266): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8266): Added TimaKesytore provider
,E/SPPClientService( 5844): [b] __InitReply__
,D/dalvikvm( 6808): GC_CONCURRENT freed 2492K, 29% free 10050K/14116K, paused 9ms+4ms, total 52ms
,E/SQLiteDatabase( 5844): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5844): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5844): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5844): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.i.d.l(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.e.a.c.e(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.e.a.c.i(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.e.a.c.d(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.e.a.c.handleMessage(Unknown Source)
E/SQLiteDatabase( 5844): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5844): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5844): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SPPClientService( 5844): [d] [getAllUserSN()] Exception with message =not an error (code 0): Could not open the database in read/write mode.
,D/dalvikvm( 8259): GC_CONCURRENT freed 3001K, 33% free 9567K/14120K, paused 4ms+2ms, total 49ms
,D/dalvikvm( 8259): WAIT_FOR_CONCURRENT_GC blocked 39ms
,E/SQLiteDatabase( 5844): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5844): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5844): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5844): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.i.d.l(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.util.b.a(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.f.a.g.a(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.f.a.h.a(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.e.a.c.i(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.e.a.c.d(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.e.a.c.handleMessage(Unknown Source)
E/SQLiteDatabase( 5844): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5844): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5844): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SPPClientService( 5844): [d] [getAllUserSN()] Exception with message =not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5844): Failed to open database '/data/data/com.sec.spp.push/databases/log_data_db'.
E/SQLiteDatabase( 5844): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5844): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5844): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.c.c.<init>(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.c.c.a(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.log.collector.PushClientLogCollectService.i(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.log.collector.PushClientLogCollectService.onHandleIntent(Unknown Source)
E/SQLiteDatabase( 5844): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5844): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5844): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5844): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SPPClientService( 5844): [[SPPLogCollecter]] null
,D/dalvikvm( 8266): GC_CONCURRENT freed 3008K, 33% free 9555K/14112K, paused 3ms+2ms, total 66ms
,D/dalvikvm( 8266): WAIT_FOR_CONCURRENT_GC blocked 59ms
,E/SQLiteDatabase( 5844): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5844): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5844): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5844): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.i.d.m(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.f.a.g.a(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.f.a.h.a(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.e.a.c.i(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.e.a.c.d(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.e.a.c.handleMessage(Unknown Source)
E/SQLiteDatabase( 5844): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5844): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5844): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SPPClientService( 5844): [d] [DeReg] not an error (code 0): Could not open the database in read/write mode.
,I/ActivityManager( 3236): Killing 7437:com.sec.android.cloudagent/u0a2 (adj 15): empty #43
,E/SQLiteDatabase( 8266): Failed to open database '/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db'.
E/SQLiteDatabase( 8266): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8266): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8266): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8266): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8266): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8266): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8266): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8266): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8266): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8266): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8266): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8266): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8266): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8266): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8266): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:265)
E/SQLiteDatabase( 8266): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:228)
E/SQLiteDatabase( 8266): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 8266): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 8266): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 8266): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 8266): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 8266): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 8266): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 8266): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8266): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8266): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8266): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8266): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8266): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8266): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8266): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 8266): Shutting down VM
,W/dalvikvm( 8266): threadid=1: thread exiting with uncaught exception (group=0x4180cc08)
E/AndroidRuntime( 8266): FATAL EXCEPTION: main
E/AndroidRuntime( 8266): Process: com.samsung.android.provider.shootingmodeprovider, PID: 8266
E/AndroidRuntime( 8266): java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8266): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 8266): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 8266): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 8266): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8266): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 8266): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8266): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 8266): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 8266): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 8266): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 8266): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 8266): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 8266): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 8266): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8266): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8266): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 8266): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 8266): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8266): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8266): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8266): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 8266): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 8266): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8266): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 8266): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 8266): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 8266): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 8266): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:265)
E/AndroidRuntime( 8266): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:228)
E/AndroidRuntime( 8266): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 8266): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 8266): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 8266): 	... 12 more
,E/DropBoxManagerService( 3236): Can't write: system_app_crash
E/DropBoxManagerService( 3236): java.io.FileNotFoundException: /data/system/dropbox/drop224.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3236): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 3236): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 3236): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 3236): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 3236): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 3236): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 3236): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3236): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3236): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 3236): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 3236): 	... 5 more
,I/SELinux ( 8291): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8291):  
,I/Process ( 8266): Sending signal. PID: 8266 SIG: 9
,I/ActivityManager( 3236): Process com.samsung.android.provider.shootingmodeprovider (pid 8266) (adj 0) has died.
,E/SharedPreferencesImpl( 4176): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,I/SELinux ( 8291): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8291):  
I/SELinux ( 8291):  
,I/SELinux ( 8291): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8291): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 8291): >>>>> Normal User
,E/dalvikvm( 8291): >>>>> com.n7mobile.promenadaplusa [ userId:0 | appId:10183 ]
,E/SharedPreferencesImpl( 4176): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,E/SELinux ( 8291): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 8291): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8291): Cannot add TimaSignature Service, License check Failed
,E/Icing   ( 4176): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,D/ActivityThread( 8291): Added TimaKesytore provider
,E/SharedPreferencesImpl( 4176): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,E/SharedPreferencesImpl( 4176): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,E/Icing   ( 4176): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,E/SharedPreferencesImpl( 4176): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,E/SharedPreferencesImpl( 4176): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml.bak
D/dalvikvm( 8291): GC_CONCURRENT freed 3012K, 33% free 9552K/14120K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 8291): WAIT_FOR_CONCURRENT_GC blocked 24ms
,E/Icing   ( 4176): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,D/ApplicationPromenada( 8291): Application OnCreate start
,D/ApplicationPromenada( 8291): Application OnCreate po on Create
D/CrashReporter( 8291): Initing Crashreporter: com.n7mobile.promenada2.ApplicationPromenada@422d2290
D/CrashReporter( 8291): Swaping uncaught exception handler
,D/ApplicationPromenada( 8291): Application OnCreate App Loader start
,D/ApplicationPromenada( 8291): Application OnCreate App Loader finish
,E/SQLiteDatabase( 8216): Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db'.
E/SQLiteDatabase( 8216): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8216): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8216): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8216): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8216): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8216): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8216): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8216): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8216): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8216): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8216): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8216): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8216): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8216): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.getWritableDatabase(InternalIcingCorporaProvider.java:500)
E/SQLiteDatabase( 8216): 	at com.google.android.gms.appdatasearch.util.AppDataSearchDbOpenHelperBase.cleanSequenceTable(AppDataSearchDbOpenHelperBase.java:348)
E/SQLiteDatabase( 8216): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.requestIndexingIfRequired(AppDataSearchProviderBase.java:321)
E/SQLiteDatabase( 8216): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:165)
E/SQLiteDatabase( 8216): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:156)
E/SQLiteDatabase( 8216): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.executeWithConnection(AppDataSearchProviderBase.java:295)
E/SQLiteDatabase( 8216): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider.registerCorpora(AppDataSearchProvider.java:171)
E/SQLiteDatabase( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.safeRegisterCorpora(InternalIcingCorporaProvider.java:376)
E/SQLiteDatabase( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.registerCorpora(InternalIcingCorporaProvider.java:330)
E/SQLiteDatabase( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:273)
E/SQLiteDatabase( 8216): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/SQLiteDatabase( 8216): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/SQLiteDatabase( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/SQLiteDatabase( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/SQLiteDatabase( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/SQLiteDatabase( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaPro,vider.java:1087)
E/SQLiteDatabase( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/SQLiteDatabase( 8216): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 8216): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8216): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8216): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/Icing.InternalIcingCorporaProvider( 8216): Exception thrown from registerCorpora
E/Icing.InternalIcingCorporaProvider( 8216): java.lang.RuntimeException: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/Icing.InternalIcingCorporaProvider( 8216): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.executeWithConnection(AppDataSearchProviderBase.java:297)
E/Icing.InternalIcingCorporaProvider( 8216): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider.registerCorpora(AppDataSearchProvider.java:171)
E/Icing.InternalIcingCorporaProvider( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.safeRegisterCorpora(InternalIcingCorporaProvider.java:376)
E/Icing.InternalIcingCorporaProvider( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.registerCorpora(InternalIcingCorporaProvider.java:330)
E/Icing.InternalIcingCorporaProvider( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:273)
E/Icing.InternalIcingCorporaProvider( 8216): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/Icing.InternalIcingCorporaProvider( 8216): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/Icing.InternalIcingCorporaProvider( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/Icing.InternalIcingCorporaProvider( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/Icing.InternalIcingCorporaProvider( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/Icing.InternalIcingCorporaProvider( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/Icing.InternalIcingCorporaProvider( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/Icing.InternalIcingCorporaProvider( 8216): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Icing.InternalIcingCorporaProvider( 8216): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Icing.InternalIcingCorporaProvider( 8216): 	at android.os.Looper.loop(Looper.java:146)
E/Icing.InternalIcingCorporaProvider( 8216): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/Icing.InternalIcingCorporaProvider( 8216): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/Icing.InternalIcingCorporaProvider( 8216): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/Icing.InternalIcingCorporaProvider( 8216): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/Icing.InternalIcingCorporaProvider( 8216): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/Icing.InternalIcingCorporaProvider( 8216): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/Icing.InternalIcingCorporaProvider( 8216): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/Icing.InternalIcingCorporaProvider( 8216): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/Icing.InternalIcingCorporaProvider( 8216): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/Icing.InternalIcingCorporaProvider( 8216): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/Icing.InternalIcingCorporaProvider( 8216): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.jav,a:696)
E/Icing.InternalIcingCorporaProvider( 8216): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/Icing.InternalIcingCorporaProvider( 8216): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/Icing.InternalIcingCorporaProvider( 8216): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/Icing.InternalIcingCorporaProvider( 8216): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/Icing.InternalIcingCorporaProvider( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.getWritableDatabase(InternalIcingCorporaProvider.java:500)
E/Icing.InternalIcingCorporaProvider( 8216): 	at com.google.android.gms.appdatasearch.util.AppDataSearchDbOpenHelperBase.cleanSequenceTable(AppDataSearchDbOpenHelperBase.java:348)
E/Icing.InternalIcingCorporaProvider( 8216): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.requestIndexingIfRequired(AppDataSearchProviderBase.java:321)
E/Icing.InternalIcingCorporaProvider( 8216): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:165)
E/Icing.InternalIcingCorporaProvider( 8216): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:156)
E/Icing.InternalIcingCorporaProvider( 8216): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.executeWithConnection(AppDataSearchProviderBase.java:295)
E/Icing.InternalIcingCorporaProvider( 8216): 	... 15 more
,W/Icing.InternalIcingCorporaProvider( 8216): Corpora registration failed
E/SQLiteDatabase( 8216): Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db'.
E/SQLiteDatabase( 8216): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8216): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8216): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8216): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8216): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8216): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8216): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8216): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8216): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8216): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8216): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8216): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8216): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8216): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.getWritableDatabase(InternalIcingCorporaProvider.java:500)
E/SQLiteDatabase( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:281)
E/SQLiteDatabase( 8216): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/SQLiteDatabase( 8216): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/SQLiteDatabase( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/SQLiteDatabase( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/SQLiteDatabase( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/SQLiteDatabase( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/SQLiteDatabase( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/SQLiteDatabase( 8216): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 8216): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8216): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8216): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 8216): threadid=10: thread exiting with uncaught exception (group=0x4180cc08)
E/AndroidRuntime( 8216): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 8216): Process: com.google.android.googlequicksearchbox:search, PID: 8216
E/AndroidRuntime( 8216): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8216): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8216): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 8216): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 8216): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8216): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8216): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8216): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 8216): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 8216): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8216): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 8216): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 8216): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 8216): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.getWritableDatabase(InternalIcingCorporaProvider.java:500)
E/AndroidRuntime( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:281)
E/AndroidRuntime( 8216): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 8216): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 8216): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 8216): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 8216): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8216): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 8216): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 8216): Sending signal. PID: 8216 SIG: 9
E/DropBoxManagerService( 3236): Can't write: system_app_crash
E/DropBoxManagerService( 3236): java.io.FileNotFoundException: /data/system/dropbox/drop225.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3236): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 3236): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 3236): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 3236): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 3236): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 3236): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 3236): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3236): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3236): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 3236): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 3236): 	... 5 more
,I/ActivityManager( 3236): Process com.google.android.googlequicksearchbox:search (pid 8216) (adj 5) has died.
,W/ActivityManager( 3236): Service crashed 2 times, stopping: ServiceRecord{4448dd20 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService}
,I/ActivityManager( 3236): Waited long enough for: ServiceRecord{44d35710 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/p2.ApplicationLoader( 8291): ############################## cached apps: 
D/AmoledAdjustTimer( 3236): prevTemp = 285, currTemp = 287, prevStep = 4, currStep = 4
D/SSRMv2:SIOP( 3236): SIOP:: AP = 340, Delta = -10
,V/WebViewChromium( 8291): Binding Chromium to the background looper Looper (main, tid 1) {422d50c0}
,I/chromium( 8291): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 8291): Initializing chromium process, renderers=0
,W/chromium( 8291): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 8291): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 8291): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 8291): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 8291): Mali API Version : 401
,I/Mali    ( 8291): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/dalvikvm( 6808): GC_CONCURRENT freed 2022K, 29% free 10024K/14116K, paused 2ms+3ms, total 30ms
,D/ApplicationPromenada( 8291): Application OnCreate Finish
,W/System.err( 8291): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 8291): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
W/System.err( 8291): 	at com.n7mobile.promenada2.applications.ApplicationInstallationReceiver.onReceive(SourceFile:27)
W/System.err( 8291): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 8291): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 8291): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
,W/System.err( 8291): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8291): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 8291): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 8291): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 8291): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 8291): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 8291): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 8291): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager( 3236): Killing 6311:com.sec.android.diagmonagent/1000 (adj 15): empty #43
,D/PackageBroadcastService( 4176): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 4176): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 4176): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4176): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4176): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4176): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 4176): Removing dialog suppression flag for package com.test.thalitest
,E/SQLiteLog( 4176): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog( 4176): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog( 3760): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 3760): Shutting down VM
W/dalvikvm( 4176): threadid=46: thread exiting with uncaught exception (group=0x4180cc08)
,W/dalvikvm( 3760): threadid=1: thread exiting with uncaught exception (group=0x4180cc08)
,E/DriveAsyncService( 4176): disk I/O error (code 3850)
E/DriveAsyncService( 4176): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4176): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4176): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/DriveAsyncService( 4176): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4176): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4176): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/DriveAsyncService( 4176): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/DriveAsyncService( 4176): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 4176): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 4176): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 4176): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 4176): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 4176): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 4176): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4176): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 4176): 	at java.lang.Thread.run(Thread.java:841)
,E/AndroidRuntime( 4176): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 4176): Process: com.google.android.gms, PID: 4176
E/AndroidRuntime( 4176): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4176): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4176): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 4176): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4176): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4176): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 4176): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
E/AndroidRuntime( 4176): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 4176): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 4176): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 4176): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 4176): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 4176): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 4176): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 4176): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 4176): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 4176): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 4176): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 4176): 	at java.lang.Thread.run(Thread.java:841)
,E/AndroidRuntime( 3760): FATAL EXCEPTION: main
E/AndroidRuntime( 3760): Process: com.google.process.gapps, PID: 3760
E/AndroidRuntime( 3760): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3760): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 3760): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 3760): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 3760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3760): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 3760): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 3760): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 3760): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 3760): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 3760): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 3760): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 3760): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3760): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 3760): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 3760): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 3760): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 3760): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 3760): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 3760): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 3760): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 3760): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 3760): 	... 10 more
,E/DropBoxManagerService( 3236): Can't write: system_app_crash
E/DropBoxManagerService( 3236): java.io.FileNotFoundException: /data/system/dropbox/drop226.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3236): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 3236): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 3236): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 3236): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 3236): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 3236): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 3236): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3236): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3236): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 3236): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 3236): 	... 5 more
,I/Process ( 4176): Sending signal. PID: 4176 SIG: 9
,E/DropBoxManagerService( 3236): Can't write: system_app_crash
E/DropBoxManagerService( 3236): java.io.FileNotFoundException: /data/system/dropbox/drop227.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3236): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 3236): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 3236): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 3236): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 3236): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 3236): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 3236): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3236): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3236): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 3236): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 3236): 	... 5 more
,E/SQLiteDatabase( 5844): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5844): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5844): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5844): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5844): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.i.d.e(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5844): 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
E/SQLiteDatabase( 5844): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5844): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5844): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 5844): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5844): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5844): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 5844): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 5844): 	at dalvik.system.NativeStart.main(Native Method)
,I/Process ( 3760): Sending signal. PID: 3760 SIG: 9
,E/SPPClientService( 5844): [d] [getAppId()] Exception with message =not an error (code 0): Could not open the database in read/write mode.
,D/BatteryService( 3236): level:100, scale:100, status:5, health:2, present:true, voltage: 4380, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 3236): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3236): stay LED for fully charged
,I/SELinux ( 8332): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8332):  
,D/KeyguardUpdateMonitor( 3500): received broadcast android.intent.action.BATTERY_CHANGED

```
