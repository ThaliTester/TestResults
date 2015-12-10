#### Test 506502784dae475_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
I/PowerManagerService( 2420): [PWL] Off : 105s ago
I/PowerManagerService( 2420): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2420): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2420): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2420, ws=null) (elapsedTime=257)
,--------- beginning of /dev/log/main
D/AndroidRuntime( 6906): 
D/AndroidRuntime( 6906): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6906): CheckJNI is OFF
D/AndroidRuntime( 6906): setted country_code = Poland
D/AndroidRuntime( 6906): setted countryiso_code = PL
D/AndroidRuntime( 6906): setted sales_code = PLS
D/AndroidRuntime( 6906): readGMSProperty: start
D/AndroidRuntime( 6906): readGMSProperty: already setted!!
D/AndroidRuntime( 6906): readGMSProperty: end
D/AndroidRuntime( 6906): addProductProperty: start
D/dalvikvm( 6906): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6906): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6906): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6906): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6906): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6906): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6906): failed to load memtrack module: -2
D/dalvikvm( 6906): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6906): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2420): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@4
I/SurfaceFlinger( 1921): id=20 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1921): id=21 createSurf (16x16),-1 flag=20004, EimLayer
W/ActivityManager( 2420): mDVFSHelper.acquire()
I/SELinux ( 6919): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6919):  
D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6906): Shutting down VM
D/dalvikvm( 6906): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 6919): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6919):  
I/SELinux ( 6919):  
I/SELinux ( 6919): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6919): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6919): >>>>> Normal User
E/dalvikvm( 6919): >>>>> com.test.thalitest [ userId:0 | appId:10528 ]
E/SELinux ( 6919): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 6919): in addTimaSignatureService
D/TimaKeyStoreProvider( 6919): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6919): Added TimaKesytore provider
V/WindowManager( 2420): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SQLiteSecureOpenHelper( 4133): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4133): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=9 Removed Mauncher (8/10)
I/SurfaceFlinger( 1921): id=9 Removed Mauncher (-2/10)
D/Launcher( 2788): onTrimMemory. Level: 20
D/dalvikvm( 6919): GC_CONCURRENT freed 2997K, 32% free 9568K/13940K, paused 2ms+1ms, total 19ms
D/dalvikvm( 6919): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 6919): Binding Chromium to the background looper Looper (main, tid 1) {422ad378}
I/chromium( 6919): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 6919): Initializing chromium process, renderers=0
W/chromium( 6919): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 6919): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 6919): loaded /system/lib/egl/libGLESv1_CM_mali.so
D/libEGL  ( 6919): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 6919): Mali API Version : 401
I/Mali    ( 6919): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
I/dalvikvm( 6919): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 6919): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 6919): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 6919): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 6919): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 6919): VFY: replacing opcode 0x6e at 0x0008
D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2420): tr p:6919,o:f
W/dalvikvm( 6919): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 6919): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 6919): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 6919): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 6919): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 6919): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 6919): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 6919): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 6919): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6919): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 6919): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 6919): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 6919): CordovaWebView is running on device made by: samsung
D/StatusBarManagerService( 2420): semi p:6919,o:f
D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
I/SurfaceFlinger( 1921): id=22 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
I/HWUI    ( 6919): EGLImpl-HWUI Protected EGL context created
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/OpenGLRenderer( 6919): Enabling debug mode 0
W/AwContents( 6919): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 6919): showStatusIcon on inactive InputConnection
W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2420): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@8
D/JsMessageQueue( 6919): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 6919): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422a9b20
D/dalvikvm( 6919): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422a9b20
D/jxcore_app_log( 6919): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2030908344
D/JX-Cordova( 6919): jxcore cordova android initializing
I/dalvikvm( 6919): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 6919): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 6919): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 6919): GC_CONCURRENT freed 1307K, 20% free 11334K/14012K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 6919): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 6919): GC_CONCURRENT freed 1865K, 18% free 14968K/18224K, paused 2ms+2ms, total 44ms
,D/dalvikvm( 6919): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 6919): GC_FOR_ALLOC freed 5358K, 31% free 16210K/23188K, paused 52ms, total 52ms
,D/dalvikvm( 6919): GC_CONCURRENT freed 6685K, 32% free 17669K/25772K, paused 1ms+11ms, total 68ms
,D/dalvikvm( 6919): WAIT_FOR_CONCURRENT_GC blocked 43ms
,D/dalvikvm( 6919): GC_FOR_ALLOC freed 1243K, 33% free 17498K/25772K, paused 51ms, total 51ms
,I/dalvikvm-heap( 6919): Grow heap (frag case) to 21.942MB for 3688532-byte allocation
,D/dalvikvm( 6919): GC_FOR_ALLOC freed 2434K, 37% free 18665K/29376K, paused 57ms, total 57ms
,W/jxcore-log( 6919): Initializing JXcore engine
,W/jxcore-log( 6919): JXcore engine is ready
,W/jxcore-log( 6919): Starting JXcore engine
,W/jxcore-log( 6919): Platform android
W/jxcore-log( 6919): 
,W/jxcore-log( 6919): Process ARCH arm
W/jxcore-log( 6919): 
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/jxcore-log( 6919): JXcore Cordova bridge is ready!,
I/jxcore-log( 6919): 
,W/jxcore-log( 6919): JXcore engine is started,
,I/chromium( 6919): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/jxcore-log( 6919): Toggling radios to true,
I/jxcore-log( 6919): 
,W/ActivityManager( 2420): Permission Denial: getCurrentUser() from pid=6919, uid=10528 requires android.permission.INTERACT_ACROSS_USERS,
,W/BluetoothManagerService( 2420): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 2420): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6919, uid=10528 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 2420): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/BluetoothManagerService( 2420): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:620)
W/BluetoothManagerService( 2420): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
W/BluetoothManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DevicePolicyManagerService( 2420): getAllowBluetoothMode - value retunrs : 2
,D/BluetoothManagerService( 2420): foregroundUser: 0
,E/BluetoothManagerService( 2420): Package is exist.
,I/WifiManager( 6919): packageName : com.test.thalitest
,I/WifiManager( 6919): setWifiEnabled : true
,I/WifiService( 2420): setWifiEnabled: true pid=6919, uid=10528
D/BluetoothAdapterState( 5063): CURRENT_STATE=OFF, MSG = USER_TURN_ON
I/BluetoothAdapterState( 5063): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 5063): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5063): updateAdapterState state is 11
D/BluetoothAdapterService( 5063): Broadcasting updateAdapterState() to 1 receivers.
,W/ActivityManager( 2420): Permission Denial: getCurrentUser() from pid=6919, uid=10528 requires android.permission.INTERACT_ACROSS_USERS
D/BluetoothAdapterService( 5063): Autoconnection is available 
D/BluetoothAdapterService( 5063): updateAdapterState prevState = 10newState = 11
D/BtConfig.SecureMode( 5063): isSecureModeOn:false
D/BtSettings.ProfileConfig( 5063): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/WifiService( 2420): Failed getting userId using ActivityManagerNative
W/WifiService( 2420): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6919, uid=10528 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2420): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2420): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2420): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2420): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService( 2420): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2420): [BT Setting State] State =11
W/BluetoothAdapterService( 5063): isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
D/BtSettings.ProfileConfig( 5063): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/PhoneApp( 2752): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 11
,I/SamsungIME( 2952): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
W/BluetoothAdapterService( 5063): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 5063): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,I/QuickConnect[1.1][2] ( 5037): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_ON
W/BluetoothAdapterService( 5063): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 5063): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 5063): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 5063): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,E/WifiHW  ( 2420): ##################### set firmware type 0 #####################
,I/WifiService( 2420): disconnect: pid=6919, uid=10528
W/BluetoothAdapterService( 5063): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 5063): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,I/jxcore-log( 6919): Radios toggled
I/jxcore-log( 6919): 
I/WifiHW  ( 1915): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
W/BluetoothAdapterService( 5063): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5063): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
E/WifiHW  ( 1915): Cannot open "/data/.cid.info": No such file or directory
I/WifiHW  ( 1915): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
E/WifiHW  ( 1915): TEMP_FAILURE_RETRY complete
,D/SoftapController( 1915): Softap fwReload - Ok
W/BluetoothAdapterService( 5063): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 5063): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5063): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5063): Unable to stop service com.android.bluetooth.gatt.GattService. Invalid state: 12
W/BluetoothAdapterService( 5063): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5063): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 5063): Not skipping com.android.bluetooth.hfp.HeadsetService
D/CommandListener( 1915): Setting iface cfg
,D/CommandListener( 1915): Trying to bring down wlan0
W/BluetoothAdapterService( 5063): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 5063): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5063): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5063): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5063): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5063): Not skipping com.android.bluetooth.hid.HidService
,D/WifiHW  ( 2420): Skip the update_ctrl_interface
,D/WifiHW  ( 2420): Skip the update_ctrl_interface
,E/WifiHW  ( 2420): supplicant_name : p2p_supplicant
W/BluetoothAdapterService( 5063): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5063): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5063): Not skipping com.android.bluetooth.hdp.HealthService
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/HeadsetService( 5063): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 5063): classInitNative: succeeds
D/HeadsetStateMachine( 5063): Version 1.5
,D/HeadsetStateMachine( 5063): make
D/BluetoothNotiBroadcastReceiver( 5524): onReceive
,D/WifiMonitor( 2420): startMonitoring(wlan0) with mConnected = false
,E/HeadsetStateMachine( 5063): # of Max HF connection is 2
,D/QuickConnect[1.1][2] ( 5037): HeadsetProfile.onServiceConnected - Bluetooth service connected
,W/BluetoothAdapterService( 5063): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 5063): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,I/wpa_supplicant( 6967): wpa_supplicant v2.1-devel-4.4.22014-07-16/12:43:14
,W/BluetoothAdapterService( 5063): Not skipping com.android.bluetooth.pan.PanService
,I/wpa_supplicant( 6967): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 6967): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 6967): >>>>> Not GET KEY, IV <<<<<
,I/SELinux ( 6969): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6969):  
E/wpa_supplicant( 6967): getIMSI cannot open file
E/wpa_supplicant( 6967): Interworking config: - SIM READ ERROR
,W/BluetoothAdapterService( 5063): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 5063): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5063): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5063): check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 5063): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5063): Not skipping com.broadcom.bt.service.sap.SapService
,I/bluedroid( 5063): get_profile_interface handsfree
,I/BluetoothAdapterState( 5063): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAtMessage( 5063): createCMTIContentObservers
,D/HeadsetStateMachine( 5063): Enter Disconnected: -2
,E/HeadsetStateMachine( 5063): set to mRemoteBrsf = 0
I/SELinux ( 6969): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6969):  
I/SELinux ( 6969):  
,I/SELinux ( 6969): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/HeadsetStateMachine( 5063): map size, before remove : 0
D/HeadsetStateMachine( 5063): map size, after remove: 0
,D/HeadsetStateMachine( 5063): mNextConnectingDevice : null
E/SELinux ( 6969): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6969): >>>>> Normal User
,E/dalvikvm( 6969): >>>>> pl.k2.droidoaudioteka [ userId:0 | appId:10066 ]
,E/SELinux ( 6969): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/BluetoothA2dp( 2420): Proxy object connected
,D/BluetoothA2dp( 5037): Proxy object connected
D/A2dpService( 5063): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 5063): classInitNative: succeeds
,D/A2dpStateMachine( 5063): make
,I/bluedroid( 5063): get_profile_interface a2dp
,D/QuickConnect[1.1][2] ( 5037): A2dpProfile.onServiceConnected - Bluetooth service connected
,I/GKI_LINUX( 5063): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 5063): Enter Disconnected: -2
I/BluetoothAvrcpServiceJni( 5063): classInitNative: succeeds
,D/BluetoothA2dp( 4133): Proxy object connected
,I/bluedroid( 5063): get_profile_interface avrcp
,I/dalvikvm( 6969): Enabling JNI app bug workarounds for target SDK version 7...
,D/MediaFocusControl( 2420): >>> registerRemoteControlDisplay
,D/TimaKeyStoreProvider( 6969): in addTimaSignatureService
,I/BluetoothHidServiceJni( 5063): classInitNative: succeeds
,D/BluetoothInputDevice( 5037): Proxy object connected
,D/HidService( 5063): Received start request. Starting profile...
I/bluedroid( 5063): get_profile_interface hidhost
,D/HidService( 5063): setHidService(): set to: null
,I/BluetoothHealthServiceJni( 5063): classInitNative: succeeds
,D/QuickConnect[1.1][2] ( 5037): HidProfile.onServiceConnected - Bluetooth service connected
,D/HealthService( 5063): Received start request. Starting profile...
,I/bluedroid( 5063): get_profile_interface health
,I/BluetoothPanServiceJni( 5063): classInitNative(L105): succeeds
,D/TimaKeyStoreProvider( 6969): Cannot add TimaSignature Service, License check Failed
,D/BluetoothPan( 2420): BluetoothPAN Proxy object connected
,D/ActivityThread( 6969): Added TimaKesytore provider
D/PanService( 5063): Received start request. Starting profile...
D/BluetoothPanServiceJni( 5063): initializeNative(L110): pan
,I/bluedroid( 5063): get_profile_interface pan
,D/BluetoothTethering( 2420): got CMD_CHANNEL_HALF_CONNECTED
,D/HeadsetStateMachine( 5063): Try to query the phonestate on bind
,D/BluetoothPhoneService( 2752): handleMessage: 4
,V/BluetoothPhoneService( 2752): Call state Converted2: IDLE/IDLE -> 6
,W/BluetoothHeadset( 2752): Proxy not attached to service
,I/wpa_supplicant( 6967): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 6967): getIMSI cannot open file
,E/wpa_supplicant( 6967): Interworking config: - SIM READ ERROR
,I/wpa_supplicant( 6967): >>>>> Not GET KEY, IV <<<<<
I/wpa_supplicant( 6967): rfkill: Cannot open RFKILL control device
,D/BluetoothMapService( 5063): Received start request. Starting profile...
,W/BluetoothMapMasInstance( 5063): mAccount : null
,I/BluetoothSAPServiceJni( 5063): classInitNative(L204): succeeds
D/SapService( 5063): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 5063): initializeNative(L209): sap
,I/bluedroid( 5063): get_profile_interface sap
,D/HeadsetPhoneState( 5063): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetStateMachine( 5063): Disconnected process message: 11
,D/HeadsetStateMachine( 5063): Proxy object connected
D/HeadsetPhoneState( 5063): sendDeviceDataStateChanged
,D/HeadsetStateMachine( 5063): Disconnected process message: 20
D/HeadsetPhoneState( 5063): Signal level : previous=0 curr=0
,V/HeadsetService( 5063): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5063): Disconnected process message: 10
,D/HeadsetPhoneState( 5063): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5063): Disconnected process message: 11
D/BluetoothAdapterService( 5063): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5063): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5063): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5063): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5063): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5063): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterState( 5063): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 5063): enable
,D/GKI_LINUX( 5063): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,E/bt-btif ( 5063): Calling BTA_HhEnable
,E/bt-btif ( 5063): btif_storage_get_adapter_property service_mask:0x160040
,E/BluetoothServiceJni( 5063): populateRssiValuesNative
I/bluedroid( 5063): getModelRssiValues
,E/BluetoothServiceJni( 5063): model_rssi_values_callback: low = -75, mid = -65, high = 127
,D/dalvikvm( 6969): GC_CONCURRENT freed 2994K, 32% free 9575K/13944K, paused 5ms+1ms, total 36ms
D/dalvikvm( 6969): WAIT_FOR_CONCURRENT_GC blocked 30ms
,E/BluetoothRemoteDevices( 5063): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BtConfig.SecureMode( 5063): isSecureModeOn:false
,E/Watchdog( 2420): !@Sync 10
E/BluetoothRemoteDevices( 5063): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 241
,E/BluetoothRemoteDevices( 5063): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 10
,D/BtConfig.SecureMode( 5063): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5063): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 241
,E/BluetoothRemoteDevices( 5063): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,D/BtConfig.SecureMode( 5063): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5063): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 241
,E/BluetoothRemoteDevices( 5063): devicePropertyChangedCallback: bdDevice: F8:CF:C5:D9:E5:61, value is empty for type: 10
,D/BtConfig.SecureMode( 5063): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5063): devicePropertyChangedCallback: bdDevice: F8:CF:C5:D9:E5:61, value is empty for type: 241
,E/BluetoothRemoteDevices( 5063): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
,D/BtConfig.SecureMode( 5063): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5063): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 241
,E/BluetoothRemoteDevices( 5063): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,D/BtConfig.SecureMode( 5063): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5063): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 241
,E/BluetoothRemoteDevices( 5063): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,D/BtConfig.SecureMode( 5063): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5063): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 241
,E/BluetoothRemoteDevices( 5063): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/BtConfig.SecureMode( 5063): isSecureModeOn:false
E/BluetoothRemoteDevices( 5063): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 241
E/bt-btif ( 5063): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 5063): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
E/bt-btif ( 5063): btif_sock_init: !radio_req && !rfc_init
,D/IOP_DB_BT( 5063): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 5063): db_open: db_open : handle 2011030572l, read 9734 bytes onto local cache
D/IOP_DB_BT( 5063): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 5063): db_query: result 1
,I/        ( 5063): iop_db_open: iop_db_open status 0
,I/bte_conf( 5063): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 5063): [1] primary_record=1 vendor_id=0x0075 vendor_id_source=0x0001 product_id=0x0100 version=0x0200
,I/bte_conf( 5063): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 5063): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,D/BluetoothAdapterState( 5063): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5063): ScanMode =  20
,D/BluetoothAdapterProperties( 5063): State =  11
,D/BtConfig.SecureMode( 5063): isSecureModeOn:false
D/BtConfig.SecureMode( 5063): isSecureModeOn:false
D/BtConfig.SecureMode( 5063): isSecureModeOn:false
D/BtConfig.SecureMode( 5063): isSecureModeOn:false
,D/BtConfig.SecureMode( 5063): isSecureModeOn:false
D/BtConfig.SecureMode( 5063): isSecureModeOn:false
D/BtConfig.SecureMode( 5063): isSecureModeOn:false
D/BtConfig.SecureMode( 5063): isSecureModeOn:false
,I/BluetoothAdapterState( 5063): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterService( 5063): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5063): updateAdapterState state is 12
,D/BluetoothAdapterService( 5063): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterService(1110085320)( 5063): Register RemoteMessageListener
,D/HeadsetService( 5063): registerMessageListener
D/BluetoothAdapterService( 5063): Autoconnection is available 
,D/HeadsetStateMachine( 5063): Disconnected process message: 70
D/HeadsetStateMachine( 5063): processRegisterMessageListener : 2, com.android.bluetooth.btservice.RemoteDevices$1@42298708
,D/BluetoothAdapterService( 5063): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 5063): starting service from this receiver
D/BluetoothInputDevice( 5037): onBluetoothStateChange: up=true
,D/BluetoothPanServiceJni( 5063): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
,D/BluetoothA2dp( 4133): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 5037): onBluetoothStateChange: up=true
D/BluetoothA2dp( 2420): onBluetoothStateChange: up=true
,W/ContextImpl( 5063): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.startService:506 com.android.bluetooth.btservice.AdapterService.updateAdapterState:653 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
,W/System.err( 6969): java.io.FileNotFoundException: /system/etc/vold.fstab: open failed: ENOENT (No such file or directory)
,D/BluetoothAdapterService( 5063): initWakeLock, pfd lock: {ParcelFileDescriptor: FileDescriptor[85]}, pfd unlock: {ParcelFileDescriptor: FileDescriptor[86]}
,D/bluedroid( 5063): init_wake_lock lock_fd:85, unlock_fd:86
,I/BluetoothPbapService( 5063): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,I/BluetoothAdapterState( 5063): Entering On State from state = 11
W/System.err( 6969): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 6969): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 6969): 	at java.util.Scanner.<init>(Scanner.java:158)
,W/System.err( 6969): 	at java.util.Scanner.<init>(Scanner.java:138)
,W/System.err( 6969): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.readVoldFile(StorageOptions.java:107)
W/System.err( 6969): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.determineStorageOptions(StorageOptions.java:31)
W/System.err( 6969): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:81)
,W/System.err( 6969): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:129)
,W/System.err( 6969): 	at pl.k2.droidoaudioteka.ui.AudiotekaApplication.onCreate(AudiotekaApplication.java:171)
W/InputMethodManagerService( 2420): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2420): [BT Setting State] State =12
,I/InputMethodManagerService( 2420): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
W/System.err( 6969): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 6969): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 6969): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 6969): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 6969): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6969): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6969): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 6969): 	at java.lang.reflect.Method.invokeNative(Native Method)
D/BluetoothAdapterService(1110085320)( 5063): Get Bonded Devices being called
W/System.err( 6969): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 6969): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 6969): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 6969): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 6969): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 6969): 	at libcore.io.Posix.open(Native Method)
W/System.err( 6969): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 6969): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 6969): 	... 20 more
W/System.err( 6969): file res dir: /data/data/pl.k2.droidoaudioteka/files
W/System.err( 6969): Excternal dir: /mnt/sdcard
D/PhoneApp( 2752): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 12
I/SamsungIME( 2952): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothHeadset( 2752): registerListener : 11, listenercom.android.phone.PhoneGlobals$MessageListener@42501450, true
,D/BluetoothHeadset( 2752): registerMessageListener
,I/QuickConnect[1.1][2] ( 5037): BluetoothHelper.ACTION_STATE_CHANGED - STATE_ON,
,D/HeadsetService( 5063): registerMessageListener,
D/HeadsetService( 5063): registerMessageListener,
D/HeadsetStateMachine( 5063): Disconnected process message: 70
,D/PhoneApp( 2752): registerMessageListener,
,D/HeadsetStateMachine( 5063): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@4238f6b0,
,I/BluetoothPbapService( 5063): Handler(): got msg=1
,V/BluetoothPbapService( 5063): PBAP Service initSocket try: 0
,D/BluetoothMapMasInstance( 5063): set MAP SDP message type : 1
,W/BluetoothAdapter( 5063): getBluetoothService() called with no BluetoothManagerCallback
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:2
E/BluetoothServiceJni( 5063): SOCK FLAG = 1 ***********************
W/BluetoothAdapter( 5063): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothPbapService( 5063): PBAP Socket is BluetoothServerSocket
E/BluetoothServiceJni( 5063): SOCK FLAG = 3 ***********************
,V/MaBo    ( 6969): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6969): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6969): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6969): moge zapisać w resDir?true
,D/GKI_LINUX( 5063): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,V/MaBo    ( 6969): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6969): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6969): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,W/GAV2    ( 6969): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/GAV2    ( 6969): Thread[main,5,main]: ExceptionReporter created, original handler is pl.k2.droidoaudioteka.common.helpers.AudiotekaExceptionHandler
,I/AUDIOTEKA_GA( 6969): init tracking...
,I/AUDIOTEKA_GA( 6969): app started!
,I/BugSenseHandler( 6969): Registering default exceptions handler
,D/AuthorizationBluetoothService( 2847): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/DownloadService( 6969): Tworzenie serwisu - onCreate()
,I/DownloadService( 6969): Start serwisu - onStart()
,I/BugSenseHandler( 6969): Registering default exceptions handler
,I/BugSenseHandler( 6969): Flushing...
,I/knox    ( 4976): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 4976): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/BugSenseHandler( 6969): Registering default exceptions handler
,I/knox    ( 4976): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 4976): KNOXAgentService : onCreate()
,D/knox    ( 4976): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 4976): KNOXAgentService. startJobThread() start
,D/knox    ( 4976): KNOXAgentService. JobThread()
,D/knox    ( 4976): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 4976): KNOXAgentService. startJobThread() wait
,I/PlayerService( 6969): Tworzenie serwisu - onCreate()
,I/SELinux ( 7012): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7012):  
I/BugSenseHandler( 6969): Flushing...
,I/BugSenseHandler( 6969): Registering default exceptions handler
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 13% free 9505K/10924K, paused 3ms+4ms, total 43ms
,I/SELinux ( 7012): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7012):  
I/SELinux ( 7012):  
,I/SELinux ( 7012): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7012): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7012): >>>>> Normal User
,E/dalvikvm( 7012): >>>>> tv.peel.smartremote [ userId:0 | appId:10165 ]
,E/SELinux ( 7012): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/knox    ( 4976): KNOXAgentService : onDestroy().
,D/knox    ( 4976): ModuleBase.cancelAllAlarmManageModule()
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9505K/10924K, paused 2ms+4ms, total 33ms
I/MediaFocusControl( 2420):   Remote Control   registerMediaButtonIntent() for PendingIntent{42cb1ea8: PendingIntentRecord{43120e50 pl.k2.droidoaudioteka broadcastIntent}}
D/TimaKeyStoreProvider( 7012): in addTimaSignatureService
V/KeyguardUpdateMonitor( 2580): handleSetGenerationId(g=2, clear=true)
D/TimaKeyStoreProvider( 7012): Cannot add TimaSignature Service, License check Failed
V/AUDIOTEKA_MB( 6969): new AudioManagerFocusWrapper in playerservice oncreate
D/ActivityThread( 7012): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9505K/10924K, paused 3ms+4ms, total 30ms
,I/PlayerService( 6969): Start serwisu - onStart()
,D/dalvikvm( 7012): GC_CONCURRENT freed 2998K, 32% free 9575K/13948K, paused 4ms+1ms, total 24ms
D/dalvikvm( 7012): WAIT_FOR_CONCURRENT_GC blocked 12ms
W/ContextImpl( 5524): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/LocalBluetoothProfileManager( 5524): Adding local A2DP profile
I/System.out( 6969): Thread-614(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 6969): Thread-618(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 6969): Thread-618(ApacheHTTPLog):isShipBuild true
I/System.out( 6969): Thread-618(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6969): Thread-614(ApacheHTTPLog):isShipBuild true
I/System.out( 6969): Thread-614(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
D/Tethering( 2420): interfaceStatusChanged wlan0, true
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
D/Tethering( 2420): interfaceStatusChanged wlan0, true
E/Tethering( 2420): No numeric data
I/ConnectivityService( 2420): defaultVal : 1, tetherEnabledInSettings : true
W/ContextImpl( 5524): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
D/Tethering( 2420): sendTetherStateChangedBroadcast 1, 0, 0
D/NtpTrustedTime( 2420): forceRefresh() from cache miss
D/NtpTrustedTime( 2420): forceRefresh Fail.
V/NetworkStats( 2420): performPollLocked(flags=0x1)
I/wpa_supplicant( 6967): wlan0: Setting scan request: 0 sec 100000 usec
D/NtpTrustedTime( 2420): forceRefresh() from cache miss
D/NtpTrustedTime( 2420): forceRefresh Fail.
V/NetworkStats( 2420): performPollLocked() took 16ms
I/wpa_supplicant( 6967): >>>>> Not GET KEY, IV <<<<<
D/LocalBluetoothProfileManager( 5524): Adding local HEADSET profile
I/wpa_supplicant( 6967): >>>>> Not GET KEY, IV <<<<<
I/wpa_supplicant( 6967): rfkill: Cannot open RFKILL control device
D/Tethering( 2420): interfaceLinkStateChanged p2p0, true
D/Tethering( 2420): interfaceStatusChanged p2p0, true
D/Tethering( 2420): interfaceLinkStateChanged p2p0, true
D/Tethering( 2420): interfaceStatusChanged p2p0, true
E/BluetoothHeadset( 5524): BTStateChangeCB is registed
E/BluetoothHeadset( 5524): BluetoothHeadset service is binded
W/ContextImpl( 5524): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
I/wpa_supplicant( 6967): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
W/ContextImpl( 5524): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/Bluetoothsap( 5524): bindService called to Bluetooth SAP Service
I/System.out( 6969): pool-1-thread-1 calls detatch()
W/BugSenseHandler( 6969): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
I/wpa_supplicant( 6967): P2P: initialized channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
I/wpa_supplicant( 6967): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/System.out( 6969): pool-1-thread-2 calls detatch()
W/BugSenseHandler( 6969): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
W/ContextImpl( 5524): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
D/WifiStateMachine( 2420): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
I/wpa_supplicant( 6967): Skip scan - bUseNetwork false
D/WifiNative( 2420): callSECApiString - ID [21]
W/ContextImpl( 5524): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
I/wpa_supplicant( 6967): HOTSPOT20_ENABLE called
I/wpa_supplicant( 6967): wlan0: HS20_DISABLED_COMPLETE normal
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
D/LocalBluetoothProfileManager( 5524): PANU : true
D/LocalBluetoothProfileManager( 5524): Adding local MAP profile
D/BluetoothMap( 5524): Create BluetoothMap proxy object
W/ContextImpl( 5524): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
D/WifiNative( 2420): callSECApiInt - ID [65]
E/WifiConfigStore( 2420): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative( 2420): callSECApiBoolean - ID [13]
I/wpa_supplicant( 6967): USE_NETWORK : USE_NETWORK ON
W/ContextImpl( 5524): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
I/wpa_supplicant( 6967): reset timer : RESET_TIMER 0
I/wpa_supplicant( 6967): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 6967): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 6967): First Scan Start
I/wpa_supplicant( 6967): Scan requested (ret=0) - scan timeout 30 seconds
W/ContextImpl( 5524): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/Bluetoothsap( 5524): bindService called to Bluetooth SAP Service
D/LocalBluetoothProfileManager( 5524): LocalBluetoothProfileManager construction complete
W/Settings( 5314): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 2420): Set the Nv default ccode
D/DockEventReceiver( 5524): finishStartingService: stopping service
D/BluetoothNotiBroadcastReceiver( 5524): onReceive
D/BluetoothA2dp( 5524): Proxy object connected
D/A2dpProfile( 5524): Bluetooth service connected
D/BtConfig.SecureMode( 5063): isSecureModeOn:false
D/WifiStateMachine( 2420): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
E/WifiStateMachine( 2420): HS20_DISABLED_COMPLETEnormal
D/WifiP2pService( 2420): P2pDisabledState{ what=131203 }
D/AuthorizationBluetoothService( 2847): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/AuthorizationBluetoothService( 2847): Proximity feature is not enabled.
D/CommandListener( 1915): Setting iface cfg
D/CommandListener( 1915): Trying to bring up p2p0
I/wpa_supplicant( 6967): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
D/WifiMonitor( 2420): startMonitoring(p2p0) with mConnected = true
E/WifiStateMachine( 2420): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiP2pService( 2420): P2pEnablingState
D/WifiP2pService( 2420): P2pEnablingState{ what=147457 }
D/WifiP2pService( 2420): P2p socket connection successful
D/WifiP2pService( 2420): P2pEnabledState
D/WifiP2pService( 2420): sending p2p connection changed broadcast: IDLE
D/WifiDisplayController( 2420): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController( 2420): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 2420): disconnect
D/QuickConnect[1.1][2] ( 5037): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
D/WifiDisplayController( 2420): updateConnection
D/WifiDisplayController( 2420): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 2420): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/HeadsetProfile( 5524): Bluetooth service connected
D/QuickConnect[1.1][2] ( 5037): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
D/WifiDisplayAdapter( 2420): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/WifiP2pStateTracker( 2420): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController( 2420): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/QuickConnect[1.1][2] ( 5037): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
D/Bluetoothsap( 5524): BluetoothSAP Proxy object connected
D/SapProfile( 5524): Bluetooth service connected
D/Bluetoothsap( 5524): getConnectedDevices()
D/BluetoothInputDevice( 5524): Proxy object connected
D/HidProfile( 5524): Bluetooth service connected
D/QuickConnect[1.1][2] ( 5037): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
W/BluetoothAdapter( 5063): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothPan( 5524): BluetoothPAN Proxy object connected
E/BluetoothServiceJni( 5063): SOCK FLAG = 0 ***********************
D/GKI_LINUX( 5063): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
D/WifiDisplayController( 2420): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: S5mini-1
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
I/BtOppRfcommListener( 5063): Accept thread started.
D/PanProfile( 5524): Bluetooth service connected
D/WifiP2pService( 2420): DeviceAddress: 02:e0:6d
D/BluetoothMap( 5524): Proxy object connected
D/MapProfile( 5524): Bluetooth service connected
D/BluetoothPbap( 5524): Proxy object connected
D/PbapServerProfile( 5524): Bluetooth service connected
D/Bluetoothsap( 5524): BluetoothSAP Proxy object connected
D/SapProfile( 5524): Bluetooth service connected
D/Bluetoothsap( 5524): getConnectedDevices()
D/WifiP2pService( 2420): sending p2p persistent groups changed broadcast
D/WifiP2pService( 2420): InactiveState
D/WifiP2pService( 2420): InactiveState{ what=139287 }
D/WifiP2pService( 2420): P2pEnabledState{ what=139287 }
D/QuickConnect[1.1][2] ( 5037): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/WifiP2pService( 2420): DefaultState{ what=139287 }
I/System.out( 6969): pool-1-thread-1 calls detatch()
W/BugSenseHandler( 6969): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
I/System.out( 6969): pool-1-thread-2 calls detatch()
W/BugSenseHandler( 6969): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
D/GKI_LINUX( 5063): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
D/dalvikvm( 2420): GC_CONCURRENT freed 4018K, 56% free 24409K/55324K, paused 9ms+13ms, total 177ms
D/dalvikvm( 2420): WAIT_FOR_CONCURRENT_GC blocked 83ms
,I/wpa_supplicant( 6967): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,D/dalvikvm( 2420): GC_EXPLICIT freed 152K, 57% free 24257K/55324K, paused 8ms+19ms, total 224ms
,I/ActivityManager( 2420): Killing 5736:com.sec.phone/1001 (adj 15): empty #43
,I/knox    ( 4976): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 4976): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 4976): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 4976): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
,D/knox    ( 4976): KNOXAgentService : onCreate()
,D/knox    ( 4976): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 4976): KNOXAgentService. startJobThread() start
,D/knox    ( 4976): KNOXAgentService. JobThread()
D/knox    ( 4976): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 4976): KNOXAgentService. startJobThread() wait
,D/knox    ( 4976): KNOXAgentService : onDestroy().
,D/knox    ( 4976): ModuleBase.cancelAllAlarmManageModule()
,D/NearbySettings( 5524): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 5524): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 5524): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 5524): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 5524): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5524): DMSUtil.isNetworkConnected - WIFI: IDLE
,I/NearbySettings( 5524): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5524): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5524): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5524): MountReceiver.mPrefHandler - 7002
,D/FileShare-Server( 5929): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/wpa_supplicant( 6967): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 6967): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 6967): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 6967): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,D/FileShare-Server( 5929): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,I/wpa_supplicant( 6967): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-6ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 6967): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 6967): Associated with C0.AA.48,
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 6967): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 6967): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 6967): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 6967): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 6967): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/WifiNative( 2420): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7047): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7047):  
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7047): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7047):  
I/SELinux ( 7047):  
,I/SELinux ( 7047): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7047): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7047): >>>>> Normal User
,E/dalvikvm( 7047): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7047): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7047): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7047): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7047): Added TimaKesytore provider
,D/WifiP2pService( 2420): InactiveState{ what=143375 }
,D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,D/AmoledAdjustTimer( 2420): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,D/dalvikvm( 7047): GC_CONCURRENT freed 2990K, 32% free 9575K/13940K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 7047): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/System.out( 7047): Inside WakeupProvider
,I/System.out( 7047): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 7047): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7047): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7047): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,I/dhcpcd  ( 7059): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7059): bssid match
,D/DialogFlow( 7047): initQueue()
,D/NearbySettings( 5524): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5524): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 5524): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 5524): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5524): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5524): MountReceiver.onReceive - Set preference state off
,I/ActivityManager( 2420): Killing 5602:com.google.android.music:main/u0a125 (adj 15): empty #43
V/NearbySettings( 5524): MountReceiver.mPrefHandler - 7002
,D/WifiP2pService( 2420): InactiveState{ what=143375 }
,D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2420): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2420): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2420): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2420): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2420): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2420): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
D/ConnectivityService( 2420): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2420): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2420): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2420): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/NearbySettings( 5524): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 5524): MountReceiver.onReceive - Keep current state
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,D/NearbySettings( 5524): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/NearbySettings( 5524): DMSUtil.isNetworkConnected - flag-null, state-null
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,I/NearbySettings( 5524): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 5524): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5524): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5524): MountReceiver.onReceive - Keep current state
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1,
,V/NetworkStats( 2420): updateIfacesLocked(),
,V/NetworkStats( 2420): performPollLocked(flags=0x1),
D/NtpTrustedTime( 2420): forceRefresh() from cache miss
,V/NetworkStats( 2420): performPollLocked() took 21ms,
,D/NearbySettings( 5524): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,I/NearbySettings( 5524): MountReceiver.onReceive - Keep current state,
,I/SurfaceFlinger( 1921): id=23 createSurf (1x1),1 flag=4, Uoast,
,D/NtpTrustedTime( 2420): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1449751219260 mCachedNtpElapsedRealtime : 321495 mCachedNtpCertainty : 10,
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit,
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/PowerManagerService( 2420): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2420
V/NetworkStats( 2420): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/Tethering( 2420): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2420): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2420): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/        ( 2420): Setting time of day to sec=1449751219
,D/        ( 2420): Trying to open a file
D/        ( 2420): File Open Success,
,D/        ( 2420): File Close Success,
,I/        ( 2420): DRM_TIME_PATH CHMOD 660 for resetState done ,
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
,D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,V/AlarmManager( 2420): waitForAlarm result :65536,
,I/DBG_DM  ( 4637): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/PCWCLIENTTRACE_PushUtil( 6151): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6151): sales region : global
,I/DBG_DM  ( 4637): [3.19.140541][Line:609][onReceive] ----------- XEVENT_DM_INIT WIFI ok
I/PCWCLIENTTRACE_PushUtil( 6151): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6151): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 4637): [3.19.140541][Line:214][xdmAgentTaskHandler] XEVENT_DM_INIT
,I/DBG_DM  ( 4637): [3.19.140541][Line:432][xdmInitAdpWaitSystemRootingCheck] Check completed.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,I/DBG_DM  ( 4637): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
D/StatusBar-DoNotDistrub( 2580): Received intent with android.intent.action.TIME_SET action
D/StatusBar-DoNotDistrub( 2580): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/NotificationMgr( 2752): updateNotificationsAtStartup()...
,D/NotificationMgr( 2752): - start call log query...
,W/Settings( 2420): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Parcel  ( 2420): nm 23
,I/PrGenericPlugin( 1924): [A] ENTER onAcquireDrmInfo : 0xb0d
I/PrGenericPlugin( 1924): [A] LEAVE onAcquireDrmInfo : 0xb0d
,I/DrmEventService( 2420):  no response from SecureClock 
D/StatusBar-DoNotDistrub( 2580): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,I/AudioService( 2420): getStreamVolume 5 index 110
D/StatusBar-DoNotDistrub( 2580): The STREAM NOTIFICATION volume is 0
,D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=com.android.systemui
I/DBG_DM  ( 4637): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
I/DBG_DM  ( 4637): [3.19.140541][Line:78][xdmFeatureGetBearerSettingFromCSCFotaDataBase] 
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
D/STATUSBAR-NotificationService( 2420): received android.intent.action.DORMANT_MODE_OFF
D/LightsService( 2420): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2420) 
,I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 5
D/Sensors ( 2420): LightSensor setDelay = 200000000
D/Sensors ( 2420): LightSensor setSensorDelay = 200000000
,D/LightsService( 2420): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/Sensors ( 2420): Light sensor flush: not enabled 0
D/Sensors ( 2420): LightSensor enable = 1
D/Sensors ( 2420): LightSensor enableSensor = 1
D/SensorManager( 2420): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/NotificationMgr( 2752): call log query complete.
D/NotificationMgr( 2752): call log cursor count : 0
,D/NotificationMgr( 2752): call log cursor count2 : null
I/SQLiteSecureOpenHelper( 4133): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4133): getDatabaseLocked(b,b,pwd)...
,I/DBG_DM  ( 4637): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,I/DBG_DM  ( 4637): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/dalvikvm( 4637): Total arena pages for JIT: 11
,I/dalvikvm( 4637): Total arena pages for JIT: 12
I/dalvikvm( 4637): Total arena pages for JIT: 13
I/dalvikvm( 4637): Total arena pages for JIT: 14
,I/dalvikvm( 4637): Total arena pages for JIT: 15
I/dalvikvm( 4637): Total arena pages for JIT: 16
,I/dalvikvm( 4637): Total arena pages for JIT: 17
,I/DBG_DM  ( 4637): [3.19.140541][Line:5949][xdbGetFUMOInitiatedType] Initiated Type: 2
,I/DBG_DM  ( 4637): [3.19.140541][Line:119][xdmInitAdpEXTInit] nStatus [220]
,I/DBG_DM  ( 4637): [3.19.140541][Line:463][xdmGetEnableLiveDemoFromCSCFeature] enable LiveDemo : false
,E/DBG_DM  ( 4637): Warning!!! [3.19.140541][Line:65][xdmInitAdpGetSIMLockState] SIM Status is not ready
,I/DBG_DM  ( 4637): [3.19.140541][Line:261][xdmInitAdpEXTInit] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 4637): [3.19.140541][Line:271][xdmAgentTaskHandler] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 4637): [3.19.140541][Line:769][xdmUIEvent] XUI_DL_UPDATE_START
,I/DBG_DM  ( 4637): [3.19.140541][Line:369][handleMessage] event ->214
,I/DBG_DM  ( 4637): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 4637): [3.19.140541][Line:2008][xdmCallUiFotaInstall] 
,I/DBG_DM  ( 4637): [3.19.140541][Line:1854][xdmAgentCheckResumeNoti] 
,I/DBG_DM  ( 4637): [3.19.140541][Line:318][xdmBroadcastGetIsSavedNfcMode] m_IsSavedNfcMode : false
,I/DBG_DM  ( 4637): [3.19.140541][Line:546][xuiAdpGetUpdateReport] Get bUpdateReport = false
,I/SQLiteSecureOpenHelper( 4133): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4133): getDatabaseLocked(b,b,pwd)...
,I/DBG_DM  ( 4637): [3.19.140541][Line:729][xdmUIEvent] XUI_DL_UPDATE_CONFIRM
,W/ContextImpl( 4637): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 com.wssyncmldm.XDMService.xdmCallUiFotaInstall:2023 com.wssyncmldm.XDMService$1.handleMessage:372 android.os.Handler.dispatchMessage:102 
,D/Sensors ( 2420): LightSensor enable = 0
,D/Sensors ( 2420): LightSensor enableSensor = 0
,D/LightsService( 2420): [SvcLED]  onSensorChanged::light value = 10
,D/SensorManager( 2420): unregisterListener ::   
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/dalvikvm( 2847): GC_CONCURRENT freed 1880K, 24% free 10844K/14164K, paused 5ms+6ms, total 100ms
,I/DBG_DM  ( 4637): [3.19.140541][Line:890][xdmUnRegisterBatteryReceiver] 
,E/DBG_DM  ( 4637): Warning!!! [3.19.140541][Line:898][xdmUnRegisterBatteryReceiver] didn't register
,I/DBG_DM  ( 4637): [3.19.140541][Line:1320][xdmCheckIdleScreen] Idle Screen : false
,E/DBG_DM  ( 4637): Warning!!! [3.19.140541][Line:899][xdmUnRegisterBatteryReceiver] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.XDMService$3@423c1838
,I/SELinux ( 7121): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7121):  
,I/SELinux ( 7121): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7121):  
I/SELinux ( 7121):  
,I/SELinux ( 7121): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7121): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7121): >>>>> Normal User
,E/dalvikvm( 7121): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7121): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7121): in addTimaSignatureService
,I/DBG_DM  ( 4637): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,D/TimaKeyStoreProvider( 7121): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7121): Added TimaKesytore provider
,I/dalvikvm( 4637): Total arena pages for JIT: 18
,I/DBG_DM  ( 4637): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2420): sendNotification(1) - 4
,I/dalvikvm( 3307): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 3307): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 3307): VFY: replacing opcode 0x6e at 0x003d
,W/ResourceType( 2580): Attempt to retrieve bag 0x01030068 which is invalid or in a cycle.
,W/ResourceType( 2580): Attempt to retrieve bag 0x01030067 which is invalid or in a cycle.
,D/ProgressBar( 2580): setProgressDrawable drawableHeight = 12
,D/DelayedSyncController( 6020): Delaying sync.
,D/ProgressBar( 2580): setProgressDrawable drawableHeight = 12
,D/PhoneStatusBar( 2580): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@422b8288
,D/dalvikvm( 7121): GC_CONCURRENT freed 2987K, 32% free 9575K/13940K, paused 41ms+1ms, total 119ms
,D/dalvikvm( 7121): WAIT_FOR_CONCURRENT_GC blocked 99ms
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection...
,E/Auth.Api.Credentials( 3307): [CredentialSyncAdapter] Unknown sync event.
,I/SELinux ( 7144): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7144):  
,I/SELinux ( 7144): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7144):  
I/SELinux ( 7144):  
,I/SELinux ( 7144): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7144): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7144): >>>>> Normal User
,E/dalvikvm( 7144): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7144): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7144): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7144): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7144): Added TimaKesytore provider
,I/PhenotypeConfigurator( 2735): Scheduling Phenotype for one-off execution 5919 seconds from now (1449751220812)
,D/dalvikvm( 7144): GC_CONCURRENT freed 2997K, 32% free 9568K/13940K, paused 2ms+7ms, total 39ms
,D/dalvikvm( 7144): WAIT_FOR_CONCURRENT_GC blocked 36ms
,D/KLMS-2.3.201 : ( 7144): KLMSValidator() : checkQATesting()
,D/GetConfigurationSnapshotOperation( 2735): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/KLMS-2.3.201 : ( 7144): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449751220921
,I/KLMS-2.3.201 : ( 7144): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/PhenotypeFlagCommitter( 2735): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/SELinux ( 7162): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7162):  
D/PackageManager( 2420): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/LocationTagReadyService( 3466): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
,I/System.out( 7121): Thread-612(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/GallerySearchProvider( 3593): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,W/dalvikvm( 2735): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2735): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2735): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 2735): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2735): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2735): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2735): Using platform SSLCertificateSocketFactory
I/SELinux ( 7162): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7162):  
I/SELinux ( 7162):  
,I/SELinux ( 7162): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7162): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7162): >>>>> Normal User
,E/dalvikvm( 7162): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7162): [DEBUG] seapp_context_lookup: seinfoCategory = release,
,I/System.out( 7121): Thread-612(ApacheHTTPLog):isShipBuild true
,I/System.out( 7121): Thread-612(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false,
,D/TimaKeyStoreProvider( 7162): in addTimaSignatureService,
,D/dalvikvm( 2720): GC_EXPLICIT freed 313K, 34% free 9965K/14884K, paused 4ms+5ms, total 58ms,
,I/SELinux ( 7174): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7174):  
,D/TimaKeyStoreProvider( 7162): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7162): Added TimaKesytore provider,
,I/SELinux ( 7174): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7174):  
I/SELinux ( 7174):  
I/SELinux ( 7174): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7174): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
E/dalvikvm( 7174): >>>>> Normal User
,E/dalvikvm( 7174): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ],
,E/SELinux ( 7174): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,D/TimaKeyStoreProvider( 7174): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7174): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7174): Added TimaKesytore provider,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/LocationManagerService( 2420): getLastLocation: Request[POWER_NONE passive fastest=0 num=1],
,D/dalvikvm( 7162): GC_CONCURRENT freed 3001K, 32% free 9568K/13944K, paused 4ms+1ms, total 58ms,
,D/dalvikvm( 7162): WAIT_FOR_CONCURRENT_GC blocked 15ms,
,D/dalvikvm( 7174): GC_CONCURRENT freed 3011K, 32% free 9562K/13944K, paused 2ms+3ms, total 26ms,
,D/dalvikvm( 7174): WAIT_FOR_CONCURRENT_GC blocked 24ms,
,D/SO_AGENT( 7162): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE,
,I/SO_AGENT( 7162): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...,
,V/KVNProvider( 7174): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query,
,V/KVNProvider( 7174): getFindoCursor query string : ,
,I/SA      ( 6318): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ],
,V/KVNProvider( 7174): getTagSearchCursor() tagSearchCursor count : 0,
,I/SA      ( 6318): [BDLM] already registered in spp,
,I/SA      ( 6318): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ],
,I/SA      ( 6318): [OR] == ACTION_CONNECTIVITY_CHANGE ==,
,I/SA      ( 6318): [SLFUCHKMGR] constructor called
,I/System.out( 7121): AsyncTask #1 calls detatch()
,D/dalvikvm( 6260): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x422a35e8, skipping init
,I/GAV2    ( 6969): Thread[GAThread,5,main]: connecting to Analytics service
,W/ContextImpl( 6969): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:529 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
I/SA      ( 6318): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6318): [OR] == isSIMCardReady false ==
,I/SA      ( 6318): [SCU] == networkStateCheck == true
,I/GAV2    ( 6969): Thread[GAThread,5,main]: connect: bindService returned true for Intent { act=com.google.android.gms.analytics.service.START (has extras) }
I/SA      ( 6318): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6318): isChinaCountryCode : false
,I/SA      ( 6318): [OR] == networkStateCheck true ==
,D/GAV2    ( 6969): Thread[main,5,main]: service connected, binder: android.os.BinderProxy@4251c9a0
,I/SA      ( 6318): [OR] GetMyCountryZoneTask
,D/GAV2    ( 6969): Thread[main,5,main]: bound to service
,I/GAV2    ( 6969): Thread[main,5,main]: Connected to service
,I/SA      ( 6318): [OR] onReceive END
,I/SA      ( 6318): [SRS] prepareGetMyCountryZone
,I/ActivityManager( 2420): Killing 5314:com.google.android.talk/u0a109 (adj 15): empty #43
I/SecureStorage( 6260): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 1970): [INFO]: SPID(0x00000004)Credentials: uid 1000, gid 1000, pid 6260
I/SecureStorage( 1970): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
I/GAV2    ( 6969): Thread[GAThread,5,main]: No campaign data found.
I/SA      ( 6318): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6318): [SSP] query invoked
,I/GAV2    ( 6969): Thread[GAThread,5,main]: putHit called
,I/GAV2    ( 6969): Thread[GAThread,5,main]: Sending hit to service
D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 6081): Other Intent
,W/System.err( 7121): com.sec.android.fota.osp.http.RestClientException
,W/System.err( 7121): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7121): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7121): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7121): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7121): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 7121): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7121): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 7121): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7121): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 7121): Caused by: java.lang.NullPointerException
,W/System.err( 7121): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7121): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7121): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7121): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7121): 	... 8 more
,I/SELinux ( 7199): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7199):  
,I/ActivityManager( 2420): Killing 5824:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/SELinux ( 7199): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7199):  
I/SELinux ( 7199):  
,I/SELinux ( 7199): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7199): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7199): >>>>> Normal User
,E/dalvikvm( 7199): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7199): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 6318): [TPMU] GetMccFromDB : null
I/SA      ( 6318): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6318): [TPM] isNoProxy(default) : true
,D/TimaKeyStoreProvider( 7199): in addTimaSignatureService
,I/dalvikvm( 2735): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 2735): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2735): VFY: replacing opcode 0x6e at 0x003d
,I/SA      ( 6318): [RC New] Execute method=[GET] start
,D/TimaKeyStoreProvider( 7199): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7199): Added TimaKesytore provider
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection...
,D/dalvikvm( 7199): GC_CONCURRENT freed 3009K, 32% free 9566K/13948K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 7199): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/com.samsung.app( 7199): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7199): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7199): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7199): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7199): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7199): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5260): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/dalvikvm( 2420): GC_EXPLICIT freed 2142K, 56% free 24491K/55324K, paused 15ms+21ms, total 231ms
,D/com.samsung.app( 7199): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5260): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7199): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5260): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7199): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7199): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2420): Killing 5769:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7211): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7211):  
,I/SELinux ( 7211): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7211):  
I/SELinux ( 7211):  
,I/SELinux ( 7211): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/System.out( 2735): Thread-124(HTTPLog):isShipBuild true
,I/System.out( 2735): Thread-124(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
E/SELinux ( 7211): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7211): >>>>> Normal User
,E/dalvikvm( 7211): >>>>> com.samsung.android.internal.headlines [ userId:0 | appId:10110 ]
,E/SELinux ( 7211): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7211): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7211): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7211): Added TimaKesytore provider
,D/dalvikvm( 7211): GC_CONCURRENT freed 2989K, 32% free 9579K/13944K, paused 3ms+2ms, total 21ms
,D/dalvikvm( 7211): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/System.out( 6318): Thread-572(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/HeadlinesChannelApplication( 7211): [onCreate]
,D/Headlines( 7211): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 7211): getCountryCode(): countryCode = PL
I/System.out( 6318): Thread-572(ApacheHTTPLog):isShipBuild true
,I/System.out( 6318): Thread-572(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/Headlines( 7211): Breath.onCreate
,D/HeadlinesCardManager( 7211): HeadlinesCardManager : constructor
,E/HeadlinesCardManager( 7211): HeadlinesCardManager : ctor = image_cache size is 42MB
,D/SA Version( 7211): CardProvider Library : 13
I/SELinux ( 7226): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7226):  
,I/SELinux ( 7226): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7226):  
I/SELinux ( 7226):  
,I/SELinux ( 7226): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7226): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 7226): >>>>> Normal User
,E/dalvikvm( 7226): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7226): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/MagazineService::CardProviderContentProvider( 6362): insertProvider: provider already exists.: com.samsung.android.app.headlines
,D/MagazineService::CardProviderContentProvider( 6362): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/TimaKeyStoreProvider( 7226): in addTimaSignatureService
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 7211): registerCardProvider: provider already exists.
,D/TimaKeyStoreProvider( 7226): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7226): Added TimaKesytore provider
,I/Headlines( 7211): HeadlinesDataCenter ctor
,I/Headlines( 7211): HeadlinesDataCenter. mLocale = en_US
,D/HeadlinesChannelUtil( 7211): getCountryCode(): countryCode = PL
,D/HeadlinesCardManager( 7211): HeadlinesCardManager : constructor welcome :YES
,D/btif_config_util( 5063): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/Headlines( 7211): Breath timer started. interval : 30000
,V/AlarmManager( 2420): waitForAlarm result :8
D/Headlines( 7211): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 7211): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 7211): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 7211): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 7211): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 7211): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 7211): requestUpdateNewsWelcomeCard !!! no welcome card
,D/dalvikvm( 7226): GC_CONCURRENT freed 2986K, 32% free 9581K/13944K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7226): WAIT_FOR_CONCURRENT_GC blocked 17ms
,V/WebViewChromium( 7226): Binding Chromium to the background looper Looper (main, tid 1) {422abf88}
,I/chromium( 7226): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7226): Initializing chromium process, renderers=0
,W/chromium( 7226): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7226): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7226): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7226): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7226): Mali API Version : 401
,I/Mali    ( 7226): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,E/WifiStateMachine( 2420): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,W/GAV2    ( 7226): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,I/SecureStorage( 1970): [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
I/SecureStorage( 1970): [INFO]: SPID(0x00000004)PID: 6260, TID: 6285
,W/ContextImpl( 7226): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/SecureStorage( 6260): [INFO]: SPID(0x00000000)Processing data has been completed
,I/NSApplication( 7226): Starting up...
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/SurfaceFlinger( 1921): id=23 Removed Uoast (10/11)
,I/ActivityManager( 2420): Killing 5800:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,I/SurfaceFlinger( 1921): id=23 Removed Uoast (-2/11)
D/PowerManagerService( 2420): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2420) eventTime = 324943
D/PowerManagerService( 2420): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2420 (0x0)
D/PowerManagerService( 2420): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2420, ws=WorkSource{1000}) (elapsedTime=3446)
,I/ImageResourceManager( 5689): ImageResourceManager: uninitalized
,I/SurfaceFlinger( 1921): id=24 createSurf (1x1),1 flag=4, Uoast
,I/iu.Environment( 5689): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/PowerManagerService( 2420): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2420
I/ActivityManager( 2420): Killing 6067:com.android.defcontainer/u0a6 (adj 15): empty #43
,E/ActivityThread( 3307): Failed to find provider info for com.android.contacts.metadata
D/QuickConnect[1.1][2] ( 5037): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5037): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 5037): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422aebb0
,I/SELinux ( 7268): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7268):  
,D/dalvikvm( 5689): GC_FOR_ALLOC freed 149K, 30% free 9826K/13944K, paused 48ms, total 49ms
,I/dalvikvm-heap( 5689): Grow heap (frag case) to 12.969MB for 2129936-byte allocation
,I/SELinux ( 7268): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7268):  
I/SELinux ( 7268):  
,I/SELinux ( 7268): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7268): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7268): >>>>> Normal User
,E/dalvikvm( 7268): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7268): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7268): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7268): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7268): Added TimaKesytore provider
,D/dalvikvm( 5689): GC_CONCURRENT freed 4K, 26% free 11902K/16028K, paused 6ms+1ms, total 44ms
D/dalvikvm( 5689): WAIT_FOR_CONCURRENT_GC blocked 38ms
D/dalvikvm( 5689): WAIT_FOR_CONCURRENT_GC blocked 37ms
,D/dalvikvm( 5689): WAIT_FOR_CONCURRENT_GC blocked 38ms
,I/iu.UploadsManager( 5689): num queued entries: 0
,D/dalvikvm( 5689): WAIT_FOR_CONCURRENT_GC blocked 42ms
,I/iu.UploadsManager( 5689): num updated entries: 0
,I/iu.SyncManager( 5689): NEXT; no task
,D/dalvikvm( 2735): GC_CONCURRENT freed 1615K, 21% free 11867K/14968K, paused 10ms+6ms, total 63ms
,D/dalvikvm( 7268): GC_CONCURRENT freed 2989K, 32% free 9584K/13948K, paused 3ms+1ms, total 26ms
,D/dalvikvm( 7268): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/SA      ( 6318): [RC New] [v2liruge] api execute + 1411
,I/SA      ( 6318): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6318): AsyncTask #1 calls detatch()
,I/SA      ( 6318): [TPMU] getNetworkMcc : 
,I/SA      ( 6318): [SCU] saveMccToPreferece Start
I/SA      ( 6318): [SCU] RegionMCC : 260,
,I/SA      ( 6318): [SSP] query invoked,
,I/SA      ( 6318): [TPMU] GetMccFromDB : null,
I/SA      ( 6318): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6318): [SCU] saveMccToPreferece End,
,I/SA      ( 6318): [RC New] executeRequest [v2liruge] end. 1461,
,I/SA      ( 6318): [RC New] Execute end,
I/SA      ( 6318): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6318): [OR] GetMyCountryZoneTask Success,
,I/ActivityManager( 2420): Killing 5935:com.google.android.partnersetup/u0a14 (adj 15): empty #43,
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId,
,D/NtpTrustedTime( 2420): getCachedNtpTime() cache hit,
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId,
I/dalvikvm( 6260): Total arena pages for JIT: 11
,I/dalvikvm( 6260): Total arena pages for JIT: 12
I/dalvikvm( 6260): Total arena pages for JIT: 13
,I/dalvikvm( 6260): Total arena pages for JIT: 14
I/dalvikvm( 6260): Total arena pages for JIT: 15
,I/dalvikvm( 6260): Total arena pages for JIT: 16
,I/dalvikvm( 6260): Total arena pages for JIT: 17
,I/SELinux ( 7287): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7287):  
,D/SyncManager( 2420): failed sync operation 
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/SyncManager( 2420): not retrying sync operation because the error is a hard error: 
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,I/SELinux ( 7287): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7287):  
I/SELinux ( 7287):  
,I/SELinux ( 7287): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7287): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7287): >>>>> Normal User
,E/dalvikvm( 7287): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7287): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 7293): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7293):  
,I/ActivityManager( 2420): Killing 6124:com.samsung.groupcast/u0a15 (adj 15): empty #43
,W/ActivityManager( 2420): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 13% free 9505K/10924K, paused 2ms+3ms, total 35ms
I/SELinux ( 7293): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7293):  
I/SELinux ( 7293):  
,I/SELinux ( 7293): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7293): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7293): >>>>> Normal User
,E/dalvikvm( 7293): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
D/TimaKeyStoreProvider( 7287): in addTimaSignatureService
,E/SELinux ( 7293): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7293): in addTimaSignatureService,
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9505K/10924K, paused 2ms+3ms, total 25ms,
,D/TimaKeyStoreProvider( 7287): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7287): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 7293): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7293): Added TimaKesytore provider
,I/ActivityManager( 2420): Killing 6138:com.android.musicfx/u0a24 (adj 15): empty #43
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9505K/10924K, paused 2ms+3ms, total 25ms
,D/dalvikvm( 7287): GC_CONCURRENT freed 3010K, 32% free 9557K/13940K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 7287): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/BadgeProvider( 7287): onCreate
,D/BadgeProvider( 7287): DatabaseHelper
,D/dalvikvm( 7293): GC_CONCURRENT freed 2997K, 32% free 9575K/13948K, paused 13ms+1ms, total 53ms
,D/dalvikvm( 7293): WAIT_FOR_CONCURRENT_GC blocked 36ms
,D/BadgeProvider( 7287): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/SELinux ( 7313): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7313):  
,I/SELinux ( 7313): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7313):  
I/SELinux ( 7313):  
,I/SELinux ( 7313): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7313): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7313): >>>>> Normal User
,E/dalvikvm( 7313): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
,E/SELinux ( 7313): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
I/ActivityManager( 2420): Killing 6164:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,D/LocationManagerService( 2420): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/BadgeProvider( 7287): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7287): sendNotify, [notify] : null
D/BadgeProvider( 7287): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7287): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7287): update, [UpdateCount] : 1
,D/Launcher.Model( 2788): reloadBadges entered.
,D/TimaKeyStoreProvider( 7313): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7313): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7313): Added TimaKesytore provider
,D/dalvikvm( 7313): GC_CONCURRENT freed 2990K, 32% free 9579K/13940K, paused 3ms+1ms, total 26ms
,D/dalvikvm( 7313): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/dalvikvm( 7313): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 7313): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 7313): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 7313): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
,W/dalvikvm( 7313): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7313): VFY: replacing opcode 0x22 at 0x0000
,D/LocationManagerService( 2420): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/dalvikvm( 7313): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
W/dalvikvm( 7313): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 7313): VFY: replacing opcode 0x22 at 0x0037
,D/PicasaService( 3593): start picasa sync
,D/PicasaService( 3593): end picasa sync
,W/WifiP2pStateTracker( 2420): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,W/dalvikvm( 7313): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7313): Link of class 'Ldqp;' failed
,W/dalvikvm( 7313): VFY: unable to find class referenced in signature (Ldqp;)
D/ConnectivityService( 2420): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2420):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
D/ConnectivityService( 2420): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2420): updateSourceRoutes : no source routing conditions
W/dalvikvm( 7313): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7313): Link of class 'Ldqp;' failed
I/dalvikvm( 7313): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 7313): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
D/dalvikvm( 7313): VFY: replacing opcode 0x6e at 0x0000
,E/dalvikvm( 7313): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7313): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7313): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 7313): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7313): Link of class 'Ldqp;' failed
,W/dalvikvm( 7313): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7313): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7313): Link of class 'Ldqp;' failed
I/dalvikvm( 7313): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 7313): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
,D/dalvikvm( 7313): VFY: replacing opcode 0x6e at 0x0008
E/dalvikvm( 7313): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 7313): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
,D/dalvikvm( 7313): VFY: replacing opcode 0x1c at 0x0026
,D/dalvikvm( 5689): GC_FOR_ALLOC freed 16K, 26% free 11906K/16028K, paused 19ms, total 19ms
W/dalvikvm( 7313): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7313): Link of class 'Ldqp;' failed
W/dalvikvm( 7313): VFY: unable to find class referenced in signature (Ldqp;)
,W/dalvikvm( 7313): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 7313): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7313): Link of class 'Ldqp;' failed
I/dalvikvm( 7313): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 7313): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
,D/dalvikvm( 7313): VFY: replacing opcode 0x6e at 0x0003
,I/dalvikvm-heap( 5689): Grow heap (frag case) to 15.000MB for 2129936-byte allocation
W/dalvikvm( 7313): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7313): Link of class 'Lax;' failed
E/dalvikvm( 7313): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 7313): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
,D/dalvikvm( 7313): VFY: replacing opcode 0x22 at 0x0006
,W/dalvikvm( 7313): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7313): Link of class 'Laz;' failed
E/dalvikvm( 7313): Could not find class 'az', referenced from method g.a
W/dalvikvm( 7313): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
,D/dalvikvm( 7313): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 7313): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 7313): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7313): VFY: replacing opcode 0x6e at 0x0008
,I/dalvikvm( 7313): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
W/dalvikvm( 7313): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 7313): VFY: replacing opcode 0x6e at 0x000c
,I/dalvikvm( 7313): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 7313): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7313): VFY: replacing opcode 0x6e at 0x0006
,I/dalvikvm( 7313): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 7313): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
,D/dalvikvm( 7313): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 7313): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 7313): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
,D/dalvikvm( 7313): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7313): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
W/dalvikvm( 7313): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
,D/dalvikvm( 7313): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7313): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 7313): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 7313): VFY: replacing opcode 0x72 at 0x0000
,D/dalvikvm( 5689): GC_FOR_ALLOC freed 0K, 23% free 13986K/18112K, paused 17ms, total 17ms
,W/dalvikvm( 7313): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 7313): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 7313): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 7313): VFY: replacing opcode 0x23 at 0x0005
,D/dalvikvm( 5689): GC_CONCURRENT freed 7K, 23% free 13994K/18112K, paused 3ms+4ms, total 18ms
,I/dalvikvm( 7313): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
W/dalvikvm( 7313): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7313): VFY: replacing opcode 0x6e at 0x0009
,D/LocationManagerService( 2420): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 5689): GC_FOR_ALLOC freed 5K, 23% free 13998K/18112K, paused 15ms, total 15ms
,W/dalvikvm( 7313): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
W/dalvikvm( 7313): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 7313): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 7313): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
,D/dalvikvm( 7313): VFY: replacing opcode 0x1c at 0x0002
,E/dalvikvm( 7313): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 7313): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 7313): VFY: replacing opcode 0x1f at 0x000c
,D/dalvikvm( 7313): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 7313): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7313): VFY: replacing opcode 0x62 at 0x0006
,D/dalvikvm( 7313): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7313): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
,D/dalvikvm( 7313): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7313): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
,D/dalvikvm( 7313): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
,W/dalvikvm( 7313): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7313): Link of class 'Lax;' failed
,D/dalvikvm( 7313): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 7313): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7313): Link of class 'Laz;' failed
,D/dalvikvm( 7313): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 7313): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
,D/dalvikvm( 7313): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/dalvikvm( 7313): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x4229dc70
,D/dalvikvm( 7313): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x4229dc70
,D/DelayedSyncController( 6020): Delaying sync.
,I/dalvikvm( 7313): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
W/dalvikvm( 7313): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 7313): VFY: replacing opcode 0x6e at 0x0076
,I/Babel_SMS( 7313): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7313): MmsConfig.loadMmsSettings
I/Babel_SMS( 7313): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/Babel_SMS( 7313): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7313): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7313): MmsConfig.loadFromResources
,E/Babel_SMS( 7313): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7313): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,W/dalvikvm( 7313): Unable to resolve superclass of Lfzc; (613)
,W/dalvikvm( 7313): Link of class 'Lfzc;' failed
E/dalvikvm( 7313): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
,W/dalvikvm( 7313): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
D/dalvikvm( 7313): VFY: replacing opcode 0x22 at 0x0033
,W/dalvikvm( 7313): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7313): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,D/dalvikvm( 7313): GC_CONCURRENT freed 1677K, 22% free 10974K/14004K, paused 2ms+4ms, total 34ms
,W/dalvikvm( 7313): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
,W/dalvikvm( 7313): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,I/dalvikvm( 7313): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 7313): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
,D/dalvikvm( 7313): VFY: replacing opcode 0x74 at 0x006d
,I/dalvikvm( 7313): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 7313): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
,D/dalvikvm( 7313): VFY: replacing opcode 0x6e at 0x0033
,I/dalvikvm( 7313): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 7313): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
,D/dalvikvm( 7313): VFY: replacing opcode 0x6e at 0x0030
,W/dalvikvm( 7313): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7313): Link of class 'Lfzc;' failed
,D/dalvikvm( 7313): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
,E/SensorService( 2420): Permission Denial : SEC Private Sensor 
,E/SensorService( 2420): Permission Denial : SEC Private Sensor 
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,W/Settings( 7313): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7313): startup - clean
,I/Babel   ( 7313): deleted: false for 0
,I/dalvikvm( 7313): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
,W/dalvikvm( 7313): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7313): VFY: replacing opcode 0x6e at 0x000d
,W/dalvikvm( 7313): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,I/dalvikvm( 7313): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 7313): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
,D/dalvikvm( 7313): VFY: replacing opcode 0x6e at 0x004e
W/dalvikvm( 7313): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7313): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7313): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 7313): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
,D/dalvikvm( 7313): VFY: replacing opcode 0x22 at 0x0071
,W/dalvikvm( 7313): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7313): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7313): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7313): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7313): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 7313): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
,D/dalvikvm( 7313): VFY: replacing opcode 0x1f at 0x0021
,W/dalvikvm( 7313): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 7313): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
,I/dalvikvm( 7313): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
,W/dalvikvm( 7313): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
,D/dalvikvm( 7313): VFY: replacing opcode 0x6e at 0x0074
,D/WaitQueueForNetworkActivate( 6459): notifyNetworkActivated
,I/vclib   ( 7313): onServiceConnected
,W/Babel   ( 7313): Attempted to change video mute state without an active call.
,W/ContextImpl( 6459): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager( 2420): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/dalvikvm( 7313): GC_CONCURRENT freed 1056K, 17% free 11964K/14392K, paused 3ms+5ms, total 54ms
,D/dalvikvm( 7313): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 7313): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6151): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6151): [hasSamungAccount] - No Samsung Account
,D/dalvikvm( 7313): GC_FOR_ALLOC freed 672K, 18% free 12592K/15352K, paused 30ms, total 48ms
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6151): failed to loading secure library
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6151): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6151): GetString : secure API is not supported!!
,I/PCWCLIENTTRACE_PushUtil( 6151): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6151): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6151): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6151): [ensureRegistration] - No Samsung account
,D/hcjo    ( 6459): AutoUpdateManager:IDLE:execute
,D/dalvikvm( 7313): GC_FOR_ALLOC freed 1793K, 24% free 12994K/16944K, paused 28ms, total 30ms
,I/System.out( 7313): Thread-653(HTTPLog):isShipBuild true
,I/System.out( 7313): Thread-653(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/dalvikvm( 6459): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
W/dalvikvm( 6459): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 6459): VFY: replacing opcode 0x6e at 0x0024
,D/InitializeManagerStateMachine( 6459): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6459): exit::IDLE
,D/InitializeManagerStateMachine( 6459): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6459): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6459): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6459): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6459): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6459): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 6459): entry::SUCCESS
,D/hcjo    ( 6459): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6459): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 6459): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6459): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6459): exit::SUCCESS
,D/InitializeManagerStateMachine( 6459): entry::IDLE
,D/dalvikvm( 3307): GC_FOR_ALLOC freed 1069K, 22% free 12392K/15752K, paused 38ms, total 38ms
,I/iu.Environment( 3307): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 3307): num queued entries: 0
,I/iu.UploadsManager( 3307): num updated entries: 0
,I/iu.SyncManager( 3307): NEXT; no task
,I/Babel   ( 7313): connection state changed from UNKNOWN to CONNECTED
,E/SPPClientService( 6479): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6479): [SystemStateMoniter] Current Time : 327382
,E/SPPClientService( 6479): [SystemStateMoniter] No Connect : false
,I/SELinux ( 7359): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7359):  
I/ActivityManager( 2420): Killing 6178:com.sec.android.app.shealth/u0a36 (adj 15): empty #43
,I/SELinux ( 7359): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7359):  
I/SELinux ( 7359):  
,I/SELinux ( 7359): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7359): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7359): >>>>> Normal User
,E/dalvikvm( 7359): >>>>> com.android.calendar [ userId:0 | appId:10144 ]
,E/SELinux ( 7359): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7359): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7359): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7359): Added TimaKesytore provider
,D/dalvikvm( 7359): GC_CONCURRENT freed 2994K, 32% free 9574K/13944K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7359): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/GCM     ( 2847): GCM config loaded
,I/ActivityManager( 2420): Killing 6196:com.sec.android.service.health/u0a16 (adj 15): empty #43
,D/BootCompletedReceiver( 2420): onReceive
,I/KLMS-2.3.201 : ( 7144): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 360, Delta = 40
,I/KLMS-2.3.201 : ( 7144): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1449751225491
,I/KLMS-2.3.201 : ( 7144): StateImplV2() : dateTimeChanged() : Thu Dec 10 13:40:25 CET 2015
D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4342, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): stay LED for fully charged
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5063): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5063): Disconnected process message: 10
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SELinux ( 7378): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7378):  
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/SELinux ( 7378): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7378):  
I/SELinux ( 7378):  
,I/SELinux ( 7378): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7378): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7378): >>>>> Normal User
,E/dalvikvm( 7378): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
,E/SELinux ( 7378): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7378): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7378): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7378): Added TimaKesytore provider
,D/dalvikvm( 7378): GC_CONCURRENT freed 2998K, 32% free 9570K/13944K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 7378): WAIT_FOR_CONCURRENT_GC blocked 18ms
,W/ContextImpl( 7378): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 

```
