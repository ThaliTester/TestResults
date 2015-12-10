#### Test 50650278c0f6ec2_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
--------- beginning of /dev/log/main
D/AndroidRuntime( 6985): 
D/AndroidRuntime( 6985): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6985): CheckJNI is OFF
D/AndroidRuntime( 6985): setted country_code = Poland
D/AndroidRuntime( 6985): setted countryiso_code = PL
D/AndroidRuntime( 6985): setted sales_code = PLS
D/AndroidRuntime( 6985): readGMSProperty: start
D/AndroidRuntime( 6985): readGMSProperty: already setted!!
D/AndroidRuntime( 6985): readGMSProperty: end
D/AndroidRuntime( 6985): addProductProperty: start
D/dalvikvm( 6985): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6985): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6985): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6985): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6985): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6985): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6985): failed to load memtrack module: -2
D/dalvikvm( 6985): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6985): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2418): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2418): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2418): mDVFSHelper.acquire()
I/SurfaceFlinger( 1920): id=19 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1920): id=20 createSurf (16x16),-1 flag=20004, EimLayer
I/SELinux ( 7013): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7013):  
D/PointerIcon( 2418): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2418): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2418): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2418): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6985): Shutting down VM
D/dalvikvm( 6985): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 7013): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7013):  
I/SELinux ( 7013):  
I/SELinux ( 7013): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7013): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7013): >>>>> Normal User
E/dalvikvm( 7013): >>>>> com.test.thalitest [ userId:0 | appId:10527 ]
E/SELinux ( 7013): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7013): in addTimaSignatureService
D/TimaKeyStoreProvider( 7013): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7013): Added TimaKesytore provider
V/WindowManager( 2418): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SQLiteSecureOpenHelper( 4127): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4127): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (8/10)
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (-2/10)
D/Launcher( 2774): onTrimMemory. Level: 20
D/dalvikvm( 7013): GC_CONCURRENT freed 3000K, 32% free 9569K/13992K, paused 2ms+1ms, total 19ms
D/dalvikvm( 7013): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7013): Binding Chromium to the background looper Looper (main, tid 1) {422ce358}
I/chromium( 7013): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7013): Initializing chromium process, renderers=0
W/chromium( 7013): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7013): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 7013): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7013): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7013): Mali API Version : 401
,I/Mali    ( 7013): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7013): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7013): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7013): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7013): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7013): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7013): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/StatusBarManagerService( 2418): tr p:7013,o:f
W/dalvikvm( 7013): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7013): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7013): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7013): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 7013): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7013): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7013): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7013): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7013): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7013): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7013): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7013): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7013): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2418): semi p:7013,o:f
,I/SurfaceFlinger( 1920): id=21 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2418): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2418): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2418): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2418): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2418): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2418): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7013): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7013): Enabling debug mode 0
,W/AwContents( 7013): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/AwContents( 7013): nativeOnDraw failed; clearing to background color.
D/CustomFrequencyManagerService( 2418): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2418): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2418): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  pkgName : ACTIVITY_RESUME_BOOSTER@8
W/IInputConnectionWrapper( 7013): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 7013): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7013): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422cf0e0
,D/dalvikvm( 7013): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422cf0e0
D/jxcore_app_log( 7013): JniHelper::setJavaVM(0x4172a220), pthread_self() = 2027481552
,D/JX-Cordova( 7013): jxcore cordova android initializing
I/dalvikvm( 7013): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 7013): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7013): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 7013): GC_CONCURRENT freed 1303K, 20% free 11339K/14060K, paused 2ms+2ms, total 22ms
,D/dalvikvm( 7013): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 7013): GC_CONCURRENT freed 1932K, 19% free 14926K/18296K, paused 2ms+2ms, total 39ms
,D/dalvikvm( 7013): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/CustomFrequencyManagerService( 2418): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7013): GC_FOR_ALLOC freed 5292K, 31% free 16202K/23184K, paused 50ms, total 59ms
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 7013): GC_CONCURRENT freed 6699K, 32% free 17668K/25812K, paused 2ms+15ms, total 78ms
,D/dalvikvm( 7013): WAIT_FOR_CONCURRENT_GC blocked 53ms
,D/dalvikvm( 7013): GC_FOR_ALLOC freed 1308K, 33% free 17411K/25812K, paused 50ms, total 50ms
,I/dalvikvm-heap( 7013): Grow heap (frag case) to 21.903MB for 3688532-byte allocation
,D/dalvikvm( 7013): GC_FOR_ALLOC freed 2434K, 37% free 18578K/29416K, paused 48ms, total 48ms
,W/jxcore-log( 7013): Initializing JXcore engine
,W/jxcore-log( 7013): JXcore engine is ready
,W/jxcore-log( 7013): Starting JXcore engine
,W/jxcore-log( 7013): Platform android
W/jxcore-log( 7013): 
,W/jxcore-log( 7013): Process ARCH arm
W/jxcore-log( 7013): 
,I/jxcore-log( 7013): JXcore Cordova bridge is ready!
I/jxcore-log( 7013): 
,W/jxcore-log( 7013): JXcore engine is started
,I/chromium( 7013): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7013): Toggling radios to true
I/jxcore-log( 7013): 
,W/ActivityManager( 2418): Permission Denial: getCurrentUser() from pid=7013, uid=10527 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 2418): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 2418): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7013, uid=10527 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 2418): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/BluetoothManagerService( 2418): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:620)
W/BluetoothManagerService( 2418): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService( 2418): 	at android.os.Binder.execTransact(Binder.java:404)
W/BluetoothManagerService( 2418): 	at dalvik.system.NativeStart.run(Native Method)
E/DevicePolicyManagerService( 2418): getAllowBluetoothMode - value retunrs : 2
,D/BluetoothManagerService( 2418): foregroundUser: 0
,E/BluetoothManagerService( 2418): Package is exist.
,I/WifiManager( 7013): packageName : com.test.thalitest
,I/WifiManager( 7013): setWifiEnabled : true
,I/WifiService( 2418): setWifiEnabled: true pid=7013, uid=10527
D/BluetoothAdapterState( 5076): CURRENT_STATE=OFF, MSG = USER_TURN_ON
,I/BluetoothAdapterState( 5076): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 5076): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5076): updateAdapterState state is 11
,D/BluetoothAdapterService( 5076): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 5076): Autoconnection is available 
D/BluetoothAdapterService( 5076): updateAdapterState prevState = 10newState = 11
,W/ActivityManager( 2418): Permission Denial: getCurrentUser() from pid=7013, uid=10527 requires android.permission.INTERACT_ACROSS_USERS
D/BtConfig.SecureMode( 5076): isSecureModeOn:false
D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/WifiService( 2418): Failed getting userId using ActivityManagerNative
W/WifiService( 2418): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7013, uid=10527 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2418): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2418): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2418): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2418): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2418): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2418): 	at dalvik.system.NativeStart.run(Native Method)
W/BluetoothAdapterService( 5076): isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/InputMethodManagerService( 2418): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 2418): [BT Setting State] State =11
I/SamsungIME( 2970): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
D/PhoneApp( 2751): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 11
I/QuickConnect[1.1][2] ( 5050): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_ON
W/BluetoothAdapterService( 5076): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
I/WifiService( 2418): disconnect: pid=7013, uid=10527
W/BluetoothAdapterService( 5076): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.android.bluetooth.hid.HidService
E/WifiHW  ( 2418): ##################### set firmware type 0 #####################
I/jxcore-log( 7013): Radios toggled
I/jxcore-log( 7013): 
W/BluetoothAdapterService( 5076): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
I/WifiHW  ( 1915): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
E/WifiHW  ( 1915): Cannot open "/data/.cid.info": No such file or directory
I/WifiHW  ( 1915): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
E/WifiHW  ( 1915): TEMP_FAILURE_RETRY complete
D/SoftapController( 1915): Softap fwReload - Ok
,W/BluetoothAdapterService( 5076): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 5076): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 5076): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5076): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5076): Unable to stop service com.android.bluetooth.gatt.GattService. Invalid state: 12
W/BluetoothAdapterService( 5076): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 5076): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/BluetoothNotiBroadcastReceiver( 5550): onReceive
D/CommandListener( 1915): Setting iface cfg
,D/CommandListener( 1915): Trying to bring down wlan0
,W/BluetoothAdapterService( 5076): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5076): Not skipping com.android.bluetooth.a2dp.A2dpService
,I/SELinux ( 7062): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7062):  
,D/QuickConnect[1.1][2] ( 5050): HeadsetProfile.onServiceConnected - Bluetooth service connected
W/BluetoothAdapterService( 5076): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5076): Not skipping com.android.bluetooth.hid.HidService
,D/HeadsetService( 5076): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 5076): classInitNative: succeeds
D/HeadsetStateMachine( 5076): Version 1.5
,D/HeadsetStateMachine( 5076): make
W/BluetoothAdapterService( 5076): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5076): Not skipping com.android.bluetooth.hdp.HealthService
,E/HeadsetStateMachine( 5076): # of Max HF connection is 2
W/BluetoothAdapterService( 5076): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5076): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5076): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5076): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5076): check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5076): Not skipping com.broadcom.bt.service.sap.SapService
I/SELinux ( 7062): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7062):  
I/SELinux ( 7062):  
,I/SELinux ( 7062): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7062): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7062): >>>>> Normal User
,E/dalvikvm( 7062): >>>>> pl.k2.droidoaudioteka [ userId:0 | appId:10066 ]
,E/SELinux ( 7062): [DEBUG] seapp_context_lookup: seinfoCategory = default
,I/BluetoothAdapterState( 5076): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid( 5076): get_profile_interface handsfree
,I/dalvikvm( 7062): Enabling JNI app bug workarounds for target SDK version 7...
D/WifiHW  ( 2418): Skip the update_ctrl_interface
,D/WifiHW  ( 2418): Skip the update_ctrl_interface
,E/WifiHW  ( 2418): supplicant_name : p2p_supplicant
,D/BluetoothAtMessage( 5076): createCMTIContentObservers
,D/HeadsetStateMachine( 5076): Enter Disconnected: -2
,E/HeadsetStateMachine( 5076): set to mRemoteBrsf = 0
,D/TimaKeyStoreProvider( 7062): in addTimaSignatureService
,D/HeadsetStateMachine( 5076): map size, before remove : 0
D/HeadsetStateMachine( 5076): map size, after remove: 0
,D/HeadsetStateMachine( 5076): mNextConnectingDevice : null
,D/BluetoothA2dp( 2418): Proxy object connected
,D/BluetoothA2dp( 5050): Proxy object connected
,D/BluetoothA2dp( 4127): Proxy object connected
,D/TimaKeyStoreProvider( 7062): Cannot add TimaSignature Service, License check Failed
,D/QuickConnect[1.1][2] ( 5050): A2dpProfile.onServiceConnected - Bluetooth service connected
,D/ActivityThread( 7062): Added TimaKesytore provider
D/A2dpService( 5076): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 5076): classInitNative: succeeds
,D/A2dpStateMachine( 5076): make
,I/bluedroid( 5076): get_profile_interface a2dp
,I/GKI_LINUX( 5076): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 5076): Enter Disconnected: -2
,I/wpa_supplicant( 7075): wpa_supplicant v2.1-devel-4.4.22014-07-16/12:43:14
,I/BluetoothAvrcpServiceJni( 5076): classInitNative: succeeds
,I/bluedroid( 5076): get_profile_interface avrcp
I/wpa_supplicant( 7075): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 7075): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 7075): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 7075): getIMSI cannot open file
,E/wpa_supplicant( 7075): Interworking config: - SIM READ ERROR
,D/MediaFocusControl( 2418): >>> registerRemoteControlDisplay
,I/BluetoothHidServiceJni( 5076): classInitNative: succeeds
,D/BluetoothInputDevice( 5050): Proxy object connected
,D/QuickConnect[1.1][2] ( 5050): HidProfile.onServiceConnected - Bluetooth service connected
,D/HidService( 5076): Received start request. Starting profile...
I/bluedroid( 5076): get_profile_interface hidhost
,D/HidService( 5076): setHidService(): set to: null
,I/BluetoothHealthServiceJni( 5076): classInitNative: succeeds
,D/HealthService( 5076): Received start request. Starting profile...
,I/bluedroid( 5076): get_profile_interface health
,I/BluetoothPanServiceJni( 5076): classInitNative(L105): succeeds
,D/WifiMonitor( 2418): startMonitoring(wlan0) with mConnected = false
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/BluetoothPan( 2418): BluetoothPAN Proxy object connected
D/PanService( 5076): Received start request. Starting profile...
D/BluetoothPanServiceJni( 5076): initializeNative(L110): pan
,I/bluedroid( 5076): get_profile_interface pan
,D/BluetoothTethering( 2418): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothMapService( 5076): Received start request. Starting profile...
,W/BluetoothMapMasInstance( 5076): mAccount : null
,D/dalvikvm( 7062): GC_CONCURRENT freed 2997K, 32% free 9566K/13984K, paused 13ms+4ms, total 52ms
D/dalvikvm( 7062): WAIT_FOR_CONCURRENT_GC blocked 30ms
,I/BluetoothSAPServiceJni( 5076): classInitNative(L204): succeeds
D/SapService( 5076): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 5076): initializeNative(L209): sap
,I/bluedroid( 5076): get_profile_interface sap
,D/HeadsetStateMachine( 5076): Try to query the phonestate on bind
D/BluetoothPhoneService( 2751): handleMessage: 4
,V/BluetoothPhoneService( 2751): Call state Converted2: IDLE/IDLE -> 6
W/BluetoothHeadset( 2751): Proxy not attached to service
,D/HeadsetStateMachine( 5076): Proxy object connected
,D/HeadsetPhoneState( 5076): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState( 5076): sendDeviceDataStateChanged
D/HeadsetPhoneState( 5076): Signal level : previous=0 curr=0
D/HeadsetStateMachine( 5076): Disconnected process message: 11
,D/HeadsetStateMachine( 5076): Disconnected process message: 20
V/HeadsetService( 5076): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothAdapterService( 5076): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5076): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5076): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5076): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5076): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/HeadsetStateMachine( 5076): Disconnected process message: 10
D/HeadsetPhoneState( 5076): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 5076): Disconnected process message: 11
,D/BluetoothAdapterService( 5076): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterState( 5076): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 5076): enable
,D/GKI_LINUX( 5076): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,E/bt-btif ( 5076): Calling BTA_HhEnable
,E/bt-btif ( 5076): btif_storage_get_adapter_property service_mask:0x160040
E/BluetoothServiceJni( 5076): populateRssiValuesNative
I/bluedroid( 5076): getModelRssiValues
,E/BluetoothServiceJni( 5076): model_rssi_values_callback: low = -75, mid = -65, high = 127
,I/wpa_supplicant( 7075): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 7075): getIMSI cannot open file
,E/wpa_supplicant( 7075): Interworking config: - SIM READ ERROR
,I/wpa_supplicant( 7075): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 7075): rfkill: Cannot open RFKILL control device
,E/BluetoothRemoteDevices( 5076): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BtConfig.SecureMode( 5076): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5076): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 241
,W/System.err( 7062): java.io.FileNotFoundException: /system/etc/vold.fstab: open failed: ENOENT (No such file or directory)
,W/System.err( 7062): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 7062): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 7062): 	at java.util.Scanner.<init>(Scanner.java:158)
,W/System.err( 7062): 	at java.util.Scanner.<init>(Scanner.java:138)
W/System.err( 7062): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.readVoldFile(StorageOptions.java:107)
W/System.err( 7062): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.determineStorageOptions(StorageOptions.java:31)
,E/BluetoothRemoteDevices( 5076): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 10
W/System.err( 7062): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:81)
W/System.err( 7062): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:129)
,W/System.err( 7062): 	at pl.k2.droidoaudioteka.ui.AudiotekaApplication.onCreate(AudiotekaApplication.java:171)
W/System.err( 7062): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 7062): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
,W/System.err( 7062): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7062): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
D/BtConfig.SecureMode( 5076): isSecureModeOn:false
W/System.err( 7062): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 7062): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 7062): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 7062): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 7062): 	at java.lang.reflect.Method.invoke(Method.java:515)
,E/BluetoothRemoteDevices( 5076): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 241
W/System.err( 7062): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 7062): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 7062): 	at dalvik.system.NativeStart.main(Native Method)
,W/System.err( 7062): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 7062): 	at libcore.io.Posix.open(Native Method)
W/System.err( 7062): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/BluetoothRemoteDevices( 5076): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,W/System.err( 7062): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 7062): 	... 20 more
,D/BtConfig.SecureMode( 5076): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5076): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 241
,W/System.err( 7062): file res dir: /data/data/pl.k2.droidoaudioteka/files
,W/System.err( 7062): Excternal dir: /mnt/sdcard
,E/BluetoothRemoteDevices( 5076): devicePropertyChangedCallback: bdDevice: F8:CF:C5:D9:E5:61, value is empty for type: 10
,D/BtConfig.SecureMode( 5076): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5076): devicePropertyChangedCallback: bdDevice: F8:CF:C5:D9:E5:61, value is empty for type: 241
,E/BluetoothRemoteDevices( 5076): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
D/BtConfig.SecureMode( 5076): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5076): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 241
,E/BluetoothRemoteDevices( 5076): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,D/BtConfig.SecureMode( 5076): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5076): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 241
,E/BluetoothRemoteDevices( 5076): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,D/BtConfig.SecureMode( 5076): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5076): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 241
,E/BluetoothRemoteDevices( 5076): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/BtConfig.SecureMode( 5076): isSecureModeOn:false
E/BluetoothRemoteDevices( 5076): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 241
E/bt-btif ( 5076): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 5076): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
E/bt-btif ( 5076): btif_sock_init: !radio_req && !rfc_init
,D/IOP_DB_BT( 5076): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT( 5076): db_open: db_open : handle 2010096684l, read 9734 bytes onto local cache
D/IOP_DB_BT( 5076): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,D/IOP_DB_BT( 5076): db_query: result 1
I/        ( 5076): iop_db_open: iop_db_open status 0
I/bte_conf( 5076): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 5076): [1] primary_record=1 vendor_id=0x0075 vendor_id_source=0x0001 product_id=0x0100 version=0x0200
I/bte_conf( 5076): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 5076): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothAdapterState( 5076): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5076): ScanMode =  20
,D/BluetoothAdapterProperties( 5076): State =  11
,D/BtConfig.SecureMode( 5076): isSecureModeOn:false
D/BtConfig.SecureMode( 5076): isSecureModeOn:false
D/BtConfig.SecureMode( 5076): isSecureModeOn:false
D/BtConfig.SecureMode( 5076): isSecureModeOn:false
,D/BtConfig.SecureMode( 5076): isSecureModeOn:false
D/BtConfig.SecureMode( 5076): isSecureModeOn:false
D/BtConfig.SecureMode( 5076): isSecureModeOn:false
D/BtConfig.SecureMode( 5076): isSecureModeOn:false
I/BluetoothAdapterState( 5076): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 5076): Bluetooth PBAP supproted is true
V/MaBo    ( 7062): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
D/BluetoothAdapterService( 5076): updateAdapterState state is 12
D/BluetoothAdapterService( 5076): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService(1110312368)( 5076): Register RemoteMessageListener
D/BluetoothA2dp( 4127): onBluetoothStateChange: up=true
D/HeadsetService( 5076): registerMessageListener
D/HeadsetStateMachine( 5076): Disconnected process message: 70
D/HeadsetStateMachine( 5076): processRegisterMessageListener : 2, com.android.bluetooth.btservice.RemoteDevices$1@423397f8
D/BluetoothInputDevice( 5050): onBluetoothStateChange: up=true
D/BluetoothAdapterService( 5076): Autoconnection is available 
D/BluetoothAdapterService( 5076): updateAdapterState prevState = 11newState = 12
D/BluetoothA2dp( 5050): onBluetoothStateChange: up=true
D/BluetoothAdapterService( 5076): starting service from this receiver
D/BluetoothA2dp( 2418): onBluetoothStateChange: up=true
D/BluetoothAdapterService( 5076): initWakeLock, pfd lock: {ParcelFileDescriptor: FileDescriptor[85]}, pfd unlock: {ParcelFileDescriptor: FileDescriptor[86]}
D/bluedroid( 5076): init_wake_lock lock_fd:85, unlock_fd:86
W/InputMethodManagerService( 2418): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2418): [BT Setting State] State =12
,W/ContextImpl( 5076): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.startService:506 com.android.bluetooth.btservice.AdapterService.updateAdapterState:653 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
,I/InputMethodManagerService( 2418): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
I/BluetoothPbapService( 5076): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
I/BluetoothPbapService( 5076): Handler(): got msg=1
D/BluetoothAdapterService(1110312368)( 5076): Get Bonded Devices being called
D/PhoneApp( 2751): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 12
V/BluetoothPbapService( 5076): PBAP Service initSocket try: 0
I/QuickConnect[1.1][2] ( 5050): BluetoothHelper.ACTION_STATE_CHANGED - STATE_ON
I/SamsungIME( 2970): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothHeadset( 2751): registerListener : 11, listenercom.android.phone.PhoneGlobals$MessageListener@424e6c48, true
D/BluetoothPanServiceJni( 5076): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
D/BluetoothHeadset( 2751): registerMessageListener
I/BluetoothAdapterState( 5076): Entering On State from state = 11
,D/HeadsetService( 5076): registerMessageListener
,D/HeadsetService( 5076): registerMessageListener
D/HeadsetStateMachine( 5076): Disconnected process message: 70
D/HeadsetStateMachine( 5076): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@423ae650
D/PhoneApp( 2751): registerMessageListener
D/BluetoothMapMasInstance( 5076): set MAP SDP message type : 1
W/BluetoothAdapter( 5076): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 5076): SOCK FLAG = 1 ***********************
,W/BluetoothAdapter( 5076): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothPbapService( 5076): PBAP Socket is BluetoothServerSocket
,E/BluetoothServiceJni( 5076): SOCK FLAG = 3 ***********************
,I/System.out( 7062): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 7062): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 7062): moge zapisać w resDir?true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(336), More:false, Req:false Child:2
,V/MaBo    ( 7062): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 7062): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 7062): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,D/GKI_LINUX( 5076): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,W/GAV2    ( 7062): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/GAV2    ( 7062): Thread[main,5,main]: ExceptionReporter created, original handler is pl.k2.droidoaudioteka.common.helpers.AudiotekaExceptionHandler
,I/AUDIOTEKA_GA( 7062): init tracking...
,I/AUDIOTEKA_GA( 7062): app started!
,I/BugSenseHandler( 7062): Registering default exceptions handler
,D/AuthorizationBluetoothService( 2845): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/knox    ( 4990): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,I/DownloadService( 7062): Tworzenie serwisu - onCreate()
,I/DownloadService( 7062): Start serwisu - onStart()
,I/BugSenseHandler( 7062): Registering default exceptions handler
W/ContextImpl( 4990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/BugSenseHandler( 7062): Flushing...
,I/knox    ( 4990): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 4990): KNOXAgentService : onCreate()
,D/knox    ( 4990): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 4990): KNOXAgentService. startJobThread() start
D/knox    ( 4990): KNOXAgentService. JobThread()
D/knox    ( 4990): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 4990): KNOXAgentService. startJobThread() wait
,I/BugSenseHandler( 7062): Registering default exceptions handler
,I/SELinux ( 7103): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7103):  
,D/knox    ( 4990): KNOXAgentService : onDestroy().
,D/knox    ( 4990): ModuleBase.cancelAllAlarmManageModule()
,I/PlayerService( 7062): Tworzenie serwisu - onCreate()
,I/MediaFocusControl( 2418):   Remote Control   registerMediaButtonIntent() for PendingIntent{42ac27f8: PendingIntentRecord{42912b48 pl.k2.droidoaudioteka broadcastIntent}}
I/BugSenseHandler( 7062): Flushing...
,I/BugSenseHandler( 7062): Registering default exceptions handler
,V/AUDIOTEKA_MB( 7062): new AudioManagerFocusWrapper in playerservice oncreate
,I/SELinux ( 7103): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7103):  
I/SELinux ( 7103):  
,I/SELinux ( 7103): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7103): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/KeyguardUpdateMonitor( 2578): handleSetGenerationId(g=2, clear=true)
E/dalvikvm( 7103): >>>>> Normal User
,E/dalvikvm( 7103): >>>>> tv.peel.smartremote [ userId:0 | appId:10165 ]
,I/PlayerService( 7062): Start serwisu - onStart()
,E/SELinux ( 7103): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7103): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7103): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7103): Added TimaKesytore provider
,D/dalvikvm( 7103): GC_CONCURRENT freed 3001K, 32% free 9566K/13988K, paused 2ms+2ms, total 34ms
,D/dalvikvm( 7103): WAIT_FOR_CONCURRENT_GC blocked 28ms
,I/System.out( 7062): Thread-612(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 7062): Thread-612(ApacheHTTPLog):isShipBuild true
I/System.out( 7062): Thread-612(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 7062): Thread-609(ApacheHTTPLog):isShipBuild true
I/System.out( 7062): Thread-609(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 7062): pool-1-thread-1 calls detatch()
W/BugSenseHandler( 7062): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
I/System.out( 7062): pool-1-thread-2 calls detatch()
W/BugSenseHandler( 7062): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
W/ContextImpl( 5550): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/LocalBluetoothProfileManager( 5550): Adding local A2DP profile
D/AmoledAdjustTimer( 2418): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4
I/System.out( 7062): pool-1-thread-1 calls detatch()
W/BugSenseHandler( 7062): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
W/ContextImpl( 5550): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
D/LocalBluetoothProfileManager( 5550): Adding local HEADSET profile
E/BluetoothHeadset( 5550): BTStateChangeCB is registed
W/ContextImpl( 5550): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
E/BluetoothHeadset( 5550): BluetoothHeadset service is binded
I/System.out( 7062): pool-1-thread-2 calls detatch()
W/BugSenseHandler( 7062): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
W/ContextImpl( 5550): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/Bluetoothsap( 5550): bindService called to Bluetooth SAP Service
W/ContextImpl( 5550): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
D/LocalBluetoothProfileManager( 5550): PANU : true
W/ContextImpl( 5550): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
D/LocalBluetoothProfileManager( 5550): Adding local MAP profile
D/BluetoothMap( 5550): Create BluetoothMap proxy object
W/ContextImpl( 5550): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
W/ContextImpl( 5550): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
W/ContextImpl( 5550): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/Bluetoothsap( 5550): bindService called to Bluetooth SAP Service
D/LocalBluetoothProfileManager( 5550): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 5550): finishStartingService: stopping service
D/BluetoothNotiBroadcastReceiver( 5550): onReceive
D/BluetoothA2dp( 5550): Proxy object connected
D/A2dpProfile( 5550): Bluetooth service connected
D/HeadsetProfile( 5550): Bluetooth service connected
D/BtConfig.SecureMode( 5076): isSecureModeOn:false
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
D/Tethering( 2418): interfaceStatusChanged wlan0, true
E/Tethering( 2418): No numeric data
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
I/ConnectivityService( 2418): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering( 2418): interfaceStatusChanged wlan0, true
D/Tethering( 2418): sendTetherStateChangedBroadcast 1, 0, 0
D/Bluetoothsap( 5550): BluetoothSAP Proxy object connected
D/NtpTrustedTime( 2418): forceRefresh() from cache miss
D/SapProfile( 5550): Bluetooth service connected
D/Bluetoothsap( 5550): getConnectedDevices()
D/NtpTrustedTime( 2418): forceRefresh Fail.
V/NetworkStats( 2418): performPollLocked(flags=0x1)
D/BluetoothInputDevice( 5550): Proxy object connected
D/AuthorizationBluetoothService( 2845): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/AuthorizationBluetoothService( 2845): Proximity feature is not enabled.
I/wpa_supplicant( 7075): wlan0: Setting scan request: 0 sec 100000 usec
D/HidProfile( 5550): Bluetooth service connected
D/BluetoothPan( 5550): BluetoothPAN Proxy object connected
D/NtpTrustedTime( 2418): forceRefresh() from cache miss
D/NtpTrustedTime( 2418): forceRefresh Fail.
D/PanProfile( 5550): Bluetooth service connected
V/NetworkStats( 2418): performPollLocked() took 18ms
D/BluetoothMap( 5550): Proxy object connected
D/MapProfile( 5550): Bluetooth service connected
D/BluetoothPbap( 5550): Proxy object connected
D/PbapServerProfile( 5550): Bluetooth service connected
D/Bluetoothsap( 5550): BluetoothSAP Proxy object connected
D/SapProfile( 5550): Bluetooth service connected
D/Bluetoothsap( 5550): getConnectedDevices()
I/ActivityManager( 2418): Killing 5877:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
I/wpa_supplicant( 7075): >>>>> Not GET KEY, IV <<<<<
I/wpa_supplicant( 7075): >>>>> Not GET KEY, IV <<<<<
I/wpa_supplicant( 7075): rfkill: Cannot open RFKILL control device
D/Tethering( 2418): interfaceLinkStateChanged p2p0, true
D/Tethering( 2418): interfaceStatusChanged p2p0, true
D/Tethering( 2418): interfaceLinkStateChanged p2p0, true
D/Tethering( 2418): interfaceStatusChanged p2p0, true
W/BluetoothAdapter( 5076): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 5076): SOCK FLAG = 0 ***********************
D/GKI_LINUX( 5076): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
I/BtOppRfcommListener( 5076): Accept thread started.
I/wpa_supplicant( 7075): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
I/wpa_supplicant( 7075): P2P: initialized channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
I/wpa_supplicant( 7075): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant( 7075): Skip scan - bUseNetwork false
D/WifiStateMachine( 2418): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
D/WifiNative( 2418): callSECApiString - ID [21]
I/wpa_supplicant( 7075): HOTSPOT20_ENABLE called
I/wpa_supplicant( 7075): wlan0: HS20_DISABLED_COMPLETE normal
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
D/WifiNative( 2418): callSECApiInt - ID [65]
I/knox    ( 4990): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/GKI_LINUX( 5076): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
W/ContextImpl( 4990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/knox    ( 4990): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 4990): KNOXAgentService : onCreate()
D/knox    ( 4990): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 4990): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
D/knox    ( 4990): KNOXAgentService. startJobThread() start
D/knox    ( 4990): KNOXAgentService. JobThread()
D/knox    ( 4990): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 4990): KNOXAgentService. startJobThread() wait
D/knox    ( 4990): KNOXAgentService : onDestroy().
D/knox    ( 4990): ModuleBase.cancelAllAlarmManageModule()
E/WifiConfigStore( 2418): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative( 2418): callSECApiBoolean - ID [13]
I/wpa_supplicant( 7075): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 7075): reset timer : RESET_TIMER 0
I/wpa_supplicant( 7075): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 7075): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 7075): First Scan Start
W/Settings( 5327): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 7075): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine( 2418): Set the Nv default ccode
D/WifiP2pService( 2418): P2pDisabledState{ what=131203 }
D/WifiStateMachine( 2418): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
E/WifiStateMachine( 2418): HS20_DISABLED_COMPLETEnormal
D/CommandListener( 1915): Setting iface cfg
D/CommandListener( 1915): Trying to bring up p2p0
I/wpa_supplicant( 7075): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
D/WifiMonitor( 2418): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 2418): P2pEnablingState
D/WifiP2pService( 2418): P2pEnablingState{ what=147457 }
D/WifiP2pService( 2418): P2p socket connection successful
E/WifiStateMachine( 2418): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiP2pService( 2418): P2pEnabledState
D/QuickConnect[1.1][2] ( 5050): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
D/WifiDisplayController( 2418): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiP2pService( 2418): sending p2p connection changed broadcast: IDLE
D/WifiDisplayController( 2418): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 2418): disconnect
D/WifiDisplayController( 2418): updateConnection
D/WifiDisplayController( 2418): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 2418): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/QuickConnect[1.1][2] ( 5050): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
D/WifiDisplayAdapter( 2418): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/QuickConnect[1.1][2] ( 5050): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
D/WifiDisplayController( 2418): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
W/WifiP2pStateTracker( 2418): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/QuickConnect[1.1][2] ( 5050): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
D/WifiP2pService( 2418): DeviceAddress: 02:e0:6d
D/WifiDisplayController( 2418): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: S5mini-1
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
D/NearbySettings( 5550): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 5550): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 5550): MountReceiver.onReceive - Create mPrefHandler
D/NearbySettings( 5550): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/NearbySettings( 5550): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 5550): DMSUtil.isNetworkConnected - WIFI: IDLE
I/NearbySettings( 5550): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5550): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 5550): MountReceiver.onReceive - Set preference state off
D/WifiP2pService( 2418): sending p2p persistent groups changed broadcast
V/NearbySettings( 5550): MountReceiver.mPrefHandler - 7002
D/QuickConnect[1.1][2] ( 5050): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/WifiP2pService( 2418): InactiveState
D/WifiP2pService( 2418): InactiveState{ what=139287 }
D/WifiP2pService( 2418): P2pEnabledState{ what=139287 }
D/WifiP2pService( 2418): DefaultState{ what=139287 }
D/FileShare-Server( 5942): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/FileShare-Server( 5942): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,I/wpa_supplicant( 7075): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,I/wpa_supplicant( 7075): nl80211: Received scan results (5 BSSes)
,I/wpa_supplicant( 7075): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 7075): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 7075): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 7075): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,E/WifiStateMachine( 2418): Error! unhandled message{ when=-5ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 7075): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 7075): Associated with C0.AA.48
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 7075): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 7075): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 7075): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 7075): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 7075): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
,D/WifiNative( 2418): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7139): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7139):  
,I/SELinux ( 7139): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7139):  
I/SELinux ( 7139):  
,I/SELinux ( 7139): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7139): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 14% free 9502K/10968K, paused 3ms+6ms, total 41ms
E/dalvikvm( 7139): >>>>> Normal User
,E/dalvikvm( 7139): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/SELinux ( 7139): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7139): in addTimaSignatureService
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 14% free 9502K/10968K, paused 3ms+4ms, total 29ms
,D/TimaKeyStoreProvider( 7139): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7139): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 14% free 9502K/10968K, paused 2ms+3ms, total 25ms
,D/dalvikvm( 7139): GC_CONCURRENT freed 2998K, 32% free 9573K/13992K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 7139): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/WifiP2pService( 2418): InactiveState{ what=143375 }
,D/WifiP2pService( 2418): P2pEnabledState{ what=143375 }
,I/System.out( 7139): Inside WakeupProvider
,I/System.out( 7139): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 7139): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7139): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7139): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,I/dhcpcd  ( 7154): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7154): bssid match
,D/NearbySettings( 5550): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5550): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5550): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 5550): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5550): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5550): MountReceiver.onReceive - Set preference state off
,D/DialogFlow( 7139): initQueue()
,V/NearbySettings( 5550): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2418): Killing 5614:com.google.android.music:main/u0a125 (adj 15): empty #43
,D/WifiP2pService( 2418): InactiveState{ what=143375 }
,D/WifiP2pService( 2418): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2418): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2418): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2418): CaptivePortalCheckState enter
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2418): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2418): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2418): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
D/ConnectivityService( 2418): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2418): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2418): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/NearbySettings( 5550): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
D/ConnectivityService( 2418): handleConnectivityChange: setting default proxy info 
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,I/NearbySettings( 5550): MountReceiver.onReceive - Keep current state
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,D/NearbySettings( 5550): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/NearbySettings( 5550): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5550): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 5550): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5550): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5550): MountReceiver.onReceive - Keep current state
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/NtpTrustedTime( 2418): forceRefresh() from cache miss
V/NetworkStats( 2418): updateIfacesLocked()
V/NetworkStats( 2418): performPollLocked(flags=0x1)
,V/NetworkStats( 2418): performPollLocked() took 18ms
,D/NearbySettings( 5550): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 5550): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger( 1920): id=22 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 2418): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2418
,D/NtpTrustedTime( 2418): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1449748855950 mCachedNtpElapsedRealtime : 334296 mCachedNtpCertainty : 11
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
V/NetworkStats( 2418): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/Tethering( 2418): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2418): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2418): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
D/        ( 2418): Setting time of day to sec=1449748856
,D/        ( 2418): Trying to open a file
D/        ( 2418): File Open Success
D/        ( 2418): File Close Success
,I/        ( 2418): DRM_TIME_PATH CHMOD 660 for resetState done 
D/STATUSBAR-NetworkController( 2578): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2578): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2578): updateDataNetType()
D/STATUSBAR-NetworkController( 2578): NoService, mRoamingIconId = 0
V/AlarmManager( 2418): waitForAlarm result :65536
,I/DBG_DM  ( 4647): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/PCWCLIENTTRACE_PushUtil( 6171): SPPPushClient is installed : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,I/PCWCLIENTTRACE_PushUtil( 6171): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 6171): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6171): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
D/StatusBar-DoNotDistrub( 2578): Received intent with android.intent.action.TIME_SET action
D/NotificationMgr( 2751): updateNotificationsAtStartup()...
,D/NotificationMgr( 2751): - start call log query...
D/StatusBar-DoNotDistrub( 2578): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Settings( 2418): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/AudioService( 2418): getStreamVolume 5 index 110
D/StatusBar-DoNotDistrub( 2578): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,E/Parcel  ( 2418): nm 23
D/StatusBar-DoNotDistrub( 2578): The STREAM NOTIFICATION volume is 0
D/STATUSBAR-StatusBarManagerService( 2418): manageDisableList what=0x0 pkg=com.android.systemui
,I/PrGenericPlugin( 1923): [A] ENTER onAcquireDrmInfo : 0x939
,I/PrGenericPlugin( 1923): [A] LEAVE onAcquireDrmInfo : 0x939
,I/DrmEventService( 2418):  no response from SecureClock 
,I/SensorManagerA( 2418): getReportingMode :: sensor.mType = 5
D/STATUSBAR-NotificationService( 2418): received android.intent.action.DORMANT_MODE_OFF
D/LightsService( 2418): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2418) 
,D/LightsService( 2418): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/Sensors ( 2418): LightSensor setDelay = 200000000
D/Sensors ( 2418): LightSensor setSensorDelay = 200000000
D/Sensors ( 2418): Light sensor flush: not enabled 0
D/Sensors ( 2418): LightSensor enable = 1
D/Sensors ( 2418): LightSensor enableSensor = 1
D/SensorManager( 2418): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/NotificationMgr( 2751): call log query complete.
,D/NotificationMgr( 2751): call log cursor count : 0
,D/NotificationMgr( 2751): call log cursor count2 : null
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:2
,I/DBG_DM  ( 4647): [3.19.140541][Line:609][onReceive] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_DM  ( 4647): [3.19.140541][Line:214][xdmAgentTaskHandler] XEVENT_DM_INIT
,I/DBG_DM  ( 4647): [3.19.140541][Line:432][xdmInitAdpWaitSystemRootingCheck] Check completed.
,I/DBG_DM  ( 4647): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/DBG_DM  ( 4647): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 4647): [3.19.140541][Line:78][xdmFeatureGetBearerSettingFromCSCFotaDataBase] 
,I/SQLiteSecureOpenHelper( 4127): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4127): getDatabaseLocked(b,b,pwd)...
,I/SELinux ( 7205): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7205):  
,I/SELinux ( 7205): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7205):  
I/SELinux ( 7205):  
,I/SELinux ( 7205): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7205): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7205): >>>>> Normal User
,E/dalvikvm( 7205): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
,E/SELinux ( 7205): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7205): in addTimaSignatureService
,D/Sensors ( 2418): LightSensor enable = 0
,D/Sensors ( 2418): LightSensor enableSensor = 0
,D/SensorManager( 2418): unregisterListener ::   
D/LightsService( 2418): [SvcLED]  onSensorChanged::light value = 13
,D/LightsService( 2418): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/TimaKeyStoreProvider( 7205): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7205): Added TimaKesytore provider
,I/DBG_DM  ( 4647): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/DBG_DM  ( 4647): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,D/PackageManager( 2418): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/dalvikvm( 4647): Total arena pages for JIT: 11
,I/dalvikvm( 4647): Total arena pages for JIT: 12
I/dalvikvm( 4647): Total arena pages for JIT: 13
,I/dalvikvm( 4647): Total arena pages for JIT: 14
I/dalvikvm( 4647): Total arena pages for JIT: 15
I/dalvikvm( 4647): Total arena pages for JIT: 16
,I/dalvikvm( 4647): Total arena pages for JIT: 17
,I/DBG_DM  ( 4647): [3.19.140541][Line:5949][xdbGetFUMOInitiatedType] Initiated Type: 2
,I/DBG_DM  ( 4647): [3.19.140541][Line:119][xdmInitAdpEXTInit] nStatus [220]
,I/DBG_DM  ( 4647): [3.19.140541][Line:463][xdmGetEnableLiveDemoFromCSCFeature] enable LiveDemo : false
,E/DBG_DM  ( 4647): Warning!!! [3.19.140541][Line:65][xdmInitAdpGetSIMLockState] SIM Status is not ready
,D/dalvikvm( 7205): GC_CONCURRENT freed 3000K, 32% free 9560K/13984K, paused 2ms+17ms, total 66ms
,D/dalvikvm( 7205): WAIT_FOR_CONCURRENT_GC blocked 58ms
,I/SQLiteSecureOpenHelper( 4127): getWritableDatabase(pwd)
,I/GAV2    ( 7062): Thread[GAThread,5,main]: connecting to Analytics service
I/SQLiteSecureOpenHelper( 4127): getDatabaseLocked(b,b,pwd)...
,W/ContextImpl( 7062): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:529 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/DBG_DM  ( 4647): [3.19.140541][Line:261][xdmInitAdpEXTInit] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 4647): [3.19.140541][Line:271][xdmAgentTaskHandler] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 4647): [3.19.140541][Line:1854][xdmAgentCheckResumeNoti] 
,I/DBG_DM  ( 4647): [3.19.140541][Line:769][xdmUIEvent] XUI_DL_UPDATE_START
,I/DBG_DM  ( 4647): [3.19.140541][Line:369][handleMessage] event ->214
,I/DBG_DM  ( 4647): [3.19.140541][Line:318][xdmBroadcastGetIsSavedNfcMode] m_IsSavedNfcMode : false
,I/DBG_DM  ( 4647): [3.19.140541][Line:546][xuiAdpGetUpdateReport] Get bUpdateReport = false
,I/GAV2    ( 7062): Thread[GAThread,5,main]: connect: bindService returned true for Intent { act=com.google.android.gms.analytics.service.START (has extras) }
,I/DBG_DM  ( 4647): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 4647): [3.19.140541][Line:2008][xdmCallUiFotaInstall] 
,I/SELinux ( 7222): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7222):  
,D/GAV2    ( 7062): Thread[main,5,main]: service connected, binder: android.os.BinderProxy@425408a8,
D/GAV2    ( 7062): Thread[main,5,main]: bound to service
,I/DBG_DM  ( 4647): [3.19.140541][Line:729][xdmUIEvent] XUI_DL_UPDATE_CONFIRM,
,I/GAV2    ( 7062): Thread[main,5,main]: Connected to service,
,I/GAV2    ( 7062): Thread[GAThread,5,main]: No campaign data found.,
W/ContextImpl( 4647): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 com.wssyncmldm.XDMService.xdmCallUiFotaInstall:2023 com.wssyncmldm.XDMService$1.handleMessage:372 android.os.Handler.dispatchMessage:102 
,I/DBG_DM  ( 4647): [3.19.140541][Line:1320][xdmCheckIdleScreen] Idle Screen : false
,I/DBG_DM  ( 4647): [3.19.140541][Line:890][xdmUnRegisterBatteryReceiver] 
,E/DBG_DM  ( 4647): Warning!!! [3.19.140541][Line:898][xdmUnRegisterBatteryReceiver] didn't register
,E/DBG_DM  ( 4647): Warning!!! [3.19.140541][Line:899][xdmUnRegisterBatteryReceiver] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.XDMService$3@423dc5e8
I/SELinux ( 7222): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7222):  
I/SELinux ( 7222):  
,I/SELinux ( 7222): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7222): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7222): >>>>> Normal User
,E/dalvikvm( 7222): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7222): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/GAV2    ( 7062): Thread[GAThread,5,main]: putHit called
,I/GAV2    ( 7062): Thread[GAThread,5,main]: Sending hit to service
,I/dalvikvm( 4647): Total arena pages for JIT: 18
,D/TimaKeyStoreProvider( 7222): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7222): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7222): Added TimaKesytore provider
,I/DBG_DM  ( 4647): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,D/dalvikvm( 2845): GC_CONCURRENT freed 1835K, 24% free 10845K/14168K, paused 6ms+10ms, total 136ms
,I/DBG_DM  ( 4647): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2418): sendNotification(1) - 4
,W/ResourceType( 2578): Attempt to retrieve bag 0x01030068 which is invalid or in a cycle.
,W/ResourceType( 2578): Attempt to retrieve bag 0x01030067 which is invalid or in a cycle.
,D/ProgressBar( 2578): setProgressDrawable drawableHeight = 12
,D/ProgressBar( 2578): setProgressDrawable drawableHeight = 12
,D/PhoneStatusBar( 2578): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@42317638
,E/dalvikvm( 7205): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a
W/dalvikvm( 7205): VFY: unable to resolve new-instance 406 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm( 7205): VFY: replacing opcode 0x22 at 0x0000
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
D/dalvikvm( 2418): GC_EXPLICIT freed 2671K, 55% free 24496K/54232K, paused 15ms+18ms, total 240ms
,W/dalvikvm( 7205): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 7205): Link of class 'Lal;' failed
E/dalvikvm( 7205): Could not find class 'al', referenced from method b.a
W/dalvikvm( 7205): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
,D/dalvikvm( 7205): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 7205): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 7205): Link of class 'Lan;' failed
E/dalvikvm( 7205): Could not find class 'an', referenced from method b.a
W/dalvikvm( 7205): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
,D/dalvikvm( 7205): VFY: replacing opcode 0x22 at 0x002a
I/dalvikvm( 7205): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm( 7205): VFY: unable to resolve virtual method 5407: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 7205): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 7205): Could not find method android.view.View.getTransitionName, referenced from method b.a
W/dalvikvm( 7205): VFY: unable to resolve virtual method 5231: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7205): VFY: replacing opcode 0x6e at 0x0006
,W/dalvikvm( 7205): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 7205): Could not find class 'android.app.RemoteInput[]', referenced from method b.a
W/dalvikvm( 7205): VFY: unable to resolve new-array 12200 ([Landroid/app/RemoteInput;) in Lb;
,D/dalvikvm( 7205): VFY: replacing opcode 0x23 at 0x0005
,D/dalvikvm( 7205): DexOpt: unable to opt direct call 0x090f at 0x0e in Lb;.a
D/dalvikvm( 7222): GC_CONCURRENT freed 2994K, 32% free 9576K/13992K, paused 4ms+7ms, total 32ms
,D/dalvikvm( 7222): WAIT_FOR_CONCURRENT_GC blocked 23ms
W/dalvikvm( 7205): Unable to resolve superclass of Lal; (749)
,W/dalvikvm( 7205): Link of class 'Lal;' failed
D/dalvikvm( 7205): DexOpt: unable to opt direct call 0x068d at 0x08 in Lb;.a
,W/dalvikvm( 7205): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 7205): Link of class 'Lan;' failed
,D/dalvikvm( 7205): DexOpt: unable to opt direct call 0x0802 at 0x2c in Lb;.a
,D/dalvikvm( 7205): DexOpt: unable to opt direct call 0x0957 at 0x13 in Lb;.a
,I/dalvikvm( 7205): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method dyp.a
,W/dalvikvm( 7205): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7205): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 7205): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 7205): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7205): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7205): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7205): VFY: unable to resolve instance field 36
,D/dalvikvm( 7205): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 7205): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 7205): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7205): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 7205): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 7205): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 7205): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42389a98
,D/dalvikvm( 7205): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42389a98
,D/dalvikvm( 7205): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42389a98, skipping init
,D/dalvikvm( 7205): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42389a98
,D/dalvikvm( 7205): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42389a98
,V/JNIHelp ( 7205): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 7205): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42389a98
,D/dalvikvm( 7205): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x42389a98
D/dalvikvm( 7205): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42389a98
,D/dalvikvm( 7205): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42389a98
,I/SELinux ( 7247): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7247):  
,I/SELinux ( 7247): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7247):  
I/SELinux ( 7247):  
,I/SELinux ( 7247): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7247): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7247): >>>>> Normal User
,E/dalvikvm( 7247): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7247): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/btif_config_util( 5076): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/TimaKeyStoreProvider( 7247): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7247): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7247): Added TimaKesytore provider
,I/dalvikvm( 7205): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
,W/dalvikvm( 7205): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7205): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 7247): GC_CONCURRENT freed 2997K, 32% free 9565K/13988K, paused 6ms+1ms, total 29ms
,D/dalvikvm( 7247): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/ProviderInstaller( 7205): Installed default security provider GmsCore_OpenSSL
,D/KLMS-2.3.201 : ( 7247): KLMSValidator() : checkQATesting()
,I/dalvikvm( 7205): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
,W/dalvikvm( 7205): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 7205): VFY: replacing opcode 0x71 at 0x004e
,E/YouTube MDX( 7205): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/dalvikvm( 7205): DexOpt: --- BEGIN 'ads901222981.jar' (bootstrap=0) ---
,I/KLMS-2.3.201 : ( 7247): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449748857892
,I/KLMS-2.3.201 : ( 7247): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 7205): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/SELinux ( 7285): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7285):  
,I/LocationTagReadyService( 3466): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
,I/SELinux ( 7285): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7285):  
I/SELinux ( 7285):  
,I/SELinux ( 7285): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7285): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7285): >>>>> Normal User
,E/dalvikvm( 7285): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7285): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/GallerySearchProvider( 3593): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,D/TimaKeyStoreProvider( 7285): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7285): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7285): Added TimaKesytore provider
,D/dalvikvm( 7277): DexOpt: load 4ms, verify+opt 15ms, 194052 bytes
D/dalvikvm( 7205): GC_CONCURRENT freed 1865K, 24% free 10769K/14052K, paused 6ms+5ms, total 106ms
,D/dalvikvm( 7205): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 7205): DexOpt: --- END 'ads901222981.jar' (success) ---
,D/dalvikvm( 7205): DEX prep '/data/data/com.google.android.youtube/cache/ads901222981.jar': unzip in 7ms, rewrite 217ms
,D/dalvikvm( 7285): GC_CONCURRENT freed 3001K, 32% free 9565K/13992K, paused 2ms+2ms, total 22ms
,D/dalvikvm( 7285): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/SO_AGENT( 7285): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7285): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/SA      ( 6333): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 6333): [BDLM] already registered in spp
,I/SA      ( 6333): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 6333): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/System.out( 7222): Thread-612(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/SA      ( 6333): [SLFUCHKMGR] constructor called
,I/SA      ( 6333): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6333): [OR] == isSIMCardReady false ==
,I/SA      ( 6333): [SCU] == networkStateCheck == true
I/SA      ( 6333): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6333): isChinaCountryCode : false
,I/SA      ( 6333): [OR] == networkStateCheck true ==
,I/SA      ( 6333): [OR] GetMyCountryZoneTask
,D/dalvikvm( 6275): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42311a30, skipping init
,I/SA      ( 6333): [OR] onReceive END
,I/SA      ( 6333): [SRS] prepareGetMyCountryZone
,I/System.out( 7222): Thread-612(ApacheHTTPLog):isShipBuild true
,I/System.out( 7222): Thread-612(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/SecureStorage( 6275): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 1959): [INFO]: SPID(0x00000004)Credentials: uid 1000, gid 1000, pid 6275
,I/SecureStorage( 1959): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 6073): Other Intent
,I/SA      ( 6333): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SELinux ( 7313): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7313):  
,I/SA      ( 6333): [SSP] query invoked
,D/dalvikvm( 2721): GC_EXPLICIT freed 326K, 29% free 9965K/13976K, paused 4ms+23ms, total 245ms
I/dalvikvm( 7205): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 7205): VFY: unable to resolve virtual method 2614: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 7205): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 7205): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 7205): VFY: unable to resolve virtual method 2615: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 7205): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7205): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
,W/dalvikvm( 7205): VFY: unable to resolve virtual method 2622: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 7205): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7205): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 7205): VFY: unable to resolve virtual method 2623: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 7205): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 7205): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method agv.getLeanbackLaunchIntentForPackage
W/dalvikvm( 7205): VFY: unable to resolve virtual method 2639: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 7205): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7205): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method agv.getPackageInstaller
,W/dalvikvm( 7205): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7205): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7205): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method agv.getUserBadgedDrawableForDensity
W/dalvikvm( 7205): VFY: unable to resolve virtual method 2659: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 7205): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7205): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method agv.getUserBadgedIcon
,W/dalvikvm( 7205): VFY: unable to resolve virtual method 2660: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 7205): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 7205): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method agv.getUserBadgedLabel
W/dalvikvm( 7205): VFY: unable to resolve virtual method 2661: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm( 7205): VFY: replacing opcode 0x6e at 0x0002
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7205): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
I/SELinux ( 7313): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7313):  
I/SELinux ( 7313):  
I/SELinux ( 7313): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7313): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7313): >>>>> Normal User
E/dalvikvm( 7313): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
E/SELinux ( 7313): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/ContextImpl( 7205): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7205): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,D/TimaKeyStoreProvider( 7313): in addTimaSignatureService
,W/InstanceID/Rpc( 7205): Found 10012
,D/TimaKeyStoreProvider( 7313): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7313): Added TimaKesytore provider
,I/SA      ( 6333): [TPMU] GetMccFromDB : null
,I/SA      ( 6333): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6333): [TPM] isNoProxy(default) : true
,I/SA      ( 6333): [RC New] Execute method=[GET] start
,I/SELinux ( 7330): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7330):  
E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
I/SELinux ( 7330): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7330):  
I/SELinux ( 7330):  
I/SELinux ( 7330): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7330): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7330): >>>>> Normal User
E/dalvikvm( 7330): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
E/SELinux ( 7330): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7330): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7330): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7330): Added TimaKesytore provider
,W/ContextImpl( 7205): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/dalvikvm( 3309): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,D/dalvikvm( 7313): GC_CONCURRENT freed 3005K, 32% free 9563K/13992K, paused 1ms+3ms, total 39ms
,D/dalvikvm( 7313): WAIT_FOR_CONCURRENT_GC blocked 31ms
,W/dalvikvm( 3309): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 3309): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm( 7330): GC_CONCURRENT freed 2990K, 32% free 9577K/13988K, paused 5ms+2ms, total 34ms
,D/dalvikvm( 7330): WAIT_FOR_CONCURRENT_GC blocked 29ms
,I/System.out( 7222): AsyncTask #1 calls detatch()
,D/com.samsung.app( 7313): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7313): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7313): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,V/KVNProvider( 7330): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7330): getFindoCursor query string : 
,V/KVNProvider( 7330): getTagSearchCursor() tagSearchCursor count : 0
,D/com.samsung.app( 7313): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7313): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7313): [KK AccuPhone]>>> RM:136 [0:0]  V init 
I/ActivityManager( 2418): Killing 5327:com.google.android.talk/u0a109 (adj 15): empty #43
,D/daemonapp( 5273): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7313): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5273): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,W/System.err( 7222): com.sec.android.fota.osp.http.RestClientException
,W/System.err( 7222): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
,W/System.err( 7222): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
,W/System.err( 7222): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7222): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 7222): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 7222): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 7222): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 7222): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7222): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7222): Caused by: java.lang.NullPointerException
,W/System.err( 7222): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7222): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7222): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7222): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7222): 	... 8 more
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 350, Delta = 20
,I/ActivityManager( 2418): Killing 5836:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,D/DelayedSyncController( 6020): Delaying sync.
,E/ActivityThread( 3309): Failed to find provider info for com.android.contacts.metadata
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): stay LED for fully charged
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5076): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5076): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth.Api.Credentials( 3309): [CredentialSyncAdapter] Unknown sync event.
,E/WifiStateMachine( 2418): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/com.samsung.app( 7313): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5273): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7313): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7313): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2418): Killing 5772:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7379): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7379):  
,I/SELinux ( 7379): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7379):  
I/SELinux ( 7379):  
,I/SELinux ( 7379): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7379): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7379): >>>>> Normal User
,E/dalvikvm( 7379): >>>>> com.samsung.android.internal.headlines [ userId:0 | appId:10110 ]
,E/SELinux ( 7379): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7379): in addTimaSignatureService
,D/libgps  ( 2418): agps_ril_update_network_state: Waiting for IPC connection...
,D/TimaKeyStoreProvider( 7379): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7379): Added TimaKesytore provider
,I/System.out( 7205): Thread-669(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7205): Thread-669(ApacheHTTPLog):isShipBuild true
,I/System.out( 7205): Thread-669(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 7379): GC_CONCURRENT freed 3007K, 32% free 9566K/13992K, paused 3ms+2ms, total 24ms
,D/dalvikvm( 7379): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/HeadlinesChannelApplication( 7379): [onCreate]
,D/Headlines( 7379): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 7379): getCountryCode(): countryCode = PL
,D/Headlines( 7379): Breath.onCreate
,D/HeadlinesCardManager( 7379): HeadlinesCardManager : constructor
E/HeadlinesCardManager( 7379): HeadlinesCardManager : ctor = image_cache size is 42MB
,D/SA Version( 7379): CardProvider Library : 13
,I/SELinux ( 7392): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7392):  
,I/ActivityManager( 2418): Killing 5815:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
I/SurfaceFlinger( 1920): id=22 Removed Uoast (10/11)
,I/SurfaceFlinger( 1920): id=22 Removed Uoast (-2/11)
D/PowerManagerService( 2418): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2418) eventTime = 337757
D/PowerManagerService( 2418): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2418 (0x0)
,D/PowerManagerService( 2418): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2418, ws=WorkSource{1000}) (elapsedTime=3492)
I/SELinux ( 7392): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7392):  
I/SELinux ( 7392):  
I/SELinux ( 7392): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7392): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7392): >>>>> Normal User
E/dalvikvm( 7392): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
E/SELinux ( 7392): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7392): in addTimaSignatureService
,I/SurfaceFlinger( 1920): id=23 createSurf (1x1),1 flag=4, Uoast
,D/TimaKeyStoreProvider( 7392): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7392): Added TimaKesytore provider
,D/PowerManagerService( 2418): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2418
,I/SecureStorage( 1959): [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 1959): [INFO]: SPID(0x00000004)PID: 6275, TID: 6304
,D/dalvikvm( 7392): GC_CONCURRENT freed 2993K, 32% free 9571K/13984K, paused 4ms+1ms, total 25ms
,D/dalvikvm( 7392): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/System.out( 6333): Thread-572(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/MagazineService::CardProviderContentProvider( 6378): insertProvider: provider already exists.: com.samsung.android.app.headlines
,D/MagazineService::CardProviderContentProvider( 6378): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 7379): registerCardProvider: provider already exists.
,I/System.out( 6333): Thread-572(ApacheHTTPLog):isShipBuild true
,I/System.out( 6333): Thread-572(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/Headlines( 7379): HeadlinesDataCenter ctor
I/Headlines( 7379): HeadlinesDataCenter. mLocale = en_US
,D/HeadlinesChannelUtil( 7379): getCountryCode(): countryCode = PL
,D/HeadlinesCardManager( 7379): HeadlinesCardManager : constructor welcome :YES
,I/SecureStorage( 6275): [INFO]: SPID(0x00000000)Processing data has been completed
,V/WebViewChromium( 7392): Binding Chromium to the background looper Looper (main, tid 1) {422ce088}
,I/chromium( 7392): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/Headlines( 7379): Breath timer started. interval : 30000
D/Headlines( 7379): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 7379): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 7379): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 7379): queryCategory.  mRequest is not initialized.
,I/BrowserProcessMain( 7392): Initializing chromium process, renderers=0
D/HeadlinesCardManager( 7379): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 7379): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 7379): requestUpdateNewsWelcomeCard !!! no welcome card
,I/System.out( 7205): Thread-669 calls detatch()
,W/chromium( 7392): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7392): loaded /system/lib/egl/libEGL_mali.so
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/libEGL  ( 7392): loaded /system/lib/egl/libGLESv1_CM_mali.so
D/libEGL  ( 7392): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7392): Mali API Version : 401
,I/Mali    ( 7392): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,W/GAV2    ( 7392): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 7392): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,V/AlarmManager( 2418): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,W/WifiP2pStateTracker( 2418): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
D/ConnectivityService( 2418): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2418):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2418): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2418): updateSourceRoutes : no source routing conditions
,I/dalvikvm( 6275): Total arena pages for JIT: 11
,I/dalvikvm( 6275): Total arena pages for JIT: 12
I/dalvikvm( 6275): Total arena pages for JIT: 13
,I/dalvikvm( 6275): Total arena pages for JIT: 14
I/dalvikvm( 6275): Total arena pages for JIT: 15
I/dalvikvm( 6275): Total arena pages for JIT: 16
,I/dalvikvm( 6275): Total arena pages for JIT: 17
,I/NSApplication( 7392): Starting up...
,I/ImageResourceManager( 5700): ImageResourceManager: uninitalized
,D/dalvikvm( 5700): GC_FOR_ALLOC freed 1139K, 29% free 9959K/13988K, paused 24ms, total 28ms
,I/dalvikvm-heap( 5700): Grow heap (frag case) to 13.139MB for 2129936-byte allocation
,D/dalvikvm( 5700): GC_FOR_ALLOC freed 40K, 26% free 11999K/16072K, paused 18ms, total 18ms
,I/iu.Environment( 5700): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager( 2418): Killing 6100:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/QuickConnect[1.1][2] ( 5050): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5050): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5050): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422d8620
D/dalvikvm( 5700): GC_CONCURRENT freed 38K, 26% free 11974K/16072K, paused 4ms+8ms, total 36ms
,D/dalvikvm( 5700): WAIT_FOR_CONCURRENT_GC blocked 19ms
D/libgps  ( 2418): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2418): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2418): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2418): agps_ril_update_network_availability: Waiting for IPC connection...
,I/dalvikvm-heap( 5700): Grow heap (frag case) to 15.107MB for 2129936-byte allocation
,I/SELinux ( 7437): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7437):  
,D/dalvikvm( 5700): GC_FOR_ALLOC freed 16K, 23% free 14037K/18156K, paused 21ms, total 21ms,
,I/iu.UploadsManager( 5700): num queued entries: 0,
,I/iu.UploadsManager( 5700): num updated entries: 0,
,I/iu.SyncManager( 5700): NEXT; no task,
,I/SELinux ( 7437): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7437):  
I/SELinux ( 7437):  
,I/SELinux ( 7437): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7437): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7437): >>>>> Normal User
,E/dalvikvm( 7437): >>>>> com.android.email [ userId:0 | appId:10157 ],
,E/SELinux ( 7437): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7437): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7437): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7437): Added TimaKesytore provider
,I/SA      ( 6333): [RC New] [v2liruge] api execute + 2040
,I/SA      ( 6333): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6333): AsyncTask #1 calls detatch()
,I/SA      ( 6333): [TPMU] getNetworkMcc : 
,D/dalvikvm( 2418): GC_EXPLICIT freed 1748K, 55% free 24494K/54232K, paused 9ms+16ms, total 187ms
,I/SA      ( 6333): [SCU] saveMccToPreferece Start
,I/SA      ( 6333): [SCU] RegionMCC : 260
,I/SA      ( 6333): [SSP] query invoked,
I/SA      ( 6333): [TPMU] GetMccFromDB : null
I/SA      ( 6333): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6333): [SCU] saveMccToPreferece End
I/SA      ( 6333): [RC New] executeRequest [v2liruge] end. 2074
,I/SA      ( 6333): [RC New] Execute end
,I/SA      ( 6333): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6333): [OR] GetMyCountryZoneTask Success
,D/dalvikvm( 7437): GC_CONCURRENT freed 2990K, 32% free 9581K/13992K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 7437): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,I/System.out( 7205): Thread-658 calls detatch()
,D/dalvikvm( 7205): GC_CONCURRENT freed 1351K, 20% free 11381K/14148K, paused 8ms+5ms, total 54ms
,I/SELinux ( 7457): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7457):  
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,I/SELinux ( 7457): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7457):  
I/SELinux ( 7457):  
,I/SELinux ( 7457): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7457): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7457): >>>>> Normal User
,E/dalvikvm( 7457): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,I/ActivityManager( 2418): Killing 5948:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,E/SELinux ( 7457): [DEBUG] seapp_context_lookup: seinfoCategory = release
W/ActivityManager( 2418): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 7457): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7457): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7457): Added TimaKesytore provider
,I/SELinux ( 7472): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7472):  
,I/ActivityManager( 2418): Killing 6145:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/ActivityManager( 2418): Killing 6157:com.android.musicfx/u0a24 (adj 15): empty #43
,D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 14% free 9502K/10968K, paused 2ms+3ms, total 34ms
,I/SELinux ( 7472): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7472):  
I/SELinux ( 7472):  
,I/SELinux ( 7472): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7472): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7472): >>>>> Normal User
,E/dalvikvm( 7472): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7472): [DEBUG] seapp_context_lookup: seinfoCategory = shared,
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 14% free 9502K/10968K, paused 2ms+3ms, total 25ms,
,D/TimaKeyStoreProvider( 7472): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7472): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7472): Added TimaKesytore provider,
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 14% free 9502K/10968K, paused 2ms+3ms, total 25ms,
,D/dalvikvm( 7457): GC_CONCURRENT freed 3000K, 32% free 9565K/13988K, paused 3ms+1ms, total 41ms,
,D/dalvikvm( 7457): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/BadgeProvider( 7457): onCreate
,D/BadgeProvider( 7457): DatabaseHelper,
,D/BadgeProvider( 7457): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge',
,D/BadgeProvider( 7457): sendNotify entered. [uri] : content://com.sec.badge/apps/1,
D/BadgeProvider( 7457): sendNotify, [notify] : null
D/BadgeProvider( 7457): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7457): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7457): update, [UpdateCount] : 1,
,D/Launcher.Model( 2774): reloadBadges entered.,
,D/dalvikvm( 7472): GC_CONCURRENT freed 2998K, 32% free 9572K/13992K, paused 2ms+1ms, total 30ms
,D/dalvikvm( 7472): WAIT_FOR_CONCURRENT_GC blocked 28ms
,I/SELinux ( 7484): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7484):  
,I/ActivityManager( 2418): Killing 6185:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,I/SELinux ( 7484): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7484):  
I/SELinux ( 7484):  
,I/SELinux ( 7484): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7484): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 7484): >>>>> Normal User
,E/dalvikvm( 7484): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
,E/SELinux ( 7484): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7484): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7484): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7484): Added TimaKesytore provider
,D/dalvikvm( 7484): GC_CONCURRENT freed 3000K, 32% free 9566K/13984K, paused 2ms+1ms, total 21ms
,D/dalvikvm( 7484): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/dalvikvm( 7484): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 7484): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 7484): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 7484): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7484): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7484): VFY: replacing opcode 0x22 at 0x0000
,D/libgps  ( 2418): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2418): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2418): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
E/dalvikvm( 7484): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
W/dalvikvm( 7484): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 7484): VFY: replacing opcode 0x22 at 0x0037
,W/dalvikvm( 7484): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7484): Link of class 'Ldqp;' failed
,W/dalvikvm( 7484): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7484): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7484): Link of class 'Ldqp;' failed
I/dalvikvm( 7484): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 7484): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 7484): VFY: replacing opcode 0x6e at 0x0000
,I/ActivityManager( 2418): Killing 6199:com.sec.android.app.shealth/u0a36 (adj 15): empty #43
,E/dalvikvm( 7484): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
,W/dalvikvm( 7484): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7484): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 7484): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 7484): Link of class 'Ldqp;' failed
,W/dalvikvm( 7484): VFY: unable to find class referenced in signature (Ldqp;)
,D/SyncManager( 2418): failed sync operation 
,W/dalvikvm( 7484): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7484): Link of class 'Ldqp;' failed
,I/dalvikvm( 7484): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 7484): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
,D/dalvikvm( 7484): VFY: replacing opcode 0x6e at 0x0008
,D/SyncManager( 2418): not retrying sync operation because the error is a hard error: 
,E/dalvikvm( 7484): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 7484): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
,D/dalvikvm( 7484): VFY: replacing opcode 0x1c at 0x0026
,W/dalvikvm( 7484): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 7484): Link of class 'Ldqp;' failed
W/dalvikvm( 7484): VFY: unable to find class referenced in signature (Ldqp;)
,W/dalvikvm( 7484): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 7484): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 7484): Link of class 'Ldqp;' failed
I/dalvikvm( 7484): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 7484): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
,D/dalvikvm( 7484): VFY: replacing opcode 0x6e at 0x0003
,W/dalvikvm( 7484): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7484): Link of class 'Lax;' failed
E/dalvikvm( 7484): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 7484): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
,D/dalvikvm( 7484): VFY: replacing opcode 0x22 at 0x0006
,W/dalvikvm( 7484): Unable to resolve superclass of Laz; (841)
,W/dalvikvm( 7484): Link of class 'Laz;' failed
E/dalvikvm( 7484): Could not find class 'az', referenced from method g.a
W/dalvikvm( 7484): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
,D/dalvikvm( 7484): VFY: replacing opcode 0x22 at 0x002c
,I/dalvikvm( 7484): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 7484): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7484): VFY: replacing opcode 0x6e at 0x0008
,I/dalvikvm( 7484): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
W/dalvikvm( 7484): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 7484): VFY: replacing opcode 0x6e at 0x000c
,I/dalvikvm( 7484): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 7484): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7484): VFY: replacing opcode 0x6e at 0x0006
,I/dalvikvm( 7484): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 7484): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
D/dalvikvm( 7484): VFY: replacing opcode 0x6e at 0x000a
,I/dalvikvm( 7484): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 7484): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 7484): VFY: replacing opcode 0x72 at 0x0000
,I/dalvikvm( 7484): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
,W/dalvikvm( 7484): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
,D/dalvikvm( 7484): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7484): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 7484): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 7484): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 7484): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 7484): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 7484): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 7484): VFY: replacing opcode 0x23 at 0x0005
,I/dalvikvm( 7484): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
,W/dalvikvm( 7484): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7484): VFY: replacing opcode 0x6e at 0x0009
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6171): mConnectivityHandler : connected
,D/NtpTrustedTime( 2418): getCachedNtpTime() cache hit
W/dalvikvm( 7484): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
W/dalvikvm( 7484): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
,E/dalvikvm( 7484): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 7484): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
,D/dalvikvm( 7484): VFY: replacing opcode 0x1c at 0x0002
,E/dalvikvm( 7484): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 7484): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 7484): VFY: replacing opcode 0x1f at 0x000c
,W/PCWCLIENTTRACE_AccountUtil( 6171): [hasSamungAccount] - No Samsung Account
,D/dalvikvm( 7484): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 7484): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7484): VFY: replacing opcode 0x62 at 0x0006
,D/dalvikvm( 7484): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7484): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
,D/dalvikvm( 7484): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7484): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
,D/dalvikvm( 7484): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
W/dalvikvm( 7484): Unable to resolve superclass of Lax; (841)
,W/dalvikvm( 7484): Link of class 'Lax;' failed
,D/dalvikvm( 7484): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 7484): Unable to resolve superclass of Laz; (841)
,W/dalvikvm( 7484): Link of class 'Laz;' failed
,D/dalvikvm( 7484): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 7484): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
,D/dalvikvm( 7484): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,D/dalvikvm( 7484): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x422bf428
,D/dalvikvm( 7484): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x422bf428
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6171): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6171): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6171): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6171): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6171): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6171): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6171): [ensureRegistration] - No Samsung account
,I/dalvikvm( 7484): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
,W/dalvikvm( 7484): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 7484): VFY: replacing opcode 0x6e at 0x0076
,I/Babel_SMS( 7484): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7484): MmsConfig.loadMmsSettings
I/Babel_SMS( 7484): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/Babel_SMS( 7484): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7484): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7484): MmsConfig.loadFromResources
,E/Babel_SMS( 7484): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7484): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,W/dalvikvm( 7484): Unable to resolve superclass of Lfzc; (613)
,W/dalvikvm( 7484): Link of class 'Lfzc;' failed
E/dalvikvm( 7484): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
,W/dalvikvm( 7484): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
,D/dalvikvm( 7484): VFY: replacing opcode 0x22 at 0x0033
,W/dalvikvm( 7484): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7484): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7484): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
,W/dalvikvm( 7484): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,I/dalvikvm( 7484): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
,W/dalvikvm( 7484): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
,D/dalvikvm( 7484): VFY: replacing opcode 0x74 at 0x006d
,I/dalvikvm( 7484): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 7484): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
,D/dalvikvm( 7484): VFY: replacing opcode 0x6e at 0x0033
I/dalvikvm( 7484): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 7484): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
,D/dalvikvm( 7484): VFY: replacing opcode 0x6e at 0x0030
W/dalvikvm( 7484): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7484): Link of class 'Lfzc;' failed
,D/dalvikvm( 7484): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
,E/SensorService( 2418): Permission Denial : SEC Private Sensor 
,E/SensorService( 2418): Permission Denial : SEC Private Sensor 
,D/dalvikvm( 7484): GC_CONCURRENT freed 1748K, 23% free 10890K/14056K, paused 3ms+3ms, total 34ms
,D/dalvikvm( 7484): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 7484): WAIT_FOR_CONCURRENT_GC blocked 15ms
D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,D/PicasaService( 3593): start picasa sync
,D/PicasaService( 3593): end picasa sync
,D/DelayedSyncController( 6020): Delaying sync.
,W/Settings( 7484): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7484): startup - clean
,I/dalvikvm( 7484): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
,W/dalvikvm( 7484): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7484): VFY: replacing opcode 0x6e at 0x000d
,I/Babel   ( 7484): deleted: false for 0
,W/dalvikvm( 7484): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,I/dalvikvm( 7484): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 7484): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
D/dalvikvm( 7484): VFY: replacing opcode 0x6e at 0x004e
,W/dalvikvm( 7484): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7484): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7484): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 7484): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
,D/dalvikvm( 7484): VFY: replacing opcode 0x22 at 0x0071
,W/dalvikvm( 7484): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7484): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7484): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7484): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7484): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 7484): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
,D/dalvikvm( 7484): VFY: replacing opcode 0x1f at 0x0021
,W/dalvikvm( 7484): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 7484): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
,D/WaitQueueForNetworkActivate( 6473): notifyNetworkActivated
,I/dalvikvm( 7484): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/dalvikvm( 7484): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
,D/dalvikvm( 7484): VFY: replacing opcode 0x6e at 0x0074
,I/vclib   ( 7484): onServiceConnected
,W/Babel   ( 7484): Attempted to change video mute state without an active call.
,W/ContextImpl( 6473): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager( 2418): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/dalvikvm( 7484): GC_CONCURRENT freed 929K, 17% free 12008K/14356K, paused 6ms+3ms, total 63ms
,D/dalvikvm( 7484): WAIT_FOR_CONCURRENT_GC blocked 56ms
,D/dalvikvm( 7484): WAIT_FOR_CONCURRENT_GC blocked 50ms
,D/dalvikvm( 7484): GC_FOR_ALLOC freed 713K, 18% free 12579K/15332K, paused 27ms, total 27ms
,D/dalvikvm( 7484): GC_FOR_ALLOC freed 1782K, 24% free 12964K/16924K, paused 30ms, total 31ms
,D/hcjo    ( 6473): AutoUpdateManager:IDLE:execute
,I/dalvikvm( 6473): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
,W/dalvikvm( 6473): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 6473): VFY: replacing opcode 0x6e at 0x0024
I/System.out( 7484): Thread-653(HTTPLog):isShipBuild true
,I/System.out( 7484): Thread-653(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/InitializeManagerStateMachine( 6473): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6473): exit::IDLE
,D/InitializeManagerStateMachine( 6473): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6473): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6473): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6473): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6473): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 6473): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6473): entry::SUCCESS
,D/hcjo    ( 6473): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6473): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 6473): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6473): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6473): exit::SUCCESS
,D/InitializeManagerStateMachine( 6473): entry::IDLE
,I/iu.Environment( 3309): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 3309): num queued entries: 0
,I/iu.UploadsManager( 3309): num updated entries: 0
,I/iu.SyncManager( 3309): NEXT; no task
,E/SPPClientService( 5468): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5468): [SystemStateMoniter] Current Time : 340800
,E/SPPClientService( 5468): [SystemStateMoniter] No Connect : false
,I/SELinux ( 7526): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7526):  
,I/Babel   ( 7484): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager( 2418): Killing 6217:com.sec.android.service.health/u0a16 (adj 15): empty #43
,I/SELinux ( 7526): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7526):  
I/SELinux ( 7526):  
,I/SELinux ( 7526): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7526): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7526): >>>>> Normal User
,E/dalvikvm( 7526): >>>>> com.android.calendar [ userId:0 | appId:10144 ]
,E/SELinux ( 7526): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7526): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7526): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7526): Added TimaKesytore provider
D/AmoledAdjustTimer( 2418): prevTemp = 301, currTemp = 302, prevStep = 4, currStep = 4
,D/dalvikvm( 7526): GC_CONCURRENT freed 2994K, 32% free 9572K/13984K, paused 2ms+1ms, total 24ms
,D/dalvikvm( 7526): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/GCM     ( 2845): GCM config loaded
,I/ActivityManager( 2418): Killing 6312:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty #43
,D/BootCompletedReceiver( 2418): onReceive
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/KLMS-2.3.201 : ( 7247): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/SurfaceFlinger( 1920): id=23 Removed Uoast (10/11)
,I/SurfaceFlinger( 1920): id=23 Removed Uoast (-2/11)
,D/PowerManagerService( 2418): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2418) eventTime = 341266
,D/PowerManagerService( 2418): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2418 (0x0)
,D/PowerManagerService( 2418): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2418, ws=WorkSource{1000}) (elapsedTime=3464)
,I/KLMS-2.3.201 : ( 7247): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1449748862938
,I/KLMS-2.3.201 : ( 7247): StateImplV2() : dateTimeChanged() : Thu Dec 10 13:01:02 CET 2015
,I/SELinux ( 7545): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7545):  
,I/SELinux ( 7545): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7545):  
I/SELinux ( 7545):  
,I/SELinux ( 7545): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7545): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7545): >>>>> Normal User
,E/dalvikvm( 7545): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
,E/SELinux ( 7545): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7545): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7545): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7545): Added TimaKesytore provider
,D/dalvikvm( 7545): GC_CONCURRENT freed 2998K, 32% free 9568K/13988K, paused 3ms+2ms, total 23ms
,D/dalvikvm( 7545): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/PhenotypeConfigurator( 2733): Scheduling Phenotype for one-off execution 5432 seconds from now (1449748863178)
,D/GetConfigurationSnapshotOperation( 2733): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,W/ContextImpl( 7545): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
,I/SELinux ( 7568): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7568):  
D/ConnectivityService( 2418): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController( 2578): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2578): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2578): updateDataNetType()
,D/STATUSBAR-NetworkController( 2578): NoService, mRoamingIconId = 0
,I/SELinux ( 7568): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7568):  
I/SELinux ( 7568):  
,I/SELinux ( 7568): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7568): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7568): >>>>> Normal User
,E/dalvikvm( 7568): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,E/SELinux ( 7568): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/PhenotypeFlagCommitter( 2733): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,D/TimaKeyStoreProvider( 7568): in addTimaSignatureService
E/Device Type Shared Preferences( 7545): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 7545): Device Type Shared Preferences - not connecting to service
,E/com.sec.android.app.shealth.SHealthApplication( 7545): ContentProvider is not null
,D/TimaKeyStoreProvider( 7568): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7568): Added TimaKesytore provider
,W/dalvikvm( 2733): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2733): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/ResourceType( 7545): No package identifier when getting value for resource number 0x00000000
,I/System.out( 7545): resource Id::2131361807
,W/dalvikvm( 2733): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 2733): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2733): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2733): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2733): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 7568): GC_CONCURRENT freed 3002K, 32% free 9568K/13988K, paused 2ms+1ms, total 32ms
,D/dalvikvm( 7568): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/com.sec.android.app.shealth.SHealthApplication( 7545): Success during batch insertion in App registry:0
,I/System.out( 3309): Thread-188(HTTPLog):isShipBuild true
,I/System.out( 3309): Thread-188(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/LocationManagerService( 2418): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 2733): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 2733): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2733): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 2733): Thread-125(HTTPLog):isShipBuild true
,I/System.out( 2733): Thread-125(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,V/MediaPlayer( 7545): decode(56, 30565892, 48105)
,V/MediaPlayerService( 1924): decode(26, 30565892, 48105)
,V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): constructor
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
V/StagefrightPlayer( 1924): setDataSource(26, 30565892, 48105)
,V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b4bc8, 8, 0, 0)
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
,V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
,I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b4bc8, 200, 973, 0)
,V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b4bc8, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b4bc8, 1, 0, 0)
,V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
,V/StagefrightPlayer( 1924): start
,V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b4bc8, 6, 0, 0)
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
V/AudioCache( 1924): notify(0x442b4bc8, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b4bc8, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b4bc8, 8, 0, 0)
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
,V/MediaPlayer( 7545): decode(58, 30501792, 10421)
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
V/AudioCache( 1924): notify(0x444f7c48, 8, 0, 0)
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
V/AudioCache( 1924): notify(0x444f7c48, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f7c48, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f7c48, 1, 0, 0)
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
V/AudioCache( 1924): notify(0x444f7c48, 6, 0, 0)
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
V/AudioCache( 1924): notify(0x444f7c48, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f7c48, 7, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f7c48, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x45, OMX_CommandStateSet, OMX_StateIdle)
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
V/AwesomePlayer( 1924): mSecMediaClock clear
,V/MediaPlayer( 7545): decode(59, 34044116, 34198)
,V/MediaPlayerService( 1924): decode(26, 34044116, 34198)
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
V/StagefrightPlayer( 1924): setDataSource(26, 34044116, 34198)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441ae520, 8, 0, 0)
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
,D/dalvikvm( 3309): GC_FOR_ALLOC freed 1636K, 21% free 12474K/15780K, paused 79ms, total 85ms
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x441ae520, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441ae520, 5, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441ae520, 1, 0, 0)
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
V/AudioCache( 1924): notify(0x441ae520, 6, 0, 0)
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
V/AudioCache( 1924): notify(0x441ae520, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441ae520, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441ae520, 8, 0, 0)
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
V/MediaPlayer( 7545): decode(60, 30449260, 7405)
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
V/AudioCache( 1924): notify(0x442b97e0, 8, 0, 0)
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
V/AudioCache( 1924): notify(0x442b97e0, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b97e0, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b97e0, 1, 0, 0)
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
V/AudioCache( 1924): notify(0x442b97e0, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
I/AudioPlayer( 1924): First fillBuffer call!!
,V/MediaPlayerService( 1924): wait for playback complete
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b97e0, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b97e0, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b97e0, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x47, OMX_CommandStateSet, OMX_StateIdle)
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
,V/MediaPlayer( 7545): decode(61, 34134748, 5555)
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
V/AudioCache( 1924): notify(0x442b8170, 8, 0, 0)
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
V/AudioCache( 1924): notify(0x442b8170, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b8170, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b8170, 1, 0, 0)
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
V/AudioCache( 1924): notify(0x442b8170, 6, 0, 0)
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
V/AudioCache( 1924): notify(0x442b8170, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b8170, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b8170, 8, 0, 0)
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
,V/MediaPlayer( 7545): decode(62, 26954540, 5085)
,V/MediaPlayerService( 1924): decode(26, 26954540, 5085)
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
V/AudioCache( 1924): notify(0x442baca8, 8, 0, 0)
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
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442baca8, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442baca8, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442baca8, 1, 0, 0)
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
V/AudioCache( 1924): notify(0x442baca8, 6, 0, 0)
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
V/AudioCache( 1924): notify(0x442baca8, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442baca8, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442baca8, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x49, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 7545): decode(63, 26959684, 21552)
,V/MediaPlayerService( 1924): decode(26, 26959684, 21552)
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
V/StagefrightPlayer( 1924): setDataSource(26, 26959684, 21552)
,V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442bc7e8, 8, 0, 0)
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
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442bc7e8, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442bc7e8, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442bc7e8, 1, 0, 0)
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
V/AudioCache( 1924): notify(0x442bc7e8, 6, 0, 0)
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
V/AudioCache( 1924): notify(0x442bc7e8, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442bc7e8, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442bc7e8, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x4a, OMX_CommandStateSet, OMX_StateIdle)
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
,V/MediaPlayer( 7545): decode(64, 34130460, 4230)
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
V/AudioCache( 1924): notify(0x442bc890, 8, 0, 0)
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
V/AudioCache( 1924): notify(0x442bc890, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442bc890, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442bc890, 1, 0, 0)
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
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 1924): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442bc890, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442bc890, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442bc890, 7, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442bc890, 8, 0, 0)
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
V/MediaPlayer( 7545): decode(65, 26923896, 9400)
,V/MediaPlayerService( 1924): decode(26, 26923896, 9400)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): constructor
,V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
,V/StagefrightPlayer( 1924): setDataSource(26, 26923896, 9400)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f7c60, 8, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
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
V/AudioCache( 1924): notify(0x444f7c60, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f7c60, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f7c60, 1, 0, 0)
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
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache( 1924): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f7c60, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,D/dalvikvm( 7568): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x422b98c8, skipping init
I/SecureStorage( 7568): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/SecureStorage( 7568): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage( 1959): [INFO]: SPID(0x00000005)Credentials: uid 10016, gid 10016, pid 7568
I/SecureStorage( 1959): [INFO]: SPID(0x00000005)Received function mask & code: 0000010C
,I/SecureStorage( 7568): [INFO]: SPID(0x00000000)SS Daemon is running
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f7c60, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f7c60, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f7c60, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x4c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/SecureStorage( 7568): [INFO]: SPID(0x00000000)Processing data
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
V/MediaPlayer( 7545): decode(66, 30512272, 44276)
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
V/AudioCache( 1924): notify(0x444f9c38, 8, 0, 0)
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
I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/SecureStorage( 1959): [INFO]: SPID(0x00000005)Credentials: uid 10016, gid 10016, pid 7568
,I/SecureStorage( 1959): [INFO]: SPID(0x00000005)Received function mask & code: 00000106
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x444f9c38, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f9c38, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f9c38, 1, 0, 0)
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
V/AudioCache( 1924): notify(0x444f9c38, 6, 0, 0)
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
V/AudioCache( 1924): notify(0x444f9c38, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f9c38, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f9c38, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x4d, OMX_CommandStateSet, OMX_StateIdle)
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
,V/MediaPlayer( 7545): decode(67, 30472480, 29256)
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
V/AudioCache( 1924): notify(0x441ad038, 8, 0, 0)
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
,V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
,I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x441ad038, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441ad038, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441ad038, 1, 0, 0)
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
V/AudioCache( 1924): notify(0x441ad038, 6, 0, 0)
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
V/AudioCache( 1924): notify(0x441ad038, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441ad038, 7, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x441ad038, 8, 0, 0)
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
,V/MediaPlayer( 7545): decode(68, 34078380, 52024)
,V/MediaPlayerService( 1924): decode(26, 34078380, 52024)
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
V/AudioCache( 1924): notify(0x44150d80, 8, 0, 0)
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
V/AudioCache( 1924): notify(0x44150d80, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x44150d80, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x44150d80, 1, 0, 0)
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
,V/AudioCache( 1924): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x44150d80, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,D/dalvikvm( 2733): GC_CONCURRENT freed 1506K, 21% free 11967K/15104K, paused 3ms+8ms, total 72ms
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x44150d80, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x44150d80, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x44150d80, 8, 0, 0)
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
V/MediaPlayer( 7545): decode(69, 30556608, 9226)
V/MediaPlayerService( 1924): decode(26, 30556608, 9226)
,D/LocationManagerService( 2418): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
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
V/AudioCache( 1924): notify(0x442b3798, 8, 0, 0)
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
,V/AwesomePlayer( 1924): onPrepareAsyncEvent
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
V/AudioCache( 1924): notify(0x442b3798, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3798, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3798, 1, 0, 0)
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
V/AudioCache( 1924): notify(0x442b3798, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
,V/MediaPlayerService( 1924): wait for playback complete
,I/AudioPlayer( 1924): First fillBuffer call!!
,I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3798, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3798, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3798, 8, 0, 0)
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
,V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 7545): decode(70, 26989388, 4509)
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
V/AudioCache( 1924): notify(0x442b4bc8, 8, 0, 0)
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
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b4bc8, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b4bc8, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b4bc8, 1, 0, 0)
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
V/AudioCache( 1924): notify(0x442b4bc8, 6, 0, 0)
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
V/AudioCache( 1924): notify(0x442b4bc8, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b4bc8, 7, 0, 0)
V/AudioCache( 1924): ignored
,V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
,V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b4bc8, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x51, OMX_CommandStateSet, OMX_StateIdle)
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
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 1924): mSecMediaClock clear
,D/LocationManagerService( 2418): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService( 2418): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/GAV2    ( 7392): Thread[GAThread,5,main]: No campaign data found.
,I/SecureStorage( 1959): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 1959): [INFO]: SPID(0x00000005)PID: 7568, TID: 7580
,I/SecureStorage( 7568): [INFO]: SPID(0x00000000)Processing data has been completed
I/SecureStorage( 7568): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 7568): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 7568): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 7568): Open platform.db in secure mode
,E/SPPClientService( 5468): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,V/AlarmManager( 2418):  next == MAX_VALUE
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/SQLiteSecureOpenHelper( 7568): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 7568): ...getDatabaseLocked(b,b,pwd)
,E/SPPClientService( 5468): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,D/SO_AGENT( 7285): [ServerTimeReceiver.java(Line:44/Method:onReceive)] Receive broadcast meassage:android.intent.action.TIME_SET
,E/SPPClientService( 5468): [a] [ConnectionManager] Connection is already disconnected.
,I/SO_AGENT( 7285): [ServerTimeReceiver.java(Line:47/Method:onReceive)] No action is available before server time settings
,I/SA      ( 6333): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
V/AlarmManager( 2418): waitForAlarm result :4
V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Mms/MessagingNotification( 5565): [start]    nonBlockingUpdateMessageIndicator()
,D/Mms/MessagingNotification( 5565): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 5565): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 5565): isDefault true
,I/SELinux ( 7665): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7665):  
,I/ActivityManager( 2418): Killing 4798:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
,I/SELinux ( 7665): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7665):  
I/SELinux ( 7665):  
,I/SELinux ( 7665): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7665): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7665): >>>>> Normal User
,E/dalvikvm( 7665): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10064 ]
,E/SELinux ( 7665): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7665): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7665): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7665): Added TimaKesytore provider
,D/dalvikvm( 7665): GC_CONCURRENT freed 2999K, 32% free 9569K/13988K, paused 4ms+2ms, total 21ms
,D/dalvikvm( 7665): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 2418): GC_EXPLICIT freed 2176K, 55% free 24517K/54232K, paused 7ms+17ms, total 202ms
,D/TP/MmsSmsProvider( 2751): match 8:Elapsed time : 207.487 ms
,D/com.samsung.app( 7313): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidintentactionTIME_SET
,D/com.samsung.app( 7313): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/TP/MmsSmsProvider( 2751): match 200:Elapsed time : 1.038 ms
,I/ Time Manager ( 7665): Time Difference not stored. TIME_DIFFERENCE
,I/SELinux ( 7678): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7678):  
,I/ActivityManager( 2418): Killing 6352:com.sec.android.service.cm/u0a82 (adj 15): empty #43
,I/SELinux ( 7678): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7678):  
I/SELinux ( 7678):  
,I/SELinux ( 7678): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7678): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7678): >>>>> Normal User
,E/dalvikvm( 7678): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10088 ]
,E/SELinux ( 7678): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7678): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7678): Cannot add TimaSignature Service, License check Failed
,D/BadgeProvider( 7457): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/ActivityThread( 7678): Added TimaKesytore provider
,D/Launcher.Model( 2774): reloadBadges entered.
,D/BadgeProvider( 7457): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 7457): sendNotify, [notify] : null
D/BadgeProvider( 7457): update, [uri] : content://com.sec.badge/apps/2
,D/BadgeProvider( 7457): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7457): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 5565): setBadgeCount(), count=0
,D/MessagingNotification( 5565): remove alarm
,D/Mms/MessagingNotification( 5565): updateAllHistoryAsRead()
,D/Mms/MessagingNotification( 5565): [end]    nonBlockingUpdateMessageIndicator()
,D/dalvikvm( 7678): GC_CONCURRENT freed 2993K, 32% free 9578K/13992K, paused 5ms+1ms, total 24ms
,D/dalvikvm( 7678): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/SELinux ( 7692): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7692):  
I/ActivityManager( 2418): Killing 6364:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty #43
,I/SELinux ( 7692): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7692):  
I/SELinux ( 7692):  
,I/SELinux ( 7692): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7692): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7692): >>>>> Normal User
,E/dalvikvm( 7692): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 7692): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7692): in addTimaSignatureService
,D/CaptivePortalTracker( 2418): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/TimaKeyStoreProvider( 7692): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7692): Added TimaKesytore provider
,D/CaptivePortalTracker( 2418): Checking http://216.58.209.46/generate_204
D/ConnectivityService( 2418): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/ActivityThread( 2418): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/System.out( 2418): Thread-161(HTTPLog):isShipBuild true
,I/System.out( 2418): Thread-161(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 7692): GC_CONCURRENT freed 3013K, 32% free 9558K/13992K, paused 2ms+4ms, total 24ms
,D/dalvikvm( 7692): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/elm:14132( 7692): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14132( 7692): ELMEngine.ELMEngine( context ).
,D/elm:14132( 7692): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 7692): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,I/knox    ( 4990): MainReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,D/elm:14132( 7692): ElmAgentService : onCreate()
,W/ContextImpl( 4990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/elm:14132( 7692): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
D/knox    ( 4990): MainReceiver.listeningToTimeDateChanges( context, intent ).
I/knox    ( 4990): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
D/knox    ( 4990): KNOXAgentService : onCreate()
D/knox    ( 4990): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 4990): KNOXAgentService. startJobThread() start
D/knox    ( 4990): KNOXAgentService. JobThread()
D/elm:14132( 7692): ELMAgentService.listeningToTimeDateChanges( context, intent ).
D/knox    ( 4990): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 4990): KNOXAgentService. startJobThread() wait
D/elm:14132( 7692): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:14132( 7692): ModuleBase.resetCalllogAPIAlarm()
,I/SELinux ( 7709): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7709):  
D/CaptivePortalTracker( 2418): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 2418): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 2418): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2418): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
D/knox    ( 4990): KNOXAgentService : onDestroy().
,D/knox    ( 4990): ModuleBase.cancelAllAlarmManageModule(),
D/ConnectivityService( 2418): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/elm:14132( 7692): ModuleBase.ModifySetAlarm(),
D/elm:14132( 7692): MDMBridge.getInstance()
,D/elm:14132( 7692): MDMBridge.getAllLicenseInfoFromSDK(),
,D/elm:14132( 7692): ElmAgentService : onDestroy().,
I/ActivityManager( 2418): Killing 6391:com.samsung.helphub/1000 (adj 15): empty #43
,I/SELinux ( 7709): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7709):  
I/SELinux ( 7709):  
I/SELinux ( 7709): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7709): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7709): >>>>> Normal User
,E/dalvikvm( 7709): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10145 ]
,E/SELinux ( 7709): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7709): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7709): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7709): Added TimaKesytore provider
,D/dalvikvm( 7709): GC_CONCURRENT freed 3001K, 32% free 9570K/13992K, paused 3ms+2ms, total 20ms
,D/dalvikvm( 7709): WAIT_FOR_CONCURRENT_GC blocked 11ms
,I/SELinux ( 7721): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7721):  
I/ActivityManager( 2418): Killing 6404:com.sec.kidsplat.installer/u0a160 (adj 15): empty #43
,I/SELinux ( 7721): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7721):  
I/SELinux ( 7721):  
,I/SELinux ( 7721): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7721): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7721): >>>>> Normal User
,E/dalvikvm( 7721): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10168 ]
,E/SELinux ( 7721): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7721): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7721): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7721): Added TimaKesytore provider
,D/dalvikvm( 7721): GC_CONCURRENT freed 2997K, 32% free 9566K/13988K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7721): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/ActivityManager( 2418): Killing 6416:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty #43
,D/daemonapp( 5273): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5273): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5273): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5273): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5273): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionTIME_SET, run:true
D/comsamsunglog( 5273): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5273): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5273): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5273): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5273): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5273): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5273): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
I/ActivityManager( 2418): Waited long enough for: ServiceRecord{4433ebb0 u0 pl.k2.droidoaudioteka/.services.DownloadService}
,D/daemonapp( 5273): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 5273): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5273): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,I/ActivityManager( 2418): Waited long enough for: ServiceRecord{44282378 u0 pl.k2.droidoaudioteka/.services.PlayerService}
D/daemonapp( 5273): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/comdaemonstockapp( 5273): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 5273): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,I/CheckinService( 3309): Checkin interval check for package: unspecified last checkin: 1449576680750 min interval config: 0 actual interval: 172186123
,I/EventLogService( 3309): Aggregate from 1449747000563 (log), 1449747000563 (data)
,E/SPPClientService( 5468): [g] getNetMCC return empty string
,E/SPPClientService( 5468): [g] getNetMNC return empty string
,D/Mms/MessagesLockscreen( 5565): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
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
,I/jxcore-log( 7013): Test app app.js loaded
I/jxcore-log( 7013): 
,I/Choreographer( 7013): Skipped 1047 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7013): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/PowerManagerService( 2418): [PWL] Off : 140s ago
I/PowerManagerService( 2418): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2418): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2418): [PWL]       PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10088, pid=7678, ws=null) (elapsedTime=2495)
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 360, Delta = 10
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4355, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5076): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5076): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 11
,E/SPPClientService( 5468): [b] __ProvisionReply__
,E/SPPClientService( 5468): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5468): [d] null
,V/AlarmManager( 2418):  next == MAX_VALUE
,E/SPPClientService( 5468): [g] getPLMN return empty string
,E/SPPClientService( 5468): [b] SharedConstants.WHAT_PROV_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5468): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5468): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5468): [g] getNetMCC return empty string
,D/dalvikvm( 5468): GC_CONCURRENT freed 2111K, 26% free 10418K/13980K, paused 6ms+6ms, total 70ms
,D/PreloadUpdateManagerStateMachine( 6473): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6473): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6473): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6473): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6473): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6473): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 6473): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6473): entry::IDLE,
,D/AmoledAdjustTimer( 2418): prevTemp = 302, currTemp = 303, prevStep = 4, currStep = 4,
,E/SPPClientService( 5468): [b] __InitReply__,
,I/ActivityManager( 2418): Waited long enough for: ServiceRecord{42d0c278 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,V/AlarmManager( 2418): waitForAlarm result :4,
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 7810): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7810):  
,I/SELinux ( 7810): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7810):  
I/SELinux ( 7810):  
,I/SELinux ( 7810): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7810): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7810): >>>>> Normal User
,E/dalvikvm( 7810): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 7810): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 7810): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7810): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7810): Added TimaKesytore provider,
,D/dalvikvm( 7810): GC_CONCURRENT freed 3011K, 32% free 9555K/13984K, paused 3ms+2ms, total 28ms,
,D/dalvikvm( 7810): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/Headlines( 7379): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
D/Headlines( 7379): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7379): Breath 16256 latestRequest time : 1449748859666 current time : 1449748875922,
,I/ActivityManager( 2418): Killing 6428:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty #43,
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 340, Delta = -20,
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate,
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5076): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5076): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,I/wpa_supplicant( 7075): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030,
I/wpa_supplicant( 7075): WPA: Group rekeying completed with C0.AA.48 [GTK=CCMP]
,I/wpa_supplicant( 7075): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030,
,I/ActivityManager( 2418): Waited long enough for: ServiceRecord{442c3fa8 u0 com.sec.spp.push/.PushClientService},
,D/AmoledAdjustTimer( 2418): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4,
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2418): waitForAlarm result :4,
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = -10,
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2418): stay LED for fully charged,
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5076): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5076): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/AlarmManager( 2418): waitForAlarm result :8,
,D/Headlines( 7379): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
D/Headlines( 7379): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7379): Breath 30018 latestRequest time : 1449748859666 current time : 1449748889684,
,D/AmoledAdjustTimer( 2418): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5076): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5076): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 12,
,D/AmoledAdjustTimer( 2418): prevTemp = 303, currTemp = 302, prevStep = 4, currStep = 4,
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2418): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2418): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4,
,I/jxcore-log( 7013): Toggling radios to false,
I/jxcore-log( 7013): 
,D/BluetoothAdapterService(1110312368)( 5076): unRegister RemoteMessageListener,
,D/HeadsetService( 5076): registerMessageListener,
D/BluetoothAdapterState( 5076): CURRENT_STATE=ON, MSG = USER_TURN_OFF
I/BluetoothAdapterState( 5076): Bluetooth adapter state changed: 12-> 13
,D/HeadsetStateMachine( 5076): Disconnected process message: 80
,D/BluetoothAdapterService( 5076): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5076): updateAdapterState state is 13
,D/HeadsetStateMachine( 5076): processUnRegisterMessageListener : 2
,I/BluetoothPbapService( 5076): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,E/bt-btif ( 5076): bta_jv_rfcomm_stop_server
,D/BluetoothAdapterService( 5076): Broadcasting updateAdapterState() to 1 receivers.
,I/WifiManager( 7013): packageName : com.test.thalitest
,D/BluetoothAdapterService( 5076): Autoconnection is available 
,D/BluetoothAdapterService( 5076): updateAdapterState prevState = 12newState = 13
,D/BluetoothAdapterService( 5076): terminating service from this receiver
,D/PhoneApp( 2751): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 13
,I/SamsungIME( 2970): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/QuickConnect[1.1][2] ( 5050): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_OFF
,W/ContextImpl( 5076): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.stopService:511 com.android.bluetooth.btservice.AdapterService.updateAdapterState:657 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
,I/WifiManager( 7013): setWifiEnabled : false
,E/bt-btif ( 5076): bta_jv_rfcomm_stop_server
,I/WifiService( 2418): setWifiEnabled: false pid=7013, uid=10527
D/STATUSBAR-IconMerger( 2578): checkOverflow(336), More:false, Req:false Child:3
,V/AlarmManager( 2418): waitForAlarm result :4
,W/InputMethodManagerService( 2418): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 2418): [BT Setting State] State =13
,I/BtOppRfcommListener( 5076): stopping Accept Thread
,E/BtOppRfcommListener( 5076): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 5076): bta_jv_rfcomm_stop_server
,I/BtOppRfcommListener( 5076): BluetoothSocket listen thread finished
,I/jxcore-log( 7013): Radios toggled
I/jxcore-log( 7013): 
,D/BluetoothPbap( 5550): Proxy object disconnected
,D/PbapServerProfile( 5550): Bluetooth service disconnected
I/wpa_supplicant( 7075): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 7075): wlan0: Setting scan request: 0 sec 0 usec
,W/Settings( 2418): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine( 2418): ignore requestNetworkTransitionWakelock airplane:true
,V/BluetoothEventManager( 5550): Received android.bluetooth.adapter.action.STATE_CHANGED
,I/wpa_supplicant( 7075): Scan requested (ret=0) - scan timeout 30 seconds
D/WifiP2pService( 2418): InactiveState{ what=143375 }
D/WifiP2pService( 2418): P2pEnabledState{ what=143375 }
,D/GKI_LINUX( 5076): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,I/BluetoothAdapterState( 5076): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,W/ContextImpl( 5550): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/CommandListener( 1915): Clearing all IP addresses on wlan0
D/BluetoothAdapterState( 5076): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 5076): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
E/bt-btif ( 5076): cmd socket is not created
D/btif_config_util( 5076): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
D/ConnectivityService( 2418): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2418): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2418): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2418): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2418): net.tcp.delack.default not found in system default properties
,E/ConnectivityService( 2418): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/IOP_DB_BT( 5076): db_close: nbr users 0
,D/IOP_DB_BT( 5076): db_close: free database
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,E/WifiStateMachine( 2418): Error! unhandled message{ when=-3ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2418): Error! unhandled message{ when=-4ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/DockEventReceiver( 5550): finishStartingService: stopping service
D/WifiP2pService( 2418): InactiveState{ what=131204 }
D/WifiP2pService( 2418): P2pEnabledState{ what=131204 }
D/ConnectivityService( 2418): Attempting to switch to mobile
,D/ConnectivityService( 2418): Attempting to switch to BLUETOOTH_TETHER
D/BluetoothNotiBroadcastReceiver( 5550): onReceive
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/WifiP2pService( 2418): sending p2p connection changed broadcast: FAILED
,W/WifiP2pStateTracker( 2418): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController( 2418): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter( 2418): onP2pDisconnected
D/IpRemoteDisplayController( 2418): disconnectWfdBridgeServer
,D/IpRemoteDisplayController( 2418): WfdBridgeServer is already null
D/QuickConnect[1.1][2] ( 5050): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
D/QuickConnect[1.1][2] ( 5050): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
,D/AuthorizationBluetoothService( 2845): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/WifiP2pService( 2418): sending p2p connection changed broadcast: DISCONNECTED
,E/WifiStateMachine( 2418): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/QuickConnect[1.1][2] ( 5050): SconnectManager.INetworkStateListener, onDisabled - mNetworkState : 0
D/WifiDisplayController( 2418): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 2418): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 2418): disconnect
D/WifiDisplayController( 2418): updateConnection
D/WifiDisplayController( 2418): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayAdapter( 2418): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/QuickConnect[1.1][2] ( 5050): P2pHelper.cancelConnectPeer -  mTargetList clear all 
D/QuickConnect[1.1][2] ( 5050): P2pHelper.removeP2pConfirm - skip: false
,D/QuickConnect[1.1][2] ( 5050): CentralActionManager.removeHoldingIntentAll - all request done.
D/WifiP2pService( 2418): P2pDisablingState
D/WifiP2pService( 2418): P2pDisablingState{ what=139287 }
,D/QuickConnect[1.1][2] ( 5050): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
,V/RouteController( 1915): RTNETLINK answers: No such process
D/WifiP2pService( 2418): DefaultState{ what=139287 }
D/WifiP2pService( 2418): P2pDisablingState{ what=147458 }
D/WifiP2pService( 2418): p2p socket connection lost
D/WifiP2pService( 2418): P2pDisabledState
D/WifiP2pService( 2418): P2pDisabledState{ what=139376 }
D/WifiP2pService( 2418): DefaultState{ what=139376 }
,E/WifiP2pService( 2418): Unhandled message { what=139376 }
V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
,D/QuickConnect[1.1][2] ( 5050): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
D/WifiDisplayController( 2418): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter( 2418): onP2pDisconnected
D/IpRemoteDisplayController( 2418): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 2418): WfdBridgeServer is already null
D/WifiP2pService( 2418): P2pDisabledState{ what=139287 }
,D/QuickConnect[1.1][2] ( 5050): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
D/QuickConnect[1.1][2] ( 5050): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
,D/QuickConnect[1.1][2] ( 5050): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/WifiP2pService( 2418): DefaultState{ what=139287 }
,D/WifiDisplayAdapter( 2418): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
V/RouteController( 1915): RTNETLINK answers: No such file or directory
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
W/WifiP2pStateTracker( 2418): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,W/NetworkManagementService( 2418): route cmd failed: 
W/NetworkManagementService( 2418): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '35 route del src v6 2' failed with '400 35 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
,V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
D/WifiNative( 2418): callSECApiBoolean - ID [13]
I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
,I/wpa_supplicant( 7075): USE_NETWORK : USE_NETWORK OFF
,V/RouteController( 1915): RTNETLINK answers: No such process
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,D/NearbySettings( 5550): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5550): DMSUtil.isNetworkConnected - flag-null, state-null
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,I/NearbySettings( 5550): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
I/NearbySettings( 5550): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 5550): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 5550): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 5550): MountReceiver.mPrefHandler - 7002
D/BluetoothAdapterState( 5076): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 5076): isSecureModeOn:false
W/BluetoothAdapterService( 5076): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5076): Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5076): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5076): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/NetUtils( 2418): android_net_utils_resetConnections in env=0x7ba03018 clazz=0x61000001 iface=wlan0 mask=0x3
,D/ConnectivityService( 2418): resetConnections(wlan0, 3)
E/WifiStateMachine( 2418): Error! unhandled message{ when=-35ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2418): Error! unhandled message{ when=-35ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
,D/HeadsetService( 5076): Received stop request...Stopping profile...
,E/WifiStateMachine( 2418): Error! unhandled message{ when=-23ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2418): Error! unhandled message{ when=-23ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
,W/BluetoothAdapterService( 5076): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,D/QuickConnect[1.1][2] ( 5050): HeadsetProfile.onServiceDisconnected - Bluetooth service disconnected
,W/BluetoothAdapterService( 5076): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/HeadsetProfile( 5550): Bluetooth service disconnected
,W/BluetoothAdapterService( 5076): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5076): Not skipping com.android.bluetooth.hid.HidService
,D/NearbySettings( 5550): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 5550): DMSUtil.isNetworkConnected - flag-null, state-null
W/BluetoothAdapterService( 5076): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
I/NearbySettings( 5550): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,W/BluetoothAdapterService( 5076): Not skipping com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 5076): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5076): Not skipping com.android.bluetooth.pan.PanService
I/NearbySettings( 5550): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 5550): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 5550): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5550): MountReceiver.mPrefHandler - 7002
,W/BluetoothAdapterService( 5076): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5076): Not skipping com.android.bluetooth.map.BluetoothMapService
,V/NativeCrypto( 2845): Read error: ssl=0x750c45a8: I/O error during system call, Connection timed out
,W/BluetoothAdapterService( 5076): check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/FileShare-Server( 5942): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,W/BluetoothAdapterService( 5076): Not skipping com.broadcom.bt.service.sap.SapService
,D/FileShare-Server( 5942): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() DISCONNECTED
,V/NativeCrypto( 2845): SSL shutdown failed: ssl=0x750c45a8: I/O error during system call, Broken pipe
,D/BluetoothAdapterState( 5076): Stopping profile services that were post enabled
,E/SPPClientService( 5468): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5468): [e] exceptionCaught(). NET_TIMEOUT
,D/GKI_LINUX( 5076): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
D/NearbySettings( 5550): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5550): DMSUtil.isNetworkConnected - flag-null, state-null
D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5076): Profile still running: com.broadcom.bt.service.sap.SapService
,I/NearbySettings( 5550): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,E/SPPClientService( 5468): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
I/NearbySettings( 5550): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 5550): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5550): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5550): MountReceiver.mPrefHandler - 7002
W/BluetoothHeadsetServiceJni( 5076): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 5076): Cleaning up Bluetooth Handsfree callback object
,D/A2dpService( 5076): Received stop request...Stopping profile...
,D/Avrcp   ( 5076): Unregistering previous receiver
,D/MediaFocusControl( 2418): <<< unregisterRemoteControlDisplay
D/A2dpStateMachine( 5076): Exit Disconnected: -1
,E/SPPClientService( 5468): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5468): [b] ResponseMap empty
,D/BluetoothA2dp( 2418): Proxy object disconnected
D/BluetoothA2dp( 5050): Proxy object disconnected
D/QuickConnect[1.1][2] ( 5050): A2dpProfile.onServiceConnected - Bluetooth service disconnected
,D/BluetoothA2dp( 5550): Proxy object disconnected
,D/A2dpProfile( 5550): Bluetooth service disconnected
D/HidService( 5076): Received stop request...Stopping profile...
,D/HidService( 5076): Stopping Bluetooth HidService
,D/BluetoothA2dp( 4127): Proxy object disconnected
D/BluetoothInputDevice( 5050): Proxy object disconnected
,D/QuickConnect[1.1][2] ( 5050): HidProfile.onServiceDisconnected - Bluetooth service disconnected
D/BluetoothInputDevice( 5550): Proxy object disconnected
,D/HidProfile( 5550): Bluetooth service disconnected
,D/HealthService( 5076): Received stop request...Stopping profile...
,D/PanService( 5076): Received stop request...Stopping profile...
,D/BluetoothPan( 2418): BluetoothPAN Proxy object disconnected
,D/BluetoothPan( 5550): BluetoothPAN Proxy object disconnected
D/PanProfile( 5550): Bluetooth service disconnected
,D/BluetoothMapService( 5076): Received stop request...Stopping profile...
,D/BluetoothMap( 5550): Proxy object disconnected
D/MapProfile( 5550): Bluetooth service disconnected
D/SapService( 5076): Received stop request...Stopping profile...
,D/SapService( 5076): Stopping Bluetooth SapService
,D/Bluetoothsap( 5550): BluetoothSAP Proxy object disconnected
D/SapProfile( 5550): Bluetooth service disconnected
D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5076): Profile still running: com.broadcom.bt.service.sap.SapService
,I/GKI_LINUX( 5076): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 5076): GKI_exit_task: GKI_exit_task 2 done
,I/GKI_LINUX( 5076): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5076): Profile still running: com.broadcom.bt.service.sap.SapService
I/wpa_supplicant( 7075): p2p0: CTRL-EVENT-TERMINATING 
W/BluetoothHidServiceJni( 5076): Cleaning up Bluetooth HID Interface...
,W/BluetoothHidServiceJni( 5076): Cleaning up Bluetooth GID callback object
D/Tethering( 2418): interfaceLinkStateChanged p2p0, true
,D/Tethering( 2418): interfaceStatusChanged p2p0, true
,D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5076): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothHealthServiceJni( 5076): Cleaning up Bluetooth Health Interface...
D/Tethering( 2418): interfaceLinkStateChanged p2p0, false
D/Tethering( 2418): interfaceStatusChanged p2p0, false
,W/BluetoothHealthServiceJni( 5076): Cleaning up Bluetooth Health object
D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5076): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothPanServiceJni( 5076): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 5076): Cleaning up Bluetooth PAN callback object
,D/BtSettings.ProfileConfig( 5076): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5076): Profile still running: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5076): Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
I/knox    ( 4990): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/BluetoothAdapterState( 5076): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 5076): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 5076): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5076): updateAdapterState state is 10
D/BluetoothAdapterService( 5076): Broadcasting updateAdapterState() to 1 receivers.
W/BluetoothSAPServiceJni( 5076): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
D/BluetoothAdapterService( 5076): Autoconnection is available 
D/BluetoothAdapterService( 5076): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 5076): Entering OffState
,W/BluetoothSAPServiceJni( 5076): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/BluetoothA2dp( 4127): onBluetoothStateChange: up=false
D/Bluetoothsap( 5550): BluetoothSAP Proxy object disconnected
D/SapProfile( 5550): Bluetooth service disconnected
I/wpa_supplicant( 7075): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 7075): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/BluetoothMap( 5550): onBluetoothStateChange: up=false
,D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
W/ContextImpl( 4990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 4990): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 4990): KNOXAgentService : onCreate()
,D/knox    ( 4990): KNOXAgentService : set alarms for deniallog and usage data upload
,D/BluetoothInputDevice( 5550): onBluetoothStateChange: up=false
,D/knox    ( 4990): KNOXAgentService. startJobThread() start
D/knox    ( 4990): KNOXAgentService. JobThread()
,D/knox    ( 4990): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 4990): KNOXAgentService. startJobThread() wait
,D/knox    ( 4990): KNOXAgentService : onDestroy().
,D/knox    ( 4990): ModuleBase.cancelAllAlarmManageModule()
,D/Bluetoothsap( 5550): onBluetoothStateChange: up=false
,D/Bluetoothsap( 5550): Unbinding service...
,D/BluetoothInputDevice( 5050): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 5050): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 5550): onBluetoothStateChange: up=false
D/Bluetoothsap( 5550): onBluetoothStateChange: up=false
,D/Bluetoothsap( 5550): Unbinding service...
,D/BluetoothPbap( 5550): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 2418): onBluetoothStateChange: up=false
W/InputMethodManagerService( 2418): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2418): [BT Setting State] State =10
I/InputMethodManagerService( 2418): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/PhoneApp( 2751): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 10
,I/SamsungIME( 2970): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/QuickConnect[1.1][2] ( 5050): BluetoothHelper.ACTION_STATE_CHANGED - STATE_OFF
,V/BluetoothEventManager( 5550): Received android.bluetooth.adapter.action.STATE_CHANGED
,W/ContextImpl( 5550): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 5550): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 5550): onReceive
,D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
D/BluetoothTethering( 2418): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering( 2418): attempted to stop reverse tether with nothing tethered
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
D/ConnectivityService( 2418): handleInetConditionChange: no active default network - ignore
V/NetworkStats( 2418): updateIfacesLocked()
V/NetworkStats( 2418): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
V/NetworkStats( 2418): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/AuthorizationBluetoothService( 2845): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
V/NetworkStats( 2418): performPollLocked() took 33ms
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/Tethering( 2418): interfaceLinkStateChanged wlan0, false
,D/Tethering( 2418): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 7075): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering( 2418): InitialState.processMessage what=4
,E/Tethering( 2418): No numeric data
,I/ConnectivityService( 2418): defaultVal : 1, tetherEnabledInSettings : true
,D/Tethering( 2418): sendTetherStateChangedBroadcast 0, 0, 0
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
V/NetworkStats( 2418): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,V/NetworkStats( 2418): performPollLocked() took 19ms
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/WifiStateMachine( 2418): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,W/Settings( 7484): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,W/Settings( 2733): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/knox    ( 4990): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 4990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 4990): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 4990): KNOXAgentService : onCreate()
,D/knox    ( 4990): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 4990): KNOXAgentService. startJobThread() start
,D/knox    ( 4990): KNOXAgentService. JobThread()
D/knox    ( 4990): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 4990): KNOXAgentService. startJobThread() wait
,D/knox    ( 4990): KNOXAgentService : onDestroy().
,D/knox    ( 4990): ModuleBase.cancelAllAlarmManageModule()
,D/WifiStateMachine( 2418): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,D/Tethering( 2418): Tethering got CONNECTIVITY_ACTION
D/Tethering( 2418): MasterInitialState.processMessage what=3
,I/ApplicationPolicy( 2418): updateDataUsageMap
,D/CaptivePortalTracker( 2418): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2418): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2578): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2578): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2578): updateDataNetType()
D/STATUSBAR-NetworkController( 2578): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4647): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/PCWCLIENTTRACE_PushUtil( 6171): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6171): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6171): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6171): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6171): noConnectivity : true
,D/libgps  ( 2418): agps_ril_update_network_state: Waiting for IPC connection...
,I/KLMS-2.3.201 : ( 7247): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,I/KLMS-2.3.201 : ( 7247): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449748919043
,I/KLMS-2.3.201 : ( 7247): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/SO_AGENT( 7285): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7285): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 6333): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 6333): [BDLM] already registered in spp
I/SA      ( 6333): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 6333): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 6333): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6333): [OR] == isSIMCardReady false ==
I/SA      ( 6333): [SCU] == networkStateCheck == false
,I/SA      ( 6333): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 6073): Other Intent
,D/com.samsung.app( 7313): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7313): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 7379): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 7379): getCountryCode(): countryCode = PL
,D/Headlines( 7379): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 7379): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 7379): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 7379): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 7379): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 7379): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 7379): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 5700): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/QuickConnect[1.1][2] ( 5050): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5050): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5050): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422d8620
,I/iu.UploadsManager( 5700): num queued entries: 0
,I/iu.UploadsManager( 5700): num updated entries: 0
,I/iu.SyncManager( 5700): NEXT; no task
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,I/Babel   ( 7484): connection state changed from CONNECTED to DISCONNECTED
,I/iu.Environment( 3309): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 3309): num queued entries: 0
,I/iu.UploadsManager( 3309): num updated entries: 0
,I/iu.SyncManager( 3309): NEXT; no task
,E/SPPClientService( 5468): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5468): [SystemStateMoniter] Current Time : 397679
,E/SPPClientService( 5468): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5468): [[SystemStateMonitorService]] No Active Internet
,E/SPPClientService( 5468): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5468): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5468): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,I/ActivityManager( 2418): Killing 6442:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty #43
,V/AlarmManager( 2418): waitForAlarm result :8
,D/Headlines( 7379): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7379): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7379): Breath 521 latestRequest time : 1449748919157 current time : 1449748919678
,D/libgps  ( 2418): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2418): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2418): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2418): agps_ril_update_network_availability: Waiting for IPC connection...
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/libgps  ( 2418): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2418): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2418): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/AmoledAdjustTimer( 2418): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 13
,D/AmoledAdjustTimer( 2418): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2418): waitForAlarm result :8
,D/Headlines( 7379): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7379): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7379): Breath 30522 latestRequest time : 1449748919157 current time : 1449748949679
,D/AmoledAdjustTimer( 2418): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 225s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = -10
,E/Watchdog( 2418): !@Sync 14
,D/AmoledAdjustTimer( 2418): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,V/AlarmManager( 2418): waitForAlarm result :8
,D/Headlines( 7379): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 7379): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7379): Breath 60515 latestRequest time : 1449748919157 current time : 1449748979672
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2418): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 15
,D/AmoledAdjustTimer( 2418): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 275s ago
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2418): waitForAlarm result :8
,D/Headlines( 7379): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7379): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7379): Breath 90540 latestRequest time : 1449748919157 current time : 1449749009697
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2418): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 16
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2418): waitForAlarm result :8
,D/Headlines( 7379): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7379): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7379): Breath 120542 latestRequest time : 1449748919157 current time : 1449749039699
,D/Headlines( 7379): stop 
,D/Headlines( 7379): Breath.onDestroy : 
I/ActivityManager( 2418): Killing 5894:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty #43
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): stay LED for fully charged
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/dalvikvm( 2418): GC_CONCURRENT freed 3560K, 55% free 24736K/54232K, paused 18ms+21ms, total 261ms
D/dalvikvm( 2418): WAIT_FOR_CONCURRENT_GC blocked 223ms
,D/dalvikvm( 2418): WAIT_FOR_CONCURRENT_GC blocked 223ms
,D/PackageManager( 2418): getApplicationInfo - Execution time: 224 ms
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 17
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 18
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 19
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,D/TimaService( 2418): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2418): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2418): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 21
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 455s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 22
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2418): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2418): <AppSync3 Whitelist>
,V/AlarmManager( 2418): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/dalvikvm( 4051): GC_CONCURRENT freed 2883K, 31% free 9725K/14028K, paused 4ms+3ms, total 37ms
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 23
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 525s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 24
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 25
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 292, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 26
,D/AmoledAdjustTimer( 2418): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2418): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 27
,D/AmoledAdjustTimer( 2418): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 28
,D/AmoledAdjustTimer( 2418): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2418): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 29
,D/AmoledAdjustTimer( 2418): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/TimaService( 2418): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2418): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2418): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2418): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/GAV2    ( 7062): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 7062): Thread[disconnect check,5,main]: Disconnected from service
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2418): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 9972
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2418): !@Sync 31
,D/dalvikvm( 2418): GC_CONCURRENT freed 3822K, 55% free 24636K/54232K, paused 25ms+18ms, total 283ms
,D/AmoledAdjustTimer( 2418): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 290, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 765s ago
,E/Watchdog( 2418): !@Sync 32
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): stay LED for fully charged
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2418): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2418): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 33
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 34
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2418): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 855s ago
,E/Watchdog( 2418): !@Sync 35
,V/AlarmManager( 2418): waitForAlarm result :8
,I/SensorManagerA( 2418): getReportingMode :: sensor.mType = 5
,D/LightsService( 2418): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2418): LightSensor setDelay = 200000000
D/Sensors ( 2418): LightSensor setSensorDelay = 200000000
D/Sensors ( 2418): Light sensor flush: not enabled 0
D/Sensors ( 2418): LightSensor enable = 1
D/Sensors ( 2418): LightSensor enableSensor = 1
D/SensorManager( 2418): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 10
,E/SPPClientService( 5468): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,V/AlarmManager( 2418):  next == MAX_VALUE
,E/SPPClientService( 5468): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,D/Sensors ( 2418): LightSensor enable = 0
,D/Sensors ( 2418): LightSensor enableSensor = 0
,D/SensorManager( 2418): unregisterListener ::   
D/LightsService( 2418): [SvcLED]  onSensorChanged::light value = 14
D/LightsService( 2418): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/AmoledAdjustTimer( 2418): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2418): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/ActivityManager( 2418): Waited long enough for: ServiceRecord{448fb000 u0 com.sec.spp.push/.PushClientService}
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 36
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 37
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 950s ago
,E/Watchdog( 2418): !@Sync 38
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 39
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/TimaService( 2418): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2418): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2418): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2418): !@Sync 40
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 10
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 41
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2418): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 42
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2418): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2418): <AppSync3 Whitelist>
,V/AlarmManager( 2418): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 43
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 44
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 1155s ago
,E/Watchdog( 2418): !@Sync 45
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/dalvikvm( 2418): GC_CONCURRENT freed 3678K, 55% free 24649K/54232K, paused 20ms+17ms, total 251ms
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 46
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/dalvikvm( 4051): GC_CONCURRENT freed 2050K, 31% free 9723K/14028K, paused 8ms+2ms, total 40ms
,D/dalvikvm( 4051): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 47
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 48
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 1265s ago
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 49
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2418): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2418): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2418): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 51
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 52
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 53
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 54
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 55
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 56
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 57
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 58
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 59
,V/AlarmManager( 2418): waitForAlarm result :8
,I/SensorManagerA( 2418): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2418): LightSensor setDelay = 200000000
,D/Sensors ( 2418): LightSensor setSensorDelay = 200000000
,D/LightsService( 2418): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2418): Light sensor flush: not enabled 0
D/Sensors ( 2418): LightSensor enable = 1
D/Sensors ( 2418): LightSensor enableSensor = 1
D/SensorManager( 2418): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,E/SPPClientService( 5468): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,D/Sensors ( 2418): LightSensor enable = 0
,D/Sensors ( 2418): LightSensor enableSensor = 0
,D/SensorManager( 2418): unregisterListener ::   
D/LightsService( 2418): [SvcLED]  onSensorChanged::light value = 13
D/LightsService( 2418): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 2418): GC_CONCURRENT freed 3698K, 55% free 24647K/54232K, paused 19ms+15ms, total 250ms
,D/TimaService( 2418): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2418): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2418): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2418): [PWL] Off : 1625s ago
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,I/ProcessStatsService( 2418): Prepared write state in 59ms
,I/ProcessStatsService( 2418): Pruning old procstats: /data/system/procstats/state-2015-12-09-18-11-58.bin
,I/ProcessStatsService( 2418): Prepared write state in 41ms
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 61
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 62
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2418): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2418): <AppSync3 Whitelist>
,V/AlarmManager( 2418): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/dalvikvm( 2774): GC_CONCURRENT freed 8993K, 37% free 18083K/28492K, paused 15ms+9ms, total 80ms
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 63
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 64
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,I/ActivityManager( 2418): Killing 6007:com.sec.android.Kies/1000 (adj 15): empty for 1801s
,I/ActivityManager( 2418): Killing 5971:com.sec.knox.bridge/1000 (adj 15): empty for 1825s
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2418): [PWL] Off : 1755s ago
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 65
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 66
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,I/ActivityManager( 2418): Killing 5511:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty for 1811s
,I/ActivityManager( 2418): Killing 6037:com.google.android.apps.uploader/u0a117 (adj 15): empty for 1851s
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 67
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 68
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 69
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2418): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2418): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2418): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 70
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,I/ActivityManager( 2418): Killing 6378:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1800s
,I/ActivityManager( 2418): Killing 7330:com.sec.android.app.voicenote/1000 (adj 15): empty for 1801s
,I/ActivityManager( 2418): Killing 7205:com.google.android.youtube/u0a175 (adj 15): empty for 1801s
,I/ActivityManager( 2418): Killing 5756:com.sec.android.app.videoplayer/u0a53 (adj 15): empty for 1801s
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/dalvikvm( 4051): GC_CONCURRENT freed 2047K, 31% free 9723K/14020K, paused 3ms+3ms, total 50ms
,D/dalvikvm( 4051): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime(13758): 
D/AndroidRuntime(13758): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(13758): CheckJNI is OFF
D/AndroidRuntime(13758): setted country_code = Poland
D/AndroidRuntime(13758): setted countryiso_code = PL
D/AndroidRuntime(13758): setted sales_code = PLS
D/AndroidRuntime(13758): readGMSProperty: start
D/AndroidRuntime(13758): readGMSProperty: already setted!!
D/AndroidRuntime(13758): readGMSProperty: end
D/AndroidRuntime(13758): addProductProperty: start
D/dalvikvm(13758): Trying to load lib libjavacore.so 0x0
D/dalvikvm(13758): Added shared lib libjavacore.so 0x0
D/dalvikvm(13758): Trying to load lib libnativehelper.so 0x0
D/dalvikvm(13758): Added shared lib libnativehelper.so 0x0
D/dalvikvm(13758): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack(13758): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug(13758): failed to load memtrack module: -2
D/dalvikvm(13758): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime(13758): Calling main entry com.android.commands.pm.Pm
D/AmoledAdjustTimer( 2418): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
D/PackageManager( 2418): START PACKAGE DELETE: observer{1126986816}
D/PackageManager( 2418): pkg{<packageName>}
D/PackageManager( 2418): user{0}
D/PackageManager( 2418): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager( 2418): [MSG] DELETE_PACKAGE_AS_USER
D/ApplicationPolicy( 2418): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2418): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2418): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2418): !@killApplicatoin: 10527, uninstall pkg
I/ActivityManager( 2418): Killing 7013:com.test.thalitest/u0a527 (adj 0): stop com.test.thalitest
I/ActivityManager( 2418): Killing 7545:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1800s
I/ActivityManager( 2418): Killing 7526:com.android.calendar/u0a144 (adj 15): empty for 1801s
I/ActivityManager( 2418): Killing 6020:com.android.chrome/u0a85 (adj 15): empty for 1802s
I/ActivityManager( 2418): Killing 7457:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1803s
D/PointerIcon( 2418): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2418): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2418): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2418): setHoveringSpenCustomIcon IconType is same.1
I/SurfaceFlinger( 1920): id=20 Removed EimLayer (5/10)
I/SurfaceFlinger( 1920): id=20 Removed EimLayer (-2/10)
I/SurfaceFlinger( 1920): id=19 Removed EimLayer (4/9)
I/SurfaceFlinger( 1920): id=19 Removed EimLayer (-2/9)
V/WindowManager( 2418): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
W/InputDispatcher( 2418): channel ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher( 2418): channel ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher( 2418): Attempted to unregister already unregistered input channel
I/SurfaceFlinger( 1920): id=21 Removed NainActivit (6/8)
I/WindowState( 2418): WIN DEATH: Window{423bb278 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1920): id=21 Removed NainActivit (-2/8)
I/SurfaceFlinger( 1920): id=21 Removed NainActivit (-2/8)
D/Launcher( 2774): onRestart, Launcher: 1110430304
D/Launcher( 2774): onStart, Launcher: 1110430304
D/Launcher.HomeView( 2774): onStart
D/dalvikvm( 2418): GC_CONCURRENT freed 3751K, 55% free 24707K/54232K, paused 12ms+17ms, total 212ms
D/dalvikvm( 2418): WAIT_FOR_CONCURRENT_GC blocked 166ms
D/dalvikvm( 2418): WAIT_FOR_CONCURRENT_GC blocked 166ms
I/SurfaceFlinger( 1920): id=24 createSurf (720x1280),1 flag=4, Mauncher
D/STATUSBAR-StatusBarManagerService( 2418): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2418): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2418): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2418): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2418): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2418): setHoveringSpenCustomIcon IconType is same.1
D/StatusBarManagerService( 2418): tr p:2774,o:f
D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2418): semi p:2774,o:f
W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 2418): Got RemoteException sending setActive(false) notification to pid 7013 uid 10527
W/PackageSettings( 2418): Skipping PackageSetting{42b8fe78 com.example.hello/10511} due to missing metadata
D/PackageManager( 2418): checkUidPermission - Execution time: 375 ms
D/PackageManager( 2418): checkUidPermission - Execution time: 325 ms
D/PackageManager( 2418): checkUidPermission - Execution time: 127 ms
D/PackageManager( 2418): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10527, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/PackageManager( 2418): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10527, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/FPMS_FingerprintManagerService( 2598): onReceive: android.intent.action.PACKAGE_REMOVED
E/SamsungIME( 2970): mOCRHelper is null
D/QuickConnect[1.1][2] ( 5050): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
D/dalvikvm( 3309): GC_EXPLICIT freed 421K, 22% free 12453K/15780K, paused 9ms+39ms, total 150ms
W/SQLiteConnectionPool( 3309): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/dalvikvm( 5924): GC_EXPLICIT freed 574K, 30% free 9985K/14068K, paused 8ms+5ms, total 128ms
W/GeofencerStateMachine( 2733): Ignoring removeGeofence because network location is disabled.
D/RCPManagerService( 2418): PackageReceiver onReceive()
D/dalvikvm( 2951): GC_EXPLICIT freed 1468K, 29% free 10034K/13988K, paused 15ms+8ms, total 140ms
I/HarmonyEASService( 2418): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/elm:14132( 7692): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2418):   Scheme: "sms"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 7692): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 7692): ElmAgentService : onCreate()
D/elm:14132( 7692): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 7692): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 7692): MDMBridge.getInstance()
D/elm:14132( 7692): MDMBridge.getAllLicenseInfoFromSDK()
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2418):   Scheme: "smsto"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/InputReader( 2418): Reconfiguring input devices.  changes=0x00000010
D/elm:14132( 7692): MDMBridge.getAllLicenseInfoFromSDK()
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2418):   Scheme: "mms"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (13791): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13791):  
D/RegisteredServicesCache( 2755): empty dynamic service
D/elm:14132( 7692): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2418):   Scheme: "mmsto"
D/elm:14132( 7692): ElmAgentService : onDestroy().
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 14% free 9502K/10968K, paused 3ms+3ms, total 37ms
I/SELinux (13791): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13791):  
I/SELinux (13791):  
I/SELinux (13791): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13791): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13791): >>>>> Normal User
E/dalvikvm(13791): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 14% free 9502K/10968K, paused 2ms+3ms, total 26ms
E/SELinux (13791): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(13791): in addTimaSignatureService
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 14% free 9502K/10968K, paused 2ms+4ms, total 26ms
D/TimaKeyStoreProvider(13791): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13791): Added TimaKesytore provider
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2418):   Scheme: "sms"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2418):   Scheme: "smsto"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2418):   Scheme: "mms"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2418):   Scheme: "mmsto"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(13791): GC_CONCURRENT freed 2997K, 32% free 9567K/13988K, paused 3ms+1ms, total 20ms
D/dalvikvm(13791): WAIT_FOR_CONCURRENT_GC blocked 13ms
D/EnterpriseDeviceManagerService( 2418): Package has changed for user 0
D/dalvikvm( 2418): GC_EXPLICIT freed 1452K, 55% free 24798K/54232K, paused 13ms+25ms, total 397ms
D/PackageManager( 2418): delete sourFile : 
D/BackupManagerService( 2418): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 2418): removePackageParticipantsLocked: uid=10527 #1
W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (13803): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13803):  
W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (13803): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13803):  
I/SELinux (13803):  
I/SELinux (13803): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13803): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(13803): >>>>> Normal User
E/dalvikvm(13803): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
E/SELinux (13803): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/PackageManager( 2418): delete native library directory: 
D/PackageManager( 2418): return delete result to caller: 1126986816
D/PackageManager( 2418): returnCode: 1
D/AndroidRuntime(13758): Shutting down VM
D/TimaKeyStoreProvider(13803): in addTimaSignatureService
D/dalvikvm(13758): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+1ms, total 6ms
D/TimaKeyStoreProvider(13803): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13803): Added TimaKesytore provider
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2418):   Scheme: "sms"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2418):   Scheme: "smsto"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2418):   Scheme: "mms"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2418):   Scheme: "mmsto"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(13803): GC_CONCURRENT freed 3007K, 32% free 9565K/13992K, paused 4ms+2ms, total 38ms
D/dalvikvm(13803): WAIT_FOR_CONCURRENT_GC blocked 29ms
W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PCWCLIENTTRACE_PushUtil( 6171): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6171): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6171): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6171): [onReceive] - android.intent.action.PACKAGE_REMOVED
W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (13816): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13816):  
I/ActivityManager( 2418): Killing 7665:com.samsung.android.scloud.sync/u0a64 (adj 15): empty for 1800s
I/SELinux (13816): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13816):  
I/SELinux (13816):  
I/SELinux (13816): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13816): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13816): >>>>> Normal User
E/dalvikvm(13816): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
E/SELinux (13816): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(13816): in addTimaSignatureService
D/TimaKeyStoreProvider(13816): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13816): Added TimaKesytore provider
W/ApplicationsProvider( 2951): Could not fetch usage stats
W/ApplicationsProvider( 2951): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2951): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2951): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2951): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2951): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2951): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2951): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2951): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2951): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2951): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2951): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2951): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(13816): GC_CONCURRENT freed 2994K, 32% free 9569K/13988K, paused 5ms+2ms, total 27ms
D/dalvikvm(13816): WAIT_FOR_CONCURRENT_GC blocked 18ms
W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector( 2418): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2418): clearDefaults: com.test.thalitest
W/AtomicFile( 2418): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl( 2418): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/System.err(13816): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err(13816): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err(13816): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err(13816): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err(13816): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err(13816): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err(13816): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err(13816): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err(13816): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err(13816): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err(13816): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err(13816): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err(13816): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err(13816): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err(13816): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err(13816): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(13816): 	at android.os.Looper.loop(Looper.java:146)
W/System.err(13816): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err(13816): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err(13816): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err(13816): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err(13816): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err(13816): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err(13816): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err(13816): 	at libcore.io.Posix.open(Native Method)
W/System.err(13816): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err(13816): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err(13816): 	... 21 more
D/GalaxyFinderApplication(13816): [Slink platform] Version = 29011
D/GalaxyFinderApplication(13816): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux (13833): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13833):  
I/ActivityManager( 2418): Killing 7678:com.sec.android.app.clockpackage/u0a88 (adj 15): empty for 1800s
I/SELinux (13833): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13833):  
I/SELinux (13833):  
I/SELinux (13833): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13833): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(13833): >>>>> Normal User
E/dalvikvm(13833): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
E/SELinux (13833): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(13833): in addTimaSignatureService
D/TimaKeyStoreProvider(13833): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13833): Added TimaKesytore provider
D/dalvikvm(13833): GC_CONCURRENT freed 2998K, 32% free 9568K/13988K, paused 3ms+2ms, total 24ms
D/dalvikvm(13833): WAIT_FOR_CONCURRENT_GC blocked 20ms
W/ContextImpl(13833): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
I/ActivityManager( 2418): Killing 7709:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty for 1800s
E/Device Type Shared Preferences(13833): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences(13833): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication(13833): ContentProvider is not null
I/ActivityManager( 2418): Killing 7721:com.sec.android.app.taskmanager/u0a168 (adj 15): empty for 1800s
W/ResourceType(13833): No package identifier when getting value for resource number 0x00000000
I/System.out(13833): resource Id::2131361807
E/SQLiteDatabase(13833): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(13833): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13833): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(13833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(13833): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13833): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(13833): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(13833): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(13833): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(13833): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(13833): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(13833): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(13833): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/SQLiteDatabase(13833): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/SQLiteDatabase(13833): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/SQLiteDatabase(13833): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase(13833): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase(13833): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase(13833): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase(13833): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/SQLiteDatabase(13833): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/SQLiteDatabase(13833): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/SQLiteDatabase(13833): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/SQLiteDatabase(13833): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/SQLiteDatabase(13833): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/SQLiteDatabase(13833): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/SQLiteDatabase(13833): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(13833): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(13833): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13833): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(13833): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(13833): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(13833): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(13833): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(13833): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(13833): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(13833): Shutting down VM
W/dalvikvm(13833): threadid=1: thread exiting with uncaught exception (group=0x41821c08)
E/AndroidRuntime(13833): FATAL EXCEPTION: main
E/AndroidRuntime(13833): Process: com.sec.android.app.shealth, PID: 13833
E/AndroidRuntime(13833): java.lang.RuntimeException: Unable to create application com.sec.android.app.shealth.SHealthApplication: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13833): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4793)
E/AndroidRuntime(13833): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(13833): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(13833): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(13833): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(13833): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(13833): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(13833): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(13833): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(13833): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(13833): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(13833): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13833): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(13833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(13833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(13833): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(13833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(13833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(13833): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(13833): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(13833): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(13833): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(13833): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(13833): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/AndroidRuntime(13833): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/AndroidRuntime(13833): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/AndroidRuntime(13833): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/AndroidRuntime(13833): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/AndroidRuntime(13833): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/AndroidRuntime(13833): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/AndroidRuntime(13833): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/AndroidRuntime(13833): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/AndroidRuntime(13833): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/AndroidRuntime(13833): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/AndroidRuntime(13833): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/AndroidRuntime(13833): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/AndroidRuntime(13833): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/AndroidRuntime(13833): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/AndroidRuntime(13833): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/AndroidRuntime(13833): 	... 10 more
E/DropBoxManagerService( 2418): Can't write: system_app_crash
E/DropBoxManagerService( 2418): java.io.FileNotFoundException: /data/system/dropbox/drop230.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2418): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2418): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2418): 	... 5 more
I/SELinux (13853): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13853):  
I/Process (13833): Sending signal. PID: 13833 SIG: 9
I/ActivityManager( 2418): Process com.sec.android.app.shealth (pid 13833) (adj 0) has died.
I/SELinux (13853): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13853):  
I/SELinux (13853):  
I/SELinux (13853): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13853): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm(13853): >>>>> Normal User
E/dalvikvm(13853): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10043 ]
E/SELinux (13853): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider(13853): in addTimaSignatureService
D/TimaKeyStoreProvider(13853): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13853): Added TimaKesytore provider
D/dalvikvm(13853): GC_CONCURRENT freed 3002K, 32% free 9569K/13992K, paused 2ms+2ms, total 24ms
D/dalvikvm(13853): WAIT_FOR_CONCURRENT_GC blocked 21ms
E/SQLiteDatabase(13853): Failed to open database '/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db'.
E/SQLiteDatabase(13853): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13853): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13853): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(13853): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(13853): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13853): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13853): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13853): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(13853): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(13853): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(13853): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(13853): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(13853): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(13853): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(13853): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:429)
E/SQLiteDatabase(13853): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase(13853): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase(13853): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase(13853): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase(13853): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase(13853): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(13853): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(13853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13853): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(13853): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(13853): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(13853): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(13853): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(13853): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(13853): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(13853): Shutting down VM
W/dalvikvm(13853): threadid=1: thread exiting with uncaught exception (group=0x41821c08)
E/AndroidRuntime(13853): FATAL EXCEPTION: main
E/AndroidRuntime(13853): Process: com.samsung.android.sdk.samsunglink, PID: 13853
E/AndroidRuntime(13853): java.lang.RuntimeException: Unable to get provider com.mfluent.asp.datamodel.ASPMediaStoreProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13853): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime(13853): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime(13853): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime(13853): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(13853): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(13853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(13853): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(13853): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(13853): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(13853): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(13853): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(13853): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(13853): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(13853): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13853): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(13853): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(13853): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(13853): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(13853): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(13853): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(13853): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(13853): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(13853): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(13853): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(13853): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(13853): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime(13853): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime(13853): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:429)
E/AndroidRuntime(13853): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime(13853): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime(13853): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime(13853): 	... 12 more
E/DropBoxManagerService( 2418): Can't write: system_app_crash
E/DropBoxManagerService( 2418): java.io.FileNotFoundException: /data/system/dropbox/drop231.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2418): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2418): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2418): 	... 5 more
I/Process (13853): Sending signal. PID: 13853 SIG: 9
I/SA      ( 6333): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
I/SA      ( 6333): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
I/ActivityManager( 2418): Process com.samsung.android.sdk.samsunglink (pid 13853) (adj 9) has died.
E/SharedPreferencesImpl( 3593): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
I/Icing.InternalIcingCorporaProvider( 5924): Updating corpora: A: com.test.thalitest, C: MAYBE
E/SQLiteLog( 5924): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 5924): threadid=15: thread exiting with uncaught exception (group=0x41821c08)
E/AndroidRuntime( 5924): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 5924): Process: com.google.android.googlequicksearchbox:search, PID: 5924
E/AndroidRuntime( 5924): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 5924): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 5924): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 5924): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 5924): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 5924): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 5924): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 5924): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:171)
E/AndroidRuntime( 5924): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 5924): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
E/AndroidRuntime( 5924): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 5924): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 5924): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 5924): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 5924): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 5924): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 5924): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 5924): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5924): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5924): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 5924): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
