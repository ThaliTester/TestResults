#### Test 5357450766a890e_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
E/Watchdog( 2409): !@Sync 8
--------- beginning of /dev/log/main
D/AndroidRuntime( 7151): 
D/AndroidRuntime( 7151): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7151): CheckJNI is OFF
D/AndroidRuntime( 7151): setted country_code = Poland
D/AndroidRuntime( 7151): setted countryiso_code = PL
D/AndroidRuntime( 7151): setted sales_code = PLS
D/AndroidRuntime( 7151): readGMSProperty: start
D/AndroidRuntime( 7151): readGMSProperty: already setted!!
D/AndroidRuntime( 7151): readGMSProperty: end
D/AndroidRuntime( 7151): addProductProperty: start
D/dalvikvm( 7151): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7151): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7151): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7151): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7151): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7151): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7151): failed to load memtrack module: -2
D/dalvikvm( 7151): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7151): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2409): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2409): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2409  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2409): mDVFSHelper.acquire()
I/SELinux ( 7177): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7177):  
D/PointerIcon( 2409): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2409): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2409): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2409): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7151): Shutting down VM
D/dalvikvm( 7151): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 7177): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7177):  
I/SELinux ( 7177):  
I/SELinux ( 7177): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7177): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7177): >>>>> Normal User
E/dalvikvm( 7177): >>>>> com.test.thalitest [ userId:0 | appId:10538 ]
E/SELinux ( 7177): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7177): in addTimaSignatureService
D/TimaKeyStoreProvider( 7177): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7177): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4172): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4172): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7177): GC_CONCURRENT freed 3006K, 31% free 9564K/13792K, paused 2ms+1ms, total 18ms
D/dalvikvm( 7177): WAIT_FOR_CONCURRENT_GC blocked 17ms
V/WebViewChromium( 7177): Binding Chromium to the background looper Looper (main, tid 1) {42282268}
I/chromium( 7177): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7177): Initializing chromium process, renderers=0
W/chromium( 7177): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7177): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7177): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7177): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7177): Mali API Version : 401
,I/Mali    ( 7177): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7177): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7177): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7177): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7177): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7177): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7177): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2582): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2409): tr p:7177,o:f
,W/dalvikvm( 7177): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7177): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7177): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7177): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7177): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7177): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7177): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7177): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 7177): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7177): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7177): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7177): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7177): CordovaWebView is running on device made by: samsung
D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 0
,D/PhoneStatusBar( 2582): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2409): semi p:7177,o:f
,I/SurfaceFlinger( 1921): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2409): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2409): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2409): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2409): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2409): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2409): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7177): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7177): Enabling debug mode 0
,W/AwContents( 7177): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7177): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2409): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2409  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2409): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2409): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2409  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/JsMessageQueue( 7177): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7177): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4227a7e0
,D/dalvikvm( 7177): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4227a7e0
D/jxcore_app_log( 7177): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2030884936
,D/JX-Cordova( 7177): jxcore cordova android initializing
,D/AmoledAdjustTimer( 2409): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4
,D/dalvikvm( 7177): GC_CONCURRENT freed 1285K, 19% free 11353K/13856K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 7177): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 7177): GC_CONCURRENT freed 1931K, 18% free 14922K/18092K, paused 1ms+2ms, total 38ms
,D/dalvikvm( 7177): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/CustomFrequencyManagerService( 2409): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2409  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7177): GC_FOR_ALLOC freed 5406K, 30% free 16228K/23076K, paused 51ms, total 51ms
,D/dalvikvm( 7177): GC_CONCURRENT freed 6619K, 31% free 17696K/25640K, paused 1ms+13ms, total 76ms
,D/dalvikvm( 7177): WAIT_FOR_CONCURRENT_GC blocked 71ms
,D/dalvikvm( 7177): GC_FOR_ALLOC freed 1592K, 33% free 17414K/25640K, paused 59ms, total 63ms
,I/dalvikvm-heap( 7177): Grow heap (frag case) to 21.787MB for 3767174-byte allocation
,D/dalvikvm( 7177): GC_FOR_ALLOC freed 5K, 29% free 21087K/29320K, paused 55ms, total 55ms
,W/jxcore-log( 7177): Initializing JXcore engine
,W/jxcore-log( 7177): JXcore engine is ready
,W/jxcore-log( 7177): Starting JXcore engine
,W/jxcore-log( 7177): Platform android
W/jxcore-log( 7177): 
,W/jxcore-log( 7177): Process ARCH arm
W/jxcore-log( 7177): 
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7177): JXcore Cordova bridge is ready!
I/jxcore-log( 7177): 
,W/jxcore-log( 7177): JXcore engine is started
,I/chromium( 7177): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7177): Toggling radios to true
I/jxcore-log( 7177): 
,D/BluetoothAdapter( 7177): enable(): BT is already enabled..!
,I/WifiManager( 7177): packageName : com.test.thalitest
,I/WifiManager( 7177): setWifiEnabled : true
,I/WifiService( 2409): setWifiEnabled: true pid=7177, uid=10538
,W/ActivityManager( 2409): Permission Denial: getCurrentUser() from pid=7177, uid=10538 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2409): Failed getting userId using ActivityManagerNative
W/WifiService( 2409): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7177, uid=10538 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2409): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2409): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2409): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2409): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2409): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2409): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2409): disconnect: pid=7177, uid=10538
I/jxcore-log( 7177): Radios toggled
I/jxcore-log( 7177): 
I/wpa_supplicant( 3979): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3979): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3979): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2409): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2409): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3979): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3979): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3979): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3979): First Scan Start
,I/wpa_supplicant( 3979): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering( 2409): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2409): interfaceStatusChanged wlan0, true
,W/Settings( 2409): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2409): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2409): InactiveState{ what=143375 }
D/WifiP2pService( 2409): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/wpa_supplicant( 3979): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3979): Skip scan - already scanning
,I/WifiTrafficPoller( 2409): evaluateTrafficStatsPolling
D/ConnectivityService( 2409): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/WifiP2pService( 2409): InactiveState{ what=143375 }
D/WifiP2pService( 2409): P2pEnabledState{ what=143375 }
D/ConnectivityService( 2409): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2409): net.tcp.usercfg.default not found in system default properties
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
E/ConnectivityService( 2409): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2409): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2409): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
,D/ConnectivityService( 2409): Attempting to switch to mobile
,D/ConnectivityService( 2409): Attempting to switch to BLUETOOTH_TETHER
,I/SELinux ( 7225): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7225):  
D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
,V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,I/SELinux ( 7225): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7225):  
I/SELinux ( 7225):  
,I/SELinux ( 7225): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/WifiStateMachine( 2409): Error! unhandled message{ when=-80ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2409): Error! unhandled message{ when=-80ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiTrafficPoller( 2409): evaluateTrafficStatsPolling
E/SELinux ( 7225): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7225): >>>>> Normal User
,E/dalvikvm( 7225): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7225): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,W/NetworkManagementService( 2409): route cmd failed: 
W/NetworkManagementService( 2409): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '36 route del src v6 2' failed with '400 36 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2409): '
W/NetworkManagementService( 2409): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2409): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2409): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2409): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2409): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2409): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2409): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2409): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2409): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2409): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2409): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2409): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2409): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1
,E/WifiStateMachine( 2409): Error! unhandled message{ when=-6ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 7225): in addTimaSignatureService
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 7225): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7225): Added TimaKesytore provider
,D/NetUtils( 2409): android_net_utils_resetConnections in env=0x78124ad0 clazz=0x61a00001 iface=wlan0 mask=0x3
D/ConnectivityService( 2409): resetConnections(wlan0, 3)
,E/SPPClientService( 5514): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,D/dalvikvm( 7225): GC_CONCURRENT freed 2985K, 31% free 9582K/13792K, paused 4ms+2ms, total 28ms
,D/dalvikvm( 7225): WAIT_FOR_CONCURRENT_GC blocked 19ms
,V/NativeCrypto( 2854): Read error: ssl=0x7b9ee398: I/O error during system call, Connection timed out
,V/NativeCrypto( 2854): SSL shutdown failed: ssl=0x7b9ee398: I/O error during system call, Broken pipe
,E/SPPClientService( 5514): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5514): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5514): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5514): [b] ResponseMap empty
,D/ConnectivityService( 2409): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
V/NetworkStats( 2409): updateIfacesLocked()
V/NetworkStats( 2409): performPollLocked(flags=0x1)
V/NetworkStats( 2409): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
V/NetworkStats( 2409): performPollLocked() took 23ms
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,I/System.out( 7225): Inside WakeupProvider
,I/System.out( 7225): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 7225): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7225): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7225): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2835): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2835): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2835): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2409): Killing 6140:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/DialogFlow( 7225): initQueue()
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2835): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2835): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2835): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2409): Tethering got CONNECTIVITY_ACTION
I/ApplicationPolicy( 2409): updateDataUsageMap
,D/Tethering( 2409): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2409): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2409): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6551): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6551): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6551): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6551): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6551): noConnectivity : true
,I/DBG_DM  ( 4733): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2409): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7254): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7254):  
,I/SELinux ( 7254): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7254):  
I/SELinux ( 7254):  
,I/SELinux ( 7254): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/wpa_supplicant( 3979): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 3979): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3979): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3979): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
D/Tethering( 2409): interfaceLinkStateChanged wlan0, true
D/Tethering( 2409): interfaceStatusChanged wlan0, true
E/SELinux ( 7254): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7254): >>>>> Normal User
,E/dalvikvm( 7254): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7254): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7254): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7254): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7254): Added TimaKesytore provider
,I/wpa_supplicant( 3979): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2409): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2409): interfaceStatusChanged wlan0, true
D/Tethering( 2409): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2409): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3979): Associated with C0.AA.48
D/Tethering( 2409): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2409): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3979): freq(2412) increment count 2
,I/wpa_supplicant( 3979): meet head of list.
,I/wpa_supplicant( 3979): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3979): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3979): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3979): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3979): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2409): interfaceLinkStateChanged wlan0, true
D/Tethering( 2409): interfaceStatusChanged wlan0, true
D/WifiNative( 2409): callSECApiVoid - ID [50]
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/dalvikvm( 7254): GC_CONCURRENT freed 2996K, 31% free 9570K/13788K, paused 3ms+2ms, total 53ms
,D/dalvikvm( 7254): WAIT_FOR_CONCURRENT_GC blocked 40ms
,I/ActivityManager( 2409): Killing 6211:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/WifiP2pService( 2409): InactiveState{ what=143375 }
,D/WifiP2pService( 2409): P2pEnabledState{ what=143375 }
,I/SELinux ( 7268): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7268):  
,I/SELinux ( 7268): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7268):  
I/SELinux ( 7268):  
,I/SELinux ( 7268): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7268): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7268): >>>>> Normal User
,E/dalvikvm( 7268): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7268): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7268): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7268): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7268): Added TimaKesytore provider,
,I/dhcpcd  ( 7280): if(wlan0) info get Success. (MAC : C0.AA.48),
,I/dhcpcd  ( 7280): bssid match,
,D/dalvikvm( 7268): GC_CONCURRENT freed 2993K, 31% free 9574K/13792K, paused 29ms+2ms, total 52ms,
,D/dalvikvm( 7268): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/ActivityManager( 2409): Killing 6257:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43,
,I/SELinux ( 7287): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7287):  
,I/SELinux ( 7287): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7287):  
I/SELinux ( 7287):  
,I/SELinux ( 7287): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7287): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7287): >>>>> Normal User
,E/dalvikvm( 7287): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7287): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7287): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7287): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7287): Added TimaKesytore provider
,D/dalvikvm( 7287): GC_CONCURRENT freed 3003K, 31% free 9568K/13792K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7287): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/KLMS-2.3.201 : ( 7287): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7287): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450106536764
,I/KLMS-2.3.201 : ( 7287): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/libgps  ( 2409): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2409): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2409): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2409): agps_ril_update_network_availability: Waiting for IPC connection...,
I/ActivityManager( 2409): Killing 6281:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7299): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7299):  
,I/SELinux ( 7299): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7299):  
I/SELinux ( 7299):  
,I/SELinux ( 7299): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7299): [DEBUG] seapp_context_lookup: seinfoCategory = release,
E/dalvikvm( 7299): >>>>> Normal User
,E/dalvikvm( 7299): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ],
,E/SELinux ( 7299): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7299): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7299): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7299): Added TimaKesytore provider
,D/dalvikvm( 7299): GC_CONCURRENT freed 3000K, 31% free 9564K/13784K, paused 3ms+2ms, total 21ms,
,D/dalvikvm( 7299): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/SO_AGENT( 7299): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7299): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available,
,I/SA      ( 5775): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ],
,I/SA      ( 5775): [BDLM] already registered in spp
,I/SA      ( 5775): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5775): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5775): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5775): [OR] == isSIMCardReady false ==
I/SA      ( 5775): [SCU] == networkStateCheck == false
,I/SA      ( 5775): [OR] onReceive END
,I/ActivityManager( 2409): Killing 5558:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): Phone number locator feature is dsiabled
,I/SELinux ( 7311): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7311):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 12% free 9501K/10764K, paused 2ms+3ms, total 35ms
,I/SELinux ( 7311): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7311):  
I/SELinux ( 7311):  
,I/SELinux ( 7311): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7311): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7311): >>>>> Normal User
,E/dalvikvm( 7311): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7311): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9501K/10764K, paused 3ms+3ms, total 32ms
,D/TimaKeyStoreProvider( 7311): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7311): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7311): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9501K/10764K, paused 2ms+4ms, total 29ms
,D/dalvikvm( 7311): GC_CONCURRENT freed 2997K, 31% free 9576K/13792K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7311): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/sCloudBackupApp( 7311): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7311): Other Intent
I/ActivityManager( 2409): Killing 6245:com.sec.phone/1001 (adj 15): empty #43
,I/SELinux ( 7324): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7324):  
,I/SELinux ( 7324): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7324):  
I/SELinux ( 7324):  
,I/SELinux ( 7324): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7324): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7324): >>>>> Normal User
,E/dalvikvm( 7324): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7324): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7324): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7324): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7324): Added TimaKesytore provider
,D/dalvikvm( 7324): GC_CONCURRENT freed 2990K, 31% free 9569K/13784K, paused 4ms+1ms, total 28ms
,D/dalvikvm( 7324): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 2409): GC_CONCURRENT freed 4226K, 71% free 25408K/87024K, paused 10ms+26ms, total 277ms
,D/com.samsung.app( 7324): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7324): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7324): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7324): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7324): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7324): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5308): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7324): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5308): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7324): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5308): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7324): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7324): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2409): Killing 6302:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,D/Headlines( 5839): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5839): getCountryCode(): countryCode = PL
,D/Headlines( 5839): Breath.onCreate
,D/Headlines( 5839): Breath timer started. interval : 30000
,I/SELinux ( 7337): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7337):  
,D/Headlines( 5839): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5839): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,V/AlarmManager( 2409): waitForAlarm result :8
D/HeadlinesCardManager( 5839): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5839): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5839): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5839): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5839): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7337): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7337):  
I/SELinux ( 7337):  
,I/SELinux ( 7337): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7337): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7337): >>>>> Normal User
,E/dalvikvm( 7337): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7337): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7337): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7337): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7337): Added TimaKesytore provider
,D/libgps  ( 2409): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2409): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2409): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/dalvikvm( 7337): GC_CONCURRENT freed 2994K, 31% free 9571K/13784K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 7337): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,V/WebViewChromium( 7337): Binding Chromium to the background looper Looper (main, tid 1) {4227f390}
,D/BatteryService( 2409): stay LED for fully charged
,I/chromium( 7337): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
I/BrowserProcessMain( 7337): Initializing chromium process, renderers=0
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/chromium( 7337): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7337): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7337): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7337): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7337): Mali API Version : 401
,I/Mali    ( 7337): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,W/GAV2    ( 7337): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7337): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,D/WifiP2pService( 2409): InactiveState{ what=143375 }
,D/WifiP2pService( 2409): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2409): VerifyingLinkState enter
,I/NSApplication( 7337): Starting up...
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2409): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2409): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2409): evaluateTrafficStatsPolling
,I/iu.Environment( 5907): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/WifiStateMachine( 2409): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2409): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2409): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2409): evaluateTrafficStatsPolling
D/ConnectivityService( 2409): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2409): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2409): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,I/iu.SyncManager( 5907): SYNC; picasa accounts
,D/ConnectivityService( 2409): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,I/iu.UploadsManager( 5907): num queued entries: 0
,D/QuickConnect[1.1][2] ( 5110): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/iu.UploadsManager( 5907): num updated entries: 0
I/QuickConnect[1.1][2] ( 5110): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,I/iu.SyncManager( 5907): NEXT; no task
,V/QuickConnect[1.1][2] ( 5110): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228f220
V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,I/SELinux ( 7404): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7404):  
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
I/SELinux ( 7404): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7404):  
I/SELinux ( 7404):  
,I/SELinux ( 7404): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7404): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7404): >>>>> Normal User
,E/dalvikvm( 7404): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7404): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
V/NetworkStats( 2409): updateIfacesLocked()
V/NetworkStats( 2409): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
V/NetworkStats( 2409): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
V/NetworkStats( 2409): performPollLocked() took 19ms
,D/TimaKeyStoreProvider( 7404): in addTimaSignatureService
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/TimaKeyStoreProvider( 7404): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7404): Added TimaKesytore provider
,D/dalvikvm( 7404): GC_CONCURRENT freed 2991K, 31% free 9580K/13792K, paused 4ms+2ms, total 28ms
,D/dalvikvm( 7404): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/RCPManagerService( 2409): exchangeData() failure , invalid userId
,D/RCPManagerService( 2409): exchangeData() failure , invalid userId
,D/RCPManagerService( 2409): exchangeData() failure , invalid userId
,I/SELinux ( 7431): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7431):  
,D/RCPManagerService( 2409): exchangeData() failure , invalid userId
,D/RCPManagerService( 2409): exchangeData() failure , invalid userId
,W/ActivityManager( 2409): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/RCPManagerService( 2409): exchangeData() failure , invalid userId
,I/ActivityManager( 2409): Killing 5950:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7431): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7431):  
I/SELinux ( 7431):  
,I/SELinux ( 7431): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7431): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7431): >>>>> Normal User
,E/dalvikvm( 7431): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7431): [DEBUG] seapp_context_lookup: seinfoCategory = release,
,D/TimaKeyStoreProvider( 7431): in addTimaSignatureService,
,I/SELinux ( 7444): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7444):  
D/TimaKeyStoreProvider( 7431): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7431): Added TimaKesytore provider,
,I/ActivityManager( 2409): Killing 6286:com.android.providers.calendar/u0a45 (adj 15): empty #43,
,I/SELinux ( 7444): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7444):  
I/SELinux ( 7444):  
,I/SELinux ( 7444): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7444): [DEBUG] seapp_context_lookup: seinfoCategory = shared,
E/dalvikvm( 7444): >>>>> Normal User
,E/dalvikvm( 7444): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ],
,E/SELinux ( 7444): [DEBUG] seapp_context_lookup: seinfoCategory = shared,
,D/TimaKeyStoreProvider( 7444): in addTimaSignatureService,
D/dalvikvm( 7431): GC_CONCURRENT freed 3002K, 31% free 9564K/13792K, paused 3ms+1ms, total 32ms
,D/dalvikvm( 7431): WAIT_FOR_CONCURRENT_GC blocked 27ms,
,D/TimaKeyStoreProvider( 7444): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7444): Added TimaKesytore provider,
,D/BadgeProvider( 7431): onCreate,
,D/BadgeProvider( 7431): DatabaseHelper,
,D/Tethering( 2409): Tethering got CONNECTIVITY_ACTION,
,D/Tethering( 2409): MasterInitialState.processMessage what=3,
,D/CaptivePortalTracker( 2409): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler },
D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4733): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/BadgeProvider( 7431): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7431): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7431): sendNotify, [notify] : null
D/Launcher.Model( 2778): reloadBadges entered.
D/BadgeProvider( 7431): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7431): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7431): update, [UpdateCount] : 1
,D/dalvikvm( 7444): GC_CONCURRENT freed 3006K, 31% free 9557K/13788K, paused 5ms+1ms, total 28ms
,D/dalvikvm( 7444): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/libgps  ( 2409): agps_ril_update_network_state: Waiting for IPC connection...
,D/hcjo    ( 5928): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5928): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5928): exit::IDLE
,D/InitializeManagerStateMachine( 5928): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5928): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5928): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5928): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5928): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 5928): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5928): entry::SUCCESS
,D/hcjo    ( 5928): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5928): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5928): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5928): exit::SUCCESS
,D/InitializeManagerStateMachine( 5928): entry::IDLE
,E/SPPClientService( 5514): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5514): [SystemStateMoniter] Current Time : 268152
,E/SPPClientService( 5514): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5514): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2835): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2835): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2835): MountReceiver.onReceive - Keep current state
,D/Headlines( 5839): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5839): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5839): Breath 1619 latestRequest time : 1450106537676 current time : 1450106539295
,E/SPPClientService( 5514): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5514): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2835): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2835): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2835): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5514): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,E/SPPClientService( 5514): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/SurfaceFlinger( 1921): id=20 createSurf (1x1),1 flag=4, Uoast
,E/SPPClientService( 5514): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
D/PowerManagerService( 2409): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2409
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2835): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5514): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5514): [g] getNetMCC return empty string
,I/PCWCLIENTTRACE_PushUtil( 6551): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6551): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6551): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6551): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.3.201 : ( 7287): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7287): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450106539648
,I/KLMS-2.3.201 : ( 7287): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7299): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3300): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/GalaxyFinderApplication( 3300): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3300): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3300): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7299): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 3428): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7468): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7468):  
,I/SELinux ( 7468): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7468):  
I/SELinux ( 7468):  
,I/SELinux ( 7468): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7468): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7468): >>>>> Normal User
,E/dalvikvm( 7468): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7468): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7468): in addTimaSignatureService
,D/dalvikvm( 2722): GC_EXPLICIT freed 278K, 32% free 10036K/14688K, paused 7ms+9ms, total 104ms
,D/TimaKeyStoreProvider( 7468): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7468): Added TimaKesytore provider
,I/SELinux ( 7482): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7482):  
,W/WifiP2pStateTracker( 2409): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2409): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2409):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
D/ConnectivityService( 2409): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2409): updateSourceRoutes : no source routing conditions
I/SELinux ( 7482): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7482):  
I/SELinux ( 7482):  
I/SELinux ( 7482): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7482): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7482): >>>>> Normal User
E/dalvikvm( 7482): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
E/SELinux ( 7482): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/System.out( 7268): Thread-630(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7268): Thread-630(ApacheHTTPLog):isShipBuild true
,I/System.out( 7268): Thread-630(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/TimaKeyStoreProvider( 7482): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7482): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7482): Added TimaKesytore provider
,D/dalvikvm( 7468): GC_CONCURRENT freed 2985K, 31% free 9582K/13788K, paused 3ms+2ms, total 58ms
,D/dalvikvm( 7468): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 7482): GC_CONCURRENT freed 2995K, 31% free 9565K/13784K, paused 4ms+3ms, total 30ms
,D/dalvikvm( 7482): WAIT_FOR_CONCURRENT_GC blocked 25ms
,V/KVNProvider( 7482): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7482): getFindoCursor query string : 
,I/SA      ( 5775): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5775): [BDLM] already registered in spp
I/SA      ( 5775): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5775): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5775): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5775): [OR] == isSIMCardReady false ==
,I/SA      ( 5775): [SCU] == networkStateCheck == true
I/SA      ( 5775): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5775): isChinaCountryCode : false
,I/SA      ( 5775): [OR] == networkStateCheck true ==
,V/KVNProvider( 7482): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 5775): [OR] GetMyCountryZoneTask
,I/SA      ( 5775): [OR] onReceive END
,I/SA      ( 5775): [SRS] prepareGetMyCountryZone
,I/SA      ( 5775): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5775): [SSP] query invoked
,I/SA      ( 5775): [TPMU] GetMccFromDB : null
,I/SA      ( 5775): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5775): [TPM] isNoProxy(default) : true
,I/SA      ( 5775): [RC New] Execute method=[GET] start
I/ActivityManager( 2409): Killing 6127:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7311): Other Intent
D/PackageManager( 2409): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/com.samsung.app( 7324): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7324): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5839): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5839): getCountryCode(): countryCode = PL
,D/Headlines( 5839): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/libgps  ( 2409): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2409): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2409): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2409): agps_ril_update_network_availability: Waiting for IPC connection...
,D/HeadlinesCardManager( 5839): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5839): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 5839): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5839): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5839): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5839): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 5907): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 5907): num queued entries: 0
,I/iu.UploadsManager( 5907): num updated entries: 0
,D/QuickConnect[1.1][2] ( 5110): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5110): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5110): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228f220
,I/iu.SyncManager( 5907): NEXT; no task
,D/RCPManagerService( 2409): exchangeData() failure , invalid userId
,D/RCPManagerService( 2409): exchangeData() failure , invalid userId
,D/hcjo    ( 5928): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5928): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5928): exit::IDLE
,D/InitializeManagerStateMachine( 5928): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5928): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5928): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5928): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5928): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5928): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5928): entry::SUCCESS
,D/hcjo    ( 5928): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/System.out( 7268): AsyncTask #1 calls detatch()
D/hcjo    ( 5928): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5928): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5928): exit::SUCCESS
,D/InitializeManagerStateMachine( 5928): entry::IDLE
,E/SPPClientService( 5514): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5514): [SystemStateMoniter] Current Time : 269296
,E/SPPClientService( 5514): [SystemStateMoniter] No Connect : false
,W/System.err( 7268): com.sec.android.fota.osp.http.RestClientException
D/dalvikvm( 5514): GC_CONCURRENT freed 2006K, 25% free 10446K/13780K, paused 9ms+4ms, total 62ms
,D/dalvikvm( 5514): WAIT_FOR_CONCURRENT_GC blocked 23ms
D/SSRMv2:SIOP( 2409): SIOP:: AP = 350, Delta = 20
,W/System.err( 7268): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7268): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7268): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
,W/System.err( 7268): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 7268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7268): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 7268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7268): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7268): Caused by: java.lang.NullPointerException
W/System.err( 7268): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7268): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7268): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7268): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7268): 	... 8 more
,I/ActivityManager( 2409): Killing 6164:com.google.android.music:main/u0a125 (adj 15): empty #43
,I/jxcore-log( 7177): Got Device Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 7177): 
,I/jxcore-log( 7177): my name is : samsung-SM-G800F_PT9198
I/jxcore-log( 7177): 
,I/jxcore-log( 7177): attempting to connect to test coordinator
I/jxcore-log( 7177): 
,I/jxcore-log( 7177): check test folder
I/jxcore-log( 7177): 
,I/jxcore-log( 7177): found test : ./testFindPeers.js
I/jxcore-log( 7177): 
,I/jxcore-log( 7177): found test : ./testReConnect.js
I/jxcore-log( 7177): 
,I/jxcore-log( 7177): found test : ./testSendData.js
I/jxcore-log( 7177): 
,I/jxcore-log( 7177): Test app app.js loaded
I/jxcore-log( 7177): 
,I/Choreographer( 7177): Skipped 371 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7177): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/SA      ( 5775): [RC New] [v2liruge] api execute + 694
,I/SA      ( 5775): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5775): AsyncTask #2 calls detatch()
,I/SA      ( 5775): [TPMU] getNetworkMcc : 
,I/jxcore-log( 7177): DBG, CoordinatorConnector connect called
I/jxcore-log( 7177): 
,I/jxcore-log( 7177): Coordinator is now connected to the server!
I/jxcore-log( 7177): 
I/SA      ( 5775): [SCU] saveMccToPreferece Start
,I/SA      ( 5775): [SCU] RegionMCC : 260
,I/SA      ( 5775): [SSP] query invoked
,I/SA      ( 5775): [TPMU] GetMccFromDB : null
,I/SA      ( 5775): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5775): [SCU] saveMccToPreferece End
I/SA      ( 5775): [RC New] executeRequest [v2liruge] end. 724
,I/SA      ( 5775): [RC New] Execute end
I/SA      ( 5775): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5775): [OR] GetMyCountryZoneTask Success
,I/chromium( 7177): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/AmoledAdjustTimer( 2409): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4
D/libgps  ( 2409): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2409): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2409): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
E/SPPClientService( 5514): [b] __InitReply__
E/WifiStateMachine( 2409): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger( 1921): id=20 Removed Uoast (10/11)
,I/SurfaceFlinger( 1921): id=20 Removed Uoast (-2/11)
I/ActivityManager( 2409): Killing 6494:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/PowerManagerService( 2409): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2409) eventTime = 271799
,D/PowerManagerService( 2409): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2409 (0x0)
,D/PowerManagerService( 2409): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2409, ws=WorkSource{1000}) (elapsedTime=3475)
,I/GAV2    ( 7337): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6551): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil( 6551): [hasSamungAccount] - No Samsung Account,
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6551): failed to loading secure library,
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6551): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6551): GetString : secure API is not supported!!
,I/PCWCLIENTTRACE_PushUtil( 6551): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6551): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6551): getPushTypeList : [SPP, GCM],
,E/PCWCLIENTTRACE_PCWHandler( 6551): [ensureRegistration] - No Samsung account,
,I/jxcore-log( 7177): BLE advertisement not supported: Bluetooth LE advertising is not supported,
I/jxcore-log( 7177): 
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3999): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/CaptivePortalTracker( 2409): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
D/ConnectivityService( 2409): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2409): Checking http://216.58.209.78/generate_204,
,D/CaptivePortalTracker( 2409): Don't send network conditions - lacking user consent.,
,D/CaptivePortalTracker( 2409): isCaptivePortal: ret=false rspCode=204,
D/CaptivePortalTracker( 2409): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2409): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
D/ConnectivityService( 2409): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 5928): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 5928): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5928): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 5928): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5928): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 5928): exit::CHECK_TIMEOUT_FOR_UPDATE,
,D/PreloadUpdateManagerStateMachine( 5928): entry::IDLE,
,D/PreloadUpdateManagerStateMachine( 5928): execute::IDLE:EXECUTE,
,D/PreloadUpdateManagerStateMachine( 5928): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5928): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 5928): AutoUpdateTriggerManager:IDLE:notifyNextTime,
,D/PreloadUpdateManagerStateMachine( 5928): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 5928): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5928): entry::IDLE,
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 340, Delta = -10,
,D/AmoledAdjustTimer( 2409): prevTemp = 306, currTemp = 307, prevStep = 4, currStep = 4,
,I/ActivityManager( 2409): Waited long enough for: ServiceRecord{46a65b50 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,I/ActivityManager( 2409): Waited long enough for: ServiceRecord{463545f8 u0 com.sec.spp.push/.PushClientService},
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2409): !@Sync 9,
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = -10,
,D/AmoledAdjustTimer( 2409): prevTemp = 307, currTemp = 306, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2409): [PWL] Off : 225s ago,
,V/AlarmManager( 2409): waitForAlarm result :8,
,D/Headlines( 5839): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5839): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5839): Breath 27477 latestRequest time : 1450106540237 current time : 1450106567714,
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2409): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4,
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2409): waitForAlarm result :8,
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2409): prevTemp = 306, currTemp = 305, prevStep = 4, currStep = 4,
,D/TimaService( 2409): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 2409): TimaServiceHandler.handleMessage what =1,
,D/TimaService( 2409): TIMA: checkEvent, operation: 50000 subject: 10000,
,I/TLC_TIMA_PKM_initialize( 2409): initializing...,
I/TLC_TIMA_PKM_initialize( 2409): root = 0, root_strlen = 1,
,I/TLC_TIMA_PKM_initialize( 2409): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2409): input max_sendmsg_size = 262196,
I/TZ: mc_tlc_communication( 2409): input max_recvmsg_size = 262196,
,I/TZ: mc_tlc_communication( 2409): root = 0, root_len = 1,
I/TZ: mc_tlc_communication( 2409): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2409): aligned max_sendmsg_size = 262208,
I/TZ: mc_tlc_communication( 2409): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 2409): device_id = 0x0
,I/TZ: mc_tlc_communication( 2409): tlc_open() was called
,I/TZ: mc_tlc_communication( 2409): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2409): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2409): Opening the session,
,I/TZ: mc_tlc_communication( 2409): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2409): Trustlet response is completed,
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2409): !@Sync 10,
,I/TLC_TIMA_PKM_measure_kernel( 2409): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2409): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2409): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
D/TimaService( 2409): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2409): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2409): waitForAlarm result :8,
,D/Headlines( 5839): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5839): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5839): Breath 57474 latestRequest time : 1450106540237 current time : 1450106597711,
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2409): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2409): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3999): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2409): prevTemp = 305, currTemp = 304, prevStep = 4, currStep = 4,
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2409): [PWL] Off : 275s ago,
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged,
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3999): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2409): !@Sync 11,
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2409): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4,
,V/AlarmManager( 2409): waitForAlarm result :4,
,V/AlarmManager( 2409): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 8126): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 8126):  
,I/SELinux ( 8126): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 8126):  
I/SELinux ( 8126):  
I/SELinux ( 8126): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8126): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 8126): >>>>> Normal User
,E/dalvikvm( 8126): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 8126): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 8126): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 8126): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8126): Added TimaKesytore provider
,D/dalvikvm( 8126): GC_CONCURRENT freed 3000K, 31% free 9567K/13792K, paused 3ms+2ms, total 27ms,
,D/dalvikvm( 8126): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/ActivityManager( 2409): Killing 6411:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,V/AlarmManager( 2409): waitForAlarm result :8,
,D/Headlines( 5839): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5839): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5839): Breath 87473 latestRequest time : 1450106540237 current time : 1450106627710,
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged,
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2409): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4,
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2409): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2582): GC_CONCURRENT freed 15712K, 34% free 33860K/50788K, paused 40ms+11ms, total 156ms
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 304, currTemp = 303, prevStep = 4, currStep = 4
,I/jxcore-log( 7177): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 7177): 
,I/jxcore-log( 7177): DBG, CoordinatorConnector command called
I/jxcore-log( 7177): 
,I/jxcore-log( 7177): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":21,"addressList":[{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"38:94:96:B5:06:DC","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"08:EC:A9:50:76
,I/jxcore-log( 7177): Start now : testSendData.js
I/jxcore-log( 7177): 
,I/jxcore-log( 7177): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 21
I/jxcore-log( 7177): 
,I/jxcore-log( 7177): check server
I/jxcore-log( 7177): 
,I/jxcore-log( 7177): serverPort is 60243
I/jxcore-log( 7177): 
,I/dalvikvm( 7177): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7177): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7177): VFY: replacing opcode 0x6e at 0x0019
I/dalvikvm( 7177): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7177): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7177): VFY: replacing opcode 0x6e at 0x0020
,I/jxcore-log( 7177): 2015-12-14T15:24:08.006Z SendDataTCPServer.js: TCP/IP server is bound to port: 60243
I/jxcore-log( 7177): 
,D/AndroidRuntime( 7177): Shutting down VM
,W/dalvikvm( 7177): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7177): FATAL EXCEPTION: main
E/AndroidRuntime( 7177): Process: com.test.thalitest, PID: 7177
E/AndroidRuntime( 7177): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 7177): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 7177): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 7177): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 7177): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 7177): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 7177): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 7177): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 7177): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 7177): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 7177): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 7177): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7177): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7177): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7177): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7177): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7177): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7177): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7177): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 2409):   Force finishing activity com.test.thalitest/.MainActivity
,D/PointerIcon( 2409): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2409): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2409): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2409): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager( 2409): Killing 6524:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/Process ( 7177): Sending signal. PID: 7177 SIG: 9
,D/CrashAnrDetector( 2409): processName: com.test.thalitest
,D/CrashAnrDetector( 2409): broadcastEvent : com.test.thalitest data_app_crash
D/CustomFrequencyManagerService( 2409): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2409  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
W/ActivityManager( 2409): mDVFSHelper.acquire()
,I/DBG_DM  ( 4733): [3.19.140541][Line:408][onResume] 
,I/ActivityManager( 2409): Process com.test.thalitest (pid 7177) (adj 9) has died.
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (-2/10)
,I/WindowState( 2409): WIN DEATH: Window{443230d0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/DBG_DM  ( 4733): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
I/SurfaceFlinger( 1921): id=19 Removed NainActivit (-2/10)
,I/DBG_DM  ( 4733): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4733): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4733): [3.19.140541][Line:418][onResume] Postpone Count : 26
,I/DBG_DM  ( 4733): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4733): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4733): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2409): sendNotification(2) - 4
,I/DBG_DM  ( 4733): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
,I/DBG_DM  ( 4733): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4733): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4733): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4733): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4733): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4733): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/PhoneStatusBar( 2582): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/Activity( 4733): setTransGradationMode to true
,I/DBG_DM  ( 4733): [3.19.140541][Line:400][onPause] 
D/StatusBarManagerService( 2409): semi p:4733,o:t
,I/SurfaceFlinger( 1921): id=21 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2409): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2409): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2409): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2409): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2409): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2409): setHoveringSpenCustomIcon IconType is same.1
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 2409): Got RemoteException sending setActive(false) notification to pid 7177 uid 10538
,D/CustomFrequencyManagerService( 2409): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2409  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2409): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2409): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2409  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2409): !@Sync 12
,D/CustomFrequencyManagerService( 2409): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2409  tag : ACTIVITY_RESUME_BOOSTER@8
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 303, currTemp = 302, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3999): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,V/AlarmManager( 2409): waitForAlarm result :8
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: G3-1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/dalvikvm( 6391): GC_CONCURRENT freed 2587K, 28% free 10054K/13860K, paused 4ms+3ms, total 62ms
,D/dalvikvm( 6391): WAIT_FOR_CONCURRENT_GC blocked 36ms
,D/dalvikvm( 6391): WAIT_FOR_CONCURRENT_GC blocked 37ms
,D/Headlines( 5839): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5839): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5839): Breath 117562 latestRequest time : 1450106540237 current time : 1450106657799
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 302, currTemp = 303, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: G3-1
,I/SELinux ( 8416): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8416):  
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,I/SELinux ( 8416): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8416):  
I/SELinux ( 8416):  
,I/SELinux ( 8416): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8416): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8416): >>>>> Normal User
,E/dalvikvm( 8416): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 8416): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 8416): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8416): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8416): Added TimaKesytore provider
,D/dalvikvm( 8416): GC_CONCURRENT freed 2996K, 31% free 9568K/13784K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 8416): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/UserAnalysis.PlaceProvider( 8416): Create SecureDbHelper
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2409): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:3f:54:73:64:c0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: G3-1
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2409): !@Sync 13
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: G3-1
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 303, currTemp = 304, prevStep = 4, currStep = 4
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:3f:54:73:64:c0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: G3-1
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,V/AlarmManager( 2409): waitForAlarm result :8
,D/Headlines( 5839): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5839): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5839): Breath 147463 latestRequest time : 1450106540237 current time : 1450106687701
,D/Headlines( 5839): stop 
,D/Headlines( 5839): Breath.onDestroy : 
I/ActivityManager( 2409): Killing 6537:com.android.musicfx/u0a24 (adj 15): empty #43
,D/dalvikvm( 2409): GC_CONCURRENT freed 4391K, 72% free 24892K/86608K, paused 15ms+21ms, total 224ms
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2409): stay LED for fully charged
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3999): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 304, currTemp = 303, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0,
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: G3-1
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:3f:54:73:64:c0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: G3-1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: G3-1
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2409): !@Sync 14
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = -10
,D/AmoledAdjustTimer( 2409): prevTemp = 303, currTemp = 302, prevStep = 4, currStep = 4
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:3f:54:73:64:c0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: G3-1
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 2409): Skipping unknown process pid 8793
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 0:0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 0:0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3999): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/PowerManagerService( 2409): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: XT1072
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2409): !@Sync 15
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: XT1072
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: XT1072
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: XT1072
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: XT1072
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/Watchdog( 2409): !@Sync 16
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: XT1072
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: XT1072
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: XT1072
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: XT1072
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2409): [PWL] Off : 455s ago
,E/Watchdog( 2409): !@Sync 17
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,E/Watchdog( 2409): !@Sync 18
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 299, currTemp = 300, prevStep = 4, currStep = 4
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2409): !@Sync 19
,D/BatteryService( 2409): level:100, scale:100, status:3, health:9, present:true, voltage: 4371, temperature: 300, technology: Li-ion, AC powered:false, USB powered:false, Wireless powered:false, icon:17303678, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
D/LightsService( 2409): [api] [SvcLED] turnOff:: id = 3 (uid: 0 pid: 0) 
D/LightsService( 2409): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
,D/BatteryService( 2409): turn off LED
,D/lights  ( 2409): led_pattern : 0 +
D/LightsService( 2409): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/lights  ( 2409): led_pattern : 0 -
,D/lights  ( 2409): button : 1 +
,D/lights  ( 2409): button : 1 -
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/PowerManagerService( 2409): [api] updateIsPoweredLocked : mIsPowered: false mPlugType: 0
D/LightsService( 2409): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/PowerManagerService( 2409): !@[ps] Screen__On :  powered change
I/PowerManagerService( 2409): Waking up from sleep...
D/PowerManagerService( 2409): Screen Readiness Inspection requested: mNestCount=1
D/PowerManagerService( 2409): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2409): [s] WAKEFULNESS_AWAKE
D/PowerManagerService( 2409): [s] UserActivityState : 0 -> 1
D/PowerManagerService( 2409): [PWL] sb acquire: PowerManagerService.Display
D/DisplayPowerController( 2409): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,I/SensorManagerA( 2409): getReportingMode :: sensor.mType = 5
D/Sensors ( 2409): LightSensor setDelay = 200000000
D/Sensors ( 2409): LightSensor setSensorDelay = 200000000
,D/Sensors ( 2409): Light sensor flush: not enabled 0
D/DisplayPowerController( 2409): [DAB] setLightSensorEnabled : registerListener mLightSensor
I/DisplayPowerController( 2409): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
I/DisplayPowerController( 2409): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/Sensors ( 2409): LightSensor enable = 1
D/Sensors ( 2409): LightSensor enableSensor = 1
I/libsuspend( 2409): !@[s] autosuspend_autosleep_disable
I/libsuspend( 2409): !@[s] autosuspend_autosleep_disable done
D/SensorManager( 2409): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/SurfaceFlinger( 1921): Screen acquired, type=0 flinger=0x40eec550
I/SensorManagerA( 2409): getReportingMode :: sensor.mType = 1
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/DisplayPowerController( 2409): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2409): [DAB] no lux value from sensor manager
D/DisplayPowerController( 2409): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2409): unblankAllDisplays() is called.
D/PowerManagerService( 2409): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
D/PowerManagerService( 2409): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 9ms
I/Sensors ( 2409): HAL: batch Dry Run is complete
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,I/Sensors ( 2409): HAL:resetDataRates mEnabled=4
,D/PowerUI ( 2582): Overvoltage/Undervoltage (recovered) so turn on the screen.
,I/SensorManagerA( 2409): getReportingMode :: sensor.mType = 65558
D/UsbDeviceManager( 2409): handleMessage -> MSG_POWER_STATE = 0
D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/PowerManagerService( 2409): [api] [s] wakeUp (uid: 10019 pid: 2582) eventTime = 588743
D/RampAnimator( 2409): Light Animator Finished currentValue=8
,D/SensorManager( 2409): registerListener :: 2, MPL Accelerometer, 200000, 0,  
D/NotificationService( 2409): cancelNotificationLocked
D/NotificationService( 2409):  hasClearableItems
D/NotificationService( 2409):  has clearable items no 
D/NotificationService( 2409): cancelNotificationLocked: cancel alarm
D/NotificationService( 2409): cancelNotificationLocked: cancel alarm
W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:3 health:9
D/UsbDeviceManager( 2409): sending intent : ACTION_USB_CABLE_STATE : connected = false
D/PowerManagerService( 2409): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 20ms
D/STATUSBAR-StatusBarManagerService( 2409): sendNotification(3) - 5
,D/SensorService( 2409): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2409): AutoRotationSensor::activate (ident=0x81c9f9c8, enabled=1)
D/SensorService( 2409): AutoRotationSensor::AR_init
,I/Sensors ( 2409): HAL: batch Dry Run is complete
D/LightsService( 2409): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2409) 
D/LightsService( 2409): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/UsbDeviceManager( 2409): received ACTION_POWER_DISCONNECTED = -1
D/LightsService( 2409): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2409): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/Sensors ( 2409): HAL:resetDataRates mEnabled=4
,D/SensorManager( 2409): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
V/KeyguardServiceDelegate( 2409): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@4231ec48)
I/SELinux ( 9362): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 9362):  
D/KeyguardViewMediator( 2582): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 2582): notifyScreenOnLocked
D/KeyguardViewMediator( 2582): handleNotifyScreenOn
,D/KeyguardViewManager( 2582): onScreenTurnedOn()
,V/KeyguardViewManager( 2582): send wm null token: host was null
I/KeyguardEffectViewMain( 2582): *** KeyguardEffectView getInstance ***
V/KeyguardServiceDelegate( 2409): **** SHOWN CALLED ****
D/VisualEffectParticleEffect( 2582): KeyguardEffectViewParticleSpace : screenTurnedOn
D/VisualEffectParticleEffect( 2582): screenOnAnimationStart
D/InputDispatcher( 2409): setInputDispatchMode: enabled=1, frozen=0
,D/LockPatternUtils( 2582): isPcwEnable = 10
I/WindowManager( 2409): No lock screen! windowToken=null
D/PowerManagerNotifier( 2409): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/PowerManagerService( 2409): Screen Readiness Inspection completed: mNestCount=0
,I/SurfaceFlinger( 1921): id=14 Removed FlectronBea (10/10)
,I/SurfaceFlinger( 1921): id=14 Removed FlectronBea (-2/10)
D/DisplayPowerController( 2409): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 2409): !@ElectronBeam exit
D/lights  ( 2409): lcd : 8 +
,D/lights  ( 2409): lcd : 8 -
,D/LockPatternUtils( 2582): isPcwEnable = 10
D/DisplayPowerController( 2409): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2409): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/BatteryMeterView( 2582): onDraw batteryColor : -1
,I/SELinux ( 9362): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 9362):  
I/SELinux ( 9362):  
,I/SELinux ( 9362): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 9362): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 9362): >>>>> Normal User
,E/dalvikvm( 9362): >>>>> com.sec.android.Kies [ userId:0 | appId:1000 ]
,E/SELinux ( 9362): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 9362): in addTimaSignatureService
,D/SensorService( 2409): AutoRotationSensor::process: Acc  eventTimestamp = 588835717783, previousAccTimestamp = 68487460389, difference = 520348257394 
,D/SensorService( 2409): AutoRotationSensor::reset oldrotation = [100], initState = [1]
,D/TimaKeyStoreProvider( 9362): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 9362): Added TimaKesytore provider
,D/DisplayPowerController( 2409): [api] [DAB] onSensorChanged : 1st lux : 5.0
,D/DisplayPowerController( 2409): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 5.0 < 15.0 (0.0)
,D/SensorService( 2409): AutoRotationSensor::process: Acc  eventTimestamp = 588902380209, previousAccTimestamp = 68487460389, difference = 520414919820 
,D/SensorService( 2409):  [AR] 0.3 0.0 9.9
,D/SensorService( 2409): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
,D/SurfaceControl( 2409): Excessive delay in unblankDisplay() while turning screen on: 247ms
,D/MISC PowerHAL( 2409): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2409): sysfs_write +: /sys/class/input/input1/enabled: 1
D/PowerManagerService( 2409): Excessive delay in mDisplayManagerService.unblankAllDisplaysFromPowerManager(): 247ms
,I/display ( 1921): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/LightsService( 2409): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2409) 
,D/LightsService( 2409): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2409): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/PalmMotionService( 2409): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/PalmMotionService( 2409): SURFACE_PALM_SWIPE: 1
D/LightsService( 2409): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/MISC PowerHAL( 2409): sysfs_write -: /sys/class/input/input1/enabled: 1
,D/MISC PowerHAL( 2409): miscpower_set_interactive: /sys/class/input/input0/enabled
,D/MISC PowerHAL( 2409): sysfs_write +: /sys/class/input/input0/enabled: 1
E/MotionRecognitionService( 2409):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,I/NfcService( 2766): applyRouting return - 2 
,D/SSRMv2:TSP:AirViewOnOff( 2409): SettingsAirViewInfo:: 000000000
E/NfcService( 2766): callback == null
D/SamsungIME( 3016): showDlgMsgBox : false true true
,I/FPMS_FingerprintManagerService( 2602): onReceive: android.intent.action.USER_PRESENT
,I/WifiTrafficPoller( 2409): evaluateTrafficStatsPolling
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,I/DBG_DM  ( 4733): [3.19.140541][Line:408][onResume] 
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
D/STATUSBAR-NotificationService( 2409): ACTION_SCREEN_ON
D/LightsService( 2409): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2409) 
,D/LightsService( 2409): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2409): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2409): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/AudioHardwareTinyALSA( 1925): setParameters(screen_state=on)
I/SecExternalDisplayIntents_Java( 2409): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,I/DBG_DM  ( 4733): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
,D/MISC PowerHAL( 2409): sysfs_write -: /sys/class/input/input0/enabled: 1
D/MISC PowerHAL( 2409): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 2409): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
,D/PowerManagerService-JNI( 2409): Excessive delay in MISC setInteractive(true) while turning screen on: 167ms
D/SEC PowerHAL( 2409): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2409): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2409): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2409): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
,D/SEC PowerHAL( 2409): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2409): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2409): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
,D/SEC PowerHAL( 2409): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
D/PowerManagerService( 2409): Excessive delay in nativeSetInteractive(true): 170ms
D/PowerManagerService( 2409): SecHardwareInterface.setBatteryADC : true
,D/dalvikvm( 9362): GC_CONCURRENT freed 3000K, 31% free 9571K/13792K, paused 8ms+2ms, total 49ms
,D/dalvikvm( 9362): WAIT_FOR_CONCURRENT_GC blocked 33ms
D/IpRemoteDisplayController( 2409): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2409): Bridge Server is not available
,D/PersonaManagerService( 2409): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 2409): MSG_ACTION_SCREEN_ON called
,I/DBG_DM  ( 4733): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/NfcService( 2766): NFC: Screen On & Cover Open
,I/KIES_RECEIVE( 9362): [APK BnR] Receive KIES_USB_DISCONNECT
W/ContextImpl( 9362): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 android.content.ContextWrapper.stopService:511 com.sec.android.Kies.kies_receiver.onReceive:170 android.app.ActivityThread.handleReceiver:2698 
,I/NfcService( 2766): applyRouting return - 2 
,E/NfcService( 2766): callback == null
,I/DBG_DM  ( 4733): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4733): [3.19.140541][Line:418][onResume] Postpone Count : 26
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
E/TranscodeReceiver( 7468): onReceive : android.intent.action.ACTION_POWER_DISCONNECTED
,I/DBG_DM  ( 4733): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,D/videowall-Global( 7468): core_num = 4
,D/dalvikvm( 7468): No JNI_OnLoad found in /system/lib/libsavsff.so 0x4227f9b0, skipping init
D/STATUSBAR-NetworkController( 2582): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,I/DBG_DM  ( 4733): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,W/linker  ( 7468): libvwengine.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/videowall-Global( 7468): density : 2.0 width : 720 height : 1280 Raw width : 720 Raw height : 1280
,D/videowall-Global( 7468): dsp : 720, swkey : false, Cores : 4, Clock : 0
,I/DBG_DM  ( 4733): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,I/SELinux ( 9379): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 9379):  
,I/DBG_DM  ( 4733): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
,I/DBG_DM  ( 4733): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(9)
,I/DBG_DM  ( 4733): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4733): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4733): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4733): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 12% free 9501K/10764K, paused 6ms+7ms, total 50ms
,D/STATUSBAR-StatusBarManagerService( 2409): sendNotification(2) - 4
I/DBG_DM  ( 4733): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
I/SELinux ( 9379): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 9379):  
I/SELinux ( 9379):  
I/SELinux ( 9379): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 9379): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 9379): >>>>> Normal User
,E/dalvikvm( 9379): >>>>> com.android.chrome [ userId:0 | appId:10085 ]
D/PhoneStatusBar( 2582): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/Activity( 4733): setTransGradationMode to true
,E/SELinux ( 9379): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
D/StatusBarManagerService( 2409): semi p:4733,o:t
,D/TimaKeyStoreProvider( 9379): in addTimaSignatureService
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9501K/10764K, paused 5ms+4ms, total 38ms
,D/TimaKeyStoreProvider( 9379): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 9379): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9501K/10764K, paused 3ms+3ms, total 34ms
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/QuickConnect[1.1][2] ( 5110): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
,V/QuickConnect[1.1][2] ( 5110): BleHelper.shouldScanBleBg - 
,D/dalvikvm( 9379): GC_CONCURRENT freed 3005K, 31% free 9564K/13788K, paused 2ms+2ms, total 22ms
D/dalvikvm( 9379): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/QuickConnect[1.1][2] ( 5110): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5110): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228f220
,V/QuickConnect[1.1][2] ( 5110): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228f220
V/QuickConnect[1.1][2] ( 5110): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 5110): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228f220
V/QuickConnect[1.1][2] ( 5110): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228f220
,V/QuickConnect[1.1][2] ( 5110): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228f220
D/QuickConnect[1.1][2] ( 5110): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 5110): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 5110): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 5110): BleHelper.startScan - shouldScanBleFg = false
,D/daemonapp( 5308): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5308): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5308): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionSCREEN_ON
,D/PowerManagerService( 2409): [PWL] sb release: PowerManagerService.Broadcasts
,I/display ( 1921): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(3)
,I/SELinux ( 9393): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 9393):  
I/ActivityManager( 2409): Killing 6563:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,I/SELinux ( 9393): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 9393):  
I/SELinux ( 9393):  
,I/SELinux ( 9393): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 9393): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 9393): >>>>> Normal User
,E/dalvikvm( 9393): >>>>> com.google.android.apps.uploader [ userId:0 | appId:10117 ]
,E/SELinux ( 9393): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 9393): in addTimaSignatureService
,D/TimaKeyStoreProvider( 9393): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 9393): Added TimaKesytore provider
,D/dalvikvm( 9393): GC_CONCURRENT freed 3014K, 31% free 9552K/13788K, paused 3ms+1ms, total 28ms
,D/dalvikvm( 9393): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/iu.Environment( 5907): update battery state; isPlugged? false*
,I/iu.UploadsManager( 5907): num queued entries: 0
,I/ActivityManager( 2409): Killing 5968:com.sec.android.app.shealth/u0a36 (adj 15): empty #43
I/iu.UploadsManager( 5907): num updated entries: 0
I/iu.SyncManager( 5907): NEXT; no task
,D/PicasaUploader( 9393):    wifiOnlyPhoto changed to true
D/PicasaUploader( 9393):    wifiOnlyVideo changed to true
,D/PicasaUploader( 9393):    syncOnBattery changed to true
,I/iu.Environment( 3160): update battery state; isPlugged? false*
,D/PicasaUploaderSync( 9393): sync account database
,I/iu.UploadsManager( 3160): num queued entries: 0
,I/GCoreUlr( 2736): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_DISCONNECTED}]
,I/iu.UploadsManager( 3160): num updated entries: 0
,I/iu.SyncManager( 3160): NEXT; no task
,I/GCoreUlr( 2736): DispatchingService.onCreate()
,D/PicasaUploaderSync( 9393): accounts in DB=1
D/PicasaUploaderSyncManager( 9393): active network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PicasaUploaderSyncManager( 9393): background data: true
,D/PicasaUploaderSyncManager( 9393): battery info: false
,D/dalvikvm( 2736): GC_CONCURRENT freed 1698K, 20% free 12082K/15072K, paused 4ms+9ms, total 75ms
,D/LockPatternUtils( 2582): isPcwEnable = 10
,I/GCoreUlr( 2736): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_DISCONNECTED
,D/daemonapp( 5308): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5308): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5308): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5308): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5308): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 5308): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5308): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5308): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5308): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5308): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5308): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 5308): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5308): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 5308): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1450121880000
,D/daemonapp( 5308): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1450106861177
,D/daemonapp( 5308): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,I/GCoreUlr( 2736): WorldUpdater:android.intent.action.ACTION_POWER_DISCONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
I/GCoreUlr( 2736): Unbound from all location providers
I/GCoreUlr( 2736): Place inference reporting - stopped
D/daemonapp( 5308): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5308): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5308): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5308): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5308): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/GCoreUlr( 2736): DispatchingService.onDestroy()
,I/GCoreUlr( 2736): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
,D/AmoledAdjustTimer( 2409): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,D/dalvikvm( 5308): GC_CONCURRENT freed 2669K, 29% free 9980K/13868K, paused 23ms+5ms, total 107ms
,D/dalvikvm( 5308): WAIT_FOR_CONCURRENT_GC blocked 37ms
,D/daemonapp( 5308): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5308): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5308): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/lights  ( 2409): button : 0 +
,D/lights  ( 2409): button : 0 -
,D/daemonapp( 5308): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5308): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 5308): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5308): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5308): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5308): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 5308): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5308): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 5308): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5308): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5308): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 5308): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5308): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
D/SSRMv2:TSP:AirViewOnOff( 2409): SettingsAirViewInfo:: 000000000
,D/SensorService( 2409):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2409):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2409):   0.3 0.0 9.8
,D/BatteryService( 2409): level:100, scale:100, status:2, health:2, present:true, voltage: 4361, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/PowerManagerService( 2409): [api] updateIsPoweredLocked : mIsPowered: true mPlugType: 2
D/PowerUI ( 2582): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2409): [api] [s] wakeUp (uid: 10019 pid: 2582) eventTime = 598664
D/PowerUI ( 2582): playSound : 1
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,V/Vibrator( 2582): Called vibrateImmVibe(int) API - PUID: 10019, PackageName: com.android.keyguard
V/Vibrator( 2582): vibrateImmVibe - PUID: 10019, PackageName: com.android.keyguard, type: 10, magType: TouchMagnitude
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
V/VibratorService( 2409): vibrateImmVibeMagnitudeType - magnitudeType: TouchMagnitude
V/VibratorService( 2409): vibrate - package: com.android.keyguard, ms: 100, token: null
D/VibratorService( 2409): JNI vibratorOff()
D/VibratorService( 2409): JNI vibratorOn() : 100
D/PowerUI ( 2582): RINGER_MODE_VIBRATE
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
D/UsbDeviceManager( 2409): handleMessage -> MSG_POWER_STATE = 1
D/UsbDeviceManager( 2409): sending intent : ACTION_USB_CABLE_STATE : connected = true
D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
,I/EntropyMixer( 2409): Writing entropy...
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
,D/BatteryMeterView( 2582): onDraw batteryColor : -1
E/TranscodeReceiver( 7468): onReceive : android.intent.action.ACTION_POWER_CONNECTED
I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
,D/TranscodeService( 7468): onCreate()
,I/SCloudBackupReceiver( 7311): Other Intent
,D/dalvikvm( 7468): No JNI_OnLoad found in /system/lib/libsavsvc.so 0x4227f9b0, skipping init
,D/dalvikvm( 7468): No JNI_OnLoad found in /system/lib/libsavscmn.so 0x4227f9b0, skipping init
,D/dalvikvm( 7468): No JNI_OnLoad found in /system/lib/libsthmb.so 0x4227f9b0, skipping init
D/TranscodeService( 7468): power? : true / screen off : false
,D/TranscodeService( 7468): releaseTranscodeThread.
,D/PicasaUploaderSyncManager( 9393): battery info: true
,I/iu.Environment( 5907): update battery state; isPlugged? true*
,I/iu.UploadsManager( 5907): num queued entries: 0
,I/iu.UploadsManager( 5907): num updated entries: 0
D/VibratorService( 2409): JNI vibratorOff()
,I/iu.SyncManager( 5907): NEXT; no task
,I/iu.FingerprintManager( 5907): Start processing all media
,I/iu.FingerprintManager( 5907): Start processing media store URI: content://media/external/images/media
,I/iu.Environment( 3160): update battery state; isPlugged? true*
,I/iu.UploadsManager( 3160): num queued entries: 0
,I/iu.UploadsManager( 3160): num updated entries: 0
,I/iu.FingerprintManager( 5907): Start processing media store URI: content://media/external/video/media
,I/iu.SyncManager( 3160): NEXT; no task
,E/NetworkScheduler.SchedulerReceiver( 2854): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 2854): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/GCoreUlr( 2736): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_CONNECTED}]
,I/iu.FingerprintManager( 3160): Start processing all media
,I/GCoreUlr( 2736): DispatchingService.onCreate()
,I/iu.FingerprintManager( 5907): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 3160): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 5907): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 5907): Finished generating fingerprints; 0.070 seconds
,I/iu.FingerprintManager( 5907):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/iu.FingerprintManager( 3160): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 3160): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 3160): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 3160): Finished generating fingerprints; 0.063 seconds
,I/iu.FingerprintManager( 3160):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/GCoreUlr( 2736): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_CONNECTED
,I/GCoreUlr( 2736): WorldUpdater:android.intent.action.ACTION_POWER_CONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
,I/GCoreUlr( 2736): DispatchingService.onDestroy()
,I/GCoreUlr( 2736): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 10
,D/AmoledAdjustTimer( 2409): prevTemp = 300, currTemp = 301, prevStep = 4, currStep = 4
,I/wpa_supplicant( 3979): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=0
I/wpa_supplicant( 3979): wlan0: Setting scan request: 0 sec 500000 usec
,I/wpa_supplicant( 3979): wlan0: Setting scan request: 0 sec 100000 usec
,I/wpa_supplicant( 3979): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2409): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2409): interfaceStatusChanged wlan0, true
,D/Tethering( 2409): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2409): interfaceStatusChanged wlan0, true
D/WifiP2pService( 2409): InactiveState{ what=143375 }
D/WifiP2pService( 2409): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2409): evaluateTrafficStatsPolling
I/wpa_supplicant( 3979): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3979): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3979): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
D/ConnectivityService( 2409): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,W/Settings( 2409): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine( 2409): ignore requestNetworkTransitionWakelock airplane:true
,I/wpa_supplicant( 3979): Scan requested (ret=0) - scan timeout 30 seconds
D/ConnectivityService( 2409): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2409): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2409): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2409): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2409): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
D/ConnectivityService( 2409): Attempting to switch to mobile
D/ConnectivityService( 2409): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:2
,D/WifiP2pService( 2409): InactiveState{ what=143375 }
,D/WifiP2pService( 2409): P2pEnabledState{ what=143375 }
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2835): DMSUtil.isNetworkConnected - flag-null, state-null
D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 2835): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/NearbySettings( 2835): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 2835): MountReceiver.mPrefHandler - 7002
V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1
,E/WifiStateMachine( 2409): Error! unhandled message{ when=-59ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2409): Error! unhandled message{ when=-59ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiTrafficPoller( 2409): evaluateTrafficStatsPolling
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,W/NetworkManagementService( 2409): route cmd failed: 
W/NetworkManagementService( 2409): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '58 route del src v6 2' failed with '400 58 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2409): '
W/NetworkManagementService( 2409): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2409): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2409): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2409): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2409): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2409): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2409): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2409): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2409): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2409): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2409): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2409): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2409): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,E/WifiStateMachine( 2409): Error! unhandled message{ when=-41ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2835): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/NetUtils( 2409): android_net_utils_resetConnections in env=0x78124ad0 clazz=0x9d800001 iface=wlan0 mask=0x3
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2835): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2835): MountReceiver.mPrefHandler - 7002
D/ConnectivityService( 2409): resetConnections(wlan0, 3)
,E/SPPClientService( 5514): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5514): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5514): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5514): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5514): [b] ResponseMap empty
,D/dalvikvm( 2409): GC_CONCURRENT freed 3876K, 72% free 24794K/86608K, paused 17ms+15ms, total 227ms
,V/NetworkStats( 2409): updateIfacesLocked()
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,V/NetworkStats( 2409): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
V/NetworkStats( 2409): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
V/NetworkStats( 2409): performPollLocked() took 16ms
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/SensorService( 2409):   0.3 -0.0 9.9
,I/ApplicationPolicy( 2409): updateDataUsageMap
,D/Tethering( 2409): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2409): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2409): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2409): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4733): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/PCWCLIENTTRACE_PushUtil( 6551): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6551): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6551): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6551): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6551): noConnectivity : true
,D/libgps  ( 2409): agps_ril_update_network_state: Waiting for IPC connection...
,D/dalvikvm( 5715): GC_CONCURRENT freed 2521K, 27% free 10124K/13864K, paused 14ms+3ms, total 65ms
,D/dalvikvm( 5715): WAIT_FOR_CONCURRENT_GC blocked 48ms
,I/KLMS-2.3.201 : ( 7287): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7287): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450106873433
,I/KLMS-2.3.201 : ( 7287): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/SO_AGENT( 7299): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7299): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5775): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5775): [BDLM] already registered in spp
,I/SA      ( 5775): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5775): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5775): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5775): [OR] == isSIMCardReady false ==
,I/SA      ( 5775): [SCU] == networkStateCheck == false
,I/SA      ( 5775): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7311): Other Intent
,D/com.samsung.app( 7324): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7324): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5839): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5839): getCountryCode(): countryCode = PL
,D/Headlines( 5839): Breath.onCreate
,D/Headlines( 5839): Breath timer started. interval : 30000
,D/Headlines( 5839): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5839): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5839): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5839): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5839): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5839): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5839): requestUpdateNewsWelcomeCard !!! no welcome card
V/AlarmManager( 2409): waitForAlarm result :8
,I/iu.Environment( 5907): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 5907): num queued entries: 0
I/iu.UploadsManager( 5907): num updated entries: 0
,D/QuickConnect[1.1][2] ( 5110): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5110): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5110): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228f220
,I/iu.SyncManager( 5907): NEXT; no task
,D/RCPManagerService( 2409): exchangeData() failure , invalid userId
,D/RCPManagerService( 2409): exchangeData() failure , invalid userId
,I/Babel   ( 5362): connection state changed from CONNECTED to DISCONNECTED
,I/iu.Environment( 3160): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 3160): num queued entries: 0
,I/iu.UploadsManager( 3160): num updated entries: 0
,I/iu.SyncManager( 3160): NEXT; no task
,E/SPPClientService( 5514): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5514): [SystemStateMoniter] Current Time : 602606
,E/SPPClientService( 5514): [SystemStateMoniter] No Connect : true
,D/Headlines( 5839): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5839): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
D/Headlines( 5839): Breath 162 latestRequest time : 1450106873564 current time : 1450106873726
,E/SPPClientService( 5514): [[SystemStateMonitorService]] No Active Internet
,E/SPPClientService( 5514): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5514): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5514): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/libgps  ( 2409): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2409): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2409): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2409): agps_ril_update_network_availability: Waiting for IPC connection...
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/libgps  ( 2409): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2409): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2409): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/ActivityManager( 2409): Waited long enough for: ServiceRecord{46ab5168 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/wpa_supplicant( 3979): nl80211: Received scan results (1 BSSes)
I/wpa_supplicant( 3979): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3979): wlan0: CTRL-EVENT-NO-CONNECTION
I/wpa_supplicant( 3979): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 3979): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
D/WifiP2pService( 2409): InactiveState{ what=147461 }
D/Tethering( 2409): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2409): interfaceStatusChanged wlan0, true
D/WifiP2pService( 2409): P2pEnabledState{ what=147461 }
D/WifiP2pService( 2409): DefaultState{ what=147461 }
D/WifiP2pService( 2409): InactiveState{ what=147462 }
D/WifiP2pService( 2409): P2pEnabledState{ what=147462 }
D/WifiP2pService( 2409): DefaultState{ what=147462 }
,D/SensorService( 2409):   0.3 0.0 9.9
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8975
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8975
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3999): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,D/SensorService( 2409):   0.3 -0.0 9.9
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/PowerManagerService( 2409): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2582
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/NotificationService( 2409): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200a5 contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
D/STATUSBAR-StatusBarManagerService( 2409): sendNotification(1) - 5
,D/RCPManagerService( 2409): NotificationReceiver onReceive()
,D/RCPManagerService( 2409):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
,D/RCPManagerService( 2409): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967298409
,D/RCPManagerService( 2409): getPolicy: policy value returned = false
D/RCPManagerService( 2409): going to get the app label for pkg == com.android.systemui
,D/RCPManagerService( 2409): app label == com.android.systemui
,D/RCPManagerService( 2409): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967298409
,D/UserManagerService( 2409): User -1does not exists!!
D/RCPManagerService( 2409): getPolicy: policy value returned = true
D/RCPManagerService( 2409): Calling User is -1
,D/RCPManagerService( 2409): userid of SBN ==-1
,E/PersonaManagerService( 2409): returning null in  getPersonasForUser
D/ProgressBar( 2582): setProgressDrawable drawableHeight = 12
,D/PhoneStatusBar( 2582): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@422a2c68
,D/BatteryMeterView( 2582): onDraw batteryColor : -1
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/daemonapp( 5308): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5308): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5308): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionTIME_TICK
,I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(56)
,D/daemonapp( 5308): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5308): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5308): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5308): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5308): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 5308): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 5308): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
,D/comsamsunglog( 5308): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5308): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5308): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5308): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 5308): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5308): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5308): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 5308): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5308): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 0
,I/display ( 1921): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/AmoledAdjustTimer( 2409): prevTemp = 301, currTemp = 302, prevStep = 4, currStep = 4
,D/SensorService( 2409):   0.3 0.0 9.9
,D/TimaService( 2409): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2409): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2409): TimaServiceHandler.handleMessage what =1
,I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(59)
,I/wpa_supplicant( 3979): Scan requested (ret=0) - scan timeout 30 seconds
,I/display ( 1921): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=0, deviceClass=0])
D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,I/ActivityManager( 2409): Waited long enough for: ServiceRecord{444a4678 u0 com.sec.android.app.videoplayer/.videowall.TranscodeService}
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3
,D/SensorService( 2409):   0.3 -0.0 9.9
,I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(60)
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 3999): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/display ( 1921): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,I/wpa_supplicant( 3979): nl80211: Received scan results (1 BSSes)
I/wpa_supplicant( 3979): wlan0: Setting scan request: 16 sec 0 usec
I/wpa_supplicant( 3979): wlan0: CTRL-EVENT-NO-CONNECTION
,I/wpa_supplicant( 3979): wlan0: Setting scan request: 16 sec 0 usec
D/WifiP2pService( 2409): InactiveState{ what=147461 }
D/WifiP2pService( 2409): P2pEnabledState{ what=147461 }
D/WifiP2pService( 2409): DefaultState{ what=147461 }
,D/Tethering( 2409): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2409): interfaceStatusChanged wlan0, true
,I/ActivityManager( 2409): Waited long enough for: ServiceRecord{46390df8 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,I/TLC_TIMA_PKM_measure_kernel( 2409): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2409): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2409): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2409): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2409): !@Sync 20
,D/SensorService( 2409):   0.3 -0.0 9.8
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 302, currTemp = 303, prevStep = 4, currStep = 4
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Nexus 5
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/SensorService( 2409):   0.3 -0.0 9.9
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [08:ec:a9:50:76:27]: 7, f, 6109
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=0, deviceClass=0]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Thali Test (Galaxy A3),
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/PowerManagerService( 2409): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 2409): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2409): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/lights  ( 2409): lcd : 2 +
D/RampAnimator( 2409): Light Animator Finished currentValue=2
,D/lights  ( 2409): lcd : 2 -
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 3979): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3979): Scan requested (ret=0) - scan timeout 30 seconds
,D/SensorService( 2409):   0.3 0.0 9.9
,I/wpa_supplicant( 3979): nl80211: Received scan results (1 BSSes)
I/wpa_supplicant( 3979): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3979): wlan0: CTRL-EVENT-NO-CONNECTION
,I/wpa_supplicant( 3979): wlan0: Setting scan request: 8 sec 0 usec
D/WifiP2pService( 2409): InactiveState{ what=147461 }
D/WifiP2pService( 2409): P2pEnabledState{ what=147461 }
D/Tethering( 2409): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2409): interfaceStatusChanged wlan0, true
D/WifiP2pService( 2409): DefaultState{ what=147461 }
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [34:fc:ef:11:ae:67]: 0, 0, 0
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Nexus 5
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/SensorService( 2409):   0.3 -0.0 9.9
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbc668 rs_disc_pending=1
E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/PowerManagerService( 2409): [s] UserActivityState : 2 -> 0
I/PowerManagerService( 2409): [PWL] On : 588720 (39942 ms ago)
I/PowerManagerService( 2409): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
,I/PowerManagerService( 2409): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=2582, ws=null) (elapsedTime=19934)
,D/PowerManagerService( 2409): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2582 (0x0)
,I/PowerManagerService( 2409): Nap time...
D/PowerManagerService( 2409): [s] WAKEFULNESS_NAPPING
,I/PowerManagerService( 2409): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2409): Going to sleep due to screen timeout...
,D/PowerManagerService( 2409): [s] WAKEFULNESS_ASLEEP
,D/DisplayPowerController( 2409): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/DisplayPowerController( 2409): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/Sensors ( 2409): LightSensor enable = 0
,D/Sensors ( 2409): LightSensor enableSensor = 0
D/DisplayPowerController( 2409): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
D/SensorManager( 2409): unregisterListener ::   
,I/SurfaceFlinger( 1921): id=22 createSurf (720x1280),-1 flag=20004, FlectronBea
I/DisplayPowerController( 2409): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
,I/Sensors ( 2409): HAL:resetDataRates mEnabled=4
,D/DisplayPowerController( 2409): !@ElectronBeam entry
,D/SensorManager( 2409): unregisterListener ::   
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/lights  ( 2409): lcd : 0 +
,D/lights  ( 2409): lcd : 0 -
D/PowerManagerService( 2409): blankAllDisplays() is called.
D/PowerManagerService( 2409): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2409): [PWL] sb acquire: PowerManagerService.Broadcasts
D/MISC PowerHAL( 2409): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2409): sysfs_write +: /sys/class/input/input1/enabled: 0
V/WindowOrientationListener( 2409): WindowOrientationListener disabled
D/SensorService( 2409): AutoRotationSensor::activate (ident=0x81c9f9c8, enabled=0)
,I/Sensors ( 2409): HAL: batch Dry Run is complete
,D/PowerManagerService( 2409): [PWL] sb release: PowerManagerService.Display
D/KeyguardViewMediator( 2582): onScreenTurnedOff(3)
D/MISC PowerHAL( 2409): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2409): miscpower_set_interactive: /sys/class/input/input0/enabled
D/MISC PowerHAL( 2409): sysfs_write +: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2409): sysfs_write -: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2409): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2409): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/SEC PowerHAL( 2409): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2409): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SensorManager( 2409): unregisterListener ::   
D/SEC PowerHAL( 2409): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2409): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/InputDispatcher( 2409): setInputDispatchMode: enabled=0, frozen=0
D/SEC PowerHAL( 2409): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2409): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2409): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SEC PowerHAL( 2409): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SurfaceFlinger( 1921): Screen released, type=0 flinger=0x40eec550
D/PowerManagerService( 2409): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,D/LockPatternUtils( 2582): isPcwEnable = 10
,D/LockPatternUtils( 2582): isPcwEnable = 10
,D/SurfaceControl( 2409): Excessive delay in blankDisplay() while turning screen off: 209ms
I/libsuspend( 2409): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2409): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2409): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 216ms
D/PowerManagerService( 2409): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2409): [PWL] Off : 0s ago
I/PowerManagerService( 2409): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2409): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2409): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=2409, ws=null) (elapsedTime=215)
I/PowerManagerService( 2409): [PWL]   PowerManagerService.Broadcasts: ref count=1
,I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(29)
,I/DBG_DM  ( 4733): [3.19.140541][Line:400][onPause] 
,I/SQLiteSecureOpenHelper( 4172): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4172): getDatabaseLocked(b,b,pwd)...
,D/KeyguardViewMediator( 2582): setting alarm to turn off keyguard, seq = 2
,D/LightsService( 2409): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2409) 
,I/SensorManagerA( 2409): getReportingMode :: sensor.mType = 5
D/Sensors ( 2409): LightSensor setDelay = 200000000
,D/Sensors ( 2409): LightSensor setSensorDelay = 200000000
D/Sensors ( 2409): Light sensor flush: not enabled 0
D/Sensors ( 2409): LightSensor enable = 1
,D/Sensors ( 2409): LightSensor enableSensor = 1
D/LightsService( 2409): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/SensorManager( 2409): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2409): turn on LED for fully charged
D/VibratorService( 2409): JNI vibratorOff()
,I/WifiTrafficPoller( 2409): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2409): ACTION_SCREEN_OFF
D/LightsService( 2409): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2409) 
,D/LightsService( 2409): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/AudioHardwareTinyALSA( 1925): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2409): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2409): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2409): Bridge Server is not available
,D/PersonaManagerService( 2409): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2409): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2582):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2582): makeExpandedInvisible
D/PhoneStatusBarView( 2582): marqueeStatusBar:122, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2582):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2766): applyRouting return - 2 
,E/NfcService( 2766): callback == null
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3
,D/LockPatternUtils( 2582): isPcwEnable = 10
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 0
,D/QuickConnect[1.1][2] ( 5110): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
,V/QuickConnect[1.1][2] ( 5110): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5110): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
,V/QuickConnect[1.1][2] ( 5110): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228f220
V/QuickConnect[1.1][2] ( 5110): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228f220
D/QuickConnect[1.1][2] ( 5110): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 5110): BleHelper.stopScan - shouldScanBleBg = false
,I/QuickConnect[1.1][2] ( 5110): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 5110): stopLeScan()
,D/QuickConnect[1.1][2] ( 5110): BleHelper.stopScan - call stopLeScan() complete
,E/TranscodeReceiver( 7468): onReceive : android.intent.action.SCREEN_OFF
,D/TranscodeService( 7468): power? : true / screen off : true
D/PowerManagerService( 2409): [PWL] sb release: PowerManagerService.Broadcasts
D/TranscodeService( 7468): Music is = false
,D/TranscodeService( 7468): runvideoplayer is false
,D/TranscodeService( 7468): Thread start
D/TranscodeService( 7468): WakeLock.acquire()
,D/videowall-FileMgr( 7468): thumbnailDBSync -1
,D/Sensors ( 2409): LightSensor enable = 0
,D/Sensors ( 2409): LightSensor enableSensor = 0
,D/LightsService( 2409): [SvcLED]  onSensorChanged::light value = 5
D/SensorManager( 2409): unregisterListener ::   
D/lights  ( 2409): led_pattern : 5 +
,D/lights  ( 2409): led_pattern : 5 -
D/LightsService( 2409): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/WVMDrmPlugIn( 1924): WVMDrmPlugin::onInitialize : 3246
,D/WVMDrmPlugIn( 1924): WVMDrmPlugin::onSetOnInfoListener : add 3246
I/PrGenericPlugin( 1924): [A] ENTER onInitialize : 0xcae
,I/PrGenericPlugin( 1924): [A] LEAVE onInitialize : 0xcae
,D/TranscodeService( 7468): Thread end
,D/TranscodeService( 7468): WakeLock.release()
D/TranscodeService( 7468): onDestroy()
D/TranscodeService( 7468): releaseTranscodeThread.
,D/TranscodeService( 7468): Thread isAlive
,D/vwengine( 7468): stopTranscoding
,D/TranscodeService( 7468): transThread.join();
,V/ApplicationPolicy( 2409): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
,D/AmoledAdjustTimer( 2409): prevTemp = 303, currTemp = 305, prevStep = 4, currStep = 4,
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new,
,V/AlarmManager( 2409): waitForAlarm result :8,
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag,
E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0,
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 0:0,
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Nexus 5,
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,V/AlarmManager( 2409): waitForAlarm result :4,
,D/KeyguardViewMediator( 2582): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2,
,D/LockPatternUtils( 2582): isPcwEnable = 10,
,D/KeyguardViewMediator( 2582): in doKeyguardLocked mIsRollUp false null,
,D/PersonaManager( 2582): isKioskContainerExistOnDevice,
,D/LockPatternUtils( 2582): isPcwEnable = 10
,V/AlarmManager( 2409): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/LockPatternUtils( 2582): isPcwEnable = 10
D/KeyguardViewMediator( 2582): doKeyguard: not showing because lockscreen is off
,D/Headlines( 5839): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5839): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5839): Breath 31613 latestRequest time : 1450106873564 current time : 1450106905177
,I/PowerManagerService( 2409): [PWL] Off : 5s ago
,I/wpa_supplicant( 3979): Scan requested (ret=0) - scan timeout 30 seconds,
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27,
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/        ( 3999): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=0, deviceClass=0]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Thali Test (Galaxy A3),
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3
,I/wpa_supplicant( 3979): nl80211: Received scan results (1 BSSes)
I/wpa_supplicant( 3979): wlan0: Setting scan request: 16 sec 0 usec
I/wpa_supplicant( 3979): wlan0: CTRL-EVENT-NO-CONNECTION
,I/wpa_supplicant( 3979): wlan0: Setting scan request: 16 sec 0 usec,
D/WifiP2pService( 2409): InactiveState{ what=147461 }
D/WifiP2pService( 2409): P2pEnabledState{ what=147461 }
D/WifiP2pService( 2409): DefaultState{ what=147461 },
,D/Tethering( 2409): interfaceLinkStateChanged wlan0, true,
,D/Tethering( 2409): interfaceStatusChanged wlan0, true
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2409): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 0:0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 0:0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Nexus 5
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbc668 rs_disc_pending=1,
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag,
E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=0, deviceClass=0]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Thali Test (Galaxy A3),
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2409): [PWL] Off : 15s ago,
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new,
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag,
E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0,
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Nexus 5,
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,E/Watchdog( 2409): !@Sync 21,
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true,
,D/BatteryService( 2409): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3999): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27,
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/        ( 3999): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=0, deviceClass=0]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/        ( 3999): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Nexus 5
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,I/wpa_supplicant( 3979): Scan requested (ret=0) - scan timeout 30 seconds
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:2a:f7:ed:96:be,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 271
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 271,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbc134 rs_disc_pending=0,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 271
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:1544,
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/        ( 3999): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: ALE-L21
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbc134 rs_disc_pending=1
,I/wpa_supplicant( 3979): nl80211: Received scan results (1 BSSes)
,I/wpa_supplicant( 3979): wlan0: Setting scan request: 32 sec 0 usec
I/wpa_supplicant( 3979): wlan0: CTRL-EVENT-NO-CONNECTION
,I/wpa_supplicant( 3979): wlan0: Setting scan request: 32 sec 0 usec,
,D/Tethering( 2409): interfaceLinkStateChanged wlan0, true,
,D/Tethering( 2409): interfaceStatusChanged wlan0, true,
D/WifiP2pService( 2409): InactiveState{ what=147461 }
D/WifiP2pService( 2409): P2pEnabledState{ what=147461 }
D/WifiP2pService( 2409): DefaultState{ what=147461 }
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2409): mCoverManager.getCoverState() : true,
,D/BatteryService( 2409): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3999): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2409): [PWL] Off : 30s ago,
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 0,
,V/AlarmManager( 2409): waitForAlarm result :4,
,V/AlarmManager( 2409): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8709,
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8709,
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag,
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED,
,D/AmoledAdjustTimer( 2409): prevTemp = 305, currTemp = 304, prevStep = 4, currStep = 4
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Nexus 5
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbc9e0 rs_disc_pending=0
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Note4-1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbc9e0 rs_disc_pending=1
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag,
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 271
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:1544,
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: ALE-L21,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,V/AlarmManager( 2409): waitForAlarm result :8,
,D/Headlines( 5839): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
D/Headlines( 5839): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5839): Breath 60007 latestRequest time : 1450106873564 current time : 1450106933571,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 271
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/        ( 3999): remote version info [08:ec:a9:50:76:27]: 6, 10f, 608,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=0, deviceClass=0]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Thali Test (Galaxy A3),
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbc9e0 rs_disc_pending=0
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbc668 rs_disc_pending=0,
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new,
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/        ( 3999): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,E/bt-btm  ( 3999): RS in progress - Set DISC Pending flag in btm_sec_send_hci_disconnect to delay disconnect,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Nexus 5,
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 271
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:1544
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED,
V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=0, deviceClass=0]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Thali Test (Galaxy A3),
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbc9e0 rs_disc_pending=1
,V/AlarmManager( 2409): waitForAlarm result :8,
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3,
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag,
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8709
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED,
V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Note4-1,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 0
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:2a:f7:ed:96:be,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 271
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 271,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/AmoledAdjustTimer( 2409): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:2a:f7:ed:96:be,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003,
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/        ( 3999): remote version info [58:2a:f7:ed:96:be]: 7, 1d, 7d3,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: ALE-L21,
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbc824 rs_disc_pending=0,
,I/GAV2    ( 5601): Thread[disconnect check,5,main]: Disconnecting due to inactivity,
,I/GAV2    ( 5601): Thread[disconnect check,5,main]: Disconnected from service,
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag,
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Nexus 5,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new,
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbc134 rs_disc_pending=0,
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag,
E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:2a:f7:ed:96:be,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: ALE-L21,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1,
,E/Watchdog( 2409): !@Sync 22,
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3999): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8709
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0,
,I/PowerManagerService( 2409): [PWL] Off : 50s ago,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 271
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:1544
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [e0:db:10:14:e2:c0]: 6, 10f, 608,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Note4-1
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = -10
,D/AmoledAdjustTimer( 2409): prevTemp = 304, currTemp = 303, prevStep = 4, currStep = 4,
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag,
E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 271
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Note4-1,
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new,
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true,
,D/BatteryService( 2409): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3999): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2409): prevTemp = 303, currTemp = 302, prevStep = 4, currStep = 4,
,I/wpa_supplicant( 3979): Scan requested (ret=0) - scan timeout 30 seconds,
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 271
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:1544
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1,
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 271
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0,
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8709,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Note4-1,
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
V/AlarmManager( 2409): waitForAlarm result :8
,D/Headlines( 5839): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5839): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5839): Breath 90005 latestRequest time : 1450106873564 current time : 1450106963569
,I/wpa_supplicant( 3979): nl80211: Received scan results (1 BSSes),
I/wpa_supplicant( 3979): wlan0: Setting scan request: 64 sec 0 usec
I/wpa_supplicant( 3979): wlan0: CTRL-EVENT-NO-CONNECTION
,I/wpa_supplicant( 3979): wlan0: Setting scan request: 64 sec 0 usec,
,D/Tethering( 2409): interfaceLinkStateChanged wlan0, true,
,D/Tethering( 2409): interfaceStatusChanged wlan0, true,
D/WifiP2pService( 2409): InactiveState{ what=147461 }
,D/WifiP2pService( 2409): P2pEnabledState{ what=147461 },
,D/WifiP2pService( 2409): DefaultState{ what=147461 },
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:2a:f7:ed:96:be,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:2a:f7:ed:96:be,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:2a:f7:ed:96:be,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841,
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/        ( 3999): remote version info [58:2a:f7:ed:96:be]: 7, f, 6109,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: ALE-L21,
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag,
E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Note4-1,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new,
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0,
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag,
E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:2a:f7:ed:96:be,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED,
V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: ALE-L21,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1,
,D/dalvikvm( 3999): GC_CONCURRENT freed 2664K, 29% free 9857K/13784K, paused 13ms+3ms, total 84ms,
,D/AmoledAdjustTimer( 2409): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2409): [PWL] Off : 75s ago,
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0,
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8709,
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/        ( 3999): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Note4-1
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:2a:f7:ed:96:be,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:2a:f7:ed:96:be,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 271
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/        ( 3999): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: ALE-L21,
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbc9e0 rs_disc_pending=1,
,E/Watchdog( 2409): !@Sync 23,
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/BatteryService( 2409): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3999): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0,
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbc134 rs_disc_pending=0,
,D/AmoledAdjustTimer( 2409): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4,
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag,
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8709,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,D/dalvikvm( 2409): GC_CONCURRENT freed 2939K, 71% free 25599K/86580K, paused 22ms+21ms, total 259ms,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Note4-1,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new,
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag,
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 271
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: ALE-L21,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1,
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8709,
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/        ( 3999): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Note4-1,
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbc9e0 rs_disc_pending=0
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2409): mCoverManager.getCoverState() : true
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4,
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:2a:f7:ed:96:be,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 271,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:1544,
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 271,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:1544,
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:2a:f7:ed:96:be,
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 271,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/        ( 3999): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: ALE-L21,
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbc9e0 rs_disc_pending=1,
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbc9e0 rs_disc_pending=0,
,V/AlarmManager( 2409): waitForAlarm result :8,
,D/Headlines( 5839): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5839): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
D/Headlines( 5839): Breath 120030 latestRequest time : 1450106873564 current time : 1450106993594
,D/Headlines( 5839): stop ,
,D/Headlines( 5839): Breath.onDestroy : ,
I/ActivityManager( 2409): Killing 6595:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty #43
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbc134 rs_disc_pending=0,
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new,
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag,
E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Note4-1,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag,
E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:2a:f7:ed:96:be,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 271
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,V/AlarmManager( 2409): waitForAlarm result :8,
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK,
,V/AlarmManager( 2409): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2409): <AppSync3 Whitelist>
,V/AlarmManager( 2409): (AppSync) ### 0 added ###,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3,
,D/dalvikvm( 4073): GC_CONCURRENT freed 2890K, 30% free 9724K/13836K, paused 15ms+3ms, total 96ms,
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2409): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2409): [PWL] Off : 105s ago,
,E/Watchdog( 2409): !@Sync 24,
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
,D/BatteryService( 2409): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2409): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,I/wpa_supplicant( 3979): Scan requested (ret=0) - scan timeout 30 seconds,
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): stay LED for fully charged
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4
,I/wpa_supplicant( 3979): nl80211: Received scan results (2 BSSes),
I/wpa_supplicant( 3979): wlan0: Setting scan request: 128 sec 0 usec
I/wpa_supplicant( 3979): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz),
,I/wpa_supplicant( 3979): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=,
,D/Tethering( 2409): interfaceLinkStateChanged wlan0, true,
,D/Tethering( 2409): interfaceStatusChanged wlan0, true,
,I/wpa_supplicant( 3979): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030,
,D/Tethering( 2409): interfaceLinkStateChanged wlan0, true
D/Tethering( 2409): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3979): Associated with C0.AA.48
D/Tethering( 2409): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2409): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3979): freq(2412) increment count 3
,I/wpa_supplicant( 3979): meet head of list.
D/Tethering( 2409): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2409): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3979): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3979): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3979): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3979): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3979): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2409): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2409): interfaceStatusChanged wlan0, true
,D/WifiNative( 2409): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2835): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
,I/NearbySettings( 2835): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2835): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2835): MountReceiver.mPrefHandler - 7002
,D/WifiP2pService( 2409): InactiveState{ what=143375 }
,D/WifiP2pService( 2409): P2pEnabledState{ what=143375 }
,I/dhcpcd  (10440): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  (10440): bssid match
,D/WifiP2pService( 2409): InactiveState{ what=143375 }
,D/WifiP2pService( 2409): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2409): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2409): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2409): CaptivePortalCheckState enter
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2409): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2409): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2409): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2409): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/NearbySettings( 2835): MountReceiver.onReceive - Keep current state
,I/WifiTrafficPoller( 2409): evaluateTrafficStatsPolling
D/ConnectivityService( 2409): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2409): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2409): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2409): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2835): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,I/NearbySettings( 2835): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2835): MountReceiver.onReceive - Keep current state
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,I/NearbySettings( 2835): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger( 1921): id=23 createSurf (1x1),1 flag=4, Uoast
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/PowerManagerService( 2409): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2409
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
V/NetworkStats( 2409): updateIfacesLocked()
,V/NetworkStats( 2409): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
V/NetworkStats( 2409): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
V/NetworkStats( 2409): performPollLocked() took 22ms
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/Tethering( 2409): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2409): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2409): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
,D/STATUSBAR-NetworkController( 2582): updateDataNetType()
D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4733): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
I/PCWCLIENTTRACE_PushUtil( 6551): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6551): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6551): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6551): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/libgps  ( 2409): agps_ril_update_network_state: Waiting for IPC connection...
,I/KLMS-2.3.201 : ( 7287): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/System.err( 7268): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7268): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7268): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7268): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7268): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7268): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7268): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7268): Caused by: java.lang.NullPointerException
,D/dalvikvm( 7268): GC_CONCURRENT freed 2695K, 29% free 9945K/13860K, paused 4ms+5ms, total 44ms
,W/System.err( 7268): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7268): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7268): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7268): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7268): 	... 8 more
,I/KLMS-2.3.201 : ( 7287): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450107035798
,I/KLMS-2.3.201 : ( 7287): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7299): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7299): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/LocationTagReadyService( 3300): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3300): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3300): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3300): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 3428): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,V/KVNProvider( 7482): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7482): getFindoCursor query string : 
,V/KVNProvider( 7482): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 5775): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5775): [BDLM] already registered in spp
,I/SA      ( 5775): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5775): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5775): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5775): [OR] == isSIMCardReady false ==
,I/SA      ( 5775): [SCU] == networkStateCheck == true
I/SA      ( 5775): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5775): isChinaCountryCode : false
,I/SA      ( 5775): [OR] == networkStateCheck true ==
I/SA      ( 5775): [OR] GetMyCountryZoneTask
,I/SA      ( 5775): [SRS] prepareGetMyCountryZone
,I/SA      ( 5775): [OR] onReceive END
I/SA      ( 5775): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5775): [SSP] query invoked
,I/SA      ( 5775): [TPMU] GetMccFromDB : null
,I/SA      ( 5775): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5775): [TPM] isNoProxy(default) : true
,I/SA      ( 5775): [RC New] Execute method=[GET] start
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7311): Other Intent
,D/com.samsung.app( 7324): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7324): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5839): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE,
,D/HeadlinesChannelUtil( 5839): getCountryCode(): countryCode = PL
,D/Headlines( 5839): Breath.onCreate
,D/Headlines( 5839): Breath timer started. interval : 30000
,V/AlarmManager( 2409): waitForAlarm result :8
D/Headlines( 5839): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5839): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5839): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5839): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5839): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5839): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5839): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 5907): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 5907): num queued entries: 0
,I/iu.UploadsManager( 5907): num updated entries: 0
,D/QuickConnect[1.1][2] ( 5110): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/iu.SyncManager( 5907): NEXT; no task
I/QuickConnect[1.1][2] ( 5110): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5110): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4228f220
,D/RCPManagerService( 2409): exchangeData() failure , invalid userId
,D/RCPManagerService( 2409): exchangeData() failure , invalid userId
,D/WaitQueueForNetworkActivate( 5928): notifyNetworkActivated
,D/hcjo    ( 5928): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 5928): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5928): exit::IDLE
,D/InitializeManagerStateMachine( 5928): entry::NETWORK_CHECK,
D/InitializeManagerStateMachine( 5928): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 5928): exit::NETWORK_CHECK,
D/InitializeManagerStateMachine( 5928): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5928): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 5928): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5928): entry::SUCCESS
,D/hcjo    ( 5928): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5928): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5928): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5928): exit::SUCCESS
,D/InitializeManagerStateMachine( 5928): entry::IDLE
,I/iu.Environment( 3160): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 3160): num queued entries: 0
,I/iu.UploadsManager( 3160): num updated entries: 0
,I/iu.SyncManager( 3160): NEXT; no task
,E/SPPClientService( 5514): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5514): [SystemStateMoniter] Current Time : 765078
,E/SPPClientService( 5514): [SystemStateMoniter] No Connect : false
,D/Headlines( 5839): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5839): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5839): Breath 147 latestRequest time : 1450107036047 current time : 1450107036194
,I/Babel   ( 5362): connection state changed from DISCONNECTED to CONNECTED
,D/libgps  ( 2409): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2409): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2409): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2409): agps_ril_update_network_availability: Waiting for IPC connection...
,I/SA      ( 5775): [RC New] [v2liruge] api execute + 705
,I/SA      ( 5775): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5775): AsyncTask #3 calls detatch()
,I/SA      ( 5775): [TPMU] getNetworkMcc : 
,I/SA      ( 5775): [SCU] saveMccToPreferece Start
,I/SA      ( 5775): [SCU] RegionMCC : 260
,I/SA      ( 5775): [SSP] query invoked
,I/SA      ( 5775): [TPMU] GetMccFromDB : null
I/SA      ( 5775): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5775): [SCU] saveMccToPreferece End
I/SA      ( 5775): [RC New] executeRequest [v2liruge] end. 729
,I/SA      ( 5775): [RC New] Execute end
I/SA      ( 5775): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5775): [OR] GetMyCountryZoneTask Success
,D/ConnectivityService( 2409): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
,D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
,W/WifiP2pStateTracker( 2409): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED,
,D/ConnectivityService( 2409): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0,
D/ConnectivityService( 2409):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
D/ConnectivityService( 2409): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2409): updateSourceRoutes : no source routing conditions,
,D/libgps  ( 2409): agps_ril_update_network_availability: Waiting for IPC connection - timeout,
E/libgps  ( 2409): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2409): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability,
,E/WifiStateMachine( 2409): CAPTIVE_PORTAL_EVENT_AUTHENTICATED,
,I/SurfaceFlinger( 1921): id=23 Removed Uoast (10/11),
,I/SurfaceFlinger( 1921): id=23 Removed Uoast (-2/11),
D/PowerManagerService( 2409): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2409) eventTime = 767387
D/PowerManagerService( 2409): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2409 (0x0)
D/PowerManagerService( 2409): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2409, ws=WorkSource{1000}) (elapsedTime=3478)
,E/Watchdog( 2409): !@Sync 25,
,E/SPPClientService( 5514): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19,
,V/AlarmManager( 2409):  next == MAX_VALUE,
,E/SPPClientService( 5514): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false,
,E/SPPClientService( 5514): [a] [ConnectionManager] Connection is already disconnected.,
,E/SPPClientService( 5514): [g] getNetMCC return empty string,
,I/PowerManagerService( 2409): [PWL] Off : 140s ago,
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6551): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil( 6551): [hasSamungAccount] - No Samsung Account,
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6551): [GetString-S],
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6551): GetString : secure API is not supported!!,
I/PCWCLIENTTRACE_PushUtil( 6551): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6551): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6551): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6551): [ensureRegistration] - No Samsung account,
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true,
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2409): prevTemp = 298, currTemp = 300, prevStep = 4, currStep = 4
,E/SPPClientService( 5514): [b] __InitReply__,
,D/CaptivePortalTracker( 2409): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler },
D/ConnectivityService( 2409): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2409): Checking http://216.58.209.78/generate_204,
,D/CaptivePortalTracker( 2409): Don't send network conditions - lacking user consent.,
D/CaptivePortalTracker( 2409): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 2409): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2409): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
D/ConnectivityService( 2409): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 5928): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 5928): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5928): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 5928): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5928): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5928): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5928): entry::IDLE,
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10,
D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 2409): Waited long enough for: ServiceRecord{4636b0d0 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,D/AmoledAdjustTimer( 2409): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4,
,I/ActivityManager( 2409): Waited long enough for: ServiceRecord{42879980 u0 com.sec.spp.push/.PushClientService},
,V/AlarmManager( 2409): waitForAlarm result :8,
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2409): stay LED for fully charged
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/AmoledAdjustTimer( 2409): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,V/AlarmManager( 2409): waitForAlarm result :8,
,D/Headlines( 5839): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5839): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5839): Breath 30028 latestRequest time : 1450107036047 current time : 1450107066075,
,E/Watchdog( 2409): !@Sync 26,
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2409): stay LED for fully charged,
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3999): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2409): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2409): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2409): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2409): stay LED for fully charged,
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3999): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2409): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4,
,V/AlarmManager( 2409): waitForAlarm result :8,
,D/Headlines( 5839): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5839): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5839): Breath 60024 latestRequest time : 1450107036047 current time : 1450107096072,
,E/Watchdog( 2409): !@Sync 27,
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2409): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: G4-1,
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2409): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag,
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: G4-1,
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new,
,V/AlarmManager( 2409): waitForAlarm result :8,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate,
V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2409): prevTemp = 296, currTemp = 297, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1,
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/        ( 3999): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: G4-1,
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,I/PowerManagerService( 2409): [PWL] Off : 225s ago,
,V/AlarmManager( 2409): waitForAlarm result :8,
,D/Headlines( 5839): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5839): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5839): Breath 90026 latestRequest time : 1450107036047 current time : 1450107126074,
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag,
E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: G4-1,
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new,
,E/Watchdog( 2409): !@Sync 28,
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2409): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/        ( 3999): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: G4-1,
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/dalvikvm( 6391): GC_CONCURRENT freed 1879K, 28% free 10097K/13840K, paused 2ms+3ms, total 63ms,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:1f:c9:5e,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:1f:c9:5e,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109,
,E/BluetoothRemoteDevices( 3999): aclStateChangeCallback: Device is NULL,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED,
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbb888 rs_disc_pending=1,
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbcb9c rs_disc_pending=0,
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag,
E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841,
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: G4-1,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag,
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=0, deviceClass=0]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2409): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:1f:c9:5e,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:1f:c9:5e,
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/        ( 3999): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=0, deviceClass=0]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Note3-1,
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/        ( 3999): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: G4-1,
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbcb9c rs_disc_pending=1,
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag,
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=0, deviceClass=0]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: S5-1,
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0,
D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2409): stay LED for fully charged
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2409): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:1f:c9:5e,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
D/IOP_DB_BT( 3999): db_query_execute: result 1,
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:1f:c9:5e,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841,
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:1f:c9:5e,
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/        ( 3999): remote version info [e0:db:10:1f:c9:5e]: 7, f, 2205,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=0, deviceClass=0]),
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Note3-1,
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag,
E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,V/AlarmManager( 2409): waitForAlarm result :8,
,D/Headlines( 5839): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5839): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
D/Headlines( 5839): Breath 120034 latestRequest time : 1450107036047 current time : 1450107156081
,D/Headlines( 5839): stop ,
,D/Headlines( 5839): Breath.onDestroy : ,
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new,
,E/Watchdog( 2409): !@Sync 29,
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag,
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:1f:c9:5e,
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3999): db_query_execute: result 1,
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED,
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Note3-1,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called,
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2409): stay LED for fully charged
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2409): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: G4-1
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbbc00 rs_disc_pending=1
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbb888 rs_disc_pending=0
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Note3-1
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/dalvikvm( 2409): GC_CONCURRENT freed 3906K, 71% free 25615K/86580K, paused 13ms+20ms, total 231ms
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbbc00 rs_disc_pending=1
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbb888 rs_disc_pending=1
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbbc00 rs_disc_pending=1
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2409): prevTemp = 298, currTemp = 299, prevStep = 4, currStep = 4
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,I/PowerManagerService( 2409): [PWL] Off : 275s ago
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Note3-1
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2409): stay LED for fully charged
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2409): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbbc00 rs_disc_pending=1
,D/TimaService( 2409): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2409): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2409): TimaServiceHandler.handleMessage what =1
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,I/TLC_TIMA_PKM_measure_kernel( 2409): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2409): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2409): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2409): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2409): !@Sync 30
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2409): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: S5-1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [e0:db:10:1f:c9:5e]: 7, f, 610c
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Note3-1
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbcb9c rs_disc_pending=0
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 6109
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: S5-1
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbcb9c rs_disc_pending=1
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,E/bt-btm  ( 3999): RS in progress - Set DISC Pending flag in btm_sec_send_hci_disconnect to delay disconnect
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbbc00 rs_disc_pending=2
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: S5-1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8975
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Nexus 6
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: S5-1
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbba44 rs_disc_pending=1
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8975
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Nexus 6
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,E/bt-btm  ( 3999): RS in progress - Set DISC Pending flag in btm_sec_send_hci_disconnect to delay disconnect
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,E/bt-btm  ( 3999): tBTM_SEC_DEV:0x77dbbc00 rs_disc_pending=2
E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: S5-1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8975
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8975
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,E/Watchdog( 2409): !@Sync 31
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2409): mCoverManager.getCoverState() : true
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2409): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2409): !@Sync 32
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8975
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8975
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,E/bt-l2cap( 3999): L2CAP got conn_req while connected (state:4). Reject it
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Nexus 6
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2409): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/bt-l2cap( 3999): L2CAP got conn_comp in bad state: 4  status: 0x16
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8975
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Nexus 6
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8975
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8975
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8975
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Nexus 6
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8975
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Nexus 6
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 298, currTemp = 299, prevStep = 4, currStep = 4
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8975
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8975
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8975
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Nexus 6
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8975
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Nexus 6
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/Watchdog( 2409): !@Sync 33
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8975
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8975
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8975
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Nexus 6
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:8975
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Nexus 6
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/PowerManagerService( 2409): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2409): stay LED for fully charged
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2409): !@Sync 34
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2409): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2409): waitForAlarm result :4
,V/AlarmManager( 2409): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2409): !@Sync 35
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2409): [PWL] Off : 455s ago
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2778): GC_CONCURRENT freed 7044K, 39% free 18945K/30708K, paused 15ms+8ms, total 108ms
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2409): !@Sync 36
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3999): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,D/dalvikvm( 3999): GC_CONCURRENT freed 1980K, 29% free 9827K/13768K, paused 4ms+4ms, total 46ms
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Thali Test (Galaxy A5)
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,E/Watchdog( 2409): !@Sync 37
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Thali Test (Galaxy A5)
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Thali Test (Galaxy A5)
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Thali Test (Galaxy A5)
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 294, currTemp = 295, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: Thali Test (Galaxy A5)
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,I/PowerManagerService( 2409): [PWL] Off : 525s ago
,E/Watchdog( 2409): !@Sync 38
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2409): !@Sync 39
,V/AlarmManager( 2409): waitForAlarm result :4
,V/AlarmManager( 2409): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5514): [b] __PingReply__
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/dalvikvm( 2409): GC_CONCURRENT freed 3948K, 71% free 25615K/86580K, paused 21ms+21ms, total 252ms
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/TimaService( 2409): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2409): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2409): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2409): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2409): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2409): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2409): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2409): !@Sync 40
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,I/PowerManagerService( 2409): [PWL] Off : 600s ago
,V/AlarmManager( 2409): waitForAlarm result :8
,I/SensorManagerA( 2409): getReportingMode :: sensor.mType = 5
,D/LightsService( 2409): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2409): LightSensor setDelay = 200000000
D/Sensors ( 2409): LightSensor setSensorDelay = 200000000
D/Sensors ( 2409): Light sensor flush: not enabled 0
D/Sensors ( 2409): LightSensor enable = 1
D/Sensors ( 2409): LightSensor enableSensor = 1
D/SensorManager( 2409): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2409): LightSensor enable = 0
,D/Sensors ( 2409): LightSensor enableSensor = 0
,D/LightsService( 2409): [SvcLED]  onSensorChanged::light value = 5
,D/SensorManager( 2409): unregisterListener ::   
D/LightsService( 2409): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2409): !@Sync 41
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:75:41
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3999): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:75:41
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: A3-1
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:75:41
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: A3-1
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:75:41
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: A3-1
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 292, currTemp = 293, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:75:41
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: A3-1
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,E/Watchdog( 2409): !@Sync 42
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:75:41
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: A3-1
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:75:41
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0,
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!,
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: A3-1
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:75:41
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: A3-1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 293, currTemp = 294, prevStep = 4, currStep = 4
,W/ProcessCpuTracker( 2409): Skipping unknown process pid 13431
,W/ProcessCpuTracker( 2409): Skipping unknown process pid 13436
,W/ProcessCpuTracker( 2409): Skipping unknown process pid 13441
,W/ProcessCpuTracker( 2409): Skipping unknown process pid 13448
,W/ProcessCpuTracker( 2409): Skipping unknown process pid 13451
,W/ProcessCpuTracker( 2409): Skipping unknown process pid 13454
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [44:80:eb:7b:5a:05]: 7, 1d, 7d3
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: XT1072
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:75:41
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,E/Watchdog( 2409): !@Sync 43
,I/PowerManagerService( 2409): [PWL] Off : 680s ago
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: XT1072
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2409): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2409): <AppSync3 Whitelist>
,V/AlarmManager( 2409): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2409): !@Sync 44
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,E/bt-l2cap( 3999): L2CAP got conn_req while connected (state:4). Reject it
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:75:41
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/dalvikvm( 5514): GC_CONCURRENT freed 1889K, 24% free 10477K/13780K, paused 7ms+4ms, total 56ms
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,E/bt-l2cap( 3999): L2CAP got conn_comp in bad state: 4  status: 0x16
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 293, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2409): !@Sync 45
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,E/bt-l2cap( 3999): L2CAP got conn_req while connected (state:4). Reject it
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,E/bt-l2cap( 3999): L2CAP got conn_comp in bad state: 4  status: 0x16
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2409): [PWL] Off : 765s ago
,E/Watchdog( 2409): !@Sync 46
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 293, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: XT1072
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: XT1072
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/Watchdog( 2409): !@Sync 47
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2409): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3999): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4073): GC_CONCURRENT freed 2050K, 30% free 9721K/13836K, paused 4ms+3ms, total 50ms
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2409): !@Sync 48
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3999): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: A5-1
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: A5-1
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,I/PowerManagerService( 2409): [PWL] Off : 855s ago
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3999): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: A5-1
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,W/ProcessCpuTracker( 2409): Skipping unknown process pid 14044
,W/ProcessCpuTracker( 2409): Skipping unknown process pid 14049
,W/ProcessCpuTracker( 2409): Skipping unknown process pid 14054
,W/ProcessCpuTracker( 2409): Skipping unknown process pid 14058
,W/ProcessCpuTracker( 2409): Skipping unknown process pid 14060
,W/ProcessCpuTracker( 2409): Skipping unknown process pid 14063
,W/ProcessCpuTracker( 2409): Skipping unknown process pid 14066
,E/Watchdog( 2409): !@Sync 49
,V/AlarmManager( 2409): waitForAlarm result :8
,E/SPPClientService( 5514): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/TimaService( 2409): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2409): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2409): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): stay LED for fully charged
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel( 2409): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2409): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2409): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2409): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2409): !@Sync 50
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:85:54
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:85:54
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:24841
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/GKI_LINUX( 3999): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3999): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:85:54
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:16653
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/        ( 3999): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: G3s-1
,D/UserAnalysis.CarAnalyzer( 8416): Create SecureDbHelper
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/btif_config_util( 3999): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3999): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 3999): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:85:54
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3999): db_query_add_key: key KEY_LMP_VER, value 6:16653
,D/IOP_DB_BT( 3999): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3999): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2835): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2835): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6391): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/BluetoothAdapterService(1109913288)( 3999): Get Bonded Devices being called
,D/GKI_LINUX( 3999): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): stay LED for fully charged
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2409): !@Sync 51
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 290, currTemp = 292, prevStep = 4, currStep = 4
,D/dalvikvm( 2409): GC_CONCURRENT freed 3951K, 71% free 25615K/86580K, paused 23ms+21ms, total 246ms
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2409): !@Sync 52
,I/PowerManagerService( 2409): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2409): !@Sync 53
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2409): !@Sync 54
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2409): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2409): mCoverManager.getCoverState() : true
D/BatteryService( 2409): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2409): waitForAlarm result :4
,V/AlarmManager( 2409): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2409): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/EventLogService( 3160): Aggregate from 1450106000418 (log), 1450106000418 (data)
,D/dalvikvm( 3160): GC_CONCURRENT freed 1814K, 20% free 12665K/15700K, paused 5ms+9ms, total 111ms
,D/ConnectivityService( 2409): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
,D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
,E/Watchdog( 2409): !@Sync 55
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2409): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2409): !@Sync 56
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2409): !@Sync 57
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2409): !@Sync 58
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2409): [PWL] Off : 1155s ago
,E/Watchdog( 2409): !@Sync 59
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/TimaService( 2409): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2409): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2409): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2409): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2409): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2409): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2409): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2409): !@Sync 60
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2409): !@Sync 61
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2409): waitForAlarm result :4
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
V/NetworkStats( 2409): performPollLocked(flags=0x3)
,V/AlarmManager( 2409): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/NetworkStats( 2409): performPollLocked() took 47ms
D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/LightsService( 2409): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2409): getReportingMode :: sensor.mType = 5
D/Sensors ( 2409): LightSensor setDelay = 200000000
D/Sensors ( 2409): LightSensor setSensorDelay = 200000000
D/Sensors ( 2409): Light sensor flush: not enabled 0
D/Sensors ( 2409): LightSensor enable = 1
D/Sensors ( 2409): LightSensor enableSensor = 1
D/SensorManager( 2409): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/SELinux (15184): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (15184):  
,I/ProcessStatsService( 2409): Prepared write state in 39ms
,I/SELinux (15184): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (15184):  
I/SELinux (15184):  
,I/SELinux (15184): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (15184): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(15184): >>>>> Normal User
,E/dalvikvm(15184): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (15184): [DEBUG] seapp_context_lookup: seinfoCategory = default
I/ProcessStatsService( 2409): Prepared write state in 24ms
,D/TimaKeyStoreProvider(15184): in addTimaSignatureService
,D/TimaKeyStoreProvider(15184): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(15184): Added TimaKesytore provider
,D/Sensors ( 2409): LightSensor enable = 0
,D/Sensors ( 2409): LightSensor enableSensor = 0
D/dalvikvm(15184): GC_CONCURRENT freed 3011K, 31% free 9558K/13792K, paused 3ms+3ms, total 28ms
,D/dalvikvm(15184): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/SensorManager( 2409): unregisterListener ::   
D/LightsService( 2409): [SvcLED]  onSensorChanged::light value = 6
D/LightsService( 2409): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/@ WidgetProvider(15184): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(15184): onUpdate called for widgetId : 0
,D/@ WidgetProvider(15184): Widget random data : 5
,D/@ WidgetProvider(15184): onUpdate called for widgetId : 5
,D/@ WidgetProvider(15184): Widget random data : 4
,E/dalvikvm(15184): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(15184): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(15184): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(15184): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(15184): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(15184): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(15184): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(15184): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(15184): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(15184): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(15184): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(15184): VFY: replacing opcode 0x22 at 0x0038
D/dalvikvm(15184): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
,D/dalvikvm(15184): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(15184): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(15184): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,I/ProcessStatsService( 2409): Pruning old procstats: /data/system/procstats/state-2015-12-13-17-59-00.bin
,V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2854): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(15184): Thread-678(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(15184): Thread-678(ApacheHTTPLog):isShipBuild true
,I/System.out(15184): Thread-678(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 2854): GC_CONCURRENT freed 1873K, 23% free 10828K/13992K, paused 13ms+4ms, total 59ms
,I/System.out(15184): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(15184): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(15184): Max ALLOWED memory (MB): 128
V/ImageManager(15184): Max SHOULD USE memory (MB): 128
,V/ImageManager(15184): Max Image Cache memory (MB): 32
,D/skia    (15184): getTotalSize : Do not get file length
,D/@ WidgetProvider(15184): Building widget : 5
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2409): !@Sync 62
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2409): [PWL] Off : 1265s ago
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2409): !@Sync 63
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2409): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2409): <AppSync3 Whitelist>
,V/AlarmManager( 2409): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2409): GC_CONCURRENT freed 3941K, 71% free 25613K/86580K, paused 18ms+19ms, total 231ms
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2409): !@Sync 64
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2409): !@Sync 65
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
I/ActivityManager( 2409): Killing 6405:com.sec.knox.bridge/1000 (adj 15): empty for 1836s
,I/ActivityManager( 2409): Killing 4834:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1836s
,I/ActivityManager( 2409): Killing 6366:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1846s
,I/ActivityManager( 2409): Killing 6711:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1846s
,I/ActivityManager( 2409): Killing 6697:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1847s
,I/ActivityManager( 2409): Killing 6685:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1847s
,I/ActivityManager( 2409): Killing 6673:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1847s
,I/ActivityManager( 2409): Killing 6660:com.samsung.helphub/1000 (adj 15): empty for 1848s
,I/ActivityManager( 2409): Killing 6647:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1848s
,I/ActivityManager( 2409): Killing 6634:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1848s
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2409): Killing 6621:com.sec.android.service.cm/u0a82 (adj 15): empty for 1848s
,I/ActivityManager( 2409): Killing 6324:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1848s
,I/ActivityManager( 2409): Killing 5666:com.android.mms/u0a49 (adj 15): empty for 1848s
,D/CountryDetector( 2409): No listener is left
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2409): !@Sync 66
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/BatteryService( 2409): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3999): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3999): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2409): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2409): !@Sync 67
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2409): waitForAlarm result :8
,V/AlarmManager( 2409): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2409): !@Sync 68
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2409): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms)
```
