#### Test 561510933390750_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
E/Watchdog( 2421): !@Sync 8
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
V/ApplicationPolicy( 2421): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2421): mDVFSHelper.acquire()
I/SELinux ( 7153): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7153):  
D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7125): Shutting down VM
D/dalvikvm( 7125): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 7153): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7153):  
I/SELinux ( 7153):  
I/SELinux ( 7153): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7153): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7153): >>>>> Normal User
E/dalvikvm( 7153): >>>>> com.test.thalitest [ userId:0 | appId:10628 ]
E/SELinux ( 7153): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7153): in addTimaSignatureService
D/TimaKeyStoreProvider( 7153): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7153): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4166): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4166): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1922): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1922): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7153): GC_CONCURRENT freed 3010K, 31% free 9561K/13728K, paused 2ms+1ms, total 18ms
D/dalvikvm( 7153): WAIT_FOR_CONCURRENT_GC blocked 17ms
V/WebViewChromium( 7153): Binding Chromium to the background looper Looper (main, tid 1) {42276258}
I/chromium( 7153): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7153): Initializing chromium process, renderers=0
W/chromium( 7153): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7153): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7153): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7153): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7153): Mali API Version : 401
,I/Mali    ( 7153): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7153): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 7153): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7153): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7153): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7153): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7153): VFY: replacing opcode 0x6e at 0x0008
,D/StatusBarManagerService( 2421): tr p:7153,o:f
D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,W/dalvikvm( 7153): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 7153): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7153): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7153): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7153): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7153): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7153): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7153): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 7153): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7153): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7153): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7153): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7153): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2421): semi p:7153,o:f
,I/SurfaceFlinger( 1922): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7153): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7153): Enabling debug mode 0
,W/AwContents( 7153): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7153): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2421): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/JsMessageQueue( 7153): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7153): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42276fe0
,D/dalvikvm( 7153): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42276fe0
D/jxcore_app_log( 7153): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2031465376
,D/JX-Cordova( 7153): jxcore cordova android initializing
,D/dalvikvm( 7153): GC_CONCURRENT freed 1293K, 18% free 11341K/13788K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 7153): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0
,D/dalvikvm( 7153): GC_CONCURRENT freed 1719K, 17% free 15136K/18036K, paused 3ms+3ms, total 41ms
,D/dalvikvm( 7153): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 7153): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@8
,D/AmoledAdjustTimer( 2421): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4
,D/dalvikvm( 7153): GC_FOR_ALLOC freed 5743K, 30% free 16766K/23704K, paused 53ms, total 53ms
,D/dalvikvm( 7153): GC_CONCURRENT freed 6778K, 31% free 18148K/26116K, paused 2ms+8ms, total 57ms
,D/dalvikvm( 7153): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/dalvikvm( 7153): WAIT_FOR_CONCURRENT_GC blocked 38ms
,D/dalvikvm( 7153): GC_FOR_ALLOC freed 1149K, 32% free 17860K/26116K, paused 59ms, total 59ms
,I/dalvikvm-heap( 7153): Grow heap (frag case) to 22.084MB for 3688532-byte allocation
,D/dalvikvm( 7153): GC_FOR_ALLOC freed 2421K, 36% free 19040K/29720K, paused 57ms, total 57ms
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
,I/WifiManager( 7153): packageName : com.test.thalitest,
I/WifiManager( 7153): setWifiEnabled : true
,I/WifiService( 2421): setWifiEnabled: true pid=7153, uid=10628,
,W/ActivityManager( 2421): Permission Denial: getCurrentUser() from pid=7153, uid=10628 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2421): Failed getting userId using ActivityManagerNative
W/WifiService( 2421): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7153, uid=10628 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2421): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2421): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2421): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2421): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2421): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2421): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2421): disconnect: pid=7153, uid=10628
I/jxcore-log( 7153): Radios toggled
I/jxcore-log( 7153): 
I/jxcore-log( 7153): My device name is: samsung-SM-G800F
I/jxcore-log( 7153): 
I/wpa_supplicant( 3969): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3969): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3969): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2421): interfaceStatusChanged wlan0, true
D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2421): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3969): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3969): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3969): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3969): First Scan Start
W/Settings( 2421): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/wpa_supplicant( 3969): Scan requested (ret=0) - scan timeout 30 seconds
,I/WifiStateMachine( 2421): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2421): InactiveState{ what=143375 }
D/WifiP2pService( 2421): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/wpa_supplicant( 3969): wlan0: Setting scan request: 0 sec 0 usec
I/WifiTrafficPoller( 2421): evaluateTrafficStatsPolling
,I/wpa_supplicant( 3969): Skip scan - already scanning
D/WifiP2pService( 2421): InactiveState{ what=143375 }
D/ConnectivityService( 2421): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2421): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2421): net.tcp.usercfg.default not found in system default properties
D/WifiP2pService( 2421): P2pEnabledState{ what=143375 }
E/ConnectivityService( 2421): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2421): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2421): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2421): Attempting to switch to mobile
,D/ConnectivityService( 2421): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
I/SELinux ( 7200): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7200):  
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2421): evaluateTrafficStatsPolling
,E/WifiStateMachine( 2421): Error! unhandled message{ when=-41ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2421): Error! unhandled message{ when=-46ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1
,E/WifiStateMachine( 2421): Error! unhandled message{ when=-10ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1916): RTNETLINK answers: No such process
I/SELinux ( 7200): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7200):  
I/SELinux ( 7200):  
,I/SELinux ( 7200): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
E/SELinux ( 7200): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7200): >>>>> Normal User
,E/dalvikvm( 7200): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7200): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,W/NetworkManagementService( 2421): route cmd failed: 
W/NetworkManagementService( 2421): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2421): '
W/NetworkManagementService( 2421): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2421): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2421): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2421): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2421): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2421): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2421): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2421): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2421): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2421): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2421): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1
,D/TimaKeyStoreProvider( 7200): in addTimaSignatureService
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 7200): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7200): Added TimaKesytore provider
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/NetUtils( 2421): android_net_utils_resetConnections in env=0x7b9f1d58 clazz=0x60f00001 iface=wlan0 mask=0x3
D/ConnectivityService( 2421): resetConnections(wlan0, 3)
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 7200): GC_CONCURRENT freed 2990K, 31% free 9582K/13732K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 7200): WAIT_FOR_CONCURRENT_GC blocked 18ms
,V/NativeCrypto( 2852): Read error: ssl=0x746b71f8: I/O error during system call, Connection timed out
,V/NativeCrypto( 2852): SSL shutdown failed: ssl=0x746b71f8: I/O error during system call, Broken pipe
,E/SPPClientService( 5594): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5594): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5594): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5594): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5594): [b] ResponseMap empty
,I/System.out( 7200): Inside WakeupProvider
,I/System.out( 7200): Inside onCreate() of WakeupTriggerProvide
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
V/NetworkStats( 2421): updateIfacesLocked()
D/ConnectivityService( 2421): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
V/NetworkStats( 2421): performPollLocked(flags=0x1)
V/NetworkStats( 2421): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit,
V/NetworkStats( 2421): performPollLocked() took 24ms
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit,
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,I/VlingoApplication( 7200): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7200): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7200): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility,
,D/NearbySettings( 4751): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
V/NearbySettings( 4751): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4751): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4751): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4751): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4751): MountReceiver.onReceive - Set preference state off,
,I/ActivityManager( 2421): Killing 6228:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
V/NearbySettings( 4751): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 7200): initQueue()
,D/NearbySettings( 4751): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4751): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4751): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4751): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4751): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 4751): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4751): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2421): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2421): MasterInitialState.processMessage what=3
,I/ApplicationPolicy( 2421): updateDataUsageMap
,D/CaptivePortalTracker( 2421): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2421): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6638): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6638): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6638): getPushTypeList : [SPP, GCM]
I/DBG_DM  ( 4781): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6638): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6638): noConnectivity : true
,I/SELinux ( 7229): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7229):  
,D/libgps  ( 2421): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7229): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7229):  
I/SELinux ( 7229):  
,I/SELinux ( 7229): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7229): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7229): >>>>> Normal User
,E/dalvikvm( 7229): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7229): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/wpa_supplicant( 3969): nl80211: Received scan results (6 BSSes)
,I/wpa_supplicant( 3969): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3969): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3969): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2421): interfaceStatusChanged wlan0, true
,D/TimaKeyStoreProvider( 7229): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7229): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7229): Added TimaKesytore provider
,D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
D/Tethering( 2421): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3969): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
D/Tethering( 2421): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3969): Associated with C0.AA.48
I/wpa_supplicant( 3969): freq(2412) increment count 2
I/wpa_supplicant( 3969): meet head of list.
D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
D/Tethering( 2421): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3969): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/dalvikvm( 7229): GC_CONCURRENT freed 3001K, 31% free 9570K/13732K, paused 4ms+2ms, total 50ms
D/dalvikvm( 7229): WAIT_FOR_CONCURRENT_GC blocked 44ms
I/wpa_supplicant( 3969): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3969): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3969): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3969): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/WifiNative( 2421): callSECApiVoid - ID [50]
D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
D/Tethering( 2421): interfaceStatusChanged wlan0, true
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/ActivityManager( 2421): Killing 6297:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
D/WifiP2pService( 2421): InactiveState{ what=143375 }
D/WifiP2pService( 2421): P2pEnabledState{ what=143375 }
I/SELinux ( 7243): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7243):  
D/dalvikvm( 1923): WAIT_FOR_CONCURRENT_GC blocked 1ms
D/dalvikvm( 1923): GC_EXPLICIT freed 43K, 12% free 9505K/10708K, paused 4ms+4ms, total 45ms
I/SELinux ( 7243): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7243):  
I/SELinux ( 7243):  
I/SELinux ( 7243): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7243): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7243): >>>>> Normal User
E/dalvikvm( 7243): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
E/SELinux ( 7243): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 12% free 9505K/10708K, paused 3ms+4ms, total 35ms
D/TimaKeyStoreProvider( 7243): in addTimaSignatureService
D/TimaKeyStoreProvider( 7243): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7243): Added TimaKesytore provider
D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 12% free 9505K/10708K, paused 3ms+4ms, total 34ms
D/dalvikvm( 7243): GC_CONCURRENT freed 2998K, 31% free 9575K/13728K, paused 16ms+2ms, total 46ms
D/dalvikvm( 7243): WAIT_FOR_CONCURRENT_GC blocked 28ms
I/dhcpcd  ( 7255): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7255): bssid match
I/ActivityManager( 2421): Killing 6350:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
I/SELinux ( 7262): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7262):  
I/SELinux ( 7262): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7262):  
I/SELinux ( 7262):  
I/SELinux ( 7262): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7262): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7262): >>>>> Normal User
E/dalvikvm( 7262): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
E/SELinux ( 7262): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 7262): in addTimaSignatureService
D/TimaKeyStoreProvider( 7262): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7262): Added TimaKesytore provider
D/dalvikvm( 7262): GC_CONCURRENT freed 3014K, 31% free 9561K/13732K, paused 3ms+2ms, total 26ms
D/dalvikvm( 7262): WAIT_FOR_CONCURRENT_GC blocked 22ms
D/KLMS-2.3.201 : ( 7262): KLMSValidator() : checkQATesting()
I/KLMS-2.3.201 : ( 7262): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453032999764
D/libgps  ( 2421): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2421): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2421): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
D/libgps  ( 2421): agps_ril_update_network_availability: Waiting for IPC connection...
I/KLMS-2.3.201 : ( 7262): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
I/ActivityManager( 2421): Killing 6365:com.sec.android.app.voicenote/1000 (adj 15): empty #43
I/SELinux ( 7274): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7274):  
,I/SELinux ( 7274): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7274):  
I/SELinux ( 7274):  
,I/SELinux ( 7274): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7274): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7274): >>>>> Normal User
,E/dalvikvm( 7274): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7274): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7274): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7274): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7274): Added TimaKesytore provider
,D/dalvikvm( 7274): GC_CONCURRENT freed 2993K, 31% free 9568K/13724K, paused 2ms+1ms, total 31ms
,D/dalvikvm( 7274): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/SO_AGENT( 7274): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7274): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5860): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5860): [BDLM] already registered in spp
,I/SA      ( 5860): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5860): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5860): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5860): [OR] == isSIMCardReady false ==
I/SA      ( 5860): [SCU] == networkStateCheck == false
,I/SA      ( 5860): [OR] onReceive END
I/ActivityManager( 2421): Killing 6386:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): Phone number locator feature is dsiabled
,I/SELinux ( 7286): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7286):  
,I/SELinux ( 7286): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7286):  
I/SELinux ( 7286):  
,I/SELinux ( 7286): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7286): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7286): >>>>> Normal User
,E/dalvikvm( 7286): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ],
,E/SELinux ( 7286): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7286): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7286): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7286): Added TimaKesytore provider,
,D/dalvikvm( 7286): GC_CONCURRENT freed 2998K, 31% free 9573K/13732K, paused 3ms+2ms, total 20ms,
,D/dalvikvm( 7286): WAIT_FOR_CONCURRENT_GC blocked 12ms,
,I/sCloudBackupApp( 7286): sCloudBackupApp Version Info : 3.7.3.KK_APP,
,I/SCloudBackupReceiver( 7286): Other Intent,
I/ActivityManager( 2421): Killing 6439:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,I/SELinux ( 7299): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7299):  
,I/SELinux ( 7299): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7299):  
I/SELinux ( 7299):  
I/SELinux ( 7299): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7299): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7299): >>>>> Normal User
E/dalvikvm( 7299): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
E/SELinux ( 7299): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 7299): in addTimaSignatureService
D/TimaKeyStoreProvider( 7299): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7299): Added TimaKesytore provider
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4004): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4004): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
,D/dalvikvm( 7299): GC_CONCURRENT freed 2995K, 31% free 9580K/13732K, paused 3ms+1ms, total 22ms
,D/dalvikvm( 7299): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/com.samsung.app( 7299): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7299): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7299): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7299): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7299): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7299): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5391): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7299): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5391): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7299): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5391): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7299): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7299): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2421): Killing 5644:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/Headlines( 5926): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE,
,D/HeadlinesChannelUtil( 5926): getCountryCode(): countryCode = PL
,D/Headlines( 5926): Breath.onCreate
,D/Headlines( 5926): Breath timer started. interval : 30000
,I/SELinux ( 7316): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7316):  
,D/Headlines( 5926): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5926): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5926): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5926): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5926): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5926): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5926): requestUpdateNewsWelcomeCard !!! no welcome card
V/AlarmManager( 2421): waitForAlarm result :8
,I/SELinux ( 7316): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7316):  
I/SELinux ( 7316):  
,I/SELinux ( 7316): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7316): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7316): >>>>> Normal User
,E/dalvikvm( 7316): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7316): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7316): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7316): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7316): Added TimaKesytore provider
,D/dalvikvm( 7316): GC_CONCURRENT freed 2999K, 31% free 9574K/13732K, paused 4ms+2ms, total 26ms
,D/dalvikvm( 7316): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/libgps  ( 2421): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2421): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2421): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,V/WebViewChromium( 7316): Binding Chromium to the background looper Looper (main, tid 1) {42273158}
,I/chromium( 7316): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7316): Initializing chromium process, renderers=0
,D/WifiP2pService( 2421): InactiveState{ what=143375 }
,D/WifiP2pService( 2421): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/WifiStateMachine( 2421): VerifyingLinkState enter
,D/libEGL  ( 7316): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7316): loaded /system/lib/egl/libGLESv1_CM_mali.so
,W/chromium( 7316): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/libEGL  ( 7316): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7316): Mali API Version : 401
,I/Mali    ( 7316): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/WifiStateMachine( 2421): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2421): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2421): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2421): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2421): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2421): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2421): evaluateTrafficStatsPolling
D/ConnectivityService( 2421): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2421): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2421): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/ConnectivityService( 2421): handleConnectivityChange: setting default proxy info 
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,W/GAV2    ( 7316): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7316): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,V/NetworkStats( 2421): updateIfacesLocked()
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,V/NetworkStats( 2421): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
V/NetworkStats( 2421): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
V/NetworkStats( 2421): performPollLocked() took 16ms
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,I/NSApplication( 7316): Starting up...
,I/iu.Environment( 5993): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5192): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5192): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5192): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422842e0
,I/SELinux ( 7386): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7386):  
,I/SELinux ( 7386): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7386):  
I/SELinux ( 7386):  
,I/SELinux ( 7386): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7386): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7386): >>>>> Normal User
,E/dalvikvm( 7386): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7386): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7386): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7386): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7386): Added TimaKesytore provider
,D/dalvikvm( 7386): GC_CONCURRENT freed 2985K, 31% free 9584K/13724K, paused 4ms+1ms, total 21ms
,D/dalvikvm( 7386): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 7386): WAIT_FOR_CONCURRENT_GC blocked 1ms
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,I/SELinux ( 7405): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7405):  
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,I/ActivityManager( 2421): Killing 6332:com.sec.phone/1001 (adj 15): empty #43
,I/SELinux ( 7405): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7405):  
I/SELinux ( 7405):  
,I/SELinux ( 7405): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7405): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7405): >>>>> Normal User
,E/dalvikvm( 7405): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7405): [DEBUG] seapp_context_lookup: seinfoCategory = release
,W/ActivityManager( 2421): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/Tethering( 2421): Tethering got CONNECTIVITY_ACTION
D/Tethering( 2421): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 2421): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
,D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,D/TimaKeyStoreProvider( 7405): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7405): Cannot add TimaSignature Service, License check Failed
,I/DBG_DM  ( 4781): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/ActivityThread( 7405): Added TimaKesytore provider
,I/SELinux ( 7418): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7418):  
,I/ActivityManager( 2421): Killing 6402:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/SELinux ( 7418): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7418):  
I/SELinux ( 7418):  
,I/SELinux ( 7418): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7418): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7418): >>>>> Normal User
,E/dalvikvm( 7418): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7418): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7418): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7418): Cannot add TimaSignature Service, License check Failed
,D/libgps  ( 2421): agps_ril_update_network_state: Waiting for IPC connection...
,D/ActivityThread( 7418): Added TimaKesytore provider
,D/dalvikvm( 7405): GC_CONCURRENT freed 3013K, 31% free 9561K/13732K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7405): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/BadgeProvider( 7405): onCreate
,D/BadgeProvider( 7405): DatabaseHelper
,D/dalvikvm( 7418): GC_CONCURRENT freed 3000K, 31% free 9572K/13732K, paused 3ms+1ms, total 30ms
D/dalvikvm( 7418): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/BadgeProvider( 7405): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7405): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7405): sendNotify, [notify] : null
D/BadgeProvider( 7405): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7405): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7405): update, [UpdateCount] : 1
,D/Launcher.Model( 2778): reloadBadges entered.
,D/hcjo    ( 6016): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6016): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6016): exit::IDLE
,D/InitializeManagerStateMachine( 6016): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 6016): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6016): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6016): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6016): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6016): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6016): entry::SUCCESS
,D/hcjo    ( 6016): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6016): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6016): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6016): exit::SUCCESS
,D/InitializeManagerStateMachine( 6016): entry::IDLE
,E/SPPClientService( 5594): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5594): [SystemStateMoniter] Current Time : 268425
,E/SPPClientService( 5594): [SystemStateMoniter] No Connect : true
,D/NearbySettings( 4751): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4751): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4751): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 4751): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4751): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4751): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5594): [[SystemStateMonitorService]] No Active Internet
,D/Headlines( 5926): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5926): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5926): Breath 1442 latestRequest time : 1453033000590 current time : 1453033002032
,D/NearbySettings( 4751): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4751): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5594): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5594): [a] [ConnectionManager] Connection is already disconnected.
I/ActivityManager( 2421): Killing 6044:com.android.calendar/u0a144 (adj 15): empty #43
,D/NearbySettings( 4751): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4751): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4751): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,E/SPPClientService( 5594): [[PushClientService]] <<--- deInitPushClientService  END  --->>
I/NearbySettings( 4751): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4751): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4751): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5594): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/SurfaceFlinger( 1922): id=20 createSurf (1x1),1 flag=4, Uoast
,E/SPPClientService( 5594): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
D/PowerManagerService( 2421): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2421
,D/NearbySettings( 4751): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4751): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5594): [a] [ConnectionManager] Connection is already disconnected.
,I/PCWCLIENTTRACE_PushUtil( 6638): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6638): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6638): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6638): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5594): [g] getNetMCC return empty string
,I/KLMS-2.3.201 : ( 7262): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7262): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453033002362
,I/KLMS-2.3.201 : ( 7262): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7274): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3467): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,I/SO_AGENT( 7274): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/GalaxyFinderApplication( 3467): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3467): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3467): [Slink platform] The state of Slink geocode service is true
,I/SELinux ( 7441): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7441):  
,I/GallerySearchProvider( 3595): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7441): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7441):  
I/SELinux ( 7441):  
,I/SELinux ( 7441): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7441): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7441): >>>>> Normal User
,E/dalvikvm( 7441): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7441): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7441): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7441): Cannot add TimaSignature Service, License check Failed
I/SA      ( 5860): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5860): [BDLM] already registered in spp
,D/ActivityThread( 7441): Added TimaKesytore provider
I/SA      ( 5860): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5860): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5860): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5860): [OR] == isSIMCardReady false ==
,I/SA      ( 5860): [SCU] == networkStateCheck == true
,I/SA      ( 5860): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5860): isChinaCountryCode : false
,I/SA      ( 5860): [OR] == networkStateCheck true ==
,I/SA      ( 5860): [OR] GetMyCountryZoneTask
,I/SA      ( 5860): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): Phone number locator feature is dsiabled
,D/dalvikvm( 7441): GC_CONCURRENT freed 2990K, 31% free 9582K/13732K, paused 7ms+1ms, total 26ms
,D/dalvikvm( 7441): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/SCloudBackupReceiver( 7286): Other Intent
,I/SA      ( 5860): [SRS] prepareGetMyCountryZone
,I/SA      ( 5860): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,D/dalvikvm( 2421): GC_EXPLICIT freed 4048K, 74% free 25592K/98056K, paused 7ms+21ms, total 276ms
,I/SA      ( 5860): [SSP] query invoked
,D/com.samsung.app( 7299): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7299): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/SA      ( 5860): [TPMU] GetMccFromDB : null
I/SA      ( 5860): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5860): [TPM] isNoProxy(default) : true
,D/Headlines( 5926): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5926): getCountryCode(): countryCode = PL
,I/SA      ( 5860): [RC New] Execute method=[GET] start
,D/Headlines( 5926): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5926): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5926): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5926): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5926): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5926): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5926): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7459): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7459):  
,I/System.out( 7243): Thread-639(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/libgps  ( 2421): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2421): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2421): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2421): agps_ril_update_network_availability: Waiting for IPC connection...
I/System.out( 7243): Thread-639(ApacheHTTPLog):isShipBuild true
,I/System.out( 7243): Thread-639(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/iu.Environment( 5993): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5192): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5192): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5192): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422842e0
I/SELinux ( 7459): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7459):  
I/SELinux ( 7459):  
,I/SELinux ( 7459): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7459): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7459): >>>>> Normal User
,E/dalvikvm( 7459): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7459): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 7459): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7459): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7459): Added TimaKesytore provider
,D/PackageManager( 2421): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/hcjo    ( 6016): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6016): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6016): exit::IDLE
,D/InitializeManagerStateMachine( 6016): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 6016): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6016): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6016): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6016): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6016): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6016): entry::SUCCESS
,D/hcjo    ( 6016): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6016): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6016): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6016): exit::SUCCESS
D/InitializeManagerStateMachine( 6016): entry::IDLE
D/dalvikvm( 7459): GC_CONCURRENT freed 3006K, 31% free 9562K/13728K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 7459): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/System.out( 7243): AsyncTask #1 calls detatch()
,V/KVNProvider( 7459): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7459): getFindoCursor query string : 
,V/KVNProvider( 7459): getTagSearchCursor() tagSearchCursor count : 0
,W/System.err( 7243): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7243): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7243): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7243): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7243): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7243): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 7243): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7243): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7243): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7243): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 7243): Caused by: java.lang.NullPointerException
W/System.err( 7243): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7243): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7243): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7243): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7243): 	... 8 more
E/SPPClientService( 5594): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5594): [SystemStateMoniter] Current Time : 269512
,E/SPPClientService( 5594): [SystemStateMoniter] No Connect : false
,I/ActivityManager( 2421): Killing 6215:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/dalvikvm( 5594): GC_CONCURRENT freed 1990K, 24% free 10469K/13712K, paused 4ms+11ms, total 51ms
,W/WifiP2pStateTracker( 2421): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2421): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2421):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2421): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2421): updateSourceRoutes : no source routing conditions
,I/SA      ( 5860): [RC New] [v2liruge] api execute + 789
,I/SA      ( 5860): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5860): AsyncTask #2 calls detatch()
,I/SA      ( 5860): [TPMU] getNetworkMcc : 
,I/SA      ( 5860): [SCU] saveMccToPreferece Start
I/SA      ( 5860): [SCU] RegionMCC : 260
,I/SA      ( 5860): [SSP] query invoked
,I/SA      ( 5860): [TPMU] GetMccFromDB : null
,I/SA      ( 5860): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5860): [SCU] saveMccToPreferece End
,I/SA      ( 5860): [RC New] executeRequest [v2liruge] end. 819
I/SA      ( 5860): [RC New] Execute end
,I/SA      ( 5860): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5860): [OR] GetMyCountryZoneTask Success
,D/libgps  ( 2421): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2421): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2421): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 350, Delta = 20
,E/SPPClientService( 5594): [b] __InitReply__
,E/WifiStateMachine( 2421): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/AmoledAdjustTimer( 2421): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4
,I/jxcore-log( 7153): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7153): 
,I/jxcore-log( 7153): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7153): 
,I/jxcore-log( 7153): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7153): 
,I/jxcore-log( 7153): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7153): 
,I/jxcore-log( 7153): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7153): 
,I/jxcore-log( 7153): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7153): 
,I/SurfaceFlinger( 1922): id=20 Removed Uoast (10/11)
,I/SurfaceFlinger( 1922): id=20 Removed Uoast (-2/11)
I/ActivityManager( 2421): Killing 6250:com.google.android.music:main/u0a125 (adj 15): empty #43
D/PowerManagerService( 2421): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2421) eventTime = 272081
D/PowerManagerService( 2421): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2421 (0x0)
D/PowerManagerService( 2421): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2421, ws=WorkSource{1000}) (elapsedTime=3470)
,I/jxcore-log( 7153): Test app app.js loaded
I/jxcore-log( 7153): 
,I/chromium( 7153): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 7153): --= Surplus to requirements =--
I/jxcore-log( 7153): 
,I/jxcore-log( 7153): ****TEST TOOK:  ms ****
I/jxcore-log( 7153): 
,I/jxcore-log( 7153): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7153): 
,I/GAV2    ( 7316): Thread[GAThread,5,main]: No campaign data found.
,D/AndroidRuntime( 7486): 
D/AndroidRuntime( 7486): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7486): CheckJNI is OFF
,D/AndroidRuntime( 7486): setted country_code = Poland
,D/AndroidRuntime( 7486): setted countryiso_code = PL
,D/AndroidRuntime( 7486): setted sales_code = PLS
D/AndroidRuntime( 7486): readGMSProperty: start
D/AndroidRuntime( 7486): readGMSProperty: already setted!!
D/AndroidRuntime( 7486): readGMSProperty: end
,D/AndroidRuntime( 7486): addProductProperty: start
,D/dalvikvm( 7486): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 7486): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 7486): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7486): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 7486): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,E/memtrack( 7486): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 7486): failed to load memtrack module: -2
,D/dalvikvm( 7486): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,D/AndroidRuntime( 7486): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 2421): START PACKAGE DELETE: observer{1125021416}
D/PackageManager( 2421): pkg{<packageName>}
D/PackageManager( 2421): user{0}
,D/PackageManager( 2421): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2421): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2421): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService( 2421): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2421): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManager( 2421): !@killApplicatoin: 10628, uninstall pkg
,I/ActivityManager( 2421): Killing 7153:com.test.thalitest/u0a628 (adj 0): stop com.test.thalitest
,D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2421): mDVFSHelper.acquire()
,I/SurfaceFlinger( 1922): id=19 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1922): id=19 Removed NainActivit (-2/10)
,I/WindowState( 2421): WIN DEATH: Window{4302c9b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1922): id=19 Removed NainActivit (-2/10)
D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 2421): Skipping PackageSetting{4298e5f8 com.example.hello/10614} due to missing metadata
,D/PackageManager( 2421): setPackageStoppedState - Execution time: 114 ms
D/PackageManager( 2421): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10628, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6638): mConnectivityHandler : connected
,D/dalvikvm( 6797): GC_EXPLICIT freed 477K, 29% free 9967K/13948K, paused 4ms+4ms, total 40ms
,D/dalvikvm( 6480): GC_EXPLICIT freed 2470K, 28% free 9887K/13728K, paused 3ms+4ms, total 55ms
,I/DBG_DM  ( 4781): [3.19.140541][Line:408][onResume] 
D/PackageManager( 2421): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10628, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
W/PCWCLIENTTRACE_AccountUtil( 6638): [hasSamungAccount] - No Samsung Account
I/DBG_DM  ( 4781): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
D/dalvikvm( 2958): GC_EXPLICIT freed 1469K, 27% free 10039K/13728K, paused 7ms+5ms, total 87ms
I/DBG_DM  ( 4781): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
I/FPMS_FingerprintManagerService( 2601): onReceive: android.intent.action.PACKAGE_REMOVED
E/SamsungIME( 2977): mOCRHelper is null
,D/QuickConnect[1.1][2] ( 5192): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "sms"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 7498): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7498):  
,I/DBG_DM  ( 4781): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4781): [3.19.140541][Line:418][onResume] Postpone Count : 29
,I/DBG_DM  ( 4781): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,W/GeofencerStateMachine( 2736): Ignoring removeGeofence because network location is disabled.
,I/SELinux ( 7498): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7498):  
I/SELinux ( 7498):  
,I/SELinux ( 7498): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7498): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7498): >>>>> Normal User
,E/dalvikvm( 7498): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 7498): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1923): GC_EXPLICIT freed 42K, 12% free 9505K/10708K, paused 3ms+8ms, total 37ms
,I/DBG_DM  ( 4781): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 12% free 9505K/10708K, paused 2ms+3ms, total 28ms
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "smsto"
,I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 7498): in addTimaSignatureService
D/RCPManagerService( 2421): PackageReceiver onReceive()
I/InputReader( 2421): Reconfiguring input devices.  changes=0x00000010
,I/HarmonyEASService( 2421): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/TimaKeyStoreProvider( 7498): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7498): Added TimaKesytore provider
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 12% free 9505K/10708K, paused 2ms+3ms, total 25ms
,D/dalvikvm( 3283): GC_EXPLICIT freed 2185K, 22% free 12431K/15772K, paused 16ms+123ms, total 269ms
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "mms"
,I/DBG_DM  ( 4781): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6638): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6638): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6638): GetString : secure API is not supported!!
,D/PackageManager( 2421): queryIntentReceivers - Execution time: 139 ms
I/PCWCLIENTTRACE_PushUtil( 6638): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6638): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6638): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6638): [ensureRegistration] - No Samsung account
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "mmsto"
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "sms"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4781): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "smsto"
,I/DBG_DM  ( 4781): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4781): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "mms"
,I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/DBG_DM  ( 4781): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4781): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
I/DBG_DM  ( 4781): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
I/DBG_DM  ( 4781): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
D/Activity( 4781): setTransGradationMode to true
,D/PhoneStatusBar( 2580): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/DBG_DM  ( 4781): [3.19.140541][Line:400][onPause] 
D/StatusBarManagerService( 2421): semi p:4781,o:t
,D/RegisteredServicesCache( 2758): empty dynamic service
,I/SurfaceFlinger( 1922): id=21 createSurf (720x1280),2 flag=404, YUIInstallC
D/dalvikvm( 7498): GC_CONCURRENT freed 3004K, 31% free 9568K/13728K, paused 3ms+2ms, total 42ms
,D/dalvikvm( 7498): WAIT_FOR_CONCURRENT_GC blocked 21ms
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "mmsto"
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
,D/elm:14132( 7498): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14132( 7498): ELMEngine.ELMEngine( context ).
,D/elm:14132( 7498): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 7498): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14132( 7498): ElmAgentService : onCreate()
W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 2421): Got RemoteException sending setActive(false) notification to pid 7153 uid 10628
,D/elm:14132( 7498): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 7498): MainReceiver.listeningToPackageRemoved()
,D/elm:14132( 7498): MDMBridge.getInstance()
,D/elm:14132( 7498): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 7498): MDMBridge.getAllLicenseInfoFromSDK()
,I/SELinux ( 7516): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7516):  
D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2421): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/EnterpriseDeviceManagerService( 2421): Package has changed for user 0
,I/SELinux ( 7516): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7516):  
I/SELinux ( 7516):  
,I/SELinux ( 7516): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7516): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7516): >>>>> Normal User
,E/dalvikvm( 7516): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,E/SELinux ( 7516): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7516): in addTimaSignatureService
D/BackupManagerService( 2421): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 2421): removePackageParticipantsLocked: uid=10628 #1
D/TimaKeyStoreProvider( 7516): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7516): Added TimaKesytore provider
,D/elm:14132( 7498): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:14132( 7498): ElmAgentService : onDestroy().
I/ActivityManager( 2421): Killing 6580:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/dalvikvm( 2758): GC_CONCURRENT freed 2336K, 26% free 10259K/13744K, paused 24ms+2ms, total 133ms
W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2421): sendNotification(2) - 4
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 7516): GC_CONCURRENT freed 2990K, 31% free 9581K/13732K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 7516): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 2421): GC_EXPLICIT freed 3267K, 75% free 25336K/98056K, paused 9ms+28ms, total 484ms
D/PackageManager( 2421): delete sourFile : 
,D/PackageManager( 2421): delete native library directory: 
D/PackageManager( 2421): return delete result to caller: 1125021416
,D/AndroidRuntime( 7486): Shutting down VM
,D/PackageManager( 2421): returnCode: 1
D/dalvikvm( 7486): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 0ms+1ms, total 3ms
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "sms"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "smsto"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "mms"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 7533): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7533):  
I/ActivityManager( 2421): Killing 6500:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "mmsto"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 7533): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7533):  
I/SELinux ( 7533):  
,I/SELinux ( 7533): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7533): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7533): >>>>> Normal User
,E/dalvikvm( 7533): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
,E/SELinux ( 7533): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7533): in addTimaSignatureService
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 7533): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7533): Added TimaKesytore provider
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 7533): GC_CONCURRENT freed 3011K, 31% free 9563K/13732K, paused 2ms+2ms, total 23ms
,D/dalvikvm( 7533): WAIT_FOR_CONCURRENT_GC blocked 19ms
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector( 2421): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2421): clearDefaults: com.test.thalitest
,W/AppWidgetServiceImpl( 2421): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/PCWCLIENTTRACE_PushUtil( 6638): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6638): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6638): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6638): [onReceive] - android.intent.action.PACKAGE_REMOVED
,W/ApplicationsProvider( 2958): Could not fetch usage stats
W/ApplicationsProvider( 2958): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2958): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2958): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2958): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2958): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2958): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2958): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2958): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2958): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2958): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2958): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2958): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SA      ( 5860): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5860): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
,E/SQLiteLog( 6059): (3850) statement aborts at 35: [DELETE FROM app_registry WHERE package_name=? AND plugin_id=? AND sync_status != 170004 AND sync_status = 170002] disk I/O error
,W/dalvikvm( 6059): threadid=12: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 6059): FATAL EXCEPTION: IntentService[HandleAppDataService]
E/AndroidRuntime( 6059): Process: com.sec.android.app.shealth, PID: 6059
E/AndroidRuntime( 6059): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6059): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6059): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 6059): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6059): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6059): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 6059): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericDelete(BaseContentProvider.java:486)
E/AndroidRuntime( 6059): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.delete(BaseContentProvider.java:441)
E/AndroidRuntime( 6059): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6059): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6059): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.deleteAppRegistryData(AppRegistryDbManagerWithProvider.java:459)
E/AndroidRuntime( 6059): 	at com.sec.android.app.shealth.service.HandleAppDataService.onHandleIntent(HandleAppDataService.java:56)
E/AndroidRuntime( 6059): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6059): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6059): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6059): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SharedPreferencesImpl( 3595): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
I/Icing.InternalIcingCorporaProvider( 6480): Updating corpora: A: com.test.thalitest, C: MAYBE
E/SQLiteLog( 6480): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/dalvikvm( 6480): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop217.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,I/SELinux ( 7553): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7553):  
,I/Process ( 6059): Sending signal. PID: 6059 SIG: 9
E/AndroidRuntime( 6480): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 6480): Process: com.google.android.googlequicksearchbox:search, PID: 6480
E/AndroidRuntime( 6480): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6480): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6480): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 6480): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6480): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6480): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 6480): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 6480): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:171)
E/AndroidRuntime( 6480): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 6480): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
E/AndroidRuntime( 6480): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 6480): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 6480): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 6480): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 6480): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 6480): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 6480): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 6480): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6480): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6480): Sending signal. PID: 6480 SIG: 9
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop218.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
I/ActivityManager( 2421): Process com.sec.android.app.shealth (pid 6059) (adj 5) has died.
I/SELinux ( 7553): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7553):  
I/SELinux ( 7553):  
I/SELinux ( 7553): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/ActivityManager( 2421): Process com.google.android.googlequicksearchbox:search (pid 6480) (adj 5) has died.
E/SELinux ( 7553): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7553): >>>>> Normal User
E/dalvikvm( 7553): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
E/SELinux ( 7553): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7553): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7553): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7553): Added TimaKesytore provider
,D/dalvikvm( 7553): GC_CONCURRENT freed 3008K, 31% free 9562K/13728K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7553): WAIT_FOR_CONCURRENT_GC blocked 16ms
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
W/ContextImpl( 6415): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:165 android.app.ActivityThread.handleReceiver:2698 
,D/RCPManager( 6494):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2421):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2421): queryAllProviders():  providerCallBack is not register for 0
E/SQLiteDatabase( 6415): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 6415): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6415): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6415): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6415): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6415): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6415): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6415): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6415): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6415): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6415): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6415): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6415): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6415): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6415): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6415): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 6415): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 6415): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6415): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6415): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6415): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/CapabilityManagerService New( 6706): Receiver Broadcast:android.intent.action.PACKAGE_REMOVED
D/CapabilityManagerService New( 6706): The package(com.test.thalitest) removed
W/System.err( 6415): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 6415): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 6415): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 2421): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 6415): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2421): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2421): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 6415): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 2421): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 6415): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 2421): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2421): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2421): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 6415): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 2421): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 6415): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 6415): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 6415): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2421): 	... 8 more
W/System.err( 2421): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2421): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 6415): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 6415): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 2421): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2421): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2421): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 6415): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 2421): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 6415): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 6415): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 2421): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 6415): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 6415): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 2421): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2421): 	... 8 more
W/System.err( 6415): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6415): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6415): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/MagazineService::MagazineBroadcastReceiver( 6733): [onReceive] android.intent.action.PACKAGE_REMOVED com.test.thalitest
,I/MagazineService::MagazineService( 6733): [onHandleIntent] ACTION_PACKAGE_REMOVED
D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@8
,E/SQLiteDatabase( 6733): Failed to open database '/data/data/com.samsung.android.app.headlines/databases/card.db'.
E/SQLiteDatabase( 6733): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6733): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6733): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6733): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6733): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6733): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6733): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6733): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6733): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6733): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6733): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/SQLiteDatabase( 6733): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/SQLiteDatabase( 6733): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/SQLiteDatabase( 6733): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/SQLiteDatabase( 6733): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6733): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6733): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6733): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 6733): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,I/SELinux ( 7568): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7568):  
E/AndroidRuntime( 6733): FATAL EXCEPTION: IntentService[MagazineService::MagazineService]
E/AndroidRuntime( 6733): Process: com.samsung.android.magazine.service, PID: 6733
E/AndroidRuntime( 6733): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6733): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 6733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 6733): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6733): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 6733): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 6733): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 6733): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 6733): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 6733): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 6733): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 6733): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/AndroidRuntime( 6733): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6733): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6733): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/AndroidRuntime( 6733): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6733): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6733): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6733): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6733): Sending signal. PID: 6733 SIG: 9
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop219.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,I/ActivityManager( 2421): Process com.samsung.android.magazine.service (pid 6733) (adj 5) has died.
,I/SELinux ( 7568): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7568):  
I/SELinux ( 7568):  
,I/SELinux ( 7568): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7568): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7568): >>>>> Normal User
,E/dalvikvm( 7568): >>>>> com.android.keychain [ userId:0 | appId:1000 ]
,E/SELinux ( 7568): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7568): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7568): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7568): Added TimaKesytore provider
,D/dalvikvm( 7568): GC_CONCURRENT freed 3008K, 31% free 9561K/13728K, paused 1ms+1ms, total 17ms
,D/dalvikvm( 7568): WAIT_FOR_CONCURRENT_GC blocked 15ms
,W/ContextImpl( 7568): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2698 
,E/SQLiteDatabase( 7568): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
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
,D/KidsModeInstallReceiver( 6759): onReceive intent data =  package:com.test.thalitest
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
,D/KidsPlatformStub( 6759): Package not found : com.sec.android.app.kidshome
,I/Process ( 7568): Sending signal. PID: 7568 SIG: 9
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop220.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,W/System.err( 6797): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6797): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
W/System.err( 6797): 	at com.n7mobile.promenada2.applications.ApplicationInstallationReceiver.onReceive(SourceFile:27)
W/System.err( 6797): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 6797): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 6797): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 6797): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 6797): 	at android.os.Looper.loop(Looper.java:146)
,W/System.err( 6797): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 6797): 	at java.lang.reflect.Method.invokeNative(Native Method)
,I/ActivityManager( 2421): Process com.android.keychain (pid 7568) (adj 5) has died.
W/System.err( 6797): 	at java.lang.reflect.Method.invoke(Method.java:515)
,W/System.err( 6797): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 6797): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 6797): 	at dalvik.system.NativeStart.main(Native Method)
,D/PackageBroadcastService( 3283): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest,
,D/AccountUtils( 3283): Clearing selected account for com.test.thalitest,
,D/ChimeraCfgMgr( 3283): Loading module com.google.android.gms.games from APK com.google.android.play.games,
,D/ChimeraModuleLdr( 3283): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 3283): Removing dialog suppression flag for package com.test.thalitest
,E/SQLiteLog( 3283): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/ProcessCpuTracker( 2421): Skipping unknown process pid 7568
,E/DriveAsyncService( 3283): disk I/O error (code 3850)
E/DriveAsyncService( 3283): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 3283): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 3283): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/DriveAsyncService( 3283): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 3283): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 3283): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/DriveAsyncService( 3283): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/DriveAsyncService( 3283): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 3283): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 3283): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 3283): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 3283): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 3283): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 3283): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 3283): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 3283): 	at java.lang.Thread.run(Thread.java:841)
,D/ChimeraCfgMgr( 3283): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3283): Module APK com.google.android.play.games already loaded
,E/SQLiteLog( 2852): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteLog( 3283): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/AndroidRuntime( 2852): Shutting down VM
,W/dalvikvm( 2852): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,W/dalvikvm( 3283): threadid=53: thread exiting with uncaught exception (group=0x4180ac08)
,E/SQLiteDatabase( 3283): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 3283): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3283): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3283): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3283): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3283): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3283): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3283): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3283): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3283): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3283): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3283): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3283): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3283): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3283): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3283): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 3283): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 3283): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 3283): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 3283): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3283): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3283): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3283): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 3283): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 3283): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3283): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3283): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 3283): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 3283): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 3283): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 3283): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 3283): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 3283): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 3283): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 3283): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 3283): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 3283): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3283): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3283): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 3283): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 3283): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 3283): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 3283): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 3283): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3283): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 3283): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 2852): FATAL EXCEPTION: main
E/AndroidRuntime( 2852): Process: com.google.process.gapps, PID: 2852
E/AndroidRuntime( 2852): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2852): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 2852): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 2852): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 2852): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2852): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2852): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 2852): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2852): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2852): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 2852): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 2852): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2852): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2852): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2852): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRunt,ime( 2852): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2852): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2852): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 2852): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 2852): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 2852): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 2852): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 2852): 	... 10 more
W/SQLiteOpenHelper( 3283): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 3283): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 3283): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,E/SQLiteLog( 3283): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 3283): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 3283): threadid=52: thread exiting with uncaught exception (group=0x4180ac08)
,I/Process ( 3283): Sending signal. PID: 3283 SIG: 9
,I/Process ( 2852): Sending signal. PID: 2852 SIG: 9
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop221.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,E/SQLiteDatabase( 5594): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5594): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5594): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5594): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5594): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5594): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5594): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5594): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5594): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5594): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5594): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5594): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5594): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5594): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5594): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5594): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5594): 	at com.sec.spp.push.i.d.e(Unknown Source)
E/SQLiteDatabase( 5594): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5594): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5594): 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
E/SQLiteDatabase( 5594): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5594): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5594): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 5594): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5594): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5594): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 5594): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 5594): 	at dalvik.system.NativeStart.main(Native Method)
,E/SPPClientService( 5594): [d] [getAppId()] Exception with message =not an error (code 0): Could not open the database in read/write mode.
,E/SQLiteDatabase( 6456): Failed to open database '/data/data/com.sec.spp.push/databases/evtDb'.
E/SQLiteDatabase( 6456): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6456): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6456): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6456): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6456): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6456): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6456): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6456): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6456): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6456): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6456): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6456): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6456): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6456): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6456): 	at com.sec.spp.push.notisvc.tracking.h.b(Unknown Source)
E/SQLiteDatabase( 6456): 	at com.sec.spp.push.notisvc.tracking.g.a(Unknown Source)
E/SQLiteDatabase( 6456): 	at com.sec.spp.push.notisvc.tracking.f.a(Unknown Source)
E/SQLiteDatabase( 6456): 	at com.sec.spp.push.notisvc.tracking.a.c(Unknown Source)
E/SQLiteDatabase( 6456): 	at com.sec.spp.push.notisvc.tracking.a.a(Unknown Source)
E/SQLiteDatabase( 6456): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6456): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6456): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6456): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6456): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6456): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6456): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6456): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6456): [g] not an error (code 0): Could not open the database in read/write mode.
,I/SELinux ( 7593): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7593):  
I/ActivityManager( 2421): Process com.google.process.gapps (pid 2852) (adj 5) has died.
I/ActivityManager( 2421): Process com.google.android.gms (pid 3283) (adj 5) has died.
,E/SQLiteDatabase( 6456): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 6456): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6456): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6456): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6456): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6456): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6456): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6456): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6456): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6456): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6456): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6456): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6456): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6456): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6456): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6456): 	at com.sec.spp.push.notisvc.b.b.<init>(Unknown Source)
E/SQLiteDatabase( 6456): 	at com.sec.spp.push.notisvc.b.b.a(Unknown Source)
E/SQLiteDatabase( 6456): 	at com.sec.spp.push.notisvc.registration.q.b(Unknown Source)
E/SQLiteDatabase( 6456): 	at com.sec.spp.push.notisvc.registration.q.a(Unknown Source)
E/SQLiteDatabase( 6456): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6456): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6456): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6456): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6456): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6456): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6456): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6456): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6456): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6456): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6456): [b] open fail. android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,D/GAV2    ( 5687): Thread[main,5,main]: service disconnected: ComponentInfo{com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService}
,I/GAV2    ( 5687): Thread[main,5,main]: Unexpected disconnect.
,I/SELinux ( 7593): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7593):  
I/SELinux ( 7593):  
,I/SELinux ( 7593): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7593): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7593): >>>>> Normal User
,E/dalvikvm( 7593): >>>>> com.android.documentsui [ userId:0 | appId:10093 ]
,E/SELinux ( 7593): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7593): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7593): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7593): Added TimaKesytore provider
,D/dalvikvm( 7593): GC_CONCURRENT freed 3006K, 31% free 9570K/13732K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 7593): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/Documents( 7593): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 7593): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 7593): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7593): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7593): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7593): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7593): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7593): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7593): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7593): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7593): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7593): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7593): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7593): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7593): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7593): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7593): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 7593): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 7593): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 7593): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/SQLiteDatabase( 7593): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 7593): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7593): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7593): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7593): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7593): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7593): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7593): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7593): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7593): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7593): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7593): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 7593): Shutting down VM
,W/dalvikvm( 7593): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,I/SELinux ( 7609): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7609):  
E/AndroidRuntime( 7593): FATAL EXCEPTION: main
E/AndroidRuntime( 7593): Process: com.android.documentsui, PID: 7593
E/AndroidRuntime( 7593): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7593): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 7593): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 7593): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7593): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7593): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7593): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7593): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7593): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7593): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7593): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7593): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7593): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7593): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7593): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7593): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7593): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7593): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7593): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7593): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7593): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7593): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7593): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7593): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7593): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7593): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7593): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 7593): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 7593): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 7593): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/AndroidRuntime( 7593): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 7593): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 7593): 	... 10 more
,I/SELinux ( 7613): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7613):  
,I/Process ( 7593): Sending signal. PID: 7593 SIG: 9
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop222.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,I/ActivityManager( 2421): Process com.android.documentsui (pid 7593) (adj 9) has died.
,I/SELinux ( 7609): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7609):  
I/SELinux ( 7609):  
,I/SELinux ( 7609): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7609): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7609): >>>>> Normal User
,E/dalvikvm( 7609): >>>>> com.android.externalstorage [ userId:0 | appId:10009 ]
,E/SELinux ( 7609): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 7613): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7613):  
I/SELinux ( 7613):  
,I/SELinux ( 7613): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7613): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7613): >>>>> Normal User
,E/dalvikvm( 7613): >>>>> com.google.android.gms [ userId:0 | appId:10012 ]
,E/SELinux ( 7613): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7609): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7609): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7609): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 7613): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7613): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7613): Added TimaKesytore provider
,D/dalvikvm( 7609): GC_CONCURRENT freed 3010K, 31% free 9561K/13728K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7609): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/ExternalStorage( 7609): After updating volumes, found 1 active roots
,D/dalvikvm( 7613): GC_CONCURRENT freed 2947K, 30% free 9626K/13732K, paused 3ms+1ms, total 23ms
,D/dalvikvm( 7613): WAIT_FOR_CONCURRENT_GC blocked 12ms
,W/dalvikvm( 7613): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7613): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 7613): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 7613): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 7613): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 7613): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7613): install
,I/MultiDex( 7613): MultiDexExtractor.load(/data/app/com.google.android.gms-5.apk, false)
,I/MultiDex( 7613): loading existing secondary dex files
,I/MultiDex( 7613): load found 3 secondary dex files
,I/MultiDex( 7613): install done
,I/SELinux ( 7635): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7635):  
,I/SELinux ( 7635): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7635):  
I/SELinux ( 7635):  
,I/SELinux ( 7635): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7635): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 7635): >>>>> Normal User
,E/dalvikvm( 7635): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 7635): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7635): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7635): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7635): Added TimaKesytore provider
,I/SELinux ( 7649): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7649):  
,I/SELinux ( 7649): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7649):  
I/SELinux ( 7649):  
,I/SELinux ( 7649): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7649): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7649): >>>>> Normal User
,E/dalvikvm( 7649): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7649): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7649): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7649): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7649): Added TimaKesytore provider
,D/dalvikvm( 7635): GC_CONCURRENT freed 2993K, 31% free 9578K/13728K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7635): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 7649): GC_CONCURRENT freed 2979K, 31% free 9587K/13728K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7649): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/Icing.InternalIcingCorporaProvider( 7635): Updating corpora: A: com.test.thalitest, C: MAYBE
,I/SELinux ( 7665): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7665):  
,D/LocationManagerService( 2421): getProviders()=[passive]
,I/GservicesProvider( 7649): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7649): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7649): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7649): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7649): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7649): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7649): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7649): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7649): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7649): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7649): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7649): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7649): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7649): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7649): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7649): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7649): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7649): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7649): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7649): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7649): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7649): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7649): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7649): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7649): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7649): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7649): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7649): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7649): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7649): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7649): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7649): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7649): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7649): Shutting down VM
,W/dalvikvm( 7649): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
I/SELinux ( 7665): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7665):  
I/SELinux ( 7665):  
,I/SELinux ( 7665): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7665): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7665): >>>>> Normal User
,E/dalvikvm( 7665): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 7665): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/AndroidRuntime( 7649): FATAL EXCEPTION: main
E/AndroidRuntime( 7649): Process: com.google.process.gapps, PID: 7649
E/AndroidRuntime( 7649): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7649): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7649): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7649): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7649): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7649): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7649): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7649): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7649): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7649): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7649): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7649): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7649): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7649): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7649): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7649): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7649): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7649): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7649): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7649): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7649): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7649): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7649): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7649): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7649): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7649): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7649): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7649): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7649): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7649): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7649): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7649): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7649): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7649): 	... 12 more
,I/Process ( 7649): Sending signal. PID: 7649 SIG: 9
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop223.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,D/TimaKeyStoreProvider( 7665): in addTimaSignatureService
I/ActivityManager( 2421): Process com.google.process.gapps (pid 7649) (adj 0) has died.
,W/ActivityManager( 2421): Service crashed 2 times, stopping: ServiceRecord{43083090 u0 com.google.android.gms/.gcm.GcmService},
D/TimaKeyStoreProvider( 7665): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7665): Added TimaKesytore provider
I/SELinux ( 7683): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7683):  
,D/dalvikvm( 1923): GC_EXPLICIT freed 43K, 12% free 9505K/10708K, paused 2ms+3ms, total 30ms,
,I/SELinux ( 7683): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7683):  
I/SELinux ( 7683):  
I/SELinux ( 7683): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7683): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7683): >>>>> Normal User
,E/dalvikvm( 7683): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ],
,E/SELinux ( 7683): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 12% free 9505K/10708K, paused 2ms+3ms, total 26ms,
,D/TimaKeyStoreProvider( 7683): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7683): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7683): Added TimaKesytore provider
,D/dalvikvm( 7665): GC_CONCURRENT freed 3001K, 31% free 9570K/13728K, paused 3ms+1ms, total 27ms
,D/dalvikvm( 7665): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 12% free 9505K/10708K, paused 2ms+3ms, total 25ms
,D/dalvikvm( 7683): GC_CONCURRENT freed 2987K, 31% free 9584K/13728K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 7683): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7683): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7683): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
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
E/SQLiteDatabase( 7683): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7683): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7683): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7683): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7683): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7683): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7683): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7683): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7683): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7683): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7683): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7683): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7683): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7683): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7683): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7683): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7683): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7683): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7683): Shutting down VM
,W/dalvikvm( 7683): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7683): FATAL EXCEPTION: main
E/AndroidRuntime( 7683): Process: com.google.process.gapps, PID: 7683
E/AndroidRuntime( 7683): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7683): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7683): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7683): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7683): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7683): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7683): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7683): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7683): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7683): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7683): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7683): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7683): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7683): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7683): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7683): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7683): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7683): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7683): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7683): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7683): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7683): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7683): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7683): 	... 12 more
W/ActivityManager( 2421): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2421): Killing 7683:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2421): Unable to launch app com.google.android.gsf/10012 for provider com.google.settings: launching app beca,me null
W/ActivityManager( 2421): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
W/ActivityManager( 2421): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7665): Failed to find provider info for com.google.android.gsf.gservices
E/ActivityThread( 7635): Failed to find provider info for com.google.settings
E/ActivityThread( 7613): Failed to find provider info for com.google.android.gsf.gservices
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop224.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,I/SELinux ( 7701): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7701):  
,I/SELinux ( 7701): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7701):  
I/SELinux ( 7701):  
,I/SELinux ( 7701): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7701): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7701): >>>>> Normal User
,E/dalvikvm( 7701): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7701): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7701): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7701): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7701): Added TimaKesytore provider
,D/dalvikvm( 7701): GC_CONCURRENT freed 2990K, 31% free 9581K/13728K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 7701): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7701): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7701): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7701): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7701): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7701): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7701): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7701): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7701): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7701): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7701): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7701): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7701): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7701): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7701): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7701): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7701): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7701): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7701): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7701): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7701): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7701): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7701): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7701): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7701): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7701): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7701): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7701): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7701): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7701): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7701): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7701): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7701): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7701): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7701): Shutting down VM
,W/dalvikvm( 7701): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7701): FATAL EXCEPTION: main
E/AndroidRuntime( 7701): Process: com.google.process.gapps, PID: 7701
E/AndroidRuntime( 7701): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7701): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7701): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7701): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7701): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7701): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7701): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7701): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7701): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7701): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7701): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7701): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7701): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7701): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7701): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7701): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7701): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7701): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7701): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7701): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7701): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7701): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7701): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7701): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7701): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7701): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7701): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7701): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7701): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7701): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7701): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7701): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7701): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7701): 	... 12 more
,I/Process ( 7701): Sending signal. PID: 7701 SIG: 9
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop225.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,I/ActivityManager( 2421): Process com.google.process.gapps (pid 7701) (adj 0) has died.
,I/SELinux ( 7716): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7716):  
,I/SELinux ( 7716): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7716):  
I/SELinux ( 7716):  
,I/SELinux ( 7716): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7716): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7716): >>>>> Normal User
E/dalvikvm( 7716): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
E/SELinux ( 7716): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7716): in addTimaSignatureService
D/TimaKeyStoreProvider( 7716): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7716): Added TimaKesytore provider
,D/dalvikvm( 7716): GC_CONCURRENT freed 2994K, 31% free 9581K/13732K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7716): WAIT_FOR_CONCURRENT_GC blocked 15ms,
,I/GservicesProvider( 7716): Gservices pushing to system: true; secure/global: true,
E/SQLiteDatabase( 7716): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7716): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7716): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7716): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512),
E/SQLiteDatabase( 7716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7716): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7716): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7716): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7716): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7716): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7716): ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7716): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7716): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7716): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7716): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7716): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7716): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294),
E/SQLiteDatabase( 7716): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7716): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7716): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7716): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7716): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7716): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7716): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7716): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7716): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7716): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7716): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7716): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7716): Shutting down VM
,W/dalvikvm( 7716): threadid=1: thread exiting with uncaught exception (group=0x4180ac08),
E/AndroidRuntime( 7716): FATAL EXCEPTION: main
E/AndroidRuntime( 7716): Process: com.google.process.gapps, PID: 7716
E/AndroidRuntime( 7716): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7716): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7716): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7716): ,	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7716): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7716): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7716): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7716): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7716): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
,E/AndroidRuntime( 7716): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7716): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7716): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7716): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7716): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7716): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7716): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method),
E/AndroidRuntime( 7716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7716): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7716): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7716): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
,E/AndroidRuntime( 7716): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7716): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7716): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7716): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7716): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7716): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7716): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
,E/AndroidRuntime( 7716): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7716): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7716): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7716): 	... 12 more
W/ActivityManager( 2421): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2421): Killing 7716:com.google.process.gapps/u0a12 (adj 0): crash
,W/ActivityManager( 2421): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7665): Failed to find provider info for com.google.android.gsf.gservices
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop226.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	,at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,E/DropBoxManagerService( 2421): 	... 5 more
D/dalvikvm( 7613): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/ActivityManager( 2421): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
,E/ActivityThread( 7613): Failed to find provider info for com.google.android.gsf.gservices,
W/dalvikvm( 7613): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7613): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7613): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7613): VFY: unable to resolve instance field 36
D/dalvikvm( 7613): VFY: replacing opcode 0x54 at 0x005f,
D/dalvikvm( 7613): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7613): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7613): VFY: replacing opcode 0x62 at 0x0047
,I/ActivityManager( 2421): Killing 6612:com.samsung.groupcast/u0a15 (adj 15): empty #43
D/dalvikvm( 7613): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 7613): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 7613): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4226ea78
D/dalvikvm( 7613): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4226ea78
D/dalvikvm( 7613): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4226ea78, skipping init
D/dalvikvm( 7613): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4226ea78
D/dalvikvm( 7613): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4226ea78
V/JNIHelp ( 7613): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 7613): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4226ea78
,D/dalvikvm( 7613): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x4226ea78
D/dalvikvm( 7613): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4226ea78
,D/dalvikvm( 7613): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4226ea78
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4004): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4004): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ProviderInstaller( 7613): Installed default security provider GmsCore_OpenSSL,
,I/SELinux ( 7731): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7731):  
,I/SELinux ( 7731): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7731):  
I/SELinux ( 7731):  
,I/SELinux ( 7731): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7731): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7731): >>>>> Normal User
,E/dalvikvm( 7731): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ],
,E/SELinux ( 7731): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/TimaKeyStoreProvider( 7731): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7731): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7731): Added TimaKesytore provider,
,D/dalvikvm( 7731): GC_CONCURRENT freed 2991K, 31% free 9581K/13732K, paused 2ms+2ms, total 18ms,
,D/dalvikvm( 7731): WAIT_FOR_CONCURRENT_GC blocked 15ms,
,I/GservicesProvider( 7731): Gservices pushing to system: true; secure/global: true,
E/SQLiteDatabase( 7731): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7731): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7731): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7731): ,	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7731): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7731): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7731): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7731): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7731): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
,E/SQLiteDatabase( 7731): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7731): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7731): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7731): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7731): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7731): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562),
E/SQLiteDatabase( 7731): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7731): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7731): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7731): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7731): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7731): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7731): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7731): 	,at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7731): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7731): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7731): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7731): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7731): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7731): Shutting down VM,
,W/dalvikvm( 7731): threadid=1: thread exiting with uncaught exception (group=0x4180ac08),
,E/AndroidRuntime( 7731): FATAL EXCEPTION: main,
E/AndroidRuntime( 7731): Process: com.google.process.gapps, PID: 7731
E/AndroidRuntime( 7731): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7731): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7731): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7731): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7731): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7731): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368),
E/AndroidRuntime( 7731): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7731): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7731): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7731): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7731): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7731): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7731): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,E/AndroidRuntime( 7731): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7731): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7731): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7731): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206),
E/AndroidRuntime( 7731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7731): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7731): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7731): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7731): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7731): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7731): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7731): 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7731): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7731): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7731): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7731): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7731): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7731): 	... 12 more
,I/Process ( 7731): Sending signal. PID: 7731 SIG: 9,
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop227.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	,at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,I/ActivityManager( 2421): Process com.google.process.gapps (pid 7731) (adj 0) has died.,
,I/SELinux ( 7746): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7746):  
,I/SELinux ( 7746): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7746):  
I/SELinux ( 7746):  
I/SELinux ( 7746): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7746): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7746): >>>>> Normal User
,E/dalvikvm( 7746): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7746): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7746): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7746): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7746): Added TimaKesytore provider
,D/dalvikvm( 7746): GC_CONCURRENT freed 2995K, 31% free 9581K/13732K, paused 3ms+2ms, total 19ms
,D/dalvikvm( 7746): WAIT_FOR_CONCURRENT_GC blocked 8ms
,I/GservicesProvider( 7746): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7746): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7746): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7746): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7746): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7746): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7746): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7746): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7746): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7746): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7746): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7746): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7746): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7746): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7746): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7746): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7746): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7746): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7746): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7746): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7746): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7746): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7746): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7746): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7746): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7746): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7746): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7746): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7746): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7746): Shutting down VM
,W/dalvikvm( 7746): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7746): FATAL EXCEPTION: main
E/AndroidRuntime( 7746): Process: com.google.process.gapps, PID: 7746
E/AndroidRuntime( 7746): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7746): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7746): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7746): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7746): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7746): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7746): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7746): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7746): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7746): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7746): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7746): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7746): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7746): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7746): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7746): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7746): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7746): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7746): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7746): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7746): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7746): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7746): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7746): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7746): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7746): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7746): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7746): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7746): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7746): 	... 12 more
W/ActivityManager( 2421): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2421): Killing 7746:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2421): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launc,hing app became null
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop228.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,E/ActivityThread( 7613): Failed to find provider info for com.google.android.gsf.gservices
W/NativeLibraryUtils( 7613): Failed to open lock file
W/NativeLibraryUtils( 7613): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7613): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/NativeLibraryUtils( 7613): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:118)
W/NativeLibraryUtils( 7613): 	at com.google.android.gms.common.util.ay.b(SourceFile:325)
W/NativeLibraryUtils( 7613): 	at com.google.android.gms.common.app.b.run(SourceFile:209)
W/NativeLibraryUtils( 7613): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7613): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7613): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/NativeLibraryUtils( 7613): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/NativeLibraryUtils( 7613): 	... 3 more
,W/dalvikvm( 2958): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
,I/dalvikvm( 7613): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 7613): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7613): VFY: replacing opcode 0x6e at 0x000d
,E/AndroidRuntime( 2958): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 2958): Process: android.process.acore, PID: 2958
E/AndroidRuntime( 2958): android.database.sqlite.SQLiteDatabaseLockedException: database is locked (code 5)
E/AndroidRuntime( 2958): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2958): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 2958): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2958): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2958): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 2958): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 2958): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:408)
E/AndroidRuntime( 2958): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:377)
E/AndroidRuntime( 2958): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2467)
E/AndroidRuntime( 2958): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 2958): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2958): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2958): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 2958): Sending signal. PID: 2958 SIG: 9
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop229.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,I/SELinux ( 7767): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7767):  
I/ActivityManager( 2421): Process android.process.acore (pid 2958) (adj -12) has died.
,I/SELinux ( 7771): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7771):  
,I/SELinux ( 7767): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7767):  
I/SELinux ( 7767):  
,I/SELinux ( 7767): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7767): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7767): >>>>> Normal User
,E/dalvikvm( 7767): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7767): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/SELinux ( 7771): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7771):  
I/SELinux ( 7771):  
,I/SELinux ( 7771): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7771): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7771): >>>>> Normal User
,E/dalvikvm( 7771): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7771): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7767): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7767): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7767): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 7771): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7771): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7771): Added TimaKesytore provider
,D/dalvikvm( 7767): GC_CONCURRENT freed 2999K, 31% free 9574K/13732K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7767): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 7771): GC_CONCURRENT freed 3003K, 31% free 9572K/13732K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7771): WAIT_FOR_CONCURRENT_GC blocked 16ms
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
,E/AndroidRuntime( 7767): FATAL EXCEPTION: main
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
,I/Process ( 7767): Sending signal. PID: 7767 SIG: 9
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop230.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,I/ActivityManager( 2421): Process com.google.process.gapps (pid 7767) (adj 0) has died.
,I/SELinux ( 7796): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7796):  
,I/SELinux ( 7796): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7796):  
I/SELinux ( 7796):  
,I/SELinux ( 7796): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7796): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7796): >>>>> Normal User
,E/dalvikvm( 7796): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7796): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7796): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7796): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7796): Added TimaKesytore provider,
,E/SQLiteDatabase( 7771): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.,
E/SQLiteDatabase( 7771): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
,E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7771): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7771): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7771): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7771): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7771): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7771): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7771): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7771): 	at android.os.Looper.loop(Looper.java:146),
E/SQLiteDatabase( 7771): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 7771): Couldn't open contacts2.db for writing (will try read-only):,
E/SQLiteOpenHelper( 7771): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7771): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7771): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
,E/SQLiteOpenHelper( 7771): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7771): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7771): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7771): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7771): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7771): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7771): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188),
E/SQLiteOpenHelper( 7771): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7771): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7771): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7771): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7771): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7771): 	at android.os.Looper.loop(Looper.java:146),
E/SQLiteOpenHelper( 7771): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 7771): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7771): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
E/SQLiteLog( 7771): (14) unable to open database file,
E/SQLiteDatabase( 7771): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7771): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7771): ,	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7771): 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7771): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7771): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider,2.java:2315)
E/SQLiteDatabase( 7771): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7771): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7771): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7771): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7771): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7771): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7771): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7771): Process: android.process.acore, PID: 7771
E/AndroidRuntime( 7771): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7771): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7771): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7771): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7771): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7771): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7771): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7771): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 2421): Process android.process.acore has crashed too many times: killing!
,I/Process ( 7771): Sending signal. PID: 7771 SIG: 9
E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop231.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
,I/ActivityManager( 2421): Process android.process.acore (pid 7771) (adj -12) has died.
,F/ActivityManager( 2421): Service ServiceRecord{4691f8c0 u0 com.android.providers.contacts/.VoicemailCleanupService} in process ProcessRecord{42e5f390 7771:android.process.acore/u0a20} not same as in map: null
,E/DropBoxManagerService( 2421): Can't write: system_server_wtf
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop164.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2421): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2421): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2421): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2421): 	at android.util.Slog.wtf(Slog.java:163)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2151)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15153)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4944)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5122)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1322)
E/DropBoxManagerService( 2421): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:493)
E/DropBoxManagerService( 2421): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 18 more
,I/SELinux ( 7811): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7811):  
,D/dalvikvm( 7796): GC_CONCURRENT freed 2990K, 31% free 9581K/13732K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 7796): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/SELinux ( 7811): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7811):  
I/SELinux ( 7811):  
,I/SELinux ( 7811): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7811): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7811): >>>>> Normal User
,E/dalvikvm( 7811): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7811): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,I/GservicesProvider( 7796): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7796): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7796): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7796): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7796): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7796): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7796): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7796): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7796): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7796): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7796): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7796): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7796): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7796): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7796): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7796): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7796): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7796): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7796): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7796): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7796): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7796): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7796): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7796): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7796): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7796): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7796): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7796): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7796): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7796): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7796): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7796): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7796): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7796): Shutting down VM
,W/dalvikvm( 7796): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,D/TimaKeyStoreProvider( 7811): in addTimaSignatureService
E/AndroidRuntime( 7796): FATAL EXCEPTION: main
E/AndroidRuntime( 7796): Process: com.google.process.gapps, PID: 7796
E/AndroidRuntime( 7796): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7796): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7796): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7796): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7796): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7796): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7796): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7796): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7796): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7796): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7796): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7796): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7796): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7796): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7796): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7796): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7796): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7796): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7796): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7796): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7796): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7796): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7796): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7796): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7796): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7796): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7796): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7796): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7796): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7796): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7796): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7796): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7796): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7796): 	... 12 more
,I/GAv4-SVC( 7613): Google Analytics 8.4.89 is starting up.
W/ActivityManager( 2421): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2421): Killing 7796:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2421): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7613): Failed to find provider info for com.google.android.gsf.gservices
,E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop233.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
D/TimaKeyStoreProvider( 7811): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7811): Added TimaKesytore provider
,I/SELinux ( 7826): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7826):  
,I/SELinux ( 7826): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7826):  
I/SELinux ( 7826):  
,I/SELinux ( 7826): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7826): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7826): >>>>> Normal User
,E/dalvikvm( 7826): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7826): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 7811): GC_CONCURRENT freed 2994K, 31% free 9579K/13732K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7811): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/TimaKeyStoreProvider( 7826): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7826): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7826): Added TimaKesytore provider
,D/dalvikvm( 7826): GC_CONCURRENT freed 2991K, 31% free 9581K/13728K, paused 3ms+2ms, total 19ms
,D/dalvikvm( 7826): WAIT_FOR_CONCURRENT_GC blocked 15ms
,E/SQLiteDatabase( 7811): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7811): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7811): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7811): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7811): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7811): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7811): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7811): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7811): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7811): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7811): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 7811): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7811): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7811): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7811): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7811): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7811): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7811): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7811): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7811): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7811): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7811): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7811): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7811): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7811): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7811): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7811): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7811): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7811): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 7811): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7811): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7811): (14) unable to open database file
,E/SQLiteDatabase( 7811): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7811): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7811): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7811): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7811): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7811): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7811): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7811): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7811): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7811): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7811): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7811): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7811): Process: android.process.acore, PID: 7811
E/AndroidRuntime( 7811): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7811): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7811): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7811): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7811): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7811): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7811): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7811): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7811): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7811): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7811): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7811): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7811): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7811): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7811): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7811): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7811): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7811): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 7811): Sending signal. PID: 7811 SIG: 9
,I/GservicesProvider( 7826): Gservices pushing to system: true; secure/global: true
W/ActivityManager( 2421): Process android.process.acore has crashed too many times: killing!
,E/DropBoxManagerService( 2421): Can't write: system_app_crash
E/DropBoxManagerService( 2421): java.io.FileNotFoundException: /data/system/dropbox/drop234.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2421): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2421): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2421): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2421): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2421): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2421): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2421): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2421): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2421): 	... 5 more
E/SQLiteDatabase( 7826): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
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
E/SQLiteDatabase( 7826): 	a
```
