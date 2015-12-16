#### Test 50650278cd699a4_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2396): stay LED for fully charged
D/UiModeManager( 2396): mCoverManager.getCoverState() : true
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 3997): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
D/AndroidRuntime( 7467): 
D/AndroidRuntime( 7467): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7467): CheckJNI is OFF
D/AndroidRuntime( 7467): setted country_code = Poland
D/AndroidRuntime( 7467): setted countryiso_code = PL
D/AndroidRuntime( 7467): setted sales_code = PLS
D/AndroidRuntime( 7467): readGMSProperty: start
D/AndroidRuntime( 7467): readGMSProperty: already setted!!
D/AndroidRuntime( 7467): readGMSProperty: end
D/AndroidRuntime( 7467): addProductProperty: start
D/dalvikvm( 7467): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7467): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7467): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7467): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7467): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7467): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7467): failed to load memtrack module: -2
D/dalvikvm( 7467): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7467): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2396): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2396): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2396  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2396): mDVFSHelper.acquire()
I/SELinux ( 7497): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7497):  
D/PointerIcon( 2396): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2396): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2396): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2396): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7467): Shutting down VM
D/dalvikvm( 7467): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 7497): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7497):  
I/SELinux ( 7497):  
I/SELinux ( 7497): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7497): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7497): >>>>> Normal User
E/dalvikvm( 7497): >>>>> com.test.thalitest [ userId:0 | appId:10556 ]
E/SELinux ( 7497): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7497): in addTimaSignatureService
D/TimaKeyStoreProvider( 7497): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7497): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4157): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4157): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7497): GC_CONCURRENT freed 2997K, 32% free 9567K/14020K, paused 2ms+1ms, total 20ms
D/dalvikvm( 7497): WAIT_FOR_CONCURRENT_GC blocked 17ms
V/WebViewChromium( 7497): Binding Chromium to the background looper Looper (main, tid 1) {422c0320}
I/chromium( 7497): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7497): Initializing chromium process, renderers=0
W/chromium( 7497): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7497): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7497): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7497): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7497): Mali API Version : 401
,I/Mali    ( 7497): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7497): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>,
W/dalvikvm( 7497): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7497): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7497): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7497): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7497): VFY: replacing opcode 0x6e at 0x0008,
,D/PhoneStatusBar( 2579): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false,
D/StatusBarManagerService( 2396): tr p:7497,o:f
,W/dalvikvm( 7497): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;),
W/dalvikvm( 7497): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7497): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7497): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7497): VFY: replacing opcode 0x6f at 0x001a,
W/dalvikvm( 7497): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7497): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7497): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7497): VFY: replacing opcode 0x6e at 0x000d,
I/dalvikvm( 7497): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7497): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7497): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7497): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2579): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false,
D/StatusBarManagerService( 2396): semi p:7497,o:f
,I/SurfaceFlinger( 1920): id=21 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2396): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2396): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2396): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2396): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2396): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2396): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7497): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7497): Enabling debug mode 0,
,W/AwContents( 7497): nativeOnDraw failed; clearing to background color.,
,W/ContextImpl( 2396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/CustomFrequencyManagerService( 2396): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2396  tag : ACTIVITY_RESUME_BOOSTER@4
,W/AwContents( 7497): nativeOnDraw failed; clearing to background color.,
W/ActivityManager( 2396): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2396): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2396  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/IInputConnectionWrapper( 7497): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 7497): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 7497): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422c10c8
D/dalvikvm( 7497): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422c10c8
D/jxcore_app_log( 7497): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027542608
D/JX-Cordova( 7497): jxcore cordova android initializing
D/dalvikvm( 7497): GC_CONCURRENT freed 1306K, 20% free 11333K/14088K, paused 1ms+2ms, total 23ms
D/dalvikvm( 7497): WAIT_FOR_CONCURRENT_GC blocked 13ms
D/dalvikvm( 7497): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/CustomFrequencyManagerService( 2396): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2396  tag : ACTIVITY_RESUME_BOOSTER@8,
,D/dalvikvm( 7497): GC_CONCURRENT freed 1926K, 19% free 14915K/18304K, paused 1ms+2ms, total 43ms
,D/dalvikvm( 7497): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 7497): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/AmoledAdjustTimer( 2396): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4
,D/dalvikvm( 7497): GC_FOR_ALLOC freed 5381K, 31% free 16207K/23248K, paused 54ms, total 54ms
,D/dalvikvm( 7497): GC_CONCURRENT freed 6704K, 32% free 17672K/25848K, paused 3ms+9ms, total 61ms
,D/dalvikvm( 7497): WAIT_FOR_CONCURRENT_GC blocked 37ms
,D/dalvikvm( 7497): GC_FOR_ALLOC freed 1319K, 33% free 17495K/25848K, paused 37ms, total 37ms
,I/dalvikvm-heap( 7497): Grow heap (frag case) to 22.039MB for 3713210-byte allocation
,D/dalvikvm( 7497): GC_FOR_ALLOC freed 42K, 29% free 21079K/29476K, paused 38ms, total 38ms
,W/jxcore-log( 7497): Initializing JXcore engine
,W/jxcore-log( 7497): JXcore engine is ready
,W/jxcore-log( 7497): Starting JXcore engine
,W/jxcore-log( 7497): Platform android
W/jxcore-log( 7497): 
,W/jxcore-log( 7497): Process ARCH arm
W/jxcore-log( 7497): 
,I/jxcore-log( 7497): JXcore Cordova bridge is ready!
I/jxcore-log( 7497): 
,W/jxcore-log( 7497): JXcore engine is started
,I/chromium( 7497): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ContextImpl( 2396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7497): Toggling radios to true
I/jxcore-log( 7497): 
,D/BluetoothAdapter( 7497): enable(): BT is already enabled..!
,I/WifiManager( 7497): packageName : com.test.thalitest
,I/WifiManager( 7497): setWifiEnabled : true
,I/WifiService( 2396): setWifiEnabled: true pid=7497, uid=10556
W/ActivityManager( 2396): Permission Denial: getCurrentUser() from pid=7497, uid=10556 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 2396): Failed getting userId using ActivityManagerNative
W/WifiService( 2396): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7497, uid=10556 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2396): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2396): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2396): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2396): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2396): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2396): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService( 2396): disconnect: pid=7497, uid=10556
,I/wpa_supplicant( 3969): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7497): Radios toggled
I/jxcore-log( 7497): 
,I/wpa_supplicant( 3969): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3969): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2396): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2396): interfaceStatusChanged wlan0, true
I/jxcore-log( 7497): Got Device Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 7497): 
D/Tethering( 2396): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2396): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3969): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3969): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3969): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3969): First Scan Start
,W/Settings( 2396): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 3969): Scan requested (ret=0) - scan timeout 30 seconds
,I/WifiStateMachine( 2396): ignore requestNetworkTransitionWakelock airplane:true
,I/jxcore-log( 7497): Perf Test app loaded loaded
I/jxcore-log( 7497): 
D/WifiP2pService( 2396): InactiveState{ what=143375 }
D/WifiP2pService( 2396): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/jxcore-log( 7497): check test folder
I/jxcore-log( 7497): 
D/CommandListener( 1915): Clearing all IP addresses on wlan0
,I/jxcore-log( 7497): found test : ./testFindPeers.js
I/jxcore-log( 7497): 
,I/WifiTrafficPoller( 2396): evaluateTrafficStatsPolling
I/wpa_supplicant( 3969): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3969): Skip scan - already scanning
D/ConnectivityService( 2396): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
D/ConnectivityService( 2396): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2396): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2396): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2396): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2396): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/WifiP2pService( 2396): InactiveState{ what=143375 }
D/WifiP2pService( 2396): P2pEnabledState{ what=143375 }
,D/STATUSBAR-IconMerger( 2579): checkOverflow(336), More:false, Req:false Child:3
,I/SELinux ( 7544): Function: selinux_android_load_priority [0], There is no sepolicy file.
,I/SELinux ( 7544):  
D/ConnectivityService( 2396): Attempting to switch to mobile
D/ConnectivityService( 2396): Attempting to switch to BLUETOOTH_TETHER
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1915): Clearing all IP addresses on wlan0,
,I/WifiTrafficPoller( 2396): evaluateTrafficStatsPolling,
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1,
,I/jxcore-log( 7497): found test : ./testSendData.js
I/jxcore-log( 7497): 
I/SELinux ( 7544): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7544):  
I/SELinux ( 7544):  
,I/SELinux ( 7544): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7544): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7544): >>>>> Normal User
,E/dalvikvm( 7544): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7544): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/WifiStateMachine( 2396): Error! unhandled message{ when=-88ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2396): Error! unhandled message{ when=-90ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1915): RTNETLINK answers: No such process
,E/WifiStateMachine( 2396): Error! unhandled message{ when=-33ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,W/NetworkManagementService( 2396): route cmd failed: 
W/NetworkManagementService( 2396): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2396): '
W/NetworkManagementService( 2396): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2396): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2396): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2396): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2396): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2396): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2396): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2396): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2396): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2396): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2396): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2396): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2396): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/TimaKeyStoreProvider( 7544): in addTimaSignatureService
,V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
,D/TimaKeyStoreProvider( 7544): Cannot add TimaSignature Service, License check Failed
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,D/ActivityThread( 7544): Added TimaKesytore provider
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/NetUtils( 2396): android_net_utils_resetConnections in env=0x782d42e0 clazz=0x61900001 iface=wlan0 mask=0x3
D/ConnectivityService( 2396): resetConnections(wlan0, 3)
,E/SPPClientService( 5505): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
E/SPPClientService( 5505): [e] exceptionCaught(). NET_TIMEOUT
V/NativeCrypto( 2845): Read error: ssl=0x7bb488b8: I/O error during system call, Connection timed out
E/SPPClientService( 5505): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
V/NativeCrypto( 2845): SSL shutdown failed: ssl=0x7bb488b8: I/O error during system call, Broken pipe
,E/SPPClientService( 5505): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5505): [b] ResponseMap empty
,D/dalvikvm( 7544): GC_CONCURRENT freed 2994K, 32% free 9581K/14024K, paused 6ms+1ms, total 34ms
,D/dalvikvm( 7544): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/System.out( 7544): Inside WakeupProvider
,I/System.out( 7544): Inside onCreate() of WakeupTriggerProvide
,I/chromium( 7497): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/NtpTrustedTime( 2396): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2396): currentTimeMillis() cache hit
V/NetworkStats( 2396): updateIfacesLocked()
V/NetworkStats( 2396): performPollLocked(flags=0x1)
D/ConnectivityService( 2396): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime( 2396): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2396): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2396): currentTimeMillis() cache hit
,V/NetworkStats( 2396): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2396): currentTimeMillis() cache hit,
V/NetworkStats( 2396): performPollLocked() took 24ms
,D/NtpTrustedTime( 2396): currentTimeMillis() cache hit,
,D/NtpTrustedTime( 2396): currentTimeMillis() cache hit
,I/VlingoApplication( 7544): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS,
D/VlingoApplication( 7544): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7544): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility,
,D/NearbySettings( 2830): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,V/NearbySettings( 2830): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2830): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 2830): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2830): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2830): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2830): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2396): Killing 5359:com.google.android.talk/u0a109 (adj 15): empty #43
,D/DialogFlow( 7544): initQueue()
,D/NearbySettings( 2830): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2830): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2830): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 2830): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2830): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2830): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2830): MountReceiver.mPrefHandler - 7002
,I/SELinux ( 7572): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7572):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 14% free 9503K/10996K, paused 5ms+5ms, total 54ms
I/SELinux ( 7572): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7572):  
I/SELinux ( 7572):  
,I/SELinux ( 7572): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7572): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7572): >>>>> Normal User
,E/dalvikvm( 7572): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
,E/SELinux ( 7572): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7572): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7572): Cannot add TimaSignature Service, License check Failed
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 14% free 9503K/10996K, paused 6ms+5ms, total 40ms
,D/ActivityThread( 7572): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 14% free 9503K/10996K, paused 3ms+5ms, total 38ms
,I/ApplicationPolicy( 2396): updateDataUsageMap
,D/Tethering( 2396): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2396): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2396): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2579): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/ConnectivityService( 2396): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2579): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2579): updateDataNetType()
D/STATUSBAR-NetworkController( 2579): NoService, mRoamingIconId = 0
,D/dalvikvm( 7572): GC_CONCURRENT freed 2998K, 32% free 9577K/14024K, paused 4ms+3ms, total 36ms
,D/dalvikvm( 7572): WAIT_FOR_CONCURRENT_GC blocked 31ms,
,I/DBG_DM  ( 4726): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected,
,D/libgps  ( 2396): agps_ril_update_network_state: Waiting for IPC connection...,
,I/dalvikvm( 7572): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N,
W/dalvikvm( 7572): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 7572): VFY: replacing opcode 0x6e at 0x0008,
,I/wpa_supplicant( 3969): nl80211: Received scan results (2 BSSes),
I/wpa_supplicant( 3969): wlan0: Setting scan request: 8 sec 0 usec,
D/Tethering( 2396): interfaceLinkStateChanged wlan0, true
D/Tethering( 2396): interfaceStatusChanged wlan0, true,
I/wpa_supplicant( 3969): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3969): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=,
,E/dalvikvm( 7572): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a,
W/dalvikvm( 7572): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7572): VFY: replacing opcode 0x22 at 0x0000,
,E/dalvikvm( 7572): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a,
W/dalvikvm( 7572): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 7572): VFY: replacing opcode 0x22 at 0x0037
,I/wpa_supplicant( 3969): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2396): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2396): interfaceStatusChanged wlan0, true
D/Tethering( 2396): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2396): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3969): Associated with C0.AA.48
D/Tethering( 2396): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2396): interfaceStatusChanged wlan0, true,
I/wpa_supplicant( 3969): freq(2412) increment count 2
,I/wpa_supplicant( 3969): meet head of list.
,I/wpa_supplicant( 3969): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3969): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3969): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3969): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3969): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2396): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2396): interfaceStatusChanged wlan0, true
W/dalvikvm( 7572): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7572): Link of class 'Ldqp;' failed
,W/dalvikvm( 7572): VFY: unable to find class referenced in signature (Ldqp;)
D/WifiNative( 2396): callSECApiVoid - ID [50]
W/dalvikvm( 7572): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7572): Link of class 'Ldqp;' failed
I/dalvikvm( 7572): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 7572): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 7572): VFY: replacing opcode 0x6e at 0x0000
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,E/dalvikvm( 7572): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7572): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7572): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 7572): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7572): Link of class 'Ldqp;' failed
,W/dalvikvm( 7572): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7572): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7572): Link of class 'Ldqp;' failed
I/dalvikvm( 7572): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 7572): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
,D/dalvikvm( 7572): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 7572): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 7572): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
,D/dalvikvm( 7572): VFY: replacing opcode 0x1c at 0x0026
,W/dalvikvm( 7572): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 7572): Link of class 'Ldqp;' failed
,W/dalvikvm( 7572): VFY: unable to find class referenced in signature (Ldqp;)
,W/dalvikvm( 7572): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;),
W/dalvikvm( 7572): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7572): Link of class 'Ldqp;' failed
I/dalvikvm( 7572): Could not find method dqp.d, referenced from method g.a
,W/dalvikvm( 7572): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
,D/dalvikvm( 7572): VFY: replacing opcode 0x6e at 0x0003
,W/dalvikvm( 7572): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7572): Link of class 'Lax;' failed
E/dalvikvm( 7572): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 7572): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
,D/dalvikvm( 7572): VFY: replacing opcode 0x22 at 0x0006,
W/dalvikvm( 7572): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7572): Link of class 'Laz;' failed
E/dalvikvm( 7572): Could not find class 'az', referenced from method g.a
W/dalvikvm( 7572): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
D/dalvikvm( 7572): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 7572): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 7572): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7572): VFY: replacing opcode 0x6e at 0x0008
,I/dalvikvm( 7572): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
W/dalvikvm( 7572): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 7572): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 7572): Could not find method android.view.View.getTransitionName, referenced from method g.a
,W/dalvikvm( 7572): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7572): VFY: replacing opcode 0x6e at 0x0006
,I/dalvikvm( 7572): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 7572): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
,D/dalvikvm( 7572): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 7572): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 7572): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
,D/dalvikvm( 7572): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7572): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
W/dalvikvm( 7572): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
,D/dalvikvm( 7572): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7572): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 7572): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 7572): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 7572): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 7572): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 7572): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 7572): VFY: replacing opcode 0x23 at 0x0005
,I/dalvikvm( 7572): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
,W/dalvikvm( 7572): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7572): VFY: replacing opcode 0x6e at 0x0009
,D/WifiP2pService( 2396): InactiveState{ what=143375 }
,D/WifiP2pService( 2396): P2pEnabledState{ what=143375 }
,W/dalvikvm( 7572): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
W/dalvikvm( 7572): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 7572): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 7572): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
,D/dalvikvm( 7572): VFY: replacing opcode 0x1c at 0x0002
E/dalvikvm( 7572): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 7572): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 7572): VFY: replacing opcode 0x1f at 0x000c
,D/dalvikvm( 7572): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7572): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7572): VFY: replacing opcode 0x62 at 0x0006
,D/dalvikvm( 7572): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7572): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
,D/dalvikvm( 7572): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7572): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
,D/dalvikvm( 7572): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
W/dalvikvm( 7572): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7572): Link of class 'Lax;' failed
D/dalvikvm( 7572): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 7572): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7572): Link of class 'Laz;' failed
,D/dalvikvm( 7572): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 7572): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
,D/dalvikvm( 7572): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,D/dalvikvm( 7572): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x42315208
,D/dalvikvm( 7572): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x42315208
,I/dalvikvm( 7572): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
W/dalvikvm( 7572): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 7572): VFY: replacing opcode 0x6e at 0x0076
,I/Babel_SMS( 7572): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7572): MmsConfig.loadMmsSettings
I/Babel_SMS( 7572): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/Babel_SMS( 7572): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7572): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7572): MmsConfig.loadFromResources
,E/Babel_SMS( 7572): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7572): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
I/dhcpcd  ( 7586): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7586): bssid match
,W/dalvikvm( 7572): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7572): Link of class 'Lfzc;' failed
,E/dalvikvm( 7572): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 7572): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
,D/dalvikvm( 7572): VFY: replacing opcode 0x22 at 0x0033
,W/dalvikvm( 7572): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7572): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7572): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
,W/dalvikvm( 7572): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,I/dalvikvm( 7572): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 7572): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
,D/dalvikvm( 7572): VFY: replacing opcode 0x74 at 0x006d
,I/dalvikvm( 7572): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 7572): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
,D/dalvikvm( 7572): VFY: replacing opcode 0x6e at 0x0033
I/dalvikvm( 7572): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 7572): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
,D/dalvikvm( 7572): VFY: replacing opcode 0x6e at 0x0030
,W/dalvikvm( 7572): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7572): Link of class 'Lfzc;' failed
,D/dalvikvm( 7572): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
E/SensorService( 2396): Permission Denial : SEC Private Sensor 
,E/SensorService( 2396): Permission Denial : SEC Private Sensor 
,D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,W/Settings( 7572): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7572): startup - clean
,I/PowerManagerService( 2396): [PWL] Off : 140s ago
I/PowerManagerService( 2396): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2396): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2396): [PWL]       PARTIAL_WAKE_LOCK              'GpsLocationProvider' (uid=1000, pid=2396, ws=null) (elapsedTime=791)
,I/PowerManagerService( 2396): [PWL]       PARTIAL_WAKE_LOCK              'DHCP' (uid=1000, pid=2396, ws=null) (elapsedTime=413)
,D/dalvikvm( 7572): GC_CONCURRENT freed 1796K, 24% free 10856K/14100K, paused 4ms+5ms, total 43ms
,D/dalvikvm( 7572): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 7572): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 7572): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/Babel   ( 7572): deleted: false for 0
I/dalvikvm( 7572): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
W/dalvikvm( 7572): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7572): VFY: replacing opcode 0x6e at 0x000d
,W/dalvikvm( 7572): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
I/dalvikvm( 7572): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 7572): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
,D/dalvikvm( 7572): VFY: replacing opcode 0x6e at 0x004e
,W/dalvikvm( 7572): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7572): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,E/dalvikvm( 7572): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 7572): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
,D/dalvikvm( 7572): VFY: replacing opcode 0x22 at 0x0071
,W/dalvikvm( 7572): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7572): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7572): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7572): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7572): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 7572): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
,D/dalvikvm( 7572): VFY: replacing opcode 0x1f at 0x0021
,W/dalvikvm( 7572): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 7572): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
,I/PCWCLIENTTRACE_PushUtil( 6604): SPPPushClient is installed : true,
I/PCWCLIENTTRACE_PushUtil( 6604): sales region : global,
I/PCWCLIENTTRACE_PushUtil( 6604): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6604): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE,
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6604): noConnectivity : true,
I/dalvikvm( 7572): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
,W/dalvikvm( 7572): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
,D/dalvikvm( 7572): VFY: replacing opcode 0x6e at 0x0074
,I/ActivityManager( 2396): Killing 6298:com.sec.phone/1001 (adj 15): empty #43
,I/vclib   ( 7572): onServiceConnected
,W/Babel   ( 7572): Attempted to change video mute state without an active call.,
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 340, Delta = 20,
,D/libgps  ( 2396): agps_ril_update_network_state: Waiting for IPC connection - timeout,
E/libgps  ( 2396): LIBGPS: Cannot communicate (write) with a GPSD,
E/libgps  ( 2396): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state,
,D/libgps  ( 2396): agps_ril_update_network_availability: Waiting for IPC connection...
,I/SELinux ( 7604): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7604):  
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2396): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2396): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3997): Disconnected process message: 10
I/SELinux ( 7604): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7604):  
I/SELinux ( 7604):  
I/SELinux ( 7604): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7604): [DEBUG] seapp_context_lookup: seinfoCategory = release
,E/dalvikvm( 7604): >>>>> Normal User
E/dalvikvm( 7604): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7604): [DEBUG] seapp_context_lookup: seinfoCategory = release,
D/STATUSBAR-IconMerger( 2579): checkOverflow(336), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/dalvikvm( 7572): GC_CONCURRENT freed 987K, 18% free 11896K/14348K, paused 5ms+3ms, total 57ms
D/dalvikvm( 7572): WAIT_FOR_CONCURRENT_GC blocked 39ms,
,D/TimaKeyStoreProvider( 7604): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7604): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7604): Added TimaKesytore provider,
,D/dalvikvm( 7572): GC_FOR_ALLOC freed 494K, 18% free 12398K/15116K, paused 38ms, total 38ms,
,D/dalvikvm( 7604): GC_CONCURRENT freed 3007K, 32% free 9566K/14024K, paused 4ms+2ms, total 31ms,
,D/dalvikvm( 7604): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 7572): GC_FOR_ALLOC freed 1759K, 24% free 12769K/16700K, paused 37ms, total 37ms,
,I/ActivityManager( 2396): Killing 5552:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SELinux ( 7617): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7617):  
,I/SELinux ( 7617): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7617):  
I/SELinux ( 7617):  
,I/SELinux ( 7617): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7617): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7617): >>>>> Normal User,
,E/dalvikvm( 7617): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ],
,E/SELinux ( 7617): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,D/TimaKeyStoreProvider( 7617): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7617): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7617): Added TimaKesytore provider,
,D/dalvikvm( 7617): GC_CONCURRENT freed 2987K, 32% free 9573K/14016K, paused 4ms+2ms, total 27ms,
,D/dalvikvm( 7617): WAIT_FOR_CONCURRENT_GC blocked 21ms,
,D/KLMS-2.3.201 : ( 7617): KLMSValidator() : checkQATesting(),
,I/KLMS-2.3.201 : ( 7617): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450240903864,
,I/KLMS-2.3.201 : ( 7617): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false,
,I/ActivityManager( 2396): Killing 6321:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43,
,E/Watchdog( 2396): !@Sync 11,
,I/SELinux ( 7629): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7629):  
,I/SELinux ( 7629): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7629):  
I/SELinux ( 7629):  
,I/SELinux ( 7629): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7629): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7629): >>>>> Normal User
,E/dalvikvm( 7629): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7629): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7629): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7629): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7629): Added TimaKesytore provider
,D/dalvikvm( 7629): GC_CONCURRENT freed 2997K, 32% free 9566K/14016K, paused 4ms+2ms, total 36ms
,D/dalvikvm( 7629): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/SO_AGENT( 7629): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7629): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5769): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5769): [BDLM] already registered in spp
,I/SA      ( 5769): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5769): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5769): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5769): [OR] == isSIMCardReady false ==
I/SA      ( 5769): [SCU] == networkStateCheck == false
,I/SA      ( 5769): [OR] onReceive END
D/libgps  ( 2396): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2396): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2396): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
I/ActivityManager( 2396): Killing 5956:com.android.calendar/u0a144 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5792): Other Intent
,I/SELinux ( 7659): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7659):  
,D/PackageManager( 2396): [MSG] WRITE_PACKAGE_RESTRICTIONS,
,I/SELinux ( 7659): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7659):  
I/SELinux ( 7659):  
,I/SELinux ( 7659): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7659): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7659): >>>>> Normal User
,E/dalvikvm( 7659): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7659): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/WifiP2pService( 2396): InactiveState{ what=143375 },
,D/WifiP2pService( 2396): P2pEnabledState{ what=143375 }
,D/TimaKeyStoreProvider( 7659): in addTimaSignatureService
,D/WifiStateMachine( 2396): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/TimaKeyStoreProvider( 7659): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7659): Added TimaKesytore provider
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2396): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2396): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2396): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2396): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2396): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2396): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2396): evaluateTrafficStatsPolling
D/ConnectivityService( 2396): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2396): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2396): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/ConnectivityService( 2396): handleConnectivityChange: setting default proxy info 
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,D/dalvikvm( 7659): GC_CONCURRENT freed 2994K, 32% free 9578K/14024K, paused 6ms+2ms, total 47ms
,D/dalvikvm( 7659): WAIT_FOR_CONCURRENT_GC blocked 28ms
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/NtpTrustedTime( 2396): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2396): currentTimeMillis() cache hit
V/NetworkStats( 2396): updateIfacesLocked()
,V/NetworkStats( 2396): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2396): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2396): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2396): currentTimeMillis() cache hit
V/NetworkStats( 2396): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2396): currentTimeMillis() cache hit
V/NetworkStats( 2396): performPollLocked() took 19ms
,D/com.samsung.app( 7659): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7659): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7659): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7659): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7659): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7659): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/NtpTrustedTime( 2396): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2396): currentTimeMillis() cache hit
,D/daemonapp( 5305): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7659): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5305): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7659): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5305): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7659): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7659): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2396): Killing 6131:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/Headlines( 5837): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5837): getCountryCode(): countryCode = PL
,D/Headlines( 5837): Breath.onCreate
,D/Headlines( 5837): Breath timer started. interval : 30000
,I/SELinux ( 7689): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7689):  
,D/Headlines( 5837): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5837): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5837): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5837): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5837): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5837): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5837): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7689): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7689):  
I/SELinux ( 7689):  
,I/SELinux ( 7689): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7689): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7689): >>>>> Normal User
,E/dalvikvm( 7689): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7689): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7689): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7689): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7689): Added TimaKesytore provider
,D/dalvikvm( 7689): GC_CONCURRENT freed 2998K, 32% free 9573K/14020K, paused 4ms+2ms, total 31ms
,D/dalvikvm( 7689): WAIT_FOR_CONCURRENT_GC blocked 18ms
,V/WebViewChromium( 7689): Binding Chromium to the background looper Looper (main, tid 1) {422bbf58}
,I/chromium( 7689): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7689): Initializing chromium process, renderers=0
,W/chromium( 7689): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7689): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7689): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7689): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7689): Mali API Version : 401
,I/Mali    ( 7689): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/Tethering( 2396): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2396): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2396): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2579): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2579): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2579): updateDataNetType()
D/STATUSBAR-NetworkController( 2579): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4726): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/libgps  ( 2396): agps_ril_update_network_state: Waiting for IPC connection...
,W/GAV2    ( 7689): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7689): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,I/NSApplication( 7689): Starting up...
,I/iu.Environment( 5902): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5107): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5107): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5107): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422c77f8
,I/SELinux ( 7729): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7729):  
,I/SELinux ( 7729): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7729):  
I/SELinux ( 7729):  
I/SELinux ( 7729): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7729): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7729): >>>>> Normal User
E/dalvikvm( 7729): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7729): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7729): in addTimaSignatureService
,D/dalvikvm( 2396): GC_CONCURRENT freed 4476K, 58% free 25416K/59236K, paused 13ms+21ms, total 250ms
,D/TimaKeyStoreProvider( 7729): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7729): Added TimaKesytore provider
,D/dalvikvm( 7729): GC_CONCURRENT freed 2984K, 32% free 9582K/14020K, paused 4ms+2ms, total 37ms
,D/dalvikvm( 7729): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/RCPManagerService( 2396): exchangeData() failure , invalid userId
,D/RCPManagerService( 2396): exchangeData() failure , invalid userId
,D/RCPManagerService( 2396): exchangeData() failure , invalid userId
,D/RCPManagerService( 2396): exchangeData() failure , invalid userId
,I/SELinux ( 7748): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7748):  
,D/RCPManagerService( 2396): exchangeData() failure , invalid userId
,D/RCPManagerService( 2396): exchangeData() failure , invalid userId
W/ActivityManager( 2396): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager( 2396): Killing 6170:com.google.android.music:main/u0a125 (adj 15): empty #43
,I/SELinux ( 7748): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7748):  
I/SELinux ( 7748):  
,I/SELinux ( 7748): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7748): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7748): >>>>> Normal User
,E/dalvikvm( 7748): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7748): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 7758): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7758):  
,D/TimaKeyStoreProvider( 7748): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7748): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7748): Added TimaKesytore provider
,I/ActivityManager( 2396): Killing 6200:com.android.defcontainer/u0a6 (adj 15): empty #43
,I/SELinux ( 7758): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7758):  
I/SELinux ( 7758):  
,I/SELinux ( 7758): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7758): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/AmoledAdjustTimer( 2396): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
E/dalvikvm( 7758): >>>>> Normal User
E/dalvikvm( 7758): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
E/SELinux ( 7758): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,I/jxcore-log( 7497): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 7497): 
,D/TimaKeyStoreProvider( 7758): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7758): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7758): Added TimaKesytore provider
,D/dalvikvm( 7748): GC_CONCURRENT freed 2988K, 32% free 9577K/14020K, paused 4ms+2ms, total 35ms
,D/dalvikvm( 7748): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/BadgeProvider( 7748): onCreate
,D/BadgeProvider( 7748): DatabaseHelper
,D/libgps  ( 2396): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2396): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2396): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2396): agps_ril_update_network_availability: Waiting for IPC connection...
,D/BadgeProvider( 7748): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 2776): reloadBadges entered.
D/BadgeProvider( 7748): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7748): sendNotify, [notify] : null
D/BadgeProvider( 7748): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7748): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7748): update, [UpdateCount] : 1
,D/dalvikvm( 7758): GC_CONCURRENT freed 2992K, 32% free 9577K/14024K, paused 4ms+2ms, total 34ms
,D/dalvikvm( 7758): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/WaitQueueForNetworkActivate( 6794): notifyNetworkActivated
,W/ContextImpl( 6794): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager( 2396): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/System.out( 7572): Thread-650(HTTPLog):isShipBuild true
,I/System.out( 7572): Thread-650(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/Babel   ( 7572): connection state changed from UNKNOWN to CONNECTED
,D/hcjo    ( 6794): AutoUpdateManager:IDLE:execute
,I/dalvikvm( 6794): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
W/dalvikvm( 6794): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 6794): VFY: replacing opcode 0x6e at 0x0024
,D/InitializeManagerStateMachine( 6794): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6794): exit::IDLE
,D/InitializeManagerStateMachine( 6794): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 6794): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6794): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6794): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6794): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6794): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6794): entry::SUCCESS
,D/hcjo    ( 6794): AutoUpdateManager:INITCHECK:onInitializeSuccess
,E/SPPClientService( 5505): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5505): [SystemStateMoniter] Current Time : 350860
E/SPPClientService( 5505): [SystemStateMoniter] No Connect : true
D/hcjo    ( 6794): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6794): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6794): exit::SUCCESS
,D/InitializeManagerStateMachine( 6794): entry::IDLE
,E/SPPClientService( 5505): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 2830): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2830): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2830): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2830): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2830): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2830): MountReceiver.onReceive - Keep current state
I/ActivityManager( 2396): Killing 6450:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,E/SPPClientService( 5505): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5505): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 2830): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2830): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 2830): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2830): DMSUtil.isNetworkConnected - flag-null, state-null
E/SPPClientService( 5505): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,I/NearbySettings( 2830): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2830): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2830): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2830): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5505): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/SurfaceFlinger( 1920): id=22 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 2396): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2396
,D/NearbySettings( 2830): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2830): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5505): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,I/PCWCLIENTTRACE_PushUtil( 6604): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6604): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6604): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6604): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5505): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5505): [g] getNetMCC return empty string
,I/KLMS-2.3.201 : ( 7617): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/libgps  ( 2396): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2396): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2396): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/KLMS-2.3.201 : ( 7617): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450240907273
,I/KLMS-2.3.201 : ( 7617): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7629): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3297): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/GalaxyFinderApplication( 3297): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3297): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3297): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7629): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 3425): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7786): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7786):  
,I/System.out( 7604): Thread-642(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/SELinux ( 7786): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7786):  
I/SELinux ( 7786):  
,I/SELinux ( 7786): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7786): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7786): >>>>> Normal User
,E/dalvikvm( 7786): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7786): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 5769): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5769): [BDLM] already registered in spp
,I/SA      ( 5769): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
I/SA      ( 5769): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/System.out( 7604): Thread-642(ApacheHTTPLog):isShipBuild true
,I/System.out( 7604): Thread-642(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/SA      ( 5769): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5769): [OR] == isSIMCardReady false ==
I/SA      ( 5769): [SCU] == networkStateCheck == true
I/SA      ( 5769): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5769): isChinaCountryCode : false
,I/SA      ( 5769): [OR] == networkStateCheck true ==
,I/SA      ( 5769): [OR] GetMyCountryZoneTask
,I/SA      ( 5769): [OR] onReceive END
,I/SA      ( 5769): [SRS] prepareGetMyCountryZone
,D/TimaKeyStoreProvider( 7786): in addTimaSignatureService
I/SA      ( 5769): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5769): [SSP] query invoked
,I/SA      ( 5769): [TPMU] GetMccFromDB : null
I/SA      ( 5769): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5769): [TPM] isNoProxy(default) : true
,I/SA      ( 5769): [RC New] Execute method=[GET] start
,D/TimaKeyStoreProvider( 7786): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7786): Added TimaKesytore provider
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5792): Other Intent
,D/com.samsung.app( 7659): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7659): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5837): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5837): getCountryCode(): countryCode = PL
,D/Headlines( 5837): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5837): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5837): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5837): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5837): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5837): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5837): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 5902): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/dalvikvm( 7786): GC_CONCURRENT freed 3001K, 32% free 9568K/14020K, paused 3ms+2ms, total 36ms
,D/dalvikvm( 7786): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/QuickConnect[1.1][2] ( 5107): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5107): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5107): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422c77f8
,I/System.out( 7604): AsyncTask #1 calls detatch(),
D/RCPManagerService( 2396): exchangeData() failure , invalid userId
,D/RCPManagerService( 2396): exchangeData() failure , invalid userId,
,W/System.err( 7604): com.sec.android.fota.osp.http.RestClientException,
W/System.err( 7604): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7604): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7604): ,	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7604): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7604): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7604): ,	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7604): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7604): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7604): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 7604): Caused by: java.lang.NullPointerException,
V/KVNProvider( 7786): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
W/System.err( 7604): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7604): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
V/KVNProvider( 7786): getFindoCursor query string : 
W/System.err( 7604): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7604): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7604): ,	... 8 more
,D/hcjo    ( 6794): AutoUpdateManager:IDLE:execute,
D/InitializeManagerStateMachine( 6794): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6794): exit::IDLE
,D/InitializeManagerStateMachine( 6794): entry::NETWORK_CHECK,
D/InitializeManagerStateMachine( 6794): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6794): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6794): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6794): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6794): exit::CHECK_COUNTRY_INFO,
D/InitializeManagerStateMachine( 6794): entry::SUCCESS
,D/hcjo    ( 6794): AutoUpdateManager:INITCHECK:onInitializeSuccess,
,D/hcjo    ( 6794): AutoUpdateTriggerManager:IDLE:notifyNextTime,
,D/hcjo    ( 6794): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime,
,V/KVNProvider( 7786): getTagSearchCursor() tagSearchCursor count : 0
,D/InitializeManagerStateMachine( 6794): exit::SUCCESS
,D/InitializeManagerStateMachine( 6794): entry::IDLE
,E/WifiStateMachine( 2396): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/SPPClientService( 5505): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5505): [SystemStateMoniter] Current Time : 351950
,E/SPPClientService( 5505): [SystemStateMoniter] No Connect : false
,D/dalvikvm( 5505): GC_CONCURRENT freed 1910K, 26% free 10460K/14012K, paused 4ms+5ms, total 49ms
,I/SA      ( 5769): [RC New] [v2liruge] api execute + 981
,I/SA      ( 5769): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5769): AsyncTask #2 calls detatch()
,I/SA      ( 5769): [TPMU] getNetworkMcc : 
,I/SA      ( 5769): [SCU] saveMccToPreferece Start
,I/SA      ( 5769): [SCU] RegionMCC : 260
,I/SA      ( 5769): [SSP] query invoked
,I/SA      ( 5769): [TPMU] GetMccFromDB : null
,I/SA      ( 5769): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5769): [SCU] saveMccToPreferece End
I/SA      ( 5769): [RC New] executeRequest [v2liruge] end. 1005
I/SA      ( 5769): [RC New] Execute end
I/SA      ( 5769): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5769): [OR] GetMyCountryZoneTask Success
,I/jxcore-log( 7497): Connected to the server!
I/jxcore-log( 7497): 
,I/chromium( 7497): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,W/WifiP2pStateTracker( 2396): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2396): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2396):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2396): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2396): updateSourceRoutes : no source routing conditions
,E/SPPClientService( 5505): [b] __InitReply__
,V/AlarmManager( 2396): waitForAlarm result :4
,V/AlarmManager( 2396): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 7815): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7815):  
,I/SELinux ( 7815): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7815):  
I/SELinux ( 7815):  
,I/SELinux ( 7815): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7815): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7815): >>>>> Normal User
,E/dalvikvm( 7815): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 7815): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 7815): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7815): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7815): Added TimaKesytore provider
,D/dalvikvm( 7815): GC_CONCURRENT freed 2999K, 32% free 9566K/14016K, paused 4ms+3ms, total 35ms
,D/dalvikvm( 7815): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/Headlines( 5837): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5837): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5837): Breath 1784 latestRequest time : 1450240907611 current time : 1450240909396
,I/ActivityManager( 2396): Killing 6574:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/GAV2    ( 7689): Thread[GAThread,5,main]: No campaign data found.,
,I/SurfaceFlinger( 1920): id=22 Removed Uoast (10/11)
,I/SurfaceFlinger( 1920): id=22 Removed Uoast (-2/11),
I/ActivityManager( 2396): Killing 6590:com.android.musicfx/u0a24 (adj 15): empty #43
,D/PowerManagerService( 2396): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2396) eventTime = 354553,
,D/PowerManagerService( 2396): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2396 (0x0)
,D/PowerManagerService( 2396): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2396, ws=WorkSource{1000}) (elapsedTime=3483)
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6604): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil( 6604): [hasSamungAccount] - No Samsung Account,
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6604): failed to loading secure library
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6604): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6604): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6604): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6604): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6604): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6604): [ensureRegistration] - No Samsung account
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 330, Delta = -10,
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2396): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2396): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/CaptivePortalTracker( 2396): DelayedCaptiveCheckState{ when=-4ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
D/ConnectivityService( 2396): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2396): Checking http://216.58.209.46/generate_204,
,D/CaptivePortalTracker( 2396): Don't send network conditions - lacking user consent.,
,D/CaptivePortalTracker( 2396): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 2396): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2396): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
D/ConnectivityService( 2396): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/AmoledAdjustTimer( 2396): prevTemp = 300, currTemp = 301, prevStep = 4, currStep = 4,
,D/PreloadUpdateManagerStateMachine( 6794): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 6794): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6794): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 6794): AutoUpdateTriggerManager:IDLE:notifyNextTime,
,D/PreloadUpdateManagerStateMachine( 6794): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 6794): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6794): entry::IDLE,
,D/PreloadUpdateManagerStateMachine( 6794): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 6794): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6794): entry::CHECK_TIMEOUT_FOR_UPDATE,
,D/hcjo    ( 6794): AutoUpdateTriggerManager:IDLE:notifyNextTime,
,D/PreloadUpdateManagerStateMachine( 6794): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 6794): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6794): entry::IDLE,
,W/ContextImpl( 2396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/ActivityManager( 2396): Waited long enough for: ServiceRecord{43098ec8 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,V/AlarmManager( 2396): waitForAlarm result :8,
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,I/ActivityManager( 2396): Waited long enough for: ServiceRecord{44072130 u0 com.sec.spp.push/.PushClientService},
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2396): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2396): stay LED for fully charged
,D/UiModeManager( 2396): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2396): !@Sync 12,
,V/AlarmManager( 2396): waitForAlarm result :8,
,D/Headlines( 5837): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5837): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5837): Breath 27139 latestRequest time : 1450240907611 current time : 1450240934750,
,D/AmoledAdjustTimer( 2396): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4,
,W/ContextImpl( 2396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2396): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2396): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2396): mCoverManager.getCoverState() : true
,D/BatteryService( 2396): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2396): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4
,W/ContextImpl( 2396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2396): !@Sync 13
,V/AlarmManager( 2396): waitForAlarm result :8
,D/Headlines( 5837): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5837): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5837): Breath 57138 latestRequest time : 1450240907611 current time : 1450240964749
,D/AmoledAdjustTimer( 2396): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2396): mCoverManager.getCoverState() : true
D/BatteryService( 2396): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2396): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,I/PowerManagerService( 2396): [PWL] Off : 225s ago
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2396): !@Sync 14
,V/AlarmManager( 2396): waitForAlarm result :8
,D/Headlines( 5837): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5837): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5837): Breath 87122 latestRequest time : 1450240907611 current time : 1450240994733
,D/AmoledAdjustTimer( 2396): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/ProcessCpuTracker( 2396): Skipping unknown process pid 8328
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2396): stay LED for fully charged
,D/UiModeManager( 2396): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2396): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2396): !@Sync 15
,V/AlarmManager( 2396): waitForAlarm result :8
,D/Headlines( 5837): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5837): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5837): Breath 117122 latestRequest time : 1450240907611 current time : 1450241024734
,D/AmoledAdjustTimer( 2396): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,I/PowerManagerService( 2396): [PWL] Off : 275s ago
,W/ContextImpl( 2396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2396): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2396): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2396): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2396): !@Sync 16
,V/AlarmManager( 2396): waitForAlarm result :8
,D/Headlines( 5837): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5837): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
D/Headlines( 5837): Breath 147122 latestRequest time : 1450240907611 current time : 1450241054734
,D/Headlines( 5837): stop 
,D/Headlines( 5837): Breath.onDestroy : 
,I/ActivityManager( 2396): Killing 6616:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,D/AmoledAdjustTimer( 2396): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,W/ContextImpl( 2396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2396): mCoverManager.getCoverState() : true
,D/BatteryService( 2396): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2396): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2396): !@Sync 17
,D/AmoledAdjustTimer( 2396): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,I/PowerManagerService( 2396): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2396): !@Sync 18
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2396): mCoverManager.getCoverState() : true
,D/BatteryService( 2396): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2396): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2396): !@Sync 19
,D/AmoledAdjustTimer( 2396): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,I/PowerManagerService( 2396): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/TimaService( 2396): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2396): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2396): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2396): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2396): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2396): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2396): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2396): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2396): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/dalvikvm( 2396): GC_CONCURRENT freed 3936K, 58% free 25377K/59236K, paused 23ms+19ms, total 265ms
,D/AmoledAdjustTimer( 2396): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2396): mCoverManager.getCoverState() : true
,D/BatteryService( 2396): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2396): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2396): !@Sync 21
,D/AmoledAdjustTimer( 2396): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,I/PowerManagerService( 2396): [PWL] Off : 455s ago
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4051): GC_CONCURRENT freed 2889K, 31% free 9726K/14064K, paused 25ms+3ms, total 101ms
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,I/GAV2    ( 5593): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5593): Thread[disconnect check,5,main]: Disconnected from service
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2396): !@Sync 22
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2396): stay LED for fully charged
,D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2396): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2396): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2396): !@Sync 23
,D/AmoledAdjustTimer( 2396): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2396): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2396): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
V/AlarmManager( 2396): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService( 2396): [PWL] Off : 525s ago
,E/Watchdog( 2396): !@Sync 24
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2396): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2396): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2396): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 25
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 26
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2396): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,D/LightsService( 2396): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK,
I/SensorManagerA( 2396): getReportingMode :: sensor.mType = 5
D/Sensors ( 2396): LightSensor setDelay = 200000000
D/Sensors ( 2396): LightSensor setSensorDelay = 200000000
D/Sensors ( 2396): Light sensor flush: not enabled 0
D/Sensors ( 2396): LightSensor enable = 1
D/Sensors ( 2396): LightSensor enableSensor = 1
D/SensorManager( 2396): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,E/SPPClientService( 5505): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/Sensors ( 2396): LightSensor enable = 0
,D/Sensors ( 2396): LightSensor enableSensor = 0
,D/LightsService( 2396): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2396): unregisterListener ::   
D/LightsService( 2396): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 27
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 28
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2396): mCoverManager.getCoverState() : true
,D/BatteryService( 2396): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2396): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2396): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2396): [PWL] Off : 680s ago
,E/Watchdog( 2396): !@Sync 29
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/TimaService( 2396): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2396): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2396): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2396): !@Sync 30
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 10
,I/TLC_TIMA_PKM_measure_kernel( 2396): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2396): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2396): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2396): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2396): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2396): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 31
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2396): [PWL] Off : 765s ago
,E/Watchdog( 2396): !@Sync 32
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2396): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2396): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 33
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 34
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2396): [PWL] Off : 855s ago
,E/Watchdog( 2396): !@Sync 35
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2396): GC_FOR_ALLOC freed 3930K, 58% free 25414K/59236K, paused 207ms, total 207ms
,D/dalvikvm( 2396): GC_CONCURRENT freed 205K, 58% free 25254K/59236K, paused 9ms+16ms, total 204ms
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 36
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :4
,V/AlarmManager( 2396): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5505): [b] __PingReply__
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 37
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2396): mCoverManager.getCoverState() : true
,D/BatteryService( 2396): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2396): [PWL] Off : 950s ago
,E/Watchdog( 2396): !@Sync 38
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 39
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/TimaService( 2396): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2396): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2396): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2396): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2396): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2396): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2396): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2396): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 41
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2396): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 42
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 43
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2396): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2396): <AppSync3 Whitelist>
,V/AlarmManager( 2396): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 44
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2396): [PWL] Off : 1155s ago
,E/Watchdog( 2396): !@Sync 45
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4051): GC_CONCURRENT freed 2050K, 31% free 9724K/14064K, paused 3ms+2ms, total 42ms
,D/dalvikvm( 4051): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 46
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2396): stay LED for fully charged
,D/UiModeManager( 2396): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2396): !@Sync 47
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2396): stay LED for fully charged
,D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2396): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2396): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2396): mCoverManager.getCoverState() : true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2396): !@Sync 48
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2396): [PWL] Off : 1265s ago
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 49
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/TimaService( 2396): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2396): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2396): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2396): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 2396): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2396): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2396): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2396): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/dalvikvm( 2396): GC_CONCURRENT freed 3771K, 58% free 25338K/59236K, paused 23ms+16ms, total 254ms
,E/Watchdog( 2396): !@Sync 51
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 52
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2396): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 53
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2396): waitForAlarm result :4
,I/SensorManagerA( 2396): getReportingMode :: sensor.mType = 5
,D/LightsService( 2396): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2396): LightSensor setDelay = 200000000
D/Sensors ( 2396): LightSensor setSensorDelay = 200000000
D/Sensors ( 2396): Light sensor flush: not enabled 0
D/Sensors ( 2396): LightSensor enable = 1
D/Sensors ( 2396): LightSensor enableSensor = 1
D/SensorManager( 2396): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2396): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,I/EventLogService( 3155): Aggregate from 1450240385227 (log), 1450240385227 (data)
,D/dalvikvm( 3155): GC_CONCURRENT freed 1842K, 21% free 12558K/15888K, paused 16ms+9ms, total 107ms
,D/Sensors ( 2396): LightSensor enable = 0
,D/Sensors ( 2396): LightSensor enableSensor = 0
D/LightsService( 2396): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2396): unregisterListener ::   
D/LightsService( 2396): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 54
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 55
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 56
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2396): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,E/SPPClientService( 5505): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 57
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 58
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2396): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2396): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2396): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2396): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 59
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/TimaService( 2396): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2396): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2396): TimaServiceHandler.handleMessage what =1
,W/ProcessCpuTracker( 2396): Skipping unknown process pid 12320
,E/Watchdog( 2396): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 2396): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 2396): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2396): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2396): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2396): [PWL] Off : 1625s ago
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 61
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2396): Prepared write state in 59ms
,I/ProcessStatsService( 2396): Prepared write state in 34ms
,I/ProcessStatsService( 2396): Pruning old procstats: /data/system/procstats/state-2015-12-15-18-46-50.bin
,V/AlarmManager( 2396): waitForAlarm result :4
,D/NtpTrustedTime( 2396): currentTimeMillis() cache hit
V/NetworkStats( 2396): performPollLocked(flags=0x3)
,V/AlarmManager( 2396): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2396): currentTimeMillis() cache hit
V/NetworkStats( 2396): performPollLocked() took 52ms
,D/NtpTrustedTime( 2396): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2396): currentTimeMillis() cache hit
,I/SELinux (12473): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12473):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 14% free 9503K/10996K, paused 3ms+4ms, total 43ms
,I/SELinux (12473): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12473):  
I/SELinux (12473):  
,I/SELinux (12473): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (12473): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(12473): >>>>> Normal User
,E/dalvikvm(12473): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (12473): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 14% free 9503K/10996K, paused 3ms+4ms, total 38ms
,D/TimaKeyStoreProvider(12473): in addTimaSignatureService
,D/TimaKeyStoreProvider(12473): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(12473): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 14% free 9503K/10996K, paused 3ms+4ms, total 36ms
,D/dalvikvm(12473): GC_CONCURRENT freed 3014K, 32% free 9556K/14020K, paused 3ms+2ms, total 28ms
,D/dalvikvm(12473): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/@ WidgetProvider(12473): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(12473): onUpdate called for widgetId : 0
,D/@ WidgetProvider(12473): Widget random data : 8
,D/@ WidgetProvider(12473): onUpdate called for widgetId : 5
,D/@ WidgetProvider(12473): Widget random data : 3
E/dalvikvm(12473): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(12473): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12473): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12473): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12473): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12473): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12473): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
,W/dalvikvm(12473): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(12473): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12473): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
,W/dalvikvm(12473): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12473): VFY: replacing opcode 0x22 at 0x0038
I/ActivityManager( 2396): Killing 5975:com.sec.android.app.shealth/u0a36 (adj 15): empty #43
,D/dalvikvm(12473): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
,D/dalvikvm(12473): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(12473): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(12473): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 2845): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 2845): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 2845): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 2845): VFY: replacing opcode 0x1f at 0x0011
I/dalvikvm( 2845): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 2845): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2845): VFY: replacing opcode 0x6e at 0x003d
,I/System.out(12473): Thread-672(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(12473): Thread-672(ApacheHTTPLog):isShipBuild true
,I/System.out(12473): Thread-672(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 2845): Thread-55(HTTPLog):isShipBuild true
,I/System.out( 2845): Thread-55(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 2845): GC_CONCURRENT freed 1885K, 24% free 10850K/14260K, paused 7ms+7ms, total 58ms
,I/System.out(12473): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(12473): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(12473): Max ALLOWED memory (MB): 128
,V/ImageManager(12473): Max SHOULD USE memory (MB): 128
,V/ImageManager(12473): Max Image Cache memory (MB): 32
,D/skia    (12473): getTotalSize : Do not get file length
,D/@ WidgetProvider(12473): Building widget : 5
,D/dalvikvm( 2776): GC_CONCURRENT freed 8253K, 34% free 18901K/28608K, paused 4ms+7ms, total 65ms
,D/dalvikvm( 2776): WAIT_FOR_CONCURRENT_GC blocked 58ms
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2396): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2396): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2396): stay LED for fully charged
,D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2396): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2396): !@Sync 62
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 63
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2396): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2396): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
V/AlarmManager( 2396): (AppSync) ### 0 added ###
,I/ActivityManager( 2396): Killing 6397:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1800s,
,I/ActivityManager( 2396): Killing 6762:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1801s
,I/ActivityManager( 2396): Killing 6748:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1801s
,I/ActivityManager( 2396): Killing 6736:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1802s
,I/ActivityManager( 2396): Killing 6724:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1802s
,I/ActivityManager( 2396): Killing 6711:com.samsung.helphub/1000 (adj 15): empty for 1802s
I/ActivityManager( 2396): Killing 6698:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1802s
,I/ActivityManager( 2396): Killing 6685:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1802s
,I/ActivityManager( 2396): Killing 6672:com.sec.android.service.cm/u0a82 (adj 15): empty for 1802s
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2396): Killing 6355:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1803s
,I/ActivityManager( 2396): Killing 5656:com.android.mms/u0a49 (adj 15): empty for 1803s
,I/ActivityManager( 2396): Killing 6646:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1803s
,D/CountryDetector( 2396): No listener is left
,D/dalvikvm( 2396): GC_CONCURRENT freed 3928K, 58% free 25395K/59236K, paused 19ms+18ms, total 237ms
,D/dalvikvm( 2396): WAIT_FOR_CONCURRENT_GC blocked 190ms
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 64
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2396): [PWL] Off : 1755s ago
,E/Watchdog( 2396): !@Sync 65
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,I/ActivityManager( 2396): Killing 6501:com.google.android.apps.uploader/u0a117 (adj 15): empty for 1807s
,I/ActivityManager( 2396): Killing 6485:com.android.chrome/u0a85 (adj 15): empty for 1807s
,I/ActivityManager( 2396): Killing 6472:com.sec.android.Kies/1000 (adj 15): empty for 1817s
,I/ActivityManager( 2396): Killing 6434:com.sec.knox.bridge/1000 (adj 15): empty for 1850s
,I/ActivityManager( 2396): Killing 4830:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1850s
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2396): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService( 2396): stay LED for fully charged
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 66
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2396): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2396): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2396): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2396): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2396): mCoverManager.getCoverState() : true
,D/BatteryService( 2396): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 67
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 68
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 69
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2396): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2396): waitForAlarm result :8
,V/AlarmManager( 2396): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4051): GC_CONCURRENT freed 2045K, 31% free 9726K/14064K, paused 9ms+3ms, total 31ms
,D/dalvikvm( 4051): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2396): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2396): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2396): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2396): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 70
,I/TLC_TIMA_PKM_measure_kernel( 2396): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 2396): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2396): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2396): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2396): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2396): !@Sync 71
,TIME-OUT KILL (timeout was 1800000ms),D/SSRMv2:SIOP( 2396): SIOP:: AP = 310, Delta = 0
D/AndroidRuntime(13280): 
D/AndroidRuntime(13280): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(13280): CheckJNI is OFF
D/AndroidRuntime(13280): setted country_code = Poland
D/AndroidRuntime(13280): setted countryiso_code = PL
D/AndroidRuntime(13280): setted sales_code = PLS
D/AndroidRuntime(13280): readGMSProperty: start
D/AndroidRuntime(13280): readGMSProperty: already setted!!
D/AndroidRuntime(13280): readGMSProperty: end
D/AndroidRuntime(13280): addProductProperty: start
D/dalvikvm(13280): Trying to load lib libjavacore.so 0x0
D/dalvikvm(13280): Added shared lib libjavacore.so 0x0
D/dalvikvm(13280): Trying to load lib libnativehelper.so 0x0
D/dalvikvm(13280): Added shared lib libnativehelper.so 0x0
D/dalvikvm(13280): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack(13280): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug(13280): failed to load memtrack module: -2
D/dalvikvm(13280): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime(13280): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2396): START PACKAGE DELETE: observer{1120773192}
D/PackageManager( 2396): pkg{<packageName>}
D/PackageManager( 2396): user{0}
D/PackageManager( 2396): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2396): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2396): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2396): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2396): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 2396): !@killApplicatoin: 10556, uninstall pkg
I/ActivityManager( 2396): Killing 7497:com.test.thalitest/u0a556 (adj 0): stop com.test.thalitest
I/ActivityManager( 2396): Killing 7748:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1800s
D/CustomFrequencyManagerService( 2396): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2396  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2396): mDVFSHelper.acquire()
I/SurfaceFlinger( 1920): id=21 Removed NainActivit (8/10)
I/WindowState( 2396): WIN DEATH: Window{43049410 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1920): id=21 Removed NainActivit (-2/10)
D/PointerIcon( 2396): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2396): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2396): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2396): setHoveringSpenCustomIcon IconType is same.1
W/PackageSettings( 2396): Skipping PackageSetting{423fc1f0 com.example.hello/10551} due to missing metadata
D/PackageManager( 2396): setPackageStoppedState - Execution time: 114 ms
D/PackageManager( 2396): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10556, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/ActivityManager( 2396): Killing 2830:com.android.settings/1000 (adj 15): empty for 1800s
I/ActivityManager( 2396): Killing 6604:com.sec.pcw.device/1000 (adj 15): empty for 1800s
I/DBG_DM  ( 4726): [3.19.140541][Line:408][onResume] 
D/dalvikvm( 6420): GC_EXPLICIT freed 573K, 30% free 9985K/14100K, paused 3ms+4ms, total 43ms
I/FPMS_FingerprintManagerService( 2599): onReceive: android.intent.action.PACKAGE_REMOVED
I/DBG_DM  ( 4726): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
E/SamsungIME( 2959): mOCRHelper is null
D/QuickConnect[1.1][2] ( 5107): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/DBG_DM  ( 4726): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
I/DBG_DM  ( 4726): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
I/DBG_DM  ( 4726): [3.19.140541][Line:418][onResume] Postpone Count : 26
I/DBG_DM  ( 4726): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
D/dalvikvm( 2972): GC_EXPLICIT freed 1469K, 29% free 10037K/14016K, paused 24ms+7ms, total 110ms
I/DBG_DM  ( 4726): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
I/InputReader( 2396): Reconfiguring input devices.  changes=0x00000010
I/SELinux (13309): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13309):  
I/DBG_DM  ( 4726): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
W/GeofencerStateMachine( 2734): Ignoring removeGeofence because network location is disabled.
I/SELinux (13309): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13309):  
I/SELinux (13309):  
I/SELinux (13309): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13309): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13309): >>>>> Normal User
E/dalvikvm(13309): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux (13309): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 3155): GC_EXPLICIT freed 418K, 22% free 12483K/15888K, paused 12ms+73ms, total 192ms
D/PackageManager( 2396): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10556, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/RegisteredServicesCache( 2756): empty dynamic service
D/TimaKeyStoreProvider(13309): in addTimaSignatureService
I/DBG_DM  ( 4726): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
I/DBG_DM  ( 4726): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
I/DBG_DM  ( 4726): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
I/DBG_DM  ( 4726): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4726): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
I/DBG_DM  ( 4726): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
I/DBG_DM  ( 4726): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
D/TimaKeyStoreProvider(13309): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13309): Added TimaKesytore provider
D/dalvikvm( 2396): GC_EXPLICIT freed 3382K, 58% free 24976K/59236K, paused 8ms+40ms, total 255ms
I/ActivityManager( 2396): Killing 7617:com.samsung.klmsagent/u0a18 (adj 15): empty for 1800s
I/PackageManager( 2396):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2396):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2396):   Scheme: "sms"
I/ActivityManager( 2396): Killing 7604:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1800s
I/ActivityManager( 2396): Killing 5708:com.sec.android.diagmonagent/1000 (adj 15): empty for 1800s
I/PackageManager( 2396): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/ActivityManager( 2396): Killing 5694:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1800s
D/Activity( 4726): setTransGradationMode to true
D/PhoneStatusBar( 2579): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2396): semi p:4726,o:t
D/dalvikvm( 2396): WAIT_FOR_CONCURRENT_GC blocked 14ms
I/PackageManager( 2396):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2396):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2396):   Scheme: "smsto"
I/PackageManager( 2396): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2396):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2396):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2396):   Scheme: "mms"
I/PackageManager( 2396): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/DBG_DM  ( 4726): [3.19.140541][Line:400][onPause] 
D/RCPManagerService( 2396): PackageReceiver onReceive()
I/HarmonyEASService( 2396): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/SurfaceFlinger( 1920): id=23 createSurf (720x1280),2 flag=404, YUIInstallC
I/PackageManager( 2396):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2396):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2396):   Scheme: "mmsto"
I/PackageManager( 2396): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/STATUSBAR-StatusBarManagerService( 2396): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2396): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2396): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2396): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2396): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2396): setHoveringSpenCustomIcon IconType is same.1
I/PackageManager( 2396):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2396):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2396):   Scheme: "sms"
I/PackageManager( 2396): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(13309): GC_CONCURRENT freed 3014K, 32% free 9560K/14024K, paused 2ms+1ms, total 54ms
D/dalvikvm(13309): WAIT_FOR_CONCURRENT_GC blocked 51ms
W/ContextImpl( 2396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 2396): Got RemoteException sending setActive(false) notification to pid 7497 uid 10556
I/ActivityManager( 2396): Killing 6630:com.policydm/1000 (adj 15): empty for 1800s
I/ActivityManager( 2396): Killing 7629:com.sec.android.soagent/u0a38 (adj 15): empty for 1800s
I/ActivityManager( 2396): Killing 7544:com.vlingo.midas/u0a34 (adj 15): empty for 1800s
I/PackageManager( 2396):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2396):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2396):   Scheme: "smsto"
I/PackageManager( 2396): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/CustomFrequencyManagerService( 2396): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2396  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2396): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2396): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2396  pkgName : ACTIVITY_RESUME_BOOSTER@8
I/PackageManager( 2396):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2396):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2396):   Scheme: "mms"
I/PackageManager( 2396): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2396):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2396):   Category: "android.intent.category.DEFAULT"
D/elm:14132(13309): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
I/PackageManager( 2396):   Scheme: "mmsto"
D/elm:14132(13309): ELMEngine.ELMEngine( context ).
I/PackageManager( 2396): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132(13309): MDMBridge.setEnterpriseBridge()
D/EnterpriseDeviceManagerService( 2396): Package has changed for user 0
D/elm:14132(13309): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132(13309): ElmAgentService : onCreate()
D/elm:14132(13309): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132(13309): MainReceiver.listeningToPackageRemoved()
D/elm:14132(13309): MDMBridge.getInstance()
D/elm:14132(13309): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132(13309): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux (13323): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13323):  
D/dalvikvm( 2756): GC_CONCURRENT freed 2339K, 27% free 10258K/14044K, paused 13ms+2ms, total 110ms
I/SELinux (13323): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13323):  
I/SELinux (13323):  
I/SELinux (13323): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13323): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13323): >>>>> Normal User
E/dalvikvm(13323): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux (13323): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/elm:14132(13309): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/TimaKeyStoreProvider(13323): in addTimaSignatureService
W/Resources( 2396): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider(13323): Cannot add TimaSignature Service, License check Failed
D/elm:14132(13309): ElmAgentService : onDestroy().
D/ActivityThread(13323): Added TimaKesytore provider
I/ActivityManager( 2396): Killing 6311:com.sec.android.app.videoplayer/u0a53 (adj 15): empty for 1800s
D/dalvikvm( 2396): GC_EXPLICIT freed 944K, 58% free 25051K/59236K, paused 11ms+50ms, total 393ms
W/Resources( 2396): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/AmoledAdjustTimer( 2396): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
D/BackupManagerService( 2396): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 2396): removePackageParticipantsLocked: uid=10556 #1
D/dalvikvm(13323): GC_CONCURRENT freed 2994K, 32% free 9569K/14016K, paused 3ms+3ms, total 44ms
D/dalvikvm(13323): WAIT_FOR_CONCURRENT_GC blocked 36ms
W/ContextImpl( 2396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
D/STATUSBAR-StatusBarManagerService( 2396): sendNotification(2) - 4
D/PackageManager( 2396): delete sourFile : 
W/Resources( 2396): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (13338): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13338):  
W/Resources( 2396): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 2396): Killing 5769:com.osp.app.signin/u0a44 (adj 15): empty for 1800s
D/PackageManager( 2396): delete native library directory: 
D/PackageManager( 2396): return delete result to caller: 1120773192
D/PackageManager( 2396): returnCode: 1
D/AndroidRuntime(13280): Shutting down VM
W/Resources( 2396): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(13280): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 0ms+1ms, total 3ms
I/SELinux (13338): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13338):  
I/SELinux (13338):  
I/SELinux (13338): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13338): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13338): >>>>> Normal User
E/dalvikvm(13338): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
I/PackageManager( 2396):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2396):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2396):   Scheme: "sms"
I/PackageManager( 2396): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
E/SELinux (13338): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(13338): in addTimaSignatureService
D/TimaKeyStoreProvider(13338): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13338): Added TimaKesytore provider
I/PackageManager( 2396):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2396):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2396):   Scheme: "smsto"
I/PackageManager( 2396): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2396):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2396):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2396):   Scheme: "mms"
I/PackageManager( 2396): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2396):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2396):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2396):   Scheme: "mmsto"
I/PackageManager( 2396): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2396): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(13338): GC_CONCURRENT freed 2997K, 32% free 9569K/14016K, paused 2ms+1ms, total 25ms
D/dalvikvm(13338): WAIT_FOR_CONCURRENT_GC blocked 22ms
W/Resources( 2396): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (13352): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13352):  
I/ActivityManager( 2396): Killing 7786:com.sec.android.app.voicenote/1000 (adj 15): empty for 1800s
W/ApplicationsProvider( 2972): Could not fetch usage stats
W/ApplicationsProvider( 2972): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2972): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2972): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2972): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2972): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2972): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2972): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2972): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2972): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2972): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2972): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2972): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SELinux (13352): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13352):  
I/SELinux (13352):  
I/SELinux (13352): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13352): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(13352): >>>>> Normal User
E/dalvikvm(13352): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
W/Resources( 2396): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux (13352): [DEBUG] seapp_context_lookup: seinfoCategory = release
W/Resources( 2396): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2396): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2396): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2396): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2396): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider(13352): in addTimaSignatureService
W/Resources( 2396): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/TimaKeyStoreProvider(13352): Cannot add TimaSignature Service, License check Failed
W/Resources( 2396): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityThread(13352): Added TimaKesytore provider
W/Resources( 2396): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2396): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector( 2396): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2396): clearDefaults: com.test.thalitest
D/dalvikvm(13352): GC_CONCURRENT freed 3011K, 32% free 9556K/14016K, paused 2ms+1ms, total 20ms
D/dalvikvm(13352): WAIT_FOR_CONCURRENT_GC blocked 17ms
I/SELinux (13367): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13367):  
I/SELinux (13367): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13367):  
I/SELinux (13367):  
I/SELinux (13367): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13367): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13367): >>>>> Normal User
E/dalvikvm(13367): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
E/SELinux (13367): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/dalvikvm(13367): Enabling JNI app bug workarounds for target SDK version 8...
D/TimaKeyStoreProvider(13367): in addTimaSignatureService
I/ActivityManager( 2396): Killing 5792:com.samsung.android.scloud.backup/u0a62 (adj 15): empty for 1800s
D/TimaKeyStoreProvider(13367): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13367): Added TimaKesytore provider
D/dalvikvm(13367): GC_CONCURRENT freed 3011K, 32% free 9561K/14024K, paused 2ms+2ms, total 19ms
D/dalvikvm(13367): WAIT_FOR_CONCURRENT_GC blocked 16ms
E/SQLiteDatabase(13367): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(13367): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13367): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(13367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(13367): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13367): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(13367): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(13367): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(13367): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(13367): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(13367): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(13367): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(13367): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/SQLiteDatabase(13367): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase(13367): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase(13367): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase(13367): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase(13367): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase(13367): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(13367): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(13367): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13367): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(13367): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(13367): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(13367): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(13367): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(13367): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(13367): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(13367): Shutting down VM
W/dalvikvm(13367): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(13367): FATAL EXCEPTION: main
E/AndroidRuntime(13367): Process: com.sec.pcw.device, PID: 13367
E/AndroidRuntime(13367): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.URLProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13367): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime(13367): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime(13367): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime(13367): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(13367): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(13367): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(13367): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(13367): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(13367): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(13367): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(13367): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(13367): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(13367): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(13367): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13367): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(13367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(13367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(13367): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(13367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(13367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(13367): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(13367): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(13367): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(13367): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(13367): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(13367): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime(13367): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime(13367): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/AndroidRuntime(13367): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime(13367): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime(13367): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime(13367): 	... 12 more
I/SELinux (13381): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13381):  
I/Process (13367): Sending signal. PID: 13367 SIG: 9
E/DropBoxManagerService( 2396): Can't write: system_app_crash
E/DropBoxManagerService( 2396): java.io.FileNotFoundException: /data/system/dropbox/drop235.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2396): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2396): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2396): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2396): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2396): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2396): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2396): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2396): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2396): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2396): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2396): 	... 5 more
I/ActivityManager( 2396): Process com.sec.pcw.device (pid 13367) (adj 0) has died.
I/SELinux (13381): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13381):  
I/SELinux (13381):  
I/SELinux (13381): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13381): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13381): >>>>> Normal User
E/dalvikvm(13381): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
E/SELinux (13381): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(13381): in addTimaSignatureService
D/TimaKeyStoreProvider(13381): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13381): Added TimaKesytore provider
D/CustomFrequencyManagerService( 2396): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2396  tag : ACTIVITY_RESUME_BOOSTER@8
D/dalvikvm(13381): GC_CONCURRENT freed 3020K, 32% free 9553K/14024K, paused 2ms+2ms, total 19ms
D/dalvikvm(13381): WAIT_FOR_CONCURRENT_GC blocked 16ms
W/System.err(13381): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err(13381): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err(13381): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err(13381): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err(13381): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err(13381): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err(13381): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err(13381): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err(13381): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err(13381): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err(13381): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err(13381): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err(13381): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err(13381): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err(13381): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err(13381): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(13381): 	at android.os.Looper.loop(Looper.java:146)
W/System.err(13381): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err(13381): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err(13381): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err(13381): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err(13381): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err(13381): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err(13381): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err(13381): 	at libcore.io.Posix.open(Native Method)
W/System.err(13381): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err(13381): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err(13381): 	... 21 more
D/GalaxyFinderApplication(13381): [Slink platform] Version = 29011
D/GalaxyFinderApplication(13381): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux (13395): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13395):  
I/ActivityManager( 2396): Killing 7659:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty for 1801s
I/SELinux (13395): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13395):  
I/SELinux (13395):  
I/SELinux (13395): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13395): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(13395): >>>>> Normal User
E/dalvikvm(13395): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
E/SELinux (13395): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(13395): in addTimaSignatureService
D/TimaKeyStoreProvider(13395): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13395): Added TimaKesytore provider
D/dalvikvm(13395): GC_CONCURRENT freed 2995K, 32% free 9573K/14020K, paused 1ms+1ms, total 17ms
D/dalvikvm(13395): WAIT_FOR_CONCURRENT_GC blocked 16ms
W/ContextImpl(13395): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences(13395): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences(13395): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication(13395): ContentProvider is not null
W/ResourceType(13395): No package identifier when getting value for resource number 0x00000000
I/System.out(13395): resource Id::2131361807
E/SQLiteDatabase(13395): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(13395): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13395): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13395): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(13395): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(13395): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13395): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13395): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13395): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(13395): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(13395): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(13395): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(13395): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(13395): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(13395): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(13395): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/SQLiteDatabase(13395): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/SQLiteDatabase(13395): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/SQLiteDatabase(13395): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase(13395): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase(13395): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase(13395): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase(13395): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/SQLiteDatabase(13395): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/SQLiteDatabase(13395): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/SQLiteDatabase(13395): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/SQLiteDatabase(13395): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/SQLiteDatabase(13395): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/SQLiteDatabase(13395): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/SQLiteDatabase(13395): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(13395): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(13395): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13395): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(13395): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(13395): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(13395): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(13395): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(13395): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(13395): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(13395): Shutting down VM
W/dalvikvm(13395): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(13395): FATAL EXCEPTION: main
E/AndroidRuntime(13395): Process: com.sec.android.app.shealth, PID: 13395
E/AndroidRuntime(13395): java.lang.RuntimeException: Unable to create application com.sec.android.app.shealth.SHealthApplication: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13395): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4793)
E/AndroidRuntime(13395): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(13395): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(13395): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(13395): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(13395): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(13395): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(13395): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(13395): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(13395): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(13395): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(13395): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13395): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(13395): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(13395): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(13395): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(13395): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(13395): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(13395): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(13395): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(13395): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(13395): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(13395): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(13395): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/AndroidRuntime(13395): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/AndroidRuntime(13395): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/AndroidRuntime(13395): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/AndroidRuntime(13395): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/AndroidRuntime(13395): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/AndroidRuntime(13395): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/AndroidRuntime(13395): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/AndroidRuntime(13395): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/AndroidRuntime(13395): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/AndroidRuntime(13395): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/AndroidRuntime(13395): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/AndroidRuntime(13395): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/AndroidRuntime(13395): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/AndroidRuntime(13395): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/AndroidRuntime(13395): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/AndroidRuntime(13395): 	... 10 more
E/DropBoxManagerService( 2396): Can't write: system_app_crash
E/DropBoxManagerService( 2396): java.io.FileNotFoundException: /data/system/dropbox/drop236.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2396): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2396): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2396): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2396): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2396): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2396): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2396): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2396): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2396): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2396): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2396): 	... 5 more
I/SELinux (13415): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13415):  
I/Process (13395): Sending signal. PID: 13395 SIG: 9

```
