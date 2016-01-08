#### Test 54970261d953416_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
,E/Watchdog( 2420): !@Sync 8
--------- beginning of /dev/log/main
D/AndroidRuntime( 7144): 
D/AndroidRuntime( 7144): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7144): CheckJNI is OFF
D/AndroidRuntime( 7144): setted country_code = Poland
D/AndroidRuntime( 7144): setted countryiso_code = PL
D/AndroidRuntime( 7144): setted sales_code = PLS
D/AndroidRuntime( 7144): readGMSProperty: start
D/AndroidRuntime( 7144): readGMSProperty: already setted!!
D/AndroidRuntime( 7144): readGMSProperty: end
D/AndroidRuntime( 7144): addProductProperty: start
D/dalvikvm( 7144): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7144): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7144): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7144): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7144): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7144): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7144): failed to load memtrack module: -2
D/dalvikvm( 7144): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7144): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2420): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2420): mDVFSHelper.acquire()
I/SELinux ( 7171): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7171):  
D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7144): Shutting down VM
D/dalvikvm( 7144): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 7171): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7171):  
I/SELinux ( 7171):  
I/SELinux ( 7171): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7171): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7171): >>>>> Normal User
E/dalvikvm( 7171): >>>>> com.test.thalitest [ userId:0 | appId:10602 ]
E/SELinux ( 7171): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7171): in addTimaSignatureService
D/TimaKeyStoreProvider( 7171): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7171): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4192): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4192): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7171): GC_CONCURRENT freed 3011K, 32% free 9556K/14000K, paused 2ms+1ms, total 18ms
D/dalvikvm( 7171): WAIT_FOR_CONCURRENT_GC blocked 17ms
V/WebViewChromium( 7171): Binding Chromium to the background looper Looper (main, tid 1) {422b9370}
I/chromium( 7171): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7171): Initializing chromium process, renderers=0
W/chromium( 7171): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7171): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7171): loaded /system/lib/egl/libGLESv1_CM_mali.so
D/libEGL  ( 7171): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7171): Mali API Version : 401
I/Mali    ( 7171): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
I/dalvikvm( 7171): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7171): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7171): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7171): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7171): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 7171): VFY: replacing opcode 0x6e at 0x0008
D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2420): tr p:7171,o:f
W/dalvikvm( 7171): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7171): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7171): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7171): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 7171): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7171): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7171): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7171): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7171): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7171): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7171): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7171): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7171): CordovaWebView is running on device made by: samsung
D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2420): semi p:7171,o:f
I/SurfaceFlinger( 1920): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
I/HWUI    ( 7171): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 7171): Enabling debug mode 0
W/AwContents( 7171): nativeOnDraw failed; clearing to background color.
W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/IInputConnectionWrapper( 7171): showStatusIcon on inactive InputConnection
D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2420): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@8
D/JsMessageQueue( 7171): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 7171): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422ba138
D/dalvikvm( 7171): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422ba138
D/jxcore_app_log( 7171): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2028724232
D/JX-Cordova( 7171): jxcore cordova android initializing
D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
D/dalvikvm( 7171): GC_CONCURRENT freed 1288K, 20% free 11340K/14056K, paused 2ms+2ms, total 23ms
D/dalvikvm( 7171): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 7171): GC_CONCURRENT freed 1923K, 19% free 14950K/18320K, paused 2ms+2ms, total 40ms
,D/dalvikvm( 7171): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@8
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/dalvikvm( 7171): GC_FOR_ALLOC freed 5310K, 31% free 16231K/23212K, paused 51ms, total 51ms
,D/dalvikvm( 7171): GC_CONCURRENT freed 6712K, 32% free 17688K/25852K, paused 2ms+10ms, total 66ms
,D/dalvikvm( 7171): WAIT_FOR_CONCURRENT_GC blocked 48ms
,D/dalvikvm( 7171): GC_FOR_ALLOC freed 1154K, 33% free 17578K/25852K, paused 52ms, total 53ms
,I/dalvikvm-heap( 7171): Grow heap (frag case) to 22.076MB for 3688532-byte allocation
,D/dalvikvm( 7171): GC_FOR_ALLOC freed 2477K, 37% free 18702K/29456K, paused 43ms, total 43ms
,W/jxcore-log( 7171): Initializing JXcore engine
,W/jxcore-log( 7171): JXcore engine is ready
,W/jxcore-log( 7171): Starting JXcore engine
,W/jxcore-log( 7171): Platform android
W/jxcore-log( 7171): 
,W/jxcore-log( 7171): Process ARCH arm
W/jxcore-log( 7171): 
,I/jxcore-log( 7171): JXcore Cordova bridge is ready!
I/jxcore-log( 7171): 
,W/jxcore-log( 7171): JXcore engine is started
,I/chromium( 7171): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7171): Toggling radios to true
I/jxcore-log( 7171): 
,D/BluetoothAdapter( 7171): enable(): BT is already enabled..!
,I/WifiManager( 7171): packageName : com.test.thalitest
,I/WifiManager( 7171): setWifiEnabled : true
,I/WifiService( 2420): setWifiEnabled: true pid=7171, uid=10602
W/ActivityManager( 2420): Permission Denial: getCurrentUser() from pid=7171, uid=10602 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 2420): Failed getting userId using ActivityManagerNative
W/WifiService( 2420): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7171, uid=10602 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2420): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2420): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2420): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2420): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService( 2420): disconnect: pid=7171, uid=10602
,I/jxcore-log( 7171): Radios toggled
I/jxcore-log( 7171): 
,I/wpa_supplicant( 3980): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3980): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3980): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3980): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3980): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3980): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3980): First Scan Start
W/Settings( 2420): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 3980): Scan requested (ret=0) - scan timeout 30 seconds
I/WifiStateMachine( 2420): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2420): InactiveState{ what=143375 }
D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/wpa_supplicant( 3980): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3980): Skip scan - already scanning
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
D/ConnectivityService( 2420): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/WifiP2pService( 2420): InactiveState{ what=143375 }
D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
D/ConnectivityService( 2420): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2420): net.tcp.usercfg.default not found in system default properties
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
E/ConnectivityService( 2420): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2420): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2420): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
,D/ConnectivityService( 2420): Attempting to switch to mobile
,D/ConnectivityService( 2420): Attempting to switch to BLUETOOTH_TETHER
,I/SELinux ( 7218): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7218):  
D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
E/WifiStateMachine( 2420): Error! unhandled message{ when=-41ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-38ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-9ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
I/SELinux ( 7218): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7218):  
I/SELinux ( 7218):  
,I/SELinux ( 7218): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7218): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7218): >>>>> Normal User
,E/dalvikvm( 7218): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7218): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
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
,D/TimaKeyStoreProvider( 7218): in addTimaSignatureService
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 7218): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7218): Added TimaKesytore provider
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/ConnectivityService( 2420): resetConnections(wlan0, 3)
D/NetUtils( 2420): android_net_utils_resetConnections in env=0x77eac100 clazz=0x62000001 iface=wlan0 mask=0x3
,D/dalvikvm( 7218): GC_CONCURRENT freed 2990K, 32% free 9577K/14000K, paused 4ms+2ms, total 31ms
,D/dalvikvm( 7218): WAIT_FOR_CONCURRENT_GC blocked 25ms
,E/SPPClientService( 5600): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5600): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5600): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5600): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5600): [b] ResponseMap empty
,V/NativeCrypto( 2849): Read error: ssl=0x7b9bfa30: I/O error during system call, Connection timed out
,V/NativeCrypto( 2849): SSL shutdown failed: ssl=0x7b9bfa30: I/O error during system call, Broken pipe
,I/System.out( 7218): Inside WakeupProvider
,I/System.out( 7218): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 7218): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7218): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7218): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/ConnectivityService( 2420): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): updateIfacesLocked()
,V/NetworkStats( 2420): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): performPollLocked() took 25ms
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NearbySettings( 4756): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4756): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4756): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4756): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4756): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4756): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4756): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2420): Killing 6230:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/DialogFlow( 7218): initQueue()
,D/NearbySettings( 4756): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4756): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4756): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 4756): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4756): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4756): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4756): MountReceiver.mPrefHandler - 7002
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/Tethering( 2420): Tethering got CONNECTIVITY_ACTION
,I/ApplicationPolicy( 2420): updateDataUsageMap
,D/Tethering( 2420): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2420): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2420): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6641): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6641): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6641): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6641): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver( 6641): noConnectivity : true
,I/DBG_DM  ( 4782): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/SELinux ( 7247): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7247):  
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7247): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7247):  
I/SELinux ( 7247):  
,I/SELinux ( 7247): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7247): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7247): >>>>> Normal User
,E/dalvikvm( 7247): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7247): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7247): in addTimaSignatureService
I/wpa_supplicant( 3980): nl80211: Received scan results (7 BSSes)
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
D/Tethering( 2420): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3980): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3980): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3980): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
D/TimaKeyStoreProvider( 7247): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7247): Added TimaKesytore provider
,I/wpa_supplicant( 3980): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3980): Associated with C0.AA.48
,I/wpa_supplicant( 3980): freq(2412) increment count 2
I/wpa_supplicant( 3980): meet head of list.
D/dalvikvm( 7247): GC_CONCURRENT freed 3001K, 32% free 9564K/14000K, paused 6ms+3ms, total 49ms
,D/dalvikvm( 7247): WAIT_FOR_CONCURRENT_GC blocked 39ms
,I/wpa_supplicant( 3980): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3980): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3980): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3980): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=],
I/wpa_supplicant( 3980): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,D/WifiNative( 2420): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
,I/ActivityManager( 2420): Killing 6299:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/WifiP2pService( 2420): InactiveState{ what=143375 }
,D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,I/SELinux ( 7261): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7261):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 14% free 9500K/10976K, paused 3ms+3ms, total 36ms
,I/SELinux ( 7261): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7261):  
I/SELinux ( 7261):  
,I/SELinux ( 7261): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7261): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7261): >>>>> Normal User
,E/dalvikvm( 7261): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7261): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 14% free 9500K/10976K, paused 2ms+4ms, total 31ms
,D/TimaKeyStoreProvider( 7261): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7261): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7261): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 14% free 9500K/10976K, paused 3ms+4ms, total 29ms
,D/dalvikvm( 7261): GC_CONCURRENT freed 2998K, 32% free 9569K/14000K, paused 3ms+1ms, total 23ms
,D/dalvikvm( 7261): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/ActivityManager( 2420): Killing 6372:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
I/dhcpcd  ( 7273): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7273): bssid match
,I/SELinux ( 7280): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7280):  
,I/SELinux ( 7280): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7280):  
I/SELinux ( 7280):  
,I/SELinux ( 7280): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7280): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7280): >>>>> Normal User
,E/dalvikvm( 7280): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
E/SELinux ( 7280): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 7280): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7280): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7280): Added TimaKesytore provider
,D/dalvikvm( 7280): GC_CONCURRENT freed 3014K, 32% free 9556K/14000K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7280): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/KLMS-2.3.201 : ( 7280): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7280): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452280675784
,I/KLMS-2.3.201 : ( 7280): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2420): Killing 6389:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7292): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7292):  
,I/SELinux ( 7292): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7292):  
I/SELinux ( 7292):  
,I/SELinux ( 7292): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7292): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7292): >>>>> Normal User
,E/dalvikvm( 7292): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7292): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7292): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7292): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7292): Added TimaKesytore provider
,D/dalvikvm( 7292): GC_CONCURRENT freed 2993K, 32% free 9573K/14000K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7292): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/SO_AGENT( 7292): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7292): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5866): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5866): [BDLM] already registered in spp
I/SA      ( 5866): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5866): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5866): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5866): [OR] == isSIMCardReady false ==
,I/SA      ( 5866): [SCU] == networkStateCheck == false
,I/SA      ( 5866): [OR] onReceive END
I/ActivityManager( 2420): Killing 6443:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection...
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SELinux ( 7310): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7310):  
,I/SELinux ( 7310): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7310):  
I/SELinux ( 7310):  
,I/SELinux ( 7310): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7310): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7310): >>>>> Normal User
,E/dalvikvm( 7310): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7310): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7310): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7310): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7310): Added TimaKesytore provider
,D/dalvikvm( 7310): GC_CONCURRENT freed 2997K, 32% free 9567K/13996K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 7310): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/sCloudBackupApp( 7310): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7310): Other Intent
I/ActivityManager( 2420): Killing 5648:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SELinux ( 7338): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7338):  
,D/WifiP2pService( 2420): InactiveState{ what=143375 }
,D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2420): VerifyingLinkState enter
I/SELinux ( 7338): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7338):  
I/SELinux ( 7338):  
,I/SELinux ( 7338): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7338): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/dalvikvm( 7338): >>>>> Normal User
E/dalvikvm( 7338): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
E/SELinux ( 7338): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2420): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2420): CaptivePortalCheckState enter
,D/TimaKeyStoreProvider( 7338): in addTimaSignatureService
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2420): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2420): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 2420): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TimaKeyStoreProvider( 7338): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7338): Added TimaKesytore provider
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
D/ConnectivityService( 2420): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2420): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2420): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2420): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/dalvikvm( 7338): GC_CONCURRENT freed 3001K, 32% free 9568K/14000K, paused 3ms+3ms, total 29ms
,D/dalvikvm( 7338): WAIT_FOR_CONCURRENT_GC blocked 25ms
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/com.samsung.app( 7338): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7338): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7338): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
D/com.samsung.app( 7338): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/com.samsung.app( 7338): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): updateIfacesLocked()
,V/NetworkStats( 2420): performPollLocked(flags=0x1)
D/com.samsung.app( 7338): [KK AccuPhone]>>> RM:136 [0:0]  V init 
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/daemonapp( 5399): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): performPollLocked() took 19ms
,D/com.samsung.app( 7338): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/daemonapp( 5399): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7338): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5399): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7338): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7338): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2420): Killing 6359:com.sec.phone/1001 (adj 15): empty #43
,D/Headlines( 5933): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5933): getCountryCode(): countryCode = PL
,D/Headlines( 5933): Breath.onCreate
,D/Headlines( 5933): Breath timer started. interval : 30000
,I/SELinux ( 7366): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7366):  
,D/Headlines( 5933): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5933): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5933): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5933): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5933): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5933): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,V/AlarmManager( 2420): waitForAlarm result :8
D/HeadlinesDataCenter( 5933): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7366): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7366):  
I/SELinux ( 7366):  
,I/SELinux ( 7366): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7366): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7366): >>>>> Normal User
,E/dalvikvm( 7366): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7366): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7366): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7366): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7366): Added TimaKesytore provider
,D/dalvikvm( 7366): GC_CONCURRENT freed 3005K, 32% free 9562K/13996K, paused 2ms+1ms, total 23ms
,D/dalvikvm( 7366): WAIT_FOR_CONCURRENT_GC blocked 21ms
,V/WebViewChromium( 7366): Binding Chromium to the background looper Looper (main, tid 1) {422b5f88}
,I/chromium( 7366): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7366): Initializing chromium process, renderers=0
,W/chromium( 7366): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7366): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7366): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7366): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7366): Mali API Version : 401
,I/Mali    ( 7366): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,W/GAV2    ( 7366): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7366): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,D/Tethering( 2420): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2420): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2420): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4782): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection...
,I/NSApplication( 7366): Starting up...
,I/iu.Environment( 5997): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5200): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5200): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5200): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422c6370
,I/SELinux ( 7404): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7404):  
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
I/SELinux ( 7404): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7404):  
I/SELinux ( 7404):  
,I/SELinux ( 7404): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/BatteryService( 2420): stay LED for fully charged
E/SELinux ( 7404): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7404): >>>>> Normal User
,E/dalvikvm( 7404): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7404): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4015): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4015): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/TimaKeyStoreProvider( 7404): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7404): Cannot add TimaSignature Service, License check Failed
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/ActivityThread( 7404): Added TimaKesytore provider
,D/dalvikvm( 7404): GC_CONCURRENT freed 2984K, 32% free 9579K/13996K, paused 4ms+2ms, total 29ms
,D/dalvikvm( 7404): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,I/SELinux ( 7424): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7424):  
,W/ActivityManager( 2420): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/RCPManagerService( 2420): exchangeData() failure , invalid userId
D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,I/ActivityManager( 2420): Killing 6401:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/SELinux ( 7424): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7424):  
I/SELinux ( 7424):  
,I/SELinux ( 7424): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7424): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7424): >>>>> Normal User
,E/dalvikvm( 7424): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ],
,E/SELinux ( 7424): [DEBUG] seapp_context_lookup: seinfoCategory = release
,W/WifiP2pStateTracker( 2420): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/TimaKeyStoreProvider( 7424): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7424): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7424): Added TimaKesytore provider
,I/SELinux ( 7437): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7437):  
,I/ActivityManager( 2420): Killing 6043:com.android.calendar/u0a144 (adj 15): empty #43
,D/ConnectivityService( 2420): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2420):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2420): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2420): updateSourceRoutes : no source routing conditions
,I/SELinux ( 7437): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7437):  
I/SELinux ( 7437):  
,I/SELinux ( 7437): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7437): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7437): >>>>> Normal User
,E/dalvikvm( 7437): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7437): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7437): in addTimaSignatureService
D/dalvikvm( 7424): GC_CONCURRENT freed 2988K, 32% free 9573K/13996K, paused 3ms+2ms, total 24ms
,D/dalvikvm( 7424): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/TimaKeyStoreProvider( 7437): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7437): Added TimaKesytore provider
,D/BadgeProvider( 7424): onCreate
,D/BadgeProvider( 7424): DatabaseHelper
,D/BadgeProvider( 7424): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 2771): reloadBadges entered.
,D/BadgeProvider( 7424): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7424): sendNotify, [notify] : null
D/BadgeProvider( 7424): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7424): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7424): update, [UpdateCount] : 1
,D/dalvikvm( 7437): GC_CONCURRENT freed 2992K, 32% free 9573K/14000K, paused 6ms+1ms, total 28ms
,D/dalvikvm( 7437): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/hcjo    ( 6018): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6018): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6018): exit::IDLE
,D/InitializeManagerStateMachine( 6018): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6018): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 6018): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6018): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6018): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 6018): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6018): entry::SUCCESS
,D/hcjo    ( 6018): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6018): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6018): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6018): exit::SUCCESS
,D/InitializeManagerStateMachine( 6018): entry::IDLE
,E/SPPClientService( 5600): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5600): [SystemStateMoniter] Current Time : 267560
,E/SPPClientService( 5600): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5600): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 4756): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4756): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4756): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 4756): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4756): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4756): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 4756): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4756): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5600): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5600): [a] [ConnectionManager] Connection is already disconnected.
I/ActivityManager( 2420): Killing 6320:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/NearbySettings( 4756): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4756): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4756): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 4756): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4756): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4756): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5600): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,E/SPPClientService( 5600): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/SurfaceFlinger( 1920): id=20 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 2420): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2420
,D/NearbySettings( 4756): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4756): MountReceiver.onReceive - Keep current state
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection...
,D/Headlines( 5933): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5933): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5933): Breath 1472 latestRequest time : 1452280676722 current time : 1452280678194
I/PCWCLIENTTRACE_PushUtil( 6641): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6641): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6641): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6641): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5600): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5600): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5600): [g] getNetMCC return empty string
,I/KLMS-2.3.201 : ( 7280): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/dalvikvm( 2420): GC_EXPLICIT freed 3528K, 72% free 25456K/89900K, paused 7ms+18ms, total 190ms
,I/System.out( 7261): Thread-639(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7261): Thread-639(ApacheHTTPLog):isShipBuild true
,I/System.out( 7261): Thread-639(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/KLMS-2.3.201 : ( 7280): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452280678575
,I/KLMS-2.3.201 : ( 7280): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7292): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7292): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/LocationTagReadyService( 3473): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3473): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3473): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3473): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 3601): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7465): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7465):  
,I/System.out( 7261): AsyncTask #1 calls detatch()
I/SELinux ( 7465): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7465):  
I/SELinux ( 7465):  
,I/SELinux ( 7465): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7465): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7465): >>>>> Normal User
,E/dalvikvm( 7465): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7465): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 7475): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7475):  
D/TimaKeyStoreProvider( 7465): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7465): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7465): Added TimaKesytore provider
I/SELinux ( 7475): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7475):  
I/SELinux ( 7475):  
I/SELinux ( 7475): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7475): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7475): >>>>> Normal User
E/dalvikvm( 7475): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7475): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/System.err( 7261): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7261): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7261): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7261): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7261): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7261): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7261): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7261): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7261): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7261): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 7261): Caused by: java.lang.NullPointerException
,W/System.err( 7261): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7261): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7261): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,I/SA      ( 5866): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,W/System.err( 7261): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7261): 	... 8 more
,D/TimaKeyStoreProvider( 7475): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7475): Cannot add TimaSignature Service, License check Failed
,I/SA      ( 5866): [BDLM] already registered in spp
,D/ActivityThread( 7475): Added TimaKesytore provider
I/SA      ( 5866): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5866): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5866): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5866): [OR] == isSIMCardReady false ==
,I/SA      ( 5866): [SCU] == networkStateCheck == true
I/SA      ( 5866): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5866): isChinaCountryCode : false
,I/SA      ( 5866): [OR] == networkStateCheck true ==
,I/SA      ( 5866): [OR] GetMyCountryZoneTask
,D/dalvikvm( 7465): GC_CONCURRENT freed 2989K, 32% free 9577K/13996K, paused 11ms+2ms, total 39ms
I/SA      ( 5866): [OR] onReceive END
,D/dalvikvm( 7465): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/SA      ( 5866): [SRS] prepareGetMyCountryZone
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7310): Other Intent
,D/dalvikvm( 7475): GC_CONCURRENT freed 2999K, 32% free 9564K/13996K, paused 5ms+5ms, total 51ms
,D/dalvikvm( 7475): WAIT_FOR_CONCURRENT_GC blocked 43ms
,D/com.samsung.app( 7338): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7338): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/SA      ( 5866): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5866): [SSP] query invoked
,V/KVNProvider( 7475): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,D/Headlines( 5933): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 5933): getCountryCode(): countryCode = PL
,V/KVNProvider( 7475): getFindoCursor query string : 
,D/Headlines( 5933): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5933): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5933): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5933): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5933): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5933): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5933): requestUpdateNewsWelcomeCard !!! no welcome card
I/SA      ( 5866): [TPMU] GetMccFromDB : null
I/SA      ( 5866): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5866): [TPM] isNoProxy(default) : true
,I/SA      ( 5866): [RC New] Execute method=[GET] start
,I/iu.Environment( 5997): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,V/KVNProvider( 7475): getTagSearchCursor() tagSearchCursor count : 0
,D/QuickConnect[1.1][2] ( 5200): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5200): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5200): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422c6370
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
I/ActivityManager( 2420): Killing 6217:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/hcjo    ( 6018): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 6018): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6018): exit::IDLE
,D/InitializeManagerStateMachine( 6018): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6018): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6018): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6018): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6018): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6018): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6018): entry::SUCCESS
,D/hcjo    ( 6018): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 6018): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6018): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6018): exit::SUCCESS
,D/InitializeManagerStateMachine( 6018): entry::IDLE
,E/SPPClientService( 5600): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5600): [SystemStateMoniter] Current Time : 268734
,E/SPPClientService( 5600): [SystemStateMoniter] No Connect : false
,D/dalvikvm( 5600): GC_CONCURRENT freed 2014K, 26% free 10431K/13980K, paused 7ms+3ms, total 55ms
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/PackageManager( 2420): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/SA      ( 5866): [RC New] [v2liruge] api execute + 697
,I/SA      ( 5866): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5866): AsyncTask #2 calls detatch()
,I/SA      ( 5866): [TPMU] getNetworkMcc : 
,I/SA      ( 5866): [SCU] saveMccToPreferece Start
,I/SA      ( 5866): [SCU] RegionMCC : 260
,I/SA      ( 5866): [SSP] query invoked
,I/SA      ( 5866): [TPMU] GetMccFromDB : null
,I/SA      ( 5866): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5866): [SCU] saveMccToPreferece End
I/SA      ( 5866): [RC New] executeRequest [v2liruge] end. 728
,I/SA      ( 5866): [RC New] Execute end
I/SA      ( 5866): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5866): [OR] GetMyCountryZoneTask Success
,E/WifiStateMachine( 2420): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/SPPClientService( 5600): [b] __InitReply__
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 20
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (10/11)
,I/ActivityManager( 2420): Killing 6252:com.google.android.music:main/u0a125 (adj 15): empty #43
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (-2/11)
D/PowerManagerService( 2420): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2420) eventTime = 271218
D/PowerManagerService( 2420): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2420 (0x0)
D/PowerManagerService( 2420): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2420, ws=WorkSource{1000}) (elapsedTime=3483)
,I/GAV2    ( 7366): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6641): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6641): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6641): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6641): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6641): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6641): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6641): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6641): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6641): [ensureRegistration] - No Samsung account
,D/CaptivePortalTracker( 2420): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker( 2420): Checking http://216.58.209.46/generate_204
D/ConnectivityService( 2420): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2420): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 2420): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2420): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2420): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2420): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
V/HeadsetService( 4015): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4015): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PreloadUpdateManagerStateMachine( 6018): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6018): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6018): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 6018): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6018): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 6018): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6018): entry::IDLE
,I/jxcore-log( 7171): Test app app.js loaded
I/jxcore-log( 7171): 
,I/Choreographer( 7171): Skipped 892 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7171): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 7171): --= Surplus to requirements =--
I/jxcore-log( 7171): 
I/jxcore-log( 7171): ****TEST TOOK:  ms ****
I/jxcore-log( 7171): 
,I/jxcore-log( 7171): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7171): 
,D/PreloadUpdateManagerStateMachine( 6018): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6018): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6018): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 6018): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6018): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 6018): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6018): entry::IDLE
,D/AndroidRuntime( 7510): 
D/AndroidRuntime( 7510): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7510): CheckJNI is OFF
,D/AndroidRuntime( 7510): setted country_code = Poland
,D/AndroidRuntime( 7510): setted countryiso_code = PL
,D/AndroidRuntime( 7510): setted sales_code = PLS
D/AndroidRuntime( 7510): readGMSProperty: start
,D/AndroidRuntime( 7510): readGMSProperty: already setted!!
D/AndroidRuntime( 7510): readGMSProperty: end
,D/AndroidRuntime( 7510): addProductProperty: start
,D/dalvikvm( 7510): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 7510): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 7510): Trying to load lib libnativehelper.so 0x0
,D/dalvikvm( 7510): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 7510): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,E/memtrack( 7510): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 7510): failed to load memtrack module: -2
,D/dalvikvm( 7510): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,D/AndroidRuntime( 7510): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 2420): START PACKAGE DELETE: observer{1121960464}
D/PackageManager( 2420): pkg{<packageName>}
D/PackageManager( 2420): user{0}
,D/PackageManager( 2420): deletePackageAsUser : uid = 2000 userId = 0
,D/ApplicationPolicy( 2420): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2420): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService( 2420): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2420): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManager( 2420): !@killApplicatoin: 10602, uninstall pkg
,I/ActivityManager( 2420): Killing 7171:com.test.thalitest/u0a602 (adj 0): stop com.test.thalitest
,D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2420): mDVFSHelper.acquire()
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (-2/10)
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (-2/10)
,I/WindowState( 2420): WIN DEATH: Window{43050c30 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 2420): Skipping PackageSetting{4284fe68 com.example.hello/10600} due to missing metadata
,D/PackageManager( 2420): setPackageStoppedState - Execution time: 106 ms
D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10602, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/dalvikvm( 6803): GC_EXPLICIT freed 199K, 30% free 9956K/14216K, paused 8ms+4ms, total 46ms
,D/dalvikvm( 6483): GC_EXPLICIT freed 2480K, 30% free 9882K/13996K, paused 8ms+4ms, total 55ms
,I/DBG_DM  ( 4782): [3.19.140541][Line:408][onResume] 
,D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10602, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/DBG_DM  ( 4782): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
,I/FPMS_FingerprintManagerService( 2600): onReceive: android.intent.action.PACKAGE_REMOVED
,E/SamsungIME( 2988): mOCRHelper is null
,D/dalvikvm( 2951): GC_EXPLICIT freed 1469K, 29% free 10033K/13996K, paused 8ms+5ms, total 108ms
,I/DBG_DM  ( 4782): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,D/QuickConnect[1.1][2] ( 5200): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
,I/DBG_DM  ( 4782): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/InputReader( 2420): Reconfiguring input devices.  changes=0x00000010
,I/DBG_DM  ( 4782): [3.19.140541][Line:418][onResume] Postpone Count : 29
,I/SELinux ( 7521): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7521):  
,W/GeofencerStateMachine( 2734): Ignoring removeGeofence because network location is disabled.
,D/dalvikvm( 3315): GC_EXPLICIT freed 2244K, 23% free 12421K/16096K, paused 10ms+10ms, total 159ms
,I/DBG_DM  ( 4782): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 14% free 9500K/10976K, paused 3ms+3ms, total 32ms
,I/SELinux ( 7521): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7521):  
I/SELinux ( 7521):  
,I/SELinux ( 7521): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7521): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7521): >>>>> Normal User
,E/dalvikvm( 7521): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 7521): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 14% free 9500K/10976K, paused 2ms+3ms, total 25ms
,I/DBG_DM  ( 4782): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 14% free 9500K/10976K, paused 3ms+4ms, total 26ms
,D/TimaKeyStoreProvider( 7521): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7521): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7521): Added TimaKesytore provider
,I/DBG_DM  ( 4782): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,D/dalvikvm( 2420): GC_EXPLICIT freed 2241K, 73% free 25139K/89900K, paused 9ms+25ms, total 233ms
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "smsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4782): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
,I/DBG_DM  ( 4782): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4782): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4782): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4782): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4782): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,D/RegisteredServicesCache( 2756): empty dynamic service
,I/DBG_DM  ( 4782): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mmsto"
,D/Activity( 4782): setTransGradationMode to true
,D/PhoneStatusBar( 2580): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2420): semi p:4782,o:t
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4782): [3.19.140541][Line:400][onPause] 
,I/SurfaceFlinger( 1920): id=21 createSurf (720x1280),2 flag=404, YUIInstallC
,D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/RCPManagerService( 2420): PackageReceiver onReceive()
,D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
,D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
I/HarmonyEASService( 2420): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 7521): GC_CONCURRENT freed 3004K, 32% free 9563K/13996K, paused 7ms+1ms, total 37ms
,D/dalvikvm( 7521): WAIT_FOR_CONCURRENT_GC blocked 12ms
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "smsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2420): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@8
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 0
,D/dalvikvm( 2756): GC_CONCURRENT freed 1582K, 32% free 10251K/14960K, paused 7ms+2ms, total 80ms
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
,D/elm:14132( 7521): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mmsto"
,D/elm:14132( 7521): ELMEngine.ELMEngine( context ).
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 7521): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 7521): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14132( 7521): ElmAgentService : onCreate()
W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
D/elm:14132( 7521): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 7521): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 7521): MDMBridge.getInstance()
,D/elm:14132( 7521): MDMBridge.getAllLicenseInfoFromSDK()
W/InputMethodManagerService( 2420): Got RemoteException sending setActive(false) notification to pid 7171 uid 10602
,D/elm:14132( 7521): MDMBridge.getAllLicenseInfoFromSDK()
,I/SELinux ( 7540): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7540):  
,D/elm:14132( 7521): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
,D/elm:14132( 7521): ElmAgentService : onDestroy().
I/ActivityManager( 2420): Killing 6586:com.android.defcontainer/u0a6 (adj 15): empty #43
,I/SELinux ( 7540): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7540):  
I/SELinux ( 7540):  
,I/SELinux ( 7540): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7540): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7540): >>>>> Normal User
,E/dalvikvm( 7540): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,E/SELinux ( 7540): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/EnterpriseDeviceManagerService( 2420): Package has changed for user 0
,D/TimaKeyStoreProvider( 7540): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7540): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7540): Added TimaKesytore provider
,D/BackupManagerService( 2420): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 2420): removePackageParticipantsLocked: uid=10602 #1
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2420): sendNotification(2) - 4
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 7540): GC_CONCURRENT freed 2990K, 32% free 9576K/14000K, paused 4ms+1ms, total 38ms
,D/dalvikvm( 7540): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 2420): GC_EXPLICIT freed 1389K, 72% free 25209K/89900K, paused 13ms+30ms, total 523ms
D/PackageManager( 2420): delete sourFile : 
,D/PackageManager( 2420): delete native library directory: 
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 2420): return delete result to caller: 1121960464
,D/AndroidRuntime( 7510): Shutting down VM
,D/PackageManager( 2420): returnCode: 1
D/dalvikvm( 7510): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+0ms, total 4ms
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "smsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 7555): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7555):  
,I/ActivityManager( 2420): Killing 6503:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 7555): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7555):  
I/SELinux ( 7555):  
,I/SELinux ( 7555): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7555): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7555): >>>>> Normal User
,E/dalvikvm( 7555): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
,E/SELinux ( 7555): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mmsto"
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 7555): in addTimaSignatureService
D/TimaKeyStoreProvider( 7555): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7555): Added TimaKesytore provider
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 7555): GC_CONCURRENT freed 2994K, 32% free 9565K/13992K, paused 5ms+1ms, total 26ms
,D/dalvikvm( 7555): WAIT_FOR_CONCURRENT_GC blocked 18ms
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PCWCLIENTTRACE_PushUtil( 6641): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6641): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6641): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6641): [onReceive] - android.intent.action.PACKAGE_REMOVED
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector( 2420): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2420): clearDefaults: com.test.thalitest
,W/ApplicationsProvider( 2951): Could not fetch usage stats
W/ApplicationsProvider( 2951): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2951): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2951): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2951): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2951): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2951): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2951): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2951): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2951): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2951): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2951): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2951): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
I/SA      ( 5866): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
I/SA      ( 5866): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
,E/SharedPreferencesImpl( 3601): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,I/Icing.InternalIcingCorporaProvider( 6483): Updating corpora: A: com.test.thalitest, C: MAYBE
,E/SQLiteLog( 6483): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/dalvikvm( 6483): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,I/SELinux ( 7575): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7575):  
E/AndroidRuntime( 6483): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 6483): Process: com.google.android.googlequicksearchbox:search, PID: 6483
E/AndroidRuntime( 6483): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6483): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6483): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 6483): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6483): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6483): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 6483): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 6483): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:171)
E/AndroidRuntime( 6483): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 6483): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
E/AndroidRuntime( 6483): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 6483): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 6483): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 6483): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 6483): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 6483): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 6483): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 6483): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6483): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6483): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6483): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6483): Sending signal. PID: 6483 SIG: 9
E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop221.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager( 2420): Process com.google.android.googlequicksearchbox:search (pid 6483) (adj 5) has died.
I/SELinux ( 7575): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7575):  
I/SELinux ( 7575):  
I/SELinux ( 7575): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7575): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7575): >>>>> Normal User
E/dalvikvm( 7575): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
E/SELinux ( 7575): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7575): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7575): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7575): Added TimaKesytore provider
,D/dalvikvm( 7575): GC_CONCURRENT freed 2998K, 32% free 9567K/14000K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7575): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/UserAnalysis.PlaceProvider( 7575): Create SecureDbHelper
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 7575): Create SecureDbHelper
,E/SQLiteDatabase( 7575): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7575): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7575): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7575): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7575): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7575): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7575): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteDatabase( 7575): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7575): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7575): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7575): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7575): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7575): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7575): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7575): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7575): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7575): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7575): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7575): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7575): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7575): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7575): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7575): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7575): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7575): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7575): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7575): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7575): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7575): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7575): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7575): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7575): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7575): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7575): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7575): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7575): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7575): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteOpenHelper( 7575): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7575): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7575): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7575): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7575): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7575): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7575): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7575): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7575): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7575): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7575): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7575): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 7575): Opened privacy in read-only mode
E/SQLiteDatabase( 7575): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7575): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7575): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7575): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7575): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7575): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7575): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteDatabase( 7575): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7575): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7575): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7575): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7575): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7575): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7575): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7575): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7575): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7575): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7575): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7575): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 7575): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7575): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7575): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7575): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7575): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7575): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7575): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7575): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7575): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7575): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7575): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7575): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7575): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7575): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7575): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7575): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7575): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7575): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteOpenHelper( 7575): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7575): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7575): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7575): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7575): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7575): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7575): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7575): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7575): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7575): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7575): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7575): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 7575): Opened privacy in read-only mode
E/SQLiteDatabase( 7575): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7575): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7575): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7575): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7575): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7575): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7575): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
E/SQLiteDatabase( 7575): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7575): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7575): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7575): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7575): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7575): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7575): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7575): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7575): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7575): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7575): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7575): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 7575): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 7575): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 7575): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 7575): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 7575): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 7575): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 7575): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 7575): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 7575): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 7575): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 7575): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 7575): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7575): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7575): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 7575): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 7575): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
W/System.err( 7575): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
W/System.err( 7575): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 7575): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 7575): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 7575): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7575): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 7575): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 7575): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 7575): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 7575): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 7575): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 7575): 	at dalvik.system.NativeStart.main(Native Method)
W/ContextImpl( 6419): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:165 android.app.ActivityThread.handleReceiver:2698 
D/RCPManager( 6498):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2420):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 2420): queryAllProviders():  providerCallBack is not register for 0
D/CapabilityManagerService New( 6713): Receiver Broadcast:android.intent.action.PACKAGE_REMOVED
D/CapabilityManagerService New( 6713): The package(com.test.thalitest) removed
E/SQLiteDatabase( 6419): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 6419): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6419): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6419): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6419): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6419): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6419): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6419): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6419): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6419): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6419): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6419): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6419): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6419): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6419): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6419): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 6419): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 6419): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6419): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6419): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6419): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 6419): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 6419): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 6419): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 6419): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 6419): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 6419): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 6419): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 6419): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 6419): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 6419): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 6419): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 6419): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 6419): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 6419): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 6419): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 6419): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 6419): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 6419): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6419): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6419): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 2420): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2420): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2420): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2420): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 2420): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2420): 	... 8 more
W/System.err( 2420): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2420): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2420): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2420): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2420): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2420): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 2420): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2420): 	... 8 more
,D/MagazineService::MagazineBroadcastReceiver( 6739): [onReceive] android.intent.action.PACKAGE_REMOVED com.test.thalitest
,I/MagazineService::MagazineService( 6739): [onHandleIntent] ACTION_PACKAGE_REMOVED
D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@8
,I/SELinux ( 7590): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7590):  
,E/SQLiteDatabase( 6739): Failed to open database '/data/data/com.samsung.android.app.headlines/databases/card.db'.
E/SQLiteDatabase( 6739): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6739): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6739): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6739): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6739): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6739): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6739): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6739): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6739): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6739): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6739): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/SQLiteDatabase( 6739): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/SQLiteDatabase( 6739): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/SQLiteDatabase( 6739): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/SQLiteDatabase( 6739): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6739): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6739): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6739): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 6739): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 6739): FATAL EXCEPTION: IntentService[MagazineService::MagazineService]
E/AndroidRuntime( 6739): Process: com.samsung.android.magazine.service, PID: 6739
E/AndroidRuntime( 6739): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6739): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 6739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 6739): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6739): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 6739): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 6739): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 6739): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 6739): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 6739): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 6739): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 6739): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/AndroidRuntime( 6739): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6739): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6739): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/AndroidRuntime( 6739): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6739): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6739): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6739): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6739): Sending signal. PID: 6739 SIG: 9
E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop222.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager( 2420): Process com.samsung.android.magazine.service (pid 6739) (adj 5) has died.
,I/SELinux ( 7590): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7590):  
I/SELinux ( 7590):  
,I/SELinux ( 7590): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7590): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7590): >>>>> Normal User
,E/dalvikvm( 7590): >>>>> com.android.keychain [ userId:0 | appId:1000 ]
,E/SELinux ( 7590): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7590): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7590): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7590): Added TimaKesytore provider
,D/dalvikvm( 7590): GC_CONCURRENT freed 3008K, 32% free 9563K/14000K, paused 1ms+1ms, total 17ms
,D/dalvikvm( 7590): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/ContextImpl( 7590): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2698 
,D/KidsModeInstallReceiver( 6765): onReceive intent data =  package:com.test.thalitest
,E/SQLiteDatabase( 7590): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 7590): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7590): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7590): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7590): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7590): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7590): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7590): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7590): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7590): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7590): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7590): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7590): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7590): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7590): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7590): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/SQLiteDatabase( 7590): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/SQLiteDatabase( 7590): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7590): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7590): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7590): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7590): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,D/KidsPlatformStub( 6765): Package not found : com.sec.android.app.kidshome
E/AndroidRuntime( 7590): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 7590): Process: com.android.keychain, PID: 7590
E/AndroidRuntime( 7590): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7590): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7590): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7590): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7590): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7590): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7590): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7590): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7590): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7590): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7590): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7590): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7590): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7590): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7590): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/AndroidRuntime( 7590): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/AndroidRuntime( 7590): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7590): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7590): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7590): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/System.err( 6803): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop223.tmp: open failed: EROFS (Read-only file system)
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
W/System.err( 6803): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
W/System.err( 6803): 	at com.n7mobile.promenada2.applications.ApplicationInstallationReceiver.onReceive(SourceFile:27)
W/System.err( 6803): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 6803): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 6803): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
I/Process ( 7590): Sending signal. PID: 7590 SIG: 9
W/System.err( 6803): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6803): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6803): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 6803): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 6803): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 6803): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 6803): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 6803): 	at dalvik.system.NativeStart.main(Native Method)
,I/ActivityManager( 2420): Process com.android.keychain (pid 7590) (adj 5) has died.
D/PackageBroadcastService( 3315): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 3315): Clearing selected account for com.test.thalitest
I/ActivityManager( 2420): Waited long enough for: ServiceRecord{4451ede0 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,E/SQLiteLog( 3315): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,I/LocationSettingsChecker( 3315): Removing dialog suppression flag for package com.test.thalitest
,D/ChimeraCfgMgr( 3315): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3315): Module APK com.google.android.play.games already loaded
,E/DriveAsyncService( 3315): disk I/O error (code 3850)
E/DriveAsyncService( 3315): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 3315): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 3315): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/DriveAsyncService( 3315): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 3315): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 3315): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/DriveAsyncService( 3315): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/DriveAsyncService( 3315): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 3315): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 3315): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 3315): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 3315): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 3315): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 3315): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 3315): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 3315): 	at java.lang.Thread.run(Thread.java:841)
,E/SQLiteDatabase( 3315): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 3315): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3315): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3315): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3315): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3315): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3315): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3315): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3315): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3315): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3315): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3315): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3315): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3315): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3315): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3315): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 3315): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 3315): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 3315): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 3315): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3315): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3315): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3315): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 3315): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 3315): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3315): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3315): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 3315): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 3315): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 3315): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 3315): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 3315): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 3315): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 3315): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 3315): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 3315): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 3315): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3315): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3315): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 3315): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 3315): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 3315): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 3315): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 3315): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3315): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 3315): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 3315): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 3315): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/ChimeraCfgMgr( 3315): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3315): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 3315): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,E/SQLiteLog( 2849): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteLog( 3315): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
E/SQLiteLog( 3315): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/gH_CompatibleDatabase( 3315): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/dalvikvm( 3315): threadid=48: thread exiting with uncaught exception (group=0x4180ac08)
D/AndroidRuntime( 2849): Shutting down VM
,W/dalvikvm( 2849): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 3315): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 3315): Process: com.google.android.gms, PID: 3315
E/AndroidRuntime( 3315): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 3315): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 3315): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 3315): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 3315): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 3315): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 3315): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 3315): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 3315): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 3315): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3315): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 3315): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 3315): Runtime exception while performing operation
E/ClearPendingStateOp( 3315): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 3315): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 3315): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/ClearPendingStateOp( 3315): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 3315): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 3315): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/ClearPendingStateOp( 3315): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
E/ClearPendingStateOp( 3315): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 3315): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 3315): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/ClearPendingStateOp( 3315): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/ClearPendingStateOp( 3315): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 3315): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 3315): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 3315): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 3315): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 3315): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 3315): 	at java.lang.Thread.run(Thread.java:841)
,E/SQLiteDatabase( 3315): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 3315): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3315): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3315): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3315): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3315): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3315): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3315): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3315): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3315): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3315): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3315): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3315): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3315): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3315): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3315): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3315): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 3315): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3315): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3315): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3315): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 3315): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 3315): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 3315): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 3315): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
F/ClearPendingStateOp( 3315): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 3315): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 3315): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
F/ClearPendingStateOp( 3315): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
F/ClearPendingStateOp( 3315): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 3315): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 3315): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
F/ClearPendingStateOp( 3315): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
F/ClearPendingStateOp( 3315): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 3315): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 3315): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 3315): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 3315): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 3315): 	at com.google.android.gms.common.util.a.c.run(Sourc,eFile:17)
F/ClearPendingStateOp( 3315): 	at java.lang.Thread.run(Thread.java:841)
E/PhenotypeInitializer( 3315): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 3315): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 3315): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 3315): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/PhenotypeInitializer( 3315): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/PhenotypeInitializer( 3315): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 3315): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 3315): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 3315): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/PhenotypeInitializer( 3315): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/PhenotypeInitializer( 3315): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/PhenotypeInitializer( 3315): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/PhenotypeInitializer( 3315): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3315): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3315): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 3315): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 3315): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 3315): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 3315): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 3315): 	at android.os.Looper.loop(Looper.java:146)
E/PhenotypeInitializer( 3315): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 3315): Sending signal. PID: 3315 SIG: 9
E/AndroidRuntime( 2849): FATAL EXCEPTION: main
E/AndroidRuntime( 2849): Process: com.google.process.gapps, PID: 2849
E/AndroidRuntime( 2849): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2849): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 2849): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 2849): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 2849): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2849): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2849): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 2849): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2849): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2849): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 2849): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 2849): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2849): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2849): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2849): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 2849): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2849): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2849): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 2849): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 2849): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 2849): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 2849): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 2849): 	... 10 more
E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop224.tmp: open failed: EROFS (Read-only file system)
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
,I/Process ( 2849): Sending signal. PID: 2849 SIG: 9
E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop225.tmp: open failed: EROFS (Read-only file system)
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
,E/SQLiteDatabase( 5600): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5600): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5600): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5600): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5600): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5600): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5600): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5600): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5600): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5600): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5600): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5600): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5600): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5600): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5600): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5600): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5600): 	at com.sec.spp.push.i.d.e(Unknown Source)
E/SQLiteDatabase( 5600): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5600): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5600): 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
E/SQLiteDatabase( 5600): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5600): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5600): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 5600): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5600): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5600): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 5600): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 5600): 	at dalvik.system.NativeStart.main(Native Method)
,E/SPPClientService( 5600): [d] [getAppId()] Exception with message =not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6460): Failed to open database '/data/data/com.sec.spp.push/databases/evtDb'.
E/SQLiteDatabase( 6460): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6460): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6460): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6460): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6460): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6460): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6460): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6460): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6460): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6460): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6460): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6460): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6460): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6460): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6460): 	at com.sec.spp.push.notisvc.tracking.h.b(Unknown Source)
E/SQLiteDatabase( 6460): 	at com.sec.spp.push.notisvc.tracking.g.a(Unknown Source)
E/SQLiteDatabase( 6460): 	at com.sec.spp.push.notisvc.tracking.f.a(Unknown Source)
E/SQLiteDatabase( 6460): 	at com.sec.spp.push.notisvc.tracking.a.c(Unknown Source)
E/SQLiteDatabase( 6460): 	at com.sec.spp.push.notisvc.tracking.a.a(Unknown Source)
E/SQLiteDatabase( 6460): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6460): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6460): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6460): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6460): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6460): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6460): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6460): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6460): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6460): [g] not an error (code 0): Could not open the database in read/write mode.
,D/GAV2    ( 5691): Thread[main,5,main]: service disconnected: ComponentInfo{com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService}
,I/GAV2    ( 5691): Thread[main,5,main]: Unexpected disconnect.
,I/SELinux ( 7616): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7616):  
,I/ActivityManager( 2420): Process com.google.android.gms (pid 3315) (adj 5) has died.
E/SQLiteDatabase( 6460): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 6460): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6460): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6460): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6460): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6460): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6460): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6460): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6460): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6460): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6460): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6460): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6460): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6460): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6460): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6460): 	at com.sec.spp.push.notisvc.b.b.<init>(Unknown Source)
E/SQLiteDatabase( 6460): 	at com.sec.spp.push.notisvc.b.b.a(Unknown Source)
E/SQLiteDatabase( 6460): 	at com.sec.spp.push.notisvc.registration.q.b(Unknown Source)
E/SQLiteDatabase( 6460): 	at com.sec.spp.push.notisvc.registration.q.a(Unknown Source)
E/SQLiteDatabase( 6460): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6460): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6460): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6460): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6460): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6460): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6460): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6460): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6460): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6460): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6460): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6460): [b] open fail. android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/ActivityManager( 2420): Process com.google.process.gapps (pid 2849) (adj 5) has died.
,I/SELinux ( 7616): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7616):  
I/SELinux ( 7616):  
,I/SELinux ( 7616): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7616): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7616): >>>>> Normal User
,E/dalvikvm( 7616): >>>>> com.android.documentsui [ userId:0 | appId:10093 ]
,E/SELinux ( 7616): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7616): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7616): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7616): Added TimaKesytore provider
,D/dalvikvm( 7616): GC_CONCURRENT freed 3006K, 32% free 9565K/14000K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7616): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/Documents( 7616): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 7616): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 7616): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7616): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7616): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7616): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7616): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7616): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7616): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7616): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7616): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7616): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7616): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7616): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7616): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7616): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7616): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 7616): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 7616): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 7616): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/SQLiteDatabase( 7616): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 7616): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7616): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7616): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7616): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7616): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7616): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7616): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7616): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7616): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7616): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7616): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7616): Shutting down VM
,W/dalvikvm( 7616): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7616): FATAL EXCEPTION: main
E/AndroidRuntime( 7616): Process: com.android.documentsui, PID: 7616
E/AndroidRuntime( 7616): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7616): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 7616): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 7616): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7616): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7616): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7616): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7616): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7616): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7616): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7616): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7616): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7616): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7616): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7616): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7616): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7616): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7616): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7616): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7616): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7616): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7616): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7616): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7616): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7616): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7616): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7616): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 7616): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 7616): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 7616): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/AndroidRuntime( 7616): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 7616): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 7616): 	... 10 more
,I/SELinux ( 7631): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7631):  
,I/SELinux ( 7635): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7635):  
,I/ActivityManager( 2420): Killing 6616:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/Process ( 7616): Sending signal. PID: 7616 SIG: 9
E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop226.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager( 2420): Process com.android.documentsui (pid 7616) (adj 9) has died.
,I/SELinux ( 7631): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7631):  
I/SELinux ( 7631):  
,I/SELinux ( 7631): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7631): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7631): >>>>> Normal User
,E/dalvikvm( 7631): >>>>> com.android.externalstorage [ userId:0 | appId:10009 ]
,E/SELinux ( 7631): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/SELinux ( 7635): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7635):  
I/SELinux ( 7635):  
,I/SELinux ( 7635): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7635): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7635): >>>>> Normal User
,E/dalvikvm( 7635): >>>>> com.google.android.gms [ userId:0 | appId:10012 ]
,E/SELinux ( 7635): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7631): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7631): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7631): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 7635): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7635): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7635): Added TimaKesytore provider
,D/dalvikvm( 7631): GC_CONCURRENT freed 3003K, 32% free 9562K/14000K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 7631): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 7635): GC_CONCURRENT freed 2948K, 32% free 9620K/14000K, paused 2ms+2ms, total 20ms
,D/dalvikvm( 7635): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/ExternalStorage( 7631): After updating volumes, found 1 active roots
,W/dalvikvm( 7635): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7635): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 7635): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 7635): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 7635): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 7635): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7635): install
,I/MultiDex( 7635): MultiDexExtractor.load(/data/app/com.google.android.gms-5.apk, false)
,I/MultiDex( 7635): loading existing secondary dex files
,I/MultiDex( 7635): load found 3 secondary dex files
,I/MultiDex( 7635): install done
,I/SELinux ( 7658): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7658):  
,I/SELinux ( 7663): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7663):  
,I/SELinux ( 7658): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7658):  
I/SELinux ( 7658):  
,I/SELinux ( 7658): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7658): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7658): >>>>> Normal User
,E/dalvikvm( 7658): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 7658): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7658): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7658): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7658): Added TimaKesytore provider
,I/SELinux ( 7663): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7663):  
I/SELinux ( 7663):  
,I/SELinux ( 7663): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7663): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7663): >>>>> Normal User
,E/dalvikvm( 7663): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7663): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7663): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7663): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7663): Added TimaKesytore provider
,D/dalvikvm( 7658): GC_CONCURRENT freed 2994K, 32% free 9573K/13996K, paused 2ms+1ms, total 28ms
,D/dalvikvm( 7658): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 7663): GC_CONCURRENT freed 2997K, 32% free 9571K/14000K, paused 2ms+1ms, total 25ms
,D/dalvikvm( 7663): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/Icing.InternalIcingCorporaProvider( 7658): Updating corpora: A: com.test.thalitest, C: MAYBE
,I/SELinux ( 7688): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7688):  
,D/LocationManagerService( 2420): getProviders()=[passive]
,I/GservicesProvider( 7663): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7663): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7663): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7663): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7663): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7663): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7663): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7663): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7663): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7663): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7663): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7663): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7663): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7663): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7663): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7663): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7663): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7663): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7663): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7663): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 7663): Shutting down VM
,W/dalvikvm( 7663): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
I/SELinux ( 7688): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7688):  
I/SELinux ( 7688):  
,E/AndroidRuntime( 7663): FATAL EXCEPTION: main
E/AndroidRuntime( 7663): Process: com.google.process.gapps, PID: 7663
E/AndroidRuntime( 7663): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7663): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7663): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7663): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7663): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7663): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7663): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7663): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7663): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7663): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7663): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7663): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7663): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7663): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7663): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7663): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7663): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7663): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7663): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7663): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7663): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7663): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7663): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7663): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7663): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7663): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7663): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7663): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7663): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7663): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7663): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7663): 	... 12 more
I/SELinux ( 7688): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7688): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7688): >>>>> Normal User
E/dalvikvm( 7688): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
E/SELinux ( 7688): [DEBUG] seapp_context_lookup: seinfoCategory = untrus,ted
I/Process ( 7663): Sending signal. PID: 7663 SIG: 9
,E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop227.tmp: open failed: EROFS (Read-only file system)
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
,D/TimaKeyStoreProvider( 7688): in addTimaSignatureService
I/ActivityManager( 2420): Process com.google.process.gapps (pid 7663) (adj 0) has died.
W/ActivityManager( 2420): Service crashed 2 times, stopping: ServiceRecord{431a2e18 u0 com.google.android.gms/.gcm.GcmService}
,D/TimaKeyStoreProvider( 7688): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7688): Added TimaKesytore provider
,I/SELinux ( 7705): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7705):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 44K, 14% free 9500K/10976K, paused 2ms+4ms, total 32ms
,I/SELinux ( 7705): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7705):  
I/SELinux ( 7705):  
,I/SELinux ( 7705): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7705): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7705): >>>>> Normal User
,E/dalvikvm( 7705): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7705): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 14% free 9500K/10976K, paused 2ms+3ms, total 26ms
,D/TimaKeyStoreProvider( 7705): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7705): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7705): Added TimaKesytore provider
,D/dalvikvm( 7688): GC_CONCURRENT freed 3002K, 32% free 9564K/13996K, paused 3ms+2ms, total 26ms
,D/dalvikvm( 7688): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 14% free 9500K/10976K, paused 2ms+3ms, total 24ms
,D/dalvikvm( 7705): GC_CONCURRENT freed 2981K, 32% free 9575K/13992K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 7705): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7705): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7705): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7705): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7705): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7705): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7705): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7705): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7705): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7705): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7705): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7705): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7705): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7705): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7705): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7705): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7705): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7705): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7705): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7705): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7705): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7705): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7705): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7705): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7705): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7705): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7705): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7705): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7705): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7705): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7705): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7705): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7705): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7705): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7705): Shutting down VM
,W/dalvikvm( 7705): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7705): FATAL EXCEPTION: main
E/AndroidRuntime( 7705): Process: com.google.process.gapps, PID: 7705
E/AndroidRuntime( 7705): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7705): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7705): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7705): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7705): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7705): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7705): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7705): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7705): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7705): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7705): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7705): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7705): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7705): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7705): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7705): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7705): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7705): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7705): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7705): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7705): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7705): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7705): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7705): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7705): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7705): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7705): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7705): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7705): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7705): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7705): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7705): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7705): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7705): 	... 12 more
W/ActivityManager( 2420): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2420): Killing 7705:com.google.process.gapps/u0a12 (adj 0): crash
E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /d,ata/system/dropbox/drop228.tmp: open failed: EROFS (Read-only file system)
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
W/ActivityManager( 2420): Unable to launch app com.google.android.gsf/10012 for provider com.google.settings: launching app became null
W/ActivityManager( 2420): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
W/ActivityManager( 2420): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7635): Failed to find provider info for com.google.android.gsf.gservices
E/ActivityThread( 7658): Failed to find provider info for com.google.settings
E/ActivityThread( 7688): Failed to find provider info for com.google.android.gsf.gservices
,I/SELinux ( 7723): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7723):  
,I/SELinux ( 7723): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7723):  
I/SELinux ( 7723):  
,I/SELinux ( 7723): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7723): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7723): >>>>> Normal User
,E/dalvikvm( 7723): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7723): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7723): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7723): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7723): Added TimaKesytore provider
,D/dalvikvm( 7723): GC_CONCURRENT freed 2990K, 32% free 9576K/13996K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7723): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7723): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7723): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7723): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7723): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7723): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7723): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7723): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7723): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7723): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7723): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7723): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7723): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7723): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7723): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7723): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7723): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7723): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7723): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7723): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7723): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7723): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7723): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7723): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7723): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7723): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7723): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7723): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7723): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7723): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7723): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7723): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7723): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7723): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7723): Shutting down VM
,W/dalvikvm( 7723): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7723): FATAL EXCEPTION: main
E/AndroidRuntime( 7723): Process: com.google.process.gapps, PID: 7723
E/AndroidRuntime( 7723): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7723): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7723): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7723): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7723): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7723): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7723): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7723): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7723): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7723): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7723): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7723): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7723): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7723): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7723): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7723): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7723): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7723): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7723): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7723): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7723): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7723): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7723): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7723): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7723): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7723): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7723): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7723): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7723): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7723): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7723): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7723): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7723): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7723): 	... 12 more
,I/Process ( 7723): Sending signal. PID: 7723 SIG: 9
E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop229.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager( 2420): Process com.google.process.gapps (pid 7723) (adj 0) has died.
,I/SELinux ( 7738): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7738):  
,I/SELinux ( 7738): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7738):  
I/SELinux ( 7738):  
,I/SELinux ( 7738): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7738): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7738): >>>>> Normal User
,E/dalvikvm( 7738): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7738): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7738): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7738): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7738): Added TimaKesytore provider
,D/dalvikvm( 7738): GC_CONCURRENT freed 2987K, 32% free 9582K/14000K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 7738): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7738): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7738): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7738): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7738): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7738): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7738): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7738): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7738): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7738): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7738): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7738): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7738): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7738): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7738): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7738): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7738): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7738): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7738): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7738): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7738): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7738): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7738): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7738): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7738): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7738): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7738): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7738): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7738): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7738): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7738): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7738): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7738): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7738): Shutting down VM
,W/dalvikvm( 7738): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7738): FATAL EXCEPTION: main
E/AndroidRuntime( 7738): Process: com.google.process.gapps, PID: 7738
E/AndroidRuntime( 7738): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7738): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7738): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7738): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7738): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7738): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7738): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7738): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7738): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7738): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7738): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7738): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7738): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7738): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7738): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7738): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7738): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7738): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7738): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7738): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7738): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7738): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7738): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7738): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7738): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7738): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7738): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7738): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7738): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7738): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7738): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7738): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7738): 	... 12 more
W/ActivityManager( 2420): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2420): Killing 7738:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2420): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launc,hing app became null
W/ActivityManager( 2420): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7688): Failed to find provider info for com.google.android.gsf.gservices
E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop230.tmp: open failed: EROFS (Read-only file system)
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
E/ActivityThread( 7635): Failed to find provider info for com.google.android.gsf.gservices
D/dalvikvm( 7635): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7635): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7635): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7635): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7635): VFY: unable to resolve instance field 36
D/dalvikvm( 7635): VFY: replacing opcode 0x54 at 0x005f
,I/ActivityManager( 2420): Killing 5760:com.android.mms/u0a49 (adj 15): empty #43
D/dalvikvm( 7635): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7635): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7635): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 7635): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 7635): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 7635): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422c91a0
D/dalvikvm( 7635): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422c91a0
D/dalvikvm( 7635): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422c91a0, skipping init
,D/dalvikvm( 7635): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x422c91a0
D/dalvikvm( 7635): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x422c91a0
,V/JNIHelp ( 7635): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager( 2420): Waited long enough for: ServiceRecord{4454fb48 u0 com.sec.spp.push/.PushClientService}
,D/CountryDetector( 2420): No listener is left
,D/dalvikvm( 7635): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422c91a0
D/dalvikvm( 7635): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x422c91a0
,D/dalvikvm( 7635): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x422c91a0
,D/dalvikvm( 7635): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x422c91a0
,I/ProviderInstaller( 7635): Installed default security provider GmsCore_OpenSSL
,I/SELinux ( 7753): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7753):  
,I/SELinux ( 7753): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7753):  
I/SELinux ( 7753):  
,I/SELinux ( 7753): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7753): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7753): >>>>> Normal User
,E/dalvikvm( 7753): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7753): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7753): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7753): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7753): Added TimaKesytore provider
,D/dalvikvm( 7753): GC_CONCURRENT freed 2998K, 32% free 9569K/14000K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7753): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7753): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7753): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7753): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7753): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7753): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7753): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7753): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7753): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7753): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7753): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7753): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7753): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7753): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7753): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7753): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7753): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7753): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7753): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7753): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7753): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7753): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7753): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7753): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7753): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7753): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7753): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7753): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7753): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7753): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7753): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7753): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7753): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7753): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 7753): Shutting down VM
,W/dalvikvm( 7753): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7753): FATAL EXCEPTION: main
E/AndroidRuntime( 7753): Process: com.google.process.gapps, PID: 7753
E/AndroidRuntime( 7753): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7753): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7753): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7753): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7753): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7753): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7753): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7753): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7753): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7753): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7753): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7753): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7753): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7753): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7753): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7753): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7753): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7753): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7753): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7753): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7753): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7753): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7753): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7753): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7753): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7753): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7753): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7753): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7753): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7753): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7753): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7753): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7753): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7753): 	... 12 more
,I/Process ( 7753): Sending signal. PID: 7753 SIG: 9
E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop231.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager( 2420): Process com.google.process.gapps (pid 7753) (adj 0) has died.
,I/SELinux ( 7768): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7768):  
,I/SELinux ( 7768): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7768):  
I/SELinux ( 7768):  
,I/SELinux ( 7768): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7768): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7768): >>>>> Normal User
,E/dalvikvm( 7768): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7768): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7768): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7768): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7768): Added TimaKesytore provider
,D/dalvikvm( 7768): GC_CONCURRENT freed 2985K, 32% free 9579K/13996K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7768): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7768): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7768): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7768): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7768): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7768): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7768): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7768): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7768): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7768): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7768): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7768): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7768): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7768): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7768): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7768): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7768): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7768): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7768): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7768): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7768): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7768): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7768): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7768): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7768): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7768): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7768): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7768): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7768): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7768): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7768): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7768): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7768): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7768): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 7768): Shutting down VM
,W/dalvikvm( 7768): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7768): FATAL EXCEPTION: main
E/AndroidRuntime( 7768): Process: com.google.process.gapps, PID: 7768
E/AndroidRuntime( 7768): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7768): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7768): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7768): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7768): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7768): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7768): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7768): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7768): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7768): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7768): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7768): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7768): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7768): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7768): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7768): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7768): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7768): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7768): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7768): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7768): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7768): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7768): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7768): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7768): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7768): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7768): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7768): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7768): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7768): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7768): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7768): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7768): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7768): 	... 12 more
W/ActivityManager( 2420): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2420): Killing 7768:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2420): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launc,hing app became null
E/ActivityThread( 7635): Failed to find provider info for com.google.android.gsf.gservices
E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop232.tmp: open failed: EROFS (Read-only file system)
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
,W/NativeLibraryUtils( 7635): Failed to open lock file
W/NativeLibraryUtils( 7635): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7635): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/NativeLibraryUtils( 7635): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:118)
W/NativeLibraryUtils( 7635): 	at com.google.android.gms.common.util.ay.b(SourceFile:325)
W/NativeLibraryUtils( 7635): 	at com.google.android.gms.common.app.b.run(SourceFile:209)
W/NativeLibraryUtils( 7635): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7635): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7635): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/NativeLibraryUtils( 7635): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/NativeLibraryUtils( 7635): 	... 3 more
,I/dalvikvm( 7635): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
,W/dalvikvm( 7635): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7635): VFY: replacing opcode 0x6e at 0x000d
,I/SELinux ( 7787): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7787):  
,W/dalvikvm( 2951): threadid=14: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 2951): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime( 2951): Process: android.process.acore, PID: 2951
E/AndroidRuntime( 2951): android.database.sqlite.SQLiteDatabaseLockedException: database is locked (code 5)
E/AndroidRuntime( 2951): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2951): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 2951): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2951): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2951): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 2951): 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:176)
E/AndroidRuntime( 2951): 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:458)
E/AndroidRuntime( 2951): 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:130)
E/AndroidRuntime( 2951): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 2951): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 2951): 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/AndroidRuntime( 2951): 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime( 2951): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2951): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2951): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2951): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SELinux ( 7787): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7787):  
I/SELinux ( 7787):  
,I/SELinux ( 7787): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/Process ( 2951): Sending signal. PID: 2951 SIG: 9
E/SELinux ( 7787): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 7787): >>>>> Normal User
,E/dalvikvm( 7787): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7787): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
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
,D/TimaKeyStoreProvider( 7787): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7787): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7787): Added TimaKesytore provider
,I/ActivityManager( 2420): Process android.process.acore (pid 2951) (adj -12) has died.
,I/SELinux ( 7800): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7800):  
,D/dalvikvm( 7787): GC_FOR_ALLOC freed 3006K, 32% free 9562K/14000K, paused 17ms, total 17ms
I/SELinux ( 7800): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7800):  
I/SELinux ( 7800):  
,I/SELinux ( 7800): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7800): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7800): >>>>> Normal User
,E/dalvikvm( 7800): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7800): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/dalvikvm( 7787): GC_CONCURRENT freed 230K, 17% free 9573K/11484K, paused 3ms+2ms, total 17ms
,D/TimaKeyStoreProvider( 7800): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7800): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7800): Added TimaKesytore provider
,D/dalvikvm( 7800): GC_CONCURRENT freed 3003K, 32% free 9567K/14000K, paused 1ms+1ms, total 18ms
,D/dalvikvm( 7800): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/GservicesProvider( 7787): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7787): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7787): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7787): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7787): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7787): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7787): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7787): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7787): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7787): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7787): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7787): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7787): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7787): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7787): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7787): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7787): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7787): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7787): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7787): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7787): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7787): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7787): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7787): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7787): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7787): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7787): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7787): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7787): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7787): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7787): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7787): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7787): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 7787): Shutting down VM
,W/dalvikvm( 7787): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7787): FATAL EXCEPTION: main
E/AndroidRuntime( 7787): Process: com.google.process.gapps, PID: 7787
E/AndroidRuntime( 7787): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7787): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7787): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7787): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7787): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7787): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7787): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7787): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7787): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7787): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7787): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7787): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7787): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7787): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7787): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7787): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7787): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7787): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7787): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7787): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7787): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7787): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7787): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7787): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7787): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7787): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7787): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7787): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7787): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7787): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7787): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7787): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7787): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7787): 	... 12 more
,I/Process ( 7787): Sending signal. PID: 7787 SIG: 9
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
,I/ActivityManager( 2420): Process com.google.process.gapps (pid 7787) (adj 0) has died.
,I/SELinux ( 7816): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7816):  
,I/SELinux ( 7816): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7816):  
I/SELinux ( 7816):  
,I/SELinux ( 7816): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7816): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7816): >>>>> Normal User
,E/dalvikvm( 7816): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7816): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7816): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7816): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7816): Added TimaKesytore provider
,E/SQLiteDatabase( 7800): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7800): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7800): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7800): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7800): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7800): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7800): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7800): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7800): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7800): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7800): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 7800): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7800): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7800): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7800): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7800): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7800): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7800): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7800): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7800): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7800): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7800): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7800): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7800): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7800): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7800): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7800): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7800): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7800): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 7800): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7800): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7800): (14) unable to open database file
E/SQLiteDatabase( 7800): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7800): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7800): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7800): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7800): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7800): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7800): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7800): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7800): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7800): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7800): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7800): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7800): Process: android.process.acore, PID: 7800
E/AndroidRuntime( 7800): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7800): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7800): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7800): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7800): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7800): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7800): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7800): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7800): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7800): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7800): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7800): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7800): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7800): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7800): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7800): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7800): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7800): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 2420): Process android.process.acore has crashed too many times: killing!
,I/Process ( 7800): Sending signal. PID: 7800 SIG: 9
E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop235.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager( 2420): Process android.process.acore (pid 7800) (adj -12) has died.
,F/ActivityManager( 2420): Service ServiceRecord{431c8e88 u0 com.android.providers.contacts/.VoicemailCleanupService} in process ProcessRecord{429d4398 7800:android.process.acore/u0a20} not same as in map: null
,E/DropBoxManagerService( 2420): Can't write: system_server_wtf
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop16.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2420): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2420): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2420): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2420): 	at android.util.Slog.wtf(Slog.java:163)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2151)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15153)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4944)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5122)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1322)
E/DropBoxManagerService( 2420): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:493)
E/DropBoxManagerService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 18 more
,I/SELinux ( 7832): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7832):  
,D/dalvikvm( 7816): GC_CONCURRENT freed 2990K, 32% free 9576K/14000K, paused 2ms+2ms, total 19ms
,D/dalvikvm( 7816): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/SELinux ( 7832): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7832):  
I/SELinux ( 7832):  
,I/SELinux ( 7832): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7832): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7832): >>>>> Normal User
,E/dalvikvm( 7832): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7832): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7832): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7832): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7832): Added TimaKesytore provider
,I/GservicesProvider( 7816): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7816): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7816): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7816): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7816): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7816): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7816): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7816): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7816): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7816): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7816): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7816): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7816): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7816): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7816): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7816): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7816): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7816): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7816): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7816): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7816): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7816): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7816): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7816): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7816): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7816): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7816): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7816): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7816): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 7816): Shutting down VM
,W/dalvikvm( 7816): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7816): FATAL EXCEPTION: main
E/AndroidRuntime( 7816): Process: com.google.process.gapps, PID: 7816
E/AndroidRuntime( 7816): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7816): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7816): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7816): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7816): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7816): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7816): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7816): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7816): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7816): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7816): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7816): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7816): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7816): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7816): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7816): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7816): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7816): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7816): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7816): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7816): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7816): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7816): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7816): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7816): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7816): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7816): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7816): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7816): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7816): 	... 12 more
,I/GAv4-SVC( 7635): Google Analytics 8.4.89 is starting up.
W/ActivityManager( 2420): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2420): Killing 7816:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2420): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7635): Failed to find provider info for com.google.android.gsf.gservices
E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop237.tmp: open failed: EROFS (Read-only file system)
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
,I/SELinux ( 7849): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7849):  
,D/dalvikvm( 7832): GC_CONCURRENT freed 2987K, 32% free 9580K/13996K, paused 3ms+2ms, total 20ms
,D/dalvikvm( 7832): WAIT_FOR_CONCURRENT_GC blocked 12ms
,I/SELinux ( 7849): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7849):  
I/SELinux ( 7849):  
,I/SELinux ( 7849): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7849): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7849): >>>>> Normal User
,E/dalvikvm( 7849): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7849): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7849): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7849): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7849): Added TimaKesytore provider
,D/dalvikvm( 7849): GC_CONCURRENT freed 2991K, 32% free 9576K/14000K, paused 3ms+1ms, total 22ms
,D/dalvikvm( 7849): WAIT_FOR_CONCURRENT_GC blocked 13ms
,E/SQLiteDatabase( 7832): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7832): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7832): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7832): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7832): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7832): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7832): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7832): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7832): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7832): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7832): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 7832): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7832): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7832): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7832): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7832): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7832): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7832): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7832): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7832): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7832): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7832): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7832): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7832): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7832): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7832): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7832): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7832): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7832): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 7832): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7832): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7832): (14) unable to open database file
E/SQLiteDatabase( 7832): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7832): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7832): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7832): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7832): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7832): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7832): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7832): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7832): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7832): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7832): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7832): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7832): Process: android.process.acore, PID: 7832
E/AndroidRuntime( 7832): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7832): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7832): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7832): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7832): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7832): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7832): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7832): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7832): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 7832): Sending signal. PID: 7832 SIG: 9
W/ActivityManager( 2420): Process android.process.acore has crashed too many times: killing!
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
,I/ActivityManager( 2420): Process android.process.acore (pid 7832) (adj -12) has died.
,I/SELinux ( 7867): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7867):  
,I/GservicesProvider( 7849): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7849): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7849): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7849): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7849): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7849): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7849): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7849): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7849): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7849): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7849): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7849): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7849): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7849): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7849): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7849): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7849): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7849): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7849): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7849): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7849): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7849): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7849): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7849): Shutting down VM
,W/dalvikvm( 7849): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7849): FATAL EXCEPTION: main
E/AndroidRuntime( 7849): Process: com.google.process.gapps, PID: 7849
E/AndroidRuntime( 7849): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7849): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7849): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7849): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7849): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7849): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7849): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7849): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7849): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7849): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7849): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7849): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7849): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7849): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7849): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7849): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7849): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7849): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7849): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7849): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7849): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7849): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7849): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7849): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7849): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7849): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7849): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7849): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7849): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7849): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7849): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7849): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7849): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7849): 	... 12 more
,I/Process ( 7849): Sending signal. PID: 7849 SIG: 9
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
,I/SELinux ( 7867): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7867):  
I/SELinux ( 7867):  
,I/SELinux ( 7867): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7867): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7867): >>>>> Normal User
,E/dalvikvm( 7867): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7867): [DEBUG] seapp_context_lookup: seinfoCategory = shared
I/ActivityManager( 2420): Process com.google.process.gapps (pid 7849) (adj 0) has died.
,D/TimaKeyStoreProvider( 7867): in addTimaSignatureService
,I/SELinux ( 7881): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7881):  
,D/TimaKeyStoreProvider( 7867): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7867): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed 44K, 14% free 9500K/10976K, paused 2ms+3ms, total 31ms
,I/SELinux ( 7881): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7881):  
I/SELinux ( 7881):  
,I/SELinux ( 7881): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7881): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7881): >>>>> Normal User
,E/dalvikvm( 7881): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]

```
