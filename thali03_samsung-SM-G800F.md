#### Test 549702610b97681_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
,E/Watchdog( 2401): !@Sync 8
--------- beginning of /dev/log/main
D/AndroidRuntime( 7191): 
D/AndroidRuntime( 7191): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7191): CheckJNI is OFF
D/AndroidRuntime( 7191): setted country_code = Poland
D/AndroidRuntime( 7191): setted countryiso_code = PL
D/AndroidRuntime( 7191): setted sales_code = PLS
D/AndroidRuntime( 7191): readGMSProperty: start
D/AndroidRuntime( 7191): readGMSProperty: already setted!!
D/AndroidRuntime( 7191): readGMSProperty: end
D/AndroidRuntime( 7191): addProductProperty: start
D/dalvikvm( 7191): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7191): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7191): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7191): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7191): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7191): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7191): failed to load memtrack module: -2
D/SSRMv2:SIOP( 2401): SIOP:: AP = 310, Delta = 0
D/dalvikvm( 7191): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7191): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2401): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2401): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2401): mDVFSHelper.acquire()
I/SELinux ( 7219): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7219):  
D/PointerIcon( 2401): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2401): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2401): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2401): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7191): Shutting down VM
D/dalvikvm( 7191): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 3ms
I/SELinux ( 7219): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7219):  
I/SELinux ( 7219):  
I/SELinux ( 7219): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7219): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7219): >>>>> Normal User
E/dalvikvm( 7219): >>>>> com.test.thalitest [ userId:0 | appId:10605 ]
E/SELinux ( 7219): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7219): in addTimaSignatureService
D/TimaKeyStoreProvider( 7219): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7219): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4184): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4184): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7219): GC_CONCURRENT freed 3006K, 31% free 9558K/13696K, paused 2ms+1ms, total 17ms
D/dalvikvm( 7219): WAIT_FOR_CONCURRENT_GC blocked 15ms
V/WebViewChromium( 7219): Binding Chromium to the background looper Looper (main, tid 1) {4226b310}
I/chromium( 7219): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7219): Initializing chromium process, renderers=0
W/chromium( 7219): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7219): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 7219): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7219): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7219): Mali API Version : 401
,I/Mali    ( 7219): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/AmoledAdjustTimer( 2401): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,I/dalvikvm( 7219): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7219): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,D/dalvikvm( 7219): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7219): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7219): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7219): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2401): tr p:7219,o:f
,W/dalvikvm( 7219): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 7219): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7219): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7219): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7219): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7219): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7219): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7219): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 7219): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7219): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
,W/dalvikvm( 7219): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7219): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7219): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2401): semi p:7219,o:f
,I/SurfaceFlinger( 1920): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2401): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2401): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2401): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2401): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2401): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2401): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7219): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7219): Enabling debug mode 0
,W/AwContents( 7219): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7219): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2401): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  tag : ACTIVITY_RESUME_BOOSTER@4
,D/CustomFrequencyManagerService( 2401): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/ActivityManager( 2401): mDVFSHelper.release()
,D/JsMessageQueue( 7219): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7219): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4225c508
,D/dalvikvm( 7219): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4225c508
D/jxcore_app_log( 7219): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027564664
,D/JX-Cordova( 7219): jxcore cordova android initializing
,D/dalvikvm( 7219): GC_CONCURRENT freed 1287K, 18% free 11344K/13756K, paused 1ms+3ms, total 23ms
,D/dalvikvm( 7219): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 7219): GC_CONCURRENT freed 1934K, 18% free 14954K/18028K, paused 3ms+2ms, total 43ms
D/dalvikvm( 7219): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/dalvikvm( 7219): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/CustomFrequencyManagerService( 2401): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7219): GC_FOR_ALLOC freed 5343K, 30% free 16237K/22924K, paused 49ms, total 50ms
,D/dalvikvm( 7219): GC_CONCURRENT freed 6716K, 31% free 17691K/25556K, paused 3ms+14ms, total 96ms
D/dalvikvm( 7219): WAIT_FOR_CONCURRENT_GC blocked 65ms
,D/dalvikvm( 7219): WAIT_FOR_CONCURRENT_GC blocked 66ms
,D/dalvikvm( 7219): GC_FOR_ALLOC freed 1402K, 32% free 17383K/25556K, paused 59ms, total 59ms
,I/dalvikvm-heap( 7219): Grow heap (frag case) to 21.590MB for 3688532-byte allocation
,D/dalvikvm( 7219): GC_FOR_ALLOC freed 8K, 29% free 20976K/29160K, paused 55ms, total 55ms
,W/jxcore-log( 7219): Initializing JXcore engine
,W/jxcore-log( 7219): JXcore engine is ready
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/jxcore-log( 7219): Starting JXcore engine
,W/jxcore-log( 7219): Platform android
W/jxcore-log( 7219): 
,W/jxcore-log( 7219): Process ARCH arm
W/jxcore-log( 7219): 
,I/jxcore-log( 7219): JXcore Cordova bridge is ready!
I/jxcore-log( 7219): 
,W/jxcore-log( 7219): JXcore engine is started
,I/chromium( 7219): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7219): Toggling radios to true
I/jxcore-log( 7219): 
,D/BluetoothAdapter( 7219): enable(): BT is already enabled..!
,I/WifiManager( 7219): packageName : com.test.thalitest
,I/WifiManager( 7219): setWifiEnabled : true
,I/WifiService( 2401): setWifiEnabled: true pid=7219, uid=10605
W/ActivityManager( 2401): Permission Denial: getCurrentUser() from pid=7219, uid=10605 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2401): Failed getting userId using ActivityManagerNative
W/WifiService( 2401): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7219, uid=10605 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2401): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2401): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2401): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2401): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2401): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2401): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService( 2401): disconnect: pid=7219, uid=10605
,I/jxcore-log( 7219): Radios toggled
I/jxcore-log( 7219): 
,I/wpa_supplicant( 3959): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7219): My device name is: samsung-SM-G800F
I/jxcore-log( 7219): 
,I/wpa_supplicant( 3959): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3959): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2401): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3959): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 3959): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3959): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3959): First Scan Start
,W/Settings( 2401): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
D/Tethering( 2401): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3959): Scan requested (ret=0) - scan timeout 30 seconds
,I/WifiStateMachine( 2401): ignore requestNetworkTransitionWakelock airplane:true
,D/WifiP2pService( 2401): InactiveState{ what=143375 }
,D/WifiP2pService( 2401): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/CommandListener( 1915): Clearing all IP addresses on wlan0
,I/wpa_supplicant( 3959): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3959): Skip scan - already scanning
,I/WifiTrafficPoller( 2401): evaluateTrafficStatsPolling
D/ConnectivityService( 2401): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/WifiP2pService( 2401): InactiveState{ what=143375 }
D/ConnectivityService( 2401): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2401): net.tcp.usercfg.default not found in system default properties
D/WifiP2pService( 2401): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
E/ConnectivityService( 2401): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2401): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2401): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
,D/ConnectivityService( 2401): Attempting to switch to mobile
,D/ConnectivityService( 2401): Attempting to switch to BLUETOOTH_TETHER
,I/SELinux ( 7267): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7267):  
D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/CommandListener( 1915): Clearing all IP addresses on wlan0
,E/WifiStateMachine( 2401): Error! unhandled message{ when=-35ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2401): Error! unhandled message{ when=-32ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiTrafficPoller( 2401): evaluateTrafficStatsPolling
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
,E/WifiStateMachine( 2401): Error! unhandled message{ when=-8ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
,I/SELinux ( 7267): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7267):  
I/SELinux ( 7267):  
,I/SELinux ( 7267): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7267): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7267): >>>>> Normal User
,E/dalvikvm( 7267): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7267): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
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
,V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 7267): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7267): Cannot add TimaSignature Service, License check Failed
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/ActivityThread( 7267): Added TimaKesytore provider
,D/NetUtils( 2401): android_net_utils_resetConnections in env=0x77d1c388 clazz=0x62800001 iface=wlan0 mask=0x3
,D/ConnectivityService( 2401): resetConnections(wlan0, 3)
,E/SPPClientService( 5526): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5526): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5526): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5526): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5526): [b] ResponseMap empty
,D/dalvikvm( 7267): GC_CONCURRENT freed 2985K, 31% free 9583K/13700K, paused 4ms+2ms, total 32ms
,D/dalvikvm( 7267): WAIT_FOR_CONCURRENT_GC blocked 21ms
,V/NativeCrypto( 2858): Read error: ssl=0x7bae9758: I/O error during system call, Connection timed out
,V/NativeCrypto( 2858): SSL shutdown failed: ssl=0x7bae9758: I/O error during system call, Broken pipe
,I/System.out( 7267): Inside WakeupProvider
,I/System.out( 7267): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 7267): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7267): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7267): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/ConnectivityService( 2401): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
V/NetworkStats( 2401): updateIfacesLocked()
V/NetworkStats( 2401): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
V/NetworkStats( 2401): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
V/NetworkStats( 2401): performPollLocked() took 23ms
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,D/NearbySettings( 2821): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2821): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2821): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 2821): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2821): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2821): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2821): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2401): Killing 6156:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/DialogFlow( 7267): initQueue()
,D/NearbySettings( 2821): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2821): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2821): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2821): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2821): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2821): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2821): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2401): Tethering got CONNECTIVITY_ACTION
I/ApplicationPolicy( 2401): updateDataUsageMap
,D/Tethering( 2401): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2401): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2401): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6566): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6566): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6566): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6566): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 4728): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6566): noConnectivity : true
,D/libgps  ( 2401): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7296): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7296):  
,I/SELinux ( 7296): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7296):  
I/SELinux ( 7296):  
,I/SELinux ( 7296): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7296): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7296): >>>>> Normal User
,E/dalvikvm( 7296): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7296): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/wpa_supplicant( 3959): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 3959): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3959): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3959): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/TimaKeyStoreProvider( 7296): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7296): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7296): Added TimaKesytore provider
,D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2401): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3959): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
D/Tethering( 2401): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3959): Associated with C0.AA.48
I/wpa_supplicant( 3959): freq(2412) increment count 2
,I/wpa_supplicant( 3959): meet head of list.
D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2401): interfaceStatusChanged wlan0, true
,D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2401): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3959): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/dalvikvm( 7296): GC_CONCURRENT freed 3014K, 31% free 9560K/13700K, paused 4ms+2ms, total 33ms
,D/dalvikvm( 7296): WAIT_FOR_CONCURRENT_GC blocked 29ms
,I/wpa_supplicant( 3959): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3959): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3959): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3959): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2401): interfaceStatusChanged wlan0, true
,D/WifiNative( 2401): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/ActivityManager( 2401): Killing 6226:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/WifiP2pService( 2401): InactiveState{ what=143375 }
,D/WifiP2pService( 2401): P2pEnabledState{ what=143375 }
,I/SELinux ( 7310): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7310):  
,I/SELinux ( 7310): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7310):  
I/SELinux ( 7310):  
,I/SELinux ( 7310): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7310): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7310): >>>>> Normal User
,E/dalvikvm( 7310): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7310): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7310): in addTimaSignatureService
D/TimaKeyStoreProvider( 7310): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7310): Added TimaKesytore provider
,D/dalvikvm( 7310): GC_CONCURRENT freed 3010K, 31% free 9558K/13696K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 7310): WAIT_FOR_CONCURRENT_GC blocked 13ms
,I/dhcpcd  ( 7322): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7322): bssid match
,I/ActivityManager( 2401): Killing 6296:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7329): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7329):  
,I/SELinux ( 7329): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7329):  
I/SELinux ( 7329):  
,I/SELinux ( 7329): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7329): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7329): >>>>> Normal User
,E/dalvikvm( 7329): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7329): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7329): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7329): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7329): Added TimaKesytore provider
,D/dalvikvm( 7329): GC_CONCURRENT freed 3003K, 31% free 9569K/13700K, paused 16ms+2ms, total 33ms
,D/dalvikvm( 7329): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/KLMS-2.3.201 : ( 7329): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7329): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452294512002
,I/KLMS-2.3.201 : ( 7329): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2401): Killing 6326:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7341): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7341):  
,I/SELinux ( 7341): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7341):  
I/SELinux ( 7341):  
,I/SELinux ( 7341): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7341): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7341): >>>>> Normal User
,E/dalvikvm( 7341): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7341): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7341): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7341): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7341): Added TimaKesytore provider
,D/libgps  ( 2401): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2401): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2401): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2401): agps_ril_update_network_availability: Waiting for IPC connection...
,D/dalvikvm( 7341): GC_CONCURRENT freed 3000K, 31% free 9565K/13692K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 7341): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/SO_AGENT( 7341): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7341): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5791): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5791): [BDLM] already registered in spp
I/SA      ( 5791): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5791): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5791): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5791): [OR] == isSIMCardReady false ==
,I/SA      ( 5791): [SCU] == networkStateCheck == false
,I/SA      ( 5791): [OR] onReceive END
,I/ActivityManager( 2401): Killing 6245:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): Phone number locator feature is dsiabled
D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4352, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2401): stay LED for fully charged
,I/SELinux ( 7354): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7354):  
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3996): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3996): Disconnected process message: 10
,D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 11% free 9502K/10672K, paused 2ms+3ms, total 32ms
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
I/SELinux ( 7354): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7354):  
I/SELinux ( 7354):  
,I/SELinux ( 7354): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7354): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7354): >>>>> Normal User
,E/dalvikvm( 7354): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
E/SELinux ( 7354): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9502K/10672K, paused 2ms+3ms, total 25ms
,D/TimaKeyStoreProvider( 7354): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7354): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7354): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9502K/10672K, paused 2ms+3ms, total 24ms
,D/dalvikvm( 7354): GC_CONCURRENT freed 2997K, 31% free 9577K/13700K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7354): WAIT_FOR_CONCURRENT_GC blocked 12ms
,I/sCloudBackupApp( 7354): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7354): Other Intent
I/ActivityManager( 2401): Killing 5572:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SELinux ( 7367): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7367):  
,I/SELinux ( 7367): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7367):  
I/SELinux ( 7367):  
,I/SELinux ( 7367): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7367): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7367): >>>>> Normal User
,E/dalvikvm( 7367): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7367): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7367): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7367): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7367): Added TimaKesytore provider
,D/dalvikvm( 7367): GC_CONCURRENT freed 3000K, 31% free 9560K/13692K, paused 1ms+1ms, total 17ms
,D/dalvikvm( 7367): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/com.samsung.app( 7367): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7367): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7367): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7367): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7367): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7367): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5324): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7367): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5324): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7367): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5324): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7367): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7367): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2401): Killing 6278:com.sec.phone/1001 (adj 15): empty #43
,D/Headlines( 5854): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5854): getCountryCode(): countryCode = PL
,D/Headlines( 5854): Breath.onCreate
,D/Headlines( 5854): Breath timer started. interval : 30000
,I/SELinux ( 7395): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7395):  
,D/Headlines( 5854): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5854): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5854): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5854): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5854): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5854): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5854): requestUpdateNewsWelcomeCard !!! no welcome card
V/AlarmManager( 2401): waitForAlarm result :8
,I/SELinux ( 7395): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7395):  
I/SELinux ( 7395):  
,I/SELinux ( 7395): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7395): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 7395): >>>>> Normal User
,E/dalvikvm( 7395): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7395): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7395): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7395): Cannot add TimaSignature Service, License check Failed
D/WifiP2pService( 2401): InactiveState{ what=143375 }
,D/ActivityThread( 7395): Added TimaKesytore provider
D/WifiP2pService( 2401): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2401): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2401): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2401): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2401): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2401): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2401): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2401): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2401): evaluateTrafficStatsPolling
D/ConnectivityService( 2401): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2401): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2401): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/dalvikvm( 7395): GC_CONCURRENT freed 3004K, 31% free 9561K/13696K, paused 2ms+2ms, total 51ms
,D/dalvikvm( 7395): WAIT_FOR_CONCURRENT_GC blocked 48ms
D/ConnectivityService( 2401): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/NetworkStats( 2401): updateIfacesLocked()
,V/NetworkStats( 2401): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
V/NetworkStats( 2401): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,V/NetworkStats( 2401): performPollLocked() took 18ms
D/libgps  ( 2401): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2401): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2401): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,V/WebViewChromium( 7395): Binding Chromium to the background looper Looper (main, tid 1) {42268368}
,I/chromium( 7395): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7395): Initializing chromium process, renderers=0
,W/chromium( 7395): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7395): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7395): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7395): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7395): Mali API Version : 401
,I/Mali    ( 7395): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7395): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/GAV2    ( 7395): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/dalvikvm( 2858): GC_CONCURRENT freed 1847K, 22% free 10809K/13856K, paused 2ms+4ms, total 41ms
,I/NSApplication( 7395): Starting up...
,I/iu.Environment( 5922): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5124): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5124): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5124): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42278090
,I/SELinux ( 7453): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7453):  
,I/SELinux ( 7453): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7453):  
I/SELinux ( 7453):  
,I/SELinux ( 7453): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7453): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7453): >>>>> Normal User
,E/dalvikvm( 7453): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7453): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7453): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7453): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7453): Added TimaKesytore provider
,D/Tethering( 2401): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2401): MasterInitialState.processMessage what=3
D/dalvikvm( 7453): GC_CONCURRENT freed 2998K, 31% free 9574K/13700K, paused 2ms+2ms, total 22ms
,D/dalvikvm( 7453): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/CaptivePortalTracker( 2401): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4728): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId
,D/libgps  ( 2401): agps_ril_update_network_state: Waiting for IPC connection...
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId
,I/SELinux ( 7473): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7473):  
D/RCPManagerService( 2401): exchangeData() failure , invalid userId
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId
,I/ActivityManager( 2401): Killing 6300:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/SELinux ( 7473): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7473):  
I/SELinux ( 7473):  
,I/SELinux ( 7473): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7473): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7473): >>>>> Normal User
,E/dalvikvm( 7473): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7473): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 7483): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7483):  
,W/ActivityManager( 2401): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/TimaKeyStoreProvider( 7473): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7473): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7473): Added TimaKesytore provider
,I/ActivityManager( 2401): Killing 5967:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7483): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7483):  
I/SELinux ( 7483):  
,I/SELinux ( 7483): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7483): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7483): >>>>> Normal User
,E/dalvikvm( 7483): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7483): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7483): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7483): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7483): Added TimaKesytore provider
,D/dalvikvm( 7473): GC_CONCURRENT freed 3002K, 31% free 9565K/13696K, paused 3ms+1ms, total 25ms
,D/dalvikvm( 7473): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/BadgeProvider( 7473): onCreate
,D/BadgeProvider( 7473): DatabaseHelper
,D/BadgeProvider( 7473): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/dalvikvm( 7483): GC_CONCURRENT freed 2999K, 31% free 9572K/13700K, paused 3ms+1ms, total 25ms
,D/dalvikvm( 7483): WAIT_FOR_CONCURRENT_GC blocked 15ms
D/BadgeProvider( 7473): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7473): sendNotify, [notify] : null
D/Launcher.Model( 2774): reloadBadges entered.
D/BadgeProvider( 7473): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7473): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7473): update, [UpdateCount] : 1
,D/hcjo    ( 5943): AutoUpdateManager:IDLE:execute
,E/SPPClientService( 5526): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5526): [SystemStateMoniter] Current Time : 268880
,E/SPPClientService( 5526): [SystemStateMoniter] No Connect : true
,D/NearbySettings( 2821): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2821): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2821): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2821): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2821): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2821): MountReceiver.onReceive - Keep current state
D/InitializeManagerStateMachine( 5943): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5943): exit::IDLE
,D/InitializeManagerStateMachine( 5943): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5943): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5943): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5943): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5943): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5943): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5943): entry::SUCCESS
,D/hcjo    ( 5943): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/Headlines( 5854): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,E/SPPClientService( 5526): [[SystemStateMonitorService]] No Active Internet
D/hcjo    ( 5943): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5943): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5943): exit::SUCCESS
,D/InitializeManagerStateMachine( 5943): entry::IDLE
D/Headlines( 5854): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5854): Breath 1431 latestRequest time : 1452294512807 current time : 1452294514238
,E/SPPClientService( 5526): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5526): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5526): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/NearbySettings( 2821): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2821): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5526): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,D/dalvikvm( 2401): GC_EXPLICIT freed 4150K, 74% free 25456K/96300K, paused 11ms+22ms, total 264ms
,D/NearbySettings( 2821): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2821): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2821): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2821): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2821): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2821): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 2821): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,E/SPPClientService( 5526): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,I/NearbySettings( 2821): MountReceiver.onReceive - Keep current state
,I/PCWCLIENTTRACE_PushUtil( 6566): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6566): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6566): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6566): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5526): [a] [ConnectionManager] Connection is already disconnected.
,I/SurfaceFlinger( 1920): id=20 createSurf (1x1),1 flag=4, Uoast
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 330, Delta = 20
,E/SPPClientService( 5526): [g] getNetMCC return empty string
D/PowerManagerService( 2401): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2401
,I/KLMS-2.3.201 : ( 7329): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7329): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452294514620
,I/KLMS-2.3.201 : ( 7329): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7341): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3253): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3253): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3253): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7341): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/GalaxyFinderApplication( 3253): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 3382): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7509): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7509):  
,I/SELinux ( 7513): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7513):  
I/SELinux ( 7509): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7509):  
I/SELinux ( 7509):  
I/SELinux ( 7509): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7509): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7509): >>>>> Normal User
E/dalvikvm( 7509): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
E/SELinux ( 7509): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/SELinux ( 7513): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7513):  
I/SELinux ( 7513):  
I/SELinux ( 7513): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7513): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7513): >>>>> Normal User
E/dalvikvm( 7513): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7513): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/libgps  ( 2401): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2401): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2401): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2401): agps_ril_update_network_availability: Waiting for IPC connection...
,D/PackageManager( 2401): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/TimaKeyStoreProvider( 7509): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7509): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7509): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 7513): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7513): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7513): Added TimaKesytore provider
,D/dalvikvm( 7509): GC_CONCURRENT freed 2985K, 31% free 9583K/13696K, paused 3ms+7ms, total 58ms
,D/dalvikvm( 7509): WAIT_FOR_CONCURRENT_GC blocked 49ms
,D/dalvikvm( 7513): GC_CONCURRENT freed 3002K, 31% free 9570K/13700K, paused 4ms+1ms, total 28ms
,D/dalvikvm( 7513): WAIT_FOR_CONCURRENT_GC blocked 13ms
,V/KVNProvider( 7513): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7513): getFindoCursor query string : 
I/SA      ( 5791): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5791): [BDLM] already registered in spp
,I/SA      ( 5791): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5791): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,V/KVNProvider( 7513): getTagSearchCursor() tagSearchCursor count : 0
I/SA      ( 5791): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5791): [OR] == isSIMCardReady false ==
,I/SA      ( 5791): [SCU] == networkStateCheck == true
,D/AmoledAdjustTimer( 2401): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
I/SA      ( 5791): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5791): isChinaCountryCode : false
I/SA      ( 5791): [OR] == networkStateCheck true ==
,I/SA      ( 5791): [OR] GetMyCountryZoneTask
,I/SA      ( 5791): [OR] onReceive END
,I/SA      ( 5791): [SRS] prepareGetMyCountryZone
,I/SA      ( 5791): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5791): [SSP] query invoked
,I/SA      ( 5791): [TPMU] GetMccFromDB : null
D/PhoneNumberLocatorBootCompletedReceiver( 2754): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): Phone number locator feature is dsiabled
,I/SA      ( 5791): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5791): [TPM] isNoProxy(default) : true
,I/SCloudBackupReceiver( 7354): Other Intent
,I/SA      ( 5791): [RC New] Execute method=[GET] start
,I/ActivityManager( 2401): Killing 6143:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/com.samsung.app( 7367): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7367): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5854): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5854): getCountryCode(): countryCode = PL
,D/Headlines( 5854): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5854): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5854): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5854): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5854): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5854): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5854): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 5922): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5124): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5124): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5124): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42278090
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId
,I/System.out( 7310): Thread-630(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables,
,I/System.out( 7310): Thread-630(ApacheHTTPLog):isShipBuild true
,I/System.out( 7310): Thread-630(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/hcjo    ( 5943): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5943): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5943): exit::IDLE
,D/InitializeManagerStateMachine( 5943): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5943): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5943): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5943): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5943): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5943): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5943): entry::SUCCESS
,D/hcjo    ( 5943): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5943): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5943): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5943): exit::SUCCESS
,D/InitializeManagerStateMachine( 5943): entry::IDLE
,E/SPPClientService( 5526): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5526): [SystemStateMoniter] Current Time : 269953
,E/SPPClientService( 5526): [SystemStateMoniter] No Connect : false
,I/System.out( 7310): AsyncTask #1 calls detatch()
,W/System.err( 7310): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7310): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7310): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7310): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7310): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7310): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 7310): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7310): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7310): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7310): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7310): Caused by: java.lang.NullPointerException
W/System.err( 7310): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7310): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7310): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7310): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7310): 	... 8 more
,I/ActivityManager( 2401): Killing 6179:com.google.android.music:main/u0a125 (adj 15): empty #43
,D/dalvikvm( 5526): GC_CONCURRENT freed 2009K, 24% free 10445K/13688K, paused 3ms+3ms, total 33ms
,D/dalvikvm( 5526): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/libgps  ( 2401): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2401): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2401): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/SA      ( 5791): [RC New] [v2liruge] api execute + 850
I/SA      ( 5791): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5791): AsyncTask #2 calls detatch()
,I/SA      ( 5791): [TPMU] getNetworkMcc : 
,I/SA      ( 5791): [SCU] saveMccToPreferece Start
,I/SA      ( 5791): [SCU] RegionMCC : 260
,I/SA      ( 5791): [SSP] query invoked
,I/SA      ( 5791): [TPMU] GetMccFromDB : null
I/SA      ( 5791): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5791): [SCU] saveMccToPreferece End
,I/SA      ( 5791): [RC New] executeRequest [v2liruge] end. 872
I/SA      ( 5791): [RC New] Execute end
I/SA      ( 5791): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5791): [OR] GetMyCountryZoneTask Success
,E/WifiStateMachine( 2401): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/SPPClientService( 5526): [b] __InitReply__
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (10/11)
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (-2/11)
I/ActivityManager( 2401): Killing 6509:com.android.defcontainer/u0a6 (adj 15): empty #43
D/PowerManagerService( 2401): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2401) eventTime = 272634
D/PowerManagerService( 2401): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2401 (0x0)
D/PowerManagerService( 2401): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2401, ws=WorkSource{1000}) (elapsedTime=3465)
,I/GAV2    ( 7395): Thread[GAThread,5,main]: No campaign data found.
,W/WifiP2pStateTracker( 2401): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2401): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2401):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2401): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2401): updateSourceRoutes : no source routing conditions
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6566): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6566): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6566): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6566): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6566): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6566): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6566): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6566): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6566): [ensureRegistration] - No Samsung account
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2401): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3996): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3996): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/CaptivePortalTracker( 2401): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 2401): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2401): Checking http://216.58.209.46/generate_204
,I/jxcore-log( 7219): Test app app.js loaded
I/jxcore-log( 7219): 
,I/chromium( 7219): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/PreloadUpdateManagerStateMachine( 5943): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5943): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5943): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5943): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5943): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5943): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5943): entry::IDLE
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 284, currTemp = 286, prevStep = 4, currStep = 4
,D/PreloadUpdateManagerStateMachine( 5943): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5943): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5943): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5943): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5943): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5943): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5943): entry::IDLE
,D/CaptivePortalTracker( 2401): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 2401): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2401): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2401): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2401): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/jxcore-log( 7219): --= Surplus to requirements =--
I/jxcore-log( 7219): 
,I/jxcore-log( 7219): ****TEST TOOK:  ms ****
I/jxcore-log( 7219): 
,I/jxcore-log( 7219): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7219): 
,I/ActivityManager( 2401): Waited long enough for: ServiceRecord{43cb7b30 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/AndroidRuntime( 7590): 
D/AndroidRuntime( 7590): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7590): CheckJNI is OFF
D/AndroidRuntime( 7590): setted country_code = Poland
D/AndroidRuntime( 7590): setted countryiso_code = PL
D/AndroidRuntime( 7590): setted sales_code = PLS
D/AndroidRuntime( 7590): readGMSProperty: start
D/AndroidRuntime( 7590): readGMSProperty: already setted!!
D/AndroidRuntime( 7590): readGMSProperty: end
D/AndroidRuntime( 7590): addProductProperty: start
D/dalvikvm( 7590): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7590): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7590): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7590): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7590): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,E/memtrack( 7590): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 7590): failed to load memtrack module: -2
,D/dalvikvm( 7590): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,D/AndroidRuntime( 7590): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 2401): START PACKAGE DELETE: observer{1124575344}
D/PackageManager( 2401): pkg{<packageName>}
D/PackageManager( 2401): user{0}
,D/PackageManager( 2401): deletePackageAsUser : uid = 2000 userId = 0
,D/ApplicationPolicy( 2401): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2401): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService( 2401): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2401): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManager( 2401): !@killApplicatoin: 10605, uninstall pkg
,I/ActivityManager( 2401): Killing 7219:com.test.thalitest/u0a605 (adj 0): stop com.test.thalitest
,D/CustomFrequencyManagerService( 2401): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2401): mDVFSHelper.acquire()
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (-2/10)
,I/WindowState( 2401): WIN DEATH: Window{43055cb8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1920): id=19 Removed NainActivit (-2/10)
D/PointerIcon( 2401): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2401): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2401): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2401): setHoveringSpenCustomIcon IconType is same.1
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/PackageSettings( 2401): Skipping PackageSetting{42475f30 com.example.hello/10600} due to missing metadata
,D/PackageManager( 2401): setPackageStoppedState - Execution time: 101 ms
D/PackageManager( 2401): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10605, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/dalvikvm( 6410): GC_EXPLICIT freed 2495K, 28% free 9884K/13700K, paused 3ms+4ms, total 55ms
,D/dalvikvm( 6726): GC_EXPLICIT freed 159K, 29% free 9958K/13936K, paused 3ms+4ms, total 51ms
,D/PackageManager( 2401): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10605, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/DBG_DM  ( 4728): [3.19.140541][Line:408][onResume] 
,I/FPMS_FingerprintManagerService( 2600): onReceive: android.intent.action.PACKAGE_REMOVED
,E/SamsungIME( 3001): mOCRHelper is null
,D/QuickConnect[1.1][2] ( 5124): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
,D/dalvikvm( 2954): GC_EXPLICIT freed 1472K, 27% free 10036K/13696K, paused 8ms+5ms, total 113ms
,D/dalvikvm( 3446): GC_EXPLICIT freed 1735K, 21% free 12399K/15596K, paused 10ms+12ms, total 143ms
W/GeofencerStateMachine( 2736): Ignoring removeGeofence because network location is disabled.
,I/InputReader( 2401): Reconfiguring input devices.  changes=0x00000010
,I/DBG_DM  ( 4728): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
,W/SQLiteConnectionPool( 3446): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "sms"
,I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 7619): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7619):  
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "smsto"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 7619): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7619):  
I/SELinux ( 7619):  
,I/SELinux ( 7619): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7619): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7619): >>>>> Normal User
,E/dalvikvm( 7619): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 7619): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/DBG_DM  ( 4728): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "mms"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4728): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4728): [3.19.140541][Line:418][onResume] Postpone Count : 29
,D/TimaKeyStoreProvider( 7619): in addTimaSignatureService
,I/DBG_DM  ( 4728): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,D/TimaKeyStoreProvider( 7619): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7619): Added TimaKesytore provider
,D/dalvikvm( 2401): GC_EXPLICIT freed 2560K, 74% free 25043K/96300K, paused 13ms+28ms, total 257ms
,D/PackageManager( 2401): queryIntentReceivers - Execution time: 130 ms
,I/DBG_DM  ( 4728): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "mmsto"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4728): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "sms"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/RCPManagerService( 2401): PackageReceiver onReceive()
,I/HarmonyEASService( 2401): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/DBG_DM  ( 4728): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "smsto"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4728): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,D/RegisteredServicesCache( 2760): empty dynamic service
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "mms"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4728): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4728): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4728): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4728): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4728): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
D/dalvikvm( 7619): GC_CONCURRENT freed 2993K, 31% free 9576K/13696K, paused 3ms+2ms, total 38ms
,D/dalvikvm( 7619): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/Activity( 4728): setTransGradationMode to true
,D/PhoneStatusBar( 2580): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/DBG_DM  ( 4728): [3.19.140541][Line:400][onPause] 
D/StatusBarManagerService( 2401): semi p:4728,o:t
,I/SurfaceFlinger( 1920): id=21 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2401): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "mmsto"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/PointerIcon( 2401): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2401): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2401): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2401): setHoveringSpenCustomIcon IconType is same.1
D/STATUSBAR-StatusBarManagerService( 2401): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/elm:14132( 7619): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14132( 7619): ELMEngine.ELMEngine( context ).
,D/elm:14132( 7619): MDMBridge.setEnterpriseBridge()
W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 2401): Got RemoteException sending setActive(false) notification to pid 7219 uid 10605
,D/elm:14132( 7619): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14132( 7619): ElmAgentService : onCreate()
D/elm:14132( 7619): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14132( 7619): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 7619): MDMBridge.getInstance()
,D/elm:14132( 7619): MDMBridge.getAllLicenseInfoFromSDK()
,I/SELinux ( 7634): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7634):  
,D/elm:14132( 7619): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux ( 7634): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7634):  
I/SELinux ( 7634):  
,I/SELinux ( 7634): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7634): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7634): >>>>> Normal User
,E/dalvikvm( 7634): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,E/SELinux ( 7634): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7634): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7634): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7634): Added TimaKesytore provider
,D/elm:14132( 7619): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
,D/EnterpriseDeviceManagerService( 2401): Package has changed for user 0
,D/dalvikvm( 2760): GC_CONCURRENT freed 2336K, 26% free 10254K/13712K, paused 6ms+3ms, total 102ms
,D/elm:14132( 7619): ElmAgentService : onDestroy().
D/CustomFrequencyManagerService( 2401): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2401): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2401): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  pkgName : ACTIVITY_RESUME_BOOSTER@8
I/ActivityManager( 2401): Killing 6430:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,D/BackupManagerService( 2401): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 2401): removePackageParticipantsLocked: uid=10605 #1
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2401): sendNotification(2) - 4
,D/dalvikvm( 7634): GC_CONCURRENT freed 2997K, 31% free 9568K/13696K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 7634): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/ActivityManager( 2401): Waited long enough for: ServiceRecord{447207f0 u0 com.sec.spp.push/.PushClientService}
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 2401): GC_EXPLICIT freed 1026K, 74% free 25193K/96300K, paused 11ms+33ms, total 451ms
D/PackageManager( 2401): delete sourFile : 
,D/PackageManager( 2401): delete native library directory: 
D/PackageManager( 2401): return delete result to caller: 1124575344
,D/AndroidRuntime( 7590): Shutting down VM
,D/PackageManager( 2401): returnCode: 1
D/dalvikvm( 7590): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 0ms+1ms, total 3ms
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "sms"
,I/SELinux ( 7649): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7649):  
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/ActivityManager( 2401): Killing 6538:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/SELinux ( 7649): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7649):  
I/SELinux ( 7649):  
,I/SELinux ( 7649): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7649): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7649): >>>>> Normal User
,E/dalvikvm( 7649): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
,E/SELinux ( 7649): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "smsto"
,D/TimaKeyStoreProvider( 7649): in addTimaSignatureService
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 7649): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7649): Added TimaKesytore provider
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "mms"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "mmsto"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 7649): GC_CONCURRENT freed 3000K, 31% free 9567K/13696K, paused 2ms+1ms, total 28ms
,D/dalvikvm( 7649): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PCWCLIENTTRACE_PushUtil( 6566): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6566): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6566): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6566): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/SA      ( 5791): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5791): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/Icing.InternalIcingCorporaProvider( 6410): Updating corpora: A: com.test.thalitest, C: MAYBE
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ApplicationsProvider( 2954): Could not fetch usage stats
W/ApplicationsProvider( 2954): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2954): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2954): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2954): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2954): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2954): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2954): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2954): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2954): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2954): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2954): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2954): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SELinux ( 7670): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7670):  
,E/SQLiteLog( 2939): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 11% free 9502K/10672K, paused 2ms+3ms, total 31ms
,E/DatabaseUtils( 2939): Writing exception to parcel
E/DatabaseUtils( 2939): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DatabaseUtils( 2939): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DatabaseUtils( 2939): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/DatabaseUtils( 2939): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DatabaseUtils( 2939): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DatabaseUtils( 2939): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/DatabaseUtils( 2939): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/DatabaseUtils( 2939): 	at com.sec.android.provider.logsprovider.LogsProvider.delete(LogsProvider.java:3022)
E/DatabaseUtils( 2939): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/DatabaseUtils( 2939): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:199)
E/DatabaseUtils( 2939): 	at android.os.Binder.execTransact(Binder.java:404)
E/DatabaseUtils( 2939): 	at dalvik.system.NativeStart.run(Native Method)
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/dalvikvm( 2954): threadid=14: thread exiting with uncaught exception (group=0x4180ac08)
,I/SELinux ( 7670): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7670):  
I/SELinux ( 7670):  
,E/AndroidRuntime( 2954): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime( 2954): Process: android.process.acore, PID: 2954
E/AndroidRuntime( 2954): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2954): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
E/AndroidRuntime( 2954): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
E/AndroidRuntime( 2954): 	at android.content.ContentProviderProxy.delete(ContentProviderNative.java:536)
E/AndroidRuntime( 2954): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 2954): 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:474)
E/AndroidRuntime( 2954): 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:130)
E/AndroidRuntime( 2954): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 2954): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 2954): 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/AndroidRuntime( 2954): 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime( 2954): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2954): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2954): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2954): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SELinux ( 7670): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7670): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7670): >>>>> Normal User
E/dalvikvm( 7670): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
E/SELinux ( 7670): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9502K/10672K, paused 2ms+3ms, total 24ms
,I/Process ( 2954): Sending signal. PID: 2954 SIG: 9
E/DropBoxManagerService( 2401): Can't write: system_app_crash
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
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9502K/10672K, paused 2ms+3ms, total 24ms
D/TimaKeyStoreProvider( 7670): in addTimaSignatureService
E/SQLiteLog( 6410): (10) unixWrite() gets errno : 9
E/SQLiteLog( 6410): (10) unixWrite() gets errno : 9
W/dalvikvm( 6410): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
D/TimaKeyStoreProvider( 7670): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7670): Added TimaKesytore provider
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/ActivityManager( 2401): Process android.process.acore (pid 2954) (adj -12) has died.
E/AndroidRuntime( 6410): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 6410): Process: com.google.android.googlequicksearchbox:search, PID: 6410
E/AndroidRuntime( 6410): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AndroidRuntime( 6410): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6410): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 6410): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
E/AndroidRuntime( 6410): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
E/AndroidRuntime( 6410): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:524)
E/AndroidRuntime( 6410): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:248)
E/AndroidRuntime( 6410): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 6410): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
E/AndroidRuntime( 6410): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 6410): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 6410): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 6410): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 6410): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 6410): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 6410): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 6410): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6410): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6410): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6410): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SELinux ( 7683): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7683):  
I/CrashAnrDetector( 2401): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2401): clearDefaults: com.test.thalitest
I/Process ( 6410): Sending signal. PID: 6410 SIG: 9
E/DropBoxManagerService( 2401): Can't write: system_app_crash
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
,I/ActivityManager( 2401): Process com.google.android.googlequicksearchbox:search (pid 6410) (adj 5) has died.
,W/AtomicFile( 2401): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl( 2401): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/SELinux ( 7683): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7683):  
I/SELinux ( 7683):  
,I/SELinux ( 7683): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7683): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7683): >>>>> Normal User
,E/dalvikvm( 7683): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7683): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7683): in addTimaSignatureService
D/dalvikvm( 7670): GC_CONCURRENT freed 2997K, 31% free 9569K/13696K, paused 4ms+1ms, total 28ms
,D/dalvikvm( 7670): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/TimaKeyStoreProvider( 7683): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7683): Added TimaKesytore provider
,D/dalvikvm( 7683): GC_CONCURRENT freed 2990K, 31% free 9576K/13696K, paused 2ms+1ms, total 21ms
,D/dalvikvm( 7683): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/UserAnalysis.PlaceProvider( 7670): Create SecureDbHelper
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 7670): Create SecureDbHelper
,E/SQLiteDatabase( 7670): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7670): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7670): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7670): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7670): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7670): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7670): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteDatabase( 7670): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7670): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7670): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7670): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7670): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7670): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7670): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7670): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7670): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7670): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7670): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7670): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7670): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7670): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7670): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7670): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7670): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7670): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7670): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7670): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7670): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7670): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7670): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7670): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7670): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7670): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7670): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7670): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7670): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7670): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteOpenHelper( 7670): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7670): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7670): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7670): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7670): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7670): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7670): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7670): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7670): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7670): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7670): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7670): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 7670): Opened privacy in read-only mode
E/SQLiteDatabase( 7670): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7670): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7670): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7670): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7670): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7670): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7670): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteDatabase( 7670): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7670): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7670): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7670): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7670): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7670): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7670): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7670): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7670): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7670): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7670): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7670): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 7670): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7670): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7670): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7670): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7670): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7670): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7670): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7670): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7670): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7670): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7670): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7670): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7670): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7670): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7670): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7670): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7670): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7670): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteOpenHelper( 7670): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7670): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7670): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7670): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7670): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7670): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7670): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7670): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7670): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7670): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7670): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7670): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 7670): Opened privacy in read-only mode
E/SQLiteDatabase( 7670): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7670): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7670): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7670): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7670): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7670): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7670): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
E/SQLiteDatabase( 7670): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7670): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7670): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7670): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7670): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7670): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7670): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7670): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7670): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7670): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7670): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7670): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 7670): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 7670): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 7670): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 7670): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 7670): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 7670): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 7670): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 7670): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 7670): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 7670): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 7670): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 7670): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7670): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7670): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 7670): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 7670): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
W/System.err( 7670): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
W/System.err( 7670): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 7670): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 7670): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 7670): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7670): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 7670): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 7670): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 7670): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 7670): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 7670): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 7670): 	at dalvik.system.NativeStart.main(Native Method)
,W/ContextImpl( 6345): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:165 android.app.ActivityThread.handleReceiver:2698 
D/RCPManager( 6424):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2401):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2401): queryAllProviders():  providerCallBack is not register for 0
D/CapabilityManagerService New( 6635): Receiver Broadcast:android.intent.action.PACKAGE_REMOVED
D/CapabilityManagerService New( 6635): The package(com.test.thalitest) removed
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
E/SQLiteDatabase( 6345): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 6345): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6345): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6345): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6345): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6345): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6345): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6345): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6345): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6345): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6345): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6345): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6345): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6345): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6345): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6345): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 6345): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 6345): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6345): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6345): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6345): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 2401): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2401): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2401): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2401): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2401): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 6345): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 2401): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2401): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 6345): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 2401): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 2401): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2401): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2401): 	... 8 more
W/System.err( 6345): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 6345): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 6345): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 6345): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 6345): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 6345): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 6345): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 6345): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 6345): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 6345): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 6345): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 6345): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 6345): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 6345): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 6345): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 6345): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6345): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6345): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/MagazineService::MagazineBroadcastReceiver( 6662): [onReceive] android.intent.action.PACKAGE_REMOVED com.test.thalitest
,I/MagazineService::MagazineService( 6662): [onHandleIntent] ACTION_PACKAGE_REMOVED
,E/SQLiteDatabase( 6662): Failed to open database '/data/data/com.samsung.android.app.headlines/databases/card.db'.
E/SQLiteDatabase( 6662): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6662): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6662): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6662): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6662): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6662): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6662): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6662): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6662): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6662): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6662): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6662): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6662): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6662): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6662): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/SQLiteDatabase( 6662): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/SQLiteDatabase( 6662): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/SQLiteDatabase( 6662): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/SQLiteDatabase( 6662): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6662): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6662): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6662): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 6662): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
I/SELinux ( 7700): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7700):  
,E/AndroidRuntime( 6662): FATAL EXCEPTION: IntentService[MagazineService::MagazineService]
E/AndroidRuntime( 6662): Process: com.samsung.android.magazine.service, PID: 6662
E/AndroidRuntime( 6662): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6662): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6662): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 6662): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 6662): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6662): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6662): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6662): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 6662): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 6662): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 6662): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 6662): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 6662): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 6662): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 6662): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/AndroidRuntime( 6662): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6662): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6662): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/AndroidRuntime( 6662): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6662): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6662): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6662): 	at android.os.HandlerThread.run(HandlerThread.java:61)
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
I/Process ( 6662): Sending signal. PID: 6662 SIG: 9
,I/ActivityManager( 2401): Process com.samsung.android.magazine.service (pid 6662) (adj 5) has died.
,E/SQLiteDatabase( 7683): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7683): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7683): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7683): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7683): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7683): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7683): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7683): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7683): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7683): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7683): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 7683): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7683): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7683): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7683): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7683): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7683): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7683): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7683): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7683): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7683): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7683): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7683): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7683): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7683): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7683): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7683): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7683): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7683): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7683): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7683): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7683): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7683): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 7683): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7683): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7683): (14) unable to open database file
E/SQLiteDatabase( 7683): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7683): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7683): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7683): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7683): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7683): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7683): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7683): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7683): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7683): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
I/SELinux ( 7700): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7700):  
I/SELinux ( 7700):  
,I/SELinux ( 7700): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/AndroidRuntime( 7683): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7683): Process: android.process.acore, PID: 7683
E/AndroidRuntime( 7683): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7683): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7683): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7683): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7683): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7683): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7683): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7683): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SELinux ( 7700): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7700): >>>>> Normal User
,E/dalvikvm( 7700): >>>>> com.android.keychain [ userId:0 | appId:1000 ]
,I/Process ( 7683): Sending signal. PID: 7683 SIG: 9
,E/SELinux ( 7700): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/ActivityManager( 2401): Process android.process.acore has crashed too many times: killing!
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
,I/ActivityManager( 2401): Process android.process.acore (pid 7683) (adj -12) has died.
,D/TimaKeyStoreProvider( 7700): in addTimaSignatureService
,F/ActivityManager( 2401): Service ServiceRecord{456e6fe0 u0 com.android.providers.contacts/.VoicemailCleanupService} in process ProcessRecord{4257d890 7683:android.process.acore/u0a20} not same as in map: null
,D/TimaKeyStoreProvider( 7700): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7700): Added TimaKesytore provider
E/DropBoxManagerService( 2401): Can't write: system_server_wtf
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop165.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2401): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2401): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2401): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2401): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2401): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2401): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2401): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2401): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2401): 	at android.util.Slog.wtf(Slog.java:163)
E/DropBoxManagerService( 2401): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2151)
E/DropBoxManagerService( 2401): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15153)
E/DropBoxManagerService( 2401): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4944)
E/DropBoxManagerService( 2401): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5122)
E/DropBoxManagerService( 2401): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1322)
E/DropBoxManagerService( 2401): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:493)
E/DropBoxManagerService( 2401): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2401): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2401): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2401): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2401): 	... 18 more
,I/SELinux ( 7717): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7717):  
,I/SELinux ( 7717): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7717):  
I/SELinux ( 7717):  
,I/SELinux ( 7717): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7717): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7717): >>>>> Normal User
,E/dalvikvm( 7717): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7717): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/dalvikvm( 7700): GC_CONCURRENT freed 2993K, 31% free 9572K/13696K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 7700): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/TimaKeyStoreProvider( 7717): in addTimaSignatureService
,D/CustomFrequencyManagerService( 2401): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  tag : ACTIVITY_RESUME_BOOSTER@8
D/TimaKeyStoreProvider( 7717): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7717): Added TimaKesytore provider
W/ContextImpl( 7700): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2698 
,E/SQLiteDatabase( 7700): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 7700): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7700): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7700): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7700): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7700): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7700): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7700): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7700): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7700): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7700): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7700): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7700): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7700): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7700): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7700): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/SQLiteDatabase( 7700): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/SQLiteDatabase( 7700): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7700): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7700): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7700): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7700): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,D/KidsModeInstallReceiver( 6688): onReceive intent data =  package:com.test.thalitest
,D/KidsPlatformStub( 6688): Package not found : com.sec.android.app.kidshome
E/AndroidRuntime( 7700): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 7700): Process: com.android.keychain, PID: 7700
E/AndroidRuntime( 7700): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7700): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7700): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7700): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7700): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7700): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7700): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7700): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7700): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7700): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7700): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7700): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7700): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7700): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7700): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/AndroidRuntime( 7700): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/AndroidRuntime( 7700): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7700): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7700): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7700): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/System.err( 6726): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6726): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
W/System.err( 6726): 	at com.n7mobile.promenada2.applications.ApplicationInstallationReceiver.onReceive(SourceFile:27)
W/System.err( 6726): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 6726): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 6726): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 6726): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6726): 	at android.os.Looper.loop(Looper.java:146)
,I/Process ( 7700): Sending signal. PID: 7700 SIG: 9
,W/System.err( 6726): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
,W/System.err( 6726): 	at java.lang.reflect.Method.invokeNative(Native Method)
,W/System.err( 6726): 	at java.lang.reflect.Method.invoke(Method.java:515)
,W/System.err( 6726): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 6726): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 6726): 	at dalvik.system.NativeStart.main(Native Method)
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop224.tmp: open failed: EROFS (Read-only file system)
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
,D/dalvikvm( 7717): GC_CONCURRENT freed 2998K, 31% free 9569K/13696K, paused 2ms+3ms, total 22ms
,D/dalvikvm( 7717): WAIT_FOR_CONCURRENT_GC blocked 18ms
I/ActivityManager( 2401): Process com.android.keychain (pid 7700) (adj 5) has died.
,D/PackageBroadcastService( 3446): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 3446): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 3446): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3446): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 3446): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3446): Module APK com.google.android.play.games already loaded
,E/SQLiteLog( 3446): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,I/LocationSettingsChecker( 3446): Removing dialog suppression flag for package com.test.thalitest
,E/SQLiteLog( 3446): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/dalvikvm( 3446): threadid=47: thread exiting with uncaught exception (group=0x4180ac08)
,E/SQLiteLog( 2858): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 2858): Shutting down VM
,W/dalvikvm( 2858): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 2858): FATAL EXCEPTION: main
E/AndroidRuntime( 2858): Process: com.google.process.gapps, PID: 2858
E/AndroidRuntime( 2858): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2858): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 2858): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 2858): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 2858): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2858): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2858): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 2858): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2858): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2858): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 2858): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 2858): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2858): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2858): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2858): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 2858): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2858): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2858): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 2858): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 2858): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 2858): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 2858): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 2858): 	... 10 more
E/DriveAsyncService( 3446): disk I/O error (code 3850)
E/DriveAsyncService( 3446): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 3446): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 3446): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/DriveAsyncService( 3446): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 3446): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 3446): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/DriveAsyncService( 3446): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/DriveAsyncService( 3446): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 3446): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 3446): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 3446): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 3446): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 3446): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 3446): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 3446): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 3446): 	at java.lang.Thread.run(T,hread.java:841)
,E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop225.tmp: open failed: EROFS (Read-only file system)
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
,I/Process ( 2858): Sending signal. PID: 2858 SIG: 9
,E/SQLiteLog( 3446): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDatabase( 5526): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
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
E/SQLiteDatabase( 5526): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
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
,E/SPPClientService( 5526): [d] [getAppId()] Exception with message =not an error (code 0): Could not open the database in read/write mode.
,E/SQLiteDatabase( 3446): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 3446): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3446): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3446): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3446): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3446): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3446): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3446): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3446): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3446): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3446): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3446): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3446): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3446): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3446): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3446): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3446): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 3446): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3446): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3446): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3446): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AndroidRuntime( 3446): FATAL EXCEPTION: PlayGamesAsyncThread2
E/AndroidRuntime( 3446): Process: com.google.android.gms, PID: 3446
E/AndroidRuntime( 3446): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3446): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 3446): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 3446): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 3446): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 3446): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 3446): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
E/AndroidRuntime( 3446): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 3446): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 3446): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 3446): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 3446): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 3446): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 3446): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 3446): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 3446): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 3446): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 3446): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 3446): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 6386): Failed to open database '/data/data/com.sec.spp.push/databases/evtDb'.
E/SQLiteDatabase( 6386): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6386): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6386): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6386): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6386): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6386): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6386): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6386): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6386): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6386): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6386): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6386): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6386): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6386): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6386): 	at com.sec.spp.push.notisvc.tracking.h.b(Unknown Source)
E/SQLiteDatabase( 6386): 	at com.sec.spp.push.notisvc.tracking.g.a(Unknown Source)
E/SQLit,eDatabase( 6386): 	at com.sec.spp.push.notisvc.tracking.f.a(Unknown Source)
E/SQLiteDatabase( 6386): 	at com.sec.spp.push.notisvc.tracking.a.c(Unknown Source)
E/SQLiteDatabase( 6386): 	at com.sec.spp.push.notisvc.tracking.a.a(Unknown Source)
E/SQLiteDatabase( 6386): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6386): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6386): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6386): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6386): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6386): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6386): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6386): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6386): 	at dalvik.system.NativeStart.main(Native Method)
E/LNoti   ( 6386): [g] not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 3446): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 3446): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 3446): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 3446): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/PhenotypeInitializer( 3446): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/PhenotypeInitializer( 3446): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 3446): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 3446): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 3446): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/PhenotypeInitializer( 3446): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/PhenotypeInitializer( 3446): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/PhenotypeInitializer( 3446): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/PhenotypeInitializer( 3446): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3446): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3446): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 3446): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 3446): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 3446): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 3446): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 3446): 	at android.os.Looper.loop(Looper.java:146)
E/PhenotypeInitializer( 3446): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SELinux ( 7744): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7744):  
,E/ClearPendingStateOp( 3446): Runtime exception while performing operation
E/ClearPendingStateOp( 3446): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 3446): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 3446): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/ClearPendingStateOp( 3446): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 3446): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 3446): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/ClearPendingStateOp( 3446): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
E/ClearPendingStateOp( 3446): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 3446): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 3446): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/ClearPendingStateOp( 3446): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/ClearPendingStateOp( 3446): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 3446): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 3446): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 3446): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 3446): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 3446): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 3446): 	at java.lang.Thread.run(Thread.java:841)
,I/ActivityManager( 2401): Process com.google.process.gapps (pid 2858) (adj 5) has died.
F/ClearPendingStateOp( 3446): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 3446): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 3446): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 3446): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
F/ClearPendingStateOp( 3446): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 3446): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 3446): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
F/ClearPendingStateOp( 3446): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
F/ClearPendingStateOp( 3446): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 3446): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 3446): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
F/ClearPendingStateOp( 3446): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
F/ClearPendingStateOp( 3446): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 3446): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 3446): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 3446): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 3446): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 3446): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 3446): 	at java.lang.Thread.run(Thread.java:841)
,I/Process ( 3446): Sending signal. PID: 3446 SIG: 9
E/DropBoxManagerService( 2401): Can't write: system_app_crash
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
,E/SQLiteDatabase( 6386): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 6386): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6386): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6386): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6386): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6386): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6386): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6386): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6386): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6386): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6386): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6386): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6386): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6386): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6386): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6386): 	at com.sec.spp.push.notisvc.b.b.<init>(Unknown Source)
E/SQLiteDatabase( 6386): 	at com.sec.spp.push.notisvc.b.b.a(Unknown Source)
E/SQLiteDatabase( 6386): 	at com.sec.spp.push.notisvc.registration.q.b(Unknown Source)
E/SQLiteDatabase( 6386): 	at com.sec.spp.push.notisvc.registration.q.a(Unknown Source)
E/SQLiteDatabase( 6386): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6386): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6386): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6386): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6386): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6386): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6386): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6386): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6386): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6386): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6386): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6386): [b] open fail. android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,I/SELinux ( 7744): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7744):  
I/SELinux ( 7744):  
,I/SELinux ( 7744): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7744): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7744): >>>>> Normal User
,E/dalvikvm( 7744): >>>>> com.android.documentsui [ userId:0 | appId:10093 ]
,E/SELinux ( 7744): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager( 2401): Process com.google.android.gms (pid 3446) (adj 5) has died.
,E/SQLiteDatabase( 7717): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7717): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7717): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7717): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7717): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7717): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7717): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7717): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7717): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7717): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7717): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 7717): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7717): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7717): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7717): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7717): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7717): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7717): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7717): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7717): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7717): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7717): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7717): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7717): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7717): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7717): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7717): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7717): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7717): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7717): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7717): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7717): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7717): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 7717): (14) cannot open file at line 31285 of [00bb9c9ce4]
,D/TimaKeyStoreProvider( 7744): in addTimaSignatureService
E/SQLiteLog( 7717): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7717): (14) unable to open database file
,E/SQLiteDatabase( 7717): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7717): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7717): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7717): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7717): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7717): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7717): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7717): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7717): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7717): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7717): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
,D/TimaKeyStoreProvider( 7744): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7744): Added TimaKesytore provider
,D/GAV2    ( 5616): Thread[main,5,main]: service disconnected: ComponentInfo{com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService}
E/AndroidRuntime( 7717): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7717): Process: android.process.acore, PID: 7717
E/AndroidRuntime( 7717): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7717): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7717): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7717): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7717): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7717): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7717): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7717): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7717): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7717): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7717): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7717): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7717): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7717): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7717): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7717): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7717): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7717): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7717): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7717): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7717): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7717): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 2401): Process android.process.acore has crashed too many times: killing!
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
,I/Process ( 7717): Sending signal. PID: 7717 SIG: 9
,I/GAV2    ( 5616): Thread[main,5,main]: Unexpected disconnect.
,I/ActivityManager( 2401): Process android.process.acore (pid 7717) (adj -12) has died.
,I/SELinux ( 7764): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7764):  
,D/dalvikvm( 7744): GC_CONCURRENT freed 3001K, 31% free 9568K/13700K, paused 3ms+2ms, total 19ms
,D/dalvikvm( 7744): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/SELinux ( 7764): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7764):  
I/SELinux ( 7764):  
,I/SELinux ( 7764): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7764): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7764): >>>>> Normal User
,E/dalvikvm( 7764): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7764): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/Documents( 7744): Loading roots for com.android.externalstorage.documents
,D/TimaKeyStoreProvider( 7764): in addTimaSignatureService
,E/SQLiteDatabase( 7744): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 7744): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7744): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7744): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7744): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7744): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7744): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7744): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7744): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7744): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7744): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7744): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7744): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7744): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7744): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7744): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 7744): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 7744): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 7744): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/SQLiteDatabase( 7744): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 7744): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7744): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7744): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7744): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7744): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7744): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7744): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7744): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7744): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7744): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7744): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7744): Shutting down VM
,W/dalvikvm( 7744): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,I/SELinux ( 7777): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7777):  
,D/TimaKeyStoreProvider( 7764): Cannot add TimaSignature Service, License check Failed
,E/AndroidRuntime( 7744): FATAL EXCEPTION: main
E/AndroidRuntime( 7744): Process: com.android.documentsui, PID: 7744
E/AndroidRuntime( 7744): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7744): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 7744): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 7744): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7744): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7744): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7744): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7744): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7744): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7744): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7744): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7744): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7744): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7744): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7744): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7744): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7744): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7744): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7744): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7744): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7744): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7744): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7744): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7744): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7744): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7744): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7744): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 7744): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 7744): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 7744): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/AndroidRuntime( 7744): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 7744): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 7744): 	... 10 more
D/ActivityThread( 7764): Added TimaKesytore provider
,I/SELinux ( 7781): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7781):  
I/ActivityManager( 2401): Killing 5685:com.android.mms/u0a49 (adj 15): empty #43
,I/Process ( 7744): Sending signal. PID: 7744 SIG: 9
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
,D/CountryDetector( 2401): No listener is left
,I/SELinux ( 7777): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7777):  
I/SELinux ( 7777):  
,I/SELinux ( 7777): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7777): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7777): >>>>> Normal User
,E/dalvikvm( 7777): >>>>> com.android.externalstorage [ userId:0 | appId:10009 ]
,E/SELinux ( 7777): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager( 2401): Process com.android.documentsui (pid 7744) (adj 9) has died.
,I/SELinux ( 7781): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7781):  
I/SELinux ( 7781):  
,I/SELinux ( 7781): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7781): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7781): >>>>> Normal User
,E/dalvikvm( 7781): >>>>> com.google.android.gms [ userId:0 | appId:10012 ]
,E/SELinux ( 7781): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7777): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7777): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7777): Added TimaKesytore provider
,D/dalvikvm( 7764): GC_CONCURRENT freed 2998K, 31% free 9569K/13696K, paused 2ms+1ms, total 21ms
,D/dalvikvm( 7764): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/TimaKeyStoreProvider( 7781): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7781): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7781): Added TimaKesytore provider
,D/dalvikvm( 7777): GC_CONCURRENT freed 3002K, 31% free 9565K/13696K, paused 4ms+1ms, total 21ms
,D/dalvikvm( 7777): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/ExternalStorage( 7777): After updating volumes, found 1 active roots
D/dalvikvm( 7781): GC_CONCURRENT freed 2947K, 30% free 9623K/13700K, paused 3ms+2ms, total 21ms
,D/dalvikvm( 7781): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/dalvikvm( 7781): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7781): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 7781): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 7781): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
D/dalvikvm( 7781): VFY: replacing opcode 0x6e at 0x00cd
,E/SQLiteDatabase( 7764): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7764): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7764): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7764): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7764): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7764): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7764): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7764): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7764): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7764): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7764): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 7764): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7764): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7764): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7764): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7764): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7764): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7764): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7764): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7764): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7764): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7764): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7764): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7764): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7764): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7764): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7764): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7764): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7764): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 7764): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7764): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7764): (14) unable to open database file
E/SQLiteDatabase( 7764): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7764): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7764): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7764): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7764): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7764): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7764): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7764): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7764): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7764): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7764): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7764): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7764): Process: android.process.acore, PID: 7764
E/AndroidRuntime( 7764): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7764): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7764): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7764): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7764): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7764): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7764): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7764): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7764): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 7781): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7781): install
,I/Process ( 7764): Sending signal. PID: 7764 SIG: 9
W/ActivityManager( 2401): Process android.process.acore has crashed too many times: killing!
,E/DropBoxManagerService( 2401): Can't write: system_app_crash
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
I/MultiDex( 7781): MultiDexExtractor.load(/data/app/com.google.android.gms-5.apk, false)
,I/ActivityManager( 2401): Process android.process.acore (pid 7764) (adj -12) has died.
I/MultiDex( 7781): loading existing secondary dex files
I/MultiDex( 7781): load found 3 secondary dex files
I/SELinux ( 7808): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7808):  
,I/MultiDex( 7781): install done
,I/SELinux ( 7808): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7808):  
I/SELinux ( 7808):  
,I/SELinux ( 7808): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7808): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7808): >>>>> Normal User
,E/dalvikvm( 7808): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7808): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7808): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7808): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7808): Added TimaKesytore provider
,I/SELinux ( 7820): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7820):  
,D/dalvikvm( 7808): GC_CONCURRENT freed 2992K, 31% free 9576K/13696K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 7808): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/SELinux ( 7820): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7820):  
I/SELinux ( 7820):  
,I/SELinux ( 7820): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7820): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7820): >>>>> Normal User
,E/dalvikvm( 7820): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 7820): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7820): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7820): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7820): Added TimaKesytore provider
,E/SQLiteDatabase( 7808): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7808): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7808): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7808): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7808): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7808): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7808): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7808): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7808): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7808): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7808): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 7808): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7808): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7808): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7808): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7808): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7808): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7808): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7808): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7808): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7808): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7808): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7808): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7808): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7808): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7808): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7808): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7808): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7808): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7808): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7808): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7808): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7808): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 7808): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7808): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7808): (14) unable to open database file
E/SQLiteDatabase( 7808): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7808): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7808): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7808): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7808): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7808): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7808): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7808): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7808): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7808): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7808): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7808): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7808): Process: android.process.acore, PID: 7808
E/AndroidRuntime( 7808): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7808): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7808): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7808): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7808): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7808): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7808): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7808): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7808): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7808): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7808): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7808): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7808): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7808): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7808): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7808): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7808): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7808): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7808): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7808): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7808): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7808): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 2401): Process android.process.acore has crashed too many times: killing!
,I/Process ( 7808): Sending signal. PID: 7808 SIG: 9
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
,D/dalvikvm( 7820): GC_CONCURRENT freed 2990K, 31% free 9576K/13696K, paused 4ms+2ms, total 23ms
,D/dalvikvm( 7820): WAIT_FOR_CONCURRENT_GC blocked 13ms
I/ActivityManager( 2401): Process android.process.acore (pid 7808) (adj -12) has died.
,I/SELinux ( 7838): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7838):  
,I/Icing.InternalIcingCorporaProvider( 7820): Updating corpora: A: com.test.thalitest, C: MAYBE
,I/SELinux ( 7845): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7845):  
,I/SELinux ( 7838): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7838):  
I/SELinux ( 7838):  
,I/SELinux ( 7838): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7838): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7838): >>>>> Normal User
,E/dalvikvm( 7838): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7838): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7838): in addTimaSignatureService
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 11% free 9502K/10672K, paused 2ms+3ms, total 30ms
,D/TimaKeyStoreProvider( 7838): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7838): Added TimaKesytore provider
I/SELinux ( 7845): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7845):  
I/SELinux ( 7845):  
,I/SELinux ( 7845): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7845): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7845): >>>>> Normal User
,E/dalvikvm( 7845): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7845): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9502K/10672K, paused 2ms+3ms, total 24ms
,D/TimaKeyStoreProvider( 7845): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7845): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7845): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9502K/10672K, paused 2ms+3ms, total 22ms
,I/SELinux ( 7867): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7867):  
,D/LocationManagerService( 2401): getProviders()=[passive]
,I/SELinux ( 7867): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7867):  
I/SELinux ( 7867):  
,I/SELinux ( 7867): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7867): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7867): >>>>> Normal User
,E/dalvikvm( 7867): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 7867): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7867): in addTimaSignatureService
D/dalvikvm( 7838): GC_CONCURRENT freed 3000K, 31% free 9569K/13696K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 7838): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/TimaKeyStoreProvider( 7867): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7867): Added TimaKesytore provider
,D/dalvikvm( 7845): GC_CONCURRENT freed 2980K, 30% free 9591K/13700K, paused 2ms+1ms, total 23ms
,D/dalvikvm( 7845): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 7867): GC_CONCURRENT freed 3008K, 31% free 9567K/13700K, paused 3ms+2ms, total 20ms
,D/dalvikvm( 7867): WAIT_FOR_CONCURRENT_GC blocked 11ms
,E/SQLiteDatabase( 7838): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7838): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7838): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7838): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7838): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7838): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7838): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7838): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7838): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7838): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7838): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 7838): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7838): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7838): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7838): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7838): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7838): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7838): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7838): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7838): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7838): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7838): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7838): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7838): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7838): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7838): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7838): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7838): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7838): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7838): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7838): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7838): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7838): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 7838): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7838): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7838): (14) unable to open database file
,E/SQLiteDatabase( 7838): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7838): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7838): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7838): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7838): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7838): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7838): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7838): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7838): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7838): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7838): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
,I/GservicesProvider( 7845): Gservices pushing to system: true; secure/global: true
E/AndroidRuntime( 7838): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7838): Process: android.process.acore, PID: 7838
E/AndroidRuntime( 7838): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7838): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7838): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7838): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7838): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7838): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7838): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7838): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7838): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7838): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7838): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7838): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7838): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7838): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7838): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7838): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7838): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7838): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7838): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7838): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7838): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7838): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 2401): Process android.process.acore has crashed too many times: killing!
,E/DropBoxManagerService( 2401): Can't write: system_app_crash
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
I/Process ( 7838): Sending signal. PID: 7838 SIG: 9
E/SQLiteDatabase( 7845): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7845): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7845): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7845): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7845): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7845): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7845): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7845): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7845): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7845): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7845): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7845): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7845): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7845): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7845): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7845): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7845): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7845): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7845): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7845): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7845): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7845): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7845): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7845): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7845): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7845): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7845): 	at android.app.ActivityThread.main(A,ctivityThread.java:5694)
E/SQLiteDatabase( 7845): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7845): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7845): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7845): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7845): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7845): Shutting down VM
,W/dalvikvm( 7845): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7845): FATAL EXCEPTION: main
E/AndroidRuntime( 7845): Process: com.google.process.gapps, PID: 7845
E/AndroidRuntime( 7845): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7845): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7845): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7845): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7845): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7845): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7845): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7845): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7845): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7845): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7845): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7845): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7845): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7845): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7845): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7845): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7845): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7845): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7845): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7845): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7845): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7845): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7845): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7845): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7845): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7845): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7845): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7845): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7845): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7845): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7845): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7845): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7845): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7845): 	... 12 more
,E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop232.tmp: open failed: EROFS (Read-only file system)
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
,I/Process ( 7845): Sending signal. PID: 7845 SIG: 9
I/ActivityManager( 2401): Process android.process.acore (pid 7838) (adj -12) has died.
,I/SELinux ( 7892): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7892):  
I/ActivityManager( 2401): Process com.google.process.gapps (pid 7845) (adj 0) has died.
W/ActivityManager( 2401): Service crashed 2 times, stopping: ServiceRecord{43110570 u0 com.google.android.gms/.gcm.GcmService}
,I/SELinux ( 7896): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7896):  
,I/SELinux ( 7892): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7892):  
I/SELinux ( 7892):  
,I/SELinux ( 7892): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7892): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7892): >>>>> Normal User
,E/dalvikvm( 7892): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7892): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,I/SELinux ( 7896): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7896):  
I/SELinux ( 7896):  
,I/SELinux ( 7896): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7896): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7896): >>>>> Normal User
,E/dalvikvm( 7896): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,D/TimaKeyStoreProvider( 7892): in addTimaSignatureService
,E/SELinux ( 7896): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7892): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7892): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 7896): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7896): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7896): Added TimaKesytore provider
,D/dalvikvm( 7892): GC_CONCURRENT freed 2993K, 31% free 9576K/13700K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7892): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 2401): GC_EXPLICIT freed 2767K, 75% free 24902K/96300K, paused 7ms+17ms, total 171ms
,D/dalvikvm( 7896): GC_CONCURRENT freed 2990K, 31% free 9578K/13696K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 7896): WAIT_FOR_CONCURRENT_GC blocked 15ms
,E/SQLiteDatabase( 7892): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7892): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7892): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7892): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7892): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7892): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7892): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7892): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7892): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7892): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7892): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 7892): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7892): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7892): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7892): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7892): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7892): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7892): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7892): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7892): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7892): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7892): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7892): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7892): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7892): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7892): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7892): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7892): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7892): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7892): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7892): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7892): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7892): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 7892): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7892): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7892): (14) unable to open database file
E/SQLiteDatabase( 7892): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7892): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7892): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7892): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7892): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7892): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7892): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7892): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7892): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7892): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7892): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7892): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7892): Process: android.process.acore, PID: 7892
E/AndroidRuntime( 7892): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7892): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7892): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7892): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7892): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7892): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7892): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7892): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7892): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7892): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7892): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7892): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7892): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7892): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7892): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7892): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7892): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7892): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7892): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7892): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7892): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7892): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager( 2401): Process android.process.acore has crashed too many times: killing!
,I/Process ( 7892): Sending signal. PID: 7892 SIG: 9
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop233.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager( 2401): Process android.process.acore (pid 7892) (adj -12) has died.
I/GservicesProvider( 7896): Gservices pushing to system: true; secure/global: true
E/SQLiteDatabase( 7896): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7896): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7896): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7896): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7896): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7896): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7896): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7896): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7896): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7896): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7896): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7896): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7896): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7896): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7896): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7896): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7896): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7896): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7896): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7896): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7896): Shutting down VM
W/dalvikvm( 7896): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,I/SELinux ( 7923): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7923):  
E/AndroidRuntime( 7896): FATAL EXCEPTION: main
E/AndroidRuntime( 7896): Process: com.google.process.gapps, PID: 7896
E/AndroidRuntime( 7896): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7896): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7896): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7896): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7896): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7896): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7896): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7896): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7896): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7896): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7896): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7896): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7896): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7896): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7896): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7896): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7896): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7896): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7896): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7896): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7896): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7896): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7896): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7896): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7896): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7896): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7896): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7896): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7896): 	... 12 more
,W/ActivityManager( 2401): Process com.google.process.gapps has crashed too many times: killing!
,I/ActivityManager( 2401): Killing 7896:com.google.process.gapps/u0a12 (adj 0): crash
,E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop234.tmp: open failed: EROFS (Read-only file system)
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
,W/ActivityManager( 2401): Unable to launch app com.google.android.gsf/10012 for provider com.google.settings: launching app became null
W/ActivityManager( 2401): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7820): Failed to find provider info for com.google.settings
,W/ActivityManager( 2401): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
,E/ActivityThread( 7781): Failed to find provider info for com.google.android.gsf.gservices
,E/ActivityThread( 7867): Failed to find provider info for com.google.android.gsf.gservices
,I/SELinux ( 7929): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7929):  
,I/SELinux ( 7923): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7923):  
I/SELinux ( 7923):  
,I/SELinux ( 7923): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7923): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7923): >>>>> Normal User
,E/dalvikvm( 7923): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7923): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7923): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7923): Cannot add TimaSignature Service, License check Failed
I/SELinux ( 7929): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7929):  
I/SELinux ( 7929):  
,I/SELinux ( 7929): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/ActivityThread( 7923): Added TimaKesytore provider
E/SELinux ( 7929): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7929): >>>>> Normal User
,E/dalvikvm( 7929): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7929): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7929): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7929): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7929): Added TimaKesytore provider
,D/dalvikvm( 7923): GC_CONCURRENT freed 3001K, 31% free 9569K/13700K, paused 2ms+2ms, total 19ms
,D/dalvikvm( 7923): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 7929): GC_CONCURRENT freed 2988K, 31% free 9582K/13700K, paused 1ms+1ms, total 18ms
,D/dalvikvm( 7929): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7929): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7929): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7929): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7929): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7929): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7929): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7929): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7929): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7929): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7929): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7929): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7929): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7929): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7929): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7929): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7929): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7929): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7929): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7929): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7929): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7929): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7929): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7929): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7929): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7929): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7929): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7929): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7929): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7929): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7929): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7929): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7929): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7929): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7929): Shutting down VM
,W/dalvikvm( 7929): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7929): FATAL EXCEPTION: main
E/AndroidRuntime( 7929): Process: com.google.process.gapps, PID: 7929
E/AndroidRuntime( 7929): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7929): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7929): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7929): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7929): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7929): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7929): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7929): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7929): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7929): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7929): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7929): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7929): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7929): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7929): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7929): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7929): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7929): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7929): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7929): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7929): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7929): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7929): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7929): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7929): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7929): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7929): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7929): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7929): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7929): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7929): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7929): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7929): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7929): 	... 12 more
,I/Process ( 7929): Sending signal. PID: 7929 SIG: 9
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop235.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager( 2401): Process com.google.process.gapps (pid 7929) (adj 0) has died.
,E/SQLiteDatabase( 7923): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7923): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7923): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7923): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7923): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7923): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7923): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7923): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7923): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7923): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7923): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 7923): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7923): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7923): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7923): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7923): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7923): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7923): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7923): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7923): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7923): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7923): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7923): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7923): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7923): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7923): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7923): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7923): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7923): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 7923): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7923): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7923): (14) unable to open database file
E/SQLiteDatabase( 7923): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7923): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7923): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7923): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7923): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7923): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7923): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7923): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7923): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7923): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7923): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
,I/SELinux ( 7956): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7956):  
E/AndroidRuntime( 7923): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7923): Process: android.process.acore, PID: 7923
E/AndroidRuntime( 7923): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7923): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7923): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7923): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7923): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7923): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7923): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7923): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7923): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7923): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7923): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7923): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7923): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7923): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7923): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7923): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7923): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7923): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7923): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7923): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 7923): Sending signal. PID: 7923 SIG: 9
W/ActivityManager( 2401): Process android.process.acore has crashed too many times: killing!
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop236.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager( 2401): Process android.process.acore (pid 7923) (adj -12) has died.
,I/SELinux ( 7961): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7961):  
,I/SELinux ( 7956): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7956):  
I/SELinux ( 7956):  
,I/SELinux ( 7956): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7956): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7956): >>>>> Normal User
,E/dalvikvm( 7956): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7956): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7956): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7956): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7956): Added TimaKesytore provider
,I/SELinux ( 7961): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7961):  
I/SELinux ( 7961):  
,I/SELinux ( 7961): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7961): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7961): >>>>> Normal User
,E/dalvikvm( 7961): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7961): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7961): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7961): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7961): Added TimaKesytore provider
,D/dalvikvm( 7956): GC_CONCURRENT freed 2985K, 31% free 9578K/13692K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 7956): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 7961): GC_CONCURRENT freed 2989K, 31% free 9576K/13696K, paused 3ms+2ms, total 19ms
,D/dalvikvm( 7961): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7956): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7956): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7956): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7956): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7956): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7956): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7956): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7956): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7956): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7956): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7956): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7956): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7956): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7956): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7956): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7956): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7956): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7956): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7956): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7956): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7956): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7956): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7956): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7956): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7956): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7956): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7956): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7956): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7956): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7956): Shutting down VM
,W/dalvikvm( 7956): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7956): FATAL EXCEPTION: main
E/AndroidRuntime( 7956): Process: com.google.process.gapps, PID: 7956
E/AndroidRuntime( 7956): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7956): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7956): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7956): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7956): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7956): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7956): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7956): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7956): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7956): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7956): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7956): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7956): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7956): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7956): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7956): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7956): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7956): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7956): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7956): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7956): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7956): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7956): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7956): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7956): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7956): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7956): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7956): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7956): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7956): 	... 12 more
W/ActivityManager( 2401): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2401): Killing 7956:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2401): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launc,hing app became null
W/ActivityManager( 2401): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7867): Failed to find provider info for com.google.android.gsf.gservices
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop237.tmp: open failed: EROFS (Read-only file system)
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
E/ActivityThread( 7781): Failed to find provider info for com.google.android.gsf.gservices
D/dalvikvm( 7781): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7781): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7781): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7781): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7781): VFY: unable to resolve instance field 36
,D/dalvikvm( 7781): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 7781): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7781): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7781): VFY: replacing opcode 0x62 at 0x0047
,I/ActivityManager( 2401): Killing 6712:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty #43
D/dalvikvm( 7781): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 7781): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 7781): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42265c28
D/dalvikvm( 7781): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42265c28
D/dalvikvm( 7781): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42265c28, skipping init
D/dalvikvm( 7781): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42265c28
D/dalvikvm( 7781): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42265c28
V/JNIHelp ( 7781): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 7781): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42265c28
,D/dalvikvm( 7781): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x42265c28
D/dalvikvm( 7781): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42265c28
,D/dalvikvm( 7781): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42265c28
,E/SQLiteDatabase( 7961): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7961): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7961): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7961): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7961): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7961): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7961): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7961): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7961): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7961): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7961): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 7961): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7961): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7961): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7961): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7961): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7961): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7961): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7961): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7961): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7961): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7961): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7961): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7961): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7961): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7961): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7961): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7961): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7961): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 7961): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7961): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7961): (14) unable to open database file
E/SQLiteDatabase( 7961): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7961): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7961): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7961): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7961): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7961): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7961): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7961): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7961): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7961): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7961): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7961): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7961): Process: android.process.acore, PID: 7961
E/AndroidRuntime( 7961): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7961): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7961): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7961): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7961): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7961): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7961): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7961): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7961): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7961): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7961): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7961): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7961): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7961): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7961): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7961): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7961): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7961): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 7961): Sending signal. PID: 7961 SIG: 9
W/ActivityManager( 2401): Process android.process.acore has crashed too many times: killing!
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
,I/ActivityManager( 2401): Process android.process.acore (pid 7961) (adj -12) has died.
,I/SELinux ( 7989): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7989):  
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2401): stay LED for fully charged
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3996): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3996): Disconnected process message: 10
I/SELinux ( 7989): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7989):  
I/SELinux ( 7989):  
I/SELinux ( 7989): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7989): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7989): >>>>> Normal User
E/dalvikvm( 7989): >>>>> android.process.acore [ userId:0 | appId:10020 ]
E/SELinux ( 7989): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/TimaKeyStoreProvider( 7989): in addTimaSignatureService
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/ProviderInstaller( 7781): Installed default security provider GmsCore_OpenSSL
D/TimaKeyStoreProvider( 7989): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7989): Added TimaKesytore provider
,I/SELinux ( 8001): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8001):  
,I/SELinux ( 8001): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8001):  
I/SELinux ( 8001):  
,I/SELinux ( 8001): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8001): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 8001): >>>>> Normal User
,E/dalvikvm( 8001): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 8001): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 7989): GC_CONCURRENT freed 2993K, 31% free 9576K/13696K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7989): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/TimaKeyStoreProvider( 8001): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8001): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8001): Added TimaKesytore provider
,D/dalvikvm( 8001): GC_CONCURRENT freed 2990K, 31% free 9578K/13696K, paused 3ms+2ms, total 19ms
,D/dalvikvm( 8001): WAIT_FOR_CONCURRENT_GC blocked 11ms
,E/SQLiteDatabase( 7989): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7989): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7989): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7989): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7989): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7989): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7989): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7989): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7989): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7989): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7989): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 7989): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7989): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7989): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7989): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7989): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7989): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7989): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7989): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7989): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7989): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7989): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7989): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7989): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7989): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7989): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7989): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7989): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7989): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7989): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7989): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7989): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7989): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 7989): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7989): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7989): (14) unable to open database file
,E/SQLiteDatabase( 7989): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7989): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7989): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7989): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7989): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7989): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7989): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7989): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7989): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7989): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7989): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7989): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7989): Process: android.process.acore, PID: 7989
E/AndroidRuntime( 7989): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7989): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7989): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7989): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7989): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7989): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7989): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7989): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7989): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7989): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7989): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7989): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7989): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7989): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7989): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7989): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7989): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7989): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7989): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7989): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7989): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7989): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 7989): Sending signal. PID: 7989 SIG: 9
W/ActivityManager( 2401): Process android.process.acore has crashed too many times: killing!
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop239.tmp: open failed: EROFS (Read-only file system)
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
,I/GservicesProvider( 8001): Gservices pushing to system: true; secure/global: true
E/SQLiteDatabase( 8001): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 8001): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8001): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8001): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8001): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8001): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8001): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8001): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8001): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8001): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8001): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8001): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8001): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8001): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8001): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8001): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 8001): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 8001): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 8001): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 8001): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 8001): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 8001): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 8001): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 8001): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 8001): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8001): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8001): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8001): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8001): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8001): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8001): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8001): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 8001): Shutting down VM
,W/dalvikvm( 8001): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
I/ActivityManager( 2401): Process android.process.acore (pid 7989) (adj -12) has died.
E/AndroidRuntime( 8001): FATAL EXCEPTION: main
E/AndroidRuntime( 8001): Process: com.google.process.gapps, PID: 8001
E/AndroidRuntime( 8001): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8001): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 8001): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 8001): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 8001): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8001): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 8001): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8001): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 8001): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 8001): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 8001): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 8001): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 8001): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 8001): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 8001): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8001): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8001): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 8001): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 8001): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8001): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8001): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8001): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 8001): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 8001): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8001): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 8001): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 8001): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 8001): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 8001): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 8001): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 8001): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 8001): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 8001): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 8001): 	... 12 more
,I/SELinux ( 8020): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8020):  
,I/Process ( 8001): Sending signal. PID: 8001 SIG: 9
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop240.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager( 2401): Process com.google.process.gapps (pid 8001) (adj 0) has died.
,I/SELinux ( 8025): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8025):  
,I/SELinux ( 8020): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8020):  
I/SELinux ( 8020):  
,I/SELinux ( 8020): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8020): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 8020): >>>>> Normal User
,E/dalvikvm( 8020): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 8020): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 8020): in addTimaSignatureService
,D/dalvikvm( 1921): GC_EXPLICIT freed 44K, 11% free 9502K/10672K, paused 3ms+3ms, total 30ms
,D/TimaKeyStoreProvider( 8020): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8020): Added TimaKesytore provider
,I/SELinux ( 8025): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8025):  
I/SELinux ( 8025):  
,I/SELinux ( 8025): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8025): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 8025): >>>>> Normal User
,E/dalvikvm( 8025): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 8025): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9502K/10672K, paused 2ms+3ms, total 24ms
,D/TimaKeyStoreProvider( 8025): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8025): Cannot add TimaSignature Service, License check Failed
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9502K/10672K, paused 2ms+3ms, total 24ms
,D/ActivityThread( 8025): Added TimaKesytore provider
,D/dalvikvm( 8020): GC_CONCURRENT freed 2994K, 31% free 9576K/13696K, paused 4ms+1ms, total 22ms
,D/dalvikvm( 8020): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 8025): GC_CONCURRENT freed 2988K, 31% free 9582K/13700K, paused 1ms+1ms, total 17ms
,D/dalvikvm( 8025): WAIT_FOR_CONCURRENT_GC blocked 16ms
,E/SQLiteDatabase( 8020): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 8020): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8020): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8020): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 8020): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 8020): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 8020): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 8020): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 8020): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8020): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8020): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 8020): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 8020): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 8020): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 8020): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 8020): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 8020): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 8020): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 8020): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 8020): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 8020): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 8020): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 8020): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 8020): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 8020): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 8020): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 8020): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 8020): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 8020): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 8020): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 8020): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 8020): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 8020): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 8020): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 8020): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 8020): (14) unable to open database file
E/SQLiteDatabase( 8020): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 8020): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 8020): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 8020): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 8020): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 8020): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 8020): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 8020): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8020): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8020): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 8020): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 8020): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 8020): Process: android.process.acore, PID: 8020
E/AndroidRuntime( 8020): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 8020): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 8020): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 8020): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 8020): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 8020): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 8020): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 8020): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8020): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8020): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8020): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 8020): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 8020): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8020): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 8020): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 8020): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 8020): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 8020): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 8020): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 8020): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8020): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 8020): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/GservicesProvider( 8025): Gservices pushing to system: true; secure/global: true
,I/Process ( 8020): Sending signal. PID: 8020 SIG: 9
W/ActivityManager( 2401): Process android.process.acore has crashed too many times: killing!
E/SQLiteDatabase( 8025): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 8025): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8025): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8025): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8025): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8025): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8025): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8025): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8025): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8025): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8025): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8025): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8025): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8025): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8025): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8025): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 8025): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 8025): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 8025): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 8025): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 8025): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 8025): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 8025): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 8025): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 8025): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8025): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8025): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8025): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8025): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8025): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8025): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8025): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 8025): Shutting down VM
,W/dalvikvm( 8025): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop241.tmp: open failed: EROFS (Read-only file system)
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
E/AndroidRuntime( 8025): FATAL EXCEPTION: main
E/AndroidRuntime( 8025): Process: com.google.process.gapps, PID: 8025
E/AndroidRuntime( 8025): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8025): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 8025): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 8025): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 8025): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8025): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 8025): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8025): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 8025): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 8025): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 8025): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 8025): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 8025): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 8025): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 8025): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8025): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8025): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 8025): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 8025): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8025): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8025): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8025): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 8025): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 8025): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8025): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 8025): 	at android.co,ntent.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 8025): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 8025): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 8025): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 8025): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 8025): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 8025): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 8025): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 8025): 	... 12 more
W/ActivityManager( 2401): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2401): Killing 8025:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2401): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
,W/NativeLibraryUtils( 7781): Failed to open lock file
W/NativeLibraryUtils( 7781): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7781): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/NativeLibraryUtils( 7781): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:118)
W/NativeLibraryUtils( 7781): 	at com.google.android.gms.common.util.ay.b(SourceFile:325)
W/NativeLibraryUtils( 7781): 	at com.google.android.gms.common.app.b.run(SourceFile:209)
W/NativeLibraryUtils( 7781): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7781): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7781): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/NativeLibraryUtils( 7781): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/NativeLibraryUtils( 7781): 	... 3 more
E/ActivityThread( 7781): Failed to find provider info for com.google.android.gsf.gservices
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop242.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager( 2401): Process android.process.acore (pid 8020) (adj -12) has died.
,I/SELinux ( 8056): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8056):  
,I/dalvikvm( 7781): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 7781): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7781): VFY: replacing opcode 0x6e at 0x000d
,I/SELinux ( 8056): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8056):  
I/SELinux ( 8056):  
,I/SELinux ( 8056): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8056): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 8056): >>>>> Normal User
,E/dalvikvm( 8056): >>>>> android.process.acore [ userId:0 | appId:10020 ]
E/SELinux ( 8056): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,I/SELinux ( 8061): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8061):  
,D/TimaKeyStoreProvider( 8056): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8056): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8056): Added TimaKesytore provider
,I/SELinux ( 8061): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8061):  
I/SELinux ( 8061):  
,I/SELinux ( 8061): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 8061): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 8061): >>>>> Normal User
E/dalvikvm( 8061): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 8061): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 8061): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8061): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8061): Added TimaKesytore provider

```
