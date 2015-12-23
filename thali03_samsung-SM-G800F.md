#### Test 543122980a88295_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,--------- beginning of /dev/log/main
D/AndroidRuntime( 7244): 
D/AndroidRuntime( 7244): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7244): CheckJNI is OFF
D/AndroidRuntime( 7244): setted country_code = Poland
D/AndroidRuntime( 7244): setted countryiso_code = PL
D/AndroidRuntime( 7244): setted sales_code = PLS
D/AndroidRuntime( 7244): readGMSProperty: start
D/AndroidRuntime( 7244): readGMSProperty: already setted!!
D/AndroidRuntime( 7244): readGMSProperty: end
D/AndroidRuntime( 7244): addProductProperty: start
D/dalvikvm( 7244): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7244): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7244): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7244): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7244): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7244): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7244): failed to load memtrack module: -2
D/dalvikvm( 7244): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7244): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2420): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2420): mDVFSHelper.acquire()
I/SELinux ( 7272): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7272):  
D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7244): Shutting down VM
D/dalvikvm( 7244): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+0ms, total 3ms
I/SELinux ( 7272): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7272):  
I/SELinux ( 7272):  
I/SELinux ( 7272): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7272): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7272): >>>>> Normal User
E/dalvikvm( 7272): >>>>> com.test.thalitest [ userId:0 | appId:10577 ]
E/SELinux ( 7272): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7272): in addTimaSignatureService
D/TimaKeyStoreProvider( 7272): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7272): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4193): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4193): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1922): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1922): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7272): GC_CONCURRENT freed 3016K, 31% free 9548K/13648K, paused 1ms+1ms, total 17ms
D/dalvikvm( 7272): WAIT_FOR_CONCURRENT_GC blocked 15ms
V/WebViewChromium( 7272): Binding Chromium to the background looper Looper (main, tid 1) {426e0288}
I/chromium( 7272): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7272): Initializing chromium process, renderers=0
W/chromium( 7272): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7272): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7272): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7272): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7272): Mali API Version : 401
,I/Mali    ( 7272): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7272): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7272): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,D/dalvikvm( 7272): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7272): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7272): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7272): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,W/dalvikvm( 7272): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,D/StatusBarManagerService( 2420): tr p:7272,o:f
W/dalvikvm( 7272): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7272): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7272): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 7272): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7272): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7272): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7272): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7272): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7272): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7272): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7272): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7272): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2420): semi p:7272,o:f
,I/SurfaceFlinger( 1922): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7272): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7272): Enabling debug mode 0
,W/AwContents( 7272): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7272): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2420): mDVFSHelper.release()
,D/JsMessageQueue( 7272): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7272): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x426d1508
,D/dalvikvm( 7272): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x426d1508
,D/jxcore_app_log( 7272): JniHelper::setJavaVM(0x41c78220), pthread_self() = 2027603040
,D/JX-Cordova( 7272): jxcore cordova android initializing
,D/dalvikvm( 7272): GC_CONCURRENT freed 1278K, 18% free 11345K/13700K, paused 2ms+2ms, total 23ms
,D/dalvikvm( 7272): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 7272): GC_CONCURRENT freed 1951K, 17% free 14925K/17968K, paused 3ms+3ms, total 50ms,
,D/dalvikvm( 7272): WAIT_FOR_CONCURRENT_GC blocked 30ms,
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@8
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 7272): GC_FOR_ALLOC freed 5352K, 30% free 16208K/22868K, paused 52ms, total 55ms,
,E/Watchdog( 2420): !@Sync 9,
,D/dalvikvm( 7272): GC_CONCURRENT freed 6702K, 31% free 17676K/25480K, paused 3ms+12ms, total 87ms,
D/dalvikvm( 7272): WAIT_FOR_CONCURRENT_GC blocked 51ms,
,D/dalvikvm( 7272): WAIT_FOR_CONCURRENT_GC blocked 57ms,
,D/dalvikvm( 7272): GC_FOR_ALLOC freed 1413K, 32% free 17433K/25480K, paused 59ms, total 60ms,
,I/dalvikvm-heap( 7272): Grow heap (frag case) to 21.617MB for 3713210-byte allocation,
,D/dalvikvm( 7272): GC_FOR_ALLOC freed 43K, 28% free 21016K/29108K, paused 49ms, total 49ms,
,W/jxcore-log( 7272): Initializing JXcore engine,
,W/jxcore-log( 7272): JXcore engine is ready
,W/jxcore-log( 7272): Starting JXcore engine,
,W/jxcore-log( 7272): Platform android,
W/jxcore-log( 7272): 
,W/jxcore-log( 7272): Process ARCH arm,
W/jxcore-log( 7272): 
,I/jxcore-log( 7272): JXcore Cordova bridge is ready!,
I/jxcore-log( 7272): 
W/jxcore-log( 7272): JXcore engine is started
,I/chromium( 7272): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/jxcore-log( 7272): Toggling radios to true,
I/jxcore-log( 7272): 
,D/BluetoothAdapter( 7272): enable(): BT is already enabled..!,
,I/WifiManager( 7272): packageName : com.test.thalitest,
I/WifiManager( 7272): setWifiEnabled : true
,I/WifiService( 2420): setWifiEnabled: true pid=7272, uid=10577,
,W/ActivityManager( 2420): Permission Denial: getCurrentUser() from pid=7272, uid=10577 requires android.permission.INTERACT_ACROSS_USERS,
W/WifiService( 2420): Failed getting userId using ActivityManagerNative
W/WifiService( 2420): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7272, uid=10577 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2420): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2420): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2420): ,	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2420): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2420): disconnect: pid=7272, uid=10577
I/jxcore-log( 7272): Radios toggled,
I/jxcore-log( 7272): 
I/wpa_supplicant( 3965): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7272): Got Device Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 7272): 
,I/jxcore-log( 7272): Perf Test app loaded loaded,
I/jxcore-log( 7272): 
,I/wpa_supplicant( 3965): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,I/jxcore-log( 7272): check test folder
I/jxcore-log( 7272): 
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,I/jxcore-log( 7272): found test : ./testFindPeers.js
I/jxcore-log( 7272): 
I/wpa_supplicant( 3965): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 3965): wlan0: Setting scan request: 0 sec 0 usec
,W/Settings( 2420): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/WifiStateMachine( 2420): ignore requestNetworkTransitionWakelock airplane:true
,I/wpa_supplicant( 3965): First Scan Start
,I/wpa_supplicant( 3965): Scan requested (ret=0) - scan timeout 30 seconds
D/WifiP2pService( 2420): InactiveState{ what=143375 }
D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
,D/ConnectivityService( 2420): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/wpa_supplicant( 3965): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3965): Skip scan - already scanning
D/ConnectivityService( 2420): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2420): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2420): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2420): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2420): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/WifiP2pService( 2420): InactiveState{ what=143375 }
D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
,I/SELinux ( 7319): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7319):  
D/ConnectivityService( 2420): Attempting to switch to mobile
D/ConnectivityService( 2420): Attempting to switch to BLUETOOTH_TETHER
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-45ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-37ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/jxcore-log( 7272): found test : ./testSendData.js
I/jxcore-log( 7272): 
E/WifiStateMachine( 2420): Error! unhandled message{ when=-13ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
V/RouteController( 1916): RTNETLINK answers: No such process
V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
,I/SELinux ( 7319): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7319):  
I/SELinux ( 7319):  
,I/SELinux ( 7319): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7319): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7319): >>>>> Normal User
E/dalvikvm( 7319): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,E/SELinux ( 7319): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,W/NetworkManagementService( 2420): route cmd failed: 
W/NetworkManagementService( 2420): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
,V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 7319): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7319): Cannot add TimaSignature Service, License check Failed
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/ActivityThread( 7319): Added TimaKesytore provider
,D/NetUtils( 2420): android_net_utils_resetConnections in env=0x77e3d820 clazz=0x62600001 iface=wlan0 mask=0x3
D/ConnectivityService( 2420): resetConnections(wlan0, 3)
,I/jxcore-log( 7272): found test : ./testSendData2.js
I/jxcore-log( 7272): 
,E/SPPClientService( 5544): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,D/dalvikvm( 7319): GC_CONCURRENT freed 2985K, 30% free 9583K/13652K, paused 5ms+2ms, total 32ms
,D/dalvikvm( 7319): WAIT_FOR_CONCURRENT_GC blocked 23ms
,E/SPPClientService( 5544): [e] exceptionCaught(). NET_TIMEOUT
,V/NativeCrypto( 2850): Read error: ssl=0x7c702ee8: I/O error during system call, Connection timed out
,E/SPPClientService( 5544): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5544): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5544): [b] ResponseMap empty
,V/NativeCrypto( 2850): SSL shutdown failed: ssl=0x7c702ee8: I/O error during system call, Broken pipe
,I/System.out( 7319): Inside WakeupProvider
,I/System.out( 7319): Inside onCreate() of WakeupTriggerProvide
,I/chromium( 7272): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService( 2420): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): updateIfacesLocked()
V/NetworkStats( 2420): performPollLocked(flags=0x1)
V/NetworkStats( 2420): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/VlingoApplication( 7319): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7319): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7319): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): performPollLocked() took 31ms
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2831): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/DialogFlow( 7319): initQueue()
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2831): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2831): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2420): Killing 6178:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2831): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 2831): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2831): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2831): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2420): Tethering got CONNECTIVITY_ACTION,
I/ApplicationPolicy( 2420): updateDataUsageMap
,D/Tethering( 2420): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2420): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/ConnectivityService( 2420): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6593): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6593): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6593): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6593): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 4732): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6593): noConnectivity : true
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7348): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7348):  
,I/wpa_supplicant( 3965): nl80211: Received scan results (2 BSSes)
,I/wpa_supplicant( 3965): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3965): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,I/SELinux ( 7348): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7348):  
I/SELinux ( 7348):  
,I/SELinux ( 7348): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7348): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7348): >>>>> Normal User
,E/dalvikvm( 7348): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7348): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3965): Associated with C0.AA.48
,D/TimaKeyStoreProvider( 7348): in addTimaSignatureService
I/wpa_supplicant( 3965): freq(2412) increment count 2
,I/wpa_supplicant( 3965): meet head of list.
,D/TimaKeyStoreProvider( 7348): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7348): Added TimaKesytore provider
,I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3965): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3965): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,D/WifiNative( 2420): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/dalvikvm( 7348): GC_CONCURRENT freed 3007K, 30% free 9567K/13652K, paused 5ms+2ms, total 29ms
,D/dalvikvm( 7348): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/WifiP2pService( 2420): InactiveState{ what=143375 }
,D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,I/ActivityManager( 2420): Killing 6248:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,I/SELinux ( 7362): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7362):  
,I/SELinux ( 7362): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7362):  
I/SELinux ( 7362):  
,I/SELinux ( 7362): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7362): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7362): >>>>> Normal User
,E/dalvikvm( 7362): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7362): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7362): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7362): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7362): Added TimaKesytore provider
,I/dhcpcd  ( 7366): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7366): bssid match
,D/dalvikvm( 7362): GC_CONCURRENT freed 2993K, 30% free 9575K/13648K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 7362): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/PowerManagerService( 2420): [PWL] Off : 225s ago
I/PowerManagerService( 2420): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2420): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2420): [PWL]       PARTIAL_WAKE_LOCK              'GpsLocationProvider' (uid=1000, pid=2420, ws=null) (elapsedTime=844)
,I/PowerManagerService( 2420): [PWL]       PARTIAL_WAKE_LOCK              'DHCP' (uid=1000, pid=2420, ws=null) (elapsedTime=462)
,I/ActivityManager( 2420): Killing 6300:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7381): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7381):  
,I/SELinux ( 7381): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7381):  
I/SELinux ( 7381):  
,I/SELinux ( 7381): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7381): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7381): >>>>> Normal User
,E/dalvikvm( 7381): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7381): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7381): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7381): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7381): Added TimaKesytore provider
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection...
,D/dalvikvm( 7381): GC_CONCURRENT freed 3007K, 30% free 9554K/13644K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 7381): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/KLMS-2.3.201 : ( 7381): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7381): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450834225814
,I/KLMS-2.3.201 : ( 7381): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2420): Killing 6316:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7393): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7393):  
,I/SELinux ( 7393): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7393):  
I/SELinux ( 7393):  
,I/SELinux ( 7393): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7393): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7393): >>>>> Normal User
,E/dalvikvm( 7393): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7393): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7393): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7393): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7393): Added TimaKesytore provider
,D/dalvikvm( 7393): GC_CONCURRENT freed 3010K, 30% free 9554K/13644K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 7393): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/SO_AGENT( 7393): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7393): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5810): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5810): [BDLM] already registered in spp
,I/SA      ( 5810): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5810): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5810): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5810): [OR] == isSIMCardReady false ==
I/SA      ( 5810): [SCU] == networkStateCheck == false
,I/SA      ( 5810): [OR] onReceive END
I/ActivityManager( 2420): Killing 6330:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SELinux ( 7406): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7406):  
,D/dalvikvm( 1923): GC_EXPLICIT freed 42K, 11% free 9502K/10628K, paused 4ms+4ms, total 44ms
,I/SELinux ( 7406): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7406):  
I/SELinux ( 7406):  
,I/SELinux ( 7406): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7406): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7406): >>>>> Normal User
,E/dalvikvm( 7406): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7406): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 11% free 9502K/10628K, paused 2ms+4ms, total 38ms
,D/TimaKeyStoreProvider( 7406): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7406): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7406): Added TimaKesytore provider
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 11% free 9502K/10628K, paused 4ms+6ms, total 40ms
,D/dalvikvm( 7406): GC_CONCURRENT freed 3004K, 30% free 9570K/13652K, paused 4ms+2ms, total 36ms
,D/dalvikvm( 7406): WAIT_FOR_CONCURRENT_GC blocked 31ms
,I/sCloudBackupApp( 7406): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7406): Other Intent
,I/ActivityManager( 2420): Killing 5595:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SELinux ( 7421): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7421):  
,I/SELinux ( 7421): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7421):  
I/SELinux ( 7421):  
,I/SELinux ( 7421): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7421): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7421): >>>>> Normal User
,E/dalvikvm( 7421): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7421): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7421): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7421): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7421): Added TimaKesytore provider
,D/PackageManager( 2420): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
D/dalvikvm( 7421): GC_CONCURRENT freed 2990K, 30% free 9570K/13644K, paused 5ms+2ms, total 43ms
,D/dalvikvm( 7421): WAIT_FOR_CONCURRENT_GC blocked 33ms
,D/com.samsung.app( 7421): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7421): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7421): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7421): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7421): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7421): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5344): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7421): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5344): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7421): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
D/WifiP2pService( 2420): InactiveState{ what=143375 }
,D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
D/daemonapp( 5344): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/WifiStateMachine( 2420): VerifyingLinkState enter
,D/com.samsung.app( 7421): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7421): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2420): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2420): CaptivePortalCheckState enter
I/ActivityManager( 2420): Killing 6281:com.sec.phone/1001 (adj 15): empty #43
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2420): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2420): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2420): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/Headlines( 5876): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE,
I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
,D/HeadlinesChannelUtil( 5876): getCountryCode(): countryCode = PL,
D/ConnectivityService( 2420): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2420): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2420): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false),
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/Headlines( 5876): Breath.onCreate
,D/Headlines( 5876): Breath timer started. interval : 30000
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/SELinux ( 7452): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7452):  
,D/ConnectivityService( 2420): handleConnectivityChange: setting default proxy info 
,V/AlarmManager( 2420): waitForAlarm result :8
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/Headlines( 5876): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5876): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5876): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 5876): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5876): updateCategory : HeadlinesCardManager:updateCategory() reponse : false,
D/HeadlinesCardManager( 5876): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5876): requestUpdateNewsWelcomeCard !!! no welcome card
V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory,
I/SELinux ( 7452): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7452):  
I/SELinux ( 7452):  
I/SELinux ( 7452): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
E/SELinux ( 7452): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7452): >>>>> Normal User
,E/dalvikvm( 7452): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7452): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1,
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,D/TimaKeyStoreProvider( 7452): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7452): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7452): Added TimaKesytore provider
,V/RouteController( 1916): RTNETLINK answers: No such process,
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1,
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/NetworkStats( 2420): updateIfacesLocked(),
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit,
V/NetworkStats( 2420): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit,
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit,
V/NetworkStats( 2420): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): performPollLocked() took 27ms
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit,
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit,
,D/dalvikvm( 7452): GC_CONCURRENT freed 2994K, 30% free 9571K/13648K, paused 6ms+2ms, total 32ms,
,D/dalvikvm( 7452): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 7452): WAIT_FOR_CONCURRENT_GC blocked 1ms
,V/WebViewChromium( 7452): Binding Chromium to the background looper Looper (main, tid 1) {426dd2d8}
,I/chromium( 7452): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserProcessMain( 7452): Initializing chromium process, renderers=0,
,W/chromium( 7452): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7452): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7452): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7452): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7452): Mali API Version : 401
,I/Mali    ( 7452): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,W/GAV2    ( 7452): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 7452): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/Tethering( 2420): Tethering got CONNECTIVITY_ACTION,
,D/Tethering( 2420): MasterInitialState.processMessage what=3,
,D/CaptivePortalTracker( 2420): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4732): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection...
,I/NSApplication( 7452): Starting up...
,I/iu.Environment( 5941): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5145): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5145): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5145): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@426ed2d0
,I/SELinux ( 7506): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7506):  
,I/SELinux ( 7506): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7506):  
I/SELinux ( 7506):  
,I/SELinux ( 7506): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7506): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7506): >>>>> Normal User
,E/dalvikvm( 7506): >>>>> com.android.email [ userId:0 | appId:10157 ]
,I/jxcore-log( 7272): Connected to the server!
I/jxcore-log( 7272): 
,E/SELinux ( 7506): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7506): in addTimaSignatureService
,I/chromium( 7272): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/TimaKeyStoreProvider( 7506): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7506): Added TimaKesytore provider
,D/dalvikvm( 7506): GC_CONCURRENT freed 2980K, 30% free 9584K/13648K, paused 4ms+2ms, total 36ms
,D/dalvikvm( 7506): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,I/SELinux ( 7533): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7533):  
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,W/ActivityManager( 2420): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,I/ActivityManager( 2420): Killing 6344:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/SELinux ( 7533): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7533):  
I/SELinux ( 7533):  
,I/SELinux ( 7533): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7533): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7533): >>>>> Normal User
,E/dalvikvm( 7533): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7533): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 7543): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7543):  
,D/TimaKeyStoreProvider( 7533): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7533): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7533): Added TimaKesytore provider
,I/SELinux ( 7543): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7543):  
I/SELinux ( 7543):  
,I/SELinux ( 7543): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7543): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7543): >>>>> Normal User
,E/dalvikvm( 7543): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,I/ActivityManager( 2420): Killing 5993:com.android.calendar/u0a144 (adj 15): empty #43
E/SELinux ( 7543): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/TimaKeyStoreProvider( 7543): in addTimaSignatureService
,W/WifiP2pStateTracker( 2420): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
D/TimaKeyStoreProvider( 7543): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7543): Added TimaKesytore provider
D/ConnectivityService( 2420): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2420):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
D/ConnectivityService( 2420): handleConnectivityChange: setting default proxy info 
D/ConnectivityService( 2420): updateSourceRoutes : no source routing conditions
,D/dalvikvm( 7533): GC_CONCURRENT freed 3002K, 30% free 9565K/13652K, paused 5ms+2ms, total 32ms
,D/dalvikvm( 7533): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/BadgeProvider( 7533): onCreate
,D/BadgeProvider( 7533): DatabaseHelper
,D/BadgeProvider( 7533): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7533): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7533): sendNotify, [notify] : null
D/BadgeProvider( 7533): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7533): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7533): update, [UpdateCount] : 1
,D/Launcher.Model( 2778): reloadBadges entered.
D/dalvikvm( 7543): GC_CONCURRENT freed 2999K, 30% free 9565K/13648K, paused 4ms+4ms, total 42ms
,D/dalvikvm( 7543): WAIT_FOR_CONCURRENT_GC blocked 35ms
I/dalvikvm( 7272): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7272): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7272): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 7272): Shutting down VM
,W/dalvikvm( 7272): threadid=1: thread exiting with uncaught exception (group=0x41c8bc08)
,E/AndroidRuntime( 7272): FATAL EXCEPTION: main
E/AndroidRuntime( 7272): Process: com.test.thalitest, PID: 7272
E/AndroidRuntime( 7272): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 7272): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 7272): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 7272): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 7272): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 7272): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 7272): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 7272): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 7272): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 7272): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 7272): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 7272): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7272): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7272): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7272): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7272): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7272): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7272): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7272): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 2420):   Force finishing activity com.test.thalitest/.MainActivity
,D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 2420): Killing 6164:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2420): mDVFSHelper.acquire()
,I/Process ( 7272): Sending signal. PID: 7272 SIG: 9
,D/CrashAnrDetector( 2420): processName: com.test.thalitest
,D/CrashAnrDetector( 2420): broadcastEvent : com.test.thalitest data_app_crash
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection...
W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/ActivityManager( 2420): Process com.test.thalitest (pid 7272) (adj 9) has died.
,I/SurfaceFlinger( 1922): id=19 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1922): id=19 Removed NainActivit (-2/10)
,I/WindowState( 2420): WIN DEATH: Window{433fe908 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1922): id=19 Removed NainActivit (-2/10)
,D/dalvikvm( 2420): GC_EXPLICIT freed 4685K, 74% free 25116K/95112K, paused 12ms+18ms, total 214ms
,I/DBG_DM  ( 4732): [3.19.140541][Line:408][onResume] 
,I/DBG_DM  ( 4732): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 27
,D/hcjo    ( 5963): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5963): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5963): exit::IDLE
,D/InitializeManagerStateMachine( 5963): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5963): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5963): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5963): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5963): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5963): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5963): entry::SUCCESS
,D/hcjo    ( 5963): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5963): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5963): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/DBG_DM  ( 4732): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
D/InitializeManagerStateMachine( 5963): exit::SUCCESS
,D/InitializeManagerStateMachine( 5963): entry::IDLE
,E/SPPClientService( 5544): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5544): [SystemStateMoniter] Current Time : 297544
,E/SPPClientService( 5544): [SystemStateMoniter] No Connect : true
,I/DBG_DM  ( 4732): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4732): [3.19.140541][Line:418][onResume] Postpone Count : 27
,E/SPPClientService( 5544): [[SystemStateMonitorService]] No Active Internet
,I/DBG_DM  ( 4732): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2831): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2831): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2831): MountReceiver.onReceive - Keep current state
,I/DBG_DM  ( 4732): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
E/SPPClientService( 5544): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5544): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2831): MountReceiver.onReceive - Keep current state
,I/DBG_DM  ( 4732): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2420): sendNotification(2) - 4
I/DBG_DM  ( 4732): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 27
E/SPPClientService( 5544): [[PushClientService]] <<--- deInitPushClientService  END  --->>
D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 2831): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2831): MountReceiver.onReceive - Keep current state
I/DBG_DM  ( 4732): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
E/SPPClientService( 5544): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/DBG_DM  ( 4732): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4732): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4732): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4732): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4732): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4732): setTransGradationMode to true
,D/PhoneStatusBar( 2580): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/DBG_DM  ( 4732): [3.19.140541][Line:400][onPause] 
D/StatusBarManagerService( 2420): semi p:4732,o:t
,I/SurfaceFlinger( 1922): id=20 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 2420): Got RemoteException sending setActive(false) notification to pid 7272 uid 10577
,D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2831): MountReceiver.onReceive - Keep current state
,D/Headlines( 5876): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,I/SurfaceFlinger( 1922): id=21 createSurf (1x1),1 flag=4, Uoast
,D/Headlines( 5876): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5876): Breath 2116 latestRequest time : 1450834227021 current time : 1450834229137
I/PCWCLIENTTRACE_PushUtil( 6593): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6593): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6593): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6593): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
D/PowerManagerService( 2420): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2420
,E/SPPClientService( 5544): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5544): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5544): [g] getNetMCC return empty string
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2420): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@8
,I/KLMS-2.3.201 : ( 7381): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7381): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450834229310
,I/KLMS-2.3.201 : ( 7381): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7393): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3297): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3297): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3297): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3297): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7393): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/SELinux ( 7571): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7571):  
,I/GallerySearchProvider( 3425): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7575): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7575):  
I/SELinux ( 7571): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7571):  
I/SELinux ( 7571):  
,I/SELinux ( 7571): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7571): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7571): >>>>> Normal User
,E/dalvikvm( 7571): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7571): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7571): in addTimaSignatureService
,D/dalvikvm( 2724): GC_EXPLICIT freed 271K, 32% free 10043K/14560K, paused 8ms+6ms, total 55ms
,I/SELinux ( 7575): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7575):  
I/SELinux ( 7575):  
,I/SELinux ( 7575): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7575): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7575): >>>>> Normal User
,E/dalvikvm( 7575): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7575): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7571): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7571): Added TimaKesytore provider
,I/SA      ( 5810): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5810): [BDLM] already registered in spp
,I/SA      ( 5810): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5810): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5810): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 5810): [OR] == isSIMCardReady false ==
I/SA      ( 5810): [SCU] == networkStateCheck == true
I/SA      ( 5810): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5810): isChinaCountryCode : false
,I/SA      ( 5810): [OR] == networkStateCheck true ==
,I/SA      ( 5810): [OR] GetMyCountryZoneTask
,D/TimaKeyStoreProvider( 7575): in addTimaSignatureService
,I/SA      ( 5810): [OR] onReceive END
,I/SA      ( 5810): [SRS] prepareGetMyCountryZone
,I/SA      ( 5810): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5810): [SSP] query invoked
,D/TimaKeyStoreProvider( 7575): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7575): Added TimaKesytore provider
I/SA      ( 5810): [TPMU] GetMccFromDB : null
I/SA      ( 5810): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5810): [TPM] isNoProxy(default) : true
,I/SA      ( 5810): [RC New] Execute method=[GET] start
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7406): Other Intent
,D/com.samsung.app( 7421): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/dalvikvm( 7571): GC_CONCURRENT freed 2992K, 30% free 9576K/13648K, paused 4ms+4ms, total 29ms
,D/dalvikvm( 7571): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/com.samsung.app( 7421): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5876): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5876): getCountryCode(): countryCode = PL
,D/dalvikvm( 7575): GC_CONCURRENT freed 3012K, 30% free 9559K/13652K, paused 3ms+1ms, total 22ms
,D/dalvikvm( 7575): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/Headlines( 5876): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5876): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 5876): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 5876): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5876): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5876): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5876): requestUpdateNewsWelcomeCard !!! no welcome card
,V/KVNProvider( 7575): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7575): getFindoCursor query string : 
,I/iu.Environment( 5941): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/System.out( 7362): Thread-630(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/QuickConnect[1.1][2] ( 5145): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5145): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5145): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@426ed2d0
,I/System.out( 7362): Thread-630(ApacheHTTPLog):isShipBuild true
,I/System.out( 7362): Thread-630(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,V/KVNProvider( 7575): getTagSearchCursor() tagSearchCursor count : 0
,D/hcjo    ( 5963): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 5963): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5963): exit::IDLE
,D/InitializeManagerStateMachine( 5963): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5963): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5963): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5963): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5963): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5963): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5963): entry::SUCCESS
,D/hcjo    ( 5963): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5963): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5963): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5963): exit::SUCCESS
,D/InitializeManagerStateMachine( 5963): entry::IDLE
,E/SPPClientService( 5544): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5544): [SystemStateMoniter] Current Time : 298288
,E/SPPClientService( 5544): [SystemStateMoniter] No Connect : false
,I/System.out( 7362): AsyncTask #1 calls detatch()
,W/System.err( 7362): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7362): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7362): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7362): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
,W/System.err( 7362): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7362): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7362): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 7362): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7362): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7362): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7362): Caused by: java.lang.NullPointerException
W/System.err( 7362): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7362): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7362): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7362): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7362): 	... 8 more
,I/ActivityManager( 2420): Killing 6201:com.google.android.music:main/u0a125 (adj 15): empty #43
D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/dalvikvm( 5544): GC_CONCURRENT freed 1924K, 24% free 10485K/13640K, paused 3ms+5ms, total 36ms
,I/SA      ( 5810): [RC New] [v2liruge] api execute + 623
,I/SA      ( 5810): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5810): AsyncTask #2 calls detatch()
,I/SA      ( 5810): [TPMU] getNetworkMcc : 
,I/SA      ( 5810): [SCU] saveMccToPreferece Start
,I/SA      ( 5810): [SCU] RegionMCC : 260
,I/SA      ( 5810): [SSP] query invoked
,I/SA      ( 5810): [TPMU] GetMccFromDB : null
I/SA      ( 5810): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5810): [SCU] saveMccToPreferece End
,I/SA      ( 5810): [RC New] executeRequest [v2liruge] end. 642
I/SA      ( 5810): [RC New] Execute end
I/SA      ( 5810): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5810): [OR] GetMyCountryZoneTask Success
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@8
,E/WifiStateMachine( 2420): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/SPPClientService( 5544): [b] __InitReply__,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 10,
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 293, prevStep = 4, currStep = 4,
,I/GAV2    ( 7452): Thread[GAThread,5,main]: No campaign data found.,
,I/ActivityManager( 2420): Killing 6536:com.android.defcontainer/u0a6 (adj 15): empty #43,
,I/SurfaceFlinger( 1922): id=21 Removed Uoast (10/11),
,I/SurfaceFlinger( 1922): id=21 Removed Uoast (-2/11),
,D/PowerManagerService( 2420): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2420) eventTime = 301224,
,D/PowerManagerService( 2420): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2420 (0x0)
,D/PowerManagerService( 2420): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2420, ws=WorkSource{1000}) (elapsedTime=3498),
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6593): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil( 6593): [hasSamungAccount] - No Samsung Account,
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6593): failed to loading secure library,
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6593): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6593): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6593): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6593): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6593): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6593): [ensureRegistration] - No Samsung account
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CaptivePortalTracker( 2420): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
D/ConnectivityService( 2420): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2420): Checking http://216.58.209.46/generate_204,
,D/CaptivePortalTracker( 2420): Don't send network conditions - lacking user consent.,
D/CaptivePortalTracker( 2420): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2420): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2420): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
D/ConnectivityService( 2420): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PreloadUpdateManagerStateMachine( 5963): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 5963): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5963): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 5963): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5963): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 5963): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5963): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 5963): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5963): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5963): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 5963): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5963): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5963): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5963): entry::IDLE
,I/ActivityManager( 2420): Waited long enough for: ServiceRecord{433a6dc0 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2420): prevTemp = 293, currTemp = 294, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2420): initializing...,
I/TLC_TIMA_PKM_initialize( 2420): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2420): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2420): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2420): input max_recvmsg_size = 262196,
I/TZ: mc_tlc_communication( 2420): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2420): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2420): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2420): aligned max_recvmsg_size = 262208,
I/TZ: mc_tlc_communication( 2420): device_id = 0x0
I/TZ: mc_tlc_communication( 2420): tlc_open() was called
,I/TZ: mc_tlc_communication( 2420): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2420): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2420): Opening the session
,I/TZ: mc_tlc_communication( 2420): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2420): Trustlet response is completed,
,I/ActivityManager( 2420): Waited long enough for: ServiceRecord{472538a0 u0 com.sec.spp.push/.PushClientService}
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 10,
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2420): waitForAlarm result :8,
,D/Headlines( 5876): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5876): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5876): Breath 27418 latestRequest time : 1450834229590 current time : 1450834257008,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2420): waitForAlarm result :8,
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2420): [PWL] Off : 275s ago,
,E/Watchdog( 2420): !@Sync 11,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :4,
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7998): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7998):  
,I/SELinux ( 7998): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7998):  
I/SELinux ( 7998):  
I/SELinux ( 7998): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7998): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7998): >>>>> Normal User
,E/dalvikvm( 7998): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 7998): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 7998): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7998): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7998): Added TimaKesytore provider
,D/dalvikvm( 7998): GC_CONCURRENT freed 3000K, 30% free 9568K/13652K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 7998): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/ActivityManager( 2420): Killing 6448:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,V/AlarmManager( 2420): waitForAlarm result :8,
,D/Headlines( 5876): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5876): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5876): Breath 57421 latestRequest time : 1450834229590 current time : 1450834287012,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4001): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = -10,
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 12
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2420): waitForAlarm result :8
,D/Headlines( 5876): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5876): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5876): Breath 87421 latestRequest time : 1450834229590 current time : 1450834317011
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2420): !@Sync 13
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,D/Headlines( 5876): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5876): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5876): Breath 117418 latestRequest time : 1450834229590 current time : 1450834347009
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 14
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2420): waitForAlarm result :8
,D/Headlines( 5876): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5876): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5876): Breath 147421 latestRequest time : 1450834229590 current time : 1450834377011
,D/Headlines( 5876): stop 
,D/Headlines( 5876): Breath.onDestroy : 
I/ActivityManager( 2420): Killing 6566:com.samsung.groupcast/u0a15 (adj 15): empty #43
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2420): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2420): !@Sync 15
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 16
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2420): [PWL] Off : 455s ago
,E/Watchdog( 2420): !@Sync 17
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 18
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm( 2420): GC_CONCURRENT freed 4037K, 74% free 25007K/95112K, paused 26ms+23ms, total 282ms
,D/dalvikvm( 2420): WAIT_FOR_CONCURRENT_GC blocked 76ms
,D/dalvikvm( 2420): WAIT_FOR_CONCURRENT_GC blocked 94ms
,D/dalvikvm( 2737): GC_CONCURRENT freed 1486K, 18% free 12147K/14784K, paused 5ms+11ms, total 68ms
,E/Watchdog( 2420): !@Sync 19
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 525s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/Watchdog( 2420): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2420): !@Sync 21
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/GAV2    ( 5639): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5639): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2420): !@Sync 22
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2420): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2420): <AppSync3 Whitelist>
,V/AlarmManager( 2420): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 23
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 24
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2420): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 25
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 26
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4068): GC_CONCURRENT freed 2888K, 29% free 9725K/13692K, paused 22ms+2ms, total 86ms
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
,E/SPPClientService( 5544): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,I/EventLogService( 3157): Aggregate from 1450832913874 (log), 1450832913874 (data)
,D/Sensors ( 2420): LightSensor enable = 0
,D/Sensors ( 2420): LightSensor enableSensor = 0
,D/SensorManager( 2420): unregisterListener ::   
D/LightsService( 2420): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/dalvikvm( 3157): GC_CONCURRENT freed 2186K, 21% free 12682K/15948K, paused 6ms+10ms, total 106ms
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 27
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 765s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 28
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 29
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 855s ago
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 31
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 32
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2420): GC_CONCURRENT freed 3952K, 74% free 24942K/94880K, paused 14ms+18ms, total 220ms
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 33
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 950s ago
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 34
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 35
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 36
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5544): [b] __PingReply__
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1050s ago
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 37
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 38
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 39
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/PowerManagerService( 2420): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 41
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 42
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2420): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2420): <AppSync3 Whitelist>
,V/AlarmManager( 2420): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 43
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1265s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 44
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2778): GC_FOR_ALLOC freed 7072K, 39% free 19056K/30976K, paused 111ms, total 111ms
,D/dalvikvm( 2778): GC_CONCURRENT freed 1178K, 43% free 17938K/30976K, paused 6ms+6ms, total 55ms
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 45
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = -10
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 46
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 10
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2420): waitForAlarm result :8
,D/LightsService( 2420): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 5
D/Sensors ( 2420): LightSensor setDelay = 200000000
D/Sensors ( 2420): LightSensor setSensorDelay = 200000000
D/Sensors ( 2420): Light sensor flush: not enabled 0
D/Sensors ( 2420): LightSensor enable = 1
D/Sensors ( 2420): LightSensor enableSensor = 1
D/SensorManager( 2420): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2420): LightSensor enable = 0
D/Sensors ( 2420): LightSensor enableSensor = 0
,D/SensorManager( 2420): unregisterListener ::   
D/LightsService( 2420): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/dalvikvm( 2420): GC_CONCURRENT freed 3904K, 74% free 24829K/94880K, paused 20ms+19ms, total 243ms
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 47
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = -10
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1380s ago
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 48
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 49
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 10
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4068): GC_CONCURRENT freed 2050K, 29% free 9722K/13692K, paused 12ms+5ms, total 46ms
,D/dalvikvm( 4068): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = -10
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 51
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 52
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 53
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 54
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 55
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
I/PowerManagerService( 2420): [PWL] Off : 1625s ago
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 56
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2420): waitForAlarm result :8
,E/SPPClientService( 5544): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 57
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 58
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 59
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/PowerManagerService( 2420): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/dalvikvm( 2420): GC_CONCURRENT freed 3733K, 74% free 24853K/94880K, paused 22ms+19ms, total 251ms
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2420): Prepared write state in 43ms
,I/ProcessStatsService( 2420): Prepared write state in 42ms
,I/ProcessStatsService( 2420): Pruning old procstats: /data/system/procstats/state-2015-12-22-01-49-58.bin
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 61
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 62
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2420): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2420): <AppSync3 Whitelist>
,V/AlarmManager( 2420): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 63
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 64
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,I/ActivityManager( 2420): Killing 6404:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1804s
,I/ActivityManager( 2420): Killing 6753:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1804s
,I/ActivityManager( 2420): Killing 6739:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1805s
,I/ActivityManager( 2420): Killing 6727:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1805s
,I/ActivityManager( 2420): Killing 6715:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1805s
,I/ActivityManager( 2420): Killing 6702:com.samsung.helphub/1000 (adj 15): empty for 1806s
,I/ActivityManager( 2420): Killing 6689:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1806s
,I/ActivityManager( 2420): Killing 6676:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1806s
,I/ActivityManager( 2420): Killing 6663:com.sec.android.service.cm/u0a82 (adj 15): empty for 1806s
I/ActivityManager( 2420): Killing 6361:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1806s
,I/ActivityManager( 2420): Killing 5704:com.android.mms/u0a49 (adj 15): empty for 1806s
,I/ActivityManager( 2420): Killing 6637:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1806s
,I/ActivityManager( 2420): Killing 6009:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1807s
,I/ActivityManager( 2420): Killing 6605:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty for 1807s
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2420): Killing 6579:com.android.musicfx/u0a24 (adj 15): empty for 1808s
,D/CountryDetector( 2420): No listener is left
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 65
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 66
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,I/ActivityManager( 2420): Killing 6444:com.sec.knox.bridge/1000 (adj 15): empty for 1854s
,I/ActivityManager( 2420): Killing 4859:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1854s
,I/ActivityManager( 2420): Killing 6428:com.google.android.googlequicksearchbox:search/u0a59 (adj 15): empty for 1854s
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2420): waitForAlarm result :4
,V/NetworkStats( 2420): performPollLocked(flags=0x3)
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,V/NetworkStats( 2420): performPollLocked() took 53ms
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,I/SELinux (11939): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11939):  
,I/SELinux (11939): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11939):  
I/SELinux (11939):  
,I/SELinux (11939): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (11939): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(11939): >>>>> Normal User
,E/dalvikvm(11939): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
E/SELinux (11939): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(11939): in addTimaSignatureService
,D/TimaKeyStoreProvider(11939): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(11939): Added TimaKesytore provider
,D/dalvikvm(11939): GC_CONCURRENT freed 3003K, 30% free 9569K/13652K, paused 3ms+2ms, total 27ms
,D/dalvikvm(11939): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/@ WidgetProvider(11939): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(11939): onUpdate called for widgetId : 0
,D/@ WidgetProvider(11939): Widget random data : 5
,D/@ WidgetProvider(11939): onUpdate called for widgetId : 5
,D/@ WidgetProvider(11939): Widget random data : 3
,E/dalvikvm(11939): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(11939): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(11939): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(11939): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(11939): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(11939): VFY: replacing opcode 0x22 at 0x0038
,E/dalvikvm(11939): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(11939): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(11939): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(11939): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(11939): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(11939): VFY: replacing opcode 0x22 at 0x0038
,I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 5
,D/LightsService( 2420): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2420): LightSensor setDelay = 200000000
D/Sensors ( 2420): LightSensor setSensorDelay = 200000000
D/Sensors ( 2420): Light sensor flush: not enabled 0
D/Sensors ( 2420): LightSensor enable = 1
D/Sensors ( 2420): LightSensor enableSensor = 1
D/SensorManager( 2420): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/dalvikvm(11939): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
D/dalvikvm(11939): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(11939): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(11939): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NativeCrypto( 2850): SSL shutdown failed: ssl=0x7462ad68: I/O error during system call, Connection timed out
,V/NativeCrypto( 2850): SSL shutdown failed: ssl=0x7bafeba8: I/O error during system call, Connection timed out
,I/System.out(11939): Thread-666(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11939): Thread-666(ApacheHTTPLog):isShipBuild true
,I/System.out(11939): Thread-666(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/Sensors ( 2420): LightSensor enable = 0
,D/Sensors ( 2420): LightSensor enableSensor = 0
,D/SensorManager( 2420): unregisterListener ::   
D/LightsService( 2420): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/System.out(11939): AsyncNetworking-1-thread-1 calls detatch()
,V/NativeCrypto( 2850): SSL shutdown failed: ssl=0x7bb1db78: I/O error during system call, Connection timed out
,V/NativeCrypto( 2850): SSL shutdown failed: ssl=0x7baad960: I/O error during system call, Connection timed out
,I/System.out(11939): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(11939): Max ALLOWED memory (MB): 128
V/ImageManager(11939): Max SHOULD USE memory (MB): 128
,V/ImageManager(11939): Max Image Cache memory (MB): 32
,D/skia    (11939): getTotalSize : Do not get file length
,D/@ WidgetProvider(11939): Building widget : 5
,I/SELinux (11977): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11977):  
,I/SELinux (11977): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11977):  
I/SELinux (11977):  
,I/SELinux (11977): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (11977): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm(11977): >>>>> Normal User
,E/dalvikvm(11977): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
,E/SELinux (11977): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider(11977): in addTimaSignatureService
,D/TimaKeyStoreProvider(11977): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(11977): Added TimaKesytore provider
,D/dalvikvm(11977): GC_CONCURRENT freed 3011K, 30% free 9559K/13648K, paused 3ms+2ms, total 27ms
,D/dalvikvm(11977): WAIT_FOR_CONCURRENT_GC blocked 24ms
,E/dalvikvm(11977): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a
W/dalvikvm(11977): VFY: unable to resolve new-instance 406 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm(11977): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm(11977): Unable to resolve superclass of Lal; (749)
W/dalvikvm(11977): Link of class 'Lal;' failed
E/dalvikvm(11977): Could not find class 'al', referenced from method b.a
W/dalvikvm(11977): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
,D/dalvikvm(11977): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm(11977): Unable to resolve superclass of Lan; (749)
W/dalvikvm(11977): Link of class 'Lan;' failed
E/dalvikvm(11977): Could not find class 'an', referenced from method b.a
W/dalvikvm(11977): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
,D/dalvikvm(11977): VFY: replacing opcode 0x22 at 0x002a
I/dalvikvm(11977): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm(11977): VFY: unable to resolve virtual method 5407: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm(11977): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm(11977): Could not find method android.view.View.getTransitionName, referenced from method b.a
W/dalvikvm(11977): VFY: unable to resolve virtual method 5231: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm(11977): VFY: replacing opcode 0x6e at 0x0006
,W/dalvikvm(11977): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
,E/dalvikvm(11977): Could not find class 'android.app.RemoteInput[]', referenced from method b.a
W/dalvikvm(11977): VFY: unable to resolve new-array 12200 ([Landroid/app/RemoteInput;) in Lb;
,D/dalvikvm(11977): VFY: replacing opcode 0x23 at 0x0005
,D/dalvikvm(11977): DexOpt: unable to opt direct call 0x090f at 0x0e in Lb;.a
W/dalvikvm(11977): Unable to resolve superclass of Lal; (749)
W/dalvikvm(11977): Link of class 'Lal;' failed
,D/dalvikvm(11977): DexOpt: unable to opt direct call 0x068d at 0x08 in Lb;.a
W/dalvikvm(11977): Unable to resolve superclass of Lan; (749)
W/dalvikvm(11977): Link of class 'Lan;' failed
D/dalvikvm(11977): DexOpt: unable to opt direct call 0x0802 at 0x2c in Lb;.a
,D/dalvikvm(11977): DexOpt: unable to opt direct call 0x0957 at 0x13 in Lb;.a
,I/dalvikvm(11977): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method dyp.a
W/dalvikvm(11977): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm(11977): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm(11977): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm(11977): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm(11977): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm(11977): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm(11977): VFY: unable to resolve instance field 36
,D/dalvikvm(11977): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm(11977): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm(11977): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm(11977): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm(11977): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm(11977): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm(11977): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x427a1a38
,D/dalvikvm(11977): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x427a1a38
,D/dalvikvm(11977): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x427a1a38, skipping init
,D/dalvikvm(11977): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x427a1a38
,D/dalvikvm(11977): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x427a1a38
,V/JNIHelp (11977): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/dalvikvm(11977): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm(11977): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm(11977): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm(11977): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x427a1a38
,D/dalvikvm(11977): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x427a1a38
D/dalvikvm(11977): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x427a1a38
,D/dalvikvm(11977): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x427a1a38
,I/dalvikvm(11977): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm(11977): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm(11977): VFY: replacing opcode 0x71 at 0x004e
,D/dalvikvm(11977): DexOpt: --- BEGIN 'ads-609983541.jar' (bootstrap=0) ---
,I/ProviderInstaller(11977): Installed default security provider GmsCore_OpenSSL
,D/dalvikvm(12004): DexOpt: load 5ms, verify+opt 15ms, 194052 bytes
,D/dalvikvm(11977): DexOpt: --- END 'ads-609983541.jar' (success) ---
,D/dalvikvm(11977): DEX prep '/data/data/com.google.android.youtube/cache/ads-609983541.jar': unzip in 0ms, rewrite 131ms
,E/YouTube MDX(11977): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/dalvikvm(11977): GC_CONCURRENT freed 1946K, 23% free 10688K/13712K, paused 4ms+5ms, total 46ms
,D/dalvikvm(11977): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm(11977): WAIT_FOR_CONCURRENT_GC blocked 21ms
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl(11977): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,I/dalvikvm(11977): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm(11977): VFY: unable to resolve virtual method 2614: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm(11977): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(11977): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm(11977): VFY: unable to resolve virtual method 2615: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
D/dalvikvm(11977): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(11977): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm(11977): VFY: unable to resolve virtual method 2622: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm(11977): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(11977): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm(11977): VFY: unable to resolve virtual method 2623: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm(11977): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(11977): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method agv.getLeanbackLaunchIntentForPackage
W/dalvikvm(11977): VFY: unable to resolve virtual method 2639: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm(11977): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(11977): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method agv.getPackageInstaller
,W/dalvikvm(11977): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm(11977): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm(11977): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method agv.getUserBadgedDrawableForDensity
E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/dalvikvm(11977): VFY: unable to resolve virtual method 2659: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
D/dalvikvm(11977): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm(11977): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method agv.getUserBadgedIcon
W/dalvikvm(11977): VFY: unable to resolve virtual method 2660: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
W/ContextImpl(11977): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
D/dalvikvm(11977): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(11977): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method agv.getUserBadgedLabel
W/dalvikvm(11977): VFY: unable to resolve virtual method 2661: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm(11977): VFY: replacing opcode 0x6e at 0x0002
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl(11977): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl(11977): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,W/InstanceID/Rpc(11977): Found 10012
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl(11977): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,D/dalvikvm( 2850): GC_CONCURRENT freed 1925K, 22% free 10940K/14012K, paused 5ms+8ms, total 71ms
,I/System.out(11977): Thread-732(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11977): Thread-732(ApacheHTTPLog):isShipBuild true
,I/System.out(11977): Thread-732(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out(11977): Thread-732 calls detatch()
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 10
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 67
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = -10
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 68
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 69
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 2030s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 70
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,I/ActivityManager( 2420): Killing 5810:com.osp.app.signin/u0a44 (adj 15): empty for 1830s
,I/ActivityManager( 2420): Killing 6621:com.policydm/1000 (adj 15): empty for 1830s
,I/ActivityManager( 2420): Killing 7393:com.sec.android.soagent/u0a38 (adj 15): empty for 1830s
,I/ActivityManager( 2420): Killing 7319:com.vlingo.midas/u0a34 (adj 15): empty for 1830s
,I/ActivityManager( 2420): Killing 7381:com.samsung.klmsagent/u0a18 (adj 15): empty for 1830s
,I/ActivityManager( 2420): Killing 7362:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1830s
I/ActivityManager( 2420): Killing 5752:com.sec.android.diagmonagent/1000 (adj 15): empty for 1830s
,I/ActivityManager( 2420): Killing 7348:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1830s
,I/ActivityManager( 2420): Killing 6593:com.sec.pcw.device/1000 (adj 15): empty for 1830s
,I/ActivityManager( 2420): Killing 2831:com.android.settings/1000 (adj 15): empty for 1830s
,I/ActivityManager( 2420): Killing 7533:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1831s
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2420): GC_CONCURRENT freed 3843K, 74% free 24864K/94880K, paused 11ms+19ms, total 233ms
,TIME-OUT KILL (timeout was 1800000ms)
```
