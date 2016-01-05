#### Test 549702617d40def_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0
--------- beginning of /dev/log/main
D/AndroidRuntime( 7489): 
D/AndroidRuntime( 7489): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7489): CheckJNI is OFF
D/AndroidRuntime( 7489): setted country_code = Poland
D/AndroidRuntime( 7489): setted countryiso_code = PL
D/AndroidRuntime( 7489): setted sales_code = PLS
D/AndroidRuntime( 7489): readGMSProperty: start
D/AndroidRuntime( 7489): readGMSProperty: already setted!!
D/AndroidRuntime( 7489): readGMSProperty: end
D/AndroidRuntime( 7489): addProductProperty: start
D/dalvikvm( 7489): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7489): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7489): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7489): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7489): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7489): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7489): failed to load memtrack module: -2
D/dalvikvm( 7489): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7489): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2401): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2401): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2401): mDVFSHelper.acquire()
I/SELinux ( 7518): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7518):  
D/PointerIcon( 2401): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2401): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2401): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2401): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7489): Shutting down VM
D/dalvikvm( 7489): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 7518): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7518):  
I/SELinux ( 7518):  
I/SELinux ( 7518): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7518): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7518): >>>>> Normal User
E/dalvikvm( 7518): >>>>> com.test.thalitest [ userId:0 | appId:10583 ]
E/SELinux ( 7518): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7518): in addTimaSignatureService
D/TimaKeyStoreProvider( 7518): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7518): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4176): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4176): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7518): GC_CONCURRENT freed 3001K, 32% free 9568K/13888K, paused 3ms+1ms, total 19ms
D/dalvikvm( 7518): WAIT_FOR_CONCURRENT_GC blocked 12ms
V/WebViewChromium( 7518): Binding Chromium to the background looper Looper (main, tid 1) {4229a188}
I/chromium( 7518): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7518): Initializing chromium process, renderers=0
W/chromium( 7518): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7518): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7518): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7518): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7518): Mali API Version : 401
,I/Mali    ( 7518): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 ,
,I/dalvikvm( 7518): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>,
W/dalvikvm( 7518): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7518): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7518): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7518): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7518): VFY: replacing opcode 0x6e at 0x0008,
,D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2401): tr p:7518,o:f
,W/dalvikvm( 7518): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7518): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7518): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7518): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7518): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7518): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7518): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7518): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 7518): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7518): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7518): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7518): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7518): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2401): semi p:7518,o:f
,I/SurfaceFlinger( 1921): id=21 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2401): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2401): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2401): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2401): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2401): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2401): setHoveringSpenCustomIcon IconType is same.1
I/HWUI    ( 7518): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7518): Enabling debug mode 0
,W/AwContents( 7518): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7518): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2401): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/CustomFrequencyManagerService( 2401): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2401): mDVFSHelper.release()
,D/JsMessageQueue( 7518): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7518): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42292238
,D/dalvikvm( 7518): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42292238
D/jxcore_app_log( 7518): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2029842544
,D/JX-Cordova( 7518): jxcore cordova android initializing
,D/dalvikvm( 7518): GC_CONCURRENT freed 1290K, 19% free 11351K/13956K, paused 3ms+2ms, total 26ms
D/dalvikvm( 7518): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/dalvikvm( 7518): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/CustomFrequencyManagerService( 2401): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7518): GC_CONCURRENT freed 1870K, 18% free 15037K/18236K, paused 2ms+3ms, total 51ms
,D/dalvikvm( 7518): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 7518): WAIT_FOR_CONCURRENT_GC blocked 36ms
,D/dalvikvm( 7518): GC_FOR_ALLOC freed 5420K, 30% free 16288K/23232K, paused 50ms, total 50ms
,D/AmoledAdjustTimer( 2401): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/dalvikvm( 7518): GC_CONCURRENT freed 6693K, 32% free 17734K/25796K, paused 2ms+10ms, total 67ms
,D/dalvikvm( 7518): WAIT_FOR_CONCURRENT_GC blocked 50ms
,D/dalvikvm( 7518): GC_FOR_ALLOC freed 1270K, 32% free 17568K/25796K, paused 51ms, total 51ms
,I/dalvikvm-heap( 7518): Grow heap (frag case) to 21.956MB for 3688532-byte allocation
,D/dalvikvm( 7518): GC_FOR_ALLOC freed 37K, 29% free 21133K/29400K, paused 47ms, total 47ms
,W/jxcore-log( 7518): Initializing JXcore engine
,W/jxcore-log( 7518): JXcore engine is ready
,W/jxcore-log( 7518): Starting JXcore engine
,W/jxcore-log( 7518): Platform android
W/jxcore-log( 7518): 
,W/jxcore-log( 7518): Process ARCH arm
W/jxcore-log( 7518): 
,I/jxcore-log( 7518): JXcore Cordova bridge is ready!
I/jxcore-log( 7518): 
,W/jxcore-log( 7518): JXcore engine is started
,I/chromium( 7518): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7518): Toggling radios to true
I/jxcore-log( 7518): 
,D/BluetoothAdapter( 7518): enable(): BT is already enabled..!
,I/WifiManager( 7518): packageName : com.test.thalitest
,I/WifiManager( 7518): setWifiEnabled : true
,I/WifiService( 2401): setWifiEnabled: true pid=7518, uid=10583
W/ActivityManager( 2401): Permission Denial: getCurrentUser() from pid=7518, uid=10583 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 2401): Failed getting userId using ActivityManagerNative
W/WifiService( 2401): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7518, uid=10583 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2401): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2401): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2401): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2401): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2401): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2401): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService( 2401): disconnect: pid=7518, uid=10583
,I/wpa_supplicant( 3975): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7518): Radios toggled
I/jxcore-log( 7518): 
,I/wpa_supplicant( 3975): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3975): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2401): interfaceStatusChanged wlan0, true
,D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2401): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3975): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3975): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3975): Disconnected - do not scan
,W/Settings( 2401): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2401): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2401): InactiveState{ what=143375 }
D/WifiP2pService( 2401): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/wpa_supplicant( 3975): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3975): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3975): First Scan Start
,I/WifiTrafficPoller( 2401): evaluateTrafficStatsPolling
,I/wpa_supplicant( 3975): Scan requested (ret=0) - scan timeout 30 seconds
D/ConnectivityService( 2401): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
D/WifiP2pService( 2401): InactiveState{ what=143375 }
D/WifiP2pService( 2401): P2pEnabledState{ what=143375 }
D/ConnectivityService( 2401): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2401): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2401): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
,E/ConnectivityService( 2401): net.tcp.delack.default not found in system default properties
,E/ConnectivityService( 2401): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
,D/ConnectivityService( 2401): Attempting to switch to mobile
,D/ConnectivityService( 2401): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-IconMerger( 2583): checkOverflow(336), More:false, Req:false Child:3
,I/SELinux ( 7564): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7564):  
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1
,I/WifiTrafficPoller( 2401): evaluateTrafficStatsPolling
,D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,E/WifiStateMachine( 2401): Error! unhandled message{ when=-58ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2401): Error! unhandled message{ when=-57ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,E/WifiStateMachine( 2401): Error! unhandled message{ when=-27ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,W/NetworkManagementService( 2401): route cmd failed: 
W/NetworkManagementService( 2401): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2401): '
W/NetworkManagementService( 2401): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2401): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2401): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2401): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2401): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2401): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2401): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2401): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2401): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2401): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2401): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2401): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2401): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1
I/SELinux ( 7564): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7564):  
I/SELinux ( 7564):  
,I/SELinux ( 7564): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7564): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7564): >>>>> Normal User
,E/dalvikvm( 7564): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7564): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 7564): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7564): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7564): Added TimaKesytore provider
,D/NetUtils( 2401): android_net_utils_resetConnections in env=0x77b854a8 clazz=0x61600001 iface=wlan0 mask=0x3
D/ConnectivityService( 2401): resetConnections(wlan0, 3)
,V/NativeCrypto( 2853): Read error: ssl=0x7baee1c0: I/O error during system call, Connection timed out
,V/NativeCrypto( 2853): SSL shutdown failed: ssl=0x7baee1c0: I/O error during system call, Broken pipe
,E/SPPClientService( 5586): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5586): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5586): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5586): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5586): [b] ResponseMap empty
,D/dalvikvm( 7564): GC_CONCURRENT freed 2998K, 32% free 9575K/13892K, paused 4ms+3ms, total 55ms
,D/dalvikvm( 7564): WAIT_FOR_CONCURRENT_GC blocked 44ms
,I/System.out( 7564): Inside WakeupProvider
,I/System.out( 7564): Inside onCreate() of WakeupTriggerProvide
,D/ConnectivityService( 2401): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
V/NetworkStats( 2401): updateIfacesLocked()
,V/NetworkStats( 2401): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
V/NetworkStats( 2401): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/VlingoApplication( 7564): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7564): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7564): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
V/NetworkStats( 2401): performPollLocked() took 38ms
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/DialogFlow( 7564): initQueue()
,D/NearbySettings( 4757): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 4757): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4757): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4757): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4757): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4757): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4757): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2401): Killing 5438:com.google.android.talk/u0a109 (adj 15): empty #43
,D/NearbySettings( 4757): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4757): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4757): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4757): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4757): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4757): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4757): MountReceiver.mPrefHandler - 7002
,I/SELinux ( 7592): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7592):  
,I/SELinux ( 7592): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7592):  
I/SELinux ( 7592):  
,I/SELinux ( 7592): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7592): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7592): >>>>> Normal User
,E/dalvikvm( 7592): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
,E/SELinux ( 7592): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7592): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7592): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7592): Added TimaKesytore provider
,D/dalvikvm( 7592): GC_CONCURRENT freed 2984K, 32% free 9579K/13884K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7592): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/dalvikvm( 7592): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 7592): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 7592): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 7592): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7592): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7592): VFY: replacing opcode 0x22 at 0x0000
,E/dalvikvm( 7592): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
W/dalvikvm( 7592): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 7592): VFY: replacing opcode 0x22 at 0x0037
,I/ApplicationPolicy( 2401): updateDataUsageMap
,D/Tethering( 2401): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2401): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2401): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2401): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2583): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2583): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2583): updateDataNetType()
D/STATUSBAR-NetworkController( 2583): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4789): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2401): agps_ril_update_network_state: Waiting for IPC connection...
,W/dalvikvm( 7592): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7592): Link of class 'Ldqp;' failed
,W/dalvikvm( 7592): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7592): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7592): Link of class 'Ldqp;' failed
I/dalvikvm( 7592): Could not find method dqp.q, referenced from method g.a
,W/dalvikvm( 7592): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 7592): VFY: replacing opcode 0x6e at 0x0000
,E/dalvikvm( 7592): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7592): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7592): VFY: replacing opcode 0x22 at 0x0000
W/dalvikvm( 7592): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7592): Link of class 'Ldqp;' failed
W/dalvikvm( 7592): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7592): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7592): Link of class 'Ldqp;' failed
I/dalvikvm( 7592): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 7592): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
D/dalvikvm( 7592): VFY: replacing opcode 0x6e at 0x0008
E/dalvikvm( 7592): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 7592): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
D/dalvikvm( 7592): VFY: replacing opcode 0x1c at 0x0026
W/dalvikvm( 7592): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7592): Link of class 'Ldqp;' failed
W/dalvikvm( 7592): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7592): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 7592): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7592): Link of class 'Ldqp;' failed
I/dalvikvm( 7592): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 7592): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
D/dalvikvm( 7592): VFY: replacing opcode 0x6e at 0x0003
W/dalvikvm( 7592): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7592): Link of class 'Lax;' failed
E/dalvikvm( 7592): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 7592): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
D/dalvikvm( 7592): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 7592): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7592): Link of class 'Laz;' failed
E/dalvikvm( 7592): Could not find class 'az', referenced from method g.a
W/dalvikvm( 7592): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
D/dalvikvm( 7592): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 7592): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 7592): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
D/dalvikvm( 7592): VFY: replacing opcode 0x6e at 0x0008
I/dalvikvm( 7592): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
W/dalvikvm( 7592): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 7592): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 7592): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 7592): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 7592): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 7592): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 7592): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
D/dalvikvm( 7592): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 7592): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 7592): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 7592): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7592): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
W/dalvikvm( 7592): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 7592): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7592): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 7592): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
D/dalvikvm( 7592): VFY: replacing opcode 0x72 at 0x0000
W/dalvikvm( 7592): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 7592): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 7592): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 7592): VFY: replacing opcode 0x23 at 0x0005
,I/dalvikvm( 7592): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
,W/dalvikvm( 7592): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7592): VFY: replacing opcode 0x6e at 0x0009
,W/dalvikvm( 7592): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
,W/dalvikvm( 7592): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 7592): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 7592): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
D/dalvikvm( 7592): VFY: replacing opcode 0x1c at 0x0002
E/dalvikvm( 7592): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 7592): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 7592): VFY: replacing opcode 0x1f at 0x000c
,D/dalvikvm( 7592): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7592): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7592): VFY: replacing opcode 0x62 at 0x0006
,D/dalvikvm( 7592): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7592): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
,D/dalvikvm( 7592): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7592): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
,D/dalvikvm( 7592): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
W/dalvikvm( 7592): Unable to resolve superclass of Lax; (841)
,W/dalvikvm( 7592): Link of class 'Lax;' failed
D/dalvikvm( 7592): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 7592): Unable to resolve superclass of Laz; (841)
,W/dalvikvm( 7592): Link of class 'Laz;' failed
,D/dalvikvm( 7592): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 7592): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
,D/dalvikvm( 7592): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,D/dalvikvm( 7592): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x4229f7f0
,D/dalvikvm( 7592): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x4229f7f0
,I/wpa_supplicant( 3975): nl80211: Received scan results (8 BSSes)
,I/wpa_supplicant( 3975): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3975): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3975): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2401): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3975): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3975): Associated with C0.AA.48
D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2401): interfaceStatusChanged wlan0, true
D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
D/Tethering( 2401): interfaceStatusChanged wlan0, true
I/dalvikvm( 7592): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
W/dalvikvm( 7592): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
D/dalvikvm( 7592): VFY: replacing opcode 0x6e at 0x0076
D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2401): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3975): freq(2412) increment count 2
,I/wpa_supplicant( 3975): meet head of list.
,I/wpa_supplicant( 3975): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
I/Babel_SMS( 7592): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7592): MmsConfig.loadMmsSettings
I/Babel_SMS( 7592): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/Babel_SMS( 7592): MmsConfig.loadFromDatabase
,I/wpa_supplicant( 3975): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3975): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3975): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3975): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2401): interfaceStatusChanged wlan0, true
,D/WifiNative( 2401): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,E/Babel_SMS( 7592): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7592): MmsConfig.loadFromResources
,E/Babel_SMS( 7592): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7592): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,W/dalvikvm( 7592): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7592): Link of class 'Lfzc;' failed
E/dalvikvm( 7592): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 7592): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
,D/dalvikvm( 7592): VFY: replacing opcode 0x22 at 0x0033
W/dalvikvm( 7592): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7592): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7592): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
,W/dalvikvm( 7592): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
I/dalvikvm( 7592): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 7592): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
,D/dalvikvm( 7592): VFY: replacing opcode 0x74 at 0x006d
I/dalvikvm( 7592): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 7592): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
,D/dalvikvm( 7592): VFY: replacing opcode 0x6e at 0x0033
I/dalvikvm( 7592): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 7592): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
,D/dalvikvm( 7592): VFY: replacing opcode 0x6e at 0x0030
,W/dalvikvm( 7592): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7592): Link of class 'Lfzc;' failed,
,D/dalvikvm( 7592): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>,
,E/SensorService( 2401): Permission Denial : SEC Private Sensor 
,E/SensorService( 2401): Permission Denial : SEC Private Sensor ,
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras),
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getCameraInfo),
D/dalvikvm( 7592): GC_CONCURRENT freed 1774K, 23% free 10879K/13968K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 7592): WAIT_FOR_CONCURRENT_GC blocked 10ms,
D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getCameraInfo),
,D/WifiP2pService( 2401): InactiveState{ what=143375 }
,D/WifiP2pService( 2401): P2pEnabledState{ what=143375 }
,W/Settings( 7592): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,I/Babel_Crash( 7592): startup - clean,
,I/Babel   ( 7592): deleted: false for 0
,I/dalvikvm( 7592): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
W/dalvikvm( 7592): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7592): VFY: replacing opcode 0x6e at 0x000d
,W/dalvikvm( 7592): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
I/dalvikvm( 7592): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 7592): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
,D/dalvikvm( 7592): VFY: replacing opcode 0x6e at 0x004e
W/dalvikvm( 7592): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7592): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7592): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
,W/dalvikvm( 7592): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
,D/dalvikvm( 7592): VFY: replacing opcode 0x22 at 0x0071
,W/dalvikvm( 7592): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7592): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7592): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7592): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7592): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 7592): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
,D/dalvikvm( 7592): VFY: replacing opcode 0x1f at 0x0021
,W/dalvikvm( 7592): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 7592): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
,I/PCWCLIENTTRACE_PushUtil( 6703): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6703): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6703): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6703): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6703): noConnectivity : true
,I/dalvikvm( 7592): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/dalvikvm( 7592): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
,D/dalvikvm( 7592): VFY: replacing opcode 0x6e at 0x0074
,I/vclib   ( 7592): onServiceConnected
,W/Babel   ( 7592): Attempted to change video mute state without an active call.
I/ActivityManager( 2401): Killing 6612:com.sec.android.diagmonagent/1000 (adj 15): empty #43
,I/SELinux ( 7616): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7616):  
,I/SELinux ( 7616): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7616):  
I/SELinux ( 7616):  
,I/SELinux ( 7616): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7616): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7616): >>>>> Normal User
,E/dalvikvm( 7616): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7616): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7616): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7616): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7616): Added TimaKesytore provider
,D/dalvikvm( 7592): GC_CONCURRENT freed 931K, 16% free 11890K/14144K, paused 3ms+6ms, total 37ms
I/dhcpcd  ( 7629): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7629): bssid match
,D/dalvikvm( 7616): GC_CONCURRENT freed 3006K, 32% free 9570K/13892K, paused 15ms+1ms, total 33ms
,D/dalvikvm( 7616): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 7592): GC_FOR_ALLOC freed 565K, 18% free 12399K/15040K, paused 29ms, total 29ms
,I/ActivityManager( 2401): Killing 5634:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
D/dalvikvm( 7592): GC_FOR_ALLOC freed 1759K, 23% free 12770K/16568K, paused 27ms, total 28ms
,I/SELinux ( 7636): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7636):  
,I/SELinux ( 7636): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7636):  
I/SELinux ( 7636):  
,I/SELinux ( 7636): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7636): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7636): >>>>> Normal User
,E/dalvikvm( 7636): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7636): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7636): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7636): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7636): Added TimaKesytore provider
,D/dalvikvm( 7636): GC_CONCURRENT freed 2992K, 32% free 9578K/13888K, paused 3ms+3ms, total 30ms
,D/dalvikvm( 7636): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/KLMS-2.3.201 : ( 7636): KLMSValidator() : checkQATesting()
,D/libgps  ( 2401): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2401): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2401): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2401): agps_ril_update_network_availability: Waiting for IPC connection...
,I/KLMS-2.3.201 : ( 7636): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1451957088394
,I/KLMS-2.3.201 : ( 7636): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2401): Killing 6421:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/SELinux ( 7648): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7648):  
,I/SELinux ( 7648): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7648):  
I/SELinux ( 7648):  
,I/SELinux ( 7648): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7648): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7648): >>>>> Normal User
,E/dalvikvm( 7648): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7648): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7648): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7648): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7648): Added TimaKesytore provider
,D/dalvikvm( 7648): GC_CONCURRENT freed 2996K, 32% free 9568K/13884K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 7648): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/SO_AGENT( 7648): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7648): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5832): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5832): [BDLM] already registered in spp
I/SA      ( 5832): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5832): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5832): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5832): [OR] == isSIMCardReady false ==
I/SA      ( 5832): [SCU] == networkStateCheck == false
,I/SA      ( 5832): [OR] onReceive END
I/ActivityManager( 2401): Killing 6000:com.android.calendar/u0a144 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5854): Other Intent
,I/SELinux ( 7660): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7660):  
,I/SELinux ( 7660): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7660):  
I/SELinux ( 7660):  
,I/SELinux ( 7660): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7660): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7660): >>>>> Normal User
,E/dalvikvm( 7660): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7660): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7660): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7660): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7660): Added TimaKesytore provider
,D/dalvikvm( 7660): GC_CONCURRENT freed 2993K, 32% free 9580K/13888K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 7660): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/com.samsung.app( 7660): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7660): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7660): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7660): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7660): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7660): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5382): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7660): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5382): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7660): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5382): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7660): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7660): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2401): Killing 6403:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/Headlines( 5880): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5880): getCountryCode(): countryCode = PL
,D/Headlines( 5880): Breath.onCreate
,D/Headlines( 5880): Breath timer started. interval : 30000
,I/SELinux ( 7672): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7672):  
,D/Headlines( 5880): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5880): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 5880): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5880): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5880): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5880): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5880): requestUpdateNewsWelcomeCard !!! no welcome card
,D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 13% free 9505K/10868K, paused 6ms+3ms, total 33ms,
I/SELinux ( 7672): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7672):  
I/SELinux ( 7672):  
,I/SELinux ( 7672): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7672): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7672): >>>>> Normal User
,E/dalvikvm( 7672): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ],
,E/SELinux ( 7672): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/TimaKeyStoreProvider( 7672): in addTimaSignatureService,
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9505K/10868K, paused 2ms+3ms, total 29ms
,D/TimaKeyStoreProvider( 7672): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7672): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9505K/10868K, paused 3ms+3ms, total 25ms
,D/dalvikvm( 7672): GC_CONCURRENT freed 2997K, 32% free 9574K/13888K, paused 3ms+2ms, total 22ms
,D/dalvikvm( 7672): WAIT_FOR_CONCURRENT_GC blocked 12ms
,V/WebViewChromium( 7672): Binding Chromium to the background looper Looper (main, tid 1) {422a0c58}
,I/chromium( 7672): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7672): Initializing chromium process, renderers=0
,W/chromium( 7672): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7672): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7672): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7672): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7672): Mali API Version : 401
,I/Mali    ( 7672): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,W/GAV2    ( 7672): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7672): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/libgps  ( 2401): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2401): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2401): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/NSApplication( 7672): Starting up...
,I/iu.Environment( 5947): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*,
,I/iu.UploadsManager( 5947): num queued entries: 0
,I/iu.UploadsManager( 5947): num updated entries: 0
,I/iu.SyncManager( 5947): NEXT; no task
,D/QuickConnect[1.1][2] ( 5184): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5184): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5184): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422a9150
,I/SELinux ( 7714): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7714):  
,I/SELinux ( 7714): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7714):  
I/SELinux ( 7714):  
,I/SELinux ( 7714): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7714): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7714): >>>>> Normal User
,E/dalvikvm( 7714): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7714): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,D/TimaKeyStoreProvider( 7714): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7714): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7714): Added TimaKesytore provider
,D/dalvikvm( 7714): GC_CONCURRENT freed 2983K, 31% free 9584K/13888K, paused 3ms+1ms, total 31ms,
,D/dalvikvm( 7714): WAIT_FOR_CONCURRENT_GC blocked 24ms,
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId,
,D/WifiP2pService( 2401): InactiveState{ what=143375 },
,D/WifiP2pService( 2401): P2pEnabledState{ what=143375 },
,D/WifiStateMachine( 2401): VerifyingLinkState enter,
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
,D/WifiStateMachine( 2401): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2401): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2401): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2401): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2401): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2401): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2401): evaluateTrafficStatsPolling
D/ConnectivityService( 2401): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2401): net.tcp.usercfg.wifi not found in system properties. Using defaults
,E/ConnectivityService( 2401): net.tcp.delack.wifi not found in system properties. Using defaults
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2401): handleConnectivityChange: setting default proxy info 
,I/PowerManagerService( 2401): [PWL] Off : 140s ago
,I/SELinux ( 7750): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7750):  
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,I/SELinux ( 7750): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7750):  
I/SELinux ( 7750):  
,I/SELinux ( 7750): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7750): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7750): >>>>> Normal User
,E/dalvikvm( 7750): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7750): [DEBUG] seapp_context_lookup: seinfoCategory = release
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1,
W/ActivityManager( 2401): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/ActivityManager( 2401): Killing 6193:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7750): in addTimaSignatureService,
D/NtpTrustedTime( 2401): currentTimeMillis() cache hit,
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
V/NetworkStats( 2401): updateIfacesLocked()
V/NetworkStats( 2401): performPollLocked(flags=0x1)
,V/NetworkStats( 2401): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/TimaKeyStoreProvider( 7750): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7750): Added TimaKesytore provider
,I/ActivityManager( 2401): Killing 6230:com.google.android.music:main/u0a125 (adj 15): empty #43
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
V/NetworkStats( 2401): performPollLocked() took 18ms
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,I/SELinux ( 7777): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7777):  
,I/SELinux ( 7777): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7777):  
I/SELinux ( 7777):  
,I/SELinux ( 7777): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7777): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7777): >>>>> Normal User
,E/dalvikvm( 7777): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7777): [DEBUG] seapp_context_lookup: seinfoCategory = shared
D/dalvikvm( 7750): GC_CONCURRENT freed 2987K, 32% free 9575K/13884K, paused 3ms+2ms, total 24ms
,D/dalvikvm( 7750): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/BadgeProvider( 7750): onCreate
,D/BadgeProvider( 7750): DatabaseHelper
,D/TimaKeyStoreProvider( 7777): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7777): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7777): Added TimaKesytore provider
D/SSRMv2:SIOP( 2401): SIOP:: AP = 330, Delta = 20
,D/BadgeProvider( 7750): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 2777): reloadBadges entered.
,D/BadgeProvider( 7750): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7750): sendNotify, [notify] : null
D/BadgeProvider( 7750): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7750): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7750): update, [UpdateCount] : 1
,D/dalvikvm( 7777): GC_CONCURRENT freed 2998K, 32% free 9568K/13888K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7777): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2401): stay LED for fully charged
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true,
D/WaitQueueForNetworkActivate( 6894): notifyNetworkActivated,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED,
V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/HeadsetStateMachine( 4013): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 6894): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 ,
W/ActivityManager( 2401): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/System.out( 7592): Thread-668(HTTPLog):isShipBuild true,
,I/System.out( 7592): Thread-668(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false,
,I/Babel   ( 7592): connection state changed from UNKNOWN to CONNECTED,
,D/Tethering( 2401): Tethering got CONNECTIVITY_ACTION,
,D/Tethering( 2401): MasterInitialState.processMessage what=3,
,D/CaptivePortalTracker( 2401): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2583): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2583): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2583): updateDataNetType()
D/STATUSBAR-NetworkController( 2583): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4789): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/libgps  ( 2401): agps_ril_update_network_state: Waiting for IPC connection...
,D/hcjo    ( 6894): AutoUpdateManager:IDLE:execute
,I/dalvikvm( 6894): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
,W/dalvikvm( 6894): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 6894): VFY: replacing opcode 0x6e at 0x0024
,D/InitializeManagerStateMachine( 6894): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6894): exit::IDLE
,D/InitializeManagerStateMachine( 6894): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6894): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6894): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6894): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6894): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 6894): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6894): entry::SUCCESS
,D/hcjo    ( 6894): AutoUpdateManager:INITCHECK:onInitializeSuccess
E/SPPClientService( 5586): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5586): [SystemStateMoniter] Current Time : 347710
,E/SPPClientService( 5586): [SystemStateMoniter] No Connect : true
D/hcjo    ( 6894): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6894): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6894): exit::SUCCESS
,D/InitializeManagerStateMachine( 6894): entry::IDLE
,E/SPPClientService( 5586): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 4757): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4757): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4757): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 4757): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4757): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4757): MountReceiver.onReceive - Keep current state
I/ActivityManager( 2401): Killing 6294:com.android.defcontainer/u0a6 (adj 15): empty #43
,E/SPPClientService( 5586): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5586): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 4757): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4757): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5586): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/NearbySettings( 4757): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4757): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4757): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 4757): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4757): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4757): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5586): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/SurfaceFlinger( 1921): id=22 createSurf (1x1),1 flag=4, Uoast
,E/SPPClientService( 5586): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5586): [a] [ConnectionManager] Connection is already disconnected.
D/PowerManagerService( 2401): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2401
,D/NearbySettings( 4757): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4757): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5586): [g] getNetMCC return empty string
,I/PCWCLIENTTRACE_PushUtil( 6703): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6703): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6703): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6703): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SELinux ( 7801): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7801):  
,I/SELinux ( 7801): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7801):  
I/SELinux ( 7801):  
,I/SELinux ( 7801): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7801): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7801): >>>>> Normal User
,E/dalvikvm( 7801): >>>>> com.sec.android.diagmonagent [ userId:0 | appId:1000 ]
,E/SELinux ( 7801): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7801): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7801): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7801): Added TimaKesytore provider
,D/dalvikvm( 7801): GC_CONCURRENT freed 3007K, 32% free 9563K/13888K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7801): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/DBG_DIAGMONDM( 7801): [1.140541.0531][Line:472][xdmGetCheckWifiOnlyModel] isWifiOnly : false,
,I/DBG_DIAGMONDM( 7801): [1.140541.0531][Line:48][onCreate] myUserId : 0,
,I/DBG_DIAGMONDM( 7801): [1.140541.0531][Line:376][xdbDMffs_Init] ,
,I/DBG_DIAGMONDM( 7801): [1.140541.0531][Line:70][onCreate] nStatus : 0,
,E/Watchdog( 2401): !@Sync 11,
,D/PackageManager( 2401): [MSG] WRITE_PACKAGE_RESTRICTIONS,
,D/dalvikvm( 2401): GC_EXPLICIT freed 2934K, 58% free 25316K/59192K, paused 10ms+17ms, total 197ms,
,I/KLMS-2.3.201 : ( 7636): KLMSSystemProperties(): getBoolean(): ro.product_ship = true,
,D/libgps  ( 2401): agps_ril_update_network_state: Waiting for IPC connection - timeout,
,E/libgps  ( 2401): LIBGPS: Cannot communicate (write) with a GPSD,
E/libgps  ( 2401): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2401): agps_ril_update_network_availability: Waiting for IPC connection...,
,I/KLMS-2.3.201 : ( 7636): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1451957091687,
,I/KLMS-2.3.201 : ( 7636): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false,
,D/SO_AGENT( 7648): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE,
I/LocationTagReadyService( 3473): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert,
D/GalaxyFinderApplication( 3473): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3473): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3473): [Slink platform] The state of Slink geocode service is true,
,I/SO_AGENT( 7648): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...,
,I/GallerySearchProvider( 3602): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query,
,D/dalvikvm( 5586): GC_CONCURRENT freed 1954K, 25% free 10512K/13872K, paused 6ms+4ms, total 79ms,
,D/dalvikvm( 5586): WAIT_FOR_CONCURRENT_GC blocked 37ms,
,I/SELinux ( 7821): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7821):  
,I/SA      ( 5832): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ],
I/SA      ( 5832): [BDLM] already registered in spp,
I/SA      ( 5832): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5832): [OR] == ACTION_CONNECTIVITY_CHANGE ==,
I/SA      ( 5832): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 5832): [OR] == isSIMCardReady false ==
,I/SA      ( 5832): [SCU] == networkStateCheck == true
,I/SA      ( 5832): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5832): isChinaCountryCode : false
,I/SA      ( 5832): [OR] == networkStateCheck true ==
I/SELinux ( 7821): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7821):  
I/SELinux ( 7821):  
I/SELinux ( 7821): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7821): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7821): >>>>> Normal User
E/dalvikvm( 7821): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7821): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 5832): [OR] GetMyCountryZoneTask
,I/SA      ( 5832): [OR] onReceive END
,I/SA      ( 5832): [SRS] prepareGetMyCountryZone
,D/TimaKeyStoreProvider( 7821): in addTimaSignatureService
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): Phone number locator feature is dsiabled
,D/TimaKeyStoreProvider( 7821): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7821): Added TimaKesytore provider
,I/SA      ( 5832): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 5832): [SSP] query invoked
,I/SCloudBackupReceiver( 5854): Other Intent
,D/com.samsung.app( 7660): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7660): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/SA      ( 5832): [TPMU] GetMccFromDB : null
I/SA      ( 5832): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5832): [TPM] isNoProxy(default) : true
,I/SA      ( 5832): [RC New] Execute method=[GET] start
,I/System.out( 7616): Thread-660(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
D/Headlines( 5880): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5880): getCountryCode(): countryCode = PL
,D/Headlines( 5880): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5880): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5880): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5880): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5880): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5880): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5880): requestUpdateNewsWelcomeCard !!! no welcome card
,D/dalvikvm( 7821): GC_CONCURRENT freed 3011K, 32% free 9562K/13892K, paused 2ms+2ms, total 28ms
,D/dalvikvm( 7821): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/System.out( 7616): Thread-660(ApacheHTTPLog):isShipBuild true
,I/System.out( 7616): Thread-660(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/iu.Environment( 5947): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/QuickConnect[1.1][2] ( 5184): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5184): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5184): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422a9150
,I/iu.UploadsManager( 5947): num queued entries: 0
,I/iu.UploadsManager( 5947): num updated entries: 0
,V/KVNProvider( 7821): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,I/iu.SyncManager( 5947): NEXT; no task
,V/KVNProvider( 7821): getFindoCursor query string : 
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId
,D/dalvikvm( 2725): GC_EXPLICIT freed 355K, 29% free 9969K/13876K, paused 3ms+5ms, total 39ms
,V/KVNProvider( 7821): getTagSearchCursor() tagSearchCursor count : 0
,D/hcjo    ( 6894): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 6894): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6894): exit::IDLE
,D/InitializeManagerStateMachine( 6894): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 6894): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6894): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6894): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6894): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6894): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 6894): entry::SUCCESS
,D/hcjo    ( 6894): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 6894): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6894): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6894): exit::SUCCESS
,D/InitializeManagerStateMachine( 6894): entry::IDLE
,E/SPPClientService( 5586): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5586): [SystemStateMoniter] Current Time : 349341
,E/SPPClientService( 5586): [SystemStateMoniter] No Connect : false
,I/System.out( 7616): AsyncTask #1 calls detatch()
,W/System.err( 7616): com.sec.android.fota.osp.http.RestClientException,
W/System.err( 7616): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7616): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
,W/System.err( 7616): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7616): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 7616): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7616): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7616): ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7616): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7616): ,	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7616): Caused by: java.lang.NullPointerException
,W/System.err( 7616): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7616): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7616): ,	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7616): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7616): ,	... 8 more
,I/ActivityManager( 2401): Killing 6529:com.google.android.partnersetup/u0a14 (adj 15): empty #43,
,D/libgps  ( 2401): agps_ril_update_network_availability: Waiting for IPC connection - timeout,
E/libgps  ( 2401): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2401): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability,
,I/SA      ( 5832): [RC New] [v2liruge] api execute + 695,
I/SA      ( 5832): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5832): AsyncTask #2 calls detatch(),
,I/SA      ( 5832): [TPMU] getNetworkMcc : ,
,I/SA      ( 5832): [SCU] saveMccToPreferece Start,
I/SA      ( 5832): [SCU] RegionMCC : 260
,I/SA      ( 5832): [SSP] query invoked,
I/SA      ( 5832): [TPMU] GetMccFromDB : null
I/SA      ( 5832): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5832): [SCU] saveMccToPreferece End
I/SA      ( 5832): [RC New] executeRequest [v2liruge] end. 716
,I/SA      ( 5832): [RC New] Execute end
I/SA      ( 5832): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5832): [OR] GetMyCountryZoneTask Success,
,E/SPPClientService( 5586): [b] __InitReply__,
,E/WifiStateMachine( 2401): CAPTIVE_PORTAL_EVENT_AUTHENTICATED,
,D/AmoledAdjustTimer( 2401): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
I/ActivityManager( 2401): Killing 6675:com.samsung.groupcast/u0a15 (adj 15): empty #43
I/SurfaceFlinger( 1921): id=22 Removed Uoast (10/11)
I/SurfaceFlinger( 1921): id=22 Removed Uoast (-2/11)
D/PowerManagerService( 2401): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2401) eventTime = 351343
D/PowerManagerService( 2401): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2401 (0x0)
D/PowerManagerService( 2401): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2401, ws=WorkSource{1000}) (elapsedTime=3465)
I/GAV2    ( 7672): Thread[GAThread,5,main]: No campaign data found.
,W/WifiP2pStateTracker( 2401): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED,
D/ConnectivityService( 2401): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2401):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2401): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2401): updateSourceRoutes : no source routing conditions
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6703): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil( 6703): [hasSamungAccount] - No Samsung Account,
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6703): failed to loading secure library,
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6703): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6703): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6703): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6703): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6703): getPushTypeList : [SPP, GCM],
,E/PCWCLIENTTRACE_PCWHandler( 6703): [ensureRegistration] - No Samsung account,
,V/AlarmManager( 2401): waitForAlarm result :4,
,V/AlarmManager( 2401): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 7845): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7845):  
,I/SELinux ( 7845): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7845):  
I/SELinux ( 7845):  
,I/SELinux ( 7845): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7845): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7845): >>>>> Normal User,
,E/dalvikvm( 7845): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 7845): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 7845): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7845): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7845): Added TimaKesytore provider,
,D/dalvikvm( 7845): GC_CONCURRENT freed 3009K, 32% free 9561K/13888K, paused 2ms+1ms, total 18ms,
,D/dalvikvm( 7845): WAIT_FOR_CONCURRENT_GC blocked 16ms,
,D/Headlines( 5880): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5880): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5880): Breath 6462 latestRequest time : 1451957092041 current time : 1451957098503
,I/ActivityManager( 2401): Killing 6688:com.android.musicfx/u0a24 (adj 15): empty #43
,I/jxcore-log( 7518): Test app app.js loaded
I/jxcore-log( 7518): 
,I/chromium( 7518): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/AlarmManager( 2401): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 340, Delta = 10
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2401): stay LED for fully charged
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/CaptivePortalTracker( 2401): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 2401): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2401): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 2401): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker( 2401): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2401): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2401): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2401): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 6894): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6894): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6894): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6894): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6894): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 6894): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6894): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 6894): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 6894): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6894): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 6894): AutoUpdateTriggerManager:IDLE:notifyNextTime,
,D/PreloadUpdateManagerStateMachine( 6894): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 6894): exit::CHECK_TIMEOUT_FOR_UPDATE,
,D/PreloadUpdateManagerStateMachine( 6894): entry::IDLE,
,D/AmoledAdjustTimer( 2401): prevTemp = 287, currTemp = 289, prevStep = 4, currStep = 4,
,I/ActivityManager( 2401): Waited long enough for: ServiceRecord{44351580 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,I/ActivityManager( 2401): Waited long enough for: ServiceRecord{44329d80 u0 com.sec.spp.push/.PushClientService},
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 320, Delta = -20,
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2401): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2401): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4,
,V/AlarmManager( 2401): waitForAlarm result :8,
,D/Headlines( 5880): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5880): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5880): Breath 26941 latestRequest time : 1451957092041 current time : 1451957118982,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2401): stay LED for fully charged
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4013): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2401): !@Sync 12,
,D/AmoledAdjustTimer( 2401): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4,
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2401): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = -10,
,D/AmoledAdjustTimer( 2401): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0,
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2401): stay LED for fully charged,
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4013): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2401): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4,
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2401): waitForAlarm result :8,
,D/Headlines( 5880): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5880): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5880): Breath 56939 latestRequest time : 1451957092041 current time : 1451957148980,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0,
,E/Watchdog( 2401): !@Sync 13,
,D/AmoledAdjustTimer( 2401): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4,
,V/AlarmManager( 2401): waitForAlarm result :8,
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2401): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4,
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0,
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2401): stay LED for fully charged
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2401): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2401): [PWL] Off : 225s ago,
,V/AlarmManager( 2401): waitForAlarm result :8,
,D/Headlines( 5880): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5880): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5880): Breath 86939 latestRequest time : 1451957092041 current time : 1451957178981,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0,
,E/Watchdog( 2401): !@Sync 14,
,D/AmoledAdjustTimer( 2401): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4,
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2401): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0,
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2401): mCoverManager.getCoverState() : true,
,D/BatteryService( 2401): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4013): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2401): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4,
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2401): waitForAlarm result :8,
,D/Headlines( 5880): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5880): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5880): Breath 116944 latestRequest time : 1451957092041 current time : 1451957208986,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0,
,E/Watchdog( 2401): !@Sync 15
,D/AmoledAdjustTimer( 2401): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4,
,V/AlarmManager( 2401): waitForAlarm result :8,
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0,
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true,
,D/BatteryService( 2401): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4013): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2401): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2401): [PWL] Off : 275s ago,
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2401): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,D/Headlines( 5880): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5880): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5880): Breath 146935 latestRequest time : 1451957092041 current time : 1451957238977
,D/Headlines( 5880): stop 
,D/Headlines( 5880): Breath.onDestroy : 
I/ActivityManager( 2401): Killing 6716:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2401): !@Sync 16
,D/AmoledAdjustTimer( 2401): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2401): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,E/Watchdog( 2401): !@Sync 17
V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2401): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2401): [PWL] Off : 330s ago
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2401): !@Sync 18
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2401): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2401): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2401): !@Sync 19
,D/AmoledAdjustTimer( 2401): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,I/PowerManagerService( 2401): [PWL] Off : 390s ago
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2401): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2401): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/TimaService( 2401): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2401): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2401): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2401): !@Sync 20
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2401): stay LED for fully charged
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
I/TLC_TIMA_PKM_measure_kernel( 2401): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2401): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/TimaService( 2401): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 2401): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2401): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2401): stay LED for fully charged
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2401): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = -10
,E/Watchdog( 2401): !@Sync 21
,D/AmoledAdjustTimer( 2401): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4088): GC_CONCURRENT freed 2889K, 31% free 9728K/13932K, paused 17ms+3ms, total 73ms
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2401): stay LED for fully charged
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2401): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/dalvikvm( 2401): GC_CONCURRENT freed 3945K, 58% free 25246K/59192K, paused 23ms+19ms, total 259ms
,I/PowerManagerService( 2401): [PWL] Off : 455s ago
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,I/GAV2    ( 5677): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5677): Thread[disconnect check,5,main]: Disconnected from service
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2401): !@Sync 22
,D/AmoledAdjustTimer( 2401): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2401): !@Sync 23
,D/AmoledAdjustTimer( 2401): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2401): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2401): <AppSync3 Whitelist>
,V/AlarmManager( 2401): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2401): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2401): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService( 2401): [PWL] Off : 525s ago
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2401): !@Sync 24
,D/AmoledAdjustTimer( 2401): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2401): !@Sync 25
,D/AmoledAdjustTimer( 2401): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService( 2401): stay LED for fully charged
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2401): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2401): !@Sync 26
,D/AmoledAdjustTimer( 2401): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService( 2401): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,D/LightsService( 2401): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2401): getReportingMode :: sensor.mType = 5
D/Sensors ( 2401): LightSensor setDelay = 200000000
D/Sensors ( 2401): LightSensor setSensorDelay = 200000000
D/Sensors ( 2401): Light sensor flush: not enabled 0
D/Sensors ( 2401): LightSensor enable = 1
D/Sensors ( 2401): LightSensor enableSensor = 1
D/SensorManager( 2401): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,E/SPPClientService( 5586): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/Sensors ( 2401): LightSensor enable = 0
,D/LightsService( 2401): [SvcLED]  onSensorChanged::light value = 0
D/Sensors ( 2401): LightSensor enableSensor = 0
,D/SensorManager( 2401): unregisterListener ::   
D/LightsService( 2401): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2401): !@Sync 27
,D/AmoledAdjustTimer( 2401): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2401): !@Sync 28
,D/AmoledAdjustTimer( 2401): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService( 2401): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2401): !@Sync 29
,D/AmoledAdjustTimer( 2401): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2401): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2401): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/TimaService( 2401): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2401): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2401): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2401): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2401): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2401): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2401): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2401): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2401): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2401): !@Sync 31
,D/AmoledAdjustTimer( 2401): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService( 2401): [PWL] Off : 765s ago
,V/AlarmManager( 2401): waitForAlarm result :4
,V/AlarmManager( 2401): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/Watchdog( 2401): !@Sync 32
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 33
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/BatteryService( 2401): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4013): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2401): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 34
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService( 2401): [PWL] Off : 855s ago
,E/Watchdog( 2401): !@Sync 35
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 36
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/dalvikvm( 2401): GC_CONCURRENT freed 3853K, 58% free 25233K/59192K, paused 22ms+18ms, total 272ms
,D/AmoledAdjustTimer( 2401): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :4
,V/AlarmManager( 2401): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5586): [b] __PingReply__
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 37
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService( 2401): [PWL] Off : 950s ago
,E/Watchdog( 2401): !@Sync 38
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/BatteryService( 2401): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 39
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2401): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2401): stay LED for fully charged
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/TimaService( 2401): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2401): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2401): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2401): !@Sync 40
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel( 2401): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2401): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2401): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2401): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2401): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 41
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2401): [PWL] Off : 1050s ago
,I/PowerManagerService( 2401): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService( 2401): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2401): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=2401, ws=WorkSource{1000}) (elapsedTime=82)
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 42
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 43
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2401): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2401): <AppSync3 Whitelist>
,V/AlarmManager( 2401): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2401): stay LED for fully charged
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4013): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2401): !@Sync 44
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2401): stay LED for fully charged
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService( 2401): [PWL] Off : 1155s ago
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2401): stay LED for fully charged
D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2401): !@Sync 45
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4088): GC_CONCURRENT freed 2048K, 31% free 9725K/13932K, paused 14ms+4ms, total 54ms
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2401): stay LED for fully charged
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2401): !@Sync 46
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2401): stay LED for fully charged
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,I/SensorManagerA( 2401): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2401): LightSensor setDelay = 200000000
,D/LightsService( 2401): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2401): LightSensor setSensorDelay = 200000000
D/Sensors ( 2401): Light sensor flush: not enabled 0
D/Sensors ( 2401): LightSensor enable = 1
D/Sensors ( 2401): LightSensor enableSensor = 1
D/SensorManager( 2401): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2401): LightSensor enable = 0
,D/Sensors ( 2401): LightSensor enableSensor = 0
,D/SensorManager( 2401): unregisterListener ::   
D/LightsService( 2401): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2401): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 47
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 48
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,I/PowerManagerService( 2401): [PWL] Off : 1265s ago
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2401): mCoverManager.getCoverState() : true
D/BatteryService( 2401): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2401): stay LED for fully charged
D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4013): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2401): !@Sync 49
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/TimaService( 2401): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2401): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2401): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 2401): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2401): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2401): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2401): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/dalvikvm( 2401): GC_CONCURRENT freed 3808K, 58% free 25259K/59192K, paused 21ms+18ms, total 265ms
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 51
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 52
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,I/PowerManagerService( 2401): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 53
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2401): stay LED for fully charged
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/BatteryService( 2401): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/BatteryService( 2401): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2401): !@Sync 54
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 55
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 56
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,I/PowerManagerService( 2401): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,E/SPPClientService( 5586): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 57
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2401): stay LED for fully charged
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2401): !@Sync 58
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2401): stay LED for fully charged
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 59
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/TimaService( 2401): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2401): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2401): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 2401): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2401): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2401): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2401): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService( 2401): [PWL] Off : 1625s ago
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 61
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2401): Prepared write state in 77ms
,I/ProcessStatsService( 2401): Prepared write state in 43ms
,I/ProcessStatsService( 2401): Pruning old procstats: /data/system/procstats/state-2016-01-04-05-32-10.bin
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 62
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2401): stay LED for fully charged
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 63
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2401): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2401): <AppSync3 Whitelist>
,V/AlarmManager( 2401): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2777): GC_CONCURRENT freed 9081K, 37% free 18056K/28452K, paused 8ms+8ms, total 73ms
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 64
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/dalvikvm( 2401): GC_CONCURRENT freed 3872K, 58% free 25236K/59192K, paused 20ms+17ms, total 250ms
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService( 2401): [PWL] Off : 1755s ago
,D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2401): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2401): !@Sync 65
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2401): stay LED for fully charged
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4013): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
I/ActivityManager( 2401): Killing 6558:com.google.android.apps.uploader/u0a117 (adj 15): empty for 1810s
I/ActivityManager( 2401): Killing 6522:com.android.chrome/u0a85 (adj 15): empty for 1810s
I/ActivityManager( 2401): Killing 6496:com.sec.android.Kies/1000 (adj 15): empty for 1820s
I/ActivityManager( 2401): Killing 6593:com.sec.knox.bridge/1000 (adj 15): empty for 1841s
I/ActivityManager( 2401): Killing 6580:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1841s
I/ActivityManager( 2401): Killing 6477:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1851s
I/ActivityManager( 2401): Killing 6863:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1851s
I/ActivityManager( 2401): Killing 6848:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1852s
,I/ActivityManager( 2401): Killing 6836:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1852s
,I/ActivityManager( 2401): Killing 6824:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1852s
,I/ActivityManager( 2401): Killing 6811:com.samsung.helphub/1000 (adj 15): empty for 1853s
,I/ActivityManager( 2401): Killing 6798:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1853s
,I/ActivityManager( 2401): Killing 6785:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1853s
,I/ActivityManager( 2401): Killing 6772:com.sec.android.service.cm/u0a82 (adj 15): empty for 1853s
,I/ActivityManager( 2401): Killing 6434:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1853s
,I/ActivityManager( 2401): Killing 6129:com.android.mms/u0a49 (adj 15): empty for 1853s
,I/ActivityManager( 2401): Killing 6746:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1853s
,I/ActivityManager( 2401): Killing 6018:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1854s
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/CountryDetector( 2401): No listener is left
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 66
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :4
,V/NetworkStats( 2401): performPollLocked(flags=0x3)
D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,V/AlarmManager( 2401): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2401): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
V/NetworkStats( 2401): performPollLocked() took 52ms
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,I/SELinux (13386): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13386):  
,I/SELinux (13386): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13386):  
I/SELinux (13386):  
,I/SELinux (13386): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (13386): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(13386): >>>>> Normal User
,E/dalvikvm(13386): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (13386): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(13386): in addTimaSignatureService
,D/TimaKeyStoreProvider(13386): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(13386): Added TimaKesytore provider
,D/dalvikvm(13386): GC_CONCURRENT freed 2996K, 32% free 9572K/13888K, paused 2ms+3ms, total 27ms
,D/dalvikvm(13386): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/@ WidgetProvider(13386): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(13386): onUpdate called for widgetId : 0
,D/@ WidgetProvider(13386): Widget random data : 3
,D/@ WidgetProvider(13386): onUpdate called for widgetId : 5
,D/@ WidgetProvider(13386): Widget random data : 10
,E/dalvikvm(13386): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(13386): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(13386): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(13386): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(13386): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(13386): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(13386): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(13386): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(13386): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(13386): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(13386): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(13386): VFY: replacing opcode 0x22 at 0x0038
,D/dalvikvm(13386): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
,D/dalvikvm(13386): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(13386): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(13386): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,I/SensorManagerA( 2401): getReportingMode :: sensor.mType = 5
,D/LightsService( 2401): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2401): LightSensor setDelay = 200000000
D/Sensors ( 2401): LightSensor setSensorDelay = 200000000
D/Sensors ( 2401): Light sensor flush: not enabled 0
D/Sensors ( 2401): LightSensor enable = 1
D/Sensors ( 2401): LightSensor enableSensor = 1
D/SensorManager( 2401): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/EventLogService( 3157): Aggregate from 1451956954976 (log), 1451956954976 (data)
,V/GLSActivity( 2853): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2853): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(13386): Thread-693(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(13386): Thread-693(ApacheHTTPLog):isShipBuild true
,I/System.out(13386): Thread-693(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/Sensors ( 2401): LightSensor enable = 0
,D/Sensors ( 2401): LightSensor enableSensor = 0
,D/SensorManager( 2401): unregisterListener ::   
D/LightsService( 2401): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2401): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/System.out(13386): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(13386): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(13386): Max ALLOWED memory (MB): 128
V/ImageManager(13386): Max SHOULD USE memory (MB): 128
,V/ImageManager(13386): Max Image Cache memory (MB): 32
,D/skia    (13386): getTotalSize : Do not get file length
,D/@ WidgetProvider(13386): Building widget : 5
,D/dalvikvm( 2777): GC_FOR_ALLOC freed 339K, 34% free 18800K/28452K, paused 55ms, total 55ms
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/BatteryService( 2401): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4013): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2401): !@Sync 67
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2401): stay LED for fully charged
V/HeadsetService( 4013): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4013): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 68
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 69
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4088): GC_CONCURRENT freed 2033K, 31% free 9725K/13928K, paused 2ms+2ms, total 23ms
,I/PowerManagerService( 2401): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/TimaService( 2401): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2401): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2401): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 70
,I/TLC_TIMA_PKM_measure_kernel( 2401): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 2401): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2401): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2401): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/Watchdog( 2401): !@Sync 71
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,I/ActivityManager( 2401): Killing 6730:com.policydm/1000 (adj 15): empty for 1808s
,I/ActivityManager( 2401): Killing 7648:com.sec.android.soagent/u0a38 (adj 15): empty for 1808s
,I/ActivityManager( 2401): Killing 7564:com.vlingo.midas/u0a34 (adj 15): empty for 1808s
,I/ActivityManager( 2401): Killing 7636:com.samsung.klmsagent/u0a18 (adj 15): empty for 1808s
,I/ActivityManager( 2401): Killing 7616:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1808s
,I/ActivityManager( 2401): Killing 7801:com.sec.android.diagmonagent/1000 (adj 15): empty for 1809s
,I/ActivityManager( 2401): Killing 5756:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1809s
,I/ActivityManager( 2401): Killing 6703:com.sec.pcw.device/1000 (adj 15): empty for 1809s
,I/ActivityManager( 2401): Killing 4757:com.android.settings/1000 (adj 15): empty for 1809s
,I/ActivityManager( 2401): Killing 7750:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1809s
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 300, Delta = 0
,TIME-OUT KILL (timeout was 1800000ms),W/ProcessCpuTracker( 2401): Skipping unknown process pid 13821
D/AndroidRuntime(13824): 
D/AndroidRuntime(13824): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(13824): CheckJNI is OFF
D/AndroidRuntime(13824): setted country_code = Poland
D/AndroidRuntime(13824): setted countryiso_code = PL
D/AndroidRuntime(13824): setted sales_code = PLS
D/AndroidRuntime(13824): readGMSProperty: start
D/AndroidRuntime(13824): readGMSProperty: already setted!!
D/AndroidRuntime(13824): readGMSProperty: end
D/AndroidRuntime(13824): addProductProperty: start
D/dalvikvm(13824): Trying to load lib libjavacore.so 0x0
D/dalvikvm(13824): Added shared lib libjavacore.so 0x0
D/dalvikvm(13824): Trying to load lib libnativehelper.so 0x0
D/dalvikvm(13824): Added shared lib libnativehelper.so 0x0
D/dalvikvm(13824): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/AmoledAdjustTimer( 2401): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
E/memtrack(13824): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug(13824): failed to load memtrack module: -2
D/dalvikvm(13824): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime(13824): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2401): START PACKAGE DELETE: observer{1121094080}
D/PackageManager( 2401): pkg{<packageName>}
D/PackageManager( 2401): user{0}
D/ApplicationPolicy( 2401): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2401): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2401): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2401): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager( 2401): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 2401): !@killApplicatoin: 10583, uninstall pkg
I/ActivityManager( 2401): Killing 7518:com.test.thalitest/u0a583 (adj 0): stop com.test.thalitest
D/CustomFrequencyManagerService( 2401): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2401): mDVFSHelper.acquire()
I/SurfaceFlinger( 1921): id=21 Removed NainActivit (8/10)
I/SurfaceFlinger( 1921): id=21 Removed NainActivit (-2/10)
I/SurfaceFlinger( 1921): id=21 Removed NainActivit (-2/10)
I/WindowState( 2401): WIN DEATH: Window{432c7c78 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/PointerIcon( 2401): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2401): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2401): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2401): setHoveringSpenCustomIcon IconType is same.1
W/PackageSettings( 2401): Skipping PackageSetting{4281e9f0 com.example.hello/10580} due to missing metadata
D/PackageManager( 2401): setPackageStoppedState - Execution time: 112 ms
D/PackageManager( 2401): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10583, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 6510): GC_EXPLICIT freed 572K, 29% free 9987K/13964K, paused 6ms+5ms, total 45ms
I/DBG_DM  ( 4789): [3.19.140541][Line:408][onResume] 
D/dalvikvm( 3157): GC_EXPLICIT freed 510K, 24% free 12422K/16164K, paused 4ms+7ms, total 74ms
D/PackageManager( 2401): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10583, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 2969): GC_EXPLICIT freed 1456K, 28% free 10038K/13888K, paused 7ms+6ms, total 75ms
I/DBG_DM  ( 4789): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 27
E/SamsungIME( 2981): mOCRHelper is null
I/InputReader( 2401): Reconfiguring input devices.  changes=0x00000010
I/FPMS_FingerprintManagerService( 2603): onReceive: android.intent.action.PACKAGE_REMOVED
D/QuickConnect[1.1][2] ( 5184): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/SELinux (13853): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13853):  
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2401):   Scheme: "sms"
I/DBG_DM  ( 4789): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/DBG_DM  ( 4789): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
I/DBG_DM  ( 4789): [3.19.140541][Line:418][onResume] Postpone Count : 27
I/DBG_DM  ( 4789): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
I/SELinux (13853): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13853):  
I/SELinux (13853):  
I/SELinux (13853): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13853): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13853): >>>>> Normal User
E/dalvikvm(13853): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux (13853): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/DBG_DM  ( 4789): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2401):   Scheme: "smsto"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider(13853): in addTimaSignatureService
I/DBG_DM  ( 4789): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
D/TimaKeyStoreProvider(13853): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13853): Added TimaKesytore provider
D/dalvikvm( 2401): GC_EXPLICIT freed 3767K, 58% free 24982K/59192K, paused 10ms+29ms, total 242ms
D/PackageManager( 2401): queryIntentReceivers - Execution time: 122 ms
D/dalvikvm( 2401): WAIT_FOR_CONCURRENT_GC blocked 1ms
W/GeofencerStateMachine( 2737): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2401):   Scheme: "mms"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/DBG_DM  ( 4789): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 27
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2401):   Scheme: "mmsto"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/DBG_DM  ( 4789): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
D/RegisteredServicesCache( 2759): empty dynamic service
I/DBG_DM  ( 4789): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
I/DBG_DM  ( 4789): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4789): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
I/DBG_DM  ( 4789): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
I/DBG_DM  ( 4789): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
D/Activity( 4789): setTransGradationMode to true
D/PhoneStatusBar( 2583): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
I/DBG_DM  ( 4789): [3.19.140541][Line:400][onPause] 
D/StatusBarManagerService( 2401): semi p:4789,o:t
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2401):   Scheme: "sms"
I/SurfaceFlinger( 1921): id=23 createSurf (720x1280),2 flag=404, YUIInstallC
D/RCPManagerService( 2401): PackageReceiver onReceive()
D/STATUSBAR-StatusBarManagerService( 2401): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2401): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2401): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2401): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2401): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2401): setHoveringSpenCustomIcon IconType is same.1
I/HarmonyEASService( 2401): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/dalvikvm(13853): GC_CONCURRENT freed 2992K, 32% free 9578K/13892K, paused 5ms+1ms, total 28ms
D/dalvikvm(13853): WAIT_FOR_CONCURRENT_GC blocked 16ms
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2401):   Scheme: "smsto"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2401):   Scheme: "mms"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 2401): Got RemoteException sending setActive(false) notification to pid 7518 uid 10583
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2401):   Scheme: "mmsto"
D/elm:14132(13853): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132(13853): ELMEngine.ELMEngine( context ).
D/elm:14132(13853): MDMBridge.setEnterpriseBridge()
D/elm:14132(13853): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132(13853): ElmAgentService : onCreate()
D/elm:14132(13853): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132(13853): MainReceiver.listeningToPackageRemoved()
D/elm:14132(13853): MDMBridge.getInstance()
D/elm:14132(13853): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux (13868): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13868):  
I/SELinux (13868): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13868):  
I/SELinux (13868):  
I/SELinux (13868): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13868): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13868): >>>>> Normal User
E/dalvikvm(13868): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux (13868): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 2759): GC_CONCURRENT freed 2340K, 27% free 10261K/13912K, paused 7ms+2ms, total 104ms
D/CustomFrequencyManagerService( 2401): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2401): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2401): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  pkgName : ACTIVITY_RESUME_BOOSTER@8
D/elm:14132(13853): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132(13853): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/TimaKeyStoreProvider(13868): in addTimaSignatureService
D/elm:14132(13853): ElmAgentService : onDestroy().
D/TimaKeyStoreProvider(13868): Cannot add TimaSignature Service, License check Failed
I/ActivityManager( 2401): Killing 6371:com.sec.android.app.videoplayer/u0a53 (adj 15): empty for 1814s
D/ActivityThread(13868): Added TimaKesytore provider
D/dalvikvm( 2401): GC_EXPLICIT freed 944K, 58% free 24906K/59192K, paused 9ms+28ms, total 377ms
D/EnterpriseDeviceManagerService( 2401): Package has changed for user 0
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService( 2401): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 2401): removePackageParticipantsLocked: uid=10583 #1
W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
D/STATUSBAR-StatusBarManagerService( 2401): sendNotification(2) - 4
D/dalvikvm(13868): GC_CONCURRENT freed 2997K, 32% free 9571K/13884K, paused 7ms+2ms, total 40ms
D/dalvikvm(13868): WAIT_FOR_CONCURRENT_GC blocked 29ms
D/PackageManager( 2401): delete sourFile : 
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 2401): delete native library directory: 
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/AndroidRuntime(13824): Shutting down VM
D/PackageManager( 2401): return delete result to caller: 1121094080
D/PackageManager( 2401): returnCode: 1
D/dalvikvm(13824): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+0ms, total 4ms
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2401):   Scheme: "sms"
I/SELinux (13883): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13883):  
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/ActivityManager( 2401): Killing 5832:com.osp.app.signin/u0a44 (adj 15): empty for 1815s
I/SELinux (13883): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13883):  
I/SELinux (13883):  
I/SELinux (13883): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13883): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13883): >>>>> Normal User
E/dalvikvm(13883): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux (13883): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(13883): in addTimaSignatureService
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2401):   Scheme: "smsto"
D/TimaKeyStoreProvider(13883): Cannot add TimaSignature Service, License check Failed
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/ActivityThread(13883): Added TimaKesytore provider
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2401):   Scheme: "mms"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2401):   Scheme: "mmsto"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(13883): GC_FOR_ALLOC freed 3017K, 32% free 9553K/13892K, paused 24ms, total 24ms
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(13883): GC_CONCURRENT freed 242K, 32% free 9583K/13892K, paused 3ms+3ms, total 31ms
I/SELinux (13897): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13897):  
I/ActivityManager( 2401): Killing 5854:com.samsung.android.scloud.backup/u0a62 (adj 15): empty for 1815s
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 13% free 9505K/10868K, paused 3ms+3ms, total 36ms
I/SELinux (13897): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13897):  
I/SELinux (13897):  
I/SELinux (13897): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13897): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(13897): >>>>> Normal User
E/dalvikvm(13897): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux (13897): [DEBUG] seapp_context_lookup: seinfoCategory = release
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider(13897): in addTimaSignatureService
D/TimaKeyStoreProvider(13897): Cannot add TimaSignature Service, License check Failed
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ActivityThread(13897): Added TimaKesytore provider
D/UsbSettingsManager( 2401): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 2401): onPackageRemoved : com.test.thalitest
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9505K/10868K, paused 3ms+3ms, total 38ms
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9505K/10868K, paused 2ms+3ms, total 28ms
D/dalvikvm(13897): GC_CONCURRENT freed 3004K, 32% free 9568K/13892K, paused 2ms+1ms, total 18ms
D/dalvikvm(13897): WAIT_FOR_CONCURRENT_GC blocked 15ms
I/SELinux (13912): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13912):  
W/ApplicationsProvider( 2969): Could not fetch usage stats
W/ApplicationsProvider( 2969): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2969): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2969): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2969): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2969): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2969): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2969): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2969): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2969): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2969): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2969): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2969): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SELinux (13912): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13912):  
I/SELinux (13912):  
I/SELinux (13912): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13912): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13912): >>>>> Normal User
E/dalvikvm(13912): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
E/SELinux (13912): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/dalvikvm(13912): Enabling JNI app bug workarounds for target SDK version 8...
D/TimaKeyStoreProvider(13912): in addTimaSignatureService
D/TimaKeyStoreProvider(13912): Cannot add TimaSignature Service, License check Failed
I/ActivityManager( 2401): Killing 7821:com.sec.android.app.voicenote/1000 (adj 15): empty for 1815s
D/ActivityThread(13912): Added TimaKesytore provider
D/dalvikvm(13912): GC_CONCURRENT freed 2996K, 32% free 9570K/13888K, paused 2ms+1ms, total 23ms
D/dalvikvm(13912): WAIT_FOR_CONCURRENT_GC blocked 17ms
E/SQLiteDatabase(13912): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(13912): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13912): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13912): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(13912): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(13912): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13912): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13912): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13912): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(13912): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(13912): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(13912): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(13912): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(13912): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(13912): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(13912): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/SQLiteDatabase(13912): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase(13912): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase(13912): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase(13912): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase(13912): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase(13912): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(13912): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(13912): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13912): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(13912): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(13912): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(13912): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(13912): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(13912): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(13912): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(13912): Shutting down VM
W/dalvikvm(13912): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(13912): FATAL EXCEPTION: main
E/AndroidRuntime(13912): Process: com.sec.pcw.device, PID: 13912
E/AndroidRuntime(13912): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.URLProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13912): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime(13912): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime(13912): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime(13912): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(13912): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(13912): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(13912): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(13912): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(13912): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(13912): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(13912): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(13912): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(13912): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(13912): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13912): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(13912): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(13912): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(13912): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(13912): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(13912): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(13912): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(13912): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(13912): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(13912): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(13912): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(13912): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime(13912): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime(13912): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/AndroidRuntime(13912): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime(13912): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime(13912): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime(13912): 	... 12 more
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop238.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2401): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2401): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2401): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2401): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2401): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2401): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2401): 	... 5 more
I/SELinux (13926): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13926):  
I/Process (13912): Sending signal. PID: 13912 SIG: 9
I/ActivityManager( 2401): Process com.sec.pcw.device (pid 13912) (adj 0) has died.
I/SELinux (13926): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13926):  
I/SELinux (13926):  
I/SELinux (13926): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13926): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13926): >>>>> Normal User
E/dalvikvm(13926): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
E/SELinux (13926): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(13926): in addTimaSignatureService
D/TimaKeyStoreProvider(13926): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13926): Added TimaKesytore provider
D/dalvikvm(13926): GC_CONCURRENT freed 2995K, 32% free 9572K/13888K, paused 4ms+2ms, total 21ms
D/dalvikvm(13926): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/CustomFrequencyManagerService( 2401): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  tag : ACTIVITY_RESUME_BOOSTER@8
W/System.err(13926): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err(13926): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err(13926): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err(13926): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err(13926): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err(13926): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err(13926): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err(13926): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err(13926): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err(13926): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err(13926): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err(13926): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err(13926): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err(13926): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err(13926): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err(13926): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(13926): 	at android.os.Looper.loop(Looper.java:146)
W/System.err(13926): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err(13926): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err(13926): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err(13926): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err(13926): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err(13926): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err(13926): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err(13926): 	at libcore.io.Posix.open(Native Method)
W/System.err(13926): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err(13926): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err(13926): 	... 21 more
D/GalaxyFinderApplication(13926): [Slink platform] Version = 29011
D/GalaxyFinderApplication(13926): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux (13940): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13940):  
I/ActivityManager( 2401): Killing 7660:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty for 1815s
I/SELinux (13940): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13940):  
I/SELinux (13940):  
I/SELinux (13940): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13940): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(13940): >>>>> Normal User
E/dalvikvm(13940): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
E/SELinux (13940): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(13940): in addTimaSignatureService
D/TimaKeyStoreProvider(13940): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13940): Added TimaKesytore provider
D/dalvikvm(13940): GC_CONCURRENT freed 2998K, 32% free 9571K/13884K, paused 1ms+1ms, total 17ms
D/dalvikvm(13940): WAIT_FOR_CONCURRENT_GC blocked 15ms
W/ContextImpl(13940): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences(13940): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences(13940): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication(13940): ContentProvider is not null
W/ResourceType(13940): No package identifier when getting value for resource number 0x00000000
I/System.out(13940): resource Id::2131361807
E/SQLiteDatabase(13940): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(13940): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13940): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(13940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(13940): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13940): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(13940): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(13940): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(13940): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(13940): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(13940): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(13940): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(13940): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/SQLiteDatabase(13940): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/SQLiteDatabase(13940): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/SQLiteDatabase(13940): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase(13940): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase(13940): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase(13940): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase(13940): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/SQLiteDatabase(13940): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/SQLiteDatabase(13940): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/SQLiteDatabase(13940): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/SQLiteDatabase(13940): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/SQLiteDatabase(13940): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/SQLiteDatabase(13940): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/SQLiteDatabase(13940): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(13940): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(13940): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13940): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(13940): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(13940): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(13940): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(13940): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(13940): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(13940): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(13940): Shutting down VM
W/dalvikvm(13940): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(13940): FATAL EXCEPTION: main
E/AndroidRuntime(13940): Process: com.sec.android.app.shealth, PID: 13940
E/AndroidRuntime(13940): java.lang.RuntimeException: Unable to create application com.sec.android.app.shealth.SHealthApplication: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13940): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4793)
E/AndroidRuntime(13940): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(13940): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(13940): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(13940): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(13940): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(13940): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(13940): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(13940): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(13940): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(13940): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(13940): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13940): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(13940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(13940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(13940): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(13940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(13940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(13940): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(13940): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(13940): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(13940): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(13940): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(13940): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/AndroidRuntime(13940): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/AndroidRuntime(13940): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/AndroidRuntime(13940): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/AndroidRuntime(13940): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/AndroidRuntime(13940): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/AndroidRuntime(13940): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/AndroidRuntime(13940): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/AndroidRuntime(13940): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/AndroidRuntime(13940): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/AndroidRuntime(13940): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/AndroidRuntime(13940): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/AndroidRuntime(13940): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/AndroidRuntime(13940): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/AndroidRuntime(13940): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/AndroidRuntime(13940): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/AndroidRuntime(13940): 	... 10 more

```
