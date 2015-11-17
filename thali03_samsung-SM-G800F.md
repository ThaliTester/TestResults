#### Test 509828476dba52d_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/BatteryService( 2405): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2405): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2405): stay LED for fully charged
D/UiModeManager( 2405): mCoverManager.getCoverState() : true
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:2
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/AlarmManager( 2405): waitForAlarm result :4
V/AlarmManager( 2405): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/SSRMv2:SIOP( 2405): SIOP:: AP = 320, Delta = -10
I/PowerManagerService( 2405): [PWL] Off : 30s ago
D/AndroidRuntime( 6720): 
D/AndroidRuntime( 6720): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6720): CheckJNI is OFF
D/AndroidRuntime( 6720): setted country_code = Poland
D/AndroidRuntime( 6720): setted countryiso_code = PL
D/AndroidRuntime( 6720): setted sales_code = PLS
D/AndroidRuntime( 6720): readGMSProperty: start
D/AndroidRuntime( 6720): readGMSProperty: already setted!!
D/AndroidRuntime( 6720): readGMSProperty: end
D/AndroidRuntime( 6720): addProductProperty: start
D/dalvikvm( 6720): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6720): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6720): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6720): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6720): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6720): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6720): failed to load memtrack module: -2
D/dalvikvm( 6720): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6720): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2405): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2405): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2405  pkgName : ACTIVITY_RESUME_BOOSTER@4
I/SurfaceFlinger( 1920): id=21 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1920): id=22 createSurf (16x16),-1 flag=20004, EimLayer
W/ActivityManager( 2405): mDVFSHelper.acquire()
I/SELinux ( 6747): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6747):  
D/PointerIcon( 2405): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2405): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2405): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2405): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6720): Shutting down VM
D/dalvikvm( 6720): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 6747): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6747):  
I/SELinux ( 6747):  
I/SELinux ( 6747): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6747): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6747): >>>>> Normal User
E/dalvikvm( 6747): >>>>> com.test.thalitest [ userId:0 | appId:10446 ]
E/SELinux ( 6747): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 6747): in addTimaSignatureService
D/TimaKeyStoreProvider( 6747): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6747): Added TimaKesytore provider
V/WindowManager( 2405): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SQLiteSecureOpenHelper( 4100): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4100): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (8/10)
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (-2/10)
D/Launcher( 2769): onTrimMemory. Level: 20
D/dalvikvm( 6747): GC_CONCURRENT freed 3013K, 30% free 9559K/13652K, paused 1ms+1ms, total 18ms
D/dalvikvm( 6747): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 6747): Binding Chromium to the background looper Looper (main, tid 1) {422610b8}
I/chromium( 6747): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 6747): Initializing chromium process, renderers=0
W/chromium( 6747): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 6747): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 6747): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6747): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 6747): Mali API Version : 401
,I/Mali    ( 6747): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 6747): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 6747): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 6747): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 6747): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 6747): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 6747): VFY: replacing opcode 0x6e at 0x0008
,D/StatusBarManagerService( 2405): tr p:6747,o:f
D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
W/dalvikvm( 6747): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 6747): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 6747): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 6747): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 6747): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 6747): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 6747): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 6747): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 6747): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6747): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 6747): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 6747): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 6747): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2405): semi p:6747,o:f
,I/SurfaceFlinger( 1920): id=23 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2405): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2405): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2405): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2405): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2405): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2405): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 6747): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 6747): Enabling debug mode 0
,W/AwContents( 6747): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2405): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/AwContents( 6747): nativeOnDraw failed; clearing to background color.
D/CustomFrequencyManagerService( 2405): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2405  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2405): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2405): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2405  pkgName : ACTIVITY_RESUME_BOOSTER@8
W/IInputConnectionWrapper( 6747): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 6747): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 6747): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42261e40
,D/dalvikvm( 6747): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42261e40
D/jxcore_app_log( 6747): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2030416592
,D/JX-Cordova( 6747): jxcore cordova android initializing
I/dalvikvm( 6747): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 6747): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 6747): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 6747): GC_CONCURRENT freed 1285K, 18% free 11346K/13708K, paused 3ms+5ms, total 33ms
,D/dalvikvm( 6747): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 6747): GC_CONCURRENT freed 2121K, 18% free 14772K/17984K, paused 2ms+2ms, total 39ms
,D/dalvikvm( 6747): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/CustomFrequencyManagerService( 2405): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2405  tag : ACTIVITY_RESUME_BOOSTER@8
,D/AmoledAdjustTimer( 2405): prevTemp = 303, currTemp = 302, prevStep = 4, currStep = 4
,D/dalvikvm( 6747): GC_FOR_ALLOC freed 5103K, 29% free 15964K/22420K, paused 49ms, total 49ms
,D/dalvikvm( 6747): GC_CONCURRENT freed 6678K, 31% free 17457K/25236K, paused 1ms+10ms, total 54ms
,D/dalvikvm( 6747): WAIT_FOR_CONCURRENT_GC blocked 38ms
,D/dalvikvm( 6747): GC_FOR_ALLOC freed 1526K, 33% free 17157K/25236K, paused 48ms, total 51ms
,I/dalvikvm-heap( 6747): Grow heap (frag case) to 21.398MB for 3767174-byte allocation
,D/dalvikvm( 6747): GC_FOR_ALLOC freed 5K, 28% free 20831K/28916K, paused 55ms, total 55ms
,W/jxcore-log( 6747): Initializing JXcore engine
,W/jxcore-log( 6747): JXcore engine is ready
,W/jxcore-log( 6747): Starting JXcore engine
,W/jxcore-log( 6747): Platform android
W/jxcore-log( 6747): 
,W/jxcore-log( 6747): Process ARCH arm
W/jxcore-log( 6747): 
,I/jxcore-log( 6747): JXcore Cordova bridge is ready!
I/jxcore-log( 6747): 
,W/jxcore-log( 6747): JXcore engine is started
,I/chromium( 6747): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ContextImpl( 2405): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 6747): Turning radios to true
I/jxcore-log( 6747): 
,W/ActivityManager( 2405): Permission Denial: getCurrentUser() from pid=6747, uid=10446 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 2405): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 2405): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6747, uid=10446 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 2405): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/BluetoothManagerService( 2405): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:620)
W/BluetoothManagerService( 2405): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService( 2405): 	at android.os.Binder.execTransact(Binder.java:404)
W/BluetoothManagerService( 2405): 	at dalvik.system.NativeStart.run(Native Method)
E/DevicePolicyManagerService( 2405): getAllowBluetoothMode - value retunrs : 2
,D/BluetoothManagerService( 2405): foregroundUser: 0
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
,E/BluetoothManagerService( 2405): Package is exist.
,I/WifiManager( 6747): packageName : com.test.thalitest
,I/WifiManager( 6747): setWifiEnabled : true
,I/WifiService( 2405): setWifiEnabled: true pid=6747, uid=10446
,D/BluetoothAdapterState( 5016): CURRENT_STATE=OFF, MSG = USER_TURN_ON
I/BluetoothAdapterState( 5016): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 5016): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5016): updateAdapterState state is 11
,W/ActivityManager( 2405): Permission Denial: getCurrentUser() from pid=6747, uid=10446 requires android.permission.INTERACT_ACROSS_USERS
D/BluetoothAdapterService( 5016): Broadcasting updateAdapterState() to 1 receivers.
W/WifiService( 2405): Failed getting userId using ActivityManagerNative
W/WifiService( 2405): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6747, uid=10446 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2405): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2405): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2405): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2405): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2405): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2405): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapterService( 5016): Autoconnection is available 
D/BluetoothAdapterService( 5016): updateAdapterState prevState = 10newState = 11
D/BtConfig.SecureMode( 5016): isSecureModeOn:false
,D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/InputMethodManagerService( 2405): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 2405): [BT Setting State] State =11
W/BluetoothAdapterService( 5016): isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5016): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/PhoneApp( 2753): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 11
W/BluetoothAdapterService( 5016): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.android.bluetooth.hid.HidService
I/SamsungIME( 2961): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
I/QuickConnect[1.1][2] ( 4990): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_ON
W/BluetoothAdapterService( 5016): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
E/WifiHW  ( 2405): ##################### set firmware type 0 #####################
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/WifiHW  ( 1915): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
W/BluetoothAdapterService( 5016): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.android.bluetooth.pan.PanService
E/WifiHW  ( 1915): Cannot open "/data/.cid.info": No such file or directory
I/WifiHW  ( 1915): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
E/WifiHW  ( 1915): TEMP_FAILURE_RETRY complete
D/SoftapController( 1915): Softap fwReload - Ok
W/BluetoothAdapterService( 5016): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 5016): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5016): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5016): Unable to stop service com.android.bluetooth.gatt.GattService. Invalid state: 12
W/BluetoothAdapterService( 5016): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5016): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/CommandListener( 1915): Setting iface cfg
,D/CommandListener( 1915): Trying to bring down wlan0
,W/BluetoothAdapterService( 5016): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5016): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5016): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5016): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5016): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5016): Not skipping com.android.bluetooth.hdp.HealthService
,D/WifiHW  ( 2405): Skip the update_ctrl_interface
,D/WifiHW  ( 2405): Skip the update_ctrl_interface
,E/WifiHW  ( 2405): supplicant_name : p2p_supplicant
,D/HeadsetService( 5016): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 5016): classInitNative: succeeds
,D/HeadsetStateMachine( 5016): Version 1.5
,D/HeadsetStateMachine( 5016): make
,D/WifiMonitor( 2405): startMonitoring(wlan0) with mConnected = false
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/BluetoothNotiBroadcastReceiver( 5484): onReceive
,E/HeadsetStateMachine( 5016): # of Max HF connection is 2
,W/BluetoothAdapterService( 5016): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5016): Not skipping com.android.bluetooth.pan.PanService
,I/wpa_supplicant( 6798): wpa_supplicant v2.1-devel-4.4.22014-07-16/12:43:14
,I/wpa_supplicant( 6798): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 6798): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 6798): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 6798): getIMSI cannot open file
,E/wpa_supplicant( 6798): Interworking config: - SIM READ ERROR
W/BluetoothAdapterService( 5016): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5016): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/QuickConnect[1.1][2] ( 4990): HeadsetProfile.onServiceConnected - Bluetooth service connected
W/BluetoothAdapterService( 5016): check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5016): Not skipping com.broadcom.bt.service.sap.SapService
,I/SELinux ( 6800): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6800):  
,I/BluetoothAdapterState( 5016): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false,
,I/bluedroid( 5016): get_profile_interface handsfree,
I/SELinux ( 6800): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6800):  
I/SELinux ( 6800):  
,I/SELinux ( 6800): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 6800): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6800): >>>>> Normal User,
,E/dalvikvm( 6800): >>>>> pl.k2.droidoaudioteka [ userId:0 | appId:10066 ],
,E/SELinux ( 6800): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,I/dalvikvm( 6800): Enabling JNI app bug workarounds for target SDK version 7...,
,D/BluetoothAtMessage( 5016): createCMTIContentObservers,
D/TimaKeyStoreProvider( 6800): in addTimaSignatureService,
,D/HeadsetStateMachine( 5016): Enter Disconnected: -2,
I/wpa_supplicant( 6798): >>>>> Not GET KEY, IV <<<<<
E/HeadsetStateMachine( 5016): set to mRemoteBrsf = 0
E/wpa_supplicant( 6798): getIMSI cannot open file
,E/wpa_supplicant( 6798): Interworking config: - SIM READ ERROR
,I/wpa_supplicant( 6798): >>>>> Not GET KEY, IV <<<<<,
D/TimaKeyStoreProvider( 6800): Cannot add TimaSignature Service, License check Failed
,I/wpa_supplicant( 6798): rfkill: Cannot open RFKILL control device,
,D/ActivityThread( 6800): Added TimaKesytore provider,
D/HeadsetStateMachine( 5016): map size, before remove : 0
D/HeadsetStateMachine( 5016): map size, after remove: 0
,D/HeadsetStateMachine( 5016): mNextConnectingDevice : null,
,D/BluetoothA2dp( 4100): Proxy object connected,
,D/BluetoothA2dp( 4990): Proxy object connected
,D/A2dpService( 5016): Received start request. Starting profile...
D/QuickConnect[1.1][2] ( 4990): A2dpProfile.onServiceConnected - Bluetooth service connected
I/BluetoothA2dpServiceJni( 5016): classInitNative: succeeds
D/A2dpStateMachine( 5016): make
,D/BluetoothA2dp( 2405): Proxy object connected
,I/bluedroid( 5016): get_profile_interface a2dp
,I/GKI_LINUX( 5016): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 5016): Enter Disconnected: -2
,I/BluetoothAvrcpServiceJni( 5016): classInitNative: succeeds
,I/bluedroid( 5016): get_profile_interface avrcp
,D/MediaFocusControl( 2405): >>> registerRemoteControlDisplay
,I/BluetoothHidServiceJni( 5016): classInitNative: succeeds
,D/BluetoothInputDevice( 4990): Proxy object connected
D/HidService( 5016): Received start request. Starting profile...
,I/bluedroid( 5016): get_profile_interface hidhost
D/HidService( 5016): setHidService(): set to: null
,I/BluetoothHealthServiceJni( 5016): classInitNative: succeeds
,D/QuickConnect[1.1][2] ( 4990): HidProfile.onServiceConnected - Bluetooth service connected
,D/HealthService( 5016): Received start request. Starting profile...
,I/bluedroid( 5016): get_profile_interface health
,I/BluetoothPanServiceJni( 5016): classInitNative(L105): succeeds
,D/BluetoothPan( 2405): BluetoothPAN Proxy object connected
D/PanService( 5016): Received start request. Starting profile...
D/BluetoothPanServiceJni( 5016): initializeNative(L110): pan
,I/bluedroid( 5016): get_profile_interface pan
,D/BluetoothTethering( 2405): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothMapService( 5016): Received start request. Starting profile...
,W/BluetoothMapMasInstance( 5016): mAccount : null
,I/BluetoothSAPServiceJni( 5016): classInitNative(L204): succeeds
D/SapService( 5016): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 5016): initializeNative(L209): sap
,I/bluedroid( 5016): get_profile_interface sap
,D/HeadsetStateMachine( 5016): Try to query the phonestate on bind
D/BluetoothPhoneService( 2753): handleMessage: 4
,V/BluetoothPhoneService( 2753): Call state Converted2: IDLE/IDLE -> 6
,W/BluetoothHeadset( 2753): Proxy not attached to service
,D/HeadsetStateMachine( 5016): Proxy object connected
,D/HeadsetPhoneState( 5016): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetStateMachine( 5016): Disconnected process message: 11
D/HeadsetPhoneState( 5016): sendDeviceDataStateChanged
D/HeadsetStateMachine( 5016): Disconnected process message: 20
D/HeadsetPhoneState( 5016): Signal level : previous=0 curr=0
V/HeadsetService( 5016): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5016): Disconnected process message: 10
D/HeadsetPhoneState( 5016): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5016): Disconnected process message: 11
D/BluetoothAdapterService( 5016): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5016): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5016): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5016): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5016): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5016): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterState( 5016): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 5016): enable
,D/GKI_LINUX( 5016): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,E/bt-btif ( 5016): Calling BTA_HhEnable
,E/bt-btif ( 5016): btif_storage_get_adapter_property service_mask:0x160040
E/BluetoothServiceJni( 5016): populateRssiValuesNative
I/bluedroid( 5016): getModelRssiValues
,E/BluetoothServiceJni( 5016): model_rssi_values_callback: low = -75, mid = -65, high = 127
,D/dalvikvm( 6800): GC_CONCURRENT freed 2992K, 30% free 9577K/13652K, paused 5ms+5ms, total 36ms
,D/dalvikvm( 6800): WAIT_FOR_CONCURRENT_GC blocked 24ms
,E/BluetoothRemoteDevices( 5016): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BtConfig.SecureMode( 5016): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5016): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 241
,E/BluetoothRemoteDevices( 5016): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 10
,D/BtConfig.SecureMode( 5016): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5016): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 241
,E/BluetoothRemoteDevices( 5016): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,D/BtConfig.SecureMode( 5016): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5016): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 241
,E/BluetoothRemoteDevices( 5016): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,D/BtConfig.SecureMode( 5016): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5016): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 241
,E/BluetoothRemoteDevices( 5016): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,D/BtConfig.SecureMode( 5016): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5016): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 241
,E/BluetoothRemoteDevices( 5016): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/BtConfig.SecureMode( 5016): isSecureModeOn:false
E/BluetoothRemoteDevices( 5016): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 241
E/bt-btif ( 5016): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 5016): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
E/bt-btif ( 5016): btif_sock_init: !radio_req && !rfc_init
,D/IOP_DB_BT( 5016): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 5016): db_open: db_open : handle 2010551340l, read 9734 bytes onto local cache
D/IOP_DB_BT( 5016): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 5016): db_query: result 1
,I/        ( 5016): iop_db_open: iop_db_open status 0
,I/bte_conf( 5016): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 5016): [1] primary_record=1 vendor_id=0x0075 vendor_id_source=0x0001 product_id=0x0100 version=0x0200
I/bte_conf( 5016): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 5016): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothAdapterState( 5016): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5016): ScanMode =  20
,D/BluetoothAdapterProperties( 5016): State =  11
D/BtConfig.SecureMode( 5016): isSecureModeOn:false
D/BtConfig.SecureMode( 5016): isSecureModeOn:false
D/BtConfig.SecureMode( 5016): isSecureModeOn:false
D/BtConfig.SecureMode( 5016): isSecureModeOn:false
D/BtConfig.SecureMode( 5016): isSecureModeOn:false
D/BtConfig.SecureMode( 5016): isSecureModeOn:false
,I/BluetoothAdapterState( 5016): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 5016): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5016): updateAdapterState state is 12
,D/BluetoothAdapterService( 5016): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothA2dp( 4100): onBluetoothStateChange: up=true
,D/BluetoothAdapterService(1109748704)( 5016): Register RemoteMessageListener
D/HeadsetService( 5016): registerMessageListener
D/BluetoothA2dp( 4990): onBluetoothStateChange: up=true
D/BluetoothAdapterService( 5016): Autoconnection is available 
,D/HeadsetStateMachine( 5016): Disconnected process message: 70
D/BluetoothAdapterService( 5016): updateAdapterState prevState = 11newState = 12
D/HeadsetStateMachine( 5016): processRegisterMessageListener : 2, com.android.bluetooth.btservice.RemoteDevices$1@4229d960
,D/BluetoothAdapterService( 5016): starting service from this receiver
,D/BluetoothA2dp( 2405): onBluetoothStateChange: up=true
,W/ContextImpl( 5016): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.startService:506 com.android.bluetooth.btservice.AdapterService.updateAdapterState:653 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
,D/BluetoothPanServiceJni( 5016): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
,D/BluetoothInputDevice( 4990): onBluetoothStateChange: up=true
D/BluetoothAdapterService( 5016): initWakeLock, pfd lock: {ParcelFileDescriptor: FileDescriptor[85]}, pfd unlock: {ParcelFileDescriptor: FileDescriptor[86]}
,I/BluetoothAdapterState( 5016): Entering On State from state = 11
D/bluedroid( 5016): init_wake_lock lock_fd:85, unlock_fd:86
,W/System.err( 6800): java.io.FileNotFoundException: /system/etc/vold.fstab: open failed: ENOENT (No such file or directory)
,I/BluetoothPbapService( 5016): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,D/BluetoothAdapterService(1109748704)( 5016): Get Bonded Devices being called
W/InputMethodManagerService( 2405): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2405): [BT Setting State] State =12
,I/InputMethodManagerService( 2405): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/PhoneApp( 2753): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 12
I/SamsungIME( 2961): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothHeadset( 2753): registerListener : 11, listenercom.android.phone.PhoneGlobals$MessageListener@423d21b8, true
,I/QuickConnect[1.1][2] ( 4990): BluetoothHelper.ACTION_STATE_CHANGED - STATE_ON
,D/BluetoothHeadset( 2753): registerMessageListener
,W/System.err( 6800): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 6800): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 6800): 	at java.util.Scanner.<init>(Scanner.java:158)
W/System.err( 6800): 	at java.util.Scanner.<init>(Scanner.java:138)
,W/System.err( 6800): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.readVoldFile(StorageOptions.java:107)
W/System.err( 6800): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.determineStorageOptions(StorageOptions.java:31)
W/System.err( 6800): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:81)
W/System.err( 6800): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:129)
W/System.err( 6800): 	at pl.k2.droidoaudioteka.ui.AudiotekaApplication.onCreate(AudiotekaApplication.java:171)
W/System.err( 6800): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 6800): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 6800): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 6800): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 6800): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6800): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6800): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 6800): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 6800): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 6800): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 6800): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 6800): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 6800): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 6800): 	at libcore.io.Posix.open(Native Method)
W/System.err( 6800): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 6800): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 6800): 	... 20 more
W/System.err( 6800): file res dir: /data/data/pl.k2.droidoaudioteka/files
W/System.err( 6800): Excternal dir: /mnt/sdcard
D/HeadsetService( 5016): registerMessageListener
D/HeadsetService( 5016): registerMessageListener
D/HeadsetStateMachine( 5016): Disconnected process message: 70
D/HeadsetStateMachine( 5016): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@4232ef68
D/PhoneApp( 2753): registerMessageListener
I/BluetoothPbapService( 5016): Handler(): got msg=1
,D/BluetoothMapMasInstance( 5016): set MAP SDP message type : 1
,V/BluetoothPbapService( 5016): PBAP Service initSocket try: 0
,D/GKI_LINUX( 5016): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:2
,W/BluetoothAdapter( 5016): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 5016): SOCK FLAG = 1 ***********************
,D/GKI_LINUX( 5016): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/BluetoothPbapService( 5016): PBAP Socket is BluetoothServerSocket
,W/BluetoothAdapter( 5016): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 5016): SOCK FLAG = 3 ***********************
,V/MaBo    ( 6800): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6800): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6800): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6800): moge zapisać w resDir?true
,V/MaBo    ( 6800): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
,D/GKI_LINUX( 5016): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,I/System.out( 6800): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6800): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,D/dalvikvm( 2405): GC_EXPLICIT freed 2340K, 56% free 24249K/53956K, paused 10ms+16ms, total 221ms
,D/BluetoothAdapterService(1109748704)( 5016): Get Bonded Devices being called
,W/GAV2    ( 6800): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GAV2    ( 6800): Thread[main,5,main]: ExceptionReporter created, original handler is pl.k2.droidoaudioteka.common.helpers.AudiotekaExceptionHandler
,I/AUDIOTEKA_GA( 6800): init tracking...
,I/AUDIOTEKA_GA( 6800): app started!
,D/AuthorizationBluetoothService( 2852): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/BugSenseHandler( 6800): Registering default exceptions handler
,I/knox    ( 4928): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 4928): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 4928): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 4928): KNOXAgentService : onCreate()
,D/knox    ( 4928): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 4928): KNOXAgentService. startJobThread() start
D/knox    ( 4928): KNOXAgentService. JobThread()
D/knox    ( 4928): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 4928): KNOXAgentService. startJobThread() wait
,I/DownloadService( 6800): Tworzenie serwisu - onCreate()
,I/DownloadService( 6800): Start serwisu - onStart()
,I/BugSenseHandler( 6800): Registering default exceptions handler
,I/SELinux ( 6839): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6839):  
,D/knox    ( 4928): KNOXAgentService : onDestroy().,
,D/knox    ( 4928): ModuleBase.cancelAllAlarmManageModule()
,I/SELinux ( 6839): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 6839):  
I/SELinux ( 6839):  
,I/SELinux ( 6839): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6839): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6839): >>>>> Normal User,
,E/dalvikvm( 6839): >>>>> tv.peel.smartremote [ userId:0 | appId:10165 ],
,E/SELinux ( 6839): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,I/BugSenseHandler( 6800): Flushing...,
,I/BugSenseHandler( 6800): Registering default exceptions handler,
,D/TimaKeyStoreProvider( 6839): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 6839): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6839): Added TimaKesytore provider
,I/BugSenseHandler( 6800): Flushing...
,I/BugSenseHandler( 6800): Registering default exceptions handler
,I/PlayerService( 6800): Tworzenie serwisu - onCreate()
,I/MediaFocusControl( 2405):   Remote Control   registerMediaButtonIntent() for PendingIntent{42e26f80: PendingIntentRecord{43ee2848 pl.k2.droidoaudioteka broadcastIntent}}
,V/KeyguardUpdateMonitor( 2580): handleSetGenerationId(g=2, clear=true)
,V/AUDIOTEKA_MB( 6800): new AudioManagerFocusWrapper in playerservice oncreate
,I/PlayerService( 6800): Start serwisu - onStart()
,D/dalvikvm( 6839): GC_CONCURRENT freed 2996K, 30% free 9566K/13644K, paused 3ms+1ms, total 66ms
,D/dalvikvm( 6839): WAIT_FOR_CONCURRENT_GC blocked 61ms
,D/BluetoothAdapterService(1109748704)( 5016): Get Bonded Devices being called
,W/ContextImpl( 5484): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/Tethering( 2405): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2405): interfaceStatusChanged wlan0, true
,E/Tethering( 2405): No numeric data
,D/Tethering( 2405): sendTetherStateChangedBroadcast 1, 0, 0
I/ConnectivityService( 2405): defaultVal : 1, tetherEnabledInSettings : true
,I/System.out( 6800): Thread-608(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/Tethering( 2405): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2405): interfaceStatusChanged wlan0, true
,D/NtpTrustedTime( 2405): forceRefresh() from cache miss
,I/wpa_supplicant( 6798): wlan0: Setting scan request: 0 sec 100000 usec
,D/NtpTrustedTime( 2405): forceRefresh Fail.
,V/NetworkStats( 2405): performPollLocked(flags=0x1)
D/LocalBluetoothProfileManager( 5484): Adding local A2DP profile
I/System.out( 6800): Thread-608(ApacheHTTPLog):isShipBuild true
I/System.out( 6800): Thread-608(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 6800): Thread-613(ApacheHTTPLog):isShipBuild true
,I/System.out( 6800): Thread-613(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
W/ContextImpl( 5484): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
,I/wpa_supplicant( 6798): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 6798): >>>>> Not GET KEY, IV <<<<<
I/wpa_supplicant( 6798): rfkill: Cannot open RFKILL control device
D/NtpTrustedTime( 2405): forceRefresh() from cache miss
,V/NetworkStats( 2405): performPollLocked() took 28ms
D/NtpTrustedTime( 2405): forceRefresh Fail.
D/Tethering( 2405): interfaceLinkStateChanged p2p0, true
D/Tethering( 2405): interfaceStatusChanged p2p0, true
D/Tethering( 2405): interfaceLinkStateChanged p2p0, true
D/Tethering( 2405): interfaceStatusChanged p2p0, true
,D/LocalBluetoothProfileManager( 5484): Adding local HEADSET profile
,I/System.out( 6800): pool-1-thread-2 calls detatch()
,W/BugSenseHandler( 6800): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
I/wpa_supplicant( 6798): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
I/System.out( 6800): pool-1-thread-1 calls detatch()
,W/BugSenseHandler( 6800): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
,E/BluetoothHeadset( 5484): BTStateChangeCB is registed
W/ContextImpl( 5484): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
,E/BluetoothHeadset( 5484): BluetoothHeadset service is binded
,D/Bluetoothsap( 5484): bindService called to Bluetooth SAP Service
W/ContextImpl( 5484): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,W/ContextImpl( 5484): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
I/wpa_supplicant( 6798): P2P: initialized channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
I/wpa_supplicant( 6798): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant( 6798): Skip scan - bUseNetwork false
,D/WifiStateMachine( 2405): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative( 2405): callSECApiString - ID [21]
I/wpa_supplicant( 6798): HOTSPOT20_ENABLE called
,I/wpa_supplicant( 6798): wlan0: HS20_DISABLED_COMPLETE normal
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,W/ContextImpl( 5484): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
,D/WifiNative( 2405): callSECApiInt - ID [65]
D/LocalBluetoothProfileManager( 5484): PANU : true
,D/LocalBluetoothProfileManager( 5484): Adding local MAP profile
,D/BluetoothMap( 5484): Create BluetoothMap proxy object
W/ContextImpl( 5484): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,E/WifiConfigStore( 2405): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative( 2405): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 6798): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 6798): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 6798): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 6798): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 6798): First Scan Start
,W/ContextImpl( 5484): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
I/wpa_supplicant( 6798): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine( 2405): Set the Nv default ccode
,W/Settings( 5266): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ContextImpl( 5484): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/Bluetoothsap( 5484): bindService called to Bluetooth SAP Service
D/LocalBluetoothProfileManager( 5484): LocalBluetoothProfileManager construction complete
,D/WifiStateMachine( 2405): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,E/WifiStateMachine( 2405): HS20_DISABLED_COMPLETEnormal
D/WifiP2pService( 2405): P2pDisabledState{ what=131203 }
,D/CommandListener( 1915): Setting iface cfg
,D/CommandListener( 1915): Trying to bring up p2p0
,D/WifiMonitor( 2405): startMonitoring(p2p0) with mConnected = true
,D/DockEventReceiver( 5484): finishStartingService: stopping service
D/WifiP2pService( 2405): P2pEnablingState
D/WifiP2pService( 2405): P2pEnablingState{ what=147457 }
D/WifiP2pService( 2405): P2p socket connection successful
D/WifiP2pService( 2405): P2pEnabledState
,E/WifiStateMachine( 2405): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 5484): onReceive
,D/BluetoothA2dp( 5484): Proxy object connected
D/WifiP2pService( 2405): sending p2p connection changed broadcast: IDLE
,D/A2dpProfile( 5484): Bluetooth service connected
,D/QuickConnect[1.1][2] ( 4990): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
D/WifiDisplayController( 2405): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController( 2405): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 2405): disconnect
D/WifiDisplayController( 2405): updateConnection
D/WifiDisplayController( 2405): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 2405): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/WifiP2pStateTracker( 2405): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiDisplayController( 2405): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/QuickConnect[1.1][2] ( 4990): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
I/wpa_supplicant( 6798): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,D/BtConfig.SecureMode( 5016): isSecureModeOn:false
D/WifiDisplayAdapter( 2405): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/QuickConnect[1.1][2] ( 4990): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,D/QuickConnect[1.1][2] ( 4990): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
,D/HeadsetProfile( 5484): Bluetooth service connected
,D/Bluetoothsap( 5484): BluetoothSAP Proxy object connected
,D/SapProfile( 5484): Bluetooth service connected
,D/Bluetoothsap( 5484): getConnectedDevices()
,D/BluetoothInputDevice( 5484): Proxy object connected
,D/HidProfile( 5484): Bluetooth service connected
D/WifiP2pService( 2405): DeviceAddress: 02:e0:6d
D/WifiDisplayController( 2405): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: S5mini-1
D/WifiDisplayController( 2405):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiDisplayController( 2405):  primary type: 10-0050F204-5
D/WifiDisplayController( 2405):  secondary type: null
D/WifiDisplayController( 2405):  wps: 0
D/WifiDisplayController( 2405):  grpcapab: 0
D/WifiDisplayController( 2405):  devcapab: 0
D/WifiDisplayController( 2405):  status: 3
D/WifiDisplayController( 2405):  wfdInfo: null
D/WifiDisplayController( 2405):  groupownerAddress: null
D/WifiDisplayController( 2405):  GOdeviceName: null
D/WifiDisplayController( 2405):  interfaceAddress: 
D/WifiDisplayController( 2405):  SConnectInfo : null
,D/BluetoothPan( 5484): BluetoothPAN Proxy object connected
,D/PanProfile( 5484): Bluetooth service connected
I/System.out( 6800): pool-1-thread-2 calls detatch()
,W/BugSenseHandler( 6800): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
,D/BluetoothMap( 5484): Proxy object connected
,D/MapProfile( 5484): Bluetooth service connected
,D/BluetoothPbap( 5484): Proxy object connected
,D/PbapServerProfile( 5484): Bluetooth service connected
D/Bluetoothsap( 5484): BluetoothSAP Proxy object connected
D/SapProfile( 5484): Bluetooth service connected
,D/Bluetoothsap( 5484): getConnectedDevices()
D/WifiP2pService( 2405): sending p2p persistent groups changed broadcast
D/WifiP2pService( 2405): InactiveState
D/WifiP2pService( 2405): InactiveState{ what=139287 }
D/WifiP2pService( 2405): P2pEnabledState{ what=139287 }
D/WifiP2pService( 2405): DefaultState{ what=139287 }
,D/AuthorizationBluetoothService( 2852): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/QuickConnect[1.1][2] ( 4990): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
I/ActivityManager( 2405): Killing 5548:com.google.android.music:main/u0a125 (adj 15): empty #43
,I/System.out( 6800): pool-1-thread-1 calls detatch()
,W/BugSenseHandler( 6800): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
,E/AuthorizationBluetoothService( 2852): Proximity feature is not enabled.
,I/knox    ( 4928): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 4928): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,W/BluetoothAdapter( 5016): getBluetoothService() called with no BluetoothManagerCallback
,D/knox    ( 4928): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
,I/knox    ( 4928): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
E/BluetoothServiceJni( 5016): SOCK FLAG = 0 ***********************
,D/GKI_LINUX( 5016): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,I/BtOppRfcommListener( 5016): Accept thread started.
D/knox    ( 4928): KNOXAgentService : onCreate()
,D/knox    ( 4928): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 4928): KNOXAgentService. startJobThread() start
D/knox    ( 4928): KNOXAgentService. JobThread()
D/knox    ( 4928): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 4928): KNOXAgentService. startJobThread() wait
,D/knox    ( 4928): KNOXAgentService : onDestroy().
,D/knox    ( 4928): ModuleBase.cancelAllAlarmManageModule()
,D/NearbySettings( 5484): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 5484): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 5484): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 5484): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 5484): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5484): DMSUtil.isNetworkConnected - WIFI: IDLE
I/NearbySettings( 5484): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5484): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5484): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5484): MountReceiver.mPrefHandler - 7002
,D/FileShare-Server( 5867): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Server( 5867): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,D/GKI_LINUX( 5016): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,I/wpa_supplicant( 6798): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,I/wpa_supplicant( 6798): nl80211: Received scan results (3 BSSes)
,I/wpa_supplicant( 6798): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 6798): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2462 MHz)
,I/wpa_supplicant( 6798): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
D/Tethering( 2405): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2405): interfaceStatusChanged wlan0, true
,E/WifiStateMachine( 2405): Error! unhandled message{ when=-6ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 6798): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,I/wpa_supplicant( 6798): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 6798): Associated with C0.AA.48
D/Tethering( 2405): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2405): interfaceStatusChanged wlan0, true
D/Tethering( 2405): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2405): interfaceStatusChanged wlan0, true
D/Tethering( 2405): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2405): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 6798): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 6798): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 6798): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 6798): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 6798): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2405): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2405): interfaceStatusChanged wlan0, true
,D/WifiNative( 2405): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 6876): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6876):  
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 6876): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6876):  
I/SELinux ( 6876):  
,I/SELinux ( 6876): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6876): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6876): >>>>> Normal User
,E/dalvikvm( 6876): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 6876): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 6876): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6876): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6876): Added TimaKesytore provider
,D/WifiP2pService( 2405): InactiveState{ what=143375 }
,D/WifiP2pService( 2405): P2pEnabledState{ what=143375 }
,D/dalvikvm( 6876): GC_CONCURRENT freed 2993K, 30% free 9573K/13648K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 6876): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/System.out( 6876): Inside WakeupProvider
,I/System.out( 6876): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 6876): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 6876): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 6876): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility,
,I/dhcpcd  ( 6888): if(wlan0) info get Success. (MAC : C0.AA.48),
,I/dhcpcd  ( 6888): bssid match,
,D/NearbySettings( 5484): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,V/NearbySettings( 5484): DMSUtil.isNetworkConnected - flag-null, state-null,
,I/NearbySettings( 5484): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR,
,D/DialogFlow( 6876): initQueue()
I/NearbySettings( 5484): DMSUtil.isNetworkConnected - P2P: IDLE,
I/NearbySettings( 5484): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5484): MountReceiver.onReceive - Set preference state off,
,V/NearbySettings( 5484): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2405): Killing 5684:com.android.calendar/u0a144 (adj 15): empty #43
,D/BatteryService( 2405): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2405): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2405): stay LED for fully charged
,D/UiModeManager( 2405): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5016): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5016): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:2
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2405): SIOP:: AP = 340, Delta = 20
,D/PackageManager( 2405): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/WifiP2pService( 2405): InactiveState{ what=143375 },
,D/WifiP2pService( 2405): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2405): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2405): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2405): CaptivePortalCheckState enter
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2405): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2405): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2405): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2405): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2405): evaluateTrafficStatsPolling
D/ConnectivityService( 2405): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2405): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2405): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/NearbySettings( 5484): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 5484): MountReceiver.onReceive - Keep current state
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/ConnectivityService( 2405): handleConnectivityChange: setting default proxy info 
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,D/NearbySettings( 5484): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5484): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5484): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.112 lookup 2 prio 150 2>&1
I/NearbySettings( 5484): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5484): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5484): MountReceiver.onReceive - Keep current state
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/NtpTrustedTime( 2405): forceRefresh() from cache miss
V/NetworkStats( 2405): updateIfacesLocked()
V/NetworkStats( 2405): performPollLocked(flags=0x1)
,V/NetworkStats( 2405): performPollLocked() took 32ms
,D/NearbySettings( 5484): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 5484): MountReceiver.onReceive - Keep current state
,D/NtpTrustedTime( 2405): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1447785895599 mCachedNtpElapsedRealtime : 308640 mCachedNtpCertainty : 14
,D/NtpTrustedTime( 2405): currentTimeMillis() cache hit
D/NtpTrustedTime( 2405): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2405): currentTimeMillis() cache hit
,I/SurfaceFlinger( 1920): id=24 createSurf (1x1),1 flag=4, Uoast
D/NtpTrustedTime( 2405): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2405): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2405): currentTimeMillis() cache hit
V/NetworkStats( 2405): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/PowerManagerService( 2405): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2405
,I/GAV2    ( 6800): Thread[GAThread,5,main]: connecting to Analytics service
,W/ContextImpl( 6800): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:529 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 6800): Thread[GAThread,5,main]: connect: bindService returned true for Intent { act=com.google.android.gms.analytics.service.START (has extras) }
,D/GAV2    ( 6800): Thread[main,5,main]: service connected, binder: android.os.BinderProxy@424ce018
,D/GAV2    ( 6800): Thread[main,5,main]: bound to service
,I/GAV2    ( 6800): Thread[main,5,main]: Connected to service
,I/GAV2    ( 6800): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 6800): Thread[GAThread,5,main]: putHit called
,I/GAV2    ( 6800): Thread[GAThread,5,main]: Sending hit to service
,D/Tethering( 2405): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2405): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2405): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/NtpTrustedTime( 2405): currentTimeMillis() cache hit
D/        ( 2405): Setting time of day to sec=1447785896
,D/        ( 2405): Trying to open a file
D/        ( 2405): File Open Success
,D/        ( 2405): File Close Success
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
,D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0,
,I/        ( 2405): DRM_TIME_PATH CHMOD 660 for resetState done 
V/AlarmManager( 2405): waitForAlarm result :65536
,I/DBG_DM  ( 4595): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/DBG_DM  ( 4595): [3.19.140541][Line:609][onReceive] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_DM  ( 4595): [3.19.140541][Line:214][xdmAgentTaskHandler] XEVENT_DM_INIT
,I/PCWCLIENTTRACE_PushUtil( 6091): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6091): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6091): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6091): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,I/DBG_DM  ( 4595): [3.19.140541][Line:432][xdmInitAdpWaitSystemRootingCheck] Check completed.
D/StatusBar-DoNotDistrub( 2580): Received intent with android.intent.action.TIME_SET action
D/StatusBar-DoNotDistrub( 2580): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/NotificationMgr( 2753): updateNotificationsAtStartup()...
,D/NotificationMgr( 2753): - start call log query...
,W/Settings( 2405): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DBG_DM  ( 4595): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/StatusBar-DoNotDistrub( 2580): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,I/DBG_DM  ( 4595): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 4595): [3.19.140541][Line:78][xdmFeatureGetBearerSettingFromCSCFotaDataBase] 
,E/Parcel  ( 2405): nm 23
,I/AudioService( 2405): getStreamVolume 5 index 110
,D/StatusBar-DoNotDistrub( 2580): The STREAM NOTIFICATION volume is 0
I/PrGenericPlugin( 1923): [A] ENTER onAcquireDrmInfo : 0x1c3
I/PrGenericPlugin( 1923): [A] LEAVE onAcquireDrmInfo : 0x1c3
,I/DrmEventService( 2405):  no response from SecureClock 
,I/SensorManagerA( 2405): getReportingMode :: sensor.mType = 5
D/STATUSBAR-NotificationService( 2405): received android.intent.action.DORMANT_MODE_OFF
D/LightsService( 2405): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2405) 
D/LightsService( 2405): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/STATUSBAR-StatusBarManagerService( 2405): manageDisableList what=0x0 pkg=com.android.systemui
D/Sensors ( 2405): LightSensor setDelay = 200000000
D/Sensors ( 2405): LightSensor setSensorDelay = 200000000
D/Sensors ( 2405): Light sensor flush: not enabled 0
D/Sensors ( 2405): LightSensor enable = 1
D/Sensors ( 2405): LightSensor enableSensor = 1
D/SensorManager( 2405): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/NotificationMgr( 2753): call log query complete.
,D/NotificationMgr( 2753): call log cursor count : 0
,D/NotificationMgr( 2753): call log cursor count2 : null
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,I/SQLiteSecureOpenHelper( 4100): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4100): getDatabaseLocked(b,b,pwd)...
,I/DBG_DM  ( 4595): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
I/dalvikvm( 4595): Total arena pages for JIT: 11
,I/dalvikvm( 4595): Total arena pages for JIT: 12
,I/dalvikvm( 4595): Total arena pages for JIT: 13
I/dalvikvm( 4595): Total arena pages for JIT: 14
,I/dalvikvm( 4595): Total arena pages for JIT: 15
I/dalvikvm( 4595): Total arena pages for JIT: 16
,I/dalvikvm( 4595): Total arena pages for JIT: 17
,I/DBG_DM  ( 4595): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4595): [3.19.140541][Line:5949][xdbGetFUMOInitiatedType] Initiated Type: 2
,I/DBG_DM  ( 4595): [3.19.140541][Line:119][xdmInitAdpEXTInit] nStatus [220]
,I/DBG_DM  ( 4595): [3.19.140541][Line:463][xdmGetEnableLiveDemoFromCSCFeature] enable LiveDemo : false
,E/DBG_DM  ( 4595): Warning!!! [3.19.140541][Line:65][xdmInitAdpGetSIMLockState] SIM Status is not ready
,I/DBG_DM  ( 4595): [3.19.140541][Line:261][xdmInitAdpEXTInit] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 4595): [3.19.140541][Line:271][xdmAgentTaskHandler] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 4595): [3.19.140541][Line:769][xdmUIEvent] XUI_DL_UPDATE_START
,I/DBG_DM  ( 4595): [3.19.140541][Line:1854][xdmAgentCheckResumeNoti] 
,I/DBG_DM  ( 4595): [3.19.140541][Line:369][handleMessage] event ->214
,I/DBG_DM  ( 4595): [3.19.140541][Line:318][xdmBroadcastGetIsSavedNfcMode] m_IsSavedNfcMode : false
,I/DBG_DM  ( 4595): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
D/Sensors ( 2405): LightSensor enable = 0
,D/Sensors ( 2405): LightSensor enableSensor = 0
,D/LightsService( 2405): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2405): unregisterListener ::   
D/LightsService( 2405): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/DBG_DM  ( 4595): [3.19.140541][Line:546][xuiAdpGetUpdateReport] Get bUpdateReport = false
,I/DBG_DM  ( 4595): [3.19.140541][Line:2008][xdmCallUiFotaInstall] 
,I/SQLiteSecureOpenHelper( 4100): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4100): getDatabaseLocked(b,b,pwd)...
,I/DBG_DM  ( 4595): [3.19.140541][Line:729][xdmUIEvent] XUI_DL_UPDATE_CONFIRM
W/ContextImpl( 4595): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 com.wssyncmldm.XDMService.xdmCallUiFotaInstall:2023 com.wssyncmldm.XDMService$1.handleMessage:372 android.os.Handler.dispatchMessage:102 
,I/jxcore-log( 6747): Attempting to connect to the test coordinator server
I/jxcore-log( 6747): 
,I/DBG_DM  ( 4595): [3.19.140541][Line:1320][xdmCheckIdleScreen] Idle Screen : false
,I/DBG_DM  ( 4595): [3.19.140541][Line:890][xdmUnRegisterBatteryReceiver] 
,E/DBG_DM  ( 4595): Warning!!! [3.19.140541][Line:898][xdmUnRegisterBatteryReceiver] didn't register
,E/DBG_DM  ( 4595): Warning!!! [3.19.140541][Line:899][xdmUnRegisterBatteryReceiver] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.XDMService$3@4236ef98
,I/dalvikvm( 4595): Total arena pages for JIT: 18
,I/DBG_DM  ( 4595): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4595): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/SELinux ( 6953): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6953):  
,I/SELinux ( 6953): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6953):  
I/SELinux ( 6953):  
,I/SELinux ( 6953): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6953): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6953): >>>>> Normal User
,E/dalvikvm( 6953): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 6953): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 11% free 9503K/10624K, paused 3ms+12ms, total 49ms
,I/VacuumService( 2852): Vacuum at: now=1447785896565 tag=VacuumService
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9503K/10624K, paused 2ms+3ms, total 26ms
,D/TimaKeyStoreProvider( 6953): in addTimaSignatureService
W/ContextImpl( 2405): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
D/STATUSBAR-StatusBarManagerService( 2405): sendNotification(1) - 4
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9503K/10624K, paused 3ms+3ms, total 26ms
,D/btif_config_util( 5016): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/ResourceType( 2580): Attempt to retrieve bag 0x01030068 which is invalid or in a cycle.
,W/ResourceType( 2580): Attempt to retrieve bag 0x01030067 which is invalid or in a cycle.
,D/ProgressBar( 2580): setProgressDrawable drawableHeight = 12
,D/ProgressBar( 2580): setProgressDrawable drawableHeight = 12
,D/PhoneStatusBar( 2580): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@422be598
,D/TimaKeyStoreProvider( 6953): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6953): Added TimaKesytore provider
,I/dalvikvm( 3148): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
,W/dalvikvm( 3148): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 3148): VFY: replacing opcode 0x6e at 0x0033
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 6953): GC_CONCURRENT freed 3004K, 30% free 9565K/13652K, paused 1ms+1ms, total 31ms
,D/dalvikvm( 6953): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/AmoledAdjustTimer( 2405): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,E/Auth.Api.Credentials( 3148): [CredentialSyncAdapter] Unknown sync event.
,D/DelayedSyncController( 5966): Delaying sync.
,D/libgps  ( 2405): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 6974): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6974):  
,I/SELinux ( 6974): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6974):  
I/SELinux ( 6974):  
,I/SELinux ( 6974): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6974): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 6974): >>>>> Normal User
,E/dalvikvm( 6974): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 6974): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6974): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6974): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6974): Added TimaKesytore provider
,I/System.out( 6953): Thread-606(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6953): Thread-606(ApacheHTTPLog):isShipBuild true
,I/System.out( 6953): Thread-606(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 2405): GC_EXPLICIT freed 2478K, 55% free 24417K/53956K, paused 9ms+16ms, total 179ms
,D/dalvikvm( 6974): GC_CONCURRENT freed 2997K, 30% free 9569K/13648K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 6974): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/KLMS-2.3.201 : ( 6974): KLMSValidator() : checkQATesting()
W/WifiP2pStateTracker( 2405): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService( 2405): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2405):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
D/ConnectivityService( 2405): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2405): updateSourceRoutes : no source routing conditions
,I/KLMS-2.3.201 : ( 6974): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1447785897378
,I/KLMS-2.3.201 : ( 6974): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/System.out( 6953): AsyncTask #1 calls detatch()
,I/SELinux ( 6989): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6989):  
,I/LocationTagReadyService( 3295): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3295): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3295): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3295): [Slink platform] The state of Slink geocode service is true
,W/System.err( 6953): com.sec.android.fota.osp.http.RestClientException
W/System.err( 6953): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 6953): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 6953): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 6953): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 6953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 6953): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 6953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 6953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 6953): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 6953): Caused by: java.lang.NullPointerException
,W/System.err( 6953): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 6953): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 6953): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 6953): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 6953): 	... 8 more
,I/GallerySearchProvider( 3422): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 6989): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6989):  
I/SELinux ( 6989):  
,I/SELinux ( 6989): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6989): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6989): >>>>> Normal User
,E/dalvikvm( 6989): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 6989): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 6989): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6989): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6989): Added TimaKesytore provider
,I/SELinux ( 7001): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7001):  
,D/dalvikvm( 6989): GC_CONCURRENT freed 2987K, 30% free 9573K/13644K, paused 5ms+2ms, total 27ms
,D/dalvikvm( 6989): WAIT_FOR_CONCURRENT_GC blocked 15ms
I/SELinux ( 7001): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7001):  
I/SELinux ( 7001):  
,I/SELinux ( 7001): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7001): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7001): >>>>> Normal User
,E/dalvikvm( 7001): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7001): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/SO_AGENT( 6989): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 6989): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/TimaKeyStoreProvider( 7001): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7001): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7001): Added TimaKesytore provider
,I/SA      ( 6255): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 6255): [BDLM] already registered in spp
I/SA      ( 6255): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 6255): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/dalvikvm( 7001): GC_CONCURRENT freed 3003K, 30% free 9567K/13648K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 7001): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 6196): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x422b10d8, skipping init
,I/SecureStorage( 6196): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 1959): [INFO]: SPID(0x00000004)Credentials: uid 1000, gid 1000, pid 6196
,I/SecureStorage( 1959): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
,V/KVNProvider( 7001): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7001): getFindoCursor query string : 
,V/KVNProvider( 7001): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 6255): [SLFUCHKMGR] constructor called
,I/SA      ( 6255): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6255): [OR] == isSIMCardReady false ==
,I/SA      ( 6255): [SCU] == networkStateCheck == true
I/SA      ( 6255): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6255): isChinaCountryCode : false
,I/SA      ( 6255): [OR] == networkStateCheck true ==
,I/SA      ( 6255): [OR] GetMyCountryZoneTask
,I/SA      ( 6255): [OR] onReceive END
,I/SA      ( 6255): [SRS] prepareGetMyCountryZone
,I/SA      ( 6255): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6255): [SSP] query invoked
I/ActivityManager( 2405): Killing 5748:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 6005): Other Intent
,I/SA      ( 6255): [TPMU] GetMccFromDB : null
,I/SELinux ( 7021): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7021):  
I/SA      ( 6255): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6255): [TPM] isNoProxy(default) : true
,I/SA      ( 6255): [RC New] Execute method=[GET] start
,I/SELinux ( 7021): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7021):  
I/SELinux ( 7021):  
,I/SELinux ( 7021): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7021): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7021): >>>>> Normal User
,E/dalvikvm( 7021): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7021): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7021): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7021): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7021): Added TimaKesytore provider
,D/libgps  ( 2405): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2405): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2405): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2405): agps_ril_update_network_availability: Waiting for IPC connection...
,I/System.out( 6255): Thread-566(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6255): Thread-566(ApacheHTTPLog):isShipBuild true
,I/System.out( 6255): Thread-566(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 7021): GC_CONCURRENT freed 2995K, 30% free 9578K/13652K, paused 12ms+1ms, total 130ms
,D/dalvikvm( 7021): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/com.samsung.app( 7021): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7021): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7021): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7021): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7021): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7021): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5212): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7021): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5212): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7021): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5212): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7021): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7021): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2405): Killing 5744:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,I/SELinux ( 7034): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7034):  
,I/SELinux ( 7034): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7034):  
I/SELinux ( 7034):  
,I/SELinux ( 7034): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7034): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7034): >>>>> Normal User
,E/dalvikvm( 7034): >>>>> com.samsung.android.internal.headlines [ userId:0 | appId:10110 ]
,E/SELinux ( 7034): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7034): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7034): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7034): Added TimaKesytore provider
,D/dalvikvm( 7034): GC_CONCURRENT freed 2999K, 30% free 9573K/13652K, paused 4ms+2ms, total 21ms
,D/dalvikvm( 7034): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/HeadlinesChannelApplication( 7034): [onCreate]
,D/Headlines( 7034): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 7034): getCountryCode(): countryCode = PL
,D/Headlines( 7034): Breath.onCreate
,D/HeadlinesCardManager( 7034): HeadlinesCardManager : constructor
,E/HeadlinesCardManager( 7034): HeadlinesCardManager : ctor = image_cache size is 42MB
,D/SA Version( 7034): CardProvider Library : 13
,I/SELinux ( 7046): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7046):  
,D/MagazineService::CardProviderContentProvider( 6301): insertProvider: provider already exists.: com.samsung.android.app.headlines
,D/MagazineService::CardProviderContentProvider( 6301): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 7034): registerCardProvider: provider already exists.
,I/SELinux ( 7046): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7046):  
I/SELinux ( 7046):  
,I/SELinux ( 7046): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7046): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7046): >>>>> Normal User
,E/dalvikvm( 7046): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
I/Headlines( 7034): HeadlinesDataCenter ctor
,I/Headlines( 7034): HeadlinesDataCenter. mLocale = en_US
,D/HeadlinesChannelUtil( 7034): getCountryCode(): countryCode = PL
,E/SELinux ( 7046): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/HeadlinesCardManager( 7034): HeadlinesCardManager : constructor welcome :YES
,D/TimaKeyStoreProvider( 7046): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7046): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7046): Added TimaKesytore provider
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/Headlines( 7034): Breath timer started. interval : 30000
,D/Headlines( 7034): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 7034): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 7034): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 7034): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 7034): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 7034): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 7034): requestUpdateNewsWelcomeCard !!! no welcome card
,D/dalvikvm( 7046): GC_CONCURRENT freed 2986K, 30% free 9582K/13648K, paused 3ms+1ms, total 37ms
,D/dalvikvm( 7046): WAIT_FOR_CONCURRENT_GC blocked 26ms
,E/WifiStateMachine( 2405): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SecureStorage( 1959): [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 1959): [INFO]: SPID(0x00000004)PID: 6196, TID: 6221
,V/WebViewChromium( 7046): Binding Chromium to the background looper Looper (main, tid 1) {422602e8}
,I/chromium( 7046): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7046): Initializing chromium process, renderers=0
,D/TimaService( 2405): TIMA: TimaService scheduler is intialized. 
D/TimaService( 2405): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2405): TimaServiceHandler.handleMessage what =1
I/TLC_TIMA_PKM_initialize( 2405): initializing...
I/TLC_TIMA_PKM_initialize( 2405): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 2405): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2405): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2405): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2405): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2405): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2405): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2405): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2405): device_id = 0x0
I/TZ: mc_tlc_communication( 2405): tlc_open() was called
I/TZ: mc_tlc_communication( 2405): Opening MobiCore device
I/TZ: mc_tlc_communication( 2405): Allocating WSM for TCI
I/TZ: mc_tlc_communication( 2405): Opening the session
,I/TZ: mc_tlc_communication( 2405): tlc_open() succeeded
,D/libEGL  ( 7046): loaded /system/lib/egl/libEGL_mali.so
,I/TLC_TIMA_PKM_initialize( 2405): Trustlet response is completed
,D/libEGL  ( 7046): loaded /system/lib/egl/libGLESv1_CM_mali.so
,W/chromium( 7046): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7046): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7046): Mali API Version : 401
,I/Mali    ( 7046): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,W/GAV2    ( 7046): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/SecureStorage( 6196): [INFO]: SPID(0x00000000)Processing data has been completed
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7046): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,I/ActivityManager( 2405): Killing 5266:com.google.android.talk/u0a109 (adj 15): empty #43
I/SurfaceFlinger( 1920): id=24 Removed Uoast (10/11)
,I/SurfaceFlinger( 1920): id=24 Removed Uoast (-2/11)
D/PowerManagerService( 2405): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2405) eventTime = 312093
D/PowerManagerService( 2405): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2405 (0x0)
D/PowerManagerService( 2405): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2405, ws=WorkSource{1000}) (elapsedTime=3435)
,I/SurfaceFlinger( 1920): id=25 createSurf (1x1),1 flag=4, Uoast
D/libgps  ( 2405): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2405): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2405): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/PowerManagerService( 2405): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2405
,I/NSApplication( 7046): Starting up...
,I/ActivityManager( 2405): Killing 5768:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/ImageResourceManager( 5634): ImageResourceManager: uninitalized
,D/dalvikvm( 5634): GC_FOR_ALLOC freed 195K, 28% free 9849K/13644K, paused 37ms, total 40ms
,I/dalvikvm-heap( 5634): Grow heap (frag case) to 12.705MB for 2129936-byte allocation
,I/SA      ( 6255): [RC New] [v2liruge] api execute + 1419
,I/SA      ( 6255): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,D/dalvikvm( 5634): GC_FOR_ALLOC freed 7K, 25% free 11922K/15728K, paused 19ms, total 19ms
,I/iu.Environment( 5634): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/ActivityManager( 2405): Killing 6032:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/QuickConnect[1.1][2] ( 4990): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 4990): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 4990): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42268728
,I/SELinux ( 7088): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7088):  
,D/dalvikvm( 5634): GC_CONCURRENT freed 13K, 25% free 11921K/15728K, paused 1ms+1ms, total 43ms
,D/dalvikvm( 5634): WAIT_FOR_CONCURRENT_GC blocked 34ms
,W/ActivityThread( 6196): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/dalvikvm-heap( 5634): Grow heap (frag case) to 14.728MB for 2129936-byte allocation
I/System.out( 6255): AsyncTask #1 calls detatch()
,I/SA      ( 6255): [TPMU] getNetworkMcc : 
,D/dalvikvm( 5634): GC_FOR_ALLOC freed <1K, 22% free 14001K/17812K, paused 16ms, total 17ms
,I/iu.UploadsManager( 5634): num queued entries: 0
,I/iu.UploadsManager( 5634): num updated entries: 0
,I/iu.SyncManager( 5634): NEXT; no task
I/SA      ( 6255): [SCU] saveMccToPreferece Start
,I/SA      ( 6255): [SCU] RegionMCC : 260
,I/SA      ( 6255): [SSP] query invoked
,I/SELinux ( 7088): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7088):  
I/SELinux ( 7088):  
,I/SELinux ( 7088): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7088): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7088): >>>>> Normal User
,E/dalvikvm( 7088): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7088): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 6255): [TPMU] GetMccFromDB : null
,I/SA      ( 6255): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6255): [SCU] saveMccToPreferece End
I/SA      ( 6255): [RC New] executeRequest [v2liruge] end. 1532
,I/SA      ( 6255): [RC New] Execute end
I/SA      ( 6255): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6255): [OR] GetMyCountryZoneTask Success
,D/TimaKeyStoreProvider( 7088): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7088): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7088): Added TimaKesytore provider
I/ActivityManager( 2405): Killing 5885:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,D/NtpTrustedTime( 2405): getCachedNtpTime() cache hit
,D/dalvikvm( 7088): GC_CONCURRENT freed 2982K, 30% free 9588K/13652K, paused 7ms+1ms, total 27ms
,D/dalvikvm( 7088): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/dalvikvm( 6196): Total arena pages for JIT: 11
,I/dalvikvm( 6196): Total arena pages for JIT: 12
I/dalvikvm( 6196): Total arena pages for JIT: 13
,I/dalvikvm( 6196): Total arena pages for JIT: 14
I/dalvikvm( 6196): Total arena pages for JIT: 15
I/dalvikvm( 6196): Total arena pages for JIT: 16
,I/dalvikvm( 6196): Total arena pages for JIT: 17
,I/System.out( 6196): Thread-560(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/RCPManagerService( 2405): exchangeData() failure , invalid userId
,I/System.out( 6196): Thread-560(ApacheHTTPLog):isShipBuild true
,I/System.out( 6196): Thread-560(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/RCPManagerService( 2405): exchangeData() failure , invalid userId
,D/RCPManagerService( 2405): exchangeData() failure , invalid userId
,I/dalvikvm( 6196): Total arena pages for JIT: 18
,D/PicasaService( 3422): start picasa sync
,D/PicasaService( 3422): end picasa sync
,D/RCPManagerService( 2405): exchangeData() failure , invalid userId
,D/RCPManagerService( 2405): exchangeData() failure , invalid userId
,D/RCPManagerService( 2405): exchangeData() failure , invalid userId
,I/SELinux ( 7112): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7112):  
,I/System.out( 6196): Thread-560 calls detatch()
,W/ActivityManager( 2405): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/SELinux ( 7112): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7112):  
I/SELinux ( 7112):  
I/SELinux ( 7112): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7112): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7112): >>>>> Normal User
E/dalvikvm( 7112): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
E/SELinux ( 7112): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 7124): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7124):  
,D/TimaKeyStoreProvider( 7112): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7112): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7112): Added TimaKesytore provider
I/ActivityManager( 2405): Killing 6064:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/SELinux ( 7124): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7124):  
I/SELinux ( 7124):  
,I/SELinux ( 7124): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7124): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7124): >>>>> Normal User
,E/dalvikvm( 7124): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7124): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,I/ActivityManager( 2405): Killing 6078:com.android.musicfx/u0a24 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7124): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7124): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7124): Added TimaKesytore provider
,V/AlarmManager( 2405): waitForAlarm result :8
,V/AlarmManager( 2405): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/dalvikvm( 7112): GC_CONCURRENT freed 2993K, 30% free 9576K/13652K, paused 4ms+2ms, total 26ms
,D/dalvikvm( 7112): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/BadgeProvider( 7112): onCreate
,D/BadgeProvider( 7112): DatabaseHelper
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BadgeProvider( 7112): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7112): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7112): sendNotify, [notify] : null
D/BadgeProvider( 7112): update, [uri] : content://com.sec.badge/apps/1
D/dalvikvm( 7124): GC_CONCURRENT freed 2997K, 30% free 9566K/13644K, paused 12ms+5ms, total 62ms
D/BadgeProvider( 7112): update, [BadgeCount] : badgecount=0
,D/dalvikvm( 7124): WAIT_FOR_CONCURRENT_GC blocked 50ms
,D/BadgeProvider( 7112): update, [UpdateCount] : 1
,D/Launcher.Model( 2769): reloadBadges entered.
,D/DelayedSyncController( 5966): Delaying sync.
,I/SELinux ( 7139): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7139):  
,I/ActivityManager( 2405): Killing 6106:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,I/SELinux ( 7139): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7139):  
I/SELinux ( 7139):  
I/SELinux ( 7139): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7139): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7139): >>>>> Normal User
E/dalvikvm( 7139): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
E/SELinux ( 7139): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
I/dalvikvm( 2735): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 2735): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
D/dalvikvm( 2735): VFY: replacing opcode 0x6e at 0x0033
D/TimaKeyStoreProvider( 7139): in addTimaSignatureService
D/TimaKeyStoreProvider( 7139): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7139): Added TimaKesytore provider
D/dalvikvm( 2852): GC_EXPLICIT freed 799K, 22% free 11024K/13988K, paused 5ms+7ms, total 54ms
D/dalvikvm( 7139): GC_CONCURRENT freed 2994K, 30% free 9576K/13648K, paused 4ms+2ms, total 25ms
D/dalvikvm( 7139): WAIT_FOR_CONCURRENT_GC blocked 13ms
I/dalvikvm( 7139): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 7139): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
D/dalvikvm( 7139): VFY: replacing opcode 0x6e at 0x0008
E/dalvikvm( 7139): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7139): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
D/dalvikvm( 7139): VFY: replacing opcode 0x22 at 0x0000
E/dalvikvm( 7139): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
W/dalvikvm( 7139): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
D/dalvikvm( 7139): VFY: replacing opcode 0x22 at 0x0037
W/dalvikvm( 7139): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7139): Link of class 'Ldqp;' failed
W/dalvikvm( 7139): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7139): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7139): Link of class 'Ldqp;' failed
I/dalvikvm( 7139): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 7139): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
D/dalvikvm( 7139): VFY: replacing opcode 0x6e at 0x0000
E/dalvikvm( 7139): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7139): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
D/dalvikvm( 7139): VFY: replacing opcode 0x22 at 0x0000
W/dalvikvm( 7139): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7139): Link of class 'Ldqp;' failed
W/dalvikvm( 7139): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7139): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7139): Link of class 'Ldqp;' failed
I/dalvikvm( 7139): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 7139): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
D/dalvikvm( 7139): VFY: replacing opcode 0x6e at 0x0008
E/dalvikvm( 7139): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 7139): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
D/dalvikvm( 7139): VFY: replacing opcode 0x1c at 0x0026
W/dalvikvm( 7139): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7139): Link of class 'Ldqp;' failed
W/dalvikvm( 7139): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7139): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 7139): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7139): Link of class 'Ldqp;' failed
I/dalvikvm( 7139): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 7139): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
D/dalvikvm( 7139): VFY: replacing opcode 0x6e at 0x0003
W/dalvikvm( 7139): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7139): Link of class 'Lax;' failed
E/dalvikvm( 7139): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 7139): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
D/dalvikvm( 7139): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 7139): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7139): Link of class 'Laz;' failed
E/dalvikvm( 7139): Could not find class 'az', referenced from method g.a
W/dalvikvm( 7139): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
D/dalvikvm( 7139): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 7139): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 7139): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
D/dalvikvm( 7139): VFY: replacing opcode 0x6e at 0x0008
I/dalvikvm( 7139): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
W/dalvikvm( 7139): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 7139): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 7139): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 7139): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 7139): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 7139): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 7139): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
D/dalvikvm( 7139): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 7139): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 7139): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 7139): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7139): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
W/dalvikvm( 7139): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 7139): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7139): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 7139): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
D/dalvikvm( 7139): VFY: replacing opcode 0x72 at 0x0000
W/dalvikvm( 7139): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 7139): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 7139): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
D/dalvikvm( 7139): VFY: replacing opcode 0x23 at 0x0005
I/dalvikvm( 7139): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
W/dalvikvm( 7139): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
D/dalvikvm( 7139): VFY: replacing opcode 0x6e at 0x0009
W/dalvikvm( 7139): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
W/dalvikvm( 7139): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 7139): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 7139): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
D/dalvikvm( 7139): VFY: replacing opcode 0x1c at 0x0002
E/dalvikvm( 7139): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 7139): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
D/dalvikvm( 7139): VFY: replacing opcode 0x1f at 0x000c
D/dalvikvm( 7139): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7139): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7139): VFY: replacing opcode 0x62 at 0x0006
D/dalvikvm( 7139): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
D/dalvikvm( 7139): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
D/dalvikvm( 7139): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
D/dalvikvm( 7139): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
D/dalvikvm( 7139): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
W/dalvikvm( 7139): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7139): Link of class 'Lax;' failed
D/dalvikvm( 7139): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 7139): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7139): Link of class 'Laz;' failed
D/dalvikvm( 7139): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
D/dalvikvm( 7139): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
D/dalvikvm( 7139): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
D/dalvikvm( 7139): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x42267878
D/dalvikvm( 7139): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x42267878
I/dalvikvm( 7139): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
W/dalvikvm( 7139): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
D/dalvikvm( 7139): VFY: replacing opcode 0x6e at 0x0076
I/Babel_SMS( 7139): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7139): MmsConfig.loadMmsSettings
I/Babel_SMS( 7139): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
I/Babel_SMS( 7139): MmsConfig.loadFromDatabase
E/Babel_SMS( 7139): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7139): MmsConfig.loadFromResources
E/Babel_SMS( 7139): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7139): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
W/dalvikvm( 7139): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7139): Link of class 'Lfzc;' failed
E/dalvikvm( 7139): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 7139): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
D/dalvikvm( 7139): VFY: replacing opcode 0x22 at 0x0033
W/dalvikvm( 7139): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
W/dalvikvm( 7139): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
W/dalvikvm( 7139): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
W/dalvikvm( 7139): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
I/dalvikvm( 7139): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 7139): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
D/dalvikvm( 7139): VFY: replacing opcode 0x74 at 0x006d
I/dalvikvm( 7139): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 7139): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
D/dalvikvm( 7139): VFY: replacing opcode 0x6e at 0x0033
I/dalvikvm( 7139): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 7139): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
D/dalvikvm( 7139): VFY: replacing opcode 0x6e at 0x0030
W/dalvikvm( 7139): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7139): Link of class 'Lfzc;' failed
D/dalvikvm( 7139): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
E/SensorService( 2405): Permission Denial : SEC Private Sensor 
E/SensorService( 2405): Permission Denial : SEC Private Sensor 
D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
D/dalvikvm( 7139): GC_CONCURRENT freed 1785K, 21% free 10866K/13728K, paused 2ms+10ms, total 40ms
D/dalvikvm( 7139): WAIT_FOR_CONCURRENT_GC blocked 21ms
D/dalvikvm( 7139): WAIT_FOR_CONCURRENT_GC blocked 21ms
W/Settings( 7139): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7139): startup - clean
I/Babel   ( 7139): deleted: false for 0
I/dalvikvm( 7139): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
W/dalvikvm( 7139): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 7139): VFY: replacing opcode 0x6e at 0x000d
W/dalvikvm( 7139): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
I/dalvikvm( 7139): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 7139): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
D/dalvikvm( 7139): VFY: replacing opcode 0x6e at 0x004e
W/dalvikvm( 7139): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7139): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7139): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 7139): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
D/dalvikvm( 7139): VFY: replacing opcode 0x22 at 0x0071
W/dalvikvm( 7139): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7139): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7139): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7139): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7139): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 7139): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
D/dalvikvm( 7139): VFY: replacing opcode 0x1f at 0x0021
W/dalvikvm( 7139): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
D/dalvikvm( 7139): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
I/dalvikvm( 7139): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/dalvikvm( 7139): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
D/dalvikvm( 7139): VFY: replacing opcode 0x6e at 0x0074
I/vclib   ( 7139): onServiceConnected
W/Babel   ( 7139): Attempted to change video mute state without an active call.
I/iu.Environment( 3148): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 3148): num queued entries: 0
I/iu.UploadsManager( 3148): num updated entries: 0
I/iu.SyncManager( 3148): NEXT; no task
I/PCWCLIENTTRACE_SYSTEMReceiver( 6091): mConnectivityHandler : connected
W/PCWCLIENTTRACE_AccountUtil( 6091): [hasSamungAccount] - No Samsung Account
,V/AlarmManager( 2405): waitForAlarm result :4
,D/dalvikvm( 3148): GC_EXPLICIT freed 1515K, 20% free 11691K/14604K, paused 8ms+8ms, total 111ms
V/AlarmManager( 2405): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/WaitQueueForNetworkActivate( 6406): notifyNetworkActivated
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6091): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6091): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6091): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6091): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6091): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6091): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6091): [ensureRegistration] - No Samsung account
,D/dalvikvm( 7139): GC_FOR_ALLOC freed 2289K, 22% free 12542K/15920K, paused 38ms, total 41ms
,D/dalvikvm( 7139): GC_FOR_ALLOC freed 138K, 21% free 12666K/15920K, paused 35ms, total 36ms
,I/dalvikvm-heap( 7139): Grow heap (frag case) to 13.916MB for 521644-byte allocation
,W/ContextImpl( 6406): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager( 2405): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/dalvikvm( 7139): GC_FOR_ALLOC freed 273K, 22% free 12901K/16432K, paused 40ms, total 40ms
,I/System.out( 7139): Thread-647(HTTPLog):isShipBuild true
,I/System.out( 7139): Thread-647(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 2405): WAIT_FOR_CONCURRENT_GC blocked 1ms
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/Babel   ( 7139): connection state changed from UNKNOWN to CONNECTED
,D/dalvikvm( 2405): GC_EXPLICIT freed 1958K, 55% free 24433K/53956K, paused 16ms+27ms, total 273ms
,I/GCM     ( 2852): GCM config loaded
,D/dalvikvm( 7139): GC_CONCURRENT freed 2129K, 19% free 14182K/17388K, paused 5ms+5ms, total 85ms
,D/dalvikvm( 7139): WAIT_FOR_CONCURRENT_GC blocked 50ms
,D/hcjo    ( 6406): AutoUpdateManager:IDLE:execute
,E/SPPClientService( 6418): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6418): [SystemStateMoniter] Current Time : 314986
,E/SPPClientService( 6418): [SystemStateMoniter] No Connect : false
,I/dalvikvm( 6406): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
,I/SELinux ( 7183): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7183):  
W/dalvikvm( 6406): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 6406): VFY: replacing opcode 0x6e at 0x0024
,I/SELinux ( 7183): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7183):  
I/SELinux ( 7183):  
,I/SELinux ( 7183): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7183): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7183): >>>>> Normal User
E/dalvikvm( 7183): >>>>> com.android.calendar [ userId:0 | appId:10144 ]
E/SELinux ( 7183): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 11% free 9503K/10624K, paused 2ms+3ms, total 34ms
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9503K/10624K, paused 2ms+3ms, total 34ms
,D/TimaKeyStoreProvider( 7183): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7183): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7183): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9503K/10624K, paused 3ms+3ms, total 35ms
D/InitializeManagerStateMachine( 6406): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6406): exit::IDLE
,D/InitializeManagerStateMachine( 6406): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6406): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6406): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6406): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6406): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6406): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6406): entry::SUCCESS
,D/hcjo    ( 6406): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6406): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 6406): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6406): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6406): exit::SUCCESS
,D/InitializeManagerStateMachine( 6406): entry::IDLE
,I/ActivityManager( 2405): Killing 6120:com.sec.android.app.shealth/u0a36 (adj 15): empty #43
,D/UdcCache:FPQuery( 3148): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 2852): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2852): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 7183): GC_CONCURRENT freed 2997K, 30% free 9572K/13652K, paused 3ms+2ms, total 31ms
,D/dalvikvm( 7183): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/ActivityManager( 2405): Killing 6138:com.sec.android.service.health/u0a16 (adj 15): empty #43
,D/BootCompletedReceiver( 2405): onReceive
,I/KLMS-2.3.201 : ( 6974): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/System.out( 3148): Thread-142(HTTPLog):isShipBuild true
,I/System.out( 3148): Thread-142(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/KLMS-2.3.201 : ( 6974): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1447785902518
,I/KLMS-2.3.201 : ( 6974): StateImplV2() : dateTimeChanged() : Tue Nov 17 19:45:02 CET 2015
,I/SurfaceFlinger( 1920): id=25 Removed Uoast (10/11)
,I/SurfaceFlinger( 1920): id=25 Removed Uoast (-2/11)
D/ConnectivityService( 2405): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/SELinux ( 7201): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7201):  
D/PowerManagerService( 2405): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2405) eventTime = 315596
D/PowerManagerService( 2405): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2405 (0x0)
D/PowerManagerService( 2405): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2405, ws=WorkSource{1000}) (elapsedTime=3447)
,D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
,D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/SELinux ( 7201): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7201):  
I/SELinux ( 7201):  
,I/SELinux ( 7201): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7201): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7201): >>>>> Normal User
,E/dalvikvm( 7201): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
,E/SELinux ( 7201): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7201): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7201): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7201): Added TimaKesytore provider
,D/GetConfigurationSnapshotOperation( 2852): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/dalvikvm( 7201): GC_CONCURRENT freed 2990K, 30% free 9578K/13652K, paused 3ms+4ms, total 35ms
,D/dalvikvm( 7201): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 7201): WAIT_FOR_CONCURRENT_GC blocked 1ms
,I/PhenotypeFlagCommitter( 2852): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 2852): Using platform SSLCertificateSocketFactory
,W/ContextImpl( 7201): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
,I/SELinux ( 7222): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7222):  
,D/GetCommittedConfigurationOperation( 2852): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/dalvikvm( 2852): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 2852): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2852): VFY: replacing opcode 0x6e at 0x0033
,E/Device Type Shared Preferences( 7201): Device Type Shared Preferences - getDeviceTypeChecked -true
,E/Device Type Shared Preferences( 7201): Device Type Shared Preferences - not connecting to service
,E/com.sec.android.app.shealth.SHealthApplication( 7201): ContentProvider is not null
,I/SELinux ( 7222): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7222):  
I/SELinux ( 7222):  
,I/SELinux ( 7222): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7222): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7222): >>>>> Normal User
,E/dalvikvm( 7222): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,E/SELinux ( 7222): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/ResourceType( 7201): No package identifier when getting value for resource number 0x00000000
,I/System.out( 7201): resource Id::2131361807
,D/TimaKeyStoreProvider( 7222): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7222): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7222): Added TimaKesytore provider
,D/dalvikvm( 7222): GC_CONCURRENT freed 2994K, 30% free 9568K/13644K, paused 4ms+3ms, total 32ms
,D/dalvikvm( 7222): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/System.out( 2852): Thread-132(HTTPLog):isShipBuild true
,I/System.out( 2852): Thread-132(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/com.sec.android.app.shealth.SHealthApplication( 7201): Success during batch insertion in App registry:0
,D/dalvikvm( 2852): GC_CONCURRENT freed 1656K, 20% free 11367K/14172K, paused 4ms+5ms, total 45ms
,V/MediaPlayer( 7201): decode(56, 30565892, 48105)
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
V/AudioCache( 1924): notify(0x43f40008, 8, 0, 0)
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
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x43f40008, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f40008, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f40008, 1, 0, 0)
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
V/AudioCache( 1924): notify(0x43f40008, 6, 0, 0)
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
V/AudioCache( 1924): notify(0x43f40008, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f40008, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x43f40008, 8, 0, 0)
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
V/MediaPlayer( 7201): decode(58, 30501792, 10421)
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
V/AudioCache( 1924): notify(0x442bd2a0, 8, 0, 0)
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
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442bd2a0, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442bd2a0, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442bd2a0, 1, 0, 0)
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
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442bd2a0, 6, 0, 0)
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
V/AudioCache( 1924): notify(0x442bd2a0, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442bd2a0, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442bd2a0, 8, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
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
,V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
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
V/MediaPlayer( 7201): decode(59, 34044116, 34198)
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
V/AudioCache( 1924): notify(0x442b7228, 8, 0, 0)
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
,I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder',
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 1, 0, 0)
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
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 6, 0, 0)
,V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 8, 0, 0)
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
V/AwesomePlayer( 1924): mSecMediaClock clear
,V/MediaPlayer( 7201): decode(60, 30449260, 7405)
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
V/AudioCache( 1924): notify(0x442b00f8, 8, 0, 0)
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
,V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
,I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b00f8, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b00f8, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b00f8, 1, 0, 0)
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
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b00f8, 6, 0, 0)
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
V/AudioCache( 1924): notify(0x442b00f8, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b00f8, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b00f8, 8, 0, 0)
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
,V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 7201): decode(61, 34134748, 5555)
,V/MediaPlayerService( 1924): decode(25, 34134748, 5555)
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
V/StagefrightPlayer( 1924): setDataSource(25, 34134748, 5555)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b0d70, 8, 0, 0)
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
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b0d70, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b0d70, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b0d70, 1, 0, 0)
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
V/AudioCache( 1924): notify(0x442b0d70, 6, 0, 0)
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
V/AudioCache( 1924): notify(0x442b0d70, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b0d70, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b0d70, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x48, OMX_CommandStateSet, OMX_StateIdle)
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
,V/MediaPlayer( 7201): decode(62, 26954540, 5085)
V/MediaPlayerService( 1924): decode(26, 26954540, 5085)
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
V/StagefrightPlayer( 1924): setDataSource(26, 26954540, 5085)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b1340, 8, 0, 0)
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
V/AudioCache( 1924): notify(0x442b1340, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b1340, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b1340, 1, 0, 0)
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
,I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
,V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b1340, 6, 0, 0)
I/AudioPlayer( 1924): First fillBuffer call!!
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b1340, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b1340, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b1340, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x49, OMX_CommandStateSet, OMX_StateIdle)
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
,V/MediaPlayer( 7201): decode(63, 26959684, 21552),
,V/MediaPlayerService( 1924): decode(26, 26959684, 21552)
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
,V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
,V/StagefrightPlayer( 1924): setDataSource(26, 26959684, 21552)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b2038, 8, 0, 0)
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
,V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
,V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
,V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
,I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache( 1924): notify(0x442b2038, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b2038, 5, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b2038, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
,V/StagefrightPlayer( 1924): start
,V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache( 1924): notify(0x442b2038, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,D/GetCommittedConfigurationOperation( 2852): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b2038, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache( 1924): notify(0x442b2038, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
,V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
,V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b2038, 8, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x4a, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
,V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
,V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 7201): decode(64, 34130460, 4230)
,V/MediaPlayerService( 1924): decode(27, 34130460, 4230)
,V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): constructor
,V/AwesomePlayer( 1924): setDefault
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
V/StagefrightPlayer( 1924): setDataSource(27, 34130460, 4230)
,V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442bca60, 8, 0, 0)
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
V/AudioCache( 1924): notify(0x442bca60, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442bca60, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442bca60, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
,V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache( 1924): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442bca60, 6, 0, 0)
I/AudioPlayer( 1924): First fillBuffer call!!
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
,V/AwesomePlayer( 1924): onCheckAudioStatus
V/MediaPlayerService( 1924): wait for playback complete
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442bca60, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442bca60, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
,V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442bca60, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x4b, OMX_CommandStateSet, OMX_StateIdle)
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
,V/MediaPlayer( 7201): decode(65, 26923896, 9400)
,V/MediaPlayerService( 1924): decode(27, 26923896, 9400)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
,V/AwesomePlayer( 1924): constructor
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
V/StagefrightPlayer( 1924): setDataSource(27, 26923896, 9400)
,V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 8, 0, 0)
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
V/AudioCache( 1924): notify(0x442b7228, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 1, 0, 0)
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
V/AudioCache( 1924): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 6, 0, 0)
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
V/AudioCache( 1924): notify(0x442b7228, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x4c, OMX_CommandStateSet, OMX_StateIdle)
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
D/dalvikvm( 7222): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x4224d8c8, skipping init
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecureStorage( 7222): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
V/AwesomePlayer( 1924): mSecMediaClock clear
I/SecureStorage( 7222): [INFO]: SPID(0x00000000)This device supports Secure Storage
V/MediaPlayer( 7201): decode(66, 30512272, 44276)
V/MediaPlayerService( 1924): decode(26, 30512272, 44276)
I/SecureStorage( 1959): [INFO]: SPID(0x00000005)Credentials: uid 10016, gid 10016, pid 7222
,I/SecureStorage( 1959): [INFO]: SPID(0x00000005)Received function mask & code: 0000010C
,I/SecureStorage( 7222): [INFO]: SPID(0x00000000)SS Daemon is running
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
V/StagefrightPlayer( 1924): setDataSource(26, 30512272, 44276)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 8, 0, 0)
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
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/GAV2    ( 7046): Thread[GAThread,5,main]: No campaign data found.
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 1, 0, 0)
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
V/AudioCache( 1924): notify(0x442b7228, 6, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): addBatteryData
V/MediaPlayerService( 1924): wait for playback complete
,I/SecureStorage( 7222): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 1959): [INFO]: SPID(0x00000005)Credentials: uid 10016, gid 10016, pid 7222
,I/SecureStorage( 1959): [INFO]: SPID(0x00000005)Received function mask & code: 00000106
,W/Uploader( 2852):  no longer exists, so no auth token.
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
D/GetCommittedConfigurationOperation( 2852): no corresponding serverToken: com.google.android.gms.playlog.uploader
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 8, 0, 0)
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
,V/MediaPlayer( 7201): decode(67, 30472480, 29256)
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
V/AudioCache( 1924): notify(0x442b7228, 8, 0, 0)
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
V/AudioCache( 1924): notify(0x442b7228, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 1, 0, 0)
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
V/AudioCache( 1924): notify(0x442b7228, 6, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,D/BatteryService( 2405): level:100, scale:100, status:5, health:2, present:true, voltage: 4348, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2405): stay LED for fully charged
,D/BatteryService( 2405): Sending ACTION_BATTERY_CHANGED.
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2405): mCoverManager.getCoverState() : true
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x4e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
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
V/MediaPlayer( 7201): decode(68, 34078380, 52024)
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
V/AudioCache( 1924): notify(0x442b7228, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5016): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5016): Disconnected process message: 10
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
V/AudioCache( 1924): notify(0x442b7228, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1924): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
V/MediaPlayerService( 1924): wait for playback complete
,D/SSRMv2:SIOP( 2405): SIOP:: AP = 360, Delta = 20
,I/PowerManagerService( 2405): [PWL] Off : 50s ago
I/PowerManagerService( 2405): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2405): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2405): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2405, ws=null) (elapsedTime=5544)
I/PowerManagerService( 2405): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=2405, ws=WorkSource{10045}) (elapsedTime=3173)
,I/PowerManagerService( 2405): [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10012, pid=2852, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=2195)
,D/GetCommittedConfigurationOperation( 2852): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,V/AudioCache( 1924): notify(0x442b7228, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AudioCache( 1924): wait - success
,V/AwesomePlayer( 1924): addBatteryData
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 8, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x4f, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
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
,V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 7201): decode(69, 30556608, 9226)
V/MediaPlayerService( 1924): decode(27, 30556608, 9226)
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
V/StagefrightPlayer( 1924): setDataSource(27, 30556608, 9226)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 8, 0, 0)
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
,V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache( 1924): notify(0x442b7228, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
,V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
,V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
,I/AudioPlayer( 1924): First fillBuffer call!!
,V/MediaPlayerService( 1924): wait for playback complete
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b7228, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x50, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
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
,V/AwesomePlayer( 1924): mSecMediaClock clear
,V/MediaPlayer( 7201): decode(70, 26989388, 4509)
,V/MediaPlayerService( 1924): decode(27, 26989388, 4509)
,V/MediaPlayerService( 1924): player type = 3
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
,V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(27, 26989388, 4509)
,V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b00f8, 8, 0, 0)
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
,I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
,V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b00f8, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache( 1924): notify(0x442b00f8, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b00f8, 1, 0, 0)
,V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
,V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b00f8, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
,V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b00f8, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
,V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b00f8, 7, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache( 1924): notify(0x442b00f8, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x51, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
,V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
,D/GetCommittedConfigurationOperation( 2852): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 2852): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 2852): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 2852): no corresponding serverToken: com.google.android.gms.playlog.uploader
,E/SPPClientService( 6418): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,V/AlarmManager( 2405):  next == MAX_VALUE
,E/SPPClientService( 6418): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 6418): [a] [ConnectionManager] Connection is already disconnected.
V/AlarmManager( 2405): waitForAlarm result :4
V/AlarmManager( 2405): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SecureStorage( 1959): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 1959): [INFO]: SPID(0x00000005)PID: 7222, TID: 7234
,E/Watchdog( 2405): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel( 2405): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2405): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2405): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2405): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/SecureStorage( 7222): [INFO]: SPID(0x00000000)Processing data has been completed
I/SecureStorage( 7222): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 7222): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 7222): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 7222): Open platform.db in secure mode
,I/SQLiteSecureOpenHelper( 7222): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 7222): ...getDatabaseLocked(b,b,pwd)
,D/SO_AGENT( 6989): [ServerTimeReceiver.java(Line:44/Method:onReceive)] Receive broadcast meassage:android.intent.action.TIME_SET
,I/SO_AGENT( 6989): [ServerTimeReceiver.java(Line:47/Method:onReceive)] No action is available before server time settings
,I/SA      ( 6255): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/Mms/MessagingNotification( 5500): [start]    nonBlockingUpdateMessageIndicator()
,D/Mms/MessagingNotification( 5500): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 5500): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 5500): isDefault true
,D/TP/MmsSmsProvider( 2753): match 8:Elapsed time : 4.976 ms
,D/TP/MmsSmsProvider( 2753): match 200:Elapsed time : 2.590 ms
,I/SELinux ( 7320): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7320):  
I/ActivityManager( 2405): Killing 6226:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty #43
,I/SELinux ( 7320): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7320):  
I/SELinux ( 7320):  
,I/SELinux ( 7320): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7320): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7320): >>>>> Normal User
,E/dalvikvm( 7320): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10064 ]
,E/SELinux ( 7320): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/BadgeProvider( 7112): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 7320): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7320): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7320): Added TimaKesytore provider
D/BadgeProvider( 7112): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 7112): sendNotify, [notify] : null
D/BadgeProvider( 7112): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 7112): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7112): update, [UpdateCount] : 1
,D/Launcher.Model( 2769): reloadBadges entered.
D/Mms/MessagingNotification( 5500): setBadgeCount(), count=0
,D/MessagingNotification( 5500): remove alarm
,D/Mms/MessagingNotification( 5500): [end]    nonBlockingUpdateMessageIndicator()
,D/Mms/MessagingNotification( 5500): updateAllHistoryAsRead()
,D/dalvikvm( 7320): GC_CONCURRENT freed 3008K, 30% free 9560K/13648K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7320): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/com.samsung.app( 7021): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidintentactionTIME_SET
,D/com.samsung.app( 7021): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/ Time Manager ( 7320): Time Difference not stored. TIME_DIFFERENCE
,I/SELinux ( 7335): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7335):  
I/ActivityManager( 2405): Killing 4737:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
,I/SELinux ( 7335): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7335):  
I/SELinux ( 7335):  
,I/SELinux ( 7335): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7335): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7335): >>>>> Normal User
,E/dalvikvm( 7335): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10088 ]
,E/SELinux ( 7335): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7335): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7335): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7335): Added TimaKesytore provider
,D/dalvikvm( 7335): GC_CONCURRENT freed 3002K, 30% free 9568K/13652K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7335): WAIT_FOR_CONCURRENT_GC blocked 15ms
I/ActivityManager( 2405): Waited long enough for: ServiceRecord{44b60900 u0 pl.k2.droidoaudioteka/.services.DownloadService}
,I/ActivityManager( 2405): Waited long enough for: ServiceRecord{44b624e0 u0 pl.k2.droidoaudioteka/.services.PlayerService}
,D/CaptivePortalTracker( 2405): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker( 2405): Checking http://216.58.209.78/generate_204
D/ConnectivityService( 2405): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/ActivityThread( 2405): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/SELinux ( 7348): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7348):  
I/ActivityManager( 2405): Killing 6274:com.sec.android.service.cm/u0a82 (adj 15): empty #43
,I/System.out( 2405): Thread-161(HTTPLog):isShipBuild true
,I/System.out( 2405): Thread-161(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/SELinux ( 7348): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7348):  
I/SELinux ( 7348):  
,I/SELinux ( 7348): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7348): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7348): >>>>> Normal User
,E/dalvikvm( 7348): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 7348): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7348): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7348): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7348): Added TimaKesytore provider
,D/CaptivePortalTracker( 2405): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker( 2405): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 2405): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2405): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2405): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/dalvikvm( 7348): GC_CONCURRENT freed 2998K, 30% free 9572K/13648K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7348): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/elm:14132( 7348): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14132( 7348): ELMEngine.ELMEngine( context ).
,D/elm:14132( 7348): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 7348): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/elm:14132( 7348): ElmAgentService : onCreate()
,D/elm:14132( 7348): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,I/knox    ( 4928): MainReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,D/elm:14132( 7348): ELMAgentService.listeningToTimeDateChanges( context, intent ).
D/elm:14132( 7348): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,W/ContextImpl( 4928): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/elm:14132( 7348): ModuleBase.resetCalllogAPIAlarm()
,D/knox    ( 4928): MainReceiver.listeningToTimeDateChanges( context, intent ).
,I/knox    ( 4928): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,D/knox    ( 4928): KNOXAgentService : onCreate()
D/knox    ( 4928): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 4928): KNOXAgentService. startJobThread() start
D/knox    ( 4928): KNOXAgentService. JobThread()
D/knox    ( 4928): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 4928): KNOXAgentService. startJobThread() wait
,I/SELinux ( 7364): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7364):  
,D/elm:14132( 7348): ModuleBase.ModifySetAlarm()
D/elm:14132( 7348): MDMBridge.getInstance()
,D/elm:14132( 7348): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 7348): ElmAgentService : onDestroy().
,I/ActivityManager( 2405): Killing 6288:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty #43
,D/knox    ( 4928): KNOXAgentService : onDestroy().
,D/knox    ( 4928): ModuleBase.cancelAllAlarmManageModule()
,I/SELinux ( 7364): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7364):  
I/SELinux ( 7364):  
,I/SELinux ( 7364): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7364): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7364): >>>>> Normal User
,E/dalvikvm( 7364): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10145 ]
,E/SELinux ( 7364): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7364): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7364): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7364): Added TimaKesytore provider
,D/dalvikvm( 7364): GC_CONCURRENT freed 3010K, 30% free 9560K/13648K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 7364): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/SELinux ( 7376): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7376):  
I/ActivityManager( 2405): Killing 6319:com.samsung.helphub/1000 (adj 15): empty #43
,I/SELinux ( 7376): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7376):  
I/SELinux ( 7376):  
,I/SELinux ( 7376): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7376): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7376): >>>>> Normal User
,E/dalvikvm( 7376): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10168 ]
,E/SELinux ( 7376): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7376): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7376): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7376): Added TimaKesytore provider
,D/dalvikvm( 7376): GC_CONCURRENT freed 2989K, 30% free 9577K/13648K, paused 15ms+1ms, total 32ms
,D/dalvikvm( 7376): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/ActivityManager( 2405): Killing 6332:com.sec.kidsplat.installer/u0a160 (adj 15): empty #43
,D/daemonapp( 5212): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5212): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5212): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5212): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5212): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionTIME_SET, run:true
D/comsamsunglog( 5212): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5212): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5212): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5212): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5212): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5212): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5212): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5212): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5212): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5212): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5212): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/comdaemonstockapp( 5212): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 5212): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,I/CheckinService( 3148): Checkin interval check for package: unspecified last checkin: 1447260279528 min interval config: 0 actual interval: 525627148
,I/SELinux ( 7389): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7389):  
,I/SELinux ( 7389): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7389):  
I/SELinux ( 7389):  
,I/SELinux ( 7389): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7389): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7389): >>>>> Normal User
,E/dalvikvm( 7389): >>>>> com.android.providers.calendar [ userId:0 | appId:10045 ]
,E/SELinux ( 7389): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7389): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7389): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7389): Added TimaKesytore provider
D/AmoledAdjustTimer( 2405): prevTemp = 302, currTemp = 303, prevStep = 4, currStep = 4
,D/dalvikvm( 7389): GC_CONCURRENT freed 2992K, 30% free 9568K/13644K, paused 7ms+1ms, total 29ms
,D/dalvikvm( 7389): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 2405): GC_EXPLICIT freed 1388K, 55% free 24560K/53956K, paused 8ms+16ms, total 173ms
,D/Headlines( 7034): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 7034): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7034): Breath 8764 latestRequest time : 1447785898550 current time : 1447785907314
,E/SPPClientService( 6418): [g] getNetMCC return empty string
,E/SPPClientService( 6418): [g] getNetMNC return empty string
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
D/Mms/MessagesLockscreen( 5500): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
W/Binder  ( 2580): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 2580): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
W/Binder  ( 2580): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
W/Binder  ( 2580): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
W/Binder  ( 2580): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
W/Binder  ( 2580): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
W/Binder  ( 2580): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
W/Binder  ( 2580): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
W/Binder  ( 2580): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
W/Binder  ( 2580): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
W/Binder  ( 2580): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
W/Binder  ( 2580): 	at android.view.View.inflate(View.java:18495)
W/Binder  ( 2580): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
W/Binder  ( 2580): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
W/Binder  ( 2580): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
W/Binder  ( 2580): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
W/Binder  ( 2580): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
W/Binder  ( 2580): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 2580): 	at dalvik.system.NativeStart.run(Native Method)
W/Binder  ( 2580): Caused by: java.lang.reflect.InvocationTargetException
W/Binder  ( 2580): 	at java.lang.reflect.Constructor.constructNative(Native Method)
W/Binder  ( 2580): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
W/Binder  ( 2580): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
W/Binder  ( 2580): 	... 16 more
W/Binder  ( 2580): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
W/Binder  ( 2580): 	at android.os.Handler.<init>(Handler.java:200)
W/Binder  ( 2580): 	at android.os.Handler.<init>(Handler.java:114)
W/Binder  ( 2580): 	at android.widget.TextClock.<init>(TextClock.java:130)
W/Binder  ( 2580): 	at android.widget.TextClock.<init>(TextClock.java:191)
W/Binder  ( 2580): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
W/Binder  ( 2580): 	... 19 more
E/JavaBinder( 2580): *** Uncaught remote exception!  (Exceptions are not yet supported across processes.)
E/JavaBinder( 2580): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
E/JavaBinder( 2580): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
E/JavaBinder( 2580): 	at android.view.View.inflate(View.java:18495)
E/JavaBinder( 2580): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
E/JavaBinder( 2580): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
E/Ja,vaBinder( 2580): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
E/JavaBinder( 2580): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
E/JavaBinder( 2580): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
E/JavaBinder( 2580): 	at android.os.Binder.execTransact(Binder.java:404)
E/JavaBinder( 2580): 	at dalvik.system.NativeStart.run(Native Method)
E/JavaBinder( 2580): Caused by: java.lang.reflect.InvocationTargetException
E/JavaBinder( 2580): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/JavaBinder( 2580): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/JavaBinder( 2580): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
E/JavaBinder( 2580): 	... 16 more
E/JavaBinder( 2580): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
E/JavaBinder( 2580): 	at android.os.Handler.<init>(Handler.java:200)
E/JavaBinder( 2580): 	at android.os.Handler.<init>(Handler.java:114)
E/JavaBinder( 2580): 	at android.widget.TextClock.<init>(TextClock.java:130)
E/JavaBinder( 2580): 	at android.widget.TextClock.<init>(TextClock.java:191)
E/JavaBinder( 2580): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
E/JavaBinder( 2580): 	... 19 more
,I/ActivityManager( 2405): Killing 6344:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty #43
,W/ContextImpl( 2405): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SPPClientService( 6418): [b] __ProvisionReply__
,E/SPPClientService( 6418): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 6418): [d] null
,V/AlarmManager( 2405):  next == MAX_VALUE
,E/SPPClientService( 6418): [g] getPLMN return empty string
,E/SPPClientService( 6418): [b] SharedConstants.WHAT_PROV_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 6418): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 6418): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 6418): [g] getNetMCC return empty string
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 6418): GC_CONCURRENT freed 2189K, 24% free 10454K/13720K, paused 3ms+3ms, total 41ms
,D/dalvikvm( 6418): WAIT_FOR_CONCURRENT_GC blocked 12ms
,E/SPPClientService( 6418): [b] __InitReply__
,D/PreloadUpdateManagerStateMachine( 6406): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6406): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6406): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6406): AutoUpdateTriggerManager:IDLE:setInterval:86400000
D/hcjo    ( 6406): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6406): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 6406): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6406): entry::IDLE
,I/ActivityManager( 2405): Waited long enough for: ServiceRecord{43ef27c8 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/jxcore-log( 6747): Attempting to connect to the test coordinator server
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): Attempting to connect to the test coordinator server
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): Attempting to connect to the test coordinator server
I/jxcore-log( 6747): 
,D/BatteryService( 2405): level:100, scale:100, status:5, health:2, present:true, voltage: 4355, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2405): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2405): stay LED for fully charged
,D/UiModeManager( 2405): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 5016): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5016): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2405): SIOP:: AP = 360, Delta = 0
,I/jxcore-log( 6747): Attempting to connect to the test coordinator server
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): Attempting to connect to the test coordinator server
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): Attempting to connect to the test coordinator server
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): Test app app.js loaded
I/jxcore-log( 6747): 
,I/Choreographer( 6747): Skipped 1532 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 6747): {"type":"test","name":"setup","id":0}
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): LogCallback not set !!!!
,I/jxcore-log( 6747): 
,I/chromium( 6747): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 6747): DBG, CoordinatorConnector connect called
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): DBG, CoordinatorConnector connect called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): DBG, CoordinatorConnector connect called
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): DBG, CoordinatorConnector connect called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): DBG, CoordinatorConnector connect called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): DBG, CoordinatorConnector connect called
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): DBG, CoordinatorConnector connect called
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): DBG, CoordinatorConnector too_late called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): {"id":0,"ok":false,"name":"Coordinator server got disconnected","operator":"fail","error":{},"test":0,"type":"assert"}
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
I/WifiManager( 6747): packageName : com.test.thalitest
,D/BluetoothAdapterService(1109748704)( 5016): unRegister RemoteMessageListener
,I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
,D/HeadsetService( 5016): registerMessageListener
D/HeadsetStateMachine( 5016): Disconnected process message: 80
,D/BluetoothAdapterState( 5016): CURRENT_STATE=ON, MSG = USER_TURN_OFF
I/BluetoothAdapterState( 5016): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 5016): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5016): updateAdapterState state is 13
,D/HeadsetStateMachine( 5016): processUnRegisterMessageListener : 2
D/BluetoothAdapterService( 5016): Broadcasting updateAdapterState() to 1 receivers.
,I/BluetoothPbapService( 5016): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
E/bt-btif ( 5016): bta_jv_rfcomm_stop_server
D/BluetoothAdapterService( 5016): Autoconnection is available 
,D/BluetoothAdapterService( 5016): updateAdapterState prevState = 12newState = 13
,D/BluetoothAdapterService( 5016): terminating service from this receiver
D/BluetoothPbap( 5484): Proxy object disconnected
,D/PbapServerProfile( 5484): Bluetooth service disconnected
,W/ContextImpl( 5016): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.stopService:511 com.android.bluetooth.btservice.AdapterService.updateAdapterState:657 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
W/InputMethodManagerService( 2405): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 2405): [BT Setting State] State =13
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
I/wpa_supplicant( 6798): reset timer : RESET_TIMER 0
I/wpa_supplicant( 6798): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 6798): Scan requested (ret=0) - scan timeout 30 seconds
D/PhoneApp( 2753): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 13
W/Settings( 2405): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine( 2405): ignore requestNetworkTransitionWakelock airplane:true
I/SamsungIME( 2961): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/QuickConnect[1.1][2] ( 4990): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_OFF
,V/BluetoothEventManager( 5484): Received android.bluetooth.adapter.action.STATE_CHANGED
,E/bt-btif ( 5016): bta_jv_rfcomm_stop_server
D/WifiP2pService( 2405): InactiveState{ what=143375 }
,I/BtOppRfcommListener( 5016): stopping Accept Thread
,E/bt-btif ( 5016): bta_jv_rfcomm_stop_server
,E/BtOppRfcommListener( 5016): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/BtOppRfcommListener( 5016): BluetoothSocket listen thread finished
D/WifiP2pService( 2405): P2pEnabledState{ what=143375 }
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
D/GKI_LINUX( 5016): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
I/BluetoothAdapterState( 5016): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
D/BluetoothAdapterState( 5016): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/CommandListener( 1915): Clearing all IP addresses on wlan0
E/bt-btif ( 5016): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
E/bt-btif ( 5016): cmd socket is not created
I/WifiManager( 6747): packageName : com.test.thalitest
,D/btif_config_util( 5016): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,W/ContextImpl( 5484): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
,E/WifiController( 2405): illegal state found both WifiController and WifiStateMachine
,I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
,I/WifiTrafficPoller( 2405): evaluateTrafficStatsPolling
D/IOP_DB_BT( 5016): db_close: nbr users 0
,D/IOP_DB_BT( 5016): db_close: free database
D/ConnectivityService( 2405): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2405): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2405): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2405): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2405): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2405): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2405): Attempting to switch to mobile
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
E/WifiStateMachine( 2405): Error! unhandled message{ when=-8ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2405): Error! unhandled message{ when=-8ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 2405): Attempting to switch to BLUETOOTH_TETHER
D/WifiP2pService( 2405): InactiveState{ what=131204 }
,D/WifiP2pService( 2405): P2pEnabledState{ what=131204 }
D/DockEventReceiver( 5484): finishStartingService: stopping service
I/WifiManager( 6747): packageName : com.test.thalitest
I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
,D/BluetoothNotiBroadcastReceiver( 5484): onReceive
,D/STATUSBAR-IconMerger( 2580): checkOverflow(384), More:false, Req:false Child:3
E/WifiController( 2405): illegal state found both WifiController and WifiStateMachine
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
D/WifiP2pService( 2405): sending p2p connection changed broadcast: FAILED
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
W/WifiP2pStateTracker( 2405): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController( 2405): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter( 2405): onP2pDisconnected
D/IpRemoteDisplayController( 2405): disconnectWfdBridgeServer
,D/IpRemoteDisplayController( 2405): WfdBridgeServer is already null
D/QuickConnect[1.1][2] ( 4990): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
I/WifiManager( 6747): packageName : com.test.thalitest
I/WifiManager( 6747): setWifiEnabled : false
D/QuickConnect[1.1][2] ( 4990): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
E/WifiController( 2405): illegal state found both WifiController and WifiStateMachine
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
,E/WifiStateMachine( 2405): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
,I/WifiManager( 6747): packageName : com.test.thalitest
D/WifiP2pService( 2405): sending p2p connection changed broadcast: DISCONNECTED
D/WifiDisplayController( 2405): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 2405): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 2405): disconnect
D/WifiDisplayController( 2405): updateConnection
D/WifiDisplayController( 2405): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayAdapter( 2405): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
D/QuickConnect[1.1][2] ( 4990): SconnectManager.INetworkStateListener, onDisabled - mNetworkState : 0
,E/WifiController( 2405): illegal state found both WifiController and WifiStateMachine
,D/QuickConnect[1.1][2] ( 4990): P2pHelper.cancelConnectPeer -  mTargetList clear all 
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
D/WifiP2pService( 2405): P2pDisablingState
D/WifiP2pService( 2405): P2pDisablingState{ what=139287 }
D/WifiP2pService( 2405): DefaultState{ what=139287 }
D/WifiP2pService( 2405): P2pDisablingState{ what=147458 }
D/WifiP2pService( 2405): p2p socket connection lost
,D/QuickConnect[1.1][2] ( 4990): P2pHelper.removeP2pConfirm - skip: false
D/WifiP2pService( 2405): P2pDisabledState
,W/WifiP2pStateTracker( 2405): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/QuickConnect[1.1][2] ( 4990): CentralActionManager.removeHoldingIntentAll - all request done.
D/QuickConnect[1.1][2] ( 4990): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
D/WifiP2pService( 2405): P2pDisabledState{ what=139376 }
D/WifiP2pService( 2405): DefaultState{ what=139376 }
,E/WifiP2pService( 2405): Unhandled message { what=139376 }
D/QuickConnect[1.1][2] ( 4990): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/QuickConnect[1.1][2] ( 4990): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
D/WifiP2pService( 2405): P2pDisabledState{ what=139287 }
,D/QuickConnect[1.1][2] ( 4990): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
,D/AuthorizationBluetoothService( 2852): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/WifiP2pService( 2405): DefaultState{ what=139287 }
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
D/WifiDisplayController( 2405): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter( 2405): onP2pDisconnected
D/IpRemoteDisplayController( 2405): disconnectWfdBridgeServer
,D/IpRemoteDisplayController( 2405): WfdBridgeServer is already null
D/CommandListener( 1915): Clearing all IP addresses on wlan0
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
,I/WifiManager( 6747): packageName : com.test.thalitest
D/QuickConnect[1.1][2] ( 4990): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
,I/WifiManager( 6747): setWifiEnabled : false
,I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
,D/WifiDisplayAdapter( 2405): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/NetworkManagementService( 2405): route cmd failed: 
W/NetworkManagementService( 2405): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '35 route del src v6 2' failed with '400 35 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2405): '
W/NetworkManagementService( 2405): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2405): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2405): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2405): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2405): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2405): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2405): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2405): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2405): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2405): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2405): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2405): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2405): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/WifiController( 2405): illegal state found both WifiController and WifiStateMachine
V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
D/WifiNative( 2405): callSECApiBoolean - ID [13]
,I/WifiTrafficPoller( 2405): evaluateTrafficStatsPolling
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
V/RouteController( 1915): RTNETLINK answers: No such process
V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
I/wpa_supplicant( 6798): USE_NETWORK : USE_NETWORK OFF
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
,I/WifiManager( 6747): packageName : com.test.thalitest
,D/BluetoothAdapterState( 5016): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 5016): isSecureModeOn:false
W/BluetoothAdapterService( 5016): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 5016): Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5016): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,I/WifiManager( 6747): setWifiEnabled : false
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
,W/BluetoothAdapterService( 5016): Not skipping com.android.bluetooth.hfp.HeadsetService
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
I/jxcore-log( 6747): toggleWiFi,
I/jxcore-log( 6747): 
I/jxcore-log( 6747): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
W/BluetoothAdapterService( 5016): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
D/NetUtils( 2405): android_net_utils_resetConnections in env=0x77d79be0 clazz=0x60700001 iface=wlan0 mask=0x3
,D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 5016): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/HeadsetService( 5016): Received stop request...Stopping profile...
,D/ConnectivityService( 2405): resetConnections(wlan0, 3)
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
E/WifiStateMachine( 2405): Error! unhandled message{ when=-43ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiManager( 6747): packageName : com.test.thalitest
E/WifiStateMachine( 2405): Error! unhandled message{ when=-44ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
W/BluetoothAdapterService( 5016): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 5016): Not skipping com.android.bluetooth.hid.HidService
D/HeadsetProfile( 5484): Bluetooth service disconnected
D/QuickConnect[1.1][2] ( 4990): HeadsetProfile.onServiceDisconnected - Bluetooth service disconnected
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
D/NearbySettings( 5484): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 5484): DMSUtil.isNetworkConnected - flag-null, state-null
E/WifiStateMachine( 2405): Error! unhandled message{ when=-29ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2405): Error! unhandled message{ when=-29ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
I/NearbySettings( 5484): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
W/BluetoothAdapterService( 5016): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
W/BluetoothAdapterService( 5016): Not skipping com.android.bluetooth.hdp.HealthService
I/NearbySettings( 5484): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 5484): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 5484): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 5484): MountReceiver.mPrefHandler - 7002
W/BluetoothAdapterService( 5016): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 5016): Not skipping com.android.bluetooth.pan.PanService
I/WifiManager( 6747): packageName : com.test.thalitest
I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
W/BluetoothAdapterService( 5016): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 5016): Not skipping com.android.bluetooth.map.BluetoothMapService
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
,I/WifiManager( 6747): packageName : com.test.thalitest
I/WifiManager( 6747): setWifiEnabled : false
W/BluetoothAdapterService( 5016): check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
,W/BluetoothAdapterService( 5016): Not skipping com.broadcom.bt.service.sap.SapService
,I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
,D/NearbySettings( 5484): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 5484): DMSUtil.isNetworkConnected - flag-null, state-null
,D/BluetoothAdapterState( 5016): Stopping profile services that were post enabled
,I/NearbySettings( 5484): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
,I/NearbySettings( 5484): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 5484): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5484): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5484): MountReceiver.mPrefHandler - 7002
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
,I/WifiManager( 6747): packageName : com.test.thalitest
,I/WifiManager( 6747): setWifiEnabled : false
D/GKI_LINUX( 5016): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
,D/FileShare-Server( 5867): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
D/FileShare-Server( 5867): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() DISCONNECTED
,I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
,D/BluetoothAdapterService( 5016): Profile still running: com.broadcom.bt.service.sap.SapService
D/A2dpService( 5016): Received stop request...Stopping profile...
D/A2dpStateMachine( 5016): Exit Disconnected: -1
,D/Avrcp   ( 5016): Unregistering previous receiver
,D/MediaFocusControl( 2405): <<< unregisterRemoteControlDisplay
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
,I/WifiManager( 6747): packageName : com.test.thalitest
,I/WifiManager( 6747): setWifiEnabled : false
,I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
,I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
,D/BluetoothA2dp( 5484): Proxy object disconnected
D/A2dpProfile( 5484): Bluetooth service disconnected
,D/BluetoothA2dp( 2405): Proxy object disconnected
,I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
D/BluetoothA2dp( 4990): Proxy object disconnected
,D/QuickConnect[1.1][2] ( 4990): A2dpProfile.onServiceConnected - Bluetooth service disconnected
,V/NativeCrypto( 2852): Read error: ssl=0x7ba7ed60: I/O error during system call, Connection timed out
,D/BluetoothA2dp( 4100): Proxy object disconnected
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
,I/WifiManager( 6747): packageName : com.test.thalitest
W/BluetoothHeadsetServiceJni( 5016): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 5016): Cleaning up Bluetooth Handsfree callback object
I/WifiManager( 6747): setWifiEnabled : false
,I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
,D/HidService( 5016): Received stop request...Stopping profile...
,D/HidService( 5016): Stopping Bluetooth HidService
D/BluetoothInputDevice( 4990): Proxy object disconnected
,D/QuickConnect[1.1][2] ( 4990): HidProfile.onServiceDisconnected - Bluetooth service disconnected
,I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
,D/HealthService( 5016): Received stop request...Stopping profile...
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
D/NearbySettings( 5484): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/WifiManager( 6747): packageName : com.test.thalitest
,V/NearbySettings( 5484): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5484): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/WifiManager( 6747): setWifiEnabled : false
D/PanService( 5016): Received stop request...Stopping profile...
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
I/NearbySettings( 5484): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 5484): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5484): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5484): MountReceiver.mPrefHandler - 7002
,D/BluetoothPan( 2405): BluetoothPAN Proxy object disconnected
,I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
,D/BluetoothMapService( 5016): Received stop request...Stopping profile...
,V/NativeCrypto( 2852): SSL shutdown failed: ssl=0x7ba7ed60: I/O error during system call, Broken pipe
,E/SPPClientService( 6418): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
E/SPPClientService( 6418): [e] exceptionCaught(). NET_TIMEOUT
D/BluetoothInputDevice( 5484): Proxy object disconnected
,D/HidProfile( 5484): Bluetooth service disconnected
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
,I/WifiManager( 6747): packageName : com.test.thalitest
,I/WifiManager( 6747): setWifiEnabled : false
,I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
D/BluetoothPan( 5484): BluetoothPAN Proxy object disconnected
,D/PanProfile( 5484): Bluetooth service disconnected
,I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
,E/SPPClientService( 6418): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
D/SapService( 5016): Received stop request...Stopping profile...
,D/SapService( 5016): Stopping Bluetooth SapService
E/SPPClientService( 6418): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 6418): [b] ResponseMap empty
D/BluetoothMap( 5484): Proxy object disconnected
,D/MapProfile( 5484): Bluetooth service disconnected
,D/Bluetoothsap( 5484): BluetoothSAP Proxy object disconnected
,D/SapProfile( 5484): Bluetooth service disconnected
,D/Tethering( 2405): interfaceLinkStateChanged p2p0, true
D/Tethering( 2405): interfaceStatusChanged p2p0, true
,I/wpa_supplicant( 6798): p2p0: CTRL-EVENT-TERMINATING 
,D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5016): Profile still running: com.broadcom.bt.service.sap.SapService
,I/GKI_LINUX( 5016): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 5016): GKI_exit_task: GKI_exit_task 2 done
,I/GKI_LINUX( 5016): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
D/Tethering( 2405): interfaceLinkStateChanged p2p0, false
,D/Tethering( 2405): interfaceStatusChanged p2p0, false
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
,D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5016): Profile still running: com.broadcom.bt.service.sap.SapService
I/WifiManager( 6747): packageName : com.test.thalitest
,W/BluetoothHidServiceJni( 5016): Cleaning up Bluetooth HID Interface...
,W/BluetoothHidServiceJni( 5016): Cleaning up Bluetooth GID callback object
,D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5016): Profile still running: com.broadcom.bt.service.sap.SapService
,I/WifiManager( 6747): setWifiEnabled : false
W/BluetoothHealthServiceJni( 5016): Cleaning up Bluetooth Health Interface...
,I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
,I/wpa_supplicant( 6798): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 6798): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,W/BluetoothHealthServiceJni( 5016): Cleaning up Bluetooth Health object
,D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5016): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothPanServiceJni( 5016): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 5016): Cleaning up Bluetooth PAN callback object
D/Bluetoothsap( 5484): BluetoothSAP Proxy object disconnected
,D/SapProfile( 5484): Bluetooth service disconnected
,I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
,D/Tethering( 2405): interfaceLinkStateChanged wlan0, true
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
,D/Tethering( 2405): interfaceStatusChanged wlan0, true
,D/Tethering( 2405): interfaceLinkStateChanged wlan0, true
D/BtSettings.ProfileConfig( 5016): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5016): Profile still running: com.broadcom.bt.service.sap.SapService
,D/Tethering( 2405): interfaceStatusChanged wlan0, true
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
D/BluetoothAdapterService( 5016): Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,I/WifiManager( 6747): packageName : com.test.thalitest
I/knox    ( 4928): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/WifiManager( 6747): setWifiEnabled : false
W/BluetoothSAPServiceJni( 5016): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
W/BluetoothSAPServiceJni( 5016): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,D/BluetoothAdapterState( 5016): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 5016): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 5016): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5016): updateAdapterState state is 10
,D/BluetoothAdapterService( 5016): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothPbap( 5484): onBluetoothStateChange: up=false
D/BluetoothAdapterService( 5016): Autoconnection is available 
D/BluetoothAdapterService( 5016): updateAdapterState prevState = 13newState = 10
,I/BluetoothAdapterState( 5016): Entering OffState
,W/ContextImpl( 4928): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
D/BluetoothMap( 5484): onBluetoothStateChange: up=false
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
D/BluetoothA2dp( 4100): onBluetoothStateChange: up=false
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
I/WifiManager( 6747): packageName : com.test.thalitest
I/knox    ( 4928): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 4928): KNOXAgentService : onCreate()
D/knox    ( 4928): KNOXAgentService : set alarms for deniallog and usage data upload
I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
D/knox    ( 4928): KNOXAgentService. startJobThread() start
D/knox    ( 4928): KNOXAgentService. JobThread()
D/knox    ( 4928): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 4928): KNOXAgentService. startJobThread() wait
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
D/knox    ( 4928): KNOXAgentService : onDestroy().
D/knox    ( 4928): ModuleBase.cancelAllAlarmManageModule()
,E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
D/Bluetoothsap( 5484): onBluetoothStateChange: up=false
,D/Bluetoothsap( 5484): Unbinding service...
,I/WifiManager( 6747): packageName : com.test.thalitest
,I/WifiManager( 6747): setWifiEnabled : false
,I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
,I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
,D/BluetoothInputDevice( 5484): onBluetoothStateChange: up=false
D/Bluetoothsap( 5484): onBluetoothStateChange: up=false
,D/Bluetoothsap( 5484): Unbinding service...
,E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
,D/BluetoothA2dp( 5484): onBluetoothStateChange: up=false
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
,D/BluetoothA2dp( 4990): onBluetoothStateChange: up=false
,I/WifiManager( 6747): packageName : com.test.thalitest
,I/WifiManager( 6747): setWifiEnabled : false
,I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
,D/BluetoothA2dp( 2405): onBluetoothStateChange: up=false
,I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
,E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
,D/BluetoothInputDevice( 4990): onBluetoothStateChange: up=false
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
,I/WifiManager( 6747): packageName : com.test.thalitest
,I/WifiManager( 6747): setWifiEnabled : false
,I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
,I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
W/InputMethodManagerService( 2405): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2405): [BT Setting State] State =10
,I/InputMethodManagerService( 2405): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
I/jxcore-log( 6747): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
D/PhoneApp( 2753): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 10
I/SamsungIME( 2961): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
I/QuickConnect[1.1][2] ( 4990): BluetoothHelper.ACTION_STATE_CHANGED - STATE_OFF
V/BluetoothEventManager( 5484): Received android.bluetooth.adapter.action.STATE_CHANGED
E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
,I/WifiManager( 6747): packageName : com.test.thalitest
,I/WifiManager( 6747): setWifiEnabled : false
,W/ContextImpl( 5484): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
,I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
D/Tethering( 2405): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2405): interfaceStatusChanged wlan0, true
,D/BluetoothTethering( 2405): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering( 2405): attempted to stop reverse tether with nothing tethered
,D/NtpTrustedTime( 2405): currentTimeMillis() cache hit
D/ConnectivityService( 2405): handleInetConditionChange: no active default network - ignore
V/NetworkStats( 2405): updateIfacesLocked()
,V/NetworkStats( 2405): performPollLocked(flags=0x1)
E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
D/NtpTrustedTime( 2405): currentTimeMillis() cache hit
D/DockEventReceiver( 5484): finishStartingService: stopping service
I/WifiManager( 6747): packageName : com.test.thalitest
D/BluetoothNotiBroadcastReceiver( 5484): onReceive
I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
D/NtpTrustedTime( 2405): currentTimeMillis() cache hit
D/NtpTrustedTime( 2405): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2405): currentTimeMillis() cache hit
,V/NetworkStats( 2405): advisePersistThreshold() given 9223372036854775, clamped to 2097152
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
I/WifiManager( 6747): packageName : com.test.thalitest
I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
,D/AuthorizationBluetoothService( 2852): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/NtpTrustedTime( 2405): currentTimeMillis() cache hit
,E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
,I/WifiManager( 6747): packageName : com.test.thalitest
I/WifiManager( 6747): setWifiEnabled : false
,V/NetworkStats( 2405): performPollLocked() took 42ms
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
,I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
,E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
,I/WifiManager( 6747): packageName : com.test.thalitest
I/WifiManager( 6747): setWifiEnabled : false
,I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
D/NtpTrustedTime( 2405): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2405): currentTimeMillis() cache hit
,I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
,E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
,I/WifiManager( 6747): packageName : com.test.thalitest
,I/WifiManager( 6747): setWifiEnabled : false
,I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
,I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
,E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
,I/WifiManager( 6747): packageName : com.test.thalitest
,I/WifiManager( 6747): setWifiEnabled : false
,I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
,I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
,E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
,I/WifiManager( 6747): packageName : com.test.thalitest
,I/WifiManager( 6747): setWifiEnabled : false
,I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
,I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
,E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
,I/WifiManager( 6747): packageName : com.test.thalitest
,I/WifiManager( 6747): setWifiEnabled : false
,I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
,I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
,E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
,D/Tethering( 2405): interfaceLinkStateChanged wlan0, false
D/Tethering( 2405): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 6798): wlan0: CTRL-EVENT-TERMINATING 
I/WifiManager( 6747): packageName : com.test.thalitest
,D/Tethering( 2405): InitialState.processMessage what=4
,E/Tethering( 2405): No numeric data,
D/Tethering( 2405): sendTetherStateChangedBroadcast 0, 0, 0
,I/ConnectivityService( 2405): defaultVal : 1, tetherEnabledInSettings : true,
I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
,D/NtpTrustedTime( 2405): currentTimeMillis() cache hit
V/NetworkStats( 2405): performPollLocked(flags=0x1)
,I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
,E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
,I/WifiManager( 6747): packageName : com.test.thalitest
,I/WifiManager( 6747): setWifiEnabled : false
,I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
,I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
,E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
I/WifiManager( 6747): packageName : com.test.thalitest
I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
D/NtpTrustedTime( 2405): currentTimeMillis() cache hit
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
,V/NetworkStats( 2405): performPollLocked() took 29ms
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
D/NtpTrustedTime( 2405): currentTimeMillis() cache hit
D/NtpTrustedTime( 2405): currentTimeMillis() cache hit
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
I/WifiManager( 6747): packageName : com.test.thalitest
I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
I/WifiManager( 6747): packageName : com.test.thalitest
I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
I/WifiManager( 6747): packageName : com.test.thalitest
I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
I/WifiManager( 6747): packageName : com.test.thalitest
I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
I/WifiManager( 6747): packageName : com.test.thalitest
I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
I/WifiManager( 6747): packageName : com.test.thalitest
I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
I/WifiManager( 6747): packageName : com.test.thalitest
I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 674,7): 
I/WifiManager( 6747): packageName : com.test.thalitest
I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
I/WifiManager( 6747): packageName : com.test.thalitest
D/WifiStateMachine( 2405): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
W/Settings( 7139): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
W/Settings( 2735): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
I/WifiManager( 6747): packageName : com.test.thalitest
I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
I/knox    ( 4928): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 4928): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
I/knox    ( 4928): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
D/knox    ( 4928): KNOXAgentService : onCreate()
I/WifiManager( 6747): packageName : com.test.thalitest
,D/knox    ( 4928): KNOXAgentService : set alarms for deniallog and usage data upload
I/WifiManager( 6747): setWifiEnabled : false
D/knox    ( 4928): KNOXAgentService. startJobThread() start
D/knox    ( 4928): KNOXAgentService. JobThread()
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
D/knox    ( 4928): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 4928): KNOXAgentService. startJobThread() wait
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
D/knox    ( 4928): KNOXAgentService : onDestroy().
D/knox    ( 4928): ModuleBase.cancelAllAlarmManageModule()
E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
I/WifiManager( 6747): packageName : com.test.thalitest
,I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
,I/WifiManager( 6747): packageName : com.test.thalitest
I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
I/WifiManager( 6747): packageName : com.test.thalitest
I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
,E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
I/WifiManager( 6747): packageName : com.test.thalitest
I/WifiManager( 6747): setWifiEnabled : false
I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): The client has disconnected!
I/jxcore-log( 6747): 
I/jxcore-log( 6747): Turning radios to false
I/jxcore-log( 6747): 
E/BluetoothManagerService( 2405): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 6747): toggleBluetooth - 
I/jxcore-log( 6747): 
I/WifiManager( 6747): packageName : com.test.thalitest
I/WifiManager( 6747): setWifiEnabled : false
,I/WifiService( 2405): setWifiEnabled: false pid=6747, uid=10446
I/jxcore-log( 6747): toggleWiFi
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
,I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): DBG, CoordinatorConnector too_late called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): DBG, CoordinatorConnector too_late called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): DBG, CoordinatorConnector too_late called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): DBG, CoordinatorConnector too_late called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): DBG, CoordinatorConnector too_late called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): DBG, CoordinatorConnector too_late called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): got too_late event, closing connection now.
I/jxcore-log( 6747): 
I/jxcore-log( 6747): CoordinatorConnector close called
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST TOOK:  ms ****
I/jxcore-log( 6747): 
I/jxcore-log( 6747): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAIL]****
I/jxcore-log( 6747): 
I/chromium( 6747): [INFO:CONSOLE(63)] "logCallback 0 isOK: false : Coordinator server got disconnected", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiStateMachine( 2405): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,D/Tethering( 2405): Tethering got CONNECTIVITY_ACTION
,I/ApplicationPolicy( 2405): updateDataUsageMap
,D/Tethering( 2405): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2405): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2405): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4595): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/PCWCLIENTTRACE_PushUtil( 6091): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6091): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6091): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6091): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6091): noConnectivity : true
,D/libgps  ( 2405): agps_ril_update_network_state: Waiting for IPC connection...
,I/KLMS-2.3.201 : ( 6974): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 6974): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1447785916566
,I/KLMS-2.3.201 : ( 6974): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/SO_AGENT( 6989): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 6989): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 6255): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 6255): [BDLM] already registered in spp
,I/SA      ( 6255): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 6255): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6255): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6255): [OR] == isSIMCardReady false ==
I/SA      ( 6255): [SCU] == networkStateCheck == false
,I/SA      ( 6255): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 6005): Other Intent
,D/com.samsung.app( 7021): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7021): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 7034): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 7034): getCountryCode(): countryCode = PL
,D/Headlines( 7034): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 7034): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 7034): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 7034): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 7034): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 7034): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 7034): requestUpdateNewsWelcomeCard !!! no welcome card
,D/AndroidRuntime( 7449): 
D/AndroidRuntime( 7449): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,I/iu.Environment( 5634): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/AndroidRuntime( 7449): CheckJNI is OFF
,D/AndroidRuntime( 7449): setted country_code = Poland
,D/AndroidRuntime( 7449): setted countryiso_code = PL
D/AndroidRuntime( 7449): setted sales_code = PLS
D/AndroidRuntime( 7449): readGMSProperty: start
,D/AndroidRuntime( 7449): readGMSProperty: already setted!!
D/AndroidRuntime( 7449): readGMSProperty: end
D/QuickConnect[1.1][2] ( 4990): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,D/AndroidRuntime( 7449): addProductProperty: start
I/QuickConnect[1.1][2] ( 4990): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 4990): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42268728
,D/AndroidRuntime( 7447): 
D/AndroidRuntime( 7447): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7447): CheckJNI is OFF
,D/AndroidRuntime( 7447): setted country_code = Poland
,D/AndroidRuntime( 7447): setted countryiso_code = PL
,I/iu.UploadsManager( 5634): num queued entries: 0
D/AndroidRuntime( 7447): setted sales_code = PLS
D/AndroidRuntime( 7447): readGMSProperty: start
,D/AndroidRuntime( 7447): readGMSProperty: already setted!!
,D/AndroidRuntime( 7447): readGMSProperty: end
D/AndroidRuntime( 7447): addProductProperty: start
,I/iu.UploadsManager( 5634): num updated entries: 0
,D/RCPManagerService( 2405): exchangeData() failure , invalid userId
,I/iu.SyncManager( 5634): NEXT; no task
,D/dalvikvm( 7449): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 7449): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 7449): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7449): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 7449): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 7447): Trying to load lib libjavacore.so 0x0
,D/AmoledAdjustTimer( 2405): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4
D/dalvikvm( 7447): Added shared lib libjavacore.so 0x0
D/RCPManagerService( 2405): exchangeData() failure , invalid userId
D/dalvikvm( 7447): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7447): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7447): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,I/iu.Environment( 3148): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/Babel   ( 7139): connection state changed from CONNECTED to DISCONNECTED
,I/iu.UploadsManager( 3148): num queued entries: 0
,I/iu.UploadsManager( 3148): num updated entries: 0
,I/iu.SyncManager( 3148): NEXT; no task
,E/SPPClientService( 6418): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6418): [SystemStateMoniter] Current Time : 330043
,E/SPPClientService( 6418): [SystemStateMoniter] No Connect : true
,E/memtrack( 7449): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 7449): failed to load memtrack module: -2
,E/memtrack( 7447): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 7447): failed to load memtrack module: -2
,E/SPPClientService( 6418): [[SystemStateMonitorService]] No Active Internet
,E/SPPClientService( 6418): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 6418): [a] [ConnectionManager] Connection is already disconnected.
D/dalvikvm( 7449): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,D/dalvikvm( 7447): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,E/SPPClientService( 6418): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,I/ActivityManager( 2405): Killing 6356:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty #43
,D/AndroidRuntime( 7449): Calling main entry com.android.commands.pm.Pm
,D/AndroidRuntime( 7447): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 2405): START PACKAGE DELETE: observer{1120208232}
D/PackageManager( 2405): pkg{<packageName>}
D/PackageManager( 2405): user{0}
,D/PackageManager( 2405): deletePackageAsUser : uid = 2000 userId = 0
,D/ApplicationPolicy( 2405): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2405): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService( 2405): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2405): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManager( 2405): !@killApplicatoin: 10446, uninstall pkg
D/PackageManager( 2405): START PACKAGE DELETE: observer{1115833728}
D/PackageManager( 2405): pkg{<packageName>}
D/PackageManager( 2405): user{0}
D/PackageManager( 2405): deletePackageAsUser : uid = 2000 userId = 0
,I/ActivityManager( 2405): Killing 6747:com.test.thalitest/u0a446 (adj 0): stop com.test.thalitest
,D/PointerIcon( 2405): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2405): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2405): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2405): setHoveringSpenCustomIcon IconType is same.1
,I/SurfaceFlinger( 1920): id=22 Removed EimLayer (5/10)
I/SurfaceFlinger( 1920): id=22 Removed EimLayer (-2/10)
I/SurfaceFlinger( 1920): id=21 Removed EimLayer (4/9)
,I/SurfaceFlinger( 1920): id=21 Removed EimLayer (-2/9)
,V/WindowManager( 2405): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/Launcher( 2769): onRestart, Launcher: 1109977720
D/Launcher( 2769): onStart, Launcher: 1109977720
,D/Launcher.HomeView( 2769): onStart
,I/SurfaceFlinger( 1920): id=23 Removed NainActivit (6/8)
,I/SurfaceFlinger( 1920): id=23 Removed NainActivit (-2/8)
I/WindowState( 2405): WIN DEATH: Window{4323ed08 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger( 1920): id=26 createSurf (720x1280),1 flag=4, Mauncher
D/STATUSBAR-StatusBarManagerService( 2405): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2405): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2405): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2405): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2405): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2405): setHoveringSpenCustomIcon IconType is same.1
,D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2405): tr p:2769,o:f
D/StatusBarManagerService( 2405): semi p:2769,o:f
,W/ContextImpl( 2405): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/PackageSettings( 2405): Skipping PackageSetting{424aa0d8 com.example.hello/10445} due to missing metadata
,W/InputMethodManagerService( 2405): Got RemoteException sending setActive(false) notification to pid 6747 uid 10446
,D/libgps  ( 2405): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2405): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2405): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2405): agps_ril_update_network_availability: Waiting for IPC connection...
,D/PackageManager( 2405): checkUidPermission - Execution time: 137 ms
,D/PackageManager( 2405): checkUidPermission - Execution time: 101 ms
D/PackageManager( 2405): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10446, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/dalvikvm( 5853): GC_EXPLICIT freed 586K, 27% free 9985K/13656K, paused 5ms+5ms, total 73ms
,D/dalvikvm( 6371): GC_EXPLICIT freed 2216K, 37% free 10003K/15868K, paused 4ms+7ms, total 98ms
,D/PackageManager( 2405): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10446, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/FPMS_FingerprintManagerService( 2600): onReceive: android.intent.action.PACKAGE_REMOVED
,E/SamsungIME( 2961): mOCRHelper is null
,D/QuickConnect[1.1][2] ( 4990): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
,I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2405):   Scheme: "sms"
I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/elm:14132( 7348): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/dalvikvm( 2965): GC_EXPLICIT freed 1445K, 27% free 10025K/13652K, paused 14ms+10ms, total 147ms
,I/InputReader( 2405): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2405):   Scheme: "smsto"
I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/GeofencerStateMachine( 2735): Ignoring removeGeofence because network location is disabled.
,D/elm:14132( 7348): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14132( 7348): ElmAgentService : onCreate()
,D/elm:14132( 7348): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 7348): MainReceiver.listeningToPackageRemoved()
,D/elm:14132( 7348): MDMBridge.getInstance()
,D/elm:14132( 7348): MDMBridge.getAllLicenseInfoFromSDK()
,D/RegisteredServicesCache( 2757): empty dynamic service
,I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2405):   Scheme: "mms"
I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 7476): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7476):  
,D/elm:14132( 7348): MDMBridge.getAllLicenseInfoFromSDK()
,I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2405):   Scheme: "mmsto"
I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 7476): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7476):  
I/SELinux ( 7476):  
,I/SELinux ( 7476): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7476): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7476): >>>>> Normal User
,E/dalvikvm( 7476): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
,E/SELinux ( 7476): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 2405): GC_EXPLICIT freed 2562K, 55% free 24768K/53956K, paused 20ms+22ms, total 331ms
,D/dalvikvm( 2405): WAIT_FOR_CONCURRENT_GC blocked 166ms
,D/TimaKeyStoreProvider( 7476): in addTimaSignatureService
,D/elm:14132( 7348): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
,D/TimaKeyStoreProvider( 7476): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7476): Added TimaKesytore provider
,D/elm:14132( 7348): ElmAgentService : onDestroy().
,I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2405):   Scheme: "sms"
,D/RCPManagerService( 2405): PackageReceiver onReceive()
,I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2405):   Scheme: "smsto"
,I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/HarmonyEASService( 2405): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2405):   Scheme: "mms"
,D/dalvikvm( 2757): GC_CONCURRENT freed 2335K, 25% free 10256K/13668K, paused 21ms+3ms, total 109ms
,I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2405):   Scheme: "mmsto"
I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 7476): GC_CONCURRENT freed 2996K, 30% free 9568K/13648K, paused 4ms+1ms, total 58ms
,D/dalvikvm( 7476): WAIT_FOR_CONCURRENT_GC blocked 48ms
,I/SELinux ( 7489): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7489):  
,I/ActivityManager( 2405): Killing 6371:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty #43
,I/SELinux ( 7489): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7489):  
I/SELinux ( 7489):  
,I/SELinux ( 7489): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7489): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7489): >>>>> Normal User
E/dalvikvm( 7489): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
E/SELinux ( 7489): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7489): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7489): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7489): Added TimaKesytore provider
,D/BackupManagerService( 2405): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 2405): removePackageParticipantsLocked: uid=10446 #1
,D/dalvikvm( 7489): GC_CONCURRENT freed 2999K, 30% free 9566K/13648K, paused 4ms+1ms, total 21ms
,D/dalvikvm( 7489): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 2405): GC_EXPLICIT freed 948K, 55% free 24784K/53956K, paused 45ms+33ms, total 492ms
D/PackageManager( 2405): delete sourFile : 
,I/PCWCLIENTTRACE_PushUtil( 6091): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6091): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6091): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6091): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/SELinux ( 7503): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7503):  
,D/PackageManager( 2405): delete native library directory: ,
,D/PackageManager( 2405): return delete result to caller: 1120208232,
,D/AndroidRuntime( 7449): Shutting down VM,
D/PackageManager( 2405): returnCode: 1
,D/dalvikvm( 7449): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 0ms+1ms, total 4ms
,D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 11% free 9503K/10624K, paused 2ms+8ms, total 36ms
I/SELinux ( 7503): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7503):  
I/SELinux ( 7503):  
,I/SELinux ( 7503): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7503): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7503): >>>>> Normal User
,E/dalvikvm( 7503): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
,E/SELinux ( 7503): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2405):   Scheme: "sms"
I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 7503): in addTimaSignatureService
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9503K/10624K, paused 3ms+3ms, total 26ms
,D/TimaKeyStoreProvider( 7503): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7503): Added TimaKesytore provider
,I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2405):   Scheme: "smsto"
I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9503K/10624K, paused 3ms+4ms, total 34ms
,I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2405):   Scheme: "mms"
I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/libgps  ( 2405): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2405): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2405): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2405):   Scheme: "mmsto"
I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/ApplicationPolicy( 2405): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2405): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService( 2405): deletePackageX- pkg:com.test.thalitest, userId:0
,D/PackageManager( 2405): [MSG] DELETE_PACKAGE_AS_USER
D/dalvikvm( 7503): GC_CONCURRENT freed 3004K, 30% free 9562K/13648K, paused 4ms+4ms, total 39ms
D/dalvikvm( 7503): WAIT_FOR_CONCURRENT_GC blocked 31ms
,I/ActivityManager( 2405): Killing 5816:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty #43
,D/PackageManager( 2405): !@killApplicatoin: 10446, uninstall pkg
,W/PackageSettings( 2405): Skipping PackageSetting{424aa0d8 com.example.hello/10445} due to missing metadata
,F/PackageManager( 2405): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager( 2405): java.io.IOException: write failed: EBADF (Bad file number)
F/PackageManager( 2405): 	at libcore.io.IoBridge.write(IoBridge.java:455)
F/PackageManager( 2405): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
F/PackageManager( 2405): 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
F/PackageManager( 2405): 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
F/PackageManager( 2405): 	at com.android.internal.util.FastXmlSerializer.flush(FastXmlSerializer.java:254)
F/PackageManager( 2405): 	at com.android.internal.util.FastXmlSerializer.append(FastXmlSerializer.java:92)
F/PackageManager( 2405): 	at com.android.internal.util.FastXmlSerializer.appendIndent(FastXmlSerializer.java:127)
F/PackageManager( 2405): 	at com.android.internal.util.FastXmlSerializer.startTag(FastXmlSerializer.java:358)
F/PackageManager( 2405): 	at com.android.server.PreferredComponent.writeToXml(PreferredComponent.java:188)
F/PackageManager( 2405): 	at com.android.server.pm.PreferredActivity.writeToXml(PreferredActivity.java:50)
F/PackageManager( 2405): 	at com.android.server.pm.Settings.writePreferredActivitiesLPr(Settings.java:1477)
F/PackageManager( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1618)
F/PackageManager( 2405): 	at com.android.server.pm.Settings.writeAllUsersPackageRestrictionsLPr(Settings.java:1055)
F/PackageManager( 2405): 	at com.android.server.pm.Settings.writeLPr(Settings.java:2097)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.removePackageDataLI(PackageManagerService.java:13205)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.deleteInstalledPackageLI(PackageManagerService.java:13330)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.deletePackageLI(PackageManagerService.java:13588)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.deletePackageX(PackageManagerService.java:13062)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.access$4900(PackageManagerService.java:252)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12966)
F/PackageManager( 2405): 	at android.os.Handler.handleCallback(Handler.java:733)
F/PackageManager( 2405): 	at android.os.Handler.dispatchMessage(Handler.java:95)
F/PackageManager( 2405): 	at android.os.Looper.loop(Looper.java:146)
F/PackageManager( 2405): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/PackageManager( 2405): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
F/PackageManager( 2405): 	at libcore.io.Posix.writeBytes(Native Method)
F/PackageManager( 2405): 	at libcore.io.Posix.write(Posix.java:202)
F/PackageManager( 2405): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
F/PackageManager( 2405): 	at libcore.io.IoBridge.write(IoBridge.java:450)
F/PackageManager( 2405): 	... 23 more
,I/PackageManager( 2405): Failed to clean up mangled file: /data/system/packages-stopped.xml
,D/PackageManager( 2405): checkUidPermission - Execution time: 142 ms
E/DropBoxManagerService( 2405): Can't write: system_server_wtf
E/DropBoxManagerService( 2405): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2405): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2405): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2405): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2405): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:411)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1642)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.Settings.writeAllUsersPackageRestrictionsLPr(Settings.java:1055)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.Settings.writeLPr(Settings.java:2097)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.removePackageDataLI(PackageManagerService.java:13205)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.deleteInstalledPackageLI(PackageManagerService.java:13330)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.deletePackageLI(PackageManagerService.java:13588)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.deletePackageX(PackageManagerService.java:13062)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.access$4900(PackageManagerService.java:252)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12966)
E/DropBoxManagerService( 2405): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2405): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2405): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2405): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2405): 	... 24 more
D/PackageManager( 2405): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10446, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,W/ApplicationsProvider( 2965): Could not fetch usage stats
W/ApplicationsProvider( 2965): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2965): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2965): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2965): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2965): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2965): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2965): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2965): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2965): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2965): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2965): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2965): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/PackageManager( 2405): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10446, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/EnterpriseDeviceManagerService( 2405): Package has changed for user 0
,I/FPMS_FingerprintManagerService( 2600): onReceive: android.intent.action.PACKAGE_REMOVED
,E/SamsungIME( 2961): mOCRHelper is null
,I/InputReader( 2405): Reconfiguring input devices.  changes=0x00000010
,D/QuickConnect[1.1][2] ( 4990): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
,W/GeofencerStateMachine( 2735): Ignoring removeGeofence because network location is disabled.
,I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2405):   Scheme: "sms"
,D/RCPManagerService( 2405): PackageReceiver onReceive()
W/PackageManager( 2405): Preserving older stopped packages backup
,F/PackageManager( 2405): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager( 2405): java.io.FileNotFoundException: /data/system/users/0/package-restrictions.xml: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
F/PackageManager( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1528)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
F/PackageManager( 2405): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
F/PackageManager( 2405): 	at android.os.Binder.execTransact(Binder.java:404)
F/PackageManager( 2405): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.Posix.open(Native Method)
F/PackageManager( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
F/PackageManager( 2405): 	... 9 more
,I/PackageManager( 2405): Failed to clean up mangled file: /data/system/packages-stopped.xml
,D/RegisteredServicesCache( 2757): empty dynamic service
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/DropBoxManagerService( 2405): Can't write: system_server_wtf
E/DropBoxManagerService( 2405): java.io.FileNotFoundException: /data/system/dropbox/drop208.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2405): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2405): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2405): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2405): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:411)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1642)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2405): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2405): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2405): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2405): 	... 18 more
I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2405):   Scheme: "smsto"
I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/PackageManager( 2405): Preserving older stopped packages backup
F/PackageManager( 2405): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager( 2405): java.io.FileNotFoundException: /data/system/users/0/package-restrictions.xml: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
F/PackageManager( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1528)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
F/PackageManager( 2405): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
F/PackageManager( 2405): 	at android.os.Binder.execTransact(Binder.java:404)
F/PackageManager( 2405): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.Posix.open(Native Method)
F/PackageManager( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
F/PackageManager( 2405): 	... 9 more
,I/PackageManager( 2405): Failed to clean up mangled file: /data/system/packages-stopped.xml
E/DropBoxManagerService( 2405): Can't write: system_server_wtf
E/DropBoxManagerService( 2405): java.io.FileNotFoundException: /data/system/dropbox/drop170.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2405): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2405): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2405): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2405): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:411)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1642)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2405): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2405): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2405): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2405): 	... 18 more
,I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2405):   Scheme: "mms"
I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,F/PackageManager( 2405): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager( 2405): java.io.FileNotFoundException: /data/system/users/0/package-restrictions.xml: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
F/PackageManager( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1528)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
F/PackageManager( 2405): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
F/PackageManager( 2405): 	at android.os.Binder.execTransact(Binder.java:404)
F/PackageManager( 2405): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.Posix.open(Native Method)
F/PackageManager( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
F/PackageManager( 2405): 	... 9 more
W/PackageManager( 2405): Preserving older stopped packages backup
,I/PackageManager( 2405): Failed to clean up mangled file: /data/system/packages-stopped.xml
E/DropBoxManagerService( 2405): Can't write: system_server_wtf
E/DropBoxManagerService( 2405): java.io.FileNotFoundException: /data/system/dropbox/drop16.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2405): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2405): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2405): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2405): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:411)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1642)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2405): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2405): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2405): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2405): 	... 18 more
,I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2405):   Scheme: "mmsto"
I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,F/PackageManager( 2405): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager( 2405): java.io.FileNotFoundException: /data/system/users/0/package-restrictions.xml: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
F/PackageManager( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1528)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
F/PackageManager( 2405): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
F/PackageManager( 2405): 	at android.os.Binder.execTransact(Binder.java:404)
F/PackageManager( 2405): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.Posix.open(Native Method)
F/PackageManager( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
F/PackageManager( 2405): 	... 9 more
W/PackageManager( 2405): Preserving older stopped packages backup
,I/PackageManager( 2405): Failed to clean up mangled file: /data/system/packages-stopped.xml
E/DropBoxManagerService( 2405): Can't write: system_server_wtf
E/DropBoxManagerService( 2405): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2405): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2405): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2405): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2405): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:411)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1642)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2405): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2405): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2405): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2405): 	... 18 more
,I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2405):   Scheme: "sms"
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,F/PackageManager( 2405): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager( 2405): java.io.FileNotFoundException: /data/system/users/0/package-restrictions.xml: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
F/PackageManager( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1528)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
F/PackageManager( 2405): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
F/PackageManager( 2405): 	at android.os.Binder.execTransact(Binder.java:404)
F/PackageManager( 2405): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.Posix.open(Native Method)
F/PackageManager( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
F/PackageManager( 2405): 	... 9 more
W/PackageManager( 2405): Preserving older stopped packages backup
,I/PackageManager( 2405): Failed to clean up mangled file: /data/system/packages-stopped.xml
E/DropBoxManagerService( 2405): Can't write: system_server_wtf
E/DropBoxManagerService( 2405): java.io.FileNotFoundException: /data/system/dropbox/drop17.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2405): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2405): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2405): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2405): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:411)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1642)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2405): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2405): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2405): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2405): 	... 18 more
I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2405):   Scheme: "smsto"
,F/PackageManager( 2405): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager( 2405): java.io.FileNotFoundException: /data/system/users/0/package-restrictions.xml: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
F/PackageManager( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1528)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
F/PackageManager( 2405): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
F/PackageManager( 2405): 	at android.os.Binder.execTransact(Binder.java:404)
F/PackageManager( 2405): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.Posix.open(Native Method)
F/PackageManager( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
F/PackageManager( 2405): 	... 9 more
I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/PackageManager( 2405): Preserving older stopped packages backup
,I/PackageManager( 2405): Failed to clean up mangled file: /data/system/packages-stopped.xml
E/DropBoxManagerService( 2405): Can't write: system_server_wtf
E/DropBoxManagerService( 2405): java.io.FileNotFoundException: /data/system/dropbox/drop207.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2405): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2405): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2405): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2405): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:411)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1642)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2405): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2405): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2405): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2405): 	... 18 more
,I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2405):   Scheme: "mms"
I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/PackageManager( 2405): Preserving older stopped packages backup
F/PackageManager( 2405): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager( 2405): java.io.FileNotFoundException: /data/system/users/0/package-restrictions.xml: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
F/PackageManager( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1528)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
F/PackageManager( 2405): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
F/PackageManager( 2405): 	at android.os.Binder.execTransact(Binder.java:404)
F/PackageManager( 2405): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.Posix.open(Native Method)
F/PackageManager( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
F/PackageManager( 2405): 	... 9 more
,I/PackageManager( 2405): Failed to clean up mangled file: /data/system/packages-stopped.xml
E/DropBoxManagerService( 2405): Can't write: system_server_wtf
E/DropBoxManagerService( 2405): java.io.FileNotFoundException: /data/system/dropbox/drop208.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2405): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2405): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2405): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2405): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:411)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1642)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2405): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2405): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2405): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2405): 	... 18 more
I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2405):   Scheme: "mmsto"
I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,F/PackageManager( 2405): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager( 2405): java.io.FileNotFoundException: /data/system/users/0/package-restrictions.xml: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
F/PackageManager( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1528)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
F/PackageManager( 2405): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
F/PackageManager( 2405): 	at android.os.Binder.execTransact(Binder.java:404)
F/PackageManager( 2405): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.Posix.open(Native Method)
F/PackageManager( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
F/PackageManager( 2405): 	... 9 more
W/PackageManager( 2405): Preserving older stopped packages backup
,E/DropBoxManagerService( 2405): Can't write: system_server_wtf
E/DropBoxManagerService( 2405): java.io.FileNotFoundException: /data/system/dropbox/drop165.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2405): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2405): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2405): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2405): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:411)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1642)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2405): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1065)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2405): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2405): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2405): 	... 18 more
I/PackageManager( 2405): Failed to clean up mangled file: /data/system/packages-stopped.xml
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 2405): GC_EXPLICIT freed 3012K, 55% free 24764K/53956K, paused 8ms+26ms, total 420ms
W/PackageManager( 2405): Package source /data/app/com.test.thalitest-1.apk does not exist.
D/PackageManager( 2405): Couldn't delete sourFile : 
W/PackageManager( 2405): Couldn't delete native library directory /data/app-lib/com.test.thalitest-1
D/PackageManager( 2405): return delete result to caller: 1115833728
,D/PackageManager( 2405): returnCode: 1
D/AndroidRuntime( 7447): Shutting down VM
D/dalvikvm( 7447): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+0ms, total 5ms
,I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2405):   Scheme: "sms"
I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/PackageManager( 2405): Preserving older stopped packages backup
,F/PackageManager( 2405): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager( 2405): java.io.FileNotFoundException: /data/system/users/0/package-restrictions.xml: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
F/PackageManager( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1528)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
F/PackageManager( 2405): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
F/PackageManager( 2405): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
F/PackageManager( 2405): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:558)
F/PackageManager( 2405): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
F/PackageManager( 2405): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
F/PackageManager( 2405): 	at android.os.Handler.handleCallback(Handler.java:733)
F/PackageManager( 2405): 	at android.os.Handler.dispatchMessage(Handler.java:95)
F/PackageManager( 2405): 	at android.os.Looper.loop(Looper.java:146)
F/PackageManager( 2405): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/PackageManager( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.Posix.open(Native Method)
F/PackageManager( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
F/PackageManager( 2405): 	... 15 more
,I/PackageManager( 2405): Failed to clean up mangled file: /data/system/packages-stopped.xml
E/DropBoxManagerService( 2405): Can't write: system_server_wtf
E/DropBoxManagerService( 2405): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2405): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2405): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2405): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2405): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:411)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1642)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2405): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2405): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2405): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:558)
E/DropBoxManagerService( 2405): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2405): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2405): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2405): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2405): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2405): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2405): 	... 24 more
,I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2405):   Scheme: "smsto"
I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,F/PackageManager( 2405): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager( 2405): java.io.FileNotFoundException: /data/system/users/0/package-restrictions.xml: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
F/PackageManager( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1528)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
F/PackageManager( 2405): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
F/PackageManager( 2405): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
F/PackageManager( 2405): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:559)
F/PackageManager( 2405): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
F/PackageManager( 2405): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
F/PackageManager( 2405): 	at android.os.Handler.handleCallback(Handler.java:733)
F/PackageManager( 2405): 	at android.os.Handler.dispatchMessage(Handler.java:95)
F/PackageManager( 2405): 	at android.os.Looper.loop(Looper.java:146)
F/PackageManager( 2405): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/PackageManager( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.Posix.open(Native Method)
F/PackageManager( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
F/PackageManager( 2405): 	... 15 more
W/PackageManager( 2405): Preserving older stopped packages backup
,I/PackageManager( 2405): Failed to clean up mangled file: /data/system/packages-stopped.xml
I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
E/DropBoxManagerService( 2405): Can't write: system_server_wtf
E/DropBoxManagerService( 2405): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2405): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2405): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2405): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2405): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:411)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1642)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2405): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2405): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2405): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:559)
E/DropBoxManagerService( 2405): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2405): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2405): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2405): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2405): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2405): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2405): 	... 24 more
,I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2405):   Scheme: "mms"
,F/PackageManager( 2405): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager( 2405): java.io.FileNotFoundException: /data/system/users/0/package-restrictions.xml: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
F/PackageManager( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1528)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
F/PackageManager( 2405): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
F/PackageManager( 2405): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
F/PackageManager( 2405): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:560)
F/PackageManager( 2405): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
F/PackageManager( 2405): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
F/PackageManager( 2405): 	at android.os.Handler.handleCallback(Handler.java:733)
F/PackageManager( 2405): 	at android.os.Handler.dispatchMessage(Handler.java:95)
F/PackageManager( 2405): 	at android.os.Looper.loop(Looper.java:146)
F/PackageManager( 2405): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/PackageManager( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.Posix.open(Native Method)
F/PackageManager( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
F/PackageManager( 2405): 	... 15 more
W/PackageManager( 2405): Preserving older stopped packages backup
,I/PackageManager( 2405): Failed to clean up mangled file: /data/system/packages-stopped.xml
I/PackageManager( 2405):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2405):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2405):   Scheme: "mmsto"
E/DropBoxManagerService( 2405): Can't write: system_server_wtf
E/DropBoxManagerService( 2405): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2405): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2405): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2405): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2405): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:411)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1642)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2405): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2405): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2405): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:560)
E/DropBoxManagerService( 2405): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2405): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2405): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2405): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2405): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2405): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2405): 	... 24 more
I/PackageManager( 2405): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,F/PackageManager( 2405): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager( 2405): java.io.FileNotFoundException: /data/system/users/0/package-restrictions.xml: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
F/PackageManager( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
F/PackageManager( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1528)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
F/PackageManager( 2405): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
F/PackageManager( 2405): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
F/PackageManager( 2405): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:561)
F/PackageManager( 2405): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
F/PackageManager( 2405): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
F/PackageManager( 2405): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
F/PackageManager( 2405): 	at android.os.Handler.handleCallback(Handler.java:733)
F/PackageManager( 2405): 	at android.os.Handler.dispatchMessage(Handler.java:95)
F/PackageManager( 2405): 	at android.os.Looper.loop(Looper.java:146)
F/PackageManager( 2405): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/PackageManager( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
F/PackageManager( 2405): 	at libcore.io.Posix.open(Native Method)
F/PackageManager( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
F/PackageManager( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
F/PackageManager( 2405): 	... 15 more
W/PackageManager( 2405): Preserving older stopped packages backup
,I/PackageManager( 2405): Failed to clean up mangled file: /data/system/packages-stopped.xml
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/DropBoxManagerService( 2405): Can't write: system_server_wtf
E/DropBoxManagerService( 2405): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2405): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2405): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2405): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2405): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2405): 	at android.util.Log.wtf(Log.java:411)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1642)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:14020)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:14076)
E/DropBoxManagerService( 2405): 	at android.app.ApplicationPackageManager.replacePreferredActivity(ApplicationPackageManager.java:1459)
E/DropBoxManagerService( 2405): 	at com.android.internal.telephony.SmsApplication.replacePreferredActivity(SmsApplication.java:587)
E/DropBoxManagerService( 2405): 	at com.android.internal.telephony.SmsApplication.configurePreferredActivity(SmsApplication.java:561)
E/DropBoxManagerService( 2405): 	at com.android.internal.telephony.SmsApplication.getApplication(SmsApplication.java:347)
E/DropBoxManagerService( 2405): 	at com.android.internal.telephony.SmsApplication.getDefaultSmsApplication(SmsApplication.java:609)
E/DropBoxManagerService( 2405): 	at com.android.server.pm.PackageManagerService$12.run(PackageManagerService.java:12992)
E/DropBoxManagerService( 2405): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 2405): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 2405): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2405): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2405): 	... 24 more
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector( 2405): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2405): clearDefaults: com.test.thalitest
,W/AtomicFile( 2405): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl( 2405): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,D/EnterpriseDeviceManagerService( 2405): Package has changed for user 0
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/System.err( 7503): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
,W/System.err( 7503): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 7503): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 7503): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err( 7503): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err( 7503): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err( 7503): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err( 7503): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err( 7503): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err( 7503): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err( 7503): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err( 7503): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 7503): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 7503): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7503): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 7503): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7503): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 7503): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 7503): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 7503): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 7503): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 7503): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 7503): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 7503): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 7503): 	at libcore.io.Posix.open(Native Method)
W/System.err( 7503): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
,W/System.err( 7503): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 7503): 	... 21 more
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/GalaxyFinderApplication( 7503): [Slink platform] Version = 29011
,D/GalaxyFinderApplication( 7503): [Slink platform] use state of slink location service is [false] to [true]
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/SELinux ( 7520): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7520):  
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2405): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector( 2405): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2405): clearDefaults: com.test.thalitest
,E/SQLiteLog( 7201): (3850) statement aborts at 35: [DELETE FROM app_registry WHERE package_name=? AND plugin_id=? AND sync_status != 170004 AND sync_status = 170002] disk I/O error
,W/dalvikvm( 7201): threadid=12: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7201): FATAL EXCEPTION: IntentService[HandleAppDataService]
E/AndroidRuntime( 7201): Process: com.sec.android.app.shealth, PID: 7201
E/AndroidRuntime( 7201): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 7201): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 7201): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 7201): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 7201): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 7201): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 7201): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericDelete(BaseContentProvider.java:486)
E/AndroidRuntime( 7201): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.delete(BaseContentProvider.java:441)
E/AndroidRuntime( 7201): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 7201): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 7201): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.deleteAppRegistryData(AppRegistryDbManagerWithProvider.java:459)
E/AndroidRuntime( 7201): 	at com.sec.android.app.shealth.service.HandleAppDataService.onHandleIntent(HandleAppDataService.java:56)
E/AndroidRuntime( 7201): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7201): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7201): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7201): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService( 2405): Can't write: system_app_crash
E/DropBoxManagerService( 2405): java.io.FileNotFoundException: /data/system/dropbox/drop238.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2405): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2405): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2405): 	... 5 more
I/Process ( 7201): Sending signal. PID: 7201 SIG: 9
,I/SELinux ( 7520): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7520):  
I/SELinux ( 7520):  
,I/ActivityManager( 2405): Process com.sec.android.app.shealth (pid 7201) (adj 5) has died.
I/SELinux ( 7520): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7520): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 7520): >>>>> Normal User
E/dalvikvm( 7520): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10043 ]
E/SELinux ( 7520): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 7520): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7520): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7520): Added TimaKesytore provider
,D/dalvikvm( 7520): GC_CONCURRENT freed 2997K, 30% free 9573K/13652K, paused 2ms+2ms, total 23ms
,D/dalvikvm( 7520): WAIT_FOR_CONCURRENT_GC blocked 21ms
,W/ApplicationsProvider( 2965): Could not fetch usage stats
W/ApplicationsProvider( 2965): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2965): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2965): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2965): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2965): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2965): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2965): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2965): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2965): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2965): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2965): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2965): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteDatabase( 7520): Failed to open database '/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db'.
E/SQLiteDatabase( 7520): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7520): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7520): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7520): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7520): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7520): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7520): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7520): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7520): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7520): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7520): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7520): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7520): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7520): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7520): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:429)
E/SQLiteDatabase( 7520): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7520): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7520): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7520): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7520): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7520): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7520): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7520): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7520): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7520): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7520): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7520): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7520): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7520): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7520): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7520): Shutting down VM
,W/dalvikvm( 7520): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7520): FATAL EXCEPTION: main
E/AndroidRuntime( 7520): Process: com.samsung.android.sdk.samsunglink, PID: 7520
E/AndroidRuntime( 7520): java.lang.RuntimeException: Unable to get provider com.mfluent.asp.datamodel.ASPMediaStoreProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7520): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7520): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7520): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7520): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7520): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7520): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7520): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7520): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7520): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7520): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7520): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7520): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7520): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7520): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7520): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7520): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7520): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7520): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7520): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7520): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7520): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7520): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7520): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7520): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7520): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7520): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7520): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7520): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:429)
E/AndroidRuntime( 7520): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7520): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7520): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7520): 	... 12 more
,I/Process ( 7520): Sending signal. PID: 7520 SIG: 9
,I/SA      ( 6255): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,E/DropBoxManagerService( 2405): Can't write: system_app_crash
E/DropBoxManagerService( 2405): java.io.FileNotFoundException: /data/system/dropbox/drop239.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2405): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2405): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2405): 	... 5 more
,I/SA      ( 6255): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
I/ActivityManager( 2405): Killing 5907:com.sec.knox.bridge/1000 (adj 15): empty #43
,I/ActivityManager( 2405): Process com.samsung.android.sdk.samsunglink (pid 7520) (adj 9) has died.
,E/SharedPreferencesImpl( 3422): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,I/Icing.InternalIcingCorporaProvider( 5853): Updating corpora: A: com.test.thalitest, C: MAYBE
,E/SQLiteLog( 5853): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/dalvikvm( 5853): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,I/SELinux ( 7539): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7539):  
E/AndroidRuntime( 5853): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 5853): Process: com.google.android.googlequicksearchbox:search, PID: 5853
E/AndroidRuntime( 5853): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 5853): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 5853): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 5853): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 5853): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 5853): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 5853): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 5853): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:171)
E/AndroidRuntime( 5853): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 5853): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
E/AndroidRuntime( 5853): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 5853): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 5853): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 5853): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 5853): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 5853): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 5853): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 5853): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5853): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 5853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 5853): Sending signal. PID: 5853 SIG: 9
E/DropBoxManagerService( 2405): Can't write: system_app_crash
E/DropBoxManagerService( 2405): java.io.FileNotFoundException: /data/system/dropbox/drop240.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2405): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2405): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2405): 	... 5 more
,I/ActivityManager( 2405): Process com.google.android.googlequicksearchbox:search (pid 5853) (adj 5) has died.
,I/SELinux ( 7539): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7539):  
I/SELinux ( 7539):  
,I/SELinux ( 7539): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7539): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7539): >>>>> Normal User
,E/dalvikvm( 7539): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 7539): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7539): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7539): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7539): Added TimaKesytore provider
,D/dalvikvm( 7539): GC_CONCURRENT freed 2994K, 30% free 9570K/13648K, paused 4ms+2ms, total 26ms
,D/dalvikvm( 7539): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/UserAnalysis.PlaceProvider( 7539): Create SecureDbHelper
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 7539): Create SecureDbHelper
,E/SQLiteDatabase( 7539): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7539): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7539): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7539): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7539): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7539): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7539): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteDatabase( 7539): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7539): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7539): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7539): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7539): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7539): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7539): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7539): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7539): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7539): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7539): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7539): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7539): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7539): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7539): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7539): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7539): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7539): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7539): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7539): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7539): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7539): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7539): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7539): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7539): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7539): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteOpenHelper( 7539): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7539): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7539): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7539): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7539): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7539): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7539): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7539): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7539): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7539): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7539): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7539): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 7539): Opened privacy in read-only mode
,E/SQLiteDatabase( 7539): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7539): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7539): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7539): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7539): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7539): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7539): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteDatabase( 7539): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7539): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7539): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7539): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7539): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7539): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7539): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7539): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7539): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7539): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7539): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7539): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7539): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7539): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7539): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7539): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7539): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7539): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7539): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7539): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7539): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7539): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7539): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7539): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7539): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7539): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteOpenHelper( 7539): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7539): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7539): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7539): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7539): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7539): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7539): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7539): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7539): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7539): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7539): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7539): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 7539): Opened privacy in read-only mode
,E/SQLiteDatabase( 7539): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7539): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7539): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7539): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7539): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7539): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7539): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
E/SQLiteDatabase( 7539): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7539): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7539): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7539): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7539): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7539): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7539): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7539): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7539): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7539): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7539): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7539): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 7539): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 7539): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 7539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 7539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 7539): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 7539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 7539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 7539): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
,W/System.err( 7539): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 7539): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 7539): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 7539): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7539): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7539): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 7539): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
,W/System.err( 7539): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
W/System.err( 7539): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
W/System.err( 7539): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 7539): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 7539): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 7539): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 7539): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 7539): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 7539): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 7539): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 7539): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 7539): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 7539): 	at dalvik.system.NativeStart.main(Native Method)
,I/SELinux ( 7552): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7552):  
,I/SELinux ( 7552): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7552):  
I/SELinux ( 7552):  
,I/SELinux ( 7552): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7552): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7552): >>>>> Normal User
,E/dalvikvm( 7552): >>>>> com.samsung.android.app.assistantmenu [ userId:0 | appId:1000 ]
,E/SELinux ( 7552): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7552): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7552): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7552): Added TimaKesytore provider
,D/dalvikvm( 7552): GC_CONCURRENT freed 3004K, 30% free 9566K/13648K, paused 2ms+2ms, total 28ms
,D/dalvikvm( 7552): WAIT_FOR_CONCURRENT_GC blocked 21ms
,W/ContextImpl( 7552): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:165 android.app.ActivityThread.handleReceiver:2698 
,E/SQLiteDatabase( 7552): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 7552): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7552): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7552): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7552): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7552): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7552): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7552): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7552): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7552): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7552): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7552): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7552): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7552): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7552): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7552): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 7552): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 7552): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7552): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7552): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7552): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 7552): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 7552): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 7552): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 7552): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 7552): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 7552): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 7552): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 7552): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 7552): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 7552): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 7552): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 7552): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
,W/System.err( 7552): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 7552): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 7552): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 7552): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
,W/System.err( 7552): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 7552): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7552): 	at android.os.Looper.loop(Looper.java:146)
,W/System.err( 7552): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SELinux ( 7565): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7565):  
,I/ActivityManager( 2405): Killing 5953:com.sec.android.Kies/1000 (adj 15): empty #43
,I/SELinux ( 7565): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7565):  
I/SELinux ( 7565):  
,I/SELinux ( 7565): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7565): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7565): >>>>> Normal User
,E/dalvikvm( 7565): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
,E/SELinux ( 7565): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7565): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7565): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7565): Added TimaKesytore provider
,D/dalvikvm( 7565): GC_CONCURRENT freed 3002K, 30% free 9566K/13648K, paused 4ms+2ms, total 25ms
,D/dalvikvm( 7565): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/RCPManager( 7565):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2405):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 2405): queryAllProviders():  providerCallBack is not register for 0
,I/SELinux ( 7577): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7577):  
I/ActivityManager( 2405): Killing 5981:com.google.android.apps.uploader/u0a117 (adj 15): empty #43
,I/SELinux ( 7577): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7577):  
I/SELinux ( 7577):  
,I/SELinux ( 7577): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7577): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 7577): >>>>> Normal User
,E/dalvikvm( 7577): >>>>> com.sec.android.service.cm [ userId:0 | appId:10082 ]
,E/SELinux ( 7577): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 7577): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7577): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7577): Added TimaKesytore provider
,D/dalvikvm( 7577): GC_CONCURRENT freed 3007K, 30% free 9559K/13648K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 7577): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/CapabilityManagerService New( 7577): Receiver Broadcast:android.intent.action.PACKAGE_REMOVED
,D/CapabilityManagerService New( 7577): The package(com.test.thalitest) removed
,W/System.err( 2405): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
,W/System.err( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2405): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2405): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
,W/System.err( 2405): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2405): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2405): 	at android.os.Binder.execTransact(Binder.java:404)
,W/System.err( 2405): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
,W/System.err( 2405): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
,W/System.err( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 2405): 	... 8 more
,W/System.err( 2405): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2405): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2405): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2405): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2405): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
,W/System.err( 2405): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2405): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 2405): 	at libcore.io.Posix.open(Native Method)
,W/System.err( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 2405): 	... 8 more
,I/SELinux ( 7589): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7589):  
I/ActivityManager( 2405): Killing 5444:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SELinux ( 7589): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7589):  
I/SELinux ( 7589):  
,I/SELinux ( 7589): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7589): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7589): >>>>> Normal User
,E/dalvikvm( 7589): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10104 ]
,E/SELinux ( 7589): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7589): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7589): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7589): Added TimaKesytore provider
,D/dalvikvm( 7589): GC_CONCURRENT freed 3011K, 30% free 9559K/13652K, paused 3ms+2ms, total 24ms
,D/dalvikvm( 7589): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/MagazineService::MagazineBroadcastReceiver( 6301): [onReceive] android.intent.action.PACKAGE_REMOVED com.test.thalitest
,I/MagazineService::MagazineService( 6301): [onHandleIntent] ACTION_PACKAGE_REMOVED
,E/SQLiteLog( 6301): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/dalvikvm( 6301): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,I/SELinux ( 7602): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7602):  
E/AndroidRuntime( 6301): FATAL EXCEPTION: IntentService[MagazineService::MagazineService]
E/AndroidRuntime( 6301): Process: com.samsung.android.magazine.service, PID: 6301
E/AndroidRuntime( 6301): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6301): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6301): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 6301): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6301): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6301): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 6301): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 6301): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:408)
E/AndroidRuntime( 6301): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6301): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6301): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/AndroidRuntime( 6301): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6301): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6301): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6301): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SELinux ( 7606): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7606):  
,I/Process ( 6301): Sending signal. PID: 6301 SIG: 9
E/DropBoxManagerService( 2405): Can't write: system_app_crash
E/DropBoxManagerService( 2405): java.io.FileNotFoundException: /data/system/dropbox/drop241.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2405): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2405): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2405): 	... 5 more
,I/ActivityManager( 2405): Process com.samsung.android.magazine.service (pid 6301) (adj 5) has died.
,I/SELinux ( 7602): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7602):  
I/SELinux ( 7602):  
,I/SELinux ( 7602): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7602): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7602): >>>>> Normal User
,E/dalvikvm( 7602): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 7602): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/SELinux ( 7606): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7606):  
I/SELinux ( 7606):  
,I/SELinux ( 7606): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7606): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7606): >>>>> Normal User
,E/dalvikvm( 7606): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,D/TimaKeyStoreProvider( 7602): in addTimaSignatureService
,E/SELinux ( 7606): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7602): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7602): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 7606): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7606): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7606): Added TimaKesytore provider
,D/dalvikvm( 7606): GC_CONCURRENT freed 3000K, 30% free 9570K/13648K, paused 2ms+2ms, total 29ms
,D/dalvikvm( 7606): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 7602): GC_CONCURRENT freed 2990K, 30% free 9576K/13644K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 7602): WAIT_FOR_CONCURRENT_GC blocked 22ms
,E/SQLiteDatabase( 7606): Failed to open database '/data/data/com.samsung.helphub/databases/search.db'.
E/SQLiteDatabase( 7606): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7606): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7606): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7606): 	at com.samsung.helphub.search.SearchProvider.onCreate(SearchProvider.java:63)
E/SQLiteDatabase( 7606): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7606): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7606): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7606): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7606): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7606): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7606): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7606): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7606): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7606): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7606): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7606): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7606): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7606): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7606): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7606): Couldn't open search.db for writing (will try read-only):
E/SQLiteOpenHelper( 7606): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7606): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7606): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7606): 	at com.samsung.helphub.search.SearchProvider.onCreate(SearchProvider.java:63)
E/SQLiteOpenHelper( 7606): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteOpenHelper( 7606): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteOpenHelper( 7606): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteOpenHelper( 7606): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteOpenHelper( 7606): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteOpenHelper( 7606): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteOpenHelper( 7606): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteOpenHelper( 7606): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7606): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7606): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7606): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7606): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7606): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7606): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7606): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 7606): Opened search.db in read-only mode
,I/SELinux ( 7627): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7627):  
I/ActivityManager( 2405): Killing 5696:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/Icing.InternalIcingCorporaProvider( 7602): Updating corpora: A: com.test.thalitest, C: MAYBE
,D/AndroidRuntime( 2405): Shutting down VM
,W/dalvikvm( 2405): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
I/SELinux ( 7627): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7627):  
I/SELinux ( 7627):  
,I/SELinux ( 7627): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7627): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7627): >>>>> Normal User
E/dalvikvm( 7627): >>>>> com.android.keychain [ userId:0 | appId:1000 ]
E/SELinux ( 7627): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/AndroidRuntime( 2405): !@*** FATAL EXCEPTION IN SYSTEM PROCESS: main
E/AndroidRuntime( 2405): java.lang.RuntimeException: Error receiving broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) } in com.android.server.enterprise.keystore.TimaKeystoreService$KeystoreReceiver@424125a8
E/AndroidRuntime( 2405): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:782)
E/AndroidRuntime( 2405): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 2405): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 2405): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2405): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:2178)
E/AndroidRuntime( 2405): 	at com.android.server.SystemServer.main(SystemServer.java:2317)
E/AndroidRuntime( 2405): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2405): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2405): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 2405): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 2405): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2405): Caused by: android.database.sqlite.SQLiteDatabaseLockedException: database is locked (code 5)
E/AndroidRuntime( 2405): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2405): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 2405): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2405): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2405): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 2405): 	at com.android.server.enterprise.storage.EdmStorageProviderBase.delete(EdmStorageProviderBase.java:471)
E/AndroidRuntime( 2405): 	at com.android.server.enterprise.storage.EdmStorageProviderBase.deleteDataByFields(EdmStorageProviderBase.java:1447)
E/AndroidRuntime( 2405): 	at com.android.server.enterprise.storage.EdmStorageProvider.deleteDataByFields(EdmStorageProvider.java:445)
E/AndroidRuntime( 2405): 	at com.android.server.enterprise.keystore.TimaKeystoreService.deletePackageRecord(TimaKeystoreService.java:348)
E/AndroidRuntime( 2405): 	at com.android.server.enterprise.keystore.TimaKeystoreService.access$300(TimaKeystoreService.java:72)
E/AndroidRuntime( 2405): 	at com.android.server.enterprise.keystore.TimaKeystoreService$KeystoreReceiver.onReceive(TimaKeystoreService.java:294)
E/AndroidRuntime( 2405): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:772)
E/AndroidRuntime( 2405): 	... 10 more
I/SELinux ( 7642): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7642):  
,D/TimaKeyStoreProvider( 7627): in addTimaSignatureService
,D/LocationManagerService( 2405): getProviders()=[passive]
,D/TimaKeyStoreProvider( 7627): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7627): Added TimaKesytore provider,
,I/SELinux ( 7642): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7642):  
I/SELinux ( 7642):  
,I/SELinux ( 7642): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7642): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7642): >>>>> Normal User
,E/dalvikvm( 7642): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ],
,E/SELinux ( 7642): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/TimaKeyStoreProvider( 7642): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7642): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7642): Added TimaKesytore provider,
,D/dalvikvm( 7627): GC_CONCURRENT freed 2997K, 30% free 9572K/13648K, paused 4ms+3ms, total 33ms,
,D/dalvikvm( 7627): WAIT_FOR_CONCURRENT_GC blocked 24ms,
,W/ContextImpl( 7627): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2698 
,E/SQLiteDatabase( 7627): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 7627): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7627): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7627): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7627): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7627): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7627): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7627): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7627): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7627): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7627): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7627): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7627): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7627): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7627): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7627): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/SQLiteDatabase( 7627): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/SQLiteDatabase( 7627): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7627): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7627): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7627): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7627): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,I/SELinux ( 7661): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7661):  
,E/AndroidRuntime( 7627): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 7627): Process: com.android.keychain, PID: 7627
E/AndroidRuntime( 7627): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7627): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7627): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7627): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7627): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7627): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7627): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7627): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7627): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7627): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7627): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7627): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7627): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7627): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7627): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/AndroidRuntime( 7627): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/AndroidRuntime( 7627): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7627): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7627): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7627): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/dalvikvm( 1921): GC_EXPLICIT freed 44K, 11% free 9503K/10624K, paused 4ms+4ms, total 37ms
,E/DropBoxManagerService( 2405): Can't write: system_app_crash
E/DropBoxManagerService( 2405): java.io.FileNotFoundException: /data/system/dropbox/drop242.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2405): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2405): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2405): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2405): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2405): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2405): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2405): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2405): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2405): 	... 5 more
,I/Process ( 7627): Sending signal. PID: 7627 SIG: 9
,I/SELinux ( 7661): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7661):  
I/SELinux ( 7661):  
,I/SELinux ( 7661): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7661): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7661): >>>>> Normal User
,E/dalvikvm( 7661): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10160 ]
,E/SELinux ( 7661): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9503K/10624K, paused 3ms+4ms, total 30ms
D/dalvikvm( 7642): GC_CONCURRENT freed 2995K, 30% free 9574K/13648K, paused 3ms+2ms, total 65ms
,D/dalvikvm( 7642): WAIT_FOR_CONCURRENT_GC blocked 54ms
I/ActivityManager( 2405): Process com.android.keychain (pid 7627) (adj 5) has died.
,D/TimaKeyStoreProvider( 7661): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7661): Cannot add TimaSignature Service, License check Failed
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9503K/10624K, paused 2ms+4ms, total 30ms
,D/ActivityThread( 7661): Added TimaKesytore provider
,I/ActivityManager( 2405): Killing 7001:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,D/dalvikvm( 7661): GC_CONCURRENT freed 2999K, 30% free 9573K/13652K, paused 4ms+2ms, total 29ms
,D/dalvikvm( 7661): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/KidsModeInstallReceiver( 7661): onReceive intent data =  package:com.test.thalitest
,E/SharedPreferencesImpl( 3148): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,D/KidsPlatformStub( 7661): Package not found : com.sec.android.app.kidshome,
,I/SELinux ( 7677): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7677):  
I/ActivityManager( 2405): Killing 7112:com.sec.android.provider.badge/u0a76 (adj 15): empty #43
,E/SharedPreferencesImpl( 3148): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,E/Icing   ( 3148): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,E/SharedPreferencesImpl( 3148): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,I/SELinux ( 7677): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7677):  
I/SELinux ( 7677):  
,I/SELinux ( 7677): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7677): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7677): >>>>> Normal User
,E/dalvikvm( 7677): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10164 ]
,E/SharedPreferencesImpl( 3148): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,E/SELinux ( 7677): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/Icing   ( 3148): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,E/SharedPreferencesImpl( 3148): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,D/TimaKeyStoreProvider( 7677): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7677): Cannot add TimaSignature Service, License check Failed
,E/SharedPreferencesImpl( 3148): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml.bak
,D/ActivityThread( 7677): Added TimaKesytore provider
,E/Icing   ( 3148): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,E/SQLiteDatabase( 7602): Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db'.
E/SQLiteDatabase( 7602): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7602): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7602): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7602): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7602): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7602): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7602): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7602): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7602): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7602): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7602): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7602): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7602): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7602): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7602): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.getWritableDatabase(InternalIcingCorporaProvider.java:500)
E/SQLiteDatabase( 7602): 	at com.google.android.gms.appdatasearch.util.AppDataSearchDbOpenHelperBase.cleanSequenceTable(AppDataSearchDbOpenHelperBase.java:348)
E/SQLiteDatabase( 7602): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.requestIndexingIfRequired(AppDataSearchProviderBase.java:321)
E/SQLiteDatabase( 7602): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:165)
E/SQLiteDatabase( 7602): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:156)
E/SQLiteDatabase( 7602): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.executeWithConnection(AppDataSearchProviderBase.java:295)
E/SQLiteDatabase( 7602): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider.registerCorpora(AppDataSearchProvider.java:171)
E/SQLiteDatabase( 7602): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.safeRegisterCorpora(InternalIcingCorporaProvider.java:376)
E/SQLiteDatabase( 7602): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.registerCorpora(InternalIcingCorporaProvider.java:330)
E/SQLiteDatabase( 7602): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:273)
E/SQLiteDatabase( 7602): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/SQLiteDatabase( 7602): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/SQLiteDatabase( 7602): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/SQLiteDatabase( 7602): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/SQLiteDatabase( 7602): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/SQLiteDatabase( 7602): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaPro
```
