#### Test 506502789252e15_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0
,--------- beginning of /dev/log/main
D/AndroidRuntime( 6954): 
D/AndroidRuntime( 6954): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6954): CheckJNI is OFF
D/AndroidRuntime( 6954): setted country_code = Poland
D/AndroidRuntime( 6954): setted countryiso_code = PL
D/AndroidRuntime( 6954): setted sales_code = PLS
D/AndroidRuntime( 6954): readGMSProperty: start
D/AndroidRuntime( 6954): readGMSProperty: already setted!!
D/AndroidRuntime( 6954): readGMSProperty: end
D/AndroidRuntime( 6954): addProductProperty: start
D/dalvikvm( 6954): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6954): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6954): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6954): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6954): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6954): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6954): failed to load memtrack module: -2
D/dalvikvm( 6954): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6954): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2422): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2422): mDVFSHelper.acquire()
I/SurfaceFlinger( 1922): id=17 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1922): id=18 createSurf (16x16),-1 flag=20004, EimLayer
I/SELinux ( 6981): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6981):  
D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6954): Shutting down VM
D/dalvikvm( 6954): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+0ms, total 4ms
I/SELinux ( 6981): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6981):  
I/SELinux ( 6981):  
I/SELinux ( 6981): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6981): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6981): >>>>> Normal User
E/dalvikvm( 6981): >>>>> com.test.thalitest [ userId:0 | appId:10524 ]
E/SELinux ( 6981): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 6981): in addTimaSignatureService
D/TimaKeyStoreProvider( 6981): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6981): Added TimaKesytore provider
V/WindowManager( 2422): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
D/AmoledAdjustTimer( 2422): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
I/SQLiteSecureOpenHelper( 4131): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4131): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1922): id=9 Removed Mauncher (8/10)
I/SurfaceFlinger( 1922): id=9 Removed Mauncher (-2/10)
D/Launcher( 2786): onTrimMemory. Level: 20
D/dalvikvm( 6981): GC_CONCURRENT freed 2998K, 33% free 9565K/14072K, paused 3ms+1ms, total 20ms
D/dalvikvm( 6981): WAIT_FOR_CONCURRENT_GC blocked 13ms
V/WebViewChromium( 6981): Binding Chromium to the background looper Looper (main, tid 1) {42592328}
I/chromium( 6981): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 6981): Initializing chromium process, renderers=0
,W/chromium( 6981): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 6981): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 6981): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6981): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 6981): Mali API Version : 401
,I/Mali    ( 6981): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 6981): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 6981): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 6981): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 6981): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 6981): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 6981): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/StatusBarManagerService( 2422): tr p:6981,o:f
W/dalvikvm( 6981): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 6981): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 6981): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 6981): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 6981): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 6981): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 6981): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 6981): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 6981): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6981): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 6981): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 6981): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 6981): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2422): semi p:6981,o:f
,I/SurfaceFlinger( 1922): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 6981): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 6981): Enabling debug mode 0
,W/AwContents( 6981): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 6981): showStatusIcon on inactive InputConnection
W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2422): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/JsMessageQueue( 6981): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 6981): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4258a188
,D/dalvikvm( 6981): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4258a188
,D/jxcore_app_log( 6981): JniHelper::setJavaVM(0x41ac2220), pthread_self() = 2027509848
,D/JX-Cordova( 6981): jxcore cordova android initializing
,I/dalvikvm( 6981): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 6981): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 6981): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 6981): GC_CONCURRENT freed 1290K, 20% free 11348K/14140K, paused 2ms+2ms, total 23ms
,D/dalvikvm( 6981): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 6981): GC_CONCURRENT freed 1928K, 19% free 14926K/18376K, paused 1ms+2ms, total 38ms
,D/dalvikvm( 6981): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 6981): GC_FOR_ALLOC freed 5292K, 31% free 16202K/23256K, paused 49ms, total 49ms
,D/dalvikvm( 6981): GC_CONCURRENT freed 6700K, 32% free 17668K/25896K, paused 1ms+9ms, total 54ms
,D/dalvikvm( 6981): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/dalvikvm( 6981): GC_FOR_ALLOC freed 1196K, 33% free 17521K/25896K, paused 49ms, total 49ms
,I/dalvikvm-heap( 6981): Grow heap (frag case) to 22.093MB for 3688532-byte allocation
,D/dalvikvm( 6981): GC_FOR_ALLOC freed 2477K, 37% free 18646K/29500K, paused 40ms, total 40ms
,W/jxcore-log( 6981): Initializing JXcore engine
,W/jxcore-log( 6981): JXcore engine is ready
,W/jxcore-log( 6981): Starting JXcore engine
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/jxcore-log( 6981): Platform android
W/jxcore-log( 6981): 
,W/jxcore-log( 6981): Process ARCH arm
W/jxcore-log( 6981): 
,I/jxcore-log( 6981): JXcore Cordova bridge is ready!
I/jxcore-log( 6981): 
,W/jxcore-log( 6981): JXcore engine is started
,I/chromium( 6981): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6981): Toggling radios to true
I/jxcore-log( 6981): 
,W/ActivityManager( 2422): Permission Denial: getCurrentUser() from pid=6981, uid=10524 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 2422): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 2422): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6981, uid=10524 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 2422): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/BluetoothManagerService( 2422): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:620)
W/BluetoothManagerService( 2422): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService( 2422): 	at android.os.Binder.execTransact(Binder.java:404)
W/BluetoothManagerService( 2422): 	at dalvik.system.NativeStart.run(Native Method)
E/DevicePolicyManagerService( 2422): getAllowBluetoothMode - value retunrs : 2
,D/BluetoothManagerService( 2422): foregroundUser: 0
,E/BluetoothManagerService( 2422): Package is exist.
,I/WifiManager( 6981): packageName : com.test.thalitest
,D/BluetoothAdapterState( 5045): CURRENT_STATE=OFF, MSG = USER_TURN_ON
I/BluetoothAdapterState( 5045): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 5045): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5045): updateAdapterState state is 11
D/BluetoothAdapterService( 5045): Broadcasting updateAdapterState() to 1 receivers.
I/WifiManager( 6981): setWifiEnabled : true
D/BluetoothAdapterService( 5045): Autoconnection is available 
D/BluetoothAdapterService( 5045): updateAdapterState prevState = 10newState = 11
,D/BtConfig.SecureMode( 5045): isSecureModeOn:false
D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,I/WifiService( 2422): setWifiEnabled: true pid=6981, uid=10524
,W/WifiService( 2422): Failed getting userId using ActivityManagerNative
W/WifiService( 2422): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6981, uid=10524 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2422): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2422): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2422): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2422): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2422): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2422): 	at dalvik.system.NativeStart.run(Native Method)
W/ActivityManager( 2422): Permission Denial: getCurrentUser() from pid=6981, uid=10524 requires android.permission.INTERACT_ACROSS_USERS
W/InputMethodManagerService( 2422): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 2422): [BT Setting State] State =11
W/BluetoothAdapterService( 5045): isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,D/PhoneApp( 2755): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 11
W/BluetoothAdapterService( 5045): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,I/SamsungIME( 3005): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,W/BluetoothAdapterService( 5045): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,I/QuickConnect[1.1][2] ( 5019): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_ON
,E/WifiHW  ( 2422): ##################### set firmware type 0 #####################
,I/WifiService( 2422): disconnect: pid=6981, uid=10524
I/WifiHW  ( 1916): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
E/WifiHW  ( 1916): Cannot open "/data/.cid.info": No such file or directory
I/WifiHW  ( 1916): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
E/WifiHW  ( 1916): TEMP_FAILURE_RETRY complete
,D/SoftapController( 1916): Softap fwReload - Ok
W/BluetoothAdapterService( 5045): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,I/jxcore-log( 6981): Radios toggled
I/jxcore-log( 6981): 
,W/BluetoothAdapterService( 5045): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/CommandListener( 1916): Setting iface cfg
D/CommandListener( 1916): Trying to bring down wlan0
,W/BluetoothAdapterService( 5045): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 5045): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5045): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5045): Unable to stop service com.android.bluetooth.gatt.GattService. Invalid state: 12
W/BluetoothAdapterService( 5045): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 5045): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/WifiHW  ( 2422): Skip the update_ctrl_interface
,D/WifiHW  ( 2422): Skip the update_ctrl_interface
,E/WifiHW  ( 2422): supplicant_name : p2p_supplicant
W/BluetoothAdapterService( 5045): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5045): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/BluetoothNotiBroadcastReceiver( 5506): onReceive
,D/WifiMonitor( 2422): startMonitoring(wlan0) with mConnected = false
W/BluetoothAdapterService( 5045): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5045): Not skipping com.android.bluetooth.hid.HidService
,D/HeadsetService( 5045): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 5045): classInitNative: succeeds
D/HeadsetStateMachine( 5045): Version 1.5
,D/HeadsetStateMachine( 5045): make
,D/QuickConnect[1.1][2] ( 5019): HeadsetProfile.onServiceConnected - Bluetooth service connected
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,W/BluetoothAdapterService( 5045): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5045): Not skipping com.android.bluetooth.hdp.HealthService
,I/wpa_supplicant( 7031): wpa_supplicant v2.1-devel-4.4.22014-07-16/12:43:14
,I/wpa_supplicant( 7031): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 7031): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 7031): >>>>> Not GET KEY, IV <<<<<
,I/SELinux ( 7033): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7033):  
E/wpa_supplicant( 7031): getIMSI cannot open file
,E/wpa_supplicant( 7031): Interworking config: - SIM READ ERROR
,E/HeadsetStateMachine( 5045): # of Max HF connection is 2
,W/BluetoothAdapterService( 5045): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5045): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5045): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5045): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5045): check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5045): Not skipping com.broadcom.bt.service.sap.SapService
,I/BluetoothAdapterState( 5045): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid( 5045): get_profile_interface handsfree
I/SELinux ( 7033): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7033):  
I/SELinux ( 7033):  
,I/SELinux ( 7033): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7033): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7033): >>>>> Normal User
,E/dalvikvm( 7033): >>>>> pl.k2.droidoaudioteka [ userId:0 | appId:10066 ]
,E/SELinux ( 7033): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/BluetoothAtMessage( 5045): createCMTIContentObservers
,D/HeadsetStateMachine( 5045): Enter Disconnected: -2
,E/HeadsetStateMachine( 5045): set to mRemoteBrsf = 0
D/HeadsetStateMachine( 5045): map size, before remove : 0
D/HeadsetStateMachine( 5045): map size, after remove: 0
,D/HeadsetStateMachine( 5045): mNextConnectingDevice : null
,I/dalvikvm( 7033): Enabling JNI app bug workarounds for target SDK version 7...
,D/BluetoothA2dp( 2422): Proxy object connected
,D/BluetoothA2dp( 5019): Proxy object connected
,D/BluetoothA2dp( 4131): Proxy object connected
,D/QuickConnect[1.1][2] ( 5019): A2dpProfile.onServiceConnected - Bluetooth service connected
D/A2dpService( 5045): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 5045): classInitNative: succeeds
,D/A2dpStateMachine( 5045): make
,I/bluedroid( 5045): get_profile_interface a2dp
,I/GKI_LINUX( 5045): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 5045): Enter Disconnected: -2
I/BluetoothAvrcpServiceJni( 5045): classInitNative: succeeds
,D/TimaKeyStoreProvider( 7033): in addTimaSignatureService
,I/wpa_supplicant( 7031): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 7031): getIMSI cannot open file
E/wpa_supplicant( 7031): Interworking config: - SIM READ ERROR
I/bluedroid( 5045): get_profile_interface avrcp
I/wpa_supplicant( 7031): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 7031): rfkill: Cannot open RFKILL control device
,D/TimaKeyStoreProvider( 7033): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7033): Added TimaKesytore provider
,D/MediaFocusControl( 2422): >>> registerRemoteControlDisplay
,I/BluetoothHidServiceJni( 5045): classInitNative: succeeds
,D/BluetoothInputDevice( 5019): Proxy object connected
,D/QuickConnect[1.1][2] ( 5019): HidProfile.onServiceConnected - Bluetooth service connected
,D/HidService( 5045): Received start request. Starting profile...
I/bluedroid( 5045): get_profile_interface hidhost
,D/HidService( 5045): setHidService(): set to: null
,I/BluetoothHealthServiceJni( 5045): classInitNative: succeeds
,D/HealthService( 5045): Received start request. Starting profile...
,I/bluedroid( 5045): get_profile_interface health
,I/BluetoothPanServiceJni( 5045): classInitNative(L105): succeeds
,D/BluetoothPan( 2422): BluetoothPAN Proxy object connected
,D/PanService( 5045): Received start request. Starting profile...
D/BluetoothPanServiceJni( 5045): initializeNative(L110): pan
,I/bluedroid( 5045): get_profile_interface pan
,D/BluetoothTethering( 2422): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothMapService( 5045): Received start request. Starting profile...
,W/BluetoothMapMasInstance( 5045): mAccount : null
,I/BluetoothSAPServiceJni( 5045): classInitNative(L204): succeeds
D/SapService( 5045): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 5045): initializeNative(L209): sap
,I/bluedroid( 5045): get_profile_interface sap
,D/HeadsetStateMachine( 5045): Try to query the phonestate on bind
,D/BluetoothPhoneService( 2755): handleMessage: 4
,D/HeadsetStateMachine( 5045): Proxy object connected
,V/BluetoothPhoneService( 2755): Call state Converted2: IDLE/IDLE -> 6
W/BluetoothHeadset( 2755): Proxy not attached to service
,D/HeadsetPhoneState( 5045): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetStateMachine( 5045): Disconnected process message: 11
,D/HeadsetPhoneState( 5045): sendDeviceDataStateChanged
,D/HeadsetStateMachine( 5045): Disconnected process message: 20
,D/HeadsetPhoneState( 5045): Signal level : previous=0 curr=0
V/HeadsetService( 5045): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5045): Disconnected process message: 10
D/dalvikvm( 7033): GC_CONCURRENT freed 3001K, 33% free 9565K/14076K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 7033): WAIT_FOR_CONCURRENT_GC blocked 14ms
D/HeadsetPhoneState( 5045): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 5045): Disconnected process message: 11
,D/BluetoothAdapterService( 5045): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5045): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5045): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5045): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5045): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5045): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterState( 5045): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 5045): enable
,D/GKI_LINUX( 5045): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,E/bt-btif ( 5045): Calling BTA_HhEnable
,E/bt-btif ( 5045): btif_storage_get_adapter_property service_mask:0x160040
,E/BluetoothServiceJni( 5045): populateRssiValuesNative
I/bluedroid( 5045): getModelRssiValues
,E/BluetoothServiceJni( 5045): model_rssi_values_callback: low = -75, mid = -65, high = 127
,E/BluetoothRemoteDevices( 5045): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BtConfig.SecureMode( 5045): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5045): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 241
,E/BluetoothRemoteDevices( 5045): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 10
,D/BtConfig.SecureMode( 5045): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5045): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 241
,E/BluetoothRemoteDevices( 5045): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,W/System.err( 7033): java.io.FileNotFoundException: /system/etc/vold.fstab: open failed: ENOENT (No such file or directory)
,D/BtConfig.SecureMode( 5045): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5045): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 241
,E/BluetoothRemoteDevices( 5045): devicePropertyChangedCallback: bdDevice: F8:CF:C5:D9:E5:61, value is empty for type: 10
,D/BtConfig.SecureMode( 5045): isSecureModeOn:false
W/System.err( 7033): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 7033): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 7033): 	at java.util.Scanner.<init>(Scanner.java:158)
W/System.err( 7033): 	at java.util.Scanner.<init>(Scanner.java:138)
,W/System.err( 7033): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.readVoldFile(StorageOptions.java:107)
W/System.err( 7033): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.determineStorageOptions(StorageOptions.java:31)
W/System.err( 7033): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:81)
W/System.err( 7033): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:129)
W/System.err( 7033): 	at pl.k2.droidoaudioteka.ui.AudiotekaApplication.onCreate(AudiotekaApplication.java:171)
W/System.err( 7033): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 7033): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 7033): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7033): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 7033): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 7033): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 7033): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 7033): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 7033): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 7033): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 7033): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 7033): 	at dalvik.system.NativeStart.main(Native Method)
E/BluetoothRemoteDevices( 5045): devicePropertyChangedCallback: bdDevice: F8:CF:C5:D9:E5:61, value is empty for type: 241
W/System.err( 7033): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 7033): 	at libcore.io.Posix.open(Native Method)
W/System.err( 7033): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 7033): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 7033): 	... 20 more
E/BluetoothRemoteDevices( 5045): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
W/System.err( 7033): file res dir: /data/data/pl.k2.droidoaudioteka/files
,W/System.err( 7033): Excternal dir: /mnt/sdcard
,D/BtConfig.SecureMode( 5045): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5045): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 241
,E/BluetoothRemoteDevices( 5045): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,D/BtConfig.SecureMode( 5045): isSecureModeOn:false
E/BluetoothRemoteDevices( 5045): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 241
E/BluetoothRemoteDevices( 5045): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,D/BtConfig.SecureMode( 5045): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5045): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 241
,E/BluetoothRemoteDevices( 5045): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/BtConfig.SecureMode( 5045): isSecureModeOn:false
E/BluetoothRemoteDevices( 5045): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 241
E/bt-btif ( 5045): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 5045): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
E/bt-btif ( 5045): btif_sock_init: !radio_req && !rfc_init
,D/IOP_DB_BT( 5045): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 5045): db_open: db_open : handle 2010043436l, read 9734 bytes onto local cache
D/IOP_DB_BT( 5045): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 5045): db_query: result 1
,I/        ( 5045): iop_db_open: iop_db_open status 0
I/bte_conf( 5045): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 5045): [1] primary_record=1 vendor_id=0x0075 vendor_id_source=0x0001 product_id=0x0100 version=0x0200
I/bte_conf( 5045): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 5045): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothAdapterState( 5045): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 5045): ScanMode =  20
,D/BluetoothAdapterProperties( 5045): State =  11
D/BtConfig.SecureMode( 5045): isSecureModeOn:false
,D/BtConfig.SecureMode( 5045): isSecureModeOn:false
D/BtConfig.SecureMode( 5045): isSecureModeOn:false
,D/BtConfig.SecureMode( 5045): isSecureModeOn:false
D/BtConfig.SecureMode( 5045): isSecureModeOn:false
D/BtConfig.SecureMode( 5045): isSecureModeOn:false
D/BtConfig.SecureMode( 5045): isSecureModeOn:false
,D/BtConfig.SecureMode( 5045): isSecureModeOn:false
,I/BluetoothAdapterState( 5045): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 5045): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5045): updateAdapterState state is 12
,D/BluetoothAdapterService( 5045): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterService(1113232880)( 5045): Register RemoteMessageListener
D/BluetoothInputDevice( 5019): onBluetoothStateChange: up=true
D/HeadsetService( 5045): registerMessageListener
D/BluetoothA2dp( 5019): onBluetoothStateChange: up=true
D/HeadsetStateMachine( 5045): Disconnected process message: 70
D/HeadsetStateMachine( 5045): processRegisterMessageListener : 2, com.android.bluetooth.btservice.RemoteDevices$1@426045c8
D/BluetoothAdapterService( 5045): Autoconnection is available 
D/BluetoothA2dp( 2422): onBluetoothStateChange: up=true
D/BluetoothAdapterService( 5045): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 5045): starting service from this receiver
D/BluetoothA2dp( 4131): onBluetoothStateChange: up=true
D/BluetoothAdapterService( 5045): initWakeLock, pfd lock: {ParcelFileDescriptor: FileDescriptor[85]}, pfd unlock: {ParcelFileDescriptor: FileDescriptor[86]}
D/bluedroid( 5045): init_wake_lock lock_fd:85, unlock_fd:86
W/ContextImpl( 5045): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.startService:506 com.android.bluetooth.btservice.AdapterService.updateAdapterState:653 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
V/MaBo    ( 7033): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/BluetoothAdapterState( 5045): Entering On State from state = 11
W/InputMethodManagerService( 2422): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2422): [BT Setting State] State =12
,I/InputMethodManagerService( 2422): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/BluetoothAdapterService(1113232880)( 5045): Get Bonded Devices being called
D/PhoneApp( 2755): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 12
I/QuickConnect[1.1][2] ( 5019): BluetoothHelper.ACTION_STATE_CHANGED - STATE_ON
D/BluetoothHeadset( 2755): registerListener : 11, listenercom.android.phone.PhoneGlobals$MessageListener@427b3ae8, true
I/SamsungIME( 3005): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothHeadset( 2755): registerMessageListener
D/HeadsetService( 5045): registerMessageListener
D/HeadsetService( 5045): registerMessageListener
D/HeadsetStateMachine( 5045): Disconnected process message: 70
D/HeadsetStateMachine( 5045): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@42676ee8
D/BluetoothPanServiceJni( 5045): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
D/PhoneApp( 2755): registerMessageListener
I/BluetoothPbapService( 5045): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,I/BluetoothPbapService( 5045): Handler(): got msg=1
,V/BluetoothPbapService( 5045): PBAP Service initSocket try: 0
,D/STATUSBAR-IconMerger( 2583): checkOverflow(336), More:false, Req:false Child:2
W/BluetoothAdapter( 5045): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothMapMasInstance( 5045): set MAP SDP message type : 1
E/BluetoothServiceJni( 5045): SOCK FLAG = 1 ***********************
D/BluetoothPbapService( 5045): PBAP Socket is BluetoothServerSocket
W/BluetoothAdapter( 5045): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 5045): SOCK FLAG = 3 ***********************
I/System.out( 7033): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
I/System.out( 7033): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
I/System.out( 7033): moge zapisać w resDir?true
,V/MaBo    ( 7033): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 7033): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 7033): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,W/GAV2    ( 7033): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/GAV2    ( 7033): Thread[main,5,main]: ExceptionReporter created, original handler is pl.k2.droidoaudioteka.common.helpers.AudiotekaExceptionHandler
,I/AUDIOTEKA_GA( 7033): init tracking...
,I/AUDIOTEKA_GA( 7033): app started!
,D/GKI_LINUX( 5045): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,I/BugSenseHandler( 7033): Registering default exceptions handler
,D/AuthorizationBluetoothService( 2855): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/knox    ( 4962): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 4962): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/knox    ( 4962): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 4962): KNOXAgentService : onCreate()
D/knox    ( 4962): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 4962): KNOXAgentService. startJobThread() start
D/knox    ( 4962): KNOXAgentService. JobThread()
D/knox    ( 4962): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 4962): KNOXAgentService. startJobThread() wait
,I/DownloadService( 7033): Tworzenie serwisu - onCreate()
,I/DownloadService( 7033): Start serwisu - onStart()
,I/BugSenseHandler( 7033): Registering default exceptions handler
,I/SELinux ( 7071): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7071):  
,D/knox    ( 4962): KNOXAgentService : onDestroy().
,D/knox    ( 4962): ModuleBase.cancelAllAlarmManageModule()
,I/BugSenseHandler( 7033): Flushing...
,I/BugSenseHandler( 7033): Registering default exceptions handler
,I/PlayerService( 7033): Tworzenie serwisu - onCreate()
,I/MediaFocusControl( 2422):   Remote Control   registerMediaButtonIntent() for PendingIntent{45006110: PendingIntentRecord{4518d980 pl.k2.droidoaudioteka broadcastIntent}}
,V/KeyguardUpdateMonitor( 2583): handleSetGenerationId(g=2, clear=true)
I/SELinux ( 7071): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7071):  
I/SELinux ( 7071):  
,I/SELinux ( 7071): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/BugSenseHandler( 7033): Flushing...
E/SELinux ( 7071): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7071): >>>>> Normal User
,E/dalvikvm( 7071): >>>>> tv.peel.smartremote [ userId:0 | appId:10165 ]
,E/SELinux ( 7071): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/BugSenseHandler( 7033): Registering default exceptions handler
,V/AUDIOTEKA_MB( 7033): new AudioManagerFocusWrapper in playerservice oncreate
,I/PlayerService( 7033): Start serwisu - onStart()
,D/TimaKeyStoreProvider( 7071): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7071): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7071): Added TimaKesytore provider
,I/System.out( 7033): Thread-599(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7033): Thread-599(ApacheHTTPLog):isShipBuild true
,I/System.out( 7033): Thread-599(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 7033): pool-1-thread-2 calls detatch()
,W/BugSenseHandler( 7033): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
I/System.out( 7033): pool-1-thread-1 calls detatch()
,W/BugSenseHandler( 7033): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
,D/dalvikvm( 7071): GC_CONCURRENT freed 2999K, 32% free 9572K/14076K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 7071): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 7031): wlan0: Setting scan request: 0 sec 100000 usec
,E/Tethering( 2422): No numeric data
,I/ConnectivityService( 2422): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering( 2422): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
D/Tethering( 2422): interfaceStatusChanged wlan0, true
D/NtpTrustedTime( 2422): forceRefresh() from cache miss
,D/NtpTrustedTime( 2422): forceRefresh Fail.
V/NetworkStats( 2422): performPollLocked(flags=0x1)
,V/NetworkStats( 2422): performPollLocked() took 17ms
I/wpa_supplicant( 7031): >>>>> Not GET KEY, IV <<<<<
D/NtpTrustedTime( 2422): forceRefresh() from cache miss
I/wpa_supplicant( 7031): >>>>> Not GET KEY, IV <<<<<
D/NtpTrustedTime( 2422): forceRefresh Fail.
I/wpa_supplicant( 7031): rfkill: Cannot open RFKILL control device
D/Tethering( 2422): interfaceLinkStateChanged p2p0, true
D/Tethering( 2422): interfaceStatusChanged p2p0, true
D/Tethering( 2422): interfaceLinkStateChanged p2p0, true
D/Tethering( 2422): interfaceStatusChanged p2p0, true
,W/ContextImpl( 5506): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/wpa_supplicant( 7031): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 7031): P2P: initialized channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,I/wpa_supplicant( 7031): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 7031): Skip scan - bUseNetwork false
,D/WifiStateMachine( 2422): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative( 2422): callSECApiString - ID [21]
I/wpa_supplicant( 7031): HOTSPOT20_ENABLE called
,I/wpa_supplicant( 7031): wlan0: HS20_DISABLED_COMPLETE normal
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/LocalBluetoothProfileManager( 5506): Adding local A2DP profile
,D/WifiNative( 2422): callSECApiInt - ID [65]
,D/LocalBluetoothProfileManager( 5506): Adding local HEADSET profile
W/ContextImpl( 5506): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
,E/BluetoothHeadset( 5506): BTStateChangeCB is registed
,E/WifiConfigStore( 2422): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,E/BluetoothHeadset( 5506): BluetoothHeadset service is binded
,W/ContextImpl( 5506): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
D/WifiNative( 2422): callSECApiBoolean - ID [13]
I/wpa_supplicant( 7031): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 7031): reset timer : RESET_TIMER 0
I/wpa_supplicant( 7031): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 7031): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 7031): First Scan Start
,W/ContextImpl( 5506): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/Bluetoothsap( 5506): bindService called to Bluetooth SAP Service
I/wpa_supplicant( 7031): Scan requested (ret=0) - scan timeout 30 seconds
W/Settings( 5297): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 2422): Set the Nv default ccode
,W/ContextImpl( 5506): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,W/ContextImpl( 5506): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
,D/WifiStateMachine( 2422): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,E/WifiStateMachine( 2422): HS20_DISABLED_COMPLETEnormal
,D/WifiP2pService( 2422): P2pDisabledState{ what=131203 }
D/LocalBluetoothProfileManager( 5506): PANU : true
D/LocalBluetoothProfileManager( 5506): Adding local MAP profile
D/CommandListener( 1916): Setting iface cfg
,D/BluetoothMap( 5506): Create BluetoothMap proxy object
W/ContextImpl( 5506): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,W/ContextImpl( 5506): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/Bluetoothsap( 5506): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 5506): LocalBluetoothProfileManager construction complete
W/ContextImpl( 5506): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/CommandListener( 1916): Trying to bring up p2p0
,I/wpa_supplicant( 7031): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,D/DockEventReceiver( 5506): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 5506): onReceive
,D/WifiMonitor( 2422): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 2422): P2pEnablingState
D/WifiP2pService( 2422): P2pEnablingState{ what=147457 }
D/WifiP2pService( 2422): P2p socket connection successful
D/WifiP2pService( 2422): P2pEnabledState
,D/WifiP2pService( 2422): sending p2p connection changed broadcast: IDLE
D/BluetoothA2dp( 5506): Proxy object connected
E/WifiStateMachine( 2422): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/A2dpProfile( 5506): Bluetooth service connected
D/WifiDisplayController( 2422): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController( 2422): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 2422): disconnect
D/WifiDisplayController( 2422): updateConnection
D/WifiDisplayController( 2422): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 2422): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/QuickConnect[1.1][2] ( 5019): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
W/WifiP2pStateTracker( 2422): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/QuickConnect[1.1][2] ( 5019): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/BtConfig.SecureMode( 5045): isSecureModeOn:false
,D/QuickConnect[1.1][2] ( 5019): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
D/WifiDisplayController( 2422): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiP2pService( 2422): DeviceAddress: 02:e0:6d
,D/QuickConnect[1.1][2] ( 5019): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
D/WifiDisplayAdapter( 2422): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiDisplayController( 2422): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: S5mini-1
D/WifiDisplayController( 2422):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiDisplayController( 2422):  primary type: 10-0050F204-5
D/WifiDisplayController( 2422):  secondary type: null
D/WifiDisplayController( 2422):  wps: 0
D/WifiDisplayController( 2422):  grpcapab: 0
D/WifiDisplayController( 2422):  devcapab: 0
D/WifiDisplayController( 2422):  status: 3
D/WifiDisplayController( 2422):  wfdInfo: null
D/WifiDisplayController( 2422):  groupownerAddress: null
D/WifiDisplayController( 2422):  GOdeviceName: null
D/WifiDisplayController( 2422):  interfaceAddress: 
D/WifiDisplayController( 2422):  SConnectInfo : null
,D/WifiP2pService( 2422): sending p2p persistent groups changed broadcast
,D/WifiP2pService( 2422): InactiveState
,D/WifiP2pService( 2422): InactiveState{ what=139287 }
,D/HeadsetProfile( 5506): Bluetooth service connected
,D/QuickConnect[1.1][2] ( 5019): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/WifiP2pService( 2422): P2pEnabledState{ what=139287 }
,D/WifiP2pService( 2422): DefaultState{ what=139287 }
D/AuthorizationBluetoothService( 2855): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/AuthorizationBluetoothService( 2855): Proximity feature is not enabled.
,D/Bluetoothsap( 5506): BluetoothSAP Proxy object connected
,D/SapProfile( 5506): Bluetooth service connected
,D/Bluetoothsap( 5506): getConnectedDevices()
,D/BluetoothInputDevice( 5506): Proxy object connected
,D/HidProfile( 5506): Bluetooth service connected
,D/BluetoothPan( 5506): BluetoothPAN Proxy object connected
,D/PanProfile( 5506): Bluetooth service connected
,W/BluetoothAdapter( 5045): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 5045): SOCK FLAG = 0 ***********************
D/GKI_LINUX( 5045): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,I/BtOppRfcommListener( 5045): Accept thread started.
,D/BluetoothMap( 5506): Proxy object connected
D/MapProfile( 5506): Bluetooth service connected
,D/BluetoothPbap( 5506): Proxy object connected
D/PbapServerProfile( 5506): Bluetooth service connected
D/Bluetoothsap( 5506): BluetoothSAP Proxy object connected
D/SapProfile( 5506): Bluetooth service connected
,D/Bluetoothsap( 5506): getConnectedDevices()
,I/ActivityManager( 2422): Killing 5659:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,I/knox    ( 4962): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 4962): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 4962): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 4962): KNOXAgentService : onCreate()
,D/knox    ( 4962): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 4962): KNOXAgentService. startJobThread() start
,D/knox    ( 4962): KNOXAgentService. JobThread()
D/knox    ( 4962): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 4962): KNOXAgentService. startJobThread() wait
,D/knox    ( 4962): KNOXAgentService : onDestroy().
,D/knox    ( 4962): ModuleBase.cancelAllAlarmManageModule()
,D/knox    ( 4962): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
,D/NearbySettings( 5506): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 5506): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 5506): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 5506): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 5506): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5506): DMSUtil.isNetworkConnected - WIFI: IDLE
,I/NearbySettings( 5506): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5506): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5506): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5506): MountReceiver.mPrefHandler - 7002
,D/FileShare-Server( 5921): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Server( 5921): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,D/GKI_LINUX( 5045): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,I/wpa_supplicant( 7031): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,I/wpa_supplicant( 7031): nl80211: Received scan results (7 BSSes)
I/wpa_supplicant( 7031): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 7031): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 7031): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 7031): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,I/wpa_supplicant( 7031): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 7031): Associated with C0.AA.48
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 7031): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 2422): Error! unhandled message{ when=-41ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 7031): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 7031): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 7031): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 7031): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/WifiNative( 2422): callSECApiVoid - ID [50]
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7107): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7107):  
,D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7107): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7107):  
I/SELinux ( 7107):  
,I/SELinux ( 7107): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7107): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7107): >>>>> Normal User
,E/dalvikvm( 7107): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7107): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
V/HeadsetService( 5045): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/HeadsetStateMachine( 5045): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaKeyStoreProvider( 7107): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7107): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7107): Added TimaKesytore provider
D/STATUSBAR-IconMerger( 2583): checkOverflow(336), More:false, Req:false Child:2
,D/WifiP2pService( 2422): InactiveState{ what=143375 }
,D/WifiP2pService( 2422): P2pEnabledState{ what=143375 }
,D/dalvikvm( 7107): GC_CONCURRENT freed 2985K, 32% free 9582K/14076K, paused 6ms+2ms, total 31ms
,D/dalvikvm( 7107): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/System.out( 7107): Inside WakeupProvider
,I/System.out( 7107): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 7107): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7107): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7107): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,I/dhcpcd  ( 7122): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7122): bssid match
,D/NearbySettings( 5506): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5506): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5506): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
,I/NearbySettings( 5506): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5506): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
D/DialogFlow( 7107): initQueue()
,I/NearbySettings( 5506): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5506): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2422): Killing 5732:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,E/Watchdog( 2422): !@Sync 9
,D/WifiP2pService( 2422): InactiveState{ what=143375 }
,D/WifiP2pService( 2422): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2422): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2422): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2422): CaptivePortalCheckState enter
,D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2422): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2422): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2422): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
D/ConnectivityService( 2422): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2422): net.tcp.usercfg.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2422): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/NearbySettings( 5506): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
D/ConnectivityService( 2422): handleConnectivityChange: setting default proxy info 
,I/NearbySettings( 5506): MountReceiver.onReceive - Keep current state
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/NearbySettings( 5506): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5506): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5506): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 5506): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5506): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5506): MountReceiver.onReceive - Keep current state
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/NtpTrustedTime( 2422): forceRefresh() from cache miss
V/NetworkStats( 2422): updateIfacesLocked()
V/NetworkStats( 2422): performPollLocked(flags=0x1)
,V/NetworkStats( 2422): performPollLocked() took 22ms
,D/NearbySettings( 5506): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 5506): MountReceiver.onReceive - Keep current state
,D/NtpTrustedTime( 2422): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1449683854918 mCachedNtpElapsedRealtime : 289252 mCachedNtpCertainty : 13
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,V/NetworkStats( 2422): advisePersistThreshold() given 9223372036854775, clamped to 2097152
I/SurfaceFlinger( 1922): id=20 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 2422): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2422
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 340, Delta = 20
,D/Tethering( 2422): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2422): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2422): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
D/        ( 2422): Setting time of day to sec=1449683855
,D/        ( 2422): Trying to open a file
D/        ( 2422): File Open Success
D/        ( 2422): File Close Success
,I/        ( 2422): DRM_TIME_PATH CHMOD 660 for resetState done 
D/STATUSBAR-NetworkController( 2583): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2583): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2583): updateDataNetType()
D/STATUSBAR-NetworkController( 2583): NoService, mRoamingIconId = 0
V/AlarmManager( 2422): waitForAlarm result :65536
,I/DBG_DM  ( 4641): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/DBG_DM  ( 4641): [3.19.140541][Line:609][onReceive] ----------- XEVENT_DM_INIT WIFI ok
I/PCWCLIENTTRACE_PushUtil( 6339): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6339): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6339): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6339): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 4641): [3.19.140541][Line:214][xdmAgentTaskHandler] XEVENT_DM_INIT
,I/DBG_DM  ( 4641): [3.19.140541][Line:432][xdmInitAdpWaitSystemRootingCheck] Check completed.
,I/DBG_DM  ( 4641): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
D/StatusBar-DoNotDistrub( 2583): Received intent with android.intent.action.TIME_SET action
,D/StatusBar-DoNotDistrub( 2583): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/NotificationMgr( 2755): updateNotificationsAtStartup()...
D/NotificationMgr( 2755): - start call log query...
,I/DBG_DM  ( 4641): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 4641): [3.19.140541][Line:78][xdmFeatureGetBearerSettingFromCSCFotaDataBase] 
,I/SELinux ( 7171): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7171):  
,W/Settings( 2422): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Parcel  ( 2422): nm 23
,I/PrGenericPlugin( 1925): [A] ENTER onAcquireDrmInfo : 0xd7c
I/PrGenericPlugin( 1925): [A] LEAVE onAcquireDrmInfo : 0xd7c
,I/DrmEventService( 2422):  no response from SecureClock 
,D/StatusBar-DoNotDistrub( 2583): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,I/AudioService( 2422): getStreamVolume 5 index 110
D/StatusBar-DoNotDistrub( 2583): The STREAM NOTIFICATION volume is 0
D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=com.android.systemui
,D/STATUSBAR-NotificationService( 2422): received android.intent.action.DORMANT_MODE_OFF
,D/LightsService( 2422): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2422) 
,I/SensorManagerA( 2422): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2422): LightSensor setDelay = 200000000
,D/LightsService( 2422): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/SELinux ( 7171): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7171):  
I/SELinux ( 7171):  
I/SELinux ( 7171): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/Sensors ( 2422): LightSensor setSensorDelay = 200000000
D/Sensors ( 2422): Light sensor flush: not enabled 0
D/Sensors ( 2422): LightSensor enable = 1
D/Sensors ( 2422): LightSensor enableSensor = 1
E/SELinux ( 7171): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7171): >>>>> Normal User
E/dalvikvm( 7171): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
D/NotificationMgr( 2755): call log query complete.
D/NotificationMgr( 2755): call log cursor count : 0
D/NotificationMgr( 2755): call log cursor count2 : null
D/SensorManager( 2422): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
E/SELinux ( 7171): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/TimaKeyStoreProvider( 7171): in addTimaSignatureService
,I/DBG_DM  ( 4641): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,I/DBG_DM  ( 4641): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/dalvikvm( 4641): Total arena pages for JIT: 11
,I/dalvikvm( 4641): Total arena pages for JIT: 12
I/dalvikvm( 4641): Total arena pages for JIT: 13
I/dalvikvm( 4641): Total arena pages for JIT: 14
,I/dalvikvm( 4641): Total arena pages for JIT: 15
I/dalvikvm( 4641): Total arena pages for JIT: 16
,I/dalvikvm( 4641): Total arena pages for JIT: 17
,I/DBG_DM  ( 4641): [3.19.140541][Line:5949][xdbGetFUMOInitiatedType] Initiated Type: 2
,I/DBG_DM  ( 4641): [3.19.140541][Line:119][xdmInitAdpEXTInit] nStatus [220]
,I/DBG_DM  ( 4641): [3.19.140541][Line:463][xdmGetEnableLiveDemoFromCSCFeature] enable LiveDemo : false
,D/TimaKeyStoreProvider( 7171): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7171): Added TimaKesytore provider
,E/DBG_DM  ( 4641): Warning!!! [3.19.140541][Line:65][xdmInitAdpGetSIMLockState] SIM Status is not ready
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/DBG_DM  ( 4641): [3.19.140541][Line:261][xdmInitAdpEXTInit] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 4641): [3.19.140541][Line:271][xdmAgentTaskHandler] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 4641): [3.19.140541][Line:769][xdmUIEvent] XUI_DL_UPDATE_START
,I/DBG_DM  ( 4641): [3.19.140541][Line:369][handleMessage] event ->214
,I/DBG_DM  ( 4641): [3.19.140541][Line:1854][xdmAgentCheckResumeNoti] 
I/SQLiteSecureOpenHelper( 4131): getWritableDatabase(pwd)
I/DBG_DM  ( 4641): [3.19.140541][Line:318][xdmBroadcastGetIsSavedNfcMode] m_IsSavedNfcMode : false
,I/SQLiteSecureOpenHelper( 4131): getDatabaseLocked(b,b,pwd)...
,I/DBG_DM  ( 4641): [3.19.140541][Line:546][xuiAdpGetUpdateReport] Get bUpdateReport = false
,I/DBG_DM  ( 4641): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 4641): [3.19.140541][Line:2008][xdmCallUiFotaInstall] 
,I/DBG_DM  ( 4641): [3.19.140541][Line:729][xdmUIEvent] XUI_DL_UPDATE_CONFIRM
W/ContextImpl( 4641): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 com.wssyncmldm.XDMService.xdmCallUiFotaInstall:2023 com.wssyncmldm.XDMService$1.handleMessage:372 android.os.Handler.dispatchMessage:102 
D/Sensors ( 2422): LightSensor enable = 0
,D/Sensors ( 2422): LightSensor enableSensor = 0
,D/SensorManager( 2422): unregisterListener ::   
D/LightsService( 2422): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2422): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/DBG_DM  ( 4641): [3.19.140541][Line:890][xdmUnRegisterBatteryReceiver] 
,E/DBG_DM  ( 4641): Warning!!! [3.19.140541][Line:898][xdmUnRegisterBatteryReceiver] didn't register
,E/DBG_DM  ( 4641): Warning!!! [3.19.140541][Line:899][xdmUnRegisterBatteryReceiver] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.XDMService$3@426af980
,I/DBG_DM  ( 4641): [3.19.140541][Line:1320][xdmCheckIdleScreen] Idle Screen : false
,W/dalvikvm( 2738): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2738): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2738): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 2738): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
,W/dalvikvm( 2738): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 7171): GC_CONCURRENT freed 3006K, 33% free 9566K/14076K, paused 4ms+1ms, total 56ms
D/dalvikvm( 7171): WAIT_FOR_CONCURRENT_GC blocked 48ms
,D/dalvikvm( 2738): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2738): Using platform SSLCertificateSocketFactory
,I/SQLiteSecureOpenHelper( 4131): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4131): getDatabaseLocked(b,b,pwd)...
,D/dalvikvm( 2422): GC_CONCURRENT freed 3828K, 57% free 24674K/56260K, paused 23ms+17ms, total 237ms
,D/dalvikvm( 2422): WAIT_FOR_CONCURRENT_GC blocked 91ms
,D/dalvikvm( 2855): GC_CONCURRENT freed 1833K, 24% free 10842K/14248K, paused 4ms+16ms, total 93ms
,I/GAV2    ( 7033): Thread[GAThread,5,main]: connecting to Analytics service
,W/ContextImpl( 7033): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:529 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,D/PackageManager( 2422): [MSG] WRITE_PACKAGE_RESTRICTIONS
D/dalvikvm( 2422): GC_EXPLICIT freed 193K, 57% free 24522K/56260K, paused 14ms+20ms, total 187ms
,D/AmoledAdjustTimer( 2422): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,I/GAV2    ( 7033): Thread[GAThread,5,main]: connect: bindService returned true for Intent { act=com.google.android.gms.analytics.service.START (has extras) }
,I/DBG_DM  ( 4641): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/GAV2    ( 7033): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 7033): Thread[GAThread,5,main]: putHit called
,I/dalvikvm( 4641): Total arena pages for JIT: 18
,D/GAV2    ( 7033): Thread[main,5,main]: service connected, binder: android.os.BinderProxy@4275d920
,D/GAV2    ( 7033): Thread[main,5,main]: bound to service
,I/GAV2    ( 7033): Thread[main,5,main]: Connected to service
,I/GAV2    ( 7033): Thread[GAThread,5,main]: Sending hit to service
,I/DBG_DM  ( 4641): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2422): sendNotification(1) - 4
,W/ResourceType( 2583): Attempt to retrieve bag 0x01030068 which is invalid or in a cycle.
,W/ResourceType( 2583): Attempt to retrieve bag 0x01030067 which is invalid or in a cycle.
,D/ProgressBar( 2583): setProgressDrawable drawableHeight = 12
,D/ProgressBar( 2583): setProgressDrawable drawableHeight = 12
,D/PhoneStatusBar( 2583): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@425b7360
,I/SELinux ( 7204): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7204):  
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,I/SELinux ( 7204): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7204):  
I/SELinux ( 7204):  
,I/SELinux ( 7204): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7204): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 7204): >>>>> Normal User
,E/dalvikvm( 7204): >>>>> com.android.chrome [ userId:0 | appId:10085 ]
,E/SELinux ( 7204): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 7204): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7204): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7204): Added TimaKesytore provider
,I/PhenotypeConfigurator( 2738): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,I/SELinux ( 7217): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7217):  
,D/dalvikvm( 7204): GC_CONCURRENT freed 2992K, 32% free 9572K/14068K, paused 3ms+2ms, total 22ms
,D/dalvikvm( 7204): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/SELinux ( 7217): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7217):  
I/SELinux ( 7217):  
,I/SELinux ( 7217): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7217): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7217): >>>>> Normal User
,E/dalvikvm( 7217): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7217): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7217): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7217): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7217): Added TimaKesytore provider
,I/dalvikvm( 3284): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 3284): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 3284): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm( 7217): GC_CONCURRENT freed 2996K, 33% free 9564K/14068K, paused 5ms+1ms, total 33ms
,D/dalvikvm( 7217): WAIT_FOR_CONCURRENT_GC blocked 18ms
,E/ActivityThread( 3284): Failed to find provider info for com.android.contacts.metadata
,D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection...
,E/Auth.Api.Credentials( 3284): [CredentialSyncAdapter] Unknown sync event.
,D/btif_config_util( 5045): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/dalvikvm( 2738): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 2738): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2738): VFY: replacing opcode 0x6e at 0x003d
,I/SELinux ( 7237): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7237):  
,I/SELinux ( 7237): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7237):  
I/SELinux ( 7237):  
,I/SELinux ( 7237): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7237): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7237): >>>>> Normal User
,E/dalvikvm( 7237): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7237): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7237): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7237): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7237): Added TimaKesytore provider
,W/System.err( 7217): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7217): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7217): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7217): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7217): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7217): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 7217): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7217): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7217): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7217): Caused by: java.lang.NullPointerException
W/System.err( 7217): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7217): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7217): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7217): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7217): 	... 8 more
,I/ActivityManager( 2422): Killing 5760:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/System.out( 2738): Thread-118(HTTPLog):isShipBuild true
,I/System.out( 2738): Thread-118(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 7237): GC_CONCURRENT freed 3000K, 33% free 9565K/14072K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7237): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/KLMS-2.3.201 : ( 7237): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7237): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449683857126
,I/KLMS-2.3.201 : ( 7237): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/ActivityManager( 2422): Killing 5838:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,I/SELinux ( 7253): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7253):  
,I/LocationTagReadyService( 3439): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3439): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3439): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3439): [Slink platform] The state of Slink geocode service is true
,D/dalvikvm( 1923): GC_EXPLICIT freed 42K, 15% free 9501K/11052K, paused 2ms+3ms, total 34ms
I/SELinux ( 7253): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7253):  
I/SELinux ( 7253):  
,I/SELinux ( 7253): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7253): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7253): >>>>> Normal User
,E/dalvikvm( 7253): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7253): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7253): in addTimaSignatureService
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 15% free 9501K/11052K, paused 3ms+4ms, total 33ms
,D/TimaKeyStoreProvider( 7253): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7253): Added TimaKesytore provider
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 15% free 9501K/11052K, paused 3ms+4ms, total 33ms
,I/SELinux ( 7265): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7265):  
,I/GallerySearchProvider( 3566): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7265): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7265):  
I/SELinux ( 7265):  
,I/SELinux ( 7265): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7265): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7265): >>>>> Normal User
,E/dalvikvm( 7265): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7265): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7265): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7265): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7265): Added TimaKesytore provider
,I/SELinux ( 7277): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7277):  
,D/dalvikvm( 7253): GC_CONCURRENT freed 2997K, 32% free 9571K/14076K, paused 4ms+1ms, total 35ms
,D/dalvikvm( 7253): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/SO_AGENT( 7253): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7253): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
I/SELinux ( 7277): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7277):  
I/SELinux ( 7277):  
,I/SELinux ( 7277): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7277): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7277): >>>>> Normal User
,E/dalvikvm( 7277): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7277): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7277): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7277): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7277): Added TimaKesytore provider
D/dalvikvm( 7265): GC_CONCURRENT freed 2892K, 32% free 9670K/14072K, paused 14ms+3ms, total 36ms
D/dalvikvm( 7265): WAIT_FOR_CONCURRENT_GC blocked 2ms
I/SA      ( 6505): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
D/dalvikvm( 7277): GC_CONCURRENT freed 3000K, 33% free 9566K/14072K, paused 3ms+2ms, total 21ms
D/dalvikvm( 7277): WAIT_FOR_CONCURRENT_GC blocked 13ms
I/ActivityManager( 2422): Killing 5480:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
V/KVNProvider( 7277): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
V/KVNProvider( 7277): getFindoCursor query string : 
I/SA      ( 6505): [BDLM] already registered in spp
I/SA      ( 6505): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
I/SA      ( 6505): [OR] == ACTION_CONNECTIVITY_CHANGE ==
V/KVNProvider( 7277): getTagSearchCursor() tagSearchCursor count : 0
I/ActivityManager( 2422): Killing 5585:com.google.android.music:main/u0a125 (adj 15): empty #43
D/dalvikvm( 6446): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x425828c8, skipping init
I/SA      ( 6505): [SLFUCHKMGR] constructor called
I/SA      ( 6505): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6505): [OR] == isSIMCardReady false ==
I/SA      ( 6505): [SCU] == networkStateCheck == true
I/SA      ( 6505): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6505): isChinaCountryCode : false
I/SA      ( 6505): [OR] == networkStateCheck true ==
I/SecureStorage( 6446): [INFO]: SPID(0x00000000)Processing data
I/SA      ( 6505): [OR] GetMyCountryZoneTask
I/SecureStorage( 1961): [INFO]: SPID(0x00000004)Credentials: uid 1000, gid 1000, pid 6446
I/SecureStorage( 1961): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
I/SA      ( 6505): [OR] onReceive END
I/SA      ( 6505): [SRS] prepareGetMyCountryZone
I/ActivityManager( 2422): Killing 5718:com.sec.phone/1001 (adj 15): empty #43
I/SA      ( 6505): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6505): [SSP] query invoked
D/PhoneNumberLocatorBootCompletedReceiver( 2755): onReceive
D/PhoneNumberLocatorBootCompletedReceiver( 2755): Phone number locator feature is dsiabled
I/SA      ( 6505): [TPMU] GetMccFromDB : null
I/SA      ( 6505): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6505): [TPM] isNoProxy(default) : true
I/SA      ( 6505): [RC New] Execute method=[GET] start
I/SELinux ( 7297): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7297):  
I/SELinux ( 7297): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7297):  
I/SELinux ( 7297):  
I/SELinux ( 7297): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7297): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7297): >>>>> Normal User
E/dalvikvm( 7297): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
E/SELinux ( 7297): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 7297): in addTimaSignatureService
D/TimaKeyStoreProvider( 7297): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7297): Added TimaKesytore provider
D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection...
D/dalvikvm( 7297): GC_CONCURRENT freed 2998K, 33% free 9569K/14076K, paused 6ms+2ms, total 26ms
D/dalvikvm( 7297): WAIT_FOR_CONCURRENT_GC blocked 16ms
E/WifiStateMachine( 2422): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
I/sCloudBackupApp( 7297): sCloudBackupApp Version Info : 3.7.3.KK_APP
I/SCloudBackupReceiver( 7297): Other Intent
I/ActivityManager( 2422): Killing 5737:com.android.calendar/u0a144 (adj 15): empty #43
I/SELinux ( 7310): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7310):  
D/dalvikvm( 2738): GC_CONCURRENT freed 1630K, 22% free 11776K/15012K, paused 10ms+37ms, total 103ms
I/System.out( 6505): Thread-557(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/SELinux ( 7310): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7310):  
I/SELinux ( 7310):  
I/SELinux ( 7310): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7310): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7310): >>>>> Normal User
E/dalvikvm( 7310): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
E/SELinux ( 7310): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/System.out( 6505): Thread-557(ApacheHTTPLog):isShipBuild true
I/System.out( 6505): Thread-557(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/TimaKeyStoreProvider( 7310): in addTimaSignatureService
D/TimaKeyStoreProvider( 7310): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7310): Added TimaKesytore provider
D/dalvikvm( 7310): GC_CONCURRENT freed 2995K, 32% free 9576K/14076K, paused 3ms+1ms, total 20ms
D/dalvikvm( 7310): WAIT_FOR_CONCURRENT_GC blocked 5ms
D/com.samsung.app( 7310): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/com.samsung.app( 7310): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
D/com.samsung.app( 7310): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
D/com.samsung.app( 7310): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
D/com.samsung.app( 7310): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/com.samsung.app( 7310): [KK AccuPhone]>>> RM:136 [0:0]  V init 
D/daemonapp( 5243): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/com.samsung.app( 7310): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
D/daemonapp( 5243): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/com.samsung.app( 7310): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
D/daemonapp( 5243): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/com.samsung.app( 7310): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
D/com.samsung.app( 7310): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2422): Killing 5785:com.android.providers.calendar/u0a45 (adj 15): empty #43
I/SELinux ( 7323): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7323):  
I/SELinux ( 7323): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7323):  
I/SELinux ( 7323):  
I/SELinux ( 7323): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7323): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7323): >>>>> Normal User
E/dalvikvm( 7323): >>>>> com.samsung.android.internal.headlines [ userId:0 | appId:10110 ]
E/SELinux ( 7323): [DEBUG] seapp_context_lookup: seinfoCategory = release
I/ActivityManager( 2422): Killing 5789:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
I/SurfaceFlinger( 1922): id=20 Removed Uoast (10/11)
I/SurfaceFlinger( 1922): id=20 Removed Uoast (-2/11)
D/TimaKeyStoreProvider( 7323): in addTimaSignatureService
D/PowerManagerService( 2422): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2422) eventTime = 292739
D/PowerManagerService( 2422): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2422 (0x0)
D/PowerManagerService( 2422): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2422, ws=WorkSource{1000}) (elapsedTime=3460)
D/TimaKeyStoreProvider( 7323): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7323): Added TimaKesytore provider
I/SurfaceFlinger( 1922): id=21 createSurf (1x1),1 flag=4, Uoast
D/PowerManagerService( 2422): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2422
,W/PhenotypeConfigurator( 2738): Server returned 404
,D/dalvikvm( 7323): GC_CONCURRENT freed 2999K, 33% free 9565K/14072K, paused 3ms+1ms, total 29ms
,D/dalvikvm( 7323): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/HeadlinesChannelApplication( 7323): [onCreate]
,D/Headlines( 7323): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 7323): getCountryCode(): countryCode = PL
,I/SELinux ( 7335): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7335):  
,D/Headlines( 7323): Breath.onCreate
,D/HeadlinesCardManager( 7323): HeadlinesCardManager : constructor
,E/HeadlinesCardManager( 7323): HeadlinesCardManager : ctor = image_cache size is 42MB
,D/SA Version( 7323): CardProvider Library : 13
,I/SELinux ( 7335): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7335):  
I/SELinux ( 7335):  
,I/SELinux ( 7335): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7335): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7335): >>>>> Normal User
,E/dalvikvm( 7335): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7335): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/MagazineService::CardProviderContentProvider( 6549): insertProvider: provider already exists.: com.samsung.android.app.headlines
,D/TimaKeyStoreProvider( 7335): in addTimaSignatureService
,D/MagazineService::CardProviderContentProvider( 6549): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 7323): registerCardProvider: provider already exists.
,D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/TimaKeyStoreProvider( 7335): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7335): Added TimaKesytore provider
I/Headlines( 7323): HeadlinesDataCenter ctor
I/Headlines( 7323): HeadlinesDataCenter. mLocale = en_US
D/HeadlinesChannelUtil( 7323): getCountryCode(): countryCode = PL
D/HeadlinesCardManager( 7323): HeadlinesCardManager : constructor welcome :YES
,I/SecureStorage( 1961): [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 1961): [INFO]: SPID(0x00000004)PID: 6446, TID: 6472
,D/dalvikvm( 7335): GC_CONCURRENT freed 2986K, 32% free 9581K/14076K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 7335): WAIT_FOR_CONCURRENT_GC blocked 11ms
,I/SecureStorage( 6446): [INFO]: SPID(0x00000000)Processing data has been completed
,D/dalvikvm( 2422): GC_EXPLICIT freed 1287K, 57% free 24598K/56260K, paused 13ms+18ms, total 192ms
,D/Headlines( 7323): Breath timer started. interval : 30000
,W/WifiP2pStateTracker( 2422): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/Headlines( 7323): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 7323): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 7323): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 7323): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 7323): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 7323): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 7323): requestUpdateNewsWelcomeCard !!! no welcome card
D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
D/ConnectivityService( 2422): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2422):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
D/ConnectivityService( 2422): handleConnectivityChange: setting default proxy info 
D/ConnectivityService( 2422): updateSourceRoutes : no source routing conditions
,D/DelayedSyncController( 7204): Delaying sync.
,V/WebViewChromium( 7335): Binding Chromium to the background looper Looper (main, tid 1) {42595358}
,I/chromium( 7335): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7335): Initializing chromium process, renderers=0
,D/SyncManager( 2422): failed sync operation 
,D/SyncManager( 2422): not retrying sync operation because the error is a hard error: 
,I/dalvikvm( 6446): Total arena pages for JIT: 11
I/dalvikvm( 6446): Total arena pages for JIT: 12
,I/dalvikvm( 6446): Total arena pages for JIT: 13
,I/dalvikvm( 6446): Total arena pages for JIT: 14
,I/dalvikvm( 6446): Total arena pages for JIT: 15
,I/dalvikvm( 6446): Total arena pages for JIT: 16
,I/dalvikvm( 6446): Total arena pages for JIT: 17
,W/chromium( 7335): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7335): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7335): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7335): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7335): Mali API Version : 401
,I/Mali    ( 7335): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/SA      ( 6505): [RC New] [v2liruge] api execute + 1454
,I/SA      ( 6505): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6505): AsyncTask #1 calls detatch()
,I/SA      ( 6505): [TPMU] getNetworkMcc : 
,D/NtpTrustedTime( 2422): getCachedNtpTime() cache hit
,I/SA      ( 6505): [SCU] saveMccToPreferece Start
I/SA      ( 6505): [SCU] RegionMCC : 260
,I/SA      ( 6505): [SSP] query invoked
,I/ActivityManager( 2422): Killing 5297:com.google.android.talk/u0a109 (adj 15): empty #43
I/SA      ( 6505): [TPMU] GetMccFromDB : null
I/SA      ( 6505): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6505): [SCU] saveMccToPreferece End
I/SA      ( 6505): [RC New] executeRequest [v2liruge] end. 1487
I/SA      ( 6505): [RC New] Execute end
I/SA      ( 6505): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6505): [OR] GetMyCountryZoneTask Success
,W/GAV2    ( 7335): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 7335): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 7335): Starting up...
,I/ImageResourceManager( 5673): ImageResourceManager: uninitalized
,I/iu.Environment( 5673): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager( 2422): Killing 5809:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
D/QuickConnect[1.1][2] ( 5019): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5019): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 5019): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425a1200
,I/SELinux ( 7383): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7383):  
,D/dalvikvm( 5673): GC_FOR_ALLOC freed 1103K, 30% free 9909K/14072K, paused 33ms, total 36ms
,I/dalvikvm-heap( 5673): Grow heap (frag case) to 13.173MB for 2129936-byte allocation
,I/SELinux ( 7383): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7383):  
I/SELinux ( 7383):  
,I/SELinux ( 7383): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/dalvikvm( 5673): GC_FOR_ALLOC freed <1K, 26% free 11989K/16156K, paused 17ms, total 17ms
E/SELinux ( 7383): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7383): >>>>> Normal User
,E/dalvikvm( 7383): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7383): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/iu.SyncManager( 5673): SYNC; picasa accounts
,D/TimaKeyStoreProvider( 7383): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7383): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7383): Added TimaKesytore provider
,I/PowerManagerService( 2422): [PWL] Off : 225s ago
I/PowerManagerService( 2422): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService( 2422): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2422): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.sec.android.gallery3d.picasa.contentprovider/com.google/eM_ADDR' (uid=1000, pid=2422, ws=WorkSource{10047}) (elapsedTime=48)
I/PowerManagerService( 2422): [PWL]       PARTIAL_WAKE_LOCK              'SyncLoopWakeLock' (uid=1000, pid=2422, ws=null) (elapsedTime=30)
,I/PowerManagerService( 2422): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.android.chrome/com.google/eM_ADDR' (uid=1000, pid=2422, ws=WorkSource{10085}) (elapsedTime=9)
D/dalvikvm( 5673): GC_CONCURRENT freed 43K, 26% free 11961K/16156K, paused 4ms+6ms, total 53ms
,I/iu.UploadsManager( 5673): num queued entries: 0
,I/iu.UploadsManager( 5673): num updated entries: 0
,I/iu.SyncManager( 5673): NEXT; no task
,D/PicasaService( 3566): start picasa sync
,D/DelayedSyncController( 7204): Delaying sync.
,D/PicasaService( 3566): end picasa sync
,D/dalvikvm( 7383): GC_CONCURRENT freed 2982K, 32% free 9587K/14072K, paused 4ms+3ms, total 27ms
,D/dalvikvm( 7383): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 5673): GC_FOR_ALLOC freed 58K, 27% free 11917K/16156K, paused 19ms, total 19ms
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/dalvikvm( 5673): GC_FOR_ALLOC freed 14K, 21% free 16091K/20324K, paused 17ms, total 17ms
,I/SELinux ( 7409): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7409):  
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,W/ActivityManager( 2422): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 7409): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7409):  
I/SELinux ( 7409):  
,I/SELinux ( 7409): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7409): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7409): >>>>> Normal User
,E/dalvikvm( 7409): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,I/SELinux ( 7414): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7414):  
,E/SELinux ( 7409): [DEBUG] seapp_context_lookup: seinfoCategory = release
I/ActivityManager( 2422): Killing 6287:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7409): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7409): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7409): Added TimaKesytore provider
,I/SELinux ( 7414): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7414):  
I/SELinux ( 7414):  
,I/SELinux ( 7414): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/ActivityManager( 2422): Killing 5927:com.google.android.partnersetup/u0a14 (adj 15): empty #43
E/SELinux ( 7414): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7414): >>>>> Normal User
E/dalvikvm( 7414): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
E/SELinux ( 7414): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7414): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7414): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7414): Added TimaKesytore provider
,D/dalvikvm( 7409): GC_CONCURRENT freed 3000K, 33% free 9568K/14076K, paused 2ms+1ms, total 23ms
,D/dalvikvm( 7409): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/BadgeProvider( 7409): onCreate
,D/BadgeProvider( 7409): DatabaseHelper
,D/BadgeProvider( 7409): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 2786): reloadBadges entered.
D/BadgeProvider( 7409): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7409): sendNotify, [notify] : null
D/BadgeProvider( 7409): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7409): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7409): update, [UpdateCount] : 1
,D/dalvikvm( 7414): GC_CONCURRENT freed 2997K, 33% free 9565K/14072K, paused 2ms+2ms, total 28ms
,D/dalvikvm( 7414): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/SELinux ( 7434): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7434):  
,I/ActivityManager( 2422): Killing 6312:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/SELinux ( 7434): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7434):  
I/SELinux ( 7434):  
,I/SELinux ( 7434): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7434): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 7434): >>>>> Normal User
,E/dalvikvm( 7434): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
,E/SELinux ( 7434): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7434): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7434): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7434): Added TimaKesytore provider
,D/dalvikvm( 7434): GC_CONCURRENT freed 3001K, 32% free 9569K/14072K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 7434): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/dalvikvm( 7434): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 7434): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 7434): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 7434): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7434): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7434): VFY: replacing opcode 0x22 at 0x0000
,E/dalvikvm( 7434): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
W/dalvikvm( 7434): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 7434): VFY: replacing opcode 0x22 at 0x0037
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6339): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6339): [hasSamungAccount] - No Samsung Account
,W/dalvikvm( 7434): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 7434): Link of class 'Ldqp;' failed
,W/dalvikvm( 7434): VFY: unable to find class referenced in signature (Ldqp;)
,W/dalvikvm( 7434): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7434): Link of class 'Ldqp;' failed
,I/dalvikvm( 7434): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 7434): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 7434): VFY: replacing opcode 0x6e at 0x0000
,E/dalvikvm( 7434): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
,W/dalvikvm( 7434): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7434): VFY: replacing opcode 0x22 at 0x0000
V/AlarmManager( 2422): waitForAlarm result :4
V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,W/dalvikvm( 7434): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 7434): Link of class 'Ldqp;' failed
,W/dalvikvm( 7434): VFY: unable to find class referenced in signature (Ldqp;)
,W/dalvikvm( 7434): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7434): Link of class 'Ldqp;' failed
,I/dalvikvm( 7434): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 7434): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
,D/dalvikvm( 7434): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 7434): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 7434): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
,D/dalvikvm( 7434): VFY: replacing opcode 0x1c at 0x0026
,W/dalvikvm( 7434): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 7434): Link of class 'Ldqp;' failed
W/dalvikvm( 7434): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7434): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
,W/dalvikvm( 7434): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7434): Link of class 'Ldqp;' failed
,I/dalvikvm( 7434): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 7434): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
,D/dalvikvm( 7434): VFY: replacing opcode 0x6e at 0x0003
,W/dalvikvm( 7434): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7434): Link of class 'Lax;' failed
,E/dalvikvm( 7434): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 7434): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
,D/dalvikvm( 7434): VFY: replacing opcode 0x22 at 0x0006
,W/dalvikvm( 7434): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7434): Link of class 'Laz;' failed
E/dalvikvm( 7434): Could not find class 'az', referenced from method g.a
W/dalvikvm( 7434): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
,D/dalvikvm( 7434): VFY: replacing opcode 0x22 at 0x002c
,I/dalvikvm( 7434): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 7434): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7434): VFY: replacing opcode 0x6e at 0x0008
,I/dalvikvm( 7434): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
W/dalvikvm( 7434): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 7434): VFY: replacing opcode 0x6e at 0x000c
,I/dalvikvm( 7434): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 7434): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7434): VFY: replacing opcode 0x6e at 0x0006
,I/dalvikvm( 7434): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 7434): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
,D/dalvikvm( 7434): VFY: replacing opcode 0x6e at 0x000a
,I/dalvikvm( 7434): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 7434): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
,D/dalvikvm( 7434): VFY: replacing opcode 0x72 at 0x0000
,I/dalvikvm( 7434): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
W/dalvikvm( 7434): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
,D/dalvikvm( 7434): VFY: replacing opcode 0x72 at 0x0000
,I/dalvikvm( 7434): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
,W/dalvikvm( 7434): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 7434): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 7434): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 7434): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 7434): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 7434): VFY: replacing opcode 0x23 at 0x0005
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6339): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6339): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6339): GetString : secure API is not supported!!
,I/PCWCLIENTTRACE_PushUtil( 6339): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6339): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6339): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6339): [ensureRegistration] - No Samsung account
I/dalvikvm( 7434): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
W/dalvikvm( 7434): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7434): VFY: replacing opcode 0x6e at 0x0009
,W/dalvikvm( 7434): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
W/dalvikvm( 7434): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 7434): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 7434): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
,D/dalvikvm( 7434): VFY: replacing opcode 0x1c at 0x0002
E/dalvikvm( 7434): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 7434): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 7434): VFY: replacing opcode 0x1f at 0x000c
,D/dalvikvm( 7434): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7434): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7434): VFY: replacing opcode 0x62 at 0x0006
,D/dalvikvm( 7434): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7434): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
,D/dalvikvm( 7434): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7434): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
,D/dalvikvm( 7434): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
,W/dalvikvm( 7434): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7434): Link of class 'Lax;' failed
,D/dalvikvm( 7434): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 7434): Unable to resolve superclass of Laz; (841)
,W/dalvikvm( 7434): Link of class 'Laz;' failed
,D/dalvikvm( 7434): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 7434): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
,D/dalvikvm( 7434): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,D/dalvikvm( 7434): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x42592d40
,D/dalvikvm( 7434): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x42592d40
,I/dalvikvm( 7434): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
,W/dalvikvm( 7434): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 7434): VFY: replacing opcode 0x6e at 0x0076
,I/Babel_SMS( 7434): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7434): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7434): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/Babel_SMS( 7434): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7434): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7434): MmsConfig.loadFromResources
,E/Babel_SMS( 7434): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7434): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,W/dalvikvm( 7434): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7434): Link of class 'Lfzc;' failed
E/dalvikvm( 7434): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 7434): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
,D/dalvikvm( 7434): VFY: replacing opcode 0x22 at 0x0033
,W/dalvikvm( 7434): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7434): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7434): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
,W/dalvikvm( 7434): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
I/dalvikvm( 7434): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 7434): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
,D/dalvikvm( 7434): VFY: replacing opcode 0x74 at 0x006d
I/dalvikvm( 7434): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 7434): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
,D/dalvikvm( 7434): VFY: replacing opcode 0x6e at 0x0033
I/dalvikvm( 7434): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 7434): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
,D/dalvikvm( 7434): VFY: replacing opcode 0x6e at 0x0030
W/dalvikvm( 7434): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7434): Link of class 'Lfzc;' failed
,D/dalvikvm( 7434): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
,E/SensorService( 2422): Permission Denial : SEC Private Sensor 
,E/SensorService( 2422): Permission Denial : SEC Private Sensor 
,D/ExynosCameraInterface( 1926): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1926): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,D/ExynosCameraInterface( 1926): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1926): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,W/Settings( 7434): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7434): startup - clean
,D/dalvikvm( 7434): GC_CONCURRENT freed 1796K, 24% free 10846K/14144K, paused 3ms+3ms, total 37ms
D/dalvikvm( 7434): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 7434): WAIT_FOR_CONCURRENT_GC blocked 10ms
,I/Babel   ( 7434): deleted: false for 0
I/dalvikvm( 7434): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
W/dalvikvm( 7434): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7434): VFY: replacing opcode 0x6e at 0x000d
,W/dalvikvm( 7434): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
I/dalvikvm( 7434): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 7434): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
,D/dalvikvm( 7434): VFY: replacing opcode 0x6e at 0x004e
,W/dalvikvm( 7434): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7434): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7434): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 7434): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
,D/dalvikvm( 7434): VFY: replacing opcode 0x22 at 0x0071
,W/dalvikvm( 7434): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7434): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7434): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7434): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7434): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 7434): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
,D/dalvikvm( 7434): VFY: replacing opcode 0x1f at 0x0021
,W/dalvikvm( 7434): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 7434): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
,I/dalvikvm( 7434): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/dalvikvm( 7434): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
,D/dalvikvm( 7434): VFY: replacing opcode 0x6e at 0x0074
,D/WaitQueueForNetworkActivate( 6644): notifyNetworkActivated
,I/vclib   ( 7434): onServiceConnected
,W/Babel   ( 7434): Attempted to change video mute state without an active call.
,W/ContextImpl( 6644): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager( 2422): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/dalvikvm( 7434): GC_CONCURRENT freed 805K, 17% free 12085K/14396K, paused 2ms+3ms, total 49ms
,D/dalvikvm( 7434): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 7434): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/System.out( 7434): Thread-647(HTTPLog):isShipBuild true
,I/System.out( 7434): Thread-647(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 7434): GC_FOR_ALLOC freed 893K, 18% free 12635K/15376K, paused 30ms, total 31ms
,D/hcjo    ( 6644): AutoUpdateManager:IDLE:execute
,I/dalvikvm( 6644): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
,W/dalvikvm( 6644): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 6644): VFY: replacing opcode 0x6e at 0x0024
,D/InitializeManagerStateMachine( 6644): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6644): exit::IDLE
,D/InitializeManagerStateMachine( 6644): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6644): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6644): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6644): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6644): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6644): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 6644): entry::SUCCESS
,D/hcjo    ( 6644): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/dalvikvm( 7434): GC_FOR_ALLOC freed 1850K, 24% free 12984K/17032K, paused 32ms, total 33ms
,D/hcjo    ( 6644): AutoUpdateTriggerManager:IDLE:setInterval:345600000
D/hcjo    ( 6644): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6644): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6644): exit::SUCCESS
,D/InitializeManagerStateMachine( 6644): entry::IDLE
,I/Babel   ( 7434): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager( 2422): Killing 6326:com.android.musicfx/u0a24 (adj 15): empty #43
,I/iu.SyncManager( 3284): SYNC; picasa accounts
,D/NetworkLogImpl( 3284): Loaded NetworkSpeedPredictor
,I/iu.Environment( 3284): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 3284): num queued entries: 0
,I/iu.UploadsManager( 3284): num updated entries: 0
,I/iu.SyncManager( 3284): NEXT; no task
,E/SPPClientService( 5440): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5440): [SystemStateMoniter] Current Time : 295841
,E/SPPClientService( 5440): [SystemStateMoniter] No Connect : false
,I/SELinux ( 7471): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7471):  
,D/dalvikvm( 1923): GC_EXPLICIT freed 43K, 15% free 9501K/11052K, paused 3ms+3ms, total 29ms
,I/SELinux ( 7471): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7471):  
I/SELinux ( 7471):  
,I/SELinux ( 7471): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7471): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7471): >>>>> Normal User
,E/dalvikvm( 7471): >>>>> com.android.calendar [ userId:0 | appId:10144 ]
,E/SELinux ( 7471): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 15% free 9501K/11052K, paused 2ms+2ms, total 23ms
,D/TimaKeyStoreProvider( 7471): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7471): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7471): Added TimaKesytore provider
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 15% free 9501K/11052K, paused 2ms+2ms, total 23ms
,D/dalvikvm( 7471): GC_CONCURRENT freed 3005K, 33% free 9564K/14072K, paused 1ms+1ms, total 24ms
,D/dalvikvm( 7471): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/GCM     ( 2855): GCM config loaded
,I/ActivityManager( 2422): Killing 6352:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,D/BootCompletedReceiver( 2422): onReceive
,I/KLMS-2.3.201 : ( 7237): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/SurfaceFlinger( 1922): id=21 Removed Uoast (10/11)
,I/SurfaceFlinger( 1922): id=21 Removed Uoast (-2/11)
D/PowerManagerService( 2422): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2422) eventTime = 296237
D/PowerManagerService( 2422): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2422 (0x0)
D/PowerManagerService( 2422): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2422, ws=WorkSource{1000}) (elapsedTime=3450)
,I/KLMS-2.3.201 : ( 7237): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1449683861917
,I/KLMS-2.3.201 : ( 7237): StateImplV2() : dateTimeChanged() : Wed Dec 09 18:57:41 CET 2015
,D/SO_AGENT( 7253): [ServerTimeReceiver.java(Line:44/Method:onReceive)] Receive broadcast meassage:android.intent.action.TIME_SET
,I/SO_AGENT( 7253): [ServerTimeReceiver.java(Line:47/Method:onReceive)] No action is available before server time settings
,I/SA      ( 6505): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/PhenotypeConfigurator( 2738): Scheduling Phenotype for one-off execution 5724 seconds from now (1449683862002)
,D/Mms/MessagingNotification( 5536): [start]    nonBlockingUpdateMessageIndicator()
,D/GetConfigurationSnapshotOperation( 2738): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/Mms/MessagingNotification( 5536): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 5536): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 5536): isDefault true
,D/TP/MmsSmsProvider( 2755): match 8:Elapsed time : 11.521 ms
,I/SELinux ( 7497): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7497):  
,D/TP/MmsSmsProvider( 2755): match 200:Elapsed time : 7.220 ms
I/SELinux ( 7497): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7497):  
I/SELinux ( 7497):  
I/SELinux ( 7497): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/PhenotypeFlagCommitter( 2738): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,E/SELinux ( 7497): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7497): >>>>> Normal User
,E/dalvikvm( 7497): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10064 ]
,E/SELinux ( 7497): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7497): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7497): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7497): Added TimaKesytore provider
,I/GoogleURLConnFactory( 2738): Using platform SSLCertificateSocketFactory
,D/BadgeProvider( 7409): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/BadgeProvider( 7409): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 7409): sendNotify, [notify] : null
D/BadgeProvider( 7409): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 7409): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7409): update, [UpdateCount] : 1
D/Launcher.Model( 2786): reloadBadges entered.
,D/Mms/MessagingNotification( 5536): setBadgeCount(), count=0
,D/MessagingNotification( 5536): remove alarm
,D/Mms/MessagingNotification( 5536): updateAllHistoryAsRead()
,D/Mms/MessagingNotification( 5536): [end]    nonBlockingUpdateMessageIndicator()
D/dalvikvm( 7497): GC_CONCURRENT freed 2990K, 32% free 9569K/14068K, paused 3ms+1ms, total 32ms
,D/dalvikvm( 7497): WAIT_FOR_CONCURRENT_GC blocked 27ms
D/ConnectivityService( 2422): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/STATUSBAR-NetworkController( 2583): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2583): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2583): updateDataNetType()
D/STATUSBAR-NetworkController( 2583): NoService, mRoamingIconId = 0
,D/dalvikvm( 2422): GC_EXPLICIT freed 2255K, 57% free 24615K/56260K, paused 7ms+18ms, total 214ms
,I/ Time Manager ( 7497): Time Difference not stored. TIME_DIFFERENCE
,D/com.samsung.app( 7310): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidintentactionTIME_SET
,D/com.samsung.app( 7310): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/SELinux ( 7513): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7513):  
I/ActivityManager( 2422): Killing 6386:com.sec.android.service.health/u0a16 (adj 15): empty #43
,I/SELinux ( 7513): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7513):  
I/SELinux ( 7513):  
,I/SELinux ( 7513): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7513): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7513): >>>>> Normal User
,E/dalvikvm( 7513): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10088 ]
,E/SELinux ( 7513): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7513): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7513): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7513): Added TimaKesytore provider
,D/LocationManagerService( 2422): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 3284): Thread-181(HTTPLog):isShipBuild true
,I/System.out( 3284): Thread-181(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 7513): GC_CONCURRENT freed 2994K, 32% free 9574K/14076K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 7513): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,V/HeadsetService( 5045): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 5045): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SELinux ( 7530): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7530):  
I/ActivityManager( 2422): Killing 6480:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty #43
,D/dalvikvm( 3284): GC_FOR_ALLOC freed 1539K, 22% free 12450K/15852K, paused 47ms, total 49ms
,I/SELinux ( 7530): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7530):  
I/SELinux ( 7530):  
,I/SELinux ( 7530): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7530): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7530): >>>>> Normal User
,E/dalvikvm( 7530): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 7530): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7530): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7530): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7530): Added TimaKesytore provider
,D/dalvikvm( 7530): GC_CONCURRENT freed 3004K, 33% free 9568K/14076K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7530): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/elm:14132( 7530): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14132( 7530): ELMEngine.ELMEngine( context ).
,D/elm:14132( 7530): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 7530): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/elm:14132( 7530): ElmAgentService : onCreate()
,I/knox    ( 4962): MainReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,D/elm:14132( 7530): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,W/ContextImpl( 4962): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 4962): MainReceiver.listeningToTimeDateChanges( context, intent ).
I/knox    ( 4962): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
D/elm:14132( 7530): ELMAgentService.listeningToTimeDateChanges( context, intent ).
D/knox    ( 4962): KNOXAgentService : onCreate()
D/knox    ( 4962): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 4962): KNOXAgentService. startJobThread() start
D/knox    ( 4962): KNOXAgentService. JobThread()
D/elm:14132( 7530): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/knox    ( 4962): KNOXAgentService. JobThread. notifyAll().
D/elm:14132( 7530): ModuleBase.resetCalllogAPIAlarm()
D/knox    ( 4962): KNOXAgentService. startJobThread() wait
,I/SELinux ( 7545): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7545):  
,D/knox    ( 4962): KNOXAgentService : onDestroy().
,D/knox    ( 4962): ModuleBase.cancelAllAlarmManageModule()
,D/elm:14132( 7530): ModuleBase.ModifySetAlarm()
,D/elm:14132( 7530): MDMBridge.getInstance()
,D/elm:14132( 7530): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 7530): ElmAgentService : onDestroy().
I/ActivityManager( 2422): Killing 4770:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
,I/SELinux ( 7545): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7545):  
I/SELinux ( 7545):  
,I/SELinux ( 7545): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7545): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7545): >>>>> Normal User
,E/dalvikvm( 7545): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10145 ]
,E/SELinux ( 7545): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7545): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7545): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7545): Added TimaKesytore provider
,D/dalvikvm( 7545): GC_CONCURRENT freed 3002K, 33% free 9566K/14072K, paused 1ms+1ms, total 18ms
,D/dalvikvm( 7545): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/SELinux ( 7557): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7557):  
I/ActivityManager( 2422): Killing 6524:com.sec.android.service.cm/u0a82 (adj 15): empty #43
,D/LocationManagerService( 2422): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/SELinux ( 7557): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7557):  
I/SELinux ( 7557):  
,I/SELinux ( 7557): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7557): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7557): >>>>> Normal User
,E/dalvikvm( 7557): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10168 ]
,E/SELinux ( 7557): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7557): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7557): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7557): Added TimaKesytore provider
,D/dalvikvm( 7557): GC_CONCURRENT freed 3005K, 33% free 9565K/14076K, paused 2ms+2ms, total 21ms
,D/dalvikvm( 7557): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/ActivityManager( 2422): Killing 6536:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty #43
,D/daemonapp( 5243): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5243): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5243): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/LocationManagerService( 2422): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/daemonapp( 5243): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5243): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 5243): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 5243): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
,D/comsamsunglog( 5243): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5243): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5243): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5243): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5243): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5243): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5243): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5243): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5243): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/comdaemonstockapp( 5243): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 5243): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,D/LocationManagerService( 2422): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 2855): GC_EXPLICIT freed 966K, 25% free 10801K/14248K, paused 3ms+6ms, total 41ms
,I/CheckinService( 3284): Checkin interval check for package: unspecified last checkin: 1449576680750 min interval config: 0 actual interval: 107182694
,D/dalvikvm( 2738): GC_CONCURRENT freed 1598K, 21% free 12107K/15284K, paused 3ms+12ms, total 56ms
,I/SELinux ( 7570): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7570):  
,I/SELinux ( 7570): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7570):  
I/SELinux ( 7570):  
,I/SELinux ( 7570): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7570): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7570): >>>>> Normal User
,E/dalvikvm( 7570): >>>>> com.android.providers.calendar [ userId:0 | appId:10045 ]
,E/SELinux ( 7570): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7570): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7570): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7570): Added TimaKesytore provider
,D/dalvikvm( 7570): GC_CONCURRENT freed 3019K, 33% free 9550K/14076K, paused 2ms+2ms, total 19ms
,D/dalvikvm( 7570): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/Headlines( 7323): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7323): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7323): Breath 5155 latestRequest time : 1449683858920 current time : 1449683864075
,D/Mms/MessagesLockscreen( 5536): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
,W/Binder  ( 2583): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 2583): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
W/Binder  ( 2583): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
W/Binder  ( 2583): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
W/Binder  ( 2583): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
W/Binder  ( 2583): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
W/Binder  ( 2583): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
W/Binder  ( 2583): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
W/Binder  ( 2583): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
W/Binder  ( 2583): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
W/Binder  ( 2583): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
W/Binder  ( 2583): 	at android.view.View.inflate(View.java:18495)
W/Binder  ( 2583): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
W/Binder  ( 2583): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
W/Binder  ( 2583): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
W/Binder  ( 2583): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
W/Binder  ( 2583): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
W/Binder  ( 2583): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 2583): 	at dalvik.system.NativeStart.run(Native Method)
W/Binder  ( 2583): Caused by: java.lang.reflect.InvocationTargetException
W/Binder  ( 2583): 	at java.lang.reflect.Constructor.constructNative(Native Method)
W/Binder  ( 2583): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
W/Binder  ( 2583): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
W/Binder  ( 2583): 	... 16 more
W/Binder  ( 2583): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
W/Binder  ( 2583): 	at android.os.Handler.<init>(Handler.java:200)
W/Binder  ( 2583): 	at android.os.Handler.<init>(Handler.java:114)
W/Binder  ( 2583): 	at android.widget.TextClock.<init>(TextClock.java:130)
W/Binder  ( 2583): 	at android.widget.TextClock.<init>(TextClock.java:191)
W/Binder  ( 2583): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
W/Binder  ( 2583): 	... 19 more
,E/JavaBinder( 2583): *** Uncaught remote exception!  (Exceptions are not yet supported across processes.)
E/JavaBinder( 2583): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
E/JavaBinder( 2583): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
E/JavaBinder( 2583): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
E/JavaBinder( 2583): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
E/JavaBinder( 2583): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
E/JavaBinder( 2583): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
E/JavaBinder( 2583): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
E/JavaBinder( 2583): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
E/JavaBinder( 2583): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
E/JavaBinder( 2583): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
E/JavaBinder( 2583): 	at android.view.View.inflate(View.java:18495)
E/JavaBinder( 2583): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
E/JavaBinder( 2583): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
E/JavaBinder( 2583): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
E/JavaBinder( 2583): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
E/JavaBinder( 2583): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
E/JavaBinder( 2583): 	at android.os.Binder.execTransact(Binder.java:404)
E/JavaBinder( 2583): 	at dalvik.system.NativeStart.run(Native Method)
E/JavaBinder( 2583): Caused by: java.lang.reflect.InvocationTargetException
E/JavaBinder( 2583): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/JavaBinder( 2583): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/JavaBinder( 2583): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
E/JavaBinder( 2583): 	... 16 more
E/JavaBinder( 2583): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
E/JavaBinder( 2583): 	at android.os.Handler.<init>(Handler.java:200)
E/JavaBinder( 2583): 	at android.os.Handler.<init>(Handler.java:114)
E/JavaBinder( 2583): 	at android.widget.TextClock.<init>(TextClock.java:130)
E/JavaBinder( 2583): 	at android.widget.TextClock.<init>(TextClock.java:191)
E/JavaBinder( 2583): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
E/JavaBinder( 2583): 	... 19 more
,I/GAV2    ( 7335): Thread[GAThread,5,main]: No campaign data found.
,E/SPPClientService( 5440): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,V/AlarmManager( 2422):  next == MAX_VALUE
,E/SPPClientService( 5440): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5440): [a] [ConnectionManager] Connection is already disconnected.
V/AlarmManager( 2422): waitForAlarm result :4
V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5440): [g] getNetMCC return empty string
,E/SPPClientService( 5440): [g] getNetMNC return empty string
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 350, Delta = 10
,D/CaptivePortalTracker( 2422): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker( 2422): Checking http://216.58.209.46/generate_204
D/ConnectivityService( 2422): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/ActivityThread( 2422): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/System.out( 2422): Thread-161(HTTPLog):isShipBuild true
,I/System.out( 2422): Thread-161(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/CaptivePortalTracker( 2422): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker( 2422): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2422): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2422): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2422): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/ActivityManager( 2422): Waited long enough for: ServiceRecord{431d0550 u0 pl.k2.droidoaudioteka/.services.DownloadService}
,I/ActivityManager( 2422): Waited long enough for: ServiceRecord{43272378 u0 pl.k2.droidoaudioteka/.services.PlayerService}
,D/AmoledAdjustTimer( 2422): prevTemp = 294, currTemp = 296, prevStep = 4, currStep = 4
,I/jxcore-log( 6981): Test app app.js loaded
I/jxcore-log( 6981): 
,I/chromium( 6981): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/SPPClientService( 5440): [b] __ProvisionReply__
,E/SPPClientService( 5440): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5440): [d] null
,V/AlarmManager( 2422):  next == MAX_VALUE
,E/SPPClientService( 5440): [g] getPLMN return empty string
,E/SPPClientService( 5440): [b] SharedConstants.WHAT_PROV_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5440): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5440): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5440): [g] getNetMCC return empty string
,D/dalvikvm( 5440): GC_CONCURRENT freed 2099K, 26% free 10415K/14064K, paused 4ms+7ms, total 58ms
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/PreloadUpdateManagerStateMachine( 6644): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6644): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6644): entry::CHECK_TIMEOUT_FOR_UPDATE
,E/SPPClientService( 5440): [b] __InitReply__
,D/hcjo    ( 6644): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6644): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6644): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6644): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6644): entry::IDLE
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4372, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5045): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5045): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 2422): Waited long enough for: ServiceRecord{4326a398 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 340, Delta = -10
,D/AmoledAdjustTimer( 2422): prevTemp = 296, currTemp = 297, prevStep = 4, currStep = 4
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 2422): initializing...
,I/TLC_TIMA_PKM_initialize( 2422): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2422): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2422): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2422): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 2422): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2422): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2422): aligned max_sendmsg_size = 262208
,I/TZ: mc_tlc_communication( 2422): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2422): device_id = 0x0
,I/TZ: mc_tlc_communication( 2422): tlc_open() was called
,I/TZ: mc_tlc_communication( 2422): Opening MobiCore device
,I/TZ: mc_tlc_communication( 2422): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 2422): Opening the session
,I/TZ: mc_tlc_communication( 2422): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2422): Trustlet response is completed
,I/ActivityManager( 2422): Waited long enough for: ServiceRecord{45189bb8 u0 com.sec.spp.push/.PushClientService}
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
V/HeadsetService( 5045): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5045): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2422): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 330, Delta = -10
,D/AmoledAdjustTimer( 2422): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :4
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,V/AlarmManager( 2422): waitForAlarm result :8
,D/Headlines( 7323): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7323): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7323): Breath 30031 latestRequest time : 1449683858920 current time : 1449683888951
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 6981): Toggling radios to false
I/jxcore-log( 6981): 
,D/BluetoothAdapterService(1113232880)( 5045): unRegister RemoteMessageListener
,I/WifiManager( 6981): packageName : com.test.thalitest
,D/HeadsetService( 5045): registerMessageListener
,D/BluetoothAdapterState( 5045): CURRENT_STATE=ON, MSG = USER_TURN_OFF
D/HeadsetStateMachine( 5045): Disconnected process message: 80
,I/BluetoothAdapterState( 5045): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 5045): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5045): updateAdapterState state is 13
,D/HeadsetStateMachine( 5045): processUnRegisterMessageListener : 2
,I/BluetoothPbapService( 5045): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,E/bt-btif ( 5045): bta_jv_rfcomm_stop_server
,I/WifiManager( 6981): setWifiEnabled : false
,D/BluetoothAdapterService( 5045): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 5045): Autoconnection is available 
,D/BluetoothAdapterService( 5045): updateAdapterState prevState = 12newState = 13
,D/BluetoothAdapterService( 5045): terminating service from this receiver
,W/ContextImpl( 5045): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.stopService:511 com.android.bluetooth.btservice.AdapterService.updateAdapterState:657 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
,I/WifiService( 2422): setWifiEnabled: false pid=6981, uid=10524
,I/wpa_supplicant( 7031): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 7031): wlan0: Setting scan request: 0 sec 0 usec
,W/Settings( 2422): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/jxcore-log( 6981): Radios toggled
I/jxcore-log( 6981): 
,I/wpa_supplicant( 7031): Scan requested (ret=0) - scan timeout 30 seconds
,W/InputMethodManagerService( 2422): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 2422): [BT Setting State] State =13
,D/GKI_LINUX( 5045): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,I/BluetoothAdapterState( 5045): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/PhoneApp( 2755): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 13
,I/SamsungIME( 3005): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
I/WifiStateMachine( 2422): ignore requestNetworkTransitionWakelock airplane:true
D/BluetoothPbap( 5506): Proxy object disconnected
,D/PbapServerProfile( 5506): Bluetooth service disconnected
D/STATUSBAR-IconMerger( 2583): checkOverflow(336), More:false, Req:false Child:3
,I/QuickConnect[1.1][2] ( 5019): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_OFF
D/WifiP2pService( 2422): InactiveState{ what=143375 }
D/WifiP2pService( 2422): P2pEnabledState{ what=143375 }
,V/BluetoothEventManager( 5506): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterState( 5045): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 5045): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
E/bt-btif ( 5045): bta_jv_rfcomm_stop_server
E/bt-btif ( 5045): cmd socket is not created
,E/bt-btif ( 5045): bta_jv_rfcomm_stop_server
E/BtOppRfcommListener( 5045): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 5045): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/ContextImpl( 5506): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/BtOppRfcommListener( 5045): stopping Accept Thread
I/BtOppRfcommListener( 5045): BluetoothSocket listen thread finished
D/CommandListener( 1916): Clearing all IP addresses on wlan0
,D/DockEventReceiver( 5506): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 5506): onReceive
D/IOP_DB_BT( 5045): db_close: nbr users 0
,D/IOP_DB_BT( 5045): db_close: free database
D/WifiP2pService( 2422): InactiveState{ what=131204 }
,I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
D/WifiP2pService( 2422): P2pEnabledState{ what=131204 }
D/ConnectivityService( 2422): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2422): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2422): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2422): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2422): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2422): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
D/WifiP2pService( 2422): sending p2p connection changed broadcast: FAILED
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2422): Attempting to switch to mobile
,E/WifiStateMachine( 2422): Error! unhandled message{ when=-1ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 2422): Attempting to switch to BLUETOOTH_TETHER
E/WifiStateMachine( 2422): Error! unhandled message{ when=-3ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,W/WifiP2pStateTracker( 2422): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController( 2422): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter( 2422): onP2pDisconnected
D/IpRemoteDisplayController( 2422): disconnectWfdBridgeServer
,D/QuickConnect[1.1][2] ( 5019): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/IpRemoteDisplayController( 2422): WfdBridgeServer is already null
D/QuickConnect[1.1][2] ( 5019): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1
,E/WifiStateMachine( 2422): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiP2pService( 2422): sending p2p connection changed broadcast: DISCONNECTED
D/WifiDisplayController( 2422): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 2422): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 2422): disconnect
D/WifiDisplayController( 2422): updateConnection
D/WifiDisplayController( 2422): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/QuickConnect[1.1][2] ( 5019): SconnectManager.INetworkStateListener, onDisabled - mNetworkState : 0
,D/WifiDisplayAdapter( 2422): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/QuickConnect[1.1][2] ( 5019): P2pHelper.cancelConnectPeer -  mTargetList clear all 
D/QuickConnect[1.1][2] ( 5019): P2pHelper.removeP2pConfirm - skip: false
D/AuthorizationBluetoothService( 2855): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/QuickConnect[1.1][2] ( 5019): CentralActionManager.removeHoldingIntentAll - all request done.
,V/RouteController( 1916): RTNETLINK answers: No such process
W/WifiP2pStateTracker( 2422): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController( 2422): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter( 2422): onP2pDisconnected
D/IpRemoteDisplayController( 2422): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 2422): WfdBridgeServer is already null
D/WifiP2pService( 2422): P2pDisablingState
,D/WifiP2pService( 2422): P2pDisablingState{ what=139287 }
D/QuickConnect[1.1][2] ( 5019): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
,D/QuickConnect[1.1][2] ( 5019): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,D/QuickConnect[1.1][2] ( 5019): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/WifiP2pService( 2422): DefaultState{ what=139287 }
D/WifiDisplayAdapter( 2422): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiP2pService( 2422): P2pDisablingState{ what=147458 }
,D/QuickConnect[1.1][2] ( 5019): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
D/WifiP2pService( 2422): p2p socket connection lost
D/WifiP2pService( 2422): P2pDisabledState
D/WifiP2pService( 2422): P2pDisabledState{ what=139376 }
D/WifiP2pService( 2422): DefaultState{ what=139376 }
E/WifiP2pService( 2422): Unhandled message { what=139376 }
,D/WifiP2pService( 2422): P2pDisabledState{ what=139287 }
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
D/QuickConnect[1.1][2] ( 5019): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
D/WifiP2pService( 2422): DefaultState{ what=139287 }
,W/NetworkManagementService( 2422): route cmd failed: 
W/NetworkManagementService( 2422): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '35 route del src v6 2' failed with '400 35 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2422): '
W/NetworkManagementService( 2422): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2422): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2422): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2422): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2422): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2422): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2422): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2422): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2422): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2422): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2422): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2422): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2422): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1
,D/WifiNative( 2422): callSECApiBoolean - ID [13]
,I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
I/wpa_supplicant( 7031): USE_NETWORK : USE_NETWORK OFF
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/NearbySettings( 5506): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5506): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5506): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
I/NearbySettings( 5506): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 5506): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 5506): MountReceiver.onReceive - Set preference state off
D/BluetoothAdapterState( 5045): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/BtConfig.SecureMode( 5045): isSecureModeOn:false
W/BluetoothAdapterService( 5045): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5045): Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5045): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
V/NearbySettings( 5506): MountReceiver.mPrefHandler - 7002
,W/BluetoothAdapterService( 5045): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
E/WifiStateMachine( 2422): Error! unhandled message{ when=-30ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2422): Error! unhandled message{ when=-31ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetUtils( 2422): android_net_utils_resetConnections in env=0x7829bd58 clazz=0x60b00001 iface=wlan0 mask=0x3
D/ConnectivityService( 2422): resetConnections(wlan0, 3)
,W/BluetoothAdapterService( 5045): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,E/WifiStateMachine( 2422): Error! unhandled message{ when=-6ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,W/BluetoothAdapterService( 5045): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/HeadsetService( 5045): Received stop request...Stopping profile...
,E/WifiStateMachine( 2422): Error! unhandled message{ when=-10ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
,W/BluetoothAdapterService( 5045): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5045): Not skipping com.android.bluetooth.hid.HidService
,V/NativeCrypto( 2855): Read error: ssl=0x7bafac80: I/O error during system call, Connection timed out
,D/NearbySettings( 5506): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 5506): DMSUtil.isNetworkConnected - flag-null, state-null
W/BluetoothAdapterService( 5045): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 5045): Not skipping com.android.bluetooth.hdp.HealthService
,I/NearbySettings( 5506): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/QuickConnect[1.1][2] ( 5019): HeadsetProfile.onServiceDisconnected - Bluetooth service disconnected
,E/SPPClientService( 5440): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5440): [e] exceptionCaught(). NET_TIMEOUT
,D/A2dpService( 5045): Received stop request...Stopping profile...
D/Avrcp   ( 5045): Unregistering previous receiver
W/BluetoothAdapterService( 5045): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
D/A2dpStateMachine( 5045): Exit Disconnected: -1
,D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,D/MediaFocusControl( 2422): <<< unregisterRemoteControlDisplay
W/BluetoothAdapterService( 5045): Not skipping com.android.bluetooth.pan.PanService
I/NearbySettings( 5506): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 5506): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5506): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5506): MountReceiver.mPrefHandler - 7002
,V/NativeCrypto( 2855): SSL shutdown failed: ssl=0x7bafac80: I/O error during system call, Broken pipe
,W/BluetoothAdapterService( 5045): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5045): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/HeadsetProfile( 5506): Bluetooth service disconnected
D/BluetoothA2dp( 5506): Proxy object disconnected
D/A2dpProfile( 5506): Bluetooth service disconnected
D/BluetoothA2dp( 5019): Proxy object disconnected
,D/QuickConnect[1.1][2] ( 5019): A2dpProfile.onServiceConnected - Bluetooth service disconnected
,D/BluetoothA2dp( 2422): Proxy object disconnected
,D/GKI_LINUX( 5045): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
W/BluetoothAdapterService( 5045): check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/HidService( 5045): Received stop request...Stopping profile...
W/BluetoothAdapterService( 5045): Not skipping com.broadcom.bt.service.sap.SapService
,D/HidService( 5045): Stopping Bluetooth HidService
D/BluetoothA2dp( 4131): Proxy object disconnected
D/BluetoothInputDevice( 5019): Proxy object disconnected
D/QuickConnect[1.1][2] ( 5019): HidProfile.onServiceDisconnected - Bluetooth service disconnected
D/BluetoothInputDevice( 5506): Proxy object disconnected
,D/HidProfile( 5506): Bluetooth service disconnected
,E/SPPClientService( 5440): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,D/BluetoothAdapterState( 5045): Stopping profile services that were post enabled
D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5045): Profile still running: com.broadcom.bt.service.sap.SapService
,D/FileShare-Server( 5921): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
W/BluetoothHeadsetServiceJni( 5045): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 5045): Cleaning up Bluetooth Handsfree callback object
,D/HealthService( 5045): Received stop request...Stopping profile...
D/FileShare-Server( 5921): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() DISCONNECTED
E/SPPClientService( 5440): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5440): [b] ResponseMap empty
,D/PanService( 5045): Received stop request...Stopping profile...
,D/BluetoothPan( 2422): BluetoothPAN Proxy object disconnected
D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5045): Profile still running: com.broadcom.bt.service.sap.SapService
I/GKI_LINUX( 5045): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 5045): GKI_exit_task: GKI_exit_task 2 done
,I/GKI_LINUX( 5045): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/BluetoothMapService( 5045): Received stop request...Stopping profile...
D/BluetoothPan( 5506): BluetoothPAN Proxy object disconnected
,D/PanProfile( 5506): Bluetooth service disconnected
D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5045): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothHidServiceJni( 5045): Cleaning up Bluetooth HID Interface...
,W/BluetoothHidServiceJni( 5045): Cleaning up Bluetooth GID callback object
D/SapService( 5045): Received stop request...Stopping profile...
,D/SapService( 5045): Stopping Bluetooth SapService
D/BluetoothMap( 5506): Proxy object disconnected
,D/MapProfile( 5506): Bluetooth service disconnected
D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5045): Profile still running: com.broadcom.bt.service.sap.SapService
,W/BluetoothHealthServiceJni( 5045): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 5045): Cleaning up Bluetooth Health object
,D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5045): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothPanServiceJni( 5045): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 5045): Cleaning up Bluetooth PAN callback object
D/BtSettings.ProfileConfig( 5045): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/Bluetoothsap( 5506): BluetoothSAP Proxy object disconnected
D/SapProfile( 5506): Bluetooth service disconnected
,D/BluetoothAdapterService( 5045): Profile still running: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5045): Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
W/BluetoothSAPServiceJni( 5045): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 5045): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterState( 5045): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 5045): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 5045): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5045): updateAdapterState state is 10
,D/BluetoothAdapterService( 5045): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterService( 5045): Autoconnection is available 
D/Bluetoothsap( 5506): BluetoothSAP Proxy object disconnected
D/SapProfile( 5506): Bluetooth service disconnected
D/BluetoothAdapterService( 5045): updateAdapterState prevState = 13newState = 10
,I/BluetoothAdapterState( 5045): Entering OffState
D/NearbySettings( 5506): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5506): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5506): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/BluetoothInputDevice( 5019): onBluetoothStateChange: up=false
I/NearbySettings( 5506): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 5506): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 5506): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5506): MountReceiver.mPrefHandler - 7002
,D/BluetoothA2dp( 5019): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 2422): onBluetoothStateChange: up=false
D/Tethering( 2422): interfaceLinkStateChanged p2p0, true
,I/wpa_supplicant( 7031): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering( 2422): interfaceStatusChanged p2p0, true
,D/Tethering( 2422): interfaceLinkStateChanged p2p0, false
,D/Tethering( 2422): interfaceStatusChanged p2p0, false
,D/BluetoothA2dp( 5506): onBluetoothStateChange: up=false
,I/knox    ( 4962): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 4962): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/wpa_supplicant( 7031): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/knox    ( 4962): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,I/wpa_supplicant( 7031): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
D/knox    ( 4962): KNOXAgentService : onCreate()
,D/knox    ( 4962): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 4962): KNOXAgentService. startJobThread() start
D/knox    ( 4962): KNOXAgentService. JobThread()
D/knox    ( 4962): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 4962): KNOXAgentService. startJobThread() wait
,D/BluetoothA2dp( 4131): onBluetoothStateChange: up=false
D/knox    ( 4962): KNOXAgentService : onDestroy().
,D/knox    ( 4962): ModuleBase.cancelAllAlarmManageModule()
D/Bluetoothsap( 5506): onBluetoothStateChange: up=false
,D/Bluetoothsap( 5506): Unbinding service...
,D/BluetoothInputDevice( 5506): onBluetoothStateChange: up=false
,D/BluetoothMap( 5506): onBluetoothStateChange: up=false
,D/BluetoothPbap( 5506): onBluetoothStateChange: up=false
D/Bluetoothsap( 5506): onBluetoothStateChange: up=false
,D/Bluetoothsap( 5506): Unbinding service...
W/InputMethodManagerService( 2422): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2422): [BT Setting State] State =10
,I/InputMethodManagerService( 2422): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/PhoneApp( 2755): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 10
I/SamsungIME( 3005): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
I/QuickConnect[1.1][2] ( 5019): BluetoothHelper.ACTION_STATE_CHANGED - STATE_OFF
V/BluetoothEventManager( 5506): Received android.bluetooth.adapter.action.STATE_CHANGED
,W/ContextImpl( 5506): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 5506): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 5506): onReceive
,D/AuthorizationBluetoothService( 2855): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,D/BluetoothTethering( 2422): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering( 2422): attempted to stop reverse tether with nothing tethered
D/ConnectivityService( 2422): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
V/NetworkStats( 2422): updateIfacesLocked()
V/NetworkStats( 2422): performPollLocked(flags=0x1)
V/NetworkStats( 2422): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
V/NetworkStats( 2422): performPollLocked() took 25ms
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/Tethering( 2422): interfaceLinkStateChanged wlan0, false
,D/Tethering( 2422): interfaceStatusChanged wlan0, false
D/Tethering( 2422): InitialState.processMessage what=4
,I/wpa_supplicant( 7031): wlan0: CTRL-EVENT-TERMINATING 
,E/Tethering( 2422): No numeric data
,I/ConnectivityService( 2422): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering( 2422): sendTetherStateChangedBroadcast 0, 0, 0
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
V/NetworkStats( 2422): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,V/NetworkStats( 2422): performPollLocked() took 20ms
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/WifiStateMachine( 2422): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,W/Settings( 7434): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,W/Settings( 2738): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/knox    ( 4962): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 4962): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 4962): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 4962): KNOXAgentService : onCreate()
,D/knox    ( 4962): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 4962): KNOXAgentService. startJobThread() start
,D/knox    ( 4962): KNOXAgentService. JobThread()
D/knox    ( 4962): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 4962): KNOXAgentService. startJobThread() wait
,D/knox    ( 4962): KNOXAgentService : onDestroy().
,D/knox    ( 4962): ModuleBase.cancelAllAlarmManageModule()
,D/WifiStateMachine( 2422): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,D/Tethering( 2422): Tethering got CONNECTIVITY_ACTION
I/ApplicationPolicy( 2422): updateDataUsageMap
,D/Tethering( 2422): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2422): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2422): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/STATUSBAR-NetworkController( 2583): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2583): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2583): updateDataNetType()
,D/STATUSBAR-NetworkController( 2583): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4641): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
I/PCWCLIENTTRACE_PushUtil( 6339): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6339): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6339): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6339): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6339): noConnectivity : true
,D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection...
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/KLMS-2.3.201 : ( 7237): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7237): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449683893037
,I/KLMS-2.3.201 : ( 7237): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/SO_AGENT( 7253): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7253): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 6505): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 6505): [BDLM] already registered in spp
I/SA      ( 6505): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 6505): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6505): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6505): [OR] == isSIMCardReady false ==
,I/SA      ( 6505): [SCU] == networkStateCheck == false
,I/SA      ( 6505): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7297): Other Intent
,D/com.samsung.app( 7310): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7310): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 7323): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 7323): getCountryCode(): countryCode = PL
D/Headlines( 7323): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 7323): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 7323): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 7323): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 7323): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 7323): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 7323): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 5673): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 5673): num queued entries: 0
,I/iu.UploadsManager( 5673): num updated entries: 0
,D/QuickConnect[1.1][2] ( 5019): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/iu.SyncManager( 5673): NEXT; no task
I/QuickConnect[1.1][2] ( 5019): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5019): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425a1200
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,I/Babel   ( 7434): connection state changed from CONNECTED to DISCONNECTED
,I/iu.Environment( 3284): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 3284): num queued entries: 0
,I/iu.UploadsManager( 3284): num updated entries: 0
,I/iu.SyncManager( 3284): NEXT; no task
,E/SPPClientService( 5440): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5440): [SystemStateMoniter] Current Time : 327643
,E/SPPClientService( 5440): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5440): [[SystemStateMonitorService]] No Active Internet
,E/SPPClientService( 5440): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5440): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5440): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,I/ActivityManager( 2422): Killing 6562:com.samsung.helphub/1000 (adj 15): empty #43
,D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection...
,D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = -10
,D/AmoledAdjustTimer( 2422): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2422): [PWL] Off : 275s ago
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2422): !@Sync 11
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :4
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2422): waitForAlarm result :4
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 8103): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8103):  
,I/SELinux ( 8103): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8103):  
I/SELinux ( 8103):  
,I/SELinux ( 8103): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8103): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 8103): >>>>> Normal User
,E/dalvikvm( 8103): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 8103): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 8103): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8103): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8103): Added TimaKesytore provider
,D/dalvikvm( 8103): GC_CONCURRENT freed 3012K, 33% free 9557K/14072K, paused 3ms+2ms, total 34ms
,D/dalvikvm( 8103): WAIT_FOR_CONCURRENT_GC blocked 30ms
,I/ActivityManager( 2422): Killing 6575:com.sec.kidsplat.installer/u0a160 (adj 15): empty #43
,V/AlarmManager( 2422): waitForAlarm result :8
,D/Headlines( 7323): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 7323): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7323): Breath 25780 latestRequest time : 1449683893152 current time : 1449683918932
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 12
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,D/Headlines( 7323): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7323): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7323): Breath 55795 latestRequest time : 1449683893152 current time : 1449683948948
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2422): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2422): !@Sync 13
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,D/Headlines( 7323): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7323): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 7323): Breath 85800 latestRequest time : 1449683893152 current time : 1449683978955
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/dalvikvm( 2422): GC_CONCURRENT freed 3444K, 56% free 24891K/56260K, paused 12ms+20ms, total 222ms
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2422): !@Sync 14
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,D/Headlines( 7323): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7323): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7323): Breath 115815 latestRequest time : 1449683893152 current time : 1449684008967
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2422): !@Sync 15,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,D/Headlines( 7323): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7323): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7323): Breath 145794 latestRequest time : 1449683893152 current time : 1449684038946
,D/Headlines( 7323): stop 
,D/Headlines( 7323): Breath.onDestroy : 
I/ActivityManager( 2422): Killing 6587:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty #43
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 16
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2422): [PWL] Off : 455s ago
,E/Watchdog( 2422): !@Sync 17
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2422): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 18
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2422): !@Sync 19
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 525s ago
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 10
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2422): !@Sync 21
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2422): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2422): <AppSync3 Whitelist>
,V/AlarmManager( 2422): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 22
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 23
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 24
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 680s ago
,V/AlarmManager( 2422): waitForAlarm result :4
,D/Finsky  ( 3853): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3853): Thread-201 calls detatch()
,W/Finsky  ( 3853): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/System.out( 3853): Thread-202 calls detatch()
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3853): Thread-201 calls detatch()
,W/Finsky  ( 3853): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/dalvikvm( 3853): GC_CONCURRENT freed 1623K, 22% free 11182K/14312K, paused 7ms+5ms, total 56ms
,D/dalvikvm( 3853): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3853): Thread-202 calls detatch()
,W/Finsky  ( 3853): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 3853): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 3853): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 2422): waitForAlarm result :4
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Finsky  ( 3853): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/DeviceConnectionService( 2738): client connected with version: 8296000
,D/Finsky  ( 3853): [230] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :4
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm( 3853): GC_CONCURRENT freed 1926K, 24% free 11231K/14664K, paused 5ms+7ms, total 83ms
,D/Finsky  ( 3853): [214] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3853): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/dalvikvm( 2422): GC_CONCURRENT freed 3821K, 56% free 24826K/56260K, paused 9ms+16ms, total 224ms
,E/Watchdog( 2422): !@Sync 25
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/dalvikvm( 4050): GC_CONCURRENT freed 2875K, 32% free 9725K/14112K, paused 6ms+3ms, total 70ms
,E/Watchdog( 2422): !@Sync 26
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 27
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 765s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 28
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/ClearcutLoggerApiImpl( 2855): disconnect managed GoogleApiClient
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 29
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,I/GAV2    ( 7033): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 7033): Thread[disconnect check,5,main]: Disconnected from service
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 855s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 31
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 32
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 33
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,I/SensorManagerA( 2422): getReportingMode :: sensor.mType = 5
D/Sensors ( 2422): LightSensor setDelay = 200000000
D/Sensors ( 2422): LightSensor setSensorDelay = 200000000
D/Sensors ( 2422): Light sensor flush: not enabled 0
D/Sensors ( 2422): LightSensor enable = 1
,D/Sensors ( 2422): LightSensor enableSensor = 1
,D/LightsService( 2422): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/SensorManager( 2422): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,E/SPPClientService( 5440): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,V/AlarmManager( 2422):  next == MAX_VALUE
,E/SPPClientService( 5440): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,D/Sensors ( 2422): LightSensor enable = 0
,D/Sensors ( 2422): LightSensor enableSensor = 0
,D/SensorManager( 2422): unregisterListener ::   
D/LightsService( 2422): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2422): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,I/ActivityManager( 2422): Waited long enough for: ServiceRecord{4518a590 u0 com.sec.spp.push/.PushClientService}
,E/Watchdog( 2422): !@Sync 34
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 35
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 36
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2422): !@Sync 37
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/dalvikvm( 2786): GC_CONCURRENT freed 7042K, 39% free 18942K/30992K, paused 10ms+9ms, total 130ms
,E/Watchdog( 2422): !@Sync 38
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 39
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/dalvikvm( 2422): GC_CONCURRENT freed 3773K, 56% free 24808K/56260K, paused 23ms+16ms, total 233ms
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 41
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2422): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2422): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2422): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 42
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 43
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1265s ago
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 44
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 45
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 46
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 47
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 48
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 49
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/dalvikvm( 4050): GC_CONCURRENT freed 2049K, 32% free 9723K/14108K, paused 3ms+10ms, total 53ms
,E/Watchdog( 2422): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 51
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 52
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 53
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/dalvikvm( 2422): GC_CONCURRENT freed 3849K, 57% free 24720K/56260K, paused 8ms+15ms, total 202ms
,E/Watchdog( 2422): !@Sync 54
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 55
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1625s ago
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 56
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 57
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,I/SensorManagerA( 2422): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2422): LightSensor setDelay = 200000000
,D/Sensors ( 2422): LightSensor setSensorDelay = 200000000
,D/LightsService( 2422): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2422): Light sensor flush: not enabled 0
D/Sensors ( 2422): LightSensor enable = 1
D/Sensors ( 2422): LightSensor enableSensor = 1
D/SensorManager( 2422): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,E/SPPClientService( 5440): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,D/Sensors ( 2422): LightSensor enable = 0
,D/Sensors ( 2422): LightSensor enableSensor = 0
,D/SensorManager( 2422): unregisterListener ::   
D/LightsService( 2422): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2422): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 58
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 59
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,I/ProcessStatsService( 2422): Prepared write state in 104ms
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 12541
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 12542
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 12543
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 12544
W/ProcessCpuTracker( 2422): Skipping unknown process pid 12546
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 12547
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 12548
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 12549
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 12551
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 12552
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 12553
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 12554
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 12556
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 12557
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 12558
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 12559
,I/ProcessStatsService( 2422): Pruning old procstats: /data/system/procstats/state-2015-12-09-06-38-00.bin
,E/Watchdog( 2422): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 61
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2422): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2422): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,V/AlarmManager( 2422): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 62
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 63
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 64
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 65
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,I/ActivityManager( 2422): Killing 5951:com.sec.knox.bridge/1000 (adj 15): empty for 1821s
,I/ActivityManager( 2422): Killing 5907:com.google.android.googlequicksearchbox:search/u0a59 (adj 15): empty for 1821s
,I/ActivityManager( 2422): Killing 5855:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1831s
,I/ActivityManager( 2422): Killing 6613:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1831s
,I/ActivityManager( 2422): Killing 6599:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1832s
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 66
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 67
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:3
,D/dalvikvm( 2422): GC_CONCURRENT freed 3693K, 56% free 24846K/56260K, paused 40ms+17ms, total 277ms
,D/dalvikvm( 2422): WAIT_FOR_CONCURRENT_GC blocked 157ms
,E/Watchdog( 2422): !@Sync 68
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 69
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 2030s ago
,TIME-OUT KILL (timeout was 1800000ms),D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
D/AndroidRuntime(13430): 
D/AndroidRuntime(13430): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(13430): CheckJNI is OFF
D/AndroidRuntime(13430): setted country_code = Poland
D/AndroidRuntime(13430): setted countryiso_code = PL
D/AndroidRuntime(13430): setted sales_code = PLS
D/AndroidRuntime(13430): readGMSProperty: start
D/AndroidRuntime(13430): readGMSProperty: already setted!!
D/AndroidRuntime(13430): readGMSProperty: end
D/AndroidRuntime(13430): addProductProperty: start
D/dalvikvm(13430): Trying to load lib libjavacore.so 0x0
D/dalvikvm(13430): Added shared lib libjavacore.so 0x0
D/dalvikvm(13430): Trying to load lib libnativehelper.so 0x0
D/dalvikvm(13430): Added shared lib libnativehelper.so 0x0
D/dalvikvm(13430): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack(13430): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug(13430): failed to load memtrack module: -2
D/dalvikvm(13430): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime(13430): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2422): START PACKAGE DELETE: observer{1128734968}
D/PackageManager( 2422): pkg{<packageName>}
D/PackageManager( 2422): user{0}
D/PackageManager( 2422): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2422): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2422): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2422): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2422): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 2422): !@killApplicatoin: 10524, uninstall pkg
I/ActivityManager( 2422): Killing 6981:com.test.thalitest/u0a524 (adj 0): stop com.test.thalitest
I/ActivityManager( 2422): Killing 7545:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty for 1808s
I/ActivityManager( 2422): Killing 7471:com.android.calendar/u0a144 (adj 15): empty for 1808s
I/ActivityManager( 2422): Killing 5536:com.android.mms/u0a49 (adj 15): empty for 1809s
I/ActivityManager( 2422): Killing 7570:com.android.providers.calendar/u0a45 (adj 15): empty for 1809s
I/ActivityManager( 2422): Killing 7557:com.sec.android.app.taskmanager/u0a168 (adj 15): empty for 1809s
I/ActivityManager( 2422): Killing 7530:com.sec.esdk.elm/u0a98 (adj 15): empty for 1810s
I/ActivityManager( 2422): Killing 7513:com.sec.android.app.clockpackage/u0a88 (adj 15): empty for 1810s
I/ActivityManager( 2422): Killing 7497:com.samsung.android.scloud.sync/u0a64 (adj 15): empty for 1810s
I/ActivityManager( 2422): Killing 6368:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1811s
I/ActivityManager( 2422): Killing 7409:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1813s
I/ActivityManager( 2422): Killing 7204:com.android.chrome/u0a85 (adj 15): empty for 1813s
I/ActivityManager( 2422): Killing 6549:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1814s
I/ActivityManager( 2422): Killing 7277:com.sec.android.app.voicenote/1000 (adj 15): empty for 1815s
I/ActivityManager( 2422): Killing 7265:com.sec.android.app.videoplayer/u0a53 (adj 15): empty for 1815s
D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
I/SurfaceFlinger( 1922): id=18 Removed EimLayer (5/10)
I/SurfaceFlinger( 1922): id=17 Removed EimLayer (4/9)
I/SurfaceFlinger( 1922): id=18 Removed EimLayer (-2/9)
D/Launcher( 2786): onRestart, Launcher: 1117126664
D/Launcher( 2786): onStart, Launcher: 1117126664
D/Launcher.HomeView( 2786): onStart
I/SurfaceFlinger( 1922): id=22 createSurf (720x1280),1 flag=4, Mauncher
V/WindowManager( 2422): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
I/WindowState( 2422): WIN DEATH: Window{4319ed00 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1922): id=19 Removed NainActivit (6/9)
D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2422): tr p:2786,o:f
I/SurfaceFlinger( 1922): id=19 Removed NainActivit (-2/9)
D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2422): semi p:2786,o:f
I/SurfaceFlinger( 1922): id=19 Removed NainActivit (-2/9)
W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 2422): Got RemoteException sending setActive(false) notification to pid 6981 uid 10524
D/CountryDetector( 2422): No listener is left
W/PackageSettings( 2422): Skipping PackageSetting{42b97aa8 com.example.hello/10511} due to missing metadata
D/PackageManager( 2422): checkUidPermission - Execution time: 214 ms
D/PackageManager( 2422): checkUidPermission - Execution time: 220 ms
D/PackageManager( 2422): checkUidPermission - Execution time: 186 ms
D/PackageManager( 2422): queryIntentReceivers - Execution time: 136 ms
D/PackageManager( 2422): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10524, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/PackageManager( 2422): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10524, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/FPMS_FingerprintManagerService( 2603): onReceive: android.intent.action.PACKAGE_REMOVED
E/SamsungIME( 3005): mOCRHelper is null
D/QuickConnect[1.1][2] ( 5019): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "sms"
I/SELinux (13462): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13462):  
D/dalvikvm( 2961): GC_EXPLICIT freed 1469K, 29% free 10033K/14072K, paused 9ms+14ms, total 143ms
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "smsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/GeofencerStateMachine( 2738): Ignoring removeGeofence because network location is disabled.
D/dalvikvm( 3284): GC_EXPLICIT freed 270K, 23% free 12289K/15852K, paused 13ms+72ms, total 195ms
I/SELinux (13462): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13462):  
I/SELinux (13462):  
I/SELinux (13462): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13462): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13462): >>>>> Normal User
E/dalvikvm(13462): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux (13462): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/SQLiteConnectionPool( 3284): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "mms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider(13462): in addTimaSignatureService
D/TimaKeyStoreProvider(13462): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13462): Added TimaKesytore provider
D/RegisteredServicesCache( 2760): empty dynamic service
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "mmsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 2422): GC_EXPLICIT freed 1799K, 57% free 24670K/56260K, paused 15ms+18ms, total 293ms
D/dalvikvm( 2422): WAIT_FOR_CONCURRENT_GC blocked 122ms
I/InputReader( 2422): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "sms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "smsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(13462): GC_CONCURRENT freed 2998K, 33% free 9568K/14072K, paused 3ms+1ms, total 22ms
D/dalvikvm(13462): WAIT_FOR_CONCURRENT_GC blocked 13ms
D/RCPManagerService( 2422): PackageReceiver onReceive()
I/HarmonyEASService( 2422): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2422):   Scheme: "mms"
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
D/elm:14132(13462): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
I/PackageManager( 2422):   Scheme: "mmsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132(13462): ELMEngine.ELMEngine( context ).
D/elm:14132(13462): MDMBridge.setEnterpriseBridge()
D/elm:14132(13462): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/dalvikvm( 2760): GC_CONCURRENT freed 1210K, 30% free 10611K/14964K, paused 9ms+3ms, total 84ms
D/dalvikvm( 2760): WAIT_FOR_CONCURRENT_GC blocked 61ms
I/SELinux (13475): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13475):  
D/elm:14132(13462): ElmAgentService : onCreate()
D/elm:14132(13462): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132(13462): MainReceiver.listeningToPackageRemoved()
D/elm:14132(13462): MDMBridge.getInstance()
D/elm:14132(13462): MDMBridge.getAllLicenseInfoFromSDK()
D/EnterpriseDeviceManagerService( 2422): Package has changed for user 0
D/elm:14132(13462): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux (13475): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13475):  
I/SELinux (13475):  
I/SELinux (13475): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13475): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13475): >>>>> Normal User
E/dalvikvm(13475): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux (13475): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/elm:14132(13462): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/TimaKeyStoreProvider(13475): in addTimaSignatureService
D/elm:14132(13462): ElmAgentService : onDestroy().
D/TimaKeyStoreProvider(13475): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13475): Added TimaKesytore provider
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 2422): GC_EXPLICIT freed 785K, 56% free 24761K/56260K, paused 12ms+27ms, total 367ms
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(13475): GC_CONCURRENT freed 2989K, 32% free 9574K/14068K, paused 8ms+4ms, total 56ms
D/dalvikvm(13475): WAIT_FOR_CONCURRENT_GC blocked 49ms
D/BackupManagerService( 2422): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 2422): removePackageParticipantsLocked: uid=10524 #1
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 2422): delete sourFile : 
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (13491): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13491):  
D/PackageManager( 2422): delete native library directory: 
D/PackageManager( 2422): return delete result to caller: 1128734968
D/AndroidRuntime(13430): Shutting down VM
D/PackageManager( 2422): returnCode: 1
D/dalvikvm(13430): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+0ms, total 4ms
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "sms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (13491): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13491):  
I/SELinux (13491):  
I/SELinux (13491): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13491): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13491): >>>>> Normal User
E/dalvikvm(13491): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux (13491): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(13491): in addTimaSignatureService
D/TimaKeyStoreProvider(13491): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13491): Added TimaKesytore provider
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "smsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "mms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2422):   Scheme: "mmsto"
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(13491): GC_CONCURRENT freed 2999K, 33% free 9567K/14072K, paused 3ms+2ms, total 29ms
D/dalvikvm(13491): WAIT_FOR_CONCURRENT_GC blocked 26ms
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SELinux (13504): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13504):  
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector( 2422): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2422): clearDefaults: com.test.thalitest
D/dalvikvm( 1923): GC_EXPLICIT freed 41K, 15% free 9501K/11052K, paused 4ms+4ms, total 46ms
I/SELinux (13504): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13504):  
I/SELinux (13504):  
I/SELinux (13504): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13504): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(13504): >>>>> Normal User
E/dalvikvm(13504): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
W/ApplicationsProvider( 2961): Could not fetch usage stats
W/ApplicationsProvider( 2961): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2961): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2961): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2961): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2961): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2961): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2961): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2961): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2961): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2961): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2961): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2961): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SELinux (13504): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 15% free 9501K/11052K, paused 4ms+4ms, total 37ms
D/TimaKeyStoreProvider(13504): in addTimaSignatureService
D/TimaKeyStoreProvider(13504): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13504): Added TimaKesytore provider
D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 15% free 9501K/11052K, paused 3ms+5ms, total 40ms
D/dalvikvm(13504): GC_CONCURRENT freed 3003K, 33% free 9565K/14076K, paused 3ms+2ms, total 27ms
D/dalvikvm(13504): WAIT_FOR_CONCURRENT_GC blocked 18ms
I/PCWCLIENTTRACE_PushUtil( 6339): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6339): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6339): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6339): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/SELinux (13520): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13520):  
I/SELinux (13520): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13520):  
I/SELinux (13520):  
I/SELinux (13520): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13520): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13520): >>>>> Normal User
E/dalvikvm(13520): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
E/SELinux (13520): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(13520): in addTimaSignatureService
D/TimaKeyStoreProvider(13520): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13520): Added TimaKesytore provider
D/dalvikvm(13520): GC_CONCURRENT freed 2983K, 32% free 9576K/14068K, paused 3ms+2ms, total 26ms
D/dalvikvm(13520): WAIT_FOR_CONCURRENT_GC blocked 22ms
W/System.err(13520): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err(13520): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err(13520): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err(13520): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err(13520): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err(13520): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err(13520): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err(13520): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err(13520): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err(13520): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err(13520): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err(13520): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err(13520): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err(13520): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err(13520): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err(13520): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(13520): 	at android.os.Looper.loop(Looper.java:146)
W/System.err(13520): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err(13520): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err(13520): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err(13520): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err(13520): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err(13520): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err(13520): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err(13520): 	at libcore.io.Posix.open(Native Method)
W/System.err(13520): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err(13520): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err(13520): 	... 21 more
D/GalaxyFinderApplication(13520): [Slink platform] Version = 29011
D/GalaxyFinderApplication(13520): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux (13534): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13534):  
I/SELinux (13534): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13534):  
I/SELinux (13534):  
I/SELinux (13534): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13534): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(13534): >>>>> Normal User
E/dalvikvm(13534): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
E/SELinux (13534): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(13534): in addTimaSignatureService
D/TimaKeyStoreProvider(13534): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13534): Added TimaKesytore provider
D/dalvikvm(13534): GC_CONCURRENT freed 3004K, 33% free 9557K/14068K, paused 2ms+2ms, total 24ms
D/dalvikvm(13534): WAIT_FOR_CONCURRENT_GC blocked 21ms
W/ContextImpl(13534): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences(13534): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences(13534): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication(13534): ContentProvider is not null
W/ResourceType(13534): No package identifier when getting value for resource number 0x00000000
I/System.out(13534): resource Id::2131361807
E/SQLiteDatabase(13534): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(13534): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13534): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13534): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(13534): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(13534): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13534): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13534): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13534): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(13534): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(13534): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(13534): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(13534): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(13534): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(13534): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(13534): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/SQLiteDatabase(13534): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/SQLiteDatabase(13534): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/SQLiteDatabase(13534): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase(13534): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase(13534): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase(13534): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase(13534): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/SQLiteDatabase(13534): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/SQLiteDatabase(13534): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/SQLiteDatabase(13534): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/SQLiteDatabase(13534): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/SQLiteDatabase(13534): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/SQLiteDatabase(13534): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/SQLiteDatabase(13534): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(13534): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(13534): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13534): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(13534): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(13534): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(13534): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(13534): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(13534): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(13534): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(13534): Shutting down VM
W/dalvikvm(13534): threadid=1: thread exiting with uncaught exception (group=0x41ad5c08)
E/AndroidRuntime(13534): FATAL EXCEPTION: main
E/AndroidRuntime(13534): Process: com.sec.android.app.shealth, PID: 13534
E/AndroidRuntime(13534): java.lang.RuntimeException: Unable to create application com.sec.android.app.shealth.SHealthApplication: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13534): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4793)
E/AndroidRuntime(13534): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(13534): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(13534): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(13534): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(13534): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(13534): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(13534): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(13534): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(13534): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(13534): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(13534): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13534): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(13534): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(13534): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(13534): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(13534): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(13534): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(13534): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(13534): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(13534): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(13534): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(13534): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(13534): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/AndroidRuntime(13534): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/AndroidRuntime(13534): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/AndroidRuntime(13534): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/AndroidRuntime(13534): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/AndroidRuntime(13534): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/AndroidRuntime(13534): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/AndroidRuntime(13534): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/AndroidRuntime(13534): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/AndroidRuntime(13534): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/AndroidRuntime(13534): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/AndroidRuntime(13534): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/AndroidRuntime(13534): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/AndroidRuntime(13534): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/AndroidRuntime(13534): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/AndroidRuntime(13534): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/AndroidRuntime(13534): 	... 10 more
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop228.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2422): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2422): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2422): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2422): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2422): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2422): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2422): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2422): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2422): 	... 5 more
I/SELinux (13554): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13554):  
I/Process (13534): Sending signal. PID: 13534 SIG: 9
I/ActivityManager( 2422): Process com.sec.android.app.shealth (pid 13534) (adj 0) has died.
I/SELinux (13554): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13554):  
I/SELinux (13554):  
I/SELinux (13554): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts

```
