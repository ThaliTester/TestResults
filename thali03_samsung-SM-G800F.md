#### Test 506502782e2cb10_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
--------- beginning of /dev/log/main
D/AndroidRuntime( 7219): 
D/AndroidRuntime( 7219): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7219): CheckJNI is OFF
D/AndroidRuntime( 7219): setted country_code = Poland
D/AndroidRuntime( 7219): setted countryiso_code = PL
D/AndroidRuntime( 7219): setted sales_code = PLS
D/AndroidRuntime( 7219): readGMSProperty: start
D/AndroidRuntime( 7219): readGMSProperty: already setted!!
D/AndroidRuntime( 7219): readGMSProperty: end
D/AndroidRuntime( 7219): addProductProperty: start
D/dalvikvm( 7219): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7219): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7219): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7219): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7219): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7219): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7219): failed to load memtrack module: -2
D/dalvikvm( 7219): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7219): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2420): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2420): mDVFSHelper.acquire()
I/SELinux ( 7247): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7247):  
D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7219): Shutting down VM
D/dalvikvm( 7219): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 7247): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7247):  
I/SELinux ( 7247):  
I/SELinux ( 7247): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7247): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7247): >>>>> Normal User
E/dalvikvm( 7247): >>>>> com.test.thalitest [ userId:0 | appId:10573 ]
E/SELinux ( 7247): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7247): in addTimaSignatureService
D/TimaKeyStoreProvider( 7247): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7247): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4183): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4183): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1922): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1922): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7247): GC_CONCURRENT freed 3000K, 31% free 9572K/13864K, paused 2ms+1ms, total 18ms
D/dalvikvm( 7247): WAIT_FOR_CONCURRENT_GC blocked 15ms
V/WebViewChromium( 7247): Binding Chromium to the background looper Looper (main, tid 1) {42297198}
I/chromium( 7247): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7247): Initializing chromium process, renderers=0
W/chromium( 7247): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7247): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 7247): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7247): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7247): Mali API Version : 401
,I/Mali    ( 7247): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7247): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7247): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,D/dalvikvm( 7247): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7247): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7247): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7247): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2579): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2420): tr p:7247,o:f
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
,D/PhoneStatusBar( 2579): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2420): semi p:7247,o:f
,I/SurfaceFlinger( 1922): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7247): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7247): Enabling debug mode 0
,W/AwContents( 7247): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2420): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@8
W/AwContents( 7247): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 7247): showStatusIcon on inactive InputConnection
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/JsMessageQueue( 7247): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7247): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42293940
,D/dalvikvm( 7247): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42293940
D/jxcore_app_log( 7247): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027548760
,D/JX-Cordova( 7247): jxcore cordova android initializing
,D/dalvikvm( 7247): GC_CONCURRENT freed 1298K, 19% free 11348K/13932K, paused 1ms+2ms, total 21ms
,D/dalvikvm( 7247): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 7247): GC_CONCURRENT freed 1918K, 18% free 14899K/18124K, paused 2ms+2ms, total 42ms
,D/dalvikvm( 7247): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7247): GC_FOR_ALLOC freed 5327K, 30% free 16182K/23040K, paused 40ms, total 40ms
,D/dalvikvm( 7247): GC_CONCURRENT freed 6677K, 32% free 17651K/25660K, paused 2ms+11ms, total 68ms
,D/dalvikvm( 7247): WAIT_FOR_CONCURRENT_GC blocked 53ms
,D/dalvikvm( 7247): GC_FOR_ALLOC freed 1261K, 32% free 17516K/25660K, paused 48ms, total 48ms
,I/dalvikvm-heap( 7247): Grow heap (frag case) to 21.900MB for 3713210-byte allocation
,D/dalvikvm( 7247): GC_FOR_ALLOC freed 2494K, 37% free 18647K/29288K, paused 40ms, total 40ms
,W/jxcore-log( 7247): Initializing JXcore engine
,W/jxcore-log( 7247): JXcore engine is ready
,W/jxcore-log( 7247): Starting JXcore engine
,W/jxcore-log( 7247): Platform android
W/jxcore-log( 7247): 
,W/jxcore-log( 7247): Process ARCH arm
W/jxcore-log( 7247): 
,I/jxcore-log( 7247): JXcore Cordova bridge is ready!
I/jxcore-log( 7247): 
,W/jxcore-log( 7247): JXcore engine is started
,I/chromium( 7247): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 7247): Toggling radios to true
I/jxcore-log( 7247): 
,D/BluetoothAdapter( 7247): enable(): BT is already enabled..!
,I/WifiManager( 7247): packageName : com.test.thalitest
,I/WifiManager( 7247): setWifiEnabled : true
,I/WifiService( 2420): setWifiEnabled: true pid=7247, uid=10573
W/ActivityManager( 2420): Permission Denial: getCurrentUser() from pid=7247, uid=10573 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 2420): Failed getting userId using ActivityManagerNative
W/WifiService( 2420): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7247, uid=10573 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2420): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2420): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2420): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2420): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService( 2420): disconnect: pid=7247, uid=10573
,I/wpa_supplicant( 3971): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7247): Radios toggled
I/jxcore-log( 7247): 
,I/jxcore-log( 7247): Got Device Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 7247): 
,I/jxcore-log( 7247): Perf Test app loaded loaded
I/jxcore-log( 7247): 
,I/wpa_supplicant( 3971): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,I/Choreographer( 7247): Skipped 131 frames!  The application may be doing too much work on its main thread.
,I/wpa_supplicant( 3971): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,I/jxcore-log( 7247): check test folder
I/jxcore-log( 7247): 
,D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3971): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3971): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3971): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3971): First Scan Start
,I/jxcore-log( 7247): found test : ./testFindPeers.js
I/jxcore-log( 7247): 
I/wpa_supplicant( 3971): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings( 2420): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2420): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2420): InactiveState{ what=143375 }
D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
I/wpa_supplicant( 3971): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3971): Skip scan - already scanning
D/ConnectivityService( 2420): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/WifiP2pService( 2420): InactiveState{ what=143375 }
D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
D/ConnectivityService( 2420): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2420): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2420): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2420): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2420): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2420): Attempting to switch to mobile
,D/ConnectivityService( 2420): Attempting to switch to BLUETOOTH_TETHER
I/jxcore-log( 7247): found test : ./testSendData.js
I/jxcore-log( 7247): 
,I/SELinux ( 7294): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7294):  
,D/STATUSBAR-IconMerger( 2579): checkOverflow(336), More:false, Req:false Child:3
,V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-73ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-72ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,W/NetworkManagementService( 2420): route cmd failed: 
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
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1
,I/SELinux ( 7294): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7294):  
I/SELinux ( 7294):  
,I/SELinux ( 7294): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-8ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/SELinux ( 7294): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7294): >>>>> Normal User
,E/dalvikvm( 7294): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
V/RouteController( 1916): RTNETLINK answers: No such process
V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,E/SELinux ( 7294): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 7294): in addTimaSignatureService
,D/NetUtils( 2420): android_net_utils_resetConnections in env=0x77e50d38 clazz=0x62900001 iface=wlan0 mask=0x3
D/ConnectivityService( 2420): resetConnections(wlan0, 3)
,D/TimaKeyStoreProvider( 7294): Cannot add TimaSignature Service, License check Failed
,I/jxcore-log( 7247): found test : ./testSendData2.js
I/jxcore-log( 7247): 
,D/ActivityThread( 7294): Added TimaKesytore provider
,E/jxcore  ( 7247): Error!: missing ) after argument list
E/jxcore  ( 7247): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
,I/chromium( 7247): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/NativeCrypto( 2847): Read error: ssl=0x7a299768: I/O error during system call, Connection timed out
,V/NativeCrypto( 2847): SSL shutdown failed: ssl=0x7a299768: I/O error during system call, Broken pipe
,E/SPPClientService( 5614): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5614): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5614): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5614): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5614): [b] ResponseMap empty
,D/dalvikvm( 7294): GC_CONCURRENT freed 2990K, 31% free 9583K/13860K, paused 4ms+2ms, total 25ms
,D/dalvikvm( 7294): WAIT_FOR_CONCURRENT_GC blocked 12ms
,I/System.out( 7294): Inside WakeupProvider
,I/System.out( 7294): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 7294): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7294): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7294): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/ConnectivityService( 2420): handleInetConditionChange: no active default network - ignore
,V/NetworkStats( 2420): updateIfacesLocked()
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): performPollLocked(flags=0x1)
V/NetworkStats( 2420): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): performPollLocked() took 23ms
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NearbySettings( 4759): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4759): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4759): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4759): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4759): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4759): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4759): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 7294): initQueue()
I/ActivityManager( 2420): Killing 6244:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/NearbySettings( 4759): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4759): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4759): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 4759): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4759): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4759): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4759): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2420): Tethering got CONNECTIVITY_ACTION
,I/ApplicationPolicy( 2420): updateDataUsageMap
,D/Tethering( 2420): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2420): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2420): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2579): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2579): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2579): updateDataNetType()
D/STATUSBAR-NetworkController( 2579): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6669): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6669): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6669): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6669): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6669): noConnectivity : true
,I/DBG_DM  ( 4785): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7323): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7323):  
,I/wpa_supplicant( 3971): nl80211: Received scan results (3 BSSes)
I/wpa_supplicant( 3971): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3971): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3971): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,I/SELinux ( 7323): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7323):  
I/SELinux ( 7323):  
,I/SELinux ( 7323): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7323): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7323): >>>>> Normal User
,E/dalvikvm( 7323): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7323): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,D/TimaKeyStoreProvider( 7323): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7323): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7323): Added TimaKesytore provider
,I/wpa_supplicant( 3971): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3971): Associated with C0.AA.48
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3971): freq(2412) increment count 2
,I/wpa_supplicant( 3971): meet head of list.
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3971): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3971): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3971): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3971): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3971): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,D/WifiNative( 2420): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/dalvikvm( 7323): GC_CONCURRENT freed 3001K, 31% free 9571K/13860K, paused 4ms+2ms, total 39ms
,D/dalvikvm( 7323): WAIT_FOR_CONCURRENT_GC blocked 32ms
,I/ActivityManager( 2420): Killing 6314:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/WifiP2pService( 2420): InactiveState{ what=143375 }
,D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,I/SELinux ( 7337): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7337):  
,D/dalvikvm( 1923): GC_EXPLICIT freed 43K, 13% free 9506K/10840K, paused 3ms+4ms, total 44ms
,I/SELinux ( 7337): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7337):  
I/SELinux ( 7337):  
,I/SELinux ( 7337): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7337): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7337): >>>>> Normal User
,E/dalvikvm( 7337): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7337): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 13% free 9506K/10840K, paused 3ms+5ms, total 41ms
,D/TimaKeyStoreProvider( 7337): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7337): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7337): Added TimaKesytore provider,
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 13% free 9506K/10840K, paused 4ms+3ms, total 38ms
,I/dhcpcd  ( 7347): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7347): bssid match
D/dalvikvm( 7337): GC_CONCURRENT freed 3005K, 31% free 9569K/13864K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 7337): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/ActivityManager( 2420): Killing 6371:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7356): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7356):  
,I/SELinux ( 7356): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7356):  
I/SELinux ( 7356):  
,I/SELinux ( 7356): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7356): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7356): >>>>> Normal User
,E/dalvikvm( 7356): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7356): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7356): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7356): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7356): Added TimaKesytore provider
,D/dalvikvm( 7356): GC_CONCURRENT freed 3014K, 32% free 9562K/13864K, paused 3ms+2ms, total 31ms
,D/dalvikvm( 7356): WAIT_FOR_CONCURRENT_GC blocked 26ms
D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection...
,D/KLMS-2.3.201 : ( 7356): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7356): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450736272745
,I/KLMS-2.3.201 : ( 7356): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2420): Killing 6390:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7368): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7368):  
,I/SELinux ( 7368): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7368):  
I/SELinux ( 7368):  
,I/SELinux ( 7368): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7368): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7368): >>>>> Normal User
,E/dalvikvm( 7368): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7368): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7368): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7368): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7368): Added TimaKesytore provider
,D/dalvikvm( 7368): GC_CONCURRENT freed 3001K, 31% free 9572K/13864K, paused 3ms+1ms, total 27ms
,D/dalvikvm( 7368): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/SO_AGENT( 7368): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7368): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5879): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5879): [BDLM] already registered in spp
,I/SA      ( 5879): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5879): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5879): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5879): [OR] == isSIMCardReady false ==
,I/SA      ( 5879): [SCU] == networkStateCheck == false
,I/SA      ( 5879): [OR] onReceive END
I/ActivityManager( 2420): Killing 6394:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): Phone number locator feature is dsiabled
D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 10
,I/SELinux ( 7380): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7380):  
,I/SELinux ( 7380): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7380):  
I/SELinux ( 7380):  
,I/SELinux ( 7380): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7380): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7380): >>>>> Normal User
,E/dalvikvm( 7380): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7380): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7380): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7380): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7380): Added TimaKesytore provider
,D/dalvikvm( 7380): GC_CONCURRENT freed 2998K, 31% free 9574K/13864K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 7380): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/sCloudBackupApp( 7380): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7380): Other Intent
I/ActivityManager( 2420): Killing 5661:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SELinux ( 7393): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7393):  
,I/SELinux ( 7393): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7393):  
I/SELinux ( 7393):  
,I/SELinux ( 7393): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7393): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7393): >>>>> Normal User
,E/dalvikvm( 7393): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7393): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7393): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7393): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7393): Added TimaKesytore provider
,D/dalvikvm( 2420): GC_CONCURRENT freed 4306K, 74% free 25611K/96300K, paused 13ms+28ms, total 292ms
D/dalvikvm( 7393): GC_CONCURRENT freed 2994K, 31% free 9574K/13860K, paused 5ms+2ms, total 52ms
,D/dalvikvm( 7393): WAIT_FOR_CONCURRENT_GC blocked 39ms
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/com.samsung.app( 7393): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7393): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7393): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7393): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7393): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7393): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5409): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7393): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5409): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7393): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5409): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7393): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7393): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2420): Killing 6349:com.sec.phone/1001 (adj 15): empty #43
,D/Headlines( 5942): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5942): getCountryCode(): countryCode = PL
,D/Headlines( 5942): Breath.onCreate
,D/Headlines( 5942): Breath timer started. interval : 30000
,I/SELinux ( 7425): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7425):  
,V/AlarmManager( 2420): waitForAlarm result :8
D/Headlines( 5942): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5942): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5942): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5942): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5942): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5942): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5942): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7425): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7425):  
I/SELinux ( 7425):  
,I/SELinux ( 7425): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7425): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7425): >>>>> Normal User
,E/dalvikvm( 7425): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7425): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7425): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7425): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7425): Added TimaKesytore provider
,D/WifiP2pService( 2420): InactiveState{ what=143375 }
,D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2420): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/dalvikvm( 7425): GC_CONCURRENT freed 2998K, 31% free 9575K/13860K, paused 4ms+2ms, total 40ms
,D/dalvikvm( 7425): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2420): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2420): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2420): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2420): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2420): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
D/ConnectivityService( 2420): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2420): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2420): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/ConnectivityService( 2420): handleConnectivityChange: setting default proxy info 
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/WebViewChromium( 7425): Binding Chromium to the background looper Looper (main, tid 1) {42294108}
,I/chromium( 7425): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7425): Initializing chromium process, renderers=0
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,W/chromium( 7425): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/PackageManager( 2420): [MSG] WRITE_PACKAGE_RESTRICTIONS
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,D/libEGL  ( 7425): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7425): loaded /system/lib/egl/libGLESv1_CM_mali.so
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/libEGL  ( 7425): loaded /system/lib/egl/libGLESv2_mali.so
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
I/Mali    ( 7425): Mali API Version : 401
,I/Mali    ( 7425): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): updateIfacesLocked()
V/NetworkStats( 2420): performPollLocked(flags=0x1)
V/NetworkStats( 2420): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): performPollLocked() took 24ms
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/GAV2    ( 7425): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ContextImpl( 7425): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,I/NSApplication( 7425): Starting up...
,I/iu.Environment( 6011): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5210): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5210): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5210): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422a3f20
,I/SELinux ( 7480): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7480):  
,I/SELinux ( 7480): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7480):  
I/SELinux ( 7480):  
,I/SELinux ( 7480): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7480): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7480): >>>>> Normal User
,E/dalvikvm( 7480): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7480): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/TimaKeyStoreProvider( 7480): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7480): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7480): Added TimaKesytore provider
,D/Tethering( 2420): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2420): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2420): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2579): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2579): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2579): updateDataNetType()
D/STATUSBAR-NetworkController( 2579): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4785): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection...
,D/dalvikvm( 7480): GC_CONCURRENT freed 2985K, 31% free 9585K/13860K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 7480): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,I/SELinux ( 7500): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7500):  
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,I/ActivityManager( 2420): Killing 6420:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,W/ActivityManager( 2420): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 7500): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7500):  
I/SELinux ( 7500):  
,I/SELinux ( 7500): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7500): [DEBUG] seapp_context_lookup: seinfoCategory = release
,E/dalvikvm( 7500): >>>>> Normal User
,E/dalvikvm( 7500): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,I/SELinux ( 7504): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7504):  
,E/SELinux ( 7500): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7500): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7500): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7500): Added TimaKesytore provider
,I/ActivityManager( 2420): Killing 6062:com.android.calendar/u0a144 (adj 15): empty #43
I/SELinux ( 7504): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7504):  
I/SELinux ( 7504):  
I/SELinux ( 7504): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7504): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7504): >>>>> Normal User
E/dalvikvm( 7504): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
E/SELinux ( 7504): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7504): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7504): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7504): Added TimaKesytore provider
,D/dalvikvm( 7500): GC_CONCURRENT freed 3013K, 32% free 9562K/13864K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 7500): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/BadgeProvider( 7500): onCreate
,D/BadgeProvider( 7500): DatabaseHelper
,D/BadgeProvider( 7500): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
D/dalvikvm( 7504): GC_CONCURRENT freed 2999K, 31% free 9573K/13864K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 7504): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/BadgeProvider( 7500): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7500): sendNotify, [notify] : null
D/BadgeProvider( 7500): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7500): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7500): update, [UpdateCount] : 1
,D/Launcher.Model( 2780): reloadBadges entered.
,D/hcjo    ( 6032): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6032): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6032): exit::IDLE
,D/InitializeManagerStateMachine( 6032): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 6032): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6032): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6032): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6032): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6032): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6032): entry::SUCCESS
,D/hcjo    ( 6032): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6032): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6032): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,E/SPPClientService( 5614): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5614): [SystemStateMoniter] Current Time : 282224
,E/SPPClientService( 5614): [SystemStateMoniter] No Connect : true
,D/InitializeManagerStateMachine( 6032): exit::SUCCESS
,D/InitializeManagerStateMachine( 6032): entry::IDLE
,E/SPPClientService( 5614): [[SystemStateMonitorService]] No Active Internet
,I/dalvikvm( 7247): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 7247): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7247): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 7247): Shutting down VM
,W/dalvikvm( 7247): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,D/NearbySettings( 4759): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4759): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4759): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 4759): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4759): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4759): MountReceiver.onReceive - Keep current state
E/AndroidRuntime( 7247): FATAL EXCEPTION: main
E/AndroidRuntime( 7247): Process: com.test.thalitest, PID: 7247
E/AndroidRuntime( 7247): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 7247): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 7247): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 7247): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 7247): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 7247): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 7247): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 7247): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 7247): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 7247): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 7247): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 7247): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7247): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7247): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7247): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7247): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7247): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7247): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7247): 	at dalvik.system.NativeStart.main(Native Method)
,D/Headlines( 5942): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
W/ActivityManager( 2420):   Force finishing activity com.test.thalitest/.MainActivity
D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager( 2420): Killing 6231:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/Headlines( 5942): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
E/SPPClientService( 5614): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5614): [a] [ConnectionManager] Connection is already disconnected.
,D/Headlines( 5942): Breath 1784 latestRequest time : 1450736273852 current time : 1450736275636
,D/CrashAnrDetector( 2420): processName: com.test.thalitest
,D/CrashAnrDetector( 2420): broadcastEvent : com.test.thalitest data_app_crash
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/Process ( 7247): Sending signal. PID: 7247 SIG: 9
D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2420): mDVFSHelper.acquire()
,D/NearbySettings( 4759): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4759): MountReceiver.onReceive - Keep current state
,I/DBG_DM  ( 4785): [3.19.140541][Line:408][onResume] 
I/ActivityManager( 2420): Killing 6266:com.google.android.music:main/u0a125 (adj 15): empty #43
,E/SPPClientService( 5614): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,I/DBG_DM  ( 4785): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
,E/SPPClientService( 5614): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/SurfaceFlinger( 1922): id=19 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1922): id=19 Removed NainActivit (-2/10)
I/ActivityManager( 2420): Process com.test.thalitest (pid 7247) (adj 9) has died.
,I/WindowState( 2420): WIN DEATH: Window{42e16648 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/DBG_DM  ( 4785): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
I/SurfaceFlinger( 1922): id=19 Removed NainActivit (-2/10)
,D/NearbySettings( 4759): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4759): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4759): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 4759): DMSUtil.isNetworkConnected - P2P: IDLE
,I/DBG_DM  ( 4785): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
I/NearbySettings( 4759): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4759): MountReceiver.onReceive - Keep current state
,I/DBG_DM  ( 4785): [3.19.140541][Line:418][onResume] Postpone Count : 26
,I/DBG_DM  ( 4785): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4785): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,E/SPPClientService( 5614): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,I/SurfaceFlinger( 1922): id=20 createSurf (1x1),1 flag=4, Uoast
,I/DBG_DM  ( 4785): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,E/SPPClientService( 5614): [a] [ConnectionManager] Connection is already disconnected.
D/STATUSBAR-StatusBarManagerService( 2420): sendNotification(2) - 4
,I/DBG_DM  ( 4785): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
D/PowerManagerService( 2420): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2420
,E/SPPClientService( 5614): [g] getNetMCC return empty string
,D/NearbySettings( 4759): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4759): MountReceiver.onReceive - Keep current state
,I/DBG_DM  ( 4785): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4785): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4785): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4785): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4785): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
I/PCWCLIENTTRACE_PushUtil( 6669): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6669): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6669): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6669): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 4785): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/PhoneStatusBar( 2579): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/Activity( 4785): setTransGradationMode to true
,D/StatusBarManagerService( 2420): semi p:4785,o:t
I/DBG_DM  ( 4785): [3.19.140541][Line:400][onPause] 
,I/SurfaceFlinger( 1922): id=21 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection...
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 2420): Got RemoteException sending setActive(false) notification to pid 7247 uid 10573
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2420): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@8
,I/KLMS-2.3.201 : ( 7356): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7356): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450736276045
,I/KLMS-2.3.201 : ( 7356): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7368): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3467): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,I/SO_AGENT( 7368): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
D/GalaxyFinderApplication( 3467): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3467): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3467): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 3595): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7537): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7537):  
,I/SELinux ( 7541): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7541):  
I/SELinux ( 7537): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7537):  
I/SELinux ( 7537):  
,I/SELinux ( 7537): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7537): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7537): >>>>> Normal User
,E/dalvikvm( 7537): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7537): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 5879): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5879): [BDLM] already registered in spp
I/SA      ( 5879): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5879): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5879): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5879): [OR] == isSIMCardReady false ==
,I/SA      ( 5879): [SCU] == networkStateCheck == true
I/SA      ( 5879): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5879): isChinaCountryCode : false
,I/SA      ( 5879): [OR] == networkStateCheck true ==
,D/TimaKeyStoreProvider( 7537): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7537): Cannot add TimaSignature Service, License check Failed
,I/SA      ( 5879): [OR] GetMyCountryZoneTask
D/ActivityThread( 7537): Added TimaKesytore provider
,I/SA      ( 5879): [OR] onReceive END
,I/SA      ( 5879): [SRS] prepareGetMyCountryZone
,I/SA      ( 5879): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5879): [SSP] query invoked
I/SELinux ( 7541): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7541):  
I/SELinux ( 7541):  
,I/SELinux ( 7541): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7541): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7541): >>>>> Normal User
,E/dalvikvm( 7541): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7541): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 5879): [TPMU] GetMccFromDB : null
I/SA      ( 5879): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5879): [TPM] isNoProxy(default) : true
,I/SA      ( 5879): [RC New] Execute method=[GET] start
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7380): Other Intent
,D/TimaKeyStoreProvider( 7541): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7541): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7541): Added TimaKesytore provider
,D/com.samsung.app( 7393): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7393): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5942): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/dalvikvm( 7537): GC_FOR_ALLOC freed 3013K, 32% free 9559K/13864K, paused 21ms, total 21ms
,D/HeadlinesChannelUtil( 5942): getCountryCode(): countryCode = PL
D/Headlines( 5942): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5942): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5942): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5942): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5942): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5942): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5942): requestUpdateNewsWelcomeCard !!! no welcome card
,D/dalvikvm( 7537): GC_CONCURRENT freed 237K, 31% free 9572K/13864K, paused 3ms+5ms, total 20ms
,I/iu.Environment( 6011): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5210): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5210): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5210): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422a3f20
,D/dalvikvm( 7541): GC_CONCURRENT freed 3006K, 31% free 9563K/13860K, paused 3ms+1ms, total 31ms
,D/dalvikvm( 7541): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,I/System.out( 7337): Thread-639(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7337): Thread-639(ApacheHTTPLog):isShipBuild true
,I/System.out( 7337): Thread-639(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/hcjo    ( 6032): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6032): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6032): exit::IDLE
,D/InitializeManagerStateMachine( 6032): entry::NETWORK_CHECK
,V/KVNProvider( 7541): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
D/InitializeManagerStateMachine( 6032): execute::NETWORK_CHECK:NETWORK_STATE_OK
,V/KVNProvider( 7541): getFindoCursor query string : 
,D/InitializeManagerStateMachine( 6032): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6032): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6032): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6032): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6032): entry::SUCCESS
,D/hcjo    ( 6032): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 6032): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6032): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6032): exit::SUCCESS
,D/InitializeManagerStateMachine( 6032): entry::IDLE
,V/KVNProvider( 7541): getTagSearchCursor() tagSearchCursor count : 0
,E/SPPClientService( 5614): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5614): [SystemStateMoniter] Current Time : 283092
,E/SPPClientService( 5614): [SystemStateMoniter] No Connect : false
,I/System.out( 7337): AsyncTask #1 calls detatch()
,W/System.err( 7337): com.sec.android.fota.osp.http.RestClientException
,W/System.err( 7337): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7337): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7337): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7337): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 7337): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7337): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7337): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7337): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7337): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7337): Caused by: java.lang.NullPointerException
W/System.err( 7337): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7337): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7337): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7337): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7337): 	... 8 more
,D/dalvikvm( 5614): GC_CONCURRENT freed 2010K, 25% free 10452K/13844K, paused 2ms+3ms, total 29ms
,D/dalvikvm( 5614): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/SA      ( 5879): [RC New] [v2liruge] api execute + 625
,I/SA      ( 5879): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5879): AsyncTask #2 calls detatch()
,I/SA      ( 5879): [TPMU] getNetworkMcc : 
,I/SA      ( 5879): [SCU] saveMccToPreferece Start
,I/SA      ( 5879): [SCU] RegionMCC : 260
,I/SA      ( 5879): [SSP] query invoked
I/SA      ( 5879): [TPMU] GetMccFromDB : null
,I/SA      ( 5879): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5879): [SCU] saveMccToPreferece End
I/SA      ( 5879): [RC New] executeRequest [v2liruge] end. 647
,I/SA      ( 5879): [RC New] Execute end
I/SA      ( 5879): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5879): [OR] GetMyCountryZoneTask Success
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@8
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/WifiStateMachine( 2420): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/SPPClientService( 5614): [b] __InitReply__
,I/ActivityManager( 2420): Killing 6612:com.android.defcontainer/u0a6 (adj 15): empty #43
,I/SurfaceFlinger( 1922): id=20 Removed Uoast (10/11)
,I/SurfaceFlinger( 1922): id=20 Removed Uoast (-2/11)
,D/PowerManagerService( 2420): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2420) eventTime = 285996
,D/PowerManagerService( 2420): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2420 (0x0)
,D/PowerManagerService( 2420): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2420, ws=WorkSource{1000}) (elapsedTime=3498)
,I/GAV2    ( 7425): Thread[GAThread,5,main]: No campaign data found.
,W/WifiP2pStateTracker( 2420): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2420): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2420):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2420): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2420): updateSourceRoutes : no source routing conditions
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): stay LED for fully charged
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/PCWCLIENTTRACE_SYSTEMReceiver( 6669): mConnectivityHandler : connected
W/PCWCLIENTTRACE_AccountUtil( 6669): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6669): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6669): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6669): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6669): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6669): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6669): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6669): [ensureRegistration] - No Samsung account
,E/Watchdog( 2420): !@Sync 9
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 295, prevStep = 4, currStep = 4
,D/CaptivePortalTracker( 2420): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 2420): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2420): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 2420): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 2420): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2420): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2420): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2420): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 6032): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6032): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6032): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6032): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6032): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 6032): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6032): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 6032): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6032): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6032): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6032): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6032): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6032): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6032): entry::IDLE
,I/PowerManagerService( 2420): [PWL] Off : 225s ago
,I/ActivityManager( 2420): Waited long enough for: ServiceRecord{475d7960 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 2420): Waited long enough for: ServiceRecord{46b22240 u0 com.sec.spp.push/.PushClientService}
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = -10
,D/AmoledAdjustTimer( 2420): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 7714
,D/BatteryService( 2420): level:100, scale:100, status:3, health:9, present:true, voltage: 4370, temperature: 295, technology: Li-ion, AC powered:false, USB powered:false, Wireless powered:false, icon:17303678, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
D/LightsService( 2420): [api] [SvcLED] turnOff:: id = 3 (uid: 0 pid: 0) 
,D/LightsService( 2420): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
,D/lights  ( 2420): led_pattern : 0 +
D/LightsService( 2420): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/BatteryService( 2420): turn off LED
,D/lights  ( 2420): led_pattern : 0 -
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/PowerManagerService( 2420): [api] updateIsPoweredLocked : mIsPowered: false mPlugType: 0
I/PowerManagerService( 2420): !@[ps] Screen__On :  powered change
I/PowerManagerService( 2420): Waking up from sleep...
D/PowerManagerService( 2420): Screen Readiness Inspection requested: mNestCount=1
D/PowerManagerService( 2420): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2420): [s] WAKEFULNESS_AWAKE
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/lights  ( 2420): button : 1 +
,D/lights  ( 2420): button : 1 -
,I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 5
D/PowerManagerService( 2420): [s] UserActivityState : 0 -> 1
D/PowerManagerService( 2420): [PWL] sb acquire: PowerManagerService.Display
D/DisplayPowerController( 2420): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
I/DisplayPowerController( 2420): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
I/DisplayPowerController( 2420): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
,D/DisplayPowerController( 2420): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/Sensors ( 2420): LightSensor setDelay = 200000000
D/Sensors ( 2420): LightSensor setSensorDelay = 200000000
D/Sensors ( 2420): Light sensor flush: not enabled 0
D/Sensors ( 2420): LightSensor enable = 1
D/Sensors ( 2420): LightSensor enableSensor = 1
,D/SensorManager( 2420): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 1
D/PowerManagerService( 2420): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 5ms
D/PowerUI ( 2579): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/DisplayPowerController( 2420): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2420): [DAB] no lux value from sensor manager
,I/Sensors ( 2420): HAL: batch Dry Run is complete
,I/Sensors ( 2420): HAL:resetDataRates mEnabled=4
D/DisplayPowerController( 2420): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/libsuspend( 2420): !@[s] autosuspend_autosleep_disable
,I/libsuspend( 2420): !@[s] autosuspend_autosleep_disable done
,D/SurfaceFlinger( 1922): Screen acquired, type=0 flinger=0x40bec550
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/PowerManagerService( 2420): unblankAllDisplays() is called.
,D/PowerManagerService( 2420): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/SensorManager( 2420): registerListener :: 2, MPL Accelerometer, 200000, 0,  
D/PowerManagerService( 2420): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 17ms
D/RampAnimator( 2420): Light Animator Finished currentValue=8
,I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 65558
,D/PowerManagerService( 2420): [api] [s] wakeUp (uid: 10019 pid: 2579) eventTime = 307273
D/SensorService( 2420): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2420): AutoRotationSensor::activate (ident=0x77db6e48, enabled=1)
D/SensorService( 2420): AutoRotationSensor::AR_init
,I/Sensors ( 2420): HAL: batch Dry Run is complete
D/UsbDeviceManager( 2420): handleMessage -> MSG_POWER_STATE = 0
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:3 health:9
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,I/Sensors ( 2420): HAL:resetDataRates mEnabled=4
W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
D/NotificationService( 2420): cancelNotificationLocked
D/NotificationService( 2420):  hasClearableItems
D/NotificationService( 2420):  has clearable items no 
D/NotificationService( 2420): cancelNotificationLocked: cancel alarm
,D/NotificationService( 2420): cancelNotificationLocked: cancel alarm
D/UsbDeviceManager( 2420): sending intent : ACTION_USB_CABLE_STATE : connected = false
D/STATUSBAR-StatusBarManagerService( 2420): sendNotification(3) - 5
,D/SensorManager( 2420): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
V/KeyguardServiceDelegate( 2420): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@423b9a90)
I/SELinux ( 7737): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7737):  
D/KeyguardViewMediator( 2579): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 2579): notifyScreenOnLocked
D/KeyguardViewMediator( 2579): handleNotifyScreenOn
D/KeyguardViewManager( 2579): onScreenTurnedOn()
,V/KeyguardServiceDelegate( 2420): **** SHOWN CALLED ****
,I/KeyguardEffectViewMain( 2579): *** KeyguardEffectView getInstance ***
,V/KeyguardViewManager( 2579): send wm null token: host was null
D/VisualEffectParticleEffect( 2579): KeyguardEffectViewParticleSpace : screenTurnedOn
,D/VisualEffectParticleEffect( 2579): screenOnAnimationStart
D/LightsService( 2420): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2420) 
D/LightsService( 2420): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/UsbDeviceManager( 2420): received ACTION_POWER_DISCONNECTED = -1
D/LightsService( 2420): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/InputDispatcher( 2420): setInputDispatchMode: enabled=1, frozen=0
I/WindowManager( 2420): No lock screen! windowToken=null
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/PowerManagerNotifier( 2420): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,D/LockPatternUtils( 2579): isPcwEnable = 10
D/PowerManagerService( 2420): Screen Readiness Inspection completed: mNestCount=0
D/DisplayPowerController( 2420): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 2420): !@ElectronBeam exit
I/SurfaceFlinger( 1922): id=14 Removed FlectronBea (10/10)
I/SurfaceFlinger( 1922): id=14 Removed FlectronBea (-2/10)
D/lights  ( 2420): lcd : 8 +
D/lights  ( 2420): lcd : 8 -
,I/SELinux ( 7737): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7737):  
I/SELinux ( 7737):  
,I/SELinux ( 7737): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/DisplayPowerController( 2420): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
E/SELinux ( 7737): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7737): >>>>> Normal User
,E/dalvikvm( 7737): >>>>> com.sec.android.Kies [ userId:0 | appId:1000 ]
,D/dalvikvm( 1923): GC_EXPLICIT freed 43K, 13% free 9506K/10840K, paused 4ms+6ms, total 69ms
,D/PowerManagerService( 2420): [s] mDisplayPowerControllerCallbacks : onStateChanged()
E/SELinux ( 7737): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/BatteryMeterView( 2579): onDraw batteryColor : -1
,D/SensorService( 2420): AutoRotationSensor::process: Acc  eventTimestamp = 307377133317, previousAccTimestamp = 68859621717, difference = 238517511600 
,D/SensorService( 2420): AutoRotationSensor::reset oldrotation = [100], initState = [1]
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 13% free 9506K/10840K, paused 5ms+7ms, total 56ms
,D/DisplayPowerController( 2420): [api] [DAB] onSensorChanged : 1st lux : 0.0
,D/DisplayPowerController( 2420): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
,D/TimaKeyStoreProvider( 7737): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7737): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7737): Added TimaKesytore provider
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 13% free 9506K/10840K, paused 5ms+6ms, total 58ms
D/SensorService( 2420): AutoRotationSensor::process: Acc  eventTimestamp = 307443796308, previousAccTimestamp = 68859621717, difference = 238584174591 
D/SensorService( 2420):  [AR] 0.3 -0.0 9.9
,D/SensorService( 2420): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
,D/SurfaceControl( 2420): Excessive delay in unblankDisplay() while turning screen on: 250ms
,D/MISC PowerHAL( 2420): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2420): sysfs_write +: /sys/class/input/input1/enabled: 1
D/PowerManagerService( 2420): Excessive delay in mDisplayManagerService.unblankAllDisplaysFromPowerManager(): 251ms
,D/LockPatternUtils( 2579): isPcwEnable = 10
,D/LightsService( 2420): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2420) 
,D/LightsService( 2420): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2420): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/MISC PowerHAL( 2420): sysfs_write -: /sys/class/input/input1/enabled: 1
D/MISC PowerHAL( 2420): miscpower_set_interactive: /sys/class/input/input0/enabled
,D/MISC PowerHAL( 2420): sysfs_write +: /sys/class/input/input0/enabled: 1
D/PalmMotionService( 2420): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/SamsungIME( 2983): showDlgMsgBox : false true true
,D/PalmMotionService( 2420): SURFACE_PALM_SWIPE: 1
,E/MotionRecognitionService( 2420):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
I/FPMS_FingerprintManagerService( 2599): onReceive: android.intent.action.USER_PRESENT
,I/NfcService( 2765): applyRouting return - 2 
,D/SSRMv2:TSP:AirViewOnOff( 2420): SettingsAirViewInfo:: 000000000
E/NfcService( 2765): callback == null
I/DBG_DM  ( 4785): [3.19.140541][Line:408][onResume] 
I/display ( 1922): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,I/DBG_DM  ( 4785): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2420): ACTION_SCREEN_ON
D/LightsService( 2420): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2420) 
D/LightsService( 2420): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2420): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/AudioHardwareTinyALSA( 1926): setParameters(screen_state=on)
,I/SecExternalDisplayIntents_Java( 2420): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/DBG_DM  ( 4785): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
D/IpRemoteDisplayController( 2420): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2420): Bridge Server is not available
,D/PersonaManagerService( 2420): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 2420): MSG_ACTION_SCREEN_ON called
,I/DBG_DM  ( 4785): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
D/dalvikvm( 7737): GC_CONCURRENT freed 3003K, 31% free 9568K/13860K, paused 5ms+2ms, total 42ms
,D/dalvikvm( 7737): WAIT_FOR_CONCURRENT_GC blocked 31ms
,I/NfcService( 2765): NFC: Screen On & Cover Open
,I/DBG_DM  ( 4785): [3.19.140541][Line:418][onResume] Postpone Count : 26
,I/NfcService( 2765): applyRouting return - 2 
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
E/NfcService( 2765): callback == null
D/MISC PowerHAL( 2420): sysfs_write -: /sys/class/input/input0/enabled: 1
D/MISC PowerHAL( 2420): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 2420): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 2420): Excessive delay in MISC setInteractive(true) while turning screen on: 180ms
D/SEC PowerHAL( 2420): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2420): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2420): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2420): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2420): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2420): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2420): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
,D/SEC PowerHAL( 2420): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
,I/KIES_RECEIVE( 7737): [APK BnR] Receive KIES_USB_DISCONNECT
D/PowerManagerService( 2420): Excessive delay in nativeSetInteractive(true): 182ms
D/PowerManagerService( 2420): SecHardwareInterface.setBatteryADC : true
W/ContextImpl( 7737): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 android.content.ContextWrapper.stopService:511 com.sec.android.Kies.kies_receiver.onReceive:170 android.app.ActivityThread.handleReceiver:2698 
,I/DBG_DM  ( 4785): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,E/TranscodeReceiver( 7537): onReceive : android.intent.action.ACTION_POWER_DISCONNECTED
,D/videowall-Global( 7537): core_num = 4
,D/dalvikvm( 7537): No JNI_OnLoad found in /system/lib/libsavsff.so 0x42294650, skipping init
D/STATUSBAR-NetworkController( 2579): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,I/DBG_DM  ( 4785): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,W/linker  ( 7537): libvwengine.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/videowall-Global( 7537): density : 2.0 width : 720 height : 1280 Raw width : 720 Raw height : 1280
,D/videowall-Global( 7537): dsp : 720, swkey : false, Cores : 4, Clock : 0
,I/DBG_DM  ( 4785): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/SELinux ( 7752): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7752):  
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2420): sendNotification(2) - 4
,I/DBG_DM  ( 4785): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
,I/SELinux ( 7752): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7752):  
I/SELinux ( 7752):  
,I/SELinux ( 7752): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7752): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 7752): >>>>> Normal User
,E/dalvikvm( 7752): >>>>> com.android.chrome [ userId:0 | appId:10085 ]
,E/SELinux ( 7752): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,I/DBG_DM  ( 4785): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,D/TimaKeyStoreProvider( 7752): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7752): Cannot add TimaSignature Service, License check Failed
,I/DBG_DM  ( 4785): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
D/ActivityThread( 7752): Added TimaKesytore provider
,I/DBG_DM  ( 4785): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4785): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4785): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4785): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4785): setTransGradationMode to true
,D/PhoneStatusBar( 2579): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2420): semi p:4785,o:t
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
D/dalvikvm( 6501): GC_CONCURRENT freed 2517K, 28% free 10063K/13868K, paused 7ms+4ms, total 75ms
,D/QuickConnect[1.1][2] ( 5210): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
D/dalvikvm( 7752): GC_CONCURRENT freed 2997K, 31% free 9579K/13864K, paused 4ms+2ms, total 36ms
,D/dalvikvm( 7752): WAIT_FOR_CONCURRENT_GC blocked 28ms
,V/QuickConnect[1.1][2] ( 5210): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5210): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5210): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422a3f20
,V/QuickConnect[1.1][2] ( 5210): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422a3f20
V/QuickConnect[1.1][2] ( 5210): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 5210): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422a3f20
V/QuickConnect[1.1][2] ( 5210): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422a3f20
V/QuickConnect[1.1][2] ( 5210): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422a3f20
D/QuickConnect[1.1][2] ( 5210): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 5210): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 5210): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 5210): BleHelper.startScan - shouldScanBleFg = false
,D/daemonapp( 5409): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5409): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/PowerManagerService( 2420): [PWL] sb release: PowerManagerService.Broadcasts
,I/SELinux ( 7768): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7768):  
,I/ActivityManager( 2420): Killing 6523:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,I/SELinux ( 7768): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7768):  
I/SELinux ( 7768):  
,I/SELinux ( 7768): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7768): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7768): >>>>> Normal User
,E/dalvikvm( 7768): >>>>> com.google.android.apps.uploader [ userId:0 | appId:10117 ]
,E/SELinux ( 7768): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/TimaKeyStoreProvider( 7768): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7768): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7768): Added TimaKesytore provider
,D/dalvikvm( 7768): GC_CONCURRENT freed 3004K, 31% free 9560K/13856K, paused 2ms+2ms, total 28ms,
,D/dalvikvm( 7768): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 2420): GC_EXPLICIT freed 3690K, 74% free 25005K/96116K, paused 12ms+20ms, total 238ms
,D/MetricsUtils( 7768): [QUERY ******************************** query-result:1 time:235]
D/PicasaUploader( 7768):    wifiOnlyPhoto changed to true
D/PicasaUploader( 7768):    wifiOnlyVideo changed to true
,D/PicasaUploader( 7768):    syncOnBattery changed to true
,D/PicasaUploaderSync( 7768): sync account database
,I/iu.Environment( 6011): update battery state; isPlugged? false*
,D/PicasaUploaderSync( 7768): accounts in DB=1
,I/iu.SyncManager( 6011): SYNC; picasa accounts
D/PicasaUploaderSyncManager( 7768): active network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PicasaUploaderSyncManager( 7768): background data: true
,I/ActivityManager( 2420): Killing 6641:com.samsung.groupcast/u0a15 (adj 15): empty #43
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
I/iu.Environment( 3159): update battery state; isPlugged? false*
,I/GCoreUlr( 2737): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_DISCONNECTED}]
,I/iu.UploadsManager( 3159): num queued entries: 0
,I/iu.UploadsManager( 6011): num queued entries: 0
D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,I/iu.UploadsManager( 3159): num updated entries: 0
,I/iu.UploadsManager( 6011): num updated entries: 0
,I/GCoreUlr( 2737): DispatchingService.onCreate()
,I/iu.SyncManager( 3159): NEXT; no task
,D/PicasaUploaderSyncManager( 7768): battery info: false
,I/iu.SyncManager( 6011): NEXT; no task
,D/SSRMv2:TSP:AirViewOnOff( 2420): SettingsAirViewInfo:: 000000000
D/LockPatternUtils( 2579): isPcwEnable = 10
,I/GCoreUlr( 2737): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_DISCONNECTED
,D/lights  ( 2420): button : 0 +
,D/lights  ( 2420): button : 0 -
,D/daemonapp( 5409): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5409): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5409): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5409): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5409): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 5409): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5409): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5409): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5409): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 5409): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5409): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 5409): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5409): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 5409): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1450757640000
,D/daemonapp( 5409): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1450736302123
,D/daemonapp( 5409): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5409): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5409): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5409): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5409): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5409): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/GCoreUlr( 2737): WorldUpdater:android.intent.action.ACTION_POWER_DISCONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2737): Unbound from all location providers
,I/GCoreUlr( 2737): Place inference reporting - stopped
,I/GCoreUlr( 2737): DispatchingService.onDestroy(),
,I/GCoreUlr( 2737): Stopping handler for UlrDispSvcFast,
,I/GCoreUlr( 2737): Unbound from all location providers,
,I/GCoreUlr( 2737): Place inference reporting - stopped,
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2420):   0.3 -0.0 9.9
,V/AlarmManager( 2420): waitForAlarm result :8
,D/Headlines( 5942): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5942): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5942): Breath 27600 latestRequest time : 1450736276272 current time : 1450736303872
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/AmoledAdjustTimer( 2420): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 2420): initializing...
,I/TLC_TIMA_PKM_initialize( 2420): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 2420): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2420): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2420): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 2420): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2420): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2420): aligned max_sendmsg_size = 262208
,I/TZ: mc_tlc_communication( 2420): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2420): device_id = 0x0
I/TZ: mc_tlc_communication( 2420): tlc_open() was called
,I/TZ: mc_tlc_communication( 2420): Opening MobiCore device
,I/TZ: mc_tlc_communication( 2420): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 2420): Opening the session
,I/TZ: mc_tlc_communication( 2420): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2420): Trustlet response is completed
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2420):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2420):   0.3 -0.0 9.8
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2420): level:100, scale:100, status:2, health:2, present:true, voltage: 4355, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/PowerManagerService( 2420): [api] updateIsPoweredLocked : mIsPowered: true mPlugType: 2
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/PowerUI ( 2579): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2420): [api] [s] wakeUp (uid: 10019 pid: 2579) eventTime = 317173
,D/PowerUI ( 2579): playSound : 1
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/UsbDeviceManager( 2420): handleMessage -> MSG_POWER_STATE = 1
D/UsbDeviceManager( 2420): sending intent : ACTION_USB_CABLE_STATE : connected = true
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,I/EntropyMixer( 2420): Writing entropy...
V/Vibrator( 2579): Called vibrateImmVibe(int) API - PUID: 10019, PackageName: com.android.keyguard
V/Vibrator( 2579): vibrateImmVibe - PUID: 10019, PackageName: com.android.keyguard, type: 10, magType: TouchMagnitude
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
V/VibratorService( 2420): vibrateImmVibeMagnitudeType - magnitudeType: TouchMagnitude
V/VibratorService( 2420): vibrate - package: com.android.keyguard, ms: 100, token: null
D/VibratorService( 2420): JNI vibratorOff()
D/VibratorService( 2420): JNI vibratorOn() : 100
D/PowerUI ( 2579): RINGER_MODE_VIBRATE
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
E/TranscodeReceiver( 7537): onReceive : android.intent.action.ACTION_POWER_CONNECTED
I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,D/BatteryMeterView( 2579): onDraw batteryColor : -1
I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,I/SCloudBackupReceiver( 7380): Other Intent
,D/TranscodeService( 7537): onCreate()
,D/PicasaUploaderSyncManager( 7768): battery info: true
,I/iu.Environment( 6011): update battery state; isPlugged? true*
,D/dalvikvm( 7537): No JNI_OnLoad found in /system/lib/libsavsvc.so 0x42294650, skipping init
,D/dalvikvm( 7537): No JNI_OnLoad found in /system/lib/libsavscmn.so 0x42294650, skipping init
,D/dalvikvm( 7537): No JNI_OnLoad found in /system/lib/libsthmb.so 0x42294650, skipping init
,I/iu.UploadsManager( 6011): num queued entries: 0
D/TranscodeService( 7537): power? : true / screen off : false
,D/TranscodeService( 7537): releaseTranscodeThread.
,I/iu.UploadsManager( 6011): num updated entries: 0
,D/VibratorService( 2420): JNI vibratorOff()
I/iu.SyncManager( 6011): NEXT; no task
I/iu.FingerprintManager( 6011): Start processing all media
I/iu.FingerprintManager( 6011): Start processing media store URI: content://media/external/images/media
,I/iu.Environment( 3159): update battery state; isPlugged? true*
,I/iu.FingerprintManager( 6011): Start processing media store URI: content://media/external/video/media
,I/iu.UploadsManager( 3159): num queued entries: 0
,I/iu.UploadsManager( 3159): num updated entries: 0
,I/iu.SyncManager( 3159): NEXT; no task
,E/NetworkScheduler.SchedulerReceiver( 2847): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 2847): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/iu.FingerprintManager( 6011): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 6011): Start processing media store URI: content://media/phoneStorage/video/media
,I/GCoreUlr( 2737): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_CONNECTED}]
I/iu.FingerprintManager( 3159): Start processing all media
I/iu.FingerprintManager( 6011): Finished generating fingerprints; 0.048 seconds
,I/iu.FingerprintManager( 6011):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/GCoreUlr( 2737): DispatchingService.onCreate()
,I/iu.FingerprintManager( 3159): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 3159): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 3159): Start processing media store URI: content://media/phoneStorage/images/media
,I/GCoreUlr( 2737): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_CONNECTED
,D/dalvikvm( 2725): GC_EXPLICIT freed 362K, 28% free 9971K/13848K, paused 4ms+6ms, total 56ms
,I/iu.FingerprintManager( 3159): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 3159): Finished generating fingerprints; 0.110 seconds
,I/iu.FingerprintManager( 3159):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/GCoreUlr( 2737): WorldUpdater:android.intent.action.ACTION_POWER_CONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2737): Unbound from all location providers
,I/GCoreUlr( 2737): Place inference reporting - stopped
,D/dalvikvm( 3159): GC_CONCURRENT freed 2156K, 22% free 12540K/15984K, paused 11ms+7ms, total 82ms
,I/GCoreUlr( 2737): DispatchingService.onDestroy()
,I/GCoreUlr( 2737): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2737): Unbound from all location providers
,I/GCoreUlr( 2737): Place inference reporting - stopped
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 10
,E/Watchdog( 2420): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2420):   0.3 -0.0 9.9
,D/AmoledAdjustTimer( 2420): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager( 2420): Waited long enough for: ServiceRecord{43173200 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,D/SensorService( 2420):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2420):   0.3 0.0 9.9
,D/BatteryService( 2420): level:100, scale:100, status:2, health:2, present:true, voltage: 4378, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate,
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 0,
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 2579): GC_CONCURRENT freed 15693K, 34% free 33886K/50864K, paused 27ms+10ms, total 122ms
,D/SensorService( 2420):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2420): prevTemp = 295, currTemp = 296, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager( 2420): Waited long enough for: ServiceRecord{47216b70 u0 com.sec.android.app.videoplayer/.videowall.TranscodeService}
,D/SensorService( 2420):   0.3 -0.0 9.9,
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2420):   0.3 0.0 9.9,
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:2,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/PowerManagerService( 2420): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2579
W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/NotificationService( 2420): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200a5 contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
D/STATUSBAR-StatusBarManagerService( 2420): sendNotification(1) - 5
,D/RCPManagerService( 2420): NotificationReceiver onReceive()
,D/RCPManagerService( 2420):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
D/RCPManagerService( 2420): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967298420
D/RCPManagerService( 2420): getPolicy: policy value returned = false
D/RCPManagerService( 2420): going to get the app label for pkg == com.android.systemui
D/RCPManagerService( 2420): app label == com.android.systemui
,D/RCPManagerService( 2420): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967298420
,D/UserManagerService( 2420): User -1does not exists!!
D/RCPManagerService( 2420): getPolicy: policy value returned = true
D/RCPManagerService( 2420): Calling User is -1
,D/RCPManagerService( 2420): userid of SBN ==-1
E/PersonaManagerService( 2420): returning null in  getPersonasForUser
,D/ProgressBar( 2579): setProgressDrawable drawableHeight = 12
,D/PhoneStatusBar( 2579): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@422dece0
,D/BatteryMeterView( 2579): onDraw batteryColor : -1
,I/display ( 1922): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(60)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 0
,I/display ( 1922): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/SensorService( 2420):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,I/display ( 1922): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(60)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/PowerManagerService( 2420): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 2420): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2420): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/lights  ( 2420): lcd : 2 +
D/RampAnimator( 2420): Light Animator Finished currentValue=2
,D/lights  ( 2420): lcd : 2 -
,I/display ( 1922): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/AmoledAdjustTimer( 2420): prevTemp = 296, currTemp = 297, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/SensorService( 2420):   0.3 0.0 9.9
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/display ( 1922): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(60)
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/display ( 1922): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2420):   0.3 -0.0 9.9
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/daemonapp( 5409): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5409): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/PowerManagerService( 2420): [s] UserActivityState : 2 -> 0
I/PowerManagerService( 2420): [PWL] On : 307253 (39918 ms ago)
,I/PowerManagerService( 2420): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
,I/PowerManagerService( 2420): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=2579, ws=null) (elapsedTime=9885)
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 0
,E/Watchdog( 2420): !@Sync 11
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2420):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2420): prevTemp = 297, currTemp = 299, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2420):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 7797): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7797):  
,I/SELinux ( 7797): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7797):  
I/SELinux ( 7797):  
,I/SELinux ( 7797): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7797): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7797): >>>>> Normal User
,E/dalvikvm( 7797): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 7797): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 7797): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7797): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7797): Added TimaKesytore provider
,D/dalvikvm( 7797): GC_CONCURRENT freed 3022K, 32% free 9555K/13864K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 7797): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/Headlines( 5942): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5942): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5942): Breath 72846 latestRequest time : 1450736276272 current time : 1450736349118
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2420):   0.3 -0.0 9.9
,D/PowerManagerService( 2420): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2579 (0x0)
I/PowerManagerService( 2420): Nap time...
,D/PowerManagerService( 2420): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2420): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2420): Going to sleep due to screen timeout...
D/PowerManagerService( 2420): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController( 2420): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
D/Sensors ( 2420): LightSensor enable = 0
,D/Sensors ( 2420): LightSensor enableSensor = 0
D/DisplayPowerController( 2420): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,D/SensorManager( 2420): unregisterListener ::   
,I/Sensors ( 2420): HAL:resetDataRates mEnabled=4
I/DisplayPowerController( 2420): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,I/DisplayPowerController( 2420): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
I/SurfaceFlinger( 1922): id=22 createSurf (720x1280),-1 flag=20004, FlectronBea
,D/SensorManager( 2420): unregisterListener ::   
D/DisplayPowerController( 2420): !@ElectronBeam entry
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/lights  ( 2420): lcd : 0 +
,D/lights  ( 2420): lcd : 0 -
,D/MISC PowerHAL( 2420): miscpower_set_interactive: /sys/class/input/input1/enabled
D/PowerManagerService( 2420): blankAllDisplays() is called.
,D/MISC PowerHAL( 2420): sysfs_write +: /sys/class/input/input1/enabled: 0
V/WindowOrientationListener( 2420): WindowOrientationListener disabled
D/SensorService( 2420): AutoRotationSensor::activate (ident=0x77db6e48, enabled=0)
,I/Sensors ( 2420): HAL: batch Dry Run is complete
,D/KeyguardViewMediator( 2579): onScreenTurnedOff(3)
D/PowerManagerService( 2420): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2420): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 2420): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 2420): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2420): miscpower_set_interactive: /sys/class/input/input0/enabled
D/MISC PowerHAL( 2420): sysfs_write +: /sys/class/input/input0/enabled: 0
D/SensorManager( 2420): unregisterListener ::   
D/InputDispatcher( 2420): setInputDispatchMode: enabled=0, frozen=0
D/MISC PowerHAL( 2420): sysfs_write -: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2420): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2420): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/SEC PowerHAL( 2420): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2420): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2420): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2420): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2420): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2420): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2420): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SEC PowerHAL( 2420): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/PowerManagerService( 2420): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/SurfaceFlinger( 1922): Screen released, type=0 flinger=0x40bec550
,D/LockPatternUtils( 2579): isPcwEnable = 10
,D/LockPatternUtils( 2579): isPcwEnable = 10
,D/SurfaceControl( 2420): Excessive delay in blankDisplay() while turning screen off: 212ms
I/libsuspend( 2420): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2420): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2420): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 212ms
D/PowerManagerService( 2420): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2420): [PWL] Off : 0s ago
I/PowerManagerService( 2420): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2420): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2420): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=2420, ws=null) (elapsedTime=212)
I/PowerManagerService( 2420): [PWL]   PowerManagerService.Broadcasts: ref count=1
,I/display ( 1922): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(29)
,I/DBG_DM  ( 4785): [3.19.140541][Line:400][onPause] 
,I/SQLiteSecureOpenHelper( 4183): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4183): getDatabaseLocked(b,b,pwd)...
,D/KeyguardViewMediator( 2579): setting alarm to turn off keyguard, seq = 2
,D/LightsService( 2420): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2420) 
,D/LightsService( 2420): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 5
D/Sensors ( 2420): LightSensor setDelay = 200000000
D/Sensors ( 2420): LightSensor setSensorDelay = 200000000
D/Sensors ( 2420): Light sensor flush: not enabled 0
D/Sensors ( 2420): LightSensor enable = 1
D/Sensors ( 2420): LightSensor enableSensor = 1
,D/SensorManager( 2420): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2420): turn on LED for fully charged
D/VibratorService( 2420): JNI vibratorOff()
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2420): ACTION_SCREEN_OFF
D/LightsService( 2420): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2420) 
,D/LightsService( 2420): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/AudioHardwareTinyALSA( 1926): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2420): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2420): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2420): Bridge Server is not available
,D/PersonaManagerService( 2420): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2420): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2579):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2579): makeExpandedInvisible
D/PhoneStatusBarView( 2579): marqueeStatusBar:122, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2579):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2765): applyRouting return - 2 
,E/NfcService( 2765): callback == null
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 0
,D/LockPatternUtils( 2579): isPcwEnable = 10
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 0
,D/QuickConnect[1.1][2] ( 5210): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
V/QuickConnect[1.1][2] ( 5210): BleHelper.shouldScanBleBg - 
,D/QuickConnect[1.1][2] ( 5210): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5210): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422a3f20
V/QuickConnect[1.1][2] ( 5210): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422a3f20
,D/QuickConnect[1.1][2] ( 5210): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 5210): BleHelper.stopScan - shouldScanBleBg = false
,I/QuickConnect[1.1][2] ( 5210): BleHelper.stopScan - call stopLeScan()
,D/BluetoothAdapter( 5210): stopLeScan()
,D/QuickConnect[1.1][2] ( 5210): BleHelper.stopScan - call stopLeScan() complete
,E/TranscodeReceiver( 7537): onReceive : android.intent.action.SCREEN_OFF
,D/TranscodeService( 7537): power? : true / screen off : true
D/PowerManagerService( 2420): [PWL] sb release: PowerManagerService.Broadcasts
,D/TranscodeService( 7537): Music is = false
,D/TranscodeService( 7537): runvideoplayer is false
,D/TranscodeService( 7537): Thread start
,D/TranscodeService( 7537): WakeLock.acquire()
,D/videowall-FileMgr( 7537): thumbnailDBSync -1
,D/Sensors ( 2420): LightSensor enable = 0
,D/Sensors ( 2420): LightSensor enableSensor = 0
D/SensorManager( 2420): unregisterListener ::   
,D/lights  ( 2420): led_pattern : 5 +
D/LightsService( 2420): [SvcLED]  onSensorChanged::light value = 0
,D/lights  ( 2420): led_pattern : 5 -
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/WVMDrmPlugIn( 1925): WVMDrmPlugin::onInitialize : 1251
,D/WVMDrmPlugIn( 1925): WVMDrmPlugin::onSetOnInfoListener : add 1251
I/PrGenericPlugin( 1925): [A] ENTER onInitialize : 0x4e3
,I/PrGenericPlugin( 1925): [A] LEAVE onInitialize : 0x4e3
,D/TranscodeService( 7537): Thread end
,D/TranscodeService( 7537): WakeLock.release()
D/TranscodeService( 7537): onDestroy()
,D/TranscodeService( 7537): releaseTranscodeThread.
,V/ApplicationPolicy( 2420): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
,I/ActivityManager( 2420): Killing 6655:com.android.musicfx/u0a24 (adj 15): empty #43
,D/AmoledAdjustTimer( 2420): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,V/AlarmManager( 2420): waitForAlarm result :4,
,D/KeyguardViewMediator( 2579): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2,
,D/LockPatternUtils( 2579): isPcwEnable = 10,
,D/KeyguardViewMediator( 2579): in doKeyguardLocked mIsRollUp false null
,D/PersonaManager( 2579): isKioskContainerExistOnDevice,
,D/LockPatternUtils( 2579): isPcwEnable = 10,
D/LockPatternUtils( 2579): isPcwEnable = 10
,D/KeyguardViewMediator( 2579): doKeyguard: not showing because lockscreen is off,
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/PowerManagerService( 2420): [PWL] Off : 5s ago,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 2420): stay LED for fully charged,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = -10,
,V/AlarmManager( 2420): waitForAlarm result :8,
,D/AmoledAdjustTimer( 2420): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2420): [PWL] Off : 15s ago,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate,
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2420): !@Sync 12,
,D/AmoledAdjustTimer( 2420): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true,
,D/BatteryService( 2420): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,I/PowerManagerService( 2420): [PWL] Off : 30s ago,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,V/AlarmManager( 2420): waitForAlarm result :4,
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5942): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5942): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5942): Breath 105121 latestRequest time : 1450736276272 current time : 1450736381393
,D/AmoledAdjustTimer( 2420): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,V/AlarmManager( 2420): waitForAlarm result :8,
,D/Headlines( 5942): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5942): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5942): Breath 117610 latestRequest time : 1450736276272 current time : 1450736393882,
,D/AmoledAdjustTimer( 2420): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2420): waitForAlarm result :8,
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate,
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2420): [PWL] Off : 50s ago,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2420): !@Sync 13,
,D/AmoledAdjustTimer( 2420): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED,
,D/BatteryService( 2420): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate,
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4009): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,V/AlarmManager( 2420): waitForAlarm result :8,
,D/Headlines( 5942): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5942): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5942): Breath 147610 latestRequest time : 1450736276272 current time : 1450736423883
,D/Headlines( 5942): stop ,
,D/Headlines( 5942): Breath.onDestroy : ,
I/ActivityManager( 2420): Killing 6683:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,D/AmoledAdjustTimer( 2420): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2420): [PWL] Off : 75s ago,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED,
,D/BatteryService( 2420): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4009): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2420): !@Sync 14,
,D/AmoledAdjustTimer( 2420): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2420): stay LED for fully charged,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4009): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2420): [PWL] Off : 105s ago,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2420): waitForAlarm result :8,
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 15,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate,
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = -10,
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2420): [PWL] Off : 140s ago,
,E/Watchdog( 2420): !@Sync 16
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2420): stay LED for fully charged,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4009): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/dalvikvm( 2420): GC_CONCURRENT freed 3138K, 74% free 25641K/96116K, paused 13ms+18ms, total 228ms,
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2420): waitForAlarm result :8,
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,E/Watchdog( 2420): !@Sync 17,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2420): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4,
,E/Watchdog( 2420): !@Sync 18,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2420): stay LED for fully charged,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2420): [PWL] Off : 225s ago,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2420): waitForAlarm result :8,
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,E/Watchdog( 2420): !@Sync 19,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1,
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4,
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 20,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 275s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 21
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/GAV2    ( 5707): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5707): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2420): !@Sync 22
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2420): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2420): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2420): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4082): GC_CONCURRENT freed 2892K, 31% free 9729K/13908K, paused 13ms+4ms, total 57ms
,E/Watchdog( 2420): !@Sync 23
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 24
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 25
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 26
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 455s ago
,V/AlarmManager( 2420): waitForAlarm result :8
,E/SPPClientService( 5614): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 27
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 28
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 525s ago
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 29
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2420): GC_CONCURRENT freed 4120K, 74% free 25484K/96116K, paused 10ms+15ms, total 214ms
,E/Watchdog( 2420): !@Sync 31
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 32
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 33
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 680s ago
,E/Watchdog( 2420): !@Sync 34
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 35
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 36
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :4
,I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 5
,D/LightsService( 2420): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2420): LightSensor setDelay = 200000000
D/Sensors ( 2420): LightSensor setSensorDelay = 200000000
D/Sensors ( 2420): Light sensor flush: not enabled 0
D/Sensors ( 2420): LightSensor enable = 1
D/Sensors ( 2420): LightSensor enableSensor = 1
D/SensorManager( 2420): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Sensors ( 2420): LightSensor enable = 0
,D/Sensors ( 2420): LightSensor enableSensor = 0
,D/LightsService( 2420): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2420): unregisterListener ::   
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SPPClientService( 5614): [b] __PingReply__
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 765s ago
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 37
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 38
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 39
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 9815
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,I/PowerManagerService( 2420): [PWL] Off : 855s ago
I/PowerManagerService( 2420): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2420): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2420): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2420, ws=null) (elapsedTime=1185)
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 40
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 41
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 42
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2420): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2420): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
V/AlarmManager( 2420): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2420): [PWL] Off : 950s ago
,E/Watchdog( 2420): !@Sync 43
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 44
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 45
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 46
,D/dalvikvm( 2420): GC_CONCURRENT freed 3885K, 74% free 25490K/96116K, paused 17ms+20ms, total 241ms
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4082): GC_CONCURRENT freed 2050K, 31% free 9726K/13908K, paused 15ms+2ms, total 65ms
,E/Watchdog( 2420): !@Sync 47
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 48
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 49
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,I/PowerManagerService( 2420): [PWL] Off : 1155s ago
I/PowerManagerService( 2420): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2420): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2420): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2420, ws=null) (elapsedTime=1228)
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 50
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 51
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 52
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 53
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2420): [PWL] Off : 1265s ago
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 54
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 55
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 56
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5614): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,I/EventLogService( 3159): Aggregate from 1450735527353 (log), 1450735527353 (data)
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 5
,D/LightsService( 2420): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2420): LightSensor setDelay = 200000000
D/Sensors ( 2420): LightSensor setSensorDelay = 200000000
D/Sensors ( 2420): Light sensor flush: not enabled 0
D/Sensors ( 2420): LightSensor enable = 1
D/Sensors ( 2420): LightSensor enableSensor = 1
D/SensorManager( 2420): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2420): LightSensor enable = 0
,D/Sensors ( 2420): LightSensor enableSensor = 0
,D/LightsService( 2420): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2420): unregisterListener ::   
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 57
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 58
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 59
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/dalvikvm( 2420): GC_CONCURRENT freed 3879K, 74% free 25507K/96116K, paused 24ms+17ms, total 253ms
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 60
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2420): Prepared write state in 44ms
,I/ProcessStatsService( 2420): Prepared write state in 52ms
,I/ProcessStatsService( 2420): Pruning old procstats: /data/system/procstats/state-2015-12-21-00-50-54.bin
,E/Watchdog( 2420): !@Sync 61
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2420): waitForAlarm result :4
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): performPollLocked(flags=0x3)
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,V/NetworkStats( 2420): performPollLocked() took 47ms
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,I/SELinux (11488): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11488):  
,I/SELinux (11488): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11488):  
I/SELinux (11488):  
,I/SELinux (11488): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (11488): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(11488): >>>>> Normal User
,E/dalvikvm(11488): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (11488): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(11488): in addTimaSignatureService
,D/TimaKeyStoreProvider(11488): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(11488): Added TimaKesytore provider
,D/dalvikvm(11488): GC_CONCURRENT freed 3001K, 31% free 9569K/13864K, paused 3ms+2ms, total 27ms
,D/dalvikvm(11488): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/@ WidgetProvider(11488): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(11488): onUpdate called for widgetId : 0
,D/@ WidgetProvider(11488): Widget random data : 9
,D/@ WidgetProvider(11488): onUpdate called for widgetId : 5
,D/@ WidgetProvider(11488): Widget random data : 9
,E/dalvikvm(11488): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(11488): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(11488): VFY: replacing opcode 0x22 at 0x0038
,I/ActivityManager( 2420): Killing 6076:com.sec.android.app.shealth/u0a36 (adj 15): empty #43
E/dalvikvm(11488): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(11488): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(11488): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(11488): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(11488): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(11488): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(11488): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(11488): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(11488): VFY: replacing opcode 0x22 at 0x0038
,D/dalvikvm(11488): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
D/dalvikvm(11488): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(11488): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(11488): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,V/GLSActivity( 2847): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2847): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NativeCrypto( 2847): SSL shutdown failed: ssl=0x75048768: I/O error during system call, Connection timed out
,I/System.out(11488): Thread-684(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11488): Thread-684(ApacheHTTPLog):isShipBuild true
,I/System.out(11488): Thread-684(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out(11488): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(11488): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(11488): Max ALLOWED memory (MB): 128
V/ImageManager(11488): Max SHOULD USE memory (MB): 128
,V/ImageManager(11488): Max Image Cache memory (MB): 32
,D/skia    (11488): getTotalSize : Do not get file length
,D/@ WidgetProvider(11488): Building widget : 5
,D/dalvikvm( 2780): GC_CONCURRENT freed 8741K, 40% free 18342K/30216K, paused 11ms+6ms, total 77ms
,D/dalvikvm( 2780): WAIT_FOR_CONCURRENT_GC blocked 61ms
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 62
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2420): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2420): <AppSync3 Whitelist>
,V/AlarmManager( 2420): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 63
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 64
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
I/ActivityManager( 2420): Killing 6515:com.sec.knox.bridge/1000 (adj 15): empty for 1811s
,I/ActivityManager( 2420): Killing 4929:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1811s
,I/ActivityManager( 2420): Killing 6477:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1821s
,I/ActivityManager( 2420): Killing 6829:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1822s
,I/ActivityManager( 2420): Killing 6815:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1822s
,I/ActivityManager( 2420): Killing 6803:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1822s
,I/ActivityManager( 2420): Killing 6791:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1822s
,I/ActivityManager( 2420): Killing 6777:com.samsung.helphub/1000 (adj 15): empty for 1823s
,I/ActivityManager( 2420): Killing 6765:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1823s
,I/ActivityManager( 2420): Killing 6752:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1823s
,I/ActivityManager( 2420): Killing 6739:com.sec.android.service.cm/u0a82 (adj 15): empty for 1823s
,I/ActivityManager( 2420): Killing 6433:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1823s
,I/ActivityManager( 2420): Killing 5773:com.android.mms/u0a49 (adj 15): empty for 1823s
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2420): Killing 6713:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1823s
,D/CountryDetector( 2420): No listener is left
,E/Watchdog( 2420): !@Sync 65
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2420): [PWL] Off : 1625s ago
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 66
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 67
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 68
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
I/ActivityManager( 2420): Killing 7425:com.google.android.apps.magazines/u0a115 (adj 15): empty for 1803s
I/ActivityManager( 2420): Killing 7541:com.sec.android.app.voicenote/1000 (adj 15): empty for 1803s
I/ActivityManager( 2420): Killing 7393:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty for 1803s
I/ActivityManager( 2420): Killing 5879:com.osp.app.signin/u0a44 (adj 15): empty for 1803s
I/ActivityManager( 2420): Killing 6697:com.policydm/1000 (adj 15): empty for 1803s
I/ActivityManager( 2420): Killing 7368:com.sec.android.soagent/u0a38 (adj 15): empty for 1803s
I/ActivityManager( 2420): Killing 7294:com.vlingo.midas/u0a34 (adj 15): empty for 1803s
I/ActivityManager( 2420): Killing 7356:com.samsung.klmsagent/u0a18 (adj 15): empty for 1804s
I/ActivityManager( 2420): Killing 7337:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1804s
I/ActivityManager( 2420): Killing 5821:com.sec.android.diagmonagent/1000 (adj 15): empty for 1804s
I/ActivityManager( 2420): Killing 6669:com.sec.pcw.device/1000 (adj 15): empty for 1804s
I/ActivityManager( 2420): Killing 4759:com.android.settings/1000 (adj 15): empty for 1804s
I/ActivityManager( 2420): Killing 7500:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1804s
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 69
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1800000ms)
```
