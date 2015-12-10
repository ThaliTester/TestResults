#### Test 50650278b86327b_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
E/Watchdog( 2404): !@Sync 8
--------- beginning of /dev/log/main
D/AndroidRuntime( 7078): 
D/AndroidRuntime( 7078): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7078): CheckJNI is OFF
D/AndroidRuntime( 7078): setted country_code = Poland
D/AndroidRuntime( 7078): setted countryiso_code = PL
D/AndroidRuntime( 7078): setted sales_code = PLS
D/AndroidRuntime( 7078): readGMSProperty: start
D/AndroidRuntime( 7078): readGMSProperty: already setted!!
D/AndroidRuntime( 7078): readGMSProperty: end
D/AndroidRuntime( 7078): addProductProperty: start
D/dalvikvm( 7078): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7078): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7078): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7078): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7078): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7078): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7078): failed to load memtrack module: -2
D/dalvikvm( 7078): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7078): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2404): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2404): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2404  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2404): mDVFSHelper.acquire()
I/SELinux ( 7104): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7104):  
D/PointerIcon( 2404): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2404): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2404): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2404): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7078): Shutting down VM
D/dalvikvm( 7078): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 7104): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7104):  
I/SELinux ( 7104):  
I/SELinux ( 7104): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7104): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7104): >>>>> Normal User
E/dalvikvm( 7104): >>>>> com.test.thalitest [ userId:0 | appId:10531 ]
E/SELinux ( 7104): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7104): in addTimaSignatureService
D/TimaKeyStoreProvider( 7104): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7104): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4182): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4182): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7104): GC_CONCURRENT freed 3006K, 32% free 9556K/13992K, paused 2ms+1ms, total 18ms
D/dalvikvm( 7104): WAIT_FOR_CONCURRENT_GC blocked 15ms
V/WebViewChromium( 7104): Binding Chromium to the background looper Looper (main, tid 1) {42791378}
I/chromium( 7104): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7104): Initializing chromium process, renderers=0
W/chromium( 7104): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7104): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7104): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7104): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7104): Mali API Version : 401
,I/Mali    ( 7104): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
I/dalvikvm( 7104): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7104): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7104): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7104): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7104): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 7104): VFY: replacing opcode 0x6e at 0x0008
D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2404): tr p:7104,o:f
W/dalvikvm( 7104): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7104): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7104): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7104): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 7104): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7104): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7104): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7104): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7104): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7104): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7104): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7104): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7104): CordovaWebView is running on device made by: samsung
D/StatusBarManagerService( 2404): semi p:7104,o:f
D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
I/SurfaceFlinger( 1921): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2404): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2404): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2404): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2404): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2404): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2404): setHoveringSpenCustomIcon IconType is same.1
I/HWUI    ( 7104): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 7104): Enabling debug mode 0
W/AwContents( 7104): nativeOnDraw failed; clearing to background color.
W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/IInputConnectionWrapper( 7104): showStatusIcon on inactive InputConnection
D/CustomFrequencyManagerService( 2404): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2404  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2404): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2404): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2404  pkgName : ACTIVITY_RESUME_BOOSTER@8
D/JsMessageQueue( 7104): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 7104): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42789010
D/dalvikvm( 7104): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42789010
D/jxcore_app_log( 7104): JniHelper::setJavaVM(0x41cd3220), pthread_self() = 2027494496
D/JX-Cordova( 7104): jxcore cordova android initializing
I/dalvikvm( 7104): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 7104): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 7104): VFY: replacing opcode 0x6e at 0x0045
D/dalvikvm( 7104): GC_CONCURRENT freed 1287K, 20% free 11341K/14052K, paused 2ms+2ms, total 30ms
D/dalvikvm( 7104): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/dalvikvm( 7104): GC_CONCURRENT freed 1890K, 19% free 14966K/18304K, paused 2ms+2ms, total 50ms
,D/dalvikvm( 7104): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/CustomFrequencyManagerService( 2404): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2404  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7104): GC_FOR_ALLOC freed 5371K, 31% free 16209K/23256K, paused 50ms, total 50ms
,D/dalvikvm( 7104): GC_CONCURRENT freed 6644K, 32% free 17671K/25824K, paused 2ms+12ms, total 73ms
,D/dalvikvm( 7104): WAIT_FOR_CONCURRENT_GC blocked 64ms
,D/dalvikvm( 7104): GC_FOR_ALLOC freed 1318K, 33% free 17520K/25824K, paused 49ms, total 51ms
,I/dalvikvm-heap( 7104): Grow heap (frag case) to 22.040MB for 3713210-byte allocation
,D/dalvikvm( 7104): GC_FOR_ALLOC freed 2535K, 37% free 18611K/29452K, paused 41ms, total 41ms
,W/jxcore-log( 7104): Initializing JXcore engine
,W/jxcore-log( 7104): JXcore engine is ready
,W/jxcore-log( 7104): Starting JXcore engine
,W/jxcore-log( 7104): Platform android
W/jxcore-log( 7104): 
,W/jxcore-log( 7104): Process ARCH arm
W/jxcore-log( 7104): 
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7104): JXcore Cordova bridge is ready!
I/jxcore-log( 7104): 
,W/jxcore-log( 7104): JXcore engine is started
,I/chromium( 7104): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7104): Toggling radios to true
I/jxcore-log( 7104): 
,D/BluetoothAdapter( 7104): enable(): BT is already enabled..!
,I/WifiManager( 7104): packageName : com.test.thalitest
,I/WifiManager( 7104): setWifiEnabled : true
,I/WifiService( 2404): setWifiEnabled: true pid=7104, uid=10531
,W/ActivityManager( 2404): Permission Denial: getCurrentUser() from pid=7104, uid=10531 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2404): Failed getting userId using ActivityManagerNative
W/WifiService( 2404): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7104, uid=10531 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2404): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2404): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2404): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2404): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2404): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2404): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2404): disconnect: pid=7104, uid=10531
I/jxcore-log( 7104): Radios toggled
I/jxcore-log( 7104): 
I/wpa_supplicant( 3979): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7104): Got Device Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 7104): 
,I/jxcore-log( 7104): Perf Test app loaded loaded
I/jxcore-log( 7104): 
,I/wpa_supplicant( 3979): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/Choreographer( 7104): Skipped 123 frames!  The application may be doing too much work on its main thread.
,I/wpa_supplicant( 3979): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2404): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2404): interfaceStatusChanged wlan0, true
D/Tethering( 2404): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2404): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3979): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 3979): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3979): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3979): First Scan Start
W/Settings( 2404): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine( 2404): ignore requestNetworkTransitionWakelock airplane:true
,I/wpa_supplicant( 3979): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiP2pService( 2404): InactiveState{ what=143375 }
,D/WifiP2pService( 2404): P2pEnabledState{ what=143375 }
,I/jxcore-log( 7104): check test folder
I/jxcore-log( 7104): 
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/jxcore-log( 7104): found test : ./testFindPeers.js
I/jxcore-log( 7104): 
D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2404): evaluateTrafficStatsPolling
D/ConnectivityService( 2404): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2404): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2404): net.tcp.usercfg.default not found in system default properties
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2404): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2404): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2404): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
I/wpa_supplicant( 3979): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3979): Skip scan - already scanning
D/WifiP2pService( 2404): InactiveState{ what=143375 }
D/WifiP2pService( 2404): P2pEnabledState{ what=143375 }
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
,I/SELinux ( 7153): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7153):  
D/ConnectivityService( 2404): Attempting to switch to mobile
D/ConnectivityService( 2404): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/jxcore-log( 7104): found test : ./testSendData.js
I/jxcore-log( 7104): 
,I/WifiTrafficPoller( 2404): evaluateTrafficStatsPolling
E/WifiStateMachine( 2404): Error! unhandled message{ when=-47ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2404): Error! unhandled message{ when=-47ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,E/WifiStateMachine( 2404): Error! unhandled message{ when=-6ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,I/SELinux ( 7153): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7153):  
I/SELinux ( 7153):  
,I/SELinux ( 7153): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,W/NetworkManagementService( 2404): route cmd failed: 
W/NetworkManagementService( 2404): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2404): '
W/NetworkManagementService( 2404): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2404): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2404): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2404): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2404): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2404): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2404): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2404): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2404): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2404): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2404): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2404): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2404): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SELinux ( 7153): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7153): >>>>> Normal User
,E/dalvikvm( 7153): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1
,E/SELinux ( 7153): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 7153): in addTimaSignatureService
,D/NetUtils( 2404): android_net_utils_resetConnections in env=0x789fb5e8 clazz=0x61700001 iface=wlan0 mask=0x3
,D/TimaKeyStoreProvider( 7153): Cannot add TimaSignature Service, License check Failed
,D/ConnectivityService( 2404): resetConnections(wlan0, 3)
D/ActivityThread( 7153): Added TimaKesytore provider
,V/NativeCrypto( 2854): Read error: ssl=0x7bb75540: I/O error during system call, Connection timed out
,V/NativeCrypto( 2854): SSL shutdown failed: ssl=0x7bb75540: I/O error during system call, Broken pipe
,E/SPPClientService( 5515): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5515): [e] exceptionCaught(). NET_TIMEOUT
D/dalvikvm( 7153): GC_CONCURRENT freed 2985K, 32% free 9581K/13996K, paused 4ms+3ms, total 32ms
,D/dalvikvm( 7153): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 7153): WAIT_FOR_CONCURRENT_GC blocked 1ms
,E/SPPClientService( 5515): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5515): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5515): [b] ResponseMap empty
,I/chromium( 7104): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService( 2404): handleInetConditionChange: no active default network - ignore
,V/NetworkStats( 2404): updateIfacesLocked()
D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
,V/NetworkStats( 2404): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
V/NetworkStats( 2404): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/System.out( 7153): Inside WakeupProvider
,I/System.out( 7153): Inside onCreate() of WakeupTriggerProvide
,V/NetworkStats( 2404): performPollLocked() took 27ms
D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
,I/VlingoApplication( 7153): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7153): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7153): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2832): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2832): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2832): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 2832): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 7153): initQueue()
I/ActivityManager( 2404): Killing 6165:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2832): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2832): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2832): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2832): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2404): Tethering got CONNECTIVITY_ACTION
,I/ApplicationPolicy( 2404): updateDataUsageMap
,D/Tethering( 2404): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2404): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2404): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6576): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6576): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6576): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6576): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 4732): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6576): noConnectivity : true
,D/libgps  ( 2404): agps_ril_update_network_state: Waiting for IPC connection...
,I/wpa_supplicant( 3979): nl80211: Received scan results (3 BSSes)
,I/wpa_supplicant( 3979): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3979): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3979): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
I/SELinux ( 7183): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7183):  
,D/Tethering( 2404): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2404): interfaceStatusChanged wlan0, true
,I/SELinux ( 7183): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7183):  
I/SELinux ( 7183):  
,I/SELinux ( 7183): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7183): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7183): >>>>> Normal User
E/dalvikvm( 7183): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7183): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2404): stay LED for fully charged
D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/TimaKeyStoreProvider( 7183): in addTimaSignatureService
D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/TimaKeyStoreProvider( 7183): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7183): Added TimaKesytore provider
,I/wpa_supplicant( 3979): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2404): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2404): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3979): Associated with C0.AA.48
D/Tethering( 2404): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2404): interfaceStatusChanged wlan0, true
D/Tethering( 2404): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2404): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3979): freq(2412) increment count 2
,I/wpa_supplicant( 3979): meet head of list.
,I/wpa_supplicant( 3979): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3979): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3979): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3979): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3979): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2404): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2404): interfaceStatusChanged wlan0, true
,D/WifiNative( 2404): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/dalvikvm( 7183): GC_CONCURRENT freed 2989K, 32% free 9575K/13992K, paused 12ms+2ms, total 52ms
,D/dalvikvm( 7183): WAIT_FOR_CONCURRENT_GC blocked 34ms
,I/ActivityManager( 2404): Killing 6236:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/WifiP2pService( 2404): InactiveState{ what=143375 }
,D/WifiP2pService( 2404): P2pEnabledState{ what=143375 }
,I/SELinux ( 7200): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7200):  
,I/SELinux ( 7200): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7200):  
I/SELinux ( 7200):  
,I/SELinux ( 7200): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7200): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7200): >>>>> Normal User
,E/dalvikvm( 7200): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7200): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7200): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7200): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7200): Added TimaKesytore provider
,I/dhcpcd  ( 7212): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7212): bssid match
,D/dalvikvm( 7200): GC_CONCURRENT freed 3000K, 32% free 9566K/13992K, paused 3ms+3ms, total 41ms
,D/dalvikvm( 7200): WAIT_FOR_CONCURRENT_GC blocked 37ms
,I/ActivityManager( 2404): Killing 6319:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7219): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7219):  
,I/SELinux ( 7219): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7219):  
I/SELinux ( 7219):  
,I/SELinux ( 7219): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7219): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7219): >>>>> Normal User
,E/dalvikvm( 7219): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7219): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7219): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7219): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7219): Added TimaKesytore provider
,D/dalvikvm( 7219): GC_CONCURRENT freed 3004K, 32% free 9566K/13996K, paused 5ms+2ms, total 30ms
,D/dalvikvm( 7219): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/libgps  ( 2404): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2404): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2404): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2404): agps_ril_update_network_availability: Waiting for IPC connection...
,D/KLMS-2.3.201 : ( 7219): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7219): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449756875703,
,I/KLMS-2.3.201 : ( 7219): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2404): Killing 6325:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7231): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7231):  
,I/SELinux ( 7231): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7231):  
I/SELinux ( 7231):  
,I/SELinux ( 7231): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7231): [DEBUG] seapp_context_lookup: seinfoCategory = release
,E/dalvikvm( 7231): >>>>> Normal User
,E/dalvikvm( 7231): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7231): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7231): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7231): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7231): Added TimaKesytore provider
,D/dalvikvm( 7231): GC_CONCURRENT freed 3011K, 32% free 9552K/13992K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 7231): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/SO_AGENT( 7231): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7231): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5783): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5783): [BDLM] already registered in spp
I/SA      ( 5783): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5783): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5783): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5783): [OR] == isSIMCardReady false ==
I/SA      ( 5783): [SCU] == networkStateCheck == false
,I/SA      ( 5783): [OR] onReceive END
I/ActivityManager( 2404): Killing 5561:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SELinux ( 7243): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7243):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 14% free 9500K/10972K, paused 4ms+5ms, total 44ms
,I/SELinux ( 7243): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7243):  
I/SELinux ( 7243):  
,I/SELinux ( 7243): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7243): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7243): >>>>> Normal User
,E/dalvikvm( 7243): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7243): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9500K/10972K, paused 3ms+5ms, total 36ms
,D/TimaKeyStoreProvider( 7243): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7243): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7243): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9500K/10972K, paused 3ms+5ms, total 36ms
,D/dalvikvm( 7243): GC_CONCURRENT freed 2997K, 32% free 9567K/13992K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 7243): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/sCloudBackupApp( 7243): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7243): Other Intent
I/ActivityManager( 2404): Killing 6287:com.sec.phone/1001 (adj 15): empty #43
,I/SELinux ( 7256): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7256):  
,I/SELinux ( 7256): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7256):  
I/SELinux ( 7256):  
,I/SELinux ( 7256): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7256): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7256): >>>>> Normal User
,E/dalvikvm( 7256): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7256): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7256): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7256): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7256): Added TimaKesytore provider
,D/dalvikvm( 7256): GC_CONCURRENT freed 2997K, 32% free 9571K/13996K, paused 4ms+2ms, total 31ms
,D/dalvikvm( 7256): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/com.samsung.app( 7256): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE,
,D/com.samsung.app( 7256): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
D/com.samsung.app( 7256): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7256): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7256): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7256): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5312): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/libgps  ( 2404): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2404): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2404): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/com.samsung.app( 7256): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5312): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7256): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5312): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7256): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7256): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/ActivityManager( 2404): Killing 6305:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,D/dalvikvm( 2404): GC_CONCURRENT freed 4232K, 71% free 25440K/87168K, paused 12ms+31ms, total 321ms
,D/Headlines( 5849): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5849): getCountryCode(): countryCode = PL
,D/Headlines( 5849): Breath.onCreate
,D/Headlines( 5849): Breath timer started. interval : 30000
,I/SELinux ( 7275): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7275):  
,V/AlarmManager( 2404): waitForAlarm result :8,
,D/Headlines( 5849): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5849): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5849): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5849): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5849): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5849): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5849): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7275): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7275):  
I/SELinux ( 7275):  
,I/SELinux ( 7275): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7275): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7275): >>>>> Normal User
,E/dalvikvm( 7275): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7275): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7275): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7275): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7275): Added TimaKesytore provider
,D/dalvikvm( 7275): GC_CONCURRENT freed 2994K, 32% free 9569K/13988K, paused 2ms+1ms, total 25ms
,D/dalvikvm( 7275): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/jxcore-log( 7104): Connected to the server!
I/jxcore-log( 7104): 
,I/chromium( 7104): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,V/WebViewChromium( 7275): Binding Chromium to the background looper Looper (main, tid 1) {4278e308}
,I/chromium( 7275): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7275): Initializing chromium process, renderers=0
,W/chromium( 7275): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7275): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7275): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7275): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7275): Mali API Version : 401,
,I/Mali    ( 7275): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 ,
,D/PackageManager( 2404): [MSG] WRITE_PACKAGE_RESTRICTIONS
D/WifiP2pService( 2404): InactiveState{ what=143375 }
,D/WifiP2pService( 2404): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2404): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
,D/WifiStateMachine( 2404): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2404): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2404): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2404): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2404): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2404): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2404): evaluateTrafficStatsPolling
D/ConnectivityService( 2404): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2404): net.tcp.usercfg.wifi not found in system properties. Using defaults
,E/ConnectivityService( 2404): net.tcp.delack.wifi not found in system properties. Using defaults
W/GAV2    ( 7275): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,W/ContextImpl( 7275): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2404): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/NetworkStats( 2404): updateIfacesLocked()
,D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
V/NetworkStats( 2404): performPollLocked(flags=0x1)
V/NetworkStats( 2404): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
V/NetworkStats( 2404): performPollLocked() took 20ms
,D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
,I/NSApplication( 7275): Starting up...
,I/iu.Environment( 5913): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5133): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5133): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5133): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4279b350
,I/SELinux ( 7350): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7350):  
,I/SELinux ( 7350): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7350):  
I/SELinux ( 7350):  
,I/SELinux ( 7350): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7350): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7350): >>>>> Normal User
,E/dalvikvm( 7350): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7350): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7350): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7350): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7350): Added TimaKesytore provider
,D/dalvikvm( 7350): GC_CONCURRENT freed 2997K, 32% free 9572K/13996K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 7350): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/RCPManagerService( 2404): exchangeData() failure , invalid userId
,D/RCPManagerService( 2404): exchangeData() failure , invalid userId
,D/RCPManagerService( 2404): exchangeData() failure , invalid userId
,D/Tethering( 2404): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2404): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2404): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4732): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/libgps  ( 2404): agps_ril_update_network_state: Waiting for IPC connection...
,D/RCPManagerService( 2404): exchangeData() failure , invalid userId
,I/SELinux ( 7370): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7370):  
,D/RCPManagerService( 2404): exchangeData() failure , invalid userId
,D/RCPManagerService( 2404): exchangeData() failure , invalid userId
W/ActivityManager( 2404): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager( 2404): Killing 5983:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7374): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7374):  
,I/SELinux ( 7370): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7370):  
I/SELinux ( 7370):  
,I/SELinux ( 7370): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7370): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7370): >>>>> Normal User
,E/dalvikvm( 7370): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7370): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7370): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7370): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7370): Added TimaKesytore provider
,I/SELinux ( 7374): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7374):  
I/SELinux ( 7374):  
,I/SELinux ( 7374): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7374): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7374): >>>>> Normal User
,E/dalvikvm( 7374): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7374): [DEBUG] seapp_context_lookup: seinfoCategory = shared
I/ActivityManager( 2404): Killing 6255:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7374): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7374): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7374): Added TimaKesytore provider
,D/dalvikvm( 7370): GC_CONCURRENT freed 3001K, 32% free 9563K/13992K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 7370): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/BadgeProvider( 7370): onCreate
,D/BadgeProvider( 7370): DatabaseHelper
,D/BadgeProvider( 7370): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/dalvikvm( 7374): GC_CONCURRENT freed 2999K, 32% free 9563K/13992K, paused 6ms+5ms, total 36ms
,D/dalvikvm( 7374): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/BadgeProvider( 7370): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7370): sendNotify, [notify] : null
D/BadgeProvider( 7370): update, [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 2771): reloadBadges entered.
D/BadgeProvider( 7370): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7370): update, [UpdateCount] : 1
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 330, Delta = 10
,D/AmoledAdjustTimer( 2404): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,D/hcjo    ( 5955): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5955): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5955): exit::IDLE
,D/InitializeManagerStateMachine( 5955): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5955): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 5955): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5955): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5955): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5955): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5955): entry::SUCCESS
,D/hcjo    ( 5955): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5955): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5955): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5955): exit::SUCCESS
,D/InitializeManagerStateMachine( 5955): entry::IDLE
,E/SPPClientService( 5515): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5515): [SystemStateMoniter] Current Time : 270628
,E/SPPClientService( 5515): [SystemStateMoniter] No Connect : true
,I/jxcore-log( 7104): BLE advertisement not supported: Build version is 19
I/jxcore-log( 7104): 
,E/SPPClientService( 5515): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2832): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2832): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2832): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5515): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5515): [a] [ConnectionManager] Connection is already disconnected.
,D/Headlines( 5849): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5849): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5849): Breath 1730 latestRequest time : 1449756876820 current time : 1449756878551
I/ActivityManager( 2404): Killing 6152:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,E/SPPClientService( 5515): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2832): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5515): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2832): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2832): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5515): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,I/SurfaceFlinger( 1921): id=20 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 2404): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2404
E/SPPClientService( 5515): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2832): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5515): [g] getNetMCC return empty string
,I/PCWCLIENTTRACE_PushUtil( 6576): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6576): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6576): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6576): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.3.201 : ( 7219): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/libgps  ( 2404): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2404): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2404): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2404): agps_ril_update_network_availability: Waiting for IPC connection...
,I/KLMS-2.3.201 : ( 7219): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449756879026
,I/KLMS-2.3.201 : ( 7219): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7231): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3298): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3298): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3298): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3298): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7231): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/SELinux ( 7405): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7405):  
,I/GallerySearchProvider( 3426): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7409): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7409):  
,I/SELinux ( 7405): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7405):  
I/SELinux ( 7405):  
,I/SELinux ( 7405): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7405): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7405): >>>>> Normal User
,E/dalvikvm( 7405): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7405): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/WifiP2pStateTracker( 2404): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/TimaKeyStoreProvider( 7405): in addTimaSignatureService
,D/ConnectivityService( 2404): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2404):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2404): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2404): updateSourceRoutes : no source routing conditions
,D/TimaKeyStoreProvider( 7405): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7405): Added TimaKesytore provider
,I/SELinux ( 7409): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7409):  
I/SELinux ( 7409):  
,I/SELinux ( 7409): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7409): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7409): >>>>> Normal User
,E/dalvikvm( 7409): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7409): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7409): in addTimaSignatureService
,D/dalvikvm( 2721): GC_EXPLICIT freed 334K, 29% free 10039K/13980K, paused 13ms+8ms, total 127ms
,D/TimaKeyStoreProvider( 7409): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7409): Added TimaKesytore provider
,D/dalvikvm( 7405): GC_CONCURRENT freed 2985K, 32% free 9581K/13996K, paused 5ms+2ms, total 39ms
,D/dalvikvm( 7405): WAIT_FOR_CONCURRENT_GC blocked 34ms
,I/SA      ( 5783): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5783): [BDLM] already registered in spp
I/SA      ( 5783): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5783): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5783): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5783): [OR] == isSIMCardReady false ==
,I/SA      ( 5783): [SCU] == networkStateCheck == true
I/SA      ( 5783): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5783): isChinaCountryCode : false
,I/SA      ( 5783): [OR] == networkStateCheck true ==
,I/SA      ( 5783): [OR] GetMyCountryZoneTask
,I/SA      ( 5783): [OR] onReceive END
,I/SA      ( 5783): [SRS] prepareGetMyCountryZone
,D/dalvikvm( 7409): GC_CONCURRENT freed 2994K, 32% free 9564K/13988K, paused 3ms+2ms, total 22ms
I/SA      ( 5783): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,D/dalvikvm( 7409): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/SA      ( 5783): [SSP] query invoked
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
I/SA      ( 5783): [TPMU] GetMccFromDB : null
I/SA      ( 5783): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5783): [TPM] isNoProxy(default) : true
,I/SA      ( 5783): [RC New] Execute method=[GET] start
,I/SCloudBackupReceiver( 7243): Other Intent
,D/com.samsung.app( 7256): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7256): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/System.out( 7200): Thread-630(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/Headlines( 5849): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5849): getCountryCode(): countryCode = PL
,I/System.out( 7200): Thread-630(ApacheHTTPLog):isShipBuild true
,I/System.out( 7200): Thread-630(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/Headlines( 5849): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5849): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5849): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5849): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5849): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5849): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5849): requestUpdateNewsWelcomeCard !!! no welcome card
,V/KVNProvider( 7409): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7409): getFindoCursor query string : 
,I/iu.Environment( 5913): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,V/KVNProvider( 7409): getTagSearchCursor() tagSearchCursor count : 0
,D/QuickConnect[1.1][2] ( 5133): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5133): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5133): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4279b350
,D/RCPManagerService( 2404): exchangeData() failure , invalid userId
,D/RCPManagerService( 2404): exchangeData() failure , invalid userId
,D/hcjo    ( 5955): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 5955): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5955): exit::IDLE
,D/InitializeManagerStateMachine( 5955): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5955): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5955): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5955): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5955): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5955): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5955): entry::SUCCESS
,D/hcjo    ( 5955): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5955): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5955): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5955): exit::SUCCESS
,D/InitializeManagerStateMachine( 5955): entry::IDLE
,E/SPPClientService( 5515): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5515): [SystemStateMoniter] Current Time : 271738
,E/SPPClientService( 5515): [SystemStateMoniter] No Connect : false
,I/System.out( 7200): AsyncTask #1 calls detatch()
,W/System.err( 7200): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7200): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7200): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7200): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7200): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 7200): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7200): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7200): Caused by: java.lang.NullPointerException
W/System.err( 7200): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7200): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7200): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7200): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7200): 	... 8 more
,I/ActivityManager( 2404): Killing 6189:com.google.android.music:main/u0a125 (adj 15): empty #43
,D/dalvikvm( 5515): GC_CONCURRENT freed 2018K, 26% free 10448K/13980K, paused 7ms+5ms, total 50ms
,D/dalvikvm( 5515): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/libgps  ( 2404): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2404): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2404): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/SA      ( 5783): [RC New] [v2liruge] api execute + 784
,I/SA      ( 5783): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5783): AsyncTask #2 calls detatch()
,I/SA      ( 5783): [TPMU] getNetworkMcc : 
,I/SA      ( 5783): [SCU] saveMccToPreferece Start
,I/SA      ( 5783): [SCU] RegionMCC : 260
,I/SA      ( 5783): [SSP] query invoked
I/SA      ( 5783): [TPMU] GetMccFromDB : null
,I/SA      ( 5783): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5783): [SCU] saveMccToPreferece End
,I/SA      ( 5783): [RC New] executeRequest [v2liruge] end. 816
I/SA      ( 5783): [RC New] Execute end
I/SA      ( 5783): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5783): [OR] GetMyCountryZoneTask Success
,E/WifiStateMachine( 2404): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/SPPClientService( 5515): [b] __InitReply__
,I/SurfaceFlinger( 1921): id=20 Removed Uoast (10/11)
,I/ActivityManager( 2404): Killing 6520:com.android.defcontainer/u0a6 (adj 15): empty #43
I/SurfaceFlinger( 1921): id=20 Removed Uoast (-2/11)
,D/PowerManagerService( 2404): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2404) eventTime = 274339
,D/PowerManagerService( 2404): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2404 (0x0)
,D/PowerManagerService( 2404): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2404, ws=WorkSource{1000}) (elapsedTime=3477)
,I/GAV2    ( 7275): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6576): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6576): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6576): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6576): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6576): GetString : secure API is not supported!!
,I/PCWCLIENTTRACE_PushUtil( 6576): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6576): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6576): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6576): [ensureRegistration] - No Samsung account
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2404): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/CaptivePortalTracker( 2404): DelayedCaptiveCheckState{ when=0 what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
D/ConnectivityService( 2404): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2404): Checking http://216.58.209.46/generate_204,
,D/CaptivePortalTracker( 2404): Don't send network conditions - lacking user consent.,
D/CaptivePortalTracker( 2404): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2404): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2404): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
D/ConnectivityService( 2404): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 297, currTemp = 299, prevStep = 4, currStep = 4,
,D/PreloadUpdateManagerStateMachine( 5955): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5955): exit::IDLE,
,D/PreloadUpdateManagerStateMachine( 5955): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5955): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5955): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5955): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5955): entry::IDLE,
,D/PreloadUpdateManagerStateMachine( 5955): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 5955): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5955): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 5955): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5955): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 5955): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5955): entry::IDLE,
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/ActivityManager( 2404): Waited long enough for: ServiceRecord{46f246d8 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,I/ActivityManager( 2404): Waited long enough for: ServiceRecord{46776bf8 u0 com.sec.spp.push/.PushClientService},
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
D/BatteryService( 2404): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2404): !@Sync 9,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2404): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,V/AlarmManager( 2404): waitForAlarm result :8,
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,I/PowerManagerService( 2404): [PWL] Off : 225s ago,
,V/AlarmManager( 2404): waitForAlarm result :8,
,D/Headlines( 5849): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5849): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5849): Breath 27370 latestRequest time : 1449756879468 current time : 1449756906838,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,W/ProcessCpuTracker( 2404): Skipping unknown process pid 7634,
W/ProcessCpuTracker( 2404): Skipping unknown process pid 7639
,W/ProcessCpuTracker( 2404): Skipping unknown process pid 7644
,W/ProcessCpuTracker( 2404): Skipping unknown process pid 7649
,W/ProcessCpuTracker( 2404): Skipping unknown process pid 7652,
W/ProcessCpuTracker( 2404): Skipping unknown process pid 7654,
,W/ProcessCpuTracker( 2404): Skipping unknown process pid 7655
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3997): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4,
,D/TimaService( 2404): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 2404): TimaServiceHandler.handleMessage what =1
,D/TimaService( 2404): TIMA: checkEvent, operation: 50000 subject: 10000,
,I/TLC_TIMA_PKM_initialize( 2404): initializing...,
I/TLC_TIMA_PKM_initialize( 2404): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2404): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2404): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2404): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 2404): root = 0, root_len = 1,
I/TZ: mc_tlc_communication( 2404): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2404): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2404): aligned max_recvmsg_size = 262208,
I/TZ: mc_tlc_communication( 2404): device_id = 0x0
,I/TZ: mc_tlc_communication( 2404): tlc_open() was called
,I/TZ: mc_tlc_communication( 2404): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2404): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 2404): Opening the session,
,I/TZ: mc_tlc_communication( 2404): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2404): Trustlet response is completed,
,W/ProcessCpuTracker( 2404): Skipping unknown process pid 7778
,E/Watchdog( 2404): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2404): waitForAlarm result :8,
,D/Headlines( 5849): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5849): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5849): Breath 57366 latestRequest time : 1449756879468 current time : 1449756936834,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4,
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2404): [PWL] Off : 275s ago,
,E/Watchdog( 2404): !@Sync 11,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,V/AlarmManager( 2404): waitForAlarm result :8,
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,V/AlarmManager( 2404): waitForAlarm result :4,
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
I/SELinux ( 8012): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8012):  
,I/SELinux ( 8012): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 8012):  
I/SELinux ( 8012):  
,I/SELinux ( 8012): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 8012): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 8012): >>>>> Normal User
,E/dalvikvm( 8012): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 8012): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 8012): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8012): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 8012): Added TimaKesytore provider,
,D/dalvikvm( 8012): GC_CONCURRENT freed 2999K, 32% free 9566K/13996K, paused 3ms+2ms, total 28ms,
,D/dalvikvm( 8012): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/ActivityManager( 2404): Killing 6440:com.google.android.partnersetup/u0a14 (adj 15): empty #43,
,V/AlarmManager( 2404): waitForAlarm result :8,
,D/Headlines( 5849): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5849): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5849): Breath 87363 latestRequest time : 1449756879468 current time : 1449756966831,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2404): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 12
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2404): waitForAlarm result :8
,D/Headlines( 5849): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5849): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5849): Breath 117374 latestRequest time : 1449756879468 current time : 1449756996842
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2404): !@Sync 13
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2404): waitForAlarm result :8
,D/Headlines( 5849): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5849): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5849): Breath 147367 latestRequest time : 1449756879468 current time : 1449757026835
,D/Headlines( 5849): stop 
,D/Headlines( 5849): Breath.onDestroy : 
,I/ActivityManager( 2404): Killing 6549:com.samsung.groupcast/u0a15 (adj 15): empty #43
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 14
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2404): !@Sync 15
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2404): GC_CONCURRENT freed 4021K, 71% free 25371K/86896K, paused 11ms+19ms, total 225ms
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 16
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2404): [PWL] Off : 455s ago
,E/Watchdog( 2404): !@Sync 17
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 292, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 18
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2404): !@Sync 19
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2404): [PWL] Off : 525s ago
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2404): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/TimaService( 2404): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2404): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2404): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2404): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2404): !@Sync 21
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2404): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 10
,D/AmoledAdjustTimer( 2404): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2404): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/GAV2    ( 5605): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5605): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2404): !@Sync 22
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 23
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2404): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2404): <AppSync3 Whitelist>
,V/AlarmManager( 2404): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 24
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 25
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4071): GC_CONCURRENT freed 2891K, 31% free 9723K/14040K, paused 7ms+4ms, total 78ms
,W/ProcessCpuTracker( 2404): Skipping unknown process pid 9329
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 26
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,I/SensorManagerA( 2404): getReportingMode :: sensor.mType = 5
,D/LightsService( 2404): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/Sensors ( 2404): LightSensor setDelay = 200000000
D/Sensors ( 2404): LightSensor setSensorDelay = 200000000
D/Sensors ( 2404): Light sensor flush: not enabled 0
D/Sensors ( 2404): LightSensor enable = 1
D/Sensors ( 2404): LightSensor enableSensor = 1
D/SensorManager( 2404): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,E/SPPClientService( 5515): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/Sensors ( 2404): LightSensor enable = 0
,D/Sensors ( 2404): LightSensor enableSensor = 0
D/LightsService( 2404): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2404): unregisterListener ::   
D/LightsService( 2404): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 27
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2404): [PWL] Off : 765s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 28
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 29
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/TimaService( 2404): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2404): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2404): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ProcessCpuTracker( 2404): Skipping unknown process pid 9784
,E/Watchdog( 2404): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/dalvikvm( 2404): GC_CONCURRENT freed 3969K, 71% free 25278K/86896K, paused 23ms+20ms, total 284ms
,I/PowerManagerService( 2404): [PWL] Off : 855s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 31
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 32
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 33
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 288, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 950s ago
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 34
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 35
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 36
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :4
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5515): [b] __PingReply__
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 37
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2404): stay LED for fully charged
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 38
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2404): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2404): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 39
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/TimaService( 2404): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2404): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2404): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,W/ProcessCpuTracker( 2404): Skipping unknown process pid 10666
,W/ProcessCpuTracker( 2404): Skipping unknown process pid 10671
W/ProcessCpuTracker( 2404): Skipping unknown process pid 10679
W/ProcessCpuTracker( 2404): Skipping unknown process pid 10681
,W/ProcessCpuTracker( 2404): Skipping unknown process pid 10682
,E/Watchdog( 2404): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 41
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 42
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 43
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2404): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2404): <AppSync3 Whitelist>
,V/AlarmManager( 2404): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 1265s ago
,E/Watchdog( 2404): !@Sync 44
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 45
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2404): GC_CONCURRENT freed 3955K, 71% free 25285K/86896K, paused 10ms+16ms, total 213ms
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 46
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 47
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 48
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 49
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4071): GC_CONCURRENT freed 2050K, 31% free 9720K/14040K, paused 6ms+5ms, total 55ms
,D/dalvikvm( 4071): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :4
,I/SensorManagerA( 2404): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2404): LightSensor setDelay = 200000000
,D/Sensors ( 2404): LightSensor setSensorDelay = 200000000
,D/LightsService( 2404): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2404): Light sensor flush: not enabled 0
D/Sensors ( 2404): LightSensor enable = 1
D/Sensors ( 2404): LightSensor enableSensor = 1
D/SensorManager( 2404): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/PeopleSync( 3159): onPerformSync() [5005f081]
,D/Sensors ( 2404): LightSensor enable = 0
,D/Sensors ( 2404): LightSensor enableSensor = 0
,D/SensorManager( 2404): unregisterListener ::   
D/LightsService( 2404): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2404): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/PeopleSync( 3159): Setting subscription: result=true [5005f081]
,I/PeopleSync( 3159): Starting sync, feed=null [5005f081]
,D/dalvikvm( 3159): GC_CONCURRENT freed 1868K, 21% free 12518K/15812K, paused 8ms+10ms, total 90ms
,W/BaseAppContext( 3159): Using Auth Proxy for data requests.
,W/BaseAppContext( 3159): Using Auth Proxy for data requests.
,W/BaseAppContext( 3159): Using Auth Proxy for data requests.
,I/PeopleSync( 3159): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NativeCrypto( 2854): SSL shutdown failed: ssl=0x7bb7f2d8: I/O error during system call, Connection timed out
,V/NativeCrypto( 3159): SSL shutdown failed: ssl=0x8381dcf0: I/O error during system call, Connection timed out
,E/Volley  ( 3159): [129] BasicNetwork.performRequest: Unexpected response code 410 for https://www.googleapis.com/plus/v2whitelisted/people/me/people/all?prettyPrint=false&fields=items(etag,id,names,nicknames,images,urls,sortKeys,taglines,emails,phoneNumbers,addresses,metadata,memberships,legacyFields/mobileOwnerId),nextPageToken,nextSyncToken&customResponseMaskingType=menagerie&includeAffinity=gplusAutocomplete&includeAffinity=chatAutocomplete&includeAffinity=emailAutocomplete&includeOthers=true&maxResults=100&orderBy=modified&syncToken=CPzwkZCYKhIBMRjbEioECAEQAQ
,I/PeopleSync( 3159): Sync Token out of date, syncing all people/gaia-map
,D/TimaService( 2404): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2404): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2404): TimaServiceHandler.handleMessage what =1
,I/PeopleSync( 3159): Sync finished, successful=true, took 2467ms
,I/PeopleContactsSync( 3159): CP2 sync start [5005f081]
,I/PeopleContactsSync( 3159): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/PeopleContactsSync( 3159): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/PeopleContactsSync( 3159): CP2 cleanup done, kept= duration=75 ms
,I/PeopleContactsSync( 3159): ===CP2 sync finished, success=true, time=103,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,I/PeopleSync( 3159): ***Sync finished***, duration: 3187 [5005f081]
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :4
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 51
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 52
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 53
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/ClearcutLoggerApiImpl( 3159): disconnect managed GoogleApiClient
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 54
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2404): !@Sync 55
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2404): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2404): [PWL] Off : 1625s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 56
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,E/SPPClientService( 5515): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2404): !@Sync 57
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2404): GC_CONCURRENT freed 3867K, 71% free 25343K/86896K, paused 14ms+17ms, total 233ms
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 58
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 59
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/TimaService( 2404): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2404): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2404): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/PowerManagerService( 2404): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 61
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2404): Prepared write state in 52ms
,I/ProcessStatsService( 2404): Prepared write state in 36ms
,I/ProcessStatsService( 2404): Pruning old procstats: /data/system/procstats/state-2015-12-09-18-52-56.bin
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 62
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 63
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2404): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2404): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
V/AlarmManager( 2404): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 64
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 65
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,I/ActivityManager( 2404): Killing 6434:com.sec.knox.bridge/1000 (adj 15): empty for 1818s
,I/ActivityManager( 2404): Killing 4849:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1818s
,I/ActivityManager( 2404): Killing 6420:com.google.android.googlequicksearchbox:search/u0a59 (adj 15): empty for 1818s
,I/ActivityManager( 2404): Killing 6396:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1828s
,I/ActivityManager( 2404): Killing 6737:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1828s
,I/ActivityManager( 2404): Killing 6723:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1829s
,I/ActivityManager( 2404): Killing 6711:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1829s
,I/ActivityManager( 2404): Killing 6699:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1829s
,I/ActivityManager( 2404): Killing 6685:com.samsung.helphub/1000 (adj 15): empty for 1829s
,I/ActivityManager( 2404): Killing 6673:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1830s
,I/ActivityManager( 2404): Killing 6660:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1830s
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2404): Killing 6647:com.sec.android.service.cm/u0a82 (adj 15): empty for 1830s
,I/ActivityManager( 2404): Killing 6352:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1830s
,I/ActivityManager( 2404): Killing 5675:com.android.mms/u0a49 (adj 15): empty for 1830s
,I/ActivityManager( 2404): Killing 6621:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1830s
,I/ActivityManager( 2404): Killing 5997:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1831s
,I/ActivityManager( 2404): Killing 6591:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty for 1831s
,I/ActivityManager( 2404): Killing 6563:com.android.musicfx/u0a24 (adj 15): empty for 1831s
,D/CountryDetector( 2404): No listener is left
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 66
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 67
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2771): GC_CONCURRENT freed 9049K, 41% free 18072K/30344K, paused 14ms+6ms, total 77ms
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 68
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms)
```
