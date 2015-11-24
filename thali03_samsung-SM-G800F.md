#### Test 515172835a91168_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
--------- beginning of /dev/log/main
D/AndroidRuntime( 6966): 
D/AndroidRuntime( 6966): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6966): CheckJNI is OFF
D/AndroidRuntime( 6966): setted country_code = Poland
D/AndroidRuntime( 6966): setted countryiso_code = PL
D/AndroidRuntime( 6966): setted sales_code = PLS
D/AndroidRuntime( 6966): readGMSProperty: start
D/AndroidRuntime( 6966): readGMSProperty: already setted!!
D/AndroidRuntime( 6966): readGMSProperty: end
D/AndroidRuntime( 6966): addProductProperty: start
D/dalvikvm( 6966): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6966): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6966): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6966): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6966): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6966): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6966): failed to load memtrack module: -2
D/dalvikvm( 6966): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6966): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2408): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2408): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2408  pkgName : ACTIVITY_RESUME_BOOSTER@4
I/SurfaceFlinger( 1921): id=18 createSurf (16x16),-1 flag=20004, EimLayer
W/ActivityManager( 2408): mDVFSHelper.acquire()
I/SurfaceFlinger( 1921): id=19 createSurf (16x16),-1 flag=20004, EimLayer
I/SELinux ( 6995): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6995):  
D/PointerIcon( 2408): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2408): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2408): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2408): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6966): Shutting down VM
D/dalvikvm( 6966): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 6995): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6995):  
I/SELinux ( 6995):  
I/SELinux ( 6995): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6995): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6995): >>>>> Normal User
E/dalvikvm( 6995): >>>>> com.test.thalitest [ userId:0 | appId:10476 ]
E/SELinux ( 6995): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 6995): in addTimaSignatureService
D/TimaKeyStoreProvider( 6995): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6995): Added TimaKesytore provider
V/WindowManager( 2408): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SQLiteSecureOpenHelper( 4119): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4119): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=9 Removed Mauncher (8/10)
I/SurfaceFlinger( 1921): id=9 Removed Mauncher (-2/10)
D/Launcher( 2777): onTrimMemory. Level: 20
D/dalvikvm( 6995): GC_CONCURRENT freed 3014K, 30% free 9559K/13620K, paused 1ms+1ms, total 17ms
D/dalvikvm( 6995): WAIT_FOR_CONCURRENT_GC blocked 15ms
V/WebViewChromium( 6995): Binding Chromium to the background looper Looper (main, tid 1) {42259310}
I/chromium( 6995): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 6995): Initializing chromium process, renderers=0
W/chromium( 6995): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 6995): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 6995): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6995): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 6995): Mali API Version : 401
,I/Mali    ( 6995): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 6995): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 6995): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,D/dalvikvm( 6995): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 6995): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 6995): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 6995): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2582): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/StatusBarManagerService( 2408): tr p:6995,o:f
W/dalvikvm( 6995): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 6995): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 6995): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 6995): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 6995): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 6995): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 6995): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 6995): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 6995): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6995): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 6995): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 6995): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 6995): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2582): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2408): semi p:6995,o:f
,I/SurfaceFlinger( 1921): id=20 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2408): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2408): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2408): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2408): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2408): setHoveringSpenCustomIcon IconType is same.1
,D/STATUSBAR-StatusBarManagerService( 2408): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
I/HWUI    ( 6995): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 6995): Enabling debug mode 0
,W/AwContents( 6995): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/AwContents( 6995): nativeOnDraw failed; clearing to background color.
D/CustomFrequencyManagerService( 2408): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2408  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2408): mDVFSHelper.release()
,W/IInputConnectionWrapper( 6995): showStatusIcon on inactive InputConnection
D/CustomFrequencyManagerService( 2408): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2408  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/JsMessageQueue( 6995): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 6995): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4225a098
,D/dalvikvm( 6995): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4225a098
D/jxcore_app_log( 6995): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2030549048
,D/JX-Cordova( 6995): jxcore cordova android initializing
I/dalvikvm( 6995): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 6995): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 6995): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 6995): GC_CONCURRENT freed 1294K, 18% free 11337K/13676K, paused 3ms+2ms, total 25ms
D/dalvikvm( 6995): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 6995): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/CustomFrequencyManagerService( 2408): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2408  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 6995): GC_CONCURRENT freed 2028K, 18% free 14832K/17916K, paused 3ms+3ms, total 52ms
D/dalvikvm( 6995): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 6995): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/PowerManagerService( 2408): [PWL] Off : 140s ago
,D/dalvikvm( 6995): GC_FOR_ALLOC freed 5230K, 29% free 16127K/22652K, paused 41ms, total 41ms
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): stay LED for fully charged
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 6995): GC_CONCURRENT freed 6729K, 31% free 17571K/25364K, paused 3ms+16ms, total 92ms
,D/dalvikvm( 6995): WAIT_FOR_CONCURRENT_GC blocked 51ms
,D/dalvikvm( 6995): GC_FOR_ALLOC freed 1575K, 32% free 17274K/25364K, paused 59ms, total 60ms
,E/Watchdog( 2408): !@Sync 9
I/dalvikvm-heap( 6995): Grow heap (frag case) to 21.479MB for 3767174-byte allocation
,D/dalvikvm( 6995): GC_FOR_ALLOC freed 2473K, 37% free 18479K/29044K, paused 55ms, total 55ms
,W/jxcore-log( 6995): Initializing JXcore engine
,W/jxcore-log( 6995): JXcore engine is ready
,W/jxcore-log( 6995): Starting JXcore engine
,W/jxcore-log( 6995): Platform android
W/jxcore-log( 6995): 
,W/jxcore-log( 6995): Process ARCH arm
W/jxcore-log( 6995): 
,I/jxcore-log( 6995): JXcore Cordova bridge is ready!
I/jxcore-log( 6995): 
,W/jxcore-log( 6995): JXcore engine is started
,I/chromium( 6995): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6995): Turning radios to true
I/jxcore-log( 6995): 
,W/ActivityManager( 2408): Permission Denial: getCurrentUser() from pid=6995, uid=10476 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 2408): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 2408): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6995, uid=10476 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 2408): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/BluetoothManagerService( 2408): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:620)
W/BluetoothManagerService( 2408): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService( 2408): 	at android.os.Binder.execTransact(Binder.java:404)
W/BluetoothManagerService( 2408): 	at dalvik.system.NativeStart.run(Native Method)
E/DevicePolicyManagerService( 2408): getAllowBluetoothMode - value retunrs : 2
,D/BluetoothManagerService( 2408): foregroundUser: 0
,I/jxcore-log( 6995): toggleBluetooth - 
I/jxcore-log( 6995): 
,E/BluetoothManagerService( 2408): Package is exist.
,I/WifiManager( 6995): packageName : com.test.thalitest
,I/WifiManager( 6995): setWifiEnabled : true
,I/WifiService( 2408): setWifiEnabled: true pid=6995, uid=10476
D/BluetoothAdapterState( 5048): CURRENT_STATE=OFF, MSG = USER_TURN_ON
,I/BluetoothAdapterState( 5048): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 5048): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5048): updateAdapterState state is 11
,D/BluetoothAdapterService( 5048): Broadcasting updateAdapterState() to 1 receivers.
,W/ActivityManager( 2408): Permission Denial: getCurrentUser() from pid=6995, uid=10476 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2408): Failed getting userId using ActivityManagerNative
W/WifiService( 2408): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6995, uid=10476 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2408): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2408): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2408): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2408): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2408): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2408): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapterService( 5048): Autoconnection is available 
D/BluetoothAdapterService( 5048): updateAdapterState prevState = 10newState = 11
D/BtConfig.SecureMode( 5048): isSecureModeOn:false
,D/BtSettings.ProfileConfig( 5048): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/InputMethodManagerService( 2408): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 2408): [BT Setting State] State =11
D/PhoneApp( 2752): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 11
I/SamsungIME( 2984): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
W/BluetoothAdapterService( 5048): isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
D/BtSettings.ProfileConfig( 5048): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
I/WifiService( 2408): disconnect: pid=6995, uid=10476
I/QuickConnect[1.1][2] ( 5022): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_ON
I/jxcore-log( 6995): toggleWiFi
I/jxcore-log( 6995): 
E/WifiHW  ( 2408): ##################### set firmware type 0 #####################
W/BluetoothAdapterService( 5048): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5048): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
I/WifiHW  ( 1916): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
E/WifiHW  ( 1916): Cannot open "/data/.cid.info": No such file or directory
I/WifiHW  ( 1916): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
E/WifiHW  ( 1916): TEMP_FAILURE_RETRY complete
D/SoftapController( 1916): Softap fwReload - Ok
W/BluetoothAdapterService( 5048): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5048): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 5048): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5048): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 5048): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5048): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 5048): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5048): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 5048): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5048): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5048): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5048): Unable to stop service com.android.bluetooth.gatt.GattService. Invalid state: 12
W/BluetoothAdapterService( 5048): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5048): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5048): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/CommandListener( 1916): Setting iface cfg
,D/CommandListener( 1916): Trying to bring down wlan0
,D/BluetoothNotiBroadcastReceiver( 5508): onReceive
,W/BluetoothAdapterService( 5048): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService,
,D/BtSettings.ProfileConfig( 5048): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5048): Not skipping com.android.bluetooth.a2dp.A2dpService,
D/WifiHW  ( 2408): Skip the update_ctrl_interface
,D/WifiHW  ( 2408): Skip the update_ctrl_interface,
,E/WifiHW  ( 2408): supplicant_name : p2p_supplicant,
,I/SELinux ( 7043): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7043):  
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/HeadsetService( 5048): Received start request. Starting profile...
D/WifiMonitor( 2408): startMonitoring(wlan0) with mConnected = false
,W/BluetoothAdapterService( 5048): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5048): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5048): Not skipping com.android.bluetooth.hid.HidService
I/BluetoothHeadsetServiceJni( 5048): classInitNative: succeeds
D/HeadsetStateMachine( 5048): Version 1.5
,D/HeadsetStateMachine( 5048): make
,D/QuickConnect[1.1][2] ( 5022): HeadsetProfile.onServiceConnected - Bluetooth service connected
I/SELinux ( 7043): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7043):  
I/SELinux ( 7043):  
,I/SELinux ( 7043): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/wpa_supplicant( 7045): wpa_supplicant v2.1-devel-4.4.22014-07-16/12:43:14
E/SELinux ( 7043): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7043): >>>>> Normal User
,E/dalvikvm( 7043): >>>>> pl.k2.droidoaudioteka [ userId:0 | appId:10066 ]
W/BluetoothAdapterService( 5048): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 5048): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5048): Not skipping com.android.bluetooth.hdp.HealthService
I/wpa_supplicant( 7045): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 7045): Successfully initialized wpa_supplicant
I/wpa_supplicant( 7045): >>>>> Not GET KEY, IV <<<<<
,E/SELinux ( 7043): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/wpa_supplicant( 7045): getIMSI cannot open file
,E/wpa_supplicant( 7045): Interworking config: - SIM READ ERROR
,E/HeadsetStateMachine( 5048): # of Max HF connection is 2
W/BluetoothAdapterService( 5048): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5048): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5048): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5048): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 5048): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5048): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5048): check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 5048): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5048): Not skipping com.broadcom.bt.service.sap.SapService,
,I/BluetoothAdapterState( 5048): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false,
,I/bluedroid( 5048): get_profile_interface handsfree,
,I/dalvikvm( 7043): Enabling JNI app bug workarounds for target SDK version 7...,
,D/BluetoothAtMessage( 5048): createCMTIContentObservers
,D/HeadsetStateMachine( 5048): Enter Disconnected: -2
,E/HeadsetStateMachine( 5048): set to mRemoteBrsf = 0
,D/TimaKeyStoreProvider( 7043): in addTimaSignatureService
D/HeadsetStateMachine( 5048): map size, before remove : 0
D/HeadsetStateMachine( 5048): map size, after remove: 0
,D/HeadsetStateMachine( 5048): mNextConnectingDevice : null
,D/BluetoothA2dp( 5022): Proxy object connected
,D/TimaKeyStoreProvider( 7043): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7043): Added TimaKesytore provider
,D/BluetoothA2dp( 2408): Proxy object connected
,D/BluetoothA2dp( 4119): Proxy object connected
,D/QuickConnect[1.1][2] ( 5022): A2dpProfile.onServiceConnected - Bluetooth service connected
,D/A2dpService( 5048): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 5048): classInitNative: succeeds
,D/A2dpStateMachine( 5048): make
,I/bluedroid( 5048): get_profile_interface a2dp
,I/GKI_LINUX( 5048): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,I/BluetoothAvrcpServiceJni( 5048): classInitNative: succeeds
,D/A2dpStateMachine( 5048): Enter Disconnected: -2
,I/bluedroid( 5048): get_profile_interface avrcp
,D/MediaFocusControl( 2408): >>> registerRemoteControlDisplay
,I/BluetoothHidServiceJni( 5048): classInitNative: succeeds
,D/BluetoothInputDevice( 5022): Proxy object connected
D/HidService( 5048): Received start request. Starting profile...
I/bluedroid( 5048): get_profile_interface hidhost
,D/HidService( 5048): setHidService(): set to: null
,I/BluetoothHealthServiceJni( 5048): classInitNative: succeeds
,D/QuickConnect[1.1][2] ( 5022): HidProfile.onServiceConnected - Bluetooth service connected
,D/HealthService( 5048): Received start request. Starting profile...
,I/bluedroid( 5048): get_profile_interface health
,D/AmoledAdjustTimer( 2408): prevTemp = 304, currTemp = 303, prevStep = 4, currStep = 4
I/wpa_supplicant( 7045): >>>>> Not GET KEY, IV <<<<<
I/BluetoothPanServiceJni( 5048): classInitNative(L105): succeeds
E/wpa_supplicant( 7045): getIMSI cannot open file
E/wpa_supplicant( 7045): Interworking config: - SIM READ ERROR
I/wpa_supplicant( 7045): >>>>> Not GET KEY, IV <<<<<
I/wpa_supplicant( 7045): rfkill: Cannot open RFKILL control device
D/BluetoothPan( 2408): BluetoothPAN Proxy object connected
D/PanService( 5048): Received start request. Starting profile...
D/BluetoothPanServiceJni( 5048): initializeNative(L110): pan
I/bluedroid( 5048): get_profile_interface pan
D/BluetoothTethering( 2408): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothMapService( 5048): Received start request. Starting profile...
,W/BluetoothMapMasInstance( 5048): mAccount : null
D/dalvikvm( 7043): GC_CONCURRENT freed 3000K, 30% free 9570K/13620K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 7043): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/BluetoothSAPServiceJni( 5048): classInitNative(L204): succeeds
,D/SapService( 5048): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 5048): initializeNative(L209): sap
,I/bluedroid( 5048): get_profile_interface sap
,D/HeadsetStateMachine( 5048): Try to query the phonestate on bind
D/BluetoothPhoneService( 2752): handleMessage: 4
,V/BluetoothPhoneService( 2752): Call state Converted2: IDLE/IDLE -> 6
,D/HeadsetStateMachine( 5048): Proxy object connected
,W/BluetoothHeadset( 2752): Proxy not attached to service
,D/HeadsetPhoneState( 5048): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState( 5048): sendDeviceDataStateChanged
D/HeadsetStateMachine( 5048): Disconnected process message: 11
D/HeadsetPhoneState( 5048): Signal level : previous=0 curr=0
D/HeadsetStateMachine( 5048): Disconnected process message: 20
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
D/HeadsetPhoneState( 5048): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService( 5048): Profile still not running:com.broadcom.bt.service.sap.SapService
D/HeadsetStateMachine( 5048): Disconnected process message: 11
D/BluetoothAdapterService( 5048): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5048): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5048): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5048): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5048): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterState( 5048): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 5048): enable
,D/GKI_LINUX( 5048): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,E/bt-btif ( 5048): Calling BTA_HhEnable
,E/bt-btif ( 5048): btif_storage_get_adapter_property service_mask:0x160040
E/BluetoothServiceJni( 5048): populateRssiValuesNative
I/bluedroid( 5048): getModelRssiValues
,E/BluetoothServiceJni( 5048): model_rssi_values_callback: low = -75, mid = -65, high = 127
,E/BluetoothRemoteDevices( 5048): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BtConfig.SecureMode( 5048): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5048): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 241
,E/BluetoothRemoteDevices( 5048): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 10
,D/BtConfig.SecureMode( 5048): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5048): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 241
,W/System.err( 7043): java.io.FileNotFoundException: /system/etc/vold.fstab: open failed: ENOENT (No such file or directory)
,E/BluetoothRemoteDevices( 5048): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,D/BtConfig.SecureMode( 5048): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5048): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 241
W/System.err( 7043): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 7043): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 7043): 	at java.util.Scanner.<init>(Scanner.java:158)
W/System.err( 7043): 	at java.util.Scanner.<init>(Scanner.java:138)
W/System.err( 7043): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.readVoldFile(StorageOptions.java:107)
W/System.err( 7043): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.determineStorageOptions(StorageOptions.java:31)
W/System.err( 7043): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:81)
W/System.err( 7043): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:129)
,W/System.err( 7043): 	at pl.k2.droidoaudioteka.ui.AudiotekaApplication.onCreate(AudiotekaApplication.java:171)
W/System.err( 7043): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 7043): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 7043): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7043): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 7043): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7043): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 7043): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
,W/System.err( 7043): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 7043): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 7043): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 7043): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 7043): 	at dalvik.system.NativeStart.main(Native Method)
,E/BluetoothRemoteDevices( 5048): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,W/System.err( 7043): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
D/BtConfig.SecureMode( 5048): isSecureModeOn:false
W/System.err( 7043): 	at libcore.io.Posix.open(Native Method)
W/System.err( 7043): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 7043): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 7043): 	... 20 more
,E/BluetoothRemoteDevices( 5048): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 241
W/System.err( 7043): file res dir: /data/data/pl.k2.droidoaudioteka/files
,W/System.err( 7043): Excternal dir: /mnt/sdcard
,E/BluetoothRemoteDevices( 5048): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,D/BtConfig.SecureMode( 5048): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5048): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 241
,E/BluetoothRemoteDevices( 5048): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/BtConfig.SecureMode( 5048): isSecureModeOn:false
E/BluetoothRemoteDevices( 5048): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 241
E/bt-btif ( 5048): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 5048): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
E/bt-btif ( 5048): btif_sock_init: !radio_req && !rfc_init
,D/IOP_DB_BT( 5048): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 5048): db_open: db_open : handle 2010080300l, read 9734 bytes onto local cache
,D/IOP_DB_BT( 5048): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 5048): db_query: result 1
I/        ( 5048): iop_db_open: iop_db_open status 0
,I/bte_conf( 5048): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 5048): [1] primary_record=1 vendor_id=0x0075 vendor_id_source=0x0001 product_id=0x0100 version=0x0200
,I/bte_conf( 5048): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 5048): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothAdapterState( 5048): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 5048): ScanMode =  20
,D/BluetoothAdapterProperties( 5048): State =  11
,D/BtConfig.SecureMode( 5048): isSecureModeOn:false
D/BtConfig.SecureMode( 5048): isSecureModeOn:false
,D/BtConfig.SecureMode( 5048): isSecureModeOn:false
D/BtConfig.SecureMode( 5048): isSecureModeOn:false
,D/BtConfig.SecureMode( 5048): isSecureModeOn:false
D/BtConfig.SecureMode( 5048): isSecureModeOn:false
,I/BluetoothAdapterState( 5048): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterService( 5048): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5048): updateAdapterState state is 12
,D/BluetoothAdapterService( 5048): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService(1109740296)( 5048): Register RemoteMessageListener
,D/BluetoothPanServiceJni( 5048): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
D/HeadsetService( 5048): registerMessageListener
D/BluetoothAdapterService( 5048): Autoconnection is available 
D/BluetoothAdapterService( 5048): updateAdapterState prevState = 11newState = 12
,D/BluetoothAdapterService( 5048): starting service from this receiver
,D/BluetoothA2dp( 4119): onBluetoothStateChange: up=true
D/HeadsetStateMachine( 5048): Disconnected process message: 70
D/HeadsetStateMachine( 5048): processRegisterMessageListener : 2, com.android.bluetooth.btservice.RemoteDevices$1@422960e0
,D/BluetoothInputDevice( 5022): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 2408): onBluetoothStateChange: up=true
,W/ContextImpl( 5048): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.startService:506 com.android.bluetooth.btservice.AdapterService.updateAdapterState:653 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
,D/BluetoothA2dp( 5022): onBluetoothStateChange: up=true
,D/BluetoothAdapterService( 5048): initWakeLock, pfd lock: {ParcelFileDescriptor: FileDescriptor[85]}, pfd unlock: {ParcelFileDescriptor: FileDescriptor[86]}
,D/bluedroid( 5048): init_wake_lock lock_fd:85, unlock_fd:86
,I/BluetoothAdapterState( 5048): Entering On State from state = 11
W/InputMethodManagerService( 2408): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2408): [BT Setting State] State =12
,I/BluetoothPbapService( 5048): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,D/PhoneApp( 2752): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 12
,I/InputMethodManagerService( 2408): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
I/SamsungIME( 2984): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothAdapterService(1109740296)( 5048): Get Bonded Devices being called
,I/QuickConnect[1.1][2] ( 5022): BluetoothHelper.ACTION_STATE_CHANGED - STATE_ON
,D/BluetoothHeadset( 2752): registerListener : 11, listenercom.android.phone.PhoneGlobals$MessageListener@422a9450, true
,D/BluetoothHeadset( 2752): registerMessageListener
,D/HeadsetService( 5048): registerMessageListener
,D/HeadsetService( 5048): registerMessageListener
D/HeadsetStateMachine( 5048): Disconnected process message: 70
,D/HeadsetStateMachine( 5048): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@42321818
,D/PhoneApp( 2752): registerMessageListener
,D/BluetoothAdapterService(1109740296)( 5048): Get Bonded Devices being called
,V/MaBo    ( 7043): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/BluetoothPbapService( 5048): Handler(): got msg=1
,V/BluetoothPbapService( 5048): PBAP Service initSocket try: 0
,D/BluetoothMapMasInstance( 5048): set MAP SDP message type : 1
,W/BluetoothAdapter( 5048): getBluetoothService() called with no BluetoothManagerCallback
,W/BluetoothAdapter( 5048): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 5048): SOCK FLAG = 1 ***********************
D/BluetoothPbapService( 5048): PBAP Socket is BluetoothServerSocket
,E/BluetoothServiceJni( 5048): SOCK FLAG = 3 ***********************
D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:2
,I/System.out( 7043): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 7043): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 7043): moge zapisać w resDir?true
,V/MaBo    ( 7043): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
,D/BluetoothAdapterService(1109740296)( 5048): Get Bonded Devices being called
,D/GKI_LINUX( 5048): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,I/System.out( 7043): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 7043): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,W/GAV2    ( 7043): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/GAV2    ( 7043): Thread[main,5,main]: ExceptionReporter created, original handler is pl.k2.droidoaudioteka.common.helpers.AudiotekaExceptionHandler
,I/AUDIOTEKA_GA( 7043): init tracking...
,I/AUDIOTEKA_GA( 7043): app started!
,I/BugSenseHandler( 7043): Registering default exceptions handler
,D/AuthorizationBluetoothService( 2854): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/knox    ( 4962): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 4962): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 4962): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 4962): KNOXAgentService : onCreate()
,D/knox    ( 4962): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 4962): KNOXAgentService. startJobThread() start
D/knox    ( 4962): KNOXAgentService. JobThread()
,D/knox    ( 4962): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 4962): KNOXAgentService. startJobThread() wait
,I/DownloadService( 7043): Tworzenie serwisu - onCreate()
,I/DownloadService( 7043): Start serwisu - onStart()
,I/SELinux ( 7083): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7083):  
,I/BugSenseHandler( 7043): Registering default exceptions handler
D/knox    ( 4962): KNOXAgentService : onDestroy().
,D/knox    ( 4962): ModuleBase.cancelAllAlarmManageModule()
,I/PlayerService( 7043): Tworzenie serwisu - onCreate()
,I/BugSenseHandler( 7043): Flushing...
,I/BugSenseHandler( 7043): Registering default exceptions handler
,I/MediaFocusControl( 2408):   Remote Control   registerMediaButtonIntent() for PendingIntent{4291c480: PendingIntentRecord{45761690 pl.k2.droidoaudioteka broadcastIntent}}
I/SELinux ( 7083): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7083):  
I/SELinux ( 7083):  
,I/SELinux ( 7083): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7083): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7083): >>>>> Normal User
,E/dalvikvm( 7083): >>>>> tv.peel.smartremote [ userId:0 | appId:10165 ]
,E/SELinux ( 7083): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/KeyguardUpdateMonitor( 2582): handleSetGenerationId(g=2, clear=true)
,V/AUDIOTEKA_MB( 7043): new AudioManagerFocusWrapper in playerservice oncreate
,I/PlayerService( 7043): Start serwisu - onStart()
,I/BugSenseHandler( 7043): Flushing...
,I/BugSenseHandler( 7043): Registering default exceptions handler
,D/TimaKeyStoreProvider( 7083): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7083): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7083): Added TimaKesytore provider
,D/dalvikvm( 7083): GC_CONCURRENT freed 2997K, 30% free 9566K/13612K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7083): WAIT_FOR_CONCURRENT_GC blocked 13ms
,I/System.out( 7043): Thread-607(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 7043): Thread-607(ApacheHTTPLog):isShipBuild true
I/System.out( 7043): Thread-607(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 7043): pool-1-thread-2 calls detatch()
W/BugSenseHandler( 7043): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
I/System.out( 7043): pool-1-thread-1 calls detatch()
W/BugSenseHandler( 7043): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
W/SocketClient( 1916): write error (Broken pipe)
W/ContextImpl( 5508): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/LocalBluetoothProfileManager( 5508): Adding local A2DP profile
I/System.out( 7043): pool-1-thread-2 calls detatch()
W/BugSenseHandler( 7043): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
D/LocalBluetoothProfileManager( 5508): Adding local HEADSET profile
W/ContextImpl( 5508): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
E/BluetoothHeadset( 5508): BTStateChangeCB is registed
W/ContextImpl( 5508): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
E/BluetoothHeadset( 5508): BluetoothHeadset service is binded
W/ContextImpl( 5508): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/Bluetoothsap( 5508): bindService called to Bluetooth SAP Service
W/ContextImpl( 5508): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
W/ContextImpl( 5508): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
D/LocalBluetoothProfileManager( 5508): PANU : true
D/LocalBluetoothProfileManager( 5508): Adding local MAP profile
D/BluetoothMap( 5508): Create BluetoothMap proxy object
W/ContextImpl( 5508): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
W/ContextImpl( 5508): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
W/ContextImpl( 5508): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/Bluetoothsap( 5508): bindService called to Bluetooth SAP Service
D/LocalBluetoothProfileManager( 5508): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 5508): finishStartingService: stopping service
D/BluetoothNotiBroadcastReceiver( 5508): onReceive
D/BtConfig.SecureMode( 5048): isSecureModeOn:false
D/BluetoothA2dp( 5508): Proxy object connected
D/A2dpProfile( 5508): Bluetooth service connected
D/AuthorizationBluetoothService( 2854): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/AuthorizationBluetoothService( 2854): Proximity feature is not enabled.
D/HeadsetProfile( 5508): Bluetooth service connected
D/Bluetoothsap( 5508): BluetoothSAP Proxy object connected
D/SapProfile( 5508): Bluetooth service connected
D/Bluetoothsap( 5508): getConnectedDevices()
D/BluetoothInputDevice( 5508): Proxy object connected
D/HidProfile( 5508): Bluetooth service connected
D/BluetoothPan( 5508): BluetoothPAN Proxy object connected
D/PanProfile( 5508): Bluetooth service connected
W/BluetoothAdapter( 5048): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 5048): SOCK FLAG = 0 ***********************
D/GKI_LINUX( 5048): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
D/BluetoothMap( 5508): Proxy object connected
I/BtOppRfcommListener( 5048): Accept thread started.
D/MapProfile( 5508): Bluetooth service connected
D/BluetoothPbap( 5508): Proxy object connected
D/PbapServerProfile( 5508): Bluetooth service connected
D/Bluetoothsap( 5508): BluetoothSAP Proxy object connected
D/SapProfile( 5508): Bluetooth service connected
D/Bluetoothsap( 5508): getConnectedDevices()
I/ActivityManager( 2408): Killing 5710:com.sec.phone/1001 (adj 15): empty #43
D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
D/Tethering( 2408): interfaceStatusChanged wlan0, true
D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
D/Tethering( 2408): interfaceStatusChanged wlan0, true
E/Tethering( 2408): No numeric data
D/Tethering( 2408): sendTetherStateChangedBroadcast 1, 0, 0
D/NtpTrustedTime( 2408): forceRefresh() from cache miss
I/ConnectivityService( 2408): defaultVal : 1, tetherEnabledInSettings : true
D/NtpTrustedTime( 2408): forceRefresh Fail.
V/NetworkStats( 2408): performPollLocked(flags=0x1)
W/SocketClient( 1916): write error (Broken pipe)
I/wpa_supplicant( 7045): wlan0: Setting scan request: 0 sec 100000 usec
D/NtpTrustedTime( 2408): forceRefresh() from cache miss
D/NtpTrustedTime( 2408): forceRefresh Fail.
V/NetworkStats( 2408): performPollLocked() took 13ms
D/GKI_LINUX( 5048): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
I/wpa_supplicant( 7045): >>>>> Not GET KEY, IV <<<<<
I/wpa_supplicant( 7045): >>>>> Not GET KEY, IV <<<<<
I/wpa_supplicant( 7045): rfkill: Cannot open RFKILL control device
D/Tethering( 2408): interfaceLinkStateChanged p2p0, true
D/Tethering( 2408): interfaceStatusChanged p2p0, true
D/Tethering( 2408): interfaceLinkStateChanged p2p0, true
D/Tethering( 2408): interfaceStatusChanged p2p0, true
I/wpa_supplicant( 7045): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
I/wpa_supplicant( 7045): P2P: initialized channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
I/wpa_supplicant( 7045): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant( 7045): Skip scan - bUseNetwork false
D/WifiStateMachine( 2408): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
D/WifiNative( 2408): callSECApiString - ID [21]
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
I/wpa_supplicant( 7045): HOTSPOT20_ENABLE called
I/wpa_supplicant( 7045): wlan0: HS20_DISABLED_COMPLETE normal
D/WifiNative( 2408): callSECApiInt - ID [65]
I/knox    ( 4962): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 4962): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/knox    ( 4962): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 4962): KNOXAgentService : onCreate()
D/knox    ( 4962): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 4962): KNOXAgentService. startJobThread() start
D/knox    ( 4962): KNOXAgentService. JobThread()
D/knox    ( 4962): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 4962): KNOXAgentService. startJobThread() wait
D/knox    ( 4962): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
D/knox    ( 4962): KNOXAgentService : onDestroy().
D/knox    ( 4962): ModuleBase.cancelAllAlarmManageModule()
E/WifiConfigStore( 2408): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative( 2408): callSECApiBoolean - ID [13]
I/wpa_supplicant( 7045): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 7045): reset timer : RESET_TIMER 0
I/wpa_supplicant( 7045): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 7045): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 7045): First Scan Start
W/Settings( 5299): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 7045): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine( 2408): Set the Nv default ccode
D/WifiStateMachine( 2408): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
E/WifiStateMachine( 2408): HS20_DISABLED_COMPLETEnormal
D/WifiP2pService( 2408): P2pDisabledState{ what=131203 }
D/CommandListener( 1916): Setting iface cfg
D/CommandListener( 1916): Trying to bring up p2p0
I/wpa_supplicant( 7045): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
D/WifiMonitor( 2408): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 2408): P2pEnablingState
D/WifiP2pService( 2408): P2pEnablingState{ what=147457 }
D/WifiP2pService( 2408): P2p socket connection successful
D/WifiP2pService( 2408): P2pEnabledState
E/WifiStateMachine( 2408): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/QuickConnect[1.1][2] ( 5022): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
D/WifiP2pService( 2408): sending p2p connection changed broadcast: IDLE
D/WifiDisplayController( 2408): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController( 2408): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 2408): disconnect
D/WifiDisplayController( 2408): updateConnection
D/WifiDisplayController( 2408): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 2408): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiDisplayAdapter( 2408): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/QuickConnect[1.1][2] ( 5022): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
D/QuickConnect[1.1][2] ( 5022): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
W/WifiP2pStateTracker( 2408): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController( 2408): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/QuickConnect[1.1][2] ( 5022): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
D/NearbySettings( 5508): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 5508): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 5508): MountReceiver.onReceive - Create mPrefHandler
D/WifiDisplayController( 2408): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: S5mini-1
D/WifiDisplayController( 2408):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiDisplayController( 2408):  primary type: 10-0050F204-5
D/WifiDisplayController( 2408):  secondary type: null
D/WifiDisplayController( 2408):  wps: 0
D/WifiDisplayController( 2408):  grpcapab: 0
D/WifiDisplayController( 2408):  devcapab: 0
D/WifiDisplayController( 2408):  status: 3
D/WifiDisplayController( 2408):  wfdInfo: null
D/WifiDisplayController( 2408):  groupownerAddress: null
D/WifiDisplayController( 2408):  GOdeviceName: null
D/WifiDisplayController( 2408):  interfaceAddress: 
D/WifiDisplayController( 2408):  SConnectInfo : null
D/WifiP2pService( 2408): DeviceAddress: 02:e0:6d
D/NearbySettings( 5508): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/NearbySettings( 5508): DMSUtil.isNetworkConnected - flag-null, state-null
D/WifiP2pService( 2408): sending p2p persistent groups changed broadcast
I/NearbySettings( 5508): DMSUtil.isNetworkConnected - WIFI: IDLE
I/NearbySettings( 5508): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5508): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 5508): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 5508): MountReceiver.mPrefHandler - 7002
D/WifiP2pService( 2408): InactiveState
D/WifiP2pService( 2408): InactiveState{ what=139287 }
D/WifiP2pService( 2408): P2pEnabledState{ what=139287 }
D/WifiP2pService( 2408): DefaultState{ what=139287 }
D/QuickConnect[1.1][2] ( 5022): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/FileShare-Server( 5997): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/FileShare-Server( 5997): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,I/wpa_supplicant( 7045): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,I/wpa_supplicant( 7045): nl80211: Received scan results (5 BSSes)
,I/wpa_supplicant( 7045): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 7045): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2462 MHz)
,I/wpa_supplicant( 7045): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2408): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 7045): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,E/WifiStateMachine( 2408): Error! unhandled message{ when=-4ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 7045): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2408): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 7045): Associated with C0.AA.48
D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2408): interfaceStatusChanged wlan0, true
D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2408): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 7045): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 7045): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 7045): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 7045): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 7045): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2408): interfaceStatusChanged wlan0, true
,D/WifiNative( 2408): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7125): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7125):  
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7125): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7125):  
I/SELinux ( 7125):  
,I/SELinux ( 7125): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7125): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7125): >>>>> Normal User
,E/dalvikvm( 7125): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7125): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7125): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7125): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7125): Added TimaKesytore provider
,D/WifiP2pService( 2408): InactiveState{ what=143375 }
,D/WifiP2pService( 2408): P2pEnabledState{ what=143375 }
,D/dalvikvm( 7125): GC_CONCURRENT freed 3001K, 30% free 9574K/13620K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 7125): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/System.out( 7125): Inside WakeupProvider
,I/System.out( 7125): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 7125): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7125): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7125): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,I/dhcpcd  ( 7139): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7139): bssid match
,D/NearbySettings( 5508): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5508): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5508): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 5508): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5508): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 5508): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5508): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 7125): initQueue()
I/ActivityManager( 2408): Killing 5738:com.android.calendar/u0a144 (adj 15): empty #43
,D/PackageManager( 2408): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/WifiP2pService( 2408): InactiveState{ what=143375 }
,D/WifiP2pService( 2408): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2408): VerifyingLinkState enter,
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2408): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check,
,D/WifiStateMachine( 2408): CaptivePortalCheckState enter,
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2408): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE,
D/ConnectivityService( 2408): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
D/ConnectivityService( 2408): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling,
D/ConnectivityService( 2408): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2408): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2408): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2,
,D/ConnectivityService( 2408): handleConnectivityChange: setting default proxy info ,
,D/NearbySettings( 5508): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,I/NearbySettings( 5508): MountReceiver.onReceive - Keep current state
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1,
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1,
,V/RouteController( 1916): RTNETLINK answers: No such file or directory,
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.112 lookup 2 prio 150 2>&1,
,D/NearbySettings( 5508): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5508): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5508): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 5508): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5508): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5508): MountReceiver.onReceive - Keep current state
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/NtpTrustedTime( 2408): forceRefresh() from cache miss
V/NetworkStats( 2408): updateIfacesLocked()
V/NetworkStats( 2408): performPollLocked(flags=0x1)
,V/NetworkStats( 2408): performPollLocked() took 20ms
,D/NearbySettings( 5508): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 5508): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger( 1921): id=21 createSurf (1x1),1 flag=4, Uoast
,D/NtpTrustedTime( 2408): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1448345058493 mCachedNtpElapsedRealtime : 295331 mCachedNtpCertainty : 10
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
V/NetworkStats( 2408): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/PowerManagerService( 2408): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2408
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/Tethering( 2408): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2408): MasterInitialState.processMessage what=3
D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/CaptivePortalTracker( 2408): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
,D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
D/        ( 2408): Setting time of day to sec=1448345058
D/        ( 2408): Trying to open a file
D/        ( 2408): File Open Success
D/        ( 2408): File Close Success
,I/        ( 2408): DRM_TIME_PATH CHMOD 660 for resetState done 
,V/AlarmManager( 2408): waitForAlarm result :65536
I/DBG_DM  ( 4611): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/PCWCLIENTTRACE_PushUtil( 6250): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6250): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6250): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6250): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 4611): [3.19.140541][Line:609][onReceive] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_DM  ( 4611): [3.19.140541][Line:214][xdmAgentTaskHandler] XEVENT_DM_INIT
,I/DBG_DM  ( 4611): [3.19.140541][Line:432][xdmInitAdpWaitSystemRootingCheck] Check completed.
,I/DBG_DM  ( 4611): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/DBG_DM  ( 4611): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_SET
I/DBG_DM  ( 4611): [3.19.140541][Line:78][xdmFeatureGetBearerSettingFromCSCFotaDataBase] 
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
D/StatusBar-DoNotDistrub( 2582): Received intent with android.intent.action.TIME_SET action
,D/StatusBar-DoNotDistrub( 2582): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/NotificationMgr( 2752): updateNotificationsAtStartup()...
D/NotificationMgr( 2752): - start call log query...
,W/Settings( 2408): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Parcel  ( 2408): nm 23
,I/AudioService( 2408): getStreamVolume 5 index 110
D/StatusBar-DoNotDistrub( 2582): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,D/StatusBar-DoNotDistrub( 2582): The STREAM NOTIFICATION volume is 0
D/NotificationMgr( 2752): call log query complete.
D/NotificationMgr( 2752): call log cursor count : 0
,D/NotificationMgr( 2752): call log cursor count2 : null
,D/STATUSBAR-StatusBarManagerService( 2408): manageDisableList what=0x0 pkg=com.android.systemui
I/PrGenericPlugin( 1925): [A] ENTER onAcquireDrmInfo : 0xd17
I/PrGenericPlugin( 1925): [A] LEAVE onAcquireDrmInfo : 0xd17
,I/DrmEventService( 2408):  no response from SecureClock 
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
D/Sensors ( 2408): LightSensor setDelay = 200000000
,D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
D/Sensors ( 2408): Light sensor flush: not enabled 0
D/STATUSBAR-NotificationService( 2408): received android.intent.action.DORMANT_MODE_OFF
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
,D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/Sensors ( 2408): LightSensor enable = 1
D/Sensors ( 2408): LightSensor enableSensor = 1
D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/SQLiteSecureOpenHelper( 4119): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4119): getDatabaseLocked(b,b,pwd)...
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,I/dalvikvm( 4611): Total arena pages for JIT: 11
,I/dalvikvm( 4611): Total arena pages for JIT: 12
I/dalvikvm( 4611): Total arena pages for JIT: 13
,I/dalvikvm( 4611): Total arena pages for JIT: 14
I/dalvikvm( 4611): Total arena pages for JIT: 15
I/dalvikvm( 4611): Total arena pages for JIT: 16
,I/dalvikvm( 4611): Total arena pages for JIT: 17
,I/DBG_DM  ( 4611): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,I/GAV2    ( 7043): Thread[GAThread,5,main]: connecting to Analytics service
,W/ContextImpl( 7043): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:529 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 7043): Thread[GAThread,5,main]: connect: bindService returned true for Intent { act=com.google.android.gms.analytics.service.START (has extras) }
,I/GAV2    ( 7043): Thread[GAThread,5,main]: No campaign data found.
,D/GAV2    ( 7043): Thread[main,5,main]: service connected, binder: android.os.BinderProxy@42471e90
,D/GAV2    ( 7043): Thread[main,5,main]: bound to service
,I/GAV2    ( 7043): Thread[main,5,main]: Connected to service
,I/GAV2    ( 7043): Thread[GAThread,5,main]: putHit called
,I/DBG_DM  ( 4611): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/GAV2    ( 7043): Thread[GAThread,5,main]: Sending hit to service
,I/SQLiteSecureOpenHelper( 4119): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4119): getDatabaseLocked(b,b,pwd)...
,I/DBG_DM  ( 4611): [3.19.140541][Line:5949][xdbGetFUMOInitiatedType] Initiated Type: 2
,I/DBG_DM  ( 4611): [3.19.140541][Line:119][xdmInitAdpEXTInit] nStatus [220]
,I/DBG_DM  ( 4611): [3.19.140541][Line:463][xdmGetEnableLiveDemoFromCSCFeature] enable LiveDemo : false
,E/DBG_DM  ( 4611): Warning!!! [3.19.140541][Line:65][xdmInitAdpGetSIMLockState] SIM Status is not ready
,I/DBG_DM  ( 4611): [3.19.140541][Line:261][xdmInitAdpEXTInit] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 4611): [3.19.140541][Line:271][xdmAgentTaskHandler] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 4611): [3.19.140541][Line:769][xdmUIEvent] XUI_DL_UPDATE_START
,I/DBG_DM  ( 4611): [3.19.140541][Line:1854][xdmAgentCheckResumeNoti] 
,I/DBG_DM  ( 4611): [3.19.140541][Line:369][handleMessage] event ->214
,I/DBG_DM  ( 4611): [3.19.140541][Line:318][xdmBroadcastGetIsSavedNfcMode] m_IsSavedNfcMode : false
,I/DBG_DM  ( 4611): [3.19.140541][Line:546][xuiAdpGetUpdateReport] Get bUpdateReport = false
,D/dalvikvm( 2408): GC_CONCURRENT freed 3808K, 69% free 24567K/78468K, paused 12ms+24ms, total 244ms
D/dalvikvm( 2408): WAIT_FOR_CONCURRENT_GC blocked 125ms
D/dalvikvm( 2408): WAIT_FOR_CONCURRENT_GC blocked 121ms
D/dalvikvm( 2408): WAIT_FOR_CONCURRENT_GC blocked 124ms
D/dalvikvm( 2408): WAIT_FOR_CONCURRENT_GC blocked 103ms
,D/dalvikvm( 2408): WAIT_FOR_CONCURRENT_GC blocked 119ms
D/Sensors ( 2408): LightSensor enable = 0
,D/Sensors ( 2408): LightSensor enableSensor = 0
,D/SensorManager( 2408): unregisterListener ::   
D/LightsService( 2408): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/DBG_DM  ( 4611): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 4611): [3.19.140541][Line:2008][xdmCallUiFotaInstall] 
,I/SELinux ( 7198): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7198):  
,D/dalvikvm( 1923): GC_EXPLICIT freed 43K, 11% free 9503K/10596K, paused 3ms+3ms, total 32ms
,I/SELinux ( 7198): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7198):  
I/SELinux ( 7198):  
,I/SELinux ( 7198): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7198): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7198): >>>>> Normal User
,E/dalvikvm( 7198): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7198): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 11% free 9503K/10596K, paused 2ms+5ms, total 29ms
,I/DBG_DM  ( 4611): [3.19.140541][Line:729][xdmUIEvent] XUI_DL_UPDATE_CONFIRM
W/ContextImpl( 4611): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 com.wssyncmldm.XDMService.xdmCallUiFotaInstall:2023 com.wssyncmldm.XDMService$1.handleMessage:372 android.os.Handler.dispatchMessage:102 
,D/TimaKeyStoreProvider( 7198): in addTimaSignatureService
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 11% free 9503K/10596K, paused 3ms+2ms, total 25ms
,D/TimaKeyStoreProvider( 7198): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7198): Added TimaKesytore provider
,I/SELinux ( 7210): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7210):  
,W/WifiP2pStateTracker( 2408): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,I/DBG_DM  ( 4611): [3.19.140541][Line:890][xdmUnRegisterBatteryReceiver] 
,E/DBG_DM  ( 4611): Warning!!! [3.19.140541][Line:898][xdmUnRegisterBatteryReceiver] didn't register
,I/DBG_DM  ( 4611): [3.19.140541][Line:1320][xdmCheckIdleScreen] Idle Screen : false
,E/DBG_DM  ( 4611): Warning!!! [3.19.140541][Line:899][xdmUnRegisterBatteryReceiver] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.XDMService$3@42380f30
,I/SELinux ( 7210): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7210):  
I/SELinux ( 7210):  
,I/SELinux ( 7210): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7210): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7210): >>>>> Normal User
,E/dalvikvm( 7210): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
,E/SELinux ( 7210): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/ConnectivityService( 2408): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2408):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
D/ConnectivityService( 2408): handleConnectivityChange: setting default proxy info 
D/ConnectivityService( 2408): updateSourceRoutes : no source routing conditions
,D/TimaKeyStoreProvider( 7210): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7210): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7210): Added TimaKesytore provider
,I/dalvikvm( 4611): Total arena pages for JIT: 18
,I/DBG_DM  ( 4611): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,D/dalvikvm( 7198): GC_CONCURRENT freed 2998K, 30% free 9573K/13616K, paused 7ms+1ms, total 41ms
,D/dalvikvm( 7198): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 7210): GC_CONCURRENT freed 2997K, 30% free 9574K/13620K, paused 5ms+2ms, total 35ms
,D/dalvikvm( 7210): WAIT_FOR_CONCURRENT_GC blocked 30ms
,I/DBG_DM  ( 4611): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2408): sendNotification(1) - 4
,W/ResourceType( 2582): Attempt to retrieve bag 0x01030068 which is invalid or in a cycle.
,W/ResourceType( 2582): Attempt to retrieve bag 0x01030067 which is invalid or in a cycle.
,D/ProgressBar( 2582): setProgressDrawable drawableHeight = 12
E/dalvikvm( 7210): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a
W/dalvikvm( 7210): VFY: unable to resolve new-instance 406 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm( 7210): VFY: replacing opcode 0x22 at 0x0000
,D/ProgressBar( 2582): setProgressDrawable drawableHeight = 12
,W/dalvikvm( 7210): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 7210): Link of class 'Lal;' failed
E/dalvikvm( 7210): Could not find class 'al', referenced from method b.a
W/dalvikvm( 7210): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
,D/dalvikvm( 7210): VFY: replacing opcode 0x22 at 0x0006
,D/PhoneStatusBar( 2582): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@422a3608
W/dalvikvm( 7210): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 7210): Link of class 'Lan;' failed
E/dalvikvm( 7210): Could not find class 'an', referenced from method b.a
W/dalvikvm( 7210): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
D/dalvikvm( 7210): VFY: replacing opcode 0x22 at 0x002a
I/dalvikvm( 7210): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm( 7210): VFY: unable to resolve virtual method 5407: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 7210): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 7210): Could not find method android.view.View.getTransitionName, referenced from method b.a
W/dalvikvm( 7210): VFY: unable to resolve virtual method 5231: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 7210): VFY: replacing opcode 0x6e at 0x0006
,W/dalvikvm( 7210): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 7210): Could not find class 'android.app.RemoteInput[]', referenced from method b.a
W/dalvikvm( 7210): VFY: unable to resolve new-array 12200 ([Landroid/app/RemoteInput;) in Lb;
D/dalvikvm( 7210): VFY: replacing opcode 0x23 at 0x0005
D/btif_config_util( 5048): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/libgps  ( 2408): agps_ril_update_network_state: Waiting for IPC connection...
,D/dalvikvm( 7210): DexOpt: unable to opt direct call 0x090f at 0x0e in Lb;.a
W/dalvikvm( 7210): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 7210): Link of class 'Lal;' failed
,D/dalvikvm( 7210): DexOpt: unable to opt direct call 0x068d at 0x08 in Lb;.a
W/dalvikvm( 7210): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 7210): Link of class 'Lan;' failed
D/dalvikvm( 7210): DexOpt: unable to opt direct call 0x0802 at 0x2c in Lb;.a
,D/dalvikvm( 7210): DexOpt: unable to opt direct call 0x0957 at 0x13 in Lb;.a
,I/dalvikvm( 7210): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method dyp.a
W/dalvikvm( 7210): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7210): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 7210): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7210): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7210): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7210): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7210): VFY: unable to resolve instance field 46
,D/dalvikvm( 7210): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 7210): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 7210): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7210): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 7210): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 7210): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 7210): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x422ecad8
,D/dalvikvm( 7210): Added shared lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x422ecad8
,D/dalvikvm( 7210): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-4/libgmscore.so 0x422ecad8, skipping init
,D/dalvikvm( 7210): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x422ecad8
,D/dalvikvm( 7210): Added shared lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x422ecad8
,V/JNIHelp ( 7210): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
D/SSRMv2:SIOP( 2408): SIOP:: AP = 350, Delta = 20
,I/SELinux ( 7228): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7228):  
,D/dalvikvm( 7210): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x422ecad8
,D/dalvikvm( 7210): Shared lib '/data/app-lib/com.google.android.gms-4/libgmscore.so' already loaded in same CL 0x422ecad8
D/dalvikvm( 7210): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x422ecad8
,D/dalvikvm( 7210): Shared lib '/data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so' already loaded in same CL 0x422ecad8
I/SELinux ( 7228): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7228):  
I/SELinux ( 7228):  
,I/SELinux ( 7228): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7228): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7228): >>>>> Normal User
,E/dalvikvm( 7228): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7228): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4341, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2408): stay LED for fully charged
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/TimaKeyStoreProvider( 7228): in addTimaSignatureService
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/TimaKeyStoreProvider( 7228): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7228): Added TimaKesytore provider
,I/ProviderInstaller( 7210): Installed default security provider GmsCore_OpenSSL
,I/dalvikvm( 7210): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
,W/dalvikvm( 7210): VFY: unable to resolve static method 1165: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 7210): VFY: replacing opcode 0x71 at 0x0046
,D/dalvikvm( 7228): GC_CONCURRENT freed 3004K, 30% free 9556K/13612K, paused 3ms+4ms, total 26ms
,D/dalvikvm( 7228): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/KLMS-2.3.201 : ( 7228): KLMSValidator() : checkQATesting()
,I/dalvikvm( 7210): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
,W/dalvikvm( 7210): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7210): VFY: replacing opcode 0x6e at 0x000d
,E/YouTube MDX( 7210): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dalvikvm( 7210): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 7210): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 7210): VFY: replacing opcode 0x6e at 0x0220
,I/KLMS-2.3.201 : ( 7228): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1448345060414
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,I/KLMS-2.3.201 : ( 7228): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7210): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/jxcore-log( 6995): Attempting to connect to the test coordinator server
I/jxcore-log( 6995): 
,I/SELinux ( 7268): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7268):  
,I/LocationTagReadyService( 3466): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
,D/dalvikvm( 7210): GC_CONCURRENT freed 1819K, 21% free 10829K/13692K, paused 4ms+9ms, total 47ms
,D/dalvikvm( 7210): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 7210): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 7210): DexOpt: --- BEGIN 'ads-142579166.jar' (bootstrap=0) ---
,D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
,I/SELinux ( 7268): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7268):  
I/SELinux ( 7268):  
,I/SELinux ( 7268): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7268): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7268): >>>>> Normal User
,E/dalvikvm( 7268): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,I/GallerySearchProvider( 3593): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,E/SELinux ( 7268): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7268): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7268): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7268): Added TimaKesytore provider
,I/SELinux ( 7282): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7282):  
,I/SELinux ( 7282): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7282):  
I/SELinux ( 7282):  
,I/SELinux ( 7282): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7282): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7282): >>>>> Normal User
,E/dalvikvm( 7282): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7282): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7282): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7282): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7282): Added TimaKesytore provider
,I/dalvikvm( 7210): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 7210): VFY: unable to resolve virtual method 2614: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 7210): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7210): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 7210): VFY: unable to resolve virtual method 2615: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 7210): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7210): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 7210): VFY: unable to resolve virtual method 2622: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 7210): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7210): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 7210): VFY: unable to resolve virtual method 2623: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 7210): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7210): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method agv.getLeanbackLaunchIntentForPackage
W/dalvikvm( 7210): VFY: unable to resolve virtual method 2639: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 7210): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7210): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method agv.getPackageInstaller
W/dalvikvm( 7210): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7210): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 7210): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method agv.getUserBadgedDrawableForDensity
,W/dalvikvm( 7210): VFY: unable to resolve virtual method 2659: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 7210): VFY: replacing opcode 0x6e at 0x0002
E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
I/dalvikvm( 7210): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method agv.getUserBadgedIcon
W/dalvikvm( 7210): VFY: unable to resolve virtual method 2660: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 7210): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7210): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method agv.getUserBadgedLabel
W/dalvikvm( 7210): VFY: unable to resolve virtual method 2661: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm( 7210): VFY: replacing opcode 0x6e at 0x0002
,W/ContextImpl( 7210): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7210): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7210): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 7210): Found 10012
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7210): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,D/dalvikvm( 7282): GC_CONCURRENT freed 3007K, 30% free 9560K/13616K, paused 2ms+9ms, total 47ms
,D/dalvikvm( 7282): WAIT_FOR_CONCURRENT_GC blocked 44ms
,D/dalvikvm( 7268): GC_CONCURRENT freed 2997K, 30% free 9566K/13612K, paused 11ms+2ms, total 37ms
,D/dalvikvm( 7268): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/SO_AGENT( 7268): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,V/KVNProvider( 7282): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7282): getFindoCursor query string : 
,I/SO_AGENT( 7268): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,V/KVNProvider( 7282): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 6414): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 6414): [BDLM] already registered in spp
I/SA      ( 6414): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 6414): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/dalvikvm( 6355): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42253bb8, skipping init
,I/System.out( 7198): Thread-606(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/SA      ( 6414): [SLFUCHKMGR] constructor called
,I/SecureStorage( 6355): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 1974): [INFO]: SPID(0x00000004)Credentials: uid 1000, gid 1000, pid 6355
,I/SecureStorage( 1974): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
I/SA      ( 6414): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6414): [OR] == isSIMCardReady false ==
,I/SA      ( 6414): [SCU] == networkStateCheck == true
I/SA      ( 6414): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6414): isChinaCountryCode : false
,I/SA      ( 6414): [OR] == networkStateCheck true ==
,I/SA      ( 6414): [OR] GetMyCountryZoneTask
,I/SA      ( 6414): [OR] onReceive END
,I/SA      ( 6414): [SRS] prepareGetMyCountryZone
,I/System.out( 7198): Thread-606(ApacheHTTPLog):isShipBuild true
,I/System.out( 7198): Thread-606(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 7280): DexOpt: load 4ms, verify+opt 11ms, 194052 bytes
,D/libgps  ( 2408): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2408): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2408): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2408): agps_ril_update_network_availability: Waiting for IPC connection...
,I/SA      ( 6414): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6414): [SSP] query invoked
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 6026): Other Intent
,D/dalvikvm( 7210): DexOpt: --- END 'ads-142579166.jar' (success) ---
,D/dalvikvm( 7210): DEX prep '/data/data/com.google.android.youtube/cache/ads-142579166.jar': unzip in 0ms, rewrite 624ms
,I/SA      ( 6414): [TPMU] GetMccFromDB : null
I/SA      ( 6414): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6414): [TPM] isNoProxy(default) : true
,I/SELinux ( 7332): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7332):  
,I/SA      ( 6414): [RC New] Execute method=[GET] start
,I/System.out( 7210): Thread-664(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7210): Thread-664(ApacheHTTPLog):isShipBuild true
,I/System.out( 7210): Thread-664(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/SELinux ( 7332): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7332):  
I/SELinux ( 7332):  
,I/SELinux ( 7332): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7332): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7332): >>>>> Normal User
,E/dalvikvm( 7332): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7332): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7332): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7332): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7332): Added TimaKesytore provider
,D/dalvikvm( 7332): GC_CONCURRENT freed 2999K, 30% free 9571K/13616K, paused 3ms+1ms, total 32ms
,D/dalvikvm( 7332): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/System.out( 7198): AsyncTask #1 calls detatch()
,W/System.err( 7198): com.sec.android.fota.osp.http.RestClientException
,W/System.err( 7198): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
,W/System.err( 7198): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
,W/System.err( 7198): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
,W/System.err( 7198): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 7198): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 7198): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 7198): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 7198): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7198): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7198): Caused by: java.lang.NullPointerException
,W/System.err( 7198): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7198): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7198): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7198): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7198): 	... 8 more
,D/com.samsung.app( 7332): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7332): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7332): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7332): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
I/ActivityManager( 2408): Killing 5782:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/com.samsung.app( 7332): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7332): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7332): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7332): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7332): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7332): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2408): Killing 5786:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,I/SELinux ( 7349): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7349):  
,I/SELinux ( 7349): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7349):  
I/SELinux ( 7349):  
,I/SELinux ( 7349): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7349): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7349): >>>>> Normal User
,E/dalvikvm( 7349): >>>>> com.samsung.android.internal.headlines [ userId:0 | appId:10110 ]
,E/SELinux ( 7349): [DEBUG] seapp_context_lookup: seinfoCategory = release
,E/WifiStateMachine( 2408): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/TimaKeyStoreProvider( 7349): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7349): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7349): Added TimaKesytore provider
,D/dalvikvm( 7349): GC_CONCURRENT freed 3010K, 30% free 9560K/13616K, paused 2ms+2ms, total 23ms
,D/dalvikvm( 7349): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/HeadlinesChannelApplication( 7349): [onCreate]
,D/Headlines( 7349): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/System.out( 6414): Thread-566(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6414): Thread-566(ApacheHTTPLog):isShipBuild true
,I/System.out( 6414): Thread-566(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/HeadlinesChannelUtil( 7349): getCountryCode(): countryCode = PL
,D/Headlines( 7349): Breath.onCreate
,I/SELinux ( 7362): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7362):  
,I/SELinux ( 7362): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7362):  
I/SELinux ( 7362):  
,I/SELinux ( 7362): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7362): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7362): >>>>> Normal User
,E/dalvikvm( 7362): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7362): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/ActivityManager( 2408): Killing 5299:com.google.android.talk/u0a109 (adj 15): empty #43
,I/SurfaceFlinger( 1921): id=21 Removed Uoast (10/11)
,I/SurfaceFlinger( 1921): id=21 Removed Uoast (-2/11)
D/PowerManagerService( 2408): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2408) eventTime = 298837
D/PowerManagerService( 2408): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2408 (0x0)
D/PowerManagerService( 2408): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2408, ws=WorkSource{1000}) (elapsedTime=3495)
,I/SurfaceFlinger( 1921): id=22 createSurf (1x1),1 flag=4, Uoast
,D/TimaKeyStoreProvider( 7362): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7362): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7362): Added TimaKesytore provider
D/PowerManagerService( 2408): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2408
,D/HeadlinesCardManager( 7349): HeadlinesCardManager : constructor
,E/HeadlinesCardManager( 7349): HeadlinesCardManager : ctor = image_cache size is 42MB
,D/SA Version( 7349): CardProvider Library : 13
I/SecureStorage( 1974): [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 1974): [INFO]: SPID(0x00000004)PID: 6355, TID: 6381
,I/System.out( 7210): Thread-664 calls detatch()
,D/MagazineService::CardProviderContentProvider( 6458): insertProvider: provider already exists.: com.samsung.android.app.headlines
,D/MagazineService::CardProviderContentProvider( 6458): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 7349): registerCardProvider: provider already exists.
,I/Headlines( 7349): HeadlinesDataCenter ctor
I/Headlines( 7349): HeadlinesDataCenter. mLocale = en_US
,D/HeadlinesChannelUtil( 7349): getCountryCode(): countryCode = PL
,D/HeadlinesCardManager( 7349): HeadlinesCardManager : constructor welcome :YES
,D/dalvikvm( 7362): GC_CONCURRENT freed 2989K, 30% free 9572K/13612K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 7362): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/Headlines( 7349): Breath timer started. interval : 30000
,D/Headlines( 7349): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 7349): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 7349): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 7349): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 7349): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 7349): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 7349): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SecureStorage( 6355): [INFO]: SPID(0x00000000)Processing data has been completed
,D/libgps  ( 2408): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2408): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2408): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,V/WebViewChromium( 7362): Binding Chromium to the background looper Looper (main, tid 1) {422590f8}
,I/chromium( 7362): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7362): Initializing chromium process, renderers=0
,I/dalvikvm( 3278): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 3278): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 3278): VFY: replacing opcode 0x6e at 0x0033
,W/chromium( 7362): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7362): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7362): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7362): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7362): Mali API Version : 401
,I/Mali    ( 7362): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/DelayedSyncController( 5908): Delaying sync.
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/GAV2    ( 7362): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,E/Auth.Api.Credentials( 3278): [CredentialSyncAdapter] Unknown sync event.
,W/ContextImpl( 7362): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/NtpTrustedTime( 2408): getCachedNtpTime() cache hit
,I/ActivityManager( 2408): Killing 5586:com.google.android.music:main/u0a125 (adj 15): empty #43
,I/dalvikvm( 6355): Total arena pages for JIT: 11
,I/dalvikvm( 6355): Total arena pages for JIT: 12
I/dalvikvm( 6355): Total arena pages for JIT: 13
,I/dalvikvm( 6355): Total arena pages for JIT: 14
I/dalvikvm( 6355): Total arena pages for JIT: 15
,I/dalvikvm( 6355): Total arena pages for JIT: 16
,I/dalvikvm( 6355): Total arena pages for JIT: 17
,I/NSApplication( 7362): Starting up...
,I/ActivityManager( 2408): Killing 5808:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/ImageResourceManager( 5670): ImageResourceManager: uninitalized
,D/dalvikvm( 5670): GC_FOR_ALLOC freed 1178K, 27% free 9952K/13616K, paused 31ms, total 34ms
,I/dalvikvm-heap( 5670): Grow heap (frag case) to 12.768MB for 2129936-byte allocation
,D/dalvikvm( 5670): GC_FOR_ALLOC freed 4K, 24% free 12028K/15700K, paused 16ms, total 16ms
,I/iu.Environment( 5670): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/dalvikvm( 5670): GC_CONCURRENT freed 11K, 24% free 12038K/15700K, paused 17ms+18ms, total 52ms
,D/dalvikvm( 5670): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/QuickConnect[1.1][2] ( 5022): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5022): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
,I/dalvikvm-heap( 5670): Grow heap (frag case) to 14.805MB for 2129936-byte allocation
,I/SELinux ( 7411): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7411):  
,D/dalvikvm( 5670): GC_FOR_ALLOC freed 37K, 21% free 14080K/17784K, paused 22ms, total 23ms
,I/iu.UploadsManager( 5670): num queued entries: 0
,I/iu.UploadsManager( 5670): num updated entries: 0
I/SELinux ( 7411): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7411):  
I/SELinux ( 7411):  
,I/SELinux ( 7411): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7411): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7411): >>>>> Normal User
,E/dalvikvm( 7411): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7411): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/iu.SyncManager( 5670): NEXT; no task
,D/TimaKeyStoreProvider( 7411): in addTimaSignatureService
I/SA      ( 6414): [RC New] [v2liruge] api execute + 1717
,I/SA      ( 6414): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6414): AsyncTask #1 calls detatch()
,D/TimaKeyStoreProvider( 7411): Cannot add TimaSignature Service, License check Failed
,I/ActivityManager( 2408): Killing 5943:com.google.android.apps.uploader/u0a117 (adj 15): empty #43
D/ActivityThread( 7411): Added TimaKesytore provider
,I/SA      ( 6414): [TPMU] getNetworkMcc : 
,I/SA      ( 6414): [SCU] saveMccToPreferece Start
I/SA      ( 6414): [SCU] RegionMCC : 260
,I/SA      ( 6414): [SSP] query invoked
,I/SA      ( 6414): [TPMU] GetMccFromDB : null
,I/SA      ( 6414): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6414): [SCU] saveMccToPreferece End
I/SA      ( 6414): [RC New] executeRequest [v2liruge] end. 1762
,I/SA      ( 6414): [RC New] Execute end
I/SA      ( 6414): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6414): [OR] GetMyCountryZoneTask Success
,D/dalvikvm( 7411): GC_CONCURRENT freed 2993K, 30% free 9575K/13616K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 7411): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2408): GC_EXPLICIT freed 1998K, 69% free 24520K/78468K, paused 9ms+19ms, total 238ms
,D/RCPManagerService( 2408): exchangeData() failure , invalid userId
,D/RCPManagerService( 2408): exchangeData() failure , invalid userId
,D/RCPManagerService( 2408): exchangeData() failure , invalid userId
,D/PicasaService( 3593): start picasa sync
,D/PicasaService( 3593): end picasa sync
,I/SELinux ( 7434): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7434):  
,D/RCPManagerService( 2408): exchangeData() failure , invalid userId
,D/RCPManagerService( 2408): exchangeData() failure , invalid userId
,W/ActivityManager( 2408): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/RCPManagerService( 2408): exchangeData() failure , invalid userId
I/SELinux ( 7434): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7434):  
I/SELinux ( 7434):  
I/SELinux ( 7434): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7434): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7434): >>>>> Normal User
E/dalvikvm( 7434): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
E/SELinux ( 7434): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7434): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7434): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7434): Added TimaKesytore provider
,I/SELinux ( 7449): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7449):  
,I/ActivityManager( 2408): Killing 6187:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/dalvikvm( 7434): GC_CONCURRENT freed 2996K, 30% free 9566K/13612K, paused 2ms+1ms, total 87ms
,D/dalvikvm( 7434): WAIT_FOR_CONCURRENT_GC blocked 82ms,
I/SELinux ( 7449): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7449):  
I/SELinux ( 7449):  
I/SELinux ( 7449): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7449): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7449): >>>>> Normal User
,E/dalvikvm( 7449): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ],
,E/SELinux ( 7449): [DEBUG] seapp_context_lookup: seinfoCategory = shared,
,D/TimaKeyStoreProvider( 7449): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7449): Cannot add TimaSignature Service, License check Failed
,D/BadgeProvider( 7434): onCreate
D/ActivityThread( 7449): Added TimaKesytore provider
,D/BadgeProvider( 7434): DatabaseHelper,
,D/DelayedSyncController( 5908): Delaying sync.,
,D/dalvikvm( 7210): GC_CONCURRENT freed 1548K, 19% free 11282K/13876K, paused 21ms+13ms, total 81ms,
,D/BadgeProvider( 7434): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge',
,D/Launcher.Model( 2777): reloadBadges entered.,
D/BadgeProvider( 7434): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7434): sendNotify, [notify] : null
D/BadgeProvider( 7434): update, [uri] : content://com.sec.badge/apps/1,
D/BadgeProvider( 7434): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7434): update, [UpdateCount] : 1,
,I/dalvikvm( 2736): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a,
W/dalvikvm( 2736): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2736): VFY: replacing opcode 0x6e at 0x0033,
,D/dalvikvm( 7449): GC_CONCURRENT freed 3001K, 30% free 9566K/13612K, paused 4ms+1ms, total 47ms,
,D/dalvikvm( 7449): WAIT_FOR_CONCURRENT_GC blocked 32ms,
,I/SELinux ( 7465): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7465):  
,D/dalvikvm( 1923): GC_EXPLICIT freed 42K, 11% free 9503K/10596K, paused 2ms+3ms, total 30ms
I/SELinux ( 7465): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7465):  
I/SELinux ( 7465):  
,I/SELinux ( 7465): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7465): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7465): >>>>> Normal User
,E/dalvikvm( 7465): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
,I/ActivityManager( 2408): Killing 5922:com.google.android.partnersetup/u0a14 (adj 15): empty #43
E/SELinux ( 7465): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/ActivityManager( 2408): Killing 6224:com.samsung.groupcast/u0a15 (adj 15): empty #43
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 11% free 9503K/10596K, paused 2ms+3ms, total 35ms
,D/TimaKeyStoreProvider( 7465): in addTimaSignatureService
,D/AmoledAdjustTimer( 2408): prevTemp = 303, currTemp = 304, prevStep = 4, currStep = 4
,D/TimaKeyStoreProvider( 7465): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7465): Added TimaKesytore provider
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 11% free 9503K/10596K, paused 3ms+4ms, total 30ms
,I/System.out( 7210): Thread-657 calls detatch()
,D/dalvikvm( 7465): GC_CONCURRENT freed 2980K, 30% free 9587K/13616K, paused 3ms+1ms, total 31ms
,D/dalvikvm( 7465): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/ActivityManager( 2408): Killing 6237:com.android.musicfx/u0a24 (adj 15): empty #43
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6250): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6250): [hasSamungAccount] - No Samsung Account
,I/dalvikvm( 7465): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 7465): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 7465): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 7465): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7465): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7465): VFY: replacing opcode 0x22 at 0x0000
,V/AlarmManager( 2408): waitForAlarm result :4
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6250): failed to loading secure library
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6250): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6250): GetString : secure API is not supported!!
,I/PCWCLIENTTRACE_PushUtil( 6250): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6250): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6250): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6250): [ensureRegistration] - No Samsung account
,E/dalvikvm( 7465): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
W/dalvikvm( 7465): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 7465): VFY: replacing opcode 0x22 at 0x0037
,W/dalvikvm( 7465): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7465): Link of class 'Ldqp;' failed
,W/dalvikvm( 7465): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7465): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7465): Link of class 'Ldqp;' failed
I/dalvikvm( 7465): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 7465): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 7465): VFY: replacing opcode 0x6e at 0x0000
,E/dalvikvm( 7465): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7465): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7465): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 7465): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7465): Link of class 'Ldqp;' failed
,W/dalvikvm( 7465): VFY: unable to find class referenced in signature (Ldqp;)
,W/dalvikvm( 7465): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7465): Link of class 'Ldqp;' failed
I/dalvikvm( 7465): Could not find method dqp.getState, referenced from method g.a
,W/dalvikvm( 7465): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
,D/dalvikvm( 7465): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 7465): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 7465): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
,D/dalvikvm( 7465): VFY: replacing opcode 0x1c at 0x0026
,W/dalvikvm( 7465): Unable to resolve superclass of Ldqp; (762),
W/dalvikvm( 7465): Link of class 'Ldqp;' failed
,W/dalvikvm( 7465): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7465): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 7465): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7465): Link of class 'Ldqp;' failed
I/dalvikvm( 7465): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 7465): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;,
,D/dalvikvm( 7465): VFY: replacing opcode 0x6e at 0x0003,
W/dalvikvm( 7465): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7465): Link of class 'Lax;' failed
,E/dalvikvm( 7465): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 7465): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
,D/dalvikvm( 7465): VFY: replacing opcode 0x22 at 0x0006,
W/dalvikvm( 7465): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7465): Link of class 'Laz;' failed,
E/dalvikvm( 7465): Could not find class 'az', referenced from method g.a
W/dalvikvm( 7465): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
,D/dalvikvm( 7465): VFY: replacing opcode 0x22 at 0x002c,
I/dalvikvm( 7465): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 7465): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7465): VFY: replacing opcode 0x6e at 0x0008,
I/dalvikvm( 7465): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a,
W/dalvikvm( 7465): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 7465): VFY: replacing opcode 0x6e at 0x000c,
I/dalvikvm( 7465): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 7465): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7465): VFY: replacing opcode 0x6e at 0x0006,
I/dalvikvm( 7465): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 7465): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
,D/dalvikvm( 7465): VFY: replacing opcode 0x6e at 0x000a
,I/dalvikvm( 7465): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 7465): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
,D/dalvikvm( 7465): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7465): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
W/dalvikvm( 7465): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z,
D/dalvikvm( 7465): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7465): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a,
W/dalvikvm( 7465): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 7465): VFY: replacing opcode 0x72 at 0x0000,
W/dalvikvm( 7465): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
,E/dalvikvm( 7465): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 7465): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 7465): VFY: replacing opcode 0x23 at 0x0005,
,I/dalvikvm( 7465): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b,
W/dalvikvm( 7465): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7465): VFY: replacing opcode 0x6e at 0x0009,
,W/dalvikvm( 7465): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764),
W/dalvikvm( 7465): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 7465): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 7465): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;,
,D/dalvikvm( 7465): VFY: replacing opcode 0x1c at 0x0002,
E/dalvikvm( 7465): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 7465): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 7465): VFY: replacing opcode 0x1f at 0x000c,
,D/dalvikvm( 7465): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS,
W/dalvikvm( 7465): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7465): VFY: replacing opcode 0x62 at 0x0006,
,D/dalvikvm( 7465): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a,
,D/dalvikvm( 7465): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a,
,D/dalvikvm( 7465): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a,
D/dalvikvm( 7465): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
,D/dalvikvm( 7465): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a,
W/dalvikvm( 7465): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7465): Link of class 'Lax;' failed
,D/dalvikvm( 7465): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 7465): Unable to resolve superclass of Laz; (841)
,W/dalvikvm( 7465): Link of class 'Laz;' failed
,D/dalvikvm( 7465): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 7465): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a,
,D/dalvikvm( 7465): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l,
,D/dalvikvm( 7465): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x42256680,
,D/dalvikvm( 7465): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x42256680,
,I/dalvikvm( 7465): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b,
W/dalvikvm( 7465): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 7465): VFY: replacing opcode 0x6e at 0x0076,
,I/Babel_SMS( 7465): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7465): MmsConfig.loadMmsSettings
I/Babel_SMS( 7465): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/Babel_SMS( 7465): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7465): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7465): MmsConfig.loadFromResources
,E/Babel_SMS( 7465): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7465): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,W/dalvikvm( 7465): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7465): Link of class 'Lfzc;' failed
E/dalvikvm( 7465): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 7465): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
,D/dalvikvm( 7465): VFY: replacing opcode 0x22 at 0x0033
W/dalvikvm( 7465): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7465): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7465): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
,W/dalvikvm( 7465): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
I/dalvikvm( 7465): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 7465): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
,D/dalvikvm( 7465): VFY: replacing opcode 0x74 at 0x006d
I/dalvikvm( 7465): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 7465): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
,D/dalvikvm( 7465): VFY: replacing opcode 0x6e at 0x0033
,I/dalvikvm( 7465): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
,W/dalvikvm( 7465): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
D/dalvikvm( 7465): VFY: replacing opcode 0x6e at 0x0030
W/dalvikvm( 7465): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7465): Link of class 'Lfzc;' failed
,D/dalvikvm( 7465): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
,E/SensorService( 2408): Permission Denial : SEC Private Sensor 
,E/SensorService( 2408): Permission Denial : SEC Private Sensor 
,D/dalvikvm( 7465): GC_CONCURRENT freed 1795K, 21% free 10864K/13704K, paused 4ms+4ms, total 39ms
,D/dalvikvm( 7465): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 7465): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/ExynosCameraInterface( 1929): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1929): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
D/ExynosCameraInterface( 1929): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1929): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,W/Settings( 7465): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7465): startup - clean
,I/Babel   ( 7465): deleted: false for 0
I/dalvikvm( 7465): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
W/dalvikvm( 7465): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7465): VFY: replacing opcode 0x6e at 0x000d
,W/dalvikvm( 7465): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,I/dalvikvm( 7465): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 7465): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
,D/dalvikvm( 7465): VFY: replacing opcode 0x6e at 0x004e
W/dalvikvm( 7465): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7465): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7465): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 7465): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
,D/dalvikvm( 7465): VFY: replacing opcode 0x22 at 0x0071
,W/dalvikvm( 7465): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7465): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7465): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7465): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7465): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 7465): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
,D/dalvikvm( 7465): VFY: replacing opcode 0x1f at 0x0021
,W/dalvikvm( 7465): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 7465): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
,I/dalvikvm( 7465): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
,W/dalvikvm( 7465): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
,D/dalvikvm( 7465): VFY: replacing opcode 0x6e at 0x0074
,I/vclib   ( 7465): onServiceConnected
,W/Babel   ( 7465): Attempted to change video mute state without an active call.
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/iu.Environment( 3278): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 3278): num queued entries: 0
,I/iu.UploadsManager( 3278): num updated entries: 0
,I/iu.SyncManager( 3278): NEXT; no task
,D/dalvikvm( 7465): GC_CONCURRENT freed 789K, 14% free 12120K/13956K, paused 4ms+3ms, total 61ms
,D/dalvikvm( 7465): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 7465): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/WaitQueueForNetworkActivate( 6558): notifyNetworkActivated
,W/ContextImpl( 6558): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 2408): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/System.out( 7465): Thread-650(HTTPLog):isShipBuild true
,I/System.out( 7465): Thread-650(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 7465): GC_FOR_ALLOC freed 898K, 16% free 12629K/14948K, paused 62ms, total 63ms
,D/dalvikvm( 7465): GC_FOR_ALLOC freed 1816K, 22% free 12989K/16604K, paused 63ms, total 63ms,
,I/GCM     ( 2854): GCM config loaded,
,I/Babel   ( 7465): connection state changed from UNKNOWN to CONNECTED,
,D/hcjo    ( 6558): AutoUpdateManager:IDLE:execute
,E/SPPClientService( 6570): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6570): [SystemStateMoniter] Current Time : 302277
,E/SPPClientService( 6570): [SystemStateMoniter] No Connect : false
,I/dalvikvm( 6558): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
,W/dalvikvm( 6558): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 6558): VFY: replacing opcode 0x6e at 0x0024
,D/InitializeManagerStateMachine( 6558): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6558): exit::IDLE
,D/InitializeManagerStateMachine( 6558): entry::NETWORK_CHECK
,I/SELinux ( 7507): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7507):  
,D/InitializeManagerStateMachine( 6558): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 6558): exit::NETWORK_CHECK
I/SurfaceFlinger( 1921): id=22 Removed Uoast (10/11)
D/InitializeManagerStateMachine( 6558): entry::CHECK_COUNTRY_INFO
I/SurfaceFlinger( 1921): id=22 Removed Uoast (-2/11)
D/InitializeManagerStateMachine( 6558): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 6558): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6558): entry::SUCCESS
,D/hcjo    ( 6558): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/PowerManagerService( 2408): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2408) eventTime = 302336
D/PowerManagerService( 2408): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2408 (0x0)
D/PowerManagerService( 2408): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2408, ws=WorkSource{1000}) (elapsedTime=3473)
,D/dalvikvm( 3278): GC_EXPLICIT freed 1517K, 20% free 12048K/14992K, paused 69ms+8ms, total 384ms
,W/SQLiteConnectionPool( 3278): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/hcjo    ( 6558): AutoUpdateTriggerManager:IDLE:setInterval:345600000
I/SELinux ( 7507): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7507):  
I/SELinux ( 7507):  
,I/SELinux ( 7507): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7507): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7507): >>>>> Normal User
E/dalvikvm( 7507): >>>>> com.android.calendar [ userId:0 | appId:10144 ]
,E/SELinux ( 7507): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7507): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7507): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7507): Added TimaKesytore provider
,D/hcjo    ( 6558): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6558): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6558): exit::SUCCESS
,D/InitializeManagerStateMachine( 6558): entry::IDLE
I/ActivityManager( 2408): Killing 6263:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,D/dalvikvm( 7507): GC_CONCURRENT freed 2990K, 30% free 9573K/13612K, paused 2ms+2ms, total 26ms
,D/dalvikvm( 7507): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 2854): GC_EXPLICIT freed 1705K, 21% free 11150K/13976K, paused 5ms+7ms, total 59ms
,D/UdcCache:FPQuery( 3278): Bootstrapping UDC settings cache for all accounts
,I/VacuumService( 2854): Vacuum at: now=1448345065807 tag=VacuumService
,V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 2408): Killing 6279:com.sec.android.app.shealth/u0a36 (adj 15): empty #43
,D/BootCompletedReceiver( 2408): onReceive
,I/KLMS-2.3.201 : ( 7228): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/System.out( 3278): Thread-176(HTTPLog):isShipBuild true
,I/System.out( 3278): Thread-176(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/KLMS-2.3.201 : ( 7228): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1448345065999
,I/KLMS-2.3.201 : ( 7228): StateImplV2() : dateTimeChanged() : Tue Nov 24 07:04:26 CET 2015
,I/SELinux ( 7525): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7525):  
,I/SELinux ( 7525): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7525):  
I/SELinux ( 7525):  
,I/SELinux ( 7525): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7525): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7525): >>>>> Normal User
,E/dalvikvm( 7525): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
,E/SELinux ( 7525): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7525): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7525): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7525): Added TimaKesytore provider
D/ConnectivityService( 2408): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
,D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
,D/dalvikvm( 7525): GC_CONCURRENT freed 2994K, 30% free 9569K/13612K, paused 1ms+1ms, total 24ms
,D/dalvikvm( 7525): WAIT_FOR_CONCURRENT_GC blocked 13ms
,W/ContextImpl( 7525): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
,E/Device Type Shared Preferences( 7525): Device Type Shared Preferences - getDeviceTypeChecked -true
,E/Device Type Shared Preferences( 7525): Device Type Shared Preferences - not connecting to service
,E/com.sec.android.app.shealth.SHealthApplication( 7525): ContentProvider is not null
,W/ResourceType( 7525): No package identifier when getting value for resource number 0x00000000
,I/System.out( 7525): resource Id::2131361807
,D/com.sec.android.app.shealth.SHealthApplication( 7525): Success during batch insertion in App registry:0
,D/GetConfigurationSnapshotOperation( 2854): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2854): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 2854): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 2854): no corresponding serverToken: com.google.android.gms.playlog.uploader
,V/MediaPlayer( 7525): decode(56, 30565892, 48105)
,V/MediaPlayerService( 1929): decode(26, 30565892, 48105)
V/MediaPlayerService( 1929): player type = 3
V/AwesomePlayer( 1929): setDefault
,V/AwesomePlayer( 1929): constructor
V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): StagefrightPlayer
V/AwesomePlayer( 1929): setListener
V/StagefrightPlayer( 1929): initCheck
V/AwesomePlayer( 1929): setAudioSink
V/StagefrightPlayer( 1929): setDataSource(26, 30565892, 48105)
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b4cc8, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1929): mSecMediaClock clear
V/AwesomePlayer( 1929): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1929): mBitrate = -1 bits/sec
V/AwesomePlayer( 1929): current audio track index (0) is added to vector
V/AwesomePlayer( 1929): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1929): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1929): prepare
V/AwesomePlayer( 1929): prepareAsync
,V/MediaPlayerService( 1929): wait for prepare
V/AwesomePlayer( 1929): onPrepareAsyncEvent
I/SecMediaClock( 1929): SecMediaClock constructor
I/SecMediaClock( 1929): reset
V/AwesomePlayer( 1929): initAudioDecoder
V/AwesomePlayer( 1929): checkOffloadExceptions is true
,I/OMXCodec( 1929): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1929): mDispatchers.add
I/OMXCodec( 1929): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1929): finishAsyncPrepare_l
V/AwesomePlayer( 1929): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1929): notify(0x443b4cc8, 200, 973, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b4cc8, 5, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b4cc8, 1, 0, 0)
V/AudioCache( 1929): prepared
V/AudioCache( 1929): wait - success
V/MediaPlayerService( 1929): start
V/StagefrightPlayer( 1929): start
V/AwesomePlayer( 1929): play
V/AwesomePlayer( 1929): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1929): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1929): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1929): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b4cc8, 6, 0, 0)
V/AudioCache( 1929): ignored
,V/AwesomePlayer( 1929): addBatteryData
,V/MediaPlayerService( 1929): wait for playback complete
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1929): postAudioEOS delayUs (0)
V/AwesomePlayer( 1929): onCheckAudioStatus
V/AwesomePlayer( 1929): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1929): onStreamDone
V/AwesomePlayer( 1929): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1929): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b4cc8, 2, 0, 0)
V/AudioCache( 1929): playback complete - thread will wake up later
V/AwesomePlayer( 1929): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b4cc8, 7, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1929): addBatteryData
V/AudioCache( 1929): wait - success
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b4cc8, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop() sendCommand(0x44, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1929): reset out
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1929): SecMediaClock destructor
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): ~StagefrightPlayer
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/AwesomePlayer( 1929): destructor
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1929): mSecMediaClock clear
,V/MediaPlayer( 7525): decode(58, 30501792, 10421)
,V/MediaPlayerService( 1929): decode(26, 30501792, 10421)
V/MediaPlayerService( 1929): player type = 3
V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): constructor
,V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): StagefrightPlayer
V/AwesomePlayer( 1929): setListener
,V/StagefrightPlayer( 1929): initCheck
V/AwesomePlayer( 1929): setAudioSink
V/StagefrightPlayer( 1929): setDataSource(26, 30501792, 10421)
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x4424f178, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
,V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1929): mSecMediaClock clear
,V/AwesomePlayer( 1929): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1929): mBitrate = -1 bits/sec
V/AwesomePlayer( 1929): current audio track index (0) is added to vector
V/AwesomePlayer( 1929): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1929): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1929): prepare
V/AwesomePlayer( 1929): prepareAsync
V/MediaPlayerService( 1929): wait for prepare
,V/AwesomePlayer( 1929): onPrepareAsyncEvent
I/SecMediaClock( 1929): SecMediaClock constructor
I/SecMediaClock( 1929): reset
V/AwesomePlayer( 1929): initAudioDecoder
V/AwesomePlayer( 1929): checkOffloadExceptions is true
,I/OMXCodec( 1929): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 1929): mDispatchers.add
I/OMXCodec( 1929): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 1929): finishAsyncPrepare_l
V/AwesomePlayer( 1929): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1929): notify(0x4424f178, 200, 973, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x4424f178, 5, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache( 1929): notify(0x4424f178, 1, 0, 0)
V/AudioCache( 1929): prepared
V/AudioCache( 1929): wait - success
V/MediaPlayerService( 1929): start
V/StagefrightPlayer( 1929): start
V/AwesomePlayer( 1929): play
V/AwesomePlayer( 1929): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1929): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1929): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1929): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x4424f178, 6, 0, 0)
V/AudioCache( 1929): ignored
,V/AwesomePlayer( 1929): addBatteryData
I/AudioPlayer( 1929): First fillBuffer call!!
,V/MediaPlayerService( 1929): wait for playback complete
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1929): postAudioEOS delayUs (0)
V/AwesomePlayer( 1929): onCheckAudioStatus
V/AwesomePlayer( 1929): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1929): onStreamDone
V/AwesomePlayer( 1929): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1929): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x4424f178, 2, 0, 0)
V/AudioCache( 1929): playback complete - thread will wake up later
,V/AwesomePlayer( 1929): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x4424f178, 7, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1929): addBatteryData
V/AudioCache( 1929): wait - success
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
,V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x4424f178, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop() sendCommand(0x45, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1929): reset out
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1929): SecMediaClock destructor
V/AwesomePlayer( 1929): mSecMediaClock clear
,V/StagefrightPlayer( 1929): ~StagefrightPlayer
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/AwesomePlayer( 1929): destructor
,V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/MediaPlayer( 7525): decode(59, 34044116, 34198)
V/MediaPlayerService( 1929): decode(27, 34044116, 34198)
V/MediaPlayerService( 1929): player type = 3
,V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): constructor
V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
,V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): StagefrightPlayer
V/AwesomePlayer( 1929): setListener
V/StagefrightPlayer( 1929): initCheck
V/AwesomePlayer( 1929): setAudioSink
V/StagefrightPlayer( 1929): setDataSource(27, 34044116, 34198)
V/AwesomePlayer( 1929): reset_l()
,V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x442627c8, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1929): mSecMediaClock clear
,V/AwesomePlayer( 1929): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1929): mBitrate = -1 bits/sec
V/AwesomePlayer( 1929): current audio track index (0) is added to vector
V/AwesomePlayer( 1929): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1929): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1929): prepare
V/AwesomePlayer( 1929): prepareAsync
V/MediaPlayerService( 1929): wait for prepare
,V/AwesomePlayer( 1929): onPrepareAsyncEvent
I/SecMediaClock( 1929): SecMediaClock constructor
I/SecMediaClock( 1929): reset
V/AwesomePlayer( 1929): initAudioDecoder
V/AwesomePlayer( 1929): checkOffloadExceptions is true
,I/OMXCodec( 1929): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1929): mDispatchers.add
I/OMXCodec( 1929): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1929): finishAsyncPrepare_l
V/AwesomePlayer( 1929): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1929): notify(0x442627c8, 200, 973, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x442627c8, 5, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x442627c8, 1, 0, 0)
V/AudioCache( 1929): prepared
V/AudioCache( 1929): wait - success
V/MediaPlayerService( 1929): start
V/StagefrightPlayer( 1929): start
V/AwesomePlayer( 1929): play
V/AwesomePlayer( 1929): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1929): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1929): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1929): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x442627c8, 6, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): addBatteryData
,V/MediaPlayerService( 1929): wait for playback complete
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1929): postAudioEOS delayUs (0)
V/AwesomePlayer( 1929): onCheckAudioStatus
V/AwesomePlayer( 1929): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1929): onStreamDone
V/AwesomePlayer( 1929): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1929): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x442627c8, 2, 0, 0)
V/AudioCache( 1929): playback complete - thread will wake up later
V/AwesomePlayer( 1929): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x442627c8, 7, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1929): addBatteryData
V/AudioCache( 1929): wait - success
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x442627c8, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop() sendCommand(0x46, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1929): reset out
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1929): SecMediaClock destructor
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): ~StagefrightPlayer
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
,V/AwesomePlayer( 1929): destructor
,V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1929): mSecMediaClock clear
,V/MediaPlayer( 7525): decode(60, 30449260, 7405)
,V/MediaPlayerService( 1929): decode(26, 30449260, 7405)
V/MediaPlayerService( 1929): player type = 3
V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): constructor
V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): StagefrightPlayer
V/AwesomePlayer( 1929): setListener
V/StagefrightPlayer( 1929): initCheck
V/AwesomePlayer( 1929): setAudioSink
V/StagefrightPlayer( 1929): setDataSource(26, 30449260, 7405)
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x445f8b68, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1929): mSecMediaClock clear
,V/AwesomePlayer( 1929): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1929): mBitrate = -1 bits/sec
V/AwesomePlayer( 1929): current audio track index (0) is added to vector
V/AwesomePlayer( 1929): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1929): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1929): prepare
V/AwesomePlayer( 1929): prepareAsync
,V/MediaPlayerService( 1929): wait for prepare
V/AwesomePlayer( 1929): onPrepareAsyncEvent
I/SecMediaClock( 1929): SecMediaClock constructor
I/SecMediaClock( 1929): reset
V/AwesomePlayer( 1929): initAudioDecoder
V/AwesomePlayer( 1929): checkOffloadExceptions is true
,I/OMXCodec( 1929): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1929): mDispatchers.add
I/OMXCodec( 1929): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 1929): finishAsyncPrepare_l
V/AwesomePlayer( 1929): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1929): notify(0x445f8b68, 200, 973, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x445f8b68, 5, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x445f8b68, 1, 0, 0)
V/AudioCache( 1929): prepared
V/AudioCache( 1929): wait - success
V/MediaPlayerService( 1929): start
V/StagefrightPlayer( 1929): start
V/AwesomePlayer( 1929): play
V/AwesomePlayer( 1929): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1929): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1929): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1929): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x445f8b68, 6, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): addBatteryData
V/MediaPlayerService( 1929): wait for playback complete
,I/AudioPlayer( 1929): First fillBuffer call!!
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] End Of Stream
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
V/AwesomePlayer( 1929): postAudioEOS delayUs (0)
V/AwesomePlayer( 1929): onCheckAudioStatus
V/AwesomePlayer( 1929): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1929): onStreamDone
V/AwesomePlayer( 1929): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1929): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x445f8b68, 2, 0, 0)
V/AudioCache( 1929): playback complete - thread will wake up later
V/AwesomePlayer( 1929): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x445f8b68, 7, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1929): addBatteryData
V/AudioCache( 1929): wait - success
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x445f8b68, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop() sendCommand(0x47, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1929): reset out
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1929): SecMediaClock destructor
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): ~StagefrightPlayer
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/AwesomePlayer( 1929): destructor
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/MediaPlayer( 7525): decode(61, 34134748, 5555)
V/MediaPlayerService( 1929): decode(26, 34134748, 5555)
V/MediaPlayerService( 1929): player type = 3
V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): constructor
V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): StagefrightPlayer
V/AwesomePlayer( 1929): setListener
V/StagefrightPlayer( 1929): initCheck
V/AwesomePlayer( 1929): setAudioSink
V/StagefrightPlayer( 1929): setDataSource(26, 34134748, 5555)
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b3cf8, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/AwesomePlayer( 1929): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1929):, mBitrate = -1 bits/sec
V/AwesomePlayer( 1929): current audio track index (0) is added to vector
V/AwesomePlayer( 1929): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1929): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1929): prepare
V/AwesomePlayer( 1929): prepareAsync
V/MediaPlayerService( 1929): wait for prepare
V/AwesomePlayer( 1929): onPrepareAsyncEvent
I/SecMediaClock( 1929): SecMediaClock constructor
I/SecMediaClock( 1929): reset
V/AwesomePlayer( 1929): initAudioDecoder
V/AwesomePlayer( 1929): checkOffloadExceptions is true
I/OMXCodec( 1929): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1929): mDispatchers.add
I/OMXCodec( 1929): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1929): finishAsyncPrepare_l
V/AwesomePlayer( 1929): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1929): notify(0x443b3cf8, 200, 973, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b3cf8, 5, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b3cf8, 1, 0, 0)
V/AudioCache( 1929): prepared
V/AudioCache( 1929): wait - success
V/MediaPlayerService( 1929): start
V/StagefrightPlayer( 1929): start
V/AwesomePlayer( 1929): play
V/AwesomePlayer( 1929): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1929): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1929): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1929): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b3cf8, 6, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): addBatteryData
V/MediaPlayerService( 1929): wait for playback complete
I/AudioPlayer( 1929): First fillBuffer call!!
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1929): postAudioEOS delayUs (0)
V/AwesomePlayer( 1929): onCheckAudioStatus
V/AwesomePlayer( 1929): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1929): onStreamDone
V/AwesomePlayer( 1929): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1929): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b3cf8, 2, 0, 0)
V/AudioCache( 1929): playback complete - thread will wake up later
V/AwesomePlayer( 1929): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b3cf8, 7, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1929): addBatteryData
V/AudioCache( 1929): wait - success
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b3cf8, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop() sendCommand(0x48, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1929): reset out
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1929): SecMediaClock destructor
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): ~StagefrightPlayer
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/AwesomePlayer( 1929): destructor
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/MediaPlayer( 7525): decode(62, 26954540, 5085)
V/MediaPlayerService( 1929): decode(27, 26954540, 5085)
V/MediaPlayerService( 1929): player type = 3
V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): constructor
V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): StagefrightPlayer
V/AwesomePlayer( 1929): setListener
V/StagefrightPlayer( 1929): initCheck
V/AwesomePlayer( 1929): setAudioSink
V/StagefrightPlayer( 1929): setDataSource(27, 26954540, 5085)
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x44262e90, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/AwesomePlayer( 1929): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1929): mBitrate = -1 bits/sec
V/AwesomePlayer( 1929): current audio track index (0) is added to vector
V/AwesomePlayer( 1929): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1929): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1929): prepare
V/AwesomePlayer( 1929): prepareAsync
V/MediaPlayerService( 1929): wait for prepare
V/AwesomePlayer( 1929): onPrepareAsyncEvent
I/SecMediaClock( 1929): SecMediaClock constructor
I/SecMediaClock( 1929): reset
V/AwesomePlayer( 1929): initAudioDecoder
V/AwesomePlayer( 1929): checkOffloadExceptions is true
I/OMXCodec( 1929): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1929): mDispatchers.add
I/OMXCodec( 1929): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1929): finishAsyncPrepare_l
V/AwesomePlayer( 1929): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1929): notify(0x44262e90, 200, 973, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x44262e90, 5, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x44262e90, 1, 0, 0)
V/AudioCache( 1929): prepared
V/AudioCache( 1929): wait - success
V/MediaPlayerService( 1929): start
V/StagefrightPlayer( 1929): start
V/AwesomePlayer( 1929): play
V/AwesomePlayer( 1929): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1929): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1929): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1929): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x44262e90, 6, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): addBatteryData
V/MediaPlayerService( 1929): wait for playback complete
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1929): postAudioEOS delayUs (0)
V/AwesomePlayer( 1929): onCheckAudioStatus
V/AwesomePlayer( 1929): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1929): onStreamDone
V/AwesomePlayer( 1929): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1929): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x44262e90, 2, 0, 0)
V/AudioCache( 1929): playback complete - thread will wake up later
V/AwesomePlayer( 1929): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x44262e90, 7, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1929): addBatteryData
V/AudioCache( 1929): wait - success
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x44262e90, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop() sendCommand(0x49, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1929): reset out
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1929): SecMediaClock destructor
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): ~StagefrightPlayer
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/AwesomePlayer( 1929): destructor
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/MediaPlayer( 7525): decode(63, 26959684, 21552)
V/MediaPlayerService( 1929): decode(26, 26959684, 21552)
V/MediaPlayerService( 1929): player type = 3
V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): constructor
V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): StagefrightPlayer
V/AwesomePlayer( 1929): setListener
V/StagefrightPlayer( 1929): initCheck
V/AwesomePlayer( 1929): setAudioSink
V/StagefrightPlayer( 1929): setDataSource(26, 26959684, 21552)
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b53b8, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/AwesomePlayer( 1929): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1929): mBitrate = -1 bits/sec
V/AwesomePlayer( 1929): current audio track index (0) is added to vector
V/AwesomePlayer( 1929): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1929): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1929): prepare
V/AwesomePlayer( 1929): prepareAsync
V/MediaPlayerService( 1929): wait for prepare
V/AwesomePlayer( 1929): onPrepareAsyncEvent
I/SecMediaClock( 1929): SecMediaClock constructor
I/SecMediaClock( 1929): reset
V/AwesomePlayer( 1929): initAudioDecoder
V/AwesomePlayer( 1929): checkOffloadExceptions is true
I/OMXCodec( 1929): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1929): mDispatchers.add
I/OMXCodec( 1929): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1929): finishAsyncPrepare_l
V/AwesomePlayer( 1929): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1929): notify(0x443b53b8, 200, 973, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b53b8, 5, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b53b8, 1, 0, 0)
V/AudioCache( 1929): prepared
V/AudioCache( 1929): wait - success
V/MediaPlayerService( 1929): start
V/StagefrightPlayer( 1929): start
V/AwesomePlayer( 1929): play
V/AwesomePlayer( 1929): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1929): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1929): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1929): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b53b8, 6, 0, 0)
I/AudioPlayer( 1929): First fillBuffer call!!
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): addBatteryData
V/MediaPlayerService( 1929): wait for playback complete
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1929): postAudioEOS delayUs (0)
V/AwesomePlayer( 1929): onCheckAudioStatus
V/AwesomePlayer( 1929): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1929): onStreamDone
V/AwesomePlayer( 1929): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1929): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b53b8, 2, 0, 0)
V/AudioCache( 1929): playback complete - thread will wake up later
V/AwesomePlayer( 1929): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b53b8, 7, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1929): addBatteryData
V/AudioCache( 1929): wait - success
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b53b8, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop() sendCommand(0x4a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1929): reset out
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1929): SecMediaClock destructor
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): ~StagefrightPlayer
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/AwesomePlayer( 1929): destructor
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/MediaPlayer( 7525): decode(64, 34130460, 4230)
V/MediaPlayerService( 1929): decode(26, 34130460, 4230)
V/MediaPlayerService( 1929): player type = 3
V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): constructor
V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): StagefrightPlayer
V/AwesomePlayer( 1929): setListener
V/StagefrightPlayer( 1929): initCheck
V/AwesomePlayer( 1929): setAudioSink
V/StagefrightPlayer( 1929): setDataSource(26, 34130460, 4230)
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x44262778, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/AwesomePlayer( 1929): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1929): mBitrate = -1 bits/sec
V/AwesomePlayer( 1929): current audio track index (0) is added to vector
V/AwesomePlayer( 1929): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1929): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1929): prepare
V/AwesomePlayer( 1929): prepareAsync
V/MediaPlayerService( 1929): wait for prepare
V/AwesomePlayer( 1929): onPrepareAsyncEvent
I/SecMediaClock( 1929): SecMediaClock constructor
I/SecMediaClock( 1929): reset
V/AwesomePlayer( 1929): initAudioDecoder
V/AwesomePlayer( 1929): checkOffloadExceptions is true
I/OMXCodec( 1929): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1929): mDispatchers.add
I/OMXCodec( 1929): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1929): finishAsyncPrepare_l
V/AwesomePlayer( 1929): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1929): notify(0x44262778, 200, 973, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x44262778, 5, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x44262778, 1, 0, 0)
V/AudioCache( 1929): prepared
V/AudioCache( 1929): wait - success
V/MediaPlayerService( 1929): start
V/StagefrightPlayer( 1929): start
V/AwesomePlayer( 1929): play
V/AwesomePlayer( 1929): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1929): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 1929): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer( 1929): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x44262778, 6, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): addBatteryData
V/MediaPlayerService( 1929): wait for playback complete
I/AudioPlayer( 1929): First fillBuffer call!!
V/AwesomePlayer( 1929): postAudioEOS delayUs (0)
V/AwesomePlayer( 1929): onCheckAudioStatus
V/AwesomePlayer( 1929): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1929): onStreamDone
V/AwesomePlayer( 1929): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1929): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x44262778, 2, 0, 0)
V/AudioCache( 1929): playback complete - thread will wake up later
V/AwesomePlayer( 1929): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x44262778, 7, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1929): addBatteryData
V/AudioCache( 1929): wait - success
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x44262778, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop() sendCommand(0x4b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1929): reset out
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1929): SecMediaClock destructor
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): ~StagefrightPlayer
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/AwesomePlayer( 1929): destructor
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/MediaPlayer( 7525): decode(65, 26923896, 9400)
V/MediaPlayerService( 1929): decode(26, 26923896, 9400)
V/MediaPlayerService( 1929): player type = 3
V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): constructor
V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): StagefrightPlayer
V/AwesomePlayer( 1929): setListener
V/StagefrightPlayer( 1929): initCheck
V/AwesomePlayer( 1929): setAudioSink
V/StagefrightPlayer( 1929): setDataSource(26, 26923896, 9400)
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443be190, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/AwesomePlayer( 1929): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1929): mBitrate = -1 bits/sec
V/AwesomePlayer( 1929): current audio track index (0) is added to vector
V/AwesomePlayer( 1929): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1929): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1929): prepare
V/AwesomePlayer( 1929): prepareAsync
,V/MediaPlayerService( 1929): wait for prepare
,V/AwesomePlayer( 1929): onPrepareAsyncEvent
I/SecMediaClock( 1929): SecMediaClock constructor
I/SecMediaClock( 1929): reset
V/AwesomePlayer( 1929): initAudioDecoder
,V/AwesomePlayer( 1929): checkOffloadExceptions is true
,I/OMXCodec( 1929): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 1929): mDispatchers.add
I/OMXCodec( 1929): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1929): finishAsyncPrepare_l
V/AwesomePlayer( 1929): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1929): notify(0x443be190, 200, 973, 0)
V/AudioCache( 1929): ignored
,V/AwesomePlayer( 1929): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443be190, 5, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443be190, 1, 0, 0)
V/AudioCache( 1929): prepared
V/AudioCache( 1929): wait - success
V/MediaPlayerService( 1929): start
V/StagefrightPlayer( 1929): start
V/AwesomePlayer( 1929): play
V/AwesomePlayer( 1929): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1929): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache( 1929): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer( 1929): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443be190, 6, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): addBatteryData
V/MediaPlayerService( 1929): wait for playback complete
,I/AudioPlayer( 1929): First fillBuffer call!!
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1929): postAudioEOS delayUs (0)
V/AwesomePlayer( 1929): onCheckAudioStatus
V/AwesomePlayer( 1929): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1929): onStreamDone
V/AwesomePlayer( 1929): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1929): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443be190, 2, 0, 0)
V/AudioCache( 1929): playback complete - thread will wake up later
V/AwesomePlayer( 1929): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443be190, 7, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1929): addBatteryData
V/AudioCache( 1929): wait - success
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443be190, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop() sendCommand(0x4c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1929): reset out
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1929): SecMediaClock destructor
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): ~StagefrightPlayer
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
,V/AwesomePlayer( 1929): destructor
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1929): mSecMediaClock clear
V/MediaPlayer( 7525): decode(66, 30512272, 44276)
,V/MediaPlayerService( 1929): decode(26, 30512272, 44276)
V/MediaPlayerService( 1929): player type = 3
V/AwesomePlayer( 1929): setDefault
,V/AwesomePlayer( 1929): constructor
V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): StagefrightPlayer
V/AwesomePlayer( 1929): setListener
V/StagefrightPlayer( 1929): initCheck
V/AwesomePlayer( 1929): setAudioSink
,V/StagefrightPlayer( 1929): setDataSource(26, 30512272, 44276)
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x435174f8, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1929): mSecMediaClock clear
,V/AwesomePlayer( 1929): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1929): mBitrate = -1 bits/sec
V/AwesomePlayer( 1929): current audio track index (0) is added to vector
V/AwesomePlayer( 1929): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1929): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1929): prepare
,V/AwesomePlayer( 1929): prepareAsync
V/MediaPlayerService( 1929): wait for prepare
V/AwesomePlayer( 1929): onPrepareAsyncEvent
I/SecMediaClock( 1929): SecMediaClock constructor
I/SecMediaClock( 1929): reset
V/AwesomePlayer( 1929): initAudioDecoder
V/AwesomePlayer( 1929): checkOffloadExceptions is true
,I/OMXCodec( 1929): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1929): mDispatchers.add
,I/OMXCodec( 1929): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1929): finishAsyncPrepare_l
V/AwesomePlayer( 1929): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1929): notify(0x435174f8, 200, 973, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x435174f8, 5, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x435174f8, 1, 0, 0)
V/AudioCache( 1929): prepared
V/AudioCache( 1929): wait - success
V/MediaPlayerService( 1929): start
,V/StagefrightPlayer( 1929): start
V/AwesomePlayer( 1929): play
V/AwesomePlayer( 1929): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1929): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
,I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1929): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1929): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
I/AudioPlayer( 1929): First fillBuffer call!!
,V/AudioCache( 1929): notify(0x435174f8, 6, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): addBatteryData
,V/MediaPlayerService( 1929): wait for playback complete
,D/SO_AGENT( 7268): [ServerTimeReceiver.java(Line:44/Method:onReceive)] Receive broadcast meassage:android.intent.action.TIME_SET
,I/SO_AGENT( 7268): [ServerTimeReceiver.java(Line:47/Method:onReceive)] No action is available before server time settings
,I/SA      ( 6414): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1929): postAudioEOS delayUs (0)
V/AwesomePlayer( 1929): onCheckAudioStatus
V/AwesomePlayer( 1929): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1929): onStreamDone
V/AwesomePlayer( 1929): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1929): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x435174f8, 2, 0, 0)
V/AudioCache( 1929): playback complete - thread will wake up later
V/AwesomePlayer( 1929): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x435174f8, 7, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1929): addBatteryData
V/AudioCache( 1929): wait - success
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x435174f8, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop() sendCommand(0x4d, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1929): reset out
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1929): SecMediaClock destructor
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): ~StagefrightPlayer
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/AwesomePlayer( 1929): destructor
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
,V/MediaPlayer( 7525): decode(67, 30472480, 29256)
,V/MediaPlayerService( 1929): decode(26, 30472480, 29256)
V/MediaPlayerService( 1929): player type = 3
V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): constructor
V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): StagefrightPlayer
V/AwesomePlayer( 1929): setListener
V/StagefrightPlayer( 1929): initCheck
V/AwesomePlayer( 1929): setAudioSink
V/StagefrightPlayer( 1929): setDataSource(26, 30472480, 29256)
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x445eea28, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1929): mSecMediaClock clear
V/AwesomePlayer( 1929): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1929): mBitrate = -1 bits/sec
V/AwesomePlayer( 1929): current audio track index (0) is added to vector
V/AwesomePlayer( 1929): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1929): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1929): prepare
V/AwesomePlayer( 1929): prepareAsync
V/MediaPlayerService( 1929): wait for prepare
V/AwesomePlayer( 1929): onPrepareAsyncEvent
I/SecMediaClock( 1929): SecMediaClock constructor
I/SecMediaClock( 1929): reset
V/AwesomePlayer( 1929): initAudioDecoder
V/AwesomePlayer( 1929): checkOffloadExceptions is true
,I/OMXCodec( 1929): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1929): mDispatchers.add
I/OMXCodec( 1929): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1929): finishAsyncPrepare_l
V/AwesomePlayer( 1929): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1929): notify(0x445eea28, 200, 973, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x445eea28, 5, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x445eea28, 1, 0, 0)
V/AudioCache( 1929): prepared
V/AudioCache( 1929): wait - success
V/MediaPlayerService( 1929): start
V/StagefrightPlayer( 1929): start
V/AwesomePlayer( 1929): play
V/AwesomePlayer( 1929): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1929): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1929): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1929): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x445eea28, 6, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): addBatteryData
,V/MediaPlayerService( 1929): wait for playback complete
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1929): postAudioEOS delayUs (0)
V/AwesomePlayer( 1929): onCheckAudioStatus
V/AwesomePlayer( 1929): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1929): onStreamDone
V/AwesomePlayer( 1929): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1929): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x445eea28, 2, 0, 0)
V/AudioCache( 1929): playback complete - thread will wake up later
V/AwesomePlayer( 1929): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x445eea28, 7, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1929): addBatteryData
V/AudioCache( 1929): wait - success
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x445eea28, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop() sendCommand(0x4e, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1929): reset out
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1929): SecMediaClock destructor
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): ~StagefrightPlayer
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/AwesomePlayer( 1929): destructor
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1929): mSecMediaClock clear
V/MediaPlayer( 7525): decode(68, 34078380, 52024)
,V/MediaPlayerService( 1929): decode(26, 34078380, 52024)
V/MediaPlayerService( 1929): player type = 3
V/AwesomePlayer( 1929): setDefault
,V/AwesomePlayer( 1929): constructor
V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): StagefrightPlayer
V/AwesomePlayer( 1929): setListener
V/StagefrightPlayer( 1929): initCheck
V/AwesomePlayer( 1929): setAudioSink
V/StagefrightPlayer( 1929): setDataSource(26, 34078380, 52024)
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x435174f8, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1929): mSecMediaClock clear
V/AwesomePlayer( 1929): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1929): mBitrate = -1 bits/sec
V/AwesomePlayer( 1929): current audio track index (0) is added to vector
V/AwesomePlayer( 1929): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1929): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1929): prepare
V/AwesomePlayer( 1929): prepareAsync
V/MediaPlayerService( 1929): wait for prepare
V/AwesomePlayer( 1929): onPrepareAsyncEvent
I/SecMediaClock( 1929): SecMediaClock constructor
I/SecMediaClock( 1929): reset
V/AwesomePlayer( 1929): initAudioDecoder
V/AwesomePlayer( 1929): checkOffloadExceptions is true
,I/OMXCodec( 1929): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1929): mDispatchers.add
I/OMXCodec( 1929): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
D/Mms/MessagingNotification( 5538): [start]    nonBlockingUpdateMessageIndicator()
V/AwesomePlayer( 1929): finishAsyncPrepare_l
V/AwesomePlayer( 1929): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1929): notify(0x435174f8, 200, 973, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x435174f8, 5, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x435174f8, 1, 0, 0)
V/AudioCache( 1929): prepared
V/AudioCache( 1929): wait - success
V/MediaPlayerService( 1929): start
V/StagefrightPlayer( 1929): start
V/AwesomePlayer( 1929): play
V/AwesomePlayer( 1929): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1929): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1929): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer( 1929): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x435174f8, 6, 0, 0)
V/AudioCache( 1929): ignored
,V/AwesomePlayer( 1929): addBatteryData
,V/MediaPlayerService( 1929): wait for playback complete
,D/Mms/MessagingNotification( 5538): sDisableVibrateForCamera = false
,D/Mms/MessagingNotification( 5538): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 5538): isDefault true
,I/SELinux ( 7611): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7611):  
,I/ActivityManager( 2408): Killing 6387:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty #43
,I/SELinux ( 7611): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7611):  
I/SELinux ( 7611):  
,I/SELinux ( 7611): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7611): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7611): >>>>> Normal User
,E/dalvikvm( 7611): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10064 ]
,E/SELinux ( 7611): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1929): postAudioEOS delayUs (0)
V/AwesomePlayer( 1929): onCheckAudioStatus
V/AwesomePlayer( 1929): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1929): onStreamDone
V/AwesomePlayer( 1929): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1929): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x435174f8, 2, 0, 0)
V/AudioCache( 1929): playback complete - thread will wake up later
V/AwesomePlayer( 1929): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x435174f8, 7, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1929): addBatteryData
V/AudioCache( 1929): wait - success
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x435174f8, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop() sendCommand(0x4f, OMX_CommandStateSet, OMX_StateIdle)
,D/TP/MmsSmsProvider( 2752): match 200:Elapsed time : 27.537 ms
,D/TP/MmsSmsProvider( 2752): match 8:Elapsed time : 29.430 ms
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1929): reset out
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1929): SecMediaClock destructor
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): ~StagefrightPlayer
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
,V/AwesomePlayer( 1929): destructor
,V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1929): mSecMediaClock clear
,V/MediaPlayer( 7525): decode(69, 30556608, 9226)
,V/MediaPlayerService( 1929): decode(26, 30556608, 9226)
V/MediaPlayerService( 1929): player type = 3
V/AwesomePlayer( 1929): setDefault
,V/AwesomePlayer( 1929): constructor
V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): StagefrightPlayer
V/AwesomePlayer( 1929): setListener
V/StagefrightPlayer( 1929): initCheck
V/AwesomePlayer( 1929): setAudioSink
V/StagefrightPlayer( 1929): setDataSource(26, 30556608, 9226)
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x445f56d0, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
,D/TimaKeyStoreProvider( 7611): in addTimaSignatureService
V/AwesomePlayer( 1929): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1929): mBitrate = -1 bits/sec
V/AwesomePlayer( 1929): current audio track index (0) is added to vector
V/AwesomePlayer( 1929): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1929): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1929): prepare
V/AwesomePlayer( 1929): prepareAsync
V/MediaPlayerService( 1929): wait for prepare
V/AwesomePlayer( 1929): onPrepareAsyncEvent
I/SecMediaClock( 1929): SecMediaClock constructor
I/SecMediaClock( 1929): reset
V/AwesomePlayer( 1929): initAudioDecoder
V/AwesomePlayer( 1929): checkOffloadExceptions is true
,I/OMXCodec( 1929): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1929): mDispatchers.add
I/OMXCodec( 1929): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/TimaKeyStoreProvider( 7611): Cannot add TimaSignature Service, License check Failed
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1929): finishAsyncPrepare_l
V/AwesomePlayer( 1929): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1929): notify(0x445f56d0, 200, 973, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x445f56d0, 5, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x445f56d0, 1, 0, 0)
V/AudioCache( 1929): prepared
V/AudioCache( 1929): wait - success
V/MediaPlayerService( 1929): start
V/StagefrightPlayer( 1929): start
V/AwesomePlayer( 1929): play
V/AwesomePlayer( 1929): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1929): startAudioPlayer_l, sendErrorNotification (0)
,D/ActivityThread( 7611): Added TimaKesytore provider
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1929): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1929): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x445f56d0, 6, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): addBatteryData
,V/MediaPlayerService( 1929): wait for playback complete
,I/AudioPlayer( 1929): First fillBuffer call!!
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1929): postAudioEOS delayUs (0)
V/AwesomePlayer( 1929): onCheckAudioStatus
V/AwesomePlayer( 1929): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1929): onStreamDone
V/AwesomePlayer( 1929): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1929): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x445f56d0, 2, 0, 0)
V/AudioCache( 1929): playback complete - thread will wake up later
V/AwesomePlayer( 1929): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x445f56d0, 7, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1929): addBatteryData
V/AudioCache( 1929): wait - success
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x445f56d0, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop() sendCommand(0x50, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1929): reset out
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1929): SecMediaClock destructor
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): ~StagefrightPlayer
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/AwesomePlayer( 1929): destructor
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
,V/MediaPlayer( 7525): decode(70, 26989388, 4509)
,V/MediaPlayerService( 1929): decode(26, 26989388, 4509)
V/MediaPlayerService( 1929): player type = 3
V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): constructor
V/AwesomePlayer( 1929): setDefault
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): StagefrightPlayer
V/AwesomePlayer( 1929): setListener
V/StagefrightPlayer( 1929): initCheck
V/AwesomePlayer( 1929): setAudioSink
V/StagefrightPlayer( 1929): setDataSource(26, 26989388, 4509)
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b3cf8, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1929): mSecMediaClock clear
V/AwesomePlayer( 1929): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1929): mBitrate = -1 bits/sec
V/AwesomePlayer( 1929): current audio track index (0) is added to vector
V/AwesomePlayer( 1929): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1929): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1929): prepare
V/AwesomePlayer( 1929): prepareAsync
,V/MediaPlayerService( 1929): wait for prepare
V/AwesomePlayer( 1929): onPrepareAsyncEvent
I/SecMediaClock( 1929): SecMediaClock constructor
I/SecMediaClock( 1929): reset
V/AwesomePlayer( 1929): initAudioDecoder
V/AwesomePlayer( 1929): checkOffloadExceptions is true
,I/OMXCodec( 1929): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1929): mDispatchers.add
I/OMXCodec( 1929): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1929): finishAsyncPrepare_l
V/AwesomePlayer( 1929): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1929): notify(0x443b3cf8, 200, 973, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b3cf8, 5, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b3cf8, 1, 0, 0)
V/AudioCache( 1929): prepared
V/AudioCache( 1929): wait - success
V/MediaPlayerService( 1929): start
V/StagefrightPlayer( 1929): start
V/AwesomePlayer( 1929): play
V/AwesomePlayer( 1929): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1929): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1929):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1929): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1929): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b3cf8, 6, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): addBatteryData
,V/MediaPlayerService( 1929): wait for playback complete
V/AwesomePlayer( 1929): postAudioEOS delayUs (0)
V/AwesomePlayer( 1929): onCheckAudioStatus
V/AwesomePlayer( 1929): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1929): onStreamDone
V/AwesomePlayer( 1929): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1929): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b3cf8, 2, 0, 0)
V/AudioCache( 1929): playback complete - thread will wake up later
V/AwesomePlayer( 1929): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b3cf8, 7, 0, 0)
V/AudioCache( 1929): ignored
,V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1929): addBatteryData
V/AudioCache( 1929): wait - success
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1929): notify(0x443b3cf8, 8, 0, 0)
V/AudioCache( 1929): ignored
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stop() sendCommand(0x51, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1929): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1929): reset out
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1929): SecMediaClock destructor
V/AwesomePlayer( 1929): mSecMediaClock clear
V/StagefrightPlayer( 1929): ~StagefrightPlayer
V/StagefrightPlayer( 1929): reset
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1929): mSecMediaClock clear
V/AwesomePlayer( 1929): destructor
V/AwesomePlayer( 1929): reset_l()
V/AwesomePlayer( 1929): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1929): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1929): mAudioTrackVector clear
V/AwesomePlayer( 1929): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1929): mSecMediaClock clear
,D/BadgeProvider( 7434): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/BadgeProvider( 7434): sendNotify entered. [uri] : content://com.sec.badge/apps/2
,D/BadgeProvider( 7434): sendNotify, [notify] : null
D/BadgeProvider( 7434): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 7434): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7434): update, [UpdateCount] : 1
,D/Launcher.Model( 2777): reloadBadges entered.
,D/Mms/MessagingNotification( 5538): setBadgeCount(), count=0
,D/MessagingNotification( 5538): remove alarm
D/dalvikvm( 7611): GC_CONCURRENT freed 2998K, 30% free 9570K/13616K, paused 4ms+2ms, total 39ms
,D/dalvikvm( 7611): WAIT_FOR_CONCURRENT_GC blocked 28ms
,I/GAV2    ( 7362): Thread[GAThread,5,main]: No campaign data found.
,D/Mms/MessagingNotification( 5538): updateAllHistoryAsRead()
,D/Mms/MessagingNotification( 5538): [end]    nonBlockingUpdateMessageIndicator()
,D/com.samsung.app( 7332): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidintentactionTIME_SET
I/ Time Manager ( 7611): Time Difference not stored. TIME_DIFFERENCE
,D/com.samsung.app( 7332): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/SELinux ( 7636): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7636):  
,I/ActivityManager( 2408): Killing 4769:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
,D/dalvikvm( 2408): GC_EXPLICIT freed 1846K, 69% free 24582K/78468K, paused 10ms+22ms, total 197ms
I/SELinux ( 7636): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7636):  
I/SELinux ( 7636):  
,I/SELinux ( 7636): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7636): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7636): >>>>> Normal User
,E/dalvikvm( 7636): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10088 ]
,E/SELinux ( 7636): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7636): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7636): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7636): Added TimaKesytore provider
,D/dalvikvm( 7636): GC_FOR_ALLOC freed 3019K, 30% free 9552K/13616K, paused 27ms, total 27ms
,D/GetCommittedConfigurationOperation( 2854): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 7636): GC_CONCURRENT freed 205K, 30% free 9578K/13616K, paused 3ms+6ms, total 37ms
,D/dalvikvm( 2854): GC_CONCURRENT freed 1755K, 21% free 11380K/14260K, paused 6ms+7ms, total 76ms
,D/GetCommittedConfigurationOperation( 2854): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/SELinux ( 7650): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7650):  
I/ActivityManager( 2408): Killing 6432:com.sec.android.service.cm/u0a82 (adj 15): empty #43
,I/SELinux ( 7650): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7650):  
I/SELinux ( 7650):  
,I/SELinux ( 7650): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7650): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7650): >>>>> Normal User
,E/dalvikvm( 7650): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 7650): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7650): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7650): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7650): Added TimaKesytore provider
,W/Uploader( 2854):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 2854): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 7650): GC_CONCURRENT freed 2998K, 30% free 9573K/13616K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 7650): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/elm:14132( 7650): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14132( 7650): ELMEngine.ELMEngine( context ).
,D/elm:14132( 7650): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 7650): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,I/knox    ( 4962): MainReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,D/elm:14132( 7650): ElmAgentService : onCreate()
,W/ContextImpl( 4962): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 4962): MainReceiver.listeningToTimeDateChanges( context, intent ).
,I/knox    ( 4962): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
D/elm:14132( 7650): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
D/knox    ( 4962): KNOXAgentService : onCreate()
D/knox    ( 4962): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 4962): KNOXAgentService. startJobThread() start
D/knox    ( 4962): KNOXAgentService. JobThread()
D/knox    ( 4962): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 4962): KNOXAgentService. startJobThread() wait
D/elm:14132( 7650): ELMAgentService.listeningToTimeDateChanges( context, intent ).
D/elm:14132( 7650): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:14132( 7650): ModuleBase.resetCalllogAPIAlarm()
I/SELinux ( 7665): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7665):  
,D/knox    ( 4962): KNOXAgentService : onDestroy().,
,D/knox    ( 4962): ModuleBase.cancelAllAlarmManageModule(),
,D/elm:14132( 7650): ModuleBase.ModifySetAlarm(),
D/elm:14132( 7650): MDMBridge.getInstance()
,D/elm:14132( 7650): MDMBridge.getAllLicenseInfoFromSDK(),
,D/elm:14132( 7650): ElmAgentService : onDestroy().,
,I/ActivityManager( 2408): Killing 6445:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty #43,
D/GetCommittedConfigurationOperation( 2854): no corresponding serverToken: com.google.android.gms.playlog.uploader
I/SELinux ( 7665): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7665):  
I/SELinux ( 7665):  
I/SELinux ( 7665): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7665): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7665): >>>>> Normal User
E/dalvikvm( 7665): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10145 ]
E/SELinux ( 7665): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7665): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7665): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7665): Added TimaKesytore provider
,D/dalvikvm( 7665): GC_CONCURRENT freed 3003K, 30% free 9567K/13616K, paused 3ms+2ms, total 21ms,
,D/dalvikvm( 7665): WAIT_FOR_CONCURRENT_GC blocked 5ms,
,I/SELinux ( 7678): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7678):  
,D/GetCommittedConfigurationOperation( 2854): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/SELinux ( 7678): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7678):  
I/SELinux ( 7678):  
,I/SELinux ( 7678): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7678): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7678): >>>>> Normal User
,E/dalvikvm( 7678): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10168 ]
,E/SELinux ( 7678): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/SPPClientService( 6570): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,D/TimaKeyStoreProvider( 7678): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7678): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7678): Added TimaKesytore provider
,V/AlarmManager( 2408):  next == MAX_VALUE
,E/SPPClientService( 6570): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,D/dalvikvm( 7678): GC_CONCURRENT freed 2988K, 30% free 9577K/13616K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 7678): WAIT_FOR_CONCURRENT_GC blocked 9ms
,E/SPPClientService( 6570): [a] [ConnectionManager] Connection is already disconnected.
V/AlarmManager( 2408): waitForAlarm result :4
V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/ActivityManager( 2408): Killing 6471:com.samsung.helphub/1000 (adj 15): empty #43
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionTIME_SET, run:true
D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5245): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5245): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng,
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/GetCommittedConfigurationOperation( 2854): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/comdaemonstockapp( 5245): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 5245): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,I/CheckinService( 3278): Checkin interval check for package: unspecified last checkin: 1447838164620 min interval config: 0 actual interval: 506904203
,D/GetCommittedConfigurationOperation( 2854): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/CaptivePortalTracker( 2408): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler },
,D/ConnectivityService( 2408): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null,
,D/CaptivePortalTracker( 2408): Checking http://216.58.209.46/generate_204,
W/ActivityThread( 2408): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/System.out( 2408): Thread-160(HTTPLog):isShipBuild true,
,I/System.out( 2408): Thread-160(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false,
,D/CaptivePortalTracker( 2408): Don't send network conditions - lacking user consent.,
,D/CaptivePortalTracker( 2408): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 2408): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/GetCommittedConfigurationOperation( 2854): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/CaptivePortalTracker( 2408): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SELinux ( 7696): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7696):  
D/ConnectivityService( 2408): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/ActivityManager( 2408): Waited long enough for: ServiceRecord{456acab8 u0 pl.k2.droidoaudioteka/.services.DownloadService}
,I/ActivityManager( 2408): Waited long enough for: ServiceRecord{4567e398 u0 pl.k2.droidoaudioteka/.services.PlayerService}
,I/SELinux ( 7696): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7696):  
I/SELinux ( 7696):  
,I/SELinux ( 7696): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7696): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7696): >>>>> Normal User
,E/dalvikvm( 7696): >>>>> com.android.providers.calendar [ userId:0 | appId:10045 ]
,E/SELinux ( 7696): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7696): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7696): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7696): Added TimaKesytore provider
,D/dalvikvm( 7696): GC_CONCURRENT freed 2985K, 30% free 9576K/13612K, paused 4ms+2ms, total 25ms
,D/dalvikvm( 7696): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/Headlines( 7349): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 7349): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7349): Breath 7389 latestRequest time : 1448345062193 current time : 1448345069582
,D/Mms/MessagesLockscreen( 5538): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
,W/Binder  ( 2582): Caught a RuntimeException from the binder stub implementation.
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
,E/JavaBinder( 2582): *** Uncaught remote exception!  (Exceptions are not yet supported across processes.)
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
,E/SPPClientService( 6570): [g] getNetMCC return empty string
,E/SPPClientService( 6570): [g] getNetMNC return empty string
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 360, Delta = 10
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4350, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 2408): Killing 6484:com.sec.kidsplat.installer/u0a160 (adj 15): empty #43
,E/SPPClientService( 6570): [b] __ProvisionReply__
,E/SPPClientService( 6570): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 6570): [d] null
,V/AlarmManager( 2408):  next == MAX_VALUE
,E/SPPClientService( 6570): [g] getPLMN return empty string
,E/SPPClientService( 6570): [b] SharedConstants.WHAT_PROV_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 6570): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 6570): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 6570): [g] getNetMCC return empty string
,D/AmoledAdjustTimer( 2408): prevTemp = 304, currTemp = 306, prevStep = 4, currStep = 4
,D/dalvikvm( 6570): GC_CONCURRENT freed 2173K, 24% free 10438K/13656K, paused 3ms+3ms, total 35ms
,D/TimaService( 2408): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2408): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2408): TimaServiceHandler.handleMessage what =1
I/TLC_TIMA_PKM_initialize( 2408): initializing...
I/TLC_TIMA_PKM_initialize( 2408): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 2408): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2408): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2408): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2408): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2408): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2408): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2408): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2408): device_id = 0x0
I/TZ: mc_tlc_communication( 2408): tlc_open() was called
I/TZ: mc_tlc_communication( 2408): Opening MobiCore device
I/TZ: mc_tlc_communication( 2408): Allocating WSM for TCI
I/TZ: mc_tlc_communication( 2408): Opening the session
,I/TZ: mc_tlc_communication( 2408): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2408): Trustlet response is completed
,D/PreloadUpdateManagerStateMachine( 6558): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 6558): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6558): entry::CHECK_TIMEOUT_FOR_UPDATE,
,D/hcjo    ( 6558): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6558): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6558): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 6558): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6558): entry::IDLE
,E/SPPClientService( 6570): [b] __InitReply__
,I/ActivityManager( 2408): Waited long enough for: ServiceRecord{4574b228 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,I/jxcore-log( 6995): Attempting to connect to the test coordinator server
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): Attempting to connect to the test coordinator server
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): Attempting to connect to the test coordinator server
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): Attempting to connect to the test coordinator server
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): Attempting to connect to the test coordinator server
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): Attempting to connect to the test coordinator server
I/jxcore-log( 6995): 
I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/jxcore-log( 6995): Attempting to connect to the test coordinator server
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): Attempting to connect to the test coordinator server
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): Test app app.js loaded
I/jxcore-log( 6995): 
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 360, Delta = 0
,I/jxcore-log( 6995): {"type":"test","name":"setup","id":0}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): LogCallback not set !!!!
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 6995): DBG, CoordinatorConnector connect called
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): DBG, CoordinatorConnector connect called
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): DBG, CoordinatorConnector connect called
I/jxcore-log( 6995): 
I/jxcore-log( 6995): DBG, CoordinatorConnector connect called
I/jxcore-log( 6995): 
I/jxcore-log( 6995): DBG, CoordinatorConnector connect called
I/jxcore-log( 6995): 
I/jxcore-log( 6995): DBG, CoordinatorConnector connect called
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): DBG, CoordinatorConnector connect called
I/jxcore-log( 6995): 
I/jxcore-log( 6995): DBG, CoordinatorConnector connect called
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): DBG, CoordinatorConnector connect called
I/jxcore-log( 6995): 
,D/BatteryService( 2408): level:100, scale:100, status:3, health:9, present:true, voltage: 4356, temperature: 306, technology: Li-ion, AC powered:false, USB powered:false, Wireless powered:false, icon:17303678, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 3 (uid: 0 pid: 0) 
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
,D/lights  ( 2408): led_pattern : 0 +
D/BatteryService( 2408): turn off LED
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
D/lights  ( 2408): led_pattern : 0 -
D/lights  ( 2408): button : 1 +
D/PowerManagerService( 2408): [api] updateIsPoweredLocked : mIsPowered: false mPlugType: 0
I/PowerManagerService( 2408): !@[ps] Screen__On :  powered change
I/PowerManagerService( 2408): Waking up from sleep...
D/PowerManagerService( 2408): Screen Readiness Inspection requested: mNestCount=1
D/PowerManagerService( 2408): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2408): [s] WAKEFULNESS_AWAKE
D/PowerManagerService( 2408): [s] UserActivityState : 0 -> 1
D/PowerManagerService( 2408): [PWL] sb acquire: PowerManagerService.Display
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/lights  ( 2408): button : 1 -
D/Sensors ( 2408): LightSensor setDelay = 200000000
D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
D/Sensors ( 2408): Light sensor flush: not enabled 0
D/Sensors ( 2408): LightSensor enable = 1
,D/Sensors ( 2408): LightSensor enableSensor = 1
D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 1
,I/Sensors ( 2408): HAL: batch Dry Run is complete
,I/Sensors ( 2408): HAL:resetDataRates mEnabled=4
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/PowerManagerService( 2408): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 3ms
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2408): [DAB] no lux value from sensor manager
D/DisplayPowerController( 2408): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/libsuspend( 2408): !@[s] autosuspend_autosleep_disable
,I/libsuspend( 2408): !@[s] autosuspend_autosleep_disable done
D/PowerManagerService( 2408): unblankAllDisplays() is called.
D/PowerUI ( 2582): Overvoltage/Undervoltage (recovered) so turn on the screen.
,D/PowerManagerService( 2408): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
D/SurfaceFlinger( 1921): Screen acquired, type=0 flinger=0x404f8008
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 65558
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/UsbDeviceManager( 2408): handleMessage -> MSG_POWER_STATE = 0
D/PowerManagerService( 2408): [api] [s] wakeUp (uid: 10019 pid: 2582) eventTime = 317192
D/UsbDeviceManager( 2408): sending intent : ACTION_USB_CABLE_STATE : connected = false
W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:3 health:9
,D/SensorManager( 2408): registerListener :: 2, MPL Accelerometer, 200000, 0,  
D/SensorService( 2408): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2408): AutoRotationSensor::activate (ident=0x79c29310, enabled=1)
D/SensorService( 2408): AutoRotationSensor::AR_init
,I/Sensors ( 2408): HAL: batch Dry Run is complete
,D/PowerManagerService( 2408): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 20ms
,I/Sensors ( 2408): HAL:resetDataRates mEnabled=4
D/NotificationService( 2408): cancelNotificationLocked
D/NotificationService( 2408):  hasClearableItems
D/NotificationService( 2408):  has clearable items no 
,D/NotificationService( 2408): cancelNotificationLocked: cancel alarm
,D/NotificationService( 2408): cancelNotificationLocked: cancel alarm
D/STATUSBAR-StatusBarManagerService( 2408): sendNotification(3) - 5
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/UsbDeviceManager( 2408): received ACTION_POWER_DISCONNECTED = -1
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/RampAnimator( 2408): Light Animator Finished currentValue=8
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SensorManager( 2408): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
,V/KeyguardServiceDelegate( 2408): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@45af4618)
,I/SELinux ( 7737): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7737):  
,D/KeyguardViewMediator( 2582): onScreenTurnedOn, seq = 3
,D/KeyguardViewMediator( 2582): notifyScreenOnLocked
D/KeyguardViewMediator( 2582): handleNotifyScreenOn
D/KeyguardViewManager( 2582): onScreenTurnedOn()
,I/KeyguardEffectViewMain( 2582): *** KeyguardEffectView getInstance ***
V/KeyguardViewManager( 2582): send wm null token: host was null
D/VisualEffectParticleEffect( 2582): KeyguardEffectViewParticleSpace : screenTurnedOn
D/VisualEffectParticleEffect( 2582): screenOnAnimationStart
V/KeyguardServiceDelegate( 2408): **** SHOWN CALLED ****
,D/InputDispatcher( 2408): setInputDispatchMode: enabled=1, frozen=0
,I/SurfaceFlinger( 1921): id=17 Removed FlectronBea (10/10)
,I/SurfaceFlinger( 1921): id=17 Removed FlectronBea (-2/10)
I/WindowManager( 2408): No lock screen! windowToken=null
D/PowerManagerNotifier( 2408): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/PowerManagerService( 2408): Screen Readiness Inspection completed: mNestCount=0
D/DisplayPowerController( 2408): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 2408): !@ElectronBeam exit
D/lights  ( 2408): lcd : 8 +
D/lights  ( 2408): lcd : 8 -
,D/LockPatternUtils( 2582): isPcwEnable = 10
D/DisplayPowerController( 2408): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2408): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/BatteryMeterView( 2582): onDraw batteryColor : -1
,I/SELinux ( 7737): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7737):  
I/SELinux ( 7737):  
,I/SELinux ( 7737): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7737): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7737): >>>>> Normal User
,E/dalvikvm( 7737): >>>>> com.sec.android.Kies [ userId:0 | appId:1000 ]
,E/SELinux ( 7737): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7737): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7737): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7737): Added TimaKesytore provider,
D/SensorService( 2408): AutoRotationSensor::process: Acc  eventTimestamp = 317282800251, previousAccTimestamp = 146337759797, difference = 170945040454 
,D/SensorService( 2408): AutoRotationSensor::reset oldrotation = [100], initState = [1]
,D/DisplayPowerController( 2408): [api] [DAB] onSensorChanged : 1st lux : 0.0,
,D/DisplayPowerController( 2408): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0),
,D/SensorService( 2408): AutoRotationSensor::process: Acc  eventTimestamp = 317349462512, previousAccTimestamp = 146337759797, difference = 171011702715 ,
D/SensorService( 2408):  [AR] 0.3 0.0 9.9
,D/SensorService( 2408): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
D/SurfaceControl( 2408): Excessive delay in unblankDisplay() while turning screen on: 228ms
D/MISC PowerHAL( 2408): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/input/input1/enabled: 1
D/PowerManagerService( 2408): Excessive delay in mDisplayManagerService.unblankAllDisplaysFromPowerManager(): 229ms
,D/LockPatternUtils( 2582): isPcwEnable = 10
,I/FPMS_FingerprintManagerService( 2602): onReceive: android.intent.action.USER_PRESENT
,D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/input/input1/enabled: 1
,D/MISC PowerHAL( 2408): miscpower_set_interactive: /sys/class/input/input0/enabled
,D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/input/input0/enabled: 1,
,D/SamsungIME( 2984): showDlgMsgBox : false true true,
,I/NfcService( 2758): applyRouting return - 2 ,
,D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
,D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/NfcService( 2758): callback == null
D/PalmMotionService( 2408): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/PalmMotionService( 2408): SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService( 2408):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,I/chromium( 6995): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
D/SSRMv2:TSP:AirViewOnOff( 2408): SettingsAirViewInfo:: 000000000
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2408): ACTION_SCREEN_ON
,D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/AudioHardwareTinyALSA( 1929): setParameters(screen_state=on)
,I/SecExternalDisplayIntents_Java( 2408): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,I/chromium( 6995): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/IpRemoteDisplayController( 2408): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2408): Bridge Server is not available
,D/PersonaManagerService( 2408): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 2408): MSG_ACTION_SCREEN_ON called
E/libGLESv2( 6995): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 6995): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/input/input0/enabled: 1
D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 2408): Excessive delay in MISC setInteractive(true) while turning screen on: 160ms
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
,D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
D/PowerManagerService( 2408): Excessive delay in nativeSetInteractive(true): 160ms
D/PowerManagerService( 2408): SecHardwareInterface.setBatteryADC : true
,I/NfcService( 2758): NFC: Screen On & Cover Open
D/STATUSBAR-NetworkController( 2582): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,I/NfcService( 2758): applyRouting return - 2 ,
,E/NfcService( 2758): callback == null,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2,
,D/PhoneStatusBar( 2582): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false,
D/StatusBarManagerService( 2408): semi p:6995,o:f
,D/dalvikvm( 7737): GC_CONCURRENT freed 3002K, 30% free 9566K/13620K, paused 2ms+1ms, total 89ms,
,D/dalvikvm( 7737): WAIT_FOR_CONCURRENT_GC blocked 79ms,
E/libGLESv2( 6995): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 6995): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader,
,I/KIES_RECEIVE( 7737): [APK BnR] Receive KIES_USB_DISCONNECT
E/libGLESv2( 6995): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 6995): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
W/ContextImpl( 7737): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 android.content.ContextWrapper.stopService:511 com.sec.android.Kies.kies_receiver.onReceive:170 android.app.ActivityThread.handleReceiver:2698 
,E/TranscodeReceiver( 5728): onReceive : android.intent.action.ACTION_POWER_DISCONNECTED
,I/ActivityManager( 2408): Killing 6496:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty #43
,I/SELinux ( 7752): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7752):  
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 360, Delta = 0
,I/SELinux ( 7752): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7752):  
I/SELinux ( 7752):  
,I/SELinux ( 7752): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7752): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7752): >>>>> Normal User
,E/dalvikvm( 7752): >>>>> com.google.android.apps.uploader [ userId:0 | appId:10117 ]
,E/SELinux ( 7752): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/QuickConnect[1.1][2] ( 5022): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
,V/QuickConnect[1.1][2] ( 5022): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5022): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
V/QuickConnect[1.1][2] ( 5022): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
D/QuickConnect[1.1][2] ( 5022): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 5022): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 5022): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 5022): BleHelper.startScan - shouldScanBleFg = false
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5245): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionSCREEN_ON
D/PowerManagerService( 2408): [PWL] sb release: PowerManagerService.Broadcasts
,D/TimaKeyStoreProvider( 7752): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7752): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7752): Added TimaKesytore provider
,D/dalvikvm( 7752): GC_CONCURRENT freed 3010K, 30% free 9558K/13620K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7752): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/iu.Environment( 5670): update battery state; isPlugged? false*
I/ActivityManager( 2408): Killing 6508:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty #43
,I/iu.Environment( 3278): update battery state; isPlugged? false*
,I/GCoreUlr( 2736): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_DISCONNECTED}]
,I/iu.UploadsManager( 3278): num queued entries: 0
,I/iu.UploadsManager( 3278): num updated entries: 0
,I/iu.SyncManager( 3278): NEXT; no task
,I/iu.UploadsManager( 5670): num queued entries: 0
,I/iu.UploadsManager( 5670): num updated entries: 0
,I/GCoreUlr( 2736): DispatchingService.onCreate()
,D/PicasaUploader( 7752):    wifiOnlyPhoto changed to true
D/PicasaUploader( 7752):    wifiOnlyVideo changed to true
D/PicasaUploader( 7752):    syncOnBattery changed to true
,I/iu.SyncManager( 5670): NEXT; no task
,D/PicasaUploaderSync( 7752): sync account database
E/Watchdog( 2408): !@Sync 10
,D/PicasaUploaderSync( 7752): accounts in DB=1
,D/PicasaUploaderSyncManager( 7752): active network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PicasaUploaderSyncManager( 7752): background data: true
,D/LockPatternUtils( 2582): isPcwEnable = 10
,D/PicasaUploaderSyncManager( 7752): battery info: false
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 5245): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5245): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1448366400000
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1448345081361
I/GCoreUlr( 2736): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_DISCONNECTED
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5245): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5245): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 5245): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,I/GCoreUlr( 2736): WorldUpdater:android.intent.action.ACTION_POWER_DISCONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2736): Unbound from all location providers
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 2408): GC_EXPLICIT freed 1928K, 69% free 24626K/78468K, paused 10ms+20ms, total 232ms
,I/GCoreUlr( 2736): DispatchingService.onDestroy()
,I/GCoreUlr( 2736): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2736): Unbound from all location providers
,D/lights  ( 2408): button : 0 +
,D/lights  ( 2408): button : 0 -
D/SSRMv2:TSP:AirViewOnOff( 2408): SettingsAirViewInfo:: 000000000
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager( 2408): Waited long enough for: ServiceRecord{45a2ee40 u0 com.sec.spp.push/.PushClientService}
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2408): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4
,D/SensorService( 2408):   0.3 -0.0 9.8
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager( 2408): waitForAlarm result :4
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService( 2408): level:100, scale:100, status:2, health:2, present:true, voltage: 4356, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/PowerManagerService( 2408): [api] updateIsPoweredLocked : mIsPowered: true mPlugType: 2
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/PowerUI ( 2582): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2408): [api] [s] wakeUp (uid: 10019 pid: 2582) eventTime = 327195
D/PowerUI ( 2582): playSound : 1
,V/Vibrator( 2582): Called vibrateImmVibe(int) API - PUID: 10019, PackageName: com.android.keyguard
V/Vibrator( 2582): vibrateImmVibe - PUID: 10019, PackageName: com.android.keyguard, type: 10, magType: TouchMagnitude
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
V/VibratorService( 2408): vibrateImmVibeMagnitudeType - magnitudeType: TouchMagnitude
V/VibratorService( 2408): vibrate - package: com.android.keyguard, ms: 100, token: null
D/VibratorService( 2408): JNI vibratorOff()
D/UsbDeviceManager( 2408): handleMessage -> MSG_POWER_STATE = 1
D/VibratorService( 2408): JNI vibratorOn() : 100
D/UsbDeviceManager( 2408): sending intent : ACTION_USB_CABLE_STATE : connected = true
D/PowerUI ( 2582): RINGER_MODE_VIBRATE
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
I/EntropyMixer( 2408): Writing entropy...
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 2582): onDraw batteryColor : -1
,E/TranscodeReceiver( 5728): onReceive : android.intent.action.ACTION_POWER_CONNECTED
,D/TranscodeService( 5728): onCreate()
,D/TranscodeService( 5728): power? : true / screen off : false
,D/TranscodeService( 5728): releaseTranscodeThread.
,I/SCloudBackupReceiver( 6026): Other Intent
,D/PicasaUploaderSyncManager( 7752): battery info: true
,I/iu.Environment( 5670): update battery state; isPlugged? true*
,D/VibratorService( 2408): JNI vibratorOff()
I/iu.UploadsManager( 5670): num queued entries: 0
I/iu.FingerprintManager( 5670): Start processing all media
I/iu.UploadsManager( 5670): num updated entries: 0
,I/iu.SyncManager( 5670): NEXT; no task
,I/iu.FingerprintManager( 5670): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 5670): Start processing media store URI: content://media/external/video/media
,I/iu.Environment( 3278): update battery state; isPlugged? true*
,I/iu.UploadsManager( 3278): num queued entries: 0
,I/iu.UploadsManager( 3278): num updated entries: 0
,I/iu.SyncManager( 3278): NEXT; no task
,I/iu.FingerprintManager( 3278): Start processing all media
,I/iu.FingerprintManager( 3278): Start processing media store URI: content://media/external/images/media
,D/dalvikvm( 2720): GC_EXPLICIT freed 334K, 27% free 9970K/13604K, paused 4ms+8ms, total 75ms
,E/NetworkScheduler.SchedulerReceiver( 2854): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 2854): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/iu.FingerprintManager( 3278): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 5670): Start processing media store URI: content://media/phoneStorage/images/media
,I/GCoreUlr( 2736): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_CONNECTED}]
,I/iu.FingerprintManager( 5670): Start processing media store URI: content://media/phoneStorage/video/media
,I/GCoreUlr( 2736): DispatchingService.onCreate()
,I/iu.FingerprintManager( 3278): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 3278): Start processing media store URI: content://media/phoneStorage/video/media
I/iu.FingerprintManager( 3278): Finished generating fingerprints; 0.078 seconds
,I/iu.FingerprintManager( 3278):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
I/iu.FingerprintManager( 5670): Finished generating fingerprints; 0.148 seconds
,I/iu.FingerprintManager( 5670):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,D/dalvikvm( 2736): GC_CONCURRENT freed 1896K, 22% free 10951K/13968K, paused 15ms+8ms, total 80ms
,E/DataBuffer( 2736): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42370158)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,I/GCoreUlr( 2736): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_CONNECTED
,I/GCoreUlr( 2736): WorldUpdater:android.intent.action.ACTION_POWER_CONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): DispatchingService.onDestroy()
,I/GCoreUlr( 2736): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2736): Unbound from all location providers
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 350, Delta = -10
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,V/AlarmManager( 2408): waitForAlarm result :8
,D/Headlines( 7349): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7349): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7349): Breath 30016 latestRequest time : 1448345062193 current time : 1448345092209
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2408): prevTemp = 306, currTemp = 307, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5245): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionTIME_TICK
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5245): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5245): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 5245): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/PowerManagerService( 2408): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2582
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/NotificationService( 2408): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200a5 contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
D/STATUSBAR-StatusBarManagerService( 2408): sendNotification(1) - 5
W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/RCPManagerService( 2408): NotificationReceiver onReceive()
,D/RCPManagerService( 2408):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
,D/RCPManagerService( 2408): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967298408
D/RCPManagerService( 2408): getPolicy: policy value returned = false
,D/RCPManagerService( 2408): going to get the app label for pkg == com.android.systemui
D/RCPManagerService( 2408): app label == com.android.systemui
,D/RCPManagerService( 2408): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967298408
D/RCPManagerService( 2408): getPolicy: policy value returned = true
D/UserManagerService( 2408): User -1does not exists!!
,D/RCPManagerService( 2408): Calling User is -1
,D/RCPManagerService( 2408): userid of SBN ==-1
E/PersonaManagerService( 2408): returning null in  getPersonasForUser
,D/ProgressBar( 2582): setProgressDrawable drawableHeight = 12
,D/PhoneStatusBar( 2582): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@422a3608
,D/BatteryMeterView( 2582): onDraw batteryColor : -1
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 340, Delta = -10
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/AmoledAdjustTimer( 2408): prevTemp = 307, currTemp = 308, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/SensorService( 2408):   0.3 0.0 9.9
,I/ActivityManager( 2408): Waited long enough for: ServiceRecord{45b0ab20 u0 com.sec.android.app.videoplayer/.videowall.TranscodeService}
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 340, Delta = 0
,E/Watchdog( 2408): !@Sync 11
,D/SensorService( 2408):   0.3 -0.0 9.9
,D/AmoledAdjustTimer( 2408): prevTemp = 308, currTemp = 309, prevStep = 4, currStep = 4
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/PowerManagerService( 2408): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 2408): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2408): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/lights  ( 2408): lcd : 2 +
D/RampAnimator( 2408): Light Animator Finished currentValue=2
,D/lights  ( 2408): lcd : 2 -
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2408): waitForAlarm result :4
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 7785): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7785):  
,D/dalvikvm( 1923): GC_EXPLICIT freed 42K, 11% free 9503K/10596K, paused 3ms+4ms, total 47ms
,I/SELinux ( 7785): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7785):  
I/SELinux ( 7785):  
,I/SELinux ( 7785): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7785): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7785): >>>>> Normal User
,E/dalvikvm( 7785): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 7785): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 11% free 9503K/10596K, paused 3ms+3ms, total 31ms
,D/TimaKeyStoreProvider( 7785): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7785): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7785): Added TimaKesytore provider
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 11% free 9503K/10596K, paused 2ms+3ms, total 30ms
,D/dalvikvm( 7785): GC_CONCURRENT freed 3003K, 30% free 9566K/13616K, paused 7ms+2ms, total 26ms
,D/dalvikvm( 7785): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/PowerManagerService( 2408): [s] UserActivityState : 2 -> 0
I/PowerManagerService( 2408): [PWL] On : 317175 (40015 ms ago)
I/PowerManagerService( 2408): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
,I/PowerManagerService( 2408): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=2582, ws=null) (elapsedTime=19943)
,D/PowerManagerService( 2408): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2582 (0x0)
I/PowerManagerService( 2408): Nap time...
,D/PowerManagerService( 2408): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2408): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2408): Going to sleep due to screen timeout...
,D/PowerManagerService( 2408): [s] WAKEFULNESS_ASLEEP
,D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
D/Sensors ( 2408): LightSensor enable = 0
,D/Sensors ( 2408): LightSensor enableSensor = 0
,I/SurfaceFlinger( 1921): id=23 createSurf (720x1280),-1 flag=20004, FlectronBea
,I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
,D/SensorManager( 2408): unregisterListener ::   
,D/DisplayPowerController( 2408): !@ElectronBeam entry
I/Sensors ( 2408): HAL:resetDataRates mEnabled=4
,D/SensorManager( 2408): unregisterListener ::   
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/lights  ( 2408): lcd : 0 +
,D/lights  ( 2408): lcd : 0 -
D/PowerManagerService( 2408): blankAllDisplays() is called.
D/PowerManagerService( 2408): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/MISC PowerHAL( 2408): miscpower_set_interactive: /sys/class/input/input1/enabled
V/WindowOrientationListener( 2408): WindowOrientationListener disabled
D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/input/input1/enabled: 0
,D/SensorService( 2408): AutoRotationSensor::activate (ident=0x79c29310, enabled=0)
,I/Sensors ( 2408): HAL: batch Dry Run is complete
,D/KeyguardViewMediator( 2582): onScreenTurnedOff(3)
D/PowerManagerService( 2408): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 2408): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2408): miscpower_set_interactive: /sys/class/input/input0/enabled
D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/input/input0/enabled: 0
D/SensorManager( 2408): unregisterListener ::   
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/InputDispatcher( 2408): setInputDispatchMode: enabled=0, frozen=0
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/PowerManagerService( 2408): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/SurfaceFlinger( 1921): Screen released, type=0 flinger=0x404f8008
D/LockPatternUtils( 2582): isPcwEnable = 10
,D/LockPatternUtils( 2582): isPcwEnable = 10
,D/SurfaceControl( 2408): Excessive delay in blankDisplay() while turning screen off: 211ms
I/libsuspend( 2408): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2408): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2408): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 212ms
D/PowerManagerService( 2408): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2408): [PWL] Off : 0s ago
I/PowerManagerService( 2408): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2408): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2408): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=2408, ws=null) (elapsedTime=210)
I/PowerManagerService( 2408): [PWL]   PowerManagerService.Broadcasts: ref count=1
,I/SQLiteSecureOpenHelper( 4119): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4119): getDatabaseLocked(b,b,pwd)...
,D/KeyguardViewMediator( 2582): setting alarm to turn off keyguard, seq = 3
,D/LightsService( 2408): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2408) 
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2408): LightSensor setDelay = 200000000
D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
D/Sensors ( 2408): Light sensor flush: not enabled 0
D/Sensors ( 2408): LightSensor enable = 1
,D/Sensors ( 2408): LightSensor enableSensor = 1
,D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2408): turn on LED for fully charged
D/VibratorService( 2408): JNI vibratorOff()
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2408): ACTION_SCREEN_OFF
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
,D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,I/AudioHardwareTinyALSA( 1929): setParameters(screen_state=off)
,I/SecExternalDisplayIntents_Java( 2408): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2408): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2408): Bridge Server is not available
,D/PersonaManagerService( 2408): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2408): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2582):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2582): makeExpandedInvisible
D/PhoneStatusBarView( 2582): marqueeStatusBar:123, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2582):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2758): applyRouting return - 2 
,E/NfcService( 2758): callback == null
D/SSRMv2:SIOP( 2408): SIOP:: AP = 340, Delta = 0
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/LockPatternUtils( 2582): isPcwEnable = 10
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 340, Delta = 0
D/QuickConnect[1.1][2] ( 5022): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
V/QuickConnect[1.1][2] ( 5022): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5022): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
D/QuickConnect[1.1][2] ( 5022): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 5022): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 5022): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 5022): stopLeScan()
D/QuickConnect[1.1][2] ( 5022): BleHelper.stopScan - call stopLeScan() complete
,E/TranscodeReceiver( 5728): onReceive : android.intent.action.SCREEN_OFF
,D/TranscodeService( 5728): power? : true / screen off : true
,D/PowerManagerService( 2408): [PWL] sb release: PowerManagerService.Broadcasts
D/TranscodeService( 5728): Music is = false
D/TranscodeService( 5728): runvideoplayer is false
,D/TranscodeService( 5728): Thread start
D/TranscodeService( 5728): WakeLock.acquire()
D/videowall-FileMgr( 5728): thumbnailDBSync -1
,D/Sensors ( 2408): LightSensor enable = 0
,D/Sensors ( 2408): LightSensor enableSensor = 0
,D/LightsService( 2408): [SvcLED]  onSensorChanged::light value = 0
D/SensorManager( 2408): unregisterListener ::   
D/lights  ( 2408): led_pattern : 5 +
,D/lights  ( 2408): led_pattern : 5 -
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/TranscodeService( 5728): Thread end
,D/TranscodeService( 5728): WakeLock.release()
D/TranscodeService( 5728): onDestroy()
,D/TranscodeService( 5728): releaseTranscodeThread.
,V/ApplicationPolicy( 2408): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
,I/ActivityManager( 2408): Killing 6522:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty #43
,D/AmoledAdjustTimer( 2408): prevTemp = 309, currTemp = 310, prevStep = 4, currStep = 4,
,V/AlarmManager( 2408): waitForAlarm result :4,
,D/KeyguardViewMediator( 2582): received DELAYED_KEYGUARD_ACTION with seq = 3, mDelayedShowingSequence = 3,
,D/LockPatternUtils( 2582): isPcwEnable = 10,
,D/KeyguardViewMediator( 2582): in doKeyguardLocked mIsRollUp false null,
,D/PersonaManager( 2582): isKioskContainerExistOnDevice,
,D/LockPatternUtils( 2582): isPcwEnable = 10,
D/LockPatternUtils( 2582): isPcwEnable = 10
,D/KeyguardViewMediator( 2582): doKeyguard: not showing because lockscreen is off,
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 7349): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 7349): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 7349): Breath 63568 latestRequest time : 1448345062193 current time : 1448345125761,
,I/PowerManagerService( 2408): [PWL] Off : 5s ago,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 340, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 310, currTemp = 310, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2408): [PWL] Off : 15s ago,
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 7881,
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 7886
,D/BatteryService( 2408): level:100, scale:100, status:3, health:9, present:true, voltage: 4372, temperature: 309, technology: Li-ion, AC powered:false, USB powered:false, Wireless powered:false, icon:17303678, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 3 (uid: 0 pid: 0) 
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
,D/BatteryService( 2408): turn off LED
,D/lights  ( 2408): led_pattern : 0 +
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/PowerManagerService( 2408): [api] updateIsPoweredLocked : mIsPowered: false mPlugType: 0
I/PowerManagerService( 2408): !@[ps] Screen__On :  powered change
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/lights  ( 2408): led_pattern : 0 -
D/lights  ( 2408): button : 1 +
,D/lights  ( 2408): button : 1 -
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
I/PowerManagerService( 2408): Waking up from sleep...
D/PowerManagerService( 2408): Screen Readiness Inspection requested: mNestCount=1
D/PowerManagerService( 2408): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2408): [s] WAKEFULNESS_AWAKE
D/PowerManagerService( 2408): [s] UserActivityState : 0 -> 1
D/PowerManagerService( 2408): [PWL] sb acquire: PowerManagerService.Display
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : registerListener mLightSensor
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/Sensors ( 2408): LightSensor setDelay = 200000000
,D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
D/Sensors ( 2408): Light sensor flush: not enabled 0
D/Sensors ( 2408): LightSensor enable = 1
,D/Sensors ( 2408): LightSensor enableSensor = 1
,I/libsuspend( 2408): !@[s] autosuspend_autosleep_disable
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2408): [DAB] no lux value from sensor manager
D/DisplayPowerController( 2408): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2408): unblankAllDisplays() is called.
,I/libsuspend( 2408): !@[s] autosuspend_autosleep_disable done
,D/SurfaceFlinger( 1921): Screen acquired, type=0 flinger=0x404f8008
,D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 1
D/PowerUI ( 2582): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2408): [api] [s] wakeUp (uid: 10019 pid: 2582) eventTime = 377545
D/PowerManagerService( 2408): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
,D/PowerManagerService( 2408): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 11ms
I/Sensors ( 2408): HAL: batch Dry Run is complete
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 65558
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5048): Disconnected process message: 10
,I/Sensors ( 2408): HAL:resetDataRates mEnabled=4
D/UsbDeviceManager( 2408): handleMessage -> MSG_POWER_STATE = 0
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/UsbDeviceManager( 2408): sending intent : ACTION_USB_CABLE_STATE : connected = false
W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
,D/SensorManager( 2408): registerListener :: 2, MPL Accelerometer, 200000, 0,  
,D/SensorService( 2408): AutoRotationSensor::changed settle time to [1]
D/PowerManagerService( 2408): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 20ms
D/SensorService( 2408): AutoRotationSensor::activate (ident=0x87c09838, enabled=1)
D/SensorService( 2408): AutoRotationSensor::AR_init
,I/Sensors ( 2408): HAL: batch Dry Run is complete
,I/Sensors ( 2408): HAL:resetDataRates mEnabled=4
D/RampAnimator( 2408): Light Animator Finished currentValue=8
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:3 health:9
,D/NotificationService( 2408): cancelNotificationLocked
,D/STATUSBAR-StatusBarManagerService( 2408): sendNotification(3) - 5
D/NotificationService( 2408):  hasClearableItems
D/NotificationService( 2408):  has clearable items no 
D/NotificationService( 2408): cancelNotificationLocked: cancel alarm
,D/NotificationService( 2408): cancelNotificationLocked: cancel alarm
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SensorManager( 2408): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
,V/KeyguardServiceDelegate( 2408): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@45b99318)
,D/UsbDeviceManager( 2408): received ACTION_POWER_DISCONNECTED = -1
D/KeyguardViewMediator( 2582): onScreenTurnedOn, seq = 4
D/KeyguardViewMediator( 2582): notifyScreenOnLocked
D/KeyguardViewMediator( 2582): handleNotifyScreenOn
D/KeyguardViewManager( 2582): onScreenTurnedOn()
D/InputDispatcher( 2408): setInputDispatchMode: enabled=1, frozen=0
I/KeyguardEffectViewMain( 2582): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 2582): KeyguardEffectViewParticleSpace : screenTurnedOn
,D/VisualEffectParticleEffect( 2582): screenOnAnimationStart
,V/KeyguardServiceDelegate( 2408): **** SHOWN CALLED ****
,I/KIES_RECEIVE( 7737): [APK BnR] Receive KIES_USB_DISCONNECT
V/KeyguardViewManager( 2582): send wm null token: host was null
I/WindowManager( 2408): No lock screen! windowToken=null
,I/SurfaceFlinger( 1921): id=23 Removed FlectronBea (10/10)
D/PowerManagerNotifier( 2408): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/PowerManagerService( 2408): Screen Readiness Inspection completed: mNestCount=0
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
D/DisplayPowerController( 2408): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController( 2408): !@ElectronBeam exit
,W/ContextImpl( 7737): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 android.content.ContextWrapper.stopService:511 com.sec.android.Kies.kies_receiver.onReceive:170 android.app.ActivityThread.handleReceiver:2698 
I/SurfaceFlinger( 1921): id=23 Removed FlectronBea (-2/10)
D/LockPatternUtils( 2582): isPcwEnable = 10
D/lights  ( 2408): lcd : 8 +
,D/lights  ( 2408): lcd : 8 -
D/DisplayPowerController( 2408): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2408): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/BatteryMeterView( 2582): onDraw batteryColor : -1
,D/SensorService( 2408): AutoRotationSensor::process: Acc  eventTimestamp = 377647951823, previousAccTimestamp = 357416341790, difference = 20231610033 
,D/SensorService( 2408): AutoRotationSensor::reset oldrotation = [100], initState = [1]
,D/DisplayPowerController( 2408): [api] [DAB] onSensorChanged : 1st lux : 0.0
,D/DisplayPowerController( 2408): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
,D/SurfaceControl( 2408): Excessive delay in unblankDisplay() while turning screen on: 224ms
,D/MISC PowerHAL( 2408): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/input/input1/enabled: 1
D/PowerManagerService( 2408): Excessive delay in mDisplayManagerService.unblankAllDisplaysFromPowerManager(): 224ms
,D/SensorService( 2408): AutoRotationSensor::process: Acc  eventTimestamp = 377714614123, previousAccTimestamp = 357416341790, difference = 20298272333 
D/SensorService( 2408):  [AR] 0.3 0.0 9.9
,D/SensorService( 2408): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
,D/LockPatternUtils( 2582): isPcwEnable = 10
,I/FPMS_FingerprintManagerService( 2602): onReceive: android.intent.action.USER_PRESENT
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/input/input1/enabled: 1
D/MISC PowerHAL( 2408): miscpower_set_interactive: /sys/class/input/input0/enabled
,D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/input/input0/enabled: 1
,D/SamsungIME( 2984): showDlgMsgBox : false true true
,V/AlarmManager( 2408): waitForAlarm result :4
,D/PhoneStatusBar( 2582): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2408): semi p:6995,o:f
,D/PalmMotionService( 2408): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/PalmMotionService( 2408): SURFACE_PALM_SWIPE: 1
,I/NfcService( 2758): applyRouting return - 2 
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/MotionRecognitionService( 2408):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,D/SSRMv2:TSP:AirViewOnOff( 2408): SettingsAirViewInfo:: 000000000
E/NfcService( 2758): callback == null
E/TranscodeReceiver( 5728): onReceive : android.intent.action.ACTION_POWER_DISCONNECTED
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/PicasaUploaderSyncManager( 7752): battery info: false
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/input/input0/enabled: 1,
,D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/power_supply/battery/lcd: 1,
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/power_supply/battery/lcd: 1,
D/STATUSBAR-NotificationService( 2408): ACTION_SCREEN_ON
D/PowerManagerService-JNI( 2408): Excessive delay in MISC setInteractive(true) while turning screen on: 165ms
,D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
,D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
,D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000,
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/PowerManagerService( 2408): Excessive delay in nativeSetInteractive(true): 167ms
,D/PowerManagerService( 2408): SecHardwareInterface.setBatteryADC : true
I/AudioHardwareTinyALSA( 1929): setParameters(screen_state=on)
I/iu.Environment( 5670): update battery state; isPlugged? false*
,I/SecExternalDisplayIntents_Java( 2408): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,I/iu.UploadsManager( 5670): num queued entries: 0
,I/iu.UploadsManager( 5670): num updated entries: 0
,I/iu.SyncManager( 5670): NEXT; no task
,D/IpRemoteDisplayController( 2408): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2408): Bridge Server is not available
D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = -10
,D/PersonaManagerService( 2408): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 2408): MSG_ACTION_SCREEN_ON called
,I/NfcService( 2758): NFC: Screen On & Cover Open
D/STATUSBAR-NetworkController( 2582): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,I/NfcService( 2758): applyRouting return - 2 
,E/NfcService( 2758): callback == null
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,I/iu.Environment( 3278): update battery state; isPlugged? false*
,D/SnetService( 3278): snet destroyed
,I/iu.UploadsManager( 3278): num queued entries: 0
,I/iu.UploadsManager( 3278): num updated entries: 0
,I/GCoreUlr( 2736): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_DISCONNECTED}]
,I/iu.SyncManager( 3278): NEXT; no task
,I/GCoreUlr( 2736): DispatchingService.onCreate()
,E/Watchdog( 2408): !@Sync 12
,D/LockPatternUtils( 2582): isPcwEnable = 10
,D/dalvikvm( 2854): GC_CONCURRENT freed 1716K, 20% free 11588K/14424K, paused 11ms+15ms, total 89ms
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/QuickConnect[1.1][2] ( 5022): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 5245): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,V/QuickConnect[1.1][2] ( 5022): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5022): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
V/QuickConnect[1.1][2] ( 5022): BleHelper.shouldScanBleFg - 
,V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
,D/QuickConnect[1.1][2] ( 5022): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 5022): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 5022): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 5022): BleHelper.startScan - shouldScanBleFg = false
,I/GCoreUlr( 2736): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_DISCONNECTED
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 5245): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5245): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1448366400000
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1448345141439
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5245): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionSCREEN_ON
,D/PowerManagerService( 2408): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5245): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5245): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,I/GCoreUlr( 2736): WorldUpdater:android.intent.action.ACTION_POWER_DISCONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): DispatchingService.onDestroy()
,I/GCoreUlr( 2736): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2736): Unbound from all location providers
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:TSP:AirViewOnOff( 2408): SettingsAirViewInfo:: 000000000
,D/lights  ( 2408): button : 0 +
,D/lights  ( 2408): button : 0 -
,D/AmoledAdjustTimer( 2408): prevTemp = 310, currTemp = 309, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2408): level:100, scale:100, status:2, health:2, present:true, voltage: 4358, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/PowerManagerService( 2408): [api] updateIsPoweredLocked : mIsPowered: true mPlugType: 2
D/PowerUI ( 2582): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2408): [api] [s] wakeUp (uid: 10019 pid: 2582) eventTime = 387527
,D/PowerUI ( 2582): playSound : 1
V/Vibrator( 2582): Called vibrateImmVibe(int) API - PUID: 10019, PackageName: com.android.keyguard
,V/Vibrator( 2582): vibrateImmVibe - PUID: 10019, PackageName: com.android.keyguard, type: 10, magType: TouchMagnitude
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
V/VibratorService( 2408): vibrateImmVibeMagnitudeType - magnitudeType: TouchMagnitude
V/VibratorService( 2408): vibrate - package: com.android.keyguard, ms: 100, token: null
D/VibratorService( 2408): JNI vibratorOff()
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
D/VibratorService( 2408): JNI vibratorOn() : 100
D/PowerUI ( 2582): RINGER_MODE_VIBRATE
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/UsbDeviceManager( 2408): handleMessage -> MSG_POWER_STATE = 1
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
I/EntropyMixer( 2408): Writing entropy...
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/UsbDeviceManager( 2408): sending intent : ACTION_USB_CABLE_STATE : connected = true
,E/TranscodeReceiver( 5728): onReceive : android.intent.action.ACTION_POWER_CONNECTED
D/BatteryMeterView( 2582): onDraw batteryColor : -1
,D/TranscodeService( 5728): onCreate()
,I/SCloudBackupReceiver( 6026): Other Intent
D/TranscodeService( 5728): power? : true / screen off : false
,D/TranscodeService( 5728): releaseTranscodeThread.
,D/PicasaUploaderSyncManager( 7752): battery info: true
,I/iu.Environment( 5670): update battery state; isPlugged? true*
,I/iu.UploadsManager( 5670): num queued entries: 0
,I/iu.UploadsManager( 5670): num updated entries: 0
,I/iu.SyncManager( 5670): NEXT; no task
,I/iu.FingerprintManager( 5670): Start processing all media
,I/iu.FingerprintManager( 5670): Start processing media store URI: content://media/external/images/media
D/VibratorService( 2408): JNI vibratorOff()
,I/iu.Environment( 3278): update battery state; isPlugged? true*
,I/iu.UploadsManager( 3278): num queued entries: 0
,I/iu.UploadsManager( 3278): num updated entries: 0
,I/iu.FingerprintManager( 5670): Start processing media store URI: content://media/external/video/media
,I/iu.SyncManager( 3278): NEXT; no task
,I/iu.FingerprintManager( 5670): Start processing media store URI: content://media/phoneStorage/images/media
,D/dalvikvm( 2408): GC_EXPLICIT freed 2593K, 68% free 25431K/78468K, paused 10ms+19ms, total 226ms
,I/iu.FingerprintManager( 3278): Start processing all media
,I/iu.FingerprintManager( 5670): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 3278): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 5670): Finished generating fingerprints; 0.293 seconds
,I/iu.FingerprintManager( 5670):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/iu.FingerprintManager( 3278): Start processing media store URI: content://media/external/video/media
,E/NetworkScheduler.SchedulerReceiver( 2854): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 2854): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/GCoreUlr( 2736): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_CONNECTED}]
,I/GCoreUlr( 2736): DispatchingService.onCreate()
,I/iu.FingerprintManager( 3278): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 3278): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 3278): Finished generating fingerprints; 0.076 seconds
,I/iu.FingerprintManager( 3278):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/GCoreUlr( 2736): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_CONNECTED
,I/GCoreUlr( 2736): WorldUpdater:android.intent.action.ACTION_POWER_CONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2736): Unbound from all location providers
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 340, Delta = 10
,I/GCoreUlr( 2736): DispatchingService.onDestroy()
,I/GCoreUlr( 2736): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2736): Unbound from all location providers
,D/SensorService( 2408):   0.3 0.0 9.9
,V/AlarmManager( 2408): waitForAlarm result :8
,D/Headlines( 7349): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7349): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7349): Breath 90015 latestRequest time : 1448345062193 current time : 1448345152208
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2408): prevTemp = 309, currTemp = 309, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.8
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5245): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionTIME_TICK
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5245): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5245): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 5245): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/PowerManagerService( 2408): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2582
W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/NotificationService( 2408): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200a5 contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
D/STATUSBAR-StatusBarManagerService( 2408): sendNotification(1) - 5
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/RCPManagerService( 2408): NotificationReceiver onReceive()
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
D/RCPManagerService( 2408):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
D/RCPManagerService( 2408): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967298408
D/RCPManagerService( 2408): getPolicy: policy value returned = false
,D/RCPManagerService( 2408): going to get the app label for pkg == com.android.systemui
D/RCPManagerService( 2408): app label == com.android.systemui
,D/RCPManagerService( 2408): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967298408
,D/UserManagerService( 2408): User -1does not exists!!
D/RCPManagerService( 2408): getPolicy: policy value returned = true
D/RCPManagerService( 2408): Calling User is -1
,D/RCPManagerService( 2408): userid of SBN ==-1
E/PersonaManagerService( 2408): returning null in  getPersonasForUser
,D/ProgressBar( 2582): setProgressDrawable drawableHeight = 12
,D/PhoneStatusBar( 2582): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@422a3608
,D/BatteryMeterView( 2582): onDraw batteryColor : -1
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 340, Delta = 0
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/AmoledAdjustTimer( 2408): prevTemp = 309, currTemp = 310, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,I/ActivityManager( 2408): Waited long enough for: ServiceRecord{4301e230 u0 com.sec.android.app.videoplayer/.videowall.TranscodeService}
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 13
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 340, Delta = 0
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2408): prevTemp = 310, currTemp = 311, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/PowerManagerService( 2408): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 2408): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2408): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/lights  ( 2408): lcd : 2 +
D/RampAnimator( 2408): Light Animator Finished currentValue=2
,D/lights  ( 2408): lcd : 2 -
,D/SensorService( 2408):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/PowerManagerService( 2408): [s] UserActivityState : 2 -> 0
,I/PowerManagerService( 2408): [PWL] On : 377534 (39989 ms ago)
I/PowerManagerService( 2408): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
,I/PowerManagerService( 2408): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=2582, ws=null) (elapsedTime=19923)
,D/PowerManagerService( 2408): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2582 (0x0)
I/PowerManagerService( 2408): Nap time...
,D/PowerManagerService( 2408): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2408): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2408): Going to sleep due to screen timeout...
,D/PowerManagerService( 2408): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
D/Sensors ( 2408): LightSensor enable = 0
D/Sensors ( 2408): LightSensor enableSensor = 0
,D/SensorManager( 2408): unregisterListener ::   
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
I/SurfaceFlinger( 1921): id=24 createSurf (720x1280),-1 flag=20004, FlectronBea
,I/Sensors ( 2408): HAL:resetDataRates mEnabled=4
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
,D/DisplayPowerController( 2408): !@ElectronBeam entry
,D/SensorManager( 2408): unregisterListener ::   
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4372, temperature: 312, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/lights  ( 2408): lcd : 0 +
,D/lights  ( 2408): lcd : 0 -
D/MISC PowerHAL( 2408): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/input/input1/enabled: 0
D/PowerManagerService( 2408): blankAllDisplays() is called.
D/PowerManagerService( 2408): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2408): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 2408): [PWL] sb release: PowerManagerService.Display
V/WindowOrientationListener( 2408): WindowOrientationListener disabled
D/SensorService( 2408): AutoRotationSensor::activate (ident=0x87c09838, enabled=0)
I/Sensors ( 2408): HAL: batch Dry Run is complete
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2408): miscpower_set_interactive: /sys/class/input/input0/enabled
D/KeyguardViewMediator( 2582): onScreenTurnedOff(3)
D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
D/SensorManager( 2408): unregisterListener ::   
D/SurfaceFlinger( 1921): Screen released, type=0 flinger=0x404f8008
,D/InputDispatcher( 2408): setInputDispatchMode: enabled=0, frozen=0
D/PowerManagerService( 2408): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,D/LockPatternUtils( 2582): isPcwEnable = 10
,D/LockPatternUtils( 2582): isPcwEnable = 10
I/SQLiteSecureOpenHelper( 4119): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4119): getDatabaseLocked(b,b,pwd)...
,D/KeyguardViewMediator( 2582): setting alarm to turn off keyguard, seq = 4
D/LightsService( 2408): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2408) 
,D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
D/Sensors ( 2408): LightSensor setDelay = 200000000
,D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
D/Sensors ( 2408): Light sensor flush: not enabled 0
D/Sensors ( 2408): LightSensor enable = 1
,D/Sensors ( 2408): LightSensor enableSensor = 1
,D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2408): turn on LED for fully charged
D/VibratorService( 2408): JNI vibratorOff()
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2408): ACTION_SCREEN_OFF
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
,D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/AudioHardwareTinyALSA( 1929): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2408): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2408): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2408): Bridge Server is not available
,D/PersonaManagerService( 2408): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2408): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2582):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2582): makeExpandedInvisible
D/PhoneStatusBarView( 2582): marqueeStatusBar:124, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2582):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2758): applyRouting return - 2 
,E/NfcService( 2758): callback == null
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SurfaceControl( 2408): Excessive delay in blankDisplay() while turning screen off: 201ms
,I/libsuspend( 2408): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2408): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2408): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 202ms
D/PowerManagerService( 2408): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2408): [PWL] Off : 0s ago
I/PowerManagerService( 2408): [PWL]   PowerManagerService.Broadcasts: ref count=1
,D/LockPatternUtils( 2582): isPcwEnable = 10
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 340, Delta = 0
,D/QuickConnect[1.1][2] ( 5022): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
,V/QuickConnect[1.1][2] ( 5022): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5022): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
D/QuickConnect[1.1][2] ( 5022): BleHelper.stopScan - force = true
,D/QuickConnect[1.1][2] ( 5022): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 5022): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 5022): stopLeScan()
,D/QuickConnect[1.1][2] ( 5022): BleHelper.stopScan - call stopLeScan() complete
,E/TranscodeReceiver( 5728): onReceive : android.intent.action.SCREEN_OFF
,D/TranscodeService( 5728): power? : true / screen off : true
,D/TranscodeService( 5728): Music is = false
D/TranscodeService( 5728): runvideoplayer is false
,D/PowerManagerService( 2408): [PWL] sb release: PowerManagerService.Broadcasts
D/TranscodeService( 5728): Thread start
D/TranscodeService( 5728): WakeLock.acquire()
D/videowall-FileMgr( 5728): thumbnailDBSync -1
D/Sensors ( 2408): LightSensor enable = 0
,D/Sensors ( 2408): LightSensor enableSensor = 0
D/SensorManager( 2408): unregisterListener ::   
,D/lights  ( 2408): led_pattern : 5 +
D/LightsService( 2408): [SvcLED]  onSensorChanged::light value = 0
,D/lights  ( 2408): led_pattern : 5 -
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/TranscodeService( 5728): Thread end
,D/TranscodeService( 5728): WakeLock.release()
,D/TranscodeService( 5728): onDestroy()
D/TranscodeService( 5728): releaseTranscodeThread.
,D/TranscodeService( 5728): Thread isAlive
,D/vwengine( 5728): stopTranscoding
,D/TranscodeService( 5728): transThread.join();
,V/ApplicationPolicy( 2408): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
,D/AmoledAdjustTimer( 2408): prevTemp = 311, currTemp = 312, prevStep = 4, currStep = 4,
,V/AlarmManager( 2408): waitForAlarm result :4,
,D/KeyguardViewMediator( 2582): received DELAYED_KEYGUARD_ACTION with seq = 4, mDelayedShowingSequence = 4,
,D/LockPatternUtils( 2582): isPcwEnable = 10,
,D/KeyguardViewMediator( 2582): in doKeyguardLocked mIsRollUp false null,
,D/PersonaManager( 2582): isKioskContainerExistOnDevice,
,D/LockPatternUtils( 2582): isPcwEnable = 10,
D/LockPatternUtils( 2582): isPcwEnable = 10
,D/KeyguardViewMediator( 2582): doKeyguard: not showing because lockscreen is off,
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 7349): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 7349): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
D/Headlines( 7349): Breath 123916 latestRequest time : 1448345062193 current time : 1448345186109
,D/Headlines( 7349): stop ,
,D/Headlines( 7349): Breath.onDestroy : ,
,I/ActivityManager( 2408): Killing 5852:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty #43,
,I/PowerManagerService( 2408): [PWL] Off : 5s ago,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 312, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5048): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 340, Delta = 0
,V/AlarmManager( 2408): waitForAlarm result :4,
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 8006): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8006):  
,I/SELinux ( 8006): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8006):  
I/SELinux ( 8006):  
,I/SELinux ( 8006): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8006): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 8006): >>>>> Normal User
,E/dalvikvm( 8006): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10039 ]
,E/SELinux ( 8006): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 8006): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8006): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8006): Added TimaKesytore provider
,D/dalvikvm( 8006): GC_CONCURRENT freed 3014K, 30% free 9560K/13620K, paused 3ms+2ms, total 26ms
,D/dalvikvm( 8006): WAIT_FOR_CONCURRENT_GC blocked 23ms
,E/SPPClientService( 8006): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 8006): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 8006): PushLog.txt file is not deleted.
D/SPPClientService( 8006): PushLog.txt file is not deleted.
,D/SPPClientService( 8006): ============PushLog. stop!
,I/ActivityManager( 2408): Killing 5484:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/AmoledAdjustTimer( 2408): prevTemp = 312, currTemp = 312, prevStep = 4, currStep = 4
,E/SPPClientService( 6570): [b] __PingReply__
,I/PowerManagerService( 2408): [PWL] Off : 15s ago,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5048): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2408): !@Sync 14,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = -10,
,D/AmoledAdjustTimer( 2408): prevTemp = 312, currTemp = 311, prevStep = 4, currStep = 4,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2408): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2408): [PWL] Off : 30s ago
,V/AlarmManager( 2408): waitForAlarm result :4
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 311, currTemp = 310, prevStep = 4, currStep = 4,
,V/AlarmManager( 2408): waitForAlarm result :8,
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5048): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 310, currTemp = 309, prevStep = 4, currStep = 4,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2408): stay LED for fully charged,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5048): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,I/PowerManagerService( 2408): [PWL] Off : 50s ago,
,E/Watchdog( 2408): !@Sync 15,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 309, currTemp = 309, prevStep = 4, currStep = 4,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
,D/BatteryService( 2408): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5048): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 309, currTemp = 308, prevStep = 4, currStep = 4,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5048): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 308, currTemp = 308, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 75s ago,
,E/Watchdog( 2408): !@Sync 16,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2408): prevTemp = 308, currTemp = 307, prevStep = 4, currStep = 4,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 307, currTemp = 307, prevStep = 4, currStep = 4,
,V/AlarmManager( 2408): waitForAlarm result :8,
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 307, currTemp = 307, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2408): [PWL] Off : 105s ago,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2408): !@Sync 17,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5048): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2408): prevTemp = 307, currTemp = 306, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5048): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2408): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4380, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5048): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2408): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2408): [PWL] Off : 140s ago,
,E/Watchdog( 2408): !@Sync 18,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2408): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5048): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2408): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4,
,V/AlarmManager( 2408): waitForAlarm result :8,
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5048): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2408): prevTemp = 306, currTemp = 305, prevStep = 4, currStep = 4,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/jxcore-log( 6995): DBG, CoordinatorConnector start_tests called,
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}},
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): ,
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): DBG, CoordinatorConnector start_tests called,
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
,I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
,I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}},
I/jxcore-log( 6995): 
,E/Watchdog( 2408): !@Sync 19,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true,
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2408): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,I/jxcore-log( 6995): {"type":"end","test":0},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"test","name":"test connectionTable table building and cleanup","id":1},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): DB value for ThaliReplicationManager is: "bogus",
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":50,"expected":50,"test":1,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":40,"expected":40,"test":1,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":60,"expected":60,"test":1,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":1,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":1,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":{"muxPort":60,"time":1448345354527},"expected":true,"test":1,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":9,"ok":true,"name":"Cleanup was called, this table is no longer live.","operator":"throws","actual":{"message":"Cleanup was called, this table is no longer live."},"test":1,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"end","test":1}
I/jxcore-log( 6995): ,
,I/jxcore-log( 6995): {"type":"test","name":"teardown","id":2}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63),
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 1 isOK: undefined : test connectionTable table building and cleanup", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63),
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : Cleanup was called, this table is no longer live.", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 2 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63),
,I/System.out( 7210): Thread-664 calls detatch(),
,I/PowerManagerService( 2408): [PWL] Off : 180s ago,
,I/System.out( 7210): Thread-664 calls detatch(),
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,I/System.out( 7210): Thread-664 calls detatch()
,I/System.out( 7210): Thread-664 calls detatch()
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/System.out( 7210): Thread-664 calls detatch()
,I/System.out( 7210): Thread-664 calls detatch()
,I/jxcore-log( 6995): {"type":"end","test":2},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"test","name":"setup","id":3},
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63),
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 3 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63),
,D/AmoledAdjustTimer( 2408): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,I/jxcore-log( 6995): {"type":"end","test":3},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"test","name":"test connectionTable emitting events for peerIds","id":4},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): DB value for ThaliReplicationManager is: "bogus",
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":30,"expected":30,"test":4,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":40,"expected":40,"test":4,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":50,"expected":50,"test":4,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":60,"expected":60,"test":4,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":7,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"end","test":4},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"test","name":"teardown","id":5}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 4 isOK: undefined : test connectionTable emitting events for peerIds", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 5 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 6995): {"type":"end","test":5},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"test","name":"setup","id":6},
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63),
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 6 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 6995): {"type":"end","test":6}
I/jxcore-log( 6995): 
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 6995): {"type":"test","name":"start with bad friendly names","id":7},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":0,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":1,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":2,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":3,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"end","test":7}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"test","name":"teardown","id":8}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 7 isOK: undefined : start with bad friendly names", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 8 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2408): stay LED for fully charged,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2408): prevTemp = 305, currTemp = 306, prevStep = 4, currStep = 4,
,I/jxcore-log( 6995): {"type":"end","test":8},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"test","name":"setup","id":9},
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63),
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 9 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63),
,D/TimaService( 2408): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2408): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2408): TimaServiceHandler.handleMessage what =1,
,I/jxcore-log( 6995): {"type":"end","test":9},
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 6995): {"type":"test","name":"make sure startIdentityExchange sets things up properly","id":10},
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 10 isOK: undefined : make sure startIdentityExchange sets things up properly", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 6995): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: DATBWLVSopCk6vemtXsC2A==;Matt,
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":49286,"expected":49286,"test":10,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":10,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"DATBWLVSopCk6vemtXsC2A==;Matt","expected":"DATBWLVSopCk6vemtXsC2A==;Matt","test":10,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":4,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"},
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63),
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63),
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 6995): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":10,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"123","expected":"123","test":10,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":8,"ok":true,"name":"should be equal","operator":"equal","actual":"bar1","expected":"bar1","test":10,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":9,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"456","expected":"456","test":10,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":11,"ok":true,"name":"should be equal","operator":"equal","actual":"bar2","expected":"bar2","test":10,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":"started","expected":"started","test":10,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"end","test":10}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"test","name":"teardown","id":11}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 11 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,E/Watchdog( 2408): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 2408): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5048): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,I/jxcore-log( 6995): {"type":"end","test":11},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"test","name":"setup","id":12},
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63),
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 12 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63),
,D/AmoledAdjustTimer( 2408): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4,
,I/jxcore-log( 6995): {"type":"end","test":12},
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 6995): {"type":"test","name":"make sure we get an error if we call start and then immediately call stop","id":13},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state startIdentityExchangeCalledCB","test":13,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"end","test":13}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"test","name":"teardown","id":14}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: Wm8EJizt2JrQGqCv2FdqXA==;Toby
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":46557,"expected":46557,"test":13,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":13,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"Wm8EJizt2JrQGqCv2FdqXA==;Toby","expected":"Wm8EJizt2JrQGqCv2FdqXA==;Toby","test":13,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":13,"type":"assert"}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 13 isOK: undefined : make sure we get an error if we call start and then immediately call stop", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 14 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"type":"end","test":14},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"test","name":"setup","id":15},
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63),
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 15 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63),
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,I/jxcore-log( 6995): {"type":"end","test":15},
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 6995): {"type":"test","name":"Make sure stop is clean from start","id":16},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: JJOP9dw5IcDPCHFv3pQX7Q==;Luke,
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":54272,"expected":54272,"test":16,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":16,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"JJOP9dw5IcDPCHFv3pQX7Q==;Luke","expected":"JJOP9dw5IcDPCHFv3pQX7Q==;Luke","test":16,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":3,"ok":true,"name":"Should not have gotten error on startIdentityExchange","operator":"notOk","actual":null,"expected":false,"test":16,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":4,"ok":true,"name":"Should not have gotten error on stopIdentityExchange","operator":"notOk","expected":false,"test":16,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":5,"ok":true,"name":"State should be Stopped","operator":"equal","actual":"stopped","expected":"stopped","test":16,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"end","test":16}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 16 isOK: undefined : Make sure stop is clean from start", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"type":"test","name":"teardown","id":17}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : Should not have gotten error on startIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : Should not have gotten error on stopIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : State should be Stopped", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 17 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/AmoledAdjustTimer( 2408): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4,
,V/AlarmManager( 2408): waitForAlarm result :8,
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/dalvikvm( 4048): GC_CONCURRENT freed 2874K, 29% free 9726K/13648K, paused 27ms+3ms, total 121ms
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,I/jxcore-log( 6995): {"type":"end","test":17}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"test","name":"setup","id":18}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 18 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): stay LED for fully charged
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 6995): {"type":"end","test":18}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"type":"test","name":"Make sure stop is clean from stop execute identity exchange","id":19}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: Y2j05ByZ1IyI1mMlP4sMeg==;Jukka
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":54815,"expected":54815,"test":19,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":19,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"Y2j05ByZ1IyI1mMlP4sMeg==;Jukka","expected":"Y2j05ByZ1IyI1mMlP4sMeg==;Jukka","test":19,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":19,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":4,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":19,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"stopped","expected":"stopped","test":19,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"end","test":19}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"test","name":"teardown","id":20}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 19 isOK: undefined : Make sure stop is clean from stop execute identity exchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 20 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/AmoledAdjustTimer( 2408): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 225s ago
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2408): !@Sync 21
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/dalvikvm( 2408): GC_CONCURRENT freed 3915K, 68% free 25417K/78468K, paused 20ms+18ms, total 246ms
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2408): prevTemp = 306, currTemp = 305, prevStep = 4, currStep = 4
,I/jxcore-log( 6995): {"type":"end","test":20}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"test","name":"setup","id":21}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 21 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"type":"end","test":21}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"type":"test","name":"make sure we do not have a race condition between startIdentityExchange and executeIdentityExchange","id":22}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: CeyLP2gpaJtcJBp6XtKOlQ==;Doug
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":46863,"expected":46863,"test":22,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":22,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"CeyLP2gpaJtcJBp6XtKOlQ==;Doug","expected":"CeyLP2gpaJtcJBp6XtKOlQ==;Doug","test":22,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":4,"ok":true,"name":"should not throw","operator":"throws","test":22,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":22,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":22,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"end","test":22},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"test","name":"teardown","id":23}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 22 isOK: undefined : make sure we do not have a race condition between startIdentityExchange and executeIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should not throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 23 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 9178
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 9182
,D/BatteryService( 2408): level:100, scale:100, status:3, health:9, present:true, voltage: 4383, temperature: 306, technology: Li-ion, AC powered:false, USB powered:false, Wireless powered:false, icon:17303678, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 3 (uid: 0 pid: 0) 
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
,D/BatteryService( 2408): turn off LED
,D/lights  ( 2408): led_pattern : 0 +
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/lights  ( 2408): led_pattern : 0 -
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/PowerManagerService( 2408): [api] updateIsPoweredLocked : mIsPowered: false mPlugType: 0
I/PowerManagerService( 2408): !@[ps] Screen__On :  powered change
I/PowerManagerService( 2408): Waking up from sleep...
D/PowerManagerService( 2408): Screen Readiness Inspection requested: mNestCount=1
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/PowerManagerService( 2408): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2408): [s] WAKEFULNESS_AWAKE
D/PowerUI ( 2582): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2408): [s] UserActivityState : 0 -> 1
,D/lights  ( 2408): button : 1 +
,D/lights  ( 2408): button : 1 -
D/PowerManagerService( 2408): [PWL] sb acquire: PowerManagerService.Display
D/PowerManagerService( 2408): [api] [s] wakeUp (uid: 10019 pid: 2582) eventTime = 659145
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:3 health:9
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5048): Disconnected process message: 10
D/Sensors ( 2408): LightSensor setDelay = 200000000
D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
D/Sensors ( 2408): Light sensor flush: not enabled 0
D/Sensors ( 2408): LightSensor enable = 1
D/Sensors ( 2408): LightSensor enableSensor = 1
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/DisplayPowerController( 2408): [DAB] no lux value from sensor manager
,D/DisplayPowerController( 2408): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 65558
D/SensorService( 2408): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2408): AutoRotationSensor::activate (ident=0x7bd618f0, enabled=1)
D/SensorService( 2408): AutoRotationSensor::AR_init
,I/Sensors ( 2408): HAL: batch Dry Run is complete
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 1
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/UsbDeviceManager( 2408): handleMessage -> MSG_POWER_STATE = 0
D/PowerManagerService( 2408): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 8ms
,I/Sensors ( 2408): HAL:resetDataRates mEnabled=4
I/libsuspend( 2408): !@[s] autosuspend_autosleep_disable
,I/libsuspend( 2408): !@[s] autosuspend_autosleep_disable done
,D/SurfaceFlinger( 1921): Screen acquired, type=0 flinger=0x404f8008
W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
D/PowerManagerService( 2408): unblankAllDisplays() is called.
D/PowerManagerService( 2408): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
,D/UsbDeviceManager( 2408): sending intent : ACTION_USB_CABLE_STATE : connected = false
,D/NotificationService( 2408): cancelNotificationLocked
D/NotificationService( 2408):  hasClearableItems
D/NotificationService( 2408):  has clearable items no 
D/NotificationService( 2408): cancelNotificationLocked: cancel alarm
,D/NotificationService( 2408): cancelNotificationLocked: cancel alarm
I/Sensors ( 2408): HAL: batch Dry Run is complete
D/SensorManager( 2408): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
,V/KeyguardServiceDelegate( 2408): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@431d6998)
D/STATUSBAR-StatusBarManagerService( 2408): sendNotification(3) - 5
,D/SensorManager( 2408): registerListener :: 2, MPL Accelerometer, 200000, 0,  
D/KeyguardViewMediator( 2582): onScreenTurnedOn, seq = 5
,D/KeyguardViewMediator( 2582): notifyScreenOnLocked
D/PowerManagerService( 2408): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 18ms
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
D/RampAnimator( 2408): Light Animator Finished currentValue=8
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LockPatternUtils( 2582): isPcwEnable = 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/UsbDeviceManager( 2408): received ACTION_POWER_DISCONNECTED = -1
D/InputDispatcher( 2408): setInputDispatchMode: enabled=1, frozen=0
D/KeyguardViewMediator( 2582): handleNotifyScreenOn
D/KeyguardViewManager( 2582): onScreenTurnedOn()
I/KeyguardEffectViewMain( 2582): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 2582): KeyguardEffectViewParticleSpace : screenTurnedOn
D/VisualEffectParticleEffect( 2582): screenOnAnimationStart
,V/KeyguardServiceDelegate( 2408): **** SHOWN CALLED ****
,I/KIES_RECEIVE( 7737): [APK BnR] Receive KIES_USB_DISCONNECT
V/KeyguardViewManager( 2582): send wm null token: host was null
I/WindowManager( 2408): No lock screen! windowToken=null
,I/SurfaceFlinger( 1921): id=24 Removed FlectronBea (10/10)
,I/SurfaceFlinger( 1921): id=24 Removed FlectronBea (-2/10)
D/PowerManagerNotifier( 2408): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/PowerManagerService( 2408): Screen Readiness Inspection completed: mNestCount=0
W/ContextImpl( 7737): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 android.content.ContextWrapper.stopService:511 com.sec.android.Kies.kies_receiver.onReceive:170 android.app.ActivityThread.handleReceiver:2698 
D/DisplayPowerController( 2408): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 2408): !@ElectronBeam exit
D/lights  ( 2408): lcd : 8 +
,D/lights  ( 2408): lcd : 8 -
D/DisplayPowerController( 2408): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2408): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 2582): onDraw batteryColor : -1
,D/SensorService( 2408): AutoRotationSensor::process: Acc  eventTimestamp = 659234911665, previousAccTimestamp = 417757783367, difference = 241477128298 
,D/SensorService( 2408): AutoRotationSensor::reset oldrotation = [100], initState = [1]
,D/DisplayPowerController( 2408): [api] [DAB] onSensorChanged : 1st lux : 0.0
,D/DisplayPowerController( 2408): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
,D/SensorService( 2408): AutoRotationSensor::process: Acc  eventTimestamp = 659301020568, previousAccTimestamp = 417757783367, difference = 241543237201 
D/SensorService( 2408):  [AR] 0.3 0.0 9.9
,D/SensorService( 2408): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
,D/SurfaceControl( 2408): Excessive delay in unblankDisplay() while turning screen on: 227ms
,D/MISC PowerHAL( 2408): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/input/input1/enabled: 1
D/PowerManagerService( 2408): Excessive delay in mDisplayManagerService.unblankAllDisplaysFromPowerManager(): 228ms
,D/LockPatternUtils( 2582): isPcwEnable = 10
,D/SamsungIME( 2984): showDlgMsgBox : false true true
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/input/input1/enabled: 1
D/MISC PowerHAL( 2408): miscpower_set_interactive: /sys/class/input/input0/enabled
,D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/input/input0/enabled: 1
,I/FPMS_FingerprintManagerService( 2602): onReceive: android.intent.action.USER_PRESENT
,E/TranscodeReceiver( 5728): onReceive : android.intent.action.ACTION_POWER_DISCONNECTED
,I/NfcService( 2758): applyRouting return - 2 
,E/NfcService( 2758): callback == null
D/PalmMotionService( 2408): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/PalmMotionService( 2408): SURFACE_PALM_SWIPE: 1
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
E/MotionRecognitionService( 2408):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SSRMv2:TSP:AirViewOnOff( 2408): SettingsAirViewInfo:: 000000000
,D/StatusBarManagerService( 2408): semi p:6995,o:f
D/PhoneStatusBar( 2582): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PicasaUploaderSyncManager( 7752): battery info: false
,I/iu.Environment( 5670): update battery state; isPlugged? false*
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
,I/iu.UploadsManager( 5670): num queued entries: 0
,I/iu.UploadsManager( 5670): num updated entries: 0
,I/iu.Environment( 3278): update battery state; isPlugged? false*
,I/iu.SyncManager( 5670): NEXT; no task
,I/iu.UploadsManager( 3278): num queued entries: 0
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,I/iu.UploadsManager( 3278): num updated entries: 0
,I/GCoreUlr( 2736): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_DISCONNECTED}]
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/input/input0/enabled: 1
D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
,D/PowerManagerService-JNI( 2408): Excessive delay in MISC setInteractive(true) while turning screen on: 166ms
,D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
,D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
,D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
,I/iu.SyncManager( 3278): NEXT; no task
D/PowerManagerService( 2408): Excessive delay in nativeSetInteractive(true): 170ms
D/PowerManagerService( 2408): SecHardwareInterface.setBatteryADC : true
,I/GCoreUlr( 2736): DispatchingService.onCreate()
D/STATUSBAR-NotificationService( 2408): ACTION_SCREEN_ON
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/AudioHardwareTinyALSA( 1929): setParameters(screen_state=on)
,I/SecExternalDisplayIntents_Java( 2408): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/IpRemoteDisplayController( 2408): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2408): Bridge Server is not available
,D/PersonaManagerService( 2408): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 2408): MSG_ACTION_SCREEN_ON called
,I/NfcService( 2758): NFC: Screen On & Cover Open
,D/STATUSBAR-NetworkController( 2582): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
I/NfcService( 2758): applyRouting return - 2 
E/NfcService( 2758): callback == null
,D/LockPatternUtils( 2582): isPcwEnable = 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,I/GCoreUlr( 2736): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_DISCONNECTED
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/SensorService( 2408):   0.3 0.0 9.9
,D/QuickConnect[1.1][2] ( 5022): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
V/QuickConnect[1.1][2] ( 5022): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5022): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
V/QuickConnect[1.1][2] ( 5022): BleHelper.shouldScanBleFg - 
,V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
D/QuickConnect[1.1][2] ( 5022): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 5022): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 5022): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 5022): BleHelper.startScan - shouldScanBleFg = false
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5245): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5245): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/dalvikvm( 5245): GC_CONCURRENT freed 1978K, 28% free 9988K/13684K, paused 5ms+9ms, total 54ms
,D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1448366400000
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1448345423011
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5245): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionSCREEN_ON
,I/GCoreUlr( 2736): WorldUpdater:android.intent.action.ACTION_POWER_DISCONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/PowerManagerService( 2408): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/GCoreUlr( 2736): Unbound from all location providers
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5245): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5245): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 5245): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,I/GCoreUlr( 2736): DispatchingService.onDestroy()
,I/GCoreUlr( 2736): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2736): Unbound from all location providers
,D/SSRMv2:TSP:AirViewOnOff( 2408): SettingsAirViewInfo:: 000000000
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/lights  ( 2408): button : 0 +
,D/lights  ( 2408): button : 0 -
,D/AmoledAdjustTimer( 2408): prevTemp = 305, currTemp = 306, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,I/jxcore-log( 6995): {"type":"end","test":23}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"test","name":"setup","id":24}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 24 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,I/jxcore-log( 6995): {"type":"end","test":24}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"type":"test","name":"illegal method combinations","id":25}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":1,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":2,"ok":true,"name":"should throw","operator":"throws","actual":"event stopIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: at7O4b+kiNadO86hx04+5Q==;David
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":43558,"expected":43558,"test":25,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":25,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"at7O4b+kiNadO86hx04+5Q==;David","expected":"at7O4b+kiNadO86hx04+5Q==;David","test":25,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":25,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":7,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":8,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":9,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":25,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":10,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":11,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: at7O4b+kiNadO86hx04+5Q==;David
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":43558,"expected":43558,"test":25,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":13,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":25,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":14,"ok":true,"name":"should be equal","operator":"equal","actual":"at7O4b+kiNadO86hx04+5Q==;David","expected":"at7O4b+kiNadO86hx04+5Q==;David","test":25,"type":"assert"}
I/jxcore-log( 6995): 
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
I/jxcore-log( 6995): {"id":15,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":25,"type":"assert"}
I/jxcore-log( 6995): 
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,I/jxcore-log( 6995): {"id":16,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":17,"ok":true,"name":"should throw","operator":"throws","actual":"event stopIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":18,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":19,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":20,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"end","test":25}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 25 isOK: undefined : illegal method combinations", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 13 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 14 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 15 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 16 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"type":"test","name":"teardown","id":26}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 17 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 18 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 19 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 20 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 26 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/BatteryService( 2408): level:100, scale:100, status:2, health:2, present:true, voltage: 4362, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/PowerManagerService( 2408): [api] updateIsPoweredLocked : mIsPowered: true mPlugType: 2
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/PowerUI ( 2582): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2408): [api] [s] wakeUp (uid: 10019 pid: 2582) eventTime = 669132
V/Vibrator( 2582): Called vibrateImmVibe(int) API - PUID: 10019, PackageName: com.android.keyguard
,V/Vibrator( 2582): vibrateImmVibe - PUID: 10019, PackageName: com.android.keyguard, type: 10, magType: TouchMagnitude
D/PowerUI ( 2582): playSound : 1
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
V/VibratorService( 2408): vibrateImmVibeMagnitudeType - magnitudeType: TouchMagnitude
V/VibratorService( 2408): vibrate - package: com.android.keyguard, ms: 100, token: null
D/VibratorService( 2408): JNI vibratorOff()
D/VibratorService( 2408): JNI vibratorOn() : 100
D/PowerUI ( 2582): RINGER_MODE_VIBRATE
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/UsbDeviceManager( 2408): handleMessage -> MSG_POWER_STATE = 1
I/EntropyMixer( 2408): Writing entropy...
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 2582): onDraw batteryColor : -1
,D/UsbDeviceManager( 2408): sending intent : ACTION_USB_CABLE_STATE : connected = true
,E/TranscodeReceiver( 5728): onReceive : android.intent.action.ACTION_POWER_CONNECTED
,D/TranscodeService( 5728): onCreate()
,D/TranscodeService( 5728): power? : true / screen off : false
,D/TranscodeService( 5728): releaseTranscodeThread.
,I/SCloudBackupReceiver( 6026): Other Intent
,D/PicasaUploaderSyncManager( 7752): battery info: true
,I/iu.Environment( 5670): update battery state; isPlugged? true*
,I/iu.UploadsManager( 5670): num queued entries: 0
,I/iu.UploadsManager( 5670): num updated entries: 0
,D/VibratorService( 2408): JNI vibratorOff()
I/iu.SyncManager( 5670): NEXT; no task
I/iu.FingerprintManager( 5670): Start processing all media
I/iu.FingerprintManager( 5670): Start processing media store URI: content://media/external/images/media
,I/iu.Environment( 3278): update battery state; isPlugged? true*
,I/iu.UploadsManager( 3278): num queued entries: 0
,I/iu.UploadsManager( 3278): num updated entries: 0
,I/iu.SyncManager( 3278): NEXT; no task
,I/iu.FingerprintManager( 5670): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 3278): Start processing all media
,I/iu.FingerprintManager( 5670): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 3278): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 5670): Start processing media store URI: content://media/phoneStorage/video/media
,E/NetworkScheduler.SchedulerReceiver( 2854): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 2854): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/iu.FingerprintManager( 3278): Start processing media store URI: content://media/external/video/media
I/GCoreUlr( 2736): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_CONNECTED}]
I/iu.FingerprintManager( 5670): Finished generating fingerprints; 0.094 seconds
,I/iu.FingerprintManager( 5670):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/GCoreUlr( 2736): DispatchingService.onCreate()
,I/iu.FingerprintManager( 3278): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 3278): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 3278): Finished generating fingerprints; 0.118 seconds
,I/iu.FingerprintManager( 3278):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/jxcore-log( 6995): {"type":"end","test":26}
I/jxcore-log( 6995): 
,I/GCoreUlr( 2736): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_CONNECTED
,I/jxcore-log( 6995): {"type":"test","name":"setup","id":27}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 27 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/GCoreUlr( 2736): WorldUpdater:android.intent.action.ACTION_POWER_CONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2736): Unbound from all location providers
,D/SensorService( 2408):   0.3 0.0 9.9
,I/GCoreUlr( 2736): DispatchingService.onDestroy()
,I/GCoreUlr( 2736): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2736): Unbound from all location providers
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2408): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,I/jxcore-log( 6995): {"type":"end","test":27}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"type":"test","name":"do an identity exchange and get code multiple times to make sure we do not hork state","id":28}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: Ktm0vo0u4+KH5xraP8zIXA==;John
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":48270,"expected":48270,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"Ktm0vo0u4+KH5xraP8zIXA==;John","expected":"Ktm0vo0u4+KH5xraP8zIXA==;John","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: esGzMLbvcnKvnkYZGzhHxw==;Srikanth
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":50766,"expected":50766,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"esGzMLbvcnKvnkYZGzhHxw==;Srikanth","expected":"esGzMLbvcnKvnkYZGzhHxw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":7,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO smallerHash Making /identity/cb request to pkOther value esGzMLbvcnKvnkYZGzhHxw==
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 28 isOK: undefined : do an identity exchange and get code multiple times to make sure we do not hork state", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO smallerHash Making /identity/rnmine request to pkOther value esGzMLbvcnKvnkYZGzhHxw==
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":9,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"id":10,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":11,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":526528,"expected":526528,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":13,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":14,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: Ktm0vo0u4+KH5xraP8zIXA==;John
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":15,"ok":true,"name":"should be equal","operator":"equal","actual":48270,"expected":48270,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":16,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":17,"ok":true,"name":"should be equal","operator":"equal","actual":"Ktm0vo0u4+KH5xraP8zIXA==;John","expected":"Ktm0vo0u4+KH5xraP8zIXA==;John","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":18,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: esGzMLbvcnKvnkYZGzhHxw==;Srikanth
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":19,"ok":true,"name":"should be equal","operator":"equal","actual":50766,"expected":50766,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":20,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":21,"ok":true,"name":"should be equal","operator":"equal","actual":"esGzMLbvcnKvnkYZGzhHxw==;Srikanth","expected":"esGzMLbvcnKvnkYZGzhHxw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":22,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO smallerHash Making /identity/cb request to pkOther value esGzMLbvcnKvnkYZGzhHxw==
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO smallerHash Making /identity/rnmine request to pkOther value esGzMLbvcnKvnkYZGzhHxw==
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 13 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 14 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"id":23,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":24,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 15 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 16 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 17 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"id":25,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":26,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":27,"ok":true,"name":"should be equal","operator":"equal","actual":270592,"expected":270592,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":28,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":29,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: Ktm0vo0u4+KH5xraP8zIXA==;John
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":30,"ok":true,"name":"should be equal","operator":"equal","actual":48270,"expected":48270,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":31,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":32,"ok":true,"name":"should be equal","operator":"equal","actual":"Ktm0vo0u4+KH5xraP8zIXA==;John","expected":"Ktm0vo0u4+KH5xraP8zIXA==;John","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":33,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: esGzMLbvcnKvnkYZGzhHxw==;Srikanth
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":34,"ok":true,"name":"should be equal","operator":"equal","actual":50766,"expected":50766,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":35,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":36,"ok":true,"name":"should be equal","operator":"equal","actual":"esGzMLbvcnKvnkYZGzhHxw==;Srikanth","expected":"esGzMLbvcnKvnkYZGzhHxw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":37,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,I/jxcore-log( 6995): INFO smallerHash Making /identity/cb request to pkOther value esGzMLbvcnKvnkYZGzhHxw==
I/jxcore-log( 6995): 
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 18 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 19 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 20 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 21 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 22 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 23 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 24 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 25 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 26 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 27 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 28 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 29 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 30 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 31 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 32 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 33 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 34 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 35 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 36 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO smallerHash Making /identity/rnmine request to pkOther value esGzMLbvcnKvnkYZGzhHxw==
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 37 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"id":38,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":39,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 38 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"id":40,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":41,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":42,"ok":true,"name":"should be equal","operator":"equal","actual":172608,"expected":172608,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":43,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":44,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: Ktm0vo0u4+KH5xraP8zIXA==;John
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":45,"ok":true,"name":"should be equal","operator":"equal","actual":48270,"expected":48270,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":46,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":47,"ok":true,"name":"should be equal","operator":"equal","actual":"Ktm0vo0u4+KH5xraP8zIXA==;John","expected":"Ktm0vo0u4+KH5xraP8zIXA==;John","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":48,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: esGzMLbvcnKvnkYZGzhHxw==;Srikanth
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":49,"ok":true,"name":"should be equal","operator":"equal","actual":50766,"expected":50766,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":50,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":51,"ok":true,"name":"should be equal","operator":"equal","actual":"esGzMLbvcnKvnkYZGzhHxw==;Srikanth","expected":"esGzMLbvcnKvnkYZGzhHxw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":52,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO smallerHash Making /identity/cb request to pkOther value esGzMLbvcnKvnkYZGzhHxw==
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 39 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 40 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 41 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO smallerHash Making /identity/rnmine request to pkOther value esGzMLbvcnKvnkYZGzhHxw==
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 42 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"id":53,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":54,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 43 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 44 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 45 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"id":55,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":56,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":57,"ok":true,"name":"should be equal","operator":"equal","actual":378240,"expected":378240,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":58,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":59,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: Ktm0vo0u4+KH5xraP8zIXA==;John
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":60,"ok":true,"name":"should be equal","operator":"equal","actual":48270,"expected":48270,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): {"id":61,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":62,"ok":true,"name":"should be equal","operator":"equal","actual":"Ktm0vo0u4+KH5xraP8zIXA==;John","expected":"Ktm0vo0u4+KH5xraP8zIXA==;John","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":63,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: esGzMLbvcnKvnkYZGzhHxw==;Srikanth
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":64,"ok":true,"name":"should be equal","operator":"equal","actual":50766,"expected":50766,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":65,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":66,"ok":true,"name":"should be equal","operator":"equal","actual":"esGzMLbvcnKvnkYZGzhHxw==;Srikanth","expected":"esGzMLbvcnKvnkYZGzhHxw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":67,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO smallerHash Making /identity/cb request to pkOther value esGzMLbvcnKvnkYZGzhHxw==
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 46 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 47 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 48 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 49 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 50 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 51 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 52 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO smallerHash Making /identity/rnmine request to pkOther value esGzMLbvcnKvnkYZGzhHxw==
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 53 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 54 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 55 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"id":68,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":69,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 56 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 57 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 58 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 59 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 60 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 61 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 62 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 63 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"id":70,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":71,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":72,"ok":true,"name":"should be equal","operator":"equal","actual":723136,"expected":723136,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":73,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":74,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: Ktm0vo0u4+KH5xraP8zIXA==;John
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":75,"ok":true,"name":"should be equal","operator":"equal","actual":48270,"expected":48270,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":76,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":77,"ok":true,"name":"should be equal","operator":"equal","actual":"Ktm0vo0u4+KH5xraP8zIXA==;John","expected":"Ktm0vo0u4+KH5xraP8zIXA==;John","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":78,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: esGzMLbvcnKvnkYZGzhHxw==;Srikanth
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":79,"ok":true,"name":"should be equal","operator":"equal","actual":50766,"expected":50766,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":80,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":81,"ok":true,"name":"should be equal","operator":"equal","actual":"esGzMLbvcnKvnkYZGzhHxw==;Srikanth","expected":"esGzMLbvcnKvnkYZGzhHxw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":82,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO smallerHash Making /identity/cb request to pkOther value esGzMLbvcnKvnkYZGzhHxw==
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 64 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 65 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 66 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 67 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 68 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 69 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 70 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 71 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 72 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 73 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 74 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 75 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 76 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 77 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 78 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 79 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 80 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 81 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 82 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO smallerHash Making /identity/rnmine request to pkOther value esGzMLbvcnKvnkYZGzhHxw==
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":83,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":84,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 83 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"id":85,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":86,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":87,"ok":true,"name":"should be equal","operator":"equal","actual":69696,"expected":69696,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":88,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":89,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: Ktm0vo0u4+KH5xraP8zIXA==;John
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":90,"ok":true,"name":"should be equal","operator":"equal","actual":48270,"expected":48270,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":91,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":92,"ok":true,"name":"should be equal","operator":"equal","actual":"Ktm0vo0u4+KH5xraP8zIXA==;John","expected":"Ktm0vo0u4+KH5xraP8zIXA==;John","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":93,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: esGzMLbvcnKvnkYZGzhHxw==;Srikanth
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":94,"ok":true,"name":"should be equal","operator":"equal","actual":50766,"expected":50766,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":95,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":96,"ok":true,"name":"should be equal","operator":"equal","actual":"esGzMLbvcnKvnkYZGzhHxw==;Srikanth","expected":"esGzMLbvcnKvnkYZGzhHxw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":97,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO smallerHash Making /identity/cb request to pkOther value esGzMLbvcnKvnkYZGzhHxw==
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 84 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 85 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 86 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 87 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 88 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 89 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 90 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 91 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 92 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO smallerHash Making /identity/rnmine request to pkOther value esGzMLbvcnKvnkYZGzhHxw==
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 93 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 94 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 95 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 96 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 97 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,I/jxcore-log( 6995): {"id":98,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":99,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":100,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":101,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":102,"ok":true,"name":"should be equal","operator":"equal","actual":500800,"expected":500800,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":103,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":104,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: Ktm0vo0u4+KH5xraP8zIXA==;John
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":105,"ok":true,"name":"should be equal","operator":"equal","actual":48270,"expected":48270,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":106,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":107,"ok":true,"name":"should be equal","operator":"equal","actual":"Ktm0vo0u4+KH5xraP8zIXA==;John","expected":"Ktm0vo0u4+KH5xraP8zIXA==;John","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":108,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: esGzMLbvcnKvnkYZGzhHxw==;Srikanth
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":109,"ok":true,"name":"should be equal","operator":"equal","actual":50766,"expected":50766,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":110,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":111,"ok":true,"name":"should be equal","operator":"equal","actual":"esGzMLbvcnKvnkYZGzhHxw==;Srikanth","expected":"esGzMLbvcnKvnkYZGzhHxw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":112,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO smallerHash Making /identity/cb request to pkOther value esGzMLbvcnKvnkYZGzhHxw==
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 98 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 99 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 100 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 101 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 102 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 103 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 104 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 105 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 106 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 107 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO smallerHash Making /identity/rnmine request to pkOther value esGzMLbvcnKvnkYZGzhHxw==
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 108 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 109 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 110 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 111 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"id":113,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":114,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 112 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"id":115,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":116,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":117,"ok":true,"name":"should be equal","operator":"equal","actual":343872,"expected":343872,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":118,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":119,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: Ktm0vo0u4+KH5xraP8zIXA==;John
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":120,"ok":true,"name":"should be equal","operator":"equal","actual":48270,"expected":48270,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":121,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":122,"ok":true,"name":"should be equal","operator":"equal","actual":"Ktm0vo0u4+KH5xraP8zIXA==;John","expected":"Ktm0vo0u4+KH5xraP8zIXA==;John","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":123,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: esGzMLbvcnKvnkYZGzhHxw==;Srikanth
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":124,"ok":true,"name":"should be equal","operator":"equal","actual":50766,"expected":50766,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":125,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":126,"ok":true,"name":"should be equal","operator":"equal","actual":"esGzMLbvcnKvnkYZGzhHxw==;Srikanth","expected":"esGzMLbvcnKvnkYZGzhHxw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":127,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO smallerHash Making /identity/cb request to pkOther value esGzMLbvcnKvnkYZGzhHxw==
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 113 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 114 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 115 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 116 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 117 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 118 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 119 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 120 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 121 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 122 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO smallerHash Making /identity/rnmine request to pkOther value esGzMLbvcnKvnkYZGzhHxw==
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 123 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 124 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 125 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 126 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"id":128,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":129,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":130,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":131,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":132,"ok":true,"name":"should be equal","operator":"equal","actual":408768,"expected":408768,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":133,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":134,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: Ktm0vo0u4+KH5xraP8zIXA==;John
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":135,"ok":true,"name":"should be equal","operator":"equal","actual":48270,"expected":48270,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":136,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":137,"ok":true,"name":"should be equal","operator":"equal","actual":"Ktm0vo0u4+KH5xraP8zIXA==;John","expected":"Ktm0vo0u4+KH5xraP8zIXA==;John","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":138,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: esGzMLbvcnKvnkYZGzhHxw==;Srikanth
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":139,"ok":true,"name":"should be equal","operator":"equal","actual":50766,"expected":50766,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":140,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":141,"ok":true,"name":"should be equal","operator":"equal","actual":"esGzMLbvcnKvnkYZGzhHxw==;Srikanth","expected":"esGzMLbvcnKvnkYZGzhHxw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":142,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO smallerHash Making /identity/cb request to pkOther value esGzMLbvcnKvnkYZGzhHxw==
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 127 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 128 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 129 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 130 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 131 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 132 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 133 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO smallerHash Making /identity/rnmine request to pkOther value esGzMLbvcnKvnkYZGzhHxw==
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 134 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 135 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 136 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 137 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 138 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 139 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"id":143,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":144,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 140 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 141 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 142 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"id":145,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":146,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":147,"ok":true,"name":"should be equal","operator":"equal","actual":940608,"expected":940608,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":148,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":149,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: Ktm0vo0u4+KH5xraP8zIXA==;John
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":150,"ok":true,"name":"should be equal","operator":"equal","actual":48270,"expected":48270,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":151,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":152,"ok":true,"name":"should be equal","operator":"equal","actual":"Ktm0vo0u4+KH5xraP8zIXA==;John","expected":"Ktm0vo0u4+KH5xraP8zIXA==;John","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":153,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO identityExchange We will advertise the following device name as we start: esGzMLbvcnKvnkYZGzhHxw==;Srikanth
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":154,"ok":true,"name":"should be equal","operator":"equal","actual":50766,"expected":50766,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":155,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":156,"ok":true,"name":"should be equal","operator":"equal","actual":"esGzMLbvcnKvnkYZGzhHxw==;Srikanth","expected":"esGzMLbvcnKvnkYZGzhHxw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":157,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO smallerHash Making /identity/cb request to pkOther value esGzMLbvcnKvnkYZGzhHxw==
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 143 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 144 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 145 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): INFO smallerHash Making /identity/rnmine request to pkOther value esGzMLbvcnKvnkYZGzhHxw==
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 146 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 147 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"id":158,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":159,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":160,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":161,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":162,"ok":true,"name":"should be equal","operator":"equal","actual":795008,"expected":795008,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":163,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":164,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"end","test":28}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"test","name":"teardown","id":29}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 148 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 149 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 150 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 151 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 152 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 153 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 154 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 155 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 156 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63),
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 157 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 158 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63),
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 159 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63),
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 160 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63),
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 161 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 162 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63),
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 163 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63),
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 164 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63),
I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 29 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,I/jxcore-log( 6995): {"type":"end","test":29}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"test","name":"setup","id":30}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 30 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog( 2408): !@Sync 22
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,I/jxcore-log( 6995): {"type":"end","test":30}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"test","name":"test compareEqualSizeBuffers","id":31}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":1,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":2,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":3,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":4,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"Buffers must be of the same size."},"test":31,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"},
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":8,"ok":true,"name":"should be equal","operator":"equal","actual":0,"expected":0,"test":31,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":0,"expected":0,"test":31,"type":"assert"}
I/jxcore-log( 6995): 
D/BatteryService( 2408): level:100, scale:100, status:2, health:2, present:true, voltage: 4383, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
I/jxcore-log( 6995): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":1,"expected":1,"test":31,"type":"assert"}
I/jxcore-log( 6995): 
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
I/jxcore-log( 6995): {"id":11,"ok":true,"name":"should be equal","operator":"equal","actual":1,"expected":1,"test":31,"type":"assert"}
I/jxcore-log( 6995): 
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
I/jxcore-log( 6995): {"type":"end","test":31}
I/jxcore-log( 6995): 
I/jxcore-log( 6995): {"type":"test","name":"teardown","id":32}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 31 isOK: undefined : test compareEqualSizeBuffers", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 32 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 340, Delta = 10
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2408): prevTemp = 306, currTemp = 307, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager( 2408): Waited long enough for: ServiceRecord{45beb6a0 u0 com.sec.android.app.videoplayer/.videowall.TranscodeService}
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,I/jxcore-log( 6995): {"type":"end","test":32}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"test","name":"setup","id":33}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 33 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2408): level:100, scale:100, status:2, health:2, present:true, voltage: 4383, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 340, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 307, currTemp = 308, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,I/jxcore-log( 6995): {"type":"end","test":33}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"type":"test","name":"Make sure we return 404 before hitting start","id":34}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 34 isOK: undefined : Make sure we return 404 before hitting start", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":34,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"end","test":34}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"test","name":"teardown","id":35}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 35 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/PowerManagerService( 2408): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 2408): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2408): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/lights  ( 2408): lcd : 2 +
D/RampAnimator( 2408): Light Animator Finished currentValue=2
,D/lights  ( 2408): lcd : 2 -
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,I/jxcore-log( 6995): {"type":"end","test":35}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"test","name":"setup","id":36}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 36 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/SensorService( 2408):   0.3 0.0 9.8
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
V/AlarmManager( 2408): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2408): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
V/AlarmManager( 2408): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5245): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionTIME_TICK
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 5245): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5245): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 5245): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/PowerManagerService( 2408): [s] UserActivityState : 2 -> 0
I/PowerManagerService( 2408): Nap time...
D/PowerManagerService( 2408): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2408): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2408): Going to sleep due to screen timeout...
,D/PowerManagerService( 2408): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/Sensors ( 2408): LightSensor enable = 0
,D/Sensors ( 2408): LightSensor enableSensor = 0
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
I/SurfaceFlinger( 1921): id=25 createSurf (720x1280),-1 flag=20004, FlectronBea
D/SensorManager( 2408): unregisterListener ::   
,I/Sensors ( 2408): HAL:resetDataRates mEnabled=4
D/DisplayPowerController( 2408): !@ElectronBeam entry
,D/SensorManager( 2408): unregisterListener ::   
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/PowerManagerService( 2408): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2582
,I/PowerManagerService( 2408): !@[ps] Screen__On(wake lock) :  wl: PowerUI
I/PowerManagerService( 2408): Waking up from sleep...
D/PowerManagerService( 2408): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 2408): Screen Readiness Inspection requested: mNestCount=1
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2408): sendNotification(1) - 5
,D/PowerManagerNotifier( 2408): mBroadcastInProgress = true , mActualPowerState = 1 , mPendingWakeUpBroadcast = true , mPendingGoToSleepBroadcast = true , mBroadcastedPowerState = 1
,V/WindowOrientationListener( 2408): WindowOrientationListener disabled
,D/PowerManagerService( 2408): [s] WAKEFULNESS_AWAKE
D/lights  ( 2408): button : 1 +
D/NotificationService( 2408): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200a5 contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
D/lights  ( 2408): button : 1 -
D/KeyguardViewMediator( 2582): onScreenTurnedOff(3)
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
D/SensorService( 2408): AutoRotationSensor::activate (ident=0x7bd618f0, enabled=0)
,I/Sensors ( 2408): HAL: batch Dry Run is complete,
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 ,
D/Sensors ( 2408): LightSensor setDelay = 200000000
D/Sensors ( 2408): LightSensor setSensorDelay = 200000000,
,I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/Sensors ( 2408): Light sensor flush: not enabled 0
D/Sensors ( 2408): LightSensor enable = 1
D/Sensors ( 2408): LightSensor enableSensor = 1
,D/LockPatternUtils( 2582): isPcwEnable = 10
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2408): [DAB] no lux value from sensor manager
D/DisplayPowerController( 2408): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/SensorManager( 2408): unregisterListener ::   
D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 1
D/InputDispatcher( 2408): setInputDispatchMode: enabled=0, frozen=0
D/RCPManagerService( 2408): NotificationReceiver onReceive()
,D/RCPManagerService( 2408):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
,I/Sensors ( 2408): HAL: batch Dry Run is complete
,D/PowerManagerService( 2408): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 19ms
I/Sensors ( 2408): HAL:resetDataRates mEnabled=4
D/RCPManagerService( 2408): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967298408
D/LockPatternUtils( 2582): isPcwEnable = 10
D/ProgressBar( 2582): setProgressDrawable drawableHeight = 12
D/RCPManagerService( 2408): getPolicy: policy value returned = false
D/RCPManagerService( 2408): going to get the app label for pkg == com.android.systemui
D/RCPManagerService( 2408): app label == com.android.systemui
,D/RCPManagerService( 2408): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967298408
D/UserManagerService( 2408): User -1does not exists!!
D/RCPManagerService( 2408): getPolicy: policy value returned = true
D/RCPManagerService( 2408): Calling User is -1
,D/RCPManagerService( 2408): userid of SBN ==-1
E/PersonaManagerService( 2408): returning null in  getPersonasForUser
,D/lights  ( 2408): lcd : 0 +
,D/PhoneStatusBar( 2582): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@422a3608
,D/lights  ( 2408): lcd : 0 -
,D/SensorManager( 2408): registerListener :: 2, MPL Accelerometer, 200000, 0,  
D/DisplayPowerController( 2408): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2408): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 28ms
I/SQLiteSecureOpenHelper( 4119): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4119): getDatabaseLocked(b,b,pwd)...
,D/KeyguardViewMediator( 2582): setting alarm to turn off keyguard, seq = 5
D/BatteryMeterView( 2582): onDraw batteryColor : -1
,D/LightsService( 2408): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2408) 
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
,D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 2408): turn on LED for fully charged
D/VibratorService( 2408): JNI vibratorOff()
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2408): ACTION_SCREEN_OFF
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
,D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/AudioHardwareTinyALSA( 1929): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2408): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2408): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2408): Bridge Server is not available
,D/PersonaManagerService( 2408): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2408): MSG_ACTION_SCREEN_OFF called
,D/STATUSBAR-PhoneStatusBar( 2582):      ACTION_SCREEN_OFF is received!!!! 
,D/STATUSBAR-PhoneStatusBar( 2582): makeExpandedInvisible
D/PhoneStatusBarView( 2582): marqueeStatusBar:125, mClearCover:0
,D/STATUSBAR-PhoneStatusBar( 2582):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2758): applyRouting return - 2 
,E/NfcService( 2758): callback == null
,D/Sensors ( 2408): LightSensor sending flush event 16
D/Sensors ( 2408): LightSensor setDelay = 200000000
,D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
D/SensorManager( 2408): unregisterListener ::   
,D/lights  ( 2408): led_pattern : 5 +
D/LightsService( 2408): [SvcLED]  onSensorChanged::light value = 0
D/DisplayPowerController( 2408): [api] [DAB] onSensorChanged : 1st lux : 0.0
D/DisplayPowerController( 2408): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
,D/lights  ( 2408): led_pattern : 5 -
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/LockPatternUtils( 2582): isPcwEnable = 10
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 340, Delta = 0
,D/QuickConnect[1.1][2] ( 5022): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
V/QuickConnect[1.1][2] ( 5022): BleHelper.shouldScanBleBg - 
,D/QuickConnect[1.1][2] ( 5022): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
D/QuickConnect[1.1][2] ( 5022): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 5022): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 5022): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 5022): stopLeScan()
,D/QuickConnect[1.1][2] ( 5022): BleHelper.stopScan - call stopLeScan() complete
,E/TranscodeReceiver( 5728): onReceive : android.intent.action.SCREEN_OFF
,D/TranscodeService( 5728): power? : true / screen off : true
,D/TranscodeService( 5728): Music is = false
,D/TranscodeService( 5728): runvideoplayer is false
,D/TranscodeService( 5728): Thread start
D/TranscodeService( 5728): WakeLock.acquire()
,D/videowall-FileMgr( 5728): thumbnailDBSync -1
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 65558
D/SensorService( 2408): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2408): AutoRotationSensor::activate (ident=0x7cb83f50, enabled=1)
D/SensorService( 2408): AutoRotationSensor::AR_init
,I/Sensors ( 2408): HAL: batch Dry Run is complete
,I/Sensors ( 2408): HAL:resetDataRates mEnabled=4
,D/SensorService( 2408): AutoRotationSensor::process: Acc  eventTimestamp = 699558888935, previousAccTimestamp = 699215359143, difference = 343529792 
D/SensorService( 2408): AutoRotationSensor::reset oldrotation = [100], initState = [1]
D/SensorManager( 2408): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
,V/KeyguardServiceDelegate( 2408): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@456fd7c0)
,D/InputDispatcher( 2408): setInputDispatchMode: enabled=1, frozen=0
,D/KeyguardViewMediator( 2582): onScreenTurnedOn, seq = 6
D/KeyguardViewMediator( 2582): notifyScreenOnLocked
D/KeyguardViewMediator( 2582): handleNotifyScreenOn
D/KeyguardViewManager( 2582): onScreenTurnedOn()
I/KeyguardEffectViewMain( 2582): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 2582): KeyguardEffectViewParticleSpace : screenTurnedOn
,D/VisualEffectParticleEffect( 2582): screenOnAnimationStart
,V/KeyguardServiceDelegate( 2408): **** SHOWN CALLED ****
,D/LockPatternUtils( 2582): isPcwEnable = 10
V/KeyguardViewManager( 2582): send wm null token: host was null
I/WindowManager( 2408): No lock screen! windowToken=null
I/SurfaceFlinger( 1921): id=25 Removed FlectronBea (10/10)
,I/SurfaceFlinger( 1921): id=25 Removed FlectronBea (-2/10)
,D/lights  ( 2408): lcd : 2 +
,D/lights  ( 2408): lcd : 2 -
D/PowerManagerNotifier( 2408): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/PowerManagerService( 2408): Screen Readiness Inspection completed: mNestCount=0
D/DisplayPowerController( 2408): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController( 2408): !@ElectronBeam exit
D/DisplayPowerController( 2408): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2408): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/LockPatternUtils( 2582): isPcwEnable = 10
D/StatusBarManagerService( 2408): semi p:6995,o:f
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
,D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/PalmMotionService( 2408): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/PalmMotionService( 2408): SURFACE_PALM_SWIPE: 1
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,I/FPMS_FingerprintManagerService( 2602): onReceive: android.intent.action.USER_PRESENT
,E/MotionRecognitionService( 2408):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN,
D/SamsungIME( 2984): showDlgMsgBox : false true true
I/NfcService( 2758): applyRouting return - 2 
D/PhoneStatusBar( 2582): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/SSRMv2:TSP:AirViewOnOff( 2408): SettingsAirViewInfo:: 000000000,
E/NfcService( 2758): callback == null
,D/TranscodeService( 5728): Thread end,
D/Sensors ( 2408): LightSensor setDelay = 200000000
D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
D/SensorManager( 2408): unregisterListener ::   
,D/lights  ( 2408): led_pattern : 0 +,
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 2408) 
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 2408): turn off LED
,D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/TranscodeService( 5728): WakeLock.release()
,D/lights  ( 2408): led_pattern : 0 -,
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/TranscodeService( 5728): onDestroy()
D/LockPatternUtils( 2582): isPcwEnable = 10
,D/TranscodeService( 5728): releaseTranscodeThread.
,V/ApplicationPolicy( 2408): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
,D/Sensors ( 2408): LightSensor sending flush event 16
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2408): ACTION_SCREEN_ON
,D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/AudioHardwareTinyALSA( 1929): setParameters(screen_state=on)
I/SecExternalDisplayIntents_Java( 2408): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/SensorService( 2408): AutoRotationSensor::process: Acc  eventTimestamp = 699714341560, previousAccTimestamp = 699215359143, difference = 498982417 
D/SensorService( 2408):  [AR] 0.3 0.0 9.9
D/SensorService( 2408): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
D/IpRemoteDisplayController( 2408): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2408): Bridge Server is not available
,D/PersonaManagerService( 2408): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 2408): MSG_ACTION_SCREEN_ON called
,I/NfcService( 2758): NFC: Screen On & Cover Open
,I/NfcService( 2758): applyRouting return - 2 
,E/NfcService( 2758): callback == null
,D/STATUSBAR-NetworkController( 2582): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,D/SensorService( 2408):   0.3 0.0 9.9
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 340, Delta = 0
,D/QuickConnect[1.1][2] ( 5022): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
V/QuickConnect[1.1][2] ( 5022): BleHelper.shouldScanBleBg - 
,D/QuickConnect[1.1][2] ( 5022): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
V/QuickConnect[1.1][2] ( 5022): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
D/QuickConnect[1.1][2] ( 5022): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 5022): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 5022): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 5022): BleHelper.startScan - shouldScanBleFg = false
D/daemonapp( 5245): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 5245): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 5245): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5245): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1448366400000
D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1448345463129
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 5245): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
D/daemonapp( 5245): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 5245): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 5245): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 5245): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 5245): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 5245): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionSCREEN_ON
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/PowerManagerService( 2408): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5245): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5245): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5245): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 5245): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5245): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 5245): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5245): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/SSRMv2:TSP:AirViewOnOff( 2408): SettingsAirViewInfo:: 000000000
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/lights  ( 2408): button : 0 +
,D/lights  ( 2408): button : 0 -
,D/AmoledAdjustTimer( 2408): prevTemp = 308, currTemp = 310, prevStep = 4, currStep = 4
,I/jxcore-log( 6995): {"type":"end","test":36}
I/jxcore-log( 6995): 
,E/jxcore-log( 6995): (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
E/jxcore-log( 6995): 
,E/jxcore-log( 6995): Trace: 
E/jxcore-log( 6995):     at Console.prototype.trace@console.js:169:13
E/jxcore-log( 6995):     at addListener@events.js:140:7
E/jxcore-log( 6995):     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/pouchdb-all-dbs/index.js:61:3
E/jxcore-log( 6995):     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:138:9
E/jxcore-log( 6995):     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/util.js:26:16
E/jxcore-log( 6995):     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:507:13
E/jxcore-log( 6995):     at module.exports/Promise.prototype._settlePromiseAt@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:581:13
E/jxcore-log( 6995):     at module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/
,E/jxcore-log( 6995): (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
E/jxcore-log( 6995): 
,E/jxcore-log( 6995): Trace: 
E/jxcore-log( 6995):     at Console.prototype.trace@console.js:169:13
E/jxcore-log( 6995):     at addListener@events.js:140:7
E/jxcore-log( 6995):     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/pouchdb-all-dbs/index.js:85:3
E/jxcore-log( 6995):     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:138:9
E/jxcore-log( 6995):     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/util.js:26:16
E/jxcore-log( 6995):     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:507:13
E/jxcore-log( 6995):     at module.exports/Promise.prototype._settlePromiseAt@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:581:13
E/jxcore-log( 6995):     at module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"type":"test","name":"Random path after start, need 404","id":37}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 37 isOK: undefined : Random path after start, need 404", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6995): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":37,"type":"assert"}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"end","test":37}
I/jxcore-log( 6995): 
,I/jxcore-log( 6995): {"type":"test","name":"teardown","id":38}
I/jxcore-log( 6995): 
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 6995): [INFO:CONSOLE(63)] "logCallback 38 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,V/AlarmManager( 2408): waitForAlarm result :4
,D/KeyguardViewMediator( 2582): received DELAYED_KEYGUARD_ACTION with seq = 5, mDelayedShowingSequence = 6
V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2408):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 23
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SensorService( 2408):   0.3 0.0 9.9
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 340, Delta = 0
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2408): prevTemp = 310, currTemp = 311, prevStep = 4, currStep = 4
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/PowerManagerService( 2408): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2582 (0x0)
I/PowerManagerService( 2408): Nap time...
,D/PowerManagerService( 2408): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2408): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2408): Going to sleep due to screen timeout...
,D/PowerManagerService( 2408): [s] WAKEFULNESS_ASLEEP
,D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/Sensors ( 2408): LightSensor enable = 0
,D/Sensors ( 2408): LightSensor enableSensor = 0
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,D/SensorManager( 2408): unregisterListener ::   
,I/SurfaceFlinger( 1921): id=26 createSurf (720x1280),-1 flag=20004, FlectronBea
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
,I/Sensors ( 2408): HAL:resetDataRates mEnabled=4
D/DisplayPowerController( 2408): !@ElectronBeam entry
,D/SensorManager( 2408): unregisterListener ::   
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 312, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/lights  ( 2408): lcd : 0 +
,D/lights  ( 2408): lcd : 0 -
,D/PowerManagerService( 2408): blankAllDisplays() is called.
D/MISC PowerHAL( 2408): miscpower_set_interactive: /sys/class/input/input1/enabled
D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/input/input1/enabled: 0
V/WindowOrientationListener( 2408): WindowOrientationListener disabled
D/SensorService( 2408): AutoRotationSensor::activate (ident=0x7cb83f50, enabled=0)
,I/Sensors ( 2408): HAL: batch Dry Run is complete
,D/KeyguardViewMediator( 2582): onScreenTurnedOff(3)
D/PowerManagerService( 2408): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2408): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 2408): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2408): miscpower_set_interactive: /sys/class/input/input0/enabled
D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/SensorManager( 2408): unregisterListener ::   
D/InputDispatcher( 2408): setInputDispatchMode: enabled=0, frozen=0
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/PowerManagerService( 2408): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/SurfaceFlinger( 1921): Screen released, type=0 flinger=0x404f8008
D/LockPatternUtils( 2582): isPcwEnable = 10
,D/LockPatternUtils( 2582): isPcwEnable = 10
,I/SQLiteSecureOpenHelper( 4119): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4119): getDatabaseLocked(b,b,pwd)...
,D/KeyguardViewMediator( 2582): setting alarm to turn off keyguard, seq = 6
,D/LightsService( 2408): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2408) 
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
,D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/Sensors ( 2408): LightSensor setDelay = 200000000
D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
D/Sensors ( 2408): Light sensor flush: not enabled 0
D/Sensors ( 2408): LightSensor enable = 1
D/Sensors ( 2408): LightSensor enableSensor = 1
,D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2408): turn on LED for fully charged
D/VibratorService( 2408): JNI vibratorOff()
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2408): ACTION_SCREEN_OFF
,D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
,D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,I/AudioHardwareTinyALSA( 1929): setParameters(screen_state=off)
,I/SecExternalDisplayIntents_Java( 2408): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2408): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2408): Bridge Server is not available
,D/PersonaManagerService( 2408): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2408): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2582):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2582): makeExpandedInvisible
D/PhoneStatusBarView( 2582): marqueeStatusBar:126, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2582):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2758): applyRouting return - 2 
,E/NfcService( 2758): callback == null
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SurfaceControl( 2408): Excessive delay in blankDisplay() while turning screen off: 228ms
I/libsuspend( 2408): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2408): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2408): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 232ms
D/PowerManagerService( 2408): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2408): [PWL] Off : 0s ago
I/PowerManagerService( 2408): [PWL]   PowerManagerService.Broadcasts: ref count=1
,D/LockPatternUtils( 2582): isPcwEnable = 10
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 340, Delta = 0
,D/QuickConnect[1.1][2] ( 5022): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
V/QuickConnect[1.1][2] ( 5022): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5022): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
,V/QuickConnect[1.1][2] ( 5022): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42262688
D/QuickConnect[1.1][2] ( 5022): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 5022): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 5022): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 5022): stopLeScan()
,D/QuickConnect[1.1][2] ( 5022): BleHelper.stopScan - call stopLeScan() complete
,D/PowerManagerService( 2408): [PWL] sb release: PowerManagerService.Broadcasts
,D/Sensors ( 2408): LightSensor enable = 0
,D/LightsService( 2408): [SvcLED]  onSensorChanged::light value = 0
D/Sensors ( 2408): LightSensor enableSensor = 0
D/SensorManager( 2408): unregisterListener ::   
D/lights  ( 2408): led_pattern : 5 +
,D/lights  ( 2408): led_pattern : 5 -
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/AmoledAdjustTimer( 2408): prevTemp = 311, currTemp = 312, prevStep = 4, currStep = 4,
,V/AlarmManager( 2408): waitForAlarm result :4,
,D/KeyguardViewMediator( 2582): received DELAYED_KEYGUARD_ACTION with seq = 6, mDelayedShowingSequence = 6,
,D/LockPatternUtils( 2582): isPcwEnable = 10,
,D/KeyguardViewMediator( 2582): in doKeyguardLocked mIsRollUp false null,
,D/PersonaManager( 2582): isKioskContainerExistOnDevice,
,D/LockPatternUtils( 2582): isPcwEnable = 10,
D/LockPatternUtils( 2582): isPcwEnable = 10
,D/KeyguardViewMediator( 2582): doKeyguard: not showing because lockscreen is off,
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/PowerManagerService( 2408): [PWL] Off : 5s ago,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 340, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 312, currTemp = 312, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2408): [PWL] Off : 15s ago,
,E/Watchdog( 2408): !@Sync 24,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 2408): stay LED for fully charged
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5048): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = -10,
,D/AmoledAdjustTimer( 2408): prevTemp = 312, currTemp = 311, prevStep = 4, currStep = 4,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2408): waitForAlarm result :4
,I/PowerManagerService( 2408): [PWL] Off : 30s ago
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 311, currTemp = 310, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8,
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/dalvikvm( 2408): GC_CONCURRENT freed 3838K, 68% free 25473K/78468K, paused 14ms+18ms, total 235ms,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5048): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 310, currTemp = 310, prevStep = 4, currStep = 4,
,E/Watchdog( 2408): !@Sync 25,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2408): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5048): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,I/PowerManagerService( 2408): [PWL] Off : 50s ago,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 310, currTemp = 309, prevStep = 4, currStep = 4,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2408): mCoverManager.getCoverState() : true,
,D/BatteryService( 2408): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5048): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 309, currTemp = 308, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 308, currTemp = 308, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2408): [PWL] Off : 75s ago,
,E/Watchdog( 2408): !@Sync 26,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5048): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 308, currTemp = 307, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 307, currTemp = 307, prevStep = 4, currStep = 4,
,V/AlarmManager( 2408): waitForAlarm result :8,
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2408): mCoverManager.getCoverState() : true,
,D/BatteryService( 2408): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5048): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2408): prevTemp = 307, currTemp = 306, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2408): [PWL] Off : 105s ago,
,E/Watchdog( 2408): !@Sync 27,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2408): stay LED for fully charged
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2408): prevTemp = 306, currTemp = 305, prevStep = 4, currStep = 4,
,E/Watchdog( 2408): !@Sync 28,
,I/PowerManagerService( 2408): [PWL] Off : 140s ago,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,V/AlarmManager( 2408): waitForAlarm result :8,
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2408): prevTemp = 305, currTemp = 304, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 29,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4,
,I/GAV2    ( 7043): Thread[disconnect check,5,main]: Disconnecting due to inactivity,
,I/GAV2    ( 7043): Thread[disconnect check,5,main]: Disconnected from service,
,I/PowerManagerService( 2408): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4,
,D/TimaService( 2408): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2408): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2408): TimaServiceHandler.handleMessage what =1,
,E/Watchdog( 2408): !@Sync 30,
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2408): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5048): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2408): prevTemp = 304, currTemp = 303, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4,
,V/AlarmManager( 2408): waitForAlarm result :8,
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 225s ago
,E/Watchdog( 2408): !@Sync 31
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2408): prevTemp = 303, currTemp = 302, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 32
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 275s ago
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 33
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,E/SPPClientService( 6570): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2408): !@Sync 34
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 35
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = -10
,D/AmoledAdjustTimer( 2408): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 36
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 37
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2408): !@Sync 38
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 300, currTemp = 301, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 301, currTemp = 302, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2408): [PWL] Off : 455s ago
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2408): !@Sync 39
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4
,D/dalvikvm( 2408): GC_CONCURRENT freed 3936K, 68% free 25472K/78468K, paused 21ms+17ms, total 257ms
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2408): stay LED for fully charged
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 300, currTemp = 301, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4
,D/TimaService( 2408): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2408): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2408): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2408): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4048): GC_CONCURRENT freed 2050K, 29% free 9723K/13648K, paused 3ms+2ms, total 54ms
,D/dalvikvm( 4048): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 525s ago
,E/Watchdog( 2408): !@Sync 41
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 42
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2408): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2408): <AppSync3 Whitelist>
,V/AlarmManager( 2408): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 43
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :4
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2408): LightSensor setDelay = 200000000
,D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
,D/LightsService( 2408): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2408): Light sensor flush: not enabled 0
D/Sensors ( 2408): LightSensor enable = 1
D/Sensors ( 2408): LightSensor enableSensor = 1
D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2408): LightSensor enable = 0
,D/Sensors ( 2408): LightSensor enableSensor = 0
,D/LightsService( 2408): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2408): unregisterListener ::   
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/ConnectivityService( 2408): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
,D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
,E/SPPClientService( 6570): [b] __PingReply__
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 44
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2408): !@Sync 45
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 46
,I/PowerManagerService( 2408): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 47
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 48
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 765s ago
,E/Watchdog( 2408): !@Sync 49
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/TimaService( 2408): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2408): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2408): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 11929
,E/Watchdog( 2408): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2408): !@Sync 51
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 855s ago
,E/Watchdog( 2408): !@Sync 52
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2408): !@Sync 53
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/dalvikvm( 2408): GC_CONCURRENT freed 3886K, 68% free 25478K/78468K, paused 25ms+18ms, total 262ms
,E/Watchdog( 2408): !@Sync 54
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 55
,I/PowerManagerService( 2408): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 56
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2777): GC_CONCURRENT freed 8948K, 36% free 18087K/28080K, paused 28ms+10ms, total 143ms
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 57
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 58
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2408): !@Sync 59
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/TimaService( 2408): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2408): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2408): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2408): Prepared write state in 75ms
,I/ProcessStatsService( 2408): Prepared write state in 34ms
,I/ProcessStatsService( 2408): Pruning old procstats: /data/system/procstats/state-2015-11-23-14-47-39.bin
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 61
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 297, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 1155s ago
,E/Watchdog( 2408): !@Sync 62
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2408): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2408): <AppSync3 Whitelist>
,V/AlarmManager( 2408): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 63
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :4
,V/NetworkStats( 2408): performPollLocked(flags=0x3)
D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,V/NetworkStats( 2408): performPollLocked() took 72ms
D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,I/SELinux (13379): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13379):  
,I/SELinux (13379): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13379):  
I/SELinux (13379):  
,I/SELinux (13379): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (13379): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(13379): >>>>> Normal User
,E/dalvikvm(13379): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (13379): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(13379): in addTimaSignatureService
,D/TimaKeyStoreProvider(13379): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(13379): Added TimaKesytore provider
,D/dalvikvm(13379): GC_CONCURRENT freed 3001K, 30% free 9570K/13620K, paused 3ms+2ms, total 25ms
,D/dalvikvm(13379): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/@ WidgetProvider(13379): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(13379): onUpdate called for widgetId : 0
,D/@ WidgetProvider(13379): Widget random data : 7
,D/@ WidgetProvider(13379): onUpdate called for widgetId : 5
,D/@ WidgetProvider(13379): Widget random data : 6
E/dalvikvm(13379): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(13379): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(13379): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(13379): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(13379): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(13379): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(13379): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(13379): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(13379): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(13379): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(13379): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(13379): VFY: replacing opcode 0x22 at 0x0038
I/ActivityManager( 2408): Killing 6011:com.sec.knox.bridge/1000 (adj 15): empty #43
,D/dalvikvm(13379): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
,D/dalvikvm(13379): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(13379): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(13379): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SPPClientService( 6570): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,I/EventLogService( 3278): Aggregate from 1448344690681 (log), 1448344690681 (data)
,I/System.out(13379): Thread-678(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(13379): Thread-678(ApacheHTTPLog):isShipBuild true
,I/System.out(13379): Thread-678(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out(13379): AsyncNetworking-1-thread-1 calls detatch()
,V/AlarmManager( 2408): waitForAlarm result :8
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2408): LightSensor setDelay = 200000000
D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
,D/LightsService( 2408): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2408): Light sensor flush: not enabled 0
D/Sensors ( 2408): LightSensor enable = 1
D/Sensors ( 2408): LightSensor enableSensor = 1
D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
I/System.out(13379): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(13379): Max ALLOWED memory (MB): 128
V/ImageManager(13379): Max SHOULD USE memory (MB): 128
,V/ImageManager(13379): Max Image Cache memory (MB): 32
,D/skia    (13379): getTotalSize : Do not get file length
,D/@ WidgetProvider(13379): Building widget : 5
,D/Sensors ( 2408): LightSensor enable = 0
,D/Sensors ( 2408): LightSensor enableSensor = 0
,D/SensorManager( 2408): unregisterListener ::   
D/LightsService( 2408): [SvcLED]  onSensorChanged::light value = 2
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/dalvikvm( 2777): GC_FOR_ALLOC freed 677K, 35% free 18493K/28080K, paused 46ms, total 46ms
,I/System.out( 7210): Thread-654 calls detatch()
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2408): !@Sync 64
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4048): GC_CONCURRENT freed 2047K, 29% free 9724K/13648K, paused 2ms+4ms, total 24ms
,D/dalvikvm( 4048): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 65
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 1265s ago
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5048): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,D/dalvikvm( 2408): GC_CONCURRENT freed 3793K, 68% free 25578K/78468K, paused 24ms+18ms, total 259ms
,E/Watchdog( 2408): !@Sync 66
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 67
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/dalvikvm( 6570): GC_CONCURRENT freed 1941K, 24% free 10416K/13656K, paused 8ms+4ms, total 70ms
,E/Watchdog( 2408): !@Sync 68
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 69
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 1380s ago
,TIME-OUT KILL (timeout was 1800000ms),D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
D/AndroidRuntime(13730): 
D/AndroidRuntime(13730): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(13730): CheckJNI is OFF
D/AndroidRuntime(13730): setted country_code = Poland
D/AndroidRuntime(13730): setted countryiso_code = PL
D/AndroidRuntime(13730): setted sales_code = PLS
D/AndroidRuntime(13730): readGMSProperty: start
D/AndroidRuntime(13730): readGMSProperty: already setted!!
D/AndroidRuntime(13730): readGMSProperty: end
D/AndroidRuntime(13730): addProductProperty: start
D/dalvikvm(13730): Trying to load lib libjavacore.so 0x0
D/dalvikvm(13730): Added shared lib libjavacore.so 0x0
D/dalvikvm(13730): Trying to load lib libnativehelper.so 0x0
D/dalvikvm(13730): Added shared lib libnativehelper.so 0x0
D/dalvikvm(13730): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack(13730): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug(13730): failed to load memtrack module: -2
D/dalvikvm(13730): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime(13730): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2408): START PACKAGE DELETE: observer{1122144584}
D/PackageManager( 2408): pkg{<packageName>}
D/PackageManager( 2408): user{0}
D/PackageManager( 2408): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2408): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2408): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2408): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2408): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 2408): !@killApplicatoin: 10476, uninstall pkg
I/ActivityManager( 2408): Killing 6995:com.test.thalitest/u0a476 (adj 0): stop com.test.thalitest
I/ActivityManager( 2408): Killing 7650:com.sec.esdk.elm/u0a98 (adj 15): empty for 1800s
I/ActivityManager( 2408): Killing 7636:com.sec.android.app.clockpackage/u0a88 (adj 15): empty for 1800s
I/ActivityManager( 2408): Killing 7332:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty for 1800s
I/ActivityManager( 2408): Killing 7611:com.samsung.android.scloud.sync/u0a64 (adj 15): empty for 1801s
I/ActivityManager( 2408): Killing 5508:com.android.settings/1000 (adj 15): empty for 1801s
I/ActivityManager( 2408): Killing 6414:com.osp.app.signin/u0a44 (adj 15): empty for 1801s
I/ActivityManager( 2408): Killing 7268:com.sec.android.soagent/u0a38 (adj 15): empty for 1801s
I/ActivityManager( 2408): Killing 6297:com.sec.android.service.health/u0a16 (adj 15): empty for 1801s
I/ActivityManager( 2408): Killing 7525:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1801s
I/ActivityManager( 2408): Killing 7228:com.samsung.klmsagent/u0a18 (adj 15): empty for 1802s
I/ActivityManager( 2408): Killing 7198:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1802s
I/ActivityManager( 2408): Killing 7449:com.samsung.android.service.travel/u0a170 (adj 15): empty for 1804s
I/ActivityManager( 2408): Killing 7083:tv.peel.smartremote/u0a165 (adj 15): empty for 1804s
I/ActivityManager( 2408): Killing 7434:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1805s
I/ActivityManager( 2408): Killing 7411:com.android.email/u0a157 (adj 15): empty for 1805s
I/ActivityManager( 2408): Killing 6458:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1806s
I/ActivityManager( 2408): Killing 7362:com.google.android.apps.magazines/u0a115 (adj 15): empty for 1806s
I/ActivityManager( 2408): Killing 6355:com.policydm/1000 (adj 15): empty for 1807s
I/ActivityManager( 2408): Killing 7282:com.sec.android.app.voicenote/1000 (adj 15): empty for 1807s
I/ActivityManager( 2408): Killing 7125:com.vlingo.midas/u0a34 (adj 15): empty for 1807s
I/ActivityManager( 2408): Killing 5972:com.sec.android.diagmonagent/1000 (adj 15): empty for 1809s
I/ActivityManager( 2408): Killing 6250:com.sec.pcw.device/1000 (adj 15): empty for 1809s
I/ActivityManager( 2408): Killing 5997:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1813s
D/PointerIcon( 2408): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2408): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2408): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2408): setHoveringSpenCustomIcon IconType is same.1
I/SurfaceFlinger( 1921): id=19 Removed EimLayer (5/10)
I/SurfaceFlinger( 1921): id=19 Removed EimLayer (-2/10)
I/SurfaceFlinger( 1921): id=18 Removed EimLayer (4/9)
I/SurfaceFlinger( 1921): id=18 Removed EimLayer (-2/9)
V/WindowManager( 2408): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
W/InputDispatcher( 2408): channel ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher( 2408): channel ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher( 2408): Attempted to unregister already unregistered input channel
I/WindowState( 2408): WIN DEATH: Window{42f07f88 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1921): id=20 Removed NainActivit (6/8)
I/SurfaceFlinger( 1921): id=20 Removed NainActivit (-2/8)
D/Launcher( 2777): onRestart, Launcher: 1109958720
D/Launcher( 2777): onStart, Launcher: 1109958720
D/Launcher.HomeView( 2777): onStart
I/SurfaceFlinger( 1921): id=20 Removed NainActivit (-2/8)
I/SurfaceFlinger( 1921): id=27 createSurf (720x1280),1 flag=4, Mauncher
D/STATUSBAR-StatusBarManagerService( 2408): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2408): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2408): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2408): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2408): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2408): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager( 2408): Killing 7678:com.sec.android.app.taskmanager/u0a168 (adj 15): empty for 1800s
D/PhoneStatusBar( 2582): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/PhoneStatusBar( 2582): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2408): tr p:2777,o:f
D/StatusBarManagerService( 2408): semi p:2777,o:f
W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 2408): Got RemoteException sending setActive(false) notification to pid 6995 uid 10476
W/PackageSettings( 2408): Skipping PackageSetting{42384e28 com.example.hello/10475} due to missing metadata
D/PackageManager( 2408): checkUidPermission - Execution time: 215 ms
D/PackageManager( 2408): checkUidPermission - Execution time: 130 ms
D/PackageManager( 2408): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10476, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/PackageManager( 2408): checkUidPermission - Execution time: 168 ms
D/dalvikvm( 5894): GC_EXPLICIT freed 597K, 27% free 9984K/13676K, paused 14ms+6ms, total 113ms
D/PackageManager( 2408): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10476, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 2950): GC_EXPLICIT freed 1453K, 27% free 10025K/13616K, paused 22ms+11ms, total 126ms
I/FPMS_FingerprintManagerService( 2602): onReceive: android.intent.action.PACKAGE_REMOVED
E/SamsungIME( 2984): mOCRHelper is null
D/QuickConnect[1.1][2] ( 5022): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
W/GeofencerStateMachine( 2736): Ignoring removeGeofence because network location is disabled.
I/SELinux (13764): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13764):  
I/PackageManager( 2408):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2408):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2408):   Scheme: "sms"
I/PackageManager( 2408): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2408):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2408):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2408):   Scheme: "smsto"
I/PackageManager( 2408): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (13764): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13764):  
I/SELinux (13764):  
I/SELinux (13764): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13764): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13764): >>>>> Normal User
E/dalvikvm(13764): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux (13764): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(13764): in addTimaSignatureService
D/TimaKeyStoreProvider(13764): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13764): Added TimaKesytore provider
D/dalvikvm( 2408): GC_EXPLICIT freed 2140K, 68% free 25579K/78468K, paused 20ms+34ms, total 340ms
D/dalvikvm( 2408): WAIT_FOR_CONCURRENT_GC blocked 98ms
I/PackageManager( 2408):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2408):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2408):   Scheme: "mms"
I/PackageManager( 2408): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/InputReader( 2408): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 2408):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2408):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2408):   Scheme: "mmsto"
I/PackageManager( 2408): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RegisteredServicesCache( 2758): empty dynamic service
I/PackageManager( 2408):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2408):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2408):   Scheme: "sms"
I/PackageManager( 2408): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService( 2408): PackageReceiver onReceive()
I/PackageManager( 2408):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2408):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2408):   Scheme: "smsto"
I/PackageManager( 2408): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/HarmonyEASService( 2408): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/dalvikvm(13764): GC_CONCURRENT freed 2997K, 30% free 9566K/13612K, paused 5ms+2ms, total 36ms
D/dalvikvm(13764): WAIT_FOR_CONCURRENT_GC blocked 29ms
I/PackageManager( 2408):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2408):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2408):   Scheme: "mms"
I/PackageManager( 2408): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2408):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2408):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2408):   Scheme: "mmsto"
I/PackageManager( 2408): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132(13764): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132(13764): ELMEngine.ELMEngine( context ).
D/elm:14132(13764): MDMBridge.setEnterpriseBridge()
D/elm:14132(13764): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132(13764): ElmAgentService : onCreate()
D/elm:14132(13764): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132(13764): MainReceiver.listeningToPackageRemoved()
D/elm:14132(13764): MDMBridge.getInstance()
D/elm:14132(13764): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux (13778): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13778):  
D/elm:14132(13764): MDMBridge.getAllLicenseInfoFromSDK()
D/EnterpriseDeviceManagerService( 2408): Package has changed for user 0
I/SELinux (13778): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13778):  
I/SELinux (13778):  
I/SELinux (13778): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13778): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13778): >>>>> Normal User
E/dalvikvm(13778): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux (13778): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 2758): GC_CONCURRENT freed 2346K, 25% free 10257K/13644K, paused 9ms+4ms, total 154ms
D/TimaKeyStoreProvider(13778): in addTimaSignatureService
D/TimaKeyStoreProvider(13778): Cannot add TimaSignature Service, License check Failed
D/elm:14132(13764): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/ActivityThread(13778): Added TimaKesytore provider
W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 2408): Killing 7465:com.google.android.talk/u0a109 (adj 15): empty for 1800s
D/elm:14132(13764): ElmAgentService : onDestroy().
W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 2408): Killing 5538:com.android.mms/u0a49 (adj 15): empty for 1800s
D/dalvikvm( 2408): GC_EXPLICIT freed 939K, 68% free 25678K/78468K, paused 10ms+37ms, total 538ms
D/CountryDetector( 2408): No listener is left
D/dalvikvm(13778): GC_CONCURRENT freed 2995K, 30% free 9576K/13620K, paused 8ms+1ms, total 51ms
D/dalvikvm(13778): WAIT_FOR_CONCURRENT_GC blocked 34ms
W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService( 2408): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 2408): removePackageParticipantsLocked: uid=10476 #1
W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 2408): delete sourFile : 
I/SELinux (13792): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13792):  
D/PackageManager( 2408): delete native library directory: 
D/PackageManager( 2408): return delete result to caller: 1122144584
D/AndroidRuntime(13730): Shutting down VM
D/PackageManager( 2408): returnCode: 1
D/dalvikvm(13730): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+0ms, total 5ms
I/PackageManager( 2408):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2408):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2408):   Scheme: "sms"
I/PackageManager( 2408): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (13792): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13792):  
I/SELinux (13792):  
I/SELinux (13792): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13792): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13792): >>>>> Normal User
E/dalvikvm(13792): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux (13792): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(13792): in addTimaSignatureService
W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2408):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2408):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2408):   Scheme: "smsto"
I/PackageManager( 2408): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider(13792): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13792): Added TimaKesytore provider
W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2408):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2408):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2408):   Scheme: "mms"
I/PackageManager( 2408): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2408):   Action: "android.intent.action.SENDTO"
W/ApplicationsProvider( 2950): Could not fetch usage stats
W/ApplicationsProvider( 2950): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2950): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2950): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2950): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2950): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2950): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2950): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2950): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2950): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2950): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2950): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2950): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/PackageManager( 2408):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2408):   Scheme: "mmsto"
I/PackageManager( 2408): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(13792): GC_CONCURRENT freed 3005K, 30% free 9568K/13620K, paused 3ms+2ms, total 31ms
D/dalvikvm(13792): WAIT_FOR_CONCURRENT_GC blocked 27ms
W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SELinux (13807): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13807):  
W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/UsbSettingsManager( 2408): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 2408): onPackageRemoved : com.test.thalitest
I/SELinux (13807): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13807):  
I/SELinux (13807):  
I/SELinux (13807): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13807): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(13807): >>>>> Normal User
E/dalvikvm(13807): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
E/SELinux (13807): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(13807): in addTimaSignatureService
D/TimaKeyStoreProvider(13807): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13807): Added TimaKesytore provider
D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2408): stay LED for fully charged
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
V/HeadsetService( 5048): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 5048): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/dalvikvm(13807): GC_CONCURRENT freed 3009K, 30% free 9566K/13620K, paused 4ms+2ms, total 26ms
D/dalvikvm(13807): WAIT_FOR_CONCURRENT_GC blocked 21ms
I/SELinux (13823): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13823):  
I/SELinux (13823): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13823):  
I/SELinux (13823):  
I/SELinux (13823): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13823): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13823): >>>>> Normal User
E/dalvikvm(13823): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
E/SELinux (13823): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/dalvikvm(13823): Enabling JNI app bug workarounds for target SDK version 8...
D/TimaKeyStoreProvider(13823): in addTimaSignatureService
D/TimaKeyStoreProvider(13823): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13823): Added TimaKesytore provider
D/dalvikvm(13823): GC_CONCURRENT freed 2994K, 30% free 9568K/13612K, paused 2ms+2ms, total 24ms
D/dalvikvm(13823): WAIT_FOR_CONCURRENT_GC blocked 21ms
E/SQLiteDatabase(13823): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(13823): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13823): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13823): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(13823): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(13823): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13823): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13823): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13823): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(13823): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(13823): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(13823): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(13823): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(13823): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(13823): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(13823): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/SQLiteDatabase(13823): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase(13823): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase(13823): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase(13823): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase(13823): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase(13823): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(13823): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(13823): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13823): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(13823): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(13823): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(13823): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(13823): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(13823): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(13823): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(13823): Shutting down VM
W/dalvikvm(13823): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(13823): FATAL EXCEPTION: main
E/AndroidRuntime(13823): Process: com.sec.pcw.device, PID: 13823
E/AndroidRuntime(13823): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.URLProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13823): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime(13823): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime(13823): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime(13823): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(13823): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(13823): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(13823): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(13823): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(13823): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(13823): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(13823): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(13823): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(13823): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(13823): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13823): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(13823): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(13823): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(13823): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(13823): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(13823): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(13823): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(13823): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(13823): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(13823): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(13823): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(13823): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime(13823): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime(13823): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/AndroidRuntime(13823): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime(13823): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime(13823): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime(13823): 	... 12 more
E/DropBoxManagerService( 2408): Can't write: system_app_crash
E/DropBoxManagerService( 2408): java.io.FileNotFoundException: /data/system/dropbox/drop242.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2408): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2408): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2408): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2408): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2408): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2408): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2408): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2408): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2408): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2408): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2408): 	... 5 more
I/SELinux (13837): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13837):  
I/Process (13823): Sending signal. PID: 13823 SIG: 9
I/ActivityManager( 2408): Process com.sec.pcw.device (pid 13823) (adj 0) has died.
I/ActivityManager( 2408): Killing 7665:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty for 1800s
I/ActivityManager( 2408): Killing 7696:com.android.providers.calendar/u0a45 (adj 15): empty for 1800s
I/ActivityManager( 2408): Killing 7507:com.android.calendar/u0a144 (adj 15): empty for 1800s
I/SELinux (13837): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13837):  
I/SELinux (13837):  
I/SELinux (13837): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13837): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13837): >>>>> Normal User
E/dalvikvm(13837): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
E/SELinux (13837): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(13837): in addTimaSignatureService
D/TimaKeyStoreProvider(13837): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13837): Added TimaKesytore provider
D/dalvikvm(13837): GC_CONCURRENT freed 2993K, 30% free 9570K/13612K, paused 2ms+1ms, total 22ms
D/dalvikvm(13837): WAIT_FOR_CONCURRENT_GC blocked 19ms
W/System.err(13837): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err(13837): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err(13837): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err(13837): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err(13837): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err(13837): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err(13837): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err(13837): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err(13837): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err(13837): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err(13837): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err(13837): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err(13837): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err(13837): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err(13837): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err(13837): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(13837): 	at android.os.Looper.loop(Looper.java:146)
W/System.err(13837): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err(13837): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err(13837): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err(13837): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err(13837): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err(13837): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err(13837): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err(13837): 	at libcore.io.Posix.open(Native Method)
W/System.err(13837): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err(13837): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err(13837): 	... 21 more
D/GalaxyFinderApplication(13837): [Slink platform] Version = 29011
D/GalaxyFinderApplication(13837): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux (13851): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13851):  
I/SELinux (13851): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13851):  
I/SELinux (13851):  
I/SELinux (13851): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts

```
