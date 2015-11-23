#### Test 51517283e387105_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
,I/PowerManagerService( 2418): [PWL] Off : 180s ago
--------- beginning of /dev/log/main
D/AndroidRuntime( 7280): 
D/AndroidRuntime( 7280): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7280): CheckJNI is OFF
D/AndroidRuntime( 7280): setted country_code = Poland
D/AndroidRuntime( 7280): setted countryiso_code = PL
D/AndroidRuntime( 7280): setted sales_code = PLS
D/AndroidRuntime( 7280): readGMSProperty: start
D/AndroidRuntime( 7280): readGMSProperty: already setted!!
D/AndroidRuntime( 7280): readGMSProperty: end
D/AndroidRuntime( 7280): addProductProperty: start
D/dalvikvm( 7280): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7280): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7280): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7280): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7280): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
E/memtrack( 7280): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7280): failed to load memtrack module: -2
D/AmoledAdjustTimer( 2418): prevTemp = 311, currTemp = 311, prevStep = 4, currStep = 4
D/dalvikvm( 7280): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7280): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2418): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2418): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2418): mDVFSHelper.acquire()
I/SELinux ( 7308): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7308):  
D/PointerIcon( 2418): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2418): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2418): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2418): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7280): Shutting down VM
D/dalvikvm( 7280): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 7308): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7308):  
I/SELinux ( 7308):  
I/SELinux ( 7308): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7308): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7308): >>>>> Normal User
E/dalvikvm( 7308): >>>>> com.test.thalitest [ userId:0 | appId:10467 ]
E/SELinux ( 7308): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7308): in addTimaSignatureService
D/TimaKeyStoreProvider( 7308): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7308): Added TimaKesytore provider
,D/dalvikvm( 2418): GC_EXPLICIT freed 26839K, 75% free 25928K/103028K, paused 7ms+21ms, total 229ms
,I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (8/10)
,I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (-2/10)
,I/SQLiteSecureOpenHelper( 4161): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4161): getDatabaseLocked(b,b,pwd)...
,D/dalvikvm( 7308): GC_CONCURRENT freed 3000K, 31% free 9570K/13716K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7308): WAIT_FOR_CONCURRENT_GC blocked 16ms
,V/WebViewChromium( 7308): Binding Chromium to the background looper Looper (main, tid 1) {424a4310}
,I/chromium( 7308): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7308): Initializing chromium process, renderers=0
,W/chromium( 7308): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7308): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7308): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7308): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7308): Mali API Version : 401
,I/Mali    ( 7308): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7308): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7308): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7308): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7308): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7308): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7308): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2577): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/StatusBarManagerService( 2418): tr p:7308,o:f
W/dalvikvm( 7308): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7308): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7308): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7308): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 7308): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7308): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7308): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7308): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7308): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7308): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7308): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7308): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7308): CordovaWebView is running on device made by: samsung
,D/StatusBarManagerService( 2418): semi p:7308,o:f
D/PhoneStatusBar( 2577): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/SurfaceFlinger( 1920): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2418): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2418): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2418): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2418): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2418): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2418): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7308): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7308): Enabling debug mode 0
,W/AwContents( 7308): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2418): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  tag : ACTIVITY_RESUME_BOOSTER@4
,W/AwContents( 7308): nativeOnDraw failed; clearing to background color.
W/ActivityManager( 2418): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2418): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/IInputConnectionWrapper( 7308): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 7308): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7308): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4249cce0
,D/dalvikvm( 7308): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4249cce0
D/jxcore_app_log( 7308): JniHelper::setJavaVM(0x41a29220), pthread_self() = 2030523416
,D/JX-Cordova( 7308): jxcore cordova android initializing
,I/dalvikvm( 7308): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 7308): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7308): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 7308): GC_CONCURRENT freed 1305K, 18% free 11339K/13784K, paused 1ms+2ms, total 24ms
,D/dalvikvm( 7308): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 7308): GC_CONCURRENT freed 2015K, 18% free 14838K/18012K, paused 2ms+2ms, total 40ms
,D/dalvikvm( 7308): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/CustomFrequencyManagerService( 2418): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2418  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7308): GC_FOR_ALLOC freed 5250K, 30% free 16088K/22744K, paused 49ms, total 49ms
,D/dalvikvm( 7308): GC_CONCURRENT freed 6678K, 31% free 17577K/25420K, paused 1ms+10ms, total 60ms
,D/dalvikvm( 7308): WAIT_FOR_CONCURRENT_GC blocked 52ms
,D/dalvikvm( 7308): GC_FOR_ALLOC freed 1428K, 32% free 17375K/25420K, paused 52ms, total 52ms
,I/dalvikvm-heap( 7308): Grow heap (frag case) to 21.672MB for 3767174-byte allocation
,D/dalvikvm( 7308): GC_FOR_ALLOC freed 2497K, 37% free 18556K/29100K, paused 52ms, total 52ms
,W/jxcore-log( 7308): Initializing JXcore engine
,W/jxcore-log( 7308): JXcore engine is ready
,W/jxcore-log( 7308): Starting JXcore engine
,W/jxcore-log( 7308): Platform android
W/jxcore-log( 7308): 
,W/jxcore-log( 7308): Process ARCH arm
W/jxcore-log( 7308): 
,I/jxcore-log( 7308): JXcore Cordova bridge is ready!
I/jxcore-log( 7308): 
,W/jxcore-log( 7308): JXcore engine is started
,I/chromium( 7308): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7308): Turning radios to true
I/jxcore-log( 7308): 
,D/BluetoothAdapter( 7308): enable(): BT is already enabled..!
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : true
,I/WifiService( 2418): setWifiEnabled: true pid=7308, uid=10467
W/ActivityManager( 2418): Permission Denial: getCurrentUser() from pid=7308, uid=10467 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 2418): Failed getting userId using ActivityManagerNative
W/WifiService( 2418): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7308, uid=10467 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2418): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2418): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2418): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2418): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2418): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2418): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService( 2418): disconnect: pid=7308, uid=10467
,I/wpa_supplicant( 3966): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,I/wpa_supplicant( 3966): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3966): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3966): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3966): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3966): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3966): First Scan Start
,W/Settings( 2418): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/wpa_supplicant( 3966): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
D/Tethering( 2418): interfaceStatusChanged wlan0, true
,I/WifiStateMachine( 2418): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2418): InactiveState{ what=143375 }
D/WifiP2pService( 2418): P2pEnabledState{ what=143375 }
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/wpa_supplicant( 3966): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3966): Skip scan - already scanning
,I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
D/ConnectivityService( 2418): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/WifiP2pService( 2418): InactiveState{ what=143375 }
D/WifiP2pService( 2418): P2pEnabledState{ what=143375 }
D/ConnectivityService( 2418): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2418): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2418): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2418): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2418): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2418): Attempting to switch to mobile
,D/ConnectivityService( 2418): Attempting to switch to BLUETOOTH_TETHER
,I/SELinux ( 7354): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7354):  
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
D/STATUSBAR-IconMerger( 2577): checkOverflow(336), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
I/SELinux ( 7354): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7354):  
I/SELinux ( 7354):  
,I/SELinux ( 7354): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7354): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7354): >>>>> Normal User
,E/dalvikvm( 7354): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7354): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,W/NetworkManagementService( 2418): route cmd failed: 
W/NetworkManagementService( 2418): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '35 route del src v6 2' failed with '400 35 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
,V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/WifiStateMachine( 2418): Error! unhandled message{ when=-84ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2418): Error! unhandled message{ when=-90ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,E/WifiStateMachine( 2418): Error! unhandled message{ when=-19ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/TimaKeyStoreProvider( 7354): in addTimaSignatureService
,D/ConnectivityService( 2418): resetConnections(wlan0, 3)
D/NetUtils( 2418): android_net_utils_resetConnections in env=0x78207fc8 clazz=0x61200001 iface=wlan0 mask=0x3
,D/TimaKeyStoreProvider( 7354): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7354): Added TimaKesytore provider
,E/SPPClientService( 5638): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5638): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5638): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,V/NativeCrypto( 2843): Read error: ssl=0x7c27e270: I/O error during system call, Connection timed out
,E/SPPClientService( 5638): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5638): [b] ResponseMap empty
,D/dalvikvm( 7354): GC_CONCURRENT freed 2990K, 31% free 9581K/13716K, paused 3ms+1ms, total 56ms
,D/dalvikvm( 7354): WAIT_FOR_CONCURRENT_GC blocked 31ms
,V/NativeCrypto( 2843): SSL shutdown failed: ssl=0x7c27e270: I/O error during system call, Broken pipe
,D/ConnectivityService( 2418): handleInetConditionChange: no active default network - ignore
,V/NetworkStats( 2418): updateIfacesLocked()
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,V/NetworkStats( 2418): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
V/NetworkStats( 2418): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/System.out( 7354): Inside WakeupProvider
,I/System.out( 7354): Inside onCreate() of WakeupTriggerProvide
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
V/NetworkStats( 2418): performPollLocked() took 34ms
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,I/VlingoApplication( 7354): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7354): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7354): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 2827): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2827): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2827): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2827): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2827): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2827): MountReceiver.onReceive - Set preference state off
,D/DialogFlow( 7354): initQueue()
,V/NearbySettings( 2827): MountReceiver.mPrefHandler - 7002
,I/ActivityManager( 2418): Killing 6275:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/NearbySettings( 2827): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2827): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2827): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 2827): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2827): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2827): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2827): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2418): Tethering got CONNECTIVITY_ACTION,
I/ApplicationPolicy( 2418): updateDataUsageMap
D/Tethering( 2418): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2418): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2418): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2577): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2577): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2577): updateDataNetType()
D/STATUSBAR-NetworkController( 2577): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6701): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6701): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6701): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6701): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6701): noConnectivity : true
,I/DBG_DM  ( 4837): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2418): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7383): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7383):  
,I/SELinux ( 7383): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7383):  
I/SELinux ( 7383):  
,I/SELinux ( 7383): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7383): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7383): >>>>> Normal User
,E/dalvikvm( 7383): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7383): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7383): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7383): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7383): Added TimaKesytore provider
,D/dalvikvm( 7383): GC_CONCURRENT freed 3011K, 31% free 9558K/13716K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 7383): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/wpa_supplicant( 3966): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 3966): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 3966): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2462 MHz)
,I/wpa_supplicant( 3966): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,I/ActivityManager( 2418): Killing 6348:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3966): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3966): Associated with C0.AA.48
,D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3966): freq(2462) increment count 2
I/wpa_supplicant( 3966): meet head of list.
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3966): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3966): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3966): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3966): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3966): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
,D/WifiNative( 2418): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): stay LED for fully charged
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
I/SELinux ( 7399): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7399):  
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/WifiP2pService( 2418): InactiveState{ what=143375 }
,D/WifiP2pService( 2418): P2pEnabledState{ what=143375 }
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 12% free 9503K/10692K, paused 3ms+4ms, total 38ms
V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2577): checkOverflow(336), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/SELinux ( 7399): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7399):  
I/SELinux ( 7399):  
I/SELinux ( 7399): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7399): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7399): >>>>> Normal User
E/dalvikvm( 7399): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
E/SELinux ( 7399): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9503K/10692K, paused 13ms+3ms, total 42ms
,D/TimaKeyStoreProvider( 7399): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7399): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7399): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9503K/10692K, paused 2ms+4ms, total 31ms
,D/dalvikvm( 7399): GC_CONCURRENT freed 2998K, 31% free 9573K/13712K, paused 4ms+2ms, total 23ms
,D/dalvikvm( 7399): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/dhcpcd  ( 7411): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7411): bssid match
,I/ActivityManager( 2418): Killing 6417:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7419): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7419):  
,I/SELinux ( 7419): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7419):  
I/SELinux ( 7419):  
,I/SELinux ( 7419): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7419): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7419): >>>>> Normal User
,E/dalvikvm( 7419): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7419): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7419): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7419): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7419): Added TimaKesytore provider
,D/dalvikvm( 7419): GC_CONCURRENT freed 2990K, 31% free 9577K/13712K, paused 5ms+2ms, total 30ms
,D/dalvikvm( 7419): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/KLMS-2.3.201 : ( 7419): KLMSValidator() : checkQATesting()
,D/libgps  ( 2418): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2418): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2418): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2418): agps_ril_update_network_availability: Waiting for IPC connection...
,I/KLMS-2.3.201 : ( 7419): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1448282992910
,I/KLMS-2.3.201 : ( 7419): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2418): Killing 6433:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7431): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7431):  
,I/SELinux ( 7431): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7431):  
I/SELinux ( 7431):  
,I/SELinux ( 7431): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7431): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7431): >>>>> Normal User
,E/dalvikvm( 7431): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7431): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7431): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7431): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7431): Added TimaKesytore provider
,D/dalvikvm( 7431): GC_CONCURRENT freed 2994K, 31% free 9566K/13708K, paused 3ms+2ms, total 26ms
,D/dalvikvm( 7431): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/SO_AGENT( 7431): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7431): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5902): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5902): [BDLM] already registered in spp
I/SA      ( 5902): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5902): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5902): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5902): [OR] == isSIMCardReady false ==
I/SA      ( 5902): [SCU] == networkStateCheck == false
,I/SA      ( 5902): [OR] onReceive END
I/ActivityManager( 2418): Killing 6367:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2749): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2749): Phone number locator feature is dsiabled
,I/SELinux ( 7443): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7443):  
,E/Watchdog( 2418): !@Sync 8
,I/SELinux ( 7443): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7443):  
I/SELinux ( 7443):  
,I/SELinux ( 7443): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7443): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7443): >>>>> Normal User
,E/dalvikvm( 7443): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7443): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7443): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7443): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7443): Added TimaKesytore provider
,D/dalvikvm( 7443): GC_CONCURRENT freed 2998K, 31% free 9571K/13716K, paused 3ms+2ms, total 24ms
,D/dalvikvm( 7443): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/sCloudBackupApp( 7443): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7443): Other Intent
I/ActivityManager( 2418): Killing 5684:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SELinux ( 7456): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7456):  
,I/SELinux ( 7456): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7456):  
I/SELinux ( 7456):  
,I/SELinux ( 7456): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7456): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7456): >>>>> Normal User
,E/dalvikvm( 7456): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7456): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7456): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7456): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7456): Added TimaKesytore provider
,D/dalvikvm( 7456): GC_CONCURRENT freed 3012K, 31% free 9561K/13716K, paused 2ms+2ms, total 19ms
,D/dalvikvm( 7456): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/com.samsung.app( 7456): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7456): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7456): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7456): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7456): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7456): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5449): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7456): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5449): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7456): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5449): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7456): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7456): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2418): Killing 6399:com.sec.phone/1001 (adj 15): empty #43
,D/Headlines( 5971): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5971): getCountryCode(): countryCode = PL
,D/Headlines( 5971): Breath.onCreate
,D/Headlines( 5971): Breath timer started. interval : 30000
,I/SELinux ( 7468): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7468):  
,V/AlarmManager( 2418): waitForAlarm result :8
D/Headlines( 5971): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5971): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5971): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5971): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5971): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5971): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5971): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7468): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7468):  
I/SELinux ( 7468):  
,I/SELinux ( 7468): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7468): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7468): >>>>> Normal User
,E/dalvikvm( 7468): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7468): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7468): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7468): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7468): Added TimaKesytore provider
,D/libgps  ( 2418): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2418): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2418): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/dalvikvm( 7468): GC_CONCURRENT freed 2999K, 31% free 9573K/13712K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 7468): WAIT_FOR_CONCURRENT_GC blocked 14ms
,V/WebViewChromium( 7468): Binding Chromium to the background looper Looper (main, tid 1) {424a1250}
,I/chromium( 7468): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7468): Initializing chromium process, renderers=0
,W/chromium( 7468): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7468): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 7468): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7468): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7468): Mali API Version : 401
,I/Mali    ( 7468): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,W/GAV2    ( 7468): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7468): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,D/WifiP2pService( 2418): InactiveState{ what=143375 }
,D/WifiP2pService( 2418): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2418): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2418): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2418): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
D/ConnectivityService( 2418): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 2418): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine( 2418): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
D/ConnectivityService( 2418): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2418): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2418): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2418): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.112 lookup 2 prio 150 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
V/NetworkStats( 2418): updateIfacesLocked()
V/NetworkStats( 2418): performPollLocked(flags=0x1)
V/NetworkStats( 2418): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/NSApplication( 7468): Starting up...
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
V/NetworkStats( 2418): performPollLocked() took 20ms
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,I/iu.Environment( 6035): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5231): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5231): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5231): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@424b07a0
,D/dalvikvm( 6035): GC_CONCURRENT freed 518K, 6% free 26754K/28416K, paused 3ms+2ms, total 39ms
,I/SELinux ( 7543): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7543):  
,I/SELinux ( 7543): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7543):  
I/SELinux ( 7543):  
,I/SELinux ( 7543): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7543): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7543): >>>>> Normal User
,E/dalvikvm( 7543): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7543): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7543): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7543): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7543): Added TimaKesytore provider
,D/dalvikvm( 7543): GC_CONCURRENT freed 2995K, 31% free 9572K/13712K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7543): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,I/SELinux ( 7561): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7561):  
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
I/SELinux ( 7561): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7561):  
I/SELinux ( 7561):  
,I/SELinux ( 7561): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7561): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7561): >>>>> Normal User
,E/dalvikvm( 7561): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7561): [DEBUG] seapp_context_lookup: seinfoCategory = release
I/ActivityManager( 2418): Killing 6429:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7561): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7561): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7561): Added TimaKesytore provider
,I/ActivityManager( 2418): Killing 6091:com.android.calendar/u0a144 (adj 15): empty #43
,W/ActivityManager( 2418): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 7575): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7575):  
,D/Tethering( 2418): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2418): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2418): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2577): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2577): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2577): updateDataNetType()
D/STATUSBAR-NetworkController( 2577): NoService, mRoamingIconId = 0
,I/SELinux ( 7575): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7575):  
I/SELinux ( 7575):  
,I/SELinux ( 7575): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7575): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7575): >>>>> Normal User
,E/dalvikvm( 7575): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,I/DBG_DM  ( 4837): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,E/SELinux ( 7575): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7575): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7575): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7575): Added TimaKesytore provider
,D/dalvikvm( 7561): GC_CONCURRENT freed 2989K, 31% free 9577K/13712K, paused 19ms+1ms, total 72ms
,D/dalvikvm( 7561): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/libgps  ( 2418): agps_ril_update_network_state: Waiting for IPC connection...
,D/BadgeProvider( 7561): onCreate
,D/BadgeProvider( 7561): DatabaseHelper
,D/BadgeProvider( 7561): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7561): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7561): sendNotify, [notify] : null
D/BadgeProvider( 7561): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7561): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7561): update, [UpdateCount] : 1
,D/Launcher.Model( 2759): reloadBadges entered.
,D/dalvikvm( 7575): GC_CONCURRENT freed 3000K, 31% free 9570K/13716K, paused 3ms+1ms, total 30ms
,D/dalvikvm( 7575): WAIT_FOR_CONCURRENT_GC blocked 26ms
,E/SPPClientService( 5638): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5638): [SystemStateMoniter] Current Time : 259828
,E/SPPClientService( 5638): [SystemStateMoniter] No Connect : true
,D/hcjo    ( 6066): AutoUpdateManager:IDLE:execute
,E/SPPClientService( 5638): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 2827): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2827): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2827): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2827): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2827): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2827): MountReceiver.onReceive - Keep current state
,D/InitializeManagerStateMachine( 6066): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6066): exit::IDLE
,D/InitializeManagerStateMachine( 6066): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6066): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6066): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6066): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 6066): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 6066): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6066): entry::SUCCESS
,D/hcjo    ( 6066): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6066): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6066): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6066): exit::SUCCESS
,D/InitializeManagerStateMachine( 6066): entry::IDLE
,D/Headlines( 5971): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 350, Delta = 20
D/Headlines( 5971): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
D/Headlines( 5971): Breath 1541 latestRequest time : 1448282993806 current time : 1448282995347
,D/NearbySettings( 2827): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2827): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5638): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5638): [a] [ConnectionManager] Connection is already disconnected.
I/ActivityManager( 2418): Killing 6262:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/NearbySettings( 2827): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2827): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2827): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,E/SPPClientService( 5638): [[PushClientService]] <<--- deInitPushClientService  END  --->>
I/NearbySettings( 2827): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2827): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2827): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5638): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/SurfaceFlinger( 1920): id=20 createSurf (1x1),1 flag=4, Uoast
,E/SPPClientService( 5638): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5638): [a] [ConnectionManager] Connection is already disconnected.
D/PowerManagerService( 2418): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2418
,D/NearbySettings( 2827): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2827): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5638): [g] getNetMCC return empty string
,I/PCWCLIENTTRACE_PushUtil( 6701): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6701): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6701): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6701): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
D/AmoledAdjustTimer( 2418): prevTemp = 311, currTemp = 310, prevStep = 4, currStep = 4
,I/KLMS-2.3.201 : ( 7419): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7419): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1448282995683
,I/KLMS-2.3.201 : ( 7419): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7431): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3431): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
I/SO_AGENT( 7431): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/GalaxyFinderApplication( 3431): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3431): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3431): [Slink platform] The state of Slink geocode service is true
,I/SELinux ( 7599): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7599):  
,I/GallerySearchProvider( 3559): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7599): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7599):  
I/SELinux ( 7599):  
,I/SELinux ( 7599): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7599): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7599): >>>>> Normal User
,E/dalvikvm( 7599): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7599): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 5902): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5902): [BDLM] already registered in spp
,I/SA      ( 5902): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5902): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5902): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5902): [OR] == isSIMCardReady false ==
,D/TimaKeyStoreProvider( 7599): in addTimaSignatureService
,I/SA      ( 5902): [SCU] == networkStateCheck == true
,I/SA      ( 5902): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5902): isChinaCountryCode : false
,I/SA      ( 5902): [OR] == networkStateCheck true ==
D/PackageManager( 2418): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/SA      ( 5902): [OR] GetMyCountryZoneTask
,D/TimaKeyStoreProvider( 7599): Cannot add TimaSignature Service, License check Failed
,I/SA      ( 5902): [OR] onReceive END
,D/ActivityThread( 7599): Added TimaKesytore provider
,I/SA      ( 5902): [SRS] prepareGetMyCountryZone
,I/SELinux ( 7612): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7612):  
I/SA      ( 5902): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 5902): [SSP] query invoked
,I/SELinux ( 7612): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7612):  
I/SELinux ( 7612):  
,I/SELinux ( 7612): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7612): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7612): >>>>> Normal User
,E/dalvikvm( 7612): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7612): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7612): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7612): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7612): Added TimaKesytore provider
,I/System.out( 7399): Thread-639(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7399): Thread-639(ApacheHTTPLog):isShipBuild true
,I/System.out( 7399): Thread-639(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 2418): GC_EXPLICIT freed 2919K, 75% free 25249K/97496K, paused 10ms+19ms, total 249ms
,I/SA      ( 5902): [TPMU] GetMccFromDB : null
,I/SA      ( 5902): [SCU] getMccFromPreferece mcc = 260
,D/PhoneNumberLocatorBootCompletedReceiver( 2749): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2749): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7443): Other Intent
,D/libgps  ( 2418): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2418): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2418): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
D/libgps  ( 2418): agps_ril_update_network_availability: Waiting for IPC connection...
,I/SA      ( 5902): [TPM] isNoProxy(default) : true
,I/SA      ( 5902): [RC New] Execute method=[GET] start
,D/com.samsung.app( 7456): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7456): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5971): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5971): getCountryCode(): countryCode = PL
,I/System.out( 7399): AsyncTask #1 calls detatch()
D/dalvikvm( 7599): GC_CONCURRENT freed 2997K, 31% free 9574K/13712K, paused 2ms+1ms, total 35ms
,D/dalvikvm( 7599): WAIT_FOR_CONCURRENT_GC blocked 19ms
D/Headlines( 5971): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5971): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5971): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5971): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5971): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5971): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5971): requestUpdateNewsWelcomeCard !!! no welcome card
,D/dalvikvm( 7612): GC_CONCURRENT freed 3006K, 31% free 9568K/13716K, paused 2ms+1ms, total 26ms
,D/dalvikvm( 7612): WAIT_FOR_CONCURRENT_GC blocked 21ms
,W/System.err( 7399): com.sec.android.fota.osp.http.RestClientException
,W/System.err( 7399): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
,W/System.err( 7399): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7399): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7399): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7399): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7399): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7399): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 7399): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7399): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7399): Caused by: java.lang.NullPointerException
,I/iu.Environment( 6035): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5231): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5231): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5231): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@424b07a0
,W/System.err( 7399): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7399): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7399): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7399): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7399): 	... 8 more
,V/KVNProvider( 7612): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,V/KVNProvider( 7612): getFindoCursor query string : 
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,V/KVNProvider( 7612): getTagSearchCursor() tagSearchCursor count : 0
,I/ActivityManager( 2418): Killing 6298:com.google.android.music:main/u0a125 (adj 15): empty #43
,D/hcjo    ( 6066): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 6066): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6066): exit::IDLE
,D/InitializeManagerStateMachine( 6066): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 6066): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6066): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6066): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6066): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6066): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6066): entry::SUCCESS
,D/hcjo    ( 6066): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 6066): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6066): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,E/SPPClientService( 5638): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5638): [SystemStateMoniter] Current Time : 260975
D/InitializeManagerStateMachine( 6066): exit::SUCCESS
,D/InitializeManagerStateMachine( 6066): entry::IDLE
,E/SPPClientService( 5638): [SystemStateMoniter] No Connect : false
,D/dalvikvm( 5638): GC_CONCURRENT freed 2009K, 24% free 10456K/13696K, paused 5ms+3ms, total 39ms
,D/dalvikvm( 5638): WAIT_FOR_CONCURRENT_GC blocked 12ms
,I/SA      ( 5902): [RC New] [v2liruge] api execute + 720
,I/SA      ( 5902): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5902): AsyncTask #2 calls detatch()
,I/SA      ( 5902): [TPMU] getNetworkMcc : 
,I/SA      ( 5902): [SCU] saveMccToPreferece Start
,I/SA      ( 5902): [SCU] RegionMCC : 260
,I/SA      ( 5902): [SSP] query invoked
,I/SA      ( 5902): [TPMU] GetMccFromDB : null
I/SA      ( 5902): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5902): [SCU] saveMccToPreferece End
,I/SA      ( 5902): [RC New] executeRequest [v2liruge] end. 749
I/SA      ( 5902): [RC New] Execute end
,I/SA      ( 5902): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5902): [OR] GetMyCountryZoneTask Success
,D/libgps  ( 2418): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2418): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2418): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/jxcore-log( 7308): Attempting to connect to the test coordinator server
I/jxcore-log( 7308): 
,E/SPPClientService( 5638): [b] __InitReply__
,E/WifiStateMachine( 2418): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/ActivityManager( 2418): Killing 6642:com.android.defcontainer/u0a6 (adj 15): empty #43
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (10/11)
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (-2/11)
D/PowerManagerService( 2418): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2418) eventTime = 263515
D/PowerManagerService( 2418): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2418 (0x0)
D/PowerManagerService( 2418): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2418, ws=WorkSource{1000}) (elapsedTime=3469)
,W/WifiP2pStateTracker( 2418): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService( 2418): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2418):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
D/ConnectivityService( 2418): handleConnectivityChange: setting default proxy info 
D/ConnectivityService( 2418): updateSourceRoutes : no source routing conditions
W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/GAV2    ( 7468): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6701): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6701): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6701): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6701): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6701): GetString : secure API is not supported!!
,I/PCWCLIENTTRACE_PushUtil( 6701): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6701): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6701): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6701): [ensureRegistration] - No Samsung account
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 312, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/CaptivePortalTracker( 2418): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 2418): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker( 2418): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 2418): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 2418): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2418): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2418): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2418): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 6066): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6066): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6066): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6066): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6066): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6066): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6066): entry::IDLE
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 360, Delta = 10
,D/AmoledAdjustTimer( 2418): prevTemp = 310, currTemp = 312, prevStep = 4, currStep = 4
,D/PreloadUpdateManagerStateMachine( 6066): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6066): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6066): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 6066): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6066): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6066): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6066): entry::IDLE
,I/ActivityManager( 2418): Waited long enough for: ServiceRecord{4762e9d0 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,I/ActivityManager( 2418): Waited long enough for: ServiceRecord{466da360 u0 com.sec.spp.push/.PushClientService}
,I/jxcore-log( 7308): Attempting to connect to the test coordinator server
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Attempting to connect to the test coordinator server
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Attempting to connect to the test coordinator server
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Attempting to connect to the test coordinator server
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Attempting to connect to the test coordinator server
I/jxcore-log( 7308): 
,D/BatteryService( 2418): level:100, scale:100, status:3, health:9, present:true, voltage: 4365, temperature: 311, technology: Li-ion, AC powered:false, USB powered:false, Wireless powered:false, icon:17303678, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
D/LightsService( 2418): [api] [SvcLED] turnOff:: id = 3 (uid: 0 pid: 0) 
,D/LightsService( 2418): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 2418): turn off LED
,D/lights  ( 2418): led_pattern : 0 +
,D/lights  ( 2418): led_pattern : 0 -
D/LightsService( 2418): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/LightsService( 2418): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/PowerManagerService( 2418): [api] updateIsPoweredLocked : mIsPowered: false mPlugType: 0
I/PowerManagerService( 2418): !@[ps] Screen__On :  powered change
I/PowerManagerService( 2418): Waking up from sleep...
D/PowerManagerService( 2418): Screen Readiness Inspection requested: mNestCount=1
D/PowerManagerService( 2418): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2418): [s] WAKEFULNESS_AWAKE
D/PowerManagerService( 2418): [s] UserActivityState : 0 -> 1
D/PowerManagerService( 2418): [PWL] sb acquire: PowerManagerService.Display
D/DisplayPowerController( 2418): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
I/DisplayPowerController( 2418): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
D/lights  ( 2418): button : 1 +
,D/lights  ( 2418): button : 1 -
,I/SensorManagerA( 2418): getReportingMode :: sensor.mType = 5
D/DisplayPowerController( 2418): [DAB] setLightSensorEnabled : registerListener mLightSensor
I/DisplayPowerController( 2418): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/DisplayPowerController( 2418): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2418): [DAB] no lux value from sensor manager
,D/DisplayPowerController( 2418): animation target = 20 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/Sensors ( 2418): LightSensor setDelay = 200000000
D/Sensors ( 2418): LightSensor setSensorDelay = 200000000
D/Sensors ( 2418): Light sensor flush: not enabled 0
D/Sensors ( 2418): LightSensor enable = 1
D/Sensors ( 2418): LightSensor enableSensor = 1
,D/SensorManager( 2418): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
I/SensorManagerA( 2418): getReportingMode :: sensor.mType = 1
,I/Sensors ( 2418): HAL: batch Dry Run is complete
D/PowerManagerService( 2418): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 6ms
D/PowerUI ( 2577): Overvoltage/Undervoltage (recovered) so turn on the screen.
I/libsuspend( 2418): !@[s] autosuspend_autosleep_disable
,I/libsuspend( 2418): !@[s] autosuspend_autosleep_disable done
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3995): Disconnected process message: 10
,I/Sensors ( 2418): HAL:resetDataRates mEnabled=4
D/PowerManagerService( 2418): unblankAllDisplays() is called.
,D/PowerManagerService( 2418): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
I/SensorManagerA( 2418): getReportingMode :: sensor.mType = 65558
,D/SurfaceFlinger( 1920): Screen acquired, type=0 flinger=0x41057550
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/UsbDeviceManager( 2418): handleMessage -> MSG_POWER_STATE = 0
D/RampAnimator( 2418): Light Animator Finished currentValue=20
,I/jxcore-log( 7308): Attempting to connect to the test coordinator server
I/jxcore-log( 7308): 
W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
D/SensorService( 2418): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2418): AutoRotationSensor::activate (ident=0x7ba32338, enabled=1)
D/SensorService( 2418): AutoRotationSensor::AR_init
,I/Sensors ( 2418): HAL: batch Dry Run is complete
,D/SensorManager( 2418): registerListener :: 2, MPL Accelerometer, 200000, 0,  
D/PowerManagerService( 2418): [api] [s] wakeUp (uid: 10019 pid: 2577) eventTime = 277018
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/PowerManagerService( 2418): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 22ms
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:3 health:9
,I/Sensors ( 2418): HAL:resetDataRates mEnabled=4
D/UsbDeviceManager( 2418): sending intent : ACTION_USB_CABLE_STATE : connected = false
,D/STATUSBAR-StatusBarManagerService( 2418): sendNotification(3) - 5
D/NotificationService( 2418): cancelNotificationLocked
D/NotificationService( 2418):  hasClearableItems
D/NotificationService( 2418):  has clearable items no 
D/NotificationService( 2418): cancelNotificationLocked: cancel alarm
D/NotificationService( 2418): cancelNotificationLocked: cancel alarm
,D/SensorManager( 2418): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
,V/KeyguardServiceDelegate( 2418): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@47268f20)
,I/SELinux ( 7648): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7648):  
D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
D/LightsService( 2418): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2418) 
D/LightsService( 2418): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/UsbDeviceManager( 2418): received ACTION_POWER_DISCONNECTED = -1
D/LightsService( 2418): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2418): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/KeyguardViewMediator( 2577): onScreenTurnedOn, seq = 2
D/InputDispatcher( 2418): setInputDispatchMode: enabled=1, frozen=0
D/KeyguardViewMediator( 2577): notifyScreenOnLocked
D/LockPatternUtils( 2577): isPcwEnable = 10
,D/KeyguardViewMediator( 2577): handleNotifyScreenOn
D/KeyguardViewManager( 2577): onScreenTurnedOn()
,V/KeyguardServiceDelegate( 2418): **** SHOWN CALLED ****
I/KeyguardEffectViewMain( 2577): *** KeyguardEffectView getInstance ***
,D/VisualEffectParticleEffect( 2577): KeyguardEffectViewParticleSpace : screenTurnedOn
,D/VisualEffectParticleEffect( 2577): screenOnAnimationStart
V/KeyguardViewManager( 2577): send wm null token: host was null
,I/WindowManager( 2418): No lock screen! windowToken=null
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 12% free 9503K/10692K, paused 2ms+4ms, total 36ms
,D/BatteryMeterView( 2577): onDraw batteryColor : -1
I/SELinux ( 7648): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7648):  
I/SELinux ( 7648):  
I/SELinux ( 7648): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7648): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7648): >>>>> Normal User
E/dalvikvm( 7648): >>>>> com.sec.android.Kies [ userId:0 | appId:1000 ]
E/SELinux ( 7648): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9503K/10692K, paused 2ms+3ms, total 39ms
,D/TimaKeyStoreProvider( 7648): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7648): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7648): Added TimaKesytore provider
D/SensorService( 2418): AutoRotationSensor::process: Acc  eventTimestamp = 277099639635, previousAccTimestamp = 68877463760, difference = 208222175875 
,D/SensorService( 2418): AutoRotationSensor::reset oldrotation = [100], initState = [1]
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9503K/10692K, paused 4ms+5ms, total 50ms
,D/DisplayPowerController( 2418): [api] [DAB] onSensorChanged : 1st lux : 9.0
,D/DisplayPowerController( 2418): [DAB] updateAutoBrightnessSEC : 17(17.0)    0.0 < 9.0 < 16.0 (0.0)
,D/DisplayPowerController( 2418): animation target = 17 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/RampAnimator( 2418): Light Animator Finished currentValue=17
,D/SensorService( 2418): AutoRotationSensor::process: Acc  eventTimestamp = 277166301809, previousAccTimestamp = 68877463760, difference = 208288838049 
D/SensorService( 2418):  [AR] 0.3 0.0 9.9
,D/SensorService( 2418): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
,D/SurfaceControl( 2418): Excessive delay in unblankDisplay() while turning screen on: 226ms
,D/MISC PowerHAL( 2418): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/PowerManagerService( 2418): Excessive delay in mDisplayManagerService.unblankAllDisplaysFromPowerManager(): 232ms
,D/MISC PowerHAL( 2418): sysfs_write +: /sys/class/input/input1/enabled: 1
D/PowerManagerNotifier( 2418): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,I/SurfaceFlinger( 1920): id=14 Removed FlectronBea (10/10)
,I/SurfaceFlinger( 1920): id=14 Removed FlectronBea (-2/10)
D/PowerManagerService( 2418): Screen Readiness Inspection completed: mNestCount=0
D/DisplayPowerController( 2418): animation target = 17 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 2418): !@ElectronBeam exit
D/lights  ( 2418): lcd : 17 +
,D/LockPatternUtils( 2577): isPcwEnable = 10
,I/jxcore-log( 7308): Attempting to connect to the test coordinator server
I/jxcore-log( 7308): 
D/MISC PowerHAL( 2418): sysfs_write -: /sys/class/input/input1/enabled: 1
D/MISC PowerHAL( 2418): miscpower_set_interactive: /sys/class/input/input0/enabled
,D/MISC PowerHAL( 2418): sysfs_write +: /sys/class/input/input0/enabled: 1
,D/lights  ( 2418): lcd : 17 -
D/DisplayPowerController( 2418): animation target = 17 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2418): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/LightsService( 2418): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2418) 
,D/PalmMotionService( 2418): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/PalmMotionService( 2418): SURFACE_PALM_SWIPE: 1
D/LightsService( 2418): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
E/MotionRecognitionService( 2418):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/LightsService( 2418): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2418): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SamsungIME( 2997): showDlgMsgBox : false true true
,I/FPMS_FingerprintManagerService( 2597): onReceive: android.intent.action.USER_PRESENT
,D/SSRMv2:TSP:AirViewOnOff( 2418): SettingsAirViewInfo:: 000000000
I/NfcService( 2754): applyRouting return - 2 
,I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
,E/NfcService( 2754): callback == null
D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NotificationService( 2418): ACTION_SCREEN_ON
D/LightsService( 2418): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2418) 
D/LightsService( 2418): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2418): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2418): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/AudioHardwareTinyALSA( 1924): setParameters(screen_state=on)
D/MISC PowerHAL( 2418): sysfs_write -: /sys/class/input/input0/enabled: 1
D/MISC PowerHAL( 2418): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 2418): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 2418): Excessive delay in MISC setInteractive(true) while turning screen on: 159ms
D/SEC PowerHAL( 2418): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2418): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2418): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2418): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2418): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2418): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2418): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
,D/SEC PowerHAL( 2418): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
D/PowerManagerService( 2418): Excessive delay in nativeSetInteractive(true): 160ms
D/PowerManagerService( 2418): SecHardwareInterface.setBatteryADC : true
,I/SecExternalDisplayIntents_Java( 2418): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/IpRemoteDisplayController( 2418): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2418): Bridge Server is not available
,D/PersonaManagerService( 2418): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 2418): MSG_ACTION_SCREEN_ON called
,I/NfcService( 2754): NFC: Screen On & Cover Open
,D/dalvikvm( 7648): GC_CONCURRENT freed 3004K, 31% free 9566K/13716K, paused 4ms+4ms, total 56ms
,D/dalvikvm( 7648): WAIT_FOR_CONCURRENT_GC blocked 48ms
D/STATUSBAR-NetworkController( 2577): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,I/NfcService( 2754): applyRouting return - 2 
,E/NfcService( 2754): callback == null
,I/KIES_RECEIVE( 7648): [APK BnR] Receive KIES_USB_DISCONNECT
D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
W/ContextImpl( 7648): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 android.content.ContextWrapper.stopService:511 com.sec.android.Kies.kies_receiver.onReceive:170 android.app.ActivityThread.handleReceiver:2698 
,E/TranscodeReceiver( 7599): onReceive : android.intent.action.ACTION_POWER_DISCONNECTED
,D/videowall-Global( 7599): core_num = 4
,D/dalvikvm( 7599): No JNI_OnLoad found in /system/lib/libsavsff.so 0x424a1870, skipping init
,W/linker  ( 7599): libvwengine.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/videowall-Global( 7599): density : 2.0 width : 720 height : 1280 Raw width : 720 Raw height : 1280
,D/videowall-Global( 7599): dsp : 720, swkey : false, Cores : 4, Clock : 0
,I/SELinux ( 7663): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7663):  
,I/jxcore-log( 7308): Attempting to connect to the test coordinator server
I/jxcore-log( 7308): 
,I/SELinux ( 7663): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7663):  
I/SELinux ( 7663):  
,I/SELinux ( 7663): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7663): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 7663): >>>>> Normal User
,E/dalvikvm( 7663): >>>>> com.android.chrome [ userId:0 | appId:10085 ]
,E/SELinux ( 7663): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,I/jxcore-log( 7308): Test app app.js loaded
I/jxcore-log( 7308): 
,D/TimaKeyStoreProvider( 7663): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7663): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7663): Added TimaKesytore provider
,I/jxcore-log( 7308): {"type":"test","name":"setup","id":0}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): LogCallback not set !!!!
I/jxcore-log( 7308): 
,D/StatusBarManagerService( 2418): semi p:7308,o:f
D/PhoneStatusBar( 2577): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/chromium( 7308): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 7308): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 360, Delta = 0
D/dalvikvm( 7663): GC_CONCURRENT freed 2997K, 31% free 9577K/13716K, paused 8ms+3ms, total 49ms
D/dalvikvm( 7663): WAIT_FOR_CONCURRENT_GC blocked 31ms
I/chromium( 7308): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/QuickConnect[1.1][2] ( 5231): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
,E/libGLESv2( 7308): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 7308): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,V/QuickConnect[1.1][2] ( 5231): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5231): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5231): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@424b07a0
,V/QuickConnect[1.1][2] ( 5231): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@424b07a0
V/QuickConnect[1.1][2] ( 5231): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 5231): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@424b07a0
,V/QuickConnect[1.1][2] ( 5231): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@424b07a0
,V/QuickConnect[1.1][2] ( 5231): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@424b07a0
D/QuickConnect[1.1][2] ( 5231): BleHelper.startScan - propDisableScan = 0
,D/QuickConnect[1.1][2] ( 5231): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 5231): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 5231): BleHelper.startScan - shouldScanBleFg = false
,D/daemonapp( 5449): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5449): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5449): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionSCREEN_ON
,D/PowerManagerService( 2418): [PWL] sb release: PowerManagerService.Broadcasts
,E/libGLESv2( 7308): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 7308): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
E/libGLESv2( 7308): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 7308): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,I/SELinux ( 7688): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7688):  
I/ActivityManager( 2418): Killing 6545:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,I/jxcore-log( 7308): DBG, CoordinatorConnector connect called
I/jxcore-log( 7308): 
,I/SELinux ( 7688): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7688):  
I/SELinux ( 7688):  
,I/SELinux ( 7688): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7688): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7688): >>>>> Normal User
,E/dalvikvm( 7688): >>>>> com.google.android.apps.uploader [ userId:0 | appId:10117 ]
,E/SELinux ( 7688): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7688): in addTimaSignatureService
,I/jxcore-log( 7308): DBG, CoordinatorConnector connect called
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): DBG, CoordinatorConnector connect called
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector connect called
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): DBG, CoordinatorConnector connect called
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector connect called
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): DBG, CoordinatorConnector connect called
I/jxcore-log( 7308): 
D/TimaKeyStoreProvider( 7688): Cannot add TimaSignature Service, License check Failed
I/jxcore-log( 7308): DBG, CoordinatorConnector connect called
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): DBG, CoordinatorConnector connect called
I/jxcore-log( 7308): 
,D/ActivityThread( 7688): Added TimaKesytore provider
,D/dalvikvm( 7688): GC_CONCURRENT freed 3004K, 31% free 9558K/13708K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 7688): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/iu.Environment( 6035): update battery state; isPlugged? false*
,I/iu.SyncManager( 6035): SYNC; picasa accounts
,I/ActivityManager( 2418): Killing 6673:com.samsung.groupcast/u0a15 (adj 15): empty #43
D/PicasaUploader( 7688):    wifiOnlyPhoto changed to true
D/PicasaUploader( 7688):    wifiOnlyVideo changed to true
D/PicasaUploader( 7688):    syncOnBattery changed to true
,D/PicasaUploaderSync( 7688): sync account database
,I/iu.UploadsManager( 6035): num queued entries: 0
,I/iu.UploadsManager( 6035): num updated entries: 0
,I/iu.Environment( 3272): update battery state; isPlugged? false*
,D/PicasaUploaderSync( 7688): accounts in DB=1
,I/iu.SyncManager( 6035): NEXT; no task
D/PicasaUploaderSyncManager( 7688): active network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PicasaUploaderSyncManager( 7688): background data: true
,I/iu.UploadsManager( 3272): num queued entries: 0
,I/iu.UploadsManager( 3272): num updated entries: 0
,I/iu.SyncManager( 3272): NEXT; no task
,I/GCoreUlr( 2730): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_DISCONNECTED}]
,I/GCoreUlr( 2730): DispatchingService.onCreate()
,D/PicasaUploaderSyncManager( 7688): battery info: false
,D/LockPatternUtils( 2577): isPcwEnable = 10
,I/GCoreUlr( 2730): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_DISCONNECTED
,D/daemonapp( 5449): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5449): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5449): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5449): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5449): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 5449): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5449): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5449): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5449): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5449): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5449): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 5449): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5449): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 5449): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1448283540000
,D/daemonapp( 5449): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1448283013915
,D/lights  ( 2418): button : 0 +
,D/lights  ( 2418): button : 0 -
,D/daemonapp( 5449): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5449): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5449): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5449): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5449): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5449): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/dalvikvm( 5449): GC_CONCURRENT freed 2659K, 28% free 9984K/13784K, paused 22ms+4ms, total 111ms
,D/dalvikvm( 5449): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/GCoreUlr( 2730): WorldUpdater:android.intent.action.ACTION_POWER_DISCONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/SSRMv2:TSP:AirViewOnOff( 2418): SettingsAirViewInfo:: 000000000
,D/daemonapp( 5449): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5449): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5449): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/GCoreUlr( 2730): Unbound from all location providers
,D/daemonapp( 5449): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5449): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 5449): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5449): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5449): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5449): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5449): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 5449): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 5449): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 5449): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5449): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 5449): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5449): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,I/GCoreUlr( 2730): DispatchingService.onDestroy()
,I/GCoreUlr( 2730): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2730): Unbound from all location providers
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2418):   0.3 0.0 9.9
,D/AmoledAdjustTimer( 2418): prevTemp = 312, currTemp = 311, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2418):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2418):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2418): level:100, scale:100, status:2, health:2, present:true, voltage: 4365, temperature: 312, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/PowerManagerService( 2418): [api] updateIsPoweredLocked : mIsPowered: true mPlugType: 2
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UsbDeviceManager( 2418): handleMessage -> MSG_POWER_STATE = 1
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/PowerUI ( 2577): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2418): [api] [s] wakeUp (uid: 10019 pid: 2577) eventTime = 287012
,D/PowerUI ( 2577): playSound : 1
V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3995): Disconnected process message: 10
,I/EntropyMixer( 2418): Writing entropy...
I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
V/Vibrator( 2577): Called vibrateImmVibe(int) API - PUID: 10019, PackageName: com.android.keyguard
V/Vibrator( 2577): vibrateImmVibe - PUID: 10019, PackageName: com.android.keyguard, type: 10, magType: TouchMagnitude
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
V/VibratorService( 2418): vibrateImmVibeMagnitudeType - magnitudeType: TouchMagnitude
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
V/VibratorService( 2418): vibrate - package: com.android.keyguard, ms: 100, token: null
D/VibratorService( 2418): JNI vibratorOff()
D/VibratorService( 2418): JNI vibratorOn() : 100
D/PowerUI ( 2577): RINGER_MODE_VIBRATE
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/UsbDeviceManager( 2418): sending intent : ACTION_USB_CABLE_STATE : connected = true
D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
E/TranscodeReceiver( 7599): onReceive : android.intent.action.ACTION_POWER_CONNECTED
I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,D/BatteryMeterView( 2577): onDraw batteryColor : -1
I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
I/AudioFlinger( 1924): sleepTime is reduced to minimum forcely
,D/TranscodeService( 7599): onCreate()
,I/SCloudBackupReceiver( 7443): Other Intent
,D/dalvikvm( 7599): No JNI_OnLoad found in /system/lib/libsavsvc.so 0x424a1870, skipping init
D/dalvikvm( 7599): No JNI_OnLoad found in /system/lib/libsavscmn.so 0x424a1870, skipping init
,D/PicasaUploaderSyncManager( 7688): battery info: true
,D/dalvikvm( 7599): No JNI_OnLoad found in /system/lib/libsthmb.so 0x424a1870, skipping init
,D/TranscodeService( 7599): power? : true / screen off : false
,D/TranscodeService( 7599): releaseTranscodeThread.
,I/iu.Environment( 6035): update battery state; isPlugged? true*
,I/iu.UploadsManager( 6035): num queued entries: 0
,I/iu.UploadsManager( 6035): num updated entries: 0
,I/iu.SyncManager( 6035): NEXT; no task
,I/iu.FingerprintManager( 6035): Start processing all media
,I/iu.FingerprintManager( 6035): Start processing media store URI: content://media/external/images/media
,D/VibratorService( 2418): JNI vibratorOff()
,I/iu.Environment( 3272): update battery state; isPlugged? true*
,I/iu.FingerprintManager( 6035): Start processing media store URI: content://media/external/video/media
,I/iu.UploadsManager( 3272): num queued entries: 0
,I/iu.UploadsManager( 3272): num updated entries: 0
,I/iu.SyncManager( 3272): NEXT; no task
,I/iu.FingerprintManager( 6035): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 6035): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 3272): Start processing all media
,I/iu.FingerprintManager( 6035): Finished generating fingerprints; 0.069 seconds
,I/iu.FingerprintManager( 6035):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/iu.FingerprintManager( 3272): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 3272): Start processing media store URI: content://media/external/video/media
,E/NetworkScheduler.SchedulerReceiver( 2843): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 2843): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/iu.FingerprintManager( 3272): Start processing media store URI: content://media/phoneStorage/images/media
,I/GCoreUlr( 2730): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_CONNECTED}]
,I/GCoreUlr( 2730): DispatchingService.onCreate()
,D/dalvikvm( 2716): GC_EXPLICIT freed 362K, 32% free 9969K/14632K, paused 4ms+5ms, total 52ms
,I/SELinux ( 7712): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7712):  
,I/iu.FingerprintManager( 3272): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 3272): Finished generating fingerprints; 0.154 seconds
,I/iu.FingerprintManager( 3272):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/SELinux ( 7712): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7712):  
I/SELinux ( 7712):  
,I/SELinux ( 7712): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7712): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7712): >>>>> Normal User
,E/dalvikvm( 7712): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
,E/SELinux ( 7712): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7712): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7712): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7712): Added TimaKesytore provider
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 2418): GC_EXPLICIT freed 2221K, 75% free 25180K/97496K, paused 11ms+17ms, total 199ms
,I/GCoreUlr( 2730): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_CONNECTED
,W/InstanceID/Rpc( 2730): Found 10012
,D/dalvikvm( 7712): GC_CONCURRENT freed 2997K, 31% free 9571K/13716K, paused 5ms+3ms, total 39ms
,D/dalvikvm( 7712): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 7712): WAIT_FOR_CONCURRENT_GC blocked 1ms
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 350, Delta = -10
,E/Watchdog( 2418): !@Sync 9
,I/GCoreUlr( 2730): WorldUpdater:android.intent.action.ACTION_POWER_CONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2730): Unbound from all location providers
,I/GCoreUlr( 2730): DispatchingService.onDestroy()
,I/GCoreUlr( 2730): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2730): Unbound from all location providers
,E/dalvikvm( 7712): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a
,W/dalvikvm( 7712): VFY: unable to resolve new-instance 406 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm( 7712): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 7712): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 7712): Link of class 'Lal;' failed
E/dalvikvm( 7712): Could not find class 'al', referenced from method b.a
W/dalvikvm( 7712): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
,D/dalvikvm( 7712): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 7712): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 7712): Link of class 'Lan;' failed
E/dalvikvm( 7712): Could not find class 'an', referenced from method b.a
W/dalvikvm( 7712): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
,D/dalvikvm( 7712): VFY: replacing opcode 0x22 at 0x002a
I/dalvikvm( 7712): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm( 7712): VFY: unable to resolve virtual method 5407: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 7712): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 7712): Could not find method android.view.View.getTransitionName, referenced from method b.a
W/dalvikvm( 7712): VFY: unable to resolve virtual method 5231: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7712): VFY: replacing opcode 0x6e at 0x0006
,W/dalvikvm( 7712): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 7712): Could not find class 'android.app.RemoteInput[]', referenced from method b.a
W/dalvikvm( 7712): VFY: unable to resolve new-array 12200 ([Landroid/app/RemoteInput;) in Lb;
,D/dalvikvm( 7712): VFY: replacing opcode 0x23 at 0x0005
,D/dalvikvm( 7712): DexOpt: unable to opt direct call 0x090f at 0x0e in Lb;.a
W/dalvikvm( 7712): Unable to resolve superclass of Lal; (749)
,W/dalvikvm( 7712): Link of class 'Lal;' failed
,D/dalvikvm( 7712): DexOpt: unable to opt direct call 0x068d at 0x08 in Lb;.a
W/dalvikvm( 7712): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 7712): Link of class 'Lan;' failed
,D/dalvikvm( 7712): DexOpt: unable to opt direct call 0x0802 at 0x2c in Lb;.a
,D/dalvikvm( 7712): DexOpt: unable to opt direct call 0x0957 at 0x13 in Lb;.a
,I/dalvikvm( 7712): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method dyp.a
W/dalvikvm( 7712): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7712): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 7712): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7712): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7712): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7712): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7712): VFY: unable to resolve instance field 46
,D/dalvikvm( 7712): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 7712): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7712): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7712): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 7712): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 7712): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 7712): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42548be8
D/dalvikvm( 7712): Added shared lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42548be8
,D/dalvikvm( 7712): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42548be8, skipping init
,D/dalvikvm( 7712): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x42548be8
,D/dalvikvm( 7712): Added shared lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x42548be8
,V/JNIHelp ( 7712): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/dalvikvm( 7712): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42548be8
,D/dalvikvm( 7712): Shared lib '/data/app-lib/com.google.android.gms-4/libgmscore.so' already loaded in same CL 0x42548be8
D/dalvikvm( 7712): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x42548be8
,D/dalvikvm( 7712): Shared lib '/data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42548be8
,I/dalvikvm( 7712): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
,W/dalvikvm( 7712): VFY: unable to resolve static method 1165: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 7712): VFY: replacing opcode 0x71 at 0x0046
,I/dalvikvm( 7712): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
,W/dalvikvm( 7712): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7712): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 7712): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 7712): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 7712): VFY: replacing opcode 0x6e at 0x0220
,D/dalvikvm( 7712): DexOpt: --- BEGIN 'ads1688691191.jar' (bootstrap=0) ---
V/AlarmManager( 2418): waitForAlarm result :8
,D/Headlines( 5971): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5971): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5971): Breath 27600 latestRequest time : 1448282996214 current time : 1448283023814
,I/ProviderInstaller( 7712): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX( 7712): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 7739): DexOpt: load 6ms, verify+opt 18ms, 194052 bytes
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7712): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,D/dalvikvm( 7712): DexOpt: --- END 'ads1688691191.jar' (success) ---
,D/dalvikvm( 7712): DEX prep '/data/data/com.google.android.youtube/cache/ads1688691191.jar': unzip in 0ms, rewrite 132ms
,D/dalvikvm( 7712): GC_CONCURRENT freed 1948K, 23% free 10665K/13740K, paused 5ms+5ms, total 39ms
,I/dalvikvm( 7712): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
,W/dalvikvm( 7712): VFY: unable to resolve virtual method 2614: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 7712): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 7712): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 7712): VFY: unable to resolve virtual method 2615: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 7712): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7712): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 7712): VFY: unable to resolve virtual method 2622: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 7712): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7712): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 7712): VFY: unable to resolve virtual method 2623: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 7712): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7712): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method agv.getLeanbackLaunchIntentForPackage
W/dalvikvm( 7712): VFY: unable to resolve virtual method 2639: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 7712): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7712): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method agv.getPackageInstaller
W/dalvikvm( 7712): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7712): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7712): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method agv.getUserBadgedDrawableForDensity
W/dalvikvm( 7712): VFY: unable to resolve virtual method 2659: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 7712): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7712): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method agv.getUserBadgedIcon
W/dalvikvm( 7712): VFY: unable to resolve virtual method 2660: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 7712): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 7712): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method agv.getUserBadgedLabel
W/dalvikvm( 7712): VFY: unable to resolve virtual method 2661: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm( 7712): VFY: replacing opcode 0x6e at 0x0002
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7712): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7712): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7712): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 7712): Found 10012
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7712): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,I/System.out( 7712): Thread-743(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7712): Thread-743(ApacheHTTPLog):isShipBuild true
,I/System.out( 7712): Thread-743(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 7712): Thread-743 calls detatch()
,D/SensorService( 2418):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2418): prevTemp = 311, currTemp = 312, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager( 2418): Waited long enough for: ServiceRecord{471423c0 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,D/SensorService( 2418):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2418):   0.3 0.0 9.9
,D/BatteryService( 2418): level:100, scale:100, status:2, health:2, present:true, voltage: 4388, temperature: 313, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 350, Delta = 0
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2418):   0.3 0.0 9.9
,D/AmoledAdjustTimer( 2418): prevTemp = 312, currTemp = 313, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager( 2418): Waited long enough for: ServiceRecord{465a1738 u0 com.sec.android.app.videoplayer/.videowall.TranscodeService}
,D/SensorService( 2418):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2418):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 314, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/PowerManagerService( 2418): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2577
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2418): sendNotification(1) - 5
D/NotificationService( 2418): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200a5 contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
D/RCPManagerService( 2418): NotificationReceiver onReceive()
D/RCPManagerService( 2418):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
,D/RCPManagerService( 2418): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967298418
D/RCPManagerService( 2418): getPolicy: policy value returned = false
D/RCPManagerService( 2418): going to get the app label for pkg == com.android.systemui
,D/RCPManagerService( 2418): app label == com.android.systemui
D/RCPManagerService( 2418): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967298418
D/RCPManagerService( 2418): getPolicy: policy value returned = true
,D/RCPManagerService( 2418): Calling User is -1
,D/RCPManagerService( 2418): userid of SBN ==-1
D/UserManagerService( 2418): User -1does not exists!!
E/PersonaManagerService( 2418): returning null in  getPersonasForUser
,D/ProgressBar( 2577): setProgressDrawable drawableHeight = 12
,D/PhoneStatusBar( 2577): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@424c4de0
,D/BatteryMeterView( 2577): onDraw batteryColor : -1
,D/dalvikvm( 2577): GC_CONCURRENT freed 15699K, 34% free 33935K/50772K, paused 18ms+10ms, total 121ms
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 350, Delta = 0
,D/SensorService( 2418):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/AmoledAdjustTimer( 2418): prevTemp = 313, currTemp = 314, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/PowerManagerService( 2418): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 2418): animation target = 7 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2418): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/lights  ( 2418): lcd : 7 +
D/RampAnimator( 2418): Light Animator Finished currentValue=7
,D/lights  ( 2418): lcd : 7 -
,D/TimaService( 2418): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2418): TimaServiceHandler.handleMessage what =1
,D/TimaService( 2418): TIMA: checkEvent, operation: 50000 subject: 10000
I/TLC_TIMA_PKM_initialize( 2418): initializing...
I/TLC_TIMA_PKM_initialize( 2418): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 2418): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2418): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2418): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2418): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2418): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2418): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2418): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2418): device_id = 0x0
I/TZ: mc_tlc_communication( 2418): tlc_open() was called
I/TZ: mc_tlc_communication( 2418): Opening MobiCore device
I/TZ: mc_tlc_communication( 2418): Allocating WSM for TCI
I/TZ: mc_tlc_communication( 2418): Opening the session
,I/TZ: mc_tlc_communication( 2418): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2418): Trustlet response is completed
,D/SensorService( 2418):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2418):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/PowerManagerService( 2418): [s] UserActivityState : 2 -> 0
I/PowerManagerService( 2418): [PWL] On : 276992 (40018 ms ago)
I/PowerManagerService( 2418): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
,I/PowerManagerService( 2418): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=2577, ws=null) (elapsedTime=9891)
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 315, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2418): !@Sync 10
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 350, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,V/AlarmManager( 2418): waitForAlarm result :8
,D/Headlines( 5971): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5971): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5971): Breath 57611 latestRequest time : 1448282996214 current time : 1448283053825
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2418):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2418): prevTemp = 314, currTemp = 315, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2418):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/daemonapp( 5449): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5449): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5449): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionTIME_TICK
D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/daemonapp( 5449): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5449): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5449): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5449): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5449): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 5449): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 5449): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
,D/comsamsunglog( 5449): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5449): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5449): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5449): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 5449): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5449): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5449): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 5449): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5449): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2418):   0.3 0.0 9.9
,D/PowerManagerService( 2418): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2577 (0x0)
,I/PowerManagerService( 2418): Nap time...
D/PowerManagerService( 2418): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2418): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2418): Going to sleep due to screen timeout...
,D/PowerManagerService( 2418): [s] WAKEFULNESS_ASLEEP
,D/DisplayPowerController( 2418): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/DisplayPowerController( 2418): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/Sensors ( 2418): LightSensor enable = 0
,D/Sensors ( 2418): LightSensor enableSensor = 0
D/DisplayPowerController( 2418): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,D/SensorManager( 2418): unregisterListener ::   
,I/SurfaceFlinger( 1920): id=21 createSurf (720x1280),-1 flag=20004, FlectronBea
I/DisplayPowerController( 2418): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
,I/Sensors ( 2418): HAL:resetDataRates mEnabled=4
,D/SensorManager( 2418): unregisterListener ::   
D/DisplayPowerController( 2418): !@ElectronBeam entry
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/lights  ( 2418): lcd : 0 +
,D/lights  ( 2418): lcd : 0 -
D/MISC PowerHAL( 2418): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2418): sysfs_write +: /sys/class/input/input1/enabled: 0
,V/WindowOrientationListener( 2418): WindowOrientationListener disabled
D/SensorService( 2418): AutoRotationSensor::activate (ident=0x7ba32338, enabled=0)
D/PowerManagerService( 2418): blankAllDisplays() is called.
D/PowerManagerService( 2418): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2418): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 2418): [PWL] sb release: PowerManagerService.Display
I/Sensors ( 2418): HAL: batch Dry Run is complete
D/KeyguardViewMediator( 2577): onScreenTurnedOff(3)
D/MISC PowerHAL( 2418): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2418): miscpower_set_interactive: /sys/class/input/input0/enabled
D/MISC PowerHAL( 2418): sysfs_write +: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2418): sysfs_write -: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2418): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2418): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/SensorManager( 2418): unregisterListener ::   
D/InputDispatcher( 2418): setInputDispatchMode: enabled=0, frozen=0
D/SEC PowerHAL( 2418): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2418): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2418): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2418): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2418): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2418): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2418): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SEC PowerHAL( 2418): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SurfaceFlinger( 1920): Screen released, type=0 flinger=0x41057550,
,D/PowerManagerService( 2418): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/LockPatternUtils( 2577): isPcwEnable = 10
,D/LockPatternUtils( 2577): isPcwEnable = 10
,D/SurfaceControl( 2418): Excessive delay in blankDisplay() while turning screen off: 201ms
,I/libsuspend( 2418): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2418): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2418): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 203ms
D/PowerManagerService( 2418): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2418): [PWL] Off : 0s ago
I/PowerManagerService( 2418): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2418): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2418): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=2418, ws=null) (elapsedTime=205)
I/PowerManagerService( 2418): [PWL]   PowerManagerService.Broadcasts: ref count=1
,D/KeyguardViewMediator( 2577): setting alarm to turn off keyguard, seq = 2
D/LightsService( 2418): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2418) 
,I/SensorManagerA( 2418): getReportingMode :: sensor.mType = 5
D/Sensors ( 2418): LightSensor setDelay = 200000000
D/Sensors ( 2418): LightSensor setSensorDelay = 200000000
D/Sensors ( 2418): Light sensor flush: not enabled 0
D/Sensors ( 2418): LightSensor enable = 1
,D/Sensors ( 2418): LightSensor enableSensor = 1
D/LightsService( 2418): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/SensorManager( 2418): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2418): turn on LED for fully charged
D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
I/SQLiteSecureOpenHelper( 4161): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4161): getDatabaseLocked(b,b,pwd)...
D/VibratorService( 2418): JNI vibratorOff()
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2418): ACTION_SCREEN_OFF
D/LightsService( 2418): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2418) 
,D/LightsService( 2418): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/AudioHardwareTinyALSA( 1924): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2418): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2418): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2418): Bridge Server is not available
,D/PersonaManagerService( 2418): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2418): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2577):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2577): makeExpandedInvisible
D/PhoneStatusBarView( 2577): marqueeStatusBar:122, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2577):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2754): applyRouting return - 2 
,E/NfcService( 2754): callback == null
D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 350, Delta = 0
D/LockPatternUtils( 2577): isPcwEnable = 10
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 350, Delta = 0
D/QuickConnect[1.1][2] ( 5231): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
V/QuickConnect[1.1][2] ( 5231): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5231): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5231): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@424b07a0
V/QuickConnect[1.1][2] ( 5231): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@424b07a0
D/QuickConnect[1.1][2] ( 5231): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 5231): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 5231): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 5231): stopLeScan()
D/QuickConnect[1.1][2] ( 5231): BleHelper.stopScan - call stopLeScan() complete
,E/TranscodeReceiver( 7599): onReceive : android.intent.action.SCREEN_OFF
,D/TranscodeService( 7599): power? : true / screen off : true
D/PowerManagerService( 2418): [PWL] sb release: PowerManagerService.Broadcasts
,D/TranscodeService( 7599): Music is = false
,D/TranscodeService( 7599): runvideoplayer is false
,D/Sensors ( 2418): LightSensor enable = 0
,D/Sensors ( 2418): LightSensor enableSensor = 0
,D/TranscodeService( 7599): Thread start
D/SensorManager( 2418): unregisterListener ::   
,D/LightsService( 2418): [SvcLED]  onSensorChanged::light value = 8
D/lights  ( 2418): led_pattern : 5 +
D/TranscodeService( 7599): WakeLock.acquire()
D/videowall-FileMgr( 7599): thumbnailDBSync -1
,D/lights  ( 2418): led_pattern : 5 -
D/LightsService( 2418): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/WVMDrmPlugIn( 1923): WVMDrmPlugin::onInitialize : 3414
,D/WVMDrmPlugIn( 1923): WVMDrmPlugin::onSetOnInfoListener : add 3414
I/PrGenericPlugin( 1923): [A] ENTER onInitialize : 0xd56
,I/PrGenericPlugin( 1923): [A] LEAVE onInitialize : 0xd56
,D/TranscodeService( 7599): Thread end
,D/TranscodeService( 7599): WakeLock.release()
D/TranscodeService( 7599): onDestroy()
,D/TranscodeService( 7599): releaseTranscodeThread.
,V/ApplicationPolicy( 2418): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
,I/ActivityManager( 2418): Killing 6687:com.android.musicfx/u0a24 (adj 15): empty #43
,D/AmoledAdjustTimer( 2418): prevTemp = 315, currTemp = 316, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :4
,D/KeyguardViewMediator( 2577): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/LockPatternUtils( 2577): isPcwEnable = 10
,D/KeyguardViewMediator( 2577): in doKeyguardLocked mIsRollUp false null
,D/PersonaManager( 2577): isKioskContainerExistOnDevice
,D/LockPatternUtils( 2577): isPcwEnable = 10
,D/LockPatternUtils( 2577): isPcwEnable = 10
,D/KeyguardViewMediator( 2577): doKeyguard: not showing because lockscreen is off
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/PowerManagerService( 2418): [PWL] Off : 5s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 340, Delta = -10
,D/AmoledAdjustTimer( 2418): prevTemp = 316, currTemp = 316, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 15s ago
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 315, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 11
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 340, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 316, currTemp = 315, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :4
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 7917): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7917):  
,I/SELinux ( 7917): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7917):  
I/SELinux ( 7917):  
,I/SELinux ( 7917): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7917): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7917): >>>>> Normal User
,E/dalvikvm( 7917): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 7917): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 7917): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7917): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7917): Added TimaKesytore provider
,D/dalvikvm( 7917): GC_CONCURRENT freed 3001K, 31% free 9566K/13712K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 7917): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/Headlines( 5971): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5971): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5971): Breath 93943 latestRequest time : 1448282996214 current time : 1448283090158
,I/ActivityManager( 2418): Killing 6713:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 314, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2418): [PWL] Off : 30s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 340, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 315, currTemp = 314, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 313, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 340, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 314, currTemp = 313, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 312, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2418): [PWL] Off : 50s ago
,E/Watchdog( 2418): !@Sync 12
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = -10
,V/AlarmManager( 2418): waitForAlarm result :4
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5971): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5971): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5971): Breath 117623 latestRequest time : 1448282996214 current time : 1448283113837
,D/AmoledAdjustTimer( 2418): prevTemp = 313, currTemp = 312, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 312, currTemp = 311, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 311, currTemp = 311, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 75s ago
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2418): !@Sync 13
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,V/AlarmManager( 2418): waitForAlarm result :8
,D/Headlines( 5971): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5971): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5971): Breath 147607 latestRequest time : 1448282996214 current time : 1448283143822
,D/Headlines( 5971): stop 
,D/Headlines( 5971): Breath.onDestroy : 
I/ActivityManager( 2418): Killing 6105:com.sec.android.app.shealth/u0a36 (adj 15): empty #43
,D/AmoledAdjustTimer( 2418): prevTemp = 311, currTemp = 311, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 311, currTemp = 310, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 310, currTemp = 309, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 105s ago
,E/Watchdog( 2418): !@Sync 14
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 309, currTemp = 309, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 309, currTemp = 308, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 308, currTemp = 308, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2418): [PWL] Off : 140s ago
,E/Watchdog( 2418): !@Sync 15
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 308, currTemp = 307, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/dalvikvm( 2418): GC_CONCURRENT freed 3059K, 74% free 25945K/97496K, paused 17ms+18ms, total 258ms
,D/AmoledAdjustTimer( 2418): prevTemp = 307, currTemp = 307, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): stay LED for fully charged
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 307, currTemp = 307, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 16
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 307, currTemp = 307, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2418): [PWL] Off : 180s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 307, currTemp = 306, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2418): !@Sync 17
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 306, currTemp = 305, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4
,I/jxcore-log( 7308): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}},
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7308): 
,I/PowerManagerService( 2418): [PWL] Off : 225s ago
,I/jxcore-log( 7308): {"type":"end","test":0}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"test connectionTable table building and cleanup","id":1}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): DB value for ThaliReplicationManager is: "bogus"
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":50,"expected":50,"test":1,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":40,"expected":40,"test":1,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":60,"expected":60,"test":1,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":1,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":1,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":{"muxPort":60,"time":1448283290094},"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":9,"ok":true,"name":"Cleanup was called, this table is no longer live.","operator":"throws","actual":{"message":"Cleanup was called, this table is no longer live."},"test":1,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"end","test":1}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"teardown","id":2}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 1 isOK: undefined : test connectionTable table building and cleanup", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : Cleanup was called, this table is no longer live.", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 2 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"end","test":2}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"setup","id":3}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 3 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,E/Watchdog( 2418): !@Sync 18
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 7308): {"type":"end","test":3}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"test connectionTable emitting events for peerIds","id":4}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): DB value for ThaliReplicationManager is: "bogus"
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":30,"expected":30,"test":4,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":40,"expected":40,"test":4,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":50,"expected":50,"test":4,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":60,"expected":60,"test":4,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":7,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"end","test":4}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"teardown","id":5}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 4 isOK: undefined : test connectionTable emitting events for peerIds", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 5 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"end","test":5}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"setup","id":6}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 6 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/AmoledAdjustTimer( 2418): prevTemp = 305, currTemp = 304, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,I/jxcore-log( 7308): {"type":"end","test":6}
I/jxcore-log( 7308): 
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"test","name":"start with bad friendly names","id":7}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":0,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":1,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":2,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":3,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"end","test":7}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"teardown","id":8}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 7 isOK: undefined : start with bad friendly names", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 8 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"end","test":8}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"setup","id":9}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 9 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): stay LED for fully charged
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 304, currTemp = 305, prevStep = 4, currStep = 4
,I/jxcore-log( 7308): {"type":"end","test":9}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"test","name":"make sure startIdentityExchange sets things up properly","id":10}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 10 isOK: undefined : make sure startIdentityExchange sets things up properly", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: PsV1CgsPTRX+Ef9DWytnuw==;Matt
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":45544,"expected":45544,"test":10,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":10,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"PsV1CgsPTRX+Ef9DWytnuw==;Matt","expected":"PsV1CgsPTRX+Ef9DWytnuw==;Matt","test":10,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":4,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/Choreographer( 7308): Skipped 52 frames!  The application may be doing too much work on its main thread.
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"123","expected":"123","test":10,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":8,"ok":true,"name":"should be equal","operator":"equal","actual":"bar1","expected":"bar1","test":10,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":9,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"456","expected":"456","test":10,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":11,"ok":true,"name":"should be equal","operator":"equal","actual":"bar2","expected":"bar2","test":10,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":"started","expected":"started","test":10,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"end","test":10}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"teardown","id":11}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 11 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"end","test":11}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"setup","id":12}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 12 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"end","test":12}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"test","name":"make sure we get an error if we call start and then immediately call stop","id":13}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state startIdentityExchangeCalledCB","test":13,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"end","test":13}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"teardown","id":14}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: bomQRv8v5hFiseW6NtYKfg==;Toby
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":36395,"expected":36395,"test":13,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":13,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"bomQRv8v5hFiseW6NtYKfg==;Toby","expected":"bomQRv8v5hFiseW6NtYKfg==;Toby","test":13,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":13,"type":"assert"}
I/jxcore-log( 7308): 
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 13 isOK: undefined : make sure we get an error if we call start and then immediately call stop", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 14 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 305, currTemp = 304, prevStep = 4, currStep = 4
,I/jxcore-log( 7308): {"type":"end","test":14}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"setup","id":15}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 15 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7308): {"type":"end","test":15}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"test","name":"Make sure stop is clean from start","id":16}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: E0qH/RPbVAADgI5Q9d4IVQ==;Luke
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":45513,"expected":45513,"test":16,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":16,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"E0qH/RPbVAADgI5Q9d4IVQ==;Luke","expected":"E0qH/RPbVAADgI5Q9d4IVQ==;Luke","test":16,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":3,"ok":true,"name":"Should not have gotten error on startIdentityExchange","operator":"notOk","actual":null,"expected":false,"test":16,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":4,"ok":true,"name":"Should not have gotten error on stopIdentityExchange","operator":"notOk","expected":false,"test":16,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":5,"ok":true,"name":"State should be Stopped","operator":"equal","actual":"stopped","expected":"stopped","test":16,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"end","test":16}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 16 isOK: undefined : Make sure stop is clean from start", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"test","name":"teardown","id":17}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : Should not have gotten error on startIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : Should not have gotten error on stopIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : State should be Stopped", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 17 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager( 2418): waitForAlarm result :4
,I/jxcore-log( 7308): {"type":"end","test":17}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"setup","id":18}
I/jxcore-log( 7308): 
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 18 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/SnetService( 3272): snet destroyed
,E/Watchdog( 2418): !@Sync 19
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4
,I/jxcore-log( 7308): {"type":"end","test":18}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"test","name":"Make sure stop is clean from stop execute identity exchange","id":19}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: exRze/htCh6WuzHQ1EfN/g==;Jukka
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":55612,"expected":55612,"test":19,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":19,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"exRze/htCh6WuzHQ1EfN/g==;Jukka","expected":"exRze/htCh6WuzHQ1EfN/g==;Jukka","test":19,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":19,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":4,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":19,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"stopped","expected":"stopped","test":19,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"end","test":19}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 19 isOK: undefined : Make sure stop is clean from stop execute identity exchange", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"test","name":"teardown","id":20}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 20 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"end","test":20}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"setup","id":21}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 21 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"end","test":21}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"test","name":"make sure we do not have a race condition between startIdentityExchange and executeIdentityExchange","id":22}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: 55QrjWbziAOYaWaZIyjrTw==;Doug
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":54325,"expected":54325,"test":22,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":22,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"55QrjWbziAOYaWaZIyjrTw==;Doug","expected":"55QrjWbziAOYaWaZIyjrTw==;Doug","test":22,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":4,"ok":true,"name":"should not throw","operator":"throws","test":22,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"end","test":22}
I/jxcore-log( 7308): 
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 22 isOK: undefined : make sure we do not have a race condition between startIdentityExchange and executeIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"test","name":"teardown","id":23}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should not throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 23 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 275s ago
,I/jxcore-log( 7308): {"type":"end","test":23}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"setup","id":24},
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 24 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7308): {"type":"end","test":24}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"test","name":"illegal method combinations","id":25}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":1,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":2,"ok":true,"name":"should throw","operator":"throws","actual":"event stopIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: L1WY2uG8Gmhbop2ns2UIIg==;David
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":48048,"expected":48048,"test":25,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":25,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"L1WY2uG8Gmhbop2ns2UIIg==;David","expected":"L1WY2uG8Gmhbop2ns2UIIg==;David","test":25,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":25,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":7,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":8,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":9,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":25,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":10,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":11,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: L1WY2uG8Gmhbop2ns2UIIg==;David
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":48048,"expected":48048,"test":25,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":13,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":25,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":14,"ok":true,"name":"should be equal","operator":"equal","actual":"L1WY2uG8Gmhbop2ns2UIIg==;David","expected":"L1WY2uG8Gmhbop2ns2UIIg==;David","test":25,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":15,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":25,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":16,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":17,"ok":true,"name":"should throw","operator":"throws","actual":"event stopIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":18,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":19,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":20,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"end","test":25}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 25 isOK: undefined : illegal method combinations", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"test","name":"teardown","id":26}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 13 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 14 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 15 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 16 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 17 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 18 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 19 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 20 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 26 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"end","test":26}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"setup","id":27}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 27 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/BatteryService( 2418): stay LED for fully charged
V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 304, currTemp = 305, prevStep = 4, currStep = 4
,D/TimaService( 2418): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2418): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2418): TimaServiceHandler.handleMessage what =1
,I/jxcore-log( 7308): {"type":"end","test":27}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"test","name":"do an identity exchange and get code multiple times to make sure we do not hork state","id":28}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: QkmKqMT1D+ygq8W3GxVeJA==;John
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":35233,"expected":35233,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"QkmKqMT1D+ygq8W3GxVeJA==;John","expected":"QkmKqMT1D+ygq8W3GxVeJA==;John","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: iWCAtAuGvq3jU21LNhbOXQ==;Srikanth
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":33295,"expected":33295,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"iWCAtAuGvq3jU21LNhbOXQ==;Srikanth","expected":"iWCAtAuGvq3jU21LNhbOXQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":7,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO smallerHash Making /identity/cb request to pkOther value iWCAtAuGvq3jU21LNhbOXQ==
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 28 isOK: undefined : do an identity exchange and get code multiple times to make sure we do not hork state", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO smallerHash Making /identity/rnmine request to pkOther value iWCAtAuGvq3jU21LNhbOXQ==
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":9,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":10,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":11,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":988736,"expected":988736,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":13,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":14,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: QkmKqMT1D+ygq8W3GxVeJA==;John
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":15,"ok":true,"name":"should be equal","operator":"equal","actual":35233,"expected":35233,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":16,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":17,"ok":true,"name":"should be equal","operator":"equal","actual":"QkmKqMT1D+ygq8W3GxVeJA==;John","expected":"QkmKqMT1D+ygq8W3GxVeJA==;John","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":18,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: iWCAtAuGvq3jU21LNhbOXQ==;Srikanth
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":19,"ok":true,"name":"should be equal","operator":"equal","actual":33295,"expected":33295,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":20,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":21,"ok":true,"name":"should be equal","operator":"equal","actual":"iWCAtAuGvq3jU21LNhbOXQ==;Srikanth","expected":"iWCAtAuGvq3jU21LNhbOXQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":22,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO smallerHash Making /identity/cb request to pkOther value iWCAtAuGvq3jU21LNhbOXQ==
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 13 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 14 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 15 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 16 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 17 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 18 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 19 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO smallerHash Making /identity/rnmine request to pkOther value iWCAtAuGvq3jU21LNhbOXQ==
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 20 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 21 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 22 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":23,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":24,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 23 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":25,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":26,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":27,"ok":true,"name":"should be equal","operator":"equal","actual":220416,"expected":220416,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":28,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":29,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: QkmKqMT1D+ygq8W3GxVeJA==;John
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":30,"ok":true,"name":"should be equal","operator":"equal","actual":35233,"expected":35233,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":31,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":32,"ok":true,"name":"should be equal","operator":"equal","actual":"QkmKqMT1D+ygq8W3GxVeJA==;John","expected":"QkmKqMT1D+ygq8W3GxVeJA==;John","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":33,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: iWCAtAuGvq3jU21LNhbOXQ==;Srikanth
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":34,"ok":true,"name":"should be equal","operator":"equal","actual":33295,"expected":33295,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":35,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":36,"ok":true,"name":"should be equal","operator":"equal","actual":"iWCAtAuGvq3jU21LNhbOXQ==;Srikanth","expected":"iWCAtAuGvq3jU21LNhbOXQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":37,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO smallerHash Making /identity/cb request to pkOther value iWCAtAuGvq3jU21LNhbOXQ==
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 24 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 25 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 26 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO smallerHash Making /identity/rnmine request to pkOther value iWCAtAuGvq3jU21LNhbOXQ==
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 27 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":38,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":39,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 28 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 29 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":40,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":41,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":42,"ok":true,"name":"should be equal","operator":"equal","actual":507328,"expected":507328,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":43,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":44,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: QkmKqMT1D+ygq8W3GxVeJA==;John
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":45,"ok":true,"name":"should be equal","operator":"equal","actual":35233,"expected":35233,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":46,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":47,"ok":true,"name":"should be equal","operator":"equal","actual":"QkmKqMT1D+ygq8W3GxVeJA==;John","expected":"QkmKqMT1D+ygq8W3GxVeJA==;John","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":48,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: iWCAtAuGvq3jU21LNhbOXQ==;Srikanth
I/jxcore-log( 7308): 
I/jxcore-log( 7308): {"id":49,"ok":true,"name":"should be equal","operator":"equal","actual":33295,"expected":33295,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): {"id":50,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 7308): 
I/jxcore-log( 7308): {"id":51,"ok":true,"name":"should be equal","operator":"equal","actual":"iWCAtAuGvq3jU21LNhbOXQ==;Srikanth","expected":"iWCAtAuGvq3jU21LNhbOXQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":52,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO smallerHash Making /identity/cb request to pkOther value iWCAtAuGvq3jU21LNhbOXQ==
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 30 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 31 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 32 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 33 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 34 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 35 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 36 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 37 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 38 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 39 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 40 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 41 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 42 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO smallerHash Making /identity/rnmine request to pkOther value iWCAtAuGvq3jU21LNhbOXQ==
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 43 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 44 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 45 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 46 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 47 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 48 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 49 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 50 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 51 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 52 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":53,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":54,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 53 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 54 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":55,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":56,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":57,"ok":true,"name":"should be equal","operator":"equal","actual":540160,"expected":540160,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":58,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":59,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: QkmKqMT1D+ygq8W3GxVeJA==;John
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":60,"ok":true,"name":"should be equal","operator":"equal","actual":35233,"expected":35233,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":61,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":62,"ok":true,"name":"should be equal","operator":"equal","actual":"QkmKqMT1D+ygq8W3GxVeJA==;John","expected":"QkmKqMT1D+ygq8W3GxVeJA==;John","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":63,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: iWCAtAuGvq3jU21LNhbOXQ==;Srikanth
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":64,"ok":true,"name":"should be equal","operator":"equal","actual":33295,"expected":33295,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":65,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":66,"ok":true,"name":"should be equal","operator":"equal","actual":"iWCAtAuGvq3jU21LNhbOXQ==;Srikanth","expected":"iWCAtAuGvq3jU21LNhbOXQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":67,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO smallerHash Making /identity/cb request to pkOther value iWCAtAuGvq3jU21LNhbOXQ==
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 55 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 56 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 57 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO smallerHash Making /identity/rnmine request to pkOther value iWCAtAuGvq3jU21LNhbOXQ==
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 58 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":68,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":69,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 59 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 60 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 61 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 62 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":70,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":71,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":72,"ok":true,"name":"should be equal","operator":"equal","actual":151552,"expected":151552,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":73,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":74,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: QkmKqMT1D+ygq8W3GxVeJA==;John
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":75,"ok":true,"name":"should be equal","operator":"equal","actual":35233,"expected":35233,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":76,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":77,"ok":true,"name":"should be equal","operator":"equal","actual":"QkmKqMT1D+ygq8W3GxVeJA==;John","expected":"QkmKqMT1D+ygq8W3GxVeJA==;John","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":78,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: iWCAtAuGvq3jU21LNhbOXQ==;Srikanth
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":79,"ok":true,"name":"should be equal","operator":"equal","actual":33295,"expected":33295,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":80,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":81,"ok":true,"name":"should be equal","operator":"equal","actual":"iWCAtAuGvq3jU21LNhbOXQ==;Srikanth","expected":"iWCAtAuGvq3jU21LNhbOXQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":82,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO smallerHash Making /identity/cb request to pkOther value iWCAtAuGvq3jU21LNhbOXQ==
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 63 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 64 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 65 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 66 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 67 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 68 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO smallerHash Making /identity/rnmine request to pkOther value iWCAtAuGvq3jU21LNhbOXQ==
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 69 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 70 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 71 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 72 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 73 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 74 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":83,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":84,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":85,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":86,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":87,"ok":true,"name":"should be equal","operator":"equal","actual":431040,"expected":431040,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":88,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":89,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: QkmKqMT1D+ygq8W3GxVeJA==;John
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":90,"ok":true,"name":"should be equal","operator":"equal","actual":35233,"expected":35233,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":91,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":92,"ok":true,"name":"should be equal","operator":"equal","actual":"QkmKqMT1D+ygq8W3GxVeJA==;John","expected":"QkmKqMT1D+ygq8W3GxVeJA==;John","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":93,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: iWCAtAuGvq3jU21LNhbOXQ==;Srikanth
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":94,"ok":true,"name":"should be equal","operator":"equal","actual":33295,"expected":33295,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":95,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":96,"ok":true,"name":"should be equal","operator":"equal","actual":"iWCAtAuGvq3jU21LNhbOXQ==;Srikanth","expected":"iWCAtAuGvq3jU21LNhbOXQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":97,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO smallerHash Making /identity/cb request to pkOther value iWCAtAuGvq3jU21LNhbOXQ==
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 75 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 76 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 77 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 78 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 79 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 80 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 81 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 82 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 83 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 84 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 85 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 86 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 87 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 88 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 89 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 90 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 91 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 92 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 93 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 94 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 95 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO smallerHash Making /identity/rnmine request to pkOther value iWCAtAuGvq3jU21LNhbOXQ==
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 96 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 97 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":98,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":99,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 98 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 99 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":100,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":101,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":102,"ok":true,"name":"should be equal","operator":"equal","actual":889920,"expected":889920,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":103,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":104,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: QkmKqMT1D+ygq8W3GxVeJA==;John
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":105,"ok":true,"name":"should be equal","operator":"equal","actual":35233,"expected":35233,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":106,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":107,"ok":true,"name":"should be equal","operator":"equal","actual":"QkmKqMT1D+ygq8W3GxVeJA==;John","expected":"QkmKqMT1D+ygq8W3GxVeJA==;John","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":108,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: iWCAtAuGvq3jU21LNhbOXQ==;Srikanth
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":109,"ok":true,"name":"should be equal","operator":"equal","actual":33295,"expected":33295,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":110,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":111,"ok":true,"name":"should be equal","operator":"equal","actual":"iWCAtAuGvq3jU21LNhbOXQ==;Srikanth","expected":"iWCAtAuGvq3jU21LNhbOXQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":112,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO smallerHash Making /identity/cb request to pkOther value iWCAtAuGvq3jU21LNhbOXQ==
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 100 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 101 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 102 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 103 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 104 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 105 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO smallerHash Making /identity/rnmine request to pkOther value iWCAtAuGvq3jU21LNhbOXQ==
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 106 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 107 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 108 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":113,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":114,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 109 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 110 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 111 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":115,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":116,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":117,"ok":true,"name":"should be equal","operator":"equal","actual":162368,"expected":162368,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":118,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":119,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: QkmKqMT1D+ygq8W3GxVeJA==;John
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":120,"ok":true,"name":"should be equal","operator":"equal","actual":35233,"expected":35233,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":121,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":122,"ok":true,"name":"should be equal","operator":"equal","actual":"QkmKqMT1D+ygq8W3GxVeJA==;John","expected":"QkmKqMT1D+ygq8W3GxVeJA==;John","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":123,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: iWCAtAuGvq3jU21LNhbOXQ==;Srikanth
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":124,"ok":true,"name":"should be equal","operator":"equal","actual":33295,"expected":33295,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":125,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":126,"ok":true,"name":"should be equal","operator":"equal","actual":"iWCAtAuGvq3jU21LNhbOXQ==;Srikanth","expected":"iWCAtAuGvq3jU21LNhbOXQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":127,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO smallerHash Making /identity/cb request to pkOther value iWCAtAuGvq3jU21LNhbOXQ==
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 112 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 113 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 114 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 115 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 116 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 117 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 118 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 119 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 120 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 121 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO smallerHash Making /identity/rnmine request to pkOther value iWCAtAuGvq3jU21LNhbOXQ==
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 122 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 123 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 124 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 125 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":128,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":129,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 126 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 127 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 128 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":130,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":131,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":132,"ok":true,"name":"should be equal","operator":"equal","actual":45952,"expected":45952,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":133,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":134,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: QkmKqMT1D+ygq8W3GxVeJA==;John
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":135,"ok":true,"name":"should be equal","operator":"equal","actual":35233,"expected":35233,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":136,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":137,"ok":true,"name":"should be equal","operator":"equal","actual":"QkmKqMT1D+ygq8W3GxVeJA==;John","expected":"QkmKqMT1D+ygq8W3GxVeJA==;John","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":138,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: iWCAtAuGvq3jU21LNhbOXQ==;Srikanth
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":139,"ok":true,"name":"should be equal","operator":"equal","actual":33295,"expected":33295,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":140,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":141,"ok":true,"name":"should be equal","operator":"equal","actual":"iWCAtAuGvq3jU21LNhbOXQ==;Srikanth","expected":"iWCAtAuGvq3jU21LNhbOXQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":142,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO smallerHash Making /identity/cb request to pkOther value iWCAtAuGvq3jU21LNhbOXQ==
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 129 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 130 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 131 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 132 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 133 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 134 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO smallerHash Making /identity/rnmine request to pkOther value iWCAtAuGvq3jU21LNhbOXQ==
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 135 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 136 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 137 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":143,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":144,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 138 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 139 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 140 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":145,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":146,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":147,"ok":true,"name":"should be equal","operator":"equal","actual":864064,"expected":864064,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":148,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":149,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: QkmKqMT1D+ygq8W3GxVeJA==;John
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":150,"ok":true,"name":"should be equal","operator":"equal","actual":35233,"expected":35233,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":151,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":152,"ok":true,"name":"should be equal","operator":"equal","actual":"QkmKqMT1D+ygq8W3GxVeJA==;John","expected":"QkmKqMT1D+ygq8W3GxVeJA==;John","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":153,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO identityExchange We will advertise the following device name as we start: iWCAtAuGvq3jU21LNhbOXQ==;Srikanth
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":154,"ok":true,"name":"should be equal","operator":"equal","actual":33295,"expected":33295,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":155,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":156,"ok":true,"name":"should be equal","operator":"equal","actual":"iWCAtAuGvq3jU21LNhbOXQ==;Srikanth","expected":"iWCAtAuGvq3jU21LNhbOXQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":157,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO smallerHash Making /identity/cb request to pkOther value iWCAtAuGvq3jU21LNhbOXQ==
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 141 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 142 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 143 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 144 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 145 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO smallerHash Making /identity/rnmine request to pkOther value iWCAtAuGvq3jU21LNhbOXQ==
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 146 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 147 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":158,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":159,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":160,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":161,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":162,"ok":true,"name":"should be equal","operator":"equal","actual":937856,"expected":937856,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":163,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":164,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"end","test":28}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"teardown","id":29}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 148 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 149 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 150 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 151 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 152 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 153 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 154 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 155 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 156 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 157 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 158 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 159 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 160 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 161 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 162 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 163 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 164 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 29 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2418): !@Sync 20
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2418): prevTemp = 305, currTemp = 304, prevStep = 4, currStep = 4
,I/jxcore-log( 7308): {"type":"end","test":29}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"setup","id":30}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 30 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4
,I/jxcore-log( 7308): {"type":"end","test":30}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"test compareEqualSizeBuffers","id":31}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":1,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":2,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":3,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":4,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"Buffers must be of the same size."},"test":31,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":8,"ok":true,"name":"should be equal","operator":"equal","actual":0,"expected":0,"test":31,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":0,"expected":0,"test":31,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":1,"expected":1,"test":31,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":11,"ok":true,"name":"should be equal","operator":"equal","actual":1,"expected":1,"test":31,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"end","test":31}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"teardown","id":32}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 31 isOK: undefined : test compareEqualSizeBuffers", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 32 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"end","test":32}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"setup","id":33}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 33 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4
,W/ContextImpl( 2418): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7308): {"type":"end","test":33}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"Make sure we return 404 before hitting start","id":34}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":34,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"end","test":34}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"teardown","id":35}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 34 isOK: undefined : Make sure we return 404 before hitting start", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 35 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,E/Watchdog( 2418): !@Sync 21
,I/jxcore-log( 7308): {"type":"end","test":35}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"setup","id":36}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 36 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 7308): {"type":"end","test":36}
I/jxcore-log( 7308): 
,E/jxcore-log( 7308): (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
E/jxcore-log( 7308): 
,E/jxcore-log( 7308): Trace: 
E/jxcore-log( 7308):     at Console.prototype.trace@console.js:169:13
E/jxcore-log( 7308):     at addListener@events.js:140:7
E/jxcore-log( 7308):     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/pouchdb-all-dbs/index.js:61:3
E/jxcore-log( 7308):     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:138:9
E/jxcore-log( 7308):     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/util.js:26:16
E/jxcore-log( 7308):     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:507:13
E/jxcore-log( 7308):     at module.exports/Promise.prototype._settlePromiseAt@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:581:13
E/jxcore-log( 7308):     at module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/
,E/jxcore-log( 7308): (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
E/jxcore-log( 7308): 
,E/jxcore-log( 7308): Trace: 
E/jxcore-log( 7308):     at Console.prototype.trace@console.js:169:13
E/jxcore-log( 7308):     at addListener@events.js:140:7
E/jxcore-log( 7308):     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/pouchdb-all-dbs/index.js:85:3
E/jxcore-log( 7308):     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:138:9
E/jxcore-log( 7308):     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/util.js:26:16
E/jxcore-log( 7308):     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:507:13
E/jxcore-log( 7308):     at module.exports/Promise.prototype._settlePromiseAt@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:581:13
E/jxcore-log( 7308):     at module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 7308): {"type":"test","name":"Random path after start, need 404","id":37}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 37 isOK: undefined : Random path after start, need 404", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":37,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"end","test":37}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"teardown","id":38}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 38 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/AmoledAdjustTimer( 2418): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4
,I/jxcore-log( 7308): {"type":"end","test":38}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"setup","id":39}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 39 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/PowerManagerService( 2418): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,I/jxcore-log( 7308): {"type":"end","test":39}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"test","name":"Confirm we go to wrongPeer if our hash is smaller","id":40}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"WrongPeer","expected":"WrongPeer","test":40,"type":"assert"}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 40 isOK: undefined : Confirm we go to wrongPeer if our hash is smaller", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":40,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"L6juhM3NFQC4cMpjjcxBJA==","expected":"L6juhM3NFQC4cMpjjcxBJA==","test":40,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":40,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"end","test":40}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"teardown","id":41}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 41 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
D/BatteryService( 2418): stay LED for fully charged
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,I/jxcore-log( 7308): {"type":"end","test":41}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"setup","id":42}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 42 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"end","test":42}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"test","name":"Confirm we go to wrongPeer if our hash is smaller","id":43}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"WrongPeer","expected":"WrongPeer","test":43,"type":"assert"}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 43 isOK: undefined : Confirm we go to wrongPeer if our hash is smaller", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":43,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"npravcNLyqlxpSlbr3zEsQ==","expected":"npravcNLyqlxpSlbr3zEsQ==","test":43,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":43,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"end","test":43}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"teardown","id":44}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,D/AmoledAdjustTimer( 2418): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 44 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"end","test":44}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"setup","id":45}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 45 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/GAV2    ( 5729): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5729): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2418): !@Sync 22
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,I/jxcore-log( 7308): {"type":"end","test":45}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"test","name":"Confirm we get wrongPeer on cb if we give hash other than expected","id":46}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 46 isOK: undefined : Confirm we get wrongPeer on cb if we give hash other than expected", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":46,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"hq9H5BaykF6b0bJXv8z4zg==","expected":"hq9H5BaykF6b0bJXv8z4zg==","test":46,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":46,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"end","test":46}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"teardown","id":47}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 47 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/AmoledAdjustTimer( 2418): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4
,I/jxcore-log( 7308): {"type":"end","test":47}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"setup","id":48}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 48 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"end","test":48}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"test","name":"Confirm we get Skip Ahead even with a wrong peer on a rnMine request (and we can argue if this is a good choice)","id":49}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 49 isOK: undefined : Confirm we get Skip Ahead even with a wrong peer on a rnMine request (and we can argue if this is a good choice)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"skippedAhead","expected":"skippedAhead","test":49,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"7Ytse7NT2+OA1rE6KQrANQ==","expected":"7Ytse7NT2+OA1rE6KQrANQ==","test":49,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":49,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"end","test":49}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"teardown","id":50}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
V/AlarmManager( 2418): waitForAlarm result :8
V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
V/AlarmManager( 2418): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2418): <AppSync3 Whitelist>
,V/AlarmManager( 2418): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 50 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"end","test":50}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"setup","id":51}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 51 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 304, currTemp = 303, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 23
,I/jxcore-log( 7308): {"type":"end","test":51}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"NoIdentityExchange after start & stop","id":52}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 52 isOK: undefined : NoIdentityExchange after start & stop", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,I/jxcore-log( 7308): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"5ERmTtSdYLxwC5xZjtAzng==","expected":"5ERmTtSdYLxwC5xZjtAzng==","test":52,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":2,"ok":true,"name":{"req":{"method":"post","url":"http://127.0.0.1:59573/identity/cb","data":{"cbValue":"AwKYMAANEOPPZ1T6tvD3QReUc0uyDYgtIO+RFCa93qo=","pkMine":"sQCvbn9nDXRHGMMSvoY2SA=="}},"header":{"x-powered-by":"Express","content-type":"application/json; charset=utf-8","content-length":"77","etag":"W/\"4d-TY2TyfZYoReoXZEXFSJVvg\"","date":"Mon, 23 Nov 2015 12:57:24 GMT","connection":"close"},"status":400,"text":"{\"errorCode\":\"notDoingIdentityExchange\",\"pkOther\":\"5ERmTtSdYLxwC5xZjtAzng==\"}"},"operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"5ERmTtSdYLxwC5xZjtAzng==","expected":"5ERmTtSdYLxwC5xZjtAzng==","test":52,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":5,"ok":true,"name":{"req":{"method":"post","url":"http://127.0.0.1:52397/identity/rnmine","data":{"rnMine":"LL+d5hd+odYBsiUYJTNNgg==","pkOther":"ozppdXD2a5bz9FvoZbE+jQ=="}},"header":{"x-powered-by":"Express","content-type":"application/json; charset=utf-8","content-length":"77","etag":"W/\"4d-TY2TyfZYoReoXZEXFSJVvg\"","date":"Mon, 23 Nov 2015 12:57:24 GMT","connection":"close"},"status":400,"text":"{\"errorCode\":\"notDoingIdentityExchange\",\"pkOther\":\"5ERmTtSdYLxwC5xZjtAzng==\"}"},"operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"5ERmTtSdYLxwC5xZjtAzng==","expected":"5ERmTtSdYLxwC5xZjtAzng==","test":52,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":8,"ok":true,"name":{"req":{"method":"post","url":"http://127.0.0.1:38201/identity/cb","data":{"cbValue":"0ojt2fS01k+hMytgX1D/z4pCLIRjzrjpdTujxDOfT4E=","pkMine":"AX++2pNuU5M9aJGx2X1X3Q=="}},"header":{"x-powered-by":"Express","content-type":"application/json; charset=utf-8","content-length":"77","etag":"W/\"4d-TY2TyfZYoReoXZEXFSJVvg\"","date":"Mon, 23 Nov 2015 12:57:24 GMT","connection":"close"},"status":400,"text":"{\"errorCode\":\"notDoingIdentityExchange\",\"pkOther\":\"5ERmTtSdYLxwC5xZjtAzng==\"}"},"operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"5ERmTtSdYLxwC5xZjtAzng==","expected":"5ERmTtSdYLxwC5xZjtAzng==","test":52,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":11,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"end","test":52}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"teardown","id":53}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : [object Object]", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : [object Object]", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"end","test":53}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"setup","id":54}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : [object Object]", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 53 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 54 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4
,I/jxcore-log( 7308): {"type":"end","test":54}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"test","name":"cbRequest - bad request bodies","id":55}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 55 isOK: undefined : cbRequest - bad request bodies", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":" ","pkMine":"IpOyrR4zbLAfvqXPktBQBg=="}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":"{@#{$@#{$","pkMine":"lYDP/V1NtVCRU1WGYpUfSA=="}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":"RQfaufiUatIG8YGVCCHinJzglcLjHCv3rtUiNkJzY8An","pkMine":"6ug43Db2ZgkwIRUMO9b3eg=="}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":"0FMaNVt2+MQKotwujB5NV/QEcncDP0oH3Wkgd/3kqg==","pkMine":"YUhGRBV1vyCuh2FN8wPUvw=="}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"HxgO7pnTUHk+NwKcyX3ycTx2ugApU6tv7kwxWZxKcnc=","pkMine":" "}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"NhMr3cKYr2JvYBIxxtTIgTs75b+3gYi/B6h/2hPOl44=","pkMine":"{@#{$@#{$"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"7irvBX63Yl0lGWpg49QuthBEsvXAPR6LYLjFsk+s0qU=","pkMine":"lZ38RBMgfGGlcgnfN/bVUtY="}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"PQfLNYhTq9aVSXcTYnUNzl9n3fBqPqzpu88fKM6bKcA=","pkMine":"uoL+nIwNjMxQFVns16HN"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":" "}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":"{@#{$@#{$"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":"lZ38RBMgfGGlcgnfN/bVUtY="}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":"uoL+nIwNjMxQFVns16HN"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":" "},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":"{@#{$@#{$"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":"lZ38RBMgfGGlcgnfN/bVUtY="},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":"uoL+nIwNjMxQFVns16HN"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"RQfaufiUatIG8YGVCCHinJzglcLjHCv3rtUiNkJzY8An","pkMine":" "},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"RQfaufiUatIG8YGVCCHinJzglcLjHCv3rtUiNkJzY8An","pkMine":"{@#{$@#{$"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"RQfaufiUatIG8YGVCCHinJzglcLjHCv3rtUiNkJzY8An","pkMine":"lZ38RBMgfGGlcgnfN/bVUtY="},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"RQfaufiUatIG8YGVCCHinJzglcLjHCv3rtUiNkJzY8An","pkMine":"uoL+nIwNjMxQFVns16HN"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"0FMaNVt2+MQKotwujB5NV/QEcncDP0oH3Wkgd/3kqg==","pkMine":" "},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"0FMaNVt2+MQKotwujB5NV/QEcncDP0oH3Wkgd/3kqg==","pkMine":"{@#{$@#{$"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"0FMaNVt2+MQKotwujB5NV/QEcncDP0oH3Wkgd/3kqg==","pkMine":"lZ38RBMgfGGlcgnfN/bVUtY="},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"0FMaNVt2+MQKotwujB5NV/QEcncDP0oH3Wkgd/3kqg==","pkMine":"uoL+nIwNjMxQFVns16HN"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): INFO largerHash Got a /identity/cb request with a bum pkMine - {},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":11,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":13,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":14,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":15,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":16,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":17,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":18,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"},
I/jxcore-log( 7308): 
I/jxcore-log( 7308): {"id":19,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":20,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":21,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":22,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":23,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":24,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":25,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":26,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":27,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":28,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":29,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":30,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":31,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":32,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":33,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":34,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":35,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":36,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":37,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":38,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":39,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":40,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":41,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":42,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":43,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":44,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":45,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":46,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":47,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":48,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":49,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":50,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":51,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":52,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":53,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":54,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":55,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":56,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":57,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":58,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":59,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":60,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":61,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":62,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":63,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":64,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":65,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":66,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":67,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":68,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":69,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":70,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":71,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":72,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":73,"ok":true,"name":"should be equal","operator":"equal","actual":"hGTXOJXPOzgFQtsLuHoPMA==","expected":"hGTXOJXPOzgFQtsLuHoPMA==","test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":74,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"end","test":55}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"teardown","id":56}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 13 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 14 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 15 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 16 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 17 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 18 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 19 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 20 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 21 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 22 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 23 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 24 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 25 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 26 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 27 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 28 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 29 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 30 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 31 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 32 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 33 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 34 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 35 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 36 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 37 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 38 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 39 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 40 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 41 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 42 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 43 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 44 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 45 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 46 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 47 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 48 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 49 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 50 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 51 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 52 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 53 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 54 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 55 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 56 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 57 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 58 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 59 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 60 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 61 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 62 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 63 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 64 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 65 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 66 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 67 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 68 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 69 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 70 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 71 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 72 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 73 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 74 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 56 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/PowerManagerService( 2418): [PWL] Off : 390s ago
,I/jxcore-log( 7308): {"type":"end","test":56}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"setup","id":57}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 57 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,I/jxcore-log( 7308): {"type":"end","test":57}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"test","name":"re-do cb (to check we can reset) and make sure rnOther changes","id":58}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":"QGx5OcxbCtV4q6Qsl8IhUQ==","expected":true,"test":58,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"Ee9g8GRGaEztfv44MqyX4w==","expected":"Ee9g8GRGaEztfv44MqyX4w==","test":58,"type":"assert"}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 58 isOK: undefined : re-do cb (to check we can reset) and make sure rnOther changes", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":2,"ok":true,"name":"should not be equal","operator":"notEqual","actual":"QGx5OcxbCtV4q6Qsl8IhUQ==","test":58,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"Ee9g8GRGaEztfv44MqyX4w==","expected":"Ee9g8GRGaEztfv44MqyX4w==","test":58,"type":"assert"}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"Ee9g8GRGaEztfv44MqyX4w==","expected":"Ee9g8GRGaEztfv44MqyX4w==","test":58,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"end","test":58}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"teardown","id":59}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 59 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/AmoledAdjustTimer( 2418): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4
,I/jxcore-log( 7308): {"type":"end","test":59}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"setup","id":60}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 60 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"end","test":60}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"test","name":"good cb followed by good rnmine then repeat cb and finish up, make sure we have new rnOther","id":61}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 61 isOK: undefined : good cb followed by good rnmine then repeat cb and finish up, make sure we have new rnOther", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":"wiFFcwa4sr7UkugRxbIk3g==","expected":true,"test":61,"type":"assert"}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":1,"ok":true,"name":"should not be equal","operator":"notEqual","actual":"xfpnAUKsTHahcOFpscDMBQ==","test":61,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":[197,250,103,1,66,172,76,118,161,112,225,105,177,192,204,5],"expected":true,"test":61,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":338496,"expected":338496,"test":61,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"end","test":61}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"teardown","id":62}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 62 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"end","test":62}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"setup","id":63}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 63 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/AmoledAdjustTimer( 2418): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4
,I/jxcore-log( 7308): {"type":"end","test":63}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"test","name":"do a successful cb and successful rnmine and then repeat the rnmine","id":64}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":"Islm+J02A124xxnHcX9e6A==","expected":true,"test":64,"type":"assert"}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 64 isOK: undefined : do a successful cb and successful rnmine and then repeat the rnmine", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":[34,201,102,248,157,54,3,93,184,199,25,199,113,127,94,232],"expected":true,"test":64,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":789184,"expected":789184,"test":64,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"end","test":64}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"teardown","id":65}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 65 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7308): {"type":"end","test":65}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"setup","id":66}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 66 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,E/Watchdog( 2418): !@Sync 24
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4083): GC_CONCURRENT freed 2890K, 30% free 9726K/13760K, paused 28ms+3ms, total 114ms
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4
,I/jxcore-log( 7308): {"type":"end","test":66},
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 7308): {"type":"test","name":"do a rnmine without a cb","id":67},
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"skippedAhead","expected":"skippedAhead","test":67,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"XWxLFuGdk2YOSgGmtLUo4w==","expected":"XWxLFuGdk2YOSgGmtLUo4w==","test":67,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":67,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"end","test":67}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"type":"test","name":"teardown","id":68}
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 67 isOK: undefined : do a rnmine without a cb", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 68 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 303, currTemp = 302, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 25
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 455s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 26
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/daemonapp( 5449): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 5449): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
D/daemonapp( 5449): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5449): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5449): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionAUTOREFRESH, run:true
D/comsamsunglog( 5449): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5449): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5449): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5449): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5449): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5449): [MSC_Daemon]>>> WDSM:441 [0:0] == executeAutofresh ==
,D/daemonapp( 5449): [MSC_Daemon]>>> WU:551 [0:0] Cncl30MinRftAl
,D/daemonapp( 5449): [MSC_Daemon]>>> WDSM:447 [0:0] !!!! isScreenOn = false
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,E/SPPClientService( 5638): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 27
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = -10
,D/AmoledAdjustTimer( 2418): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 525s ago
,E/Watchdog( 2418): !@Sync 28
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 301, currTemp = 302, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 29
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/dalvikvm( 2418): GC_CONCURRENT freed 4054K, 73% free 25920K/95884K, paused 21ms+20ms, total 269ms
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,D/TimaService( 2418): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2418): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2418): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2418): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 330, Delta = 10
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2418): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2418): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = -10
,D/AmoledAdjustTimer( 2418): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 31
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 32
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 680s ago
,E/Watchdog( 2418): !@Sync 33
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 34
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 35
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2418): [PWL] Off : 765s ago
,E/Watchdog( 2418): !@Sync 36
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2759): GC_CONCURRENT freed 7039K, 39% free 18947K/30632K, paused 19ms+8ms, total 122ms
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :4
,I/SensorManagerA( 2418): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2418): LightSensor setDelay = 200000000
,D/Sensors ( 2418): LightSensor setSensorDelay = 200000000
,D/LightsService( 2418): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2418): Light sensor flush: not enabled 0
D/Sensors ( 2418): LightSensor enable = 1
D/Sensors ( 2418): LightSensor enableSensor = 1
D/SensorManager( 2418): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Sensors ( 2418): LightSensor enable = 0
,D/Sensors ( 2418): LightSensor enableSensor = 0
,D/SensorManager( 2418): unregisterListener ::   
D/LightsService( 2418): [SvcLED]  onSensorChanged::light value = 8
D/LightsService( 2418): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SPPClientService( 5638): [b] __PingReply__
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 37
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 38
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 855s ago
,E/Watchdog( 2418): !@Sync 39
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/TimaService( 2418): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2418): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2418): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): stay LED for fully charged
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 11600
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 11602
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 11603
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 11605
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 11607
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 11608
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 11610
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 11612
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 11613
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 11615
,E/Watchdog( 2418): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 41
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2418): [PWL] Off : 950s ago
,E/Watchdog( 2418): !@Sync 42
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2418): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2418): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2418): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 43
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 44
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2418): GC_CONCURRENT freed 4092K, 73% free 25918K/95884K, paused 12ms+18ms, total 219ms
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 45
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 46
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 47
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 298, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 48
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4083): GC_CONCURRENT freed 2050K, 30% free 9724K/13760K, paused 4ms+2ms, total 51ms
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 1155s ago
,E/Watchdog( 2418): !@Sync 49
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/TimaService( 2418): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2418): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2418): TimaServiceHandler.handleMessage what =1
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 12370
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 12375
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 12380
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 12385
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 12388
,W/ProcessCpuTracker( 2418): Skipping unknown process pid 12391
,E/Watchdog( 2418): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 51
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 52
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,I/PowerManagerService( 2418): [PWL] Off : 1265s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 53
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 54
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 55
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 56
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2418): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :4
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5638): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,I/EventLogService( 3272): Aggregate from 1448282118214 (log), 1448282118214 (data)
,V/AlarmManager( 2418): waitForAlarm result :8
,I/SensorManagerA( 2418): getReportingMode :: sensor.mType = 5
D/Sensors ( 2418): LightSensor setDelay = 200000000
D/Sensors ( 2418): LightSensor setSensorDelay = 200000000
D/Sensors ( 2418): Light sensor flush: not enabled 0
,D/Sensors ( 2418): LightSensor enable = 1
,D/Sensors ( 2418): LightSensor enableSensor = 1
,D/LightsService( 2418): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/SensorManager( 2418): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2418): LightSensor enable = 0
,D/Sensors ( 2418): LightSensor enableSensor = 0
,D/LightsService( 2418): [SvcLED]  onSensorChanged::light value = 7
,D/SensorManager( 2418): unregisterListener ::   
D/LightsService( 2418): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 57
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 296, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 58
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 59
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/dalvikvm( 2418): GC_CONCURRENT freed 4012K, 73% free 25957K/95884K, paused 24ms+18ms, total 257ms
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/TimaService( 2418): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2418): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2418): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2418): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2418): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2418): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2418): Prepared write state in 53ms
,I/ProcessStatsService( 2418): Pruning old procstats: /data/system/procstats/state-2015-11-22-16-39-57.bin
,I/ProcessStatsService( 2418): Prepared write state in 36ms
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2418): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2418): !@Sync 61
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2418): waitForAlarm result :4
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
V/NetworkStats( 2418): performPollLocked(flags=0x3)
,V/AlarmManager( 2418): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,V/NetworkStats( 2418): performPollLocked() took 38ms
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,I/SELinux (13562): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13562):  
,I/SELinux (13562): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13562):  
I/SELinux (13562):  
,I/SELinux (13562): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (13562): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(13562): >>>>> Normal User
,E/dalvikvm(13562): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (13562): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(13562): in addTimaSignatureService
,D/TimaKeyStoreProvider(13562): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(13562): Added TimaKesytore provider
,D/dalvikvm(13562): GC_CONCURRENT freed 2998K, 31% free 9574K/13716K, paused 4ms+2ms, total 29ms
,D/dalvikvm(13562): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/@ WidgetProvider(13562): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(13562): onUpdate called for widgetId : 0
,D/@ WidgetProvider(13562): Widget random data : 10
,D/@ WidgetProvider(13562): onUpdate called for widgetId : 5
,D/@ WidgetProvider(13562): Widget random data : 7
,I/ActivityManager( 2418): Killing 6743:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty #43
E/dalvikvm(13562): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(13562): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(13562): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(13562): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(13562): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(13562): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(13562): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(13562): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(13562): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(13562): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(13562): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(13562): VFY: replacing opcode 0x22 at 0x0038
,D/dalvikvm(13562): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
,D/dalvikvm(13562): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(13562): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(13562): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,V/GLSActivity( 2843): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2843): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(13562): Thread-687(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(13562): Thread-687(ApacheHTTPLog):isShipBuild true
,I/System.out(13562): Thread-687(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out(13562): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(13562): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(13562): Max ALLOWED memory (MB): 128
V/ImageManager(13562): Max SHOULD USE memory (MB): 128
,V/ImageManager(13562): Max Image Cache memory (MB): 32
,D/skia    (13562): getTotalSize : Do not get file length
,D/@ WidgetProvider(13562): Building widget : 5
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 294, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 62
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager( 2418): waitForAlarm result :8
,V/AlarmManager( 2418): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2418): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2418): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2418): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,E/Watchdog( 2418): !@Sync 63
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/BatteryService( 2418): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3995): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3995): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2418): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2418): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,I/jxcore-log( 7308): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,D/BluetoothAdapterService(1112222984)( 3995): unRegister RemoteMessageListener
,D/HeadsetService( 3995): registerMessageListener
,D/HeadsetStateMachine( 3995): Disconnected process message: 80
,D/BluetoothAdapterState( 3995): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,I/BluetoothAdapterState( 3995): Bluetooth adapter state changed: 12-> 13
,D/HeadsetStateMachine( 3995): processUnRegisterMessageListener : 2
D/BluetoothAdapterService( 3995): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 3995): updateAdapterState state is 13
,I/BluetoothPbapService( 3995): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothAdapterService( 3995): Broadcasting updateAdapterState() to 1 receivers.
,E/bt-btif ( 3995): bta_jv_rfcomm_stop_server
,D/BluetoothAdapterService( 3995): Autoconnection is available 
,D/PhoneApp( 2749): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 13
W/InputMethodManagerService( 2418): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/SamsungIME( 2997): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/InputMethodManagerService( 2418): [BT Setting State] State =13
D/BluetoothAdapterService( 3995): updateAdapterState prevState = 12newState = 13
I/QuickConnect[1.1][2] ( 5231): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_OFF
D/BluetoothAdapterService( 3995): terminating service from this receiver
W/ContextImpl( 3995): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.stopService:511 com.android.bluetooth.btservice.AdapterService.updateAdapterState:657 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
D/BluetoothPbap( 2827): Proxy object disconnected
,D/STATUSBAR-IconMerger( 2577): checkOverflow(336), More:false, Req:false Child:3
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
E/bt-btif ( 3995): bta_jv_rfcomm_stop_server
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
D/PbapServerProfile( 2827): Bluetooth service disconnected
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
I/wpa_supplicant( 3966): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3966): wlan0: Setting scan request: 0 sec 0 usec
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
V/BluetoothEventManager( 2827): Received android.bluetooth.adapter.action.STATE_CHANGED
W/Settings( 2418): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine( 2418): ignore requestNetworkTransitionWakelock airplane:true
E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
I/wpa_supplicant( 3966): Scan requested (ret=0) - scan timeout 30 seconds
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
D/GKI_LINUX( 3995): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,I/BluetoothAdapterState( 3995): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/WifiP2pService( 2418): InactiveState{ what=143375 }
,D/WifiP2pService( 2418): P2pEnabledState{ what=143375 }
I/BtOppRfcommListener( 3995): stopping Accept Thread
D/BluetoothAdapterState( 3995): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
E/BtOppRfcommListener( 3995): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 3995): BluetoothSocket listen thread finished
I/WifiManager( 7308): packageName : com.test.thalitest
E/bt-btif ( 3995): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
E/bt-btif ( 3995): bta_jv_rfcomm_stop_server
E/bt-btif ( 3995): cmd socket is not created
D/CommandListener( 1915): Clearing all IP addresses on wlan0
D/btif_config_util( 3995): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
,D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): {"id":0,"ok":false,"name":"Coordinator server got disconnected","operator":"fail","error":{},"test":68,"type":"assert"}
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
D/ConnectivityService( 2418): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2418): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2418): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2418): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2418): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2418): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/IOP_DB_BT( 3995): db_close: nbr users 0
,D/IOP_DB_BT( 3995): db_close: free database
D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
D/ConnectivityService( 2418): Attempting to switch to mobile
D/ConnectivityService( 2418): Attempting to switch to BLUETOOTH_TETHER
,E/WifiStateMachine( 2418): Error! unhandled message{ when=-2ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2418): Error! unhandled message{ when=-1ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
D/STATUSBAR-IconMerger( 2577): checkOverflow(384), More:false, Req:false Child:3
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
D/WifiP2pService( 2418): InactiveState{ what=131204 }
,D/WifiP2pService( 2418): P2pEnabledState{ what=131204 }
V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,D/WifiP2pService( 2418): sending p2p connection changed broadcast: FAILED
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
V/RouteController( 1915): RTNETLINK answers: No such file or directory
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,W/NetworkManagementService( 2418): route cmd failed: 
W/NetworkManagementService( 2418): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '59 route del src v6 2' failed with '400 59 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
W/WifiP2pStateTracker( 2418): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiDisplayController( 2418): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
D/QuickConnect[1.1][2] ( 5231): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
D/WifiDisplayAdapter( 2418): onP2pDisconnected
D/IpRemoteDisplayController( 2418): disconnectWfdBridgeServer
,D/IpRemoteDisplayController( 2418): WfdBridgeServer is already null
D/QuickConnect[1.1][2] ( 5231): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
V/RouteController( 1915): RTNETLINK answers: No such process
V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/WifiStateMachine( 2418): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController( 2418): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,D/QuickConnect[1.1][2] ( 5231): SconnectManager.INetworkStateListener, onDisabled - mNetworkState : 0
D/WifiDisplayController( 2418): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 2418): disconnect
D/WifiDisplayController( 2418): updateConnection
D/WifiDisplayController( 2418): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayAdapter( 2418): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/QuickConnect[1.1][2] ( 5231): P2pHelper.cancelConnectPeer -  mTargetList clear all 
,D/QuickConnect[1.1][2] ( 5231): P2pHelper.removeP2pConfirm - skip: false
,D/NetUtils( 2418): android_net_utils_resetConnections in env=0x78207fc8 clazz=0x9da00001 iface=wlan0 mask=0x3
D/WifiP2pService( 2418): sending p2p connection changed broadcast: DISCONNECTED
D/ConnectivityService( 2418): resetConnections(wlan0, 3)
D/WifiDisplayAdapter( 2418): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/ContextImpl( 2827): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/WifiP2pService( 2418): P2pDisablingState
D/WifiP2pService( 2418): P2pDisablingState{ what=139287 }
D/WifiP2pService( 2418): DefaultState{ what=139287 }
D/WifiP2pService( 2418): P2pDisablingState{ what=147458 }
D/WifiP2pService( 2418): p2p socket connection lost
,D/WifiP2pService( 2418): P2pDisabledState
D/QuickConnect[1.1][2] ( 5231): CentralActionManager.removeHoldingIntentAll - all request done.
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
D/QuickConnect[1.1][2] ( 5231): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
,D/QuickConnect[1.1][2] ( 5231): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
W/WifiP2pStateTracker( 2418): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController( 2418): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter( 2418): onP2pDisconnected
D/IpRemoteDisplayController( 2418): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 2418): WfdBridgeServer is already null
D/WifiP2pService( 2418): P2pDisabledState{ what=139376 }
D/WifiP2pService( 2418): DefaultState{ what=139376 }
,E/WifiP2pService( 2418): Unhandled message { what=139376 }
D/QuickConnect[1.1][2] ( 5231): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/WifiManager( 7308): packageName : com.test.thalitest
D/QuickConnect[1.1][2] ( 5231): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,D/BluetoothAdapterState( 3995): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
D/QuickConnect[1.1][2] ( 5231): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/BtConfig.SecureMode( 3995): isSecureModeOn:false
W/BluetoothAdapterService( 3995): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 3995): Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 3995): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
D/WifiP2pService( 2418): P2pDisabledState{ what=139287 }
,D/WifiP2pService( 2418): DefaultState{ what=139287 }
D/BtSettings.ProfileConfig( 3995): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
W/BluetoothAdapterService( 3995): Not skipping com.android.bluetooth.hfp.HeadsetService
D/HeadsetService( 3995): Received stop request...Stopping profile...
W/BluetoothAdapterService( 3995): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 3995): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
W/BluetoothAdapterService( 3995): Not skipping com.android.bluetooth.a2dp.A2dpService
D/DockEventReceiver( 2827): finishStartingService: stopping service
I/WifiManager( 7308): packageName : com.test.thalitest
W/BluetoothAdapterService( 3995): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 3995): getProfileSaveSetting: com.android.bluetooth.hid.HidService
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
W/BluetoothAdapterService( 3995): Not skipping com.android.bluetooth.hid.HidService
D/QuickConnect[1.1][2] ( 5231): HeadsetProfile.onServiceDisconnected - Bluetooth service disconnected
E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
W/BluetoothAdapterService( 3995): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 3995): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
W/BluetoothAdapterService( 3995): Not skipping com.android.bluetooth.hdp.HealthService
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
W/BluetoothAdapterService( 3995): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 3995): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/BluetoothNotiBroadcastReceiver( 2827): onReceive
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
W/BluetoothAdapterService( 3995): Not skipping com.android.bluetooth.pan.PanService
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
D/HeadsetProfile( 2827): Bluetooth service disconnected
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
W/BluetoothAdapterService( 3995): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 3995): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 3995): Not skipping com.android.bluetooth.map.BluetoothMapService
E/SPPClientService( 5638): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
E/SPPClientService( 5638): [e] exceptionCaught(). NET_TIMEOUT
W/BluetoothAdapterService( 3995): check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 3995): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
W/BluetoothAdapterServic,e( 3995): Not skipping com.broadcom.bt.service.sap.SapService
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
E/SPPClientService( 5638): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
D/BluetoothAdapterState( 3995): Stopping profile services that were post enabled
E/SPPClientService( 5638): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
E/SPPClientService( 5638): [b] ResponseMap empty
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
D/BtSettings.ProfileConfig( 3995): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 3995): Profile still running: com.broadcom.bt.service.sap.SapService
D/A2dpService( 3995): Received stop request...Stopping profile...
D/A2dpStateMachine( 3995): Exit Disconnected: -1
D/Avrcp   ( 3995): Unregistering previous receiver
D/MediaFocusControl( 2418): <<< unregisterRemoteControlDisplay
E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
D/GKI_LINUX( 3995): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
I/WifiTrafficPoller( 2418): evaluateTrafficStatsPolling
D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
D/BluetoothA2dp( 5231): Proxy object disconnected
D/QuickConnect[1.1][2] ( 5231): A2dpProfile.onServiceConnected - Bluetooth service disconnected
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
D/BluetoothA2dp( 2418): Proxy object disconnected
D/WifiNative( 2418): callSECApiBoolean - ID [13]
E/WifiController( 2418): illegal state found both WifiController and WifiStateMachine
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
I/wpa_supplicant( 3966): USE_NETWORK : USE_NETWORK OFF
W/BluetoothHeadsetServiceJni( 3995): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3995): Cleaning up Bluetooth Handsfree callback object
D/HidService( 3995): Received stop request...Stopping profile...
D/HidService( 3995): Stopping Bluetooth HidService
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/WifiManager( 7308): packageName : com.test.thalitest
D/BluetoothInputDevice( 5231): Proxy object disconnected
D/QuickConnect[1.1][2] ( 5231): HidProfile.onServiceDisconnected - Bluetooth service disconnected
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
D/HealthService( 3995): Received stop request...Stopping profile...
D/BluetoothA2dp( 4161): Proxy object disconnected
E/WifiStateMachine( 2418): Error! unhandled message{ when=-26ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
E/WifiStateMachine( 2418): Error! unhandled message{ when=-31ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2577): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2577): refreshSignalCluster: data=-1 bt=false
D/BluetoothA2dp( 2827): Proxy object disconnected
D/PanService( 3995): Received stop request...Stopping profile...
E/WifiStateMachine( 2418): Error! unhandled message{ when=-2ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2418): Error! unhandled message{ when=-2ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
D/A2dpProfile( 2827): Bluetooth service disconnected
D/BluetoothInputDevice( 2827): Proxy object disconnected
D/HidProfile( 2827): Bluetooth service disconnected
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
D/BluetoothPan( 2418): BluetoothPAN Proxy object disconnected
I/WifiManager( 7308): packageName : com.test.thalitest
D/BluetoothPan( 2827): BluetoothPAN Proxy object disconnected
D/PanProfile( 2827): Bluetooth service disconnected
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
D/BluetoothMapService( 3995): Received stop request...Stopping profile...
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
D/BluetoothMap( 2827): Proxy object disconnected
D/MapProfile( 2827): Bluetooth service disconnected
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
D/SapService( 3995): Received stop request...Stopping profile...
D/SapService( 3995): Stopping Bluetooth SapService
D/AuthorizationBluetoothService( 2843): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/Bluetoothsap( 2827): BluetoothSAP Proxy object disconnected
D/SapProfile( 2827): Bluetooth service disconnected
D/BtSettings.ProfileConfig( 3995): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 3995): Profile still running: com.broadcom.bt.service.sap.SapService
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/WifiManager( 7308): packageName : com.test.thalitest
D/Bluetoothsap( 2827): BluetoothSAP Proxy object disconnected
D/SapProfile( 2827): Bluetooth service disconnected
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
I/GKI_LINUX( 3995): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3995): GKI_exit_task: GKI_exit_task 2 done
I/GKI_LINUX( 3995): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BtSettings.ProfileConfig( 3995): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 3995): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothHidServiceJni( 3995): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3995): Cleaning up Bluetooth GID callback object
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
D/BtSettings.ProfileConfig( 3995): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 3995): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothHealthServiceJni( 3995): Cleaning up Bluetooth Health Interface...
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
W/BluetoothHealthServiceJni( 3995): Cleaning up Bluetooth Health object
D/BtSettings.ProfileConfig( 3995): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 3995): Profile still running: com.broadcom.bt.service.sap.SapService,
W/BluetoothPanServiceJni( 3995): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3995): Cleaning up Bluetooth PAN callback object
D/BtSettings.ProfileConfig( 3995): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 3995): Profile still running: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 3995): Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
W/BluetoothSAPServiceJni( 3995): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 3995): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterState( 3995): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 3995): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 3995): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 3995): updateAdapterState state is 10
D/BluetoothAdapterService( 3995): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 3995): Autoconnection is available 
D/BluetoothAdapterService( 3995): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 3995): Entering OffState
D/BluetoothA2dp( 5231): onBluetoothStateChange: up=false
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
D/BluetoothInputDevice( 5231): onBluetoothStateChange: up=false
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
D/Bluetoothsap( 2827): onBluetoothStateChange: up=false
D/Bluetoothsap( 2827): Unbinding service...
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
D/BluetoothA2dp( 4161): onBluetoothStateChange: up=false
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
D/BluetoothPbap( 2827): onBluetoothStateChange: up=false
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
D/BluetoothMap( 2827): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 2827): onBluetoothStateChange: up=false
D/Bluetoothsap( 2827): onBluetoothStateChange: up=false
D/Bluetoothsap( 2827): Unbinding service...
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
D/BluetoothA2dp( 2418): onBluetoothStateChange: up=false
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
D/NearbySettings( 2827): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/BluetoothA2dp( 2827): onBluetoothStateChange: up=false
V/NearbySettings( 2827): DMSUtil.isNetworkConnected - flag-null, state-null
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
I/NearbySettings( 2827): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
W/InputMethodManagerService( 2418): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2418): [BT Setting State] State =10
,I/InputMethodManagerService( 2418): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/PhoneApp( 2749): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 10
I/NearbySettings( 2827): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 2827): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2827): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 2827): MountReceiver.mPrefHandler - 7002
I/SamsungIME( 2997): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
I/QuickConnect[1.1][2] ( 5231): BluetoothHelper.ACTION_STATE_CHANGED - STATE_OFF
V/BluetoothEventManager( 2827): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTethering( 2418): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering( 2418): attempted to stop reverse tether with nothing tethered
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
V/NetworkStats( 2418): updateIfacesLocked()
,V/NetworkStats( 2418): performPollLocked(flags=0x1)
I/wpa_supplicant( 3966): p2p0: CTRL-EVENT-TERMINATING 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
D/Tethering( 2418): interfaceLinkStateChanged p2p0, true
D/Tethering( 2418): interfaceStatusChanged p2p0, true
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
D/Tethering( 2418): interfaceLinkStateChanged p2p0, false
D/Tethering( 2418): interfaceStatusChanged p2p0, false
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,V/NetworkStats( 2418): advisePersistThreshold() given 9223372036854775, clamped to 2097152
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/wpa_supplicant( 3966): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/wpa_supplicant( 3966): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
D/Tethering( 2418): interfaceStatusChanged wlan0, true
D/NearbySettings( 2827): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
D/Tethering( 2418): interfaceStatusChanged wlan0, true
V/NearbySettings( 2827): DMSUtil.isNetworkConnected - flag-null, state-null
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/NearbySettings( 2827): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
I/NearbySettings( 2827): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 2827): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2827): MountReceiver.onReceive - Set preference state off
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,V/NetworkStats( 2418): performPollLocked() took 45ms
V/NearbySettings( 2827): MountReceiver.mPrefHandler - 7002
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/FileShare-Server( 4953): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,D/FileShare-Server( 4953): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() DISCONNECTED
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,D/NearbySettings( 2827): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2827): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 2827): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/NearbySettings( 2827): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 2827): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2827): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2827): MountReceiver.mPrefHandler - 7002
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,I/knox    ( 5172): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
D/Tethering( 2418): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2418): interfaceStatusChanged wlan0, true
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,W/ContextImpl( 5172): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/knox    ( 5172): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
D/knox    ( 5172): KNOXAgentService : onCreate()
D/knox    ( 5172): KNOXAgentService : set alarms for deniallog and usage data upload
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
D/knox    ( 5172): KNOXAgentService. startJobThread() start
D/knox    ( 5172): KNOXAgentService. JobThread()
D/knox    ( 5172): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 5172): KNOXAgentService. startJobThread() wait
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
D/knox    ( 5172): KNOXAgentService : onDestroy().
,W/ContextImpl( 2827): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/knox    ( 5172): ModuleBase.cancelAllAlarmManageModule()
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
D/DockEventReceiver( 2827): finishStartingService: stopping service
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
D/BluetoothNotiBroadcastReceiver( 2827): onReceive
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,D/AuthorizationBluetoothService( 2843): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
I/wpa_supplicant( 3966): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering( 2418): interfaceLinkStateChanged wlan0, false
D/Tethering( 2418): interfaceStatusChanged wlan0, false
D/Tethering( 2418): InitialState.processMessage what=4
,E/Tethering( 2418): No numeric data
,I/ConnectivityService( 2418): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering( 2418): sendTetherStateChangedBroadcast 0, 0, 0
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,V/NetworkStats( 2418): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
D/WifiStateMachine( 2418): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/WifiManager( 7308): packageName : com.test.thalitest
,D/STATUSBAR-NetworkController( 2577): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,W/Settings( 5503): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,I/jxcore-log( 7308): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 7308): 
,V/NetworkStats( 2418): performPollLocked() took 28ms
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2418): currentTimeMillis() cache hit
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,W/Settings( 2730): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/knox    ( 5172): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,W/ContextImpl( 5172): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
I/knox    ( 5172): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
D/knox    ( 5172): KNOXAgentService : onCreate()
D/knox    ( 5172): KNOXAgentService : set alarms for deniallog and usage data upload
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
D/knox    ( 5172): KNOXAgentService. startJobThread() start
D/knox    ( 5172): KNOXAgentService. JobThread()
D/knox    ( 5172): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 5172): KNOXAgentService. startJobThread() wait
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
D/knox    ( 5172): KNOXAgentService : onDestroy().
,D/knox    ( 5172): ModuleBase.cancelAllAlarmManageModule()
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.,
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
D/WifiStateMachine( 2418): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,D/Tethering( 2418): Tethering got CONNECTIVITY_ACTION
I/ApplicationPolicy( 2418): updateDataUsageMap
,D/Tethering( 2418): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2418): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
D/ConnectivityService( 2418): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2577): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2577): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2577): updateDataNetType()
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,D/STATUSBAR-NetworkController( 2577): NoService, mRoamingIconId = 0
I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/DBG_DM  ( 4837): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
I/PCWCLIENTTRACE_PushUtil( 6701): SPPPushClient is installed : true
,I/WifiManager( 7308): packageName : com.test.thalitest
I/PCWCLIENTTRACE_PushUtil( 6701): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6701): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6701): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6701): noConnectivity : true
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,D/libgps  ( 2418): agps_ril_update_network_state: Waiting for IPC connection...
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
I/jxcore-log( 7308): The client has disconnected!
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Turning radios to false
I/jxcore-log( 7308): 
,E/BluetoothManagerService( 2418): Bluetooth is already disabled. DO NOT disable again.
,I/jxcore-log( 7308): toggleBluetooth - 
I/jxcore-log( 7308): 
,I/WifiManager( 7308): packageName : com.test.thalitest
,I/WifiManager( 7308): setWifiEnabled : false
,I/WifiService( 2418): setWifiEnabled: false pid=7308, uid=10467
,I/jxcore-log( 7308): toggleWiFi
I/jxcore-log( 7308): 
,I/chromium( 7308): [INFO:CONSOLE(63)] "logCallback 0 isOK: false : Coordinator server got disconnected", source: file:///android_asset/www/js/thali_main.js (63)
,D/dalvikvm( 5843): GC_CONCURRENT freed 2478K, 27% free 10162K/13780K, paused 12ms+4ms, total 97ms
,D/dalvikvm( 5843): WAIT_FOR_CONCURRENT_GC blocked 66ms
,I/KLMS-2.3.201 : ( 7419): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7419): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1448284659133
,I/KLMS-2.3.201 : ( 7419): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/SO_AGENT( 7431): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7431): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5902): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5902): [BDLM] already registered in spp
,I/SA      ( 5902): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5902): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5902): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5902): [OR] == isSIMCardReady false ==
I/SA      ( 5902): [SCU] == networkStateCheck == false
,I/SA      ( 5902): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 2749): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2749): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7443): Other Intent
,D/com.samsung.app( 7456): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7456): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5971): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5971): getCountryCode(): countryCode = PL
,D/Headlines( 5971): Breath.onCreate
,D/Headlines( 5971): Breath timer started. interval : 30000
,V/AlarmManager( 2418): waitForAlarm result :8
D/Headlines( 5971): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5971): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5971): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5971): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5971): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5971): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5971): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 6035): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/QuickConnect[1.1][2] ( 5231): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5231): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5231): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@424b07a0
,I/iu.UploadsManager( 6035): num queued entries: 0
,I/iu.UploadsManager( 6035): num updated entries: 0
,I/iu.SyncManager( 6035): NEXT; no task
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,D/RCPManagerService( 2418): exchangeData() failure , invalid userId
,I/Babel   ( 5503): connection state changed from CONNECTED to DISCONNECTED
,I/iu.Environment( 3272): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 3272): num queued entries: 0
,I/iu.UploadsManager( 3272): num updated entries: 0
,I/iu.SyncManager( 3272): NEXT; no task
,E/SPPClientService( 5638): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5638): [SystemStateMoniter] Current Time : 1923987
,E/SPPClientService( 5638): [SystemStateMoniter] No Connect : true
,D/Headlines( 5971): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5971): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5971): Breath 188 latestRequest time : 1448284659264 current time : 1448284659452
,E/SPPClientService( 5638): [[SystemStateMonitorService]] No Active Internet
,E/SPPClientService( 5638): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5638): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5638): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/libgps  ( 2418): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2418): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2418): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2418): agps_ril_update_network_availability: Waiting for IPC connection...
,I/jxcore-log( 7308): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,D/libgps  ( 2418): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2418): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2418): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/BatteryService( 2418): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2418): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2418): mCoverManager.getCoverState() : true
,D/BatteryService( 2418): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2577): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 7308): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
,I/jxcore-log( 7308): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 
I/jxcore-log( 7308): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7308): 

```
