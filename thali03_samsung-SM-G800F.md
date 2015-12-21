#### Test 54312298c831015_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/BatteryService( 2411): stay LED for fully charged
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime( 7248): 
D/AndroidRuntime( 7248): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7248): CheckJNI is OFF
D/AndroidRuntime( 7248): setted country_code = Poland
D/AndroidRuntime( 7248): setted countryiso_code = PL
D/AndroidRuntime( 7248): setted sales_code = PLS
D/AndroidRuntime( 7248): readGMSProperty: start
D/AndroidRuntime( 7248): readGMSProperty: already setted!!
D/AndroidRuntime( 7248): readGMSProperty: end
D/AndroidRuntime( 7248): addProductProperty: start
D/dalvikvm( 7248): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7248): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7248): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7248): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7248): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7248): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7248): failed to load memtrack module: -2
D/dalvikvm( 7248): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7248): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2411): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2411): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  pkgName : ACTIVITY_RESUME_BOOSTER@4
I/SurfaceFlinger( 1920): id=22 createSurf (16x16),-1 flag=20004, EimLayer
W/ActivityManager( 2411): mDVFSHelper.acquire()
I/SurfaceFlinger( 1920): id=23 createSurf (16x16),-1 flag=20004, EimLayer
I/SELinux ( 7259): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7259):  
D/PointerIcon( 2411): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2411): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2411): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2411): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7248): Shutting down VM
D/dalvikvm( 7248): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+0ms, total 3ms
I/SELinux ( 7259): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7259):  
I/SELinux ( 7259):  
I/SELinux ( 7259): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7259): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7259): >>>>> Normal User
E/dalvikvm( 7259): >>>>> com.test.thalitest [ userId:0 | appId:10574 ]
E/SELinux ( 7259): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7259): in addTimaSignatureService
D/TimaKeyStoreProvider( 7259): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7259): Added TimaKesytore provider
V/WindowManager( 2411): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SQLiteSecureOpenHelper( 4175): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4175): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=19 Removed Mauncher (8/10)
I/SurfaceFlinger( 1920): id=19 Removed Mauncher (-2/10)
D/Launcher( 2774): onTrimMemory. Level: 20
D/dalvikvm( 7259): GC_CONCURRENT freed 3014K, 32% free 9558K/14040K, paused 2ms+1ms, total 18ms
D/dalvikvm( 7259): WAIT_FOR_CONCURRENT_GC blocked 15ms
V/WebViewChromium( 7259): Binding Chromium to the background looper Looper (main, tid 1) {425e0360}
I/chromium( 7259): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7259): Initializing chromium process, renderers=0
W/chromium( 7259): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7259): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7259): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7259): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7259): Mali API Version : 401
,I/Mali    ( 7259): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7259): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7259): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7259): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7259): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7259): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 7259): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2579): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2411): tr p:7259,o:f
,W/dalvikvm( 7259): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7259): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7259): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7259): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7259): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7259): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7259): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7259): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 7259): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7259): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7259): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7259): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7259): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2579): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2411): semi p:7259,o:f
,I/SurfaceFlinger( 1920): id=24 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2411): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2411): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2411): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2411): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2411): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2411): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7259): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7259): Enabling debug mode 0
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/AwContents( 7259): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 7259): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2411): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2411): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2411): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/JsMessageQueue( 7259): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7259): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x425d9128
,D/dalvikvm( 7259): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x425d9128
D/jxcore_app_log( 7259): JniHelper::setJavaVM(0x41b1b220), pthread_self() = 2030938320
,D/JX-Cordova( 7259): jxcore cordova android initializing
,D/dalvikvm( 7259): GC_CONCURRENT freed 1265K, 20% free 11364K/14096K, paused 1ms+2ms, total 24ms
,D/dalvikvm( 7259): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 7259): GC_CONCURRENT freed 2038K, 20% free 14933K/18452K, paused 3ms+2ms, total 42ms
,D/dalvikvm( 7259): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/CustomFrequencyManagerService( 2411): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7259): GC_FOR_ALLOC freed 5204K, 31% free 16170K/23120K, paused 48ms, total 48ms
,D/dalvikvm( 7259): GC_CONCURRENT freed 6689K, 32% free 17649K/25828K, paused 2ms+11ms, total 65ms
,D/dalvikvm( 7259): WAIT_FOR_CONCURRENT_GC blocked 41ms
,D/dalvikvm( 7259): GC_FOR_ALLOC freed 1256K, 33% free 17499K/25828K, paused 51ms, total 51ms
,I/dalvikvm-heap( 7259): Grow heap (frag case) to 22.060MB for 3713210-byte allocation
,D/dalvikvm( 7259): GC_FOR_ALLOC freed 2453K, 37% free 18672K/29456K, paused 49ms, total 49ms
,W/jxcore-log( 7259): Initializing JXcore engine
,W/jxcore-log( 7259): JXcore engine is ready
,W/jxcore-log( 7259): Starting JXcore engine
,D/AmoledAdjustTimer( 2411): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4
,W/jxcore-log( 7259): Platform android
W/jxcore-log( 7259): 
,W/jxcore-log( 7259): Process ARCH arm
W/jxcore-log( 7259): 
,I/PowerManagerService( 2411): [PWL] Off : 105s ago
,I/jxcore-log( 7259): JXcore Cordova bridge is ready!
I/jxcore-log( 7259): 
,W/jxcore-log( 7259): JXcore engine is started
,I/chromium( 7259): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7259): Toggling radios to true
I/jxcore-log( 7259): 
,D/BluetoothAdapter( 7259): enable(): BT is already enabled..!
,I/WifiManager( 7259): packageName : com.test.thalitest
,I/WifiManager( 7259): setWifiEnabled : true
,I/WifiService( 2411): setWifiEnabled: true pid=7259, uid=10574
,W/ActivityManager( 2411): Permission Denial: getCurrentUser() from pid=7259, uid=10574 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2411): Failed getting userId using ActivityManagerNative
W/WifiService( 2411): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7259, uid=10574 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2411): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2411): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2411): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2411): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2411): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2411): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2411): disconnect: pid=7259, uid=10574
I/wpa_supplicant( 3970): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7259): Radios toggled
I/jxcore-log( 7259): 
,I/jxcore-log( 7259): Got Device Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 7259): 
,I/jxcore-log( 7259): Perf Test app loaded loaded
I/jxcore-log( 7259): 
,I/wpa_supplicant( 3970): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3970): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2411): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2411): interfaceStatusChanged wlan0, true
D/Tethering( 2411): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2411): interfaceStatusChanged wlan0, true
,I/jxcore-log( 7259): check test folder
I/jxcore-log( 7259): 
I/wpa_supplicant( 3970): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3970): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3970): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3970): First Scan Start
W/Settings( 2411): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2411): ignore requestNetworkTransitionWakelock airplane:true
,I/wpa_supplicant( 3970): Scan requested (ret=0) - scan timeout 30 seconds
,I/jxcore-log( 7259): found test : ./testFindPeers.js
I/jxcore-log( 7259): 
D/WifiP2pService( 2411): InactiveState{ what=143375 }
D/WifiP2pService( 2411): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/CommandListener( 1915): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2411): evaluateTrafficStatsPolling
I/wpa_supplicant( 3970): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3970): Skip scan - already scanning
D/ConnectivityService( 2411): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/WifiP2pService( 2411): InactiveState{ what=143375 }
D/ConnectivityService( 2411): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2411): net.tcp.usercfg.default not found in system default properties
D/WifiP2pService( 2411): P2pEnabledState{ what=143375 }
E/ConnectivityService( 2411): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2411): net.tcp.delack.default not found in system default properties
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2411): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2411): Attempting to switch to mobile
,D/ConnectivityService( 2411): Attempting to switch to BLUETOOTH_TETHER
,I/SELinux ( 7306): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7306):  
D/STATUSBAR-IconMerger( 2579): checkOverflow(336), More:false, Req:false Child:3
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
,I/jxcore-log( 7259): found test : ./testSendData.js
I/jxcore-log( 7259): 
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
,W/NetworkManagementService( 2411): route cmd failed: 
W/NetworkManagementService( 2411): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '36 route del src v6 2' failed with '400 36 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2411): '
W/NetworkManagementService( 2411): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2411): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2411): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2411): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2411): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2411): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2411): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2411): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2411): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2411): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2411): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2411): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2411): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
,I/SELinux ( 7306): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7306):  
I/SELinux ( 7306):  
,I/SELinux ( 7306): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7306): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7306): >>>>> Normal User
E/dalvikvm( 7306): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
I/WifiTrafficPoller( 2411): evaluateTrafficStatsPolling
,E/SELinux ( 7306): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,E/WifiStateMachine( 2411): Error! unhandled message{ when=-96ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/WifiStateMachine( 2411): Error! unhandled message{ when=-98ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,E/WifiStateMachine( 2411): Error! unhandled message{ when=-12ms what=135188 target=com.android.internal.util.StateMachine$SmHandler },
,D/NetUtils( 2411): android_net_utils_resetConnections in env=0x77e59888 clazz=0x62200001 iface=wlan0 mask=0x3,
,D/TimaKeyStoreProvider( 7306): in addTimaSignatureService,
D/ConnectivityService( 2411): resetConnections(wlan0, 3)
,D/TimaKeyStoreProvider( 7306): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7306): Added TimaKesytore provider,
,I/jxcore-log( 7259): found test : ./testSendData2.js,
I/jxcore-log( 7259): 
,E/jxcore  ( 7259): Error!: missing ) after argument list,
E/jxcore  ( 7259): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
I/chromium( 7259): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/NativeCrypto( 2852): Read error: ssl=0x7c58b148: I/O error during system call, Connection timed out,
,V/NativeCrypto( 2852): SSL shutdown failed: ssl=0x7c58b148: I/O error during system call, Broken pipe,
,D/dalvikvm( 7306): GC_CONCURRENT freed 2994K, 32% free 9572K/14036K, paused 7ms+2ms, total 42ms
,D/dalvikvm( 7306): WAIT_FOR_CONCURRENT_GC blocked 29ms
,E/SPPClientService( 5584): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5584): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5584): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5584): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5584): [b] ResponseMap empty
,I/System.out( 7306): Inside WakeupProvider
,I/System.out( 7306): Inside onCreate() of WakeupTriggerProvide
,D/ConnectivityService( 2411): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
V/NetworkStats( 2411): updateIfacesLocked()
,V/NetworkStats( 2411): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
V/NetworkStats( 2411): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/VlingoApplication( 7306): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7306): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7306): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
V/NetworkStats( 2411): performPollLocked() took 32ms
,D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
,D/NearbySettings( 5724): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5724): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5724): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 5724): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5724): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5724): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5724): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2411): Killing 5439:com.google.android.talk/u0a109 (adj 15): empty #43
,D/DialogFlow( 7306): initQueue()
,D/NearbySettings( 5724): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5724): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5724): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 5724): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5724): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5724): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5724): MountReceiver.mPrefHandler - 7002
,I/SELinux ( 7335): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7335):  
,I/SELinux ( 7335): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7335):  
I/SELinux ( 7335):  
,I/SELinux ( 7335): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7335): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7335): >>>>> Normal User
,E/dalvikvm( 7335): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
,E/SELinux ( 7335): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7335): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7335): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7335): Added TimaKesytore provider
,I/ApplicationPolicy( 2411): updateDataUsageMap
,D/Tethering( 2411): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2411): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2411): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2411): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2579): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2579): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2579): updateDataNetType()
,D/STATUSBAR-NetworkController( 2579): NoService, mRoamingIconId = 0
D/dalvikvm( 7335): GC_CONCURRENT freed 2997K, 32% free 9569K/14036K, paused 3ms+2ms, total 36ms
D/dalvikvm( 7335): WAIT_FOR_CONCURRENT_GC blocked 32ms
,I/DBG_DM  ( 4788): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2411): agps_ril_update_network_state: Waiting for IPC connection...
,I/dalvikvm( 7335): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 7335): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 7335): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 7335): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7335): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7335): VFY: replacing opcode 0x22 at 0x0000
,E/dalvikvm( 7335): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
W/dalvikvm( 7335): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 7335): VFY: replacing opcode 0x22 at 0x0037
,W/dalvikvm( 7335): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7335): Link of class 'Ldqp;' failed
,W/dalvikvm( 7335): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7335): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7335): Link of class 'Ldqp;' failed
I/dalvikvm( 7335): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 7335): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 7335): VFY: replacing opcode 0x6e at 0x0000
I/wpa_supplicant( 3970): nl80211: Received scan results (4 BSSes)
I/wpa_supplicant( 3970): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3970): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3970): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/dalvikvm( 7335): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7335): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7335): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 7335): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7335): Link of class 'Ldqp;' failed
,W/dalvikvm( 7335): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7335): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7335): Link of class 'Ldqp;' failed
I/dalvikvm( 7335): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 7335): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
,D/dalvikvm( 7335): VFY: replacing opcode 0x6e at 0x0008
E/dalvikvm( 7335): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 7335): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
,D/dalvikvm( 7335): VFY: replacing opcode 0x1c at 0x0026
,W/dalvikvm( 7335): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7335): Link of class 'Ldqp;' failed
,W/dalvikvm( 7335): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7335): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 7335): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7335): Link of class 'Ldqp;' failed
,I/dalvikvm( 7335): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 7335): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
,D/dalvikvm( 7335): VFY: replacing opcode 0x6e at 0x0003
,W/dalvikvm( 7335): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7335): Link of class 'Lax;' failed
E/dalvikvm( 7335): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 7335): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
,D/dalvikvm( 7335): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 7335): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7335): Link of class 'Laz;' failed
,E/dalvikvm( 7335): Could not find class 'az', referenced from method g.a
W/dalvikvm( 7335): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
D/dalvikvm( 7335): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 7335): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
,W/dalvikvm( 7335): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7335): VFY: replacing opcode 0x6e at 0x0008
,I/dalvikvm( 7335): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
W/dalvikvm( 7335): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 7335): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 7335): Could not find method android.view.View.getTransitionName, referenced from method g.a
,W/dalvikvm( 7335): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7335): VFY: replacing opcode 0x6e at 0x0006
D/Tethering( 2411): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2411): interfaceStatusChanged wlan0, true
I/dalvikvm( 7335): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 7335): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
,D/dalvikvm( 7335): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 7335): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 7335): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
,D/dalvikvm( 7335): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7335): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
W/dalvikvm( 7335): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 7335): VFY: replacing opcode 0x72 at 0x0000
,I/dalvikvm( 7335): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 7335): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 7335): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 7335): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 7335): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
,W/dalvikvm( 7335): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 7335): VFY: replacing opcode 0x23 at 0x0005
,I/wpa_supplicant( 3970): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2411): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2411): interfaceStatusChanged wlan0, true
D/Tethering( 2411): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2411): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3970): Associated with C0.AA.48
D/Tethering( 2411): interfaceLinkStateChanged wlan0, true
D/Tethering( 2411): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3970): freq(2412) increment count 2
,I/wpa_supplicant( 3970): meet head of list.
,I/dalvikvm( 7335): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
W/dalvikvm( 7335): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7335): VFY: replacing opcode 0x6e at 0x0009
,I/wpa_supplicant( 3970): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3970): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3970): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3970): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3970): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2411): interfaceLinkStateChanged wlan0, true
D/Tethering( 2411): interfaceStatusChanged wlan0, true
,D/WifiNative( 2411): callSECApiVoid - ID [50]
,W/dalvikvm( 7335): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
,W/dalvikvm( 7335): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 7335): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 7335): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
,D/dalvikvm( 7335): VFY: replacing opcode 0x1c at 0x0002
,E/dalvikvm( 7335): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 7335): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 7335): VFY: replacing opcode 0x1f at 0x000c
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/dalvikvm( 7335): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7335): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7335): VFY: replacing opcode 0x62 at 0x0006
,D/dalvikvm( 7335): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7335): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
,D/dalvikvm( 7335): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7335): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
,D/dalvikvm( 7335): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
W/dalvikvm( 7335): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7335): Link of class 'Lax;' failed
,D/dalvikvm( 7335): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 7335): Unable to resolve superclass of Laz; (841)
,W/dalvikvm( 7335): Link of class 'Laz;' failed
D/dalvikvm( 7335): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 7335): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
,D/dalvikvm( 7335): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,D/dalvikvm( 7335): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x425daaf8
,D/dalvikvm( 7335): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x425daaf8
,D/WifiP2pService( 2411): InactiveState{ what=143375 }
,D/WifiP2pService( 2411): P2pEnabledState{ what=143375 }
,I/dalvikvm( 7335): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
W/dalvikvm( 7335): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 7335): VFY: replacing opcode 0x6e at 0x0076
,I/Babel_SMS( 7335): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7335): MmsConfig.loadMmsSettings
I/Babel_SMS( 7335): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/Babel_SMS( 7335): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7335): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7335): MmsConfig.loadFromResources
,E/Babel_SMS( 7335): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7335): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,W/dalvikvm( 7335): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7335): Link of class 'Lfzc;' failed
E/dalvikvm( 7335): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 7335): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
,D/dalvikvm( 7335): VFY: replacing opcode 0x22 at 0x0033
,W/dalvikvm( 7335): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7335): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7335): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
,W/dalvikvm( 7335): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
I/dalvikvm( 7335): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 7335): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
,D/dalvikvm( 7335): VFY: replacing opcode 0x74 at 0x006d
I/dalvikvm( 7335): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 7335): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
,D/dalvikvm( 7335): VFY: replacing opcode 0x6e at 0x0033
I/dalvikvm( 7335): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 7335): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
,D/dalvikvm( 7335): VFY: replacing opcode 0x6e at 0x0030
W/dalvikvm( 7335): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7335): Link of class 'Lfzc;' failed
,D/dalvikvm( 7335): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
E/SensorService( 2411): Permission Denial : SEC Private Sensor 
,E/SensorService( 2411): Permission Denial : SEC Private Sensor 
,D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,W/Settings( 7335): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7335): startup - clean
,D/dalvikvm( 7335): GC_CONCURRENT freed 1780K, 24% free 10862K/14108K, paused 5ms+4ms, total 46ms
,D/dalvikvm( 7335): WAIT_FOR_CONCURRENT_GC blocked 13ms
D/dalvikvm( 7335): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 7335): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/dalvikvm( 7335): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
,W/dalvikvm( 7335): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7335): VFY: replacing opcode 0x6e at 0x000d
,I/Babel   ( 7335): deleted: false for 0
,I/dhcpcd  ( 7357): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7357): bssid match
,W/dalvikvm( 7335): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
I/dalvikvm( 7335): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 7335): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
,D/dalvikvm( 7335): VFY: replacing opcode 0x6e at 0x004e
W/dalvikvm( 7335): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7335): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7335): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 7335): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
,D/dalvikvm( 7335): VFY: replacing opcode 0x22 at 0x0071
,W/dalvikvm( 7335): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7335): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7335): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7335): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7335): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 7335): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
,D/dalvikvm( 7335): VFY: replacing opcode 0x1f at 0x0021
,W/dalvikvm( 7335): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 7335): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
,I/PCWCLIENTTRACE_PushUtil( 6697): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6697): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6697): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6697): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6697): noConnectivity : true
I/dalvikvm( 7335): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/dalvikvm( 7335): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
,D/dalvikvm( 7335): VFY: replacing opcode 0x6e at 0x0074
,I/ActivityManager( 2411): Killing 6454:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/vclib   ( 7335): onServiceConnected
,W/Babel   ( 7335): Attempted to change video mute state without an active call.
,I/SELinux ( 7367): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7367):  
,I/SELinux ( 7367): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7367):  
I/SELinux ( 7367):  
,I/SELinux ( 7367): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7367): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7367): >>>>> Normal User
,E/dalvikvm( 7367): >>>>> com.sec.android.diagmonagent [ userId:0 | appId:1000 ]
,E/SELinux ( 7367): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7367): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7367): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7367): Added TimaKesytore provider
,D/dalvikvm( 7367): GC_CONCURRENT freed 3007K, 32% free 9560K/14040K, paused 4ms+2ms, total 31ms
,D/dalvikvm( 7367): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/libgps  ( 2411): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2411): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2411): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2411): agps_ril_update_network_availability: Waiting for IPC connection...
,D/dalvikvm( 7335): GC_CONCURRENT freed 978K, 18% free 11902K/14364K, paused 3ms+3ms, total 48ms
,D/dalvikvm( 7335): WAIT_FOR_CONCURRENT_GC blocked 38ms
,I/DBG_DIAGMONDM( 7367): [1.140541.0531][Line:472][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/DBG_DIAGMONDM( 7367): [1.140541.0531][Line:48][onCreate] myUserId : 0
,D/dalvikvm( 7335): GC_FOR_ALLOC freed 488K, 19% free 12395K/15132K, paused 36ms, total 36ms
,I/DBG_DIAGMONDM( 7367): [1.140541.0531][Line:376][xdbDMffs_Init] 
,D/dalvikvm( 7335): GC_FOR_ALLOC freed 1759K, 24% free 12766K/16716K, paused 30ms, total 31ms
,I/DBG_DIAGMONDM( 7367): [1.140541.0531][Line:70][onCreate] nStatus : 0
,I/SELinux ( 7381): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7381):  
,I/SELinux ( 7381): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7381):  
I/SELinux ( 7381):  
,I/SELinux ( 7381): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7381): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7381): >>>>> Normal User
,E/dalvikvm( 7381): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7381): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7381): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7381): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7381): Added TimaKesytore provider
,D/dalvikvm( 7381): GC_CONCURRENT freed 2999K, 32% free 9564K/14036K, paused 3ms+1ms, total 26ms
,D/dalvikvm( 7381): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/ActivityManager( 2411): Killing 6399:com.sec.phone/1001 (adj 15): empty #43
,I/ActivityManager( 2411): Killing 6106:com.android.calendar/u0a144 (adj 15): empty #43
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 330, Delta = 10
I/SELinux ( 7394): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7394):  
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(336), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SELinux ( 7394): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7394):  
I/SELinux ( 7394):  
,I/SELinux ( 7394): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7394): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7394): >>>>> Normal User
,E/dalvikvm( 7394): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7394): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7394): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7394): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7394): Added TimaKesytore provider
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
D/STATUSBAR-IconMerger( 2579): checkOverflow(336), More:false, Req:false Child:3
D/dalvikvm( 7394): GC_CONCURRENT freed 3002K, 32% free 9564K/14036K, paused 4ms+1ms, total 31ms
D/dalvikvm( 7394): WAIT_FOR_CONCURRENT_GC blocked 21ms
D/KLMS-2.3.201 : ( 7394): KLMSValidator() : checkQATesting()
I/KLMS-2.3.201 : ( 7394): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450739100160
I/KLMS-2.3.201 : ( 7394): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
D/libgps  ( 2411): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2411): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2411): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
I/ActivityManager( 2411): Killing 6438:com.android.providers.calendar/u0a45 (adj 15): empty #43
I/SELinux ( 7407): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7407):  
I/SELinux ( 7407): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7407):  
I/SELinux ( 7407):  
I/SELinux ( 7407): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7407): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7407): >>>>> Normal User
E/dalvikvm( 7407): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
E/SELinux ( 7407): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 7407): in addTimaSignatureService
D/TimaKeyStoreProvider( 7407): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7407): Added TimaKesytore provider
D/dalvikvm( 2411): GC_CONCURRENT freed 4099K, 55% free 25575K/56556K, paused 10ms+23ms, total 304ms
D/dalvikvm( 2411): WAIT_FOR_CONCURRENT_GC blocked 74ms
D/dalvikvm( 2411): WAIT_FOR_CONCURRENT_GC blocked 256ms
D/dalvikvm( 7407): GC_CONCURRENT freed 2989K, 32% free 9575K/14036K, paused 4ms+2ms, total 36ms
D/dalvikvm( 7407): WAIT_FOR_CONCURRENT_GC blocked 30ms
D/SO_AGENT( 7407): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
I/SO_AGENT( 7407): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
I/SA      ( 5946): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
I/SA      ( 5946): [BDLM] already registered in spp
I/SA      ( 5946): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
I/SA      ( 5946): [OR] == ACTION_CONNECTIVITY_CHANGE ==
D/WifiP2pService( 2411): InactiveState{ what=143375 }
I/SA      ( 5946): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 5946): [OR] == isSIMCardReady false ==
I/SA      ( 5946): [SCU] == networkStateCheck == false
I/SA      ( 5946): [OR] onReceive END
D/WifiP2pService( 2411): P2pEnabledState{ what=143375 }
I/ActivityManager( 2411): Killing 6274:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
D/WifiStateMachine( 2411): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/WifiStateMachine( 2411): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 2411): CaptivePortalCheckState enter
D/PhoneNumberLocatorBootCompletedReceiver( 2751): onReceive
D/PhoneNumberLocatorBootCompletedReceiver( 2751): Phone number locator feature is dsiabled
I/WifiTrafficPoller( 2411): evaluateTrafficStatsPolling
D/WifiStateMachine( 2411): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2411): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2411): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/SCloudBackupReceiver( 5969): Other Intent
I/WifiTrafficPoller( 2411): evaluateTrafficStatsPolling
D/ConnectivityService( 2411): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
E/ConnectivityService( 2411): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2411): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
I/SELinux ( 7440): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7440):  
D/ConnectivityService( 2411): handleConnectivityChange: setting default proxy info 
V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
V/RouteController( 1915): RTNETLINK answers: No such file or directory
I/SELinux ( 7440): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7440):  
I/SELinux ( 7440):  
I/SELinux ( 7440): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
E/SELinux ( 7440): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7440): >>>>> Normal User
E/dalvikvm( 7440): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
E/SELinux ( 7440): [DEBUG] seapp_context_lookup: seinfoCategory = platform
V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
D/TimaKeyStoreProvider( 7440): in addTimaSignatureService
V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
D/TimaKeyStoreProvider( 7440): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7440): Added TimaKesytore provider
V/RouteController( 1915): RTNETLINK answers: No such process
V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
V/NetworkStats( 2411): updateIfacesLocked()
V/NetworkStats( 2411): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
V/NetworkStats( 2411): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
V/NetworkStats( 2411): performPollLocked() took 24ms
D/PackageManager( 2411): [MSG] WRITE_PACKAGE_RESTRICTIONS
D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
D/dalvikvm( 7440): GC_CONCURRENT freed 2993K, 32% free 9569K/14032K, paused 7ms+2ms, total 40ms
D/dalvikvm( 7440): WAIT_FOR_CONCURRENT_GC blocked 21ms
D/com.samsung.app( 7440): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/com.samsung.app( 7440): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
D/com.samsung.app( 7440): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
D/com.samsung.app( 7440): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
D/com.samsung.app( 7440): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/com.samsung.app( 7440): [KK AccuPhone]>>> RM:136 [0:0]  V init 
D/daemonapp( 5382): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/com.samsung.app( 7440): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5382): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7440): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5382): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7440): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7440): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2411): Killing 6314:com.google.android.music:main/u0a125 (adj 15): empty #43
,D/Headlines( 5995): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5995): getCountryCode(): countryCode = PL
,D/Headlines( 5995): Breath.onCreate
,D/Headlines( 5995): Breath timer started. interval : 30000
,I/SELinux ( 7467): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7467):  
,D/Headlines( 5995): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5995): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,V/AlarmManager( 2411): waitForAlarm result :8
D/HeadlinesCardManager( 5995): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5995): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5995): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5995): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5995): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7467): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7467):  
I/SELinux ( 7467):  
,I/SELinux ( 7467): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7467): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7467): >>>>> Normal User
,E/dalvikvm( 7467): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7467): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/Watchdog( 2411): !@Sync 9
,D/TimaKeyStoreProvider( 7467): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7467): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7467): Added TimaKesytore provider
,D/dalvikvm( 7467): GC_CONCURRENT freed 2997K, 32% free 9571K/14040K, paused 4ms+2ms, total 32ms
,D/dalvikvm( 7467): WAIT_FOR_CONCURRENT_GC blocked 26ms
,V/WebViewChromium( 7467): Binding Chromium to the background looper Looper (main, tid 1) {425e7f38}
,I/chromium( 7467): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7467): Initializing chromium process, renderers=0
,W/chromium( 7467): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7467): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7467): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/Tethering( 2411): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2411): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2411): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2579): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/libEGL  ( 7467): loaded /system/lib/egl/libGLESv2_mali.so
D/STATUSBAR-NetworkController( 2579): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2579): updateDataNetType()
,D/STATUSBAR-NetworkController( 2579): NoService, mRoamingIconId = 0
I/DBG_DM  ( 4788): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/Mali    ( 7467): Mali API Version : 401
,I/Mali    ( 7467): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/libgps  ( 2411): agps_ril_update_network_state: Waiting for IPC connection...
,W/GAV2    ( 7467): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7467): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 7467): Starting up...
,I/iu.Environment( 5701): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5184): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5184): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5184): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425f1df0
,I/SELinux ( 7505): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7505):  
,I/SELinux ( 7505): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7505):  
I/SELinux ( 7505):  
,I/SELinux ( 7505): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7505): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7505): >>>>> Normal User
,E/dalvikvm( 7505): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7505): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7505): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7505): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7505): Added TimaKesytore provider
,D/dalvikvm( 7505): GC_CONCURRENT freed 2976K, 32% free 9591K/14036K, paused 5ms+3ms, total 39ms
,D/dalvikvm( 7505): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/RCPManagerService( 2411): exchangeData() failure , invalid userId
,D/RCPManagerService( 2411): exchangeData() failure , invalid userId
,D/RCPManagerService( 2411): exchangeData() failure , invalid userId
,D/RCPManagerService( 2411): exchangeData() failure , invalid userId
,I/SELinux ( 7524): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7524):  
,I/dalvikvm( 7259): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7259): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7259): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 7259): Shutting down VM
,W/dalvikvm( 7259): threadid=1: thread exiting with uncaught exception (group=0x41b2ec08)
E/AndroidRuntime( 7259): FATAL EXCEPTION: main
E/AndroidRuntime( 7259): Process: com.test.thalitest, PID: 7259
E/AndroidRuntime( 7259): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 7259): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 7259): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 7259): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 7259): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 7259): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 7259): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 7259): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 7259): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 7259): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 7259): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 7259): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7259): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7259): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7259): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7259): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7259): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7259): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7259): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 2411):   Force finishing activity com.test.thalitest/.MainActivity
D/PointerIcon( 2411): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2411): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2411): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2411): setHoveringSpenCustomIcon IconType is same.1
I/SELinux ( 7524): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7524):  
I/SELinux ( 7524):  
I/SELinux ( 7524): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 14% free 9501K/11016K, paused 6ms+4ms, total 50ms
E/SELinux ( 7524): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7524): >>>>> Normal User
,E/dalvikvm( 7524): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
I/ActivityManager( 2411): Killing 6621:com.sec.android.Kies/1000 (adj 15): empty #43
,E/SELinux ( 7524): [DEBUG] seapp_context_lookup: seinfoCategory = release
,W/ActivityManager( 2411): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/CrashAnrDetector( 2411): processName: com.test.thalitest
,D/CrashAnrDetector( 2411): broadcastEvent : com.test.thalitest data_app_crash
,I/Process ( 7259): Sending signal. PID: 7259 SIG: 9
W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,D/RCPManagerService( 2411): exchangeData() failure , invalid userId
,D/RCPManagerService( 2411): exchangeData() failure , invalid userId
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 14% free 9501K/11016K, paused 4ms+4ms, total 38ms
,I/ActivityManager( 2411): Killing 5660:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
D/TimaKeyStoreProvider( 7524): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7524): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7524): Added TimaKesytore provider
,I/ActivityManager( 2411): Killing 5672:com.android.chrome/u0a85 (adj 15): empty #43
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 14% free 9501K/11016K, paused 3ms+4ms, total 33ms
,I/SurfaceFlinger( 1920): id=24 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1920): id=24 Removed NainActivit (-2/10)
,I/WindowState( 2411): WIN DEATH: Window{44c026a8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1920): id=24 Removed NainActivit (-2/10)
,I/SELinux ( 7540): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7540):  
,D/dalvikvm( 7524): GC_CONCURRENT freed 2997K, 32% free 9571K/14036K, paused 3ms+2ms, total 23ms
,D/dalvikvm( 7524): WAIT_FOR_CONCURRENT_GC blocked 13ms
,I/SurfaceFlinger( 1920): id=23 Removed EimLayer (6/9)
I/SurfaceFlinger( 1920): id=22 Removed EimLayer (5/8)
I/SurfaceFlinger( 1920): id=23 Removed EimLayer (-2/8)
,I/SurfaceFlinger( 1920): id=22 Removed EimLayer (-2/8)
,I/ActivityManager( 2411): Process com.test.thalitest (pid 7259) (adj 9) has died.
D/BadgeProvider( 7524): onCreate
,D/BadgeProvider( 7524): DatabaseHelper
V/WindowManager( 2411): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/Launcher( 2774): onRestart, Launcher: 1113664584
D/Launcher( 2774): onStart, Launcher: 1113664584
,D/Launcher.HomeView( 2774): onStart
,D/BadgeProvider( 7524): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
I/SELinux ( 7540): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7540):  
I/SELinux ( 7540):  
,I/SELinux ( 7540): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7540): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7540): >>>>> Normal User
,E/dalvikvm( 7540): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7540): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,I/SurfaceFlinger( 1920): id=25 createSurf (720x1280),1 flag=4, Mauncher
,D/BadgeProvider( 7524): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7524): sendNotify, [notify] : null
D/BadgeProvider( 7524): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7524): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7524): update, [UpdateCount] : 1
D/STATUSBAR-StatusBarManagerService( 2411): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2411): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/TimaKeyStoreProvider( 7540): in addTimaSignatureService
D/PointerIcon( 2411): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2411): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2411): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2411): setHoveringSpenCustomIcon IconType is same.1
,D/libgps  ( 2411): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2411): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2411): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
D/TimaKeyStoreProvider( 7540): Cannot add TimaSignature Service, License check Failed
,D/libgps  ( 2411): agps_ril_update_network_availability: Waiting for IPC connection...
,D/ActivityThread( 7540): Added TimaKesytore provider
,D/Launcher.Model( 2774): reloadBadges entered.
,D/PhoneStatusBar( 2579): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2579): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2411): tr p:2774,o:f
D/StatusBarManagerService( 2411): semi p:2774,o:f
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 2411): Got RemoteException sending setActive(false) notification to pid 7259 uid 10574
,D/dalvikvm( 7540): GC_CONCURRENT freed 3008K, 32% free 9565K/14040K, paused 5ms+2ms, total 31ms
,D/dalvikvm( 7540): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/hcjo    ( 6085): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6085): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6085): exit::IDLE
,D/InitializeManagerStateMachine( 6085): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6085): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6085): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6085): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 6085): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6085): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6085): entry::SUCCESS
,D/hcjo    ( 6085): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6085): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6085): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6085): exit::SUCCESS
,D/InitializeManagerStateMachine( 6085): entry::IDLE
,E/SPPClientService( 5584): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5584): [SystemStateMoniter] Current Time : 289748
,E/SPPClientService( 5584): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5584): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 5724): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5724): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5724): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 5724): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5724): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5724): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5584): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5584): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 5724): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 5724): MountReceiver.onReceive - Keep current state
,I/System.out( 7335): Thread-659(HTTPLog):isShipBuild true
,I/System.out( 7335): Thread-659(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/NearbySettings( 5724): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5724): DMSUtil.isNetworkConnected - flag-null, state-null
E/SPPClientService( 5584): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,I/NearbySettings( 5724): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 5724): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5724): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5724): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5584): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/SurfaceFlinger( 1920): id=26 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 2411): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2411
,I/Babel   ( 7335): connection state changed from UNKNOWN to CONNECTED
,D/NearbySettings( 5724): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 5724): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5584): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,D/Headlines( 5995): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5995): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5995): Breath 1810 latestRequest time : 1450739101017 current time : 1450739102827
,I/PCWCLIENTTRACE_PushUtil( 6697): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6697): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6697): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6697): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5584): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5584): [g] getNetMCC return empty string
,I/KLMS-2.3.201 : ( 7394): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7394): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450739103118
,I/KLMS-2.3.201 : ( 7394): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7407): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3466): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7407): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 3594): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7565): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7565):  
,I/SELinux ( 7569): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7569):  
,I/SELinux ( 7565): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7565):  
I/SELinux ( 7565):  
,I/SELinux ( 7565): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7565): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7565): >>>>> Normal User
,E/dalvikvm( 7565): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7565): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 5946): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5946): [BDLM] already registered in spp
I/SA      ( 5946): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5946): [OR] == ACTION_CONNECTIVITY_CHANGE ==
D/TimaKeyStoreProvider( 7565): in addTimaSignatureService
I/SA      ( 5946): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5946): [OR] == isSIMCardReady false ==
,I/SA      ( 5946): [SCU] == networkStateCheck == true
I/SA      ( 5946): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5946): isChinaCountryCode : false
,I/SA      ( 5946): [OR] == networkStateCheck true ==
,I/SA      ( 5946): [OR] GetMyCountryZoneTask
,I/SELinux ( 7569): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7569):  
I/SELinux ( 7569):  
,I/SELinux ( 7569): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/SA      ( 5946): [OR] onReceive END
,D/TimaKeyStoreProvider( 7565): Cannot add TimaSignature Service, License check Failed
,E/SELinux ( 7569): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7569): >>>>> Normal User
,E/dalvikvm( 7569): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,D/ActivityThread( 7565): Added TimaKesytore provider
,I/SA      ( 5946): [SRS] prepareGetMyCountryZone
,E/SELinux ( 7569): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 5946): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5946): [SSP] query invoked
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): Phone number locator feature is dsiabled
,D/TimaKeyStoreProvider( 7569): in addTimaSignatureService
,I/SCloudBackupReceiver( 5969): Other Intent
,D/TimaKeyStoreProvider( 7569): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7569): Added TimaKesytore provider
,D/com.samsung.app( 7440): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7440): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
D/libgps  ( 2411): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2411): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2411): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/System.out( 7381): Thread-654(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
D/Headlines( 5995): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5995): getCountryCode(): countryCode = PL
,I/SA      ( 5946): [TPMU] GetMccFromDB : null
D/Headlines( 5995): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5995): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5995): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 5995): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5995): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5995): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5995): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SA      ( 5946): [SCU] getMccFromPreferece mcc = 260
,I/System.out( 7381): Thread-654(ApacheHTTPLog):isShipBuild true
,I/System.out( 7381): Thread-654(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/iu.Environment( 5701): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/dalvikvm( 7565): GC_CONCURRENT freed 2994K, 32% free 9572K/14040K, paused 3ms+2ms, total 34ms
,D/dalvikvm( 7565): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/SA      ( 5946): [TPM] isNoProxy(default) : true
,I/SA      ( 5946): [RC New] Execute method=[GET] start
,D/QuickConnect[1.1][2] ( 5184): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,D/dalvikvm( 7569): GC_CONCURRENT freed 3014K, 32% free 9555K/14036K, paused 3ms+2ms, total 32ms
D/dalvikvm( 7569): WAIT_FOR_CONCURRENT_GC blocked 28ms
I/QuickConnect[1.1][2] ( 5184): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5184): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425f1df0
,D/RCPManagerService( 2411): exchangeData() failure , invalid userId
,D/RCPManagerService( 2411): exchangeData() failure , invalid userId
,V/KVNProvider( 7569): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7569): getFindoCursor query string : 
,V/KVNProvider( 7569): getTagSearchCursor() tagSearchCursor count : 0
,D/hcjo    ( 6085): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6085): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6085): exit::IDLE
,D/InitializeManagerStateMachine( 6085): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 6085): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6085): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6085): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 6085): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6085): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6085): entry::SUCCESS
,D/hcjo    ( 6085): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6085): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6085): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6085): exit::SUCCESS
,D/InitializeManagerStateMachine( 6085): entry::IDLE
,I/System.out( 7381): AsyncTask #1 calls detatch(),
E/SPPClientService( 5584): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5584): [SystemStateMoniter] Current Time : 290771
,E/SPPClientService( 5584): [SystemStateMoniter] No Connect : false
,W/System.err( 7381): com.sec.android.fota.osp.http.RestClientException
,W/System.err( 7381): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7381): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7381): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
,W/System.err( 7381): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7381): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 7381): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7381): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7381): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7381): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7381): Caused by: java.lang.NullPointerException
,W/System.err( 7381): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7381): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7381): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7381): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7381): 	... 8 more
,I/ActivityManager( 2411): Killing 5687:com.google.android.apps.uploader/u0a117 (adj 15): empty #43
,E/WifiStateMachine( 2411): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/dalvikvm( 5584): GC_CONCURRENT freed 2012K, 26% free 10451K/14020K, paused 4ms+4ms, total 44ms
,D/dalvikvm( 5584): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/SA      ( 5946): [RC New] [v2liruge] api execute + 695
,I/SA      ( 5946): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5946): AsyncTask #2 calls detatch()
,I/SA      ( 5946): [TPMU] getNetworkMcc : 
,I/SA      ( 5946): [SCU] saveMccToPreferece Start
,I/SA      ( 5946): [SCU] RegionMCC : 260
,I/SA      ( 5946): [SSP] query invoked
,I/SA      ( 5946): [TPMU] GetMccFromDB : null
,I/SA      ( 5946): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5946): [SCU] saveMccToPreferece End
I/SA      ( 5946): [RC New] executeRequest [v2liruge] end. 734
,I/SA      ( 5946): [RC New] Execute end
,I/SA      ( 5946): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5946): [OR] GetMyCountryZoneTask Success
,D/AmoledAdjustTimer( 2411): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,E/SPPClientService( 5584): [b] __InitReply__
,I/SurfaceFlinger( 1920): id=26 Removed Uoast (8/9)
,I/SurfaceFlinger( 1920): id=26 Removed Uoast (-2/9)
I/ActivityManager( 2411): Killing 6600:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/PowerManagerService( 2411): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2411) eventTime = 293423
,D/PowerManagerService( 2411): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2411 (0x0)
,D/PowerManagerService( 2411): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2411, ws=WorkSource{1000}) (elapsedTime=3473)
,I/GAV2    ( 7467): Thread[GAThread,5,main]: No campaign data found.
,W/WifiP2pStateTracker( 2411): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2411): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2411):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2411): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2411): updateSourceRoutes : no source routing conditions
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6697): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil( 6697): [hasSamungAccount] - No Samsung Account,
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6697): failed to loading secure library,
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6697): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6697): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6697): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6697): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6697): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6697): [ensureRegistration] - No Samsung account,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2411): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate,
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/CaptivePortalTracker( 2411): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
D/ConnectivityService( 2411): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2411): Checking http://216.58.209.46/generate_204,
,D/CaptivePortalTracker( 2411): Don't send network conditions - lacking user consent.,
D/CaptivePortalTracker( 2411): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 2411): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2411): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
D/ConnectivityService( 2411): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 6085): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 6085): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6085): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 6085): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6085): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 6085): exit::CHECK_TIMEOUT_FOR_UPDATE,
,D/PreloadUpdateManagerStateMachine( 6085): entry::IDLE,
,D/PreloadUpdateManagerStateMachine( 6085): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 6085): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6085): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6085): AutoUpdateTriggerManager:IDLE:notifyNextTime,
,D/PreloadUpdateManagerStateMachine( 6085): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 6085): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6085): entry::IDLE,
,D/AmoledAdjustTimer( 2411): prevTemp = 299, currTemp = 300, prevStep = 4, currStep = 4,
,I/ActivityManager( 2411): Waited long enough for: ServiceRecord{44e09df8 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/ActivityManager( 2411): Waited long enough for: ServiceRecord{445ae4a8 u0 com.sec.spp.push/.PushClientService},
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate,
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4012): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4,
,D/TimaService( 2411): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2411): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2411): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2411): initializing...,
I/TLC_TIMA_PKM_initialize( 2411): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2411): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2411): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2411): input max_recvmsg_size = 262196,
I/TZ: mc_tlc_communication( 2411): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2411): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2411): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2411): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 2411): device_id = 0x0
I/TZ: mc_tlc_communication( 2411): tlc_open() was called
,I/TZ: mc_tlc_communication( 2411): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2411): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 2411): Opening the session
,I/TZ: mc_tlc_communication( 2411): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2411): Trustlet response is completed,
,I/PowerManagerService( 2411): [PWL] Off : 140s ago,
I/PowerManagerService( 2411): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2411): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2411): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2411, ws=null) (elapsedTime=5024)
,W/ProcessCpuTracker( 2411): Skipping unknown process pid 7781,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = -10,
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;,
V/AlarmManager( 2411): waitForAlarm result :8
,D/Headlines( 5995): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
D/TimaService( 2411): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
D/TimaService( 2411): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/Headlines( 5995): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5995): Breath 27623 latestRequest time : 1450739103416 current time : 1450739131039,
,E/Watchdog( 2411): !@Sync 10,
,D/AmoledAdjustTimer( 2411): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2411): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate,
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2411): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,V/AlarmManager( 2411): waitForAlarm result :8,
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2411): !@Sync 11,
,D/AmoledAdjustTimer( 2411): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4,
,V/AlarmManager( 2411): waitForAlarm result :4,
,V/AlarmManager( 2411): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7937): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7937):  
,I/SELinux ( 7937): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7937):  
I/SELinux ( 7937):  
,I/SELinux ( 7937): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7937): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 7937): >>>>> Normal User
,E/dalvikvm( 7937): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 7937): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 7937): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7937): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7937): Added TimaKesytore provider,
,D/dalvikvm( 7937): GC_CONCURRENT freed 3012K, 32% free 9554K/14036K, paused 3ms+2ms, total 28ms,
,D/dalvikvm( 7937): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/Headlines( 5995): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5995): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5995): Breath 65344 latestRequest time : 1450739103416 current time : 1450739168760
,I/ActivityManager( 2411): Killing 6657:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,I/PowerManagerService( 2411): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2411): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED,
,D/BatteryService( 2411): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4012): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,V/AlarmManager( 2411): waitForAlarm result :8,
,D/Headlines( 5995): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
D/Headlines( 5995): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5995): Breath 87615 latestRequest time : 1450739103416 current time : 1450739191031,
,E/Watchdog( 2411): !@Sync 12,
,D/AmoledAdjustTimer( 2411): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true,
,D/BatteryService( 2411): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4012): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2411): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2411): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2411): [PWL] Off : 225s ago,
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2411): waitForAlarm result :8,
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,V/AlarmManager( 2411): waitForAlarm result :8,
,D/Headlines( 5995): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5995): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5995): Breath 117620 latestRequest time : 1450739103416 current time : 1450739221036,
,E/Watchdog( 2411): !@Sync 13,
,D/AmoledAdjustTimer( 2411): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate,
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4012): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2411): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,V/AlarmManager( 2411): waitForAlarm result :8,
,D/Headlines( 5995): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5995): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
D/Headlines( 5995): Breath 147628 latestRequest time : 1450739103416 current time : 1450739251044
,D/Headlines( 5995): stop ,
,D/Headlines( 5995): Breath.onDestroy : ,
I/ActivityManager( 2411): Killing 6671:com.samsung.groupcast/u0a15 (adj 15): empty #43
,E/Watchdog( 2411): !@Sync 14,
,D/AmoledAdjustTimer( 2411): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2411): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2411): [PWL] Off : 275s ago,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2411): !@Sync 15
,D/AmoledAdjustTimer( 2411): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,D/dalvikvm( 2411): GC_CONCURRENT freed 4169K, 56% free 25340K/56556K, paused 20ms+20ms, total 251ms
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2411): !@Sync 16
,D/AmoledAdjustTimer( 2411): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2411): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2411): !@Sync 17
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2411): !@Sync 18
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2411): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = -10
,E/Watchdog( 2411): !@Sync 19
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2411): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2411): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2411): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ProcessCpuTracker( 2411): Skipping unknown process pid 8589
,W/ProcessCpuTracker( 2411): Skipping unknown process pid 8594
,W/ProcessCpuTracker( 2411): Skipping unknown process pid 8599
,W/ProcessCpuTracker( 2411): Skipping unknown process pid 8604
,W/ProcessCpuTracker( 2411): Skipping unknown process pid 8607
,W/ProcessCpuTracker( 2411): Skipping unknown process pid 8610
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 10
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2411): !@Sync 20
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = -10
,I/PowerManagerService( 2411): [PWL] Off : 455s ago
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4084): GC_CONCURRENT freed 2889K, 31% free 9724K/14080K, paused 13ms+2ms, total 72ms
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2411): !@Sync 21
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/GAV2    ( 5787): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5787): Thread[disconnect check,5,main]: Disconnected from service
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2411): !@Sync 22
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2411): [PWL] Off : 525s ago
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2411): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2411): <AppSync3 Whitelist>
,V/AlarmManager( 2411): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2411): !@Sync 23
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 24
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2411): !@Sync 25
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2411): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 26
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :4
,D/LightsService( 2411): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2411): getReportingMode :: sensor.mType = 5
D/Sensors ( 2411): LightSensor setDelay = 200000000
D/Sensors ( 2411): LightSensor setSensorDelay = 200000000
D/Sensors ( 2411): Light sensor flush: not enabled 0
D/Sensors ( 2411): LightSensor enable = 1
D/Sensors ( 2411): LightSensor enableSensor = 1
D/SensorManager( 2411): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2411): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5584): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,I/EventLogService( 3271): Aggregate from 1450737707290 (log), 1450737707290 (data)
,D/Sensors ( 2411): LightSensor enable = 0
,D/Sensors ( 2411): LightSensor enableSensor = 0
,D/SensorManager( 2411): unregisterListener ::   
D/LightsService( 2411): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2411): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/dalvikvm( 3271): GC_CONCURRENT freed 2207K, 23% free 12685K/16360K, paused 9ms+9ms, total 98ms
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2411): !@Sync 27
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2411): [PWL] Off : 680s ago
,E/Watchdog( 2411): !@Sync 28
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2411): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2411): !@Sync 29
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2411): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2411): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2411): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2411): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/dalvikvm( 2411): GC_CONCURRENT freed 3963K, 56% free 25253K/56556K, paused 18ms+17ms, total 241ms
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2411): [PWL] Off : 765s ago
,D/AmoledAdjustTimer( 2411): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2411): !@Sync 31
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 32
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2411): !@Sync 33
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2411): [PWL] Off : 855s ago
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 34
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2411): !@Sync 35
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 36
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2411): waitForAlarm result :4
,V/AlarmManager( 2411): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/SPPClientService( 5584): [b] __PingReply__
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2411): [PWL] Off : 950s ago
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2411): !@Sync 37
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 38
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2411): stay LED for fully charged
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2411): !@Sync 39
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2411): TIMA: TimaService scheduler is intialized. 
D/TimaService( 2411): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2411): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2411): !@Sync 40
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2411): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2411): !@Sync 41
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 42
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2411): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2411): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2411): (AppSync) ### 0 added ###,
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2411): !@Sync 43
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2411): [PWL] Off : 1155s ago
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2411): stay LED for fully charged
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 44
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2411): stay LED for fully charged
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 2411): GC_CONCURRENT freed 3951K, 56% free 25145K/56556K, paused 21ms+17ms, total 234ms
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4084): GC_CONCURRENT freed 2050K, 31% free 9722K/14080K, paused 11ms+3ms, total 49ms
,D/dalvikvm( 4084): WAIT_FOR_CONCURRENT_GC blocked 14ms
,E/Watchdog( 2411): !@Sync 45
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 46
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2411): waitForAlarm result :8
,D/LightsService( 2411): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2411): getReportingMode :: sensor.mType = 5
D/Sensors ( 2411): LightSensor setDelay = 200000000
D/Sensors ( 2411): LightSensor setSensorDelay = 200000000
D/Sensors ( 2411): Light sensor flush: not enabled 0
D/Sensors ( 2411): LightSensor enable = 1
D/Sensors ( 2411): LightSensor enableSensor = 1
D/SensorManager( 2411): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): stay LED for fully charged
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/LightsService( 2411): [SvcLED]  onSensorChanged::light value = 0
D/Sensors ( 2411): LightSensor enable = 0
D/Sensors ( 2411): LightSensor enableSensor = 0
,D/SensorManager( 2411): unregisterListener ::   
D/LightsService( 2411): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2411): !@Sync 47
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2411): [PWL] Off : 1265s ago
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 48
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2411): !@Sync 49
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2411): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2411): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2411): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2411): !@Sync 50
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2411): !@Sync 51
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2411): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4,
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 52
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2411): !@Sync 53
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): stay LED for fully charged
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2411): !@Sync 54
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2411): !@Sync 55
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2411): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 56
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2411): waitForAlarm result :8
,E/SPPClientService( 5584): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2411): !@Sync 57
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2411): !@Sync 58
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 2411): GC_CONCURRENT freed 3806K, 56% free 25158K/56556K, paused 27ms+14ms, total 229ms
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2411): !@Sync 59
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2411): [PWL] Off : 1625s ago
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2411): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2411): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2411): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): stay LED for fully charged
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2411): !@Sync 60
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2411): Prepared write state in 43ms
,I/ProcessStatsService( 2411): Prepared write state in 56ms
,D/dalvikvm( 2774): GC_CONCURRENT freed 8878K, 37% free 18252K/28596K, paused 8ms+9ms, total 76ms
,I/ProcessStatsService( 2411): Pruning old procstats: /data/system/procstats/state-2015-12-21-01-31-15.bin
,E/Watchdog( 2411): !@Sync 61
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 62
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2411): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2411): <AppSync3 Whitelist>
,V/AlarmManager( 2411): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2411): !@Sync 63
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2411): [PWL] Off : 1755s ago
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 64
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,I/ActivityManager( 2411): Killing 5853:com.android.mms/u0a49 (adj 15): empty for 1810s
,I/ActivityManager( 2411): Killing 6534:com.sec.knox.bridge/1000 (adj 15): empty for 1816s
,I/ActivityManager( 2411): Killing 4907:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1816s
,I/ActivityManager( 2411): Killing 6509:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1826s
,I/ActivityManager( 2411): Killing 6858:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1826s
,I/ActivityManager( 2411): Killing 6844:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1827s
,I/ActivityManager( 2411): Killing 6832:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1827s
I/ActivityManager( 2411): Killing 6820:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1827s
,I/ActivityManager( 2411): Killing 6807:com.samsung.helphub/1000 (adj 15): empty for 1827s
,I/ActivityManager( 2411): Killing 6794:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1827s
,I/ActivityManager( 2411): Killing 6781:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1828s
I/ActivityManager( 2411): Killing 6769:com.sec.android.service.cm/u0a82 (adj 15): empty for 1828s
,I/ActivityManager( 2411): Killing 6467:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1828s
,I/ActivityManager( 2411): Killing 6742:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1828s
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2411): Killing 6120:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1829s
,I/ActivityManager( 2411): Killing 6712:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty for 1829s
,I/ActivityManager( 2411): Killing 6684:com.android.musicfx/u0a24 (adj 15): empty for 1829s
,D/CountryDetector( 2411): No listener is left
,E/Watchdog( 2411): !@Sync 65
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 66
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,I/ActivityManager( 2411): Killing 5742:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty for 1850s
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2411): !@Sync 67
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 281, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 68
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2411): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4084): GC_CONCURRENT freed 2047K, 31% free 9722K/14072K, paused 12ms+2ms, total 49ms
,D/dalvikvm( 4084): WAIT_FOR_CONCURRENT_GC blocked 12ms
,E/Watchdog( 2411): !@Sync 69
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,TIME-OUT KILL (timeout was 1800000ms)
```
