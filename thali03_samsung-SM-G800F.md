#### Test 5497026140aeaf4_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
,E/Watchdog( 2418): !@Sync 8
--------- beginning of /dev/log/main
D/AndroidRuntime( 7200): 
D/AndroidRuntime( 7200): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7200): CheckJNI is OFF
D/AndroidRuntime( 7200): setted country_code = Poland
D/AndroidRuntime( 7200): setted countryiso_code = PL
D/AndroidRuntime( 7200): setted sales_code = PLS
D/AndroidRuntime( 7200): readGMSProperty: start
D/AndroidRuntime( 7200): readGMSProperty: already setted!!
D/AndroidRuntime( 7200): readGMSProperty: end
D/AndroidRuntime( 7200): addProductProperty: start
D/dalvikvm( 7200): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7200): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7200): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7200): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7200): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7200): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7200): failed to load memtrack module: -2
D/dalvikvm( 7200): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7200): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2418): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2418): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  pkgName : ACTIVITY_RESUME_BOOSTER@4
I/SurfaceFlinger( 1921): id=18 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1921): id=19 createSurf (16x16),-1 flag=20004, EimLayer
W/ActivityManager( 2418): mDVFSHelper.acquire()
I/SELinux ( 7227): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7227):  
D/PointerIcon( 2418): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2418): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2418): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2418): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7200): Shutting down VM
D/dalvikvm( 7200): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 7227): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7227):  
I/SELinux ( 7227):  
I/SELinux ( 7227): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7227): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7227): >>>>> Normal User
E/dalvikvm( 7227): >>>>> com.test.thalitest [ userId:0 | appId:10601 ]
E/SELinux ( 7227): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7227): in addTimaSignatureService
D/TimaKeyStoreProvider( 7227): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7227): Added TimaKesytore provider
V/WindowManager( 2418): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SQLiteSecureOpenHelper( 4180): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4180): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=9 Removed Mauncher (8/10)
I/SurfaceFlinger( 1921): id=9 Removed Mauncher (-2/10)
D/Launcher( 2781): onTrimMemory. Level: 20
D/dalvikvm( 7227): GC_CONCURRENT freed 3000K, 32% free 9570K/14072K, paused 2ms+1ms, total 19ms
D/dalvikvm( 7227): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7227): Binding Chromium to the background looper Looper (main, tid 1) {422cb240}
I/chromium( 7227): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7227): Initializing chromium process, renderers=0
,W/chromium( 7227): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7227): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7227): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7227): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7227): Mali API Version : 401
,I/Mali    ( 7227): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7227): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7227): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7227): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7227): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7227): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7227): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2582): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2418): tr p:7227,o:f
,W/dalvikvm( 7227): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7227): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7227): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7227): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7227): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7227): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7227): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7227): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7227): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7227): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7227): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7227): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7227): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2582): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2418): semi p:7227,o:f
,I/SurfaceFlinger( 1921): id=20 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2418): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2418): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2418): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2418): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2418): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2418): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7227): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7227): Enabling debug mode 0
,W/AwContents( 7227): nativeOnDraw failed; clearing to background color.
W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7227): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2418): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/CustomFrequencyManagerService( 2418): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2418): mDVFSHelper.release()
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 310, Delta = 0
,D/JsMessageQueue( 7227): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7227): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422c3c10
,D/dalvikvm( 7227): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422c3c10
D/jxcore_app_log( 7227): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027588352
,D/JX-Cordova( 7227): jxcore cordova android initializing
,D/dalvikvm( 7227): GC_CONCURRENT freed 1303K, 20% free 11341K/14140K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 7227): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 7227): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/CustomFrequencyManagerService( 2418): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  tag : ACTIVITY_RESUME_BOOSTER@8
D/dalvikvm( 7227): GC_CONCURRENT freed 1916K, 19% free 14951K/18380K, paused 3ms+2ms, total 46ms
D/dalvikvm( 7227): WAIT_FOR_CONCURRENT_GC blocked 25ms
D/dalvikvm( 7227): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/dalvikvm( 7227): GC_FOR_ALLOC freed 5358K, 31% free 16238K/23304K, paused 50ms, total 50ms
,D/dalvikvm( 7227): GC_CONCURRENT freed 6718K, 32% free 17690K/25928K, paused 3ms+12ms, total 85ms
,D/dalvikvm( 7227): WAIT_FOR_CONCURRENT_GC blocked 43ms
,D/dalvikvm( 7227): WAIT_FOR_CONCURRENT_GC blocked 43ms
,D/dalvikvm( 7227): GC_FOR_ALLOC freed 1332K, 33% free 17451K/25928K, paused 49ms, total 49ms
,I/dalvikvm-heap( 7227): Grow heap (frag case) to 22.019MB for 3688532-byte allocation
,D/dalvikvm( 7227): GC_FOR_ALLOC freed 2437K, 37% free 18616K/29532K, paused 48ms, total 48ms
,W/jxcore-log( 7227): Initializing JXcore engine
,W/jxcore-log( 7227): JXcore engine is ready
,W/jxcore-log( 7227): Starting JXcore engine
,W/jxcore-log( 7227): Platform android
W/jxcore-log( 7227): 
,W/jxcore-log( 7227): Process ARCH arm
W/jxcore-log( 7227): 
,I/jxcore-log( 7227): JXcore Cordova bridge is ready!
I/jxcore-log( 7227): 
,W/jxcore-log( 7227): JXcore engine is started
,I/chromium( 7227): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7227): Toggling radios to true
I/jxcore-log( 7227): 
,D/BluetoothAdapter( 7227): enable(): BT is already enabled..!
,I/WifiManager( 7227): packageName : com.test.thalitest
,I/WifiManager( 7227): setWifiEnabled : true
,I/WifiService( 2418): setWifiEnabled: true pid=7227, uid=10601
,W/ActivityManager( 2418): Permission Denial: getCurrentUser() from pid=7227, uid=10601 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2418): Failed getting userId using ActivityManagerNative
W/WifiService( 2418): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7227, uid=10601 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2418): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2418): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2418): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2418): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2418): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2418): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2418): disconnect: pid=7227, uid=10601
I/jxcore-log( 7227): Radios toggled
I/jxcore-log( 7227): 
I/wpa_supplicant( 3967): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3967): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/wpa_supplicant( 3967): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3967): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3967): First Scan Start
W/Settings( 2418): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine( 2418): ignore requestNetworkTransitionWakelock airplane:true
,I/wpa_supplicant( 3967): Scan requested (ret=0) - scan timeout 30 seconds
D/WifiP2pService( 2418): InactiveState{ what=143375 }
D/WifiP2pService( 2418): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
D/ConnectivityService( 2418): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2418): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2418): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2418): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2418): net.tcp.delack.default not found in system default properties
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2418): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
I/wpa_supplicant( 3967): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3967): Skip scan - already scanning
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/WifiP2pService( 2418): InactiveState{ what=143375 }
,D/WifiP2pService( 2418): P2pEnabledState{ what=143375 }
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3
D/ConnectivityService( 2418): Attempting to switch to mobile
,I/SELinux ( 7275): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7275):  
D/ConnectivityService( 2418): Attempting to switch to BLUETOOTH_TETHER
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,E/WifiStateMachine( 2418): Error! unhandled message{ when=-45ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2418): Error! unhandled message{ when=-43ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1
,E/WifiStateMachine( 2418): Error! unhandled message{ when=-6ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1916): RTNETLINK answers: No such process
I/SELinux ( 7275): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7275):  
I/SELinux ( 7275):  
,I/SELinux ( 7275): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
,E/SELinux ( 7275): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7275): >>>>> Normal User
,E/dalvikvm( 7275): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7275): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,W/NetworkManagementService( 2418): route cmd failed: 
W/NetworkManagementService( 2418): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2418): '
W/NetworkManagementService( 2418): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2418): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2418): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2418): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2418): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2418): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2418): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2418): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2418): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2418): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2418): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2418): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2418): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1
,D/TimaKeyStoreProvider( 7275): in addTimaSignatureService
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 7275): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7275): Added TimaKesytore provider
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/NetUtils( 2418): android_net_utils_resetConnections in env=0x78617a58 clazz=0x61a00001 iface=wlan0 mask=0x3
D/ConnectivityService( 2418): resetConnections(wlan0, 3)
,E/SPPClientService( 5591): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5591): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5591): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5591): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5591): [b] ResponseMap empty
D/dalvikvm( 7275): GC_CONCURRENT freed 2997K, 32% free 9574K/14068K, paused 3ms+2ms, total 36ms
,D/dalvikvm( 7275): WAIT_FOR_CONCURRENT_GC blocked 32ms
,V/NativeCrypto( 2848): Read error: ssl=0x7bb8eef0: I/O error during system call, Connection timed out
,V/NativeCrypto( 2848): SSL shutdown failed: ssl=0x7bb8eef0: I/O error during system call, Broken pipe
,I/System.out( 7275): Inside WakeupProvider
,I/System.out( 7275): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 7275): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7275): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7275): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/ConnectivityService( 2418): handleInetConditionChange: no active default network - ignore
V/NetworkStats( 2418): updateIfacesLocked()
,V/NetworkStats( 2418): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
V/NetworkStats( 2418): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
V/NetworkStats( 2418): performPollLocked() took 30ms
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NearbySettings( 4754): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4754): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4754): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4754): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4754): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4754): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4754): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2418): Killing 6217:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/DialogFlow( 7275): initQueue()
,D/NearbySettings( 4754): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4754): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4754): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4754): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4754): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 4754): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4754): MountReceiver.mPrefHandler - 7002
,I/ApplicationPolicy( 2418): updateDataUsageMap
,D/Tethering( 2418): Tethering got CONNECTIVITY_ACTION
D/Tethering( 2418): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2418): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2418): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4788): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/PCWCLIENTTRACE_PushUtil( 6632): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6632): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6632): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6632): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6632): noConnectivity : true
,I/SELinux ( 7304): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7304):  
,D/libgps  ( 2418): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7304): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7304):  
I/SELinux ( 7304):  
,I/SELinux ( 7304): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7304): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7304): >>>>> Normal User
,E/dalvikvm( 7304): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7304): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/wpa_supplicant( 3967): nl80211: Received scan results (7 BSSes)
,I/wpa_supplicant( 3967): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3967): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/TimaKeyStoreProvider( 7304): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7304): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7304): Added TimaKesytore provider
,D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
D/Tethering( 2418): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3967): Associated with C0.AA.48
,D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3967): freq(2412) increment count 2
I/wpa_supplicant( 3967): meet head of list.
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3967): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3967): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
,D/WifiNative( 2418): callSECApiVoid - ID [50]
,D/dalvikvm( 7304): GC_CONCURRENT freed 3001K, 32% free 9568K/14068K, paused 5ms+2ms, total 42ms
,D/dalvikvm( 7304): WAIT_FOR_CONCURRENT_GC blocked 37ms
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/ActivityManager( 2418): Killing 6287:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/WifiP2pService( 2418): InactiveState{ what=143375 }
,D/WifiP2pService( 2418): P2pEnabledState{ what=143375 }
,I/SELinux ( 7318): Function: selinux_android_load_priority [0], There is no sepolicy file.
,I/SELinux ( 7318):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 14% free 9503K/11048K, paused 5ms+4ms, total 39ms
,I/SELinux ( 7318): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7318):  
I/SELinux ( 7318):  
,I/SELinux ( 7318): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7318): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7318): >>>>> Normal User
,E/dalvikvm( 7318): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7318): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9503K/11048K, paused 2ms+4ms, total 32ms
,D/TimaKeyStoreProvider( 7318): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7318): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7318): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9503K/11048K, paused 2ms+4ms, total 35ms
,D/dalvikvm( 7318): GC_CONCURRENT freed 3015K, 33% free 9556K/14072K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 7318): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/dhcpcd  ( 7330): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7330): bssid match
,I/ActivityManager( 2418): Killing 6339:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7337): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7337):  
,I/SELinux ( 7337): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7337):  
I/SELinux ( 7337):  
,I/SELinux ( 7337): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7337): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7337): >>>>> Normal User
,E/dalvikvm( 7337): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7337): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7337): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7337): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7337): Added TimaKesytore provider
,D/dalvikvm( 7337): GC_CONCURRENT freed 2997K, 32% free 9570K/14068K, paused 2ms+1ms, total 23ms
,D/dalvikvm( 7337): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/KLMS-2.3.201 : ( 7337): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7337): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452278512991
,I/KLMS-2.3.201 : ( 7337): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2418): Killing 6356:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7349): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7349):  
D/libgps  ( 2418): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2418): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2418): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2418): agps_ril_update_network_availability: Waiting for IPC connection...
,I/SELinux ( 7349): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7349):  
I/SELinux ( 7349):  
,I/SELinux ( 7349): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7349): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7349): >>>>> Normal User
,E/dalvikvm( 7349): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7349): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7349): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7349): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7349): Added TimaKesytore provider
,D/dalvikvm( 7349): GC_CONCURRENT freed 3000K, 32% free 9570K/14072K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 7349): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/SO_AGENT( 7349): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7349): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5856): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5856): [BDLM] already registered in spp
,I/SA      ( 5856): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5856): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5856): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5856): [OR] == isSIMCardReady false ==
I/SA      ( 5856): [SCU] == networkStateCheck == false
,I/SA      ( 5856): [OR] onReceive END
I/ActivityManager( 2418): Killing 6373:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): Phone number locator feature is dsiabled
,I/SELinux ( 7361): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7361):  
,I/SELinux ( 7361): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7361):  
I/SELinux ( 7361):  
,I/SELinux ( 7361): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7361): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7361): >>>>> Normal User
,E/dalvikvm( 7361): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7361): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7361): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7361): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7361): Added TimaKesytore provider
,D/dalvikvm( 7361): GC_CONCURRENT freed 2997K, 32% free 9571K/14072K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7361): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/sCloudBackupApp( 7361): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7361): Other Intent
I/ActivityManager( 2418): Killing 6433:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,I/SELinux ( 7374): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7374):  
,I/SELinux ( 7374): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7374):  
I/SELinux ( 7374):  
,I/SELinux ( 7374): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7374): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7374): >>>>> Normal User
,E/dalvikvm( 7374): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7374): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7374): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7374): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7374): Added TimaKesytore provider
,D/dalvikvm( 7374): GC_CONCURRENT freed 3011K, 33% free 9554K/14068K, paused 2ms+2ms, total 19ms
,D/dalvikvm( 7374): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/com.samsung.app( 7374): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/com.samsung.app( 7374): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7374): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
D/com.samsung.app( 7374): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7374): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7374): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5387): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7374): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5387): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7374): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5387): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7374): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7374): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2418): Killing 5640:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/Headlines( 5924): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5924): getCountryCode(): countryCode = PL
,D/Headlines( 5924): Breath.onCreate
,D/Headlines( 5924): Breath timer started. interval : 30000
,I/SELinux ( 7387): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7387):  
D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4380, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): stay LED for fully charged
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
V/AlarmManager( 2418): waitForAlarm result :8
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/Headlines( 5924): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5924): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5924): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5924): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5924): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5924): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5924): requestUpdateNewsWelcomeCard !!! no welcome card
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/SELinux ( 7387): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7387):  
I/SELinux ( 7387):  
I/SELinux ( 7387): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7387): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7387): >>>>> Normal User
E/dalvikvm( 7387): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
E/SELinux ( 7387): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7387): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7387): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7387): Added TimaKesytore provider
,D/dalvikvm( 7387): GC_CONCURRENT freed 2998K, 32% free 9572K/14068K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 7387): WAIT_FOR_CONCURRENT_GC blocked 22ms
,V/WebViewChromium( 7387): Binding Chromium to the background looper Looper (main, tid 1) {422c8028}
,I/chromium( 7387): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7387): Initializing chromium process, renderers=0
,W/chromium( 7387): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7387): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7387): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7387): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7387): Mali API Version : 401
,I/Mali    ( 7387): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,W/GAV2    ( 7387): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7387): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/libgps  ( 2418): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2418): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2418): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/NSApplication( 7387): Starting up...
,I/iu.Environment( 5988): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.SyncManager( 5988): SYNC; picasa accounts
,D/QuickConnect[1.1][2] ( 5190): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5190): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5190): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422d85d8
,I/iu.UploadsManager( 5988): num queued entries: 0
,I/SELinux ( 7432): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7432):  
,I/iu.UploadsManager( 5988): num updated entries: 0
,I/iu.SyncManager( 5988): NEXT; no task
,I/SELinux ( 7432): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7432):  
I/SELinux ( 7432):  
,I/SELinux ( 7432): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7432): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7432): >>>>> Normal User
,E/dalvikvm( 7432): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7432): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7432): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7432): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7432): Added TimaKesytore provider
,D/dalvikvm( 7432): GC_CONCURRENT freed 2984K, 32% free 9582K/14064K, paused 4ms+1ms, total 39ms
,D/dalvikvm( 7432): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/WifiP2pService( 2418): InactiveState{ what=143375 }
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/WifiP2pService( 2418): P2pEnabledState{ what=143375 }
D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/WifiStateMachine( 2418): VerifyingLinkState enter
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2418): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2418): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2418): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2418): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2418): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
D/ConnectivityService( 2418): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2418): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2418): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2418): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,I/SELinux ( 7473): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7473):  
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,I/ActivityManager( 2418): Killing 6321:com.sec.phone/1001 (adj 15): empty #43
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,I/SELinux ( 7473): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7473):  
I/SELinux ( 7473):  
,I/SELinux ( 7473): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7473): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7473): >>>>> Normal User
,E/dalvikvm( 7473): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7473): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
V/NetworkStats( 2418): updateIfacesLocked()
,V/NetworkStats( 2418): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
V/NetworkStats( 2418): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/SELinux ( 7492): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7492):  
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
V/NetworkStats( 2418): performPollLocked() took 25ms
,D/TimaKeyStoreProvider( 7473): in addTimaSignatureService
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/TimaKeyStoreProvider( 7473): Cannot add TimaSignature Service, License check Failed
,W/ActivityManager( 2418): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/ActivityThread( 7473): Added TimaKesytore provider
,I/SELinux ( 7492): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7492):  
I/SELinux ( 7492):  
,I/SELinux ( 7492): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7492): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,I/ActivityManager( 2418): Killing 6392:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
E/dalvikvm( 7492): >>>>> Normal User
E/dalvikvm( 7492): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
E/SELinux ( 7492): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7492): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7492): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7492): Added TimaKesytore provider
,D/dalvikvm( 7473): GC_CONCURRENT freed 3006K, 33% free 9566K/14072K, paused 3ms+1ms, total 23ms
,D/dalvikvm( 7473): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/BadgeProvider( 7473): onCreate
,D/BadgeProvider( 7473): DatabaseHelper
,D/dalvikvm( 7492): GC_CONCURRENT freed 2999K, 32% free 9570K/14072K, paused 2ms+4ms, total 26ms
,D/dalvikvm( 7492): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/BadgeProvider( 7473): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7473): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7473): sendNotify, [notify] : null
D/BadgeProvider( 7473): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7473): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7473): update, [UpdateCount] : 1
,D/Launcher.Model( 2781): reloadBadges entered.
,D/hcjo    ( 6009): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 6009): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6009): exit::IDLE
,D/InitializeManagerStateMachine( 6009): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 6009): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6009): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6009): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6009): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6009): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6009): entry::SUCCESS
,D/hcjo    ( 6009): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6009): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6009): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6009): exit::SUCCESS
,D/InitializeManagerStateMachine( 6009): entry::IDLE
,E/SPPClientService( 5591): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5591): [SystemStateMoniter] Current Time : 268231
,E/SPPClientService( 5591): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5591): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 4754): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4754): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4754): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 4754): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4754): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4754): MountReceiver.onReceive - Keep current state
,D/Headlines( 5924): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5924): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,E/SPPClientService( 5591): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5591): [a] [ConnectionManager] Connection is already disconnected.
,D/Headlines( 5924): Breath 1352 latestRequest time : 1452278513698 current time : 1452278515051
,D/NearbySettings( 4754): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4754): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5591): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/NearbySettings( 4754): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4754): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4754): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 4754): DMSUtil.isNetworkConnected - P2P: IDLE
,E/SPPClientService( 5591): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/NearbySettings( 4754): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4754): MountReceiver.onReceive - Keep current state
I/ActivityManager( 2418): Killing 6034:com.android.calendar/u0a144 (adj 15): empty #43
,E/SPPClientService( 5591): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5591): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5591): [g] getNetMCC return empty string
,D/Tethering( 2418): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2418): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2418): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4788): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/libgps  ( 2418): agps_ril_update_network_state: Waiting for IPC connection...
,D/dalvikvm( 2418): GC_EXPLICIT freed 3170K, 72% free 25104K/87996K, paused 10ms+22ms, total 205ms
,I/SurfaceFlinger( 1921): id=21 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 2418): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2418
D/NearbySettings( 4754): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 4754): MountReceiver.onReceive - Keep current state
,I/PCWCLIENTTRACE_PushUtil( 6632): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6632): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6632): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6632): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.3.201 : ( 7337): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7337): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452278515634
,I/KLMS-2.3.201 : ( 7337): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/LocationTagReadyService( 3466): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
,D/SO_AGENT( 7349): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7349): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 3594): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7519): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7519):  
,I/SELinux ( 7519): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7519):  
I/SELinux ( 7519):  
,I/SELinux ( 7519): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7519): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7519): >>>>> Normal User
,E/dalvikvm( 7519): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7519): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 7529): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7529):  
,D/TimaKeyStoreProvider( 7519): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7519): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7519): Added TimaKesytore provider
,I/SELinux ( 7529): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7529):  
I/SELinux ( 7529):  
,I/SELinux ( 7529): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7529): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7529): >>>>> Normal User
,E/dalvikvm( 7529): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
W/WifiP2pStateTracker( 2418): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,E/SELinux ( 7529): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/ConnectivityService( 2418): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2418):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
D/ConnectivityService( 2418): handleConnectivityChange: setting default proxy info 
D/ConnectivityService( 2418): updateSourceRoutes : no source routing conditions
,I/dalvikvm( 7318): Total arena pages for JIT: 11
,I/dalvikvm( 7318): Total arena pages for JIT: 12
I/dalvikvm( 7318): Total arena pages for JIT: 13
I/dalvikvm( 7318): Total arena pages for JIT: 14
,I/dalvikvm( 7318): Total arena pages for JIT: 15
I/dalvikvm( 7318): Total arena pages for JIT: 16
,I/dalvikvm( 7318): Total arena pages for JIT: 17
,I/SA      ( 5856): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5856): [BDLM] already registered in spp
I/SA      ( 5856): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
I/SA      ( 5856): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/TimaKeyStoreProvider( 7529): in addTimaSignatureService
I/SA      ( 5856): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5856): [OR] == isSIMCardReady false ==
,I/SA      ( 5856): [SCU] == networkStateCheck == true
I/SA      ( 5856): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5856): isChinaCountryCode : false
,I/SA      ( 5856): [OR] == networkStateCheck true ==
,D/TimaKeyStoreProvider( 7529): Cannot add TimaSignature Service, License check Failed
,I/SA      ( 5856): [OR] GetMyCountryZoneTask
D/ActivityThread( 7529): Added TimaKesytore provider
,I/SA      ( 5856): [OR] onReceive END
,D/dalvikvm( 7519): GC_FOR_ALLOC freed 3013K, 33% free 9557K/14072K, paused 18ms, total 18ms
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7361): Other Intent
,D/dalvikvm( 7519): GC_CONCURRENT freed 257K, 18% free 9554K/11564K, paused 2ms+2ms, total 17ms
,I/SA      ( 5856): [SRS] prepareGetMyCountryZone
,I/SA      ( 5856): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5856): [SSP] query invoked
,D/com.samsung.app( 7374): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/dalvikvm( 7529): GC_CONCURRENT freed 2999K, 32% free 9574K/14072K, paused 4ms+2ms, total 25ms
,D/dalvikvm( 7529): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/com.samsung.app( 7374): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/SA      ( 5856): [TPMU] GetMccFromDB : null
I/SA      ( 5856): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5856): [TPM] isNoProxy(default) : true
,I/SA      ( 5856): [RC New] Execute method=[GET] start
D/Headlines( 5924): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5924): getCountryCode(): countryCode = PL
D/PackageManager( 2418): [MSG] WRITE_PACKAGE_RESTRICTIONS
,V/KVNProvider( 7529): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7529): getFindoCursor query string : 
D/Headlines( 5924): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5924): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5924): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5924): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5924): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5924): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5924): requestUpdateNewsWelcomeCard !!! no welcome card
,V/KVNProvider( 7529): getTagSearchCursor() tagSearchCursor count : 0
,I/iu.Environment( 5988): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 5988): num queued entries: 0
,I/iu.UploadsManager( 5988): num updated entries: 0
,D/QuickConnect[1.1][2] ( 5190): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/iu.SyncManager( 5988): NEXT; no task
I/QuickConnect[1.1][2] ( 5190): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5190): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422d85d8
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/hcjo    ( 6009): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 6009): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6009): exit::IDLE
,D/InitializeManagerStateMachine( 6009): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 6009): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6009): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6009): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6009): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6009): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6009): entry::SUCCESS
,D/hcjo    ( 6009): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/System.out( 7318): Thread-639(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
D/hcjo    ( 6009): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6009): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6009): exit::SUCCESS
,D/InitializeManagerStateMachine( 6009): entry::IDLE
,I/System.out( 7318): Thread-639(ApacheHTTPLog):isShipBuild true
,I/System.out( 7318): Thread-639(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/SPPClientService( 5591): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5591): [SystemStateMoniter] Current Time : 269390
,E/SPPClientService( 5591): [SystemStateMoniter] No Connect : false
,I/System.out( 7318): AsyncTask #1 calls detatch()
,D/dalvikvm( 5591): GC_CONCURRENT freed 2007K, 26% free 10433K/14052K, paused 12ms+3ms, total 60ms
,W/System.err( 7318): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7318): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
,W/System.err( 7318): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7318): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7318): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 7318): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 7318): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7318): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 7318): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7318): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7318): Caused by: java.lang.NullPointerException
,W/System.err( 7318): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7318): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7318): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7318): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7318): 	... 8 more
,I/ActivityManager( 2418): Killing 6204:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/libgps  ( 2418): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2418): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2418): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2418): agps_ril_update_network_availability: Waiting for IPC connection...
,I/SA      ( 5856): [RC New] [v2liruge] api execute + 679
,I/SA      ( 5856): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5856): AsyncTask #2 calls detatch()
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 20
I/SA      ( 5856): [TPMU] getNetworkMcc : 
,I/SA      ( 5856): [SCU] saveMccToPreferece Start
,I/SA      ( 5856): [SCU] RegionMCC : 260
,I/SA      ( 5856): [SSP] query invoked
,I/SA      ( 5856): [TPMU] GetMccFromDB : null
,I/SA      ( 5856): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5856): [SCU] saveMccToPreferece End
,I/SA      ( 5856): [RC New] executeRequest [v2liruge] end. 703
I/SA      ( 5856): [RC New] Execute end
,I/SA      ( 5856): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5856): [OR] GetMyCountryZoneTask Success
,E/SPPClientService( 5591): [b] __InitReply__
,D/libgps  ( 2418): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2418): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2418): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
E/WifiStateMachine( 2418): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger( 1921): id=21 Removed Uoast (10/11)
,I/SurfaceFlinger( 1921): id=21 Removed Uoast (-2/11)
I/ActivityManager( 2418): Killing 6239:com.google.android.music:main/u0a125 (adj 15): empty #43
D/PowerManagerService( 2418): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2418) eventTime = 271883
D/PowerManagerService( 2418): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2418 (0x0)
D/PowerManagerService( 2418): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2418, ws=WorkSource{1000}) (elapsedTime=3271)
,I/GAV2    ( 7387): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6632): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6632): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6632): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6632): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6632): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6632): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6632): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6632): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6632): [ensureRegistration] - No Samsung account
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PreloadUpdateManagerStateMachine( 6009): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6009): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6009): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 6009): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6009): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 6009): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6009): entry::IDLE
,D/CaptivePortalTracker( 2418): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker( 2418): Checking http://216.58.209.46/generate_204
D/ConnectivityService( 2418): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2418): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker( 2418): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2418): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2418): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2418): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/jxcore-log( 7227): Test app app.js loaded
I/jxcore-log( 7227): 
,I/chromium( 7227): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 7227): --= Surplus to requirements =--
I/jxcore-log( 7227): 
I/jxcore-log( 7227): ****TEST TOOK:  ms ****
I/jxcore-log( 7227): 
,I/jxcore-log( 7227): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7227): 
,D/PreloadUpdateManagerStateMachine( 6009): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6009): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6009): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 6009): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6009): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 6009): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6009): entry::IDLE
,D/AndroidRuntime( 7565): 
D/AndroidRuntime( 7565): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7565): CheckJNI is OFF
,D/AndroidRuntime( 7565): setted country_code = Poland
,D/AndroidRuntime( 7565): setted countryiso_code = PL
D/AndroidRuntime( 7565): setted sales_code = PLS
D/AndroidRuntime( 7565): readGMSProperty: start
,D/AndroidRuntime( 7565): readGMSProperty: already setted!!
D/AndroidRuntime( 7565): readGMSProperty: end
,D/AndroidRuntime( 7565): addProductProperty: start
,D/dalvikvm( 7565): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 7565): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 7565): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7565): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 7565): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,E/memtrack( 7565): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 7565): failed to load memtrack module: -2
,D/dalvikvm( 7565): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,D/AndroidRuntime( 7565): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 2418): START PACKAGE DELETE: observer{1110416912}
D/PackageManager( 2418): pkg{<packageName>}
D/PackageManager( 2418): user{0}
,D/ApplicationPolicy( 2418): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2418): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService( 2418): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2418): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager( 2418): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManager( 2418): !@killApplicatoin: 10601, uninstall pkg
,I/ActivityManager( 2418): Killing 7227:com.test.thalitest/u0a601 (adj 0): stop com.test.thalitest
,D/PointerIcon( 2418): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2418): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2418): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
D/PointerIcon( 2418): setHoveringSpenCustomIcon IconType is same.1
,I/SurfaceFlinger( 1921): id=19 Removed EimLayer (5/10)
,I/SurfaceFlinger( 1921): id=19 Removed EimLayer (-2/10)
I/SurfaceFlinger( 1921): id=18 Removed EimLayer (4/9)
,I/SurfaceFlinger( 1921): id=18 Removed EimLayer (-2/9)
,V/WindowManager( 2418): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/Launcher( 2781): onRestart, Launcher: 1110415104
I/SurfaceFlinger( 1921): id=20 Removed NainActivit (6/8)
D/Launcher( 2781): onStart, Launcher: 1110415104
D/Launcher.HomeView( 2781): onStart
,I/SurfaceFlinger( 1921): id=20 Removed NainActivit (-2/8)
I/WindowState( 2418): WIN DEATH: Window{430e54c0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger( 1921): id=22 createSurf (720x1280),1 flag=4, Mauncher
D/STATUSBAR-StatusBarManagerService( 2418): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2418): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2418): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2418): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2418): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2418): setHoveringSpenCustomIcon IconType is same.1
,D/StatusBarManagerService( 2418): tr p:2781,o:f
,D/StatusBarManagerService( 2418): semi p:2781,o:f
D/PhoneStatusBar( 2582): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/PhoneStatusBar( 2582): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 2418): Got RemoteException sending setActive(false) notification to pid 7227 uid 10601
,W/PackageSettings( 2418): Skipping PackageSetting{42d6e8b8 com.example.hello/10600} due to missing metadata
,D/PackageManager( 2418): checkUidPermission - Execution time: 154 ms
,D/PackageManager( 2418): checkUidPermission - Execution time: 111 ms
D/PackageManager( 2418): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10601, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/dalvikvm( 6474): GC_EXPLICIT freed 2469K, 30% free 9885K/14064K, paused 6ms+7ms, total 95ms
,D/PackageManager( 2418): queryIntentReceivers - Execution time: 109 ms
,D/dalvikvm( 3311): GC_EXPLICIT freed 445K, 25% free 12397K/16320K, paused 10ms+36ms, total 159ms
,D/dalvikvm( 2952): GC_EXPLICIT freed 1468K, 29% free 10037K/14068K, paused 12ms+7ms, total 119ms
,D/dalvikvm( 6792): GC_EXPLICIT freed 160K, 31% free 9959K/14304K, paused 5ms+5ms, total 139ms
D/PackageManager( 2418): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10601, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/FPMS_FingerprintManagerService( 2602): onReceive: android.intent.action.PACKAGE_REMOVED
,E/SamsungIME( 2991): mOCRHelper is null
,D/QuickConnect[1.1][2] ( 5190): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2418):   Scheme: "sms"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 7580): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7580):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 14% free 9503K/11048K, paused 4ms+3ms, total 42ms
,I/SELinux ( 7580): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7580):  
I/SELinux ( 7580):  
,I/SELinux ( 7580): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7580): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7580): >>>>> Normal User
,E/dalvikvm( 7580): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 7580): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2418):   Scheme: "smsto"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9503K/11048K, paused 2ms+4ms, total 25ms
,W/GeofencerStateMachine( 2737): Ignoring removeGeofence because network location is disabled.
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9503K/11048K, paused 2ms+3ms, total 25ms
,D/TimaKeyStoreProvider( 7580): in addTimaSignatureService
,I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2418):   Scheme: "mms"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 7580): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7580): Added TimaKesytore provider
,D/dalvikvm( 2418): GC_EXPLICIT freed 2333K, 72% free 24933K/87996K, paused 13ms+22ms, total 307ms
,I/InputReader( 2418): Reconfiguring input devices.  changes=0x00000010
,D/PackageManager( 2418): queryIntentReceivers - Execution time: 131 ms
,I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2418):   Scheme: "mmsto"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/RegisteredServicesCache( 2759): empty dynamic service
,I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2418):   Scheme: "sms"
,I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService( 2418): PackageReceiver onReceive()
,I/HarmonyEASService( 2418): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2418):   Scheme: "smsto"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 7580): GC_CONCURRENT freed 3004K, 32% free 9566K/14068K, paused 4ms+2ms, total 38ms
,D/dalvikvm( 7580): WAIT_FOR_CONCURRENT_GC blocked 29ms
,I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2418):   Scheme: "mms"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/elm:14132( 7580): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14132( 7580): ELMEngine.ELMEngine( context ).
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2418):   Scheme: "mmsto"
,D/elm:14132( 7580): MDMBridge.setEnterpriseBridge()
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/elm:14132( 7580): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14132( 7580): ElmAgentService : onCreate()
,I/SELinux ( 7593): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7593):  
,D/elm:14132( 7580): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14132( 7580): MainReceiver.listeningToPackageRemoved()
,D/elm:14132( 7580): MDMBridge.getInstance()
,D/elm:14132( 7580): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 7580): MDMBridge.getAllLicenseInfoFromSDK()
,D/EnterpriseDeviceManagerService( 2418): Package has changed for user 0
,D/dalvikvm( 2759): GC_CONCURRENT freed 2337K, 28% free 10255K/14088K, paused 14ms+4ms, total 120ms
I/SELinux ( 7593): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7593):  
I/SELinux ( 7593):  
,I/SELinux ( 7593): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7593): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7593): >>>>> Normal User
,E/dalvikvm( 7593): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,E/SELinux ( 7593): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/elm:14132( 7580): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
,D/elm:14132( 7580): ElmAgentService : onDestroy().
I/ActivityManager( 2418): Killing 6573:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7593): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7593): Cannot add TimaSignature Service, License check Failed
,D/AmoledAdjustTimer( 2418): prevTemp = 286, currTemp = 288, prevStep = 4, currStep = 4
D/ActivityThread( 7593): Added TimaKesytore provider
,D/dalvikvm( 7593): GC_CONCURRENT freed 2997K, 32% free 9573K/14068K, paused 2ms+1ms, total 21ms
,D/dalvikvm( 7593): WAIT_FOR_CONCURRENT_GC blocked 18ms
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 2418): GC_EXPLICIT freed 1129K, 72% free 24947K/87996K, paused 8ms+38ms, total 512ms
D/PackageManager( 2418): delete sourFile : 
,D/BackupManagerService( 2418): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 2418): removePackageParticipantsLocked: uid=10601 #1
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 2418): delete native library directory: 
,D/AndroidRuntime( 7565): Shutting down VM
D/PackageManager( 2418): return delete result to caller: 1110416912
D/PackageManager( 2418): returnCode: 1
,D/dalvikvm( 7565): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+0ms, total 5ms
,I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2418):   Scheme: "sms"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 7608): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7608):  
I/ActivityManager( 2418): Killing 6494:com.google.android.partnersetup/u0a14 (adj 15): empty #43
I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2418):   Scheme: "smsto"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2418):   Scheme: "mms"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 7608): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7608):  
I/SELinux ( 7608):  
,I/SELinux ( 7608): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7608): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7608): >>>>> Normal User
,E/dalvikvm( 7608): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
,E/SELinux ( 7608): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/PackageManager( 2418):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2418):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2418):   Scheme: "mmsto"
I/PackageManager( 2418): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 7608): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7608): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7608): Added TimaKesytore provider
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 7608): GC_CONCURRENT freed 2994K, 32% free 9568K/14064K, paused 3ms+2ms, total 41ms
,D/dalvikvm( 7608): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PCWCLIENTTRACE_PushUtil( 6632): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6632): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6632): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6632): [onReceive] - android.intent.action.PACKAGE_REMOVED
,W/ApplicationsProvider( 2952): Could not fetch usage stats
W/ApplicationsProvider( 2952): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2952): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2952): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2952): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2952): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2952): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2952): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2952): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2952): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2952): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2952): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2952): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SA      ( 5856): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5856): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SQLiteLog( 6049): (3850) statement aborts at 35: [DELETE FROM app_registry WHERE package_name=? AND plugin_id=? AND sync_status != 170004 AND sync_status = 170002] disk I/O error
,W/dalvikvm( 6049): threadid=12: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 6049): FATAL EXCEPTION: IntentService[HandleAppDataService]
E/AndroidRuntime( 6049): Process: com.sec.android.app.shealth, PID: 6049
E/AndroidRuntime( 6049): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6049): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6049): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 6049): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6049): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6049): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 6049): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericDelete(BaseContentProvider.java:486)
E/AndroidRuntime( 6049): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.delete(BaseContentProvider.java:441)
E/AndroidRuntime( 6049): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6049): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6049): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.deleteAppRegistryData(AppRegistryDbManagerWithProvider.java:459)
E/AndroidRuntime( 6049): 	at com.sec.android.app.shealth.service.HandleAppDataService.onHandleIntent(HandleAppDataService.java:56)
E/AndroidRuntime( 6049): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6049): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6049): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6049): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SharedPreferencesImpl( 3594): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
I/Icing.InternalIcingCorporaProvider( 6474): Updating corpora: A: com.test.thalitest, C: MAYBE
E/SQLiteLog( 6474): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 6474): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,I/Process ( 6049): Sending signal. PID: 6049 SIG: 9
,E/DropBoxManagerService( 2418): Can't write: system_app_crash
E/DropBoxManagerService( 2418): java.io.FileNotFoundException: /data/system/dropbox/drop219.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2418): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2418): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2418): 	... 5 more
,E/AndroidRuntime( 6474): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 6474): Process: com.google.android.googlequicksearchbox:search, PID: 6474
E/AndroidRuntime( 6474): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6474): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6474): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 6474): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6474): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6474): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 6474): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 6474): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:171)
E/AndroidRuntime( 6474): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 6474): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
E/AndroidRuntime( 6474): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 6474): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 6474): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 6474): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 6474): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 6474): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 6474): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 6474): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6474): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6474): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6474): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SELinux ( 7630): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7630):  
I/ActivityManager( 2418): Process com.sec.android.app.shealth (pid 6049) (adj 5) has died.
I/Process ( 6474): Sending signal. PID: 6474 SIG: 9
E/DropBoxManagerService( 2418): Can't write: system_app_crash
E/DropBoxManagerService( 2418): java.io.FileNotFoundException: /data/system/dropbox/drop220.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2418): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2418): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2418): 	... 5 more
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 2418): Process com.google.android.googlequicksearchbox:search (pid 6474) (adj 5) has died.
W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SELinux ( 7630): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7630):  
I/SELinux ( 7630):  
,I/SELinux ( 7630): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7630): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7630): >>>>> Normal User
,E/dalvikvm( 7630): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SELinux ( 7630): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2418): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector( 2418): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2418): clearDefaults: com.test.thalitest
,W/AtomicFile( 2418): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
,W/AppWidgetServiceImpl( 2418): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/TimaKeyStoreProvider( 7630): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7630): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7630): Added TimaKesytore provider
,D/dalvikvm( 7630): GC_CONCURRENT freed 2997K, 32% free 9570K/14068K, paused 5ms+2ms, total 30ms
,D/dalvikvm( 7630): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/UserAnalysis.PlaceProvider( 7630): Create SecureDbHelper
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 7630): Create SecureDbHelper
,E/SQLiteDatabase( 7630): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7630): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7630): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7630): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7630): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7630): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7630): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteDatabase( 7630): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7630): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7630): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7630): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7630): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7630): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7630): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7630): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7630): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7630): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7630): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7630): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7630): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7630): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7630): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7630): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7630): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7630): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7630): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7630): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7630): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7630): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7630): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7630): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7630): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7630): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteOpenHelper( 7630): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7630): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7630): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7630): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7630): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7630): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7630): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7630): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7630): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7630): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7630): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7630): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 7630): Opened privacy in read-only mode
E/SQLiteDatabase( 7630): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7630): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7630): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7630): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7630): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7630): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7630): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteDatabase( 7630): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7630): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7630): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7630): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7630): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7630): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7630): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7630): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7630): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7630): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7630): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7630): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 7630): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7630): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7630): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7630): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7630): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7630): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7630): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7630): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7630): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7630): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7630): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7630): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7630): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7630): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteOpenHelper( 7630): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7630): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7630): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7630): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7630): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7630): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7630): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7630): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7630): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7630): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7630): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7630): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 7630): Opened privacy in read-only mode
E/SQLiteDatabase( 7630): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7630): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7630): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7630): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7630): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7630): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7630): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
E/SQLiteDatabase( 7630): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7630): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7630): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7630): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7630): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7630): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7630): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7630): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7630): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7630): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7630): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7630): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 7630): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 7630): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 7630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 7630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 7630): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 7630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 7630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 7630): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 7630): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 7630): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 7630): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 7630): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7630): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7630): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 7630): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 7630): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
W/System.err( 7630): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
W/System.err( 7630): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 7630): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 7630): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 7630): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7630): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 7630): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 7630): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 7630): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 7630): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 7630): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 7630): 	at dalvik.system.NativeStart.main(Native Method)
W/ContextImpl( 6406): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:165 android.app.ActivityThread.handleReceiver:2698 
I/ActivityManager( 2418): Waited long enough for: ServiceRecord{43125848 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
D/RCPManager( 6488):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2418):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2418): queryAllProviders():  providerCallBack is not register for 0
D/CapabilityManagerService New( 6701): Receiver Broadcast:android.intent.action.PACKAGE_REMOVED
E/SQLiteDatabase( 6406): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 6406): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6406): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6406): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6406): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6406): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6406): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6406): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6406): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6406): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6406): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6406): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6406): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6406): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6406): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6406): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 6406): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 6406): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6406): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6406): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6406): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/CapabilityManagerService New( 6701): The package(com.test.thalitest) removed
W/System.err( 6406): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 6406): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 6406): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 6406): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 6406): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 6406): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 6406): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 6406): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 6406): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 2418): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 6406): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 6406): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 6406): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 6406): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 6406): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2418): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2418): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 6406): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 2418): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2418): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 6406): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 2418): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2418): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 6406): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 6406): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6406): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6406): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 2418): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2418): 	... 8 more
W/System.err( 2418): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
,W/System.err( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
,W/System.err( 2418): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2418): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2418): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2418): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2418): 	at android.os.Binder.execTransact(Binder.java:404)
,W/System.err( 2418): 	at dalvik.system.NativeStart.run(Native Method)
,W/System.err( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
,W/System.err( 2418): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
,W/System.err( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 2418): 	... 8 more
,D/MagazineService::MagazineBroadcastReceiver( 6728): [onReceive] android.intent.action.PACKAGE_REMOVED com.test.thalitest
,I/MagazineService::MagazineService( 6728): [onHandleIntent] ACTION_PACKAGE_REMOVED
,I/SELinux ( 7645): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7645):  
,E/SQLiteDatabase( 6728): Failed to open database '/data/data/com.samsung.android.app.headlines/databases/card.db'.
E/SQLiteDatabase( 6728): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6728): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6728): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6728): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6728): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6728): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6728): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6728): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6728): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6728): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6728): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/SQLiteDatabase( 6728): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/SQLiteDatabase( 6728): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/SQLiteDatabase( 6728): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/SQLiteDatabase( 6728): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6728): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6728): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6728): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 6728): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 6728): FATAL EXCEPTION: IntentService[MagazineService::MagazineService]
E/AndroidRuntime( 6728): Process: com.samsung.android.magazine.service, PID: 6728
E/AndroidRuntime( 6728): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6728): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 6728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 6728): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6728): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 6728): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 6728): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 6728): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 6728): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 6728): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 6728): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 6728): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/AndroidRuntime( 6728): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6728): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6728): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/AndroidRuntime( 6728): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6728): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6728): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6728): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6728): Sending signal. PID: 6728 SIG: 9
E/DropBoxManagerService( 2418): Can't write: system_app_crash
E/DropBoxManagerService( 2418): java.io.FileNotFoundException: /data/system/dropbox/drop221.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2418): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2418): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2418): 	... 5 more
,I/ActivityManager( 2418): Process com.samsung.android.magazine.service (pid 6728) (adj 5) has died.
,I/SELinux ( 7645): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7645):  
I/SELinux ( 7645):  
,I/SELinux ( 7645): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7645): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7645): >>>>> Normal User
,E/dalvikvm( 7645): >>>>> com.android.keychain [ userId:0 | appId:1000 ]
,E/SELinux ( 7645): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7645): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7645): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7645): Added TimaKesytore provider
,D/dalvikvm( 7645): GC_CONCURRENT freed 3018K, 33% free 9556K/14072K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 7645): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/ContextImpl( 7645): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2698 
,E/SQLiteDatabase( 7645): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 7645): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7645): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7645): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7645): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7645): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7645): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7645): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7645): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7645): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7645): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7645): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7645): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7645): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7645): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7645): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/SQLiteDatabase( 7645): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/SQLiteDatabase( 7645): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7645): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7645): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7645): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7645): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,D/KidsModeInstallReceiver( 6754): onReceive intent data =  package:com.test.thalitest
,E/AndroidRuntime( 7645): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 7645): Process: com.android.keychain, PID: 7645
E/AndroidRuntime( 7645): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7645): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7645): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7645): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7645): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7645): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7645): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7645): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7645): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7645): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7645): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7645): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7645): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7645): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7645): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/AndroidRuntime( 7645): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/AndroidRuntime( 7645): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7645): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7645): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7645): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/KidsPlatformStub( 6754): Package not found : com.sec.android.app.kidshome
,E/DropBoxManagerService( 2418): Can't write: system_app_crash
E/DropBoxManagerService( 2418): java.io.FileNotFoundException: /data/system/dropbox/drop222.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2418): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2418): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2418): 	... 5 more
,I/Process ( 7645): Sending signal. PID: 7645 SIG: 9
,W/System.err( 6792): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6792): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
W/System.err( 6792): 	at com.n7mobile.promenada2.applications.ApplicationInstallationReceiver.onReceive(SourceFile:27)
W/System.err( 6792): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 6792): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
,W/System.err( 6792): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
,W/System.err( 6792): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6792): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6792): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 6792): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 6792): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 6792): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 6792): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 6792): 	at dalvik.system.NativeStart.main(Native Method)
,D/PackageBroadcastService( 3311): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 3311): Clearing selected account for com.test.thalitest
I/ActivityManager( 2418): Process com.android.keychain (pid 7645) (adj 5) has died.
,E/SQLiteLog( 3311): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/ChimeraCfgMgr( 3311): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3311): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 3311): Removing dialog suppression flag for package com.test.thalitest
,E/DriveAsyncService( 3311): disk I/O error (code 3850)
E/DriveAsyncService( 3311): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 3311): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 3311): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/DriveAsyncService( 3311): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 3311): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 3311): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/DriveAsyncService( 3311): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/DriveAsyncService( 3311): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 3311): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 3311): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 3311): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 3311): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 3311): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 3311): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 3311): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 3311): 	at java.lang.Thread.run(Thread.java:841)
,D/ChimeraCfgMgr( 3311): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3311): Module APK com.google.android.play.games already loaded
,E/SQLiteLog( 2848): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 2848): Shutting down VM
,W/dalvikvm( 2848): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/SQLiteLog( 3311): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/AndroidRuntime( 2848): FATAL EXCEPTION: main
E/AndroidRuntime( 2848): Process: com.google.process.gapps, PID: 2848
E/AndroidRuntime( 2848): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2848): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 2848): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 2848): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 2848): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2848): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2848): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 2848): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2848): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2848): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 2848): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 2848): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2848): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2848): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2848): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 2848): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2848): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2848): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 2848): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 2848): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 2848): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 2848): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 2848): 	... 10 more
E/SQLiteLog( 3311): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/ClearPendingStateOp( 3311): Runtime exception while performing operation
E/ClearPendingStateOp( 3311): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 3311): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 3311): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/ClearPendingStateOp( 3311): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 3311): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 3311): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/ClearPendingStateOp( 3311): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
E/ClearPendingStateOp( 3311): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 3311): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 3311): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/ClearPendingStateOp( 3311): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/ClearPendingStateOp( 3311): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 3311): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 3311): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingState,Op( 3311): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 3311): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 3311): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 3311): 	at java.lang.Thread.run(Thread.java:841)
W/dalvikvm( 3311): threadid=51: thread exiting with uncaught exception (group=0x4180ac08)
F/ClearPendingStateOp( 3311): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 3311): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 3311): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 3311): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
F/ClearPendingStateOp( 3311): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 3311): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 3311): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
F/ClearPendingStateOp( 3311): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
F/ClearPendingStateOp( 3311): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 3311): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 3311): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
F/ClearPendingStateOp( 3311): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
F/ClearPendingStateOp( 3311): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 3311): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 3311): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 3311): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 3311): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 3311): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 3311): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 3311): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 3311): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3311): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3311): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3311): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3311): 	at, android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3311): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 3311): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3311): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3311): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3311): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 3311): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 3311): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 3311): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 3311): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/PhenotypeInitializer( 3311): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/PhenotypeInitializer( 3311): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 3311): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 3311): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 3311): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/PhenotypeInitializer( 3311): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/PhenotypeInitializer( 3311): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/PhenotypeInitializer( 3311): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/PhenotypeInitializer( 3311): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3311): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3311): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 3311): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 3311): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 3311): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 3311): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 3311): 	at android.os.Looper.loop(Looper.java:146)
E/PhenotypeInitializer( 3311): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 3311): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 3311): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3311): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3311): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3311): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3311): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 3311): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 3311): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 3311): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 3311): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3311): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3311): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3311): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2418): Can't write: system_app_crash
E/DropBoxManagerService( 2418): java.io.FileNotFoundException: /data/system/dropbox/drop223.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2418): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2418): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2418): 	... 5 more
I/Process ( 2848): Sending signal. PID: 2848 SIG: 9
E/SQLiteOpenHelper( 3311): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 3311): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3311): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3311): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 3311): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 3311): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 3311): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 3311): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 3311): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 3311): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 3311): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 3311): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 3311): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 3311): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3311): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3311): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 3311): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 3311): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 3311): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 3311): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 3311): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3311): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 3311): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 3311): FATAL EXCEPTION: PlayGamesAsyncThread2
E/AndroidRuntime( 3311): Process: com.google.android.gms, PID: 3311
E/AndroidRuntime( 3311): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3311): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 3311): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 3311): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 3311): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 3311): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 3311): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
E/AndroidRuntime( 3311): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 3311): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 3311): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 3311): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 3311): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 3311): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 3311): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 3311): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 3311): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 3311): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 3311): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 3311): 	at java.lang.Thread.run(Thread.java:841)
E/DropBoxManagerService( 2418): Can't write: system_app_wtf
E/DropBoxManagerService( 2418): java.io.FileNotFoundException: /data/system/dropbox/drop224.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2418): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2418): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2418): 	... 5 more
W/SQLiteOpenHelper( 3311): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 3311): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 3311): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteDatabase( 5591): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5591): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5591): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5591): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5591): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5591): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5591): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5591): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5591): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5591): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5591): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5591): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5591): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5591): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5591): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5591): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5591): 	at com.sec.spp.push.i.d.e(Unknown Source)
E/SQLiteDatabase( 5591): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5591): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5591): 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
E/SQLiteDatabase( 5591): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5591): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5591): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 5591): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5591): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5591): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 5591): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 5591): 	at dalvik.system.NativeStart.main(Native Method)
E/SPPClientService( 5591): [d] [getAppId()] Exception with message =not an error (code 0): Could not open the database in read/write mode.
I/Icing   ( 3311): doRemovePackageData com.test.thalitest
E/SQLiteDatabase( 6450): Failed to open database '/data/data/com.sec.spp.push/databases/evtDb'.
E/SQLiteDatabase( 6450): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6450): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6450): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6450): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6450): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6450): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6450): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6450): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6450): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6450): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6450): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6450): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6450): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6450): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6450): 	at com.sec.spp.push.notisvc.tracking.h.b(Unknown Source)
E/SQLiteDatabase( 6450): 	at com.sec.spp.push.notisvc.tracking.g.a(Unknown Source)
E/SQLiteDatabase( 6450): 	at com.sec.spp.push.notisvc.tracking.f.a(Unknown Source)
E/SQLiteDatabase( 6450): 	at com.sec.spp.push.notisvc.tracking.a.c(Unknown Source)
E/SQLiteDatabase( 6450): 	at com.sec.spp.push.notisvc.tracking.a.a(Unknown Source)
E/SQLiteDatabase( 6450): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6450): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6450): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6450): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6450): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6450): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6450): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6450): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6450): 	at dalvik.system.NativeStart.main(Native Method)
E/LNoti   ( 6450): [g] not an error (code 0): Could not open the database in read/write mode.
E/SQLiteLog( 3311): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 3311): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
E/SQLiteLog( 3311): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/gH_CompatibleDatabase( 3311): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 3311): threadid=50: thread exiting with uncaught exception (group=0x4180ac08)
I/Process ( 3311): Sending signal. PID: 3311 SIG: 9
I/SELinux ( 7674): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7674):  
I/ActivityManager( 2418): Process com.google.process.gapps (pid 2848) (adj 5) has died.
E/SQLiteDatabase( 6450): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 6450): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6450): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6450): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6450): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6450): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6450): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6450): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6450): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6450): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6450): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6450): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6450): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6450): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6450): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6450): 	at com.sec.spp.push.notisvc.b.b.<init>(Unknown Source)
E/SQLiteDatabase( 6450): 	at com.sec.spp.push.notisvc.b.b.a(Unknown Source)
E/SQLiteDatabase( 6450): 	at com.sec.spp.push.notisvc.registration.q.b(Unknown Source)
E/SQLiteDatabase( 6450): 	at com.sec.spp.push.notisvc.registration.q.a(Unknown Source)
E/SQLiteDatabase( 6450): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6450): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6450): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6450): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6450): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6450): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6450): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6450): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6450): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6450): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6450): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6450): [b] open fail. android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,I/ActivityManager( 2418): Process com.google.android.gms (pid 3311) (adj 0) has died.
,D/GAV2    ( 5683): Thread[main,5,main]: service disconnected: ComponentInfo{com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService}
,D/PowerManagerService( 2418): [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'Icing' (uid=10012, pid=3311, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=70)
I/GAV2    ( 5683): Thread[main,5,main]: Unexpected disconnect.
,I/SELinux ( 7674): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7674):  
I/SELinux ( 7674):  
,I/SELinux ( 7674): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7674): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7674): >>>>> Normal User
,E/dalvikvm( 7674): >>>>> com.android.documentsui [ userId:0 | appId:10093 ]
,E/SELinux ( 7674): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7674): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7674): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7674): Added TimaKesytore provider
,D/dalvikvm( 7674): GC_CONCURRENT freed 3016K, 33% free 9558K/14072K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 7674): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/Documents( 7674): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 7674): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 7674): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7674): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 7674): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 7674): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 7674): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/SQLiteDatabase( 7674): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 7674): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7674): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7674): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7674): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7674): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7674): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7674): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7674): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7674): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7674): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7674): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7674): Shutting down VM
,W/dalvikvm( 7674): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7674): FATAL EXCEPTION: main
E/AndroidRuntime( 7674): Process: com.android.documentsui, PID: 7674
E/AndroidRuntime( 7674): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7674): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 7674): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 7674): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7674): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7674): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7674): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7674): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7674): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7674): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7674): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7674): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7674): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7674): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 7674): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 7674): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 7674): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/AndroidRuntime( 7674): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 7674): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 7674): 	... 10 more
I/SELinux ( 7691): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7691):  
,I/SELinux ( 7695): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7695):  
,I/Process ( 7674): Sending signal. PID: 7674 SIG: 9
E/DropBoxManagerService( 2418): Can't write: system_app_crash
E/DropBoxManagerService( 2418): java.io.FileNotFoundException: /data/system/dropbox/drop225.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2418): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2418): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2418): 	... 5 more
,I/ActivityManager( 2418): Process com.android.documentsui (pid 7674) (adj 9) has died.
,I/SELinux ( 7700): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7700):  
I/SELinux ( 7691): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7691):  
I/SELinux ( 7691):  
,I/SELinux ( 7691): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7691): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7691): >>>>> Normal User
,E/dalvikvm( 7691): >>>>> com.android.externalstorage [ userId:0 | appId:10009 ]
,E/SELinux ( 7691): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 7695): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7695):  
I/SELinux ( 7695):  
,I/SELinux ( 7695): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7695): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7695): >>>>> Normal User
,E/dalvikvm( 7695): >>>>> com.google.android.gms [ userId:0 | appId:10012 ]
,E/SELinux ( 7695): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7691): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7691): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7691): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 7695): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7695): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7695): Added TimaKesytore provider
I/SELinux ( 7700): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7700):  
I/SELinux ( 7700):  
,I/SELinux ( 7700): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7700): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7700): >>>>> Normal User
,E/dalvikvm( 7700): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 7700): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7700): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7700): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7700): Added TimaKesytore provider
,D/dalvikvm( 7691): GC_CONCURRENT freed 3003K, 32% free 9566K/14068K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 7691): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/ExternalStorage( 7691): After updating volumes, found 1 active roots
D/dalvikvm( 7695): GC_CONCURRENT freed 2933K, 32% free 9632K/14068K, paused 4ms+2ms, total 29ms
,D/dalvikvm( 7695): WAIT_FOR_CONCURRENT_GC blocked 20ms
,W/dalvikvm( 7695): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7695): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 7695): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 7695): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 7695): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 7695): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7695): install
,I/MultiDex( 7695): MultiDexExtractor.load(/data/app/com.google.android.gms-5.apk, false)
,I/MultiDex( 7695): loading existing secondary dex files
,I/MultiDex( 7695): load found 3 secondary dex files
,I/MultiDex( 7695): install done
,D/dalvikvm( 7700): GC_CONCURRENT freed 2986K, 32% free 9584K/14072K, paused 4ms+2ms, total 32ms
,D/dalvikvm( 7700): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/Icing.InternalIcingCorporaProvider( 7700): Updating corpora: A: com.test.thalitest, C: MAYBE
,I/SELinux ( 7733): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7733):  
,I/SELinux ( 7737): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7737):  
,D/LocationManagerService( 2418): getProviders()=[passive]
,I/SELinux ( 7733): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7733):  
I/SELinux ( 7733):  
,I/SELinux ( 7733): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7733): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7733): >>>>> Normal User
,E/dalvikvm( 7733): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 7733): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/SELinux ( 7737): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7737):  
I/SELinux ( 7737):  
,I/SELinux ( 7737): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7737): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7737): >>>>> Normal User
,E/dalvikvm( 7737): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7737): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7733): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7733): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7733): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 7737): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7737): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7737): Added TimaKesytore provider
,D/dalvikvm( 7733): GC_CONCURRENT freed 2997K, 32% free 9568K/14064K, paused 4ms+2ms, total 29ms
,D/dalvikvm( 7733): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 7737): GC_CONCURRENT freed 2994K, 32% free 9582K/14072K, paused 4ms+2ms, total 36ms
,D/dalvikvm( 7737): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 7737): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/GservicesProvider( 7737): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7737): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7737): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7737): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7737): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7737): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7737): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7737): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7737): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7737): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7737): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7737): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7737): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7737): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7737): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7737): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7737): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7737): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7737): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7737): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7737): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7737): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7737): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7737): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7737): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7737): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7737): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7737): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7737): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7737): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7737): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7737): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7737): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 7737): Shutting down VM
,W/dalvikvm( 7737): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7737): FATAL EXCEPTION: main
E/AndroidRuntime( 7737): Process: com.google.process.gapps, PID: 7737
E/AndroidRuntime( 7737): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7737): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7737): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7737): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7737): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7737): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7737): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7737): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7737): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7737): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7737): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7737): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7737): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7737): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7737): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7737): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7737): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7737): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7737): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7737): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7737): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7737): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7737): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7737): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7737): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7737): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7737): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7737): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7737): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7737): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7737): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7737): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7737): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7737): 	... 12 more
,I/Process ( 7737): Sending signal. PID: 7737 SIG: 9
E/DropBoxManagerService( 2418): Can't write: system_app_crash
E/DropBoxManagerService( 2418): java.io.FileNotFoundException: /data/system/dropbox/drop226.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2418): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2418): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2418): 	... 5 more
,I/ActivityManager( 2418): Process com.google.process.gapps (pid 7737) (adj 0) has died.
,W/ActivityManager( 2418): Service crashed 2 times, stopping: ServiceRecord{42fbc128 u0 com.google.android.gms/.gcm.GcmService}
,I/SELinux ( 7767): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7767):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 14% free 9503K/11048K, paused 3ms+3ms, total 35ms
,I/SELinux ( 7767): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7767):  
I/SELinux ( 7767):  
,I/SELinux ( 7767): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7767): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7767): >>>>> Normal User
,E/dalvikvm( 7767): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7767): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9503K/11048K, paused 2ms+4ms, total 30ms
,D/TimaKeyStoreProvider( 7767): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7767): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7767): Added TimaKesytore provider
,I/ActivityManager( 2418): Waited long enough for: ServiceRecord{43612390 u0 com.sec.spp.push/.PushClientService}
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9503K/11048K, paused 3ms+3ms, total 31ms
,D/dalvikvm( 7767): GC_CONCURRENT freed 2987K, 32% free 9583K/14068K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 7767): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/GservicesProvider( 7767): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7767): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7767): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7767): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7767): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7767): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7767): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7767): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7767): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7767): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7767): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7767): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7767): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7767): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7767): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7767): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7767): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7767): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7767): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7767): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7767): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7767): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7767): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7767): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7767): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7767): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7767): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7767): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7767): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7767): Shutting down VM
,W/dalvikvm( 7767): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7767): FATAL EXCEPTION: main
E/AndroidRuntime( 7767): Process: com.google.process.gapps, PID: 7767
E/AndroidRuntime( 7767): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7767): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7767): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7767): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7767): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7767): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7767): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7767): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7767): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7767): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7767): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7767): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7767): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7767): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7767): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7767): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7767): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7767): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7767): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7767): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7767): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7767): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7767): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7767): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7767): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7767): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7767): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7767): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7767): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7767): 	... 12 more
W/ActivityManager( 2418): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2418): Killing 7767:com.google.process.gapps/u0a12 (adj 0): crash
E/DropBoxManagerService( 2418): Can't write: system_app_crash
E/DropBoxManagerService( 2418): java.io.FileNotFoundException: /d,ata/system/dropbox/drop227.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2418): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2418): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2418): 	... 5 more
W/ActivityManager( 2418): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
W/ActivityManager( 2418): Unable to launch app com.google.android.gsf/10012 for provider com.google.settings: launching app became null
W/ActivityManager( 2418): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7733): Failed to find provider info for com.google.android.gsf.gservices
E/ActivityThread( 7695): Failed to find provider info for com.google.android.gsf.gservices
E/ActivityThread( 7700): Failed to find provider info for com.google.settings
,I/SELinux ( 7783): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7783):  
,I/SELinux ( 7783): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7783):  
I/SELinux ( 7783):  
,I/SELinux ( 7783): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7783): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 7783): >>>>> Normal User
,E/dalvikvm( 7783): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7783): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7783): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7783): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7783): Added TimaKesytore provider
,D/dalvikvm( 7783): GC_CONCURRENT freed 2990K, 32% free 9580K/14068K, paused 3ms+1ms, total 25ms
,D/dalvikvm( 7783): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/GservicesProvider( 7783): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7783): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7783): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7783): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7783): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7783): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7783): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7783): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7783): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7783): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7783): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7783): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7783): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7783): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7783): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7783): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7783): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7783): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7783): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7783): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7783): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7783): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7783): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7783): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7783): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7783): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7783): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7783): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7783): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7783): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7783): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7783): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7783): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7783): Shutting down VM
,W/dalvikvm( 7783): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7783): FATAL EXCEPTION: main
E/AndroidRuntime( 7783): Process: com.google.process.gapps, PID: 7783
E/AndroidRuntime( 7783): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7783): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7783): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7783): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7783): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7783): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7783): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7783): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7783): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7783): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7783): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7783): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7783): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7783): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7783): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7783): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7783): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7783): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7783): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7783): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7783): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7783): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7783): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7783): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7783): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7783): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7783): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7783): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7783): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7783): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7783): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7783): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7783): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7783): 	... 12 more
,I/Process ( 7783): Sending signal. PID: 7783 SIG: 9
E/DropBoxManagerService( 2418): Can't write: system_app_crash
E/DropBoxManagerService( 2418): java.io.FileNotFoundException: /data/system/dropbox/drop228.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2418): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2418): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2418): 	... 5 more
,I/ActivityManager( 2418): Process com.google.process.gapps (pid 7783) (adj 0) has died.
,I/SELinux ( 7798): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7798):  
,I/SELinux ( 7798): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7798):  
I/SELinux ( 7798):  
,I/SELinux ( 7798): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7798): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7798): >>>>> Normal User
,E/dalvikvm( 7798): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7798): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7798): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7798): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7798): Added TimaKesytore provider
,D/dalvikvm( 7798): GC_CONCURRENT freed 2994K, 32% free 9579K/14072K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 7798): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/GservicesProvider( 7798): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7798): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7798): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7798): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7798): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7798): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7798): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7798): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7798): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7798): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7798): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7798): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7798): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7798): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7798): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7798): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7798): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7798): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7798): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7798): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7798): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7798): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7798): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7798): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7798): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7798): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7798): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7798): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7798): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7798): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7798): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7798): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7798): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 7798): Shutting down VM
,W/dalvikvm( 7798): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7798): FATAL EXCEPTION: main
E/AndroidRuntime( 7798): Process: com.google.process.gapps, PID: 7798
E/AndroidRuntime( 7798): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7798): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7798): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7798): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7798): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7798): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7798): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7798): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7798): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7798): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7798): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7798): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7798): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7798): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7798): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7798): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7798): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7798): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7798): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7798): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7798): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7798): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7798): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7798): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7798): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7798): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7798): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7798): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7798): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7798): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7798): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7798): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7798): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7798): 	... 12 more
W/ActivityManager( 2418): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2418): Killing 7798:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2418): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launc,hing app became null
W/ActivityManager( 2418): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7733): Failed to find provider info for com.google.android.gsf.gservices
E/DropBoxManagerService( 2418): Can't write: system_app_crash
E/DropBoxManagerService( 2418): java.io.FileNotFoundException: /data/system/dropbox/drop229.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2418): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2418): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2418): 	... 5 more
E/ActivityThread( 7695): Failed to find provider info for com.google.android.gsf.gservices
D/dalvikvm( 7695): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7695): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7695): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7695): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7695): VFY: unable to resolve instance field 36
D/dalvikvm( 7695): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 7695): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7695): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7695): VFY: replacing opcode 0x62 at 0x0047
,I/ActivityManager( 2418): Killing 6604:com.samsung.groupcast/u0a15 (adj 15): empty #43
D/dalvikvm( 7695): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 7695): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 7695): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422c3dc8
D/dalvikvm( 7695): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422c3dc8
D/dalvikvm( 7695): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422c3dc8, skipping init
D/dalvikvm( 7695): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x422c3dc8
D/dalvikvm( 7695): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x422c3dc8
V/JNIHelp ( 7695): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/dalvikvm( 2952): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 2952): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 2952): Process: android.process.acore, PID: 2952
E/AndroidRuntime( 2952): android.database.sqlite.SQLiteDatabaseLockedException: database is locked (code 5)
E/AndroidRuntime( 2952): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2952): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 2952): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2952): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2952): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 2952): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 2952): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:408)
E/AndroidRuntime( 2952): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:377)
E/AndroidRuntime( 2952): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2467)
E/AndroidRuntime( 2952): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 2952): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2952): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2952): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 2952): Sending signal. PID: 2952 SIG: 9
E/DropBoxManagerService( 2418): Can't write: system_app_crash
E/DropBoxManagerService( 2418): java.io.FileNotFoundException: /data/system/dropbox/drop230.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2418): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2418): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2418): 	... 5 more
,I/ActivityManager( 2418): Process android.process.acore (pid 2952) (adj -12) has died.
,I/SELinux ( 7814): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7814):  
,D/dalvikvm( 7695): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422c3dc8
,D/dalvikvm( 7695): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x422c3dc8
D/dalvikvm( 7695): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x422c3dc8
,D/dalvikvm( 7695): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x422c3dc8
,I/SELinux ( 7814): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7814):  
I/SELinux ( 7814):  
,I/SELinux ( 7814): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7814): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7814): >>>>> Normal User
,E/dalvikvm( 7814): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7814): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7814): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7814): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7814): Added TimaKesytore provider
,I/ProviderInstaller( 7695): Installed default security provider GmsCore_OpenSSL
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/SELinux ( 7826): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7826):  
,D/dalvikvm( 7814): GC_CONCURRENT freed 2998K, 32% free 9577K/14072K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 7814): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/SELinux ( 7826): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7826):  
I/SELinux ( 7826):  
,I/SELinux ( 7826): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7826): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7826): >>>>> Normal User
,E/dalvikvm( 7826): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7826): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7826): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7826): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7826): Added TimaKesytore provider
,D/dalvikvm( 7826): GC_CONCURRENT freed 2995K, 32% free 9579K/14072K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 7826): WAIT_FOR_CONCURRENT_GC blocked 22ms
,E/SQLiteDatabase( 7814): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7814): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7814): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7814): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7814): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7814): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7814): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7814): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7814): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 7814): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7814): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7814): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7814): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7814): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7814): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7814): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7814): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7814): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7814): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7814): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7814): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7814): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7814): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7814): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7814): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 7814): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7814): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7814): (14) unable to open database file
E/SQLiteDatabase( 7814): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7814): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7814): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7814): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7814): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7814): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7814): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7814): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7814): threadid=13: thread exiting with uncaught exception (group=0x4180ac08),
E/AndroidRuntime( 7814): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7814): Process: android.process.acore, PID: 7814
E/AndroidRuntime( 7814): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7814): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7814): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7814): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7814): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7814): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7814): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7814): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7814): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7814): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7814): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7814): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7814): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7814): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7814): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7814): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 7814): Sending signal. PID: 7814 SIG: 9
W/ActivityManager( 2418): Process android.process.acore has crashed too many times: killing!
,E/DropBoxManagerService( 2418): Can't write: system_app_crash
E/DropBoxManagerService( 2418): java.io.FileNotFoundException: /data/system/dropbox/drop231.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2418): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2418): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2418): 	... 5 more
,I/ActivityManager( 2418): Process android.process.acore (pid 7814) (adj -12) has died.
,F/ActivityManager( 2418): Service ServiceRecord{43148478 u0 com.android.providers.contacts/.VoicemailCleanupService} in process ProcessRecord{424de408 7814:android.process.acore/u0a20} not same as in map: null
,E/DropBoxManagerService( 2418): Can't write: system_server_wtf
E/DropBoxManagerService( 2418): java.io.FileNotFoundException: /data/system/dropbox/drop160.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2418): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2418): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2418): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2418): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2418): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2418): 	at android.util.Slog.wtf(Slog.java:163)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2151)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15153)
E/DropBoxManagerService( 2418): 	,at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4944)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5122)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1322)
E/DropBoxManagerService( 2418): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:493)
E/DropBoxManagerService( 2418): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2418): 	... 18 more
,I/GservicesProvider( 7826): Gservices pushing to system: true; secure/global: true
,I/SELinux ( 7847): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7847):  
,E/SQLiteDatabase( 7826): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7826): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7826): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7826): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7826): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7826): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7826): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7826): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7826): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7826): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7826): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7826): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7826): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7826): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7826): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7826): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7826): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7826): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7826): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7826): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7826): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7826): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7826): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7826): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7826): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7826): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7826): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7826): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7826): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7826): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7826): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7826): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 7826): Shutting down VM
,W/dalvikvm( 7826): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7826): FATAL EXCEPTION: main
E/AndroidRuntime( 7826): Process: com.google.process.gapps, PID: 7826
E/AndroidRuntime( 7826): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7826): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7826): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7826): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7826): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7826): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7826): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7826): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7826): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7826): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7826): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7826): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7826): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7826): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7826): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7826): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7826): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7826): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7826): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7826): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7826): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7826): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7826): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7826): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7826): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7826): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7826): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7826): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7826): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7826): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7826): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7826): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7826): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7826): 	... 12 more
,I/Process ( 7826): Sending signal. PID: 7826 SIG: 9
E/DropBoxManagerService( 2418): Can't write: system_app_crash
E/DropBoxManagerService( 2418): java.io.FileNotFoundException: /data/system/dropbox/drop233.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2418): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2418): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2418): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2418): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2418): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2418): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2418): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2418): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2418): 	... 5 more
,I/ActivityManager( 2418): Process com.google.process.gapps (pid 7826) (adj 0) has died.
,I/SELinux ( 7852): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7852):  
I/SELinux ( 7847): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7847):  
I/SELinux ( 7847):  
,I/SELinux ( 7847): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7847): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7847): >>>>> Normal User
,E/dalvikvm( 7847): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7847): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7847): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7847): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7847): Added TimaKesytore provider
,I/SELinux ( 7852): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7852):  
I/SELinux ( 7852):  
,I/SELinux ( 7852): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7852): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7852): >>>>> Normal User
,E/dalvikvm( 7852): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7852): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7852): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7852): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7852): Added TimaKesytore provider
,D/dalvikvm( 7847): GC_CONCURRENT freed 2982K, 32% free 9587K/14068K, paused 4ms+2ms, total 27ms
,D/dalvikvm( 7847): WAIT_FOR_CONCURRENT_GC blocked 21ms

```
