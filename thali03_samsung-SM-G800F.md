#### Test 55742142a5c2fdb_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,--------- beginning of /dev/log/main
D/AndroidRuntime( 7170): 
D/AndroidRuntime( 7170): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7170): CheckJNI is OFF
D/AndroidRuntime( 7170): setted country_code = Poland
D/AndroidRuntime( 7170): setted countryiso_code = PL
D/AndroidRuntime( 7170): setted sales_code = PLS
D/AndroidRuntime( 7170): readGMSProperty: start
D/AndroidRuntime( 7170): readGMSProperty: already setted!!
D/AndroidRuntime( 7170): readGMSProperty: end
D/AndroidRuntime( 7170): addProductProperty: start
D/dalvikvm( 7170): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7170): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7170): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7170): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7170): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7170): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7170): failed to load memtrack module: -2
D/dalvikvm( 7170): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7170): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2420): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2420): mDVFSHelper.acquire()
I/SELinux ( 7197): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7197):  
D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7170): Shutting down VM
D/dalvikvm( 7170): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 7197): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7197):  
I/SELinux ( 7197):  
I/SELinux ( 7197): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7197): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7197): >>>>> Normal User
E/dalvikvm( 7197): >>>>> com.test.thalitest [ userId:0 | appId:10615 ]
E/SELinux ( 7197): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7197): in addTimaSignatureService
D/TimaKeyStoreProvider( 7197): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7197): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4183): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4183): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7197): GC_CONCURRENT freed 3014K, 32% free 9560K/13984K, paused 1ms+1ms, total 17ms
D/dalvikvm( 7197): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7197): Binding Chromium to the background looper Looper (main, tid 1) {422b42a0}
I/chromium( 7197): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7197): Initializing chromium process, renderers=0
W/chromium( 7197): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7197): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 7197): loaded /system/lib/egl/libGLESv1_CM_mali.so
D/libEGL  ( 7197): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7197): Mali API Version : 401
,I/Mali    ( 7197): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7197): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7197): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7197): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7197): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7197): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7197): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2420): tr p:7197,o:f
,W/dalvikvm( 7197): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7197): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7197): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7197): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7197): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7197): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7197): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7197): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 7197): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7197): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7197): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7197): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7197): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2420): semi p:7197,o:f
,I/SurfaceFlinger( 1920): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7197): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7197): Enabling debug mode 0
,W/AwContents( 7197): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7197): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2420): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/JsMessageQueue( 7197): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7197): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422b0a48
,D/dalvikvm( 7197): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422b0a48
D/jxcore_app_log( 7197): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027648144
,D/JX-Cordova( 7197): jxcore cordova android initializing
,D/dalvikvm( 7197): GC_CONCURRENT freed 1283K, 20% free 11350K/14040K, paused 1ms+2ms, total 22ms
,D/dalvikvm( 7197): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 7197): GC_CONCURRENT freed 1934K, 19% free 14968K/18328K, paused 1ms+2ms, total 40ms
,D/dalvikvm( 7197): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7197): GC_FOR_ALLOC freed 5340K, 31% free 16256K/23248K, paused 41ms, total 42ms
,D/dalvikvm( 7197): GC_CONCURRENT freed 6706K, 32% free 17719K/25856K, paused 1ms+9ms, total 55ms
,D/dalvikvm( 7197): WAIT_FOR_CONCURRENT_GC blocked 43ms
,D/dalvikvm( 7197): GC_FOR_ALLOC freed 1260K, 33% free 17568K/25856K, paused 52ms, total 52ms
,I/dalvikvm-heap( 7197): Grow heap (frag case) to 22.071MB for 3713210-byte allocation
,D/dalvikvm( 7197): GC_FOR_ALLOC freed 2445K, 37% free 18749K/29484K, paused 58ms, total 58ms
,W/jxcore-log( 7197): Initializing JXcore engine
,W/jxcore-log( 7197): JXcore engine is ready
,W/jxcore-log( 7197): Starting JXcore engine
,W/jxcore-log( 7197): Platform android
W/jxcore-log( 7197): 
,W/jxcore-log( 7197): Process ARCH arm
W/jxcore-log( 7197): 
,I/jxcore-log( 7197): JXcore Cordova bridge is ready!
I/jxcore-log( 7197): 
,W/jxcore-log( 7197): JXcore engine is started
,I/chromium( 7197): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 10
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/jxcore-log( 7197): Toggling radios to true
I/jxcore-log( 7197): 
,D/BluetoothAdapter( 7197): enable(): BT is already enabled..!
,I/WifiManager( 7197): packageName : com.test.thalitest
I/WifiManager( 7197): setWifiEnabled : true
,I/WifiService( 2420): setWifiEnabled: true pid=7197, uid=10615
,W/ActivityManager( 2420): Permission Denial: getCurrentUser() from pid=7197, uid=10615 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2420): Failed getting userId using ActivityManagerNative
W/WifiService( 2420): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7197, uid=10615 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2420): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2420): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2420): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2420): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2420): disconnect: pid=7197, uid=10615
I/jxcore-log( 7197): Radios toggled
I/jxcore-log( 7197): 
I/wpa_supplicant( 3978): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7197): Received device characteristics:
I/jxcore-log( 7197): Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 7197): Bluetooth name: S5mini-1
I/jxcore-log( 7197): Device name: samsung-SM-G800F
I/jxcore-log( 7197): 
,I/jxcore-log( 7197): Perf Test app loaded loaded
I/jxcore-log( 7197): 
,I/wpa_supplicant( 3978): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/jxcore-log( 7197): check test folder
I/jxcore-log( 7197): 
,I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,I/jxcore-log( 7197): found test : ./testFindPeers.js
I/jxcore-log( 7197): 
I/wpa_supplicant( 3978): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3978): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3978): First Scan Start
,W/Settings( 2420): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 3978): Scan requested (ret=0) - scan timeout 30 seconds
,I/WifiStateMachine( 2420): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2420): InactiveState{ what=143375 }
D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
,I/wpa_supplicant( 3978): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3978): Skip scan - already scanning
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
,I/jxcore-log( 7197): found test : ./testSendData.js
I/jxcore-log( 7197): 
D/ConnectivityService( 2420): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/WifiP2pService( 2420): InactiveState{ what=143375 }
D/ConnectivityService( 2420): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2420): net.tcp.usercfg.default not found in system default properties
D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
E/ConnectivityService( 2420): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2420): net.tcp.delack.default not found in system default properties
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2420): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2420): Attempting to switch to mobile
,D/ConnectivityService( 2420): Attempting to switch to BLUETOOTH_TETHER
,I/SELinux ( 7244): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7244):  
D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/CommandListener( 1915): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling,
E/WifiStateMachine( 2420): Error! unhandled message{ when=-43ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-42ms what=135188 target=com.android.internal.util.StateMachine$SmHandler },
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1,
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-9ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
I/SELinux ( 7244): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7244):  
I/SELinux ( 7244):  
,I/SELinux ( 7244): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7244): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7244): >>>>> Normal User
V/RouteController( 1915): RTNETLINK answers: No such file or directory
,E/dalvikvm( 7244): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7244): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
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
,V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 7244): in addTimaSignatureService
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 7244): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7244): Added TimaKesytore provider
,D/NetUtils( 2420): android_net_utils_resetConnections in env=0x77e2e4c8 clazz=0x62300001 iface=wlan0 mask=0x3
D/ConnectivityService( 2420): resetConnections(wlan0, 3)
,V/NativeCrypto( 2850): Read error: ssl=0x746bd8a8: I/O error during system call, Connection timed out
,D/dalvikvm( 7244): GC_CONCURRENT freed 2993K, 32% free 9575K/13976K, paused 3ms+2ms, total 26ms
,D/dalvikvm( 7244): WAIT_FOR_CONCURRENT_GC blocked 24ms
,V/NativeCrypto( 2850): SSL shutdown failed: ssl=0x746bd8a8: I/O error during system call, Broken pipe
,E/SPPClientService( 5592): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5592): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5592): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5592): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5592): [b] ResponseMap empty
,I/Choreographer( 7197): Skipped 161 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7197): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/System.out( 7244): Inside WakeupProvider
,I/System.out( 7244): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 7244): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7244): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7244): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/ConnectivityService( 2420): handleInetConditionChange: no active default network - ignore
V/NetworkStats( 2420): updateIfacesLocked()
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit,
V/NetworkStats( 2420): performPollLocked(flags=0x1)
V/NetworkStats( 2420): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit,
V/NetworkStats( 2420): performPollLocked() took 20ms
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit,
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NearbySettings( 4746): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
V/NearbySettings( 4746): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4746): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 4746): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4746): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4746): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4746): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 7244): initQueue()
I/ActivityManager( 2420): Killing 6211:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/NearbySettings( 4746): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4746): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4746): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 4746): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4746): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 4746): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4746): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2420): Tethering got CONNECTIVITY_ACTION
,I/ApplicationPolicy( 2420): updateDataUsageMap
,D/Tethering( 2420): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2420): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2420): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4782): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
I/PCWCLIENTTRACE_PushUtil( 6634): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6634): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6634): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6634): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6634): noConnectivity : true
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7273): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7273):  
,I/wpa_supplicant( 3978): nl80211: Received scan results (6 BSSes)
,I/wpa_supplicant( 3978): wlan0: Setting scan request: 8 sec 0 usec
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
D/Tethering( 2420): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3978): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
I/SELinux ( 7273): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7273):  
I/SELinux ( 7273):  
,I/SELinux ( 7273): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7273): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7273): >>>>> Normal User
,E/dalvikvm( 7273): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7273): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7273): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7273): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7273): Added TimaKesytore provider
,I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3978): Associated with C0.AA.48
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3978): freq(2412) increment count 2
,I/wpa_supplicant( 3978): meet head of list.
,I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/dalvikvm( 7273): GC_CONCURRENT freed 2997K, 32% free 9569K/13976K, paused 5ms+2ms, total 34ms
,D/dalvikvm( 7273): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3978): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3978): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,D/WifiNative( 2420): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/ActivityManager( 2420): Killing 6297:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/WifiP2pService( 2420): InactiveState{ what=143375 }
,D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,I/SELinux ( 7287): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7287):  
,I/SELinux ( 7287): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7287):  
I/SELinux ( 7287):  
,I/SELinux ( 7287): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7287): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7287): >>>>> Normal User
,E/dalvikvm( 7287): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7287): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7287): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7287): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7287): Added TimaKesytore provider
,D/dalvikvm( 7287): GC_CONCURRENT freed 3001K, 32% free 9567K/13976K, paused 5ms+3ms, total 40ms
,D/dalvikvm( 7287): WAIT_FOR_CONCURRENT_GC blocked 32ms
,I/dhcpcd  ( 7299): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7299): bssid match
,I/ActivityManager( 2420): Killing 6352:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7306): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7306):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 14% free 9504K/10960K, paused 4ms+4ms, total 44ms
,I/SELinux ( 7306): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7306):  
I/SELinux ( 7306):  
,I/SELinux ( 7306): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7306): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7306): >>>>> Normal User
,E/dalvikvm( 7306): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7306): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 14% free 9504K/10960K, paused 3ms+4ms, total 40ms
,D/TimaKeyStoreProvider( 7306): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7306): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7306): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 14% free 9504K/10960K, paused 3ms+5ms, total 39ms
,D/dalvikvm( 7306): GC_CONCURRENT freed 2997K, 32% free 9574K/13980K, paused 3ms+2ms, total 31ms
,D/dalvikvm( 7306): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/KLMS-2.3.201 : ( 7306): KLMSValidator() : checkQATesting()
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection...
,I/KLMS-2.3.201 : ( 7306): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452601171461
,I/KLMS-2.3.201 : ( 7306): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2420): Killing 6373:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7318): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7318):  
,I/SELinux ( 7318): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7318):  
I/SELinux ( 7318):  
,I/SELinux ( 7318): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7318): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7318): >>>>> Normal User
,E/dalvikvm( 7318): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7318): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7318): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7318): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7318): Added TimaKesytore provider
,D/dalvikvm( 7318): GC_CONCURRENT freed 2997K, 32% free 9571K/13980K, paused 4ms+3ms, total 38ms
,D/dalvikvm( 7318): WAIT_FOR_CONCURRENT_GC blocked 34ms
,D/SO_AGENT( 7318): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7318): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5841): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5841): [BDLM] already registered in spp
I/SA      ( 5841): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5841): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5841): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5841): [OR] == isSIMCardReady false ==
I/SA      ( 5841): [SCU] == networkStateCheck == false
,I/SA      ( 5841): [OR] onReceive END
I/ActivityManager( 2420): Killing 6438:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): Phone number locator feature is dsiabled
,I/SELinux ( 7330): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7330):  
,I/SELinux ( 7330): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7330):  
I/SELinux ( 7330):  
,I/SELinux ( 7330): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7330): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7330): >>>>> Normal User
,E/dalvikvm( 7330): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7330): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7330): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7330): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7330): Added TimaKesytore provider
,D/dalvikvm( 7330): GC_CONCURRENT freed 3004K, 32% free 9562K/13976K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 7330): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/sCloudBackupApp( 7330): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7330): Other Intent
I/ActivityManager( 2420): Killing 5643:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SELinux ( 7343): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7343):  
,I/SELinux ( 7343): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7343):  
I/SELinux ( 7343):  
,I/SELinux ( 7343): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7343): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7343): >>>>> Normal User
,E/dalvikvm( 7343): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7343): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7343): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7343): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7343): Added TimaKesytore provider
,D/dalvikvm( 7343): GC_CONCURRENT freed 2997K, 32% free 9572K/13980K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 7343): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/com.samsung.app( 7343): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7343): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7343): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7343): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7343): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7343): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5393): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7343): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5393): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7343): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5393): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7343): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7343): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2420): Killing 6336:com.sec.phone/1001 (adj 15): empty #43
,D/Headlines( 5889): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5889): getCountryCode(): countryCode = PL
,D/Headlines( 5889): Breath.onCreate
,D/Headlines( 5889): Breath timer started. interval : 30000
,I/SELinux ( 7356): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7356):  
,D/Headlines( 5889): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5889): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5889): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5889): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5889): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5889): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5889): requestUpdateNewsWelcomeCard !!! no welcome card
V/AlarmManager( 2420): waitForAlarm result :8
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/SELinux ( 7356): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7356):  
I/SELinux ( 7356):  
,I/SELinux ( 7356): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7356): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7356): >>>>> Normal User
,E/dalvikvm( 7356): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7356): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7356): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7356): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7356): Added TimaKesytore provider
,D/dalvikvm( 7356): GC_CONCURRENT freed 3001K, 32% free 9567K/13980K, paused 3ms+2ms, total 33ms
,D/dalvikvm( 7356): WAIT_FOR_CONCURRENT_GC blocked 29ms
,V/WebViewChromium( 7356): Binding Chromium to the background looper Looper (main, tid 1) {422b10f8}
,I/chromium( 7356): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7356): Initializing chromium process, renderers=0
,W/chromium( 7356): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7356): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7356): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7356): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7356): Mali API Version : 401
,I/Mali    ( 7356): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,W/GAV2    ( 7356): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7356): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/PackageManager( 2420): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/WifiP2pService( 2420): InactiveState{ what=143375 }
,D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2420): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2420): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2420): CaptivePortalCheckState enter
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2420): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2420): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2420): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/ConnectivityService( 2420): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2420): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2420): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2420): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,I/NSApplication( 7356): Starting up...
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/NetworkStats( 2420): updateIfacesLocked()
,V/NetworkStats( 2420): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
I/jxcore-log( 7197): Connected to the server!
I/jxcore-log( 7197): 
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): performPollLocked() took 42ms
,I/chromium( 7197): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,I/iu.Environment( 5956): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/dalvikvm( 5956): GC_CONCURRENT freed 519K, 7% free 26850K/28792K, paused 14ms+9ms, total 79ms
,D/dalvikvm( 5956): WAIT_FOR_CONCURRENT_GC blocked 1ms
D/QuickConnect[1.1][2] ( 5193): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5193): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5193): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b9808
,I/SELinux ( 7430): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7430):  
,I/SELinux ( 7430): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7430):  
I/SELinux ( 7430):  
,I/SELinux ( 7430): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7430): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7430): >>>>> Normal User
,E/dalvikvm( 7430): >>>>> com.android.email [ userId:0 | appId:10157 ],
,E/SELinux ( 7430): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7430): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7430): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7430): Added TimaKesytore provider
,D/dalvikvm( 7430): GC_CONCURRENT freed 2981K, 32% free 9583K/13976K, paused 4ms+1ms, total 30ms,
,D/dalvikvm( 7430): WAIT_FOR_CONCURRENT_GC blocked 23ms,
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId,
,I/SELinux ( 7449): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7449):  
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId,
,D/Tethering( 2420): Tethering got CONNECTIVITY_ACTION,
,D/Tethering( 2420): MasterInitialState.processMessage what=3,
,D/CaptivePortalTracker( 2420): NoActiveNetworkState{ when=-11ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler },
,D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION,
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
,D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0,
,I/SELinux ( 7449): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7449):  
I/SELinux ( 7449):  
,I/SELinux ( 7449): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7449): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7449): >>>>> Normal User,
,E/dalvikvm( 7449): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ],
,E/SELinux ( 7449): [DEBUG] seapp_context_lookup: seinfoCategory = release,
,D/TimaKeyStoreProvider( 7449): in addTimaSignatureService,
I/ActivityManager( 2420): Killing 6400:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
W/ActivityManager( 2420): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/TimaKeyStoreProvider( 7449): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7449): Added TimaKesytore provider
,I/DBG_DM  ( 4782): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/ActivityManager( 2420): Killing 5999:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7461): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7461):  
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7461): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7461):  
I/SELinux ( 7461):  
,I/SELinux ( 7461): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7461): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7461): >>>>> Normal User
,E/dalvikvm( 7461): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7461): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7461): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7461): Cannot add TimaSignature Service, License check Failed
,D/dalvikvm( 7449): GC_CONCURRENT freed 3002K, 32% free 9567K/13980K, paused 4ms+1ms, total 30ms
D/dalvikvm( 7449): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/ActivityThread( 7461): Added TimaKesytore provider
,D/BadgeProvider( 7449): onCreate
,D/BadgeProvider( 7449): DatabaseHelper
,D/BadgeProvider( 7449): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 2772): reloadBadges entered.
D/BadgeProvider( 7449): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7449): sendNotify, [notify] : null
D/BadgeProvider( 7449): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7449): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7449): update, [UpdateCount] : 1
,D/dalvikvm( 7461): GC_CONCURRENT freed 3013K, 32% free 9560K/13984K, paused 2ms+2ms, total 35ms
,D/dalvikvm( 7461): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/hcjo    ( 5977): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 5977): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5977): exit::IDLE
,D/InitializeManagerStateMachine( 5977): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5977): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5977): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5977): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5977): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5977): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5977): entry::SUCCESS
,D/hcjo    ( 5977): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5977): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5977): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5977): exit::SUCCESS
,D/InitializeManagerStateMachine( 5977): entry::IDLE
,E/SPPClientService( 5592): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5592): [SystemStateMoniter] Current Time : 276112
,E/SPPClientService( 5592): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5592): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 4746): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4746): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4746): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 4746): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4746): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4746): MountReceiver.onReceive - Keep current state
,D/Headlines( 5889): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5889): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5889): Breath 1759 latestRequest time : 1452601172401 current time : 1452601174162
,E/SPPClientService( 5592): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5592): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 4746): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4746): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5592): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/NearbySettings( 4746): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4746): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4746): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 4746): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4746): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4746): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5592): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
I/ActivityManager( 2420): Killing 6369:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/NearbySettings( 4746): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4746): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger( 1920): id=20 createSurf (1x1),1 flag=4, Uoast
,I/dalvikvm( 7197): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7197): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7197): VFY: replacing opcode 0x6e at 0x0002
I/PCWCLIENTTRACE_PushUtil( 6634): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6634): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6634): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6634): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
D/AndroidRuntime( 7197): Shutting down VM
,W/dalvikvm( 7197): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,D/PowerManagerService( 2420): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2420
,E/AndroidRuntime( 7197): FATAL EXCEPTION: main
E/AndroidRuntime( 7197): Process: com.test.thalitest, PID: 7197
E/AndroidRuntime( 7197): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 7197): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 7197): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 7197): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 7197): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 7197): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 7197): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 7197): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 7197): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 7197): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 7197): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 7197): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7197): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7197): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7197): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7197): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7197): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7197): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7197): 	at dalvik.system.NativeStart.main(Native Method)
,E/SPPClientService( 5592): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,W/ActivityManager( 2420):   Force finishing activity com.test.thalitest/.MainActivity
,D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
,E/SPPClientService( 5592): [a] [ConnectionManager] Connection is already disconnected.
,I/Process ( 7197): Sending signal. PID: 7197 SIG: 9
D/CrashAnrDetector( 2420): processName: com.test.thalitest
,D/CrashAnrDetector( 2420): broadcastEvent : com.test.thalitest data_app_crash
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,E/SPPClientService( 5592): [g] getNetMCC return empty string
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (8/11)
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (-2/11)
I/WindowState( 2420): WIN DEATH: Window{42ffb2b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (-2/11)
I/ActivityManager( 2420): Process com.test.thalitest (pid 7197) (adj 9) has died.
D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2420): mDVFSHelper.acquire()
,I/DBG_DM  ( 4782): [3.19.140541][Line:408][onResume] 
,I/DBG_DM  ( 4782): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
,I/KLMS-2.3.201 : ( 7306): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/DBG_DM  ( 4782): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4782): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4782): [3.19.140541][Line:418][onResume] Postpone Count : 29
,I/DBG_DM  ( 4782): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4782): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/KLMS-2.3.201 : ( 7306): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452601174625
,I/KLMS-2.3.201 : ( 7306): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/DBG_DM  ( 4782): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
W/WifiP2pStateTracker( 2420): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2420): sendNotification(2) - 4
D/ConnectivityService( 2420): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2420):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2420): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2420): updateSourceRoutes : no source routing conditions
,I/DBG_DM  ( 4782): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
,I/DBG_DM  ( 4782): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4782): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4782): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4782): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4782): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/LocationTagReadyService( 3471): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,I/DBG_DM  ( 4782): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/GalaxyFinderApplication( 3471): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3471): [Slink platform] The state of Slink geocode service is true
,D/Activity( 4782): setTransGradationMode to true
,D/StatusBarManagerService( 2420): semi p:4782,o:t
D/PhoneStatusBar( 2580): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
I/DBG_DM  ( 4782): [3.19.140541][Line:400][onPause] 
D/GalaxyFinderApplication( 3471): [Slink platform] The state of Slink geocode service is true
D/SO_AGENT( 7318): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger( 1920): id=21 createSurf (720x1280),2 flag=404, YUIInstallC
,I/SO_AGENT( 7318): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
,I/SELinux ( 7485): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7485):  
,I/GallerySearchProvider( 3599): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7485): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7485):  
I/SELinux ( 7485):  
,I/SELinux ( 7485): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7485): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7485): >>>>> Normal User
,E/dalvikvm( 7485): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7485): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 2420): Got RemoteException sending setActive(false) notification to pid 7197 uid 10615
,D/TimaKeyStoreProvider( 7485): in addTimaSignatureService
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2420): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/TimaKeyStoreProvider( 7485): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7485): Added TimaKesytore provider
,I/System.out( 7287): Thread-636(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7287): Thread-636(ApacheHTTPLog):isShipBuild true
,I/System.out( 7287): Thread-636(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection...,
,I/SA      ( 5841): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5841): [BDLM] already registered in spp,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
I/SA      ( 5841): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
I/SA      ( 5841): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5841): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 5841): [OR] == isSIMCardReady false ==,
I/SA      ( 5841): [SCU] == networkStateCheck == true
I/SA      ( 5841): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5841): isChinaCountryCode : false
I/SA      ( 5841): [OR] == networkStateCheck true ==
I/SA      ( 5841): [OR] GetMyCountryZoneTask,
I/SA      ( 5841): [OR] onReceive END
I/SA      ( 5841): [SRS] prepareGetMyCountryZone
I/SA      ( 5841): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 5841): [SSP] query invoked
,D/dalvikvm( 7485): GC_CONCURRENT freed 2992K, 32% free 9575K/13976K, paused 4ms+2ms, total 27ms
,D/dalvikvm( 7485): WAIT_FOR_CONCURRENT_GC blocked 23ms,
D/PhoneNumberLocatorBootCompletedReceiver( 2755): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): Phone number locator feature is dsiabled,
,I/SCloudBackupReceiver( 7330): Other Intent
,D/com.samsung.app( 7343): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7343): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!,
,D/Headlines( 5889): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE,
,D/HeadlinesChannelUtil( 5889): getCountryCode(): countryCode = PL,
,D/dalvikvm( 2420): GC_EXPLICIT freed 4531K, 72% free 25236K/87440K, paused 8ms+21ms, total 250ms,
D/Headlines( 5889): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5889): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5889): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5889): queryCategory.  mRequest is not initialized.,
D/HeadlinesCardManager( 5889): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5889): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5889): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SA      ( 5841): [TPMU] GetMccFromDB : null
,I/SA      ( 5841): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5841): [TPM] isNoProxy(default) : true
,I/SA      ( 5841): [RC New] Execute method=[GET] start
,I/SELinux ( 7507): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7507):  
,I/iu.Environment( 5956): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true,
,D/QuickConnect[1.1][2] ( 5193): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5193): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5193): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b9808,
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,I/SELinux ( 7507): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7507):  
I/SELinux ( 7507):  
,I/SELinux ( 7507): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7507): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7507): >>>>> Normal User
,E/dalvikvm( 7507): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7507): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7507): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7507): Cannot add TimaSignature Service, License check Failed
,D/hcjo    ( 5977): AutoUpdateManager:IDLE:execute
,D/ActivityThread( 7507): Added TimaKesytore provider
,D/InitializeManagerStateMachine( 5977): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5977): exit::IDLE
,D/InitializeManagerStateMachine( 5977): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5977): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 5977): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5977): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5977): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5977): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5977): entry::SUCCESS
,D/hcjo    ( 5977): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5977): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5977): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5977): exit::SUCCESS
,D/InitializeManagerStateMachine( 5977): entry::IDLE
,E/SPPClientService( 5592): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5592): [SystemStateMoniter] Current Time : 277173
,E/SPPClientService( 5592): [SystemStateMoniter] No Connect : false
,D/dalvikvm( 7507): GC_CONCURRENT freed 3002K, 32% free 9568K/13980K, paused 2ms+1ms, total 21ms
,D/dalvikvm( 7507): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/System.out( 7287): AsyncTask #1 calls detatch()
,V/KVNProvider( 7507): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7507): getFindoCursor query string : 
,W/System.err( 7287): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7287): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7287): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7287): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7287): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7287): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7287): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7287): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7287): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7287): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7287): Caused by: java.lang.NullPointerException
W/System.err( 7287): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7287): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7287): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7287): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7287): 	... 8 more
,V/KVNProvider( 7507): getTagSearchCursor() tagSearchCursor count : 0
,I/ActivityManager( 2420): Killing 6198:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/dalvikvm( 5592): GC_CONCURRENT freed 2018K, 26% free 10434K/13960K, paused 4ms+3ms, total 38ms
,I/SA      ( 5841): [RC New] [v2liruge] api execute + 720
,I/SA      ( 5841): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5841): AsyncTask #2 calls detatch()
,I/SA      ( 5841): [TPMU] getNetworkMcc : 
,I/SA      ( 5841): [SCU] saveMccToPreferece Start
,I/SA      ( 5841): [SCU] RegionMCC : 260
,I/SA      ( 5841): [SSP] query invoked
I/SA      ( 5841): [TPMU] GetMccFromDB : null
,I/SA      ( 5841): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5841): [SCU] saveMccToPreferece End
I/SA      ( 5841): [RC New] executeRequest [v2liruge] end. 737
I/SA      ( 5841): [RC New] Execute end
I/SA      ( 5841): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5841): [OR] GetMyCountryZoneTask Success
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@8
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,E/WifiStateMachine( 2420): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/SPPClientService( 5592): [b] __InitReply__
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,I/ActivityManager( 2420): Killing 6233:com.google.android.music:main/u0a125 (adj 15): empty #43,
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (10/11),
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (-2/11),
,D/PowerManagerService( 2420): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2420) eventTime = 279839,
,D/PowerManagerService( 2420): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2420 (0x0)
,D/PowerManagerService( 2420): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2420, ws=WorkSource{1000}) (elapsedTime=3484),
,I/GAV2    ( 7356): Thread[GAThread,5,main]: No campaign data found.,
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4,
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6634): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil( 6634): [hasSamungAccount] - No Samsung Account,
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6634): failed to loading secure library,
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6634): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6634): GetString : secure API is not supported!!,
I/PCWCLIENTTRACE_PushUtil( 6634): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6634): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6634): getPushTypeList : [SPP, GCM],
,E/PCWCLIENTTRACE_PCWHandler( 6634): [ensureRegistration] - No Samsung account
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/CaptivePortalTracker( 2420): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
D/ConnectivityService( 2420): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2420): Checking http://216.58.209.46/generate_204,
,D/CaptivePortalTracker( 2420): Don't send network conditions - lacking user consent.,
D/CaptivePortalTracker( 2420): isCaptivePortal: ret=false rspCode=204,
,D/CaptivePortalTracker( 2420): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2420): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
D/ConnectivityService( 2420): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 5977): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 5977): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5977): entry::CHECK_TIMEOUT_FOR_UPDATE,
,D/hcjo    ( 5977): AutoUpdateTriggerManager:IDLE:notifyNextTime,
,D/PreloadUpdateManagerStateMachine( 5977): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 5977): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5977): entry::IDLE,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/PreloadUpdateManagerStateMachine( 5977): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 5977): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5977): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 5977): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5977): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5977): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5977): entry::IDLE
,E/Watchdog( 2420): !@Sync 9,
,I/ActivityManager( 2420): Waited long enough for: ServiceRecord{443b8b08 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4,
,I/ActivityManager( 2420): Waited long enough for: ServiceRecord{4317b4a0 u0 com.sec.spp.push/.PushClientService},
,I/PowerManagerService( 2420): [PWL] Off : 225s ago,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = -10,
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4,
,V/AlarmManager( 2420): waitForAlarm result :8
V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2420): waitForAlarm result :8,
,D/Headlines( 5889): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5889): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5889): Breath 27412 latestRequest time : 1452601175022 current time : 1452601202434,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2420): stay LED for fully charged,
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 7735
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4,
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000,
,I/TLC_TIMA_PKM_initialize( 2420): initializing...
,I/TLC_TIMA_PKM_initialize( 2420): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2420): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2420): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2420): input max_recvmsg_size = 262196,
I/TZ: mc_tlc_communication( 2420): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2420): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2420): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2420): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 2420): device_id = 0x0
I/TZ: mc_tlc_communication( 2420): tlc_open() was called
,I/TZ: mc_tlc_communication( 2420): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2420): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2420): Opening the session
,I/TZ: mc_tlc_communication( 2420): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2420): Trustlet response is completed,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 10
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2420): [PWL] Off : 275s ago,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 2420): stay LED for fully charged,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4010): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 11,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4,
,V/AlarmManager( 2420): waitForAlarm result :4,
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7895): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7895):  
,I/SELinux ( 7895): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7895):  
I/SELinux ( 7895):  
,I/SELinux ( 7895): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7895): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7895): >>>>> Normal User
,E/dalvikvm( 7895): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 7895): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 7895): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7895): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7895): Added TimaKesytore provider
,D/dalvikvm( 7895): GC_CONCURRENT freed 3000K, 32% free 9567K/13976K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 7895): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/Headlines( 5889): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5889): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5889): Breath 77699 latestRequest time : 1452601175022 current time : 1452601252721
,I/ActivityManager( 2420): Killing 6577:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4,
,V/AlarmManager( 2420): waitForAlarm result :8,
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2420): waitForAlarm result :8,
,D/Headlines( 5889): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5889): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5889): Breath 87408 latestRequest time : 1452601175022 current time : 1452601262430,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4010): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 12,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4,
,V/AlarmManager( 2420): waitForAlarm result :4,
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 8054): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 8054):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 14% free 9504K/10960K, paused 4ms+5ms, total 43ms,
,I/SELinux ( 8054): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 8054):  
I/SELinux ( 8054):  
,I/SELinux ( 8054): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 8054): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,E/dalvikvm( 8054): >>>>> Normal User
,E/dalvikvm( 8054): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10039 ],
,E/SELinux ( 8054): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 14% free 9504K/10960K, paused 3ms+4ms, total 35ms,
,D/TimaKeyStoreProvider( 8054): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 8054): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 8054): Added TimaKesytore provider,
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 14% free 9504K/10960K, paused 3ms+4ms, total 35ms,
,D/dalvikvm( 8054): GC_CONCURRENT freed 2997K, 32% free 9575K/13984K, paused 4ms+1ms, total 29ms,
,D/dalvikvm( 8054): WAIT_FOR_CONCURRENT_GC blocked 13ms,
,E/SPPClientService( 8054): ============PushLog. commonIsShipBuild. stop!,
,E/SPPClientService( 8054): [PushClientApplication] Push log off : This is Ship build version,
,D/SPPClientService( 8054): PushLog.txt file is not deleted.,
D/SPPClientService( 8054): PushLog.txt file is not deleted.
,D/SPPClientService( 8054): ============PushLog. stop!,
,I/ActivityManager( 2420): Killing 6501:com.google.android.partnersetup/u0a14 (adj 15): empty #43,
,E/SPPClientService( 5592): [b] __PingReply__,
,V/AlarmManager( 2420): waitForAlarm result :8,
,D/Headlines( 5889): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5889): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5889): Breath 117405 latestRequest time : 1452601175022 current time : 1452601292427,
,I/PowerManagerService( 2420): [PWL] Off : 330s ago,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2420): !@Sync 13,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4,
,V/AlarmManager( 2420): waitForAlarm result :8,
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2420): waitForAlarm result :8,
,D/Headlines( 5889): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5889): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
D/Headlines( 5889): Breath 147404 latestRequest time : 1452601175022 current time : 1452601322426
,D/Headlines( 5889): stop ,
,D/Headlines( 5889): Breath.onDestroy : ,
I/ActivityManager( 2420): Killing 6606:com.samsung.groupcast/u0a15 (adj 15): empty #43
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4010): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 14,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2420): [PWL] Off : 390s ago,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2420): !@Sync 15,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4,
,V/AlarmManager( 2420): waitForAlarm result :8,
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4,
,E/Watchdog( 2420): !@Sync 16,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 4010): db_query_execute: result 1,
D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15,
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/GKI_LINUX( 4010): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0,
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1,
,D/        ( 4010): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.NAME_CHANGED
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: G4-1
,D/dalvikvm( 6479): GC_CONCURRENT freed 2565K, 29% free 10079K/14052K, paused 5ms+3ms, total 60ms
,D/dalvikvm( 6479): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 6479): WAIT_FOR_CONCURRENT_GC blocked 28ms
D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/SELinux ( 8360): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8360):  
,I/SELinux ( 8360): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8360):  
I/SELinux ( 8360):  
,I/SELinux ( 8360): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8360): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8360): >>>>> Normal User
,E/dalvikvm( 8360): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 8360): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 8360): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8360): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8360): Added TimaKesytore provider
,D/dalvikvm( 8360): GC_CONCURRENT freed 2983K, 32% free 9578K/13976K, paused 4ms+2ms, total 28ms
,D/dalvikvm( 8360): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/UserAnalysis.PlaceProvider( 8360): Create SecureDbHelper
,D/UserAnalysis.CarAnalyzer( 8360): Create SecureDbHelper
,I/ActivityManager( 2420): Killing 6620:com.android.musicfx/u0a24 (adj 15): empty #43
,E/bt-btm  ( 4010): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4010): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4746): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: G4-1
,D/GKI_LINUX( 4010): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/btif_config_util( 4010): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/GKI_LINUX( 4010): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/        ( 4010): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 4010): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.NAME_CHANGED
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/bt-btm  ( 4010): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4010): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4746): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,D/GKI_LINUX( 4010): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: Nexus 5
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/dalvikvm( 2580): GC_CONCURRENT freed 15725K, 34% free 33864K/50996K, paused 37ms+9ms, total 138ms
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4010): db_query_execute: result 1
D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/GKI_LINUX( 4010): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/        ( 4010): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: G4-1
,D/UserAnalysis.CarAnalyzer( 8360): Create SecureDbHelper
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2420): [PWL] Off : 455s ago
,E/bt-btm  ( 4010): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4010): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4746): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: G4-1
,D/GKI_LINUX( 4010): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/btif_config_util( 4010): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/Watchdog( 2420): !@Sync 17
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 284, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/GKI_LINUX( 4010): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/        ( 4010): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_CONNECTED,
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: Nexus 5
,D/UserAnalysis.CarAnalyzer( 8360): Create SecureDbHelper
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/        ( 4010): remote version info [f8:95:c7:87:3c:51]: 0, 0, 0
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: G4-1
,D/UserAnalysis.CarAnalyzer( 8360): Create SecureDbHelper
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,E/bt-btm  ( 4010): tBTM_SEC_DEV:0x77dad2f0 rs_disc_pending=1
,E/bt-btm  ( 4010): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4010): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4746): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: Nexus 5
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,E/bt-btm  ( 4010): tBTM_SEC_DEV:0x77dac888 rs_disc_pending=0
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,E/bt-btm  ( 4010): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4010): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 0
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 0:0
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4746): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: G4-1
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/GKI_LINUX( 4010): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/btif_config_util( 4010): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/GKI_LINUX( 4010): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/        ( 4010): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: Nexus 5
,D/UserAnalysis.CarAnalyzer( 8360): Create SecureDbHelper
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 8641
,D/dalvikvm( 2420): GC_CONCURRENT freed 4026K, 72% free 25057K/87440K, paused 12ms+18ms, total 202ms
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 0
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 0:0
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 0
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 0:0
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/        ( 4010): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_CONNECTED
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.NAME_CHANGED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: G4-1
,D/UserAnalysis.CarAnalyzer( 8360): Create SecureDbHelper
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
E/bt-btm  ( 4010): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 4010): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4746): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: Nexus 5
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,E/bt-btm  ( 4010): tBTM_SEC_DEV:0x77dac888 rs_disc_pending=0
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/btif_config_util( 4010): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4010): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4010): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4746): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/GKI_LINUX( 4010): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/GKI_LINUX( 4010): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/        ( 4010): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: Nexus 5
,D/UserAnalysis.CarAnalyzer( 8360): Create SecureDbHelper
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,E/Watchdog( 2420): !@Sync 18
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/bt-btm  ( 4010): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4010): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4746): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: Nexus 5
,D/GKI_LINUX( 4010): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/btif_config_util( 4010): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4010): db_query_execute: result 1
D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/GKI_LINUX( 4010): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/        ( 4010): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: G4-1
,D/UserAnalysis.CarAnalyzer( 8360): Create SecureDbHelper
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/btif_config_util( 4010): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4010): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,E/BluetoothEventManager( 4746): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: G4-1
,D/GKI_LINUX( 4010): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/GKI_LINUX( 4010): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67,
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/        ( 4010): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: Nexus 5
,D/UserAnalysis.CarAnalyzer( 8360): Create SecureDbHelper
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,D/btif_config_util( 4010): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4010): btm_sec_disconnected - Clearing Pending flag
D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4746): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: Nexus 5
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/GKI_LINUX( 4010): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:3f:54:73:64:c0
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/GKI_LINUX( 4010): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0,
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/        ( 4010): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 4010): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.NAME_CHANGED
,E/bt-btm  ( 4010): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4010): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:3f:54:73:64:c0
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,E/BluetoothEventManager( 4746): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: G3-1
,D/GKI_LINUX( 4010): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/btif_config_util( 4010): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/GKI_LINUX( 4010): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/        ( 4010): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: S5-1
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/UserAnalysis.CarAnalyzer( 8360): Create SecureDbHelper
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/bt-btm  ( 4010): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4010): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,E/BluetoothEventManager( 4746): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: S5-1
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/GKI_LINUX( 4010): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/GKI_LINUX( 4010): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/        ( 4010): remote version info [58:3f:54:73:64:c0]: 7, f, 610c
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: G3-1
,D/UserAnalysis.CarAnalyzer( 8360): Create SecureDbHelper
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,E/Watchdog( 2420): !@Sync 19
,E/bt-btm  ( 4010): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:3f:54:73:64:c0
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,E/BluetoothEventManager( 4746): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: G3-1
,D/GKI_LINUX( 4010): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/btif_config_util( 4010): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 8947
D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/GKI_LINUX( 4010): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/        ( 4010): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 4010): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.NAME_CHANGED
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/        ( 4010): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 6109
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: S5-1
,D/UserAnalysis.CarAnalyzer( 8360): Create SecureDbHelper
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,E/bt-btm  ( 4010): RS in progress - Set DISC Pending flag in btm_sec_send_hci_disconnect to delay disconnect
,E/bt-btm  ( 4010): tBTM_SEC_DEV:0x77dad668 rs_disc_pending=2
,E/bt-btm  ( 4010): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4010): btm_ble_resume_bg_conn 0
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value b0:c5:59:3f:75:69
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4746): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,I/PowerManagerService( 2420): [PWL] Off : 525s ago
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/btif_config_util( 4010): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4010): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4746): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: S5-1
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 20
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1,
,D/        ( 4010): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,D/        ( 4010): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.NAME_CHANGED
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=0, deviceClass=0])
V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothClassifier( 6479): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/UserAnalysis.CarAnalyzer( 8360): Create SecureDbHelper
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: S5-1
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/UserAnalysis.CarAnalyzer( 8360): Create SecureDbHelper
,E/bt-btm  ( 4010): tBTM_SEC_DEV:0x77dad668 rs_disc_pending=1
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:3f:54:73:64:c0
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4010): db_query_execute: result 1
D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1,
,D/IOP_DB_BT( 4010): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0,
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/        ( 4010): remote version info [58:3f:54:73:64:c0]: 0, 0, 0,
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: G3-1
,D/UserAnalysis.CarAnalyzer( 8360): Create SecureDbHelper
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,E/bt-btm  ( 4010): tBTM_SEC_DEV:0x77dad4ac rs_disc_pending=0
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/bt-btm  ( 4010): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value b0:c5:59:3f:75:69
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,E/bt-btm  ( 4010): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1,
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4746): ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4746): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524])
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,I/BluetoothClassifier( 6479): Bluetooth Device Name: S5-1
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,E/bt-btm  ( 4010): tBTM_SEC_DEV:0x77dad4ac rs_disc_pending=1
,E/bt-btm  ( 4010): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4010): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4010): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_MFCT, value 0
D/IOP_DB_BT( 4010): db_query_add_key: key KEY_LMP_VER, value 0:0
,D/IOP_DB_BT( 4010): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4010): db_query_execute: result 1
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 4746): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,E/BluetoothEventManager( 4746): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6479): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6479): Bluetooth Device Name: G3-1
,D/GKI_LINUX( 4010): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/BluetoothAdapterService(1110195728)( 4010): Get Bonded Devices being called
,D/btif_config_util( 4010): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2420): !@Sync 21
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
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
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2420): [PWL] Off : 600s ago
,V/AlarmManager( 2420): waitForAlarm result :8
,I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2420): LightSensor setDelay = 200000000
,D/Sensors ( 2420): LightSensor setSensorDelay = 200000000
,D/LightsService( 2420): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2420): Light sensor flush: not enabled 0
D/Sensors ( 2420): LightSensor enable = 1
D/Sensors ( 2420): LightSensor enableSensor = 1
D/SensorManager( 2420): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2420): LightSensor enable = 0
,D/Sensors ( 2420): LightSensor enableSensor = 0
,D/SensorManager( 2420): unregisterListener ::   
D/LightsService( 2420): [SvcLED]  onSensorChanged::light value = 3
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,I/GAV2    ( 5683): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5683): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2420): !@Sync 22
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 23
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = -10
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2420): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2420): <AppSync3 Whitelist>
,V/AlarmManager( 2420): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 24
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 25
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4099): GC_CONCURRENT freed 2894K, 31% free 9727K/14032K, paused 17ms+3ms, total 77ms
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 26
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 27
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 765s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 28
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/dalvikvm( 2420): GC_CONCURRENT freed 3956K, 72% free 24926K/86796K, paused 21ms+19ms, total 244ms
,E/Watchdog( 2420): !@Sync 29
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 30
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 855s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 31
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 32
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 33
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 34
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 35
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 36
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 37
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 38
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 39
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 40
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1155s ago
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 41
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 42
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :4
,D/LightsService( 2420): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 5
D/Sensors ( 2420): LightSensor setDelay = 200000000
D/Sensors ( 2420): LightSensor setSensorDelay = 200000000
D/Sensors ( 2420): Light sensor flush: not enabled 0
D/Sensors ( 2420): LightSensor enable = 1
D/Sensors ( 2420): LightSensor enableSensor = 1
D/SensorManager( 2420): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/EventLogService( 3284): Aggregate from 1452600380119 (log), 1452600380119 (data)
,D/Sensors ( 2420): LightSensor enable = 0
,D/Sensors ( 2420): LightSensor enableSensor = 0
,D/SensorManager( 2420): unregisterListener ::   
D/LightsService( 2420): [SvcLED]  onSensorChanged::light value = 2
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/dalvikvm( 3284): GC_CONCURRENT freed 2157K, 22% free 12677K/16244K, paused 7ms+10ms, total 90ms
,D/dalvikvm( 2420): GC_CONCURRENT freed 3837K, 72% free 24870K/86796K, paused 12ms+18ms, total 225ms
,E/SPPClientService( 5592): [b] __PingReply__
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 43
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2420): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2420): <AppSync3 Whitelist>
,V/AlarmManager( 2420): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2772): GC_CONCURRENT freed 7067K, 40% free 19056K/31308K, paused 11ms+6ms, total 97ms
,D/dalvikvm( 2772): WAIT_FOR_CONCURRENT_GC blocked 88ms
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2420): [PWL] Off : 1265s ago
,E/Watchdog( 2420): !@Sync 44
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 45
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 46
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 47
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2420): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 48
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 49
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4099): GC_CONCURRENT freed 2036K, 31% free 9724K/14032K, paused 3ms+3ms, total 26ms
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 50
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 51
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2420): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 52
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5592): [[PushClientService]] F:false, D:false, E:true, T:false, S:true, R:false
,E/SPPClientService( 5592): [b] __PingReply__
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 53
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 54
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/BatteryService( 2420): stay LED for fully charged
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 55
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/dalvikvm( 2420): GC_CONCURRENT freed 3812K, 72% free 24797K/86796K, paused 11ms+16ms, total 215ms
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1625s ago
,E/Watchdog( 2420): !@Sync 56
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 57
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 58
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 59
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 60
,I/PowerManagerService( 2420): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 61
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2420): Prepared write state in 39ms
,I/ProcessStatsService( 2420): Prepared write state in 65ms
,I/ProcessStatsService( 2420): Pruning old procstats: /data/system/procstats/state-2016-01-11-16-25-05.bin
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 62
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2420): waitForAlarm result :4
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): performPollLocked(flags=0x3)
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): performPollLocked() took 45ms
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,I/SELinux (12422): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12422):  
,I/SELinux (12422): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12422):  
I/SELinux (12422):  
,I/SELinux (12422): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (12422): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(12422): >>>>> Normal User
,E/dalvikvm(12422): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (12422): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(12422): in addTimaSignatureService
,D/TimaKeyStoreProvider(12422): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(12422): Added TimaKesytore provider
,D/dalvikvm(12422): GC_CONCURRENT freed 2994K, 32% free 9568K/13976K, paused 3ms+2ms, total 28ms
,D/dalvikvm(12422): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/@ WidgetProvider(12422): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(12422): onUpdate called for widgetId : 0
,D/@ WidgetProvider(12422): Widget random data : 9
,D/@ WidgetProvider(12422): onUpdate called for widgetId : 5
,D/@ WidgetProvider(12422): Widget random data : 10
,E/dalvikvm(12422): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(12422): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12422): VFY: replacing opcode 0x22 at 0x0038
,I/ActivityManager( 2420): Killing 6646:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
E/dalvikvm(12422): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12422): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(12422): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12422): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12422): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(12422): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12422): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(12422): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(12422): VFY: replacing opcode 0x22 at 0x0038
,D/dalvikvm(12422): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
,D/dalvikvm(12422): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(12422): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 5
D/dalvikvm(12422): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
D/Sensors ( 2420): LightSensor setDelay = 200000000
D/Sensors ( 2420): LightSensor setSensorDelay = 200000000
,D/LightsService( 2420): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2420): Light sensor flush: not enabled 0
D/Sensors ( 2420): LightSensor enable = 1
D/Sensors ( 2420): LightSensor enableSensor = 1
D/SensorManager( 2420): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(12422): Thread-678(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(12422): Thread-678(ApacheHTTPLog):isShipBuild true
,I/System.out(12422): Thread-678(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/Sensors ( 2420): LightSensor enable = 0
,D/Sensors ( 2420): LightSensor enableSensor = 0
D/LightsService( 2420): [SvcLED]  onSensorChanged::light value = 6
,D/SensorManager( 2420): unregisterListener ::   
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/System.out(12422): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(12422): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(12422): Max ALLOWED memory (MB): 128
V/ImageManager(12422): Max SHOULD USE memory (MB): 128
,V/ImageManager(12422): Max Image Cache memory (MB): 32
,D/skia    (12422): getTotalSize : Do not get file length
,D/@ WidgetProvider(12422): Building widget : 5
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10,
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 63
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2420): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2420): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
V/AlarmManager( 2420): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 64
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2420): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 65
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,I/ActivityManager( 2420): Killing 6495:com.sec.knox.bridge/1000 (adj 15): empty for 1829s
,I/ActivityManager( 2420): Killing 4915:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1829s
,I/ActivityManager( 2420): Killing 6455:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1839s
,I/ActivityManager( 2420): Killing 6794:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1839s
,I/ActivityManager( 2420): Killing 6780:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1840s
I/ActivityManager( 2420): Killing 6768:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1840s
,I/ActivityManager( 2420): Killing 6756:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1840s
,I/ActivityManager( 2420): Killing 6743:com.samsung.helphub/1000 (adj 15): empty for 1840s
,I/ActivityManager( 2420): Killing 6730:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1841s
,I/ActivityManager( 2420): Killing 6717:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1841s
I/ActivityManager( 2420): Killing 6703:com.sec.android.service.cm/u0a82 (adj 15): empty for 1841s
,I/ActivityManager( 2420): Killing 6413:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1841s
,I/ActivityManager( 2420): Killing 6129:com.android.mms/u0a49 (adj 15): empty for 1841s
,I/ActivityManager( 2420): Killing 6678:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1841s
,I/ActivityManager( 2420): Killing 6015:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1842s
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/CountryDetector( 2420): No listener is left
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 66
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 67
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2420): GC_CONCURRENT freed 3787K, 72% free 24800K/86796K, paused 17ms+17ms, total 223ms
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 12866
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 12868
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 12869
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 12871
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 12873
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 12874
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 12876
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 12878
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 12880
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 12882
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 12884
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 68
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4010): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 69
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 2030s ago
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,I/ActivityManager( 2420): Killing 7330:com.samsung.android.scloud.backup/u0a62 (adj 15): empty for 1825s
,I/ActivityManager( 2420): Killing 5841:com.osp.app.signin/u0a44 (adj 15): empty for 1825s
,I/ActivityManager( 2420): Killing 7485:com.sec.android.app.videoplayer/u0a53 (adj 15): empty for 1825s
,I/ActivityManager( 2420): Killing 6662:com.policydm/1000 (adj 15): empty for 1825s
,I/ActivityManager( 2420): Killing 7318:com.sec.android.soagent/u0a38 (adj 15): empty for 1825s
,I/ActivityManager( 2420): Killing 7306:com.samsung.klmsagent/u0a18 (adj 15): empty for 1825s
I/ActivityManager( 2420): Killing 7287:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1825s
,I/ActivityManager( 2420): Killing 5780:com.sec.android.diagmonagent/1000 (adj 15): empty for 1825s
,I/ActivityManager( 2420): Killing 7273:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1825s
I/ActivityManager( 2420): Killing 6634:com.sec.pcw.device/1000 (adj 15): empty for 1825s
,I/ActivityManager( 2420): Killing 4746:com.android.settings/1000 (adj 15): empty for 1825s
,I/ActivityManager( 2420): Killing 7449:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1826s
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime(13037): 
D/AndroidRuntime(13037): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(13037): CheckJNI is OFF
D/AndroidRuntime(13037): setted country_code = Poland
D/AndroidRuntime(13037): setted countryiso_code = PL
D/AndroidRuntime(13037): setted sales_code = PLS
D/AndroidRuntime(13037): readGMSProperty: start
D/AndroidRuntime(13037): readGMSProperty: already setted!!
D/AndroidRuntime(13037): readGMSProperty: end
D/AndroidRuntime(13037): addProductProperty: start
D/dalvikvm(13037): Trying to load lib libjavacore.so 0x0
D/dalvikvm(13037): Added shared lib libjavacore.so 0x0
D/dalvikvm(13037): Trying to load lib libnativehelper.so 0x0
D/dalvikvm(13037): Added shared lib libnativehelper.so 0x0
D/dalvikvm(13037): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack(13037): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug(13037): failed to load memtrack module: -2
D/dalvikvm(13037): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime(13037): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2420): START PACKAGE DELETE: observer{1119070432}
D/PackageManager( 2420): pkg{<packageName>}
D/PackageManager( 2420): user{0}
D/PackageManager( 2420): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2420): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2420): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2420): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2420): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 2420): !@killApplicatoin: 10615, uninstall pkg
W/PackageSettings( 2420): Skipping PackageSetting{42888a98 com.example.hello/10614} due to missing metadata
D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10615, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 6479): GC_EXPLICIT freed 1267K, 30% free 9954K/14052K, paused 5ms+5ms, total 67ms
D/dalvikvm( 3284): GC_EXPLICIT freed 417K, 24% free 12402K/16244K, paused 17ms+20ms, total 122ms
D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10615, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/InputReader( 2420): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 2994): mOCRHelper is null
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "sms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/QuickConnect[1.1][2] ( 5193): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/FPMS_FingerprintManagerService( 2601): onReceive: android.intent.action.PACKAGE_REMOVED
D/dalvikvm( 2949): GC_EXPLICIT freed 1468K, 29% free 10037K/13980K, paused 11ms+9ms, total 160ms
W/GeofencerStateMachine( 2736): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "smsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (13051): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13051):  
D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mms"
D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (13051): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13051):  
I/SELinux (13051):  
I/SELinux (13051): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13051): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13051): >>>>> Normal User
E/dalvikvm(13051): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux (13051): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mmsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider(13051): in addTimaSignatureService
D/TimaKeyStoreProvider(13051): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13051): Added TimaKesytore provider
D/RegisteredServicesCache( 2759): empty dynamic service
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "sms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/EnterpriseDeviceManagerService( 2420): Package has changed for user 0
D/dalvikvm( 2420): GC_EXPLICIT freed 2136K, 72% free 24904K/86744K, paused 11ms+24ms, total 356ms
D/dalvikvm( 2420): WAIT_FOR_CONCURRENT_GC blocked 76ms
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "smsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService( 2420): PackageReceiver onReceive()
I/HarmonyEASService( 2420): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mmsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(13051): GC_CONCURRENT freed 2998K, 32% free 9567K/13980K, paused 4ms+5ms, total 58ms
D/dalvikvm(13051): WAIT_FOR_CONCURRENT_GC blocked 49ms
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 2759): GC_CONCURRENT freed 1210K, 29% free 10614K/14872K, paused 11ms+5ms, total 113ms
D/dalvikvm( 2759): WAIT_FOR_CONCURRENT_GC blocked 89ms
D/elm:14132(13051): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132(13051): ELMEngine.ELMEngine( context ).
D/elm:14132(13051): MDMBridge.setEnterpriseBridge()
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132(13051): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132(13051): ElmAgentService : onCreate()
D/elm:14132(13051): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132(13051): MainReceiver.listeningToPackageRemoved()
I/SELinux (13064): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13064):  
D/elm:14132(13051): MDMBridge.getInstance()
D/elm:14132(13051): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132(13051): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux (13064): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13064):  
I/SELinux (13064):  
I/SELinux (13064): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13064): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13064): >>>>> Normal User
E/dalvikvm(13064): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
D/elm:14132(13051): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
E/SELinux (13064): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/elm:14132(13051): ElmAgentService : onDestroy().
I/ActivityManager( 2420): Killing 7343:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty for 1839s
D/TimaKeyStoreProvider(13064): in addTimaSignatureService
D/TimaKeyStoreProvider(13064): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13064): Added TimaKesytore provider
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService( 2420): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/BackupManagerService( 2420): removePackageParticipantsLocked: uid=10615 #1
D/dalvikvm(13064): GC_CONCURRENT freed 2995K, 32% free 9577K/13980K, paused 3ms+1ms, total 21ms
D/dalvikvm(13064): WAIT_FOR_CONCURRENT_GC blocked 11ms
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 2420): GC_EXPLICIT freed 973K, 72% free 24964K/86744K, paused 18ms+29ms, total 562ms
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (13079): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13079):  
I/ActivityManager( 2420): Killing 7356:com.google.android.apps.magazines/u0a115 (adj 15): empty for 1839s
I/SELinux (13079): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13079):  
I/SELinux (13079):  
I/SELinux (13079): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13079): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13079): >>>>> Normal User
E/dalvikvm(13079): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux (13079): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(13079): in addTimaSignatureService
D/TimaKeyStoreProvider(13079): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13079): Added TimaKesytore provider
W/ApplicationsProvider( 2949): Could not fetch usage stats
W/ApplicationsProvider( 2949): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2949): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2949): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2949): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2949): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2949): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2949): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2949): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2949): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2949): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2949): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2949): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4010): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4010): Disconnected process message: 10
D/PackageManager( 2420): delete sourFile : 
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/dalvikvm(13079): GC_CONCURRENT freed 2999K, 32% free 9569K/13980K, paused 7ms+3ms, total 38ms
D/dalvikvm(13079): WAIT_FOR_CONCURRENT_GC blocked 26ms
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 2420): delete native library directory: 
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/PackageManager( 2420): return delete result to caller: 1119070432
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/AndroidRuntime(13037): Shutting down VM
D/PackageManager( 2420): returnCode: 1
D/dalvikvm(13037): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 0ms+0ms, total 4ms
I/SELinux (13095): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13095):  
I/ActivityManager( 2420): Killing 5956:com.google.android.apps.plus/u0a133 (adj 15): empty for 1839s
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector( 2420): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2420): clearDefaults: com.test.thalitest
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "sms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (13095): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13095):  
I/SELinux (13095):  
I/SELinux (13095): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13095): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(13095): >>>>> Normal User
E/dalvikvm(13095): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
E/SELinux (13095): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(13095): in addTimaSignatureService
D/TimaKeyStoreProvider(13095): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13095): Added TimaKesytore provider
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "smsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Scheme: "mmsto"
D/dalvikvm(13095): GC_CONCURRENT freed 3002K, 32% free 9567K/13980K, paused 3ms+2ms, total 30ms
D/dalvikvm(13095): WAIT_FOR_CONCURRENT_GC blocked 19ms
I/SELinux (13108): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13108):  
I/SELinux (13108): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13108):  
I/SELinux (13108):  
I/SELinux (13108): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13108): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13108): >>>>> Normal User
E/dalvikvm(13108): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
E/SELinux (13108): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/dalvikvm(13108): Enabling JNI app bug workarounds for target SDK version 8...
D/TimaKeyStoreProvider(13108): in addTimaSignatureService
D/TimaKeyStoreProvider(13108): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13108): Added TimaKesytore provider
I/ActivityManager( 2420): Killing 7430:com.android.email/u0a157 (adj 15): empty for 1839s
D/dalvikvm(13108): GC_CONCURRENT freed 2994K, 32% free 9569K/13976K, paused 4ms+2ms, total 26ms
D/dalvikvm(13108): WAIT_FOR_CONCURRENT_GC blocked 18ms
E/SQLiteDatabase(13108): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(13108): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13108): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13108): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(13108): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(13108): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13108): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13108): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13108): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(13108): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(13108): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(13108): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(13108): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(13108): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(13108): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(13108): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/SQLiteDatabase(13108): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase(13108): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase(13108): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase(13108): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase(13108): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase(13108): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(13108): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(13108): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13108): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(13108): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(13108): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(13108): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(13108): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(13108): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(13108): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(13108): Shutting down VM
W/dalvikvm(13108): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(13108): FATAL EXCEPTION: main
E/AndroidRuntime(13108): Process: com.sec.pcw.device, PID: 13108
E/AndroidRuntime(13108): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.URLProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13108): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime(13108): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime(13108): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime(13108): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(13108): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(13108): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(13108): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(13108): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(13108): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(13108): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(13108): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(13108): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(13108): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(13108): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13108): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(13108): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(13108): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(13108): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(13108): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(13108): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(13108): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(13108): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(13108): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(13108): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(13108): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(13108): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime(13108): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime(13108): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/AndroidRuntime(13108): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime(13108): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime(13108): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime(13108): 	... 12 more
E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop233.tmp: open failed: EROFS (Read-only file system)
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
I/SELinux (13124): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13124):  
I/Process (13108): Sending signal. PID: 13108 SIG: 9
I/ActivityManager( 2420): Process com.sec.pcw.device (pid 13108) (adj 0) has died.
I/SELinux (13124): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13124):  
I/SELinux (13124):  
I/SELinux (13124): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13124): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13124): >>>>> Normal User
E/dalvikvm(13124): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
E/SELinux (13124): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(13124): in addTimaSignatureService
D/TimaKeyStoreProvider(13124): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13124): Added TimaKesytore provider
D/dalvikvm(13124): GC_CONCURRENT freed 3003K, 32% free 9561K/13976K, paused 2ms+2ms, total 28ms
D/dalvikvm(13124): WAIT_FOR_CONCURRENT_GC blocked 25ms
W/System.err(13124): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err(13124): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err(13124): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err(13124): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err(13124): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err(13124): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err(13124): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err(13124): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err(13124): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err(13124): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err(13124): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err(13124): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err(13124): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err(13124): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err(13124): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err(13124): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(13124): 	at android.os.Looper.loop(Looper.java:146)
W/System.err(13124): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err(13124): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err(13124): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err(13124): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err(13124): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err(13124): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err(13124): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err(13124): 	at libcore.io.Posix.open(Native Method)
W/System.err(13124): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err(13124): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err(13124): 	... 21 more
D/GalaxyFinderApplication(13124): [Slink platform] Version = 29011
D/GalaxyFinderApplication(13124): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux (13138): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13138):  
I/ActivityManager( 2420): Killing 7461:com.samsung.android.service.travel/u0a170 (adj 15): empty for 1840s
I/SELinux (13138): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13138):  
I/SELinux (13138):  
I/SELinux (13138): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13138): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(13138): >>>>> Normal User
E/dalvikvm(13138): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
E/SELinux (13138): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(13138): in addTimaSignatureService
D/TimaKeyStoreProvider(13138): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13138): Added TimaKesytore provider
D/dalvikvm(13138): GC_CONCURRENT freed 3014K, 32% free 9552K/13976K, paused 2ms+2ms, total 21ms
D/dalvikvm(13138): WAIT_FOR_CONCURRENT_GC blocked 19ms
I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
W/ContextImpl(13138): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
E/Device Type Shared Preferences(13138): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences(13138): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication(13138): ContentProvider is not null
W/ResourceType(13138): No package identifier when getting value for resource number 0x00000000
I/System.out(13138): resource Id::2131361807
E/SQLiteDatabase(13138): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(13138): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13138): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13138): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(13138): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(13138): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13138): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13138): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13138): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(13138): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(13138): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(13138): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(13138): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(13138): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(13138): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(13138): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/SQLiteDatabase(13138): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/SQLiteDatabase(13138): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/SQLiteDatabase(13138): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase(13138): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase(13138): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase(13138): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase(13138): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/SQLiteDatabase(13138): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/SQLiteDatabase(13138): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/SQLiteDatabase(13138): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/SQLiteDatabase(13138): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/SQLiteDatabase(13138): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/SQLiteDatabase(13138): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/SQLiteDatabase(13138): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(13138): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(13138): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13138): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(13138): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(13138): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(13138): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(13138): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(13138): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(13138): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(13138): Shutting down VM
W/dalvikvm(13138): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(13138): FATAL EXCEPTION: main
E/AndroidRuntime(13138): Process: com.sec.android.app.shealth, PID: 13138
E/AndroidRuntime(13138): java.lang.RuntimeException: Unable to create application com.sec.android.app.shealth.SHealthApplication: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13138): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4793)
E/AndroidRuntime(13138): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(13138): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(13138): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(13138): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(13138): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(13138): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(13138): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(13138): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(13138): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(13138): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(13138): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13138): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(13138): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(13138): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(13138): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(13138): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(13138): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(13138): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(13138): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(13138): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(13138): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(13138): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(13138): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/AndroidRuntime(13138): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/AndroidRuntime(13138): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/AndroidRuntime(13138): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/AndroidRuntime(13138): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/AndroidRuntime(13138): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/AndroidRuntime(13138): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/AndroidRuntime(13138): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/AndroidRuntime(13138): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/AndroidRuntime(13138): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/AndroidRuntime(13138): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/AndroidRuntime(13138): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/AndroidRuntime(13138): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/AndroidRuntime(13138): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/AndroidRuntime(13138): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/AndroidRuntime(13138): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/AndroidRuntime(13138): 	... 10 more
E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop234.tmp: open failed: EROFS (Read-only file system)
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
I/SELinux (13158): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13158):  
I/Process (13138): Sending signal. PID: 13138 SIG: 9
I/ActivityManager( 2420): Process com.sec.android.app.shealth (pid 13138) (adj 0) has died.
D/HeadlinesChannelApplication( 5889): HeadlinesChannelApplication.onTrimMemory(). level : 40
E/rsC++   ( 2772): RS Message thread exiting.
I/SELinux (13158): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13158):  
I/SELinux (13158):  
I/SELinux (13158): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/OpenGLRenderer( 2772): SFEffectCache:clear(), mSize = 0
D/Launcher( 2772): onTrimMemory. Level: 80
E/SELinux (13158): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm(13158): >>>>> Normal User
E/dalvikvm(13158): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10043 ]
W/ManagedEGLContext( 2772): doTerminate failed: EGL count is 2 but managed count is 1
V/SamsungIME( 2994): onTrimMeomory Level = 5
E/SELinux (13158): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
W/GeoLookout( 3091): at (DisasterAlertApplication.java:67) [onTrimMemory()]
D/TimaKeyStoreProvider(13158): in addTimaSignatureService
D/TimaKeyStoreProvider(13158): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13158): Added TimaKesytore provider
D/dalvikvm(13158): GC_CONCURRENT freed 3001K, 32% free 9571K/13984K, paused 2ms+1ms, total 21ms
D/dalvikvm(13158): WAIT_FOR_CONCURRENT_GC blocked 19ms
E/SQLiteDatabase(13158): Failed to open database '/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db'.
E/SQLiteDatabase(13158): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13158): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13158): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(13158): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(13158): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13158): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13158): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13158): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(13158): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(13158): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(13158): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(13158): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(13158): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(13158): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(13158): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:429)
E/SQLiteDatabase(13158): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase(13158): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase(13158): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase(13158): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase(13158): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase(13158): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(13158): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(13158): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13158): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(13158): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(13158): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(13158): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(13158): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(13158): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(13158): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(13158): Shutting down VM

```
