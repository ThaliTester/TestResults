#### Test 50650278b44f053_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
I/PowerManagerService( 2398): [PWL] Off : 225s ago
--------- beginning of /dev/log/main
D/AndroidRuntime( 7228): 
D/AndroidRuntime( 7228): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7228): CheckJNI is OFF
D/AndroidRuntime( 7228): setted country_code = Poland
D/AndroidRuntime( 7228): setted countryiso_code = PL
D/AndroidRuntime( 7228): setted sales_code = PLS
D/AndroidRuntime( 7228): readGMSProperty: start
D/AndroidRuntime( 7228): readGMSProperty: already setted!!
D/AndroidRuntime( 7228): readGMSProperty: end
D/AndroidRuntime( 7228): addProductProperty: start
D/dalvikvm( 7228): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7228): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7228): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7228): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7228): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7228): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7228): failed to load memtrack module: -2
D/dalvikvm( 7228): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7228): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2398): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2398): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2398  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2398): mDVFSHelper.acquire()
I/SELinux ( 7256): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7256):  
D/PointerIcon( 2398): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2398): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2398): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2398): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7228): Shutting down VM
D/dalvikvm( 7228): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 7256): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7256):  
I/SELinux ( 7256):  
I/SELinux ( 7256): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7256): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7256): >>>>> Normal User
E/dalvikvm( 7256): >>>>> com.test.thalitest [ userId:0 | appId:10558 ]
E/SELinux ( 7256): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7256): in addTimaSignatureService
D/TimaKeyStoreProvider( 7256): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7256): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4178): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4178): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7256): GC_CONCURRENT freed 3006K, 32% free 9557K/13920K, paused 1ms+1ms, total 17ms
D/dalvikvm( 7256): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7256): Binding Chromium to the background looper Looper (main, tid 1) {424c9370}
I/chromium( 7256): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7256): Initializing chromium process, renderers=0
,W/chromium( 7256): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7256): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7256): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7256): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7256): Mali API Version : 401
,I/Mali    ( 7256): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7256): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7256): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7256): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7256): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7256): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7256): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2577): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/StatusBarManagerService( 2398): tr p:7256,o:f
W/dalvikvm( 7256): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7256): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7256): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7256): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 7256): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7256): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7256): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7256): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7256): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7256): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7256): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7256): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7256): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2577): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2398): semi p:7256,o:f
,I/SurfaceFlinger( 1920): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2398): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2398): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2398): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2398): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2398): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2398): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7256): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7256): Enabling debug mode 0
,W/AwContents( 7256): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2398): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2398): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2398  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2398): mDVFSHelper.release()
,W/AwContents( 7256): nativeOnDraw failed; clearing to background color.
D/CustomFrequencyManagerService( 2398): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2398  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/IInputConnectionWrapper( 7256): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 7256): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7256): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x424c1820
,D/dalvikvm( 7256): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x424c1820
D/jxcore_app_log( 7256): JniHelper::setJavaVM(0x41a1d220), pthread_self() = 2030914320
,D/JX-Cordova( 7256): jxcore cordova android initializing
,D/dalvikvm( 7256): GC_CONCURRENT freed 1269K, 19% free 11360K/13980K, paused 3ms+7ms, total 34ms
,D/dalvikvm( 7256): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 7256): GC_CONCURRENT freed 2005K, 19% free 14948K/18320K, paused 1ms+2ms, total 38ms
,D/dalvikvm( 7256): WAIT_FOR_CONCURRENT_GC blocked 33ms
,D/CustomFrequencyManagerService( 2398): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2398  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7256): GC_FOR_ALLOC freed 5264K, 30% free 16201K/23088K, paused 51ms, total 52ms
,D/dalvikvm( 7256): GC_CONCURRENT freed 6697K, 32% free 17670K/25744K, paused 1ms+9ms, total 55ms
,D/dalvikvm( 7256): WAIT_FOR_CONCURRENT_GC blocked 36ms
,D/dalvikvm( 7256): GC_FOR_ALLOC freed 1214K, 32% free 17563K/25744K, paused 52ms, total 52ms
,I/dalvikvm-heap( 7256): Grow heap (frag case) to 22.009MB for 3713210-byte allocation
,D/dalvikvm( 7256): GC_FOR_ALLOC freed 2498K, 37% free 18691K/29372K, paused 42ms, total 42ms
,W/jxcore-log( 7256): Initializing JXcore engine
,W/jxcore-log( 7256): JXcore engine is ready
,W/jxcore-log( 7256): Starting JXcore engine
,W/jxcore-log( 7256): Platform android
W/jxcore-log( 7256): 
,W/jxcore-log( 7256): Process ARCH arm
W/jxcore-log( 7256): 
,I/jxcore-log( 7256): JXcore Cordova bridge is ready!
I/jxcore-log( 7256): 
,W/jxcore-log( 7256): JXcore engine is started
,I/chromium( 7256): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 330, Delta = 10
,I/jxcore-log( 7256): Toggling radios to true
I/jxcore-log( 7256): 
,D/BluetoothAdapter( 7256): enable(): BT is already enabled..!
,I/WifiManager( 7256): packageName : com.test.thalitest
,I/WifiManager( 7256): setWifiEnabled : true
,I/WifiService( 2398): setWifiEnabled: true pid=7256, uid=10558
,W/ActivityManager( 2398): Permission Denial: getCurrentUser() from pid=7256, uid=10558 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2398): Failed getting userId using ActivityManagerNative
W/WifiService( 2398): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7256, uid=10558 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2398): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2398): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2398): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2398): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2398): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2398): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2398): disconnect: pid=7256, uid=10558
I/jxcore-log( 7256): Radios toggled
I/jxcore-log( 7256): 
,I/wpa_supplicant( 3956): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7256): Got Device Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 7256): 
,I/jxcore-log( 7256): Perf Test app loaded loaded
I/jxcore-log( 7256): 
,I/jxcore-log( 7256): check test folder
I/jxcore-log( 7256): 
,I/wpa_supplicant( 3956): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/jxcore-log( 7256): found test : ./testFindPeers.js
I/jxcore-log( 7256): 
,I/wpa_supplicant( 3956): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2398): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2398): interfaceStatusChanged wlan0, true
D/Tethering( 2398): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2398): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3956): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3956): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3956): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3956): First Scan Start
,W/Settings( 2398): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine( 2398): ignore requestNetworkTransitionWakelock airplane:true
,I/wpa_supplicant( 3956): Scan requested (ret=0) - scan timeout 30 seconds
D/WifiP2pService( 2398): InactiveState{ what=143375 }
D/WifiP2pService( 2398): P2pEnabledState{ what=143375 }
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2398): evaluateTrafficStatsPolling
I/wpa_supplicant( 3956): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3956): Skip scan - already scanning
D/ConnectivityService( 2398): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/WifiP2pService( 2398): InactiveState{ what=143375 }
D/WifiP2pService( 2398): P2pEnabledState{ what=143375 }
D/ConnectivityService( 2398): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2398): net.tcp.usercfg.default not found in system default properties
D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
E/ConnectivityService( 2398): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2398): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2398): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
,D/AmoledAdjustTimer( 2398): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,I/SELinux ( 7303): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7303):  
D/STATUSBAR-IconMerger( 2577): checkOverflow(336), More:false, Req:false Child:3
D/ConnectivityService( 2398): Attempting to switch to mobile
D/ConnectivityService( 2398): Attempting to switch to BLUETOOTH_TETHER
D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/jxcore-log( 7256): found test : ./testSendData.js
I/jxcore-log( 7256): 
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
,I/WifiTrafficPoller( 2398): evaluateTrafficStatsPolling
E/WifiStateMachine( 2398): Error! unhandled message{ when=-40ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2398): Error! unhandled message{ when=-40ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,E/WifiStateMachine( 2398): Error! unhandled message{ when=-2ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
I/SELinux ( 7303): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7303):  
I/SELinux ( 7303):  
,I/SELinux ( 7303): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7303): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7303): >>>>> Normal User
,E/dalvikvm( 7303): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7303): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,W/NetworkManagementService( 2398): route cmd failed: 
W/NetworkManagementService( 2398): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2398): '
W/NetworkManagementService( 2398): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2398): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2398): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2398): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2398): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2398): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2398): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2398): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2398): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2398): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2398): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2398): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2398): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1,
,D/TimaKeyStoreProvider( 7303): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7303): Cannot add TimaSignature Service, License check Failed,
D/ActivityThread( 7303): Added TimaKesytore provider
,D/NetUtils( 2398): android_net_utils_resetConnections in env=0x783b7990 clazz=0x61a00001 iface=wlan0 mask=0x3,
D/ConnectivityService( 2398): resetConnections(wlan0, 3),
,E/SPPClientService( 5527): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out),
,D/dalvikvm( 7303): GC_CONCURRENT freed 2985K, 32% free 9582K/13924K, paused 3ms+1ms, total 25ms,
,D/dalvikvm( 7303): WAIT_FOR_CONCURRENT_GC blocked 16ms,
,V/NativeCrypto( 2850): Read error: ssl=0x7bac7480: I/O error during system call, Connection timed out,
,V/NativeCrypto( 2850): SSL shutdown failed: ssl=0x7bac7480: I/O error during system call, Broken pipe
,E/SPPClientService( 5527): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5527): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5527): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5527): [b] ResponseMap empty
,I/System.out( 7303): Inside WakeupProvider
,I/System.out( 7303): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 7303): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7303): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
D/VlingoApplication( 7303): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,I/chromium( 7256): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService( 2398): handleInetConditionChange: no active default network - ignore
,V/NetworkStats( 2398): updateIfacesLocked()
,D/NtpTrustedTime( 2398): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2398): currentTimeMillis() cache hit
,V/NetworkStats( 2398): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2398): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2398): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2398): currentTimeMillis() cache hit
V/NetworkStats( 2398): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2398): currentTimeMillis() cache hit
V/NetworkStats( 2398): performPollLocked() took 24ms
,D/NtpTrustedTime( 2398): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2398): currentTimeMillis() cache hit
,D/NearbySettings( 2828): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 2828): DMSUtil.isNetworkConnected - flag-null, state-null
,D/DialogFlow( 7303): initQueue()
,I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2828): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2828): MountReceiver.mPrefHandler - 7002
,I/ActivityManager( 2398): Killing 6160:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/NearbySettings( 2828): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2828): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2828): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2828): MountReceiver.mPrefHandler - 7002,
,I/ApplicationPolicy( 2398): updateDataUsageMap,
D/Tethering( 2398): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2398): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2398): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2577): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/ConnectivityService( 2398): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/STATUSBAR-NetworkController( 2577): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2577): updateDataNetType()
D/STATUSBAR-NetworkController( 2577): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6602): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6602): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6602): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6602): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6602): noConnectivity : true
,I/DBG_DM  ( 4727): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2398): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7332): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7332):  
,I/SELinux ( 7332): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7332):  
I/SELinux ( 7332):  
,I/SELinux ( 7332): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7332): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/wpa_supplicant( 3956): nl80211: Received scan results (5 BSSes)
E/dalvikvm( 7332): >>>>> Normal User
E/dalvikvm( 7332): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,I/wpa_supplicant( 3956): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3956): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3956): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
E/SELinux ( 7332): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/Tethering( 2398): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2398): interfaceStatusChanged wlan0, true
,D/TimaKeyStoreProvider( 7332): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7332): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7332): Added TimaKesytore provider
,I/wpa_supplicant( 3956): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3956): Associated with C0.AA.48
D/Tethering( 2398): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2398): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3956): freq(2412) increment count 2
I/wpa_supplicant( 3956): meet head of list.
D/Tethering( 2398): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2398): interfaceStatusChanged wlan0, true
D/Tethering( 2398): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2398): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3956): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/dalvikvm( 7332): GC_CONCURRENT freed 2989K, 32% free 9576K/13920K, paused 4ms+2ms, total 38ms
,D/dalvikvm( 7332): WAIT_FOR_CONCURRENT_GC blocked 29ms
,I/wpa_supplicant( 3956): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3956): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3956): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3956): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2398): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2398): interfaceStatusChanged wlan0, true
,D/WifiNative( 2398): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/ActivityManager( 2398): Killing 6231:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/WifiP2pService( 2398): InactiveState{ what=143375 }
,D/WifiP2pService( 2398): P2pEnabledState{ what=143375 }
,I/SELinux ( 7346): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7346):  
,I/SELinux ( 7346): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7346):  
I/SELinux ( 7346):  
,I/SELinux ( 7346): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7346): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7346): >>>>> Normal User
,E/dalvikvm( 7346): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7346): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7346): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7346): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7346): Added TimaKesytore provider
,D/dalvikvm( 7346): GC_CONCURRENT freed 3000K, 32% free 9568K/13920K, paused 2ms+2ms, total 33ms
,D/dalvikvm( 7346): WAIT_FOR_CONCURRENT_GC blocked 30ms
,I/dhcpcd  ( 7358): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7358): bssid match
,I/ActivityManager( 2398): Killing 6285:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7366): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7366):  
,I/SELinux ( 7366): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7366):  
I/SELinux ( 7366):  
,I/SELinux ( 7366): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7366): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7366): >>>>> Normal User
,E/dalvikvm( 7366): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7366): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7366): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7366): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7366): Added TimaKesytore provider
,D/libgps  ( 2398): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2398): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2398): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2398): agps_ril_update_network_availability: Waiting for IPC connection...
,D/dalvikvm( 7366): GC_CONCURRENT freed 3014K, 32% free 9557K/13924K, paused 2ms+2ms, total 33ms
,D/dalvikvm( 7366): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/KLMS-2.3.201 : ( 7366): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7366): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450287995070
,I/KLMS-2.3.201 : ( 7366): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2398): Killing 6304:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7378): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7378):  
,W/ContextImpl( 2398): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/SELinux ( 7378): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7378):  
I/SELinux ( 7378):  
,I/SELinux ( 7378): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7378): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7378): >>>>> Normal User
,E/dalvikvm( 7378): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7378): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7378): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7378): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7378): Added TimaKesytore provider
,D/dalvikvm( 7378): GC_CONCURRENT freed 3001K, 32% free 9564K/13920K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 7378): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/SO_AGENT( 7378): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7378): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5792): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5792): [BDLM] already registered in spp
,I/SA      ( 5792): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5792): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5792): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5792): [OR] == isSIMCardReady false ==
,I/SA      ( 5792): [SCU] == networkStateCheck == false
,I/SA      ( 5792): [OR] onReceive END
I/ActivityManager( 2398): Killing 5575:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): Phone number locator feature is dsiabled
,I/SELinux ( 7390): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7390):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 13% free 9501K/10900K, paused 4ms+5ms, total 43ms
,I/SELinux ( 7390): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7390):  
I/SELinux ( 7390):  
,I/SELinux ( 7390): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7390): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7390): >>>>> Normal User
,E/dalvikvm( 7390): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7390): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 13% free 9501K/10900K, paused 3ms+6ms, total 37ms
,D/TimaKeyStoreProvider( 7390): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7390): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7390): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 13% free 9501K/10900K, paused 5ms+5ms, total 41ms
,D/dalvikvm( 7390): GC_CONCURRENT freed 2998K, 32% free 9569K/13920K, paused 4ms+2ms, total 37ms
,D/dalvikvm( 7390): WAIT_FOR_CONCURRENT_GC blocked 29ms
,I/sCloudBackupApp( 7390): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7390): Other Intent
I/ActivityManager( 2398): Killing 6265:com.sec.phone/1001 (adj 15): empty #43
,I/SELinux ( 7403): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7403):  
,I/SELinux ( 7403): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7403):  
I/SELinux ( 7403):  
,I/SELinux ( 7403): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7403): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7403): >>>>> Normal User
,E/dalvikvm( 7403): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7403): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7403): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7403): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7403): Added TimaKesytore provider
,D/dalvikvm( 7403): GC_CONCURRENT freed 2997K, 32% free 9573K/13924K, paused 5ms+2ms, total 34ms
,D/dalvikvm( 7403): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/libgps  ( 2398): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2398): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2398): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/com.samsung.app( 7403): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7403): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7403): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7403): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7403): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7403): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5327): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7403): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5327): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7403): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5327): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7403): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7403): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/ActivityManager( 2398): Killing 6327:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,D/Headlines( 5855): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE,
,D/HeadlinesChannelUtil( 5855): getCountryCode(): countryCode = PL,
,D/Headlines( 5855): Breath.onCreate
,D/Headlines( 5855): Breath timer started. interval : 30000
,I/SELinux ( 7437): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7437):  
,D/Headlines( 5855): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0,
D/HeadlinesCardManager( 5855): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5855): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5855): queryCategory.  mRequest is not initialized.,
D/HeadlinesCardManager( 5855): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5855): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5855): requestUpdateNewsWelcomeCard !!! no welcome card,
V/AlarmManager( 2398): waitForAlarm result :8
,I/SELinux ( 7437): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7437):  
I/SELinux ( 7437):  
,I/SELinux ( 7437): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7437): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 7437): >>>>> Normal User
,E/dalvikvm( 7437): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ],
,E/SELinux ( 7437): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/TimaKeyStoreProvider( 7437): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7437): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7437): Added TimaKesytore provider
,D/WifiP2pService( 2398): InactiveState{ what=143375 }
,D/WifiP2pService( 2398): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2398): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/dalvikvm( 7437): GC_CONCURRENT freed 2994K, 32% free 9570K/13920K, paused 6ms+3ms, total 42ms
,D/dalvikvm( 7437): WAIT_FOR_CONCURRENT_GC blocked 31ms
D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2398): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2398): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2398): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2398): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2398): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2398): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2398): evaluateTrafficStatsPolling
D/ConnectivityService( 2398): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2398): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2398): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2398): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/WebViewChromium( 7437): Binding Chromium to the background looper Looper (main, tid 1) {424c6370}
,V/RouteController( 1915): RTNETLINK answers: No such process
,I/chromium( 7437): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,I/BrowserProcessMain( 7437): Initializing chromium process, renderers=0
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,W/chromium( 7437): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/NtpTrustedTime( 2398): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2398): currentTimeMillis() cache hit
D/NtpTrustedTime( 2398): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2398): currentTimeMillis() cache hit
V/NetworkStats( 2398): updateIfacesLocked()
V/NetworkStats( 2398): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 2398): currentTimeMillis() cache hit
V/NetworkStats( 2398): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2398): currentTimeMillis() cache hit
,D/libEGL  ( 7437): loaded /system/lib/egl/libEGL_mali.so
,V/NetworkStats( 2398): performPollLocked() took 24ms
D/libEGL  ( 7437): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/NtpTrustedTime( 2398): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2398): currentTimeMillis() cache hit
,D/libEGL  ( 7437): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7437): Mali API Version : 401
,I/Mali    ( 7437): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/PackageManager( 2398): [MSG] WRITE_PACKAGE_RESTRICTIONS
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/GAV2    ( 7437): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7437): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 7437): Starting up...
,I/iu.Environment( 5923): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5129): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5129): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5129): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@424d5c58
,I/SELinux ( 7491): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7491):  
,D/Tethering( 2398): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2398): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2398): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SELinux ( 7491): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7491):  
I/SELinux ( 7491):  
,I/SELinux ( 7491): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7491): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7491): >>>>> Normal User
,E/dalvikvm( 7491): >>>>> com.android.email [ userId:0 | appId:10157 ]
D/STATUSBAR-NetworkController( 2577): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2577): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2577): updateDataNetType()
D/STATUSBAR-NetworkController( 2577): NoService, mRoamingIconId = 0
,E/SELinux ( 7491): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/DBG_DM  ( 4727): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/TimaKeyStoreProvider( 7491): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7491): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7491): Added TimaKesytore provider
,D/libgps  ( 2398): agps_ril_update_network_state: Waiting for IPC connection...
,D/dalvikvm( 7491): GC_CONCURRENT freed 2990K, 32% free 9573K/13920K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 7491): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/RCPManagerService( 2398): exchangeData() failure , invalid userId
,D/RCPManagerService( 2398): exchangeData() failure , invalid userId
,D/RCPManagerService( 2398): exchangeData() failure , invalid userId
,I/SELinux ( 7509): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7509):  
,D/RCPManagerService( 2398): exchangeData() failure , invalid userId,
,I/SELinux ( 7509): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7509):  
I/SELinux ( 7509):  
,I/SELinux ( 7509): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7509): [DEBUG] seapp_context_lookup: seinfoCategory = release,
,E/dalvikvm( 7509): >>>>> Normal User
,E/dalvikvm( 7509): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ],
,W/ActivityManager( 2398): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found,
E/SELinux ( 7509): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/RCPManagerService( 2398): exchangeData() failure , invalid userId
,D/RCPManagerService( 2398): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 7509): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7509): Cannot add TimaSignature Service, License check Failed
,I/ActivityManager( 2398): Killing 5968:com.android.calendar/u0a144 (adj 15): empty #43
D/ActivityThread( 7509): Added TimaKesytore provider
,I/ActivityManager( 2398): Killing 6318:com.android.providers.calendar/u0a45 (adj 15): empty #43
,I/SELinux ( 7524): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7524):  
,D/dalvikvm( 7509): GC_CONCURRENT freed 3002K, 32% free 9564K/13920K, paused 4ms+2ms, total 33ms
,D/dalvikvm( 7509): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/BadgeProvider( 7509): onCreate
,D/BadgeProvider( 7509): DatabaseHelper
,I/SELinux ( 7524): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7524):  
I/SELinux ( 7524):  
D/BadgeProvider( 7509): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/SELinux ( 7524): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7524): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7524): >>>>> Normal User
,E/dalvikvm( 7524): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7524): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/Launcher.Model( 2761): reloadBadges entered.
D/BadgeProvider( 7509): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7509): sendNotify, [notify] : null
D/BadgeProvider( 7509): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7509): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7509): update, [UpdateCount] : 1
,D/TimaKeyStoreProvider( 7524): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7524): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7524): Added TimaKesytore provider
,D/dalvikvm( 7524): GC_CONCURRENT freed 2999K, 32% free 9571K/13924K, paused 4ms+2ms, total 31ms
,D/dalvikvm( 7524): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/jxcore-log( 7256): Connected to the server!
I/jxcore-log( 7256): 
,I/chromium( 7256): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7256): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 7256): 
,D/hcjo    ( 5944): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5944): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5944): exit::IDLE
,D/InitializeManagerStateMachine( 5944): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5944): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5944): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5944): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5944): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5944): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5944): entry::SUCCESS
,D/hcjo    ( 5944): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5944): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5944): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5944): exit::SUCCESS
,D/InitializeManagerStateMachine( 5944): entry::IDLE
,E/SPPClientService( 5527): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5527): [SystemStateMoniter] Current Time : 305951
,E/SPPClientService( 5527): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5527): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 2828): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2828): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2828): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2828): MountReceiver.onReceive - Keep current state
,D/Headlines( 5855): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5855): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5855): Breath 1867 latestRequest time : 1450287996203 current time : 1450287998070
,E/SPPClientService( 5527): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5527): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 2828): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2828): MountReceiver.onReceive - Keep current state
I/ActivityManager( 2398): Killing 6144:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,E/SPPClientService( 5527): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,E/SPPClientService( 5527): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,D/NearbySettings( 2828): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2828): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2828): MountReceiver.onReceive - Keep current state
,D/libgps  ( 2398): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2398): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2398): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2398): agps_ril_update_network_availability: Waiting for IPC connection...
,E/SPPClientService( 5527): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5527): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5527): [g] getNetMCC return empty string
,D/dalvikvm( 2398): GC_EXPLICIT freed 4372K, 68% free 25470K/78968K, paused 18ms+28ms, total 311ms
,D/NearbySettings( 2828): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2828): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger( 1920): id=20 createSurf (1x1),1 flag=4, Uoast
,I/PCWCLIENTTRACE_PushUtil( 6602): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6602): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6602): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6602): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/PowerManagerService( 2398): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2398
,I/KLMS-2.3.201 : ( 7366): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7366): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450287998869
,I/KLMS-2.3.201 : ( 7366): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/LocationTagReadyService( 3247): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3247): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3247): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3247): [Slink platform] The state of Slink geocode service is true,
,D/SO_AGENT( 7378): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE,
,I/SO_AGENT( 7378): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...,
,I/GallerySearchProvider( 3375): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7556): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7556):  
,I/SELinux ( 7556): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7556):  
I/SELinux ( 7556):  
,I/SELinux ( 7556): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7556): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7556): >>>>> Normal User
,E/dalvikvm( 7556): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7556): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2398): stay LED for fully charged
,D/dalvikvm( 2720): GC_EXPLICIT freed 331K, 28% free 10041K/13908K, paused 8ms+12ms, total 93ms
,I/SELinux ( 7570): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7570):  
,D/TimaKeyStoreProvider( 7556): in addTimaSignatureService
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate,
D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
D/TimaKeyStoreProvider( 7556): Cannot add TimaSignature Service, License check Failed
V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/ActivityThread( 7556): Added TimaKesytore provider
D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,I/SELinux ( 7570): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7570):  
I/SELinux ( 7570):  
I/SELinux ( 7570): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7570): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7570): >>>>> Normal User
,E/dalvikvm( 7570): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ],
,E/SELinux ( 7570): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,I/SA      ( 5792): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ],
I/SA      ( 5792): [BDLM] already registered in spp
,I/SA      ( 5792): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5792): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5792): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5792): [OR] == isSIMCardReady false ==
,D/TimaKeyStoreProvider( 7570): in addTimaSignatureService
,I/SA      ( 5792): [SCU] == networkStateCheck == true
I/SA      ( 5792): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5792): isChinaCountryCode : false
,I/SA      ( 5792): [OR] == networkStateCheck true ==
,I/SA      ( 5792): [OR] GetMyCountryZoneTask
I/SA      ( 5792): [OR] onReceive END
,I/SA      ( 5792): [SRS] prepareGetMyCountryZone
,I/SA      ( 5792): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5792): [SSP] query invoked
,D/TimaKeyStoreProvider( 7570): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7570): Added TimaKesytore provider
,I/SA      ( 5792): [TPMU] GetMccFromDB : null
,I/SA      ( 5792): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5792): [TPM] isNoProxy(default) : true
,I/SA      ( 5792): [RC New] Execute method=[GET] start
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): Phone number locator feature is dsiabled
,D/libgps  ( 2398): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2398): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2398): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
D/dalvikvm( 7556): GC_CONCURRENT freed 2992K, 32% free 9575K/13924K, paused 3ms+1ms, total 32ms
D/dalvikvm( 7556): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/SCloudBackupReceiver( 7390): Other Intent
,I/System.out( 7346): Thread-630(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/com.samsung.app( 7403): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7403): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/System.out( 7346): Thread-630(ApacheHTTPLog):isShipBuild true
,I/System.out( 7346): Thread-630(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/Headlines( 5855): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5855): getCountryCode(): countryCode = PL
,D/Headlines( 5855): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5855): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5855): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5855): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5855): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5855): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5855): requestUpdateNewsWelcomeCard !!! no welcome card
,D/dalvikvm( 7570): GC_CONCURRENT freed 2994K, 32% free 9565K/13916K, paused 5ms+2ms, total 28ms
,D/dalvikvm( 7570): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/iu.Environment( 5923): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5129): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5129): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5129): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@424d5c58
,D/RCPManagerService( 2398): exchangeData() failure , invalid userId
,D/RCPManagerService( 2398): exchangeData() failure , invalid userId
,V/KVNProvider( 7570): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7570): getFindoCursor query string : 
,V/KVNProvider( 7570): getTagSearchCursor() tagSearchCursor count : 0
,D/hcjo    ( 5944): AutoUpdateManager:IDLE:execute
,W/WifiP2pStateTracker( 2398): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
D/InitializeManagerStateMachine( 5944): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5944): exit::IDLE
D/InitializeManagerStateMachine( 5944): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5944): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5944): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5944): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5944): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 5944): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5944): entry::SUCCESS
,D/hcjo    ( 5944): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/ConnectivityService( 2398): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2398):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
D/ConnectivityService( 2398): handleConnectivityChange: setting default proxy info 
D/ConnectivityService( 2398): updateSourceRoutes : no source routing conditions
,D/hcjo    ( 5944): AutoUpdateTriggerManager:IDLE:notifyNextTime,
,D/hcjo    ( 5944): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime,
D/InitializeManagerStateMachine( 5944): exit::SUCCESS
,D/InitializeManagerStateMachine( 5944): entry::IDLE,
,E/SPPClientService( 5527): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE,
E/SPPClientService( 5527): [SystemStateMoniter] Current Time : 307383
,E/SPPClientService( 5527): [SystemStateMoniter] No Connect : false,
,I/System.out( 7346): AsyncTask #1 calls detatch(),
,W/System.err( 7346): com.sec.android.fota.osp.http.RestClientException
,W/System.err( 7346): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7346): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7346): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7346): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 7346): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7346): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7346): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 7346): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7346): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7346): Caused by: java.lang.NullPointerException
W/System.err( 7346): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7346): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7346): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7346): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7346): 	... 8 more
,I/ActivityManager( 2398): Killing 6184:com.google.android.music:main/u0a125 (adj 15): empty #43
,D/dalvikvm( 5527): GC_CONCURRENT freed 1934K, 24% free 10585K/13912K, paused 6ms+7ms, total 66ms
,E/WifiStateMachine( 2398): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SA      ( 5792): [RC New] [v2liruge] api execute + 911,
,I/SA      ( 5792): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK,
,I/System.out( 5792): AsyncTask #2 calls detatch()
,I/SA      ( 5792): [TPMU] getNetworkMcc : ,
,I/SA      ( 5792): [SCU] saveMccToPreferece Start,
I/SA      ( 5792): [SCU] RegionMCC : 260
,I/SA      ( 5792): [SSP] query invoked,
I/SA      ( 5792): [TPMU] GetMccFromDB : null
I/SA      ( 5792): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5792): [SCU] saveMccToPreferece End
I/SA      ( 5792): [RC New] executeRequest [v2liruge] end. 950
,I/SA      ( 5792): [RC New] Execute end
I/SA      ( 5792): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5792): [OR] GetMyCountryZoneTask Success,
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 330, Delta = 0,
,E/SPPClientService( 5527): [b] __InitReply__,
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (10/11),
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (-2/11)
,I/ActivityManager( 2398): Killing 6546:com.android.defcontainer/u0a6 (adj 15): empty #43
D/PowerManagerService( 2398): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2398) eventTime = 309699
D/PowerManagerService( 2398): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2398 (0x0)
D/PowerManagerService( 2398): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2398, ws=WorkSource{1000}) (elapsedTime=3151)
,I/GAV2    ( 7437): Thread[GAThread,5,main]: No campaign data found.
,D/AmoledAdjustTimer( 2398): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4,
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6602): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil( 6602): [hasSamungAccount] - No Samsung Account,
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6602): failed to loading secure library,
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6602): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6602): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6602): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6602): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6602): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 6602): [ensureRegistration] - No Samsung account
,D/TimaService( 2398): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2398): TimaServiceHandler.handleMessage what =1
,D/TimaService( 2398): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 2398): initializing...
I/TLC_TIMA_PKM_initialize( 2398): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2398): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2398): input max_sendmsg_size = 262196,
I/TZ: mc_tlc_communication( 2398): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2398): root = 0, root_len = 1
,I/TZ: mc_tlc_communication( 2398): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2398): aligned max_sendmsg_size = 262208
,I/TZ: mc_tlc_communication( 2398): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2398): device_id = 0x0
,I/TZ: mc_tlc_communication( 2398): tlc_open() was called
,I/TZ: mc_tlc_communication( 2398): Opening MobiCore device
,I/TZ: mc_tlc_communication( 2398): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2398): Opening the session
,I/TZ: mc_tlc_communication( 2398): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2398): Trustlet response is completed
,D/CaptivePortalTracker( 2398): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 2398): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker( 2398): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 2398): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker( 2398): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2398): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2398): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2398): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 5944): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5944): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5944): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5944): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5944): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5944): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5944): entry::IDLE
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2398): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PreloadUpdateManagerStateMachine( 5944): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5944): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5944): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 5944): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5944): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5944): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5944): entry::IDLE
,E/Watchdog( 2398): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel( 2398): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2398): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2398): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2398): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 330, Delta = 0
,I/ActivityManager( 2398): Waited long enough for: ServiceRecord{42fa3d58 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,D/AmoledAdjustTimer( 2398): prevTemp = 298, currTemp = 299, prevStep = 4, currStep = 4,
,I/ActivityManager( 2398): Waited long enough for: ServiceRecord{43d2a080 u0 com.sec.spp.push/.PushClientService},
,W/ContextImpl( 2398): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2398): mCoverManager.getCoverState() : true,
,D/BatteryService( 2398): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3,
,V/AlarmManager( 2398): waitForAlarm result :8
V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2398): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4372, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2398): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0,
,I/jxcore-log( 7256): --- start :testFindPeers.js---,
I/jxcore-log( 7256): 
,I/jxcore-log( 7256): testFindPeers created [object Object],
I/jxcore-log( 7256): 
,I/jxcore-log( 7256): serverPort is 8876,
I/jxcore-log( 7256): 
I/dalvikvm( 7256): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7256): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z,
D/dalvikvm( 7256): VFY: replacing opcode 0x6e at 0x0019,
I/dalvikvm( 7256): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7256): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7256): VFY: replacing opcode 0x6e at 0x0020,
,D/AndroidRuntime( 7256): Shutting down VM,
,W/dalvikvm( 7256): threadid=1: thread exiting with uncaught exception (group=0x41a30c08),
,E/AndroidRuntime( 7256): FATAL EXCEPTION: main,
E/AndroidRuntime( 7256): Process: com.test.thalitest, PID: 7256
E/AndroidRuntime( 7256): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 7256): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 7256): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 7256): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 7256): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
,E/AndroidRuntime( 7256): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 7256): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 7256): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 7256): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 7256): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 7256): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 7256): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7256): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7256): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7256): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7256): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7256): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7256): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,E/AndroidRuntime( 7256): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 2398):   Force finishing activity com.test.thalitest/.MainActivity,
,D/PointerIcon( 2398): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 2398): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2398): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2398): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager( 2398): Killing 6436:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,D/CrashAnrDetector( 2398): processName: com.test.thalitest,
,I/Process ( 7256): Sending signal. PID: 7256 SIG: 9
,D/CrashAnrDetector( 2398): broadcastEvent : com.test.thalitest data_app_crash
,D/CustomFrequencyManagerService( 2398): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2398  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ContextImpl( 2398): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,W/ActivityManager( 2398): mDVFSHelper.acquire()
,I/DBG_DM  ( 4727): [3.19.140541][Line:408][onResume] 
,I/DBG_DM  ( 4727): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
,I/ActivityManager( 2398): Process com.test.thalitest (pid 7256) (adj 9) has died.
,I/WindowState( 2398): WIN DEATH: Window{4321d558 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1920): id=19 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (-2/10)
I/SurfaceFlinger( 1920): id=19 Removed NainActivit (-2/10)
I/DBG_DM  ( 4727): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4727): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4727): [3.19.140541][Line:418][onResume] Postpone Count : 26
,I/DBG_DM  ( 4727): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4727): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4727): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2398): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2398): sendNotification(2) - 4
,I/DBG_DM  ( 4727): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26,
,I/DBG_DM  ( 4727): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0,
,I/DBG_DM  ( 4727): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0,
I/DBG_DM  ( 4727): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4727): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4727): [3.19.140541][Line:757][xdmGetDeviceEncryptState] ,
,I/DBG_DM  ( 4727): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false],
D/Activity( 4727): setTransGradationMode to true
,D/PhoneStatusBar( 2577): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/DBG_DM  ( 4727): [3.19.140541][Line:400][onPause] ,
D/StatusBarManagerService( 2398): semi p:4727,o:t
,I/SurfaceFlinger( 1920): id=21 createSurf (720x1280),2 flag=404, YUIInstallC,
D/STATUSBAR-StatusBarManagerService( 2398): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2398): manageDisableList what=0x0 pkg=WindowManager.LayoutParams,
D/PointerIcon( 2398): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2398): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2398): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2398): setHoveringSpenCustomIcon IconType is same.1,
W/ContextImpl( 2398): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 2398): Got RemoteException sending setActive(false) notification to pid 7256 uid 10558
,D/CustomFrequencyManagerService( 2398): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2398  tag : ACTIVITY_RESUME_BOOSTER@4,
D/CustomFrequencyManagerService( 2398): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2398  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/ActivityManager( 2398): mDVFSHelper.release(),
,D/CustomFrequencyManagerService( 2398): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2398  tag : ACTIVITY_RESUME_BOOSTER@8,
,D/AmoledAdjustTimer( 2398): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2398): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2398): [PWL] Off : 275s ago,
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/BatteryService( 2398): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2398): !@Sync 11
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2398): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,V/AlarmManager( 2398): waitForAlarm result :4,
,V/AlarmManager( 2398): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7994): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7994):  
,I/SELinux ( 7994): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7994):  
I/SELinux ( 7994):  
,I/SELinux ( 7994): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7994): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7994): >>>>> Normal User
,E/dalvikvm( 7994): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 7994): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 7994): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7994): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7994): Added TimaKesytore provider,
,D/dalvikvm( 7994): GC_CONCURRENT freed 3000K, 32% free 9567K/13920K, paused 3ms+2ms, total 37ms,
,D/dalvikvm( 7994): WAIT_FOR_CONCURRENT_GC blocked 28ms,
,D/Headlines( 5855): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5855): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5855): Breath 46311 latestRequest time : 1450287999292 current time : 1450288045603,
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2398): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate,
D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 2398): Skipping unknown process pid 8041,
,W/ProcessCpuTracker( 2398): Skipping unknown process pid 8046
,W/ProcessCpuTracker( 2398): Skipping unknown process pid 8054,
,W/ProcessCpuTracker( 2398): Skipping unknown process pid 8057,
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2398): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2398): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2398): waitForAlarm result :8,
,D/Headlines( 5855): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5855): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5855): Breath 56937 latestRequest time : 1450287999292 current time : 1450288056229,
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2398): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2398): stay LED for fully charged,
,D/UiModeManager( 2398): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3994): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2398): !@Sync 12,
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2398): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4,
,W/ContextImpl( 2398): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/BatteryService( 2398): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3994): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/AlarmManager( 2398): waitForAlarm result :8,
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK,
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2398): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4,
,V/AlarmManager( 2398): waitForAlarm result :8,
,D/Headlines( 5855): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5855): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5855): Breath 86942 latestRequest time : 1450287999292 current time : 1450288086234,
,I/PowerManagerService( 2398): [PWL] Off : 330s ago,
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2398): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,W/ContextImpl( 2398): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2398): !@Sync 13
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2398): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/BatteryService( 2398): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3994): Disconnected process message: 10,
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/dalvikvm( 2577): GC_CONCURRENT freed 15744K, 34% free 33867K/50960K, paused 30ms+9ms, total 116ms
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2398): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4,
,W/ContextImpl( 2398): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2398): waitForAlarm result :8,
,D/Headlines( 5855): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5855): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5855): Breath 116941 latestRequest time : 1450287999292 current time : 1450288116233,
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2398): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,E/Watchdog( 2398): !@Sync 14,
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2398): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,W/ContextImpl( 2398): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2398): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate,
D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3994): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/AlarmManager( 2398): waitForAlarm result :8,
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK,
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2398): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4,
,V/AlarmManager( 2398): waitForAlarm result :8,
,D/Headlines( 5855): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5855): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
D/Headlines( 5855): Breath 146935 latestRequest time : 1450287999292 current time : 1450288146227
,D/Headlines( 5855): stop ,
,D/Headlines( 5855): Breath.onDestroy : ,
I/ActivityManager( 2398): Killing 6575:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/PowerManagerService( 2398): [PWL] Off : 390s ago,
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2398): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2398): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2398): !@Sync 15,
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2398): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2398): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2398): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2398): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate,
D/BatteryService( 2398): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2398): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4,
,E/Watchdog( 2398): !@Sync 16,
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2398): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2398): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2398): waitForAlarm result :8,
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2398): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2398): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,W/ContextImpl( 2398): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2398): [PWL] Off : 455s ago,
,E/Watchdog( 2398): !@Sync 17,
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): stay LED for fully charged
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2398): mCoverManager.getCoverState() : true
V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2398): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2398): stay LED for fully charged
,D/UiModeManager( 2398): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 18
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2398): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 292, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2398): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): stay LED for fully charged
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2398): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2398): !@Sync 19
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2398): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService( 2398): [PWL] Off : 525s ago
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2398): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2398): stay LED for fully charged
,D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 2398): GC_CONCURRENT freed 4423K, 69% free 24946K/78968K, paused 12ms+18ms, total 219ms
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,D/TimaService( 2398): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2398): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2398): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2398): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2398): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2398): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2398): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2398): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 10
,D/AmoledAdjustTimer( 2398): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2398): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2398): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2398): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2398): !@Sync 21
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2398): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/GAV2    ( 5619): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5619): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2398): !@Sync 22
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2398): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2398): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
V/AlarmManager( 2398): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/BatteryService( 2398): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 23
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 24
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2398): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 25
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/BatteryService( 2398): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 26
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/BatteryService( 2398): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 289, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4075): GC_CONCURRENT freed 2894K, 31% free 9724K/13972K, paused 6ms+3ms, total 68ms
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/BatteryService( 2398): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2398): waitForAlarm result :8
,D/LightsService( 2398): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK,
I/SensorManagerA( 2398): getReportingMode :: sensor.mType = 5
D/Sensors ( 2398): LightSensor setDelay = 200000000
,D/Sensors ( 2398): LightSensor setSensorDelay = 200000000
D/Sensors ( 2398): Light sensor flush: not enabled 0
,D/Sensors ( 2398): LightSensor enable = 1
,D/Sensors ( 2398): LightSensor enableSensor = 1
,D/SensorManager( 2398): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,E/SPPClientService( 5527): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/LightsService( 2398): [SvcLED]  onSensorChanged::light value = 0
D/Sensors ( 2398): LightSensor enable = 0
D/Sensors ( 2398): LightSensor enableSensor = 0
,D/SensorManager( 2398): unregisterListener ::   
D/LightsService( 2398): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/AmoledAdjustTimer( 2398): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 27
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2398): [PWL] Off : 765s ago
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 28
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 29
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/TimaService( 2398): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2398): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2398): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2398): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2398): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2398): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2398): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2398): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2398): [PWL] Off : 855s ago
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 31
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2398): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2398): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 32
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 33
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2398): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 34
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2398): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2398): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/dalvikvm( 2398): GC_CONCURRENT freed 3823K, 69% free 24901K/78968K, paused 22ms+15ms, total 239ms
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 35
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 36
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2398): waitForAlarm result :4
,V/AlarmManager( 2398): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2398): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/EventLogService( 3437): Aggregate from 1450286749086 (log), 1450286749086 (data)
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2398): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,E/SPPClientService( 5527): [b] __PingReply__
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2398): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2398): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 37
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 38
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 39
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/TimaService( 2398): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2398): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2398): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2398): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2398): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2398): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2398): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2398): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2398): [PWL] Off : 1155s ago
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 41
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 42
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2398): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2398): <AppSync3 Whitelist>
,V/AlarmManager( 2398): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 43
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/BatteryService( 2398): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2398): mCoverManager.getCoverState() : true
D/BatteryService( 2398): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2398): [PWL] Off : 1265s ago
,E/Watchdog( 2398): !@Sync 44
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2398): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/BatteryService( 2398): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2398): !@Sync 45
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/BatteryService( 2398): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 46
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2398): waitForAlarm result :8
,I/SensorManagerA( 2398): getReportingMode :: sensor.mType = 5
,D/LightsService( 2398): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/Sensors ( 2398): LightSensor setDelay = 200000000
D/Sensors ( 2398): LightSensor setSensorDelay = 200000000
D/Sensors ( 2398): Light sensor flush: not enabled 0
D/Sensors ( 2398): LightSensor enable = 1
D/Sensors ( 2398): LightSensor enableSensor = 1
D/SensorManager( 2398): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2398): LightSensor enable = 0
,D/Sensors ( 2398): LightSensor enableSensor = 0
,D/LightsService( 2398): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2398): unregisterListener ::   
D/LightsService( 2398): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 47
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2398): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/dalvikvm( 2398): GC_CONCURRENT freed 3731K, 69% free 24920K/78968K, paused 22ms+16ms, total 241ms
,E/Watchdog( 2398): !@Sync 48
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2398): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2398): !@Sync 49
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2398): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/TimaService( 2398): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2398): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2398): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 2398): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2398): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2398): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2398): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4075): GC_CONCURRENT freed 2035K, 31% free 9686K/13972K, paused 6ms+2ms, total 29ms
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 51
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2398): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 52
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 53
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 54
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 55
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2398): [PWL] Off : 1625s ago
,E/Watchdog( 2398): !@Sync 56
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2398): waitForAlarm result :8
,E/SPPClientService( 5527): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 57
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 58
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 59
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/BatteryService( 2398): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2398): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2398): mCoverManager.getCoverState() : true
V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 2398): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2398): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2398): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2398): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2398): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2398): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2398): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2398): !@Sync 60
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2398): [PWL] Off : 1755s ago
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2398): Prepared write state in 39ms
,I/ProcessStatsService( 2398): Pruning old procstats: /data/system/procstats/state-2015-12-16-04-05-21.bin
,I/ProcessStatsService( 2398): Prepared write state in 63ms
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 61
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/dalvikvm( 2398): GC_CONCURRENT freed 3808K, 69% free 24906K/78968K, paused 22ms+17ms, total 241ms
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 62
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2398): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2398): <AppSync3 Whitelist>
,V/AlarmManager( 2398): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 63
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 64
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2398): stay LED for fully charged
,D/UiModeManager( 2398): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
I/ActivityManager( 2398): Killing 6391:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1803s
,I/ActivityManager( 2398): Killing 6764:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1803s
,I/ActivityManager( 2398): Killing 6750:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1804s
,I/ActivityManager( 2398): Killing 6738:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1804s
,I/ActivityManager( 2398): Killing 6726:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1804s
,I/ActivityManager( 2398): Killing 6713:com.samsung.helphub/1000 (adj 15): empty for 1805s
,I/ActivityManager( 2398): Killing 6700:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1805s
,I/ActivityManager( 2398): Killing 6687:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1805s
,I/ActivityManager( 2398): Killing 6674:com.sec.android.service.cm/u0a82 (adj 15): empty for 1805s
,I/ActivityManager( 2398): Killing 6348:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1805s
,I/ActivityManager( 2398): Killing 5686:com.android.mms/u0a49 (adj 15): empty for 1805s
,I/ActivityManager( 2398): Killing 6647:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1805s
,I/ActivityManager( 2398): Killing 5987:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1806s
I/ActivityManager( 2398): Killing 6617:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty for 1806s
,I/ActivityManager( 2398): Killing 6589:com.android.musicfx/u0a24 (adj 15): empty for 1807s
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/CountryDetector( 2398): No listener is left
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/BatteryService( 2398): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2398): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/BatteryService( 2398): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2398): !@Sync 65
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 66
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,I/ActivityManager( 2398): Killing 6430:com.sec.knox.bridge/1000 (adj 15): empty for 1853s
,I/ActivityManager( 2398): Killing 4850:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1853s
,I/ActivityManager( 2398): Killing 6416:com.google.android.googlequicksearchbox:search/u0a59 (adj 15): empty for 1853s
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2398): waitForAlarm result :4
,V/NetworkStats( 2398): performPollLocked(flags=0x3)
,D/NtpTrustedTime( 2398): currentTimeMillis() cache hit
,V/AlarmManager( 2398): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2398): currentTimeMillis() cache hit
,V/NetworkStats( 2398): performPollLocked() took 48ms
D/NtpTrustedTime( 2398): currentTimeMillis() cache hit
D/NtpTrustedTime( 2398): currentTimeMillis() cache hit
,I/SELinux (11779): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11779):  
,I/SELinux (11779): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11779):  
I/SELinux (11779):  
,I/SELinux (11779): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (11779): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(11779): >>>>> Normal User
,E/dalvikvm(11779): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (11779): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(11779): in addTimaSignatureService
,D/TimaKeyStoreProvider(11779): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(11779): Added TimaKesytore provider
,D/dalvikvm(11779): GC_CONCURRENT freed 3004K, 32% free 9568K/13924K, paused 3ms+2ms, total 28ms
,D/dalvikvm(11779): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/@ WidgetProvider(11779): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(11779): onUpdate called for widgetId : 0
,D/@ WidgetProvider(11779): Widget random data : 1
,D/@ WidgetProvider(11779): onUpdate called for widgetId : 5
,D/@ WidgetProvider(11779): Widget random data : 5
,E/dalvikvm(11779): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
,W/dalvikvm(11779): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(11779): VFY: replacing opcode 0x22 at 0x0038
,E/dalvikvm(11779): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(11779): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(11779): VFY: replacing opcode 0x22 at 0x0038
,E/dalvikvm(11779): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(11779): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(11779): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(11779): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
,W/dalvikvm(11779): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(11779): VFY: replacing opcode 0x22 at 0x0038
,D/dalvikvm(11779): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
D/dalvikvm(11779): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(11779): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(11779): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,I/SensorManagerA( 2398): getReportingMode :: sensor.mType = 5
D/Sensors ( 2398): LightSensor setDelay = 200000000
D/Sensors ( 2398): LightSensor setSensorDelay = 200000000
D/Sensors ( 2398): Light sensor flush: not enabled 0
D/Sensors ( 2398): LightSensor enable = 1
,D/Sensors ( 2398): LightSensor enableSensor = 1
,D/SensorManager( 2398): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/LightsService( 2398): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 2850): GC_CONCURRENT freed 1869K, 24% free 10814K/14104K, paused 4ms+5ms, total 47ms
,I/System.out(11779): Thread-666(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11779): Thread-666(ApacheHTTPLog):isShipBuild true
,I/System.out(11779): Thread-666(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/Sensors ( 2398): LightSensor enable = 0
,D/Sensors ( 2398): LightSensor enableSensor = 0
,D/SensorManager( 2398): unregisterListener ::   
D/LightsService( 2398): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2398): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/System.out(11779): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(11779): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(11779): Max ALLOWED memory (MB): 128
V/ImageManager(11779): Max SHOULD USE memory (MB): 128
,V/ImageManager(11779): Max Image Cache memory (MB): 32
,D/skia    (11779): getTotalSize : Do not get file length
,D/@ WidgetProvider(11779): Building widget : 5
,D/dalvikvm( 2761): GC_CONCURRENT freed 8899K, 40% free 18336K/30324K, paused 6ms+6ms, total 66ms
,D/dalvikvm( 2761): WAIT_FOR_CONCURRENT_GC blocked 56ms
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2398): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2398): !@Sync 67
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2398): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2398): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/BatteryService( 2398): stay LED for fully charged
D/UiModeManager( 2398): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 68
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 69
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2398): [PWL] Off : 2030s ago
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/TimaService( 2398): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2398): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2398): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2398): !@Sync 70
,I/TLC_TIMA_PKM_measure_kernel( 2398): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2398): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2398): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2398): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2398): waitForAlarm result :8
,V/AlarmManager( 2398): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,I/ActivityManager( 2398): Killing 6631:com.policydm/1000 (adj 15): empty for 1821s
,I/ActivityManager( 2398): Killing 7378:com.sec.android.soagent/u0a38 (adj 15): empty for 1821s
,I/ActivityManager( 2398): Killing 7303:com.vlingo.midas/u0a34 (adj 15): empty for 1821s
,I/ActivityManager( 2398): Killing 7366:com.samsung.klmsagent/u0a18 (adj 15): empty for 1821s
,I/ActivityManager( 2398): Killing 7346:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1821s
,I/ActivityManager( 2398): Killing 5732:com.sec.android.diagmonagent/1000 (adj 15): empty for 1821s
I/ActivityManager( 2398): Killing 7332:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1821s
,I/ActivityManager( 2398): Killing 6602:com.sec.pcw.device/1000 (adj 15): empty for 1821s
,I/ActivityManager( 2398): Killing 2828:com.android.settings/1000 (adj 15): empty for 1821s
,I/ActivityManager( 2398): Killing 7509:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1822s
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2398): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2398): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms)
```
