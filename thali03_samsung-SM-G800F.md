#### Test 549702619369e5e_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
I/PowerManagerService( 2401): [PWL] Off : 180s ago
D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0
--------- beginning of /dev/log/main
D/AndroidRuntime( 7125): 
D/AndroidRuntime( 7125): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7125): CheckJNI is OFF
D/AndroidRuntime( 7125): setted country_code = Poland
D/AndroidRuntime( 7125): setted countryiso_code = PL
D/AndroidRuntime( 7125): setted sales_code = PLS
D/AndroidRuntime( 7125): readGMSProperty: start
D/AndroidRuntime( 7125): readGMSProperty: already setted!!
D/AndroidRuntime( 7125): readGMSProperty: end
D/AndroidRuntime( 7125): addProductProperty: start
D/dalvikvm( 7125): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7125): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7125): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7125): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7125): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7125): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7125): failed to load memtrack module: -2
D/dalvikvm( 7125): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7125): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2401): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2401): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2401): mDVFSHelper.acquire()
I/SELinux ( 7153): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7153):  
D/PointerIcon( 2401): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2401): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2401): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2401): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7125): Shutting down VM
D/dalvikvm( 7125): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 7153): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7153):  
I/SELinux ( 7153):  
I/SELinux ( 7153): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7153): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7153): >>>>> Normal User
E/dalvikvm( 7153): >>>>> com.test.thalitest [ userId:0 | appId:10604 ]
E/SELinux ( 7153): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7153): in addTimaSignatureService
D/TimaKeyStoreProvider( 7153): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7153): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4182): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4182): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7153): GC_CONCURRENT freed 2999K, 32% free 9575K/13900K, paused 3ms+2ms, total 19ms
D/dalvikvm( 7153): WAIT_FOR_CONCURRENT_GC blocked 10ms
V/WebViewChromium( 7153): Binding Chromium to the background looper Looper (main, tid 1) {4229d1c0}
I/chromium( 7153): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7153): Initializing chromium process, renderers=0
W/chromium( 7153): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7153): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7153): loaded /system/lib/egl/libGLESv1_CM_mali.so,
,D/libEGL  ( 7153): loaded /system/lib/egl/libGLESv2_mali.so,
I/Mali    ( 7153): Mali API Version : 401
,I/Mali    ( 7153): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 ,
,D/AmoledAdjustTimer( 2401): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4,
I/dalvikvm( 7153): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7153): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7153): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7153): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush,
W/dalvikvm( 7153): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7153): VFY: replacing opcode 0x6e at 0x0008,
,D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false,
,D/StatusBarManagerService( 2401): tr p:7153,o:f,
W/dalvikvm( 7153): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7153): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7153): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7153): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 7153): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7153): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7153): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest,
W/dalvikvm( 7153): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7153): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7153): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7153): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7153): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7153): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2401): semi p:7153,o:f
,I/SurfaceFlinger( 1921): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2401): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2401): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2401): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2401): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2401): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2401): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7153): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7153): Enabling debug mode 0
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/AwContents( 7153): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 7153): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2401): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  tag : ACTIVITY_RESUME_BOOSTER@4
,D/CustomFrequencyManagerService( 2401): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/ActivityManager( 2401): mDVFSHelper.release()
,D/JsMessageQueue( 7153): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7153): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42294eb8
,D/dalvikvm( 7153): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42294eb8
D/jxcore_app_log( 7153): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027599336
,D/JX-Cordova( 7153): jxcore cordova android initializing
,D/dalvikvm( 7153): GC_CONCURRENT freed 1292K, 19% free 11357K/13972K, paused 1ms+2ms, total 22ms
,D/dalvikvm( 7153): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 7153): GC_CONCURRENT freed 1939K, 18% free 14958K/18236K, paused 2ms+2ms, total 40ms
,D/dalvikvm( 7153): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/CustomFrequencyManagerService( 2401): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7153): GC_FOR_ALLOC freed 5292K, 30% free 16234K/23104K, paused 51ms, total 51ms
,D/dalvikvm( 7153): GC_CONCURRENT freed 6710K, 32% free 17694K/25748K, paused 1ms+9ms, total 62ms
,D/dalvikvm( 7153): WAIT_FOR_CONCURRENT_GC blocked 41ms
,D/dalvikvm( 7153): GC_FOR_ALLOC freed 1109K, 32% free 17626K/25748K, paused 49ms, total 49ms
,I/dalvikvm-heap( 7153): Grow heap (frag case) to 22.020MB for 3688532-byte allocation
,D/dalvikvm( 7153): GC_FOR_ALLOC freed 2460K, 37% free 18768K/29352K, paused 42ms, total 42ms
,W/jxcore-log( 7153): Initializing JXcore engine
,W/jxcore-log( 7153): JXcore engine is ready
,W/jxcore-log( 7153): Starting JXcore engine
,W/jxcore-log( 7153): Platform android
W/jxcore-log( 7153): 
,W/jxcore-log( 7153): Process ARCH arm
W/jxcore-log( 7153): 
,I/jxcore-log( 7153): JXcore Cordova bridge is ready!
I/jxcore-log( 7153): 
,W/jxcore-log( 7153): JXcore engine is started
,I/chromium( 7153): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7153): Toggling radios to true
I/jxcore-log( 7153): 
,D/BluetoothAdapter( 7153): enable(): BT is already enabled..!
,I/WifiManager( 7153): packageName : com.test.thalitest
,I/WifiManager( 7153): setWifiEnabled : true
,I/WifiService( 2401): setWifiEnabled: true pid=7153, uid=10604
,W/ActivityManager( 2401): Permission Denial: getCurrentUser() from pid=7153, uid=10604 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2401): Failed getting userId using ActivityManagerNative
W/WifiService( 2401): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7153, uid=10604 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2401): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2401): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2401): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2401): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2401): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2401): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2401): disconnect: pid=7153, uid=10604
I/wpa_supplicant( 3965): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7153): Radios toggled
I/jxcore-log( 7153): 
,I/wpa_supplicant( 3965): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2401): interfaceStatusChanged wlan0, true
D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2401): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3965): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 3965): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3965): First Scan Start
W/Settings( 2401): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2401): ignore requestNetworkTransitionWakelock airplane:true
,I/wpa_supplicant( 3965): Scan requested (ret=0) - scan timeout 30 seconds
D/WifiP2pService( 2401): InactiveState{ what=143375 }
D/WifiP2pService( 2401): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2401): evaluateTrafficStatsPolling
I/wpa_supplicant( 3965): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3965): Skip scan - already scanning
D/ConnectivityService( 2401): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2401): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2401): net.tcp.usercfg.default not found in system default properties
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2401): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2401): net.tcp.delack.default not found in system default properties
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
E/ConnectivityService( 2401): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
,D/WifiP2pService( 2401): InactiveState{ what=143375 }
,D/WifiP2pService( 2401): P2pEnabledState{ what=143375 }
,D/ConnectivityService( 2401): Attempting to switch to mobile
,D/ConnectivityService( 2401): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
I/SELinux ( 7200): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7200):  
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1
,I/WifiTrafficPoller( 2401): evaluateTrafficStatsPolling
,E/WifiStateMachine( 2401): Error! unhandled message{ when=-49ms what=135188 target=com.android.internal.util.StateMachine$SmHandler },
,E/WifiStateMachine( 2401): Error! unhandled message{ when=-49ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
,E/WifiStateMachine( 2401): Error! unhandled message{ when=-16ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
I/SELinux ( 7200): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7200):  
I/SELinux ( 7200):  
,I/SELinux ( 7200): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7200): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7200): >>>>> Normal User
,E/dalvikvm( 7200): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7200): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
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
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 7200): in addTimaSignatureService
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 7200): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7200): Added TimaKesytore provider
,D/NetUtils( 2401): android_net_utils_resetConnections in env=0x77ef15d0 clazz=0x61e00001 iface=wlan0 mask=0x3
D/ConnectivityService( 2401): resetConnections(wlan0, 3)
,D/dalvikvm( 7200): GC_CONCURRENT freed 2985K, 32% free 9586K/13900K, paused 9ms+2ms, total 32ms
,D/dalvikvm( 7200): WAIT_FOR_CONCURRENT_GC blocked 15ms
,V/NativeCrypto( 2847): Read error: ssl=0x7bace978: I/O error during system call, Connection timed out
,V/NativeCrypto( 2847): SSL shutdown failed: ssl=0x7bace978: I/O error during system call, Broken pipe
,E/SPPClientService( 5526): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5526): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5526): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5526): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5526): [b] ResponseMap empty
,D/ConnectivityService( 2401): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
V/NetworkStats( 2401): updateIfacesLocked()
,V/NetworkStats( 2401): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
V/NetworkStats( 2401): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/System.out( 7200): Inside WakeupProvider
,I/System.out( 7200): Inside onCreate() of WakeupTriggerProvide
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
V/NetworkStats( 2401): performPollLocked() took 33ms
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,I/VlingoApplication( 7200): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7200): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7200): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/DialogFlow( 7200): initQueue()
,D/NearbySettings( 2819): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2819): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2819): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 2819): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2819): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2819): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2819): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2401): Killing 6155:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/NearbySettings( 2819): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2819): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2819): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 2819): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2819): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2819): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2819): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2401): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2401): MasterInitialState.processMessage what=3
,D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
I/ApplicationPolicy( 2401): updateDataUsageMap
,D/CaptivePortalTracker( 2401): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/ConnectivityService( 2401): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6561): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6561): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6561): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6561): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6561): noConnectivity : true
,I/DBG_DM  ( 4719): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2401): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7229): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7229):  
,I/SELinux ( 7229): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7229):  
I/SELinux ( 7229):  
,I/SELinux ( 7229): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7229): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7229): >>>>> Normal User
,E/dalvikvm( 7229): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7229): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7229): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7229): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7229): Added TimaKesytore provider
,D/dalvikvm( 7229): GC_CONCURRENT freed 2989K, 32% free 9580K/13896K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 7229): WAIT_FOR_CONCURRENT_GC blocked 10ms
,I/wpa_supplicant( 3965): nl80211: Received scan results (7 BSSes)
,I/wpa_supplicant( 3965): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3965): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2401): interfaceStatusChanged wlan0, true
,I/ActivityManager( 2401): Killing 6225:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3965): Associated with C0.AA.48
I/wpa_supplicant( 3965): freq(2412) increment count 2
,I/wpa_supplicant( 3965): meet head of list.
,D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2401): interfaceStatusChanged wlan0, true
D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2401): interfaceStatusChanged wlan0, true
D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2401): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3965): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3965): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
D/Tethering( 2401): interfaceStatusChanged wlan0, true
,D/WifiNative( 2401): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7243): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7243):  
,I/SELinux ( 7243): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7243):  
I/SELinux ( 7243):  
,I/SELinux ( 7243): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7243): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7243): >>>>> Normal User
,E/dalvikvm( 7243): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7243): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7243): in addTimaSignatureService
D/WifiP2pService( 2401): InactiveState{ what=143375 }
D/WifiP2pService( 2401): P2pEnabledState{ what=143375 }
,D/TimaKeyStoreProvider( 7243): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7243): Added TimaKesytore provider
,D/dalvikvm( 7243): GC_CONCURRENT freed 2993K, 32% free 9578K/13900K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7243): WAIT_FOR_CONCURRENT_GC blocked 9ms
,I/ActivityManager( 2401): Killing 6297:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7257): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7257):  
,I/SELinux ( 7257): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7257):  
I/SELinux ( 7257):  
,I/SELinux ( 7257): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7257): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7257): >>>>> Normal User
,E/dalvikvm( 7257): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7257): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7257): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7257): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7257): Added TimaKesytore provider
I/dhcpcd  ( 7256): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7256): bssid match
,D/dalvikvm( 7257): GC_CONCURRENT freed 3003K, 32% free 9571K/13900K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 7257): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/KLMS-2.3.201 : ( 7257): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7257): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452292246903
,I/KLMS-2.3.201 : ( 7257): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2401): Killing 6317:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7275): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7275):  
,I/SELinux ( 7275): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7275):  
I/SELinux ( 7275):  
,I/SELinux ( 7275): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7275): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7275): >>>>> Normal User
E/dalvikvm( 7275): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
E/SELinux ( 7275): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7275): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7275): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7275): Added TimaKesytore provider
,D/dalvikvm( 7275): GC_CONCURRENT freed 3000K, 32% free 9568K/13892K, paused 4ms+1ms, total 21ms
,D/dalvikvm( 7275): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/SO_AGENT( 7275): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7275): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5790): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5790): [BDLM] already registered in spp
,I/SA      ( 5790): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5790): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5790): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5790): [OR] == isSIMCardReady false ==
I/SA      ( 5790): [SCU] == networkStateCheck == false
,I/SA      ( 5790): [OR] onReceive END
I/ActivityManager( 2401): Killing 6243:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
,I/SELinux ( 7287): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7287):  
,D/libgps  ( 2401): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2401): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2401): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2401): agps_ril_update_network_availability: Waiting for IPC connection...
,D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 13% free 9505K/10872K, paused 3ms+3ms, total 34ms
,I/SELinux ( 7287): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7287):  
I/SELinux ( 7287):  
,I/SELinux ( 7287): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7287): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7287): >>>>> Normal User
,E/dalvikvm( 7287): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7287): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9505K/10872K, paused 2ms+3ms, total 26ms
,D/TimaKeyStoreProvider( 7287): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7287): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7287): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9505K/10872K, paused 2ms+3ms, total 25ms
,D/dalvikvm( 7287): GC_CONCURRENT freed 2997K, 32% free 9580K/13900K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7287): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/sCloudBackupApp( 7287): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7287): Other Intent
I/ActivityManager( 2401): Killing 6362:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,I/SELinux ( 7300): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7300):  
,I/SELinux ( 7300): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7300):  
I/SELinux ( 7300):  
,I/SELinux ( 7300): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7300): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7300): >>>>> Normal User
,E/dalvikvm( 7300): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7300): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7300): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7300): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7300): Added TimaKesytore provider
,D/dalvikvm( 7300): GC_CONCURRENT freed 2990K, 32% free 9573K/13892K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7300): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/com.samsung.app( 7300): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7300): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7300): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7300): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7300): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7300): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5323): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2401): stay LED for fully charged
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/com.samsung.app( 7300): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
D/HeadsetStateMachine( 3997): Disconnected process message: 10
D/daemonapp( 5323): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7300): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/daemonapp( 5323): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7300): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7300): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2401): Killing 5572:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/Headlines( 5857): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5857): getCountryCode(): countryCode = PL
,D/Headlines( 5857): Breath.onCreate,
,D/Headlines( 5857): Breath timer started. interval : 30000,
,I/SELinux ( 7313): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7313):  
,V/AlarmManager( 2401): waitForAlarm result :8,
D/Headlines( 5857): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5857): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5857): updateCategory : HeadlinesCardManager:updateCategory() try to query category list,
D/Headlines( 5857): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5857): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5857): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5857): requestUpdateNewsWelcomeCard !!! no welcome card,
,I/SELinux ( 7313): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7313):  
I/SELinux ( 7313):  
,I/SELinux ( 7313): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7313): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7313): >>>>> Normal User
,E/dalvikvm( 7313): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ],
,E/SELinux ( 7313): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/TimaKeyStoreProvider( 7313): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7313): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7313): Added TimaKesytore provider
,D/dalvikvm( 7313): GC_CONCURRENT freed 2994K, 32% free 9574K/13896K, paused 4ms+2ms, total 27ms,
,D/dalvikvm( 7313): WAIT_FOR_CONCURRENT_GC blocked 22ms,
,V/WebViewChromium( 7313): Binding Chromium to the background looper Looper (main, tid 1) {4229a2d0}
,I/chromium( 7313): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7313): Initializing chromium process, renderers=0
,W/chromium( 7313): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7313): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7313): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7313): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7313): Mali API Version : 401
,I/Mali    ( 7313): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/libgps  ( 2401): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2401): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2401): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,W/GAV2    ( 7313): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7313): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,D/WifiP2pService( 2401): InactiveState{ what=143375 }
,D/WifiP2pService( 2401): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2401): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2401): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2401): CaptivePortalCheckState enter
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2401): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2401): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2401): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2401): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2401): evaluateTrafficStatsPolling
D/ConnectivityService( 2401): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2401): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2401): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2401): GC_CONCURRENT freed 4372K, 71% free 25568K/87364K, paused 28ms+26ms, total 313ms
,D/dalvikvm( 2401): WAIT_FOR_CONCURRENT_GC blocked 217ms
,D/dalvikvm( 2401): WAIT_FOR_CONCURRENT_GC blocked 215ms
,D/dalvikvm( 2401): WAIT_FOR_CONCURRENT_GC blocked 218ms
,D/ConnectivityService( 2401): handleConnectivityChange: setting default proxy info 
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,I/NSApplication( 7313): Starting up...
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,I/iu.Environment( 5921): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,V/NetworkStats( 2401): updateIfacesLocked()
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,V/NetworkStats( 2401): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,V/NetworkStats( 2401): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/QuickConnect[1.1][2] ( 5125): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5125): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5125): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422aa180
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,I/SELinux ( 7387): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7387):  
V/NetworkStats( 2401): performPollLocked() took 23ms
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,I/SELinux ( 7387): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7387):  
I/SELinux ( 7387):  
,I/SELinux ( 7387): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7387): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7387): >>>>> Normal User
,E/dalvikvm( 7387): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7387): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7387): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7387): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7387): Added TimaKesytore provider
,D/dalvikvm( 7387): GC_CONCURRENT freed 2997K, 32% free 9577K/13900K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7387): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId
,E/Watchdog( 2401): !@Sync 8
,I/SELinux ( 7405): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7405):  
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId
,W/ActivityManager( 2401): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 7405): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7405):  
I/SELinux ( 7405):  
,I/SELinux ( 7405): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7405): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7405): >>>>> Normal User
,E/dalvikvm( 7405): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7405): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId
,I/ActivityManager( 2401): Killing 6280:com.sec.phone/1001 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7405): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7405): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7405): Added TimaKesytore provider
,I/SELinux ( 7419): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7419):  
,I/ActivityManager( 2401): Killing 6285:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/SELinux ( 7419): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7419):  
I/SELinux ( 7419):  
,I/SELinux ( 7419): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7419): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7419): >>>>> Normal User
,E/dalvikvm( 7419): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7419): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7419): in addTimaSignatureService
D/dalvikvm( 7405): GC_CONCURRENT freed 3001K, 32% free 9568K/13900K, paused 4ms+2ms, total 24ms
,D/dalvikvm( 7405): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/TimaKeyStoreProvider( 7419): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7419): Added TimaKesytore provider
,D/BadgeProvider( 7405): onCreate
,D/BadgeProvider( 7405): DatabaseHelper
,D/BadgeProvider( 7405): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7405): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7405): sendNotify, [notify] : null
D/BadgeProvider( 7405): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7405): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7405): update, [UpdateCount] : 1
,D/Launcher.Model( 2770): reloadBadges entered.
,D/Tethering( 2401): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2401): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2401): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/dalvikvm( 7419): GC_CONCURRENT freed 2999K, 32% free 9575K/13900K, paused 3ms+3ms, total 32ms
,D/dalvikvm( 7419): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/DBG_DM  ( 4719): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,D/libgps  ( 2401): agps_ril_update_network_state: Waiting for IPC connection...
,D/hcjo    ( 5942): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5942): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5942): exit::IDLE
,D/InitializeManagerStateMachine( 5942): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5942): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5942): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5942): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5942): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 5942): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5942): entry::SUCCESS
,D/hcjo    ( 5942): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5942): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5942): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5942): exit::SUCCESS
,D/InitializeManagerStateMachine( 5942): entry::IDLE
,E/SPPClientService( 5526): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5526): [SystemStateMoniter] Current Time : 258707
,E/SPPClientService( 5526): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5526): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 2819): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2819): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2819): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2819): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 2819): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2819): MountReceiver.onReceive - Keep current state
,D/Headlines( 5857): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5857): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5857): Breath 1852 latestRequest time : 1452292247713 current time : 1452292249565,
,E/SPPClientService( 5526): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5526): [a] [ConnectionManager] Connection is already disconnected.,
,D/NearbySettings( 2819): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
E/SPPClientService( 5526): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,I/NearbySettings( 2819): MountReceiver.onReceive - Keep current state,
,E/SPPClientService( 5526): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19,
,D/NearbySettings( 2819): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
V/NearbySettings( 2819): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2819): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2819): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2819): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2819): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 2819): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2819): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger( 1921): id=20 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 2401): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2401
I/PCWCLIENTTRACE_PushUtil( 6561): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6561): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6561): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6561): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5526): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5526): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5526): [g] getNetMCC return empty string
,I/KLMS-2.3.201 : ( 7257): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7257): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452292249998
,I/KLMS-2.3.201 : ( 7257): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/dalvikvm( 7243): Total arena pages for JIT: 11
,I/dalvikvm( 7243): Total arena pages for JIT: 12
,I/dalvikvm( 7243): Total arena pages for JIT: 13
I/dalvikvm( 7243): Total arena pages for JIT: 14
,I/dalvikvm( 7243): Total arena pages for JIT: 15
I/dalvikvm( 7243): Total arena pages for JIT: 16
,I/dalvikvm( 7243): Total arena pages for JIT: 17
,D/SO_AGENT( 7275): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3296): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/GalaxyFinderApplication( 3296): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3296): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3296): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7275): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 3424): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7442): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7442):  
,I/SELinux ( 7446): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7446):  
,I/SELinux ( 7442): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7442):  
I/SELinux ( 7442):  
I/SELinux ( 7442): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7442): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7442): >>>>> Normal User
E/dalvikvm( 7442): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7442): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 7446): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7446):  
I/SELinux ( 7446):  
,I/SELinux ( 7446): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7446): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7446): >>>>> Normal User
,E/dalvikvm( 7446): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,D/dalvikvm( 2722): GC_EXPLICIT freed 341K, 28% free 10038K/13884K, paused 6ms+8ms, total 89ms
,E/SELinux ( 7446): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7442): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7442): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7442): Added TimaKesytore provider
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 330, Delta = 20
,D/TimaKeyStoreProvider( 7446): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7446): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7446): Added TimaKesytore provider
,I/SA      ( 5790): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5790): [BDLM] already registered in spp
,I/SA      ( 5790): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5790): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5790): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5790): [OR] == isSIMCardReady false ==
,I/SA      ( 5790): [SCU] == networkStateCheck == true
I/SA      ( 5790): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5790): isChinaCountryCode : false
,I/SA      ( 5790): [OR] == networkStateCheck true ==
,I/SA      ( 5790): [OR] GetMyCountryZoneTask
D/dalvikvm( 7442): GC_CONCURRENT freed 2985K, 32% free 9586K/13900K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 7442): WAIT_FOR_CONCURRENT_GC blocked 12ms
,I/SA      ( 5790): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
,I/SA      ( 5790): [SRS] prepareGetMyCountryZone
,I/SCloudBackupReceiver( 7287): Other Intent
,D/dalvikvm( 7446): GC_CONCURRENT freed 3011K, 32% free 9563K/13900K, paused 2ms+1ms, total 26ms
,D/dalvikvm( 7446): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/SA      ( 5790): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5790): [SSP] query invoked
,I/SA      ( 5790): [TPMU] GetMccFromDB : null
I/SA      ( 5790): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5790): [TPM] isNoProxy(default) : true
,I/SA      ( 5790): [RC New] Execute method=[GET] start
,D/com.samsung.app( 7300): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,V/KVNProvider( 7446): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7446): getFindoCursor query string : 
,D/com.samsung.app( 7300): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,V/KVNProvider( 7446): getTagSearchCursor() tagSearchCursor count : 0
,D/Headlines( 5857): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5857): getCountryCode(): countryCode = PL
,D/Headlines( 5857): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5857): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5857): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5857): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5857): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5857): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5857): requestUpdateNewsWelcomeCard !!! no welcome card
,I/System.out( 7243): Thread-630(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7243): Thread-630(ApacheHTTPLog):isShipBuild true
,I/System.out( 7243): Thread-630(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/iu.Environment( 5921): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/ActivityManager( 2401): Killing 5968:com.android.calendar/u0a144 (adj 15): empty #43
D/QuickConnect[1.1][2] ( 5125): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5125): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 5125): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422aa180
,D/libgps  ( 2401): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2401): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2401): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2401): agps_ril_update_network_availability: Waiting for IPC connection...
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId
,D/hcjo    ( 5942): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 5942): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5942): exit::IDLE
,D/InitializeManagerStateMachine( 5942): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5942): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5942): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5942): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5942): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5942): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5942): entry::SUCCESS
,D/hcjo    ( 5942): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5942): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5942): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5942): exit::SUCCESS
,D/InitializeManagerStateMachine( 5942): entry::IDLE
,E/SPPClientService( 5526): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5526): [SystemStateMoniter] Current Time : 259743
,E/SPPClientService( 5526): [SystemStateMoniter] No Connect : false
,I/System.out( 7243): AsyncTask #1 calls detatch()
,W/System.err( 7243): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7243): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7243): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7243): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7243): ,	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7243): 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7243): ,	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 7243): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7243): ,	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7243): ,	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7243): Caused by: java.lang.NullPointerException
W/System.err( 7243): ,	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7243): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7243): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7243): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7243): ,	... 8 more
,I/ActivityManager( 2401): Killing 6141:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43,
,D/PackageManager( 2401): [MSG] WRITE_PACKAGE_RESTRICTIONS,
,D/dalvikvm( 5526): GC_CONCURRENT freed 1975K, 25% free 10450K/13888K, paused 3ms+4ms, total 39ms
,D/AmoledAdjustTimer( 2401): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4,
,I/SA      ( 5790): [RC New] [v2liruge] api execute + 786,
,I/SA      ( 5790): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK,
,I/System.out( 5790): AsyncTask #2 calls detatch(),
,I/SA      ( 5790): [TPMU] getNetworkMcc : ,
,I/SA      ( 5790): [SCU] saveMccToPreferece Start,
I/SA      ( 5790): [SCU] RegionMCC : 260
,I/SA      ( 5790): [SSP] query invoked,
I/SA      ( 5790): [TPMU] GetMccFromDB : null
,I/SA      ( 5790): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5790): [SCU] saveMccToPreferece End,
I/SA      ( 5790): [RC New] executeRequest [v2liruge] end. 810
I/SA      ( 5790): [RC New] Execute end
,I/SA      ( 5790): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5790): [OR] GetMyCountryZoneTask Success
,D/libgps  ( 2401): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2401): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2401): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,E/WifiStateMachine( 2401): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/SPPClientService( 5526): [b] __InitReply__
,I/ActivityManager( 2401): Killing 6178:com.google.android.music:main/u0a125 (adj 15): empty #43
I/SurfaceFlinger( 1921): id=20 Removed Uoast (10/11)
,I/SurfaceFlinger( 1921): id=20 Removed Uoast (-2/11)
D/PowerManagerService( 2401): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2401) eventTime = 262378
D/PowerManagerService( 2401): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2401 (0x0)
D/PowerManagerService( 2401): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2401, ws=WorkSource{1000}) (elapsedTime=3467)
,I/GAV2    ( 7313): Thread[GAThread,5,main]: No campaign data found.
,W/WifiP2pStateTracker( 2401): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2401): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2401):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2401): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2401): updateSourceRoutes : no source routing conditions
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6561): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6561): [hasSamungAccount] - No Samsung Account
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6561): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6561): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6561): GetString : secure API is not supported!!
,I/PCWCLIENTTRACE_PushUtil( 6561): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6561): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6561): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6561): [ensureRegistration] - No Samsung account
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2401): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2401): mCoverManager.getCoverState() : true
V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3997): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/CaptivePortalTracker( 2401): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
,D/ConnectivityService( 2401): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null,
D/CaptivePortalTracker( 2401): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 2401): Don't send network conditions - lacking user consent.,
D/CaptivePortalTracker( 2401): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2401): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2401): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
D/ConnectivityService( 2401): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 5942): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 5942): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5942): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 5942): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5942): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5942): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5942): entry::IDLE,
,I/jxcore-log( 7153): Test app app.js loaded,
I/jxcore-log( 7153): 
,I/Choreographer( 7153): Skipped 878 frames!  The application may be doing too much work on its main thread.,
,I/chromium( 7153): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 7153): --= Surplus to requirements =--,
I/jxcore-log( 7153): 
I/jxcore-log( 7153): ****TEST TOOK:  ms ****
I/jxcore-log( 7153): 
,I/jxcore-log( 7153): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
I/jxcore-log( 7153): 
,V/AlarmManager( 2401): waitForAlarm result :8,
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/SSRMv2:SIOP( 2401): SIOP:: AP = 330, Delta = 0
D/AndroidRuntime( 7490): 
D/AndroidRuntime( 7490): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7490): CheckJNI is OFF
D/AndroidRuntime( 7490): setted country_code = Poland
D/AndroidRuntime( 7490): setted countryiso_code = PL
D/AndroidRuntime( 7490): setted sales_code = PLS
D/AndroidRuntime( 7490): readGMSProperty: start
D/AndroidRuntime( 7490): readGMSProperty: already setted!!
D/AndroidRuntime( 7490): readGMSProperty: end
D/AndroidRuntime( 7490): addProductProperty: start
D/PreloadUpdateManagerStateMachine( 5942): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5942): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5942): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 5942): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 5942): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5942): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 5942): entry::IDLE
D/dalvikvm( 7490): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7490): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7490): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7490): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7490): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7490): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7490): failed to load memtrack module: -2
D/dalvikvm( 7490): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7490): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2401): START PACKAGE DELETE: observer{1122472848}
D/PackageManager( 2401): pkg{<packageName>}
D/PackageManager( 2401): user{0}
D/PackageManager( 2401): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2401): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2401): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2401): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2401): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 2401): !@killApplicatoin: 10604, uninstall pkg
I/ActivityManager( 2401): Killing 7153:com.test.thalitest/u0a604 (adj 0): stop com.test.thalitest
D/CustomFrequencyManagerService( 2401): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2401): mDVFSHelper.acquire()
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (-2/10)
,I/WindowState( 2401): WIN DEATH: Window{44c6a328 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/PointerIcon( 2401): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2401): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2401): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2401): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 2401): Skipping PackageSetting{42a6c040 com.example.hello/10600} due to missing metadata
,D/PackageManager( 2401): setPackageStoppedState - Execution time: 112 ms
D/PackageManager( 2401): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10604, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/AmoledAdjustTimer( 2401): prevTemp = 283, currTemp = 285, prevStep = 4, currStep = 4
,D/dalvikvm( 6721): GC_EXPLICIT freed 199K, 30% free 9961K/14112K, paused 3ms+3ms, total 48ms
,D/dalvikvm( 6403): GC_EXPLICIT freed 2511K, 29% free 9887K/13900K, paused 5ms+4ms, total 60ms
,I/DBG_DM  ( 4719): [3.19.140541][Line:408][onResume] 
D/PackageManager( 2401): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10604, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/FPMS_FingerprintManagerService( 2600): onReceive: android.intent.action.PACKAGE_REMOVED
,I/DBG_DM  ( 4719): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
,D/dalvikvm( 2963): GC_EXPLICIT freed 1465K, 28% free 10036K/13896K, paused 6ms+8ms, total 79ms
,I/DBG_DM  ( 4719): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,E/SamsungIME( 2993): mOCRHelper is null
,I/DBG_DM  ( 4719): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4719): [3.19.140541][Line:418][onResume] Postpone Count : 29
,D/QuickConnect[1.1][2] ( 5125): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
,W/GeofencerStateMachine( 2735): Ignoring removeGeofence because network location is disabled.
,I/DBG_DM  ( 4719): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
I/SELinux ( 7501): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7501):  
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2401):   Scheme: "sms"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2401):   Scheme: "smsto"
,I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 7501): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7501):  
I/SELinux ( 7501):  
I/SELinux ( 7501): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7501): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7501): >>>>> Normal User
E/dalvikvm( 7501): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux ( 7501): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/DBG_DM  ( 4719): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,D/TimaKeyStoreProvider( 7501): in addTimaSignatureService
,I/DBG_DM  ( 4719): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,D/TimaKeyStoreProvider( 7501): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7501): Added TimaKesytore provider
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "mms"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 3156): GC_EXPLICIT freed 2307K, 23% free 12428K/16060K, paused 42ms+7ms, total 293ms
,D/dalvikvm( 2401): GC_EXPLICIT freed 3394K, 72% free 25140K/86912K, paused 14ms+27ms, total 273ms
D/dalvikvm( 2401): WAIT_FOR_CONCURRENT_GC blocked 13ms
,I/InputReader( 2401): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "mmsto"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4719): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
,D/RegisteredServicesCache( 2757): empty dynamic service
,I/DBG_DM  ( 4719): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2401):   Scheme: "sms"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4719): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4719): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4719): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4719): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4719): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4719): setTransGradationMode to true
,D/PhoneStatusBar( 2580): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/DBG_DM  ( 4719): [3.19.140541][Line:400][onPause] 
D/StatusBarManagerService( 2401): semi p:4719,o:t
,I/SurfaceFlinger( 1921): id=21 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2401): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2401): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "smsto"
D/PointerIcon( 2401): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2401): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2401): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2401): setHoveringSpenCustomIcon IconType is same.1
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/RCPManagerService( 2401): PackageReceiver onReceive()
,I/HarmonyEASService( 2401): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/dalvikvm( 7501): GC_CONCURRENT freed 2992K, 32% free 9579K/13900K, paused 10ms+2ms, total 57ms
,D/dalvikvm( 7501): WAIT_FOR_CONCURRENT_GC blocked 40ms
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "mms"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "mmsto"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/InputMethodManagerService( 2401): Got RemoteException sending setActive(false) notification to pid 7153 uid 10604
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2401): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2401): mDVFSHelper.release()
,D/elm:14132( 7501): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/CustomFrequencyManagerService( 2401): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  pkgName : ACTIVITY_RESUME_BOOSTER@8
D/elm:14132( 7501): ELMEngine.ELMEngine( context ).
D/elm:14132( 7501): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 7501): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14132( 7501): ElmAgentService : onCreate()
D/elm:14132( 7501): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 7501): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 7501): MDMBridge.getInstance()
,D/elm:14132( 7501): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 7501): MDMBridge.getAllLicenseInfoFromSDK()
,I/SELinux ( 7518): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7518):  
,D/EnterpriseDeviceManagerService( 2401): Package has changed for user 0
,I/SELinux ( 7518): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7518):  
I/SELinux ( 7518):  
,I/SELinux ( 7518): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7518): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7518): >>>>> Normal User
,E/dalvikvm( 7518): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,E/SELinux ( 7518): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/elm:14132( 7501): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
,D/dalvikvm( 2757): GC_CONCURRENT freed 2334K, 27% free 10259K/13912K, paused 7ms+3ms, total 113ms
,D/TimaKeyStoreProvider( 7518): in addTimaSignatureService
,D/elm:14132( 7501): ElmAgentService : onDestroy().
,D/TimaKeyStoreProvider( 7518): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7518): Added TimaKesytore provider
I/ActivityManager( 2401): Killing 6503:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/BackupManagerService( 2401): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 2401): removePackageParticipantsLocked: uid=10604 #1
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
D/STATUSBAR-StatusBarManagerService( 2401): sendNotification(2) - 4
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 7518): GC_CONCURRENT freed 2990K, 32% free 9578K/13892K, paused 5ms+2ms, total 44ms
,D/dalvikvm( 7518): WAIT_FOR_CONCURRENT_GC blocked 37ms
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 2401): GC_EXPLICIT freed 1356K, 72% free 25159K/86912K, paused 9ms+31ms, total 520ms
D/PackageManager( 2401): delete sourFile : 
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 7535): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7535):  
D/PackageManager( 2401): delete native library directory: 
I/ActivityManager( 2401): Killing 6423:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,D/AndroidRuntime( 7490): Shutting down VM
D/PackageManager( 2401): return delete result to caller: 1122472848
D/PackageManager( 2401): returnCode: 1
,D/dalvikvm( 7490): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 0ms+0ms, total 4ms
,I/SELinux ( 7535): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7535):  
I/SELinux ( 7535):  
,I/SELinux ( 7535): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7535): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7535): >>>>> Normal User
,E/dalvikvm( 7535): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
,E/SELinux ( 7535): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "sms"
,D/TimaKeyStoreProvider( 7535): in addTimaSignatureService
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 7535): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7535): Added TimaKesytore provider
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "smsto"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "mms"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "mmsto"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 7535): GC_CONCURRENT freed 3000K, 32% free 9570K/13896K, paused 3ms+3ms, total 26ms
,D/dalvikvm( 7535): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/PCWCLIENTTRACE_PushUtil( 6561): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6561): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6561): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6561): [onReceive] - android.intent.action.PACKAGE_REMOVED
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector( 2401): onPackageRemoved : com.test.thalitest,
D/UsbSettingsManager( 2401): clearDefaults: com.test.thalitest
,I/SA      ( 5790): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5790): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
,I/ActivityManager( 2401): Killing 6535:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/Icing.InternalIcingCorporaProvider( 6403): Updating corpora: A: com.test.thalitest, C: MAYBE
,I/SELinux ( 7553): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7553):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 13% free 9505K/10872K, paused 3ms+3ms, total 36ms
,I/SELinux ( 7553): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7553):  
I/SELinux ( 7553):  
,I/SELinux ( 7553): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,W/ApplicationsProvider( 2963): Could not fetch usage stats
W/ApplicationsProvider( 2963): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2963): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2963): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2963): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2963): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2963): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2963): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2963): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2963): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2963): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2963): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2963): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SELinux ( 7553): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7553): >>>>> Normal User
,E/dalvikvm( 7553): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 7553): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9505K/10872K, paused 2ms+3ms, total 25ms
,D/TimaKeyStoreProvider( 7553): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7553): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7553): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9505K/10872K, paused 2ms+3ms, total 25ms
,E/SQLiteLog( 6403): (10) unixWrite() gets errno : 9
,E/SQLiteLog( 6403): (10) unixWrite() gets errno : 9
,W/dalvikvm( 6403): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 6403): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 6403): Process: com.google.android.googlequicksearchbox:search, PID: 6403
E/AndroidRuntime( 6403): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AndroidRuntime( 6403): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6403): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 6403): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
E/AndroidRuntime( 6403): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
E/AndroidRuntime( 6403): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:524)
E/AndroidRuntime( 6403): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:248)
E/AndroidRuntime( 6403): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 6403): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
E/AndroidRuntime( 6403): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 6403): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 6403): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 6403): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 6403): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 6403): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 6403): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 6403): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6403): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6403): Sending signal. PID: 6403 SIG: 9
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop217.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager( 2401): Process com.google.android.googlequicksearchbox:search (pid 6403) (adj 5) has died.
D/dalvikvm( 7553): GC_CONCURRENT freed 3004K, 32% free 9572K/13900K, paused 2ms+3ms, total 23ms
D/dalvikvm( 7553): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/UserAnalysis.PlaceProvider( 7553): Create SecureDbHelper
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 7553): Create SecureDbHelper
,E/SQLiteDatabase( 7553): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7553): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7553): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteDatabase( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7553): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7553): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7553): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7553): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7553): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7553): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7553): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7553): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7553): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7553): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteOpenHelper( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7553): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7553): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7553): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7553): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7553): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7553): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7553): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7553): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7553): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7553): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7553): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 7553): Opened privacy in read-only mode
E/SQLiteDatabase( 7553): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7553): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7553): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteDatabase( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7553): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7553): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7553): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7553): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7553): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7553): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7553): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 7553): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7553): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7553): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteOpenHelper( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7553): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7553): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7553): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7553): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7553): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7553): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7553): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7553): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7553): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7553): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7553): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 7553): Opened privacy in read-only mode
E/SQLiteDatabase( 7553): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7553): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7553): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
E/SQLiteDatabase( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7553): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7553): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7553): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7553): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7553): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7553): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7553): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 7553): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 7553): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 7553): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 7553): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 7553): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 7553): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 7553): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
W/System.err( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
W/System.err( 7553): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 7553): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 7553): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 7553): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7553): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 7553): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 7553): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 7553): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 7553): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 7553): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 7553): 	at dalvik.system.NativeStart.main(Native Method)
,W/ContextImpl( 6338): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:165 android.app.ActivityThread.handleReceiver:2698 
D/RCPManager( 6417):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2401):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2401): queryAllProviders():  providerCallBack is not register for 0
E/SQLiteDatabase( 6338): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 6338): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6338): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6338): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6338): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6338): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6338): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6338): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6338): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6338): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6338): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6338): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6338): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6338): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6338): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6338): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 6338): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 6338): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6338): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6338): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6338): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 6338): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 6338): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 6338): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 6338): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 6338): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 6338): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 6338): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 6338): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 6338): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 6338): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
D/CapabilityManagerService New( 6629): Receiver Broadcast:android.intent.action.PACKAGE_REMOVED
D/CapabilityManagerService New( 6629): The package(com.test.thalitest) removed
W/System.err( 6338): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 6338): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 6338): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 6338): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 6338): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 6338): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 6338): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 6338): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6338): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6338): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 2401): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2401): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2401): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2401): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2401): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2401): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2401): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2401): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 2401): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2401): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2401): 	... 8 more
W/System.err( 2401): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2401): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2401): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2401): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2401): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2401): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2401): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2401): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 2401): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2401): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 2401): 	... 8 more
,D/MagazineService::MagazineBroadcastReceiver( 6657): [onReceive] android.intent.action.PACKAGE_REMOVED com.test.thalitest
,I/MagazineService::MagazineService( 6657): [onHandleIntent] ACTION_PACKAGE_REMOVED
D/CustomFrequencyManagerService( 2401): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  tag : ACTIVITY_RESUME_BOOSTER@8
,E/SQLiteDatabase( 6657): Failed to open database '/data/data/com.samsung.android.app.headlines/databases/card.db'.
E/SQLiteDatabase( 6657): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6657): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6657): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6657): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6657): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/SQLiteDatabase( 6657): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/SQLiteDatabase( 6657): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/SQLiteDatabase( 6657): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/SQLiteDatabase( 6657): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6657): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6657): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6657): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 6657): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,I/SELinux ( 7568): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7568):  
E/AndroidRuntime( 6657): FATAL EXCEPTION: IntentService[MagazineService::MagazineService]
E/AndroidRuntime( 6657): Process: com.samsung.android.magazine.service, PID: 6657
E/AndroidRuntime( 6657): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6657): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6657): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 6657): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 6657): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6657): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6657): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6657): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 6657): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 6657): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 6657): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 6657): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 6657): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 6657): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 6657): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/AndroidRuntime( 6657): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6657): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6657): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/AndroidRuntime( 6657): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6657): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6657): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6657): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6657): Sending signal. PID: 6657 SIG: 9
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop218.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager( 2401): Process com.samsung.android.magazine.service (pid 6657) (adj 5) has died.
,I/SELinux ( 7568): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7568):  
I/SELinux ( 7568):  
,I/SELinux ( 7568): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7568): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7568): >>>>> Normal User
,E/dalvikvm( 7568): >>>>> com.android.keychain [ userId:0 | appId:1000 ]
,E/SELinux ( 7568): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager( 2401): Waited long enough for: ServiceRecord{43ba9598 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/TimaKeyStoreProvider( 7568): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7568): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7568): Added TimaKesytore provider
,D/dalvikvm( 7568): GC_CONCURRENT freed 3013K, 32% free 9561K/13900K, paused 1ms+2ms, total 18ms
,D/dalvikvm( 7568): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/ContextImpl( 7568): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2698 
,D/KidsModeInstallReceiver( 6683): onReceive intent data =  package:com.test.thalitest
,D/KidsPlatformStub( 6683): Package not found : com.sec.android.app.kidshome
E/SQLiteDatabase( 7568): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 7568): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7568): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7568): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7568): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7568): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7568): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7568): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7568): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7568): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7568): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7568): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7568): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7568): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7568): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7568): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/SQLiteDatabase( 7568): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/SQLiteDatabase( 7568): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7568): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7568): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7568): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7568): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7568): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 7568): Process: com.android.keychain, PID: 7568
E/AndroidRuntime( 7568): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7568): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7568): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7568): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7568): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7568): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7568): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7568): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7568): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7568): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7568): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7568): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7568): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7568): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7568): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/AndroidRuntime( 7568): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/AndroidRuntime( 7568): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7568): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7568): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7568): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 7568): Sending signal. PID: 7568 SIG: 9
,E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop219.tmp: open failed: EROFS (Read-only file system)
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
W/System.err( 6721): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6721): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
W/System.err( 6721): 	at com.n7mobile.promenada2.applications.ApplicationInstallationReceiver.onReceive(SourceFile:27)
W/System.err( 6721): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 6721): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 6721): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 6721): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6721): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6721): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 6721): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 6721): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 6721): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 6721): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 6721): 	at dalvik.system.NativeStart.main(Native Method)
,I/ActivityManager( 2401): Process com.android.keychain (pid 7568) (adj 5) has died.
D/PackageBroadcastService( 3156): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 3156): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 3156): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3156): Module APK com.google.android.play.games already loaded
,E/SQLiteLog( 3156): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,I/LocationSettingsChecker( 3156): Removing dialog suppression flag for package com.test.thalitest
,E/DriveAsyncService( 3156): disk I/O error (code 3850)
E/DriveAsyncService( 3156): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 3156): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 3156): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/DriveAsyncService( 3156): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 3156): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 3156): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/DriveAsyncService( 3156): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/DriveAsyncService( 3156): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 3156): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 3156): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 3156): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 3156): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 3156): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 3156): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 3156): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 3156): 	at java.lang.Thread.run(Thread.java:841)
D/ChimeraCfgMgr( 3156): Loading module com.google.android.gms.games from APK com.google.android.play.games,
,D/ChimeraModuleLdr( 3156): Module APK com.google.android.play.games already loaded
,E/SQLiteLog( 2847): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,D/AndroidRuntime( 2847): Shutting down VM
,W/dalvikvm( 2847): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/SQLiteLog( 3156): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/AndroidRuntime( 2847): FATAL EXCEPTION: main
E/AndroidRuntime( 2847): Process: com.google.process.gapps, PID: 2847
E/AndroidRuntime( 2847): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2847): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 2847): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 2847): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 2847): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2847): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2847): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 2847): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2847): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2847): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 2847): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 2847): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2847): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2847): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2847): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 2847): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2847): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2847): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 2847): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 2847): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 2847): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 2847): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 2847): 	... 10 more
E/SQLiteDatabase( 3156): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 3156): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3156): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3156): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3156): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3156): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3156): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3156): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3156): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3156): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3156): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3156): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3156): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3156): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3156): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 31,56): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3156): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 3156): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3156): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3156): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3156): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 3156): threadid=49: thread exiting with uncaught exception (group=0x4180ac08)
,E/PhenotypeInitializer( 3156): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 3156): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 3156): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 3156): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/PhenotypeInitializer( 3156): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/PhenotypeInitializer( 3156): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 3156): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 3156): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 3156): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/PhenotypeInitializer( 3156): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/PhenotypeInitializer( 3156): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/PhenotypeInitializer( 3156): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/PhenotypeInitializer( 3156): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3156): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3156): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 3156): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 3156): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 3156): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 3156): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 3156): 	at android.os.Looper.loop(Looper.java:146)
E/PhenotypeInitializer( 3156): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop220.tmp: open failed: EROFS (Read-only file system)
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
I/Process ( 2847): Sending signal. PID: 2847 SIG: 9
,E/SQLiteLog( 3156): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDatabase( 3156): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 3156): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3156): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3156): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3156): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3156): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3156): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3156): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3156): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3156): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3156): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3156): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3156): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3156): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3156): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3156): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 3156): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 3156): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 3156): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 3156): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3156): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3156): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3156): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 3156): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 3156): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3156): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3156): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 3156): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 3156): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 3156): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 3156): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 3156): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 3156): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 3156): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 3156): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 3156): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 3156): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3156): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3156): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 3156): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 3156): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 3156): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 3156): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 3156): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3156): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 3156): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ClearPendingStateOp( 3156): Runtime exception while performing operation
E/ClearPendingStateOp( 3156): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 3156): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 3156): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/ClearPendingStateOp( 3156): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 3156): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 3156): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/ClearPendingStateOp( 3156): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
E/ClearPendingStateOp( 3156): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 3156): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 3156): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/ClearPendingStateOp( 3156): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/ClearPendingStateOp( 3156): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 3156): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 3156): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 3156): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 3156): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 3156): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 3156): 	at java.lang.Thread.run(Thread.java:841)
,W/SQLiteOpenHelper( 3156): Opened metrics.db in read-only mode
,E/AndroidRuntime( 3156): FATAL EXCEPTION: PlayGamesAsyncThread2
E/AndroidRuntime( 3156): Process: com.google.android.gms, PID: 3156
E/AndroidRuntime( 3156): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3156): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 3156): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 3156): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 3156): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 3156): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 3156): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
E/AndroidRuntime( 3156): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 3156): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 3156): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 3156): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 3156): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 3156): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 3156): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 3156): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 3156): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 3156): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 3156): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 3156): 	at java.lang.Thread.run(Thread.java:841)
D/gH_CompatibleDatabase( 3156): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 3156): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteDatabase( 5526): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5526): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5526): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5526): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5526): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5526): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5526): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5526): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5526): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5526): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5526): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5526): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5526):, 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5526): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5526): 	at com.sec.spp.push.i.d.e(Unknown Source)
E/SQLiteDatabase( 5526): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5526): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5526): 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
E/SQLiteDatabase( 5526): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5526): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5526): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 5526): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5526): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5526): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 5526): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 5526): 	at dalvik.system.NativeStart.main(Native Method)
E/SPPClientService( 5526): [d] [getAppId()] Exception with message =not an error (code 0): Could not open the database in read/write mode.
,F/ClearPendingStateOp( 3156): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 3156): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 3156): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 3156): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
F/ClearPendingStateOp( 3156): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 3156): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 3156): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
F/ClearPendingStateOp( 3156): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
F/ClearPendingStateOp( 3156): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 3156): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 3156): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
F/ClearPendingStateOp( 3156): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
F/ClearPendingStateOp( 3156): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 3156): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 3156): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 3156): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 3156): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 3156): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 3156): 	at java.lang.Thread.run(Thread.java:841)
I/ActivityManager( 2401): Process com.google.process.gapps (pid 2847) (adj 5) has died.
,E/SQLiteLog( 3156): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDatabase( 6380): Failed to open database '/data/data/com.sec.spp.push/databases/evtDb'.
E/SQLiteDatabase( 6380): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6380): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6380): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6380): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6380): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6380): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6380): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6380): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6380): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6380): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6380): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6380): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6380): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6380): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6380): 	at com.sec.spp.push.notisvc.tracking.h.b(Unknown Source)
E/SQLiteDatabase( 6380): 	at com.sec.spp.push.notisvc.tracking.g.a(Unknown Source)
E/SQLiteDatabase( 6380): 	at com.sec.spp.push.notisvc.tracking.f.a(Unknown Source)
E/SQLiteDatabase( 6380): 	at com.sec.spp.push.notisvc.tracking.a.c(Unknown Source)
E/SQLiteDatabase( 6380): 	at com.sec.spp.push.notisvc.tracking.a.a(Unknown Source)
E/SQLiteDatabase( 6380): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6380): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6380): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6380): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6380): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6380): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6380): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6380): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6380): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6380): [g] not an error (code 0): Could not open the database in read/write mode.
,E/SQLiteLog( 3156): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop221.tmp: open failed: EROFS (Read-only file system)
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
W/dalvikvm( 3156): threadid=53: thread exiting with uncaught exception (group=0x4180ac08)
I/Process ( 3156): Sending signal. PID: 3156 SIG: 9
,E/SQLiteDatabase( 6380): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 6380): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6380): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6380): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6380): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6380): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6380): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6380): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6380): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6380): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6380): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6380): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6380): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6380): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6380): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6380): 	at com.sec.spp.push.notisvc.b.b.<init>(Unknown Source)
E/SQLiteDatabase( 6380): 	at com.sec.spp.push.notisvc.b.b.a(Unknown Source)
E/SQLiteDatabase( 6380): 	at com.sec.spp.push.notisvc.registration.q.b(Unknown Source)
E/SQLiteDatabase( 6380): 	at com.sec.spp.push.notisvc.registration.q.a(Unknown Source)
E/SQLiteDatabase( 6380): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6380): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6380): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6380): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6380): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6380): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6380): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6380): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6380): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6380): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6380): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6380): [b] open fail. android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,I/SELinux ( 7598): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7598):  
I/ActivityManager( 2401): Process com.google.android.gms (pid 3156) (adj 0) has died.
,D/GAV2    ( 5618): Thread[main,5,main]: service disconnected: ComponentInfo{com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService}
,I/GAV2    ( 5618): Thread[main,5,main]: Unexpected disconnect.
,I/SELinux ( 7598): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7598):  
I/SELinux ( 7598):  
,I/SELinux ( 7598): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7598): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7598): >>>>> Normal User
,E/dalvikvm( 7598): >>>>> com.android.documentsui [ userId:0 | appId:10093 ]
,E/SELinux ( 7598): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7598): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7598): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7598): Added TimaKesytore provider
,D/dalvikvm( 7598): GC_CONCURRENT freed 3001K, 32% free 9574K/13900K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7598): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/Documents( 7598): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 7598): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 7598): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7598): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7598): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7598): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7598): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7598): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7598): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7598): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7598): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7598): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7598): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7598): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7598): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7598): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7598): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 7598): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 7598): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 7598): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/SQLiteDatabase( 7598): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 7598): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7598): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7598): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7598): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7598): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7598): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7598): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7598): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7598): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7598): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7598): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7598): Shutting down VM
,W/dalvikvm( 7598): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7598): FATAL EXCEPTION: main
E/AndroidRuntime( 7598): Process: com.android.documentsui, PID: 7598
E/AndroidRuntime( 7598): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7598): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 7598): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 7598): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7598): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7598): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7598): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7598): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7598): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7598): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7598): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7598): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7598): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7598): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7598): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7598): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7598): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7598): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7598): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7598): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7598): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7598): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7598): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7598): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7598): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7598): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7598): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 7598): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 7598): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 7598): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/AndroidRuntime( 7598): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 7598): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 7598): 	... 10 more
I/SELinux ( 7614): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7614):  
,I/SELinux ( 7618): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7618):  
,I/Process ( 7598): Sending signal. PID: 7598 SIG: 9
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop222.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager( 2401): Process com.android.documentsui (pid 7598) (adj 9) has died.
,I/SELinux ( 7614): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7614):  
I/SELinux ( 7614):  
,I/SELinux ( 7614): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7614): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7614): >>>>> Normal User
,E/dalvikvm( 7614): >>>>> com.android.externalstorage [ userId:0 | appId:10009 ]
,E/SELinux ( 7614): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 7618): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7618):  
I/SELinux ( 7618):  
,I/SELinux ( 7618): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7618): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7618): >>>>> Normal User
,E/dalvikvm( 7618): >>>>> com.google.android.gms [ userId:0 | appId:10012 ]
,E/SELinux ( 7618): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7614): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7614): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7614): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 7618): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7618): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7618): Added TimaKesytore provider
,D/dalvikvm( 7614): GC_CONCURRENT freed 2998K, 32% free 9568K/13896K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7614): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/ExternalStorage( 7614): After updating volumes, found 1 active roots
,D/dalvikvm( 7618): GC_CONCURRENT freed 2922K, 31% free 9642K/13892K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7618): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/dalvikvm( 7618): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7618): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 7618): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 7618): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 7618): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 7618): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7618): install
,I/MultiDex( 7618): MultiDexExtractor.load(/data/app/com.google.android.gms-5.apk, false)
,I/MultiDex( 7618): loading existing secondary dex files
,I/MultiDex( 7618): load found 3 secondary dex files
,I/MultiDex( 7618): install done
,I/SELinux ( 7640): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7640):  
,I/SELinux ( 7640): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7640):  
I/SELinux ( 7640):  
,I/SELinux ( 7640): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7640): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7640): >>>>> Normal User
,E/dalvikvm( 7640): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 7640): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/SELinux ( 7646): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7646):  
,D/TimaKeyStoreProvider( 7640): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7640): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7640): Added TimaKesytore provider
,I/SELinux ( 7646): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7646):  
I/SELinux ( 7646):  
,I/SELinux ( 7646): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7646): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7646): >>>>> Normal User
,E/dalvikvm( 7646): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7646): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7646): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7646): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7646): Added TimaKesytore provider
,D/dalvikvm( 7640): GC_CONCURRENT freed 2981K, 31% free 9589K/13896K, paused 4ms+2ms, total 21ms
,D/dalvikvm( 7640): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 7646): GC_CONCURRENT freed 2995K, 32% free 9574K/13896K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 7646): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/Icing.InternalIcingCorporaProvider( 7640): Updating corpora: A: com.test.thalitest, C: MAYBE
,I/SELinux ( 7671): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7671):  
,D/LocationManagerService( 2401): getProviders()=[passive]
,I/GservicesProvider( 7646): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7646): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7646): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7646): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7646): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7646): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7646): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7646): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7646): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7646): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7646): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7646): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7646): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7646): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7646): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7646): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7646): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7646): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7646): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7646): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7646): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7646): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7646): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7646): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7646): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7646): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7646): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7646): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7646): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7646): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7646): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7646): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7646): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7646): Shutting down VM
,W/dalvikvm( 7646): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7646): FATAL EXCEPTION: main
E/AndroidRuntime( 7646): Process: com.google.process.gapps, PID: 7646
E/AndroidRuntime( 7646): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7646): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7646): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7646): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7646): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7646): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7646): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7646): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7646): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7646): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7646): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7646): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7646): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7646): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7646): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7646): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7646): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7646): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7646): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7646): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7646): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7646): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7646): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7646): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7646): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7646): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7646): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7646): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7646): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7646): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7646): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7646): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7646): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7646): 	... 12 more
I/SELinux ( 7671): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7671):  
I/SELinux ( 7671):  
I/SELinux ( 7671): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/Process ( 7646): Sending signal. PID: 7646 SIG: 9
E/SELinux ( 7671): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7671): >>>>> Normal User
,E/dalvikvm( 7671): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop223.tmp: open failed: EROFS (Read-only file system)
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
E/SELinux ( 7671): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/ActivityManager( 2401): Process com.google.process.gapps (pid 7646) (adj 0) has died.
,D/TimaKeyStoreProvider( 7671): in addTimaSignatureService
W/ActivityManager( 2401): Service crashed 2 times, stopping: ServiceRecord{4314f4b0 u0 com.google.android.gms/.gcm.GcmService}
,D/TimaKeyStoreProvider( 7671): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7671): Added TimaKesytore provider
,I/SELinux ( 7688): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7688):  
,I/SELinux ( 7688): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7688):  
I/SELinux ( 7688):  
,I/SELinux ( 7688): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7688): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7688): >>>>> Normal User
,E/dalvikvm( 7688): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7688): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7688): in addTimaSignatureService
D/dalvikvm( 7671): GC_CONCURRENT freed 3007K, 32% free 9570K/13900K, paused 4ms+1ms, total 23ms
,D/dalvikvm( 7671): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/TimaKeyStoreProvider( 7688): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7688): Added TimaKesytore provider
,D/dalvikvm( 7688): GC_CONCURRENT freed 2993K, 32% free 9581K/13900K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7688): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/GservicesProvider( 7688): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7688): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7688): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7688): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7688): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7688): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7688): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7688): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7688): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7688): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7688): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7688): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7688): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7688): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7688): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7688): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7688): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7688): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7688): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7688): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7688): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7688): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7688): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7688): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7688): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7688): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7688): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7688): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7688): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7688): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7688): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7688): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7688): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7688): Shutting down VM
,W/dalvikvm( 7688): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7688): FATAL EXCEPTION: main
E/AndroidRuntime( 7688): Process: com.google.process.gapps, PID: 7688
E/AndroidRuntime( 7688): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7688): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7688): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7688): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7688): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7688): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7688): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7688): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7688): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7688): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7688): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7688): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7688): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7688): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7688): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7688): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7688): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7688): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7688): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7688): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7688): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7688): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7688): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7688): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7688): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7688): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7688): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7688): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7688): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7688): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7688): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7688): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7688): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7688): 	... 12 more
W/ActivityManager( 2401): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2401): Killing 7688:com.google.process.gapps/u0a12 (adj 0): crash
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /d,ata/system/dropbox/drop224.tmp: open failed: EROFS (Read-only file system)
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
W/ActivityManager( 2401): Unable to launch app com.google.android.gsf/10012 for provider com.google.settings: launching app became null
W/ActivityManager( 2401): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
W/ActivityManager( 2401): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7640): Failed to find provider info for com.google.settings
E/ActivityThread( 7671): Failed to find provider info for com.google.android.gsf.gservices
E/ActivityThread( 7618): Failed to find provider info for com.google.android.gsf.gservices
,I/SELinux ( 7706): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7706):  
,I/SELinux ( 7706): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7706):  
I/SELinux ( 7706):  
,I/SELinux ( 7706): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7706): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7706): >>>>> Normal User
,E/dalvikvm( 7706): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7706): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7706): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7706): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7706): Added TimaKesytore provider
,D/dalvikvm( 7706): GC_CONCURRENT freed 2990K, 32% free 9581K/13900K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7706): WAIT_FOR_CONCURRENT_GC blocked 13ms
,I/GservicesProvider( 7706): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7706): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7706): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7706): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7706): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7706): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7706): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7706): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7706): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7706): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7706): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7706): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7706): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7706): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7706): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7706): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7706): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7706): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7706): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7706): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7706): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7706): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7706): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7706): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7706): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7706): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7706): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7706): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7706): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7706): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7706): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7706): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7706): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7706): Shutting down VM
,W/dalvikvm( 7706): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,I/Process ( 7706): Sending signal. PID: 7706 SIG: 9
E/AndroidRuntime( 7706): FATAL EXCEPTION: main
E/AndroidRuntime( 7706): Process: com.google.process.gapps, PID: 7706
E/AndroidRuntime( 7706): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7706): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7706): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7706): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7706): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7706): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7706): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7706): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7706): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7706): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7706): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7706): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7706): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7706): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7706): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7706): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7706): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7706): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7706): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7706): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7706): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7706): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7706): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7706): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7706): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7706): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7706): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7706): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7706): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7706): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7706): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7706): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7706): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7706): 	... 12 more
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop225.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2401): 	at java.io.FileOutputStream.<i,nit>(FileOutputStream.java:88)
E/DropBoxManagerService( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2401): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2401): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2401): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2401): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2401): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2401): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2401): 	... 5 more
,I/ActivityManager( 2401): Process com.google.process.gapps (pid 7706) (adj 0) has died.
,I/SELinux ( 7721): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7721):  
,I/SELinux ( 7721): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7721):  
I/SELinux ( 7721):  
,I/SELinux ( 7721): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7721): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7721): >>>>> Normal User
,E/dalvikvm( 7721): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7721): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7721): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7721): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7721): Added TimaKesytore provider
,D/dalvikvm( 7721): GC_CONCURRENT freed 2977K, 31% free 9591K/13896K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7721): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7721): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7721): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7721): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7721): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7721): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7721): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7721): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7721): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7721): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7721): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7721): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7721): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7721): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7721): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7721): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7721): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7721): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7721): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7721): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7721): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7721): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7721): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7721): Shutting down VM
,W/dalvikvm( 7721): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7721): FATAL EXCEPTION: main
E/AndroidRuntime( 7721): Process: com.google.process.gapps, PID: 7721
E/AndroidRuntime( 7721): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7721): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7721): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7721): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7721): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7721): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7721): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7721): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7721): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7721): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7721): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7721): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7721): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7721): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7721): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7721): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7721): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7721): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7721): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7721): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7721): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7721): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7721): 	... 12 more
W/ActivityManager( 2401): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2401): Killing 7721:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2401): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launc,hing app became null
D/dalvikvm( 7618): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7618): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7618): VFY: replacing opcode 0x62 at 0x000a
W/ActivityManager( 2401): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7671): Failed to find provider info for com.google.android.gsf.gservices
E/ActivityThread( 7618): Failed to find provider info for com.google.android.gsf.gservices
,E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop226.tmp: open failed: EROFS (Read-only file system)
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
D/dalvikvm( 7618): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7618): VFY: unable to resolve instance field 36
D/dalvikvm( 7618): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 7618): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7618): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7618): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 7618): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 7618): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 7618): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42296718
,I/ActivityManager( 2401): Killing 5684:com.android.mms/u0a49 (adj 15): empty #43
D/dalvikvm( 7618): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42296718
D/dalvikvm( 7618): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42296718, skipping init
D/dalvikvm( 7618): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42296718
D/dalvikvm( 7618): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42296718
V/JNIHelp ( 7618): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/CountryDetector( 2401): No listener is left
,D/dalvikvm( 7618): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42296718
,D/dalvikvm( 7618): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x42296718
D/dalvikvm( 7618): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42296718
,D/dalvikvm( 7618): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42296718
,I/ProviderInstaller( 7618): Installed default security provider GmsCore_OpenSSL
,I/SELinux ( 7736): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7736):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 44K, 13% free 9505K/10872K, paused 2ms+3ms, total 27ms
,I/SELinux ( 7736): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7736):  
I/SELinux ( 7736):  
,I/SELinux ( 7736): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7736): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7736): >>>>> Normal User
,E/dalvikvm( 7736): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7736): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9505K/10872K, paused 2ms+3ms, total 25ms
,D/TimaKeyStoreProvider( 7736): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7736): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7736): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9505K/10872K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 7736): GC_CONCURRENT freed 2988K, 32% free 9585K/13900K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7736): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/ActivityManager( 2401): Waited long enough for: ServiceRecord{464c0ac0 u0 com.sec.spp.push/.PushClientService}
,I/GservicesProvider( 7736): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7736): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7736): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7736): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7736): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7736): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7736): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7736): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7736): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7736): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7736): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7736): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7736): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7736): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7736): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7736): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7736): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7736): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7736): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7736): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7736): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7736): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7736): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7736): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7736): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7736): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7736): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7736): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7736): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7736): Shutting down VM
,W/dalvikvm( 7736): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7736): FATAL EXCEPTION: main
E/AndroidRuntime( 7736): Process: com.google.process.gapps, PID: 7736
E/AndroidRuntime( 7736): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7736): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7736): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7736): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7736): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7736): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7736): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7736): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7736): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7736): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7736): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7736): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7736): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7736): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7736): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7736): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7736): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7736): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7736): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7736): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7736): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7736): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7736): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7736): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7736): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7736): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7736): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7736): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7736): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7736): 	... 12 more
,I/Process ( 7736): Sending signal. PID: 7736 SIG: 9
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop227.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager( 2401): Process com.google.process.gapps (pid 7736) (adj 0) has died.
,I/SELinux ( 7751): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7751):  
,I/SELinux ( 7751): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7751):  
I/SELinux ( 7751):  
,I/SELinux ( 7751): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7751): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7751): >>>>> Normal User
,E/dalvikvm( 7751): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7751): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7751): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7751): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7751): Added TimaKesytore provider
,D/dalvikvm( 7751): GC_CONCURRENT freed 2990K, 32% free 9581K/13896K, paused 3ms+2ms, total 19ms
,D/dalvikvm( 7751): WAIT_FOR_CONCURRENT_GC blocked 10ms
,I/GservicesProvider( 7751): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7751): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7751): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7751): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7751): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7751): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7751): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7751): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7751): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7751): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7751): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7751): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7751): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7751): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7751): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7751): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7751): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7751): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7751): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7751): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7751): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7751): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7751): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7751): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7751): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7751): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7751): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7751): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7751): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7751): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7751): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7751): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7751): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7751): Shutting down VM
,W/dalvikvm( 7751): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7751): FATAL EXCEPTION: main
E/AndroidRuntime( 7751): Process: com.google.process.gapps, PID: 7751
E/AndroidRuntime( 7751): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7751): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7751): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7751): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7751): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7751): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7751): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7751): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7751): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7751): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7751): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7751): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7751): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7751): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7751): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7751): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7751): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7751): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7751): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7751): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7751): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7751): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7751): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7751): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7751): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7751): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7751): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7751): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7751): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7751): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7751): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7751): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7751): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7751): 	... 12 more
W/ActivityManager( 2401): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2401): Killing 7751:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2401): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launc,hing app became null
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop228.tmp: open failed: EROFS (Read-only file system)
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
,E/ActivityThread( 7618): Failed to find provider info for com.google.android.gsf.gservices
W/NativeLibraryUtils( 7618): Failed to open lock file
W/NativeLibraryUtils( 7618): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7618): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/NativeLibraryUtils( 7618): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:118)
W/NativeLibraryUtils( 7618): 	at com.google.android.gms.common.util.ay.b(SourceFile:325)
W/NativeLibraryUtils( 7618): 	at com.google.android.gms.common.app.b.run(SourceFile:209)
W/NativeLibraryUtils( 7618): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7618): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7618): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/NativeLibraryUtils( 7618): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/NativeLibraryUtils( 7618): 	... 3 more
,I/dalvikvm( 7618): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.service.w.a
W/dalvikvm( 7618): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 7618): VFY: replacing opcode 0x6e at 0x002b
,I/SELinux ( 7769): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7769):  
,I/SELinux ( 7769): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7769):  
I/SELinux ( 7769):  
,I/SELinux ( 7769): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7769): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7769): >>>>> Normal User
,E/dalvikvm( 7769): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7769): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7769): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7769): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7769): Added TimaKesytore provider
,D/dalvikvm( 7769): GC_CONCURRENT freed 2987K, 32% free 9581K/13896K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 7769): WAIT_FOR_CONCURRENT_GC blocked 9ms
,I/GservicesProvider( 7769): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7769): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7769): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7769): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7769): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7769): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7769): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7769): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7769): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7769): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7769): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7769): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7769): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7769): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7769): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7769): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7769): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7769): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7769): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7769): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7769): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7769): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7769): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7769): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7769): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7769): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7769): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7769): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7769): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7769): Shutting down VM
,W/dalvikvm( 7769): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7769): FATAL EXCEPTION: main
E/AndroidRuntime( 7769): Process: com.google.process.gapps, PID: 7769
E/AndroidRuntime( 7769): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7769): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7769): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7769): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7769): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7769): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7769): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7769): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7769): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7769): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7769): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7769): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7769): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7769): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7769): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7769): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7769): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7769): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7769): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7769): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7769): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7769): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7769): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7769): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7769): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7769): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7769): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7769): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7769): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7769): 	... 12 more
,I/Process ( 7769): Sending signal. PID: 7769 SIG: 9
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop229.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager( 2401): Process com.google.process.gapps (pid 7769) (adj 0) has died.
,I/SELinux ( 7784): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7784):  
,I/SELinux ( 7784): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7784):  
I/SELinux ( 7784):  
,I/SELinux ( 7784): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7784): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7784): >>>>> Normal User
,E/dalvikvm( 7784): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7784): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7784): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7784): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7784): Added TimaKesytore provider
,D/dalvikvm( 7784): GC_CONCURRENT freed 2991K, 32% free 9581K/13900K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 7784): WAIT_FOR_CONCURRENT_GC blocked 13ms
,I/GservicesProvider( 7784): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7784): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7784): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7784): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7784): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7784): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7784): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7784): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7784): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7784): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7784): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7784): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7784): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7784): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7784): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7784): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7784): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7784): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7784): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7784): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7784): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7784): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7784): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7784): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7784): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7784): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7784): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7784): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7784): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7784): Shutting down VM
,W/dalvikvm( 7784): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7784): FATAL EXCEPTION: main
E/AndroidRuntime( 7784): Process: com.google.process.gapps, PID: 7784
E/AndroidRuntime( 7784): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7784): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7784): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7784): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7784): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7784): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7784): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7784): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7784): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7784): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7784): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7784): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7784): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7784): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7784): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7784): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7784): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7784): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7784): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7784): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7784): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7784): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7784): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7784): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7784): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7784): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7784): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7784): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7784): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7784): 	... 12 more
W/ActivityManager( 2401): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2401): Killing 7784:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2401): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launc,hing app became null
E/ActivityThread( 7618): Failed to find provider info for com.google.android.gsf.gservices
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop230.tmp: open failed: EROFS (Read-only file system)
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
,D/dalvikvm( 7618): Trying to load lib /data/app-lib/com.google.android.gms-5/libAppDataSearch.so 0x42296718
,D/dalvikvm( 7618): Added shared lib /data/app-lib/com.google.android.gms-5/libAppDataSearch.so 0x42296718
,D/dalvikvm( 7618): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libAppDataSearch.so 0x42296718, skipping init
,I/dalvikvm( 7618): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 7618): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7618): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 7618): Could not find method android.app.AlarmManager.setExactAndAllowWhileIdle, referenced from method com.google.android.gms.common.stats.b.a
W/dalvikvm( 7618): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,D/dalvikvm( 7618): VFY: replacing opcode 0x6e at 0x0010
,I/SELinux ( 7802): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7802):  
,I/SELinux ( 7802): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7802):  
I/SELinux ( 7802):  
,I/SELinux ( 7802): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7802): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7802): >>>>> Normal User
,E/dalvikvm( 7802): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7802): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7802): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7802): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7802): Added TimaKesytore provider
,D/dalvikvm( 7802): GC_CONCURRENT freed 2995K, 32% free 9574K/13896K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7802): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7802): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7802): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7802): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7802): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7802): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7802): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7802): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7802): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7802): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7802): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7802): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7802): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7802): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7802): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7802): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7802): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7802): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7802): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7802): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7802): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7802): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7802): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7802): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7802): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7802): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7802): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7802): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7802): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7802): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7802): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7802): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7802): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7802): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7802): Shutting down VM
,W/dalvikvm( 7802): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7802): FATAL EXCEPTION: main
E/AndroidRuntime( 7802): Process: com.google.process.gapps, PID: 7802
E/AndroidRuntime( 7802): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7802): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7802): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7802): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7802): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7802): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7802): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7802): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7802): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7802): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7802): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7802): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7802): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7802): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7802): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7802): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7802): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7802): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7802): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7802): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7802): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7802): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7802): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7802): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7802): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7802): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7802): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7802): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7802): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7802): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7802): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7802): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7802): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7802): 	... 12 more
,I/Process ( 7802): Sending signal. PID: 7802 SIG: 9
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop231.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager( 2401): Process com.google.process.gapps (pid 7802) (adj 0) has died.
,I/SELinux ( 7819): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7819):  

```
