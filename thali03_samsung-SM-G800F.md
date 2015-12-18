#### Test 539786637913587_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,--------- beginning of /dev/log/main
D/AndroidRuntime( 7321): 
D/AndroidRuntime( 7321): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7321): CheckJNI is OFF
D/AndroidRuntime( 7321): setted country_code = Poland
D/AndroidRuntime( 7321): setted countryiso_code = PL
D/AndroidRuntime( 7321): setted sales_code = PLS
D/AndroidRuntime( 7321): readGMSProperty: start
D/AndroidRuntime( 7321): readGMSProperty: already setted!!
D/AndroidRuntime( 7321): readGMSProperty: end
D/AndroidRuntime( 7321): addProductProperty: start
D/dalvikvm( 7321): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7321): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7321): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7321): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7321): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7321): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7321): failed to load memtrack module: -2
D/dalvikvm( 7321): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7321): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2419): mDVFSHelper.acquire()
I/SELinux ( 7349): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7349):  
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7321): Shutting down VM
D/dalvikvm( 7321): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+0ms, total 3ms
I/SELinux ( 7349): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7349):  
I/SELinux ( 7349):  
I/SELinux ( 7349): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7349): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7349): >>>>> Normal User
E/dalvikvm( 7349): >>>>> com.test.thalitest [ userId:0 | appId:10563 ]
E/SELinux ( 7349): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7349): in addTimaSignatureService
D/TimaKeyStoreProvider( 7349): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7349): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4166): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4166): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7349): GC_CONCURRENT freed 3024K, 33% free 9549K/14100K, paused 1ms+1ms, total 18ms
D/dalvikvm( 7349): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7349): Binding Chromium to the background looper Looper (main, tid 1) {4230d350}
I/chromium( 7349): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7349): Initializing chromium process, renderers=0
W/chromium( 7349): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7349): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 7349): loaded /system/lib/egl/libGLESv1_CM_mali.so
D/libEGL  ( 7349): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7349): Mali API Version : 401
,I/Mali    ( 7349): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7349): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7349): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7349): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7349): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7349): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7349): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2579): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2419): tr p:7349,o:f
,W/dalvikvm( 7349): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 7349): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7349): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7349): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7349): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7349): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7349): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7349): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 7349): VFY: replacing opcode 0x6e at 0x000d,
I/dalvikvm( 7349): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7349): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7349): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7349): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2579): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2419): semi p:7349,o:f
,I/SurfaceFlinger( 1920): id=19 createSurf (1x1),1 flag=404, NainActivit,
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7349): EGLImpl-HWUI Protected EGL context created,
,D/OpenGLRenderer( 7349): Enabling debug mode 0,
,W/AwContents( 7349): nativeOnDraw failed; clearing to background color.,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/AwContents( 7349): nativeOnDraw failed; clearing to background color.
D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2419): mDVFSHelper.release()
,W/IInputConnectionWrapper( 7349): showStatusIcon on inactive InputConnection,
,D/JsMessageQueue( 7349): Set native->JS mode to OnlineEventsBridgeMode,
,D/dalvikvm( 7349): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4230e0d8,
D/dalvikvm( 7349): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4230e0d8
D/jxcore_app_log( 7349): JniHelper::setJavaVM(0x4176f220), pthread_self() = 2030942000
D/JX-Cordova( 7349): jxcore cordova android initializing
,D/dalvikvm( 7349): GC_CONCURRENT freed 1273K, 20% free 11350K/14148K, paused 3ms+2ms, total 26ms,
,D/dalvikvm( 7349): WAIT_FOR_CONCURRENT_GC blocked 6ms,
,D/dalvikvm( 7349): GC_CONCURRENT freed 1923K, 19% free 14901K/18368K, paused 2ms+1ms, total 39ms,
,D/dalvikvm( 7349): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@8,
,D/dalvikvm( 7349): GC_FOR_ALLOC freed 5407K, 31% free 16205K/23356K, paused 49ms, total 51ms,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate,
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 7349): GC_CONCURRENT freed 6687K, 32% free 17684K/25924K, paused 3ms+11ms, total 78ms,
,D/dalvikvm( 7349): WAIT_FOR_CONCURRENT_GC blocked 50ms
,D/dalvikvm( 7349): GC_FOR_ALLOC freed 1424K, 33% free 17492K/25924K, paused 50ms, total 50ms,
,I/dalvikvm-heap( 7349): Grow heap (frag case) to 22.162MB for 3767174-byte allocation,
,D/dalvikvm( 7349): GC_FOR_ALLOC freed 2457K, 37% free 18713K/29604K, paused 49ms, total 49ms,
,W/jxcore-log( 7349): Initializing JXcore engine,
,W/jxcore-log( 7349): JXcore engine is ready,
,W/jxcore-log( 7349): Starting JXcore engine,
,W/jxcore-log( 7349): Platform android,
W/jxcore-log( 7349): 
,W/jxcore-log( 7349): Process ARCH arm,
W/jxcore-log( 7349): 
,I/jxcore-log( 7349): JXcore Cordova bridge is ready!,
I/jxcore-log( 7349): 
,W/jxcore-log( 7349): JXcore engine is started,
,I/chromium( 7349): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/jxcore-log( 7349): Toggling radios to true
I/jxcore-log( 7349): 
,D/BluetoothAdapter( 7349): enable(): BT is already enabled..!
,I/WifiManager( 7349): packageName : com.test.thalitest
,I/WifiManager( 7349): setWifiEnabled : true
,I/WifiService( 2419): setWifiEnabled: true pid=7349, uid=10563
W/ActivityManager( 2419): Permission Denial: getCurrentUser() from pid=7349, uid=10563 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 2419): Failed getting userId using ActivityManagerNative
W/WifiService( 2419): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7349, uid=10563 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2419): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2419): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2419): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2419): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2419): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2419): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService( 2419): disconnect: pid=7349, uid=10563
,I/jxcore-log( 7349): Radios toggled
I/jxcore-log( 7349): 
,I/wpa_supplicant( 3965): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3965): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3965): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3965): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3965): First Scan Start
,I/wpa_supplicant( 3965): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings( 2419): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2419): ignore requestNetworkTransitionWakelock airplane:true
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
D/WifiP2pService( 2419): InactiveState{ what=143375 }
D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1914): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
,I/wpa_supplicant( 3965): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3965): Skip scan - already scanning
D/ConnectivityService( 2419): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/WifiP2pService( 2419): InactiveState{ what=143375 }
D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
D/ConnectivityService( 2419): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2419): net.tcp.usercfg.default not found in system default properties
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
E/ConnectivityService( 2419): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
,E/ConnectivityService( 2419): net.tcp.delack.default not found in system default properties
,E/ConnectivityService( 2419): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
,D/ConnectivityService( 2419): Attempting to switch to mobile
D/STATUSBAR-IconMerger( 2579): checkOverflow(336), More:false, Req:false Child:3
,D/ConnectivityService( 2419): Attempting to switch to BLUETOOTH_TETHER
,I/SELinux ( 7396): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7396):  
,V/RouteController( 1914): /system/bin/ip -6 route del default table 2 2>&1
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1914): RTNETLINK answers: No such process
,V/RouteController( 1914): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1914): RTNETLINK answers: No such file or directory
,D/CommandListener( 1914): Clearing all IP addresses on wlan0
,W/NetworkManagementService( 2419): route cmd failed: 
W/NetworkManagementService( 2419): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '35 route del src v6 2' failed with '400 35 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2419): '
W/NetworkManagementService( 2419): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2419): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2419): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2419): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2419): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2419): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2419): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2419): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2419): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2419): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2419): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2419): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2419): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1914): /system/bin/ip -4 route del default table 2 2>&1
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
I/SELinux ( 7396): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7396):  
I/SELinux ( 7396):  
,I/SELinux ( 7396): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7396): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7396): >>>>> Normal User
,E/dalvikvm( 7396): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7396): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
V/RouteController( 1914): RTNETLINK answers: No such process
V/RouteController( 1914): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 7396): in addTimaSignatureService
,V/RouteController( 1914): /system/bin/ip route flush cached 2>&1
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-121ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-120ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-15ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/TimaKeyStoreProvider( 7396): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7396): Added TimaKesytore provider
,D/NetUtils( 2419): android_net_utils_resetConnections in env=0x78451598 clazz=0x61d00001 iface=wlan0 mask=0x3
D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 10
D/ConnectivityService( 2419): resetConnections(wlan0, 3)
,V/NativeCrypto( 2853): Read error: ssl=0x7b9aef10: I/O error during system call, Connection timed out
,E/SPPClientService( 5577): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5577): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5577): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5577): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5577): [b] ResponseMap empty
,V/NativeCrypto( 2853): SSL shutdown failed: ssl=0x7b9aef10: I/O error during system call, Broken pipe
,D/dalvikvm( 7396): GC_CONCURRENT freed 2993K, 33% free 9573K/14092K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 7396): WAIT_FOR_CONCURRENT_GC blocked 23ms
,V/NetworkStats( 2419): updateIfacesLocked()
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit,
V/NetworkStats( 2419): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit,
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit,
D/ConnectivityService( 2419): handleInetConditionChange: no active default network - ignore
V/NetworkStats( 2419): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit,
V/NetworkStats( 2419): performPollLocked() took 34ms
,I/System.out( 7396): Inside WakeupProvider,
,I/System.out( 7396): Inside onCreate() of WakeupTriggerProvide,
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit,
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit,
,I/VlingoApplication( 7396): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS,
D/VlingoApplication( 7396): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7396): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility,
,D/dalvikvm( 2419): GC_CONCURRENT freed 4415K, 74% free 25559K/95720K, paused 9ms+16ms, total 202ms,
,D/NearbySettings( 4731): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
V/NearbySettings( 4731): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4731): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 4731): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4731): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4731): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4731): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2419): Killing 6211:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/DialogFlow( 7396): initQueue()
,D/NearbySettings( 4731): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4731): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4731): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4731): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4731): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4731): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4731): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2419): Tethering got CONNECTIVITY_ACTION
,I/ApplicationPolicy( 2419): updateDataUsageMap
,D/Tethering( 2419): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2419): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2419): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2579): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2579): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2579): updateDataNetType()
D/STATUSBAR-NetworkController( 2579): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6622): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6622): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6622): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6622): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6622): noConnectivity : true
,I/DBG_DM  ( 4765): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7425): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7425):  
,I/SELinux ( 7425): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7425):  
I/SELinux ( 7425):  
,I/SELinux ( 7425): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7425): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7425): >>>>> Normal User
,E/dalvikvm( 7425): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7425): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7425): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7425): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7425): Added TimaKesytore provider
,I/wpa_supplicant( 3965): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 3965): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3965): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,D/dalvikvm( 7425): GC_CONCURRENT freed 2997K, 33% free 9568K/14096K, paused 3ms+3ms, total 29ms
,D/dalvikvm( 7425): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
D/Tethering( 2419): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3965): Associated with C0.AA.48
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
D/Tethering( 2419): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3965): freq(2412) increment count 2
,I/wpa_supplicant( 3965): meet head of list.
,I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3965): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3965): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/WifiNative( 2419): callSECApiVoid - ID [50]
,D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/ActivityManager( 2419): Killing 6280:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/WifiP2pService( 2419): InactiveState{ what=143375 }
,D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,I/SELinux ( 7439): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7439):  
,I/SELinux ( 7439): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7439):  
I/SELinux ( 7439):  
,I/SELinux ( 7439): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7439): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7439): >>>>> Normal User
,E/dalvikvm( 7439): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7439): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7439): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7439): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7439): Added TimaKesytore provider
,D/dalvikvm( 7439): GC_CONCURRENT freed 3001K, 33% free 9566K/14092K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 7439): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/dhcpcd  ( 7451): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7451): bssid match
,I/ActivityManager( 2419): Killing 6333:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7462): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7462):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 15% free 9503K/11072K, paused 3ms+3ms, total 40ms
,I/SELinux ( 7462): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7462):  
I/SELinux ( 7462):  
,I/SELinux ( 7462): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7462): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7462): >>>>> Normal User
,E/dalvikvm( 7462): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7462): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 15% free 9503K/11072K, paused 3ms+4ms, total 31ms
,D/TimaKeyStoreProvider( 7462): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7462): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7462): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 15% free 9503K/11072K, paused 3ms+4ms, total 31ms
,D/dalvikvm( 7462): GC_CONCURRENT freed 2998K, 33% free 9573K/14096K, paused 3ms+1ms, total 22ms
,D/dalvikvm( 7462): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/KLMS-2.3.201 : ( 7462): KLMSValidator() : checkQATesting()
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection...
,I/KLMS-2.3.201 : ( 7462): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450443095073
,I/KLMS-2.3.201 : ( 7462): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2419): Killing 6346:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7492): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7492):  
,I/SELinux ( 7492): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7492):  
I/SELinux ( 7492):  
,I/SELinux ( 7492): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7492): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7492): >>>>> Normal User
,E/dalvikvm( 7492): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7492): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7492): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7492): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7492): Added TimaKesytore provider
,D/dalvikvm( 7492): GC_CONCURRENT freed 2997K, 33% free 9570K/14096K, paused 2ms+2ms, total 19ms
,D/dalvikvm( 7492): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/SO_AGENT( 7492): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7492): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,D/WifiP2pService( 2419): InactiveState{ what=143375 }
,I/SA      ( 5841): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5841): [BDLM] already registered in spp
,D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
I/SA      ( 5841): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
I/SA      ( 5841): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5841): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 5841): [OR] == isSIMCardReady false ==
I/SA      ( 5841): [SCU] == networkStateCheck == false
,I/SA      ( 5841): [OR] onReceive END
,I/ActivityManager( 2419): Killing 5626:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/WifiStateMachine( 2419): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2419): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2419): CaptivePortalCheckState enter
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): Phone number locator feature is dsiabled
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2419): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2419): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2419): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7504): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7504):  
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
D/ConnectivityService( 2419): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2419): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2419): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2419): handleConnectivityChange: setting default proxy info 
,I/SELinux ( 7504): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7504):  
I/SELinux ( 7504):  
,I/SELinux ( 7504): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7504): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7504): >>>>> Normal User
,E/dalvikvm( 7504): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
E/SELinux ( 7504): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,V/RouteController( 1914): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1914): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 7504): in addTimaSignatureService
D/TimaKeyStoreProvider( 7504): Cannot add TimaSignature Service, License check Failed
,V/RouteController( 1914): RTNETLINK answers: No such file or directory
,V/RouteController( 1914): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,D/ActivityThread( 7504): Added TimaKesytore provider
,V/RouteController( 1914): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1914): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1914): RTNETLINK answers: No such process
,V/RouteController( 1914): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1914): /system/bin/ip route flush cached 2>&1
,V/NetworkStats( 2419): updateIfacesLocked()
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,V/NetworkStats( 2419): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/dalvikvm( 7504): GC_CONCURRENT freed 2994K, 33% free 9571K/14092K, paused 4ms+2ms, total 49ms
,D/dalvikvm( 7504): WAIT_FOR_CONCURRENT_GC blocked 30ms
V/NetworkStats( 2419): performPollLocked() took 30ms
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,I/sCloudBackupApp( 7504): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7504): Other Intent
I/ActivityManager( 2419): Killing 6316:com.sec.phone/1001 (adj 15): empty #43
,I/SELinux ( 7532): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7532):  
,I/SELinux ( 7532): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7532):  
I/SELinux ( 7532):  
,I/SELinux ( 7532): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7532): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7532): >>>>> Normal User
,E/dalvikvm( 7532): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7532): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7532): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7532): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7532): Added TimaKesytore provider
,D/dalvikvm( 7532): GC_CONCURRENT freed 2998K, 33% free 9571K/14096K, paused 2ms+1ms, total 23ms
,D/dalvikvm( 7532): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/com.samsung.app( 7532): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7532): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7532): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7532): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7532): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7532): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5373): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7532): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5373): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7532): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5373): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7532): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7532): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2419): Killing 6383:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,D/Headlines( 5904): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5904): getCountryCode(): countryCode = PL
,D/Headlines( 5904): Breath.onCreate
,D/Headlines( 5904): Breath timer started. interval : 30000
,I/SELinux ( 7544): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7544):  
,D/Headlines( 5904): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0,
D/HeadlinesCardManager( 5904): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5904): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5904): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5904): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5904): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5904): requestUpdateNewsWelcomeCard !!! no welcome card,
,I/SELinux ( 7544): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7544):  
I/SELinux ( 7544):  
I/SELinux ( 7544): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7544): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7544): >>>>> Normal User
,E/dalvikvm( 7544): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ],
E/SELinux ( 7544): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/Tethering( 2419): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2419): MasterInitialState.processMessage what=3,
,D/CaptivePortalTracker( 2419): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler },
,D/STATUSBAR-NetworkController( 2579): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION,
D/STATUSBAR-NetworkController( 2579): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2579): updateDataNetType()
,D/STATUSBAR-NetworkController( 2579): NoService, mRoamingIconId = 0,
,I/DBG_DM  ( 4765): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected,
,D/TimaKeyStoreProvider( 7544): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7544): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7544): Added TimaKesytore provider,
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection - timeout,
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability,
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection...,
,D/dalvikvm( 7544): GC_CONCURRENT freed 3002K, 33% free 9572K/14100K, paused 2ms+2ms, total 32ms,
,D/dalvikvm( 7544): WAIT_FOR_CONCURRENT_GC blocked 29ms,
,V/WebViewChromium( 7544): Binding Chromium to the background looper Looper (main, tid 1) {4230a228},
,I/chromium( 7544): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserProcessMain( 7544): Initializing chromium process, renderers=0
,W/chromium( 7544): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation,
,D/libEGL  ( 7544): loaded /system/lib/egl/libEGL_mali.so,
,D/libEGL  ( 7544): loaded /system/lib/egl/libGLESv1_CM_mali.so,
,D/libEGL  ( 7544): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7544): Mali API Version : 401
,I/Mali    ( 7544): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,W/GAV2    ( 7544): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1910): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7544): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    ( 1910): Returning OperationFailed - no handler for errno 30
,I/NSApplication( 7544): Starting up...
,I/iu.Environment( 5972): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5174): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5174): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5174): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@423183e8
,I/SELinux ( 7582): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7582):  
,I/SELinux ( 7582): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7582):  
I/SELinux ( 7582):  
,I/SELinux ( 7582): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7582): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7582): >>>>> Normal User
,E/dalvikvm( 7582): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7582): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7582): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7582): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7582): Added TimaKesytore provider
,D/dalvikvm( 7582): GC_CONCURRENT freed 2988K, 33% free 9585K/14100K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7582): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,I/SELinux ( 7601): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7601):  
I/ActivityManager( 2419): Killing 6027:com.android.calendar/u0a144 (adj 15): empty #43
,W/ActivityManager( 2419): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 7601): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7601):  
I/SELinux ( 7601):  
,I/SELinux ( 7601): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7601): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7601): >>>>> Normal User
,E/dalvikvm( 7601): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,I/SELinux ( 7605): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7605):  
,E/SELinux ( 7601): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7601): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7601): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7601): Added TimaKesytore provider
,I/SELinux ( 7605): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7605):  
I/SELinux ( 7605):  
,I/SELinux ( 7605): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7605): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7605): >>>>> Normal User
,E/dalvikvm( 7605): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,I/ActivityManager( 2419): Killing 6198:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
E/SELinux ( 7605): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7605): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7605): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7605): Added TimaKesytore provider
,D/dalvikvm( 7601): GC_CONCURRENT freed 3009K, 33% free 9559K/14096K, paused 1ms+2ms, total 22ms
,D/dalvikvm( 7601): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/BadgeProvider( 7601): onCreate
,D/BadgeProvider( 7601): DatabaseHelper
,D/dalvikvm( 7605): GC_CONCURRENT freed 3006K, 33% free 9566K/14100K, paused 3ms+1ms, total 26ms
,D/dalvikvm( 7605): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/BadgeProvider( 7601): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7601): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7601): sendNotify, [notify] : null
D/BadgeProvider( 7601): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7601): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7601): update, [UpdateCount] : 1
D/Launcher.Model( 2783): reloadBadges entered.
D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection...
,D/hcjo    ( 5995): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 5995): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5995): exit::IDLE
,D/InitializeManagerStateMachine( 5995): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5995): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5995): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5995): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5995): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5995): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5995): entry::SUCCESS
,D/hcjo    ( 5995): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5995): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5995): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5995): exit::SUCCESS
,D/InitializeManagerStateMachine( 5995): entry::IDLE
,E/SPPClientService( 5577): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5577): [SystemStateMoniter] Current Time : 334013
,E/SPPClientService( 5577): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5577): [[SystemStateMonitorService]] No Active Internet,
,D/NearbySettings( 4731): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
V/NearbySettings( 4731): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4731): DMSUtil.isNetworkConnected - WIFI: CONNECTED,
I/NearbySettings( 4731): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4731): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4731): MountReceiver.onReceive - Keep current state,
,E/SPPClientService( 5577): [a] [ConnectionManager] Connection is already disconnected.,
,E/SPPClientService( 5577): [a] [ConnectionManager] Connection is already disconnected.,
,D/NearbySettings( 4731): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,I/NearbySettings( 4731): MountReceiver.onReceive - Keep current state,
,E/SPPClientService( 5577): [[PushClientService]] <<--- deInitPushClientService  END  --->>,
,E/SPPClientService( 5577): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19,
D/NearbySettings( 4731): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4731): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4731): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 4731): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4731): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4731): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger( 1920): id=20 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 2419): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2419
,D/NearbySettings( 4731): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4731): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5577): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,I/PCWCLIENTTRACE_PushUtil( 6622): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6622): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6622): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6622): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5577): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5577): [g] getNetMCC return empty string
,I/KLMS-2.3.201 : ( 7462): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7462): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450443097727,
,I/KLMS-2.3.201 : ( 7462): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false,
,D/SO_AGENT( 7492): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3465): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3465): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3465): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3465): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7492): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 3594): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7636): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7636):  
,I/SELinux ( 7636): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7636):  
I/SELinux ( 7636):  
,I/SELinux ( 7636): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7636): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7636): >>>>> Normal User
,E/dalvikvm( 7636): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7636): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 7640): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7640):  
,D/TimaKeyStoreProvider( 7636): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7636): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7636): Added TimaKesytore provider,
,I/SELinux ( 7640): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7640):  
I/SELinux ( 7640):  
I/SELinux ( 7640): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7640): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7640): >>>>> Normal User
E/dalvikvm( 7640): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7640): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7640): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7640): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7640): Added TimaKesytore provider
,D/dalvikvm( 7636): GC_CONCURRENT freed 2993K, 33% free 9574K/14096K, paused 2ms+1ms, total 34ms
,D/dalvikvm( 7636): WAIT_FOR_CONCURRENT_GC blocked 33ms
,I/SA      ( 5841): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5841): [BDLM] already registered in spp
,I/SA      ( 5841): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5841): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5841): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5841): [OR] == isSIMCardReady false ==
,I/SA      ( 5841): [SCU] == networkStateCheck == true
,I/SA      ( 5841): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5841): isChinaCountryCode : false
,I/SA      ( 5841): [OR] == networkStateCheck true ==
,I/SA      ( 5841): [OR] GetMyCountryZoneTask
,I/SA      ( 5841): [OR] onReceive END
,D/dalvikvm( 7640): GC_CONCURRENT freed 3002K, 33% free 9567K/14096K, paused 7ms+1ms, total 52ms
,D/dalvikvm( 7640): WAIT_FOR_CONCURRENT_GC blocked 44ms
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): Phone number locator feature is dsiabled
,I/SA      ( 5841): [SRS] prepareGetMyCountryZone
,I/SCloudBackupReceiver( 7504): Other Intent
,I/SA      ( 5841): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5841): [SSP] query invoked
,V/KVNProvider( 7640): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7640): getFindoCursor query string : 
,V/KVNProvider( 7640): getTagSearchCursor() tagSearchCursor count : 0
I/SA      ( 5841): [TPMU] GetMccFromDB : null
I/SA      ( 5841): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5841): [TPM] isNoProxy(default) : true
,I/SA      ( 5841): [RC New] Execute method=[GET] start
,D/com.samsung.app( 7532): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/System.out( 7439): Thread-636(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7439): Thread-636(ApacheHTTPLog):isShipBuild true
,I/System.out( 7439): Thread-636(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/com.samsung.app( 7532): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2419): Killing 6366:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/Headlines( 5904): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5904): getCountryCode(): countryCode = PL
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
D/Headlines( 5904): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5904): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5904): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5904): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5904): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5904): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5904): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 5972): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5174): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5174): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5174): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@423183e8
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/hcjo    ( 5995): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 5995): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5995): exit::IDLE
,D/InitializeManagerStateMachine( 5995): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5995): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5995): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5995): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5995): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5995): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5995): entry::SUCCESS
,D/hcjo    ( 5995): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5995): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5995): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5995): exit::SUCCESS
,D/InitializeManagerStateMachine( 5995): entry::IDLE
,E/SPPClientService( 5577): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5577): [SystemStateMoniter] Current Time : 335101
,E/SPPClientService( 5577): [SystemStateMoniter] No Connect : false
,I/System.out( 7439): AsyncTask #1 calls detatch()
,W/System.err( 7439): com.sec.android.fota.osp.http.RestClientException
,W/System.err( 7439): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7439): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7439): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7439): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 7439): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7439): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7439): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7439): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7439): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 7439): Caused by: java.lang.NullPointerException
,W/System.err( 7439): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7439): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7439): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7439): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7439): 	... 8 more
D/PackageManager( 2419): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/ActivityManager( 2419): Killing 6233:com.google.android.music:main/u0a125 (adj 15): empty #43
,D/dalvikvm( 5577): GC_CONCURRENT freed 2023K, 26% free 10441K/14076K, paused 6ms+5ms, total 62ms
,D/dalvikvm( 5577): WAIT_FOR_CONCURRENT_GC blocked 32ms
,E/WifiStateMachine( 2419): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SA      ( 5841): [RC New] [v2liruge] api execute + 712
,I/SA      ( 5841): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5841): AsyncTask #2 calls detatch()
,I/SA      ( 5841): [TPMU] getNetworkMcc : 
,I/SA      ( 5841): [SCU] saveMccToPreferece Start
,I/SA      ( 5841): [SCU] RegionMCC : 260
,I/SA      ( 5841): [SSP] query invoked
,I/SA      ( 5841): [TPMU] GetMccFromDB : null
,I/SA      ( 5841): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5841): [SCU] saveMccToPreferece End
,I/SA      ( 5841): [RC New] executeRequest [v2liruge] end. 755
I/SA      ( 5841): [RC New] Execute end
I/SA      ( 5841): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5841): [OR] GetMyCountryZoneTask Success
,I/jxcore-log( 7349): Got Device Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 7349): 
,I/jxcore-log( 7349): my name is : samsung-SM-G800F_PT7064
I/jxcore-log( 7349): 
,I/jxcore-log( 7349): attempting to connect to test coordinator
I/jxcore-log( 7349): 
,I/jxcore-log( 7349): check test folder
I/jxcore-log( 7349): 
,I/jxcore-log( 7349): found test : ./testFindPeers.js
I/jxcore-log( 7349): 
,I/jxcore-log( 7349): found test : ./testReConnect.js
I/jxcore-log( 7349): 
,I/jxcore-log( 7349): found test : ./testSendData.js
I/jxcore-log( 7349): 
,I/jxcore-log( 7349): Test app app.js loaded
I/jxcore-log( 7349): 
,I/Choreographer( 7349): Skipped 384 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7349): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/WifiP2pStateTracker( 2419): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2419): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2419):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2419): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2419): updateSourceRoutes : no source routing conditions
,I/jxcore-log( 7349): DBG, CoordinatorConnector connect called
I/jxcore-log( 7349): 
,I/jxcore-log( 7349): Coordinator is now connected to the server!
I/jxcore-log( 7349): 
,I/chromium( 7349): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SPPClientService( 5577): [b] __InitReply__
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (10/11)
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (-2/11)
I/ActivityManager( 2419): Killing 6562:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/PowerManagerService( 2419): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2419) eventTime = 337701
,D/PowerManagerService( 2419): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2419 (0x0)
,D/PowerManagerService( 2419): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2419, ws=WorkSource{1000}) (elapsedTime=3467)
,D/dalvikvm( 2419): GC_EXPLICIT freed 2116K, 74% free 25552K/95532K, paused 18ms+22ms, total 259ms
,I/GAV2    ( 7544): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6622): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil( 6622): [hasSamungAccount] - No Samsung Account,
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6622): failed to loading secure library,
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6622): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6622): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6622): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6622): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6622): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6622): [ensureRegistration] - No Samsung account,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 294, prevStep = 4, currStep = 4,
,I/dalvikvm( 7349): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported,
W/dalvikvm( 7349): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7349): VFY: replacing opcode 0x6e at 0x0002,
D/AndroidRuntime( 7349): Shutting down VM
,W/dalvikvm( 7349): threadid=1: thread exiting with uncaught exception (group=0x41846c08),
,E/AndroidRuntime( 7349): FATAL EXCEPTION: main,
E/AndroidRuntime( 7349): Process: com.test.thalitest, PID: 7349
E/AndroidRuntime( 7349): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 7349): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 7349): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 7349): 	,at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 7349): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 7349): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 7349): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 7349): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228),
E/AndroidRuntime( 7349): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 7349): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 7349): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 7349): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7349): ,	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7349): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7349): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7349): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7349): ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7349): ,	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7349): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 2419):   Force finishing activity com.test.thalitest/.MainActivity,
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1,
,I/ActivityManager( 2419): Killing 6484:com.google.android.partnersetup/u0a14 (adj 15): empty #43,
,D/CrashAnrDetector( 2419): processName: com.test.thalitest,
,D/CrashAnrDetector( 2419): broadcastEvent : com.test.thalitest data_app_crash,
,I/Process ( 7349): Sending signal. PID: 7349 SIG: 9,
W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@4,
,W/ActivityManager( 2419): mDVFSHelper.acquire()
,I/ActivityManager( 2419): Process com.test.thalitest (pid 7349) (adj 9) has died.
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (-2/10),
,I/WindowState( 2419): WIN DEATH: Window{430ba7e0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1920): id=19 Removed NainActivit (-2/10),
,I/DBG_DM  ( 4765): [3.19.140541][Line:408][onResume] ,
,I/DBG_DM  ( 4765): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
,I/DBG_DM  ( 4765): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0,
,I/DBG_DM  ( 4765): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0,
,I/DBG_DM  ( 4765): [3.19.140541][Line:418][onResume] Postpone Count : 26,
,I/DBG_DM  ( 4765): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4765): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7,
,I/DBG_DM  ( 4765): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 ,
,D/STATUSBAR-StatusBarManagerService( 2419): sendNotification(2) - 4,
,I/DBG_DM  ( 4765): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26,
,I/DBG_DM  ( 4765): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0,
,I/DBG_DM  ( 4765): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0,
I/DBG_DM  ( 4765): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4765): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4765): [3.19.140541][Line:757][xdmGetDeviceEncryptState] ,
,I/DBG_DM  ( 4765): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
D/Activity( 4765): setTransGradationMode to true
,D/StatusBarManagerService( 2419): semi p:4765,o:t,
D/PhoneStatusBar( 2579): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
I/DBG_DM  ( 4765): [3.19.140541][Line:400][onPause] 
,I/SurfaceFlinger( 1920): id=21 createSurf (720x1280),2 flag=404, YUIInstallC,
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams,
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 2419): Got RemoteException sending setActive(false) notification to pid 7349 uid 10563
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2419): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@8
,D/CaptivePortalTracker( 2419): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 2419): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2419): Checking http://216.58.209.46/generate_204,
,D/CaptivePortalTracker( 2419): Don't send network conditions - lacking user consent.,
D/CaptivePortalTracker( 2419): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 2419): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2419): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
D/ConnectivityService( 2419): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/PreloadUpdateManagerStateMachine( 5995): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 5995): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5995): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 5995): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5995): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 5995): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5995): entry::IDLE,
,I/PowerManagerService( 2419): [PWL] Off : 275s ago,
,D/PreloadUpdateManagerStateMachine( 5995): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 5995): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5995): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 5995): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5995): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 5995): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5995): entry::IDLE,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4007): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{46a18230 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,E/Watchdog( 2419): !@Sync 11,
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{46964fc0 u0 com.sec.spp.push/.PushClientService},
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 295, prevStep = 4, currStep = 4,
,V/AlarmManager( 2419): waitForAlarm result :4,
,I/SELinux ( 7777): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7777):  
V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 7777): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7777):  
I/SELinux ( 7777):  
I/SELinux ( 7777): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7777): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7777): >>>>> Normal User
,E/dalvikvm( 7777): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 7777): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 7777): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7777): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7777): Added TimaKesytore provider,
,D/dalvikvm( 7777): GC_CONCURRENT freed 3000K, 33% free 9566K/14092K, paused 3ms+2ms, total 28ms,
,D/dalvikvm( 7777): WAIT_FOR_CONCURRENT_GC blocked 24ms,
,D/Headlines( 5904): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5904): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5904): Breath 20060 latestRequest time : 1450443098221 current time : 1450443118281
,V/AlarmManager( 2419): waitForAlarm result :8,
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): stay LED for fully charged
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4,
,V/AlarmManager( 2419): waitForAlarm result :8,
,D/Headlines( 5904): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5904): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5904): Breath 27744 latestRequest time : 1450443098221 current time : 1450443125965,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2419): !@Sync 12
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5904): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5904): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5904): Breath 57747 latestRequest time : 1450443098221 current time : 1450443155968
,I/PowerManagerService( 2419): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2419): !@Sync 13
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4380, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5904): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5904): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5904): Breath 87744 latestRequest time : 1450443098221 current time : 1450443185965
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 14
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5904): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5904): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5904): Breath 117746 latestRequest time : 1450443098221 current time : 1450443215967
,I/PowerManagerService( 2419): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2419): !@Sync 15
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5904): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5904): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5904): Breath 147747 latestRequest time : 1450443098221 current time : 1450443245968,
,D/Headlines( 5904): stop 
,D/Headlines( 5904): Breath.onDestroy : 
I/ActivityManager( 2419): Killing 6593:com.samsung.groupcast/u0a15 (adj 15): empty #43
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1,
,D/GKI_LINUX( 4007): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/        ( 4007): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/dalvikvm( 6464): GC_CONCURRENT freed 2504K, 29% free 10112K/14136K, paused 11ms+5ms, total 85ms
,I/SELinux ( 8236): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8236):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 15% free 9503K/11072K, paused 4ms+5ms, total 51ms
I/SELinux ( 8236): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8236):  
I/SELinux ( 8236):  
,I/SELinux ( 8236): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 8236): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8236): >>>>> Normal User
,E/dalvikvm( 8236): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 8236): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 8236): in addTimaSignatureService
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 15% free 9503K/11072K, paused 3ms+8ms, total 48ms
,D/TimaKeyStoreProvider( 8236): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8236): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 15% free 9503K/11072K, paused 4ms+4ms, total 35ms
,D/dalvikvm( 8236): GC_CONCURRENT freed 2997K, 33% free 9570K/14096K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 8236): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/UserAnalysis.PlaceProvider( 8236): Create SecureDbHelper
,D/UserAnalysis.CarAnalyzer( 8236): Create SecureDbHelper
,I/ActivityManager( 2419): Killing 6607:com.android.musicfx/u0a24 (adj 15): empty #43
,E/bt-btm  ( 4007): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4007): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4731): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/GKI_LINUX( 4007): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,E/Watchdog( 2419): !@Sync 16
,D/btif_config_util( 4007): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 10
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/GKI_LINUX( 4007): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/        ( 4007): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: G4-1
,D/UserAnalysis.CarAnalyzer( 8236): Create SecureDbHelper
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/bt-btm  ( 4007): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4007): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4731): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,D/GKI_LINUX( 4007): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: G4-1
,D/dalvikvm( 2579): GC_CONCURRENT freed 15738K, 34% free 33858K/51120K, paused 37ms+19ms, total 144ms
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/btif_config_util( 4007): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/GKI_LINUX( 4007): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/        ( 4007): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_CONNECTED
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.NAME_CHANGED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: G4-1
,D/UserAnalysis.CarAnalyzer( 8236): Create SecureDbHelper
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,E/bt-btm  ( 4007): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4007): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4731): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/GKI_LINUX( 4007): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/btif_config_util( 4007): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2419): [PWL] Off : 455s ago
,D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/GKI_LINUX( 4007): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/        ( 4007): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: G4-1
,D/UserAnalysis.CarAnalyzer( 8236): Create SecureDbHelper
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,E/Watchdog( 2419): !@Sync 17
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/bt-btm  ( 4007): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4007): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,E/BluetoothEventManager( 4731): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: G4-1
,D/GKI_LINUX( 4007): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/btif_config_util( 4007): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/GKI_LINUX( 4007): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/        ( 4007): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_CONNECTED
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.NAME_CHANGED
D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: G4-1
,D/UserAnalysis.CarAnalyzer( 8236): Create SecureDbHelper
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 294, prevStep = 4, currStep = 4
,E/bt-btm  ( 4007): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4007): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,E/BluetoothEventManager( 4731): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: G4-1
,D/GKI_LINUX( 4007): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/btif_config_util( 4007): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 18
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/GKI_LINUX( 4007): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/        ( 4007): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 4007): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.NAME_CHANGED
,E/bt-btm  ( 4007): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4007): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4731): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: Nexus 5
,D/GKI_LINUX( 4007): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/btif_config_util( 4007): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/GKI_LINUX( 4007): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/        ( 4007): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: Nexus 5
,D/UserAnalysis.CarAnalyzer( 8236): Create SecureDbHelper
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/bt-btm  ( 4007): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4007): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,E/BluetoothEventManager( 4731): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: Nexus 5
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/GKI_LINUX( 4007): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 8783
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 8785
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 8786
,D/btif_config_util( 4007): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/Watchdog( 2419): !@Sync 19
,D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/GKI_LINUX( 4007): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/        ( 4007): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: Nexus 5
,D/UserAnalysis.CarAnalyzer( 8236): Create SecureDbHelper
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/bt-btm  ( 4007): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4007): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4731): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: Nexus 5
,D/GKI_LINUX( 4007): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,I/PowerManagerService( 2419): [PWL] Off : 525s ago
,D/btif_config_util( 4007): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/GKI_LINUX( 4007): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/        ( 4007): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: Nexus 5
,D/UserAnalysis.CarAnalyzer( 8236): Create SecureDbHelper
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 8928
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 8933
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 8938
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 8942
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 8943
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 8944
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 8946
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 8949
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 8951
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 8952
,D/dalvikvm( 2419): GC_CONCURRENT freed 4325K, 74% free 25157K/95532K, paused 15ms+20ms, total 231ms
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/bt-btm  ( 4007): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,E/BluetoothEventManager( 4731): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: Nexus 5
,D/GKI_LINUX( 4007): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/btif_config_util( 4007): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/GKI_LINUX( 4007): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/        ( 4007): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: Nexus 5
,D/UserAnalysis.CarAnalyzer( 8236): Create SecureDbHelper
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/btif_config_util( 4007): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4007): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 4007): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4731): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: Nexus 5
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/GKI_LINUX( 4007): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 20
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/GKI_LINUX( 4007): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/        ( 4007): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 4007): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.NAME_CHANGED
,E/Watchdog( 2419): !@Sync 21
,E/bt-btm  ( 4007): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,E/BluetoothEventManager( 4731): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: Note3-1
,D/GKI_LINUX( 4007): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/btif_config_util( 4007): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 600s ago
,V/AlarmManager( 2419): waitForAlarm result :8
,I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2419): LightSensor setDelay = 200000000
,D/LightsService( 2419): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/Sensors ( 2419): Light sensor flush: not enabled 0
D/Sensors ( 2419): LightSensor enable = 1
D/Sensors ( 2419): LightSensor enableSensor = 1
D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
,D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 3
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/GAV2    ( 5669): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5669): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2419): !@Sync 22
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 23
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2419): <AppSync3 Whitelist>
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 24
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 0
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 0:0
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 0
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 0:0
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/GKI_LINUX( 4007): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/        ( 4007): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: S5-1
,D/UserAnalysis.CarAnalyzer( 8236): Create SecureDbHelper
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,I/PowerManagerService( 2419): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/btif_config_util( 4007): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4007): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4007): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4731): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: S5-1
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/GKI_LINUX( 4007): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/GKI_LINUX( 4007): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/        ( 4007): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: S5-1
,D/UserAnalysis.CarAnalyzer( 8236): Create SecureDbHelper
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/bt-btm  ( 4007): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4007): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4731): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: S5-1
,D/GKI_LINUX( 4007): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 9617
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 9619
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 9620
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 9622
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 9624
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 9625
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 9627
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 9629
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 9630
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 9631
,D/btif_config_util( 4007): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/Watchdog( 2419): !@Sync 25
,D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/GKI_LINUX( 4007): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/        ( 4007): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: S5-1
,D/UserAnalysis.CarAnalyzer( 8236): Create SecureDbHelper
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/bt-btm  ( 4007): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4007): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,E/BluetoothEventManager( 4731): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: S5-1
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/GKI_LINUX( 4007): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/btif_config_util( 4007): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/dalvikvm( 4082): GC_CONCURRENT freed 2891K, 32% free 9726K/14144K, paused 20ms+2ms, total 69ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/GKI_LINUX( 4007): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0,
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/        ( 4007): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: S5-1
,D/UserAnalysis.CarAnalyzer( 8236): Create SecureDbHelper
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,E/bt-btm  ( 4007): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4007): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4731): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: S5-1
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/GKI_LINUX( 4007): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/btif_config_util( 4007): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 26
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,E/SPPClientService( 5577): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 27
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 765s ago
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 28
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 29
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 30
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 855s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 31
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 32
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/dalvikvm( 2419): GC_CONCURRENT freed 4027K, 74% free 24983K/95532K, paused 25ms+19ms, total 253ms
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 33
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2419): [PWL] Off : 950s ago
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 34
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 35
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 36
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SPPClientService( 5577): [b] __PingReply__
,I/PowerManagerService( 2419): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 37
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 38
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 39
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 40
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/GKI_LINUX( 4007): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/        ( 4007): remote version info [f8:95:c7:87:3c:51]: 7, f, 610c
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: G4-1
,D/UserAnalysis.CarAnalyzer( 8236): Create SecureDbHelper
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,E/bt-btm  ( 4007): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4007): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4731): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/GKI_LINUX( 4007): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/btif_config_util( 4007): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/Watchdog( 2419): !@Sync 41
,D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/GKI_LINUX( 4007): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/        ( 4007): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: G4-1
,D/UserAnalysis.CarAnalyzer( 8236): Create SecureDbHelper
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/bt-btm  ( 4007): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4007): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4731): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: G4-1
,D/GKI_LINUX( 4007): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/btif_config_util( 4007): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/GKI_LINUX( 4007): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/        ( 4007): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: G4-1
,D/UserAnalysis.CarAnalyzer( 8236): Create SecureDbHelper
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/bt-btm  ( 4007): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4007): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,E/BluetoothEventManager( 4731): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: G4-1
,D/GKI_LINUX( 4007): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/btif_config_util( 4007): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,V/AlarmManager( 2419): waitForAlarm result :8
,D/LightsService( 2419): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
D/Sensors ( 2419): LightSensor setDelay = 200000000
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/Sensors ( 2419): Light sensor flush: not enabled 0
D/Sensors ( 2419): LightSensor enable = 1
D/Sensors ( 2419): LightSensor enableSensor = 1
D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
,D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 3
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/GKI_LINUX( 4007): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/        ( 4007): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: G4-1
,D/UserAnalysis.CarAnalyzer( 8236): Create SecureDbHelper
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/bt-btm  ( 4007): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4007): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 4731): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,I/BluetoothClassifier( 6464): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/GKI_LINUX( 4007): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,E/Watchdog( 2419): !@Sync 42
,D/btif_config_util( 4007): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/GKI_LINUX( 4007): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 4007): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/        ( 4007): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: G4-1
,D/UserAnalysis.CarAnalyzer( 8236): Create SecureDbHelper
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,E/bt-btm  ( 4007): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4007): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4007): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4007): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4007): db_query_execute: result 1
,D/KeyguardViewMediator( 2579): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 4731): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2579): isGear1: device is not B1!
,E/BluetoothEventManager( 4731): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6464): Bluetooth Device Name: G4-1
,D/GKI_LINUX( 4007): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/BluetoothAdapterService(1110473088)( 4007): Get Bonded Devices being called
,D/btif_config_util( 4007): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): stay LED for fully charged
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 43
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2419): <AppSync3 Whitelist>
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1265s ago
,E/Watchdog( 2419): !@Sync 44
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 45
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2419): GC_CONCURRENT freed 3808K, 74% free 24997K/95300K, paused 16ms+19ms, total 230ms
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 46
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 47
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 48
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 49
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4082): GC_CONCURRENT freed 2050K, 32% free 9723K/14144K, paused 4ms+3ms, total 39ms
,D/dalvikvm( 4082): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 50
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 51
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 52
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 53
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 54
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 55
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1625s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 56
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5577): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,I/EventLogService( 3160): Aggregate from 1450442495994 (log), 1450442495994 (data)
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 57
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 58
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 59
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/dalvikvm( 2419): GC_CONCURRENT freed 3784K, 74% free 24995K/95300K, paused 20ms+17ms, total 227ms
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 60
,I/PowerManagerService( 2419): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 61
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2419): Prepared write state in 45ms
,I/ProcessStatsService( 2419): Prepared write state in 54ms
,I/ProcessStatsService( 2419): Pruning old procstats: /data/system/procstats/state-2015-12-17-15-43-01.bin
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,V/NetworkStats( 2419): performPollLocked(flags=0x3)
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,V/NetworkStats( 2419): performPollLocked() took 45ms
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,I/SELinux (12558): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12558):  
,I/SELinux (12558): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12558):  
I/SELinux (12558):  
,I/SELinux (12558): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (12558): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(12558): >>>>> Normal User
,E/dalvikvm(12558): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (12558): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(12558): in addTimaSignatureService
,D/TimaKeyStoreProvider(12558): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(12558): Added TimaKesytore provider
,D/dalvikvm(12558): GC_CONCURRENT freed 2997K, 33% free 9570K/14096K, paused 3ms+2ms, total 27ms
,D/dalvikvm(12558): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/@ WidgetProvider(12558): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(12558): onUpdate called for widgetId : 0
,D/@ WidgetProvider(12558): Widget random data : 10
,D/@ WidgetProvider(12558): onUpdate called for widgetId : 5
,D/@ WidgetProvider(12558): Widget random data : 10
,E/dalvikvm(12558): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
,W/dalvikvm(12558): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12558): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12558): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
,I/ActivityManager( 2419): Killing 6635:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
W/dalvikvm(12558): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(12558): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12558): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12558): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(12558): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12558): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(12558): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(12558): VFY: replacing opcode 0x22 at 0x0038
,D/dalvikvm(12558): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
,D/dalvikvm(12558): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(12558): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(12558): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
,D/LightsService( 2419): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2419): LightSensor setDelay = 200000000
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/Sensors ( 2419): Light sensor flush: not enabled 0
D/Sensors ( 2419): LightSensor enable = 1
D/Sensors ( 2419): LightSensor enableSensor = 1
D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/GLSActivity( 2853): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2853): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(12558): Thread-675(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(12558): Thread-675(ApacheHTTPLog):isShipBuild true
,I/System.out(12558): Thread-675(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 3
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/System.out(12558): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(12558): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(12558): Max ALLOWED memory (MB): 128
V/ImageManager(12558): Max SHOULD USE memory (MB): 128
,V/ImageManager(12558): Max Image Cache memory (MB): 32
,D/skia    (12558): getTotalSize : Do not get file length
,D/@ WidgetProvider(12558): Building widget : 5
,D/dalvikvm( 2783): GC_FOR_ALLOC freed 8512K, 36% free 18494K/28532K, paused 63ms, total 63ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 62
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 63
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2419): <AppSync3 Whitelist>
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 64
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 65
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,I/ActivityManager( 2419): Killing 6478:com.sec.knox.bridge/1000 (adj 15): empty for 1823s
,I/ActivityManager( 2419): Killing 4897:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1823s
,I/ActivityManager( 2419): Killing 6440:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1833s
,I/ActivityManager( 2419): Killing 6781:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1834s
,I/ActivityManager( 2419): Killing 6767:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1834s
,I/ActivityManager( 2419): Killing 6755:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1834s
,I/ActivityManager( 2419): Killing 6743:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1835s
,I/ActivityManager( 2419): Killing 6730:com.samsung.helphub/1000 (adj 15): empty for 1835s
,I/ActivityManager( 2419): Killing 6717:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1835s
I/ActivityManager( 2419): Killing 6704:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1835s
,I/ActivityManager( 2419): Killing 6691:com.sec.android.service.cm/u0a82 (adj 15): empty for 1835s
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2419): Killing 6396:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1835s
,I/ActivityManager( 2419): Killing 5735:com.android.mms/u0a49 (adj 15): empty for 1835s
,I/ActivityManager( 2419): Killing 6665:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1835s
,I/ActivityManager( 2419): Killing 6041:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1836s
,D/CountryDetector( 2419): No listener is left
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 66
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 67
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 68
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 69
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2419): [PWL] Off : 2030s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 70
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 71
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,I/ActivityManager( 2419): Killing 5841:com.osp.app.signin/u0a44 (adj 15): empty for 1822s
,I/ActivityManager( 2419): Killing 7640:com.sec.android.app.voicenote/1000 (adj 15): empty for 1822s
,I/ActivityManager( 2419): Killing 7636:com.sec.android.app.videoplayer/u0a53 (adj 15): empty for 1822s
,I/ActivityManager( 2419): Killing 6649:com.policydm/1000 (adj 15): empty for 1822s
,I/ActivityManager( 2419): Killing 7492:com.sec.android.soagent/u0a38 (adj 15): empty for 1822s
I/ActivityManager( 2419): Killing 7462:com.samsung.klmsagent/u0a18 (adj 15): empty for 1822s
,I/ActivityManager( 2419): Killing 7439:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1822s
,I/ActivityManager( 2419): Killing 5783:com.sec.android.diagmonagent/1000 (adj 15): empty for 1822s
,I/ActivityManager( 2419): Killing 7425:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1822s
I/ActivityManager( 2419): Killing 6622:com.sec.pcw.device/1000 (adj 15): empty for 1822s
,I/ActivityManager( 2419): Killing 4731:com.android.settings/1000 (adj 15): empty for 1822s
,I/ActivityManager( 2419): Killing 7601:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1822s
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms)
```
