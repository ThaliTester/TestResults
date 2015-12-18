#### Test 50650278d76d9c3_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
D/AmoledAdjustTimer( 2420): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
V/AlarmManager( 2420): waitForAlarm result :8
V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AndroidRuntime( 7515): 
D/AndroidRuntime( 7515): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7515): CheckJNI is OFF
D/AndroidRuntime( 7515): setted country_code = Poland
D/AndroidRuntime( 7515): setted countryiso_code = PL
D/AndroidRuntime( 7515): setted sales_code = PLS
D/AndroidRuntime( 7515): readGMSProperty: start
D/AndroidRuntime( 7515): readGMSProperty: already setted!!
D/AndroidRuntime( 7515): readGMSProperty: end
D/AndroidRuntime( 7515): addProductProperty: start
D/dalvikvm( 7515): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7515): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7515): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7515): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7515): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7515): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7515): failed to load memtrack module: -2
D/dalvikvm( 7515): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7515): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2420): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2420): mDVFSHelper.acquire()
I/SELinux ( 7534): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7534):  
D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7515): Shutting down VM
D/dalvikvm( 7515): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 7534): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7534):  
I/SELinux ( 7534):  
I/SELinux ( 7534): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7534): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7534): >>>>> Normal User
E/dalvikvm( 7534): >>>>> com.test.thalitest [ userId:0 | appId:10566 ]
E/SELinux ( 7534): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7534): in addTimaSignatureService
D/TimaKeyStoreProvider( 7534): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7534): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4171): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4171): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7534): GC_CONCURRENT freed 2998K, 31% free 9565K/13836K, paused 1ms+1ms, total 18ms
D/dalvikvm( 7534): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7534): Binding Chromium to the background looper Looper (main, tid 1) {4228c328}
I/chromium( 7534): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7534): Initializing chromium process, renderers=0
W/chromium( 7534): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7534): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 7534): loaded /system/lib/egl/libGLESv1_CM_mali.so
D/libEGL  ( 7534): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7534): Mali API Version : 401
I/Mali    ( 7534): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
I/dalvikvm( 7534): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7534): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7534): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7534): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7534): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 7534): VFY: replacing opcode 0x6e at 0x0008
D/PhoneStatusBar( 2582): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2420): tr p:7534,o:f
W/dalvikvm( 7534): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7534): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7534): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7534): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 7534): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7534): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7534): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7534): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7534): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7534): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7534): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7534): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7534): CordovaWebView is running on device made by: samsung
D/PhoneStatusBar( 2582): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2420): semi p:7534,o:f
I/SurfaceFlinger( 1921): id=20 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
I/HWUI    ( 7534): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 7534): Enabling debug mode 0
W/AwContents( 7534): nativeOnDraw failed; clearing to background color.
W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2420): mDVFSHelper.release()
W/AwContents( 7534): nativeOnDraw failed; clearing to background color.
D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@8
W/IInputConnectionWrapper( 7534): showStatusIcon on inactive InputConnection
D/JsMessageQueue( 7534): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 7534): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42282d68
D/dalvikvm( 7534): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42282d68
D/jxcore_app_log( 7534): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027540688
D/JX-Cordova( 7534): jxcore cordova android initializing
D/dalvikvm( 7534): GC_CONCURRENT freed 1285K, 19% free 11353K/13904K, paused 1ms+2ms, total 22ms
D/dalvikvm( 7534): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 7534): GC_CONCURRENT freed 1995K, 18% free 14927K/18204K, paused 2ms+2ms, total 37ms
,D/dalvikvm( 7534): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@8
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 7534): GC_FOR_ALLOC freed 5247K, 30% free 16175K/22944K, paused 49ms, total 49ms
,D/dalvikvm( 7534): GC_CONCURRENT freed 6695K, 32% free 17648K/25632K, paused 3ms+9ms, total 66ms
,D/dalvikvm( 7534): WAIT_FOR_CONCURRENT_GC blocked 41ms
,D/dalvikvm( 7534): GC_FOR_ALLOC freed 1423K, 33% free 17330K/25632K, paused 49ms, total 50ms
,I/dalvikvm-heap( 7534): Grow heap (frag case) to 21.700MB for 3713210-byte allocation
,D/dalvikvm( 7534): GC_FOR_ALLOC freed 26K, 29% free 20930K/29260K, paused 49ms, total 49ms
,W/jxcore-log( 7534): Initializing JXcore engine
,W/jxcore-log( 7534): JXcore engine is ready
,W/jxcore-log( 7534): Starting JXcore engine
,W/jxcore-log( 7534): Platform android
W/jxcore-log( 7534): 
,W/jxcore-log( 7534): Process ARCH arm
W/jxcore-log( 7534): 
,I/jxcore-log( 7534): JXcore Cordova bridge is ready!
I/jxcore-log( 7534): 
,W/jxcore-log( 7534): JXcore engine is started
,I/chromium( 7534): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/PowerManagerService( 2420): [PWL] Off : 140s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 10
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 11
,I/jxcore-log( 7534): Toggling radios to true
I/jxcore-log( 7534): 
,D/BluetoothAdapter( 7534): enable(): BT is already enabled..!
,I/WifiManager( 7534): packageName : com.test.thalitest
,I/WifiManager( 7534): setWifiEnabled : true
,I/WifiService( 2420): setWifiEnabled: true pid=7534, uid=10566
,W/ActivityManager( 2420): Permission Denial: getCurrentUser() from pid=7534, uid=10566 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2420): Failed getting userId using ActivityManagerNative
W/WifiService( 2420): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7534, uid=10566 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2420): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2420): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2420): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2420): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2420): disconnect: pid=7534, uid=10566
I/wpa_supplicant( 3982): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7534): Radios toggled
I/jxcore-log( 7534): 
,I/jxcore-log( 7534): Got Device Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 7534): 
,I/wpa_supplicant( 3982): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/jxcore-log( 7534): Perf Test app loaded loaded
I/jxcore-log( 7534): 
,I/wpa_supplicant( 3982): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,I/Choreographer( 7534): Skipped 128 frames!  The application may be doing too much work on its main thread.
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3982): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3982): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3982): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3982): First Scan Start
,W/Settings( 2420): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine( 2420): ignore requestNetworkTransitionWakelock airplane:true
,I/wpa_supplicant( 3982): Scan requested (ret=0) - scan timeout 30 seconds
,I/jxcore-log( 7534): check test folder
I/jxcore-log( 7534): 
D/WifiP2pService( 2420): InactiveState{ what=143375 }
D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,I/jxcore-log( 7534): found test : ./testFindPeers.js
I/jxcore-log( 7534): 
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
I/wpa_supplicant( 3982): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3982): Skip scan - already scanning
,D/ConnectivityService( 2420): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/WifiP2pService( 2420): InactiveState{ what=143375 }
D/ConnectivityService( 2420): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,E/ConnectivityService( 2420): net.tcp.usercfg.default not found in system default properties
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2420): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2420): net.tcp.delack.default not found in system default properties
D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
E/ConnectivityService( 2420): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2420): Attempting to switch to mobile
,D/ConnectivityService( 2420): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3
,I/SELinux ( 7582): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7582):  
,I/jxcore-log( 7534): found test : ./testSendData.js
I/jxcore-log( 7534): 
,V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
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
,V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
I/SELinux ( 7582): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7582):  
I/SELinux ( 7582):  
,I/SELinux ( 7582): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7582): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7582): >>>>> Normal User
,E/dalvikvm( 7582): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7582): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
V/RouteController( 1916): RTNETLINK answers: No such process
V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
E/WifiStateMachine( 2420): Error! unhandled message{ when=-108ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-106ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-3ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 7582): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7582): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7582): Added TimaKesytore provider
,D/NetUtils( 2420): android_net_utils_resetConnections in env=0x78841f30 clazz=0x62600001 iface=wlan0 mask=0x3
D/ConnectivityService( 2420): resetConnections(wlan0, 3)
,D/dalvikvm( 7582): GC_CONCURRENT freed 2995K, 31% free 9572K/13836K, paused 3ms+1ms, total 23ms
,D/dalvikvm( 7582): WAIT_FOR_CONCURRENT_GC blocked 17ms
,V/NativeCrypto( 2852): Read error: ssl=0x7bda6a10: I/O error during system call, Connection timed out
,V/NativeCrypto( 2852): SSL shutdown failed: ssl=0x7bda6a10: I/O error during system call, Broken pipe
,E/SPPClientService( 5592): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5592): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5592): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5592): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5592): [b] ResponseMap empty
,I/chromium( 7534): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/System.out( 7582): Inside WakeupProvider
,I/System.out( 7582): Inside onCreate() of WakeupTriggerProvide
D/ConnectivityService( 2420): handleInetConditionChange: no active default network - ignore
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): updateIfacesLocked()
V/NetworkStats( 2420): performPollLocked(flags=0x1)
V/NetworkStats( 2420): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): performPollLocked() took 21ms
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,I/VlingoApplication( 7582): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7582): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7582): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 4760): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4760): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4760): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4760): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4760): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4760): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4760): MountReceiver.mPrefHandler - 7002
,I/ActivityManager( 2420): Killing 6352:com.sec.phone/1001 (adj 15): empty #43
D/DialogFlow( 7582): initQueue()
,D/NearbySettings( 4760): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4760): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4760): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4760): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4760): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4760): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4760): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2420): Tethering got CONNECTIVITY_ACTION
I/ApplicationPolicy( 2420): updateDataUsageMap
,D/Tethering( 2420): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2420): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2420): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6632): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6632): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6632): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6632): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6632): noConnectivity : true
,I/DBG_DM  ( 4796): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection...
,I/wpa_supplicant( 3982): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 3982): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3982): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3982): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,I/SELinux ( 7611): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7611):  
,I/wpa_supplicant( 3982): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
D/Tethering( 2420): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3982): Associated with C0.AA.48
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3982): freq(2412) increment count 2
,I/wpa_supplicant( 3982): meet head of list.
,I/wpa_supplicant( 3982): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3982): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3982): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3982): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3982): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/WifiNative( 2420): callSECApiVoid - ID [50]
,D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,I/SELinux ( 7611): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7611):  
I/SELinux ( 7611):  
,I/SELinux ( 7611): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/SELinux ( 7611): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7611): >>>>> Normal User
E/dalvikvm( 7611): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
E/SELinux ( 7611): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7611): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7611): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7611): Added TimaKesytore provider
,D/WifiP2pService( 2420): InactiveState{ what=143375 }
,D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,D/dalvikvm( 7611): GC_CONCURRENT freed 3016K, 31% free 9554K/13840K, paused 4ms+2ms, total 37ms
,D/dalvikvm( 7611): WAIT_FOR_CONCURRENT_GC blocked 33ms
,I/ActivityManager( 2420): Killing 6423:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/SELinux ( 7623): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7623):  
,I/SELinux ( 7623): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7623):  
I/SELinux ( 7623):  
,I/SELinux ( 7623): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7623): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7623): >>>>> Normal User
,E/dalvikvm( 7623): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7623): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7623): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7623): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7623): Added TimaKesytore provider
,I/dhcpcd  ( 7627): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7627): bssid match
,D/dalvikvm( 7623): GC_CONCURRENT freed 3009K, 31% free 9564K/13840K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 7623): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/KLMS-2.3.201 : ( 7623): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7623): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450463889328
,I/KLMS-2.3.201 : ( 7623): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2420): Killing 6245:com.google.android.music:main/u0a125 (adj 15): empty #43
,I/SELinux ( 7642): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7642):  
,I/SELinux ( 7642): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7642):  
I/SELinux ( 7642):  
,I/SELinux ( 7642): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7642): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7642): >>>>> Normal User
,E/dalvikvm( 7642): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7642): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7642): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7642): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7642): Added TimaKesytore provider
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection...
,D/dalvikvm( 7642): GC_CONCURRENT freed 3006K, 31% free 9564K/13840K, paused 5ms+3ms, total 35ms
,D/dalvikvm( 7642): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/SO_AGENT( 7642): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7642): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5839): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5839): [BDLM] already registered in spp
,I/SA      ( 5839): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5839): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5839): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5839): [OR] == isSIMCardReady false ==
,I/SA      ( 5839): [SCU] == networkStateCheck == false
,I/SA      ( 5839): [OR] onReceive END
,I/ActivityManager( 2420): Killing 6020:com.android.calendar/u0a144 (adj 15): empty #43
,D/AmoledAdjustTimer( 2420): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7039): Other Intent
,I/SELinux ( 7654): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7654):  
,I/SELinux ( 7654): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7654):  
I/SELinux ( 7654):  
,I/SELinux ( 7654): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7654): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7654): >>>>> Normal User
,E/dalvikvm( 7654): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7654): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7654): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7654): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7654): Added TimaKesytore provider
,D/dalvikvm( 7654): GC_CONCURRENT freed 2992K, 31% free 9569K/13832K, paused 4ms+2ms, total 34ms
,D/dalvikvm( 7654): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/com.samsung.app( 7654): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7654): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
D/com.samsung.app( 7654): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7654): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7654): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7654): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5392): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7654): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5392): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7654): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5392): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7654): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!,
,D/com.samsung.app( 7654): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!,
I/ActivityManager( 2420): Killing 6406:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/Headlines( 5887): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE,
,D/HeadlinesChannelUtil( 5887): getCountryCode(): countryCode = PL,
,D/Headlines( 5887): Breath.onCreate
,D/Headlines( 5887): Breath timer started. interval : 30000
,I/SELinux ( 7678): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7678):  
,D/Headlines( 5887): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5887): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5887): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5887): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5887): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5887): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5887): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7678): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7678):  
I/SELinux ( 7678):  
,I/SELinux ( 7678): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7678): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 7678): >>>>> Normal User
,E/dalvikvm( 7678): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7678): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/TimaKeyStoreProvider( 7678): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7678): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7678): Added TimaKesytore provider
,D/dalvikvm( 7678): GC_CONCURRENT freed 2996K, 31% free 9571K/13836K, paused 2ms+4ms, total 29ms
,D/dalvikvm( 7678): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/WifiP2pService( 2420): InactiveState{ what=143375 }
,D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2420): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2420): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2420): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2420): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2420): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2420): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
,D/ConnectivityService( 2420): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService( 2420): net.tcp.usercfg.wifi not found in system properties. Using defaults
,E/ConnectivityService( 2420): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/ConnectivityService( 2420): handleConnectivityChange: setting default proxy info 
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,V/WebViewChromium( 7678): Binding Chromium to the background looper Looper (main, tid 1) {42291e78}
,I/chromium( 7678): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7678): Initializing chromium process, renderers=0
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,W/chromium( 7678): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,D/libEGL  ( 7678): loaded /system/lib/egl/libEGL_mali.so
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/libEGL  ( 7678): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7678): loaded /system/lib/egl/libGLESv2_mali.so
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): updateIfacesLocked()
,V/NetworkStats( 2420): performPollLocked(flags=0x1)
I/jxcore-log( 7534): Connected to the server!
I/jxcore-log( 7534): 
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/Mali    ( 7678): Mali API Version : 401
,I/Mali    ( 7678): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): performPollLocked() took 24ms
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,I/chromium( 7534): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,W/GAV2    ( 7678): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7678): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 7678): Starting up...
,I/iu.Environment( 5954): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5192): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5192): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5192): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4229bed8
,I/SELinux ( 7750): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7750):  
,I/SELinux ( 7750): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7750):  
I/SELinux ( 7750):  
,I/SELinux ( 7750): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7750): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7750): >>>>> Normal User
,E/dalvikvm( 7750): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7750): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7750): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7750): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7750): Added TimaKesytore provider
,D/Tethering( 2420): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2420): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2420): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4796): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection...
,D/PackageManager( 2420): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/dalvikvm( 7750): GC_CONCURRENT freed 2993K, 31% free 9580K/13840K, paused 4ms+3ms, total 32ms
,D/dalvikvm( 7750): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,I/SELinux ( 7770): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7770):  
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,I/ActivityManager( 2420): Killing 6210:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 13% free 9501K/10816K, paused 4ms+4ms, total 51ms
,I/SELinux ( 7770): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7770):  
I/SELinux ( 7770):  
,I/SELinux ( 7770): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7770): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7770): >>>>> Normal User
,E/dalvikvm( 7770): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7770): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10816K, paused 3ms+4ms, total 41ms
,D/TimaKeyStoreProvider( 7770): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7770): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7770): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9501K/10816K, paused 4ms+4ms, total 37ms
,I/SELinux ( 7782): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7782):  
W/ActivityManager( 2420): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager( 2420): Killing 6337:com.android.defcontainer/u0a6 (adj 15): empty #43
,I/SELinux ( 7782): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7782):  
I/SELinux ( 7782):  
,I/SELinux ( 7782): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7782): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7782): >>>>> Normal User
,E/dalvikvm( 7782): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7782): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7782): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7782): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7782): Added TimaKesytore provider
D/dalvikvm( 7770): GC_CONCURRENT freed 2997K, 31% free 9571K/13836K, paused 5ms+5ms, total 45ms
,D/dalvikvm( 7770): WAIT_FOR_CONCURRENT_GC blocked 34ms
,D/BadgeProvider( 7770): onCreate
,D/BadgeProvider( 7770): DatabaseHelper
,D/BadgeProvider( 7770): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7770): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7770): sendNotify, [notify] : null
D/BadgeProvider( 7770): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7770): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7770): update, [UpdateCount] : 1
,D/Launcher.Model( 2787): reloadBadges entered.
,D/dalvikvm( 7782): GC_CONCURRENT freed 3015K, 31% free 9558K/13840K, paused 4ms+2ms, total 38ms
,D/dalvikvm( 7782): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/hcjo    ( 5975): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5975): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5975): exit::IDLE
,D/InitializeManagerStateMachine( 5975): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5975): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5975): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5975): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5975): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5975): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5975): entry::SUCCESS
,D/hcjo    ( 5975): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5975): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5975): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5975): exit::SUCCESS
,D/InitializeManagerStateMachine( 5975): entry::IDLE
,E/SPPClientService( 5592): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5592): [SystemStateMoniter] Current Time : 352686
,E/SPPClientService( 5592): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5592): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 4760): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4760): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4760): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 4760): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4760): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4760): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 4760): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4760): MountReceiver.onReceive - Keep current state
E/SPPClientService( 5592): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5592): [a] [ConnectionManager] Connection is already disconnected.
,I/ActivityManager( 2420): Killing 6526:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,D/NearbySettings( 4760): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4760): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4760): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,E/SPPClientService( 5592): [[PushClientService]] <<--- deInitPushClientService  END  --->>
I/NearbySettings( 4760): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4760): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4760): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5592): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/SurfaceFlinger( 1921): id=21 createSurf (1x1),1 flag=4, Uoast
,E/SPPClientService( 5592): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection...
D/PowerManagerService( 2420): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2420
,D/NearbySettings( 4760): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4760): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5592): [a] [ConnectionManager] Connection is already disconnected.
,I/PCWCLIENTTRACE_PushUtil( 6632): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6632): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6632): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6632): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5592): [g] getNetMCC return empty string
,I/KLMS-2.3.201 : ( 7623): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/dalvikvm( 7534): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7534): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7534): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 7534): Shutting down VM
,W/dalvikvm( 7534): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7534): FATAL EXCEPTION: main
E/AndroidRuntime( 7534): Process: com.test.thalitest, PID: 7534
E/AndroidRuntime( 7534): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 7534): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 7534): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 7534): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 7534): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 7534): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 7534): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 7534): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 7534): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 7534): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 7534): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 7534): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7534): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7534): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7534): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7534): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7534): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7534): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7534): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 2420):   Force finishing activity com.test.thalitest/.MainActivity
I/KLMS-2.3.201 : ( 7623): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450463892524
I/KLMS-2.3.201 : ( 7623): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
,I/Process ( 7534): Sending signal. PID: 7534 SIG: 9
,D/CrashAnrDetector( 2420): processName: com.test.thalitest
,D/CrashAnrDetector( 2420): broadcastEvent : com.test.thalitest data_app_crash
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,D/SO_AGENT( 7642): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3470): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/GalaxyFinderApplication( 3470): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3470): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3470): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7642): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/WindowState( 2420): WIN DEATH: Window{444534b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger( 1921): id=20 Removed NainActivit (8/11)
,I/SurfaceFlinger( 1921): id=20 Removed NainActivit (-2/11)
,I/GallerySearchProvider( 3598): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
I/ActivityManager( 2420): Process com.test.thalitest (pid 7534) (adj 9) has died.
D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2420): mDVFSHelper.acquire()
,I/DBG_DM  ( 4796): [3.19.140541][Line:408][onResume] 
,I/DBG_DM  ( 4796): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
,I/SELinux ( 7807): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7807):  
,I/DBG_DM  ( 4796): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4796): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4796): [3.19.140541][Line:418][onResume] Postpone Count : 26
,I/SA      ( 5839): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5839): [BDLM] already registered in spp
,I/SA      ( 5839): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
I/SELinux ( 7807): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7807):  
I/SELinux ( 7807):  
I/SA      ( 5839): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SELinux ( 7807): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7807): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7807): >>>>> Normal User
,E/dalvikvm( 7807): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,I/SA      ( 5839): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5839): [OR] == isSIMCardReady false ==
,E/SELinux ( 7807): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/DBG_DM  ( 4796): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/SA      ( 5839): [SCU] == networkStateCheck == true
I/SA      ( 5839): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5839): isChinaCountryCode : false
,I/SA      ( 5839): [OR] == networkStateCheck true ==
,I/SA      ( 5839): [OR] GetMyCountryZoneTask
,I/SA      ( 5839): [OR] onReceive END
,I/SA      ( 5839): [SRS] prepareGetMyCountryZone
,I/System.out( 7611): Thread-654(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/TimaKeyStoreProvider( 7807): in addTimaSignatureService
,I/DBG_DM  ( 4796): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/SA      ( 5839): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5839): [SSP] query invoked
,D/TimaKeyStoreProvider( 7807): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7807): Added TimaKesytore provider
D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7039): Other Intent
,D/com.samsung.app( 7654): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7654): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/DBG_DM  ( 4796): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/System.out( 7611): Thread-654(ApacheHTTPLog):isShipBuild true
,I/System.out( 7611): Thread-654(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/SA      ( 5839): [TPMU] GetMccFromDB : null
I/SA      ( 5839): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5839): [TPM] isNoProxy(default) : true
,I/SA      ( 5839): [RC New] Execute method=[GET] start
,D/Headlines( 5887): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5887): getCountryCode(): countryCode = PL
W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
D/STATUSBAR-StatusBarManagerService( 2420): sendNotification(2) - 4
D/Headlines( 5887): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5887): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5887): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5887): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5887): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5887): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5887): requestUpdateNewsWelcomeCard !!! no welcome card
,I/DBG_DM  ( 4796): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
,W/WifiP2pStateTracker( 2420): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,I/DBG_DM  ( 4796): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,D/dalvikvm( 7807): GC_FOR_ALLOC freed 3017K, 31% free 9549K/13836K, paused 37ms, total 37ms
,D/ConnectivityService( 2420): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2420):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2420): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2420): updateSourceRoutes : no source routing conditions
I/DBG_DM  ( 4796): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
I/DBG_DM  ( 4796): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4796): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
I/DBG_DM  ( 4796): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
I/DBG_DM  ( 4796): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
D/dalvikvm( 7807): GC_CONCURRENT freed 208K, 31% free 9560K/13836K, paused 3ms+2ms, total 21ms
D/dalvikvm( 7807): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/dalvikvm( 2722): GC_EXPLICIT freed 376K, 33% free 9971K/14752K, paused 21ms+17ms, total 101ms
,D/Activity( 4796): setTransGradationMode to true
,D/StatusBarManagerService( 2420): semi p:4796,o:t
D/PhoneStatusBar( 2582): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
I/DBG_DM  ( 4796): [3.19.140541][Line:400][onPause] 
,I/iu.Environment( 5954): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/System.out( 7611): AsyncTask #1 calls detatch()
,W/System.err( 7611): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7611): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7611): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7611): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7611): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7611): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7611): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 7611): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7611): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7611): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 7611): Caused by: java.lang.NullPointerException
W/System.err( 7611): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7611): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7611): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7611): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7611): 	... 8 more
,D/dalvikvm( 2420): GC_EXPLICIT freed 3935K, 56% free 25025K/55660K, paused 13ms+19ms, total 187ms
,I/SurfaceFlinger( 1921): id=22 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
V/KVNProvider( 7807): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
D/QuickConnect[1.1][2] ( 5192): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
V/KVNProvider( 7807): getFindoCursor query string : 
I/QuickConnect[1.1][2] ( 5192): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 5192): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4229bed8
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,V/KVNProvider( 7807): getTagSearchCursor() tagSearchCursor count : 0
,D/dalvikvm( 5592): GC_CONCURRENT freed 2022K, 25% free 10443K/13820K, paused 6ms+14ms, total 89ms
W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
D/dalvikvm( 5592): WAIT_FOR_CONCURRENT_GC blocked 52ms
,D/dalvikvm( 5592): WAIT_FOR_CONCURRENT_GC blocked 71ms
W/InputMethodManagerService( 2420): Got RemoteException sending setActive(false) notification to pid 7534 uid 10566
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2420): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/hcjo    ( 5975): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 5975): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5975): exit::IDLE
,D/InitializeManagerStateMachine( 5975): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5975): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5975): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5975): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5975): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5975): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5975): entry::SUCCESS
,D/hcjo    ( 5975): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5975): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5975): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5975): exit::SUCCESS
,D/InitializeManagerStateMachine( 5975): entry::IDLE
,E/SPPClientService( 5592): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5592): [SystemStateMoniter] Current Time : 353954
,E/SPPClientService( 5592): [SystemStateMoniter] No Connect : false
D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/SA      ( 5839): [RC New] [v2liruge] api execute + 720
,I/SA      ( 5839): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5839): AsyncTask #2 calls detatch()
,I/SA      ( 5839): [TPMU] getNetworkMcc : 
I/SA      ( 5839): [SCU] saveMccToPreferece Start
I/SA      ( 5839): [SCU] RegionMCC : 260
,I/SA      ( 5839): [SSP] query invoked
,I/SA      ( 5839): [TPMU] GetMccFromDB : null
I/SA      ( 5839): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5839): [SCU] saveMccToPreferece End
,I/SA      ( 5839): [RC New] executeRequest [v2liruge] end. 732
I/SA      ( 5839): [RC New] Execute end
I/SA      ( 5839): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5839): [OR] GetMyCountryZoneTask Success
,E/WifiStateMachine( 2420): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 7828): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7828):  
,I/SELinux ( 7828): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7828):  
I/SELinux ( 7828):  
,I/SELinux ( 7828): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7828): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7828): >>>>> Normal User
,E/dalvikvm( 7828): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 7828): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 7828): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7828): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7828): Added TimaKesytore provider
,D/dalvikvm( 7828): GC_CONCURRENT freed 2998K, 31% free 9564K/13832K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7828): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/Headlines( 5887): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5887): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5887): Breath 1316 latestRequest time : 1450463892854 current time : 1450463894171
D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@8
,I/ActivityManager( 2420): Killing 6603:com.samsung.groupcast/u0a15 (adj 15): empty #43
E/SPPClientService( 5592): [b] __InitReply__
,I/ActivityManager( 2420): Killing 6618:com.android.musicfx/u0a24 (adj 15): empty #43,
,I/SurfaceFlinger( 1921): id=21 Removed Uoast (10/11),
,I/SurfaceFlinger( 1921): id=21 Removed Uoast (-2/11),
D/PowerManagerService( 2420): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2420) eventTime = 356409
,D/PowerManagerService( 2420): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2420 (0x0),
,D/PowerManagerService( 2420): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2420, ws=WorkSource{1000}) (elapsedTime=3485),
,I/GAV2    ( 7678): Thread[GAThread,5,main]: No campaign data found.
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6632): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6632): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6632): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6632): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6632): GetString : secure API is not supported!!
,I/PCWCLIENTTRACE_PushUtil( 6632): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6632): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6632): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6632): [ensureRegistration] - No Samsung account
,D/AmoledAdjustTimer( 2420): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4,
,D/CaptivePortalTracker( 2420): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
D/ConnectivityService( 2420): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2420): Checking http://216.58.209.46/generate_204,
,D/CaptivePortalTracker( 2420): Don't send network conditions - lacking user consent.,
D/CaptivePortalTracker( 2420): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 2420): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2420): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
D/ConnectivityService( 2420): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 5975): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5975): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5975): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 5975): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5975): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5975): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5975): entry::IDLE
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/PreloadUpdateManagerStateMachine( 5975): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5975): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5975): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5975): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5975): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5975): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5975): entry::IDLE
,I/ActivityManager( 2420): Waited long enough for: ServiceRecord{44bc5170 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = -10
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 2420): Waited long enough for: ServiceRecord{42fe9b08 u0 com.sec.spp.push/.PushClientService}
,D/AmoledAdjustTimer( 2420): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2420): !@Sync 12
,D/AmoledAdjustTimer( 2420): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,D/Headlines( 5887): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5887): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5887): Breath 27279 latestRequest time : 1450463892854 current time : 1450463920133
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2420): [PWL] Off : 180s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2420): !@Sync 13
,D/AmoledAdjustTimer( 2420): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,D/Headlines( 5887): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5887): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5887): Breath 57275 latestRequest time : 1450463892854 current time : 1450463950129
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2420): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 225s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2420): !@Sync 14
,D/AmoledAdjustTimer( 2420): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,D/Headlines( 5887): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5887): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5887): Breath 87276 latestRequest time : 1450463892854 current time : 1450463980130
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2420): !@Sync 15
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,D/Headlines( 5887): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5887): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5887): Breath 117277 latestRequest time : 1450463892854 current time : 1450464010131
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 275s ago
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2420): !@Sync 16
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,D/Headlines( 5887): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5887): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5887): Breath 147278 latestRequest time : 1450463892854 current time : 1450464040132
,D/Headlines( 5887): stop 
,D/Headlines( 5887): Breath.onDestroy : 
I/ActivityManager( 2420): Killing 6644:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2420): !@Sync 17
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 18
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 293, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2420): !@Sync 19
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 20
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2420): !@Sync 21
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 455s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4014): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,I/GAV2    ( 5684): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5684): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2420): !@Sync 22
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2420): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2420): <AppSync3 Whitelist>
,V/AlarmManager( 2420): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/dalvikvm( 4091): GC_CONCURRENT freed 2882K, 30% free 9724K/13876K, paused 6ms+4ms, total 65ms
,D/dalvikvm( 2420): GC_CONCURRENT freed 4005K, 56% free 24900K/55660K, paused 21ms+16ms, total 224ms
,E/Watchdog( 2420): !@Sync 23
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 525s ago
,E/Watchdog( 2420): !@Sync 24
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 25
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 26
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 5
,D/LightsService( 2420): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2420): LightSensor setDelay = 200000000
D/Sensors ( 2420): LightSensor setSensorDelay = 200000000
D/Sensors ( 2420): Light sensor flush: not enabled 0
D/Sensors ( 2420): LightSensor enable = 1
D/Sensors ( 2420): LightSensor enableSensor = 1
D/SensorManager( 2420): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,E/SPPClientService( 5592): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/Sensors ( 2420): LightSensor enable = 0
D/Sensors ( 2420): LightSensor enableSensor = 0
,D/SensorManager( 2420): unregisterListener ::   
D/LightsService( 2420): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 27
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 28
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 680s ago
,E/Watchdog( 2420): !@Sync 29
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 30
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 31
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 765s ago
,E/Watchdog( 2420): !@Sync 32
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 33
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 34
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 855s ago
,E/Watchdog( 2420): !@Sync 35
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 36
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5592): [b] __PingReply__
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2420): GC_CONCURRENT freed 3825K, 56% free 24898K/55660K, paused 14ms+15ms, total 211ms
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 37
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2420): [PWL] Off : 950s ago
,E/Watchdog( 2420): !@Sync 38
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2787): GC_CONCURRENT freed 7128K, 40% free 18948K/31120K, paused 9ms+7ms, total 99ms
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 39
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 40
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 41
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 42
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2420): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2420): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2420): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 43
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 44
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1155s ago
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 45
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 46
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
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
,I/EventLogService( 3314): Aggregate from 1450463000702 (log), 1450463000702 (data)
,D/Sensors ( 2420): LightSensor enable = 0
,D/Sensors ( 2420): LightSensor enableSensor = 0
,D/SensorManager( 2420): unregisterListener ::   
D/LightsService( 2420): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4091): GC_CONCURRENT freed 2050K, 30% free 9722K/13876K, paused 4ms+3ms, total 55ms
,D/dalvikvm( 4091): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 47
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 48
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1265s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 49
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 50
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 2420): GC_CONCURRENT freed 3870K, 56% free 24901K/55660K, paused 22ms+17ms, total 237ms
,D/dalvikvm( 2420): WAIT_FOR_CONCURRENT_GC blocked 212ms
,D/dalvikvm( 2420): WAIT_FOR_CONCURRENT_GC blocked 216ms
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 51
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 52
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 53
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 54
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 55
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 56
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2420): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,E/SPPClientService( 5592): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 57
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 58
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 59
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 60
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1625s ago
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2420): Prepared write state in 40ms
,I/ProcessStatsService( 2420): Prepared write state in 53ms
,I/ProcessStatsService( 2420): Pruning old procstats: /data/system/procstats/state-2015-12-18-06-51-00.bin
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 61
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 62
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2420): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2420): <AppSync3 Whitelist>
,V/AlarmManager( 2420): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 63
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 64
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/dalvikvm( 2420): GC_CONCURRENT freed 3766K, 56% free 24915K/55660K, paused 24ms+17ms, total 249ms
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
I/ActivityManager( 2420): Killing 6989:com.sec.android.Kies/1000 (adj 15): empty for 1803s
,I/ActivityManager( 2420): Killing 6520:com.sec.knox.bridge/1000 (adj 15): empty for 1822s
,I/ActivityManager( 2420): Killing 4915:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1822s
,I/ActivityManager( 2420): Killing 6482:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1832s
,I/ActivityManager( 2420): Killing 6791:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1832s
,I/ActivityManager( 2420): Killing 6777:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1833s
,I/ActivityManager( 2420): Killing 6765:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1833s
,I/ActivityManager( 2420): Killing 6753:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1833s
,I/ActivityManager( 2420): Killing 6740:com.samsung.helphub/1000 (adj 15): empty for 1833s
,I/ActivityManager( 2420): Killing 6727:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1834s
,I/ActivityManager( 2420): Killing 6714:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1834s
I/ActivityManager( 2420): Killing 6701:com.sec.android.service.cm/u0a82 (adj 15): empty for 1834s
,I/ActivityManager( 2420): Killing 6436:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1834s
,I/ActivityManager( 2420): Killing 6000:com.android.mms/u0a49 (adj 15): empty for 1834s
,I/ActivityManager( 2420): Killing 6674:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1834s
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2420): Killing 6038:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1835s
,D/CountryDetector( 2420): No listener is left
,I/PowerManagerService( 2420): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 65
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 66
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :4
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): performPollLocked(flags=0x3)
V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): performPollLocked() took 43ms
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,I/SELinux (12108): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12108):  
I/ActivityManager( 2420): Killing 7017:com.google.android.apps.uploader/u0a117 (adj 15): empty for 1849s
I/ActivityManager( 2420): Killing 7001:com.android.chrome/u0a85 (adj 15): empty for 1849s
,I/SELinux (12108): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12108):  
I/SELinux (12108):  
,I/SELinux (12108): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12108): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(12108): >>>>> Normal User
,E/dalvikvm(12108): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (12108): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(12108): in addTimaSignatureService
,D/TimaKeyStoreProvider(12108): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(12108): Added TimaKesytore provider
,D/dalvikvm(12108): GC_CONCURRENT freed 3002K, 31% free 9565K/13840K, paused 3ms+2ms, total 24ms
,D/dalvikvm(12108): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/@ WidgetProvider(12108): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(12108): onUpdate called for widgetId : 0
,D/@ WidgetProvider(12108): Widget random data : 8
,D/@ WidgetProvider(12108): onUpdate called for widgetId : 5
,D/@ WidgetProvider(12108): Widget random data : 6
,E/dalvikvm(12108): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(12108): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12108): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12108): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12108): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12108): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12108): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12108): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12108): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12108): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(12108): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12108): VFY: replacing opcode 0x22 at 0x0038
,D/dalvikvm(12108): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
,D/dalvikvm(12108): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(12108): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(12108): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 5
,D/LightsService( 2420): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2420): LightSensor setDelay = 200000000
D/Sensors ( 2420): LightSensor setSensorDelay = 200000000
D/Sensors ( 2420): Light sensor flush: not enabled 0
D/Sensors ( 2420): LightSensor enable = 1
D/Sensors ( 2420): LightSensor enableSensor = 1
D/SensorManager( 2420): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/GLSActivity( 2852): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2852): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(12108): Thread-684(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(12108): Thread-684(ApacheHTTPLog):isShipBuild true
,I/System.out(12108): Thread-684(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/LightsService( 2420): [SvcLED]  onSensorChanged::light value = 0
D/Sensors ( 2420): LightSensor enable = 0
D/Sensors ( 2420): LightSensor enableSensor = 0
,D/SensorManager( 2420): unregisterListener ::   
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/System.out(12108): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(12108): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(12108): Max ALLOWED memory (MB): 128
V/ImageManager(12108): Max SHOULD USE memory (MB): 128
,V/ImageManager(12108): Max Image Cache memory (MB): 32
,D/skia    (12108): getTotalSize : Do not get file length
,D/@ WidgetProvider(12108): Building widget : 5
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 67
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 68
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 69
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 70
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4014): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4014): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4091): GC_CONCURRENT freed 2047K, 30% free 9722K/13876K, paused 8ms+3ms, total 29ms
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 71
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime(12422): 
D/AndroidRuntime(12422): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(12422): CheckJNI is OFF
D/AndroidRuntime(12422): setted country_code = Poland
D/AndroidRuntime(12422): setted countryiso_code = PL
D/AndroidRuntime(12422): setted sales_code = PLS
D/AndroidRuntime(12422): readGMSProperty: start
D/AndroidRuntime(12422): readGMSProperty: already setted!!
D/AndroidRuntime(12422): readGMSProperty: end
D/AndroidRuntime(12422): addProductProperty: start
D/dalvikvm(12422): Trying to load lib libjavacore.so 0x0
D/dalvikvm(12422): Added shared lib libjavacore.so 0x0
D/dalvikvm(12422): Trying to load lib libnativehelper.so 0x0
D/dalvikvm(12422): Added shared lib libnativehelper.so 0x0
D/dalvikvm(12422): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack(12422): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug(12422): failed to load memtrack module: -2
D/dalvikvm(12422): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime(12422): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2420): START PACKAGE DELETE: observer{1125352600}
D/PackageManager( 2420): pkg{<packageName>}
D/PackageManager( 2420): user{0}
D/PackageManager( 2420): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2420): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2420): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2420): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2420): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 2420): !@killApplicatoin: 10566, uninstall pkg
I/ActivityManager( 2420): Killing 6658:com.policydm/1000 (adj 15): empty for 1800s
I/ActivityManager( 2420): Killing 7642:com.sec.android.soagent/u0a38 (adj 15): empty for 1800s
I/ActivityManager( 2420): Killing 7582:com.vlingo.midas/u0a34 (adj 15): empty for 1800s
I/ActivityManager( 2420): Killing 7623:com.samsung.klmsagent/u0a18 (adj 15): empty for 1800s
I/ActivityManager( 2420): Killing 7611:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1800s
I/ActivityManager( 2420): Killing 5777:com.sec.android.diagmonagent/1000 (adj 15): empty for 1801s
I/ActivityManager( 2420): Killing 6969:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1801s
I/ActivityManager( 2420): Killing 6632:com.sec.pcw.device/1000 (adj 15): empty for 1801s
I/ActivityManager( 2420): Killing 4760:com.android.settings/1000 (adj 15): empty for 1801s
I/ActivityManager( 2420): Killing 7770:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1801s
W/PackageSettings( 2420): Skipping PackageSetting{429976b8 com.example.hello/10551} due to missing metadata
D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10566, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 6505): GC_EXPLICIT freed 282K, 28% free 9983K/13824K, paused 12ms+10ms, total 74ms
D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10566, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/FPMS_FingerprintManagerService( 2602): onReceive: android.intent.action.PACKAGE_REMOVED
D/dalvikvm( 2955): GC_EXPLICIT freed 1457K, 28% free 10033K/13836K, paused 10ms+8ms, total 112ms
E/SamsungIME( 2977): mOCRHelper is null
I/InputReader( 2420): Reconfiguring input devices.  changes=0x00000010
D/QuickConnect[1.1][2] ( 5192): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/SELinux (12451): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12451):  
I/SELinux (12451): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12451):  
I/SELinux (12451):  
I/SELinux (12451): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12451): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12451): >>>>> Normal User
E/dalvikvm(12451): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux (12451): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "sms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/GeofencerStateMachine( 2736): Ignoring removeGeofence because network location is disabled.
D/TimaKeyStoreProvider(12451): in addTimaSignatureService
D/dalvikvm( 3314): GC_EXPLICIT freed 1663K, 20% free 12605K/15692K, paused 25ms+148ms, total 261ms
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "smsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider(12451): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12451): Added TimaKesytore provider
W/SQLiteConnectionPool( 3314): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/RegisteredServicesCache( 2758): empty dynamic service
D/dalvikvm( 2420): GC_EXPLICIT freed 3375K, 56% free 25018K/55660K, paused 13ms+27ms, total 310ms
D/dalvikvm( 2420): WAIT_FOR_CONCURRENT_GC blocked 152ms
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mmsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/EnterpriseDeviceManagerService( 2420): Package has changed for user 0
D/RCPManagerService( 2420): PackageReceiver onReceive()
I/HarmonyEASService( 2420): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "sms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "smsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(12451): GC_CONCURRENT freed 2999K, 31% free 9564K/13836K, paused 12ms+7ms, total 78ms
D/dalvikvm(12451): WAIT_FOR_CONCURRENT_GC blocked 66ms
D/dalvikvm( 2758): GC_CONCURRENT freed 1211K, 28% free 10614K/14732K, paused 8ms+3ms, total 74ms
D/dalvikvm( 2758): WAIT_FOR_CONCURRENT_GC blocked 44ms
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mmsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132(12451): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132(12451): ELMEngine.ELMEngine( context ).
D/elm:14132(12451): MDMBridge.setEnterpriseBridge()
D/elm:14132(12451): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132(12451): ElmAgentService : onCreate()
D/elm:14132(12451): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132(12451): MainReceiver.listeningToPackageRemoved()
D/elm:14132(12451): MDMBridge.getInstance()
D/elm:14132(12451): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux (12466): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12466):  
D/elm:14132(12451): MDMBridge.getAllLicenseInfoFromSDK()
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132(12451): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
I/SELinux (12466): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12466):  
I/SELinux (12466):  
I/SELinux (12466): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12466): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12466): >>>>> Normal User
E/dalvikvm(12466): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux (12466): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/elm:14132(12451): ElmAgentService : onDestroy().
I/ActivityManager( 2420): Killing 6372:com.sec.android.app.videoplayer/u0a53 (adj 15): empty for 1801s
D/TimaKeyStoreProvider(12466): in addTimaSignatureService
D/TimaKeyStoreProvider(12466): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12466): Added TimaKesytore provider
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService( 2420): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 2420): removePackageParticipantsLocked: uid=10566 #1
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(12466): GC_CONCURRENT freed 3010K, 31% free 9560K/13840K, paused 2ms+1ms, total 18ms
D/dalvikvm(12466): WAIT_FOR_CONCURRENT_GC blocked 15ms
D/dalvikvm( 2420): GC_EXPLICIT freed 1166K, 55% free 25063K/55660K, paused 12ms+40ms, total 462ms
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (12481): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12481):  
I/ActivityManager( 2420): Killing 5839:com.osp.app.signin/u0a44 (adj 15): empty for 1801s
I/SELinux (12481): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12481):  
I/SELinux (12481):  
I/SELinux (12481): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12481): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12481): >>>>> Normal User
E/dalvikvm(12481): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux (12481): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(12481): in addTimaSignatureService
D/TimaKeyStoreProvider(12481): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12481): Added TimaKesytore provider
D/PackageManager( 2420): delete sourFile : 
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/PackageManager( 2420): delete native library directory: 
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 2420): return delete result to caller: 1125352600
D/AndroidRuntime(12422): Shutting down VM
D/PackageManager( 2420): returnCode: 1
D/dalvikvm(12422): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 0ms+1ms, total 5ms
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "sms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(12481): GC_CONCURRENT freed 3006K, 31% free 9567K/13840K, paused 5ms+2ms, total 36ms
D/dalvikvm(12481): WAIT_FOR_CONCURRENT_GC blocked 29ms
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "smsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mmsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (12495): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12495):  
I/ActivityManager( 2420): Killing 7039:com.samsung.android.scloud.backup/u0a62 (adj 15): empty for 1801s
I/CrashAnrDetector( 2420): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2420): clearDefaults: com.test.thalitest
W/ApplicationsProvider( 2955): Could not fetch usage stats
W/ApplicationsProvider( 2955): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2955): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2955): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2955): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2955): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2955): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2955): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2955): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2955): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2955): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2955): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2955): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SELinux (12495): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12495):  
I/SELinux (12495):  
I/SELinux (12495): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12495): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(12495): >>>>> Normal User
E/dalvikvm(12495): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
E/SELinux (12495): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(12495): in addTimaSignatureService
D/TimaKeyStoreProvider(12495): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12495): Added TimaKesytore provider
D/dalvikvm(12495): GC_CONCURRENT freed 2999K, 31% free 9568K/13836K, paused 2ms+2ms, total 28ms
D/dalvikvm(12495): WAIT_FOR_CONCURRENT_GC blocked 24ms
I/SELinux (12511): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12511):  
I/ActivityManager( 2420): Killing 7807:com.sec.android.app.voicenote/1000 (adj 15): empty for 1802s
I/SELinux (12511): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12511):  
I/SELinux (12511):  
I/SELinux (12511): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12511): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12511): >>>>> Normal User
E/dalvikvm(12511): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
E/SELinux (12511): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/dalvikvm(12511): Enabling JNI app bug workarounds for target SDK version 8...
D/TimaKeyStoreProvider(12511): in addTimaSignatureService
D/TimaKeyStoreProvider(12511): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12511): Added TimaKesytore provider
D/dalvikvm(12511): GC_CONCURRENT freed 3002K, 31% free 9566K/13840K, paused 4ms+2ms, total 27ms
D/dalvikvm(12511): WAIT_FOR_CONCURRENT_GC blocked 22ms
E/SQLiteDatabase(12511): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(12511): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12511): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(12511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(12511): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12511): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(12511): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(12511): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(12511): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(12511): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(12511): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(12511): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(12511): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/SQLiteDatabase(12511): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase(12511): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase(12511): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase(12511): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase(12511): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase(12511): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(12511): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(12511): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12511): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(12511): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(12511): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(12511): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(12511): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(12511): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(12511): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(12511): Shutting down VM
W/dalvikvm(12511): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(12511): FATAL EXCEPTION: main
E/AndroidRuntime(12511): Process: com.sec.pcw.device, PID: 12511
E/AndroidRuntime(12511): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.URLProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12511): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime(12511): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime(12511): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime(12511): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(12511): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(12511): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12511): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(12511): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(12511): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(12511): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(12511): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(12511): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(12511): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(12511): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12511): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(12511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(12511): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12511): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(12511): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(12511): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(12511): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(12511): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(12511): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime(12511): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime(12511): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/AndroidRuntime(12511): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime(12511): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime(12511): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime(12511): 	... 12 more
E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop238.tmp: open failed: EROFS (Read-only file system)
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
I/SELinux (12524): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12524):  
I/Process (12511): Sending signal. PID: 12511 SIG: 9
I/ActivityManager( 2420): Process com.sec.pcw.device (pid 12511) (adj 0) has died.
I/SELinux (12524): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12524):  
I/SELinux (12524):  
I/SELinux (12524): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12524): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12524): >>>>> Normal User
E/dalvikvm(12524): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
E/SELinux (12524): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(12524): in addTimaSignatureService
D/TimaKeyStoreProvider(12524): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12524): Added TimaKesytore provider
D/dalvikvm(12524): GC_CONCURRENT freed 2994K, 31% free 9575K/13836K, paused 2ms+2ms, total 24ms
D/dalvikvm(12524): WAIT_FOR_CONCURRENT_GC blocked 22ms
W/System.err(12524): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err(12524): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err(12524): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err(12524): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err(12524): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err(12524): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err(12524): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err(12524): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err(12524): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err(12524): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err(12524): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err(12524): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err(12524): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err(12524): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err(12524): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err(12524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(12524): 	at android.os.Looper.loop(Looper.java:146)
W/System.err(12524): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err(12524): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err(12524): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err(12524): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err(12524): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err(12524): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err(12524): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err(12524): 	at libcore.io.Posix.open(Native Method)
W/System.err(12524): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err(12524): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err(12524): 	... 21 more
D/GalaxyFinderApplication(12524): [Slink platform] Version = 29011
D/GalaxyFinderApplication(12524): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux (12538): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12538):  
I/ActivityManager( 2420): Killing 7654:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty for 1802s
D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 13% free 9501K/10816K, paused 3ms+3ms, total 38ms
I/SELinux (12538): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12538):  
I/SELinux (12538):  
I/SELinux (12538): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12538): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(12538): >>>>> Normal User
E/dalvikvm(12538): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
E/SELinux (12538): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9501K/10816K, paused 2ms+4ms, total 33ms
D/TimaKeyStoreProvider(12538): in addTimaSignatureService
D/TimaKeyStoreProvider(12538): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12538): Added TimaKesytore provider
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9501K/10816K, paused 3ms+4ms, total 30ms
D/dalvikvm(12538): GC_CONCURRENT freed 3015K, 31% free 9550K/13836K, paused 3ms+2ms, total 24ms
D/dalvikvm(12538): WAIT_FOR_CONCURRENT_GC blocked 22ms
W/ContextImpl(12538): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences(12538): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences(12538): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication(12538): ContentProvider is not null
W/ResourceType(12538): No package identifier when getting value for resource number 0x00000000
I/System.out(12538): resource Id::2131361807
E/SQLiteDatabase(12538): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(12538): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12538): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12538): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(12538): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(12538): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12538): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12538): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12538): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(12538): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(12538): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(12538): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(12538): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(12538): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(12538): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(12538): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/SQLiteDatabase(12538): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/SQLiteDatabase(12538): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/SQLiteDatabase(12538): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase(12538): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase(12538): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase(12538): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase(12538): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/SQLiteDatabase(12538): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/SQLiteDatabase(12538): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/SQLiteDatabase(12538): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/SQLiteDatabase(12538): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/SQLiteDatabase(12538): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/SQLiteDatabase(12538): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/SQLiteDatabase(12538): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(12538): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(12538): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12538): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(12538): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(12538): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(12538): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(12538): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(12538): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(12538): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(12538): Shutting down VM
W/dalvikvm(12538): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(12538): FATAL EXCEPTION: main
E/AndroidRuntime(12538): Process: com.sec.android.app.shealth, PID: 12538
E/AndroidRuntime(12538): java.lang.RuntimeException: Unable to create application com.sec.android.app.shealth.SHealthApplication: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12538): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4793)
E/AndroidRuntime(12538): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(12538): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(12538): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12538): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(12538): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(12538): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(12538): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(12538): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(12538): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(12538): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(12538): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12538): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12538): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(12538): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(12538): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12538): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12538): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12538): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(12538): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(12538): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(12538): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(12538): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(12538): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/AndroidRuntime(12538): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/AndroidRuntime(12538): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/AndroidRuntime(12538): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/AndroidRuntime(12538): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/AndroidRuntime(12538): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/AndroidRuntime(12538): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/AndroidRuntime(12538): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/AndroidRuntime(12538): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/AndroidRuntime(12538): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/AndroidRuntime(12538): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/AndroidRuntime(12538): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/AndroidRuntime(12538): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/AndroidRuntime(12538): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/AndroidRuntime(12538): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/AndroidRuntime(12538): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/AndroidRuntime(12538): 	... 10 more
E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop239.tmp: open failed: EROFS (Read-only file system)
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
I/SELinux (12558): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12558):  
I/Process (12538): Sending signal. PID: 12538 SIG: 9
D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): stay LED for fully charged
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED

```
